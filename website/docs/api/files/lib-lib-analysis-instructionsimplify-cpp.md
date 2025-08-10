---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/instructionsimplify-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `InstructionSimplify.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionsimplify-h">llvm/Analysis/InstructionSimplify.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">llvm/Analysis/AssumptionCache.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/capturetracking-h">llvm/Analysis/CaptureTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cmpinstanalysis-h">llvm/Analysis/CmpInstAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/constantfolding-h">llvm/Analysis/ConstantFolding.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instsimplifyfolder-h">llvm/Analysis/InstSimplifyFolder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loads-h">llvm/Analysis/Loads.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">llvm/Analysis/LoopAnalysisManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">llvm/Analysis/MemoryBuiltins.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/overflowinstanalysis-h">llvm/Analysis/OverflowInstAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">llvm/Analysis/VectorUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">llvm/IR/ConstantRange.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">llvm/IR/Operator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">llvm/IR/Statepoint.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">llvm/Support/KnownBits.h</a>"
#include &lt;algorithm&gt;
#include &lt;optional&gt;
#include "llvm/IR/Instruction.def"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a30dc1111ec80f24c21b7ea4e7e6df202">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MonotonicType { <a href="#a4fa5495dc2ca57889c6cf2fd8bba50ef">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfd0bbcbc789bf86c6670e4de61edaba">STATISTIC</a> (NumExpand, "Number of expansions")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b287edafd0ce24fba1ca0841ef69c8b">STATISTIC</a> (NumReassoc, "Number of reassociations")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a> (Value *Op0, Value *Op1, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for an And, see if we can fold the result. <a href="#ac90052ea1afde8fc28fe6f27181fd5f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ba3e8fde7409234793175d6a978ffab">simplifyUnOp</a> (unsigned Opcode, Value *Op, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given the operand for a <a href="/web-llvm/docs/api/classes/llvm/unaryoperator">UnaryOperator</a>, see if we can fold the result. <a href="#a3ba3e8fde7409234793175d6a978ffab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6497dd4ddbdc3b5dacec510108c4e62d">simplifyFPUnOp</a> (unsigned Opcode, Value *Op, const FastMathFlags &amp;FMF, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given the operand for a <a href="/web-llvm/docs/api/classes/llvm/unaryoperator">UnaryOperator</a>, see if we can fold the result. <a href="#a6497dd4ddbdc3b5dacec510108c4e62d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac20fb14fde8d282680882caeb98c2298">simplifyBinOp</a> (unsigned Opcode, Value *LHS, Value *RHS, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for a <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a>, see if we can fold the result. <a href="#ac20fb14fde8d282680882caeb98c2298">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0587e14aef27ebf77bcbdf0770da6392">simplifyBinOp</a> (unsigned Opcode, Value *LHS, Value *RHS, const FastMathFlags &amp;FMF, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for a <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a>, see if we can fold the result. <a href="#a0587e14aef27ebf77bcbdf0770da6392">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a5e32c5d5b01554c4d171562427a2de">simplifyCmpInst</a> (CmpPredicate Predicate, Value *LHS, Value *RHS, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for a <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a>, see if we can fold the result. <a href="#a5a5e32c5d5b01554c4d171562427a2de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a> (CmpPredicate Pred, Value *LHS, Value *RHS, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for an <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a>, see if we can fold the result. <a href="#a47a81cb5e93cfda95b1de100dd5b9919">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a845e93029e92776841aaf5e0ec4c812f">simplifyOrInst</a> (Value *Op0, Value *Op1, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for an Or, see if we can fold the result. <a href="#a845e93029e92776841aaf5e0ec4c812f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cfeea050198084d67109f0260e33970">simplifyXorInst</a> (Value *Op0, Value *Op1, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for a Xor, see if we can fold the result. <a href="#a9cfeea050198084d67109f0260e33970">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfcd971ce6ccafa5489dd3bf313219af">simplifyCastInst</a> (unsigned, Value *, Type *, const SimplifyQuery &amp;, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab8aaa8e44e0609f7d3e9ae822f11f7e">simplifyGEPInst</a> (Type *SrcTy, Value *Ptr, ArrayRef&lt; Value * &gt; Indices, GEPNoWrapFlags NW, const SimplifyQuery &amp;Q, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for an <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a>, see if we can fold the result. <a href="#aab8aaa8e44e0609f7d3e9ae822f11f7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38dc339806a701c1f11ec31cf76936ff">simplifySelectInst</a> (Value *Cond, Value *TrueVal, Value *FalseVal, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for a <a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a>, see if we can fold the result. <a href="#a38dc339806a701c1f11ec31cf76936ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ef524444504c738f1da4b4fb0b5a238">simplifyInstructionWithOperands</a> (Instruction *I, ArrayRef&lt; Value * &gt; NewOps, const SimplifyQuery &amp;SQ, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See if we can compute a simplified version of this instruction. <a href="#a3ef524444504c738f1da4b4fb0b5a238">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a774f686ad651b962a54ad231e2212f64">getFalse</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For a boolean type or a vector of boolean type, return false or a vector with every element false. <a href="#a774f686ad651b962a54ad231e2212f64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa375e5211d9e07739a374c0479fb0ca">getTrue</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For a boolean type or a vector of boolean type, return true or a vector with every element true. <a href="#aaa375e5211d9e07739a374c0479fb0ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e2c41b46422f8392e87d92a2f8e9d3c">isSameCompare</a> (Value *V, CmpPredicate Pred, Value *LHS, Value *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isSameCompare - Is V equivalent to the comparison "LHS Pred RHS"? <a href="#a3e2c41b46422f8392e87d92a2f8e9d3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04cf98272b39e1eef023148e1499b1fc">simplifyCmpSelCase</a> (CmpPredicate Pred, Value *LHS, Value *RHS, Value *Cond, const SimplifyQuery &amp;Q, unsigned MaxRecurse, Constant *TrueOrFalse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simplify comparison with true or false branch of select: sel = select i1 cond, i32 tv, i32 fv cmp = icmp sle i32 sel, rhs Compose new comparison by substituting sel with either tv or fv and see if it simplifies. <a href="#a04cf98272b39e1eef023148e1499b1fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5211abbd14c49ebe208e93000a365ef0">simplifyCmpSelTrueCase</a> (CmpPredicate Pred, Value *LHS, Value *RHS, Value *Cond, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simplify comparison with true branch of select. <a href="#a5211abbd14c49ebe208e93000a365ef0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a022b0d31de4686085b7c8d2719a3edd7">simplifyCmpSelFalseCase</a> (CmpPredicate Pred, Value *LHS, Value *RHS, Value *Cond, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simplify comparison with false branch of select. <a href="#a022b0d31de4686085b7c8d2719a3edd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b14bc4633dc9ebd06733a8792510cbe">handleOtherCmpSelSimplifications</a> (Value *TCmp, Value *FCmp, Value *Cond, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We know comparison with both branches of select can be simplified, but they are not equal. <a href="#a1b14bc4633dc9ebd06733a8792510cbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af412caabe4d2526271b50f052f9d3aef">valueDominatesPHI</a> (Value *V, PHINode *P, const DominatorTree *DT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does the given value dominate the specified phi node? <a href="#af412caabe4d2526271b50f052f9d3aef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d9999d61310781a41074a967e885f12">expandBinOp</a> (Instruction::BinaryOps Opcode, Value *V, Value *OtherOp, Instruction::BinaryOps OpcodeToExpand, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to simplify a binary operator of form "V op OtherOp" where V is "(B0 opex B1)" by distributing 'op' across 'opex' as "(B0 op OtherOp) opex (B1 op OtherOp)". <a href="#a6d9999d61310781a41074a967e885f12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1588904a0310f8239c38e8790a1f1ca0">expandCommutativeBinOp</a> (Instruction::BinaryOps Opcode, Value *L, Value *R, Instruction::BinaryOps OpcodeToExpand, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to simplify binops of form "A op (B op' C)" or the commuted variant by distributing op over op'. <a href="#a1588904a0310f8239c38e8790a1f1ca0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8863b1b71b53dbab1dd0bd7933ddb3cf">simplifyAssociativeBinOp</a> (Instruction::BinaryOps Opcode, Value *LHS, Value *RHS, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generic simplifications for associative binary operations. <a href="#a8863b1b71b53dbab1dd0bd7933ddb3cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada3f0c65b41a26f74d332e974164ce55">threadBinOpOverSelect</a> (Instruction::BinaryOps Opcode, Value *LHS, Value *RHS, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In the case of a binary operation with a select instruction as an operand, try to simplify the binop by seeing whether evaluating it on both branches of the select results in the same value. <a href="#ada3f0c65b41a26f74d332e974164ce55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6faca61824779a7d72a2c1e08b9e7a0">threadCmpOverSelect</a> (CmpPredicate Pred, Value *LHS, Value *RHS, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In the case of a comparison with a select instruction, try to simplify the comparison by seeing whether both branches of the select result in the same value. <a href="#aa6faca61824779a7d72a2c1e08b9e7a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a914ac5681f80badb866f2aee44fc509a">threadBinOpOverPHI</a> (Instruction::BinaryOps Opcode, Value *LHS, Value *RHS, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In the case of a binary operation with an operand that is a PHI instruction, try to simplify the binop by seeing whether evaluating it on the incoming phi values yields the same result for every value. <a href="#a914ac5681f80badb866f2aee44fc509a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec7a76fbddf5983969def6e47c0f177">threadCmpOverPHI</a> (CmpPredicate Pred, Value *LHS, Value *RHS, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In the case of a comparison with a PHI instruction, try to simplify the comparison by seeing whether comparing with all of the incoming phi values yields the same result every time. <a href="#a1ec7a76fbddf5983969def6e47c0f177">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15df887e1ad05e6c22a7c2e6492bde2d">foldOrCommuteConstant</a> (Instruction::BinaryOps Opcode, Value *&amp;Op0, Value *&amp;Op1, const SimplifyQuery &amp;Q)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a8f0d83fd0c16251206c0d0f3e78174">simplifyAddInst</a> (Value *Op0, Value *Op1, bool IsNSW, bool IsNUW, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for an Add, see if we can fold the result. <a href="#a3a8f0d83fd0c16251206c0d0f3e78174">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59cd1a000769414b2d832576bf689c32">stripAndComputeConstantOffsets</a> (const DataLayout &amp;DL, Value *&amp;V, bool AllowNonInbounds=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the base pointer and cumulative constant offsets for V. <a href="#a59cd1a000769414b2d832576bf689c32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc235173f78d0b2a260bb5438267139e">computePointerDifference</a> (const DataLayout &amp;DL, Value *LHS, Value *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the constant difference between two pointer values. <a href="#adc235173f78d0b2a260bb5438267139e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6343e645572ce8783bbf5853d181479f">simplifyByDomEq</a> (unsigned Opcode, Value *Op0, Value *Op1, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if there is a dominating equivalence condition for the two operands. <a href="#a6343e645572ce8783bbf5853d181479f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e278bb318fd700a9c8d4f4a7c8caba9">simplifySubInst</a> (Value *Op0, Value *Op1, bool IsNSW, bool IsNUW, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for a Sub, see if we can fold the result. <a href="#a0e278bb318fd700a9c8d4f4a7c8caba9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f2df18bfd941b2e8d1cd78db5beb6f7">simplifyMulInst</a> (Value *Op0, Value *Op1, bool IsNSW, bool IsNUW, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for a Mul, see if we can fold the result. <a href="#a7f2df18bfd941b2e8d1cd78db5beb6f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac21f987259846006ea150eb82ff069df">isICmpTrue</a> (CmpPredicate Pred, Value *LHS, Value *RHS, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a predicate and two operands, return true if the comparison is true. <a href="#ac21f987259846006ea150eb82ff069df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab29fdeb7689892b6496576ca70cfc625">isDivZero</a> (Value *X, Value *Y, const SimplifyQuery &amp;Q, unsigned MaxRecurse, bool IsSigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we can simplify X / Y to 0. <a href="#ab29fdeb7689892b6496576ca70cfc625">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a789b1341fc862e30623b200657911a4c">simplifyDivRem</a> (Instruction::BinaryOps Opcode, Value *Op0, Value *Op1, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for common or similar folds of integer division or integer remainder. <a href="#a789b1341fc862e30623b200657911a4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d67c7fd2789ef1dfb05513f1eb8d054">simplifyDiv</a> (Instruction::BinaryOps Opcode, Value *Op0, Value *Op1, bool IsExact, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These are simplifications common to SDiv and UDiv. <a href="#a2d67c7fd2789ef1dfb05513f1eb8d054">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed163588354401b6679a39acad6fae2a">simplifyRem</a> (Instruction::BinaryOps Opcode, Value *Op0, Value *Op1, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These are simplifications common to SRem and URem. <a href="#aed163588354401b6679a39acad6fae2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a630c735bfbff439b152d83f92302cb34">simplifySDivInst</a> (Value *Op0, Value *Op1, bool IsExact, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for an SDiv, see if we can fold the result. <a href="#a630c735bfbff439b152d83f92302cb34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08c5c0e210c3418665efc1bc160ebcfe">simplifyUDivInst</a> (Value *Op0, Value *Op1, bool IsExact, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for a UDiv, see if we can fold the result. <a href="#a08c5c0e210c3418665efc1bc160ebcfe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add0275e00f4260c742c6cf3ec24b1987">simplifySRemInst</a> (Value *Op0, Value *Op1, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for an SRem, see if we can fold the result. <a href="#add0275e00f4260c742c6cf3ec24b1987">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2135d9db611a0be89044fae9b38e1f9">simplifyURemInst</a> (Value *Op0, Value *Op1, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for a URem, see if we can fold the result. <a href="#aa2135d9db611a0be89044fae9b38e1f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a587eab2c520053bb06fdc4afe5a57aa3">isPoisonShift</a> (Value *Amount, const SimplifyQuery &amp;Q)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if a shift by <span class="doxyComputerOutput">Amount</span> always yields poison. <a href="#a587eab2c520053bb06fdc4afe5a57aa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9d2883e296d808c7a9e18efcee71049">simplifyShift</a> (Instruction::BinaryOps Opcode, Value *Op0, Value *Op1, bool IsNSW, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for an Shl, LShr or AShr, see if we can fold the result. <a href="#ae9d2883e296d808c7a9e18efcee71049">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bb5f4b5b2420a7f3950939b2de01330">simplifyRightShift</a> (Instruction::BinaryOps Opcode, Value *Op0, Value *Op1, bool IsExact, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for an LShr or AShr, see if we can fold the result. <a href="#a5bb5f4b5b2420a7f3950939b2de01330">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e2f5715194e637f638fcd6e0851448b">simplifyShlInst</a> (Value *Op0, Value *Op1, bool IsNSW, bool IsNUW, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for an Shl, see if we can fold the result. <a href="#a8e2f5715194e637f638fcd6e0851448b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0614870543ce4ba5b6f9c7030d6867e2">simplifyLShrInst</a> (Value *Op0, Value *Op1, bool IsExact, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for an LShr, see if we can fold the result. <a href="#a0614870543ce4ba5b6f9c7030d6867e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29b4afe26752d50b7207bf4cd3f984f3">simplifyAShrInst</a> (Value *Op0, Value *Op1, bool IsExact, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for an AShr, see if we can fold the result. <a href="#a29b4afe26752d50b7207bf4cd3f984f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4355ad633eda8e7c8a6538ea41bb34f3">simplifyUnsignedRangeCheck</a> (ICmpInst *ZeroICmp, ICmpInst *UnsignedICmp, bool IsAnd, const SimplifyQuery &amp;Q)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Commuted variants are assumed to be handled by calling this function again with the parameters swapped. <a href="#a4355ad633eda8e7c8a6538ea41bb34f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5781faa80a27cf51fa316feaa2ad363">simplifyAndOrOfICmpsWithConstants</a> (ICmpInst *Cmp0, ICmpInst *Cmp1, bool IsAnd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if a pair of compares with a shared operand and 2 constants has an empty set intersection, full set union, or if one compare is a superset of the other. <a href="#ae5781faa80a27cf51fa316feaa2ad363">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a496b149294586554f0cd9fd240d8d80d">simplifyAndOfICmpsWithAdd</a> (ICmpInst *Op0, ICmpInst *Op1, const InstrInfoQuery &amp;IIQ)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a426204f20670379cdefabed663ac339f">simplifyAndOrOfICmpsWithCtpop</a> (ICmpInst *Cmp0, ICmpInst *Cmp1, bool IsAnd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to simplify and/or of icmp with ctpop intrinsic. <a href="#a426204f20670379cdefabed663ac339f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1907d1fccfb9846bfd91b6b79c0acbc">simplifyAndOfICmps</a> (ICmpInst *Op0, ICmpInst *Op1, const SimplifyQuery &amp;Q)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b473dc0c6603bb29f38c46858df840e">simplifyOrOfICmpsWithAdd</a> (ICmpInst *Op0, ICmpInst *Op1, const InstrInfoQuery &amp;IIQ)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b86bbc17cbb2be2b63a54fcdbcf4251">simplifyOrOfICmps</a> (ICmpInst *Op0, ICmpInst *Op1, const SimplifyQuery &amp;Q)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb8e54b9f6be2fdb87b369c2218db1cc">simplifyAndOrOfFCmps</a> (const SimplifyQuery &amp;Q, FCmpInst *LHS, FCmpInst *RHS, bool IsAnd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4122a9286a8dd18458df1f47230e07f">simplifyAndOrOfCmps</a> (const SimplifyQuery &amp;Q, Value *Op0, Value *Op1, bool IsAnd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad70420ff755267b04fb5a24ca252bf32">simplifyWithOpReplaced</a> (Value *V, Value *Op, Value *RepOp, const SimplifyQuery &amp;Q, bool AllowRefinement, SmallVectorImpl&lt; Instruction * &gt; *DropFlags, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae739737036faaf1bcaa66a0f4a8e1e63">simplifyAndOrWithICmpEq</a> (unsigned Opcode, Value *Op0, Value *Op1, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8c09431e3ba6ccd88dfa4a32c2127be">simplifyLogicOfAddSub</a> (Value *Op0, Value *Op1, Instruction::BinaryOps Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a bitwise logic op, check if the operands are add/sub with a common source value and inverted constant (identity: C - X -&gt; ~(X + ~C)). <a href="#ab8c09431e3ba6ccd88dfa4a32c2127be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eefa98bc7f6c24b6f1fa0bb220a77a4">simplifyAndCommutative</a> (Value *Op0, Value *Op1, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd241acbc11f163c5843ef83d13af545">simplifyOrLogic</a> (Value *X, Value *Y)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abee3cf86c05d2369d387f07f7055b9dc">getCompareTy</a> (Value *Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad38d439eec395362c9cfce6c92751677">extractEquivalentCondition</a> (Value *V, CmpPredicate Pred, Value *LHS, Value *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rummage around inside V looking for something equivalent to the comparison "LHS Pred RHS". <a href="#ad38d439eec395362c9cfce6c92751677">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9fb01a51417407eb7de1dff943c27e3">isAllocDisjoint</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the underlying object (storage) must be disjoint from storage returned by any noalias return call. <a href="#aa9fb01a51417407eb7de1dff943c27e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1766fdfd6561f8585dca1ac3f867399c">haveNonOverlappingStorage</a> (const Value *V1, const Value *V2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if V1 and V2 are each the base of some distict storage region [V, object_size(V)] which do not overlap. <a href="#a1766fdfd6561f8585dca1ac3f867399c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec29f5580509ec9a7592200e09b7aa27">computePointerICmp</a> (CmpPredicate Pred, Value *LHS, Value *RHS, const SimplifyQuery &amp;Q)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22aa6a5c92a8a6cbb5437123d7e069e6">simplifyICmpOfBools</a> (CmpPredicate Pred, Value *LHS, Value *RHS, const SimplifyQuery &amp;Q)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fold an icmp when its operands have i1 scalar type. <a href="#a22aa6a5c92a8a6cbb5437123d7e069e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a738d3c4d8f36cf843825c2b5a878f58a">simplifyICmpWithZero</a> (CmpPredicate Pred, Value *LHS, Value *RHS, const SimplifyQuery &amp;Q)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try hard to fold icmp with zero RHS because this is a common case. <a href="#a738d3c4d8f36cf843825c2b5a878f58a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7520bc5124cf32bdbb659ae6fc12cf9c">simplifyICmpWithConstant</a> (CmpPredicate Pred, Value *LHS, Value *RHS, const InstrInfoQuery &amp;IIQ)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57d8791ae7f26ddfe185e3d40b8f9c90">getUnsignedMonotonicValues</a> (SmallPtrSetImpl&lt; Value * &gt; &amp;Res, Value *V, MonotonicType Type, unsigned Depth=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get values V_i such that V uge V_i (GreaterEq) or V ule V_i (LowerEq). <a href="#a57d8791ae7f26ddfe185e3d40b8f9c90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adae506d280d297474e74be7d5d1b9762">simplifyICmpUsingMonotonicValues</a> (CmpPredicate Pred, Value *LHS, Value *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28e9b56583c0f73543606d22bfac472e">simplifyICmpWithBinOpOnLHS</a> (CmpPredicate Pred, BinaryOperator *LBO, Value *RHS, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86f75bbbe87c45fd3f9047fbad61671c">trySimplifyICmpWithAdds</a> (CmpPredicate Pred, Value *LHS, Value *RHS, const InstrInfoQuery &amp;IIQ)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64cb0c5ab10b63f22110e1b0183a648f">simplifyICmpWithBinOp</a> (CmpPredicate Pred, Value *LHS, Value *RHS, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TODO: A large part of this logic is duplicated in InstCombine's foldICmpBinOp(). <a href="#a64cb0c5ab10b63f22110e1b0183a648f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f8adcab536e4c9f42e148d7eb218e6a">simplifyICmpWithMinMax</a> (CmpPredicate Pred, Value *LHS, Value *RHS, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>simplify integer comparisons where at least one operand of the compare matches an integer min/max idiom. <a href="#a4f8adcab536e4c9f42e148d7eb218e6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9417447cf23234d645221bda42e00c4">simplifyICmpWithDominatingAssume</a> (CmpPredicate Predicate, Value *LHS, Value *RHS, const SimplifyQuery &amp;Q)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e2e121dcbec9a2ede54e53ba8be83d4">simplifyICmpWithIntrinsicOnLHS</a> (CmpPredicate Pred, Value *LHS, Value *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a407852423447c9c318189650976659fb">getRange</a> (Value *V, const InstrInfoQuery &amp;IIQ)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper method to get range from metadata or attribute. <a href="#a407852423447c9c318189650976659fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a> (CmpPredicate Pred, Value *LHS, Value *RHS, FastMathFlags FMF, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for an <a href="/web-llvm/docs/api/classes/llvm/fcmpinst">FCmpInst</a>, see if we can fold the result. <a href="#a110a350e37f3cc2ed2c603c3efde0a30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4611905728c0ddaed9f8964ae8b074a2">simplifyWithOpsReplaced</a> (Value *V, ArrayRef&lt; std::pair&lt; Value *, Value * &gt; &gt; Ops, const SimplifyQuery &amp;Q, bool AllowRefinement, SmallVectorImpl&lt; Instruction * &gt; *DropFlags, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87692407367823d3d593f8bf289f0785">simplifySelectBitTest</a> (Value *TrueVal, Value *FalseVal, Value *X, const APInt *Y, bool TrueWhenUnset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to simplify a select instruction when its condition operand is an integer comparison where one operand of the compare is a constant. <a href="#a87692407367823d3d593f8bf289f0785">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93f2e165baf61dd8295c9aececed9985">simplifyCmpSelOfMaxMin</a> (Value *CmpLHS, Value *CmpRHS, CmpPredicate Pred, Value *TVal, Value *FVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04d52227379f9e4c460d52bb45f92ff4">simplifySelectWithFakeICmpEq</a> (Value *CmpLHS, Value *CmpRHS, CmpPredicate Pred, Value *TrueVal, Value *FalseVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An alternative way to test if a bit is set or not uses sgt/slt instead of eq/ne. <a href="#a04d52227379f9e4c460d52bb45f92ff4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bee73e1eef011ba0a15bcb696cb0971">simplifySelectWithEquivalence</a> (ArrayRef&lt; std::pair&lt; Value *, Value * &gt; &gt; Replacements, Value *TrueVal, Value *FalseVal, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to simplify a select instruction when its condition operand is an integer equality or floating-point equivalence comparison. <a href="#a7bee73e1eef011ba0a15bcb696cb0971">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa1ff3254ee225171cb55d46b0eab145">simplifySelectWithICmpCond</a> (Value *CondVal, Value *TrueVal, Value *FalseVal, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to simplify a select instruction when its condition operand is an integer comparison. <a href="#afa1ff3254ee225171cb55d46b0eab145">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75fa36408fed5acf91329505b3419196">simplifySelectWithFCmp</a> (Value *Cond, Value *T, Value *F, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to simplify a select instruction when its condition operand is a floating-point comparison. <a href="#a75fa36408fed5acf91329505b3419196">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2e1b2bf5707da420c5d0578a227e34c">simplifyInsertValueInst</a> (Value *Agg, Value *Val, ArrayRef&lt; unsigned &gt; Idxs, const SimplifyQuery &amp;Q, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for an <a href="/web-llvm/docs/api/classes/llvm/insertvalueinst">InsertValueInst</a>, see if we can fold the result. <a href="#ac2e1b2bf5707da420c5d0578a227e34c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37493b7a361d3374a2731470d964c183">simplifyExtractValueInst</a> (Value *Agg, ArrayRef&lt; unsigned &gt; Idxs, const SimplifyQuery &amp;, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for an <a href="/web-llvm/docs/api/classes/llvm/extractvalueinst">ExtractValueInst</a>, see if we can fold the result. <a href="#a37493b7a361d3374a2731470d964c183">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48ebda753879b3d5d55fa0e1566b5439">simplifyExtractElementInst</a> (Value *Vec, Value *Idx, const SimplifyQuery &amp;Q, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for an <a href="/web-llvm/docs/api/classes/llvm/extractelementinst">ExtractElementInst</a>, see if we can fold the result. <a href="#a48ebda753879b3d5d55fa0e1566b5439">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a308de6b87d4d431477642d086b268a7c">simplifyPHINode</a> (PHINode *PN, ArrayRef&lt; Value * &gt; IncomingValues, const SimplifyQuery &amp;Q)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See if we can fold the given phi. If not, returns null. <a href="#a308de6b87d4d431477642d086b268a7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac91d6fa292dc4e13ce99fc9f02c90f85">foldIdentityShuffles</a> (int DestElt, Value *Op0, Value *Op1, int MaskVal, Value *RootVec, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the given destination element of a shuffle, peek through shuffles to match a root vector source operand that contains that element in the same vector lane (ie, the same mask index), so we can eliminate the shuffle(s). <a href="#ac91d6fa292dc4e13ce99fc9f02c90f85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bf04415ab72b83b24140635c6a7ea52">simplifyShuffleVectorInst</a> (Value *Op0, Value *Op1, ArrayRef&lt; int &gt; Mask, Type *RetTy, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a6e468202ea1fafcd8163afbe034823">foldConstant</a> (Instruction::UnaryOps Opcode, Value *&amp;Op, const SimplifyQuery &amp;Q)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81185b0eeb96c7354756478f505f9ec8">simplifyFNegInst</a> (Value *Op, FastMathFlags FMF, const SimplifyQuery &amp;Q, unsigned MaxRecurse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given the operand for an FNeg, see if we can fold the result. <a href="#a81185b0eeb96c7354756478f505f9ec8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20728ab5a970c250099d56e721746064">propagateNaN</a> (Constant *In)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to propagate existing NaN values when possible. <a href="#a20728ab5a970c250099d56e721746064">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6498365e4fa2bc006fc4116b4b9b990">simplifyFPOp</a> (ArrayRef&lt; Value * &gt; Ops, FastMathFlags FMF, const SimplifyQuery &amp;Q, fp::ExceptionBehavior ExBehavior, RoundingMode Rounding)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform folds that are common to any floating-point operation. <a href="#aa6498365e4fa2bc006fc4116b4b9b990">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68091149082c7a34c2198012a0800d6d">simplifyFAddInst</a> (Value *Op0, Value *Op1, FastMathFlags FMF, const SimplifyQuery &amp;Q, unsigned MaxRecurse, fp::ExceptionBehavior ExBehavior=fp::ebIgnore, RoundingMode Rounding=RoundingMode::NearestTiesToEven)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for an FAdd, see if we can fold the result. <a href="#a68091149082c7a34c2198012a0800d6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a357829c347a3ab1d10dced5dbeb27a">simplifyFSubInst</a> (Value *Op0, Value *Op1, FastMathFlags FMF, const SimplifyQuery &amp;Q, unsigned MaxRecurse, fp::ExceptionBehavior ExBehavior=fp::ebIgnore, RoundingMode Rounding=RoundingMode::NearestTiesToEven)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for an FSub, see if we can fold the result. <a href="#a9a357829c347a3ab1d10dced5dbeb27a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b47854a993004418cb56068fe2dd9dd">simplifyFMAFMul</a> (Value *Op0, Value *Op1, FastMathFlags FMF, const SimplifyQuery &amp;Q, unsigned MaxRecurse, fp::ExceptionBehavior ExBehavior, RoundingMode Rounding)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adde5a4e7e2382910bdfbd89dd30671a8">simplifyFMulInst</a> (Value *Op0, Value *Op1, FastMathFlags FMF, const SimplifyQuery &amp;Q, unsigned MaxRecurse, fp::ExceptionBehavior ExBehavior=fp::ebIgnore, RoundingMode Rounding=RoundingMode::NearestTiesToEven)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given the operands for an FMul, see if we can fold the result. <a href="#adde5a4e7e2382910bdfbd89dd30671a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ae2d2701ffe4abf529cd4fb1ca26049">simplifyFDivInst</a> (Value *Op0, Value *Op1, FastMathFlags FMF, const SimplifyQuery &amp;Q, unsigned, fp::ExceptionBehavior ExBehavior=fp::ebIgnore, RoundingMode Rounding=RoundingMode::NearestTiesToEven)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95596f2a72e57df0c710e3dc7b225597">simplifyFRemInst</a> (Value *Op0, Value *Op1, FastMathFlags FMF, const SimplifyQuery &amp;Q, unsigned, fp::ExceptionBehavior ExBehavior=fp::ebIgnore, RoundingMode Rounding=RoundingMode::NearestTiesToEven)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f39d8494e80ff534547de5b51a30623">isIdempotent</a> (Intrinsic::ID ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a796b1851dc68b49eaeeeb7af4ff3f74b">removesFPFraction</a> (Intrinsic::ID ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the intrinsic rounds a floating-point value to an integral floating-point value (not an integer type). <a href="#a796b1851dc68b49eaeeeb7af4ff3f74b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c78ae45454d731f51f0ce021a729816">simplifyRelativeLoad</a> (Constant *Ptr, Constant *Offset, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6fe80e6f4b357ca0fdc9eafa69c430f">simplifyLdexp</a> (Value *Op0, Value *Op1, const SimplifyQuery &amp;Q, bool IsStrict)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd74672cec2bec4f18c103c4cb7823d4">simplifyUnaryIntrinsic</a> (Function *F, Value *Op0, const SimplifyQuery &amp;Q, const CallBase *Call)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c67f3e7a3e50c0f051a8678d6de6f8d">foldMinMaxSharedOp</a> (Intrinsic::ID IID, Value *Op0, Value *Op1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a min/max intrinsic, see if it can be removed based on having an operand that is another min/max intrinsic with shared operand(s). <a href="#a0c67f3e7a3e50c0f051a8678d6de6f8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc7e209dff60b7e47879648c18d55745">foldMinimumMaximumSharedOp</a> (Intrinsic::ID IID, Value *Op0, Value *Op1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a min/max intrinsic, see if it can be removed based on having an operand that is another min/max intrinsic with shared operand(s). <a href="#afc7e209dff60b7e47879648c18d55745">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a554988e4897106ec290097646fd1a84e">simplifyIntrinsic</a> (CallBase *Call, Value *Callee, ArrayRef&lt; Value * &gt; Args, const SimplifyQuery &amp;Q)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4394b9bd9afc3ae5f5477e8c265d8b0e">tryConstantFoldCall</a> (CallBase *Call, Value *Callee, ArrayRef&lt; Value * &gt; Args, const SimplifyQuery &amp;Q)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0160b3b9cc2d97a29656003dc77f189e">simplifyFreezeInst</a> (Value *Op0, const SimplifyQuery &amp;Q)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given operands for a Freeze, see if we can fold the result. <a href="#a0160b3b9cc2d97a29656003dc77f189e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7071d5024d9df2ab2086cccd673f002">replaceAndRecursivelySimplifyImpl</a> (Instruction *I, Value *SimpleV, const TargetLibraryInfo *TLI, const DominatorTree *DT, AssumptionCache *AC, SmallSetVector&lt; Instruction *, 8 &gt; *UnsimplifiedUsers=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementation of recursive simplification through an instruction's uses. <a href="#aa7071d5024d9df2ab2086cccd673f002">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"instsimplify"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab17cd64831c782d0a73555e5b2bf4bc3">HANDLE_CAST_INST</a>(num, opc, clas)&nbsp;&nbsp;&nbsp;case Instruction::opc:</td>
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


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a30dc1111ec80f24c21b7ea4e7e6df202}

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


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RecursionLimit<a id="a30dc1111ec80f24c21b7ea4e7e6df202ad86c5f61eff3b493d5beab893f054a57"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>

</div>
</div>

### MonotonicType {#a4fa5495dc2ca57889c6cf2fd8bba50ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class MonotonicType </td>
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


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GreaterEq<a id="a4fa5495dc2ca57889c6cf2fd8bba50efadc68720e1e33df4d3546cd1aa63143c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LowerEq<a id="a4fa5495dc2ca57889c6cf2fd8bba50efa2a0b03b794ee59bcb81977eda463e721"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 3043 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### computePointerDifference() {#adc235173f78d0b2a260bb5438267139e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * computePointerDifference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS)</td>
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

<p>Compute the constant difference between two pointer values.</p>


<p>If the difference is not a constant, returns zero.</p>


<p>Definition at line 684 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#aa3b241b35b0039b413faf1ef4e873eb7">llvm::ConstantVector::getSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a59cd1a000769414b2d832576bf689c32">stripAndComputeConstantOffsets</a>.</p>


<p>Referenced by <a href="#a0e278bb318fd700a9c8d4f4a7c8caba9">simplifySubInst</a>.</p>

</div>
</div>

### computePointerICmp() {#aec29f5580509ec9a7592200e09b7aa27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * computePointerICmp (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q)</td>
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



<p>Definition at line 2683 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/capturetracker/#ae3425ae1022a2f2713b0047bb12a468d">llvm::CaptureTracker::captured</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a5769f1da829d6f6400b486d8e34e317f">llvm::ICmpInst::compare</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/objectsizeopts/#a0c614185ae8ad5ed7bd5ff0aa66f8242">llvm::ObjectSizeOpts::EvalMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#abee3cf86c05d2369d387f07f7055b9dc">getCompareTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62ba0e5ee2d86f663c6de4efda6082a7">llvm::getObjectSize</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a9d5f70171d811078c4d263811f13c121">llvm::ICmpInst::getSignedPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc66c148bcd950ffcc3ab83989eb70bd">llvm::getUnderlyingObjects</a>, <a href="#a1766fdfd6561f8585dca1ac3f867399c">haveNonOverlappingStorage</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#aa9fb01a51417407eb7de1dff943c27e3">isAllocDisjoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a56641197c50e1c7a9558446d14deadb3">llvm::isAllocLikeFn</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#aaaeded5d0cab77f531b294638459aca5">llvm::ICmpInst::isEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a1e32582702cf5b9d4484c0ce346b2f57">llvm::CmpInst::isFalseWhenEqual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9893e3e4b14f8fa15d7c3c25a6a0b6f6">llvm::isKnownNonZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a433468826ef20b5ddb53704fc38363fc">llvm::isNoAliasCall</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac8c0157adbe12649beac0009c2f6ad8d">llvm::APInt::isNonNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a5ba8484cef2818d14b85640a903b2598">llvm::CmpInst::isTrueWhenEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/objectsizeopts/#a77eec32ab6be9e75a4b1f7cd5c4e5b8ea78d811e98514cd165dda532286610fd2">llvm::ObjectSizeOpts::Min</a>, <a href="/web-llvm/docs/api/structs/llvm/objectsizeopts/#a0229c5396522e5a903a277fda4c3659c">llvm::ObjectSizeOpts::NullIsUnknownSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b03ed78a8e299bde6d26a8793cd4e06">llvm::NullPointerIsDefined</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7912b6c9e7843ca9fd5a11e199bef617">llvm::PointerMayBeCaptured</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#aaf09fd551f7b18f7c75c662a8a8ed040">llvm::SimplifyQuery::TLI</a>, <a href="/web-llvm/docs/api/structs/llvm/capturetracker/#a736d928ff83259d1318e7f3bd079cfa8">llvm::CaptureTracker::tooManyUses</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a545e8d5dfa1688acea0d0e275b03682f">llvm::APInt::ult</a>.</p>


<p>Referenced by <a href="#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>.</p>

</div>
</div>

### expandBinOp() {#a6d9999d61310781a41074a967e885f12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * expandBinOp (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OtherOp, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> OpcodeToExpand, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Try to simplify a binary operator of form "V op OtherOp" where V is "(B0 opex B1)" by distributing 'op' across 'opex' as "(B0 op OtherOp) opex (B1 op OtherOp)".</p>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#aba451d2306d849c2ca6821dfe84587a9">llvm::SimplifyQuery::getWithoutUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a55743bd32282bf6f87aeb49237b1fb68">llvm::Instruction::isCommutative</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa750395459fa1eb7130d6de8e3d074f6">llvm::simplifyBinOp</a>.</p>


<p>Referenced by <a href="#a1588904a0310f8239c38e8790a1f1ca0">expandCommutativeBinOp</a>.</p>

</div>
</div>

### expandCommutativeBinOp() {#a1588904a0310f8239c38e8790a1f1ca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * expandCommutativeBinOp (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * L, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * R, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> OpcodeToExpand, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Try to simplify binops of form "A op (B op' C)" or the commuted variant by distributing op over op'.</p>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>Reference <a href="#a6d9999d61310781a41074a967e885f12">expandBinOp</a>.</p>


<p>Referenced by <a href="#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="#a7f2df18bfd941b2e8d1cd78db5beb6f7">simplifyMulInst</a> and <a href="#a845e93029e92776841aaf5e0ec4c812f">simplifyOrInst</a>.</p>

</div>
</div>

### extractEquivalentCondition() {#ad38d439eec395362c9cfce6c92751677}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * extractEquivalentCondition (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS)</td>
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

<p>Rummage around inside V looking for something equivalent to the comparison "LHS Pred RHS".</p>


<p>Return such a value if found, otherwise return null. Helper function for analyzing max/min idioms.</p>


<p>Definition at line 2574 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a4f8adcab536e4c9f42e148d7eb218e6a">simplifyICmpWithMinMax</a>.</p>

</div>
</div>

### foldConstant() {#a1a6e468202ea1fafcd8163afbe034823}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * foldConstant (<a href="/web-llvm/docs/api/classes/llvm/instruction/#af9f57a32b08304fea642871735717f24">Instruction::UnaryOps</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q)</td>
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



<p>Definition at line 5579 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6810c4cb05b49909862249d3b3afa2af">llvm::ConstantFoldUnaryOpOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#a5b47854a993004418cb56068fe2dd9dd">simplifyFMAFMul</a>, <a href="#a81185b0eeb96c7354756478f505f9ec8">simplifyFNegInst</a> and <a href="#a9a357829c347a3ab1d10dced5dbeb27a">simplifyFSubInst</a>.</p>

</div>
</div>

### foldIdentityShuffles() {#ac91d6fa292dc4e13ce99fc9f02c90f85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * foldIdentityShuffles (int DestElt, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, int MaskVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RootVec, unsigned MaxRecurse)</td>
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

<p>For the given destination element of a shuffle, peek through shuffles to match a root vector source operand that contains that element in the same vector lane (ie, the same mask index), so we can eliminate the shuffle(s).</p>

<p>Definition at line 5412 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ac91d6fa292dc4e13ce99fc9f02c90f85">foldIdentityShuffles</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="#ac91d6fa292dc4e13ce99fc9f02c90f85">foldIdentityShuffles</a> and <a href="#a0bf04415ab72b83b24140635c6a7ea52">simplifyShuffleVectorInst</a>.</p>

</div>
</div>

### foldMinimumMaximumSharedOp() {#afc7e209dff60b7e47879648c18d55745}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * foldMinimumMaximumSharedOp (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IID, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1)</td>
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

<p>Given a min/max intrinsic, see if it can be removed based on having an operand that is another min/max intrinsic with shared operand(s).</p>


<p>The caller is expected to swap the operand arguments to handle commutation.</p>


<p>Definition at line 6428 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0434306df3aa5ec48fcf19d0958d7c01">llvm::getInverseMinMaxIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab8aff98d3587ddb15f9e46ed88687f0f">llvm::M0</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a58328e0582aabaf012bf9bc6f36c9e04">llvm::M1</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab720ac4c86a5f16a755b1e5cd0d32c80">llvm::simplifyBinaryIntrinsic</a>.</p>

</div>
</div>

### foldMinMaxSharedOp() {#a0c67f3e7a3e50c0f051a8678d6de6f8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * foldMinMaxSharedOp (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IID, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1)</td>
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

<p>Given a min/max intrinsic, see if it can be removed based on having an operand that is another min/max intrinsic with shared operand(s).</p>


<p>The caller is expected to swap the operand arguments to handle commutation.</p>


<p>Definition at line 6403 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0434306df3aa5ec48fcf19d0958d7c01">llvm::getInverseMinMaxIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a9d30ca764aa6f22f9812bc52abb69207">llvm::PatternMatch::m_c_MaxOrMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ad1e2bbf1a8ae559791b42b649d06bbd0">llvm::PatternMatch::m_MaxOrMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab720ac4c86a5f16a755b1e5cd0d32c80">llvm::simplifyBinaryIntrinsic</a>.</p>

</div>
</div>

### foldOrCommuteConstant() {#a15df887e1ad05e6c22a7c2e6492bde2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * foldOrCommuteConstant (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q)</td>
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



<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a964455f36837281d37f2a44e2fcb4cca">llvm::ConstantFoldBinaryOpOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1934978a43ce45ca0ec7b837e31d4ebc">llvm::ConstantFoldFPInstOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a30647c42c8c40890c577ba5b4ab16468">llvm::SimplifyQuery::CxtI</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a55743bd32282bf6f87aeb49237b1fb68">llvm::Instruction::isCommutative</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#a3a8f0d83fd0c16251206c0d0f3e78174">simplifyAddInst</a>, <a href="#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="#a2d67c7fd2789ef1dfb05513f1eb8d054">simplifyDiv</a>, <a href="#a68091149082c7a34c2198012a0800d6d">simplifyFAddInst</a>, <a href="#a7ae2d2701ffe4abf529cd4fb1ca26049">simplifyFDivInst</a>, <a href="#adde5a4e7e2382910bdfbd89dd30671a8">simplifyFMulInst</a>, <a href="#a95596f2a72e57df0c710e3dc7b225597">simplifyFRemInst</a>, <a href="#a9a357829c347a3ab1d10dced5dbeb27a">simplifyFSubInst</a>, <a href="#a7f2df18bfd941b2e8d1cd78db5beb6f7">simplifyMulInst</a>, <a href="#a845e93029e92776841aaf5e0ec4c812f">simplifyOrInst</a>, <a href="#aed163588354401b6679a39acad6fae2a">simplifyRem</a>, <a href="#ae9d2883e296d808c7a9e18efcee71049">simplifyShift</a>, <a href="#a0e278bb318fd700a9c8d4f4a7c8caba9">simplifySubInst</a> and <a href="#a9cfeea050198084d67109f0260e33970">simplifyXorInst</a>.</p>

</div>
</div>

### getCompareTy() {#abee3cf86c05d2369d387f07f7055b9dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * getCompareTy (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op)</td>
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



<p>Definition at line 2567 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a0206e74dec02d952d1b620a7b63f5694">llvm::CmpInst::makeCmpResultType</a>.</p>


<p>Referenced by <a href="#aec29f5580509ec9a7592200e09b7aa27">computePointerICmp</a>, <a href="#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a>, <a href="#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>, <a href="#a22aa6a5c92a8a6cbb5437123d7e069e6">simplifyICmpOfBools</a>, <a href="#adae506d280d297474e74be7d5d1b9762">simplifyICmpUsingMonotonicValues</a>, <a href="#a64cb0c5ab10b63f22110e1b0183a648f">simplifyICmpWithBinOp</a>, <a href="#a28e9b56583c0f73543606d22bfac472e">simplifyICmpWithBinOpOnLHS</a>, <a href="#a7520bc5124cf32bdbb659ae6fc12cf9c">simplifyICmpWithConstant</a>, <a href="#ae9417447cf23234d645221bda42e00c4">simplifyICmpWithDominatingAssume</a>, <a href="#a5e2e121dcbec9a2ede54e53ba8be83d4">simplifyICmpWithIntrinsicOnLHS</a>, <a href="#a4f8adcab536e4c9f42e148d7eb218e6a">simplifyICmpWithMinMax</a> and <a href="#a738d3c4d8f36cf843825c2b5a878f58a">simplifyICmpWithZero</a>.</p>

</div>
</div>

### getFalse() {#a774f686ad651b962a54ad231e2212f64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * getFalse (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>For a boolean type or a vector of boolean type, return false or a vector with every element false.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>.</p>


<p>Referenced by <a href="#a496b149294586554f0cd9fd240d8d80d">simplifyAndOfICmpsWithAdd</a>, <a href="#ae5781faa80a27cf51fa316feaa2ad363">simplifyAndOrOfICmpsWithConstants</a>, <a href="#a022b0d31de4686085b7c8d2719a3edd7">simplifyCmpSelFalseCase</a>, <a href="#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a>, <a href="#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>, <a href="#a22aa6a5c92a8a6cbb5437123d7e069e6">simplifyICmpOfBools</a>, <a href="#a28e9b56583c0f73543606d22bfac472e">simplifyICmpWithBinOpOnLHS</a>, <a href="#a4f8adcab536e4c9f42e148d7eb218e6a">simplifyICmpWithMinMax</a>, <a href="#a738d3c4d8f36cf843825c2b5a878f58a">simplifyICmpWithZero</a> and <a href="#a4355ad633eda8e7c8a6538ea41bb34f3">simplifyUnsignedRangeCheck</a>.</p>

</div>
</div>

### getRange() {#a407852423447c9c318189650976659fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ConstantRange &gt; getRange (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery">InstrInfoQuery</a> &amp; IIQ)</td>
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

<p>Helper method to get range from metadata or attribute.</p>

<p>Definition at line 3726 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5193c3535375c450b9430e5671cbeb2d">llvm::getConstantRangeFromMetadata</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#a312d7ea4a3b571129e9a279a18635ed2">llvm::InstrInfoQuery::getMetadata</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#aa116214bf0f5cf6201935447b27334e8">getFromRangeMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a3756185351596750edbb4790d9923eea">llvm::SelectionDAGBuilder::lowerRangeToAssertZExt</a> and <a href="#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>.</p>

</div>
</div>

### getTrue() {#aaa375e5211d9e07739a374c0479fb0ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * getTrue (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>For a boolean type or a vector of boolean type, return true or a vector with every element true.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>.</p>


<p>Referenced by <a href="#ae5781faa80a27cf51fa316feaa2ad363">simplifyAndOrOfICmpsWithConstants</a>, <a href="#a5211abbd14c49ebe208e93000a365ef0">simplifyCmpSelTrueCase</a>, <a href="#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a>, <a href="#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>, <a href="#a22aa6a5c92a8a6cbb5437123d7e069e6">simplifyICmpOfBools</a>, <a href="#a28e9b56583c0f73543606d22bfac472e">simplifyICmpWithBinOpOnLHS</a>, <a href="#a4f8adcab536e4c9f42e148d7eb218e6a">simplifyICmpWithMinMax</a>, <a href="#a738d3c4d8f36cf843825c2b5a878f58a">simplifyICmpWithZero</a>, <a href="#a7b473dc0c6603bb29f38c46858df840e">simplifyOrOfICmpsWithAdd</a> and <a href="#a4355ad633eda8e7c8a6538ea41bb34f3">simplifyUnsignedRangeCheck</a>.</p>

</div>
</div>

### getUnsignedMonotonicValues() {#a57d8791ae7f26ddfe185e3d40b8f9c90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void getUnsignedMonotonicValues (<a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; Res, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="#a4fa5495dc2ca57889c6cf2fd8bba50ef">MonotonicType</a> Type, unsigned Depth=0)</td>
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

<p>Get values V_i such that V uge V_i (GreaterEq) or V ule V_i (LowerEq).</p>

<p>Definition at line 3046 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a57d8791ae7f26ddfe185e3d40b8f9c90">getUnsignedMonotonicValues</a>, <a href="#a4fa5495dc2ca57889c6cf2fd8bba50efadc68720e1e33df4d3546cd1aa63143c3">GreaterEq</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#a4fa5495dc2ca57889c6cf2fd8bba50efa2a0b03b794ee59bcb81977eda463e721">LowerEq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae44af1eeb2e5f7a1973a4ab78963a503">llvm::PatternMatch::m_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="#a57d8791ae7f26ddfe185e3d40b8f9c90">getUnsignedMonotonicValues</a> and <a href="#adae506d280d297474e74be7d5d1b9762">simplifyICmpUsingMonotonicValues</a>.</p>

</div>
</div>

### handleOtherCmpSelSimplifications() {#a1b14bc4633dc9ebd06733a8792510cbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * handleOtherCmpSelSimplifications (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * TCmp, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * FCmp, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>We know comparison with both branches of select can be simplified, but they are not equal.</p>


<p>This routine handles some logical simplifications.</p>


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71a4a4e0f6178682ef05a0d85891e5a9">llvm::impliesPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3b3d2d8c64a7881acb82bc7467569aa9">llvm::PatternMatch::m_One</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f751e3ed5adc61048480e9fd0e257cc">llvm::simplifyAndInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4f2dc2393a7799e74a0ab4aaa96783f6">llvm::simplifyOrInst</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4f6b08837306196c6ff45fc5c65fe815">llvm::simplifyXorInst</a>.</p>


<p>Referenced by <a href="#aa6faca61824779a7d72a2c1e08b9e7a0">threadCmpOverSelect</a>.</p>

</div>
</div>

### haveNonOverlappingStorage() {#a1766fdfd6561f8585dca1ac3f867399c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool haveNonOverlappingStorage (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2)</td>
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

<p>Return true if V1 and V2 are each the base of some distict storage region [V, object_size(V)] which do not overlap.</p>


<p>Note that zero sized regions <em>are</em> possible, and that zero sized regions do not overlap with any other.</p>


<p>Definition at line 2613 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#aec29f5580509ec9a7592200e09b7aa27">computePointerICmp</a>.</p>

</div>
</div>

### isAllocDisjoint() {#aa9fb01a51417407eb7de1dff943c27e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isAllocDisjoint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Return true if the underlying object (storage) must be disjoint from storage returned by any noalias return call.</p>

<p>Definition at line 2593 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#aec29f5580509ec9a7592200e09b7aa27">computePointerICmp</a>.</p>

</div>
</div>

### isDivZero() {#ab29fdeb7689892b6496576ca70cfc625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isDivZero (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * X, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Y, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse, bool IsSigned)</td>
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

<p>Return true if we can simplify X / Y to 0.</p>


<p>Remainder can adapt that answer to simplify X % Y to X.</p>


<p>Definition at line 975 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="#ac21f987259846006ea150eb82ff069df">isICmpTrue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#adcb2d072d003fbb84707d09dd3d2bcff">llvm::PatternMatch::m_SRem</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="#a789b1341fc862e30623b200657911a4c">simplifyDivRem</a>.</p>

</div>
</div>

### isICmpTrue() {#ac21f987259846006ea150eb82ff069df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isICmpTrue (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given a predicate and two operands, return true if the comparison is true.</p>


<p>This is a helper for div/rem simplification where we return some other value when we can prove a relationship between the operands.</p>


<p>Definition at line 966 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a83813cbf71633220ae57ad2b79498f77">llvm::simplifyICmpInst</a>.</p>


<p>Referenced by <a href="#ab29fdeb7689892b6496576ca70cfc625">isDivZero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab720ac4c86a5f16a755b1e5cd0d32c80">llvm::simplifyBinaryIntrinsic</a>.</p>

</div>
</div>

### isIdempotent() {#a3f39d8494e80ff534547de5b51a30623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isIdempotent (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> ID)</td>
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



<p>Definition at line 6144 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>Referenced by <a href="#afd74672cec2bec4f18c103c4cb7823d4">simplifyUnaryIntrinsic</a>.</p>

</div>
</div>

### isPoisonShift() {#a587eab2c520053bb06fdc4afe5a57aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isPoisonShift (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Amount, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q)</td>
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

<p>Returns true if a shift by <span class="doxyComputerOutput">Amount</span> always yields poison.</p>

<p>Definition at line 1266 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a587eab2c520053bb06fdc4afe5a57aa3">isPoisonShift</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#af4b1ccc0b78f9da9f3f3944e06007f1d">llvm::APInt::uge</a>.</p>


<p>Referenced by <a href="#a587eab2c520053bb06fdc4afe5a57aa3">isPoisonShift</a> and <a href="#ae9d2883e296d808c7a9e18efcee71049">simplifyShift</a>.</p>

</div>
</div>

### isSameCompare() {#a3e2c41b46422f8392e87d92a2f8e9d3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isSameCompare (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS)</td>
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

<p>isSameCompare - Is V equivalent to the comparison "LHS Pred RHS"?</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a04cf98272b39e1eef023148e1499b1fc">simplifyCmpSelCase</a>.</p>

</div>
</div>

### propagateNaN() {#a20728ab5a970c250099d56e721746064}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * propagateNaN (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * In)</td>
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

<p>Try to propagate existing NaN values when possible.</p>


<p>If not, replace the constant or elements in the constant with a canonical NaN.</p>


<p>Definition at line 5608 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#ade9fa017ca3aa82f7694a47090547bc1">llvm::ConstantVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#ab21342133676f10340dc3f541b128f24">llvm::ConstantFP::getNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aabb53b9354c612fd43fa47b8266114d6">llvm::Constant::isNaN</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a5b9bf50c6579a978e5c1104bf8787651">llvm::Splat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab720ac4c86a5f16a755b1e5cd0d32c80">llvm::simplifyBinaryIntrinsic</a> and <a href="#aa6498365e4fa2bc006fc4116b4b9b990">simplifyFPOp</a>.</p>

</div>
</div>

### removesFPFraction() {#a796b1851dc68b49eaeeeb7af4ff3f74b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool removesFPFraction (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> ID)</td>
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

<p>Return true if the intrinsic rounds a floating-point value to an integral floating-point value (not an integer type).</p>

<p>Definition at line 6166 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>Referenced by <a href="#afd74672cec2bec4f18c103c4cb7823d4">simplifyUnaryIntrinsic</a>.</p>

</div>
</div>

### replaceAndRecursivelySimplifyImpl() {#aa7071d5024d9df2ab2086cccd673f002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool replaceAndRecursivelySimplifyImpl (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SimpleV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 8 &gt; * UnsimplifiedUsers=nullptr)</td>
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

<p>Implementation of recursive simplification through an instruction's uses.</p>


<p>This is the common implementation of the recursive simplification routines. If we have a pre-simplified value in 'SimpleV', that is forcibly used to replace the instruction 'I'. Otherwise, we simply add 'I' to the list of instructions to process and attempt to simplify it using InstructionSimplify. Recursively visited users which could not be simplified themselves are to the optional UnsimplifiedUsers set for further processing by the caller.</p>


<p>This routine returns 'true' only when <em>it</em> simplifies something. The passed in simplified value does not count toward this.</p>


<p>Definition at line 7262 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57feb935aaafd1bd4bfbb8dc56ad2129">llvm::simplifyInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a66a40e8dfb026aef2f90764d2e49a8f1">llvm::replaceAndRecursivelySimplify</a>.</p>

</div>
</div>

### simplifyAddInst() {#a3a8f0d83fd0c16251206c0d0f3e78174}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyAddInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, bool IsNSW, bool IsNUW, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for an Add, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a15df887e1ad05e6c22a7c2e6492bde2d">foldOrCommuteConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a34ee40bb2f4f5ece47ef19e5f1f57e3c">llvm::Type::isIntOrIntVectorTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae35d199ef2ac7fc6d6a5294aa8070a9e">llvm::isKnownNegation</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a00ef056813d120034e387417e9cde341">llvm::PatternMatch::m_AllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0c2ec502cbe0e39c4b7641f648b3a615">llvm::PatternMatch::m_SignMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af5c293ba602295963ee06dd6f22e6335">llvm::PatternMatch::m_Sub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1cacb72e897c55bdfd5c726d13d69af1">llvm::PatternMatch::m_Xor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="#a8863b1b71b53dbab1dd0bd7933ddb3cf">simplifyAssociativeBinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4f6b08837306196c6ff45fc5c65fe815">llvm::simplifyXorInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### simplifyAndCommutative() {#a3eefa98bc7f6c24b6f1fa0bb220a77a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyAndCommutative (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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



<p>Definition at line 1972 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a928ce56952772d0e0f43cab3a489a6fe">llvm::SimplifyQuery::AC</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a30647c42c8c40890c577ba5b4ab16468">llvm::SimplifyQuery::CxtI</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a4776fa0f5a726bd5a8a444981c283c69">llvm::SimplifyQuery::DT</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aebd66f6649c1449adbcfcedf1651af18">llvm::isCheckForZeroAndMulWithOverflow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4036c3c75bcee1206cd199548b87f9ae">llvm::isKnownToBeAPowerOfTwo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a062ccd76a126632721e9aa09775d6c0e">llvm::PatternMatch::m_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a00ef056813d120034e387417e9cde341">llvm::PatternMatch::m_AllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae80cbfea2025ff7bd0770f30be6e050a">llvm::PatternMatch::m_c_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5d295dcffba83c3c5a17d2fb3273b434">llvm::PatternMatch::m_Neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ac1c7b78fe67245930be18441b77de500">llvm::PatternMatch::m_Shl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="#ae739737036faaf1bcaa66a0f4a8e1e63">simplifyAndOrWithICmpEq</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af4b1ccc0b78f9da9f3f3944e06007f1d">llvm::APInt::uge</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>.</p>

</div>
</div>

### simplifyAndInst() {#ac90052ea1afde8fc28fe6f27181fd5f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyAndInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for an And, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 2025 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a928ce56952772d0e0f43cab3a489a6fe">llvm::SimplifyQuery::AC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a70674aa792d906276123ab69dbdbfc69">llvm::KnownBits::countMaxActiveBits</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a30647c42c8c40890c577ba5b4ab16468">llvm::SimplifyQuery::CxtI</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a4776fa0f5a726bd5a8a444981c283c69">llvm::SimplifyQuery::DT</a>, <a href="#a1588904a0310f8239c38e8790a1f1ca0">expandCommutativeBinOp</a>, <a href="#a15df887e1ad05e6c22a7c2e6492bde2d">foldOrCommuteConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3015474e70e59c0a3ed4f9f0e8644b75">llvm::APInt::getActiveBits</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab01d8694a759a934e01f1c558c3ce862">llvm::APInt::getLimitedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad960e1ff48d25c382b6d28e7961f074e">llvm::APInt::getLowBitsSet</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a825476b2436eb817b735fdd34ee521c4">llvm::KnownBits::getMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#ad029c8abde2f42c8d5837bd5515bb18e">llvm::SimplifyQuery::IIQ</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a6da514c588b2668280a861a59bfc9fa5">llvm::APInt::intersects</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7f2eb961a542779e97c0b3ec7fa6623">llvm::isImpliedCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a34ee40bb2f4f5ece47ef19e5f1f57e3c">llvm::Type::isIntOrIntVectorTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4036c3c75bcee1206cd199548b87f9ae">llvm::isKnownToBeAPowerOfTwo</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acfae9bdee6027ffa8ffe244cc22e3a76">llvm::APInt::isSubsetOf</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a062ccd76a126632721e9aa09775d6c0e">llvm::PatternMatch::m_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a00ef056813d120034e387417e9cde341">llvm::PatternMatch::m_AllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0698afabe907d2d3b87889d2e0349d47">llvm::PatternMatch::m_BinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae80cbfea2025ff7bd0770f30be6e050a">llvm::PatternMatch::m_c_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a4e2ffa92003f2eca82197ea662b30f16">llvm::PatternMatch::m_c_Xor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a469c3ed35e782000933c996ccd2d2333">llvm::PatternMatch::m_CombineAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a53fc7d443cf6412add6dfddd11652e5d">llvm::PatternMatch::m_Deferred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab8546ee1aaa68d6f4990e6241e24464c">llvm::PatternMatch::m_LShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a6d0a54a00095759d9be803abe46e2fad">llvm::PatternMatch::m_NUWShl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a103f4e50bfeab3d598adc56e1235c241">llvm::PatternMatch::m_Power2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3ccd94f6a7507492b47c7351e3fb78c6">llvm::PatternMatch::m_Select</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ac1c7b78fe67245930be18441b77de500">llvm::PatternMatch::m_Shl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2471be3f1b50002f54bf45c590d8d41b">llvm::PatternMatch::m_SpecificInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1cacb72e897c55bdfd5c726d13d69af1">llvm::PatternMatch::m_Xor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a>, <a href="#a3eefa98bc7f6c24b6f1fa0bb220a77a4">simplifyAndCommutative</a>, <a href="#ad4122a9286a8dd18458df1f47230e07f">simplifyAndOrOfCmps</a>, <a href="#a8863b1b71b53dbab1dd0bd7933ddb3cf">simplifyAssociativeBinOp</a>, <a href="#a6343e645572ce8783bbf5853d181479f">simplifyByDomEq</a>, <a href="#ab8c09431e3ba6ccd88dfa4a32c2127be">simplifyLogicOfAddSub</a>, <a href="#a914ac5681f80badb866f2aee44fc509a">threadBinOpOverPHI</a>, <a href="#ada3f0c65b41a26f74d332e974164ce55">threadBinOpOverSelect</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#a9f2a11175d1af9d1bf62666c50c60145">llvm::InstrInfoQuery::UseInstrInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### simplifyAndOfICmps() {#ac1907d1fccfb9846bfd91b6b79c0acbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyAndOfICmps (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q)</td>
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



<p>Definition at line 1721 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#ad029c8abde2f42c8d5837bd5515bb18e">llvm::SimplifyQuery::IIQ</a>, <a href="#a496b149294586554f0cd9fd240d8d80d">simplifyAndOfICmpsWithAdd</a>, <a href="#ae5781faa80a27cf51fa316feaa2ad363">simplifyAndOrOfICmpsWithConstants</a>, <a href="#a426204f20670379cdefabed663ac339f">simplifyAndOrOfICmpsWithCtpop</a>, <a href="#a4355ad633eda8e7c8a6538ea41bb34f3">simplifyUnsignedRangeCheck</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#ad4122a9286a8dd18458df1f47230e07f">simplifyAndOrOfCmps</a>.</p>

</div>
</div>

### simplifyAndOfICmpsWithAdd() {#a496b149294586554f0cd9fd240d8d80d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyAndOfICmpsWithAdd (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery">InstrInfoQuery</a> &amp; IIQ)</td>
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



<p>Definition at line 1653 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac0e942dde4b113c4c0b1fd76333db93a">llvm::APInt::getBoolValue</a>, <a href="#a774f686ad651b962a54ad231e2212f64">getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#a879785896627e7415e7aee7934bf922b">llvm::InstrInfoQuery::hasNoSignedWrap</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#affcd96f408768d8c1849b5293579143d">llvm::InstrInfoQuery::hasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aa17c104fbda554c818cf87e53f32f20a">llvm::APInt::isStrictlyPositive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a062ccd76a126632721e9aa09775d6c0e">llvm::PatternMatch::m_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab86c85b47e09489dcda68fd91d082d77">llvm::PatternMatch::m_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="#ac1907d1fccfb9846bfd91b6b79c0acbc">simplifyAndOfICmps</a>.</p>

</div>
</div>

### simplifyAndOrOfCmps() {#ad4122a9286a8dd18458df1f47230e07f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyAndOrOfCmps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, bool IsAnd)</td>
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



<p>Definition at line 1855 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bf77c90e2fb57af4d4d4aab084f7052">llvm::ConstantFoldCastOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ac1907d1fccfb9846bfd91b6b79c0acbc">simplifyAndOfICmps</a>, <a href="#acb8e54b9f6be2fdb87b369c2218db1cc">simplifyAndOrOfFCmps</a> and <a href="#a6b86bbc17cbb2be2b63a54fcdbcf4251">simplifyOrOfICmps</a>.</p>


<p>Referenced by <a href="#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a> and <a href="#a845e93029e92776841aaf5e0ec4c812f">simplifyOrInst</a>.</p>

</div>
</div>

### simplifyAndOrOfFCmps() {#acb8e54b9f6be2fdb87b369c2218db1cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyAndOrOfFCmps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, <a href="/web-llvm/docs/api/classes/llvm/fcmpinst">FCmpInst</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/fcmpinst">FCmpInst</a> * RHS, bool IsAnd)</td>
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



<p>Definition at line 1814 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa3213b645e029aba8bb1b85213607d5e">llvm::CmpInst::FCMP_ORD</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed">llvm::CmpInst::FCMP_UNO</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#afe7d477c6022fe7123b90e3b39c58e69">llvm::ConstantInt::getBool</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ad91c80980a394e9c81f04e8988261224">llvm::CmpInst::isOrdered</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aae55ea42185b7528c0c149625b998968">llvm::CmpInst::isUnordered</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#afc43bc5ec4b20c7c5d663bef90da6066">llvm::PatternMatch::m_CombineOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af07397df05f8eb1838b6d79871791e38">llvm::PatternMatch::m_FAbs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#abb2f21cbe7164d435978845d73de1a83">llvm::PatternMatch::m_PosZeroFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#ad4122a9286a8dd18458df1f47230e07f">simplifyAndOrOfCmps</a>.</p>

</div>
</div>

### simplifyAndOrOfICmpsWithConstants() {#ae5781faa80a27cf51fa316feaa2ad363}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyAndOrOfICmpsWithConstants (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Cmp0, <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Cmp1, bool IsAnd)</td>
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

<p>Test if a pair of compares with a shared operand and 2 constants has an empty set intersection, full set union, or if one compare is a superset of the other.</p>

<p>Definition at line 1616 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="#a774f686ad651b962a54ad231e2212f64">getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a>, <a href="#aaa375e5211d9e07739a374c0479fb0ca">getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa89e9cec92a0b38d2f47a077bf12cc98">llvm::ConstantRange::makeExactICmpRegion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="#ac1907d1fccfb9846bfd91b6b79c0acbc">simplifyAndOfICmps</a> and <a href="#a6b86bbc17cbb2be2b63a54fcdbcf4251">simplifyOrOfICmps</a>.</p>

</div>
</div>

### simplifyAndOrOfICmpsWithCtpop() {#a426204f20670379cdefabed663ac339f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyAndOrOfICmpsWithCtpop (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Cmp0, <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Cmp1, bool IsAnd)</td>
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

<p>Try to simplify and/or of icmp with ctpop intrinsic.</p>

<p>Definition at line 1701 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab86c85b47e09489dcda68fd91d082d77">llvm::PatternMatch::m_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a54d7212b9b2c57cced42037ae2fa7c61">llvm::PatternMatch::m_ZeroInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#ac1907d1fccfb9846bfd91b6b79c0acbc">simplifyAndOfICmps</a> and <a href="#a6b86bbc17cbb2be2b63a54fcdbcf4251">simplifyOrOfICmps</a>.</p>

</div>
</div>

### simplifyAndOrWithICmpEq() {#ae739737036faaf1bcaa66a0f4a8e1e63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyAndOrWithICmpEq (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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



<p>Definition at line 1898 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a47f9877ae06a287965eb7a7432e4c566">llvm::ConstantExpr::getBinOpAbsorber</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae9c2f00a962cb8e0316cf3548a5d8029">llvm::ConstantExpr::getBinOpIdentity</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#aba451d2306d849c2ca6821dfe84587a9">llvm::SimplifyQuery::getWithoutUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#abe8988eef2e6fc2baba032cb22afedd7">llvm::ICmpInst::isEquality</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab86c85b47e09489dcda68fd91d082d77">llvm::PatternMatch::m_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac2c120392853d2011de12503a12a16be">llvm::simplifyWithOpReplaced</a>.</p>


<p>Referenced by <a href="#a3eefa98bc7f6c24b6f1fa0bb220a77a4">simplifyAndCommutative</a> and <a href="#a845e93029e92776841aaf5e0ec4c812f">simplifyOrInst</a>.</p>

</div>
</div>

### simplifyAShrInst() {#a29b4afe26752d50b7207bf4cd3f984f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyAShrInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, bool IsExact, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for an AShr, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 1474 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a928ce56952772d0e0f43cab3a489a6fe">llvm::SimplifyQuery::AC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad46ed333b920b20e78d948610366254c">llvm::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a30647c42c8c40890c577ba5b4ab16468">llvm::SimplifyQuery::CxtI</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a4776fa0f5a726bd5a8a444981c283c69">llvm::SimplifyQuery::DT</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#ad029c8abde2f42c8d5837bd5515bb18e">llvm::SimplifyQuery::IIQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a00ef056813d120034e387417e9cde341">llvm::PatternMatch::m_AllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a67de7538f206bdfb3112f59b272bf4bd">llvm::PatternMatch::m_NSWShl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ac1c7b78fe67245930be18441b77de500">llvm::PatternMatch::m_Shl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="#a5bb5f4b5b2420a7f3950939b2de01330">simplifyRightShift</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#a9f2a11175d1af9d1bf62666c50c60145">llvm::InstrInfoQuery::UseInstrInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### simplifyAssociativeBinOp() {#a8863b1b71b53dbab1dd0bd7933ddb3cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyAssociativeBinOp (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Generic simplifications for associative binary operations.</p>


<p>Returns the simpler value, or null if none was found.</p>


<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4f0027b9d05b27206b1882976fce9038">llvm::Instruction::isAssociative</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a55743bd32282bf6f87aeb49237b1fb68">llvm::Instruction::isCommutative</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa750395459fa1eb7130d6de8e3d074f6">llvm::simplifyBinOp</a>.</p>


<p>Referenced by <a href="#a3a8f0d83fd0c16251206c0d0f3e78174">simplifyAddInst</a>, <a href="#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="#a7f2df18bfd941b2e8d1cd78db5beb6f7">simplifyMulInst</a>, <a href="#a845e93029e92776841aaf5e0ec4c812f">simplifyOrInst</a> and <a href="#a9cfeea050198084d67109f0260e33970">simplifyXorInst</a>.</p>

</div>
</div>

### simplifyBinOp() {#ac20fb14fde8d282680882caeb98c2298}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyBinOp (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for a <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a>, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 6053 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e0af1b16cab9e0efc63a6ce9de2b9cc">llvm::simplifyAddInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f751e3ed5adc61048480e9fd0e257cc">llvm::simplifyAndInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0490e6e3fbdff8ae439abff8380ec7e2">llvm::simplifyAShrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76162df5082ce14f7796e4307cba27fd">llvm::simplifyFAddInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a97ff52bca68f0168c930daf2fad29c72">llvm::simplifyFDivInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d4bdb0619aad92ee2de8f939930ba05">llvm::simplifyFMulInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a75983bc94469337f93d99c6a2ad05699">llvm::simplifyFRemInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6e8a8610223f1f09b6000dcbca9649a5">llvm::simplifyFSubInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a41cf2067684aff8591bb68edad443e">llvm::simplifyLShrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b9904a62f8c9179b90d1cb89e6e05ac">llvm::simplifyMulInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4f2dc2393a7799e74a0ab4aaa96783f6">llvm::simplifyOrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23805d3a4c907766bf29b589ba786c81">llvm::simplifySDivInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c052bfdf5f83877d32736ff3895cba5">llvm::simplifyShlInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb98fd0d755e436c5749105d46b0c0d1">llvm::simplifySRemInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5942ddc4393a8ef081555f9a938c86e9">llvm::simplifySubInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab3b0406324f59a9dcdd00f68345ef9b7">llvm::simplifyUDivInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecb805c568634be3390c7da36836d63e">llvm::simplifyURemInst</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4f6b08837306196c6ff45fc5c65fe815">llvm::simplifyXorInst</a>.</p>

</div>
</div>

### simplifyBinOp() {#a0587e14aef27ebf77bcbdf0770da6392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyBinOp (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> &amp; FMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for a <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a>, see if we can fold the result.</p>


<p>If not, this returns null. Try to use <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> when folding the result.</p>


<p>Definition at line 6104 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa750395459fa1eb7130d6de8e3d074f6">llvm::simplifyBinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76162df5082ce14f7796e4307cba27fd">llvm::simplifyFAddInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a97ff52bca68f0168c930daf2fad29c72">llvm::simplifyFDivInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d4bdb0619aad92ee2de8f939930ba05">llvm::simplifyFMulInst</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6e8a8610223f1f09b6000dcbca9649a5">llvm::simplifyFSubInst</a>.</p>

</div>
</div>

### simplifyByDomEq() {#a6343e645572ce8783bbf5853d181479f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyByDomEq (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Test if there is a dominating equivalence condition for the two operands.</p>


<p>If there is, try to reduce the binary operation between the two operands. Example: Op0 - Op1 --&gt; 0 when Op0 == Op1</p>


<p>Definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a30647c42c8c40890c577ba5b4ab16468">llvm::SimplifyQuery::CxtI</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adbc4e5b23d7154e30b03717a470e8178">llvm::isImpliedByDomCondition</a> and <a href="#a30dc1111ec80f24c21b7ea4e7e6df202ad86c5f61eff3b493d5beab893f054a57">RecursionLimit</a>.</p>


<p>Referenced by <a href="#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="#a789b1341fc862e30623b200657911a4c">simplifyDivRem</a>, <a href="#a845e93029e92776841aaf5e0ec4c812f">simplifyOrInst</a>, <a href="#a0e278bb318fd700a9c8d4f4a7c8caba9">simplifySubInst</a> and <a href="#a9cfeea050198084d67109f0260e33970">simplifyXorInst</a>.</p>

</div>
</div>

### simplifyCastInst() {#abfcd971ce6ccafa5489dd3bf313219af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyCastInst (unsigned CastOpc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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



<p>Definition at line 5362 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bf77c90e2fb57af4d4d4aab084f7052">llvm::ConstantFoldCastOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a98477b82eae8654fb3e711d95ea127ec">llvm::DataLayout::getIndexType</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a7a2619d0e489a4ba9c19a0d86a041d59">llvm::DataLayout::getIntPtrType</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a8b805c54dc1ead67b711a4b1cb72f492">llvm::CastInst::isEliminableCastPair</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ab03652069eab17006c51f00c261a6a44">llvm::Type::isPtrOrPtrVectorTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a53fc7d443cf6412add6dfddd11652e5d">llvm::PatternMatch::m_Deferred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a01e017c10a19541f103b7367f579e6f4">llvm::PatternMatch::m_PtrAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af15a15d65884a305e9eec3b690eb37f3">llvm::PatternMatch::m_PtrToInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af5c293ba602295963ee06dd6f22e6335">llvm::PatternMatch::m_Sub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### simplifyCmpInst() {#a5a5e32c5d5b01554c4d171562427a2de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyCmpInst (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Predicate, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for a <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a>, see if we can fold the result.</p>

<p>Definition at line 6132 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ad8c2100cae3093d71e65a48908158e22">llvm::CmpInst::isIntPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a45d5f84f92a3fffaaca5d922ad632dba">llvm::simplifyFCmpInst</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a83813cbf71633220ae57ad2b79498f77">llvm::simplifyICmpInst</a>.</p>

</div>
</div>

### simplifyCmpSelCase() {#a04cf98272b39e1eef023148e1499b1fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyCmpSelCase (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * TrueOrFalse)</td>
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

<p>Simplify comparison with true or false branch of select: sel = select i1 cond, i32 tv, i32 fv cmp = icmp sle i32 sel, rhs Compose new comparison by substituting sel with either tv or fv and see if it simplifies.</p>

<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="#a3e2c41b46422f8392e87d92a2f8e9d3c">isSameCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adccdd5d6b0c85f7917306e296b27c4cd">llvm::simplifyCmpInst</a>.</p>


<p>Referenced by <a href="#a022b0d31de4686085b7c8d2719a3edd7">simplifyCmpSelFalseCase</a> and <a href="#a5211abbd14c49ebe208e93000a365ef0">simplifyCmpSelTrueCase</a>.</p>

</div>
</div>

### simplifyCmpSelFalseCase() {#a022b0d31de4686085b7c8d2719a3edd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyCmpSelFalseCase (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Simplify comparison with false branch of select.</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="#a774f686ad651b962a54ad231e2212f64">getFalse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a04cf98272b39e1eef023148e1499b1fc">simplifyCmpSelCase</a>.</p>


<p>Referenced by <a href="#aa6faca61824779a7d72a2c1e08b9e7a0">threadCmpOverSelect</a>.</p>

</div>
</div>

### simplifyCmpSelOfMaxMin() {#a93f2e165baf61dd8295c9aececed9985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyCmpSelOfMaxMin (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * CmpLHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * CmpRHS, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * TVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * FVal)</td>
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



<p>Definition at line 4544 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a0578679c169c9ca4cc731185ffddb431">llvm::CmpInst::getStrictPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a9d30ca764aa6f22f9812bc52abb69207">llvm::PatternMatch::m_c_MaxOrMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="#afa1ff3254ee225171cb55d46b0eab145">simplifySelectWithICmpCond</a>.</p>

</div>
</div>

### simplifyCmpSelTrueCase() {#a5211abbd14c49ebe208e93000a365ef0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyCmpSelTrueCase (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Simplify comparison with true branch of select.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="#aaa375e5211d9e07739a374c0479fb0ca">getTrue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a04cf98272b39e1eef023148e1499b1fc">simplifyCmpSelCase</a>.</p>


<p>Referenced by <a href="#aa6faca61824779a7d72a2c1e08b9e7a0">threadCmpOverSelect</a>.</p>

</div>
</div>

### simplifyDiv() {#a2d67c7fd2789ef1dfb05513f1eb8d054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyDiv (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, bool IsExact, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>These are simplifications common to SDiv and UDiv.</p>

<p>Definition at line 1135 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a2ad6370e532a52014fe2e5a54bfbaddd">llvm::KnownBits::countMaxTrailingZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a83c7c9008ba213687483b60a658b4a13">llvm::APInt::countr_zero</a>, <a href="#a15df887e1ad05e6c22a7c2e6492bde2d">foldOrCommuteConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad1b0513de876d1c85cf6268ca21b2c86">llvm::APInt::isPowerOf2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af4f73c301d2b05039d2d8898e2c29822">llvm::PatternMatch::m_NSWMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a70e6404b68c92cddcbfbfcce69ce3334">llvm::PatternMatch::m_NUWMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="#a789b1341fc862e30623b200657911a4c">simplifyDivRem</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#a630c735bfbff439b152d83f92302cb34">simplifySDivInst</a> and <a href="#a08c5c0e210c3418665efc1bc160ebcfe">simplifyUDivInst</a>.</p>

</div>
</div>

### simplifyDivRem() {#a789b1341fc862e30623b200657911a4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyDivRem (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for common or similar folds of integer division or integer remainder.</p>


<p>This applies to all 4 opcodes (sdiv/udiv/srem/urem).</p>


<p>Definition at line 1041 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a7f47812e8e75b0616a97d7004e5fb909">llvm::KnownBits::countMinLeadingZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a4fdc09049a61f952b5d52788dbd2f69b">llvm::KnownBits::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#a879785896627e7415e7aee7934bf922b">llvm::InstrInfoQuery::hasNoSignedWrap</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#affcd96f408768d8c1849b5293579143d">llvm::InstrInfoQuery::hasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#ad029c8abde2f42c8d5837bd5515bb18e">llvm::SimplifyQuery::IIQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#ab29fdeb7689892b6496576ca70cfc625">isDivZero</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a1620c017d995c7ccbcb59e0212618017">llvm::KnownBits::isZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af10813bee5ce9c7b412807aac434deef">llvm::PatternMatch::m_c_Mul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aa288295c57b0d3adeed48f9ed452701e">llvm::PatternMatch::m_SDiv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a719c774934ac66be45cc09cef392cf65">llvm::PatternMatch::m_UDiv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#ae0f503db91504a3f3440ab81260e4134">Mul</a>, <a href="#a6343e645572ce8783bbf5853d181479f">simplifyByDomEq</a>, <a href="#a914ac5681f80badb866f2aee44fc509a">threadBinOpOverPHI</a>, <a href="#ada3f0c65b41a26f74d332e974164ce55">threadBinOpOverSelect</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#a2d67c7fd2789ef1dfb05513f1eb8d054">simplifyDiv</a> and <a href="#aed163588354401b6679a39acad6fae2a">simplifyRem</a>.</p>

</div>
</div>

### simplifyExtractElementInst() {#a48ebda753879b3d5d55fa0e1566b5439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyExtractElementInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Vec, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Idx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned)</td>
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

<p>Given operands for an <a href="/web-llvm/docs/api/classes/llvm/extractelementinst">ExtractElementInst</a>, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 5259 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab09fc7dee4f7e02c60f7a9c928dc1603">llvm::findScalarElement</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a078455f9a6da73bc84f24700a81d19d7">llvm::ConstantExpr::getExtractElement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a48fc95f799e976fb8bf571d61e6337f5">llvm::getSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a5b9bf50c6579a978e5c1104bf8787651">llvm::Splat</a>.</p>

</div>
</div>

### simplifyExtractValueInst() {#a37493b7a361d3374a2731470d964c183}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyExtractValueInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Agg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Idxs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp;, unsigned)</td>
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

<p>Given operands for an <a href="/web-llvm/docs/api/classes/llvm/extractvalueinst">ExtractValueInst</a>, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 5229 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a557be4c1daf6eb2611b214f927dccee2">llvm::ConstantFoldExtractValueInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a>.</p>

</div>
</div>

### simplifyFAddInst() {#a68091149082c7a34c2198012a0800d6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyFAddInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse, <a href="/web-llvm/docs/api/namespaces/llvm/fp/#a51c5e09b2604faec548aef87bd482630">fp::ExceptionBehavior</a> ExBehavior=fp::ebIgnore, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">RoundingMode</a> Rounding=RoundingMode::NearestTiesToEven)</td>
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

<p>Given operands for an FAdd, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 5692 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a9f3a7d3a575da12ac2fec17849b7b916">llvm::FastMathFlags::allowReassoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec4ff9b2beab5c962935042f5b5758dd">llvm::canIgnoreSNaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad6e2d414c6580430f5f84ee467630f65">llvm::cannotBeNegativeZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4137d83a9e8406ca72d0b668108814c5">llvm::canRoundingModeBe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fp/#a51c5e09b2604faec548aef87bd482630ad8009e7c0ce2967115e856052243ac62">llvm::fp::ebIgnore</a>, <a href="#a15df887e1ad05e6c22a7c2e6492bde2d">foldOrCommuteConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a75071440d60c24178371ca1299f4ef07">llvm::ConstantFP::getZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a28294e7b4ae05afa8858fd6496f3ff12">llvm::isDefaultFPEnvironment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2c7e2b8240233bff5e5f1b38465420c1">llvm::PatternMatch::m_AnyZeroFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aba7473bfa862dd9eadf04a6fefc6aa69">llvm::PatternMatch::m_FNeg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0fa2fe47478bcc6676ec49dd76544e3a">llvm::PatternMatch::m_FSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0d5f2a537875b12c29e04431fa4ac5bf">llvm::PatternMatch::m_Inf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3d80f55b28f3d81e8fe8c0d63b1b4413">llvm::PatternMatch::m_NegZeroFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#abb2f21cbe7164d435978845d73de1a83">llvm::PatternMatch::m_PosZeroFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7ca44467144e3b6bdac3e85ef6f90e7d832">llvm::NearestTiesToEven</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ac1d140361490d7847edf0c7503e3188a">llvm::FastMathFlags::noNaNs</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a278a2e29bf56f2e2109fd35ae454b050">llvm::FastMathFlags::noSignedZeros</a>, <a href="#aa6498365e4fa2bc006fc4116b4b9b990">simplifyFPOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7cacd6fee581a325642b84f1af5c0be5140">llvm::TowardNegative</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### simplifyFCmpInst() {#a110a350e37f3cc2ed2c603c3efde0a30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyFCmpInst (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for an <a href="/web-llvm/docs/api/classes/llvm/fcmpinst">FCmpInst</a>, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 4063 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/knownfpclass/#ac068bb13883a326befa8b10d45cb52a2">llvm::KnownFPClass::cannotBeOrderedLessThanZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae24d4b778b2ebb07dee151d37e2ffdf3">llvm::computeKnownFPClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3cd3a3ec28036937ecebe767498ba55d">llvm::ConstantFoldCompareInstOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a30647c42c8c40890c577ba5b4ab16468">llvm::SimplifyQuery::CxtI</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dabf7829a22591343ad790b1357955a7df">llvm::fcAllFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bae9c013750fff3023001d7e3af8df2d6d">llvm::CmpInst::FCMP_FALSE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba024db78a5ed74f64666f3ca4955e6eca">llvm::CmpInst::FCMP_OEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b">llvm::CmpInst::FCMP_OGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">llvm::CmpInst::FCMP_OGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba9835cfe02fb5027680bd7203b024f77a">llvm::CmpInst::FCMP_OLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">llvm::CmpInst::FCMP_OLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba8a80b27ca29fe2076b9bbdee02c65464">llvm::CmpInst::FCMP_ONE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa3213b645e029aba8bb1b85213607d5e">llvm::CmpInst::FCMP_ORD</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba0a33c71e3c5e8f128ca47539a85962f5">llvm::CmpInst::FCMP_TRUE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba919643b83ce3c9af2e4296ed5e413a1f">llvm::CmpInst::FCMP_UEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bae51609fc6a425f849d37c28cb9bc0344">llvm::CmpInst::FCMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba959268ceeae23abe5c9ad9e895669d0c">llvm::CmpInst::FCMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba396dda2571cd3c575f1d9cb44dc2cc09">llvm::CmpInst::FCMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba75016d5872d90adf89cc1cbf5763f474">llvm::CmpInst::FCMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad601460c9371d0f0ada5ae006bdba2bd">llvm::CmpInst::FCMP_UNE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed">llvm::CmpInst::FCMP_UNO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9ef7edd1261f6570677d850b5cf2cfc">llvm::fcmpToClassTest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dafe1646e5477c571f7791c524b54b11fe">llvm::fcNan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da4759a508982cd525d9f17024f09aea22">llvm::fcNone</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="#abee3cf86c05d2369d387f07f7055b9dc">getCompareTy</a>, <a href="#a774f686ad651b962a54ad231e2212f64">getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="#aaa375e5211d9e07739a374c0479fb0ca">getTrue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a1e32582702cf5b9d4484c0ce346b2f57">llvm::CmpInst::isFalseWhenEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a66c10680694a0184d50e7a8c0d1ea874">llvm::CmpInst::isFPPredicate</a>, <a href="/web-llvm/docs/api/structs/llvm/knownfpclass/#a009e9523110c79d3cc8fae67e9026562">llvm::KnownFPClass::isKnownAlwaysNaN</a>, <a href="/web-llvm/docs/api/structs/llvm/knownfpclass/#a9ace8a5baa7d3c3ad3639fc1e71558bb">llvm::KnownFPClass::isKnownNeverNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a5ba8484cef2818d14b85640a903b2598">llvm::CmpInst::isTrueWhenEqual</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aae55ea42185b7528c0c149625b998968">llvm::CmpInst::isUnordered</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2c7e2b8240233bff5e5f1b38465420c1">llvm::PatternMatch::m_AnyZeroFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#acd794d7b3653822f61ba126e1678e03f">llvm::PatternMatch::m_APFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a9401faf90f32158e4037a4e34bdf54a9">llvm::PatternMatch::m_APFloatAllowPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ac1d140361490d7847edf0c7503e3188a">llvm::FastMathFlags::noNaNs</a>, <a href="/web-llvm/docs/api/structs/llvm/knownfpclass/#a166b63a9217b936dc956f6b65de7602a">llvm::KnownFPClass::OrderedLessThanZeroMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="#a1ec7a76fbddf5983969def6e47c0f177">threadCmpOverPHI</a>, <a href="#aa6faca61824779a7d72a2c1e08b9e7a0">threadCmpOverSelect</a> and <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#aaf09fd551f7b18f7c75c662a8a8ed040">llvm::SimplifyQuery::TLI</a>.</p>

</div>
</div>

### simplifyFDivInst() {#a7ae2d2701ffe4abf529cd4fb1ca26049}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyFDivInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned, <a href="/web-llvm/docs/api/namespaces/llvm/fp/#a51c5e09b2604faec548aef87bd482630">fp::ExceptionBehavior</a> ExBehavior=fp::ebIgnore, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">RoundingMode</a> Rounding=RoundingMode::NearestTiesToEven)</td>
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



<p>Definition at line 5918 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a9f3a7d3a575da12ac2fec17849b7b916">llvm::FastMathFlags::allowReassoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fp/#a51c5e09b2604faec548aef87bd482630ad8009e7c0ce2967115e856052243ac62">llvm::fp::ebIgnore</a>, <a href="#a15df887e1ad05e6c22a7c2e6492bde2d">foldOrCommuteConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a75071440d60c24178371ca1299f4ef07">llvm::ConstantFP::getZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a28294e7b4ae05afa8858fd6496f3ff12">llvm::isDefaultFPEnvironment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2c7e2b8240233bff5e5f1b38465420c1">llvm::PatternMatch::m_AnyZeroFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0c004ff2fe00bedeaca7692531b267f9">llvm::PatternMatch::m_c_FMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a118c8d01680dcaaf7527f84503a2191d">llvm::PatternMatch::m_FNegNSZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a8f87f39b5e0dedd0793bb3a450f463cf">llvm::PatternMatch::m_FPOne</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7ca44467144e3b6bdac3e85ef6f90e7d832">llvm::NearestTiesToEven</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a39b529fcda9ee90b17a3e1fed732a22a">llvm::FastMathFlags::noInfs</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ac1d140361490d7847edf0c7503e3188a">llvm::FastMathFlags::noNaNs</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a278a2e29bf56f2e2109fd35ae454b050">llvm::FastMathFlags::noSignedZeros</a>, <a href="#aa6498365e4fa2bc006fc4116b4b9b990">simplifyFPOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### simplifyFMAFMul() {#a5b47854a993004418cb56068fe2dd9dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyFMAFMul (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse, <a href="/web-llvm/docs/api/namespaces/llvm/fp/#a51c5e09b2604faec548aef87bd482630">fp::ExceptionBehavior</a> ExBehavior, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">RoundingMode</a> Rounding)</td>
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



<p>Definition at line 5824 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a9f3a7d3a575da12ac2fec17849b7b916">llvm::FastMathFlags::allowReassoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae24d4b778b2ebb07dee151d37e2ffdf3">llvm::computeKnownFPClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da00a4419741933f5cb7ec001aaa6e6bb5">llvm::fcInf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dafe1646e5477c571f7791c524b54b11fe">llvm::fcNan</a>, <a href="#a1a6e468202ea1fafcd8163afbe034823">foldConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a75071440d60c24178371ca1299f4ef07">llvm::ConstantFP::getZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a28294e7b4ae05afa8858fd6496f3ff12">llvm::isDefaultFPEnvironment</a>, <a href="/web-llvm/docs/api/structs/llvm/knownfpclass/#aa0fbe688ffb115395a2665499c0639a2">llvm::KnownFPClass::isKnownNever</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2c7e2b8240233bff5e5f1b38465420c1">llvm::PatternMatch::m_AnyZeroFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a8f87f39b5e0dedd0793bb3a450f463cf">llvm::PatternMatch::m_FPOne</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a4c416c17e6042556508306f5864f3248">llvm::PatternMatch::m_Sqrt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ac1d140361490d7847edf0c7503e3188a">llvm::FastMathFlags::noNaNs</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a278a2e29bf56f2e2109fd35ae454b050">llvm::FastMathFlags::noSignedZeros</a>, <a href="/web-llvm/docs/api/structs/llvm/knownfpclass/#a98b802f50f0dfde19089adfd2f4f2f7b">llvm::KnownFPClass::SignBit</a>, <a href="#aa6498365e4fa2bc006fc4116b4b9b990">simplifyFPOp</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### simplifyFMulInst() {#adde5a4e7e2382910bdfbd89dd30671a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyFMulInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse, <a href="/web-llvm/docs/api/namespaces/llvm/fp/#a51c5e09b2604faec548aef87bd482630">fp::ExceptionBehavior</a> ExBehavior=fp::ebIgnore, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">RoundingMode</a> Rounding=RoundingMode::NearestTiesToEven)</td>
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

<p>Given the operands for an FMul, see if we can fold the result.</p>

<p>Definition at line 5873 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fp/#a51c5e09b2604faec548aef87bd482630ad8009e7c0ce2967115e856052243ac62">llvm::fp::ebIgnore</a>, <a href="#a15df887e1ad05e6c22a7c2e6492bde2d">foldOrCommuteConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a28294e7b4ae05afa8858fd6496f3ff12">llvm::isDefaultFPEnvironment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7ca44467144e3b6bdac3e85ef6f90e7d832">llvm::NearestTiesToEven</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9e6861fa4cb7fe1437d3057b8b3d1601">llvm::simplifyFMAFMul</a>.</p>

</div>
</div>

### simplifyFNegInst() {#a81185b0eeb96c7354756478f505f9ec8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyFNegInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given the operand for an FNeg, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 5588 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a1a6e468202ea1fafcd8163afbe034823">foldConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aba7473bfa862dd9eadf04a6fefc6aa69">llvm::PatternMatch::m_FNeg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### simplifyFPOp() {#aa6498365e4fa2bc006fc4116b4b9b990}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * simplifyFPOp (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Ops, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, <a href="/web-llvm/docs/api/namespaces/llvm/fp/#a51c5e09b2604faec548aef87bd482630">fp::ExceptionBehavior</a> ExBehavior, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">RoundingMode</a> Rounding)</td>
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

<p>Perform folds that are common to any floating-point operation.</p>


<p>This implies transforms based on poison/undef/NaN because the operation itself makes no difference to the result.</p>


<p>Definition at line 5650 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fp/#a51c5e09b2604faec548aef87bd482630a5dfc3e95e600e911e26874be1f27dba7">llvm::fp::ebStrict</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#ab21342133676f10340dc3f541b128f24">llvm::ConstantFP::getNaN</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a28294e7b4ae05afa8858fd6496f3ff12">llvm::isDefaultFPEnvironment</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0d5f2a537875b12c29e04431fa4ac5bf">llvm::PatternMatch::m_Inf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae138cfc26c6b3f24fd6fc3f3dfcbdfeb">llvm::PatternMatch::m_NaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0108cb60d944ff177beaa8f419c91d72">llvm::PatternMatch::m_Poison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a39b529fcda9ee90b17a3e1fed732a22a">llvm::FastMathFlags::noInfs</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ac1d140361490d7847edf0c7503e3188a">llvm::FastMathFlags::noNaNs</a> and <a href="#a20728ab5a970c250099d56e721746064">propagateNaN</a>.</p>


<p>Referenced by <a href="#a68091149082c7a34c2198012a0800d6d">simplifyFAddInst</a>, <a href="#a7ae2d2701ffe4abf529cd4fb1ca26049">simplifyFDivInst</a>, <a href="#a5b47854a993004418cb56068fe2dd9dd">simplifyFMAFMul</a>, <a href="#a95596f2a72e57df0c710e3dc7b225597">simplifyFRemInst</a>, <a href="#a9a357829c347a3ab1d10dced5dbeb27a">simplifyFSubInst</a> and <a href="#a554988e4897106ec290097646fd1a84e">simplifyIntrinsic</a>.</p>

</div>
</div>

### simplifyFPUnOp() {#a6497dd4ddbdc3b5dacec510108c4e62d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyFPUnOp (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> &amp; FMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given the operand for a <a href="/web-llvm/docs/api/classes/llvm/unaryoperator">UnaryOperator</a>, see if we can fold the result.</p>


<p>If not, this returns null. Try to use <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> when folding the result.</p>


<p>Definition at line 6031 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a6e06e93488a2f32aeb56f86797a78c33">llvm::simplifyFNegInst</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a27487de7fe616848977b268e8aa6354d">llvm::simplifyUnOp</a>.</p>

</div>
</div>

### simplifyFreezeInst() {#a0160b3b9cc2d97a29656003dc77f189e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyFreezeInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q)</td>
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

<p>Given operands for a Freeze, see if we can fold the result.</p>

<p>Definition at line 7047 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a928ce56952772d0e0f43cab3a489a6fe">llvm::SimplifyQuery::AC</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a30647c42c8c40890c577ba5b4ab16468">llvm::SimplifyQuery::CxtI</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a4776fa0f5a726bd5a8a444981c283c69">llvm::SimplifyQuery::DT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab8a7ef433279aabf7f30fa5504a4d4ef">llvm::isGuaranteedNotToBeUndefOrPoison</a>.</p>

</div>
</div>

### simplifyFRemInst() {#a95596f2a72e57df0c710e3dc7b225597}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyFRemInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned, <a href="/web-llvm/docs/api/namespaces/llvm/fp/#a51c5e09b2604faec548aef87bd482630">fp::ExceptionBehavior</a> ExBehavior=fp::ebIgnore, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">RoundingMode</a> Rounding=RoundingMode::NearestTiesToEven)</td>
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



<p>Definition at line 5977 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fp/#a51c5e09b2604faec548aef87bd482630ad8009e7c0ce2967115e856052243ac62">llvm::fp::ebIgnore</a>, <a href="#a15df887e1ad05e6c22a7c2e6492bde2d">foldOrCommuteConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a7d4cd0394293b0107e1ada58f8911387">llvm::ConstantFP::getNegativeZero</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a75071440d60c24178371ca1299f4ef07">llvm::ConstantFP::getZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a28294e7b4ae05afa8858fd6496f3ff12">llvm::isDefaultFPEnvironment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3d80f55b28f3d81e8fe8c0d63b1b4413">llvm::PatternMatch::m_NegZeroFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#abb2f21cbe7164d435978845d73de1a83">llvm::PatternMatch::m_PosZeroFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7ca44467144e3b6bdac3e85ef6f90e7d832">llvm::NearestTiesToEven</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ac1d140361490d7847edf0c7503e3188a">llvm::FastMathFlags::noNaNs</a> and <a href="#aa6498365e4fa2bc006fc4116b4b9b990">simplifyFPOp</a>.</p>

</div>
</div>

### simplifyFSubInst() {#a9a357829c347a3ab1d10dced5dbeb27a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyFSubInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse, <a href="/web-llvm/docs/api/namespaces/llvm/fp/#a51c5e09b2604faec548aef87bd482630">fp::ExceptionBehavior</a> ExBehavior=fp::ebIgnore, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">RoundingMode</a> Rounding=RoundingMode::NearestTiesToEven)</td>
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

<p>Given operands for an FSub, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 5758 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a9f3a7d3a575da12ac2fec17849b7b916">llvm::FastMathFlags::allowReassoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec4ff9b2beab5c962935042f5b5758dd">llvm::canIgnoreSNaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad6e2d414c6580430f5f84ee467630f65">llvm::cannotBeNegativeZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4137d83a9e8406ca72d0b668108814c5">llvm::canRoundingModeBe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fp/#a51c5e09b2604faec548aef87bd482630ad8009e7c0ce2967115e856052243ac62">llvm::fp::ebIgnore</a>, <a href="#a1a6e468202ea1fafcd8163afbe034823">foldConstant</a>, <a href="#a15df887e1ad05e6c22a7c2e6492bde2d">foldOrCommuteConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a28294e7b4ae05afa8858fd6496f3ff12">llvm::isDefaultFPEnvironment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2c7e2b8240233bff5e5f1b38465420c1">llvm::PatternMatch::m_AnyZeroFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#abc3abb118da27b139086f96121461bf8">llvm::PatternMatch::m_c_FAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aba7473bfa862dd9eadf04a6fefc6aa69">llvm::PatternMatch::m_FNeg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0fa2fe47478bcc6676ec49dd76544e3a">llvm::PatternMatch::m_FSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0d5f2a537875b12c29e04431fa4ac5bf">llvm::PatternMatch::m_Inf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3d80f55b28f3d81e8fe8c0d63b1b4413">llvm::PatternMatch::m_NegZeroFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#abb2f21cbe7164d435978845d73de1a83">llvm::PatternMatch::m_PosZeroFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7ca44467144e3b6bdac3e85ef6f90e7d832">llvm::NearestTiesToEven</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ac1d140361490d7847edf0c7503e3188a">llvm::FastMathFlags::noNaNs</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a278a2e29bf56f2e2109fd35ae454b050">llvm::FastMathFlags::noSignedZeros</a>, <a href="#aa6498365e4fa2bc006fc4116b4b9b990">simplifyFPOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7cacd6fee581a325642b84f1af5c0be5140">llvm::TowardNegative</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### simplifyGEPInst() {#aab8aaa8e44e0609f7d3e9ae822f11f7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyGEPInst (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * SrcTy, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Indices, <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a> NW, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned)</td>
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

<p>Given operands for an <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a>, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 5009 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a291ac49156942529f159a9ec003cc25f">llvm::ArrayRef&lt; T &gt;::back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e655fd99a56d50b071fc26d8db5fd5b">llvm::ConstantFoldConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a491cbe61681e7c63ac7d01ce209a4682">llvm::ConstantFoldGetElementPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aa713e2599e000adc01ced998c05502a7">llvm::ArrayRef&lt; T &gt;::drop_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae4d4490a35a575d97166684fb15f8662">llvm::ConstantExpr::getGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#a99d4bfe49182f8d80abb1960f2c12d46">llvm::GetElementPtrInst::getIndexedType</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#ac9e61b1a68b91217d3d10a61a1f0fbb9">llvm::DataLayout::getIndexSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a02560cda155aaed54314383bed827d60">llvm::ConstantExpr::getIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a21ae5af9c62928bb06c66379017bdda1">llvm::DataLayout::getPointerSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargettransforminfo-cpp/#a69eeffbc38c079195008fbfb5aaad0b9">getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#aa48b3b7e554b44f4e513d5dd8d9f9343">llvm::DataLayout::getTypeAllocSize</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#acf0b1898efd7f81a078e9288befd9290">llvm::DataLayout::getTypeSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aea5f26deda5ef97e02f6afc57c0c3920">llvm::APInt::isOne</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a7baf4632513de0fccabc65793c6b8dae">llvm::ConstantExpr::isSupportedGetElementPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a00ef056813d120034e387417e9cde341">llvm::PatternMatch::m_AllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0c94f3ca4234f78cf22840e79087f3f2">llvm::PatternMatch::m_AShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3aa1f5d3cd54d36e7e47f401a0118aeb">llvm::PatternMatch::m_ConstantInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5d295dcffba83c3c5a17d2fb3273b434">llvm::PatternMatch::m_Neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af15a15d65884a305e9eec3b690eb37f3">llvm::PatternMatch::m_PtrToInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aa288295c57b0d3adeed48f9ed452701e">llvm::PatternMatch::m_SDiv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2471be3f1b50002f54bf45c590d8d41b">llvm::PatternMatch::m_SpecificInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af5c293ba602295963ee06dd6f22e6335">llvm::PatternMatch::m_Sub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1cacb72e897c55bdfd5c726d13d69af1">llvm::PatternMatch::m_Xor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### simplifyICmpInst() {#a47a81cb5e93cfda95b1de100dd5b9919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyICmpInst (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for an <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a>, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 3742 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a928ce56952772d0e0f43cab3a489a6fe">llvm::SimplifyQuery::AC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aec29f5580509ec9a7592200e09b7aa27">computePointerICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bf77c90e2fb57af4d4d4aab084f7052">llvm::ConstantFoldCastOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3cd3a3ec28036937ecebe767498ba55d">llvm::ConstantFoldCompareInstOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a30647c42c8c40890c577ba5b4ab16468">llvm::SimplifyQuery::CxtI</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a4776fa0f5a726bd5a8a444981c283c69">llvm::SimplifyQuery::DT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#afe7d477c6022fe7123b90e3b39c58e69">llvm::ConstantInt::getBool</a>, <a href="#abee3cf86c05d2369d387f07f7055b9dc">getCompareTy</a>, <a href="#a774f686ad651b962a54ad231e2212f64">getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a02560cda155aaed54314383bed827d60">llvm::ConstantExpr::getIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="#a407852423447c9c318189650976659fb">getRange</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="#aaa375e5211d9e07739a374c0479fb0ca">getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#acf0b1898efd7f81a078e9288befd9290">llvm::DataLayout::getTypeSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#af07a09f1cda33d984cc725dc9e856d40">llvm::ICmpInst::getUnsignedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#ad029c8abde2f42c8d5837bd5515bb18e">llvm::SimplifyQuery::IIQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a662be1e66a5af621d46fa1c7a8aa1004">llvm::Constant::isAllOnesValue</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#abe8988eef2e6fc2baba032cb22afedd7">llvm::ICmpInst::isEquality</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adbc4e5b23d7154e30b03717a470e8178">llvm::isImpliedByDomCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ad8c2100cae3093d71e65a48908158e22">llvm::CmpInst::isIntPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa9afd47568010f063c6ca4ed6473db03">llvm::isKnownNonEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#ae4b6abe77abf42fb02081a6cc41a0132">llvm::Constant::isNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a5ba8484cef2818d14b85640a903b2598">llvm::CmpInst::isTrueWhenEqual</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5f6c38f6f64c2118341c829f97e26396">llvm::PatternMatch::m_ImmConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83813cbf71633220ae57ad2b79498f77">llvm::simplifyICmpInst</a>, <a href="#a22aa6a5c92a8a6cbb5437123d7e069e6">simplifyICmpOfBools</a>, <a href="#adae506d280d297474e74be7d5d1b9762">simplifyICmpUsingMonotonicValues</a>, <a href="#a64cb0c5ab10b63f22110e1b0183a648f">simplifyICmpWithBinOp</a>, <a href="#a7520bc5124cf32bdbb659ae6fc12cf9c">simplifyICmpWithConstant</a>, <a href="#ae9417447cf23234d645221bda42e00c4">simplifyICmpWithDominatingAssume</a>, <a href="#a5e2e121dcbec9a2ede54e53ba8be83d4">simplifyICmpWithIntrinsicOnLHS</a>, <a href="#a4f8adcab536e4c9f42e148d7eb218e6a">simplifyICmpWithMinMax</a>, <a href="#a738d3c4d8f36cf843825c2b5a878f58a">simplifyICmpWithZero</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="#a1ec7a76fbddf5983969def6e47c0f177">threadCmpOverPHI</a>, <a href="#aa6faca61824779a7d72a2c1e08b9e7a0">threadCmpOverSelect</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#aaf09fd551f7b18f7c75c662a8a8ed040">llvm::SimplifyQuery::TLI</a> and <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#a9f2a11175d1af9d1bf62666c50c60145">llvm::InstrInfoQuery::UseInstrInfo</a>.</p>

</div>
</div>

### simplifyICmpOfBools() {#a22aa6a5c92a8a6cbb5437123d7e069e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyICmpOfBools (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q)</td>
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

<p>Fold an icmp when its operands have i1 scalar type.</p>

<p>Definition at line 2832 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="#abee3cf86c05d2369d387f07f7055b9dc">getCompareTy</a>, <a href="#a774f686ad651b962a54ad231e2212f64">getFalse</a>, <a href="#aaa375e5211d9e07739a374c0479fb0ca">getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7f2eb961a542779e97c0b3ec7fa6623">llvm::isImpliedCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a34ee40bb2f4f5ece47ef19e5f1f57e3c">llvm::Type::isIntOrIntVectorTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3b3d2d8c64a7881acb82bc7467569aa9">llvm::PatternMatch::m_One</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>.</p>

</div>
</div>

### simplifyICmpUsingMonotonicValues() {#adae506d280d297474e74be7d5d1b9762}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyICmpUsingMonotonicValues (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS)</td>
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



<p>Definition at line 3088 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#af74676a3c7447be34bd2c1da76ec0c48">llvm::SmallPtrSetImpl&lt; PtrType &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#afe7d477c6022fe7123b90e3b39c58e69">llvm::ConstantInt::getBool</a>, <a href="#abee3cf86c05d2369d387f07f7055b9dc">getCompareTy</a>, <a href="#a57d8791ae7f26ddfe185e3d40b8f9c90">getUnsignedMonotonicValues</a>, <a href="#a4fa5495dc2ca57889c6cf2fd8bba50efadc68720e1e33df4d3546cd1aa63143c3">GreaterEq</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="#a4fa5495dc2ca57889c6cf2fd8bba50efa2a0b03b794ee59bcb81977eda463e721">LowerEq</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>.</p>

</div>
</div>

### simplifyICmpWithBinOp() {#a64cb0c5ab10b63f22110e1b0183a648f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyICmpWithBinOp (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>TODO: A large part of this logic is duplicated in InstCombine's foldICmpBinOp().</p>


<p>We should be able to share that and avoid the code duplication.</p>


<p>Definition at line 3251 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#abee3cf86c05d2369d387f07f7055b9dc">getCompareTy</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#a879785896627e7415e7aee7934bf922b">llvm::InstrInfoQuery::hasNoSignedWrap</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#affcd96f408768d8c1849b5293579143d">llvm::InstrInfoQuery::hasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#ad029c8abde2f42c8d5837bd5515bb18e">llvm::SimplifyQuery::IIQ</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#aaaeded5d0cab77f531b294638459aca5">llvm::ICmpInst::isEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#abe8988eef2e6fc2baba032cb22afedd7">llvm::ICmpInst::isEquality</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#a0e8fe3b04971436feea66aca9016f45b">llvm::InstrInfoQuery::isExact</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9893e3e4b14f8fa15d7c3c25a6a0b6f6">llvm::isKnownNonZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac8c0157adbe12649beac0009c2f6ad8d">llvm::APInt::isNonNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#ae955171baab3d9254f3ffb089c082206">llvm::ICmpInst::isRelational</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a3712279d70deeec90a93db09deb12d02">llvm::CmpInst::isSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acfae9bdee6027ffa8ffe244cc22e3a76">llvm::APInt::isSubsetOf</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#af206a3d6f58d9e53b074460f0d1ecb86">llvm::CmpInst::isUnsigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a59cab71d904ae725a5ef54bbf5490017">llvm::PatternMatch::m_APIntAllowPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5d295dcffba83c3c5a17d2fb3273b434">llvm::PatternMatch::m_Neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3b3d2d8c64a7881acb82bc7467569aa9">llvm::PatternMatch::m_One</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a103f4e50bfeab3d598adc56e1235c241">llvm::PatternMatch::m_Power2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ac1c7b78fe67245930be18441b77de500">llvm::PatternMatch::m_Shl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0c2ec502cbe0e39c4b7641f648b3a615">llvm::PatternMatch::m_SignMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a6ba4022cd30993a84d111871dd0f6ba6">llvm::PatternMatch::m_ZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83813cbf71633220ae57ad2b79498f77">llvm::simplifyICmpInst</a>, <a href="#a28e9b56583c0f73543606d22bfac472e">simplifyICmpWithBinOpOnLHS</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="#a86f75bbbe87c45fd3f9047fbad61671c">trySimplifyICmpWithAdds</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>.</p>

</div>
</div>

### simplifyICmpWithBinOpOnLHS() {#a28e9b56583c0f73543606d22bfac472e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyICmpWithBinOpOnLHS (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * LBO, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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



<p>Definition at line 3106 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="#abee3cf86c05d2369d387f07f7055b9dc">getCompareTy</a>, <a href="#a774f686ad651b962a54ad231e2212f64">getFalse</a>, <a href="#aaa375e5211d9e07739a374c0479fb0ca">getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#abe8988eef2e6fc2baba032cb22afedd7">llvm::ICmpInst::isEquality</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9893e3e4b14f8fa15d7c3c25a6a0b6f6">llvm::isKnownNonZero</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aabc0af41b4437080b27002ed7a1ed656">llvm::KnownBits::isNegative</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a157efd68e8b4b838829cad165b1583f8">llvm::KnownBits::isNonNegative</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a59cab71d904ae725a5ef54bbf5490017">llvm::PatternMatch::m_APIntAllowPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae80cbfea2025ff7bd0770f30be6e050a">llvm::PatternMatch::m_c_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab8546ee1aaa68d6f4990e6241e24464c">llvm::PatternMatch::m_LShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a532515120d78196926b68c48460087ab">llvm::PatternMatch::m_Mul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ac1c7b78fe67245930be18441b77de500">llvm::PatternMatch::m_Shl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af5c293ba602295963ee06dd6f22e6335">llvm::PatternMatch::m_Sub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a719c774934ac66be45cc09cef392cf65">llvm::PatternMatch::m_UDiv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a11e5bad6c60d5c3cc5e7881bddd0204d">llvm::PatternMatch::m_URem</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca14d9ec64ba4ab7fb2cef37c57d9ce4">llvm::APInt::ule</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="#a64cb0c5ab10b63f22110e1b0183a648f">simplifyICmpWithBinOp</a>.</p>

</div>
</div>

### simplifyICmpWithConstant() {#a7520bc5124cf32bdbb659ae6fc12cf9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyICmpWithConstant (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery">InstrInfoQuery</a> &amp; IIQ)</td>
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



<p>Definition at line 2995 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a546e6f5ba8f510c3e7ed2e20013548d9">llvm::computeConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aaca3a4d2b25c24b11179cbd01079b73c">llvm::ConstantRange::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#afe7d477c6022fe7123b90e3b39c58e69">llvm::ConstantInt::getBool</a>, <a href="#abee3cf86c05d2369d387f07f7055b9dc">getCompareTy</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aaaa2f5e2c6c3122d2b484f9e50950e18">llvm::ConstantRange::inverse</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a5bd6d98b4a7ecc1dcdc571e4352fcc52">llvm::ConstantRange::isEmptySet</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#abe8988eef2e6fc2baba032cb22afedd7">llvm::ICmpInst::isEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a4f6242fab5145c424cee29230fefe746">llvm::ConstantRange::isFullSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1d4262a8b76caa63441c7d5890c9b13e">llvm::isSignBitCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a3712279d70deeec90a93db09deb12d02">llvm::CmpInst::isSigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a59cab71d904ae725a5ef54bbf5490017">llvm::PatternMatch::m_APIntAllowPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aed04b081c4501c07d80fc69c308a0c23">llvm::PatternMatch::m_ElementWiseBitCast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af4f73c301d2b05039d2d8898e2c29822">llvm::PatternMatch::m_NSWMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a70e6404b68c92cddcbfbfcce69ce3334">llvm::PatternMatch::m_NUWMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a997de5064c00da2a575c5fa561dc3c65">llvm::PatternMatch::m_UIToFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa89e9cec92a0b38d2f47a077bf12cc98">llvm::ConstantRange::makeExactICmpRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#a9f2a11175d1af9d1bf62666c50c60145">llvm::InstrInfoQuery::UseInstrInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>.</p>

</div>
</div>

### simplifyICmpWithDominatingAssume() {#ae9417447cf23234d645221bda42e00c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyICmpWithDominatingAssume (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Predicate, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q)</td>
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



<p>Definition at line 3670 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a928ce56952772d0e0f43cab3a489a6fe">llvm::SimplifyQuery::AC</a>, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache/#ab711f68db26cb29c8332ac93c0bebed1">llvm::AssumptionCache::assumptionsFor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a30647c42c8c40890c577ba5b4ab16468">llvm::SimplifyQuery::CxtI</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a4776fa0f5a726bd5a8a444981c283c69">llvm::SimplifyQuery::DT</a>, <a href="#abee3cf86c05d2369d387f07f7055b9dc">getCompareTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7f2eb961a542779e97c0b3ec7fa6623">llvm::isImpliedCondition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f7c11444c9e7d7c1036ae1f049f4cee">llvm::isValidAssumeForContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>.</p>

</div>
</div>

### simplifyICmpWithIntrinsicOnLHS() {#a5e2e121dcbec9a2ede54e53ba8be83d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyICmpWithIntrinsicOnLHS (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS)</td>
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



<p>Definition at line 3693 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#abee3cf86c05d2369d387f07f7055b9dc">getCompareTy</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a9167d23c7fc4727aef51733d009e3f45">llvm::PatternMatch::m_c_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af5c293ba602295963ee06dd6f22e6335">llvm::PatternMatch::m_Sub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>.</p>

</div>
</div>

### simplifyICmpWithMinMax() {#a4f8adcab536e4c9f42e148d7eb218e6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyICmpWithMinMax (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>simplify integer comparisons where at least one operand of the compare matches an integer min/max idiom.</p>

<p>Definition at line 3485 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba07aee43ffb66908a25c55c77ce4c0d05">llvm::CmpInst::BAD_ICMP_PREDICATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#ad38d439eec395362c9cfce6c92751677">extractEquivalentCondition</a>, <a href="#abee3cf86c05d2369d387f07f7055b9dc">getCompareTy</a>, <a href="#a774f686ad651b962a54ad231e2212f64">getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="#aaa375e5211d9e07739a374c0479fb0ca">getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac981768f6aa97f560e4cb0290f0aaa9">llvm::PatternMatch::m_SMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a4709b4ef085b4ded2f9c2c888b35ee25">llvm::PatternMatch::m_SMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a7c1d2015b4d26f5afe0baf87f9e75782">llvm::PatternMatch::m_UMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af627036178ac57e62dd894233ce10fcb">llvm::PatternMatch::m_UMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83813cbf71633220ae57ad2b79498f77">llvm::simplifyICmpInst</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>.</p>

</div>
</div>

### simplifyICmpWithZero() {#a738d3c4d8f36cf843825c2b5a878f58a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyICmpWithZero (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q)</td>
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

<p>Try hard to fold icmp with zero RHS because this is a common case.</p>

<p>Definition at line 2935 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a>, <a href="#abee3cf86c05d2369d387f07f7055b9dc">getCompareTy</a>, <a href="#a774f686ad651b962a54ad231e2212f64">getFalse</a>, <a href="#aaa375e5211d9e07739a374c0479fb0ca">getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9893e3e4b14f8fa15d7c3c25a6a0b6f6">llvm::isKnownNonZero</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aabc0af41b4437080b27002ed7a1ed656">llvm::KnownBits::isNegative</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a157efd68e8b4b838829cad165b1583f8">llvm::KnownBits::isNonNegative</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>.</p>

</div>
</div>

### simplifyInsertValueInst() {#ac2e1b2bf5707da420c5d0578a227e34c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyInsertValueInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Agg, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Idxs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned)</td>
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

<p>Given operands for an <a href="/web-llvm/docs/api/classes/llvm/insertvalueinst">InsertValueInst</a>, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 5150 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad7fa9b738742521d0a684cec016ef47e">llvm::ConstantFoldInsertValueInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae058c4750de2c85f12a1f96841ac9ae3">llvm::isGuaranteedNotToBePoison</a> and <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>.</p>

</div>
</div>

### simplifyInstructionWithOperands() {#a3ef524444504c738f1da4b4fb0b5a238}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyInstructionWithOperands (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; NewOps, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; SQ, unsigned MaxRecurse)</td>
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

<p>See if we can compute a simplified version of this instruction.</p>


<p>If not, this returns null.</p>


<p>Definition at line 7098 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a291ac49156942529f159a9ec003cc25f">llvm::ArrayRef&lt; T &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bd5f9b3852cfb092d927ef2b04c7f6b">llvm::ConstantFoldInstOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a30647c42c8c40890c577ba5b4ab16468">llvm::SimplifyQuery::CxtI</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aa713e2599e000adc01ced998c05502a7">llvm::ArrayRef&lt; T &gt;::drop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a505cdf903e17bf9be677769bf0980adc">llvm::SimplifyQuery::getWithInstruction</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#a879785896627e7415e7aee7934bf922b">llvm::InstrInfoQuery::hasNoSignedWrap</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#affcd96f408768d8c1849b5293579143d">llvm::InstrInfoQuery::hasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#ad029c8abde2f42c8d5837bd5515bb18e">llvm::SimplifyQuery::IIQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#a0e8fe3b04971436feea66aca9016f45b">llvm::InstrInfoQuery::isExact</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e0af1b16cab9e0efc63a6ce9de2b9cc">llvm::simplifyAddInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f751e3ed5adc61048480e9fd0e257cc">llvm::simplifyAndInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0490e6e3fbdff8ae439abff8380ec7e2">llvm::simplifyAShrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3cc3d823b751599d37440440bd06096c">llvm::simplifyCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57b7707bae1b59648d9b09e7c3e1106c">llvm::simplifyCastInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee89448981f9fbc0d97fe68f354a8e82">llvm::simplifyExtractElementInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9442ed00a8dff89558d50f9c150951ff">llvm::simplifyExtractValueInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76162df5082ce14f7796e4307cba27fd">llvm::simplifyFAddInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a45d5f84f92a3fffaaca5d922ad632dba">llvm::simplifyFCmpInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a97ff52bca68f0168c930daf2fad29c72">llvm::simplifyFDivInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d4bdb0619aad92ee2de8f939930ba05">llvm::simplifyFMulInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6e06e93488a2f32aeb56f86797a78c33">llvm::simplifyFNegInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a12c01eba586da4db7ad4662e901b10a0">llvm::simplifyFreezeInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a75983bc94469337f93d99c6a2ad05699">llvm::simplifyFRemInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6e8a8610223f1f09b6000dcbca9649a5">llvm::simplifyFSubInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f010abd897957459c535649fa702c98">llvm::simplifyGEPInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83813cbf71633220ae57ad2b79498f77">llvm::simplifyICmpInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abdf4b5f9e1dc6887cac393ee643c10b6">llvm::simplifyInsertElementInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94b67449bc2ce740bcec33d149769fe0">llvm::simplifyInsertValueInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99fa28f2d78ae2ce889b621ab275a4ad">llvm::simplifyLoadInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a41cf2067684aff8591bb68edad443e">llvm::simplifyLShrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b9904a62f8c9179b90d1cb89e6e05ac">llvm::simplifyMulInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4f2dc2393a7799e74a0ab4aaa96783f6">llvm::simplifyOrInst</a>, <a href="#a308de6b87d4d431477642d086b268a7c">simplifyPHINode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23805d3a4c907766bf29b589ba786c81">llvm::simplifySDivInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af03a113ed05a87f07ee096463723cfc0">llvm::simplifySelectInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c052bfdf5f83877d32736ff3895cba5">llvm::simplifyShlInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4e04471ed9ac60e70f5cf2d81f49b8c4">llvm::simplifyShuffleVectorInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb98fd0d755e436c5749105d46b0c0d1">llvm::simplifySRemInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5942ddc4393a8ef081555f9a938c86e9">llvm::simplifySubInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab3b0406324f59a9dcdd00f68345ef9b7">llvm::simplifyUDivInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecb805c568634be3390c7da36836d63e">llvm::simplifyURemInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4f6b08837306196c6ff45fc5c65fe815">llvm::simplifyXorInst</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#aaf09fd551f7b18f7c75c662a8a8ed040">llvm::SimplifyQuery::TLI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a615619b0b2879029152b9a20e96624bc">llvm::transform</a>.</p>

</div>
</div>

### simplifyIntrinsic() {#a554988e4897106ec290097646fd1a84e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Callee, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Args, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q)</td>
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



<p>Definition at line 6795 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fp/#a51c5e09b2604faec548aef87bd482630ad8009e7c0ce2967115e856052243ac62">llvm::fp::ebIgnore</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpointernull/#a96f5c85e4022e369266541b2db3fda69">llvm::ConstantPointerNull::get</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="/web-llvm/docs/api/classes/llvm/gcrelocateinst/#ab825396e92860b35839338f7f1df75ad">llvm::GCRelocateInst::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/gcrelocateinst/#ae587391ac557593d998dbca4e62f0dab">llvm::GCRelocateInst::getDerivedPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aec662ee6ab1490a4cabebf2812e5b9ca">llvm::APInt::getOneBitSet</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a1d705f2b7894d43bae1ff46eaf600181">llvm::ConstantRange::getSingleElement</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a880ecb27263b592a9c72b96378c10088">llvm::getVScaleRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac8c0157adbe12649beac0009c2f6ad8d">llvm::APInt::isNonNegative</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a00ef056813d120034e387417e9cde341">llvm::PatternMatch::m_AllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2471be3f1b50002f54bf45c590d8d41b">llvm::PatternMatch::m_SpecificInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac43e0b6cbbe1e0d8988e9c5482573a92">llvm::maskIsAllZeroOrUndef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7ca44467144e3b6bdac3e85ef6f90e7d832">llvm::NearestTiesToEven</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab720ac4c86a5f16a755b1e5cd0d32c80">llvm::simplifyBinaryIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76162df5082ce14f7796e4307cba27fd">llvm::simplifyFAddInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a97ff52bca68f0168c930daf2fad29c72">llvm::simplifyFDivInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d4bdb0619aad92ee2de8f939930ba05">llvm::simplifyFMulInst</a>, <a href="#aa6498365e4fa2bc006fc4116b4b9b990">simplifyFPOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a75983bc94469337f93d99c6a2ad05699">llvm::simplifyFRemInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6e8a8610223f1f09b6000dcbca9649a5">llvm::simplifyFSubInst</a>, <a href="#ab6fe80e6f4b357ca0fdc9eafa69c430f">simplifyLdexp</a>, <a href="#afd74672cec2bec4f18c103c4cb7823d4">simplifyUnaryIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a4e3a2187cacdec76028617a403c47d89">llvm::APInt::urem</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3cc3d823b751599d37440440bd06096c">llvm::simplifyCall</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa45b543e17160f4f37f50d283ea5e2fe">llvm::simplifyConstrainedFPCall</a>.</p>

</div>
</div>

### simplifyLdexp() {#ab6fe80e6f4b357ca0fdc9eafa69c430f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyLdexp (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, bool IsStrict)</td>
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



<p>Definition at line 6235 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#ab21342133676f10340dc3f541b128f24">llvm::ConstantFP::getNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#acd794d7b3653822f61ba126e1678e03f">llvm::PatternMatch::m_APFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a54d7212b9b2c57cced42037ae2fa7c61">llvm::PatternMatch::m_ZeroInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab720ac4c86a5f16a755b1e5cd0d32c80">llvm::simplifyBinaryIntrinsic</a> and <a href="#a554988e4897106ec290097646fd1a84e">simplifyIntrinsic</a>.</p>

</div>
</div>

### simplifyLogicOfAddSub() {#ab8c09431e3ba6ccd88dfa4a32c2127be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyLogicOfAddSub (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> Opcode)</td>
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

<p>Given a bitwise logic op, check if the operands are add/sub with a common source value and inverted constant (identity: C - X -&gt; ~(X + ~C)).</p>

<p>Definition at line 1949 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a5b43a866f0fca605556f0f69f70c522a">llvm::ConstantExpr::getNot</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a2d0036d2d7b30f510927731ba7a4f4b9">llvm::Instruction::isBitwiseLogicOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a062ccd76a126632721e9aa09775d6c0e">llvm::PatternMatch::m_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a16be5fe0cce90e51f8c0e0c4d6c589f6">llvm::PatternMatch::m_Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af5c293ba602295963ee06dd6f22e6335">llvm::PatternMatch::m_Sub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="#a845e93029e92776841aaf5e0ec4c812f">simplifyOrInst</a> and <a href="#a9cfeea050198084d67109f0260e33970">simplifyXorInst</a>.</p>

</div>
</div>

### simplifyLShrInst() {#a0614870543ce4ba5b6f9c7030d6867e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyLShrInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, bool IsExact, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for an LShr, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 1437 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a70674aa792d906276123ab69dbdbfc69">llvm::KnownBits::countMaxActiveBits</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#ad029c8abde2f42c8d5837bd5515bb18e">llvm::SimplifyQuery::IIQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae80cbfea2025ff7bd0770f30be6e050a">llvm::PatternMatch::m_c_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a6d0a54a00095759d9be803abe46e2fad">llvm::PatternMatch::m_NUWShl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="#a5bb5f4b5b2420a7f3950939b2de01330">simplifyRightShift</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af4b1ccc0b78f9da9f3f3944e06007f1d">llvm::APInt::uge</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#a9f2a11175d1af9d1bf62666c50c60145">llvm::InstrInfoQuery::UseInstrInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### simplifyMulInst() {#a7f2df18bfd941b2e8d1cd78db5beb6f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyMulInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, bool IsNSW, bool IsNUW, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for a Mul, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 893 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a1588904a0310f8239c38e8790a1f1ca0">expandCommutativeBinOp</a>, <a href="#a15df887e1ad05e6c22a7c2e6492bde2d">foldOrCommuteConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#ad029c8abde2f42c8d5837bd5515bb18e">llvm::SimplifyQuery::IIQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a34ee40bb2f4f5ece47ef19e5f1f57e3c">llvm::Type::isIntOrIntVectorTy</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aba4c9e73cc7f76a376177d1dd8f32753">llvm::PatternMatch::m_Exact</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25e68280ed348917cd4b8657cac2be84">llvm::PatternMatch::m_IDiv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3b3d2d8c64a7881acb82bc7467569aa9">llvm::PatternMatch::m_One</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f751e3ed5adc61048480e9fd0e257cc">llvm::simplifyAndInst</a>, <a href="#a8863b1b71b53dbab1dd0bd7933ddb3cf">simplifyAssociativeBinOp</a>, <a href="#a914ac5681f80badb866f2aee44fc509a">threadBinOpOverPHI</a>, <a href="#ada3f0c65b41a26f74d332e974164ce55">threadBinOpOverSelect</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#a9f2a11175d1af9d1bf62666c50c60145">llvm::InstrInfoQuery::UseInstrInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### simplifyOrInst() {#a845e93029e92776841aaf5e0ec4c812f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyOrInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for an Or, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 2300 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="#a1588904a0310f8239c38e8790a1f1ca0">expandCommutativeBinOp</a>, <a href="#a15df887e1ad05e6c22a7c2e6492bde2d">foldOrCommuteConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aebd66f6649c1449adbcfcedf1651af18">llvm::isCheckForZeroAndMulWithOverflow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7f2eb961a542779e97c0b3ec7fa6623">llvm::isImpliedCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a34ee40bb2f4f5ece47ef19e5f1f57e3c">llvm::Type::isIntOrIntVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac328c5d387ddf7d4a02afe9b669723c7">llvm::APInt::isMask</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a00ef056813d120034e387417e9cde341">llvm::PatternMatch::m_AllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a014d851989a66ce781c4f89dfffb26b5">llvm::PatternMatch::m_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a9167d23c7fc4727aef51733d009e3f45">llvm::PatternMatch::m_c_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab8546ee1aaa68d6f4990e6241e24464c">llvm::PatternMatch::m_LShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3b3d2d8c64a7881acb82bc7467569aa9">llvm::PatternMatch::m_One</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3ccd94f6a7507492b47c7351e3fb78c6">llvm::PatternMatch::m_Select</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ac1c7b78fe67245930be18441b77de500">llvm::PatternMatch::m_Shl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2471be3f1b50002f54bf45c590d8d41b">llvm::PatternMatch::m_SpecificInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af5c293ba602295963ee06dd6f22e6335">llvm::PatternMatch::m_Sub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1cacb72e897c55bdfd5c726d13d69af1">llvm::PatternMatch::m_Xor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5738f911a81d4a66c8778d86be098dde">llvm::MaskedValueIsZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#ad4122a9286a8dd18458df1f47230e07f">simplifyAndOrOfCmps</a>, <a href="#ae739737036faaf1bcaa66a0f4a8e1e63">simplifyAndOrWithICmpEq</a>, <a href="#a8863b1b71b53dbab1dd0bd7933ddb3cf">simplifyAssociativeBinOp</a>, <a href="#a6343e645572ce8783bbf5853d181479f">simplifyByDomEq</a>, <a href="#ab8c09431e3ba6ccd88dfa4a32c2127be">simplifyLogicOfAddSub</a>, <a href="#abd241acbc11f163c5843ef83d13af545">simplifyOrLogic</a>, <a href="#a914ac5681f80badb866f2aee44fc509a">threadBinOpOverPHI</a>, <a href="#ada3f0c65b41a26f74d332e974164ce55">threadBinOpOverSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### simplifyOrLogic() {#abd241acbc11f163c5843ef83d13af545}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyOrLogic (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * X, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Y)</td>
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



<p>Definition at line 2209 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a014d851989a66ce781c4f89dfffb26b5">llvm::PatternMatch::m_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1981217907f3dfb1d21e902d0396fb4d">llvm::PatternMatch::m_c_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ac138cdb8de41089b8e5ab1f22b1717df">llvm::PatternMatch::m_c_LogicalAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aebe3178dbc20a19127a51895c26792b7">llvm::PatternMatch::m_c_LogicalOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae80cbfea2025ff7bd0770f30be6e050a">llvm::PatternMatch::m_c_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a4e2ffa92003f2eca82197ea662b30f16">llvm::PatternMatch::m_c_Xor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a469c3ed35e782000933c996ccd2d2333">llvm::PatternMatch::m_CombineAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1cacb72e897c55bdfd5c726d13d69af1">llvm::PatternMatch::m_Xor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="#a845e93029e92776841aaf5e0ec4c812f">simplifyOrInst</a>.</p>

</div>
</div>

### simplifyOrOfICmps() {#a6b86bbc17cbb2be2b63a54fcdbcf4251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyOrOfICmps (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q)</td>
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



<p>Definition at line 1791 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#ad029c8abde2f42c8d5837bd5515bb18e">llvm::SimplifyQuery::IIQ</a>, <a href="#ae5781faa80a27cf51fa316feaa2ad363">simplifyAndOrOfICmpsWithConstants</a>, <a href="#a426204f20670379cdefabed663ac339f">simplifyAndOrOfICmpsWithCtpop</a>, <a href="#a7b473dc0c6603bb29f38c46858df840e">simplifyOrOfICmpsWithAdd</a>, <a href="#a4355ad633eda8e7c8a6538ea41bb34f3">simplifyUnsignedRangeCheck</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#ad4122a9286a8dd18458df1f47230e07f">simplifyAndOrOfCmps</a>.</p>

</div>
</div>

### simplifyOrOfICmpsWithAdd() {#a7b473dc0c6603bb29f38c46858df840e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyOrOfICmpsWithAdd (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery">InstrInfoQuery</a> &amp; IIQ)</td>
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



<p>Definition at line 1744 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac0e942dde4b113c4c0b1fd76333db93a">llvm::APInt::getBoolValue</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="#aaa375e5211d9e07739a374c0479fb0ca">getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#a879785896627e7415e7aee7934bf922b">llvm::InstrInfoQuery::hasNoSignedWrap</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#affcd96f408768d8c1849b5293579143d">llvm::InstrInfoQuery::hasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aa17c104fbda554c818cf87e53f32f20a">llvm::APInt::isStrictlyPositive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a062ccd76a126632721e9aa09775d6c0e">llvm::PatternMatch::m_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab86c85b47e09489dcda68fd91d082d77">llvm::PatternMatch::m_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="#a6b86bbc17cbb2be2b63a54fcdbcf4251">simplifyOrOfICmps</a>.</p>

</div>
</div>

### simplifyPHINode() {#a308de6b87d4d431477642d086b268a7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyPHINode (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; IncomingValues, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q)</td>
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

<p>See if we can fold the given phi. If not, returns null.</p>

<p>Definition at line 5310 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a928ce56952772d0e0f43cab3a489a6fe">llvm::SimplifyQuery::AC</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a30647c42c8c40890c577ba5b4ab16468">llvm::SimplifyQuery::CxtI</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a4776fa0f5a726bd5a8a444981c283c69">llvm::SimplifyQuery::DT</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae058c4750de2c85f12a1f96841ac9ae3">llvm::isGuaranteedNotToBePoison</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a> and <a href="#af412caabe4d2526271b50f052f9d3aef">valueDominatesPHI</a>.</p>


<p>Referenced by <a href="#a3ef524444504c738f1da4b4fb0b5a238">simplifyInstructionWithOperands</a>.</p>

</div>
</div>

### simplifyRelativeLoad() {#a2c78ae45454d731f51f0ce021a729816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyRelativeLoad (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Offset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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



<p>Definition at line 6182 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad95650d790f6f9d252cf0cd0e0094368">llvm::ConstantFoldLoadFromConstPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e3103683ccd8b97050f821110b98ad2">llvm::IsConstantOffsetFromGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a9b5fc98b47d44d1150d3610bdfab1430">llvm::APInt::sextOrTrunc</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#ac131d830427393332e440e1d6e3013b6">llvm::APInt::srem</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab720ac4c86a5f16a755b1e5cd0d32c80">llvm::simplifyBinaryIntrinsic</a>.</p>

</div>
</div>

### simplifyRem() {#aed163588354401b6679a39acad6fae2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyRem (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>These are simplifications common to SRem and URem.</p>

<p>Definition at line 1170 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a15df887e1ad05e6c22a7c2e6492bde2d">foldOrCommuteConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#ad029c8abde2f42c8d5837bd5515bb18e">llvm::SimplifyQuery::IIQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a89dd53e89611a77bed079b8c20fbf3d4">llvm::PatternMatch::m_CheckedInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af4f73c301d2b05039d2d8898e2c29822">llvm::PatternMatch::m_NSWMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a67de7538f206bdfb3112f59b272bf4bd">llvm::PatternMatch::m_NSWShl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a70e6404b68c92cddcbfbfcce69ce3334">llvm::PatternMatch::m_NUWMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a6d0a54a00095759d9be803abe46e2fad">llvm::PatternMatch::m_NUWShl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="#a789b1341fc862e30623b200657911a4c">simplifyDivRem</a> and <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#a9f2a11175d1af9d1bf62666c50c60145">llvm::InstrInfoQuery::UseInstrInfo</a>.</p>


<p>Referenced by <a href="#add0275e00f4260c742c6cf3ec24b1987">simplifySRemInst</a> and <a href="#aa2135d9db611a0be89044fae9b38e1f9">simplifyURemInst</a>.</p>

</div>
</div>

### simplifyRightShift() {#a5bb5f4b5b2420a7f3950939b2de01330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyRightShift (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, bool IsExact, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for an LShr or AShr, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 1367 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aba205f553f24c184ea47fc1a6cb56537">llvm::KnownBits::One</a> and <a href="#ae9d2883e296d808c7a9e18efcee71049">simplifyShift</a>.</p>


<p>Referenced by <a href="#a29b4afe26752d50b7207bf4cd3f984f3">simplifyAShrInst</a> and <a href="#a0614870543ce4ba5b6f9c7030d6867e2">simplifyLShrInst</a>.</p>

</div>
</div>

### simplifySDivInst() {#a630c735bfbff439b152d83f92302cb34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifySDivInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, bool IsExact, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for an SDiv, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 1207 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae35d199ef2ac7fc6d6a5294aa8070a9e">llvm::isKnownNegation</a> and <a href="#a2d67c7fd2789ef1dfb05513f1eb8d054">simplifyDiv</a>.</p>

</div>
</div>

### simplifySelectBitTest() {#a87692407367823d3d593f8bf289f0785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifySelectBitTest (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * TrueVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * FalseVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * X, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> * Y, bool TrueWhenUnset)</td>
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

<p>Try to simplify a select instruction when its condition operand is an integer comparison where one operand of the compare is a constant.</p>

<p>Definition at line 4503 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a014d851989a66ce781c4f89dfffb26b5">llvm::PatternMatch::m_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae44af1eeb2e5f7a1973a4ab78963a503">llvm::PatternMatch::m_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="#a04d52227379f9e4c460d52bb45f92ff4">simplifySelectWithFakeICmpEq</a> and <a href="#afa1ff3254ee225171cb55d46b0eab145">simplifySelectWithICmpCond</a>.</p>

</div>
</div>

### simplifySelectInst() {#a38dc339806a701c1f11ec31cf76936ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifySelectInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * TrueVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * FalseVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for a <a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a>, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 4828 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11c89e0918b007ef2cf1d6b03c4b4948">llvm::ConstantFoldSelectInstruction</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a30647c42c8c40890c577ba5b4ab16468">llvm::SimplifyQuery::CxtI</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#ade9fa017ca3aa82f7694a47090547bc1">llvm::ConstantVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#acd530d0571f320d47d37e7ae51cf70ff">llvm::Constant::getAggregateElement</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71a4a4e0f6178682ef05a0d85891e5a9">llvm::impliesPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae058c4750de2c85f12a1f96841ac9ae3">llvm::isGuaranteedNotToBePoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adbc4e5b23d7154e30b03717a470e8178">llvm::isImpliedByDomCondition</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ac138cdb8de41089b8e5ab1f22b1717df">llvm::PatternMatch::m_c_LogicalAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aebe3178dbc20a19127a51895c26792b7">llvm::PatternMatch::m_c_LogicalOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a16be5fe0cce90e51f8c0e0c4d6c589f6">llvm::PatternMatch::m_Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3b3d2d8c64a7881acb82bc7467569aa9">llvm::PatternMatch::m_One</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a54d7212b9b2c57cced42037ae2fa7c61">llvm::PatternMatch::m_ZeroInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a75fa36408fed5acf91329505b3419196">simplifySelectWithFCmp</a>, <a href="#afa1ff3254ee225171cb55d46b0eab145">simplifySelectWithICmpCond</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### simplifySelectWithEquivalence() {#a7bee73e1eef011ba0a15bcb696cb0971}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifySelectWithEquivalence (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &gt; Replacements, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * TrueVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * FalseVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Try to simplify a select instruction when its condition operand is an integer equality or floating-point equivalence comparison.</p>

<p>Definition at line 4630 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#aba451d2306d849c2ca6821dfe84587a9">llvm::SimplifyQuery::getWithoutUndef</a> and <a href="#a4611905728c0ddaed9f8964ae8b074a2">simplifyWithOpsReplaced</a>.</p>


<p>Referenced by <a href="#a75fa36408fed5acf91329505b3419196">simplifySelectWithFCmp</a> and <a href="#afa1ff3254ee225171cb55d46b0eab145">simplifySelectWithICmpCond</a>.</p>

</div>
</div>

### simplifySelectWithFakeICmpEq() {#a04d52227379f9e4c460d52bb45f92ff4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifySelectWithFakeICmpEq (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * CmpLHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * CmpRHS, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * TrueVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * FalseVal)</td>
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

<p>An alternative way to test if a bit is set or not uses sgt/slt instead of eq/ne.</p>

<p>Definition at line 4618 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aaf52bffe6dc4a6d5d5cf515aac2e4450">llvm::decomposeBitTestICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a> and <a href="#a87692407367823d3d593f8bf289f0785">simplifySelectBitTest</a>.</p>


<p>Referenced by <a href="#afa1ff3254ee225171cb55d46b0eab145">simplifySelectWithICmpCond</a>.</p>

</div>
</div>

### simplifySelectWithFCmp() {#a75fa36408fed5acf91329505b3419196}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifySelectWithFCmp (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * T, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Try to simplify a select instruction when its condition operand is a floating-point comparison.</p>

<p>Definition at line 4778 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a30647c42c8c40890c577ba5b4ab16468">llvm::SimplifyQuery::CxtI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba024db78a5ed74f64666f3ca4955e6eca">llvm::CmpInst::FCMP_OEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad601460c9371d0f0ada5ae006bdba2bd">llvm::CmpInst::FCMP_UNE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a2c8498183c5bce88fb4f651ee4169611">llvm::Instruction::hasNoSignedZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a08d5220c6f77428fcfd5bd1de5af2bbc">llvm::PatternMatch::m_FCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="#a7bee73e1eef011ba0a15bcb696cb0971">simplifySelectWithEquivalence</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a38dc339806a701c1f11ec31cf76936ff">simplifySelectInst</a>.</p>

</div>
</div>

### simplifySelectWithICmpCond() {#afa1ff3254ee225171cb55d46b0eab145}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifySelectWithICmpCond (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * CondVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * TrueVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * FalseVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Try to simplify a select instruction when its condition operand is an integer comparison.</p>

<p>Definition at line 4655 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a6f5cd5733f1f4d2254248b60fb8a937f">llvm::canReplacePointersIfEqual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/structs/llvm/selectpatternresult/#a3ca9c2098248eac9051008d6eb9f321d">llvm::SelectPatternResult::Flavor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6626b9250a7ec4cc54a9e8ce78bc0cc3">llvm::getInverseMinMaxFlavor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a221f053d5107888218e536fe5f1f457c">llvm::getMinMaxLimit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a493bd393688f22538e5de34117e70236">llvm::getMinMaxPred</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a34ee40bb2f4f5ece47ef19e5f1f57e3c">llvm::Type::isIntOrIntVectorTy</a>, <a href="/web-llvm/docs/api/structs/llvm/selectpatternresult/#a94c732c9e96c40976f0509fe0233fe7b">llvm::SelectPatternResult::isMinOrMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a00ef056813d120034e387417e9cde341">llvm::PatternMatch::m_AllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a014d851989a66ce781c4f89dfffb26b5">llvm::PatternMatch::m_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#afc43bc5ec4b20c7c5d663bef90da6066">llvm::PatternMatch::m_CombineOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a53fc7d443cf6412add6dfddd11652e5d">llvm::PatternMatch::m_Deferred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a9b00c4440366f614c142157502105fda">llvm::PatternMatch::m_FShl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ad2886e078317288a5a7c0709ee5a58d4">llvm::PatternMatch::m_FShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab86c85b47e09489dcda68fd91d082d77">llvm::PatternMatch::m_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5d295dcffba83c3c5a17d2fb3273b434">llvm::PatternMatch::m_Neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae44af1eeb2e5f7a1973a4ab78963a503">llvm::PatternMatch::m_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2471be3f1b50002f54bf45c590d8d41b">llvm::PatternMatch::m_SpecificInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf62ca503c047621e9b9047c548f231f">llvm::matchDecomposedSelectPattern</a>, <a href="#a93f2e165baf61dd8295c9aececed9985">simplifyCmpSelOfMaxMin</a>, <a href="#a87692407367823d3d593f8bf289f0785">simplifySelectBitTest</a>, <a href="#a7bee73e1eef011ba0a15bcb696cb0971">simplifySelectWithEquivalence</a>, <a href="#a04d52227379f9e4c460d52bb45f92ff4">simplifySelectWithFakeICmpEq</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="#a38dc339806a701c1f11ec31cf76936ff">simplifySelectInst</a>.</p>

</div>
</div>

### simplifyShift() {#ae9d2883e296d808c7a9e18efcee71049}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyShift (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, bool IsNSW, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for an Shl, LShr or AShr, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 1297 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a1eeff70353694cb360b2893553c18e7d">llvm::KnownBits::countMinTrailingZeros</a>, <a href="#a15df887e1ad05e6c22a7c2e6492bde2d">foldOrCommuteConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a4fdc09049a61f952b5d52788dbd2f69b">llvm::KnownBits::getBitWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9b35c622a902a7a7dc93b807a9fa9265">llvm::KnownBits::getMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a44875c6f48f6c843cf3114a19280b5ca">llvm::KnownBits::hasConflict</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a587eab2c520053bb06fdc4afe5a57aa3">isPoisonShift</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ada19a89b7c62ce0bb713a7254b002445">llvm::APInt::isSignBitSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a058782b98991f0719657d9008d3df41b">llvm::Log2_32_Ceil</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae5cf2b09af0c75d08cf9e5e8f2818a66">llvm::PatternMatch::m_SExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aba205f553f24c184ea47fc1a6cb56537">llvm::KnownBits::One</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a4f1e1a4449b58958c5884c689e7f4861">llvm::APInt::setSignBit</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ae9ffa8b50ca6095202b2e8e7686c10b8">llvm::KnownBits::shl</a>, <a href="#a914ac5681f80badb866f2aee44fc509a">threadBinOpOverPHI</a>, <a href="#ada3f0c65b41a26f74d332e974164ce55">threadBinOpOverSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af4b1ccc0b78f9da9f3f3944e06007f1d">llvm::APInt::uge</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>


<p>Referenced by <a href="#a5bb5f4b5b2420a7f3950939b2de01330">simplifyRightShift</a> and <a href="#a8e2f5715194e637f638fcd6e0851448b">simplifyShlInst</a>.</p>

</div>
</div>

### simplifyShlInst() {#a8e2f5715194e637f638fcd6e0851448b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyShlInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, bool IsNSW, bool IsNUW, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for an Shl, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 1396 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#ad029c8abde2f42c8d5837bd5515bb18e">llvm::SimplifyQuery::IIQ</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aba4c9e73cc7f76a376177d1dd8f32753">llvm::PatternMatch::m_Exact</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a03862c488e6a18ba12e388061189a888">llvm::PatternMatch::m_Negative</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a310fbeb4d6c1b137dfd8713d354f3d76">llvm::PatternMatch::m_Shr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2471be3f1b50002f54bf45c590d8d41b">llvm::PatternMatch::m_SpecificInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="#ae9d2883e296d808c7a9e18efcee71049">simplifyShift</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#a9f2a11175d1af9d1bf62666c50c60145">llvm::InstrInfoQuery::UseInstrInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### simplifyShuffleVectorInst() {#a0bf04415ab72b83b24140635c6a7ea52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyShuffleVectorInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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



<p>Definition at line 5457 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad78da75bd1f157e72100f97d1ecdc756">llvm::all_equal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a38c50aa8e3e9588f4f968c2e03a0cee0">llvm::SmallVectorImpl&lt; T &gt;::assign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a9874bec83353914ed1e9309d5d9ccea0">llvm::ShuffleVectorInst::commuteShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ac91d6fa292dc4e13ce99fc9f02c90f85">foldIdentityShuffles</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#ade9fa017ca3aa82f7694a47090547bc1">llvm::ConstantVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a6f6506f0bc515fe29da3b58565300017">llvm::ConstantExpr::getShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#ac09a21c371a9c535cbc13e8f82503aec">llvm::ConstantInt::getZExtValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a16be5fe0cce90e51f8c0e0c4d6c589f6">llvm::PatternMatch::m_Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3aa1f5d3cd54d36e7e47f401a0118aeb">llvm::PatternMatch::m_ConstantInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aec67d7d9e090f41ec66d0d10169a440e">llvm::PatternMatch::m_InsertElt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### simplifySRemInst() {#add0275e00f4260c742c6cf3ec24b1987}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifySRemInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for an SRem, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 1235 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae35d199ef2ac7fc6d6a5294aa8070a9e">llvm::isKnownNegation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae5cf2b09af0c75d08cf9e5e8f2818a66">llvm::PatternMatch::m_SExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="#aed163588354401b6679a39acad6fae2a">simplifyRem</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### simplifySubInst() {#a0e278bb318fd700a9c8d4f4a7c8caba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifySubInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, bool IsNSW, bool IsNUW, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for a Sub, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 742 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a>, <a href="#adc235173f78d0b2a260bb5438267139e">computePointerDifference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45c454aff5d0478a70219bb15d369b3">llvm::ConstantFoldIntegerCast</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="#a15df887e1ad05e6c22a7c2e6492bde2d">foldOrCommuteConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a34ee40bb2f4f5ece47ef19e5f1f57e3c">llvm::Type::isIntOrIntVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac8099bedfdef48644386b16230fef2e5">llvm::APInt::isMaxSignedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a062ccd76a126632721e9aa09775d6c0e">llvm::PatternMatch::m_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a012d56149a3f8d7211f5e7680633861f">llvm::PatternMatch::m_LowBitMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af15a15d65884a305e9eec3b690eb37f3">llvm::PatternMatch::m_PtrToInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af5c293ba602295963ee06dd6f22e6335">llvm::PatternMatch::m_Sub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1b8442c10c9ed6e0e07160b54541450e">llvm::PatternMatch::m_Trunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1cacb72e897c55bdfd5c726d13d69af1">llvm::PatternMatch::m_Xor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa750395459fa1eb7130d6de8e3d074f6">llvm::simplifyBinOp</a>, <a href="#a6343e645572ce8783bbf5853d181479f">simplifyByDomEq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57b7707bae1b59648d9b09e7c3e1106c">llvm::simplifyCastInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4f6b08837306196c6ff45fc5c65fe815">llvm::simplifyXorInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>

</div>
</div>

### simplifyUDivInst() {#a08c5c0e210c3418665efc1bc160ebcfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyUDivInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, bool IsExact, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for a UDiv, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 1223 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>Reference <a href="#a2d67c7fd2789ef1dfb05513f1eb8d054">simplifyDiv</a>.</p>

</div>
</div>

### simplifyUnaryIntrinsic() {#afd74672cec2bec4f18c103c4cb7823d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyUnaryIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call)</td>
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



<p>Definition at line 6284 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a928ce56952772d0e0f43cab3a489a6fe">llvm::SimplifyQuery::AC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace654b9b621b04f88a6611c00e815880">llvm::computeKnownFPSignBit</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a30647c42c8c40890c577ba5b4ab16468">llvm::SimplifyQuery::CxtI</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a4776fa0f5a726bd5a8a444981c283c69">llvm::SimplifyQuery::DT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adcb96bd09d7c75c7669fa5f9d1190899">llvm::APInt::getHighBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#a3f39d8494e80ff534547de5b51a30623">isIdempotent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4036c3c75bcee1206cd199548b87f9ae">llvm::isKnownToBeAPowerOfTwo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6339f2ad6701dc229c34ca4305596d3a">llvm::isSplatValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0eb993474e9ffa2056f664cdc2e14ad4">llvm::PatternMatch::m_BitReverse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae4e4b162282728d327227c5773592d65">llvm::PatternMatch::m_BSwap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a445051c482340bacd1e3264406421afb">llvm::PatternMatch::m_ExtractValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab6ebd06f5c6506c6187670934a669db6">llvm::PatternMatch::m_SIToFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a43117391a6d351518362783bff747d44">llvm::PatternMatch::m_SpecificFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a997de5064c00da2a575c5fa561dc3c65">llvm::PatternMatch::m_UIToFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#acaf7ff6a377746861ec2f167c3c574dc">llvm::PatternMatch::m_VecReverse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5738f911a81d4a66c8778d86be098dde">llvm::MaskedValueIsZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="#a796b1851dc68b49eaeeeb7af4ff3f74b">removesFPFraction</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#a554988e4897106ec290097646fd1a84e">simplifyIntrinsic</a>.</p>

</div>
</div>

### simplifyUnOp() {#a3ba3e8fde7409234793175d6a978ffab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyUnOp (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given the operand for a <a href="/web-llvm/docs/api/classes/llvm/unaryoperator">UnaryOperator</a>, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 6018 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6e06e93488a2f32aeb56f86797a78c33">llvm::simplifyFNegInst</a>.</p>

</div>
</div>

### simplifyUnsignedRangeCheck() {#a4355ad633eda8e7c8a6538ea41bb34f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyUnsignedRangeCheck (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * ZeroICmp, <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * UnsignedICmp, bool IsAnd, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q)</td>
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

<p>Commuted variants are assumed to be handled by calling this function again with the parameters swapped.</p>

<p>Definition at line 1507 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a774f686ad651b962a54ad231e2212f64">getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="#aaa375e5211d9e07739a374c0479fb0ca">getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#abe8988eef2e6fc2baba032cb22afedd7">llvm::ICmpInst::isEquality</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9893e3e4b14f8fa15d7c3c25a6a0b6f6">llvm::isKnownNonZero</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#af206a3d6f58d9e53b074460f0d1ecb86">llvm::CmpInst::isUnsigned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a327f8dad1ecd68d640256e844d49f9ba">llvm::PatternMatch::m_c_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab86c85b47e09489dcda68fd91d082d77">llvm::PatternMatch::m_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af5c293ba602295963ee06dd6f22e6335">llvm::PatternMatch::m_Sub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="#ac1907d1fccfb9846bfd91b6b79c0acbc">simplifyAndOfICmps</a> and <a href="#a6b86bbc17cbb2be2b63a54fcdbcf4251">simplifyOrOfICmps</a>.</p>

</div>
</div>

### simplifyURemInst() {#aa2135d9db611a0be89044fae9b38e1f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyURemInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for a URem, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 1256 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>Reference <a href="#aed163588354401b6679a39acad6fae2a">simplifyRem</a>.</p>

</div>
</div>

### simplifyWithOpReplaced() {#ad70420ff755267b04fb5a24ca252bf32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyWithOpReplaced (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RepOp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, bool AllowRefinement, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; * DropFlags, unsigned MaxRecurse)</td>
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



<p>Definition at line 4479 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>Reference <a href="#a4611905728c0ddaed9f8964ae8b074a2">simplifyWithOpsReplaced</a>.</p>

</div>
</div>

### simplifyWithOpsReplaced() {#a4611905728c0ddaed9f8964ae8b074a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyWithOpsReplaced (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &gt; Ops, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, bool AllowRefinement, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; * DropFlags, unsigned MaxRecurse)</td>
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



<p>Definition at line 4295 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a118b2507b9f8c68c87b2592913406e86">llvm::canCreatePoison</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a3b12da4ca5cd8514b068a30f8716db31">llvm::SimplifyQuery::CanUseUndef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bd5f9b3852cfb092d927ef2b04c7f6b">llvm::ConstantFoldInstOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a47f9877ae06a287965eb7a7432e4c566">llvm::ConstantExpr::getBinOpAbsorber</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae9c2f00a962cb8e0316cf3548a5d8029">llvm::ConstantExpr::getBinOpIdentity</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71a4a4e0f6178682ef05a0d85891e5a9">llvm::impliesPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a947ca061d5d11bc9ff70f6782261225d">llvm::isNotCrossLaneOperation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a367cc3c1cd48f8723586daebe9a17d00">llvm::simplifyInstructionWithOperands</a>, <a href="#a4611905728c0ddaed9f8964ae8b074a2">simplifyWithOpsReplaced</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#aaf09fd551f7b18f7c75c662a8a8ed040">llvm::SimplifyQuery::TLI</a>.</p>


<p>Referenced by <a href="#a7bee73e1eef011ba0a15bcb696cb0971">simplifySelectWithEquivalence</a>, <a href="#ad70420ff755267b04fb5a24ca252bf32">simplifyWithOpReplaced</a> and <a href="#a4611905728c0ddaed9f8964ae8b074a2">simplifyWithOpsReplaced</a>.</p>

</div>
</div>

### simplifyXorInst() {#a9cfeea050198084d67109f0260e33970}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyXorInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>Given operands for a Xor, see if we can fold the result.</p>


<p>If not, this returns null.</p>


<p>Definition at line 2484 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a15df887e1ad05e6c22a7c2e6492bde2d">foldOrCommuteConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1981217907f3dfb1d21e902d0396fb4d">llvm::PatternMatch::m_c_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae80cbfea2025ff7bd0770f30be6e050a">llvm::PatternMatch::m_c_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a469c3ed35e782000933c996ccd2d2333">llvm::PatternMatch::m_CombineAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a012d56149a3f8d7211f5e7680633861f">llvm::PatternMatch::m_LowBitMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aa7ccc4b69ee025f62e15e1c6b0c468f0">llvm::PatternMatch::m_NUWSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="#a8863b1b71b53dbab1dd0bd7933ddb3cf">simplifyAssociativeBinOp</a>, <a href="#a6343e645572ce8783bbf5853d181479f">simplifyByDomEq</a>, <a href="#ab8c09431e3ba6ccd88dfa4a32c2127be">simplifyLogicOfAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### STATISTIC() {#acfd0bbcbc789bf86c6670e4de61edaba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumExpand, "Number of expansions")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a6b287edafd0ce24fba1ca0841ef69c8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumReassoc, "Number of reassociations")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### stripAndComputeConstantOffsets() {#a59cd1a000769414b2d832576bf689c32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt stripAndComputeConstantOffsets (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; V, bool AllowNonInbounds=false)</td>
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

<p>Compute the base pointer and cumulative constant offsets for V.</p>


<p>This strips all constant offsets off of V, leaving it the base pointer, and accumulates the total constant offset applied in the returned constant. It returns zero if there are no constant offsets applied.</p>


<p>This is very similar to stripAndAccumulateConstantOffsets(), except it normalizes the offset bitwidth to the stripped pointer type, not the original pointer type.</p>


<p>Definition at line 671 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#adc235173f78d0b2a260bb5438267139e">computePointerDifference</a>.</p>

</div>
</div>

### threadBinOpOverPHI() {#a914ac5681f80badb866f2aee44fc509a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * threadBinOpOverPHI (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>In the case of a binary operation with an operand that is a PHI instruction, try to simplify the binop by seeing whether evaluating it on the incoming phi values yields the same result for every value.</p>


<p>If so returns the common value, otherwise returns null.</p>


<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a4776fa0f5a726bd5a8a444981c283c69">llvm::SimplifyQuery::DT</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ac53e1aabdf64e91b8b325bcac250d8a9">llvm::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a505cdf903e17bf9be677769bf0980adc">llvm::SimplifyQuery::getWithInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a1f0ff79b64a40d383b891f1baba89c6b">llvm::PHINode::incoming_values</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa750395459fa1eb7130d6de8e3d074f6">llvm::simplifyBinOp</a> and <a href="#af412caabe4d2526271b50f052f9d3aef">valueDominatesPHI</a>.</p>


<p>Referenced by <a href="#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="#a789b1341fc862e30623b200657911a4c">simplifyDivRem</a>, <a href="#a7f2df18bfd941b2e8d1cd78db5beb6f7">simplifyMulInst</a>, <a href="#a845e93029e92776841aaf5e0ec4c812f">simplifyOrInst</a> and <a href="#ae9d2883e296d808c7a9e18efcee71049">simplifyShift</a>.</p>

</div>
</div>

### threadBinOpOverSelect() {#ada3f0c65b41a26f74d332e974164ce55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * threadBinOpOverSelect (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>In the case of a binary operation with a select instruction as an operand, try to simplify the binop by seeing whether evaluating it on both branches of the select results in the same value.</p>


<p>Returns the common value if so, otherwise returns null.</p>


<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa750395459fa1eb7130d6de8e3d074f6">llvm::simplifyBinOp</a>.</p>


<p>Referenced by <a href="#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="#a789b1341fc862e30623b200657911a4c">simplifyDivRem</a>, <a href="#a7f2df18bfd941b2e8d1cd78db5beb6f7">simplifyMulInst</a>, <a href="#a845e93029e92776841aaf5e0ec4c812f">simplifyOrInst</a> and <a href="#ae9d2883e296d808c7a9e18efcee71049">simplifyShift</a>.</p>

</div>
</div>

### threadCmpOverPHI() {#a1ec7a76fbddf5983969def6e47c0f177}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * threadCmpOverPHI (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>In the case of a comparison with a PHI instruction, try to simplify the comparison by seeing whether comparing with all of the incoming phi values yields the same result every time.</p>


<p>If so returns the common result, otherwise returns null.</p>


<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a4776fa0f5a726bd5a8a444981c283c69">llvm::SimplifyQuery::DT</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ac53e1aabdf64e91b8b325bcac250d8a9">llvm::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aca1fd00f3ab63ec8f0f1ccc2093a9f6d">llvm::PHINode::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aef51af4b490af6b3bf2dfbc8737a8f9f">llvm::PHINode::getNumIncomingValues</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a505cdf903e17bf9be677769bf0980adc">llvm::SimplifyQuery::getWithInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adccdd5d6b0c85f7917306e296b27c4cd">llvm::simplifyCmpInst</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="#af412caabe4d2526271b50f052f9d3aef">valueDominatesPHI</a>.</p>


<p>Referenced by <a href="#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a> and <a href="#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>.</p>

</div>
</div>

### threadCmpOverSelect() {#aa6faca61824779a7d72a2c1e08b9e7a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * threadCmpOverSelect (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, unsigned MaxRecurse)</td>
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

<p>In the case of a comparison with a select instruction, try to simplify the comparison by seeing whether both branches of the select result in the same value.</p>


<p>Returns the common value if so, otherwise returns null. For example, if we have: tmp = select i1 cmp, i32 1, i32 2 cmp1 = icmp sle i32 tmp, 3 We can simplify cmp1 to true, because both branches of select are less than 3. We compose new comparison by substituting tmp with both branches of select and see if it can be simplified.</p>


<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="#a1b14bc4633dc9ebd06733a8792510cbe">handleOtherCmpSelSimplifications</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#a022b0d31de4686085b7c8d2719a3edd7">simplifyCmpSelFalseCase</a>, <a href="#a5211abbd14c49ebe208e93000a365ef0">simplifyCmpSelTrueCase</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a> and <a href="#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>.</p>

</div>
</div>

### tryConstantFoldCall() {#a4394b9bd9afc3ae5f5477e8c265d8b0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * tryConstantFoldCall (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Callee, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Args, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q)</td>
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



<p>Definition at line 6988 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20f356124998d05f7e605549cc2dda91">llvm::canConstantFoldCallTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4e3a3843bf5e85d3d55c2a252ec235bd">llvm::ConstantFoldCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a> and <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#aaf09fd551f7b18f7c75c662a8a8ed040">llvm::SimplifyQuery::TLI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3cc3d823b751599d37440440bd06096c">llvm::simplifyCall</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa45b543e17160f4f37f50d283ea5e2fe">llvm::simplifyConstrainedFPCall</a>.</p>

</div>
</div>

### trySimplifyICmpWithAdds() {#a86f75bbbe87c45fd3f9047fbad61671c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool trySimplifyICmpWithAdds (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery">InstrInfoQuery</a> &amp; IIQ)</td>
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



<p>Definition at line 3226 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac8c0157adbe12649beac0009c2f6ad8d">llvm::APInt::isNonNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a98e0e44eba106bcebce4b276d2c541c9">llvm::APInt::isNonPositive</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a062ccd76a126632721e9aa09775d6c0e">llvm::PatternMatch::m_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab65bddcf2ef369ad6d5678882800a7da">llvm::PatternMatch::m_NSWAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adafa9575780f9246d1df0b7e2a619356">llvm::APInt::slt</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery/#a9f2a11175d1af9d1bf62666c50c60145">llvm::InstrInfoQuery::UseInstrInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#a64cb0c5ab10b63f22110e1b0183a648f">simplifyICmpWithBinOp</a>.</p>

</div>
</div>

### valueDominatesPHI() {#af412caabe4d2526271b50f052f9d3aef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool valueDominatesPHI (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * P, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT)</td>
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

<p>Does the given value dominate the specified phi node?</p>

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a5c69311e8d44898dac36a155c3d8691d">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a308de6b87d4d431477642d086b268a7c">simplifyPHINode</a>, <a href="#a914ac5681f80badb866f2aee44fc509a">threadBinOpOverPHI</a> and <a href="#a1ec7a76fbddf5983969def6e47c0f177">threadCmpOverPHI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"instsimplify"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>

</div>
</div>

### HANDLE\_CAST\_INST {#ab17cd64831c782d0a73555e5b2bf4bc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_CAST_INST(num, opc, clas)&nbsp;&nbsp;&nbsp;case Instruction::opc:</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 7218 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
