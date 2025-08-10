---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-loopstrengthreduce-cpp-/lsrinstance
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LSRInstance` Class

<p>This class holds state for the main loop strength reduction logic. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{LoopStrengthReduce.cpp}::LSRInstance { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a393998e4f5d7b103ee0566b8c98bbd72">UseMapTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse/#a4a62881e0181b4f2dc498eff32edf764">LSRUse::SCEVUseKindPair</a>, size_t &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bcf42be7435217d79cd175d4e6993d7">LSRInstance</a> (Loop *L, IVUsers &amp;IU, ScalarEvolution &amp;SE, DominatorTree &amp;DT, LoopInfo &amp;LI, const TargetTransformInfo &amp;TTI, AssumptionCache &amp;AC, TargetLibraryInfo &amp;TLI, MemorySSAUpdater *MSSAU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93ebde9d4c2fe184724a11d3c1184124">getChanged</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weakvh">WeakVH</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34d7093fa45e90e82de2073b08157efc">getScalarEvolutionIVs</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af93b911868eadea967fc026ed208698d">print_factors_and_types</a> (raw_ostream &amp;OS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ed1067b1498e4790ce06d7b0fb995a3">print_fixups</a> (raw_ostream &amp;OS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d604d6453ff8ad118da3e2cadc04c66">print_uses</a> (raw_ostream &amp;OS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a154b34752235c9434c21cd366250100f">print</a> (raw_ostream &amp;OS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a890ca19e74514f1ec5cbb3e5cdd8d50b">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5b019b20b40da9d880b7b9643a42616">OptimizeShadowIV</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If IV is used in a int-to-float cast inside the loop then try to eliminate the cast operation. <a href="#ae5b019b20b40da9d880b7b9643a42616">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbb35ddbd139e02e3d95e279b42db16c">FindIVUserForCond</a> (ICmpInst *Cond, IVStrideUse *&amp;CondUse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If Cond has an operand that is an expression of an IV, set the IV user and stride information and return true, otherwise return false. <a href="#afbb35ddbd139e02e3d95e279b42db16c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32352d875d91e0c18e72f49a752d071d">OptimizeMax</a> (ICmpInst *Cond, IVStrideUse *&amp;CondUse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite the loop's terminating condition if it uses a max computation. <a href="#a32352d875d91e0c18e72f49a752d071d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accaaa0062865326525359f6a78eff0f5">OptimizeLoopTermCond</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change loop terminating condition to use the postinc iv when possible. <a href="#accaaa0062865326525359f6a78eff0f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a715514c1c4664f58ecf2858fc46ed933">ChainInstruction</a> (Instruction *UserInst, Instruction *IVOper, SmallVectorImpl&lt; ChainUsers &gt; &amp;ChainUsersVec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add this IV user to an existing chain or make it the head of a new chain. <a href="#a715514c1c4664f58ecf2858fc46ed933">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a407dd69b2e6c0c82bf076a5f9a98c182">FinalizeChain</a> (IVChain &amp;Chain)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a512df630a3117cda430197944ab8f07f">CollectChains</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populate the vector of Chains. <a href="#a512df630a3117cda430197944ab8f07f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac35652ffaf6855297da971358f94ee57">GenerateIVChain</a> (const IVChain &amp;Chain, SmallVectorImpl&lt; WeakTrackingVH &gt; &amp;DeadInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate an add or subtract for each <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/ivinc">IVInc</a> in a chain to materialize the IV user's operand from the previous IV user's operand. <a href="#ac35652ffaf6855297da971358f94ee57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f7b75292a5fe583873379329eb58cc4">CollectInterestingTypesAndFactors</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afddc8565244874a6ecacf717f7f10092">CollectFixupsAndInitialFormulae</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94935b404993387e7aec5cdfb1aef6d5">reconcileNewOffset</a> (LSRUse &amp;LU, Immediate NewOffset, bool HasBaseReg, LSRUse::KindType Kind, MemAccessTy AccessTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the given use can accommodate a fixup at the given offset and other details. <a href="#a94935b404993387e7aec5cdfb1aef6d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; size_t, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad09b134600550cfb3ef01cacea128998">getUse</a> (const SCEV *&amp;Expr, LSRUse::KindType Kind, MemAccessTy AccessTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> index and an offset value for a fixup which needs the given expression, with the given kind and optional access type. <a href="#ad09b134600550cfb3ef01cacea128998">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6277d3360ab51c8c32904a2ea3669630">DeleteUse</a> (LSRUse &amp;LU, size_t LUIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Delete the given use from the Uses list. <a href="#a6277d3360ab51c8c32904a2ea3669630">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff198519c6d210ba7103bdb7749489c1">FindUseWithSimilarFormula</a> (const Formula &amp;F, const LSRUse &amp;OrigLU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look for a use distinct from OrigLU which is has a formula that has the same registers as the given formula. <a href="#aff198519c6d210ba7103bdb7749489c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d8810f530e1664ce5e435c9e1c10a11">InsertInitialFormula</a> (const SCEV *S, LSRUse &amp;LU, size_t LUIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a formula for the given expression into the given use, separating out loop-variant portions from loop-invariant and loop-computable portions. <a href="#a8d8810f530e1664ce5e435c9e1c10a11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad456e3e06233ba42e26377d835cbd32c">InsertSupplementalFormula</a> (const SCEV *S, LSRUse &amp;LU, size_t LUIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a simple single-register formula for the given expression into the given use. <a href="#ad456e3e06233ba42e26377d835cbd32c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbf65bc4fdc59b76bb459e44a5dbced2">CountRegisters</a> (const Formula &amp;F, size_t LUIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Note which registers are used by the given formula, updating RegUses. <a href="#acbf65bc4fdc59b76bb459e44a5dbced2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3c384f80656b918926278569d3afa24">InsertFormula</a> (LSRUse &amp;LU, unsigned LUIdx, const Formula &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the given formula has not yet been inserted, add it to the list, and return true. <a href="#ae3c384f80656b918926278569d3afa24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fd0b9ace01391c74a0102f465e8ed59">CollectLoopInvariantFixupsAndFormulae</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check for other uses of loop-invariant values which we're tracking. <a href="#a3fd0b9ace01391c74a0102f465e8ed59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a131e86428d982f30a771fcef8036a594">GenerateReassociations</a> (LSRUse &amp;LU, unsigned LUIdx, Formula Base, unsigned Depth=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split out subexpressions from adds and the bases of addrecs. <a href="#a131e86428d982f30a771fcef8036a594">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af84182e8fe06102c0cc81bbaafc5807e">GenerateReassociationsImpl</a> (LSRUse &amp;LU, unsigned LUIdx, const Formula &amp;Base, unsigned Depth, size_t Idx, bool IsScaledReg=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function for LSRInstance::GenerateReassociations. <a href="#af84182e8fe06102c0cc81bbaafc5807e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f9af4d0f16eb5e093fa9f008dcfd503">GenerateCombinations</a> (LSRUse &amp;LU, unsigned LUIdx, Formula Base)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate a formula consisting of all of the loop-dominating registers added into a single register. <a href="#a4f9af4d0f16eb5e093fa9f008dcfd503">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ba5135d854d22334e82bebe878bc4f4">GenerateSymbolicOffsetsImpl</a> (LSRUse &amp;LU, unsigned LUIdx, const Formula &amp;Base, size_t Idx, bool IsScaledReg=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function for LSRInstance::GenerateSymbolicOffsets. <a href="#a8ba5135d854d22334e82bebe878bc4f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26e4f1f4f86f4eaa6186570b28c625df">GenerateSymbolicOffsets</a> (LSRUse &amp;LU, unsigned LUIdx, Formula Base)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate reuse formulae using symbolic offsets. <a href="#a26e4f1f4f86f4eaa6186570b28c625df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3aec691599b58e7f5c51a5b5f52fd38">GenerateConstantOffsetsImpl</a> (LSRUse &amp;LU, unsigned LUIdx, const Formula &amp;Base, const SmallVectorImpl&lt; Immediate &gt; &amp;Worklist, size_t Idx, bool IsScaledReg=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function for LSRInstance::GenerateConstantOffsets. <a href="#ac3aec691599b58e7f5c51a5b5f52fd38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1c61ef74e884a870cf98fd79abdb1ef">GenerateConstantOffsets</a> (LSRUse &amp;LU, unsigned LUIdx, Formula Base)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GenerateConstantOffsets - Generate reuse formulae using symbolic offsets. <a href="#aa1c61ef74e884a870cf98fd79abdb1ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a099e39f2e93fc1a5ce139f9a54cdf8fb">GenerateICmpZeroScales</a> (LSRUse &amp;LU, unsigned LUIdx, Formula Base)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For ICmpZero, check to see if we can scale up the comparison. <a href="#a099e39f2e93fc1a5ce139f9a54cdf8fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8349baf5c3354477ba45c360896ffdaa">GenerateScales</a> (LSRUse &amp;LU, unsigned LUIdx, Formula Base)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate stride factor reuse formulae by making use of scaled-offset address modes, for example. <a href="#a8349baf5c3354477ba45c360896ffdaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae59c3c503720d1c5ed502655c7543617">GenerateTruncates</a> (LSRUse &amp;LU, unsigned LUIdx, Formula Base)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate reuse formulae from different IV types. <a href="#ae59c3c503720d1c5ed502655c7543617">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a593ae190c9aaffceef97b5bc9a5f0b8b">GenerateCrossUseConstantOffsets</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look for registers which are a constant distance apart and try to form reuse opportunities between them. <a href="#a593ae190c9aaffceef97b5bc9a5f0b8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bf7bfbd64324ea1cb1050bb5c89d649">GenerateAllReuseFormulae</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate formulae for each use. <a href="#a8bf7bfbd64324ea1cb1050bb5c89d649">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91a58e38ab4f3d5a32a55a39b6840efa">FilterOutUndesirableDedicatedRegisters</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If there are multiple formulae with the same set of registers used by other uses, pick the best one and delete the others. <a href="#a91a58e38ab4f3d5a32a55a39b6840efa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0000279470b1c2bb09a950398a66e54c">EstimateSearchSpaceComplexity</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Estimate the worst-case number of solutions the solver might have to consider. <a href="#a0000279470b1c2bb09a950398a66e54c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bfd40d657b0d602db076d1e74b36ac3">NarrowSearchSpaceByDetectingSupersets</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When one formula uses a superset of the registers of another formula, it won't help reduce register pressure (though it may not necessarily hurt register pressure); remove it to simplify the system. <a href="#a9bfd40d657b0d602db076d1e74b36ac3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaac954dc35f3f3dc5734d74729d4b59">NarrowSearchSpaceByCollapsingUnrolledCode</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When there are many registers for expressions like A, A+1, A+2, etc., allocate a single register for them. <a href="#abaac954dc35f3f3dc5734d74729d4b59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfdece554ed27edf399f99cf8b7decde">NarrowSearchSpaceByRefilteringUndesirableDedicatedRegisters</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call FilterOutUndesirableDedicatedRegisters again, if necessary, now that we've done more filtering, as it may be able to find more formulae to eliminate. <a href="#abfdece554ed27edf399f99cf8b7decde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4b1d4c4c64612023ec04a6ab797947f">NarrowSearchSpaceByFilterFormulaWithSameScaledReg</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> has multiple formulae with the same ScaledReg and Scale. <a href="#ae4b1d4c4c64612023ec04a6ab797947f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97ecf0b652ef46c7bede7441b512b175">NarrowSearchSpaceByFilterPostInc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we are over the complexity limit, filter out any post-inc prefering variables to only post-inc values. <a href="#a97ecf0b652ef46c7bede7441b512b175">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5021dc188b1f29105cbb965468502514">NarrowSearchSpaceByDeletingCostlyFormulas</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The function delete formulas with high registers number expectation. <a href="#a5021dc188b1f29105cbb965468502514">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad10fa4f61542c7d3f2b075d6631973db">NarrowSearchSpaceByPickingWinnerRegs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pick a register which seems likely to be profitable, and then in any use which has any reference to that register, delete all formulae which do not reference that register. <a href="#ad10fa4f61542c7d3f2b075d6631973db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8957c043357b655f3091a9c093e2652b">NarrowSearchSpaceUsingHeuristics</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If there are an extraordinary number of formulae to choose from, use some rough heuristics to prune down the number of formulae. <a href="#a8957c043357b655f3091a9c093e2652b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad48e169c4317e14b093e535f1db7c5e4">SolveRecurse</a> (SmallVectorImpl&lt; const Formula * &gt; &amp;Solution, Cost &amp;SolutionCost, SmallVectorImpl&lt; const Formula * &gt; &amp;Workspace, const Cost &amp;CurCost, const SmallPtrSet&lt; const SCEV *, 16 &gt; &amp;CurRegs, DenseSet&lt; const SCEV * &gt; &amp;VisitedRegs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the recursive solver. <a href="#ad48e169c4317e14b093e535f1db7c5e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b08cb248b1984ff1dae6899aa886a4e">Solve</a> (SmallVectorImpl&lt; const Formula * &gt; &amp;Solution) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Choose one formula from each use. <a href="#a5b08cb248b1984ff1dae6899aa886a4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adddf31c945c77716f8a1e0740c0a525a">HoistInsertPosition</a> (BasicBlock::iterator IP, const SmallVectorImpl&lt; Instruction * &gt; &amp;Inputs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for AdjustInsertPositionForExpand. <a href="#adddf31c945c77716f8a1e0740c0a525a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa318f5ed9147988ef7af4dd86b85d6ba">AdjustInsertPositionForExpand</a> (BasicBlock::iterator IP, const LSRFixup &amp;LF, const LSRUse &amp;LU) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine an input position which will be dominated by the operands and which will dominate the result. <a href="#aa318f5ed9147988ef7af4dd86b85d6ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7841bf80789049777d6e3e90bbd4b0db">Expand</a> (const LSRUse &amp;LU, const LSRFixup &amp;LF, const Formula &amp;F, BasicBlock::iterator IP, SmallVectorImpl&lt; WeakTrackingVH &gt; &amp;DeadInsts) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit instructions for the leading candidate expression for this <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> (this is called "expanding"). <a href="#a7841bf80789049777d6e3e90bbd4b0db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26330898baea53c04152823be7652aa9">RewriteForPHI</a> (PHINode *PN, const LSRUse &amp;LU, const LSRFixup &amp;LF, const Formula &amp;F, SmallVectorImpl&lt; WeakTrackingVH &gt; &amp;DeadInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for Rewrite. <a href="#a26330898baea53c04152823be7652aa9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12abc9d7a83f261e6f12535cc9b94588">Rewrite</a> (const LSRUse &amp;LU, const LSRFixup &amp;LF, const Formula &amp;F, SmallVectorImpl&lt; WeakTrackingVH &gt; &amp;DeadInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit instructions for the leading candidate expression for this <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> (this is called "expanding"), and update the UserInst to reference the newly expanded value. <a href="#a12abc9d7a83f261e6f12535cc9b94588">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4453cb4bffc0cbc29cb9f31f4f9083f8">ImplementSolution</a> (const SmallVectorImpl&lt; const Formula * &gt; &amp;Solution)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite all the fixup locations with new values, following the chosen solution. <a href="#a4453cb4bffc0cbc29cb9f31f4f9083f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ivusers">IVUsers</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43374274406d3d89701c862c95324932">IU</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75d0eecd5dcdbebc60559c49484263b4">SE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56bd333fe5572f557f3d3ca5632acf94">DT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97382d1d7a63180310d70172064215d9">LI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac46d97825effef6f5543742a094865a">AC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8727f18583c0369429fae4badd0cb76f">TLI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e1752a3672e005bebad0b4fa21c80d1">TTI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac50dbb6771a787a7f4469fb12d6a0b6b">L</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a321e2f21f3b9fc968baf2f8a93dffe80">MSSAU</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ad88649498463e1fe02380ad98886ce43">TTI::AddressingModeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb6190119088b7c7a92a909bb6428187">AMK</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f350a9d8ea17d7abce0edc235bb888a">Rewriter</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff619f77b08c608f1727c88e802b49e8">Changed</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e321389f3c9cc55787b5b0b34d5f60e">IVIncInsertPos</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the insert position that the current loop's induction variable increment should be placed. <a href="#a0e321389f3c9cc55787b5b0b34d5f60e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; int64_t, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int64_t, 8 &gt;, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; int64_t, 8 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a486ffa7182e7f0cdb85dc8030c19d4d0">Factors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interesting factors between use strides. <a href="#a486ffa7182e7f0cdb85dc8030c19d4d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/cost">Cost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7190d2744d2cff4851540183528393c">BaselineCost</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost of the current <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>, the best solution by LSR will be dropped if the solution is not profitable. <a href="#ac7190d2744d2cff4851540183528393c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdeb6377ff95fc86ef01f0bd7e41c65a">Types</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interesting use types, to facilitate truncation reuse. <a href="#acdeb6377ff95fc86ef01f0bd7e41c65a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a>, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab12767d7dcdf10ee7cf60f2468f3daad">Uses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list of interesting uses. <a href="#ab12767d7dcdf10ee7cf60f2468f3daad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/regusetracker">RegUseTracker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ab18d8bb0759fe83f7d5efb6d0ac046">RegUses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Track which uses use which register candidates. <a href="#a6ab18d8bb0759fe83f7d5efb6d0ac046">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/ivchain">IVChain</a>, MaxChains &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3cfb6ab9a4ed4669134aab058930e74">IVChainVec</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IV users can form a chain of IV increments. <a href="#ae3cfb6ab9a4ed4669134aab058930e74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *, MaxChains &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae340fc3e385bf9386c2b74615d163ac9">IVIncSet</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IV users that belong to profitable IVChains. <a href="#ae340fc3e385bf9386c2b74615d163ac9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weakvh">llvm::WeakVH</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72e78c2942bf7e8348624c615d080871">ScalarEvolutionIVs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Induction variables that were generated and inserted by the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> Expander. <a href="#a72e78c2942bf7e8348624c615d080871">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af74aac279158f04fb154b5363329815d">InsertedNonLCSSAInsts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">UseMapTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2bc35d39d375eefad685b9526d1e6ec">UseMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adea7d2cd98babadcd59137cb46b66af8">MaxChains</a> = 8</td>
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

## Description {#details}

<p>This class holds state for the main loop strength reduction logic.</p>

<p>Definition at line 2136 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### UseMapTy {#a393998e4f5d7b103ee0566b8c98bbd72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{LoopStrengthReduce.cpp}::LSRInstance::UseMapTy =  DenseMap&lt;LSRUse::SCEVUseKindPair, size_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2213 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LSRInstance() {#a9bcf42be7435217d79cd175d4e6993d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LSRInstance::LSRInstance (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/ivusers">IVUsers</a> &amp; IU, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2293 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a14cf6d7a36d091cb666cb83221b81d72">llvm::PHINode::blocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a2e520a15f4578a464f9caaac2f4758ae">isLegalUse</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a73b3c5e7c72bf97886e2ed1f12e28d54">MaxIVUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a5ecada6efd95584778cb27661747d9ba">PreferredAddresingMode</a>, <a href="#a0d604d6453ff8ad118da3e2cadc04c66">print_uses</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a3dbd582073ac67026ef5be72da94d4a3">StressIVChain</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a890ca19e74514f1ec5cbb3e5cdd8d50b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void LSRInstance::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2306 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a154b34752235c9434c21cd366250100f">print</a>.</p>

</div>
</div>

### getChanged() {#a93ebde9d4c2fe184724a11d3c1184124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopStrengthReduce.cpp}::LSRInstance::getChanged ()</td>
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



<p>Definition at line 2297 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### getScalarEvolutionIVs() {#a34d7093fa45e90e82de2073b08157efc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; WeakVH &gt; &amp; anonymous{LoopStrengthReduce.cpp}::LSRInstance::getScalarEvolutionIVs ()</td>
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



<p>Definition at line 2298 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### print() {#a154b34752235c9434c21cd366250100f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2305 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="#af93b911868eadea967fc026ed208698d">print_factors_and_types</a>, <a href="#a1ed1067b1498e4790ce06d7b0fb995a3">print_fixups</a> and <a href="#a0d604d6453ff8ad118da3e2cadc04c66">print_uses</a>.</p>


<p>Referenced by <a href="#a890ca19e74514f1ec5cbb3e5cdd8d50b">dump</a>.</p>

</div>
</div>

### print\_factors\_and\_types() {#af93b911868eadea967fc026ed208698d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::print_factors_and_types (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2302 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>.</p>


<p>Referenced by <a href="#a154b34752235c9434c21cd366250100f">print</a>.</p>

</div>
</div>

### print\_fixups() {#a1ed1067b1498e4790ce06d7b0fb995a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::print_fixups (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2303 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/lsrfixup/#aa7f24a759cb17285abd90cfa12e030c1">anonymous{LoopStrengthReduce.cpp}::LSRFixup::print</a>.</p>


<p>Referenced by <a href="#a154b34752235c9434c21cd366250100f">print</a>.</p>

</div>
</div>

### print\_uses() {#a0d604d6453ff8ad118da3e2cadc04c66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::print_uses (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2304 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a9bcf42be7435217d79cd175d4e6993d7">LSRInstance</a> and <a href="#a154b34752235c9434c21cd366250100f">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AdjustInsertPositionForExpand() {#aa318f5ed9147988ef7af4dd86b85d6ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock::iterator LSRInstance::AdjustInsertPositionForExpand (<a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> IP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/lsrfixup">LSRFixup</a> &amp; LF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; LU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine an input position which will be dominated by the operands and which will dominate the result.</p>

<p>Definition at line 2278 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### ChainInstruction() {#a715514c1c4664f58ecf2858fc46ed933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::ChainInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * UserInst, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IVOper, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/chainusers">ChainUsers</a> &gt; &amp; ChainUsersVec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add this IV user to an existing chain or make it the head of a new chain.</p>

<p>Definition at line 2202 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### CollectChains() {#a512df630a3117cda430197944ab8f07f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::CollectChains ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Populate the vector of Chains.</p>


<p>This decreases ILP at the architecture level. Targets with ample registers, multiple memory ports, and no register renaming probably don't want this. However, such targets should probably disable LSR altogether.</p>


<p>The job of LSR is to make a reasonable choice of induction variables across the loop. Subsequent passes can easily "unchain" computation exposing more ILP <em>within the loop</em> if the target wants it.</p>


<p>Finding the best IV chain is potentially a scheduling problem. Since LSR will not reorder memory operations, it will recognize this as a chain, but will generate redundant IV increments. Ideally this would be corrected later by a smart scheduler: = A[i] = A[i+x] A[i] = A[i+x] =</p>


<p>TODO: Walk the entire domtree within this loop, not just the path to the loop latch. This will discover chains on side paths, but requires maintaining multiple copies of the Chains state.</p>


<p>Definition at line 2205 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### CollectFixupsAndInitialFormulae() {#afddc8565244874a6ecacf717f7f10092}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::CollectFixupsAndInitialFormulae ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2210 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### CollectInterestingTypesAndFactors() {#a0f7b75292a5fe583873379329eb58cc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::CollectInterestingTypesAndFactors ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2209 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### CollectLoopInvariantFixupsAndFormulae() {#a3fd0b9ace01391c74a0102f465e8ed59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::CollectLoopInvariantFixupsAndFormulae ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check for other uses of loop-invariant values which we're tracking.</p>


<p>These other uses will pin these values in registers, making them less profitable for elimination. TODO: This currently misses non-constant addrec step registers. TODO: Should this give more weight to users inside the loop?</p>


<p>Definition at line 2231 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### CountRegisters() {#acbf65bc4fdc59b76bb459e44a5dbced2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::CountRegisters (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> &amp; F, size_t LUIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Note which registers are used by the given formula, updating RegUses.</p>

<p>Definition at line 2228 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### DeleteUse() {#a6277d3360ab51c8c32904a2ea3669630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::DeleteUse (<a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; LU, size_t LUIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Delete the given use from the Uses list.</p>

<p>Definition at line 2222 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### EstimateSearchSpaceComplexity() {#a0000279470b1c2bb09a950398a66e54c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t LSRInstance::EstimateSearchSpaceComplexity ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Estimate the worst-case number of solutions the solver might have to consider.</p>


<p>It almost never considers this many solutions because it prune the search space, but the pruning isn't always sufficient.</p>


<p>Definition at line 2257 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### Expand() {#a7841bf80789049777d6e3e90bbd4b0db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * LSRInstance::Expand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; LU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/lsrfixup">LSRFixup</a> &amp; LF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> IP, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> &gt; &amp; DeadInsts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit instructions for the leading candidate expression for this <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> (this is called "expanding").</p>

<p>Definition at line 2282 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### FilterOutUndesirableDedicatedRegisters() {#a91a58e38ab4f3d5a32a55a39b6840efa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::FilterOutUndesirableDedicatedRegisters ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If there are multiple formulae with the same set of registers used by other uses, pick the best one and delete the others.</p>

<p>Definition at line 2255 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### FinalizeChain() {#a407dd69b2e6c0c82bf076a5f9a98c182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::FinalizeChain (<a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/ivchain">IVChain</a> &amp; Chain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2204 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### FindIVUserForCond() {#afbb35ddbd139e02e3d95e279b42db16c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LSRInstance::FindIVUserForCond (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Cond, <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a> *&amp; CondUse)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If Cond has an operand that is an expression of an IV, set the IV user and stride information and return true, otherwise return false.</p>

<p>Definition at line 2198 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### FindUseWithSimilarFormula() {#aff198519c6d210ba7103bdb7749489c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LSRUse * LSRInstance::FindUseWithSimilarFormula (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; OrigLU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look for a use distinct from OrigLU which is has a formula that has the same registers as the given formula.</p>

<p>Definition at line 2224 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### GenerateAllReuseFormulae() {#a8bf7bfbd64324ea1cb1050bb5c89d649}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::GenerateAllReuseFormulae ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate formulae for each use.</p>

<p>Definition at line 2253 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### GenerateCombinations() {#a4f9af4d0f16eb5e093fa9f008dcfd503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::GenerateCombinations (<a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; LU, unsigned LUIdx, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> Base)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate a formula consisting of all of the loop-dominating registers added into a single register.</p>

<p>Definition at line 2239 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### GenerateConstantOffsets() {#aa1c61ef74e884a870cf98fd79abdb1ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::GenerateConstantOffsets (<a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; LU, unsigned LUIdx, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> Base)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GenerateConstantOffsets - Generate reuse formulae using symbolic offsets.</p>

<p>Definition at line 2248 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### GenerateConstantOffsetsImpl() {#ac3aec691599b58e7f5c51a5b5f52fd38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::GenerateConstantOffsetsImpl (<a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; LU, unsigned LUIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> &amp; Base, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a> &gt; &amp; Worklist, size_t Idx, bool IsScaledReg=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function for LSRInstance::GenerateConstantOffsets.</p>

<p>Definition at line 2244 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### GenerateCrossUseConstantOffsets() {#a593ae190c9aaffceef97b5bc9a5f0b8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::GenerateCrossUseConstantOffsets ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look for registers which are a constant distance apart and try to form reuse opportunities between them.</p>

<p>Definition at line 2252 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### GenerateICmpZeroScales() {#a099e39f2e93fc1a5ce139f9a54cdf8fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::GenerateICmpZeroScales (<a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; LU, unsigned LUIdx, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> Base)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For ICmpZero, check to see if we can scale up the comparison.</p>


<p>For example, x == y -&gt; x*c == y*c.</p>


<p>Definition at line 2249 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### GenerateIVChain() {#ac35652ffaf6855297da971358f94ee57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::GenerateIVChain (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/ivchain">IVChain</a> &amp; Chain, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> &gt; &amp; DeadInsts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate an add or subtract for each <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/ivinc">IVInc</a> in a chain to materialize the IV user's operand from the previous IV user's operand.</p>

<p>Definition at line 2206 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### GenerateReassociations() {#a131e86428d982f30a771fcef8036a594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::GenerateReassociations (<a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; LU, unsigned LUIdx, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> Base, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Split out subexpressions from adds and the bases of addrecs.</p>

<p>Definition at line 2233 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### GenerateReassociationsImpl() {#af84182e8fe06102c0cc81bbaafc5807e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::GenerateReassociationsImpl (<a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; LU, unsigned LUIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> &amp; Base, unsigned Depth, size_t Idx, bool IsScaledReg=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function for LSRInstance::GenerateReassociations.</p>

<p>Definition at line 2236 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### GenerateScales() {#a8349baf5c3354477ba45c360896ffdaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::GenerateScales (<a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; LU, unsigned LUIdx, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> Base)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate stride factor reuse formulae by making use of scaled-offset address modes, for example.</p>

<p>Definition at line 2250 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### GenerateSymbolicOffsets() {#a26e4f1f4f86f4eaa6186570b28c625df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::GenerateSymbolicOffsets (<a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; LU, unsigned LUIdx, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> Base)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate reuse formulae using symbolic offsets.</p>

<p>Definition at line 2243 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### GenerateSymbolicOffsetsImpl() {#a8ba5135d854d22334e82bebe878bc4f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::GenerateSymbolicOffsetsImpl (<a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; LU, unsigned LUIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> &amp; Base, size_t Idx, bool IsScaledReg=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function for LSRInstance::GenerateSymbolicOffsets.</p>

<p>Definition at line 2240 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### GenerateTruncates() {#ae59c3c503720d1c5ed502655c7543617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::GenerateTruncates (<a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; LU, unsigned LUIdx, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> Base)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate reuse formulae from different IV types.</p>

<p>Definition at line 2251 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### getUse() {#ad09b134600550cfb3ef01cacea128998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; size_t, Immediate &gt; LSRInstance::getUse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; Expr, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse/#a1ba9c6c01c92aafaeb2986bdd756dcf0">LSRUse::KindType</a> Kind, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/memaccessty">MemAccessTy</a> AccessTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> index and an offset value for a fixup which needs the given expression, with the given kind and optional access type.</p>


<p>Either reuse an existing use or create a new one, as needed.</p>


<p>Definition at line 2219 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### HoistInsertPosition() {#adddf31c945c77716f8a1e0740c0a525a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock::iterator LSRInstance::HoistInsertPosition (<a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> IP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; Inputs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper for AdjustInsertPositionForExpand.</p>


<p>Climb up the dominator tree far as we can go while still being dominated by the input positions. This helps canonicalize the insert position, which encourages sharing.</p>


<p>Definition at line 2276 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### ImplementSolution() {#a4453cb4bffc0cbc29cb9f31f4f9083f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::ImplementSolution (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> * &gt; &amp; Solution)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rewrite all the fixup locations with new values, following the chosen solution.</p>

<p>Definition at line 2290 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### InsertFormula() {#ae3c384f80656b918926278569d3afa24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LSRInstance::InsertFormula (<a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; LU, unsigned LUIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the given formula has not yet been inserted, add it to the list, and return true.</p>


<p>Return false otherwise.</p>


<p>Definition at line 2229 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### InsertInitialFormula() {#a8d8810f530e1664ce5e435c9e1c10a11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::InsertInitialFormula (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; LU, size_t LUIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a formula for the given expression into the given use, separating out loop-variant portions from loop-invariant and loop-computable portions.</p>

<p>Definition at line 2226 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### InsertSupplementalFormula() {#ad456e3e06233ba42e26377d835cbd32c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::InsertSupplementalFormula (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; LU, size_t LUIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a simple single-register formula for the given expression into the given use.</p>

<p>Definition at line 2227 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### NarrowSearchSpaceByCollapsingUnrolledCode() {#abaac954dc35f3f3dc5734d74729d4b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::NarrowSearchSpaceByCollapsingUnrolledCode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When there are many registers for expressions like A, A+1, A+2, etc., allocate a single register for them.</p>

<p>Definition at line 2259 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### NarrowSearchSpaceByDeletingCostlyFormulas() {#a5021dc188b1f29105cbb965468502514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::NarrowSearchSpaceByDeletingCostlyFormulas ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The function delete formulas with high registers number expectation.</p>


<p>Assuming we don't know the value of each formula (already delete all inefficient), generate probability of not selecting for each register. For example, Use1: reg(a) + reg({0,+,1}) reg(a) + reg({-1,+,1}) + 1 reg({a,+,1}) Use2: reg(b) + reg({0,+,1}) reg(b) + reg({-1,+,1}) + 1 reg({b,+,1}) Use3: reg(c) + reg(b) + reg({0,+,1}) reg(c) + reg({b,+,1})</p>


<p>Probability of not selecting Use1 Use2 Use3 reg(a) (1/3) * 1 * 1 reg(b) 1 * (1/3) * (1/2) reg({0,+,1}) (2/3) * (2/3) * (1/2) reg({-1,+,1}) (2/3) * (2/3) * 1 reg({a,+,1}) (2/3) * 1 * 1 reg({b,+,1}) 1 * (2/3) * (2/3) reg(c) 1 * 1 * 0</p>


<p>Now count registers number mathematical expectation for each formula: Note that for each use we exclude probability if not selecting for the use. For example for Use1 probability for reg(a) would be just 1 * 1 (excluding probabilty 1/3 of not selecting for Use1). Use1: reg(a) + reg({0,+,1}) 1 + 1/3 – to be deleted reg(a) + reg({-1,+,1}) + 1 1 + 4/9 – to be deleted reg({a,+,1}) 1 Use2: reg(b) + reg({0,+,1}) 1/2 + 1/3 – to be deleted reg(b) + reg({-1,+,1}) + 1 1/2 + 2/3 – to be deleted reg({b,+,1}) 2/3 Use3: reg(c) + reg(b) + reg({0,+,1}) 1 + 1/3 + 4/9 – to be deleted reg(c) + reg({b,+,1}) 1 + 2/3</p>


<p>Definition at line 2263 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### NarrowSearchSpaceByDetectingSupersets() {#a9bfd40d657b0d602db076d1e74b36ac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::NarrowSearchSpaceByDetectingSupersets ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When one formula uses a superset of the registers of another formula, it won't help reduce register pressure (though it may not necessarily hurt register pressure); remove it to simplify the system.</p>

<p>Definition at line 2258 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### NarrowSearchSpaceByFilterFormulaWithSameScaledReg() {#ae4b1d4c4c64612023ec04a6ab797947f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::NarrowSearchSpaceByFilterFormulaWithSameScaledReg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If a <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> has multiple formulae with the same ScaledReg and Scale.</p>


<p>Pick the best one and delete the others. This narrowing heuristic is to keep as many formulae with different Scale and ScaledReg pair as possible while narrowing the search space. The benefit is that it is more likely to find out a better solution from a formulae set with more Scale and ScaledReg variations than a formulae set with the same Scale and ScaledReg. The picking winner reg heuristic will often keep the formulae with the same Scale and ScaledReg and filter others, and we want to avoid that if possible.</p>


<p>Definition at line 2261 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### NarrowSearchSpaceByFilterPostInc() {#a97ecf0b652ef46c7bede7441b512b175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::NarrowSearchSpaceByFilterPostInc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If we are over the complexity limit, filter out any post-inc prefering variables to only post-inc values.</p>

<p>Definition at line 2262 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### NarrowSearchSpaceByPickingWinnerRegs() {#ad10fa4f61542c7d3f2b075d6631973db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::NarrowSearchSpaceByPickingWinnerRegs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pick a register which seems likely to be profitable, and then in any use which has any reference to that register, delete all formulae which do not reference that register.</p>

<p>Definition at line 2264 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### NarrowSearchSpaceByRefilteringUndesirableDedicatedRegisters() {#abfdece554ed27edf399f99cf8b7decde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::NarrowSearchSpaceByRefilteringUndesirableDedicatedRegisters ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Call FilterOutUndesirableDedicatedRegisters again, if necessary, now that we've done more filtering, as it may be able to find more formulae to eliminate.</p>

<p>Definition at line 2260 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### NarrowSearchSpaceUsingHeuristics() {#a8957c043357b655f3091a9c093e2652b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::NarrowSearchSpaceUsingHeuristics ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If there are an extraordinary number of formulae to choose from, use some rough heuristics to prune down the number of formulae.</p>


<p>This keeps the main solver from taking an extraordinary amount of time in some worst-case scenarios.</p>


<p>Definition at line 2265 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### OptimizeLoopTermCond() {#accaaa0062865326525359f6a78eff0f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::OptimizeLoopTermCond ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Change loop terminating condition to use the postinc iv when possible.</p>

<p>Definition at line 2200 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### OptimizeMax() {#a32352d875d91e0c18e72f49a752d071d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ICmpInst * LSRInstance::OptimizeMax (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Cond, <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a> *&amp; CondUse)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rewrite the loop's terminating condition if it uses a max computation.</p>


<p>This is a narrow solution to a specific, but acute, problem. For loops like this:</p>


<p>i = 0; do { p[i] = 0.0; } while (++i &lt; n);</p>


<p>the trip count isn't just 'n', because 'n' might not be positive. And unfortunately this can come up even for loops where the user didn't use a C do-while loop. For example, seemingly well-behaved top-test loops will commonly be lowered like this:</p>


<p>if (n &gt; 0) { i = 0; do { p[i] = 0.0; } while (++i &lt; n); }</p>


<p>and then it's possible for subsequent optimization to obscure the if test in such a way that indvars can't find it.</p>


<p>When indvars can't find the if test in loops like this, it creates a max expression, which allows it to give the loop a canonical induction variable:</p>


<p>i = 0; max = n &lt; 1 ? 1 : n; do { p[i] = 0.0; } while (++i != max);</p>


<p>Canonical induction variables are necessary because the loop passes are designed around them. The most obvious example of this is the <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> analysis, which doesn't remember trip count values. It expects to be able to rediscover the trip count each time it is needed, and it does this using a simple analysis that only succeeds if the loop has a canonical induction variable.</p>


<p>However, when it comes time to generate code, the maximum operation can be quite costly, especially if it's inside of an outer loop.</p>


<p>This function solves this problem by detecting this type of loop and rewriting their conditions from ICMP_NE back to ICMP_SLT, and deleting the instructions for the maximum computation.</p>


<p>Definition at line 2199 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### OptimizeShadowIV() {#ae5b019b20b40da9d880b7b9643a42616}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::OptimizeShadowIV ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If IV is used in a int-to-float cast inside the loop then try to eliminate the cast operation.</p>

<p>Definition at line 2197 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### reconcileNewOffset() {#a94935b404993387e7aec5cdfb1aef6d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LSRInstance::reconcileNewOffset (<a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; LU, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a> NewOffset, bool HasBaseReg, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse/#a1ba9c6c01c92aafaeb2986bdd756dcf0">LSRUse::KindType</a> Kind, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/memaccessty">MemAccessTy</a> AccessTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the given use can accommodate a fixup at the given offset and other details.</p>


<p>If so, update the use and return true.</p>


<p>Definition at line 2216 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### Rewrite() {#a12abc9d7a83f261e6f12535cc9b94588}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::Rewrite (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; LU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/lsrfixup">LSRFixup</a> &amp; LF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> &gt; &amp; DeadInsts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit instructions for the leading candidate expression for this <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> (this is called "expanding"), and update the UserInst to reference the newly expanded value.</p>

<p>Definition at line 2288 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### RewriteForPHI() {#a26330898baea53c04152823be7652aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::RewriteForPHI (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> &amp; LU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/lsrfixup">LSRFixup</a> &amp; LF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> &gt; &amp; DeadInsts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper for Rewrite.</p>


<p>PHI nodes are special because the use of their operands effectively happens in their predecessor blocks, so the expression may need to be expanded in multiple places.</p>


<p>Definition at line 2285 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### Solve() {#a5b08cb248b1984ff1dae6899aa886a4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::Solve (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> * &gt; &amp; Solution)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Choose one formula from each use.</p>


<p>Return the results in the given Solution vector.</p>


<p>Definition at line 2273 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### SolveRecurse() {#ad48e169c4317e14b093e535f1db7c5e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRInstance::SolveRecurse (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> * &gt; &amp; Solution, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/cost">Cost</a> &amp; SolutionCost, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> * &gt; &amp; Workspace, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/cost">Cost</a> &amp; CurCost, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, 16 &gt; &amp; CurRegs, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; VisitedRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the recursive solver.</p>

<p>Definition at line 2267 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AC {#aac46d97825effef6f5543742a094865a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache&amp; anonymous{LoopStrengthReduce.cpp}::LSRInstance::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2141 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### AMK {#acb6190119088b7c7a92a909bb6428187}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TTI::AddressingModeKind anonymous{LoopStrengthReduce.cpp}::LSRInstance::AMK</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2146 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### BaselineCost {#ac7190d2744d2cff4851540183528393c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cost anonymous{LoopStrengthReduce.cpp}::LSRInstance::BaselineCost</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost of the current <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>, the best solution by LSR will be dropped if the solution is not profitable.</p>

<p>Definition at line 2166 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### Changed {#aff619f77b08c608f1727c88e802b49e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopStrengthReduce.cpp}::LSRInstance::Changed = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2148 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### DT {#a56bd333fe5572f557f3d3ca5632acf94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree&amp; anonymous{LoopStrengthReduce.cpp}::LSRInstance::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2139 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### Factors {#a486ffa7182e7f0cdb85dc8030c19d4d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt;int64_t, SmallVector&lt;int64_t, 8&gt;, SmallSet&lt;int64_t, 8&gt; &gt; anonymous{LoopStrengthReduce.cpp}::LSRInstance::Factors</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Interesting factors between use strides.</p>


<p>We explicitly use a <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a> which contains a <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>, instead of the default, a <a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>, because we need to use the full range of int64_ts, and there's currently no good way of doing that with <a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>.</p>


<p>Definition at line 2162 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### InsertedNonLCSSAInsts {#af74aac279158f04fb154b5363329815d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetVector&lt;Instruction *, 4&gt; anonymous{LoopStrengthReduce.cpp}::LSRInstance::InsertedNonLCSSAInsts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2195 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### IU {#a43374274406d3d89701c862c95324932}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IVUsers&amp; anonymous{LoopStrengthReduce.cpp}::LSRInstance::IU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2137 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### IVChainVec {#ae3cfb6ab9a4ed4669134aab058930e74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;IVChain, MaxChains&gt; anonymous{LoopStrengthReduce.cpp}::LSRInstance::IVChainVec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IV users can form a chain of IV increments.</p>

<p>Definition at line 2183 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### IVIncInsertPos {#a0e321389f3c9cc55787b5b0b34d5f60e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{LoopStrengthReduce.cpp}::LSRInstance::IVIncInsertPos = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the insert position that the current loop's induction variable increment should be placed.</p>


<p>In simple loops, this is the latch block's terminator. But in more complicated cases, this is a position which will dominate all the in-loop post-increment users.</p>


<p>Definition at line 2154 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### IVIncSet {#ae340fc3e385bf9386c2b74615d163ac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Use*, MaxChains&gt; anonymous{LoopStrengthReduce.cpp}::LSRInstance::IVIncSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IV users that belong to profitable IVChains.</p>

<p>Definition at line 2186 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### L {#ac50dbb6771a787a7f4469fb12d6a0b6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* const anonymous{LoopStrengthReduce.cpp}::LSRInstance::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2144 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### LI {#a97382d1d7a63180310d70172064215d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo&amp; anonymous{LoopStrengthReduce.cpp}::LSRInstance::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2140 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### MSSAU {#a321e2f21f3b9fc968baf2f8a93dffe80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSAUpdater* anonymous{LoopStrengthReduce.cpp}::LSRInstance::MSSAU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2145 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### RegUses {#a6ab18d8bb0759fe83f7d5efb6d0ac046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegUseTracker anonymous{LoopStrengthReduce.cpp}::LSRInstance::RegUses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Track which uses use which register candidates.</p>

<p>Definition at line 2175 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### Rewriter {#a7f350a9d8ea17d7abce0edc235bb888a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEVExpander anonymous{LoopStrengthReduce.cpp}::LSRInstance::Rewriter</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2147 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### ScalarEvolutionIVs {#a72e78c2942bf7e8348624c615d080871}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;llvm::WeakVH, 2&gt; anonymous{LoopStrengthReduce.cpp}::LSRInstance::ScalarEvolutionIVs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Induction variables that were generated and inserted by the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> Expander.</p>

<p>Definition at line 2189 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### SE {#a75d0eecd5dcdbebc60559c49484263b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution&amp; anonymous{LoopStrengthReduce.cpp}::LSRInstance::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2138 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### TLI {#a8727f18583c0369429fae4badd0cb76f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfo&amp; anonymous{LoopStrengthReduce.cpp}::LSRInstance::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2142 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### TTI {#a0e1752a3672e005bebad0b4fa21c80d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetTransformInfo&amp; anonymous{LoopStrengthReduce.cpp}::LSRInstance::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2143 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### Types {#acdeb6377ff95fc86ef01f0bd7e41c65a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetVector&lt;Type *, 4&gt; anonymous{LoopStrengthReduce.cpp}::LSRInstance::Types</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Interesting use types, to facilitate truncation reuse.</p>

<p>Definition at line 2169 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### UseMap {#aa2bc35d39d375eefad685b9526d1e6ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UseMapTy anonymous{LoopStrengthReduce.cpp}::LSRInstance::UseMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2214 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### Uses {#ab12767d7dcdf10ee7cf60f2468f3daad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;LSRUse, 16&gt; anonymous{LoopStrengthReduce.cpp}::LSRInstance::Uses</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The list of interesting uses.</p>

<p>Definition at line 2172 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### MaxChains {#adea7d2cd98babadcd59137cb46b66af8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{LoopStrengthReduce.cpp}::LSRInstance::MaxChains = 8</td>
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



<p>Definition at line 2180 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
