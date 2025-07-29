---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/selectiondagbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SelectionDAGBuilder` Class

<p><a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> - This is the common target-independent lowering implementation that is parameterized by a <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> object. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SelectionDAGBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">CodeGen/SelectionDAG/SelectionDAGBuilder.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; DanglingDebugInfo &gt; <a href="#af281db65ead4c8bafbc63a6c7589086c">DanglingDebugInfoVector</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper type for DanglingDebugInfoMap. <a href="#af281db65ead4c8bafbc63a6c7589086c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FuncArgumentDbgValueKind { <a href="#a4f8d012b1e12df0ae8fb9888b5d37c66">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An enum that states to emit func argument dbg value the kind of intrinsic it originally had. <a href="#a4f8d012b1e12df0ae8fb9888b5d37c66">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89f8344fd5ae844b5beec8c4b9924f95">SelectionDAGBuilder</a> (SelectionDAG &amp;dag, FunctionLoweringInfo &amp;funcinfo, SwiftErrorValueTracking &amp;swifterror, CodeGenOptLevel ol)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadd87a22e72622eccf46ce5525d1976c">init</a> (GCFunctionInfo *gfi, BatchAAResults *BatchAA, AssumptionCache *AC, const TargetLibraryInfo *li)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c224fcb5175ab1e842dd2a1371eb3d8">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear out the current <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> and the associated state and prepare this <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> object to be used for a new block. <a href="#a2c224fcb5175ab1e842dd2a1371eb3d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b90604db120716e786d9d33babc3edd">clearDanglingDebugInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the dangling debug information map. <a href="#a1b90604db120716e786d9d33babc3edd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab41a8476a0c74bcf1a2bf665eeececd8">getMemoryRoot</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the current virtual root of the Selection DAG, flushing any PendingLoad items. <a href="#ab41a8476a0c74bcf1a2bf665eeececd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3e946c1fc678a70e849244389bd929a">getRoot</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to getMemoryRoot, but also flushes PendingConstrainedFP(Strict) items. <a href="#aa3e946c1fc678a70e849244389bd929a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef34360e8bb4bdecf3fd6345ff504f81">getControlRoot</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to getRoot, but instead of flushing all the PendingLoad items, flush all the PendingExports (and PendingConstrainedFPStrict) items. <a href="#aef34360e8bb4bdecf3fd6345ff504f81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb661ad9d4e5fd0d8806106e9b4d7256">getCurSDLoc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf62c0983c6240485d24b0fc329e1918">getCurDebugLoc</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5184df56e270750a839acad50a1b8501">CopyValueToVirtualRegister</a> (const Value *V, unsigned Reg, ISD::NodeType ExtendType=ISD::ANY_EXTEND)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbbfefd79a5b3d1b4ea8d8383fd01af5">visit</a> (const Instruction &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a196df57d98a1307c0ced654a8e1d202b">visitDbgInfo</a> (const Instruction &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa8e93a6e743cba008f0aa78ab4c653c">visit</a> (unsigned Opcode, const User &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0b87e85b015d15077a7d9432c500df3">getCopyFromRegs</a> (const Value *V, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If there was virtual register allocated for the value V emit CopyFromReg of the specified type Ty. <a href="#ac0b87e85b015d15077a7d9432c500df3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13b6c3ad0bdee051eda42dc7c8a1f12b">addDanglingDebugInfo</a> (SmallVectorImpl&lt; Value * &gt; &amp;Values, DILocalVariable *Var, DIExpression *Expr, bool IsVariadic, DebugLoc DL, unsigned Order)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a dbg_value which relies on a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> which we have not yet seen. <a href="#a13b6c3ad0bdee051eda42dc7c8a1f12b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac08d1b312ae9756038394d6b9568f383">dropDanglingDebugInfo</a> (const DILocalVariable *Variable, const DIExpression *Expr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we have dangling debug info that describes <span class="doxyComputerOutput">Variable</span>, or an overlapping part of variable considering the <span class="doxyComputerOutput">Expr</span>, then this method will drop that debug info as it isn't valid any longer. <a href="#ac08d1b312ae9756038394d6b9568f383">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab898c0fc6a2159b032a398271add3927">resolveDanglingDebugInfo</a> (const Value *V, SDValue Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we saw an earlier dbg_value referring to V, generate the debug data structures now that we've seen its definition. <a href="#ab898c0fc6a2159b032a398271add3927">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cf671ed90e3e80717aaa6318b24794c">salvageUnresolvedDbgValue</a> (const Value *V, DanglingDebugInfo &amp;DDI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the given dangling debuginfo record, perform last-ditch efforts to resolve the debuginfo to something that is represented in this DAG. <a href="#a8cf671ed90e3e80717aaa6318b24794c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9748fb2e4d41aaa8ac80d00b2becc52">handleDebugValue</a> (ArrayRef&lt; const Value * &gt; Values, DILocalVariable *Var, DIExpression *Expr, DebugLoc DbgLoc, unsigned Order, bool IsVariadic)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For a given list of Values, attempt to create and record a <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a> in the <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a>. <a href="#ae9748fb2e4d41aaa8ac80d00b2becc52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac42eef26cc4185a8932bc59a94dc5d16">handleKillDebugValue</a> (DILocalVariable *Var, DIExpression *Expr, DebugLoc DbgLoc, unsigned Order)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a record for a kill location debug intrinsic. <a href="#ac42eef26cc4185a8932bc59a94dc5d16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6571e1b07bfb1d4c5b1e832fdac355a1">handleDebugDeclare</a> (Value *Address, DILocalVariable *Variable, DIExpression *Expression, DebugLoc DL)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0535176e89ed7e0647a533aa033bb34">resolveOrClearDbgInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Evict any dangling debug information, attempting to salvage it first. <a href="#ab0535176e89ed7e0647a533aa033bb34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a025adb087cac36e2cd504a33e8cb749d">getValue</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getValue - Return an <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> for the given <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#a025adb087cac36e2cd504a33e8cb749d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ad02593716678add54090c344959750">getNonRegisterValue</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getNonRegisterValue - Return an <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> for the given <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, but don't look in FuncInfo.ValueMap for a virtual register. <a href="#a4ad02593716678add54090c344959750">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe3b2bbac4396d088da5c91f77754843">getValueImpl</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getValueImpl - Helper function for getValue and getNonRegisterValue. <a href="#afe3b2bbac4396d088da5c91f77754843">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8368fe85feec440623e9558e100f357">setValue</a> (const Value *V, SDValue NewN)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b0040c5b706355fa56842358cf0cbe7">setUnusedArgValue</a> (const Value *V, SDValue NewN)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a732bd4cf41862afa6092c1648c02e256">shouldKeepJumpConditionsTogether</a> (const FunctionLoweringInfo &amp;FuncInfo, const BranchInst &amp;I, Instruction::BinaryOps Opc, const Value *Lhs, const Value *Rhs, TargetLoweringBase::CondMergingParams Params) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae17b24216f27d8266c87b9fa9a70f533">FindMergedConditions</a> (const Value *Cond, MachineBasicBlock *TBB, MachineBasicBlock *FBB, MachineBasicBlock *CurBB, MachineBasicBlock *SwitchBB, Instruction::BinaryOps Opc, BranchProbability TProb, BranchProbability FProb, bool InvertCond)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41a8f459a2dcfcfc624394df6b432689">EmitBranchForMergedCondition</a> (const Value *Cond, MachineBasicBlock *TBB, MachineBasicBlock *FBB, MachineBasicBlock *CurBB, MachineBasicBlock *SwitchBB, BranchProbability TProb, BranchProbability FProb, bool InvertCond)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitBranchForMergedCondition - Helper method for FindMergedConditions. <a href="#a41a8f459a2dcfcfc624394df6b432689">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b3bd2c89ff35a733d365b34c2dca4fb">ShouldEmitAsBranches</a> (const std::vector&lt; SwitchCG::CaseBlock &gt; &amp;Cases)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the set of cases should be emitted as a series of branches, return true. <a href="#a3b3bd2c89ff35a733d365b34c2dca4fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3df768f340538afba57a5eaeb0ba277">isExportableFromCurrentBlock</a> (const Value *V, const BasicBlock *FromBB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac30ce0e7a5759d1e0bb5bf891e88662b">CopyToExportRegsIfNeeded</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CopyToExportRegsIfNeeded - If the given value has virtual registers created for it, emit nodes to copy the value into the virtual registers. <a href="#ac30ce0e7a5759d1e0bb5bf891e88662b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5254258c6a479f86e6ecfc4dcdd7a5e">ExportFromCurrentBlock</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ExportFromCurrentBlock - If this condition isn't known to be exported from the current basic block, add it to <a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMap</a> now so that we'll get a CopyTo/FromReg. <a href="#aa5254258c6a479f86e6ecfc4dcdd7a5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b4653fa0c302d9cbe4e7839d711e76a">LowerCallTo</a> (const CallBase &amp;CB, SDValue Callee, bool IsTailCall, bool IsMustTailCall, const BasicBlock *EHPadBB=nullptr, const TargetLowering::PtrAuthInfo *PAI=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3756185351596750edbb4790d9923eea">lowerRangeToAssertZExt</a> (SelectionDAG &amp;DAG, const Instruction &amp;I, SDValue Op)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a8a4b167d0244a5c34b6819dd3d5c56">populateCallLoweringInfo</a> (TargetLowering::CallLoweringInfo &amp;CLI, const CallBase *Call, unsigned ArgIdx, unsigned NumArgs, SDValue Callee, Type *ReturnTy, AttributeSet RetAttrs, bool IsPatchPoint)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populate a CallLowerinInfo (into <span class="doxyComputerOutput">CLI</span>) based on the properties of the call being lowered. <a href="#a8a8a4b167d0244a5c34b6819dd3d5c56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab29b69c993fbb9a4b9d28c3600df005d">lowerInvokable</a> (TargetLowering::CallLoweringInfo &amp;CLI, const BasicBlock *EHPadBB=nullptr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6e9499206c6a56801d70a567fc8862a">UpdateSplitBlock</a> (MachineBasicBlock *First, MachineBasicBlock *Last)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When an MBB was split during scheduling, update the references that need to refer to the last resulting block. <a href="#af6e9499206c6a56801d70a567fc8862a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe97e2bc5bd74272ca1b54da1fb30e06">LowerAsSTATEPOINT</a> (StatepointLoweringInfo &amp;SI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower <span class="doxyComputerOutput">SLI</span> into a STATEPOINT instruction. <a href="#afe97e2bc5bd74272ca1b54da1fb30e06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32cff45e4cfd323ecc3896adcb08c2a9">LowerStatepoint</a> (const GCStatepointInst &amp;I, const BasicBlock *EHPadBB=nullptr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a475d759da0893604f08519960a12d297">LowerCallSiteWithDeoptBundle</a> (const CallBase *Call, SDValue Callee, const BasicBlock *EHPadBB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a459873061a3fed537ca026ddaffe57ed">LowerDeoptimizeCall</a> (const CallInst *CI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf29bbf079b2610d2c8481212261fc49">LowerDeoptimizingReturn</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57ee991742a8027b5ef002c616a6b9fd">LowerCallSiteWithDeoptBundleImpl</a> (const CallBase *Call, SDValue Callee, const BasicBlock *EHPadBB, bool VarArgDisallowed, bool ForceVoidReturnTy)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9742261cd7ee88cb99ec122fc61f5e8">LowerCallSiteWithPtrAuthBundle</a> (const CallBase &amp;CB, const BasicBlock *EHPadBB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f4850c6b936e27186113935b002b36f">getFrameIndexTy</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the type of FrameIndex and TargetFrameIndex nodes. <a href="#a2f4850c6b936e27186113935b002b36f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe7d9f31d3030277242731ccf43478c0">visitSwitchCase</a> (SwitchCG::CaseBlock &amp;CB, MachineBasicBlock *SwitchBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>visitSwitchCase - Emits the necessary code to represent a single node in the binary search tree resulting from lowering a switch instruction. <a href="#afe7d9f31d3030277242731ccf43478c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8662f747218aee8ddeb4cdfbd1435a7">visitSPDescriptorParent</a> (StackProtectorDescriptor &amp;SPD, MachineBasicBlock *ParentBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Codegen a new tail for a stack protector check ParentMBB which has had its tail spliced into a stack protector check success bb. <a href="#ae8662f747218aee8ddeb4cdfbd1435a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afff13ac7b2e92fc0ad596603592298bd">visitSPDescriptorFailure</a> (StackProtectorDescriptor &amp;SPD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Codegen the failure basic block for a stack protector check. <a href="#afff13ac7b2e92fc0ad596603592298bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31f9f0db1bb0b321286db70b58fb001e">visitBitTestHeader</a> (SwitchCG::BitTestBlock &amp;B, MachineBasicBlock *SwitchBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>visitBitTestHeader - This function emits necessary code to produce value suitable for "bit tests" <a href="#a31f9f0db1bb0b321286db70b58fb001e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a7b439d546506d56e2cdc61a1ac1d06">visitBitTestCase</a> (SwitchCG::BitTestBlock &amp;BB, MachineBasicBlock *NextMBB, BranchProbability BranchProbToNext, Register Reg, SwitchCG::BitTestCase &amp;B, MachineBasicBlock *SwitchBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>visitBitTestCase - this function produces one "bit test" <a href="#a7a7b439d546506d56e2cdc61a1ac1d06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac730a866bfd17ffc004cc3a0e85c3770">visitJumpTable</a> (SwitchCG::JumpTable &amp;JT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>visitJumpTable - Emit <a href="/web-llvm/docs/api/namespaces/llvm/jumptable">JumpTable</a> node in the current MBB <a href="#ac730a866bfd17ffc004cc3a0e85c3770">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac85aa2ebc935e3c87ec7f9e54183cddf">visitJumpTableHeader</a> (SwitchCG::JumpTable &amp;JT, SwitchCG::JumpTableHeader &amp;JTH, MachineBasicBlock *SwitchBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>visitJumpTableHeader - This function emits necessary code to produce index in the <a href="/web-llvm/docs/api/namespaces/llvm/jumptable">JumpTable</a> from switch case. <a href="#ac85aa2ebc935e3c87ec7f9e54183cddf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/selectiondagbuilder/danglingdebuginfo/print">DanglingDebugInfo::Print</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0429f5362de4cf4b7d100c3193db49f">printDDI</a> (const Value *V, const DanglingDebugInfo &amp;DDI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an object that defines <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;operator&lt;&lt;</span> for printing. <a href="#af0429f5362de4cf4b7d100c3193db49f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e38832b5d73e2220eb8870ff2abb0ec">updateRoot</a> (SmallVectorImpl&lt; SDValue &gt; &amp;Pending)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update root to include all chains from the Pending list. <a href="#a1e38832b5d73e2220eb8870ff2abb0ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14b40f90b6f3e0ef5f24460560ba0eb8">splitWorkItem</a> (SwitchCG::SwitchWorkList &amp;WorkList, const SwitchCG::SwitchWorkListItem &amp;W, Value *Cond, MachineBasicBlock *SwitchMBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit comparison and split W into two subtrees. <a href="#a14b40f90b6f3e0ef5f24460560ba0eb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07a10f663868d19955f42e7148f41096">lowerWorkItem</a> (SwitchCG::SwitchWorkListItem W, Value *Cond, MachineBasicBlock *SwitchMBB, MachineBasicBlock *DefaultMBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower W. <a href="#a07a10f663868d19955f42e7148f41096">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a287e7e90f99384ce89643972e9e7929f">peelDominantCaseCluster</a> (const SwitchInst &amp;SI, SwitchCG::CaseClusterVector &amp;Clusters, BranchProbability &amp;PeeledCaseProb)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Peel the top probability case if it exceeds the threshold. <a href="#a287e7e90f99384ce89643972e9e7929f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aa12f54e1eb4339c69ebd8db8cbf052">visitRet</a> (const ReturnInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b10a0cbbe1874a420a8bef129fb64ad">visitBr</a> (const BranchInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a408c9bfd71e6edbb4755986c55cac5e0">visitSwitch</a> (const SwitchInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9dbd7a4da7b71d125302169e429b710">visitIndirectBr</a> (const IndirectBrInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40da2629051f9f83b1d6fb65c7fde94a">visitUnreachable</a> (const UnreachableInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbd02f6436764b133fd32b91a1e49596">visitCleanupRet</a> (const CleanupReturnInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d6eb93de27028cdb28d87075c1c59c8">visitCatchSwitch</a> (const CatchSwitchInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ffeb9158761ced0f48521ec4301339b">visitCatchRet</a> (const CatchReturnInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7da9dfec0ff00e148d07dfbc281c5109">visitCatchPad</a> (const CatchPadInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51667e5d76eead9755d11f008a4b788d">visitCleanupPad</a> (const CleanupPadInst &amp;CPI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad62f157cdaa90ddefc8b872d3baca70c">getEdgeProbability</a> (const MachineBasicBlock *Src, const MachineBasicBlock *Dst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return branch probability calculated by <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> for IR blocks. <a href="#ad62f157cdaa90ddefc8b872d3baca70c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21a6d7097a11dc947cd9ac7baf493f21">addSuccessorWithProb</a> (MachineBasicBlock *Src, MachineBasicBlock *Dst, BranchProbability Prob=BranchProbability::getUnknown())</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad260c689c5d6b23a6d0c9ef62b07fda6">visitInvoke</a> (const InvokeInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0baecbe8c996f9625d3abff4954b7a78">visitCallBr</a> (const CallBrInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab9d1b68003c3098e1a59beac208d9d2">visitCallBrLandingPad</a> (const CallInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cc665eafaf5bd4765d0f109348374bc">visitResume</a> (const ResumeInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6980e0bc12618f0c0ae89a473996d4b6">visitUnary</a> (const User &amp;I, unsigned Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7859c0692d54ad5306f6c7c5ce9d0546">visitFNeg</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fd0ba78aee5163c0b06f70f3f2dbee1">visitBinary</a> (const User &amp;I, unsigned Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0da78cbe076521e7685505199b8e82bc">visitShift</a> (const User &amp;I, unsigned Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af21eacff266ea1d0e67d8fe5e727b686">visitAdd</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43c4d28f58ce3a60b625477f598a83aa">visitFAdd</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a937657e0221c87545044638a4ab2be4c">visitSub</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae710111f773443b543bde95634e429f7">visitFSub</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52d2f236b9ce4436e4e970f35cb50752">visitMul</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba32842f60d4a6198bc89767fbc1a842">visitFMul</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7864b1229a2954734a97b38ddd74513">visitURem</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99981b95d5c98336497c404752202cf6">visitSRem</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae90de1065de3deb0f5e418b4f0a44210">visitFRem</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab0a9cf45cdba61b3f522fc9088ca221">visitUDiv</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b4f6a0a5ba8edf817dfe59012e8e95a">visitSDiv</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc0d033e09ed6f37ad9f8af32043f599">visitFDiv</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b406d72675121b9649f809078680a6a">visitAnd</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d571c48cdee414ac9b97eb13349bb69">visitOr</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe66828045d8bb988da9f890117804c8">visitXor</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e08353d0bc4a5e3861796b17f6b8fed">visitShl</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64ea76dd35ed35eaa176daddea1cbc80">visitLShr</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01a073ba73c0b424f9ebd1a19d8d8661">visitAShr</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5597c935678f50910321b226f8d7f58">visitICmp</a> (const ICmpInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08de87011f15b96feaa35e64c153cbb6">visitFCmp</a> (const FCmpInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec88d366b75cc48a99cfe6a3236f1c30">visitTrunc</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4b6eb452180d261fb0698a7bfcbf84">visitZExt</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70f67c1a7b5b393926eb0e557d26517b">visitSExt</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa97474525c7e7f9f0842f1ed4251bc5a">visitFPTrunc</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63afe238f9c42d552956548b6c7762eb">visitFPExt</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ca34d68fd2d3a67915c4011f406c68e">visitFPToUI</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca25d8a2ea316cc6bc1344cdd2077212">visitFPToSI</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fbb446d00cc9c216e4d1aa219f045ad">visitUIToFP</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad6be22335fd5d11a76fcae1ab7c3261">visitSIToFP</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6c3bf7162c871e0cc93034ab10db909">visitPtrToInt</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbe63fb4ba5a8abd8614dceeed4c024a">visitIntToPtr</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b49404226d2806ed7af4b723f29e18a">visitBitCast</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ad0574a8accf1ca35ba31fc1576ae94">visitAddrSpaceCast</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9afd4051e157f8c91019b876c1c7a2e0">visitExtractElement</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9335f601c1f67d5a1d40523c5c33024e">visitInsertElement</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a038b93be769197be0fd79608d08e6388">visitShuffleVector</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1200aa2f17c82db61df56d7f2113d5b9">visitExtractValue</a> (const ExtractValueInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a91a5a078dcb4818340526d7c76f92a">visitInsertValue</a> (const InsertValueInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12894d1bc3486785ce48cae0dbb3eb12">visitLandingPad</a> (const LandingPadInst &amp;LP)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78500cfd5e3d7495b0bb997a162358bd">visitGetElementPtr</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ef642ca35c19140020dd4b04eab0125">visitSelect</a> (const User &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45b8864f609a8a261482d8d4046ccb13">visitAlloca</a> (const AllocaInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d7cea38f6895ae6d97d4c038b0f1bc8">visitLoad</a> (const LoadInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9310870a3dfe30f89db39b762065560c">visitStore</a> (const StoreInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a426dcdae1838725d2a7975cc94e2cfea">visitMaskedLoad</a> (const CallInst &amp;I, bool IsExpanding=false)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa37c2080baa3610dba4ca82f803c699">visitMaskedStore</a> (const CallInst &amp;I, bool IsCompressing=false)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad873d634838bc135399f4b0c122f8fa3">visitMaskedGather</a> (const CallInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37f8dd258fcff12411a00b5256de1d3c">visitMaskedScatter</a> (const CallInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594bf7b91bae39e766a86902a38fcb5f">visitAtomicCmpXchg</a> (const AtomicCmpXchgInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9855415a865f8f2b8ad8d2b28cc1bd0d">visitAtomicRMW</a> (const AtomicRMWInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a319c223b1c5c2245a0d33c4ab7ccd74c">visitFence</a> (const FenceInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5420fdf35c2238d3a4122dc4ba8a5b3f">visitPHI</a> (const PHINode &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b987a656b8f13738504e7a0aa73b835">visitCall</a> (const CallInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4998b62f0ad5edc534a95a566ce0ee06">visitMemCmpBCmpCall</a> (const CallInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See if we can lower a memcmp/bcmp call into an optimized form. <a href="#a4998b62f0ad5edc534a95a566ce0ee06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c7acd0e7630a39734bbfa8635a3b697">visitMemPCpyCall</a> (const CallInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See if we can lower a mempcpy call into an optimized form. <a href="#a9c7acd0e7630a39734bbfa8635a3b697">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a914053bf64f91a0da259ee1af952b487">visitMemChrCall</a> (const CallInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See if we can lower a memchr call into an optimized form. <a href="#a914053bf64f91a0da259ee1af952b487">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a397e7dbad665bba3933f58b3fd48661f">visitStrCpyCall</a> (const CallInst &amp;I, bool isStpcpy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See if we can lower a strcpy call into an optimized form. <a href="#a397e7dbad665bba3933f58b3fd48661f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4ee024ceff1e24676579d9d13a3f2a6">visitStrCmpCall</a> (const CallInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See if we can lower a strcmp call into an optimized form. <a href="#af4ee024ceff1e24676579d9d13a3f2a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad6edde6e74cfca093a869153f5ead65">visitStrLenCall</a> (const CallInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See if we can lower a strlen call into an optimized form. <a href="#aad6edde6e74cfca093a869153f5ead65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3a880857918dc26a5d91789c9f2f8d4">visitStrNLenCall</a> (const CallInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See if we can lower a strnlen call into an optimized form. <a href="#ad3a880857918dc26a5d91789c9f2f8d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43518c43dbded63bab6be0e488c8b4ea">visitUnaryFloatCall</a> (const CallInst &amp;I, unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See if we can lower a unary floating-point operation into an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> with the specified Opcode. <a href="#a43518c43dbded63bab6be0e488c8b4ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51ce43dbac09a9facb22e8cbc421fdb0">visitBinaryFloatCall</a> (const CallInst &amp;I, unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See if we can lower a binary floating-point operation into an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> with the specified Opcode. <a href="#a51ce43dbac09a9facb22e8cbc421fdb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc47700340531b4df27c9d959da97860">visitAtomicLoad</a> (const LoadInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac881045cdf62679b06f514a2b1fa7b11">visitAtomicStore</a> (const StoreInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac10d1228801d9155ab522c0f816e1bc9">visitLoadFromSwiftError</a> (const LoadInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaa1dfc323111fb7c292ad81160f8086">visitStoreToSwiftError</a> (const StoreInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e27007fee27dc8aa8fa1518575eb386">visitFreeze</a> (const FreezeInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecee217a9b6b3934ba569dacc4a6616c">visitInlineAsm</a> (const CallBase &amp;Call, const BasicBlock *EHPadBB=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>visitInlineAsm - Handle a call to an <a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a> object. <a href="#aecee217a9b6b3934ba569dacc4a6616c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4af6f4899b4c65d90e8a82dfa204f7a">visitEntryValueDbgValue</a> (ArrayRef&lt; const Value * &gt; Values, DILocalVariable *Variable, DIExpression *Expr, DebugLoc DbgLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If DI is a debug value with an EntryValue expression, lower it using the corresponding physical register of the associated <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> value (guaranteed to exist by the verifier). <a href="#ab4af6f4899b4c65d90e8a82dfa204f7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eedf4e2f8a9b61b3b408b8c29bc9672">visitIntrinsicCall</a> (const CallInst &amp;I, unsigned Intrinsic)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower the call to the specified intrinsic function. <a href="#a9eedf4e2f8a9b61b3b408b8c29bc9672">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eb5d1c30f868f2f4a5c2422fa0b34d2">visitTargetIntrinsic</a> (const CallInst &amp;I, unsigned Intrinsic)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>visitTargetIntrinsic - Lower a call of a target intrinsic to an INTRINSIC node. <a href="#a1eb5d1c30f868f2f4a5c2422fa0b34d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af190af13bec416448d92dcce55c068f1">visitConstrainedFPIntrinsic</a> (const ConstrainedFPIntrinsic &amp;FPI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a919e259fc38a81f901c4957529fff05f">visitConvergenceControl</a> (const CallInst &amp;I, unsigned Intrinsic)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower the call to the specified intrinsic function. <a href="#a919e259fc38a81f901c4957529fff05f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8ec5b3697d7100b04c0e01d6ad83327">visitVectorHistogram</a> (const CallInst &amp;I, unsigned IntrinsicID)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbe70c9435d2e38bc5c71015a0ed31dc">visitVectorExtractLastActive</a> (const CallInst &amp;I, unsigned Intrinsic)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98418231da2a34a44ec0e86f5f712b7d">visitVPLoad</a> (const VPIntrinsic &amp;VPIntrin, EVT VT, const SmallVectorImpl&lt; SDValue &gt; &amp;OpValues)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0601cc3b22e9156807d8cfa3690ff5e2">visitVPStore</a> (const VPIntrinsic &amp;VPIntrin, const SmallVectorImpl&lt; SDValue &gt; &amp;OpValues)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9974797b2b152e3871fb766487e004ff">visitVPGather</a> (const VPIntrinsic &amp;VPIntrin, EVT VT, const SmallVectorImpl&lt; SDValue &gt; &amp;OpValues)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15674d84950f1769ff1418cbf07fd85c">visitVPScatter</a> (const VPIntrinsic &amp;VPIntrin, const SmallVectorImpl&lt; SDValue &gt; &amp;OpValues)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b3ab5ce634fb83b18830ef0240f1a3">visitVPStridedLoad</a> (const VPIntrinsic &amp;VPIntrin, EVT VT, const SmallVectorImpl&lt; SDValue &gt; &amp;OpValues)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3deeff710530f6de66107be8d0fdbc1f">visitVPStridedStore</a> (const VPIntrinsic &amp;VPIntrin, const SmallVectorImpl&lt; SDValue &gt; &amp;OpValues)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2d8d23ca4b26550ea961943d2a2bbdc">visitVPCmp</a> (const VPCmpIntrinsic &amp;VPIntrin)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a014897a6abb41d1bb46d99b8ca925d50">visitVectorPredicationIntrinsic</a> (const VPIntrinsic &amp;VPIntrin)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82a8763c5132e518a4e9f9b70453bdc5">visitVAStart</a> (const CallInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a959582865c5fe60bab89733537d14e05">visitVAArg</a> (const VAArgInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a729a34a78c9e74360fb5c83ec46326de">visitVAEnd</a> (const CallInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2662cfa7d61334ecea635901024fe72">visitVACopy</a> (const CallInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20752020d6cb05c8120c966bd681d7b7">visitStackmap</a> (const CallInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower llvm.experimental.stackmap. <a href="#a20752020d6cb05c8120c966bd681d7b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e718dd379024c5842af7f4b0a36d3ff">visitPatchpoint</a> (const CallBase &amp;CB, const BasicBlock *EHPadBB=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower llvm.experimental.patchpoint directly to its target opcode. <a href="#a2e718dd379024c5842af7f4b0a36d3ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80af9838047d9b5448e6ce6bd381b715">visitGCRelocate</a> (const GCRelocateInst &amp;Relocate)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8ceffd32caf03cad4080929f373487c">visitGCResult</a> (const GCResultInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba45c469ca384ad5814add80f5758e17">visitVectorReduce</a> (const CallInst &amp;I, unsigned Intrinsic)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4f5b59103cda710365a298ce3e3c905">visitVectorReverse</a> (const CallInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacbd78808b39f4743229ce828b188482">visitVectorSplice</a> (const CallInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8b943b2fad743449863cdb1d976df58">visitVectorInterleave</a> (const CallInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6da642116003fbf53711220e3059649">visitVectorDeinterleave</a> (const CallInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af342c629f30c0910e4da9bdc7daff657">visitStepVector</a> (const CallInst &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f33264d64406cbf782a50d32d22c1a0">visitUserOp1</a> (const Instruction &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae905a886120476763767d8e3d6e57864">visitUserOp2</a> (const Instruction &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2e044dd48bb60701e130220d73dfc27">processIntegerCallValue</a> (const Instruction &amp;I, SDValue Value, bool IsSigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the value for an instruction that produces an integer result, converting the type where necessary. <a href="#ac2e044dd48bb60701e130220d73dfc27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2cdd05d95ff1f2b337ba7c5d697a9db">HandlePHINodesInSuccessorBlocks</a> (const BasicBlock *LLVMBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle PHI nodes in successor blocks. <a href="#ae2cdd05d95ff1f2b337ba7c5d697a9db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cbeefc4fb9eb7208567c7915772ff48">emitInlineAsmError</a> (const CallBase &amp;Call, const Twine &amp;Message)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2fb6a906e9481d4d2b0d23e1080fdd1">EmitFuncArgumentDbgValue</a> (const Value *V, DILocalVariable *Variable, DIExpression *Expr, DILocation *DL, FuncArgumentDbgValueKind Kind, const SDValue &amp;N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If V is an function argument then create corresponding DBG_VALUE machine instruction for it now. <a href="#aa2fb6a906e9481d4d2b0d23e1080fdd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e07ae57e561e845f07db0ba649f113f">NextBlock</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the next block after MBB, or nullptr if there is none. <a href="#a8e07ae57e561e845f07db0ba649f113f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30f2f462034b588f7fefe18614b84f88">updateDAGForMaybeTailCall</a> (SDValue MaybeTC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the DAG and DAG builder with the relevant information after a new root node has been created which could be a tail call. <a href="#a30f2f462034b588f7fefe18614b84f88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29ea057ad9992694b82c73412792a8a8">getDbgValue</a> (SDValue N, DILocalVariable *Variable, DIExpression *Expr, const DebugLoc &amp;dl, unsigned DbgSDNodeOrder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the appropriate <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a> based on N. <a href="#a29ea057ad9992694b82c73412792a8a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77764e03957bcd38a3d8e329e8fa5ab6">lowerCallToExternalSymbol</a> (const CallInst &amp;I, const char *FunctionName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lowers <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> to an external symbol. <a href="#a77764e03957bcd38a3d8e329e8fa5ab6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23e8ca684730b4f9c9a3fbacbe374201">lowerStartEH</a> (SDValue Chain, const BasicBlock *EHPadBB, MCSymbol *&amp;BeginLabel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5d7837fb8c70f654a30f8503691f12e">lowerEndEH</a> (SDValue Chain, const InvokeInst *II, const BasicBlock *EHPadBB, MCSymbol *BeginLabel)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a1381eb77fac8d57f54f7bf25919a4e">PendingLoads</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads are not emitted to the program immediately. <a href="#a9a1381eb77fac8d57f54f7bf25919a4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate">StatepointLoweringState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77cbbcab1440ac5ef835e1a3d3f6c74e">StatepointLowering</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>State used while lowering a statepoint sequence (gc_statepoint, gc_relocate, and gc_result). <a href="#a77cbbcab1440ac5ef835e1a3d3f6c74e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad997f08bfd4680a697130632badf740e">DAG</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23f8a52e7e457d67b67aa86541f55c17">BatchAA</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb6015cccbf35f2e27ca3367cda3cdec">AC</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae283c81e2135fac41f1896dd39c4cc40">LibInfo</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/sdagswitchlowering">SDAGSwitchLowering</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a346bf6c4d7fca3ebce554ec2cdd80e87">SL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stackprotectordescriptor">StackProtectorDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e6f0d1aacd8e97d178a627fdafc3aaf">SPDescriptor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/stackprotectordescriptor">StackProtectorDescriptor</a> structure used to communicate stack protector information in between SelectBasicBlock and FinishBasicBlock. <a href="#a1e6f0d1aacd8e97d178a627fdafc3aaf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bdfdf9731f7e5501dea5dd410ebf9ef">ConstantsOut</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad10e64e191507974af84a4ea069a9e36">FuncInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Information about the function as a whole. <a href="#ad10e64e191507974af84a4ea069a9e36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/swifterrorvaluetracking">SwiftErrorValueTracking</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ac2cfd1783912207570d7cce74a3ea2">SwiftError</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Information about the swifterror values used throughout the function. <a href="#a4ac2cfd1783912207570d7cce74a3ea2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcfunctioninfo">GCFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b4db8b8082660004fda0c282da0ff0a">GFI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Garbage collection metadata for the function. <a href="#a9b4db8b8082660004fda0c282da0ff0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 4 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53319e45ea515329480adf13f0098b4b">LPadToCallSiteMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a landing pad to the call site indexes. <a href="#a53319e45ea515329480adf13f0098b4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39e446f1647e793791c33d0d2412d088">HasTailCall</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is set to true if a call in the current block has been translated as a tail call. <a href="#a39e446f1647e793791c33d0d2412d088">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac536e4b59b1e85317cea0b32d47752ef">Context</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf98d39188856842bae71a40fd6a7af4">CurInst</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current instruction being visited. <a href="#adf98d39188856842bae71a40fd6a7af4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a861c224bffd58fc2e4dae66d9656c21e">NodeMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a396e61e3845a565bb1ed778c2ba1240c">UnusedArgNodeMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps argument value for unused arguments. <a href="#a396e61e3845a565bb1ed778c2ba1240c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, DanglingDebugInfoVector &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad97bc0e0c5a9f36b3662b012557efae8">DanglingDebugInfoMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps track of dbg_values for which we have not yet seen the referent. <a href="#ad97bc0e0c5a9f36b3662b012557efae8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8e021fdfe03d8dee4c95d00f0fadcf5">AssignmentTrackingEnabled</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache the module flag for whether we should use debug-info assignment tracking. <a href="#ab8e021fdfe03d8dee4c95d00f0fadcf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28f8b07457528489f897e04c4794520c">PendingExports</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CopyToReg nodes that copy values to virtual registers for export to other blocks need to be emitted before any terminator instruction, but they have no other ordering requirements. <a href="#a28f8b07457528489f897e04c4794520c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae50ca4d135cbeb554c6ed23b3fadd41b">PendingConstrainedFP</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to loads, nodes corresponding to constrained FP intrinsics are bunched up and emitted when necessary. <a href="#ae50ca4d135cbeb554c6ed23b3fadd41b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a882a433e31fed4c06203690225a7f1b3">PendingConstrainedFPStrict</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9fa46bde40ba2275ce99bde1389d065">SDNodeOrder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A unique monotonically increasing number used to order the SDNodes we create. <a href="#ae9fa46bde40ba2275ce99bde1389d065">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3293dad09e732134cb72b1cec185de56">TM</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accb23e3bb8c3fddd1fc7a18025b1ec0d">LowestSDNodeOrder</a> = 1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lowest valid SDNodeOrder. <a href="#accb23e3bb8c3fddd1fc7a18025b1ec0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> - This is the common target-independent lowering implementation that is parameterized by a <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> object.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### DanglingDebugInfoVector {#af281db65ead4c8bafbc63a6c7589086c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt;DanglingDebugInfo&gt; llvm::SelectionDAGBuilder::DanglingDebugInfoVector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper type for DanglingDebugInfoMap.</p>

<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### FuncArgumentDbgValueKind {#a4f8d012b1e12df0ae8fb9888b5d37c66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::SelectionDAGBuilder::FuncArgumentDbgValueKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An enum that states to emit func argument dbg value the kind of intrinsic it originally had.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Value<a id="a4f8d012b1e12df0ae8fb9888b5d37c66a689202409e48743b914713f96d93947c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Declare<a id="a4f8d012b1e12df0ae8fb9888b5d37c66a2709046ed364cc54b91f908e85e512ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>This controls the internal behavior of EmitFuncArgumentDbgValue.</p>


<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SelectionDAGBuilder() {#a89f8344fd5ae844b5beec8c4b9924f95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SelectionDAGBuilder::SelectionDAGBuilder (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; dag, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; funcinfo, <a href="/web-llvm/docs/api/classes/llvm/swifterrorvaluetracking">SwiftErrorValueTracking</a> &amp; swifterror, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> ol)</td>
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



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>References <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="#ad10e64e191507974af84a4ea069a9e36">FuncInfo</a>, <a href="#accb23e3bb8c3fddd1fc7a18025b1ec0d">LowestSDNodeOrder</a>, <a href="#a346bf6c4d7fca3ebce554ec2cdd80e87">SL</a> and <a href="#a4ac2cfd1783912207570d7cce74a3ea2">SwiftError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/sdagswitchlowering/#a4eded23b59e955c010b3f0c50fef239a">llvm::SelectionDAGBuilder::SDAGSwitchLowering::SDAGSwitchLowering</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addDanglingDebugInfo() {#a13b6c3ad0bdee051eda42dc7c8a1f12b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::addDanglingDebugInfo (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; Values, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Var, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, bool IsVariadic, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, unsigned Order)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a dbg_value which relies on a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> which we have not yet seen.</p>

<p>Declaration at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1403 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a4e84a47e3ca9c1684a752533e2881cd7">handleDanglingVariadicDebugInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a196df57d98a1307c0ced654a8e1d202b">visitDbgInfo</a>.</p>

</div>
</div>

### clear() {#a2c224fcb5175ab1e842dd2a1371eb3d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clear out the current <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> and the associated state and prepare this <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> object to be used for a new block.</p>


<p>This doesn't clear out information about additional blocks that are needed to complete switch lowering or PHI node updating; that information is cleared out as it is consumed.</p>


<p>Declaration at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1099 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="#a39e446f1647e793791c33d0d2412d088">HasTailCall</a>, <a href="#accb23e3bb8c3fddd1fc7a18025b1ec0d">LowestSDNodeOrder</a>, <a href="#a9a1381eb77fac8d57f54f7bf25919a4e">PendingLoads</a> and <a href="#a77cbbcab1440ac5ef835e1a3d3f6c74e">StatepointLowering</a>.</p>

</div>
</div>

### clearDanglingDebugInfo() {#a1b90604db120716e786d9d33babc3edd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::clearDanglingDebugInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clear the dangling debug information map.</p>


<p>This function is separated from the clear so that debug information that is dangling in a basic block can be properly resolved in a different basic block. This allows the <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> to resolve dangling debug information attached to PHI nodes.</p>


<p>Declaration at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>Referenced by <a href="#ab0535176e89ed7e0647a533aa033bb34">resolveOrClearDbgInfo</a>.</p>

</div>
</div>

### CopyToExportRegsIfNeeded() {#ac30ce0e7a5759d1e0bb5bf891e88662b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::CopyToExportRegsIfNeeded (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CopyToExportRegsIfNeeded - If the given value has virtual registers created for it, emit nodes to copy the value into the virtual registers.</p>

<p>Declaration at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 2341 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5184df56e270750a839acad50a1b8501">CopyValueToVirtualRegister</a>, <a href="#ad10e64e191507974af84a4ea069a9e36">FuncInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#abbbfefd79a5b3d1b4ea8d8383fd01af5">visit</a>.</p>

</div>
</div>

### CopyValueToVirtualRegister() {#a5184df56e270750a839acad50a1b8501}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::CopyValueToVirtualRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, unsigned Reg, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110">ISD::NodeType</a> ExtendType=<a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">ISD::ANY_EXTEND</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 11376 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a84c47705bcf7271413738ae8bf3871e6">llvm::ISD::CopyFromReg</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="#ad10e64e191507974af84a4ea069a9e36">FuncInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/regsforvalue/#adf93dd21d49c19700e980b15f19cb7d7">llvm::RegsForValue::getCopyToRegs</a>, <a href="#abb661ad9d4e5fd0d8806106e9b4d7256">getCurSDLoc</a>, <a href="#a4ad02593716678add54090c344959750">getNonRegisterValue</a> and <a href="/web-llvm/docs/api/classes/llvm/register/#afacc26f29d80e10be4785a96ed6444dc">llvm::Register::isPhysicalRegister</a>.</p>


<p>Referenced by <a href="#ac30ce0e7a5759d1e0bb5bf891e88662b">CopyToExportRegsIfNeeded</a> and <a href="#aa5254258c6a479f86e6ecfc4dcdd7a5e">ExportFromCurrentBlock</a>.</p>

</div>
</div>

### dropDanglingDebugInfo() {#ac08d1b312ae9756038394d6b9568f383}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::dropDanglingDebugInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Variable, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If we have dangling debug info that describes <span class="doxyComputerOutput">Variable</span>, or an overlapping part of variable considering the <span class="doxyComputerOutput">Expr</span>, then this method will drop that debug info as it isn't valid any longer.</p>

<p>Declaration at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1420 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a7de5a04920954ac964059cfc428ad">llvm::erase_if</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a46d29699ee79b3a3d7359278f6bab01c">llvm::DIExpression::fragmentsOverlap</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#a8cf671ed90e3e80717aaa6318b24794c">salvageUnresolvedDbgValue</a>.</p>


<p>Referenced by <a href="#a196df57d98a1307c0ced654a8e1d202b">visitDbgInfo</a>.</p>

</div>
</div>

### EmitBranchForMergedCondition() {#a41a8f459a2dcfcfc624394df6b432689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::EmitBranchForMergedCondition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * FBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * CurBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SwitchBB, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> TProb, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> FProb, bool InvertCond)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EmitBranchForMergedCondition - Helper method for FindMergedConditions.</p>


<p>This function emits a branch and is used at the leaves of an OR or an AND operator tree.</p>


<p>Declaration at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 2433 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a4874816314c3308be0bf1e71de2078d8">llvm::MachineBasicBlock::getBasicBlock</a>, <a href="#abb661ad9d4e5fd0d8806106e9b4d7256">getCurSDLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab85a42eddf5fd6beac822af946d5b1e2">llvm::getFCmpCodeWithoutNaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8b3a8b47a5344da71953bc4eb38c5179">llvm::getFCmpCondCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0724f162df94451d626d918e992fe123">llvm::getICmpCondCode</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="#ae3df768f340538afba57a5eaeb0ba277">isExportableFromCurrentBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ae2e6a5e32087b9f65bd51585a6a5afb4">llvm::ISD::SETEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a>, <a href="#a346bf6c4d7fca3ebce554ec2cdd80e87">SL</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a1441f79530bc7f3a89118bb8067eac69">TBB</a>.</p>


<p>Referenced by <a href="#ae17b24216f27d8266c87b9fa9a70f533">FindMergedConditions</a>.</p>

</div>
</div>

### ExportFromCurrentBlock() {#aa5254258c6a479f86e6ecfc4dcdd7a5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::ExportFromCurrentBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ExportFromCurrentBlock - If this condition isn't known to be exported from the current basic block, add it to <a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMap</a> now so that we'll get a CopyTo/FromReg.</p>

<p>Declaration at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 2357 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="#a5184df56e270750a839acad50a1b8501">CopyValueToVirtualRegister</a>, <a href="#ad10e64e191507974af84a4ea069a9e36">FuncInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#afe97e2bc5bd74272ca1b54da1fb30e06">LowerAsSTATEPOINT</a>.</p>

</div>
</div>

### FindMergedConditions() {#ae17b24216f27d8266c87b9fa9a70f533}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::FindMergedConditions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * FBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * CurBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SwitchBB, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> Opc, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> TProb, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> FProb, bool InvertCond)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 2626 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adfc62ee16549afaac5bde30156ddc989">llvm::MachineFunction::CreateMachineBasicBlock</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a41a8f459a2dcfcfc624394df6b432689">EmitBranchForMergedCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="#ae17b24216f27d8266c87b9fa9a70f533">FindMergedConditions</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a4874816314c3308be0bf1e71de2078d8">llvm::MachineBasicBlock::getBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#afcd7ba772e220bcd0907ee2f1aa61323">InBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af4c0db6d503e0ba3b8e44067023ffbba">llvm::MachineFunction::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#acf8c16eed89e5ee1a10b6dfc08a33b3a">llvm::PatternMatch::m_LogicalAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5cce7a41c7581ff15a23ab90eb3b403a">llvm::PatternMatch::m_LogicalOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#afff2bab6bb7f206bbacad5dd589a6186">llvm::BranchProbability::normalizeProbabilities</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a1441f79530bc7f3a89118bb8067eac69">TBB</a>.</p>


<p>Referenced by <a href="#ae17b24216f27d8266c87b9fa9a70f533">FindMergedConditions</a>.</p>

</div>
</div>

### getControlRoot() {#aef34360e8bb4bdecf3fd6345ff504f81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SelectionDAGBuilder::getControlRoot ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similar to getRoot, but instead of flushing all the PendingLoad items, flush all the PendingExports (and PendingConstrainedFPStrict) items.</p>


<p>It is necessary to do this before emitting a terminator instruction.</p>


<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1167 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>Referenced by <a href="#afe97e2bc5bd74272ca1b54da1fb30e06">LowerAsSTATEPOINT</a>, <a href="#ab29b69c993fbb9a4b9d28c3600df005d">lowerInvokable</a>, <a href="#a7a7b439d546506d56e2cdc61a1ac1d06">visitBitTestCase</a>, <a href="#a31f9f0db1bb0b321286db70b58fb001e">visitBitTestHeader</a>, <a href="#ac730a866bfd17ffc004cc3a0e85c3770">visitJumpTable</a>, <a href="#ac85aa2ebc935e3c87ec7f9e54183cddf">visitJumpTableHeader</a> and <a href="#afe7d9f31d3030277242731ccf43478c0">visitSwitchCase</a>.</p>

</div>
</div>

### getCopyFromRegs() {#ac0b87e85b015d15077a7d9432c500df3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SelectionDAGBuilder::getCopyFromRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If there was virtual register allocated for the value V emit CopyFromReg of the specified type Ty.</p>


<p>getCopyFromRegs - If there was virtual register allocated for the value V emit CopyFromReg of the specified type Ty.</p>


<p>Return empty SDValue() otherwise.</p>


<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1726 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="#ad10e64e191507974af84a4ea069a9e36">FuncInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/regsforvalue/#ad782fe84b36a1c379ac9f1ac367706e1">llvm::RegsForValue::getCopyFromRegs</a>, <a href="#abb661ad9d4e5fd0d8806106e9b4d7256">getCurSDLoc</a> and <a href="#ab898c0fc6a2159b032a398271add3927">resolveDanglingDebugInfo</a>.</p>


<p>Referenced by <a href="#a025adb087cac36e2cd504a33e8cb749d">getValue</a>.</p>

</div>
</div>

### getCurDebugLoc() {#aaf62c0983c6240485d24b0fc329e1918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc llvm::SelectionDAGBuilder::getCurDebugLoc ()</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>.</p>

</div>
</div>

### getCurSDLoc() {#abb661ad9d4e5fd0d8806106e9b4d7256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDLoc llvm::SelectionDAGBuilder::getCurSDLoc ()</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="#a5184df56e270750a839acad50a1b8501">CopyValueToVirtualRegister</a>, <a href="#a41a8f459a2dcfcfc624394df6b432689">EmitBranchForMergedCondition</a>, <a href="#ac0b87e85b015d15077a7d9432c500df3">getCopyFromRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a8eaaa1b4edc9934bfea0469269f3d869">getMemCmpLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a3e8b055fdb7e07479b83d69c15211d54">getUniformBase</a>, <a href="#afe3b2bbac4396d088da5c91f77754843">getValueImpl</a>, <a href="#afe97e2bc5bd74272ca1b54da1fb30e06">LowerAsSTATEPOINT</a>, <a href="#a2b4653fa0c302d9cbe4e7839d711e76a">LowerCallTo</a>, <a href="#acf29bbf079b2610d2c8481212261fc49">LowerDeoptimizingReturn</a>, <a href="#a3756185351596750edbb4790d9923eea">lowerRangeToAssertZExt</a>, <a href="#a32cff45e4cfd323ecc3896adcb08c2a9">LowerStatepoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>, <a href="#a8a8a4b167d0244a5c34b6819dd3d5c56">populateCallLoweringInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a720a77a05d768dabfa739d154c11ddfd">pushStackMapConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#afb9b4b3ff97e290070f42849b51a13a5">spillIncomingStatepointValue</a>, <a href="#a7a7b439d546506d56e2cdc61a1ac1d06">visitBitTestCase</a>, <a href="#a31f9f0db1bb0b321286db70b58fb001e">visitBitTestHeader</a>, <a href="#afff13ac7b2e92fc0ad596603592298bd">visitSPDescriptorFailure</a>, <a href="#ae8662f747218aee8ddeb4cdfbd1435a7">visitSPDescriptorParent</a> and <a href="#afe7d9f31d3030277242731ccf43478c0">visitSwitchCase</a>.</p>

</div>
</div>

### getFrameIndexTy() {#a2f4850c6b936e27186113935b002b36f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::SelectionDAGBuilder::getFrameIndexTy ()</td>
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

<p>Returns the type of FrameIndex and TargetFrameIndex nodes.</p>

<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Reference <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a1692829d8158767fe5ac1809c90a77a3">lowerIncomingStatepointValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#adec63d991d7eb048d87fa3888099c848">reservePreviousStackSlotForValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#afb9b4b3ff97e290070f42849b51a13a5">spillIncomingStatepointValue</a>.</p>

</div>
</div>

### getMemoryRoot() {#ab41a8476a0c74bcf1a2bf665eeececd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SelectionDAGBuilder::getMemoryRoot ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the current virtual root of the Selection DAG, flushing any PendingLoad items.</p>


<p>This must be done before emitting a store or any other memory node that may need to be ordered after any prior load instructions.</p>


<p>Declaration at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1147 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>Reference <a href="#a9a1381eb77fac8d57f54f7bf25919a4e">PendingLoads</a>.</p>


<p>Referenced by <a href="#aa3e946c1fc678a70e849244389bd929a">getRoot</a>.</p>

</div>
</div>

### getNonRegisterValue() {#a4ad02593716678add54090c344959750}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SelectionDAGBuilder::getNonRegisterValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getNonRegisterValue - Return an <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> for the given <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, but don't look in FuncInfo.ValueMap for a virtual register.</p>

<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1767 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="#afe3b2bbac4396d088da5c91f77754843">getValueImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e392c596f41ac56b67f31c2e4b33dd1">llvm::isIntOrFPConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#ab898c0fc6a2159b032a398271add3927">resolveDanglingDebugInfo</a>.</p>


<p>Referenced by <a href="#a5184df56e270750a839acad50a1b8501">CopyValueToVirtualRegister</a>.</p>

</div>
</div>

### getRoot() {#aa3e946c1fc678a70e849244389bd929a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SelectionDAGBuilder::getRoot ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similar to getMemoryRoot, but also flushes PendingConstrainedFP(Strict) items.</p>


<p>This must be done before emitting any call other any other node that may need to be ordered after FP instructions due to other side effects.</p>


<p>Declaration at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="#ab41a8476a0c74bcf1a2bf665eeececd8">getMemoryRoot</a> and <a href="#a9a1381eb77fac8d57f54f7bf25919a4e">PendingLoads</a>.</p>


<p>Referenced by <a href="#afe97e2bc5bd74272ca1b54da1fb30e06">LowerAsSTATEPOINT</a>, <a href="#a2b4653fa0c302d9cbe4e7839d711e76a">LowerCallTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a1692829d8158767fe5ac1809c90a77a3">lowerIncomingStatepointValue</a>, <a href="#ab29b69c993fbb9a4b9d28c3600df005d">lowerInvokable</a> and <a href="#a8a8a4b167d0244a5c34b6819dd3d5c56">populateCallLoweringInfo</a>.</p>

</div>
</div>

### getValue() {#a025adb087cac36e2cd504a33e8cb749d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SelectionDAGBuilder::getValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getValue - Return an <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> for the given <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>

<p>Declaration at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1746 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="#ac0b87e85b015d15077a7d9432c500df3">getCopyFromRegs</a>, <a href="#afe3b2bbac4396d088da5c91f77754843">getValueImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#ab898c0fc6a2159b032a398271add3927">resolveDanglingDebugInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a21f33b0949c9004250a9978f1a5d3b3d">addStackMapLiveVars</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a8eaaa1b4edc9934bfea0469269f3d869">getMemCmpLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a3e8b055fdb7e07479b83d69c15211d54">getUniformBase</a>, <a href="#afe3b2bbac4396d088da5c91f77754843">getValueImpl</a>, <a href="#afe97e2bc5bd74272ca1b54da1fb30e06">LowerAsSTATEPOINT</a>, <a href="#ac9742261cd7ee88cb99ec122fc61f5e8">LowerCallSiteWithPtrAuthBundle</a>, <a href="#a2b4653fa0c302d9cbe4e7839d711e76a">LowerCallTo</a>, <a href="#a32cff45e4cfd323ecc3896adcb08c2a9">LowerStatepoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>, <a href="#a8a8a4b167d0244a5c34b6819dd3d5c56">populateCallLoweringInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#adec63d991d7eb048d87fa3888099c848">reservePreviousStackSlotForValue</a>, <a href="#a31f9f0db1bb0b321286db70b58fb001e">visitBitTestHeader</a>, <a href="#ac85aa2ebc935e3c87ec7f9e54183cddf">visitJumpTableHeader</a>, <a href="#ae8662f747218aee8ddeb4cdfbd1435a7">visitSPDescriptorParent</a> and <a href="#afe7d9f31d3030277242731ccf43478c0">visitSwitchCase</a>.</p>

</div>
</div>

### getValueImpl() {#afe3b2bbac4396d088da5c91f77754843}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SelectionDAGBuilder::getValueImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getValueImpl - Helper function for getValue and getNonRegisterValue.</p>


<p>Create an <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> for the given value.</p>


<p>Declaration at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1790 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab99618b3d8988b758a67f5a1a6071095">llvm::ComputeValueVTs</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ad10e64e191507974af84a4ea069a9e36">FuncInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/regsforvalue/#ad782fe84b36a1c379ac9f1ac367706e1">llvm::RegsForValue::getCopyFromRegs</a>, <a href="#abb661ad9d4e5fd0d8806106e9b4d7256">getCurSDLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#aded931e298cfa08b5038ca2b63c06bb8">llvm::MVT::getIntegerVT</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7f06dbaee5fa2b239de548d0a775b25b">llvm::SDNode::getNumValues</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="#a025adb087cac36e2cd504a33e8cb749d">getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a126c61d55fb4d2e509537ce68e8b6400">llvm::TargetLoweringBase::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a210ba6b43ba451b698857dd9de71bd15">llvm::EVT::getVectorVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3cb888a2ce8e95e0d9769687a5e2f7d8">llvm::EVT::isFloatingPoint</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a7687d0ddaf12046ae258432e98ad083e">llvm::EVT::isRISCVVectorTuple</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aa16d8f8fe394a4a8a2fd9c0a97c616d2">llvm::PatternMatch::m_VScale</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regutils-h/#a1fa2460e32327ade49189c95740bc1b5">NC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8df1b84ea64ad5048f27873205c8ab89">llvm::ISD::PtrAuthGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7f864031b6fb691b1525cbea92542ef1">llvm::ISD::SPLAT_VECTOR</a> and <a href="#abbbfefd79a5b3d1b4ea8d8383fd01af5">visit</a>.</p>


<p>Referenced by <a href="#a4ad02593716678add54090c344959750">getNonRegisterValue</a> and <a href="#a025adb087cac36e2cd504a33e8cb749d">getValue</a>.</p>

</div>
</div>

### handleDebugDeclare() {#a6571e1b07bfb1d4c5b1e832fdac355a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::handleDebugDeclare (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Address, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Variable, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expression, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1176 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable/#a45c267092569766aa684c6ba3bae9634">llvm::DILocalVariable::isParameter</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a196df57d98a1307c0ced654a8e1d202b">visitDbgInfo</a>.</p>

</div>
</div>

### handleDebugValue() {#ae9748fb2e4d41aaa8ac80d00b2becc52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SelectionDAGBuilder::handleDebugValue (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Values, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Var, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DbgLoc, unsigned Order, bool IsVariadic)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For a given list of Values, attempt to create and record a <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a> in the <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a>.</p>

<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1579 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#ab2fc167f75191e1d22e12e8e382605bb">llvm::DIExpression::createFragmentExpression</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#a839c3f734c6a978e745998e5d7904beb">llvm::SDDbgOperand::fromConst</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#a1ee3253416c1e239c9b70848aa4c4266">llvm::SDDbgOperand::fromFrameIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#a064ee6a43b2dc34747bda1d194922773">llvm::SDDbgOperand::fromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#a6e8946c426e13b7a8eac5f89fe1e8aca">llvm::SDDbgOperand::fromVReg</a>, <a href="#ad10e64e191507974af84a4ea069a9e36">FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a7cc5f1632a4c520497898439c17dc026">llvm::DIExpression::getFragmentInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/debugloc/#ada0b6f3c53a53b7274e7aeb23eeab5a8">llvm::DebugLoc::getInlinedAt</a>, <a href="/web-llvm/docs/api/structs/llvm/regsforvalue/#a03813938f6c7ea6b7e94965a27491ddc">llvm::RegsForValue::getRegsAndSizes</a>, <a href="/web-llvm/docs/api/classes/llvm/divariable/#a6b5977deeb9f99e156685e190de78403">llvm::DIVariable::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable/#a45c267092569766aa684c6ba3bae9634">llvm::DILocalVariable::isParameter</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/structs/llvm/regsforvalue/#aed4c3ed13d5c82a825cb533010000347">llvm::RegsForValue::occupiesMultipleRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#ac42eef26cc4185a8932bc59a94dc5d16">handleKillDebugValue</a>, <a href="#a8cf671ed90e3e80717aaa6318b24794c">salvageUnresolvedDbgValue</a> and <a href="#a196df57d98a1307c0ced654a8e1d202b">visitDbgInfo</a>.</p>

</div>
</div>

### handleKillDebugValue() {#ac42eef26cc4185a8932bc59a94dc5d16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::handleKillDebugValue (<a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Var, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DbgLoc, unsigned Order)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a record for a kill location debug intrinsic.</p>

<p>Declaration at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1568 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="#ac536e4b59b1e85317cea0b32d47752ef">Context</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#ab420b672954fd0fc80a22da36dd9cc52">llvm::DIExpression::convertToUndefExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="#ae9748fb2e4d41aaa8ac80d00b2becc52">handleDebugValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp/#a434449d5a0f4b334aca9163b13b6286ba02b848adda8d7d33a2b25d87dbef1d75">Poison</a>.</p>


<p>Referenced by <a href="#a196df57d98a1307c0ced654a8e1d202b">visitDbgInfo</a>.</p>

</div>
</div>

### init() {#aadd87a22e72622eccf46ce5525d1976c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::init (<a href="/web-llvm/docs/api/classes/llvm/gcfunctioninfo">GCFunctionInfo</a> * gfi, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> * BatchAA, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * li)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1085 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a74b87337454200d4d33f80c4663dc5e5">aa</a>, <a href="#acb6015cccbf35f2e27ca3367cda3cdec">AC</a>, <a href="#a23f8a52e7e457d67b67aa86541f55c17">BatchAA</a>, <a href="#ac536e4b59b1e85317cea0b32d47752ef">Context</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="#a9b4db8b8082660004fda0c282da0ff0a">GFI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa9ef2dbd1b7ce921093f7d4a7bd4cc5c">llvm::isAssignmentTrackingEnabled</a>, <a href="#ae283c81e2135fac41f1896dd39c4cc40">LibInfo</a>, <a href="#a53319e45ea515329480adf13f0098b4b">LPadToCallSiteMap</a> and <a href="#a346bf6c4d7fca3ebce554ec2cdd80e87">SL</a>.</p>

</div>
</div>

### isExportableFromCurrentBlock() {#ae3df768f340538afba57a5eaeb0ba277}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SelectionDAGBuilder::isExportableFromCurrentBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * FromBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 2368 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ad10e64e191507974af84a4ea069a9e36">FuncInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4ec05121d4b54b3691ad6203e78ff54e">llvm::BasicBlock::isEntryBlock</a>.</p>


<p>Referenced by <a href="#a41a8f459a2dcfcfc624394df6b432689">EmitBranchForMergedCondition</a>.</p>

</div>
</div>

### LowerAsSTATEPOINT() {#afe97e2bc5bd74272ca1b54da1fb30e06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SelectionDAGBuilder::LowerAsSTATEPOINT (<a href="/web-llvm/docs/api/structs/llvm/selectiondagbuilder/statepointloweringinfo">StatepointLoweringInfo</a> &amp; SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower <span class="doxyComputerOutput">SLI</span> into a STATEPOINT instruction.</p>

<p>Declaration at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 707 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a53408c95a7bfb5443b43fb2134c3eb23">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::count</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="#aa5254258c6a479f86e6ecfc4dcdd7a5e">ExportFromCurrentBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="#ad10e64e191507974af84a4ea069a9e36">FuncInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aee46c58568939eaeaa37ea6001bf432e">llvm::ISD::GC_TRANSITION_END</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71d133366c40437e06936626b32ba6d8">llvm::ISD::GC_TRANSITION_START</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abba0f0474eb4e32d1ed7b6dfdb0d5140a9db1ed1dc0fe1fc6b917ab0430b7844c">llvm::GCTransition</a>, <a href="#aef34360e8bb4bdecf3fd6345ff504f81">getControlRoot</a>, <a href="/web-llvm/docs/api/structs/llvm/regsforvalue/#adf93dd21d49c19700e980b15f19cb7d7">llvm::RegsForValue::getCopyToRegs</a>, <a href="#abb661ad9d4e5fd0d8806106e9b4d7256">getCurSDLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/gcrelocateinst/#ae587391ac557593d998dbca4e62f0dab">llvm::GCRelocateInst::getDerivedPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ae1fa8ded9bce6f8321a69e99e41a473c">llvm::SDNode::getGluedNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7f311fcc2415eee3cb3694013b985304">llvm::SDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7f06dbaee5fa2b239de548d0a775b25b">llvm::SDNode::getNumValues</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="#aa3e946c1fc678a70e849244389bd929a">getRoot</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="#a025adb087cac36e2cd504a33e8cb749d">getValue</a>, <a href="#a9b4db8b8082660004fda0c282da0ff0a">GFI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#af8947d9c8165e82094241d319758e0c5">lowerCallFromStatepointLoweringInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abba0f0474eb4e32d1ed7b6dfdb0d5140a003ec4f8bc6c6d93aa1801253e494916">llvm::MaskAll</a>, <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/statepointrelocationrecord/#ae85ec708fd4e537d4b331ce7f94acb2cae1c6c7a77fab355eb08576b3bd29b924">llvm::FunctionLoweringInfo::StatepointRelocationRecord::NoRelocate</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#aee6bd1fd282469b3476efce4b707f09a">llvm::SDNode::op_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ae499cc99d4fe44d343ca9ac6a2ae8845">llvm::SDNode::op_end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a720a77a05d768dabfa739d154c11ddfd">pushStackMapConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/statepointrelocationrecord/#ae85ec708fd4e537d4b331ce7f94acb2cafcf3e806047173bc7c8581b355375870">llvm::FunctionLoweringInfo::StatepointRelocationRecord::SDValueNode</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/statepointrelocationrecord/#ae85ec708fd4e537d4b331ce7f94acb2ca4e2303faf0f163fb7a4af33f778884e8">llvm::FunctionLoweringInfo::StatepointRelocationRecord::Spill</a>, <a href="#a77cbbcab1440ac5ef835e1a3d3f6c74e">StatepointLowering</a> and <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/statepointrelocationrecord/#ae85ec708fd4e537d4b331ce7f94acb2cad7321692f596ba5573d414ce3452c26f">llvm::FunctionLoweringInfo::StatepointRelocationRecord::VReg</a>.</p>


<p>Referenced by <a href="#a57ee991742a8027b5ef002c616a6b9fd">LowerCallSiteWithDeoptBundleImpl</a> and <a href="#a32cff45e4cfd323ecc3896adcb08c2a9">LowerStatepoint</a>.</p>

</div>
</div>

### LowerCallSiteWithDeoptBundle() {#a475d759da0893604f08519960a12d297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::LowerCallSiteWithDeoptBundle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Callee, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * EHPadBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1174 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>Reference <a href="#a57ee991742a8027b5ef002c616a6b9fd">LowerCallSiteWithDeoptBundleImpl</a>.</p>

</div>
</div>

### LowerCallSiteWithDeoptBundleImpl() {#a57ee991742a8027b5ef002c616a6b9fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::LowerCallSiteWithDeoptBundleImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Callee, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * EHPadBB, bool VarArgDisallowed, bool ForceVoidReturnTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1140 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/statepointdirectives/#ac6c1765b4a9a319dac2aad8cdc622ef2">llvm::StatepointDirectives::DeoptBundleStatepointID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#afe97e2bc5bd74272ca1b54da1fb30e06">LowerAsSTATEPOINT</a>, <a href="#a3756185351596750edbb4790d9923eea">lowerRangeToAssertZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abba0f0474eb4e32d1ed7b6dfdb0d5140a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9ca3f6df86c6efab701ade7abbc3134c25a">llvm::LLVMContext::OB_deopt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a830906f493a6d5c69ac5a94675c657fb">llvm::parseStatepointDirectivesFromAttrs</a>, <a href="#a8a8a4b167d0244a5c34b6819dd3d5c56">populateCallLoweringInfo</a> and <a href="#ad8368fe85feec440623e9558e100f357">setValue</a>.</p>


<p>Referenced by <a href="#a475d759da0893604f08519960a12d297">LowerCallSiteWithDeoptBundle</a> and <a href="#a459873061a3fed537ca026ddaffe57ed">LowerDeoptimizeCall</a>.</p>

</div>
</div>

### LowerCallSiteWithPtrAuthBundle() {#ac9742261cd7ee88cb99ec122fc61f5e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::LowerCallSiteWithPtrAuthBundle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * EHPadBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 9604 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a8d13199cbf4d080d3b5dcf330dad5d2c">llvm::CallBase::getCalledOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a23ab5f34fb7b9476d45da0102ecbfae6">llvm::CallBase::getOperandBundle</a>, <a href="#a025adb087cac36e2cd504a33e8cb749d">getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a50426b12f4acb3d9f74d0778948e9597">llvm::CallBase::isMustTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#af2c6594a90c163f7347396d39e094abe">llvm::CallBase::isTailCall</a> and <a href="#a2b4653fa0c302d9cbe4e7839d711e76a">LowerCallTo</a>.</p>

</div>
</div>

### LowerCallTo() {#a2b4653fa0c302d9cbe4e7839d711e76a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::LowerCallTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Callee, bool IsTailCall, bool IsMustTailCall, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * EHPadBB=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetlowering/ptrauthinfo">TargetLowering::PtrAuthInfo</a> * PAI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 8859 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#a4fb513d744ca72275932b2c7003f16f6">llvm::CallBase::arg_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac0f11b96f81b2769dd23d028e3189075">llvm::CallBase::arg_end</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#adde2ea00dd2613ee41bfe91908e4e68e">llvm::CallBase::arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a652220e0fde7043b474f1d6a85cd0452">llvm::CallBase::countOperandBundlesOfType</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ae76ac9826f02f95aae34e845ac110244">llvm::TargetLowering::CallLoweringInfo::DAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a3b6fcbb7bdd8ae29e8af4cd38bce7a40">llvm::TargetLowering::CallLoweringInfo::DL</a>, <a href="#ad10e64e191507974af84a4ea069a9e36">FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a155ffe05aa8e1991b486a7f96ff2e828">llvm::SelectionDAG::getCopyToReg</a>, <a href="#abb661ad9d4e5fd0d8806106e9b4d7256">getCurSDLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac3c35bd078a268a207f607d0f57dadba">llvm::CallBase::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a23ab5f34fb7b9476d45da0102ecbfae6">llvm::CallBase::getOperandBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="#aa3e946c1fc678a70e849244389bd929a">getRoot</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a025adb087cac36e2cd504a33e8cb749d">getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a58a3dfbca60dd5811b252fca05b254d3">llvm::TargetLowering::CallLoweringInfo::InVals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac32c9ebab7dfd3db749d0ab5e6e58b3e">llvm::CallBase::isConvergent</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a574efc7d85ff014d5f15e077f3c82e6b">llvm::CallBase::isIndirectCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2fadbd4626ccfbf3d2cabd27003d597">llvm::isInTailCallPosition</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="#ab29b69c993fbb9a4b9d28c3600df005d">lowerInvokable</a>, <a href="#a3756185351596750edbb4790d9923eea">lowerRangeToAssertZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9ca7ccabf0c8cf51c267c1e0cd9a66261d8">llvm::LLVMContext::OB_cfguardtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9cacdf8ff962c6163eb5fae1f9b2fb5142a">llvm::LLVMContext::OB_convergencectrl</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9cadb925bc2eb2c117b3ec0b76d1e267127">llvm::LLVMContext::OB_kcfi</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9ca1ad9f9f842cf7ba87b3db9b1d8870b9f">llvm::LLVMContext::OB_preallocated</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#af85f2971df75297dfac1455dc7211b11">llvm::TargetLowering::CallLoweringInfo::setCallee</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a248c253e17dbe9b14e68b192cf3962b5">llvm::TargetLowering::CallLoweringInfo::setCFIType</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ae8c9a19c4e49854df72efd6a33299ca6">llvm::TargetLowering::CallLoweringInfo::setChain</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ac08f737dbe6416c568d445a0fb062553">llvm::TargetLowering::CallLoweringInfo::setConvergenceControlToken</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a03ba2eacb6adc820c314cd1455f1c504">llvm::TargetLowering::CallLoweringInfo::setConvergent</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#aa05efb86ccf079a618d7ccc2d0984510">llvm::TargetLowering::CallLoweringInfo::setDebugLoc</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ab8d48ba57acd45e77101777a817ac8ce">llvm::TargetLowering::CallLoweringInfo::setIsPreallocated</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#af34cfef3c11acfa3c1f2437f25984765">llvm::TargetLowering::CallLoweringInfo::setPtrAuth</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#aa8b90e2248ac4afd696fe04d0363dba4">llvm::TargetLowering::CallLoweringInfo::setTailCall</a>, <a href="#ad8368fe85feec440623e9558e100f357">setValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0160cf5c2cae2754444db153907790a2">llvm::TargetLowering::supportKCFIBundles</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a12cbb115116dd32eb6c32ba191761093">llvm::TargetLowering::supportPtrAuthBundles</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a17694ad399c24aae0d2c0ecfbecfea5a">llvm::TargetLowering::supportSwiftError</a> and <a href="#a4ac2cfd1783912207570d7cce74a3ea2">SwiftError</a>.</p>


<p>Referenced by <a href="#ac9742261cd7ee88cb99ec122fc61f5e8">LowerCallSiteWithPtrAuthBundle</a>.</p>

</div>
</div>

### LowerDeoptimizeCall() {#a459873061a3fed537ca026ddaffe57ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::LowerDeoptimizeCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1302 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>References <a href="#ad997f08bfd4680a697130632badf740e">DAG</a> and <a href="#a57ee991742a8027b5ef002c616a6b9fd">LowerCallSiteWithDeoptBundleImpl</a>.</p>

</div>
</div>

### LowerDeoptimizingReturn() {#acf29bbf079b2610d2c8481212261fc49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::LowerDeoptimizingReturn ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 487 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1315 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>References <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="#abb661ad9d4e5fd0d8806106e9b4d7256">getCurSDLoc</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac5fb8808f3dcb9f0a83f1fc2e7747485">llvm::ISD::TRAP</a>.</p>

</div>
</div>

### lowerInvokable() {#ab29b69c993fbb9a4b9d28c3600df005d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; SDValue, SDValue &gt; SelectionDAGBuilder::lowerInvokable (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">TargetLowering::CallLoweringInfo</a> &amp; CLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * EHPadBB=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 8818 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#acd79db0f7d45129e8af1258541861ef8">llvm::TargetLowering::CallLoweringInfo::CB</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="#aef34360e8bb4bdecf3fd6345ff504f81">getControlRoot</a>, <a href="#aa3e946c1fc678a70e849244389bd929a">getRoot</a>, <a href="#a39e446f1647e793791c33d0d2412d088">HasTailCall</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a283b7df55a414e3185b56aeea1ec7ee7">llvm::TargetLowering::CallLoweringInfo::IsTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aabd42a6eddc3daec9153679b54f79300">llvm::TargetLowering::LowerCallTo</a> and <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ae8c9a19c4e49854df72efd6a33299ca6">llvm::TargetLowering::CallLoweringInfo::setChain</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#af8947d9c8165e82094241d319758e0c5">lowerCallFromStatepointLoweringInfo</a> and <a href="#a2b4653fa0c302d9cbe4e7839d711e76a">LowerCallTo</a>.</p>

</div>
</div>

### lowerRangeToAssertZExt() {#a3756185351596750edbb4790d9923eea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SelectionDAGBuilder::lowerRangeToAssertZExt (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 10541 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af23301e60475124fd80a2cb51f6ba863">llvm::ISD::AssertZext</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="#abb661ad9d4e5fd0d8806106e9b4d7256">getCurSDLoc</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a752372e170e4e7c595bf8810bb52adf2">llvm::EVT::getIntegerVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a407852423447c9c318189650976659fb">getRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a8bb58e9357b2f891f98fbbce353155efa03b0c213d98b3b6e73e3e0e4e0bdf1bf">llvm::IntegerType::MIN_INT_BITS</a> and <a href="#a346bf6c4d7fca3ebce554ec2cdd80e87">SL</a>.</p>


<p>Referenced by <a href="#a57ee991742a8027b5ef002c616a6b9fd">LowerCallSiteWithDeoptBundleImpl</a> and <a href="#a2b4653fa0c302d9cbe4e7839d711e76a">LowerCallTo</a>.</p>

</div>
</div>

### LowerStatepoint() {#a32cff45e4cfd323ecc3896adcb08c2a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::LowerStatepoint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst">GCStatepointInst</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * EHPadBB=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1014 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca4f42667edde6e9cb80cfae6361e5e76a">llvm::CallingConv::AnyReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#a603a5bfcd809283f948cbf101851c173a4bd61c6f1d2d253230fb6a6cca78d8aa">llvm::GCStatepointInst::CallArgsBeginPos</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="#ad10e64e191507974af84a4ea069a9e36">FuncInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/regsforvalue/#adf93dd21d49c19700e980b15f19cb7d7">llvm::RegsForValue::getCopyToRegs</a>, <a href="#abb661ad9d4e5fd0d8806106e9b4d7256">getCurSDLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#ab1af1f498b4d814ee68810a03fbe28a7">getGCResultLocality</a>, <a href="#a025adb087cac36e2cd504a33e8cb749d">getValue</a>, <a href="#a9b4db8b8082660004fda0c282da0ff0a">GFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a720af7e7f23150174952da03d216341a">isGCValue</a>, <a href="#afe97e2bc5bd74272ca1b54da1fb30e06">LowerAsSTATEPOINT</a>, <a href="#a8a8a4b167d0244a5c34b6819dd3d5c56">populateCallLoweringInfo</a> and <a href="#ad8368fe85feec440623e9558e100f357">setValue</a>.</p>

</div>
</div>

### populateCallLoweringInfo() {#a8a8a4b167d0244a5c34b6819dd3d5c56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::populateCallLoweringInfo (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">TargetLowering::CallLoweringInfo</a> &amp; CLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call, unsigned ArgIdx, unsigned NumArgs, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Callee, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ReturnTy, <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> RetAttrs, bool IsPatchPoint)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Populate a CallLowerinInfo (into <span class="doxyComputerOutput">CLI</span>) based on the properties of the call being lowered.</p>


<p>This is a helper for lowering intrinsics that follow a target calling convention or require stack pointer adjustment. Only a subset of the intrinsic's operands need to participate in the calling convention.</p>


<p>Declaration at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 10582 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abb661ad9d4e5fd0d8806106e9b4d7256">getCurSDLoc</a>, <a href="#aa3e946c1fc678a70e849244389bd929a">getRoot</a>, <a href="#a025adb087cac36e2cd504a33e8cb749d">getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9ca1ad9f9f842cf7ba87b3db9b1d8870b9f">llvm::LLVMContext::OB_preallocated</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#af85f2971df75297dfac1455dc7211b11">llvm::TargetLowering::CallLoweringInfo::setCallee</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ae8c9a19c4e49854df72efd6a33299ca6">llvm::TargetLowering::CallLoweringInfo::setChain</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#aa05efb86ccf079a618d7ccc2d0984510">llvm::TargetLowering::CallLoweringInfo::setDebugLoc</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a92da69e2625a91ae468da5ed229a3a93">llvm::TargetLowering::CallLoweringInfo::setDiscardResult</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a982d72dbe5b2fdba331ff1d7099cb22c">llvm::TargetLowering::CallLoweringInfo::setIsPatchPoint</a> and <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ab8d48ba57acd45e77101777a817ac8ce">llvm::TargetLowering::CallLoweringInfo::setIsPreallocated</a>.</p>


<p>Referenced by <a href="#a57ee991742a8027b5ef002c616a6b9fd">LowerCallSiteWithDeoptBundleImpl</a> and <a href="#a32cff45e4cfd323ecc3896adcb08c2a9">LowerStatepoint</a>.</p>

</div>
</div>

### resolveDanglingDebugInfo() {#ab898c0fc6a2159b032a398271add3927}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::resolveDanglingDebugInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If we saw an earlier dbg_value referring to V, generate the debug data structures now that we've seen its definition.</p>

<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1448 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a68cdc2666693dffb9173a9dffee11ab8">llvm::SDValue::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a2c7563253850e555f36f44d91157e5bb">llvm::SDNode::getIROrder</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable/#ac8c4cb4dde7067286d3e3ce80bf77224">llvm::DILocalVariable::isValidLocationForIntrinsic</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#ac0b87e85b015d15077a7d9432c500df3">getCopyFromRegs</a>, <a href="#a4ad02593716678add54090c344959750">getNonRegisterValue</a> and <a href="#a025adb087cac36e2cd504a33e8cb749d">getValue</a>.</p>

</div>
</div>

### resolveOrClearDbgInfo() {#ab0535176e89ed7e0647a533aa033bb34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::resolveOrClearDbgInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Evict any dangling debug information, attempting to salvage it first.</p>

<p>Declaration at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1716 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="#a1b90604db120716e786d9d33babc3edd">clearDanglingDebugInfo</a> and <a href="#a8cf671ed90e3e80717aaa6318b24794c">salvageUnresolvedDbgValue</a>.</p>

</div>
</div>

### salvageUnresolvedDbgValue() {#a8cf671ed90e3e80717aaa6318b24794c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::salvageUnresolvedDbgValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, DanglingDebugInfo &amp; DDI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For the given dangling debuginfo record, perform last-ditch efforts to resolve the debuginfo to something that is represented in this DAG.</p>


<p>If this cannot be done, produce an Undef debug value record.</p>


<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1502 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a5f48305fa7d23161515c94bca7c2beb6">llvm::DIExpression::appendOpsToArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a9aef6cbb464a57070a26cf422b979df9">llvm::DIExpression::getNumLocationOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#ae9748fb2e4d41aaa8ac80d00b2becc52">handleDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a99356c6b92999b95181b5d79c03868ee">llvm::salvageDebugInfoImpl</a>.</p>


<p>Referenced by <a href="#ac08d1b312ae9756038394d6b9568f383">dropDanglingDebugInfo</a> and <a href="#ab0535176e89ed7e0647a533aa033bb34">resolveOrClearDbgInfo</a>.</p>

</div>
</div>

### setUnusedArgValue() {#a6b0040c5b706355fa56842358cf0cbe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::setUnusedArgValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> NewN)</td>
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



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### setValue() {#ad8368fe85feec440623e9558e100f357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::setValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> NewN)</td>
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



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a57ee991742a8027b5ef002c616a6b9fd">LowerCallSiteWithDeoptBundleImpl</a>, <a href="#a2b4653fa0c302d9cbe4e7839d711e76a">LowerCallTo</a>, <a href="#a32cff45e4cfd323ecc3896adcb08c2a9">LowerStatepoint</a> and <a href="#afe7d9f31d3030277242731ccf43478c0">visitSwitchCase</a>.</p>

</div>
</div>

### ShouldEmitAsBranches() {#a3b3bd2c89ff35a733d365b34c2dca4fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SelectionDAGBuilder::ShouldEmitAsBranches (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock">SwitchCG::CaseBlock</a> &gt; &amp; Cases)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the set of cases should be emitted as a series of branches, return true.</p>


<p>If we should emit this as a bunch of and/or'd together conditions, return false.</p>


<p>Declaration at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 2757 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ae2e6a5e32087b9f65bd51585a6a5afb4">llvm::ISD::SETEQ</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a>.</p>

</div>
</div>

### shouldKeepJumpConditionsTogether() {#a732bd4cf41862afa6092c1648c02e256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SelectionDAGBuilder::shouldKeepJumpConditionsTogether (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; FuncInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> Opc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Lhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Rhs, <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/condmergingparams">TargetLoweringBase::CondMergingParams</a> Params)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 2512 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/condmergingparams/#a11b4b370b808f19228d93c4e8b6dc78f">llvm::TargetLoweringBase::CondMergingParams::BaseCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a9e90083bd35fdc6271e1c0060a6290d5">collectInstructionDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a8757ce7071547a0410c82cc096b1ec9a">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::contains</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ad10e64e191507974af84a4ea069a9e36">FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a89d17091515cc3617c0901a05308f27b">llvm::TargetMachine::getTargetTransformInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo/#aa2da8547348736e285afd8af9093a83d">llvm::BranchProbabilityInfo::isEdgeHot</a>, <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/condmergingparams/#a1faa2635f447e7af00d39324d5fbb099">llvm::TargetLoweringBase::CondMergingParams::LikelyBias</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4d5e16cbde22f5e6f007940d57a428fd">llvm::SelectionDAG::MaxRecursionDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba81b2c6f1f1e13e4a575e6d1c8b29b6e1">llvm::TargetTransformInfo::TCK_Latency</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#ab23f183e7947aaf3caad7960217f843c">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::try_emplace</a> and <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/condmergingparams/#a53271697575a0d9c0739b723521c4125">llvm::TargetLoweringBase::CondMergingParams::UnlikelyBias</a>.</p>

</div>
</div>

### UpdateSplitBlock() {#af6e9499206c6a56801d70a567fc8862a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::UpdateSplitBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * First, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Last)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When an MBB was split during scheduling, update the references that need to refer to the last resulting block.</p>

<p>Declaration at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3510 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/bittestblock/#aa7fe2ac4f88fa09c19520aa9323be2f7">llvm::SwitchCG::BitTestBlock::Parent</a> and <a href="#a346bf6c4d7fca3ebce554ec2cdd80e87">SL</a>.</p>

</div>
</div>

### visit() {#abbbfefd79a5b3d1b4ea8d8383fd01af5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1317 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac30ce0e7a5759d1e0bb5bf891e88662b">CopyToExportRegsIfNeeded</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#a39e446f1647e793791c33d0d2412d088">HasTailCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#abbbfefd79a5b3d1b4ea8d8383fd01af5">visit</a> and <a href="#a196df57d98a1307c0ced654a8e1d202b">visitDbgInfo</a>.</p>


<p>Referenced by <a href="#afe3b2bbac4396d088da5c91f77754843">getValueImpl</a> and <a href="#abbbfefd79a5b3d1b4ea8d8383fd01af5">visit</a>.</p>

</div>
</div>

### visit() {#afa8e93a6e743cba008f0aa78ab4c653c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visit (unsigned Opcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1372 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### visitBitTestCase() {#a7a7b439d546506d56e2cdc61a1ac1d06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitBitTestCase (<a href="/web-llvm/docs/api/structs/llvm/switchcg/bittestblock">SwitchCG::BitTestBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * NextMBB, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> BranchProbToNext, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/structs/llvm/switchcg/bittestcase">SwitchCG::BitTestCase</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SwitchBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>visitBitTestCase - this function produces one "bit test"</p>

<p>Declaration at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3264 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5be7fb35e0f523af6c939fba303403df">llvm::ISD::BR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8167e4f6fa1bfb30f074ba620b81782">llvm::ISD::BRCOND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a239abca11deebf2731206dd41cf43c0e">llvm::countr_one</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="#aef34360e8bb4bdecf3fd6345ff504f81">getControlRoot</a>, <a href="#abb661ad9d4e5fd0d8806106e9b4d7256">getCurSDLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a76483b2b4498079d3778c57326c39e99">llvm::TargetLoweringBase::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a0c54da24de983d197068425e718fb607">llvm::MachineBasicBlock::normalizeSuccProbs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/bittestblock/#af7189e175bd7c3bc39ab17be9cd91a4c">llvm::SwitchCG::BitTestBlock::Range</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/bittestblock/#a4279ed956f8d18d3db442c32edeacbbc">llvm::SwitchCG::BitTestBlock::RegVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ae2e6a5e32087b9f65bd51585a6a5afb4">llvm::ISD::SETEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>.</p>

</div>
</div>

### visitBitTestHeader() {#a31f9f0db1bb0b321286db70b58fb001e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitBitTestHeader (<a href="/web-llvm/docs/api/structs/llvm/switchcg/bittestblock">SwitchCG::BitTestBlock</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SwitchBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>visitBitTestHeader - This function emits necessary code to produce value suitable for "bit tests"</p>

<p>Declaration at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3202 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5be7fb35e0f523af6c939fba303403df">llvm::ISD::BR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8167e4f6fa1bfb30f074ba620b81782">llvm::ISD::BRCOND</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="#ad10e64e191507974af84a4ea069a9e36">FuncInfo</a>, <a href="#aef34360e8bb4bdecf3fd6345ff504f81">getControlRoot</a>, <a href="#abb661ad9d4e5fd0d8806106e9b4d7256">getCurSDLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a76483b2b4498079d3778c57326c39e99">llvm::TargetLoweringBase::getSetCCResultType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="#a025adb087cac36e2cd504a33e8cb749d">getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a995470163b6d76695cba5bc8dfb529">llvm::isUIntN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a0c54da24de983d197068425e718fb607">llvm::MachineBasicBlock::normalizeSuccProbs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a292be4a9782030bfad637581d25a5897">llvm::ISD::SETUGT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>.</p>

</div>
</div>

### visitDbgInfo() {#a196df57d98a1307c0ced654a8e1d202b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitDbgInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1229 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="#a13b6c3ad0bdee051eda42dc7c8a1f12b">addDanglingDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca2709046ed364cc54b91f908e85e512ed">llvm::DbgVariableRecord::Declare</a>, <a href="#ac08d1b312ae9756038394d6b9568f383">dropDanglingDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#ad10e64e191507974af84a4ea069a9e36">FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a3a0f4e00c3f6345c52c6acd178b3fca3">llvm::DbgRecord::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a8ec5a479378113fc24b647afa2f06ee5">llvm::DbgVariableRecord::getExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a1adb590f8f0ceed777898888ed5db7ac">llvm::DbgVariableRecord::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#aa774c62045e74bb457b32713c0670696">llvm::DbgVariableRecord::getVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a99dac64e3a954ffbcbf1fc6726a743a2">llvm::DbgVariableRecord::getVariableLocationOp</a>, <a href="#a6571e1b07bfb1d4c5b1e832fdac355a1">handleDebugDeclare</a>, <a href="#ae9748fb2e4d41aaa8ac80d00b2becc52">handleDebugValue</a>, <a href="#ac42eef26cc4185a8932bc59a94dc5d16">handleKillDebugValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#af9c8103c773f2193dafee38239051d7b">llvm::DbgVariableRecord::hasArgList</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#afd3574da4a2a86d1540dbdfcef171dd8">llvm::DbgVariableRecord::location_ops</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#abbbfefd79a5b3d1b4ea8d8383fd01af5">visit</a>.</p>

</div>
</div>

### visitJumpTable() {#ac730a866bfd17ffc004cc3a0e85c3770}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitJumpTable (<a href="/web-llvm/docs/api/structs/llvm/switchcg/jumptable">SwitchCG::JumpTable</a> &amp; JT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>visitJumpTable - Emit <a href="/web-llvm/docs/api/namespaces/llvm/jumptable">JumpTable</a> node in the current MBB</p>

<p>Declaration at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 2988 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a716d19ebad1927a2e8dd5fe3f951f882">llvm::ISD::BR_JT</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a> and <a href="#aef34360e8bb4bdecf3fd6345ff504f81">getControlRoot</a>.</p>

</div>
</div>

### visitJumpTableHeader() {#ac85aa2ebc935e3c87ec7f9e54183cddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitJumpTableHeader (<a href="/web-llvm/docs/api/structs/llvm/switchcg/jumptable">SwitchCG::JumpTable</a> &amp; JT, <a href="/web-llvm/docs/api/structs/llvm/switchcg/jumptableheader">SwitchCG::JumpTableHeader</a> &amp; JTH, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SwitchBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>visitJumpTableHeader - This function emits necessary code to produce index in the <a href="/web-llvm/docs/api/namespaces/llvm/jumptable">JumpTable</a> from switch case.</p>

<p>Declaration at line 532 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3002 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5be7fb35e0f523af6c939fba303403df">llvm::ISD::BR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8167e4f6fa1bfb30f074ba620b81782">llvm::ISD::BRCOND</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/jumptableheader/#ad62543fa4b455b7b44115597b3f44e45">llvm::SwitchCG::JumpTableHeader::FallthroughUnreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/jumptableheader/#aa26ad8f7cc9ed4d3050176cc117fe152">llvm::SwitchCG::JumpTableHeader::First</a>, <a href="#ad10e64e191507974af84a4ea069a9e36">FuncInfo</a>, <a href="#aef34360e8bb4bdecf3fd6345ff504f81">getControlRoot</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#af2c7c474fbd3717354a6297baa84a478">llvm::TargetLowering::getJumpTableRegTy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a76483b2b4498079d3778c57326c39e99">llvm::TargetLoweringBase::getSetCCResultType</a>, <a href="#a025adb087cac36e2cd504a33e8cb749d">getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/jumptableheader/#a1d65c943871802d749447457ab95fc04">llvm::SwitchCG::JumpTableHeader::Last</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a292be4a9782030bfad637581d25a5897">llvm::ISD::SETUGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a> and <a href="/web-llvm/docs/api/structs/llvm/switchcg/jumptableheader/#a743a893761acac5015cc238c259bd5ca">llvm::SwitchCG::JumpTableHeader::SValue</a>.</p>

</div>
</div>

### visitSPDescriptorFailure() {#afff13ac7b2e92fc0ad596603592298bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitSPDescriptorFailure (<a href="/web-llvm/docs/api/classes/llvm/stackprotectordescriptor">StackProtectorDescriptor</a> &amp; SPD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Codegen the failure basic block for a stack protector check.</p>


<p>A failure stack protector machine basic block consists simply of a call to __stack_chk_fail().</p>


<p>For a high level explanation of how this fits into the stack protector generation see the comment on the declaration of class <a href="/web-llvm/docs/api/classes/llvm/stackprotectordescriptor">StackProtectorDescriptor</a>.</p>


<p>Declaration at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3184 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="#abb661ad9d4e5fd0d8806106e9b4d7256">getCurSDLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ad4a2abb087afa577d8f4239b01acbea0">llvm::TargetLowering::makeLibCall</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#acd83fce25de1ac9f6c975135a8235c22">llvm::TargetOptions::NoTrapAfterNoreturn</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/makelibcalloptions/#a30d29fa3a2769f2ef75455683d7af795">llvm::TargetLowering::MakeLibCallOptions::setDiscardResult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac5fb8808f3dcb9f0a83f1fc2e7747485">llvm::ISD::TRAP</a> and <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#ae511cb5018c52294bcff10ccde3f6789">llvm::TargetOptions::TrapUnreachable</a>.</p>

</div>
</div>

### visitSPDescriptorParent() {#ae8662f747218aee8ddeb4cdfbd1435a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitSPDescriptorParent (<a href="/web-llvm/docs/api/classes/llvm/stackprotectordescriptor">StackProtectorDescriptor</a> &amp; SPD, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * ParentBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Codegen a new tail for a stack protector check ParentMBB which has had its tail spliced into a stack protector check success bb.</p>


<p>For a high level explanation of how this fits into the stack protector generation see the comment on the declaration of class <a href="/web-llvm/docs/api/classes/llvm/stackprotectordescriptor">StackProtectorDescriptor</a>.</p>


<p>Declaration at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3089 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5be7fb35e0f523af6c939fba303403df">llvm::ISD::BR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8167e4f6fa1bfb30f074ba620b81782">llvm::ISD::BRCOND</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a1ee0110a687cf5a9bdb9e8596d9ca3fb">llvm::TargetLowering::emitStackGuardXorFP</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>, <a href="#abb661ad9d4e5fd0d8806106e9b4d7256">getCurSDLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/stackprotectordescriptor/#a6dca6975019bcf560ab04e7756cbe3a2">llvm::StackProtectorDescriptor::getFailureMBB</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a0f49cd7f0f28bd9b7aaed4b5a0df02d6">getLoadStackGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a104d6154321899b53e40455e71d8e83a">llvm::FunctionType::getNumParams</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a1e415dc42f391c1d0cfcc1c28c00b2f4">llvm::FunctionType::getParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af0eff80945c732f4d52c764744d69f1a">llvm::TargetLoweringBase::getPointerMemTy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#ad65790aa94dd4678a1d339d8304e1965">llvm::FunctionType::getReturnType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a40e9675119de3bcd2fd05b549994a17d">llvm::TargetLoweringBase::getSDagStackGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a76483b2b4498079d3778c57326c39e99">llvm::TargetLoweringBase::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a5cc7ede2e4ce0498c628270ca97ed75c">llvm::TargetLoweringBase::getSSPStackGuardCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a5ee88eb786413b2cf541122aa749392c">llvm::MachineFrameInfo::getStackProtectorIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/stackprotectordescriptor/#a2aa77282a145eb011d595a554810d367">llvm::StackProtectorDescriptor::getSuccessMBB</a>, <a href="#a025adb087cac36e2cd504a33e8cb749d">getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aabd42a6eddc3daec9153679b54f79300">llvm::TargetLowering::LowerCallTo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda796891d6ca349b671fce24b6d01d77a8">llvm::MachineMemOperand::MOVolatile</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#af85f2971df75297dfac1455dc7211b11">llvm::TargetLowering::CallLoweringInfo::setCallee</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ae8c9a19c4e49854df72efd6a33299ca6">llvm::TargetLowering::CallLoweringInfo::setChain</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#aa05efb86ccf079a618d7ccc2d0984510">llvm::TargetLowering::CallLoweringInfo::setDebugLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ad2b27b633b21a362571660ad09273d52">llvm::TargetLowering::useLoadStackGuardNode</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a190effd8532e35fa84618634c54edc38">llvm::TargetLoweringBase::useStackGuardXorFP</a>.</p>

</div>
</div>

### visitSwitchCase() {#afe7d9f31d3030277242731ccf43478c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitSwitchCase (<a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock">SwitchCG::CaseBlock</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SwitchBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>visitSwitchCase - Emits the necessary code to represent a single node in the binary search tree resulting from lowering a switch instruction.</p>

<p>Declaration at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 2892 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5be7fb35e0f523af6c939fba303403df">llvm::ISD::BR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8167e4f6fa1bfb30f074ba620b81782">llvm::ISD::BRCOND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock/#aed88926c7c267de324ad1fb3849711da">llvm::SwitchCG::CaseBlock::CC</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock/#a8c69b42db9fbec24257dd3f4991dcc45">llvm::SwitchCG::CaseBlock::CmpLHS</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock/#aac82e73a81c735151477cce79e665ded">llvm::SwitchCG::CaseBlock::CmpMHS</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock/#a38cbab750fe1c9367b0b60d1fc5b93b3">llvm::SwitchCG::CaseBlock::CmpRHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="#ad997f08bfd4680a697130632badf740e">DAG</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock/#afa78f50d45ebf96fcdafc6566a3d4951">llvm::SwitchCG::CaseBlock::DL</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock/#a8b3b98f6c3852ce830744ceed0aafd63">llvm::SwitchCG::CaseBlock::FalseBB</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock/#a3cab00e92ff09b90369ee038ef5149cf">llvm::SwitchCG::CaseBlock::FalseProb</a>, <a href="#aef34360e8bb4bdecf3fd6345ff504f81">getControlRoot</a>, <a href="#abb661ad9d4e5fd0d8806106e9b4d7256">getCurSDLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a02b5aaf4357ae931647439e312a034bc">llvm::TargetLoweringBase::getMemValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a025adb087cac36e2cd504a33e8cb749d">getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a7df34dbf636f2fbbb00f2b86eccdb1eb">High</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock/#aa7e0d0a0add71615292568516d513794">llvm::SwitchCG::CaseBlock::IsUnpredictable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05609d049bfe3c5c2f64711566131a86a28d0edd045e05cf5af64e35ae0c4c6ef">llvm::Low</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a0c54da24de983d197068425e718fb607">llvm::MachineBasicBlock::normalizeSuccProbs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ae2e6a5e32087b9f65bd51585a6a5afb4">llvm::ISD::SETEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ab49f81c2ecbbff3d0fbe55dd46353774">llvm::ISD::SETLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a8e273eab0623ea5713aa5bcbdac2b16b">llvm::ISD::SETTRUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ac538f0b432df970cbaaf6b81d777c6a7">llvm::ISD::SETULE</a>, <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags/#a86f6742ee604f29556fb4b0b41131be2">llvm::SDNodeFlags::setUnpredictable</a>, <a href="#ad8368fe85feec440623e9558e100f357">setValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock/#a85dee301aa78d53f5a80ec7f8739bb00">llvm::SwitchCG::CaseBlock::TrueBB</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock/#a11ec00a8f98caffafaae61f79580d2ec">llvm::SwitchCG::CaseBlock::TrueProb</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addSuccessorWithProb() {#a21a6d7097a11dc947cd9ac7baf493f21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::addSuccessorWithProb (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Src, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Dst, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Prob=<a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a76e4454abb329dee28e8f525ddd1a210">BranchProbability::getUnknown</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 2411 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### EmitFuncArgumentDbgValue() {#aa2fb6a906e9481d4d2b0d23e1080fdd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SelectionDAGBuilder::EmitFuncArgumentDbgValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Variable, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DL, FuncArgumentDbgValueKind Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If V is an function argument then create corresponding DBG_VALUE machine instruction for it now.</p>


<p>If the <a href="/web-llvm/docs/api/classes/llvm/dbgvalueinst">DbgValueInst</a> is a dbg_value of a function argument, create the corresponding DBG_VALUE machine instruction for it now.</p>


<p>At the end of instruction selection, they will be inserted to the entry BB.</p>


<p>At the end of instruction selection, they will be inserted to the entry BB. We don't currently support this for variadic dbg_values, as they shouldn't appear for function arguments or in the prologue.</p>


<p>Declaration at line 691 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 6016 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### emitInlineAsmError() {#a2cbeefc4fb9eb7208567c7915772ff48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::emitInlineAsmError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Message)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 678 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 10483 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### getDbgValue() {#a29ea057ad9992694b82c73412792a8a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDDbgValue * SelectionDAGBuilder::getDbgValue (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Variable, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; dl, unsigned DbgSDNodeOrder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the appropriate <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a> based on N.</p>

<p>Declaration at line 704 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 6240 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### getEdgeProbability() {#ad62f157cdaa90ddefc8b872d3baca70c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability SelectionDAGBuilder::getEdgeProbability (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return branch probability calculated by <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> for IR blocks.</p>

<p>Declaration at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 2397 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### HandlePHINodesInSuccessorBlocks() {#ae2cdd05d95ff1f2b337ba7c5d697a9db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::HandlePHINodesInSuccessorBlocks (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * LLVMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle PHI nodes in successor blocks.</p>


<p>Emit code into the <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> to ensure constants are generated when needed. Remember the virtual registers that need to be added to the Machine PHI nodes as input. We cannot just directly add them, because expansion might result in multiple MBB's for one BB. As such, the start of the BB might correspond to a different MBB than the end.</p>


<p>Declaration at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 11967 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### lowerCallToExternalSymbol() {#a77764e03957bcd38a3d8e329e8fa5ab6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::lowerCallToExternalSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * FunctionName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lowers <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> to an external symbol.</p>

<p>Declaration at line 709 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 6286 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### lowerEndEH() {#ac5d7837fb8c70f654a30f8503691f12e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SelectionDAGBuilder::lowerEndEH (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/invokeinst">InvokeInst</a> * II, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * EHPadBB, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * BeginLabel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 713 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 8789 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### lowerStartEH() {#a23e8ca684730b4f9c9a3fbacbe374201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SelectionDAGBuilder::lowerStartEH (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * EHPadBB, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *&amp; BeginLabel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 711 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 8766 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### lowerWorkItem() {#a07a10f663868d19955f42e7148f41096}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::lowerWorkItem (<a href="/web-llvm/docs/api/structs/llvm/switchcg/switchworklistitem">SwitchCG::SwitchWorkListItem</a> W, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SwitchMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DefaultMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower W.</p>

<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 12064 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### NextBlock() {#a8e07ae57e561e845f07db0ba649f113f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * SelectionDAGBuilder::NextBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the next block after MBB, or nullptr if there is none.</p>

<p>Declaration at line 697 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 12044 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### peelDominantCaseCluster() {#a287e7e90f99384ce89643972e9e7929f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * SelectionDAGBuilder::peelDominantCaseCluster (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> &amp; SI, <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#a79baa30810b267c49d14b070a5a99110">SwitchCG::CaseClusterVector</a> &amp; Clusters, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> &amp; PeeledCaseProb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Peel the top probability case if it exceeds the threshold.</p>

<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 12398 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### printDDI() {#af0429f5362de4cf4b7d100c3193db49f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DanglingDebugInfo::Print llvm::SelectionDAGBuilder::printDDI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DanglingDebugInfo &amp; DDI)</td>
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

<p>Returns an object that defines <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;operator&lt;&lt;</span> for printing.</p>


<p>Usage example:</p>


<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### processIntegerCallValue() {#ac2e044dd48bb60701e130220d73dfc27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::processIntegerCallValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Value, bool IsSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the value for an instruction that produces an integer result, converting the type where necessary.</p>

<p>Declaration at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 9040 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### splitWorkItem() {#a14b40f90b6f3e0ef5f24460560ba0eb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::splitWorkItem (<a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#afa5b66c5260f307ec76bc6a21315b051">SwitchCG::SwitchWorkList</a> &amp; WorkList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/switchcg/switchworklistitem">SwitchCG::SwitchWorkListItem</a> &amp; W, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SwitchMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit comparison and split W into two subtrees.</p>

<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 12310 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### updateDAGForMaybeTailCall() {#a30f2f462034b588f7fefe18614b84f88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::updateDAGForMaybeTailCall (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> MaybeTC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the DAG and DAG builder with the relevant information after a new root node has been created which could be a tail call.</p>


<p>During lowering new call nodes can be created (such as memset, etc.).</p>


<p>Those will become new roots of the current DAG, but complications arise when they are tail calls. In such cases, the call lowering will update the root, but the builder still needs to know that a tail call has been lowered in order to avoid generating an additional return.</p>


<p>Declaration at line 701 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 12056 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### updateRoot() {#a1e38832b5d73e2220eb8870ff2abb0ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SelectionDAGBuilder::updateRoot (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Pending)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update root to include all chains from the Pending list.</p>

<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1117 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitAdd() {#af21eacff266ea1d0e67d8fe5e727b686}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
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



<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitAddrSpaceCast() {#a1ad0574a8accf1ca35ba31fc1576ae94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitAddrSpaceCast (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3979 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitAlloca() {#a45b8864f609a8a261482d8d4046ccb13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitAlloca (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 594 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 4460 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitAnd() {#a8b406d72675121b9649f809078680a6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitAnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
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



<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitAShr() {#a01a073ba73c0b424f9ebd1a19d8d8661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitAShr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
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



<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitAtomicCmpXchg() {#a594bf7b91bae39e766a86902a38fcb5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitAtomicCmpXchg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst">AtomicCmpXchgInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 5083 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitAtomicLoad() {#acc47700340531b4df27c9d959da97860}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitAtomicLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 615 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 5188 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitAtomicRMW() {#a9855415a865f8f2b8ad8d2b28cc1bd0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitAtomicRMW (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 602 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 5115 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitAtomicStore() {#ac881045cdf62679b06f514a2b1fa7b11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitAtomicStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 5224 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitBinary() {#a2fd0ba78aee5163c0b06f70f3f2dbee1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitBinary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I, unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3572 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitBinaryFloatCall() {#a51ce43dbac09a9facb22e8cbc421fdb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SelectionDAGBuilder::visitBinaryFloatCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I, unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See if we can lower a binary floating-point operation into an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> with the specified Opcode.</p>


<p>If so, return true and lower it. Otherwise return false, and it will be lowered like a normal call. The caller already checked that <span class="doxyComputerOutput">I</span> calls the appropriate <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> with a correct prototype.</p>


<p>Declaration at line 614 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 9318 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitBitCast() {#a4b49404226d2806ed7af4b723f29e18a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitBitCast (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 580 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3957 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitBr() {#a1b10a0cbbe1874a420a8bef129fb64ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitBr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 2784 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitCall() {#a7b987a656b8f13738504e7a0aa73b835}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 605 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 9334 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitCallBr() {#a0baecbe8c996f9625d3abff4954b7a78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitCallBr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbrinst">CallBrInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3420 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitCallBrLandingPad() {#aab9d1b68003c3098e1a59beac208d9d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitCallBrLandingPad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 540 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 12716 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitCatchPad() {#a7da9dfec0ff00e148d07dfbc281c5109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitCatchPad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/catchpadinst">CatchPadInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1970 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitCatchRet() {#a1ffeb9158761ced0f48521ec4301339b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitCatchRet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/catchreturninst">CatchReturnInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1983 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitCatchSwitch() {#a9d6eb93de27028cdb28d87075c1c59c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitCatchSwitch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst">CatchSwitchInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 2173 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitCleanupPad() {#a51667e5d76eead9755d11f008a4b788d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitCleanupPad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cleanuppadinst">CleanupPadInst</a> &amp; CPI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 2023 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitCleanupRet() {#adbd02f6436764b133fd32b91a1e49596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitCleanupRet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cleanupreturninst">CleanupReturnInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 2149 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitConstrainedFPIntrinsic() {#af190af13bec416448d92dcce55c068f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitConstrainedFPIntrinsic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constrainedfpintrinsic">ConstrainedFPIntrinsic</a> &amp; FPI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 8282 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitConvergenceControl() {#a919e259fc38a81f901c4957529fff05f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitConvergenceControl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I, unsigned Intrinsic)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower the call to the specified intrinsic function.</p>

<p>Declaration at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 6347 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitEntryValueDbgValue() {#ab4af6f4899b4c65d90e8a82dfa204f7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SelectionDAGBuilder::visitEntryValueDbgValue (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Values, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Variable, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DbgLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If DI is a debug value with an EntryValue expression, lower it using the corresponding physical register of the associated <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> value (guaranteed to exist by the verifier).</p>

<p>Declaration at line 624 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 6315 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitExtractElement() {#a9afd4051e157f8c91019b876c1c7a2e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitExtractElement (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 4005 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitExtractValue() {#a1200aa2f17c82db61df56d7f2113d5b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitExtractValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/extractvalueinst">ExtractValueInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 4263 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitFAdd() {#a43c4d28f58ce3a60b625477f598a83aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitFAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
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



<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitFCmp() {#a08de87011f15b96feaa35e64c153cbb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitFCmp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fcmpinst">FCmpInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3669 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitFDiv() {#afc0d033e09ed6f37ad9f8af32043f599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitFDiv (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
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



<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitFence() {#a319c223b1c5c2245a0d33c4ab7ccd74c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitFence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fenceinst">FenceInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 5174 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitFMul() {#aba32842f60d4a6198bc89767fbc1a842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitFMul (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
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



<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitFNeg() {#a7859c0692d54ad5306f6c7c5ce9d0546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitFNeg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
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



<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitFPExt() {#a63afe238f9c42d552956548b6c7762eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitFPExt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3887 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitFPToSI() {#aca25d8a2ea316cc6bc1344cdd2077212}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitFPToSI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3903 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitFPToUI() {#a9ca34d68fd2d3a67915c4011f406c68e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitFPToUI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 574 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3895 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitFPTrunc() {#aa97474525c7e7f9f0842f1ed4251bc5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitFPTrunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 572 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3876 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitFreeze() {#a7e27007fee27dc8aa8fa1518575eb386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitFreeze (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/freezeinst">FreezeInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 12624 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitFRem() {#ae90de1065de3deb0f5e418b4f0a44210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitFRem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
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



<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitFSub() {#ae710111f773443b543bde95634e429f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitFSub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
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



<p>Definition at line 551 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitGCRelocate() {#a80af9838047d9b5448e6ce6bd381b715}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitGCRelocate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcrelocateinst">GCRelocateInst</a> &amp; Relocate)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 656 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1207 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>

</div>
</div>

### visitGCResult() {#ac8ceffd32caf03cad4080929f373487c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitGCResult (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcresultinst">GCResultInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1181 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>

</div>
</div>

### visitGetElementPtr() {#a78500cfd5e3d7495b0bb997a162358bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitGetElementPtr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 4298 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitICmp() {#ac5597c935678f50910321b226f8d7f58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitICmp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3642 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitIndirectBr() {#ab9dbd7a4da7b71d125302169e429b710}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitIndirectBr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst">IndirectBrInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3523 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitInlineAsm() {#aecee217a9b6b3934ba569dacc4a6616c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitInlineAsm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * EHPadBB=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>visitInlineAsm - Handle a call to an <a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a> object.</p>

<p>Declaration at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 9941 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitInsertElement() {#a9335f601c1f67d5a1d40523c5c33024e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitInsertElement (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3994 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitInsertValue() {#a8a91a5a078dcb4818340526d7c76f92a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitInsertValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/insertvalueinst">InsertValueInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 4214 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitIntrinsicCall() {#a9eedf4e2f8a9b61b3b408b8c29bc9672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitIntrinsicCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I, unsigned Intrinsic)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower the call to the specified intrinsic function.</p>

<p>Declaration at line 627 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 6453 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitIntToPtr() {#afbe63fb4ba5a8abd8614dceeed4c024a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitIntToPtr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3945 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitInvoke() {#ad260c689c5d6b23a6d0c9ef62b07fda6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitInvoke (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/invokeinst">InvokeInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3321 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitLandingPad() {#a12894d1bc3486785ce48cae0dbb3eb12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitLandingPad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/landingpadinst">LandingPadInst</a> &amp; LP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3462 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitLoad() {#a8d7cea38f6895ae6d97d4c038b0f1bc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 4544 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitLoadFromSwiftError() {#ac10d1228801d9155ab522c0f816e1bc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitLoadFromSwiftError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 4679 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitLShr() {#a64ea76dd35ed35eaa176daddea1cbc80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitLShr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
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



<p>Definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitMaskedGather() {#ad873d634838bc135399f4b0c122f8fa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitMaskedGather (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 5032 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitMaskedLoad() {#a426dcdae1838725d2a7975cc94e2cfea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitMaskedLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I, bool IsExpanding=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 4963 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitMaskedScatter() {#a37f8dd258fcff12411a00b5256de1d3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitMaskedScatter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 4918 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitMaskedStore() {#aaa37c2080baa3610dba4ca82f803c699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitMaskedStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I, bool IsCompressing=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 4787 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitMemChrCall() {#a914053bf64f91a0da259ee1af952b487}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SelectionDAGBuilder::visitMemChrCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See if we can lower a memchr call into an optimized form.</p>


<p>If so, return true and lower it. Otherwise return false, and it will be lowered like a normal call. The caller already checked that <span class="doxyComputerOutput">I</span> calls the appropriate <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> with a correct prototype.</p>


<p>Declaration at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 9146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitMemCmpBCmpCall() {#a4998b62f0ad5edc534a95a566ce0ee06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SelectionDAGBuilder::visitMemCmpBCmpCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See if we can lower a memcmp/bcmp call into an optimized form.</p>


<p>If so, return true and lower it. Otherwise return false, and it will be lowered like a normal call. The caller already checked that <span class="doxyComputerOutput">I</span> calls the appropriate <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> with a correct prototype.</p>


<p>Declaration at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 9054 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitMemPCpyCall() {#a9c7acd0e7630a39734bbfa8635a3b697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SelectionDAGBuilder::visitMemPCpyCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See if we can lower a mempcpy call into an optimized form.</p>


<p>If so, return true and lower it. Otherwise return false, and it will be lowered like a normal call. The caller already checked that <span class="doxyComputerOutput">I</span> calls the appropriate <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> with a correct prototype.</p>


<p>Declaration at line 607 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 9170 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitMul() {#a52d2f236b9ce4436e4e970f35cb50752}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitMul (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
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



<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitOr() {#a5d571c48cdee414ac9b97eb13349bb69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitOr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
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



<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitPatchpoint() {#a2e718dd379024c5842af7f4b0a36d3ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitPatchpoint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * EHPadBB=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower llvm.experimental.patchpoint directly to its target opcode.</p>

<p>Declaration at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 10715 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitPHI() {#a5420fdf35c2238d3a4122dc4ba8a5b3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitPHI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1368 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitPtrToInt() {#aa6c3bf7162c871e0cc93034ab10db909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitPtrToInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3931 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitResume() {#a3cc665eafaf5bd4765d0f109348374bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitResume (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/resumeinst">ResumeInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3458 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitRet() {#a9aa12f54e1eb4339c69ebd8db8cbf052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitRet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/returninst">ReturnInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 2177 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitSDiv() {#a7b4f6a0a5ba8edf817dfe59012e8e95a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitSDiv (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3631 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitSelect() {#a8ef642ca35c19140020dd4b04eab0125}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitSelect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3696 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitSExt() {#a70f67c1a7b5b393926eb0e557d26517b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitSExt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3867 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitShift() {#a0da78cbe076521e7685505199b8e82bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitShift (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I, unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3592 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitShl() {#a1e08353d0bc4a5e3861796b17f6b8fed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitShl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
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



<p>Definition at line 563 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitShuffleVector() {#a038b93be769197be0fd79608d08e6388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitShuffleVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 4015 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitSIToFP() {#aad6be22335fd5d11a76fcae1ab7c3261}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitSIToFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3923 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitSRem() {#a99981b95d5c98336497c404752202cf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitSRem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
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



<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitStackmap() {#a20752020d6cb05c8120c966bd681d7b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitStackmap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower llvm.experimental.stackmap.</p>

<p>Declaration at line 652 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 10650 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitStepVector() {#af342c629f30c0910e4da9bdc7daff657}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitStepVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 12538 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitStore() {#a9310870a3dfe30f89db39b762065560c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 596 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 4712 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitStoreToSwiftError() {#aeaa1dfc323111fb7c292ad81160f8086}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitStoreToSwiftError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 4656 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitStrCmpCall() {#af4ee024ceff1e24676579d9d13a3f2a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SelectionDAGBuilder::visitStrCmpCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See if we can lower a strcmp call into an optimized form.</p>


<p>If so, return true and lower it, otherwise return false and it will be lowered like a normal call. The caller already checked that <span class="doxyComputerOutput">I</span> calls the appropriate <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> with a correct prototype.</p>


<p>Declaration at line 610 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 9232 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitStrCpyCall() {#a397e7dbad665bba3933f58b3fd48661f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SelectionDAGBuilder::visitStrCpyCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I, bool isStpcpy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See if we can lower a strcpy call into an optimized form.</p>


<p>If so, return true and lower it, otherwise return false and it will be lowered like a normal call. The caller already checked that <span class="doxyComputerOutput">I</span> calls the appropriate <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> with a correct prototype.</p>


<p>Declaration at line 609 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 9209 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitStrLenCall() {#aad6edde6e74cfca093a869153f5ead65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SelectionDAGBuilder::visitStrLenCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See if we can lower a strlen call into an optimized form.</p>


<p>If so, return true and lower it, otherwise return false and it will be lowered like a normal call. The caller already checked that <span class="doxyComputerOutput">I</span> calls the appropriate <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> with a correct prototype.</p>


<p>Declaration at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 9255 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitStrNLenCall() {#ad3a880857918dc26a5d91789c9f2f8d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SelectionDAGBuilder::visitStrNLenCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See if we can lower a strnlen call into an optimized form.</p>


<p>If so, return true and lower it, otherwise return false and it will be lowered like a normal call. The caller already checked that <span class="doxyComputerOutput">I</span> calls the appropriate <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> with a correct prototype.</p>


<p>Declaration at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 9276 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitSub() {#a937657e0221c87545044638a4ab2be4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitSub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
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



<p>Definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitSwitch() {#a408c9bfd71e6edbb4755986c55cac5e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitSwitch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 12450 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitTargetIntrinsic() {#a1eb5d1c30f868f2f4a5c2422fa0b34d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitTargetIntrinsic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I, unsigned Intrinsic)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>visitTargetIntrinsic - Lower a call of a target intrinsic to an INTRINSIC node.</p>

<p>Declaration at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 5262 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitTrunc() {#aec88d366b75cc48a99cfe6a3236f1c30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitTrunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3830 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitUDiv() {#aab0a9cf45cdba61b3f522fc9088ca221}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitUDiv (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
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



<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitUIToFP() {#a8fbb446d00cc9c216e4d1aa219f045ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitUIToFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3911 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitUnary() {#a6980e0bc12618f0c0ae89a473996d4b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitUnary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I, unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3561 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitUnaryFloatCall() {#a43518c43dbded63bab6be0e488c8b4ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SelectionDAGBuilder::visitUnaryFloatCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I, unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See if we can lower a unary floating-point operation into an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> with the specified Opcode.</p>


<p>If so, return true and lower it, otherwise return false and it will be lowered like a normal call. The caller already checked that <span class="doxyComputerOutput">I</span> calls the appropriate <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> with a correct prototype.</p>


<p>Declaration at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 9298 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitUnreachable() {#a40da2629051f9f83b1d6fb65c7fde94a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitUnreachable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/unreachableinst">UnreachableInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3544 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitURem() {#af7864b1229a2954734a97b38ddd74513}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitURem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
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



<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitUserOp1() {#a8f33264d64406cbf782a50d32d22c1a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitUserOp1 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitUserOp2() {#ae905a886120476763767d8e3d6e57864}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitUserOp2 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 669 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitVAArg() {#a959582865c5fe60bab89733537d14e05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitVAArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vaarginst">VAArgInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 10510 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitVACopy() {#ac2662cfa7d61334ecea635901024fe72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitVACopy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 10532 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitVAEnd() {#a729a34a78c9e74360fb5c83ec46326de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitVAEnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 650 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 10525 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitVAStart() {#a82a8763c5132e518a4e9f9b70453bdc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitVAStart (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 10503 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitVectorDeinterleave() {#ad6da642116003fbf53711220e3059649}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitVectorDeinterleave (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 12568 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitVectorExtractLastActive() {#abbe70c9435d2e38bc5c71015a0ed31dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitVectorExtractLastActive (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I, unsigned Intrinsic)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 6425 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitVectorHistogram() {#ad8ec5b3697d7100b04c0e01d6ad83327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitVectorHistogram (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I, unsigned IntrinsicID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 631 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 6367 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitVectorInterleave() {#ad8b943b2fad743449863cdb1d976df58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitVectorInterleave (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 662 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 12599 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitVectorPredicationIntrinsic() {#a014897a6abb41d1bb46d99b8ca925d50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitVectorPredicationIntrinsic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; VPIntrin)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 8641 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitVectorReduce() {#aba45c469ca384ad5814add80f5758e17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitVectorReduce (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I, unsigned Intrinsic)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 10862 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitVectorReverse() {#ae4f5b59103cda710365a298ce3e3c905}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitVectorReverse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 12545 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitVectorSplice() {#aacbd78808b39f4743229ce828b188482}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitVectorSplice (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 661 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 12642 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitVPCmp() {#ad2d8d23ca4b26550ea961943d2a2bbdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitVPCmp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpcmpintrinsic">VPCmpIntrinsic</a> &amp; VPIntrin)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 8607 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitVPGather() {#a9974797b2b152e3871fb766487e004ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitVPGather (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; VPIntrin, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OpValues)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 8450 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitVPLoad() {#a98418231da2a34a44ec0e86f5f712b7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitVPLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; VPIntrin, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OpValues)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 8424 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitVPScatter() {#a15674d84950f1769ff1418cbf07fd85c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitVPScatter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; VPIntrin, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OpValues)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 639 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 8514 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitVPStore() {#a0601cc3b22e9156807d8cfa3690ff5e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitVPStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; VPIntrin, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OpValues)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 8492 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitVPStridedLoad() {#a08b3ab5ce634fb83b18830ef0240f1a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitVPStridedLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; VPIntrin, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OpValues)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 8556 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitVPStridedStore() {#a3deeff710530f6de66107be8d0fdbc1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitVPStridedStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; VPIntrin, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OpValues)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 8583 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

### visitXor() {#abe66828045d8bb988da9f890117804c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SelectionDAGBuilder::visitXor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
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



<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### visitZExt() {#a6f4b6eb452180d261fb0698a7bfcbf84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SelectionDAGBuilder::visitZExt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 3844 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AC {#acb6015cccbf35f2e27ca3367cda3cdec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache* llvm::SelectionDAGBuilder::AC = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="#aadd87a22e72622eccf46ce5525d1976c">init</a>.</p>

</div>
</div>

### BatchAA {#a23f8a52e7e457d67b67aa86541f55c17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BatchAAResults* llvm::SelectionDAGBuilder::BatchAA = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a8eaaa1b4edc9934bfea0469269f3d869">getMemCmpLoad</a> and <a href="#aadd87a22e72622eccf46ce5525d1976c">init</a>.</p>

</div>
</div>

### ConstantsOut {#a7bdfdf9731f7e5501dea5dd410ebf9ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Constant *, unsigned&gt; llvm::SelectionDAGBuilder::ConstantsOut</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### Context {#ac536e4b59b1e85317cea0b32d47752ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext* llvm::SelectionDAGBuilder::Context = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="#ac42eef26cc4185a8932bc59a94dc5d16">handleKillDebugValue</a> and <a href="#aadd87a22e72622eccf46ce5525d1976c">init</a>.</p>

</div>
</div>

### DAG {#ad997f08bfd4680a697130632badf740e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectionDAG&amp; llvm::SelectionDAGBuilder::DAG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="#a13b6c3ad0bdee051eda42dc7c8a1f12b">addDanglingDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a21f33b0949c9004250a9978f1a5d3b3d">addStackMapLiveVars</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate/#a4841be2489ba10321338a1874b53f249">llvm::StatepointLoweringState::allocateStackSlot</a>, <a href="#a5184df56e270750a839acad50a1b8501">CopyValueToVirtualRegister</a>, <a href="#a41a8f459a2dcfcfc624394df6b432689">EmitBranchForMergedCondition</a>, <a href="#ae17b24216f27d8266c87b9fa9a70f533">FindMergedConditions</a>, <a href="#ac0b87e85b015d15077a7d9432c500df3">getCopyFromRegs</a>, <a href="#a2f4850c6b936e27186113935b002b36f">getFrameIndexTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a8eaaa1b4edc9934bfea0469269f3d869">getMemCmpLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a3e8b055fdb7e07479b83d69c15211d54">getUniformBase</a>, <a href="#afe3b2bbac4396d088da5c91f77754843">getValueImpl</a>, <a href="#a6571e1b07bfb1d4c5b1e832fdac355a1">handleDebugDeclare</a>, <a href="#ae9748fb2e4d41aaa8ac80d00b2becc52">handleDebugValue</a>, <a href="#aadd87a22e72622eccf46ce5525d1976c">init</a>, <a href="#afe97e2bc5bd74272ca1b54da1fb30e06">LowerAsSTATEPOINT</a>, <a href="#a57ee991742a8027b5ef002c616a6b9fd">LowerCallSiteWithDeoptBundleImpl</a>, <a href="#ac9742261cd7ee88cb99ec122fc61f5e8">LowerCallSiteWithPtrAuthBundle</a>, <a href="#a2b4653fa0c302d9cbe4e7839d711e76a">LowerCallTo</a>, <a href="#a459873061a3fed537ca026ddaffe57ed">LowerDeoptimizeCall</a>, <a href="#acf29bbf079b2610d2c8481212261fc49">LowerDeoptimizingReturn</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a1692829d8158767fe5ac1809c90a77a3">lowerIncomingStatepointValue</a>, <a href="#ab29b69c993fbb9a4b9d28c3600df005d">lowerInvokable</a>, <a href="#a3756185351596750edbb4790d9923eea">lowerRangeToAssertZExt</a>, <a href="#a32cff45e4cfd323ecc3896adcb08c2a9">LowerStatepoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a720a77a05d768dabfa739d154c11ddfd">pushStackMapConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#adec63d991d7eb048d87fa3888099c848">reservePreviousStackSlotForValue</a>, <a href="#ab898c0fc6a2159b032a398271add3927">resolveDanglingDebugInfo</a>, <a href="#a8cf671ed90e3e80717aaa6318b24794c">salvageUnresolvedDbgValue</a>, <a href="#a89f8344fd5ae844b5beec8c4b9924f95">SelectionDAGBuilder</a>, <a href="#a732bd4cf41862afa6092c1648c02e256">shouldKeepJumpConditionsTogether</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#afb9b4b3ff97e290070f42849b51a13a5">spillIncomingStatepointValue</a>, <a href="/web-llvm/docs/api/structs/llvm/selectiondagbuilder/statepointloweringinfo/#ace8fb58e34ccf8067691bd19eeca3ef2">llvm::SelectionDAGBuilder::StatepointLoweringInfo::StatepointLoweringInfo</a>, <a href="#abbbfefd79a5b3d1b4ea8d8383fd01af5">visit</a>, <a href="#a7a7b439d546506d56e2cdc61a1ac1d06">visitBitTestCase</a>, <a href="#a31f9f0db1bb0b321286db70b58fb001e">visitBitTestHeader</a>, <a href="#a196df57d98a1307c0ced654a8e1d202b">visitDbgInfo</a>, <a href="#ac730a866bfd17ffc004cc3a0e85c3770">visitJumpTable</a>, <a href="#ac85aa2ebc935e3c87ec7f9e54183cddf">visitJumpTableHeader</a>, <a href="#afff13ac7b2e92fc0ad596603592298bd">visitSPDescriptorFailure</a>, <a href="#ae8662f747218aee8ddeb4cdfbd1435a7">visitSPDescriptorParent</a> and <a href="#afe7d9f31d3030277242731ccf43478c0">visitSwitchCase</a>.</p>

</div>
</div>

### FuncInfo {#ad10e64e191507974af84a4ea069a9e36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionLoweringInfo&amp; llvm::SelectionDAGBuilder::FuncInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Information about the function as a whole.</p>

<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate/#a4841be2489ba10321338a1874b53f249">llvm::StatepointLoweringState::allocateStackSlot</a>, <a href="#ac30ce0e7a5759d1e0bb5bf891e88662b">CopyToExportRegsIfNeeded</a>, <a href="#a5184df56e270750a839acad50a1b8501">CopyValueToVirtualRegister</a>, <a href="#aa5254258c6a479f86e6ecfc4dcdd7a5e">ExportFromCurrentBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a6ac2c0f0b7439c31332c78cd1ca5c4fe">findPreviousSpillSlot</a>, <a href="#ac0b87e85b015d15077a7d9432c500df3">getCopyFromRegs</a>, <a href="#afe3b2bbac4396d088da5c91f77754843">getValueImpl</a>, <a href="#ae9748fb2e4d41aaa8ac80d00b2becc52">handleDebugValue</a>, <a href="#ae3df768f340538afba57a5eaeb0ba277">isExportableFromCurrentBlock</a>, <a href="#afe97e2bc5bd74272ca1b54da1fb30e06">LowerAsSTATEPOINT</a>, <a href="#a2b4653fa0c302d9cbe4e7839d711e76a">LowerCallTo</a>, <a href="#a32cff45e4cfd323ecc3896adcb08c2a9">LowerStatepoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#adec63d991d7eb048d87fa3888099c848">reservePreviousStackSlotForValue</a>, <a href="#a89f8344fd5ae844b5beec8c4b9924f95">SelectionDAGBuilder</a>, <a href="#a732bd4cf41862afa6092c1648c02e256">shouldKeepJumpConditionsTogether</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate/#aeb4b5a7ad5a49f17f8a34890eb6efefe">llvm::StatepointLoweringState::startNewStatepoint</a>, <a href="#a31f9f0db1bb0b321286db70b58fb001e">visitBitTestHeader</a>, <a href="#a196df57d98a1307c0ced654a8e1d202b">visitDbgInfo</a> and <a href="#ac85aa2ebc935e3c87ec7f9e54183cddf">visitJumpTableHeader</a>.</p>

</div>
</div>

### GFI {#a9b4db8b8082660004fda0c282da0ff0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCFunctionInfo* llvm::SelectionDAGBuilder::GFI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Garbage collection metadata for the function.</p>

<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="#aadd87a22e72622eccf46ce5525d1976c">init</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a720af7e7f23150174952da03d216341a">isGCValue</a>, <a href="#afe97e2bc5bd74272ca1b54da1fb30e06">LowerAsSTATEPOINT</a> and <a href="#a32cff45e4cfd323ecc3896adcb08c2a9">LowerStatepoint</a>.</p>

</div>
</div>

### HasTailCall {#a39e446f1647e793791c33d0d2412d088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SelectionDAGBuilder::HasTailCall = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is set to true if a call in the current block has been translated as a tail call.</p>


<p>In this case, no subsequent DAG nodes should be created.</p>


<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="#a2c224fcb5175ab1e842dd2a1371eb3d8">clear</a>, <a href="#ab29b69c993fbb9a4b9d28c3600df005d">lowerInvokable</a> and <a href="#abbbfefd79a5b3d1b4ea8d8383fd01af5">visit</a>.</p>

</div>
</div>

### LibInfo {#ae283c81e2135fac41f1896dd39c4cc40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo* llvm::SelectionDAGBuilder::LibInfo = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="#aadd87a22e72622eccf46ce5525d1976c">init</a>.</p>

</div>
</div>

### LPadToCallSiteMap {#a53319e45ea515329480adf13f0098b4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineBasicBlock *, SmallVector&lt;unsigned, 4&gt; &gt; llvm::SelectionDAGBuilder::LPadToCallSiteMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map a landing pad to the call site indexes.</p>

<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="#aadd87a22e72622eccf46ce5525d1976c">init</a>.</p>

</div>
</div>

### PendingLoads {#a9a1381eb77fac8d57f54f7bf25919a4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SDValue, 8&gt; llvm::SelectionDAGBuilder::PendingLoads</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Loads are not emitted to the program immediately.</p>


<p>We bunch them up and then emit token factor nodes when possible. This allows us to get simple disambiguation between loads without worrying about alias analysis.</p>


<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="#a2c224fcb5175ab1e842dd2a1371eb3d8">clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a8eaaa1b4edc9934bfea0469269f3d869">getMemCmpLoad</a>, <a href="#ab41a8476a0c74bcf1a2bf665eeececd8">getMemoryRoot</a> and <a href="#aa3e946c1fc678a70e849244389bd929a">getRoot</a>.</p>

</div>
</div>

### SL {#a346bf6c4d7fca3ebce554ec2cdd80e87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SDAGSwitchLowering&gt; llvm::SelectionDAGBuilder::SL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="#a41a8f459a2dcfcfc624394df6b432689">EmitBranchForMergedCondition</a>, <a href="#aadd87a22e72622eccf46ce5525d1976c">init</a>, <a href="#a3756185351596750edbb4790d9923eea">lowerRangeToAssertZExt</a>, <a href="#a89f8344fd5ae844b5beec8c4b9924f95">SelectionDAGBuilder</a> and <a href="#af6e9499206c6a56801d70a567fc8862a">UpdateSplitBlock</a>.</p>

</div>
</div>

### SPDescriptor {#a1e6f0d1aacd8e97d178a627fdafc3aaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackProtectorDescriptor llvm::SelectionDAGBuilder::SPDescriptor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A <a href="/web-llvm/docs/api/classes/llvm/stackprotectordescriptor">StackProtectorDescriptor</a> structure used to communicate stack protector information in between SelectBasicBlock and FinishBasicBlock.</p>

<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### StatepointLowering {#a77cbbcab1440ac5ef835e1a3d3f6c74e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StatepointLoweringState llvm::SelectionDAGBuilder::StatepointLowering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>State used while lowering a statepoint sequence (gc_statepoint, gc_relocate, and gc_result).</p>


<p>See StatepointLowering.hpp/cpp for details.</p>


<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="#a2c224fcb5175ab1e842dd2a1371eb3d8">clear</a>, <a href="#afe97e2bc5bd74272ca1b54da1fb30e06">LowerAsSTATEPOINT</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#adec63d991d7eb048d87fa3888099c848">reservePreviousStackSlotForValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#afb9b4b3ff97e290070f42849b51a13a5">spillIncomingStatepointValue</a>.</p>

</div>
</div>

### SwiftError {#a4ac2cfd1783912207570d7cce74a3ea2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SwiftErrorValueTracking&amp; llvm::SelectionDAGBuilder::SwiftError</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Information about the swifterror values used throughout the function.</p>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="#a2b4653fa0c302d9cbe4e7839d711e76a">LowerCallTo</a> and <a href="#a89f8344fd5ae844b5beec8c4b9924f95">SelectionDAGBuilder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AssignmentTrackingEnabled {#ab8e021fdfe03d8dee4c95d00f0fadcf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SelectionDAGBuilder::AssignmentTrackingEnabled = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache the module flag for whether we should use debug-info assignment tracking.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### CurInst {#adf98d39188856842bae71a40fd6a7af4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Instruction* llvm::SelectionDAGBuilder::CurInst = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The current instruction being visited.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### DanglingDebugInfoMap {#ad97bc0e0c5a9f36b3662b012557efae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;const Value*, DanglingDebugInfoVector&gt; llvm::SelectionDAGBuilder::DanglingDebugInfoMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keeps track of dbg_values for which we have not yet seen the referent.</p>


<p>We defer handling these until we do see it.</p>


<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### NodeMap {#a861c224bffd58fc2e4dae66d9656c21e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Value*, SDValue&gt; llvm::SelectionDAGBuilder::NodeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### PendingConstrainedFP {#ae50ca4d135cbeb554c6ed23b3fadd41b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SDValue, 8&gt; llvm::SelectionDAGBuilder::PendingConstrainedFP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similar to loads, nodes corresponding to constrained FP intrinsics are bunched up and emitted when necessary.</p>


<p>These can be moved across each other and any (normal) memory operation (load or store), but not across calls or instructions having unspecified side effects. As a special case, constrained FP intrinsics using fpexcept.strict may not be deleted even if otherwise unused, so they need to be chained before any terminator instruction (like PendingExports). We track the latter set of nodes in a separate list.</p>


<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### PendingConstrainedFPStrict {#a882a433e31fed4c06203690225a7f1b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SDValue, 8&gt; llvm::SelectionDAGBuilder::PendingConstrainedFPStrict</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### PendingExports {#a28f8b07457528489f897e04c4794520c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SDValue, 8&gt; llvm::SelectionDAGBuilder::PendingExports</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CopyToReg nodes that copy values to virtual registers for export to other blocks need to be emitted before any terminator instruction, but they have no other ordering requirements.</p>


<p>We bunch them up and the emit a single tokenfactor for them just before terminator instructions.</p>


<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### SDNodeOrder {#ae9fa46bde40ba2275ce99bde1389d065}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SelectionDAGBuilder::SDNodeOrder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A unique monotonically increasing number used to order the SDNodes we create.</p>

<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### TM {#a3293dad09e732134cb72b1cec185de56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetMachine&amp; llvm::SelectionDAGBuilder::TM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

### UnusedArgNodeMap {#a396e61e3845a565bb1ed778c2ba1240c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Value*, SDValue&gt; llvm::SelectionDAGBuilder::UnusedArgNodeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps argument value for unused arguments.</p>


<p>This is used to preserve debug information for incoming arguments.</p>


<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### LowestSDNodeOrder {#accb23e3bb8c3fddd1fc7a18025b1ec0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SelectionDAGBuilder::LowestSDNodeOrder = 1</td>
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

<p>Lowest valid SDNodeOrder.</p>


<p>The special case 0 is reserved for scheduling nodes without a corresponding <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>.</p>


<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="#a2c224fcb5175ab1e842dd2a1371eb3d8">clear</a> and <a href="#a89f8344fd5ae844b5beec8c4b9924f95">SelectionDAGBuilder</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
