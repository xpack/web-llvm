---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/targettransforminfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TargetTransformInfo` Class

<p>This pass provides access to the codegen interfaces that are needed for IR-level transformations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::TargetTransformInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PartialReductionExtendKind { <a href="#abd1dc2b46b5e2311e1f64d21b2991be9">...</a> }</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#af1bf12b2f33b7e30f8f361a1e7642079">TargetTransformInfo</a> (T Impl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068">TTI</a> object using a type implementing the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/concept">Concept</a></span> API below. <a href="#af1bf12b2f33b7e30f8f361a1e7642079">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7b62dddca1c89d43af02d0e2ab06030">TargetTransformInfo</a> (const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a baseline <a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068">TTI</a> object using a minimal implementation of the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/concept">Concept</a></span> API below. <a href="#ac7b62dddca1c89d43af02d0e2ab06030">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab158463a734f57c86e685364527ebaa4">TargetTransformInfo</a> (TargetTransformInfo &amp;&amp;Arg)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9e9d106cef4491370c43c4f136fc050">~TargetTransformInfo</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d955ca0eda3479b562ccc505575049b">operator=</a> (TargetTransformInfo &amp;&amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2528c700b439460d668d188813ebf08c">invalidate</a> (Function &amp;, const PreservedAnalyses &amp;, FunctionAnalysisManager::Invalidator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle the invalidation of this information. <a href="#a2528c700b439460d668d188813ebf08c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a959a58a9740a235c53703a287e722906">hasArmWideBranch</a> (bool Thumb) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1638df5cc02529342c1f54f244789d14">getFeatureMask</a> (const Function &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a bitmask constructed from the target-features or fmv-features metadata of a function. <a href="#a1638df5cc02529342c1f54f244789d14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18b7702bcf1e5ca464ef485e1abf57a0">isMultiversionedFunction</a> (const Function &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this is an instance of a function with multiple versions. <a href="#a18b7702bcf1e5ca464ef485e1abf57a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a234a5bae6ee891cc95421752592ec7">getMaxNumArgs</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd6715c54f74d5aaab522b50a9adaf69">getNumBytesToPadGlobalArray</a> (unsigned Size, Type *ArrayType) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/concept">Concept</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a81ea1496b8c0cb3f62179071cba95c">TTIImpl</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#abd1dc2b46b5e2311e1f64d21b2991be9">PartialReductionExtendKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49120eb4a93d65c200b9aa5529f88448">getPartialReductionExtendKind</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the kind of extension that an instruction represents. <a href="#a49120eb4a93d65c200b9aa5529f88448">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Generic Target Information Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TargetCostKind { <a href="#a706f223f760b55668fbae74202b816bb">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The kind of cost model. <a href="#a706f223f760b55668fbae74202b816bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TargetCostConstants { <a href="#ac44f6b9fdbb5f9cc199f8329cb0b272c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Underlying constants for 'cost' values in this interface. <a href="#ac44f6b9fdbb5f9cc199f8329cb0b272c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57fca44604259f23a346fdc969aaefeb">getGEPCost</a> (Type *PointeeType, const Value *Ptr, ArrayRef&lt; const Value * &gt; Operands, Type *AccessType=nullptr, TargetCostKind CostKind=TCK_SizeAndLatency) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Estimate the cost of a GEP operation when lowered. <a href="#a57fca44604259f23a346fdc969aaefeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75bdd6764746631f64902145e7dd7872">getPointersChainCost</a> (ArrayRef&lt; const Value * &gt; Ptrs, const Value *Base, const PointersChainInfo &amp;Info, Type *AccessTy, TargetCostKind CostKind=TTI::TCK_RecipThroughput) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Estimate the cost of a chain of pointers (typically pointer operands of a chain of loads or stores within same block) operations set when lowered. <a href="#a75bdd6764746631f64902145e7dd7872">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab827381fb7034818435387572088683">getInliningThresholdMultiplier</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb1f3979b649f86c832e425e0b7c75b9">getInliningCostBenefitAnalysisSavingsMultiplier</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e8a14f754741d2abb6d180546fef75d">getInliningCostBenefitAnalysisProfitableMultiplier</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a751d7804543eb7033df99f99d5aa1dc1">getInliningLastCallToStaticBonus</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e5dd9267d6c9b90b4daa6410be3da6a">adjustInliningThreshold</a> (const CallBase *CB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ac02d3d31a66774a2a021b7db942dc2">getCallerAllocaCost</a> (const CallBase *CB, const AllocaInst *AI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa30e16357eef0a6bb3dc98fb7fd67684">getInlinerVectorBonusPercent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cd4d71624770e0e121a19b1efd26e52">getMemcpyCost</a> (const Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af202c774afe951c5c841c5bf356efaae">getMaxMemIntrinsicInlineSizeThreshold</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the maximum memset / memcpy size in bytes that still makes it profitable to inline the call. <a href="#af202c774afe951c5c841c5bf356efaae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64b0a3c3724fe2cb1b335007c068179d">getEstimatedNumberOfCaseClusters</a> (const SwitchInst &amp;SI, unsigned &amp;JTSize, ProfileSummaryInfo *PSI, BlockFrequencyInfo *BFI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac77dbedcfd916a5c9b58e753b2678a98">getInstructionCost</a> (const User *U, ArrayRef&lt; const Value * &gt; Operands, TargetCostKind CostKind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Estimate the cost of a given IR user when lowered. <a href="#ac77dbedcfd916a5c9b58e753b2678a98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e2a0583912318be02194abf401fdf1e">getInstructionCost</a> (const User *U, TargetCostKind CostKind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a helper function which calls the three-argument getInstructionCost with <span class="doxyComputerOutput">Operands</span> which are the current operands U has. <a href="#a3e2a0583912318be02194abf401fdf1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99b320fd35acaf648a0a7826a0bdd777">getPredictableBranchThreshold</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a branch or a select condition is skewed in one direction by more than this factor, it is very likely to be predicted correctly. <a href="#a99b320fd35acaf648a0a7826a0bdd777">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaccf34a28776644495b98ebd15e87ba6">getBranchMispredictPenalty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns estimated penalty of a branch misprediction in latency. <a href="#aaccf34a28776644495b98ebd15e87ba6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a233996b13b5fa2774af23282d8870204">hasBranchDivergence</a> (const Function *F=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if branch divergence exists. <a href="#a233996b13b5fa2774af23282d8870204">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a787ddce53dcb1b93b5c173dbbba4d3f0">isSourceOfDivergence</a> (const Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether V is a source of divergence. <a href="#a787ddce53dcb1b93b5c173dbbba4d3f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b21625ceb4a9d9eb225fa18cbf951de">isAlwaysUniform</a> (const Value *V) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad61de27a7641e7ce57bc6e3fdc8cd8d2">isValidAddrSpaceCast</a> (unsigned FromAS, unsigned ToAS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query the target whether the specified address space cast from FromAS to ToAS is valid. <a href="#ad61de27a7641e7ce57bc6e3fdc8cd8d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a3e39d2d1306afddf277fd3fca9aebb">addrspacesMayAlias</a> (unsigned AS0, unsigned AS1) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return false if a <span class="doxyComputerOutput">AS0</span> address cannot possibly alias a <span class="doxyComputerOutput">AS1</span> address. <a href="#a0a3e39d2d1306afddf277fd3fca9aebb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93e74cc1819ce2f8f151a1900284ce89">getFlatAddressSpace</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the address space <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for a target's 'flat' address space. <a href="#a93e74cc1819ce2f8f151a1900284ce89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7313158dcc10a1569a2333c78cde8621">collectFlatAddressOperands</a> (SmallVectorImpl&lt; int &gt; &amp;OpIndexes, Intrinsic::ID IID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return any intrinsic address operand indexes which may be rewritten if they use a flat address space pointer. <a href="#a7313158dcc10a1569a2333c78cde8621">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50c845c07da9fd93a05ec29509486166">isNoopAddrSpaceCast</a> (unsigned FromAS, unsigned ToAS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68ca9af33d7674947e80df6bd7e22758">canHaveNonUndefGlobalInitializerInAddressSpace</a> (unsigned AS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if globals in this address space can have initializers other than <span class="doxyComputerOutput">undef</span>. <a href="#a68ca9af33d7674947e80df6bd7e22758">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bf8eeaf9756076f0eea55ab20adf4bc">getAssumedAddrSpace</a> (const Value *V) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ba50f0bbbe7b4ae53a66e70c614cce2">isSingleThreaded</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aa721827d7115203f1eb5a3479e7d5e">getPredicatedAddrSpace</a> (const Value *V) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88bd45e10d1f1069da1b4d216d0f5f73">rewriteIntrinsicWithAddressSpace</a> (IntrinsicInst *II, Value *OldV, Value *NewV) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite intrinsic call <span class="doxyComputerOutput">II</span> such that <span class="doxyComputerOutput">OldV</span> will be replaced with <span class="doxyComputerOutput">NewV</span>, which has a different address space. <a href="#a88bd45e10d1f1069da1b4d216d0f5f73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8b08fb48c8c58e63aa231a1099475d9">isLoweredToCall</a> (const Function *F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether calls to a function lower to actual program function calls. <a href="#aa8b08fb48c8c58e63aa231a1099475d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25f5cd1eed2a2102d7a012dbc5c08e1a">getUnrollingPreferences</a> (Loop *L, ScalarEvolution &amp;, UnrollingPreferences &amp;UP, OptimizationRemarkEmitter *ORE) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get target-customized preferences for the generic loop unrolling transformation. <a href="#a25f5cd1eed2a2102d7a012dbc5c08e1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaae1d7de61213a91194e93174081ab4d">isHardwareLoopProfitable</a> (Loop *L, ScalarEvolution &amp;SE, AssumptionCache &amp;AC, TargetLibraryInfo *LibInfo, HardwareLoopInfo &amp;HWLoopInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query the target whether it would be profitable to convert the given loop into a hardware loop. <a href="#aaae1d7de61213a91194e93174081ab4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3bc636212001799868362570b66d457">getEpilogueVectorizationMinVF</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae953310cea2ff4ae78d8fcf9269f9259">preferPredicateOverEpilogue</a> (TailFoldingInfo *TFI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query the target whether it would be prefered to create a predicated vector loop, which can avoid the need to emit a scalar epilogue loop. <a href="#ae953310cea2ff4ae78d8fcf9269f9259">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdd">TailFoldingStyle</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a579a550a75fcdd6ebdb773fb2efd10de">getPreferredTailFoldingStyle</a> (bool IVUpdateMayOverflow=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query the target what the preferred style of tail folding is. <a href="#a579a550a75fcdd6ebdb773fb2efd10de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af513fb5e9b4731b5b8315d757d5a252f">getPeelingPreferences</a> (Loop *L, ScalarEvolution &amp;SE, PeelingPreferences &amp;PP) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get target-customized preferences for the generic loop peeling transformation. <a href="#af513fb5e9b4731b5b8315d757d5a252f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c34992cf5a6125fc637fbde99b88890">instCombineIntrinsic</a> (InstCombiner &amp;IC, IntrinsicInst &amp;II) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets can implement their own combinations for target-specific intrinsics. <a href="#a2c34992cf5a6125fc637fbde99b88890">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac17fdac44c73248d9e36df4fd8d93b28">simplifyDemandedUseBitsIntrinsic</a> (InstCombiner &amp;IC, IntrinsicInst &amp;II, APInt DemandedMask, KnownBits &amp;Known, bool &amp;KnownBitsComputed) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Can be used to implement target-specific instruction combining. <a href="#ac17fdac44c73248d9e36df4fd8d93b28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c63492d1e619b740c6e6d123efeb4f8">simplifyDemandedVectorEltsIntrinsic</a> (InstCombiner &amp;IC, IntrinsicInst &amp;II, APInt DemandedElts, APInt &amp;UndefElts, APInt &amp;UndefElts2, APInt &amp;UndefElts3, std::function&lt; void(Instruction *, unsigned, APInt, APInt &amp;)&gt; SimplifyAndSetOp) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Can be used to implement target-specific instruction combining. <a href="#a3c63492d1e619b740c6e6d123efeb4f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Scalar Target Information Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PopcntSupportKind { <a href="#aa4c17e89b1ef061ed69f42b7cee93dbe">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flags indicating the kind of support for population count. <a href="#aa4c17e89b1ef061ed69f42b7cee93dbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AddressingModeKind { <a href="#ad88649498463e1fe02380ad98886ce43">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f5c32f4b5bd13b1279016cd9a6db37b">isLegalAddImmediate</a> (int64_t Imm) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified immediate is legal add immediate, that is the target has add instructions which can add a register with the immediate without having to materialize the immediate into a register. <a href="#a7f5c32f4b5bd13b1279016cd9a6db37b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac23902680c153a91d17e952e2623712c">isLegalAddScalableImmediate</a> (int64_t Imm) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if adding the specified scalable immediate is legal, that is the target has add instructions which can add a register with the immediate (multiplied by vscale) without having to materialize the immediate into a register. <a href="#ac23902680c153a91d17e952e2623712c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78ff38d597ee5f9da28bb64c812520d8">isLegalICmpImmediate</a> (int64_t Imm) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified immediate is legal icmp immediate, that is the target has icmp instructions which can compare a register against the immediate without having to materialize the immediate into a register. <a href="#a78ff38d597ee5f9da28bb64c812520d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6250994dada01a076d3de7e659506234">isLegalAddressingMode</a> (Type *Ty, GlobalValue *BaseGV, int64_t BaseOffset, bool HasBaseReg, int64_t Scale, unsigned AddrSpace=0, Instruction *I=nullptr, int64_t ScalableOffset=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the addressing mode represented by AM is legal for this target, for a load/store of the specified type. <a href="#a6250994dada01a076d3de7e659506234">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d57a8095a918e8a7ebe31f964c16bbe">isLSRCostLess</a> (const TargetTransformInfo::LSRCost &amp;C1, const TargetTransformInfo::LSRCost &amp;C2) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if LSR cost of C1 is lower than C2. <a href="#a1d57a8095a918e8a7ebe31f964c16bbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb09869158c4446f417427d102199632">isNumRegsMajorCostOfLSR</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if LSR major cost is number of registers. <a href="#acb09869158c4446f417427d102199632">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c7e1bf2359f86a03f8c9cba2747ee2d">shouldDropLSRSolutionIfLessProfitable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if LSR should drop a found solution if it's calculated to be less profitable than the baseline. <a href="#a1c7e1bf2359f86a03f8c9cba2747ee2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c5b11c76ffc12a4dde038d77dc4d5ae">isProfitableLSRChainElement</a> (Instruction *I) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5711c8e7ef4d1848c44e839242316c3">canMacroFuseCmp</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target can fuse a compare and branch. <a href="#ad5711c8e7ef4d1848c44e839242316c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a884326e08a0f3d72b4f5006cf31eb76f">canSaveCmp</a> (Loop *L, BranchInst **BI, ScalarEvolution *SE, LoopInfo *LI, DominatorTree *DT, AssumptionCache *AC, TargetLibraryInfo *LibInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target can save a compare for loop count, for example hardware loop saves a compare. <a href="#a884326e08a0f3d72b4f5006cf31eb76f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad88649498463e1fe02380ad98886ce43">AddressingModeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa89a5a037e90eef4edcffea07a423748">getPreferredAddressingMode</a> (const Loop *L, ScalarEvolution *SE) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the preferred addressing mode LSR should make efforts to generate. <a href="#aa89a5a037e90eef4edcffea07a423748">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9bcc7733985bba3ab58e5c2abbc129e">isLegalMaskedStore</a> (Type *DataType, Align Alignment) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports masked store. <a href="#ab9bcc7733985bba3ab58e5c2abbc129e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff5a70644f05b7731348861016ff2af1">isLegalMaskedLoad</a> (Type *DataType, Align Alignment) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports masked load. <a href="#aff5a70644f05b7731348861016ff2af1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a923b761c973df44658c12ab18b29365c">isLegalNTStore</a> (Type *DataType, Align Alignment) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports nontemporal store. <a href="#a923b761c973df44658c12ab18b29365c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bdad414050f44dd51fe2c193b7992b6">isLegalNTLoad</a> (Type *DataType, Align Alignment) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports nontemporal load. <a href="#a7bdad414050f44dd51fe2c193b7992b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a6b14ee0f0d259ea09d847875be536f">isLegalBroadcastLoad</a> (Type *ElementTy, ElementCount NumElements) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns true if the target supports broadcasting a load to a vector of type &lt;NumElements x ElementTy&gt;. <a href="#a5a6b14ee0f0d259ea09d847875be536f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a973aabc3b5429e5e05beee35892de0">isLegalMaskedScatter</a> (Type *DataType, Align Alignment) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports masked scatter. <a href="#a0a973aabc3b5429e5e05beee35892de0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33ac7704be5bd5455f78caf0b5371012">isLegalMaskedGather</a> (Type *DataType, Align Alignment) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports masked gather. <a href="#a33ac7704be5bd5455f78caf0b5371012">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a661bd4bd069ee48ef7bf8a7892790468">forceScalarizeMaskedGather</a> (VectorType *Type, Align Alignment) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target forces scalarizing of llvm.masked.gather intrinsics. <a href="#a661bd4bd069ee48ef7bf8a7892790468">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebda4a819a6130c6c0f37a8b05dfac67">forceScalarizeMaskedScatter</a> (VectorType *Type, Align Alignment) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target forces scalarizing of llvm.masked.scatter intrinsics. <a href="#aebda4a819a6130c6c0f37a8b05dfac67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4ca31dadd4ea1a5510f43fcd2910475">isLegalMaskedCompressStore</a> (Type *DataType, Align Alignment) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports masked compress store. <a href="#ab4ca31dadd4ea1a5510f43fcd2910475">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f5ac2fb320afeb13101f5331cffa693">isLegalMaskedExpandLoad</a> (Type *DataType, Align Alignment) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports masked expand load. <a href="#a1f5ac2fb320afeb13101f5331cffa693">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c88ba0590be06436d0183b1ae819924">isLegalStridedLoadStore</a> (Type *DataType, Align Alignment) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports strided load. <a href="#a6c88ba0590be06436d0183b1ae819924">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59d32a2424444b535f76e4fb19791de8">isLegalInterleavedAccessType</a> (VectorType *VTy, unsigned Factor, Align Alignment, unsigned AddrSpace) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true is the target supports interleaved access for the given vector type <span class="doxyComputerOutput">VTy</span>, interleave factor <span class="doxyComputerOutput">Factor</span>, alignment <span class="doxyComputerOutput">Alignment</span> and address space <span class="doxyComputerOutput">AddrSpace</span>. <a href="#a59d32a2424444b535f76e4fb19791de8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb5014d79db9e7af67548e98a2680e7c">isLegalMaskedVectorHistogram</a> (Type *AddrType, Type *DataType) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae67acb89326f200683e3d0b872a5329">isLegalAltInstr</a> (VectorType *VecTy, unsigned Opcode0, unsigned Opcode1, const SmallBitVector &amp;OpcodeMask) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is an alternating opcode pattern that can be lowered to a single instruction on the target. <a href="#aae67acb89326f200683e3d0b872a5329">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e034d813ec5b7818252ac121d20a5aa">enableOrderedReductions</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we should be enabling ordered reductions for the target. <a href="#a3e034d813ec5b7818252ac121d20a5aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac31bf22f119c5a99c36646d8e0eb2c0f">hasDivRemOp</a> (Type *DataType, bool IsSigned) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target has a unified operation to calculate division and remainder. <a href="#ac31bf22f119c5a99c36646d8e0eb2c0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab33e1370498d06e0760c2861ff25e43a">hasVolatileVariant</a> (Instruction *I, unsigned AddrSpace) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given instruction (assumed to be a memory access instruction) has a volatile variant. <a href="#ab33e1370498d06e0760c2861ff25e43a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a215ea3605f88c5b21ffbdf76a72a8554">prefersVectorizedAddressing</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if target doesn't mind addresses in vectors. <a href="#a215ea3605f88c5b21ffbdf76a72a8554">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae36d969fb1c0d73ddfbadec73164ee9a">getScalingFactorCost</a> (Type *Ty, GlobalValue *BaseGV, StackOffset BaseOffset, bool HasBaseReg, int64_t Scale, unsigned AddrSpace=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cost of the scaling factor used in the addressing mode represented by AM for this target, for a load/store of the specified type. <a href="#ae36d969fb1c0d73ddfbadec73164ee9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4746d964f754f53ce75d48a418196674">LSRWithInstrQueries</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the loop strength reduce pass should make Instruction* based <a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068">TTI</a> queries to <a href="#a6250994dada01a076d3de7e659506234">isLegalAddressingMode()</a>. <a href="#a4746d964f754f53ce75d48a418196674">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3e55cf13c60a8b90145f1411367b975">isTruncateFree</a> (Type *Ty1, Type *Ty2) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's free to truncate a value of type Ty1 to type Ty2. <a href="#ae3e55cf13c60a8b90145f1411367b975">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafcbf4e3010950dd8ea0be1c4b0d3281">isProfitableToHoist</a> (Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is profitable to hoist instruction in the then/else to before if. <a href="#aafcbf4e3010950dd8ea0be1c4b0d3281">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98deb6721fb0ac45c41f71b800700596">useAA</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a84209b8495d8fd3d2799eb01f1ab2b">isTypeLegal</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this type is legal. <a href="#a7a84209b8495d8fd3d2799eb01f1ab2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a6989eb41033f67be080858c27d840a">getRegUsageForType</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the estimated number of registers required to represent <span class="doxyComputerOutput">Ty</span>. <a href="#a5a6989eb41033f67be080858c27d840a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d5b47e1f017620a784b726852915d58">shouldBuildLookupTables</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if switches should be turned into lookup tables for the target. <a href="#a0d5b47e1f017620a784b726852915d58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a265e334c170d96e5cbcf8b420db520d4">shouldBuildLookupTablesForConstant</a> (Constant *C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if switches should be turned into lookup tables containing this constant value for the target. <a href="#a265e334c170d96e5cbcf8b420db520d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcb1dfc8333359b25dda0d8cbef24e4a">shouldBuildRelLookupTables</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if lookup tables should be turned into relative lookup tables. <a href="#abcb1dfc8333359b25dda0d8cbef24e4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad30e432e7796aa46c87440cb54de2243">useColdCCForColdCall</a> (Function &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the input function which is cold at all call sites, should use coldcc calling convention. <a href="#ad30e432e7796aa46c87440cb54de2243">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a885d52cea242659c8a9380877cdfc33e">isTargetIntrinsicTriviallyScalarizable</a> (Intrinsic::ID ID) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2e6aa364f319202922a886a9d6d37f6">isTargetIntrinsicWithScalarOpAtArg</a> (Intrinsic::ID ID, unsigned ScalarOpdIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identifies if the vector form of the intrinsic has a scalar operand. <a href="#ac2e6aa364f319202922a886a9d6d37f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec1193377fa34888aa32de5f4bafb4fd">isTargetIntrinsicWithOverloadTypeAtArg</a> (Intrinsic::ID ID, int OpdIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identifies if the vector form of the intrinsic is overloaded on the type of the operand at index <span class="doxyComputerOutput">OpdIdx</span>, or on the return type if <span class="doxyComputerOutput">OpdIdx</span> is -1. <a href="#aec1193377fa34888aa32de5f4bafb4fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82f6ed49c26d8e0213dcf8d1dcff998c">isTargetIntrinsicWithStructReturnOverloadAtField</a> (Intrinsic::ID ID, int RetIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identifies if the vector form of the intrinsic that returns a struct is overloaded at the struct element index <span class="doxyComputerOutput">RetIdx</span>. <a href="#a82f6ed49c26d8e0213dcf8d1dcff998c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4e134d18ed279fbb84c667a629fd047">getScalarizationOverhead</a> (VectorType *Ty, const APInt &amp;DemandedElts, bool Insert, bool Extract, TTI::TargetCostKind CostKind, ArrayRef&lt; Value * &gt; VL={}) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Estimate the overhead of scalarizing an instruction. <a href="#ac4e134d18ed279fbb84c667a629fd047">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a296acd14b143ce1e1b0db86f4c221662">getOperandsScalarizationOverhead</a> (ArrayRef&lt; const Value * &gt; Args, ArrayRef&lt; Type * &gt; Tys, TTI::TargetCostKind CostKind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Estimate the overhead of scalarizing an instructions unique non-constant operands. <a href="#a296acd14b143ce1e1b0db86f4c221662">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1af0805a1dd7afabb0aa6cc1832b5011">supportsEfficientVectorElementLoadStore</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If target has efficient vector element load/store instructions, it can return true here so that insertion/extraction costs are not added to the scalarization cost of a load/store. <a href="#a1af0805a1dd7afabb0aa6cc1832b5011">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4d10c3084307035a3ae29cc2f420440">supportsTailCalls</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the target supports tail calls. <a href="#ad4d10c3084307035a3ae29cc2f420440">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c143ebdce9475bb57428828fe848e3a">supportsTailCallFor</a> (const CallBase *CB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If target supports tail call on <span class="doxyComputerOutput">CB</span>. <a href="#a2c143ebdce9475bb57428828fe848e3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12f25864d2ad4955cb285d871a36345b">enableAggressiveInterleaving</a> (bool LoopHasReductions) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Don't restrict interleaved unrolling to small loops. <a href="#a12f25864d2ad4955cb285d871a36345b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/memcmpexpansionoptions">MemCmpExpansionOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24629c2792a37162cf0ef4b1c38ba00c">enableMemCmpExpansion</a> (bool OptSize, bool IsZeroCmp) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72110d5a1a43e21651a36bd96cfdec98">enableSelectOptimize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should the Select Optimization pass be enabled and ran. <a href="#a72110d5a1a43e21651a36bd96cfdec98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50270e81abbcbbfe470af5ca01d54e75">shouldTreatInstructionLikeSelect</a> (const Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should the Select Optimization pass treat the given instruction like a select, potentially converting it to a conditional branch. <a href="#a50270e81abbcbbfe470af5ca01d54e75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac501bf52c07df51c9e1242117cfc7b2f">enableInterleavedAccessVectorization</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable matching of interleaved access groups. <a href="#ac501bf52c07df51c9e1242117cfc7b2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b0734de892207738014317d233c72ad">enableMaskedInterleavedAccessVectorization</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable matching of interleaved access groups that contain predicated accesses or gaps and therefore vectorized using masked vector loads/stores. <a href="#a6b0734de892207738014317d233c72ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab75d51988243f8ea9086b110401f8758">isFPVectorizationPotentiallyUnsafe</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate that it is potentially unsafe to automatically vectorize floating-point operations because the semantics of vector and scalar floating-point semantics may differ. <a href="#ab75d51988243f8ea9086b110401f8758">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e737ae000f542eba6ebc679637144d9">allowsMisalignedMemoryAccesses</a> (LLVMContext &amp;Context, unsigned BitWidth, unsigned AddressSpace=0, Align Alignment=Align(1), unsigned *Fast=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the target supports unaligned memory accesses. <a href="#a9e737ae000f542eba6ebc679637144d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa4c17e89b1ef061ed69f42b7cee93dbe">PopcntSupportKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6480799b120b617b9b34f1313afe6661">getPopcntSupport</a> (unsigned IntTyWidthInBit) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return hardware support for population count. <a href="#a6480799b120b617b9b34f1313afe6661">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef998bb15ea045fc769232b62ad0d968">haveFastSqrt</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the hardware has a fast square-root instruction. <a href="#aef998bb15ea045fc769232b62ad0d968">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30646d63c1f1ca132d37dff17cf5daae">isExpensiveToSpeculativelyExecute</a> (const Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the cost of the instruction is too high to speculatively execute and should be kept behind a branch. <a href="#a30646d63c1f1ca132d37dff17cf5daae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a199e3382d45514816f88cb65310decb4">isFCmpOrdCheaperThanFCmpZero</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is faster to check if a floating-point value is NaN (or not-NaN) versus a comparison against a constant FP zero value. <a href="#a199e3382d45514816f88cb65310decb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3b0e7df7704fa34e356e1178374b49e">getFPOpCost</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the expected cost of supporting the floating point operation of the specified type. <a href="#ad3b0e7df7704fa34e356e1178374b49e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f708e28c4cf4fcdbbe363849b779a00">getIntImmCost</a> (const APInt &amp;Imm, Type *Ty, TargetCostKind CostKind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the expected cost of materializing for the given integer immediate of the specified type. <a href="#a8f708e28c4cf4fcdbbe363849b779a00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c5798a479ce88e66e1b53d70d678332">getIntImmCostInst</a> (unsigned Opc, unsigned Idx, const APInt &amp;Imm, Type *Ty, TargetCostKind CostKind, Instruction *Inst=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the expected cost of materialization for the given integer immediate of the specified type for a given instruction. <a href="#a6c5798a479ce88e66e1b53d70d678332">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6abe636878bffb348ed313016ab1c21b">getIntImmCostIntrin</a> (Intrinsic::ID IID, unsigned Idx, const APInt &amp;Imm, Type *Ty, TargetCostKind CostKind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8771f57e56c0bc0e9ace92ede634839">getIntImmCodeSizeCost</a> (unsigned Opc, unsigned Idx, const APInt &amp;Imm, Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the expected cost for the given integer when optimising for size. <a href="#aa8771f57e56c0bc0e9ace92ede634839">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a954be846c618b16d1e51108cf99168df">preferToKeepConstantsAttached</a> (const Instruction &amp;Inst, const Function &amp;Fn) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>It can be advantageous to detach complex constants from their uses to make their generation cheaper. <a href="#a954be846c618b16d1e51108cf99168df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Vector Target Information Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ShuffleKind { <a href="#af46433d0e36d3f80afc3a8c67b5c53ec">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The various kinds of shuffle patterns for vector queries. <a href="#af46433d0e36d3f80afc3a8c67b5c53ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OperandValueKind { <a href="#afa38851d75434d1476444ac93f94cb4c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Additional information about an operand's possible values. <a href="#afa38851d75434d1476444ac93f94cb4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OperandValueProperties { <a href="#a733fb237f3037c95ed59de6055b176c5">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Additional properties of an operand's values. <a href="#a733fb237f3037c95ed59de6055b176c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RegisterKind { <a href="#a8bb3b1ccf19b8c85429b777dfa4a0166">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">CacheLevel { <a href="#afbde4c30736df440ecdeee35a0608f6b">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The possible cache levels. <a href="#afbde4c30736df440ecdeee35a0608f6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CastContextHint : uint8_t { <a href="#af84cce349a77262269fd3f6756f37a64">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a hint about the context in which a cast is used. <a href="#af84cce349a77262269fd3f6756f37a64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MemIndexedMode { <a href="#acf5cc8324c33cb1f59869456263f9f4b">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type of load/store indexing. <a href="#acf5cc8324c33cb1f59869456263f9f4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ReductionShuffle { <a href="#a0692c75c1b45226b6afb90ad609eb86a">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/operandvalueinfo">OperandValueInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fecba95c1ba20950ea8e2139127e621">getOperandInfo</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect properties of V used in cost analysis, e.g. OP_PowerOf2. <a href="#a5fecba95c1ba20950ea8e2139127e621">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#af84cce349a77262269fd3f6756f37a64">CastContextHint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a096c8b641174dc0e486006926c5202cf">getCastContextHint</a> (const Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculates a <a href="#af84cce349a77262269fd3f6756f37a64">CastContextHint</a> from <span class="doxyComputerOutput">I</span>. <a href="#a096c8b641174dc0e486006926c5202cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aecc3cf03beff532c2b8bfe81e500c8">requiresOrderedReduction</a> (std::optional&lt; FastMathFlags &gt; FMF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper function to determine the type of reduction algorithm used for a given <span class="doxyComputerOutput">Opcode</span> and set of <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> <span class="doxyComputerOutput">FMF</span>. <a href="#a7aecc3cf03beff532c2b8bfe81e500c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae0e8ca52658f54e5cc6214eb1a291ef">getNumberOfRegisters</a> (unsigned ClassID) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada0fe933e853c23312ff60304ce7e220">hasConditionalLoadStoreForType</a> (Type *Ty=nullptr) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a623cced59353f83cc5eaba4068c57694">getRegisterClassForType</a> (bool Vector, Type *Ty=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97503ae3ef00c5f1eaffa5bbeb0a4357">getRegisterClassName</a> (unsigned ClassID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d30dd50c6b2d64ca3bc2826ca229fdb">getRegisterBitWidth</a> (RegisterKind K) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fa8b3631e74e836453f972aac6b4b65">getMinVectorRegisterBitWidth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3586d4f687e1a068f879bf29b046eb3a">getMaxVScale</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04394f31b3d57c89fd8211783a12736d">getVScaleForTuning</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a761a2a864705382c56d6406a6a97e6fc">isVScaleKnownToBeAPowerOfTwo</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a525b5174ebf7ac1db045dde5f579ddcb">shouldMaximizeVectorBandwidth</a> (TargetTransformInfo::RegisterKind K) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a94a8710c9c41b64870559c9098f305">getMinimumVF</a> (unsigned ElemWidth, bool IsScalable) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a785bcc5cab17bd5d96f800247dad0649">getMaximumVF</a> (unsigned ElemWidth, unsigned Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdf352ba0545cdb2ad70f4d72b594cfa">getStoreMinimumVF</a> (unsigned VF, Type *ScalarMemTy, Type *ScalarValTy) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9880b7512930d879440db073b536d362">shouldConsiderAddressTypePromotion</a> (const Instruction &amp;I, bool &amp;AllowPromotionWithoutCommonHeader) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d04cbecfee76b1c4a5ea83aa6bb113c">getCacheLineSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0d6473c3ac48c1d2d9436408e6b9e82">getCacheSize</a> (CacheLevel Level) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b210e7ba1c2c222ab9d01202a55f723">getCacheAssociativity</a> (CacheLevel Level) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4e57c55018de258547a8248748cc667">getMinPageSize</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e3f3a3d549cf057479e744e7ecfd7e1">getPrefetchDistance</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dcadecc95e9e49f77a70ab8b99a8c35">getMinPrefetchStride</a> (unsigned NumMemAccesses, unsigned NumStridedMemAccesses, unsigned NumPrefetches, bool HasCall) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some HW prefetchers can handle accesses up to a certain constant stride. <a href="#a8dcadecc95e9e49f77a70ab8b99a8c35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66cb8d0f215f1b7b66e4a7d6581b3a16">getMaxPrefetchIterationsAhead</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ec5838370bf4a0d0af43e443ee99325">enableWritePrefetching</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f4eb225c0b7b93c8b8e6c0de860fb5f">shouldPrefetchAddressSpace</a> (unsigned AS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb33d253939bf13b4cb03af00b23a182">getPartialReductionCost</a> (unsigned Opcode, Type *InputTypeA, Type *InputTypeB, Type *AccumType, ElementCount VF, PartialReductionExtendKind OpAExtend, PartialReductionExtendKind OpBExtend, std::optional&lt; unsigned &gt; BinOp=std::nullopt) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8c60443d89e7ed0d199dfddafd5885f">getMaxInterleaveFactor</a> (ElementCount VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a713bb53f77454635f44dd95c53fc8684">getArithmeticInstrCost</a> (unsigned Opcode, Type *Ty, TTI::TargetCostKind CostKind=TTI::TCK_RecipThroughput, TTI::OperandValueInfo Opd1Info={TTI::OK_AnyValue, TTI::OP_None}, TTI::OperandValueInfo Opd2Info={TTI::OK_AnyValue, TTI::OP_None}, ArrayRef&lt; const Value * &gt; Args={}, const Instruction *CxtI=nullptr, const TargetLibraryInfo *TLibInfo=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an approximation of reciprocal throughput of a math/logic op. <a href="#a713bb53f77454635f44dd95c53fc8684">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac442c18de69f9270e02ee8e35113502c">getAltInstrCost</a> (VectorType *VecTy, unsigned Opcode0, unsigned Opcode1, const SmallBitVector &amp;OpcodeMask, TTI::TargetCostKind CostKind=TTI::TCK_RecipThroughput) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the cost estimation for alternating opcode pattern that can be lowered to a single instruction on the target. <a href="#ac442c18de69f9270e02ee8e35113502c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eebd7cdc98c9b46d8d4016143c7bdcb">getShuffleCost</a> (ShuffleKind Kind, VectorType *Tp, ArrayRef&lt; int &gt; Mask={}, TTI::TargetCostKind CostKind=TTI::TCK_RecipThroughput, int Index=0, VectorType *SubTp=nullptr, ArrayRef&lt; const Value * &gt; Args={}, const Instruction *CxtI=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a425eab58717b81784602a0b169dd9ff8">getCastInstrCost</a> (unsigned Opcode, Type *Dst, Type *Src, TTI::CastContextHint CCH, TTI::TargetCostKind CostKind=TTI::TCK_SizeAndLatency, const Instruction *I=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbea7151f5e66776f92f7b4e305418d6">getExtractWithExtendCost</a> (unsigned Opcode, Type *Dst, VectorType *VecTy, unsigned Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7b131843b386c6e3cc39bd6f8141357">getCFInstrCost</a> (unsigned Opcode, TTI::TargetCostKind CostKind=TTI::TCK_SizeAndLatency, const Instruction *I=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22d6c699561d5ad3862a043fde6b797d">getCmpSelInstrCost</a> (unsigned Opcode, Type *ValTy, Type *CondTy, CmpInst::Predicate VecPred, TTI::TargetCostKind CostKind=TTI::TCK_RecipThroughput, OperandValueInfo Op1Info={OK_AnyValue, OP_None}, OperandValueInfo Op2Info={OK_AnyValue, OP_None}, const Instruction *I=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af37b2842424eb63440bdcacca0af9820">getVectorInstrCost</a> (unsigned Opcode, Type *Val, TTI::TargetCostKind CostKind, unsigned Index=-1, Value *Op0=nullptr, Value *Op1=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7e3745e82595d80efba229ee7c4ec0c">getVectorInstrCost</a> (unsigned Opcode, Type *Val, TTI::TargetCostKind CostKind, unsigned Index, Value *Scalar, ArrayRef&lt; std::tuple&lt; Value *, User *, int &gt; &gt; ScalarUserAndIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8faf795a9033768e63f8907829339ccf">getVectorInstrCost</a> (const Instruction &amp;I, Type *Val, TTI::TargetCostKind CostKind, unsigned Index=-1) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35a3b8f44dff2cf349e66821606dfa8d">getReplicationShuffleCost</a> (Type *EltTy, int ReplicationFactor, int VF, const APInt &amp;DemandedDstElts, TTI::TargetCostKind CostKind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34c987c590db0e5cff66d9869a34c556">getMemoryOpCost</a> (unsigned Opcode, Type *Src, Align Alignment, unsigned AddressSpace, TTI::TargetCostKind CostKind=TTI::TCK_RecipThroughput, OperandValueInfo OpdInfo={OK_AnyValue, OP_None}, const Instruction *I=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a846e472a2fb24cec08762c2c26624a35">getVPMemoryOpCost</a> (unsigned Opcode, Type *Src, Align Alignment, unsigned AddressSpace, TTI::TargetCostKind CostKind=TTI::TCK_RecipThroughput, const Instruction *I=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8718d4f9740c67449057887b386fb348">getMaskedMemoryOpCost</a> (unsigned Opcode, Type *Src, Align Alignment, unsigned AddressSpace, TTI::TargetCostKind CostKind=TTI::TCK_RecipThroughput) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0f4a801858ac7255f623ca0ec53394f">getGatherScatterOpCost</a> (unsigned Opcode, Type *DataTy, const Value *Ptr, bool VariableMask, Align Alignment, TTI::TargetCostKind CostKind=TTI::TCK_RecipThroughput, const Instruction *I=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b5066bc4acd72f9d474ebbf5eec6de3">getStridedMemoryOpCost</a> (unsigned Opcode, Type *DataTy, const Value *Ptr, bool VariableMask, Align Alignment, TTI::TargetCostKind CostKind=TTI::TCK_RecipThroughput, const Instruction *I=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38000267bdb6bb25b9c33f9fd7053b1d">getInterleavedMemoryOpCost</a> (unsigned Opcode, Type *VecTy, unsigned Factor, ArrayRef&lt; unsigned &gt; Indices, Align Alignment, unsigned AddressSpace, TTI::TargetCostKind CostKind=TTI::TCK_RecipThroughput, bool UseMaskForCond=false, bool UseMaskForGaps=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a421ee26483edf3fd0cd1dca34513f45e">getArithmeticReductionCost</a> (unsigned Opcode, VectorType *Ty, std::optional&lt; FastMathFlags &gt; FMF, TTI::TargetCostKind CostKind=TTI::TCK_RecipThroughput) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the cost of vector reduction intrinsics. <a href="#a421ee26483edf3fd0cd1dca34513f45e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6da1f2e3b471cce50680e800c05e4d6b">getMinMaxReductionCost</a> (Intrinsic::ID IID, VectorType *Ty, FastMathFlags FMF=FastMathFlags(), TTI::TargetCostKind CostKind=TTI::TCK_RecipThroughput) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61fd571365b64379faf5eb0b3caa1b27">getMulAccReductionCost</a> (bool IsUnsigned, Type *ResTy, VectorType *Ty, TTI::TargetCostKind CostKind=TTI::TCK_RecipThroughput) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the cost of an extended reduction pattern, similar to getArithmeticReductionCost of an Add reduction with multiply and optional extensions. <a href="#a61fd571365b64379faf5eb0b3caa1b27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f958d8d050bfd1a5b0ea73186f2e36e">getExtendedReductionCost</a> (unsigned Opcode, bool IsUnsigned, Type *ResTy, VectorType *Ty, FastMathFlags FMF, TTI::TargetCostKind CostKind=TTI::TCK_RecipThroughput) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the cost of an extended reduction pattern, similar to getArithmeticReductionCost of a reduction with an extension. <a href="#a5f958d8d050bfd1a5b0ea73186f2e36e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4218f47749d093473e680ad0199fb239">getIntrinsicInstrCost</a> (const IntrinsicCostAttributes &amp;ICA, TTI::TargetCostKind CostKind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af67833027bb46ddb390684a6f0b75398">getCallInstrCost</a> (Function *F, Type *RetTy, ArrayRef&lt; Type * &gt; Tys, TTI::TargetCostKind CostKind=TTI::TCK_SizeAndLatency) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad67b7e389a52ada1d5264e23d09f4cbe">getNumberOfParts</a> (Type *Tp) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a246f298958a4a730bf7d3a64440dd47b">getAddressComputationCost</a> (Type *Ty, ScalarEvolution *SE=nullptr, const SCEV *Ptr=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8920039419b33a0b7248a0957e262ee7">getCostOfKeepingLiveOverCall</a> (ArrayRef&lt; Type * &gt; Tys) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02e4dcfc435f179592619b03330f643b">getTgtMemIntrinsic</a> (IntrinsicInst *Inst, MemIntrinsicInfo &amp;Info) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a422b020a05731c432411d574a7728af5">getAtomicMemIntrinsicMaxElementSize</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5e18a8730e428b4967b375d57c2e401">getOrCreateResultFromMemIntrinsic</a> (IntrinsicInst *Inst, Type *ExpectedType) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e5bbdb7bb28a7e509e6893d56ab60b8">getMemcpyLoopLoweringType</a> (LLVMContext &amp;Context, Value *Length, unsigned SrcAddrSpace, unsigned DestAddrSpace, Align SrcAlign, Align DestAlign, std::optional&lt; uint32_t &gt; AtomicElementSize=std::nullopt) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae609e12c2691f94194afb835facb5c86">getMemcpyLoopResidualLoweringType</a> (SmallVectorImpl&lt; Type * &gt; &amp;OpsOut, LLVMContext &amp;Context, unsigned RemainingBytes, unsigned SrcAddrSpace, unsigned DestAddrSpace, Align SrcAlign, Align DestAlign, std::optional&lt; uint32_t &gt; AtomicCpySize=std::nullopt) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2e1f19379514bb06cdcedb2bae8748d">areInlineCompatible</a> (const Function *Caller, const Function *Callee) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eae79e5ad5916c4e64cb73eb0b27323">getInlineCallPenalty</a> (const Function *F, const CallBase &amp;Call, unsigned DefaultCallPenalty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a penalty for invoking call <span class="doxyComputerOutput">Call</span> in <span class="doxyComputerOutput">F</span>. <a href="#a2eae79e5ad5916c4e64cb73eb0b27323">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71773f01b77047575c95791e12f91246">areTypesABICompatible</a> (const Function *Caller, const Function *Callee, const ArrayRef&lt; Type * &gt; &amp;Types) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7716bda26c61738e624214efa149e83e">isIndexedLoadLegal</a> (enum MemIndexedMode Mode, Type *Ty) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a768ef7bcf1b5059f409327c1f83591">isIndexedStoreLegal</a> (enum MemIndexedMode Mode, Type *Ty) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c9d2da3e41e4cc90c7a552258166277">getLoadStoreVecRegBitWidth</a> (unsigned AddrSpace) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03aaf2f1c4d2a4bb801bc9aeea94de3c">isLegalToVectorizeLoad</a> (LoadInst *LI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0de4290b00b162ec20705cad42047b64">isLegalToVectorizeStore</a> (StoreInst *SI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaa75efd79296070e4c5f24fa3ea6f01">isLegalToVectorizeLoadChain</a> (unsigned ChainSizeInBytes, Align Alignment, unsigned AddrSpace) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58b0dcd9d3ef39aa308b7d7371e5da88">isLegalToVectorizeStoreChain</a> (unsigned ChainSizeInBytes, Align Alignment, unsigned AddrSpace) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b174ae4841c69cd671ed4bf4834db64">isLegalToVectorizeReduction</a> (const RecurrenceDescriptor &amp;RdxDesc, ElementCount VF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64e28d7d5da07059305e09ff16ee5d0b">isElementTypeLegalForScalableVector</a> (Type *Ty) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84e51850e7e39c4bd2424ad98c12e700">getLoadVectorFactor</a> (unsigned VF, unsigned LoadSize, unsigned ChainSizeInBytes, VectorType *VecTy) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47da5df7f765cada1df9036a3433e1a4">getStoreVectorFactor</a> (unsigned VF, unsigned StoreSize, unsigned ChainSizeInBytes, VectorType *VecTy) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc2ae54af36c42e74d1ed1dbb858e7e6">preferFixedOverScalableIfEqualCost</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a2b30bdeffa3fb4a4fd881e25d01817">preferInLoopReduction</a> (unsigned Opcode, Type *Ty, ReductionFlags Flags) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e8f7af4c35e8c6bc6e9a4f0850a7847">preferPredicatedReductionSelect</a> (unsigned Opcode, Type *Ty, ReductionFlags Flags) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a987fde1294b059921cb381631fa3747b">preferEpilogueVectorization</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the loop vectorizer should consider vectorizing an otherwise scalar epilogue loop. <a href="#a987fde1294b059921cb381631fa3747b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefeefc63fa057f5050b78547c6cdf0e1">shouldExpandReduction</a> (const IntrinsicInst *II) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0692c75c1b45226b6afb90ad609eb86a">ReductionShuffle</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e995d547e3a71909c78baf33c3c6942">getPreferredExpandedReductionShuffle</a> (const IntrinsicInst *II) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd2f1ef61f1c352da3b8121d4ea2c585">getGISelRematGlobalCost</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac50791ac3dd33dc3dc522df16116a27b">getMinTripCountTailFoldingThreshold</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0215ddedbe9f8179c491308a56aaceb">supportsScalableVectors</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac912bf74dab55fe744b25c739e29d7b0">enableScalableVectorization</a> () const</td>
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

## Vector Predication Information Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3898235ae1cbefb03b09d1ddebae0e5">hasActiveVectorLength</a> (unsigned Opcode, Type *DataType, Align Alignment) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae553d04f4c990459f9827950e6c71e75">isProfitableToSinkOperands</a> (Instruction *I, SmallVectorImpl&lt; Use * &gt; &amp;Ops) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if sinking I's operands to the same basic block as I is profitable, e.g. <a href="#ae553d04f4c990459f9827950e6c71e75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca4d7e4051f7cb81a1e79bb1e25f03d5">isVectorShiftByScalarCheap</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's significantly cheaper to shift a vector by a uniform scalar than by an amount which will vary across each lane. <a href="#aca4d7e4051f7cb81a1e79bb1e25f03d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/vplegalization">VPLegalization</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4843aaa2647f4f1fb037f957beda8eaa">getVPLegalizationStrategy</a> (const VPIntrinsic &amp;PI) const</td>
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

<p>This pass provides access to the codegen interfaces that are needed for IR-level transformations.</p>

<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### PartialReductionExtendKind {#abd1dc2b46b5e2311e1f64d21b2991be9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TargetTransformInfo::PartialReductionExtendKind </td>
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
<td class="doxyEnumItemName">PR_None<a id="abd1dc2b46b5e2311e1f64d21b2991be9a396ecbc9f5a284ef21d8a8770812d8ee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PR_SignExtend<a id="abd1dc2b46b5e2311e1f64d21b2991be9a06943619e512a4ace7ddb8316f4ea2fa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PR_ZeroExtend<a id="abd1dc2b46b5e2311e1f64d21b2991be9a3553356243ee35e0c75047ea0202625c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TargetTransformInfo() {#af1bf12b2f33b7e30f8f361a1e7642079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetTransformInfo::TargetTransformInfo (T Impl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a <a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068">TTI</a> object using a type implementing the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/concept">Concept</a></span> API below.</p>


<p>This is used by targets to construct a <a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068">TTI</a> wrapping their target-specific implementation that encodes appropriate costs for their target.</p>


<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a6d955ca0eda3479b562ccc505575049b">operator=</a> and <a href="#ab158463a734f57c86e685364527ebaa4">TargetTransformInfo</a>.</p>

</div>
</div>

### TargetTransformInfo() {#ac7b62dddca1c89d43af02d0e2ab06030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo::TargetTransformInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>Construct a baseline <a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068">TTI</a> object using a minimal implementation of the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/concept">Concept</a></span> API below.</p>


<p>The <a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068">TTI</a> implementation will reflect the information in the <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> provided if non-null.</p>


<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

### TargetTransformInfo() {#ab158463a734f57c86e685364527ebaa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo::TargetTransformInfo (<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;&amp; Arg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#af1bf12b2f33b7e30f8f361a1e7642079">TargetTransformInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~TargetTransformInfo() {#af9e9d106cef4491370c43c4f136fc050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo::~TargetTransformInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a6d955ca0eda3479b562ccc505575049b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo &amp; TargetTransformInfo::operator= (<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;&amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="#af1bf12b2f33b7e30f8f361a1e7642079">TargetTransformInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFeatureMask() {#a1638df5cc02529342c1f54f244789d14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t TargetTransformInfo::getFeatureMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a bitmask constructed from the target-features or fmv-features metadata of a function.</p>

<p>Declaration at line 1880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1386 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### getMaxNumArgs() {#a0a234a5bae6ee891cc95421752592ec7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getMaxNumArgs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The maximum number of function arguments the target supports.</p></dd>
</dl>


<p>Declaration at line 1886 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1394 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getNumBytesToPadGlobalArray() {#acd6715c54f74d5aaab522b50a9adaf69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getNumBytesToPadGlobalArray (unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ArrayType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>For an array of given Size, return alignment boundary to pad to. Default is no padding.</p></dd>
</dl>


<p>Declaration at line 1890 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1439 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### hasArmWideBranch() {#a959a58a9740a235c53703a287e722906}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::hasArmWideBranch (bool Thumb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Whether a 32-bit branch instruction is available in Arm or Thumb state.</p></dd>
</dl>


<p>Used by the LowerTypeTests pass, which constructs an IR inline assembler node containing a jump table in a format suitable for the target, so it needs to know what format of jump table it can legally use.</p>


<p>For non-Arm targets, this function isn't used. It defaults to returning false, but it shouldn't matter what it returns anyway.</p>


<p>Declaration at line 1876 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1382 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### invalidate() {#a2528c700b439460d668d188813ebf08c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetTransformInfo::invalidate (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp;, FunctionAnalysisManager::Invalidator &amp;)</td>
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

<p>Handle the invalidation of this information.</p>


<p>When used as a result of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/targetiranalysis">TargetIRAnalysis</a></span> this method will be called when the function this was computed for changes. When it returns false, the information is preserved across those changes.</p>


<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

### isMultiversionedFunction() {#a18b7702bcf1e5ca464ef485e1abf57a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isMultiversionedFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this is an instance of a function with multiple versions.</p>

<p>Declaration at line 1883 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1390 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### TTIImpl {#a3a81ea1496b8c0cb3f62179071cba95c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Concept&gt; llvm::TargetTransformInfo::TTIImpl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1903 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getPartialReductionExtendKind() {#a49120eb4a93d65c200b9aa5529f88448}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo::PartialReductionExtendKind TargetTransformInfo::getPartialReductionExtendKind (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Get the kind of extension that an instruction represents.</p>

<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 987 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#abd1dc2b46b5e2311e1f64d21b2991be9a396ecbc9f5a284ef21d8a8770812d8ee">PR_None</a>, <a href="#abd1dc2b46b5e2311e1f64d21b2991be9a06943619e512a4ace7ddb8316f4ea2fa">PR_SignExtend</a> and <a href="#abd1dc2b46b5e2311e1f64d21b2991be9a3553356243ee35e0c75047ea0202625c">PR_ZeroExtend</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Generic Target Information

### addrspacesMayAlias {#a0a3e39d2d1306afddf277fd3fca9aebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetTransformInfo::addrspacesMayAlias (unsigned AS0, unsigned AS1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return false if a <span class="doxyComputerOutput">AS0</span> address cannot possibly alias a <span class="doxyComputerOutput">AS1</span> address.</p>

<p>Declaration at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### adjustInliningThreshold {#a7e5dd9267d6c9b90b4daa6410be3da6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::adjustInliningThreshold (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A value to be added to the inlining threshold.</p></dd>
</dl>


<p>Declaration at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### canHaveNonUndefGlobalInitializerInAddressSpace {#a68ca9af33d7674947e80df6bd7e22758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::canHaveNonUndefGlobalInitializerInAddressSpace (unsigned AS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if globals in this address space can have initializers other than <span class="doxyComputerOutput">undef</span>.</p>

<p>Declaration at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### collectFlatAddressOperands {#a7313158dcc10a1569a2333c78cde8621}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::collectFlatAddressOperands (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; OpIndexes, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return any intrinsic address operand indexes which may be rewritten if they use a flat address space pointer.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the intrinsic was handled.</p></dd>
</dl>


<p>Declaration at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getAssumedAddrSpace {#a1bf8eeaf9756076f0eea55ab20adf4bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getAssumedAddrSpace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getBranchMispredictPenalty {#aaccf34a28776644495b98ebd15e87ba6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getBranchMispredictPenalty ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns estimated penalty of a branch misprediction in latency.</p>


<p>Indicates how aggressive the target wants for eliminating unpredictable branches. A zero return value means extra optimization applied to them should be minimal.</p>


<p>Declaration at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getCallerAllocaCost {#a9ac02d3d31a66774a2a021b7db942dc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getCallerAllocaCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * AI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The cost of having an Alloca in the caller if not inlined, to be added to the threshold</p></dd>
</dl>


<p>Declaration at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getEpilogueVectorizationMinVF {#aa3bc636212001799868362570b66d457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getEpilogueVectorizationMinVF ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 647 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getEstimatedNumberOfCaseClusters {#a64b0a3c3724fe2cb1b335007c068179d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getEstimatedNumberOfCaseClusters (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> &amp; SI, unsigned &amp; JTSize, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The estimated number of case clusters when lowering <span class="doxyComputerOutput">'<a href="/web-llvm/docs/api/namespaces/llvm/si">SI</a>'</span>. <span class="doxyComputerOutput">JTSize</span> Set a jump table size only when <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/si">SI</a></span> is suitable for a jump table.</p></dd>
</dl>


<p>Declaration at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getFlatAddressSpace {#a93e74cc1819ce2f8f151a1900284ce89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getFlatAddressSpace ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the address space <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for a target's 'flat' address space.</p>


<p>Note this is not necessarily the same as addrspace(0), which LLVM sometimes refers to as the generic address space. The flat address space is a generic address space that can be used access multiple segments of memory with different address spaces. Access of a memory location through a pointer with this address space is expected to be legal but slower compared to the same memory location accessed through a pointer with a different address space. This is for targets with different pointer representations which can be converted with the addrspacecast instruction. If a pointer is converted to this address space, optimizations should attempt to replace the access with the source address space.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>~0u if the target does not have such a flat address space to optimize away.</p></dd>
</dl>


<p>Declaration at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getGEPCost {#a57fca44604259f23a346fdc969aaefeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getGEPCost (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * PointeeType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Operands, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * AccessType=nullptr, <a href="#a706f223f760b55668fbae74202b816bb">TargetCostKind</a> CostKind=<a href="#a706f223f760b55668fbae74202b816bba7f80055e1969cb850739546467460ad8">TCK_SizeAndLatency</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Estimate the cost of a GEP operation when lowered.</p>


<p><span class="doxyComputerOutput">PointeeType</span> is the source element type of the GEP. <span class="doxyComputerOutput">Ptr</span> is the base pointer operand. <span class="doxyComputerOutput">Operands</span> is the list of indices following the base pointer.</p>


<p><span class="doxyComputerOutput">AccessType</span> is a hint as to what type of memory might be accessed by users of the GEP. getGEPCost will use it to determine if the GEP can be folded into the addressing mode of a load/store. If AccessType is null, then the resulting target type based off of PointeeType will be used as an approximation.</p>


<p>Declaration at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### getInlinerVectorBonusPercent {#aa30e16357eef0a6bb3dc98fb7fd67684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int TargetTransformInfo::getInlinerVectorBonusPercent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Vector bonus in percent.</p></dd>
</dl>


<p>Vector bonuses: We want to more aggressively inline vector-dense kernels and apply this bonus based on the percentage of vector instructions. A bonus is applied if the vector instructions exceed 50% and half that amount is applied if it exceeds 10%. Note that these bonuses are some what arbitrary and evolved over time by accident as much as because they are principled bonuses. FIXME: It would be nice to base the bonus values on something more scientific. A target may has no bonus on vector instructions.</p>


<p>Declaration at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getInliningCostBenefitAnalysisProfitableMultiplier {#a3e8a14f754741d2abb6d180546fef75d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getInliningCostBenefitAnalysisProfitableMultiplier ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getInliningCostBenefitAnalysisSavingsMultiplier {#acb1f3979b649f86c832e425e0b7c75b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getInliningCostBenefitAnalysisSavingsMultiplier ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getInliningLastCallToStaticBonus {#a751d7804543eb7033df99f99d5aa1dc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int TargetTransformInfo::getInliningLastCallToStaticBonus ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The bonus of inlining the last call to a static function.</p></dd>
</dl>


<p>Declaration at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp/#a0e5ee7a451482722a4446bdf208df9fc">shouldBeDeferred</a>.</p>

</div>
</div>

### getInliningThresholdMultiplier {#aab827381fb7034818435387572088683}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getInliningThresholdMultiplier ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A value by which our inlining threshold should be multiplied. This is primarily used to bump up the inlining threshold wholesale on targets where calls are unusually expensive.</p></dd>
</dl>


<p>TODO: This is a rather blunt instrument. Perhaps altering the costs of individual classes of instructions would be better.</p>


<p>Declaration at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getInstructionCost {#ac77dbedcfd916a5c9b58e753b2678a98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getInstructionCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> * U, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Operands, <a href="#a706f223f760b55668fbae74202b816bb">TargetCostKind</a> CostKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Estimate the cost of a given IR user when lowered.</p>


<p>This can estimate the cost of either a <a href="/web-llvm/docs/api/classes/llvm/constantexpr">ConstantExpr</a> or <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> when lowered.</p>


<p><span class="doxyComputerOutput">Operands</span> is a list of operands which can be a result of transformations of the current operands. The number of the operands on the list must equal to the number of the current operands the IR user has. Their order on the list must be the same as the order of the current operands the IR user has.</p>


<p>The returned cost is defined in terms of <span class="doxyComputerOutput"><a href="#ac44f6b9fdbb5f9cc199f8329cb0b272c">TargetCostConstants</a></span>, see its comments for a detailed explanation of the cost values.</p>


<p>Declaration at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">TCK_RecipThroughput</a>.</p>


<p>Referenced by <a href="#a3e2a0583912318be02194abf401fdf1e">getInstructionCost</a>.</p>

</div>
</div>

### getInstructionCost {#a3e2a0583912318be02194abf401fdf1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::TargetTransformInfo::getInstructionCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> * U, <a href="#a706f223f760b55668fbae74202b816bb">TargetCostKind</a> CostKind)</td>
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

<p>This is a helper function which calls the three-argument getInstructionCost with <span class="doxyComputerOutput">Operands</span> which are the current operands U has.</p>

<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="#ac77dbedcfd916a5c9b58e753b2678a98">getInstructionCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>

</div>
</div>

### getMaxMemIntrinsicInlineSizeThreshold {#af202c774afe951c5c841c5bf356efaae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t TargetTransformInfo::getMaxMemIntrinsicInlineSizeThreshold ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the maximum memset / memcpy size in bytes that still makes it profitable to inline the call.</p>

<p>Declaration at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1211 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getMemcpyCost {#a7cd4d71624770e0e121a19b1efd26e52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getMemcpyCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the expected cost of a memcpy, which could e.g. depend on the source/destination type and alignment and the number of bytes copied.</p></dd>
</dl>


<p>Declaration at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1205 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getPeelingPreferences {#af513fb5e9b4731b5b8315d757d5a252f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetTransformInfo::getPeelingPreferences (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/peelingpreferences">PeelingPreferences</a> &amp; PP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get target-customized preferences for the generic loop peeling transformation.</p>


<p>The caller will initialize <span class="doxyComputerOutput">PP</span> with the current target-independent defaults with information from <span class="doxyComputerOutput">L</span> and <span class="doxyComputerOutput">SE</span>.</p>


<p>Declaration at line 682 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getPointersChainCost {#a75bdd6764746631f64902145e7dd7872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getPointersChainCost (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Ptrs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Base, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/pointerschaininfo">PointersChainInfo</a> &amp; Info, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * AccessTy, <a href="#a706f223f760b55668fbae74202b816bb">TargetCostKind</a> CostKind=<a href="#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">TTI::TCK_RecipThroughput</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Estimate the cost of a chain of pointers (typically pointer operands of a chain of loads or stores within same block) operations set when lowered.</p>


<p><span class="doxyComputerOutput">AccessTy</span> is the type of the loads/stores that will ultimately use the <span class="doxyComputerOutput">Ptrs</span>.</p>


<p>Declaration at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>.</p>

</div>
</div>

### getPredicatedAddrSpace {#a5aa721827d7115203f1eb5a3479e7d5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; const Value *, unsigned &gt; TargetTransformInfo::getPredicatedAddrSpace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getPredictableBranchThreshold {#a99b320fd35acaf648a0a7826a0bdd777}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability TargetTransformInfo::getPredictableBranchThreshold ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If a branch or a select condition is skewed in one direction by more than this factor, it is very likely to be predicted correctly.</p>

<p>Declaration at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp/#a8e2625c3d933e9755aa91dbbaadd5eb5">PredictableBranchThreshold</a>.</p>

</div>
</div>

### getPreferredTailFoldingStyle {#a579a550a75fcdd6ebdb773fb2efd10de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TailFoldingStyle TargetTransformInfo::getPreferredTailFoldingStyle (bool IVUpdateMayOverflow=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Query the target what the preferred style of tail folding is.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">IVUpdateMayOverflow</td>
<td class="doxyParamItemDescription"><p>Tells whether it is known if the IV update may (or will never) overflow for the suggested VF/UF in the given loop. Targets can use this information to select a more optimal tail folding style. The value conservatively defaults to true, such that no assumptions are made on overflow.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 660 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getUnrollingPreferences {#a25f5cd1eed2a2102d7a012dbc5c08e1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetTransformInfo::getUnrollingPreferences (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences">UnrollingPreferences</a> &amp; UP, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get target-customized preferences for the generic loop unrolling transformation.</p>


<p>The caller will initialize UP with the current target-independent defaults.</p>


<p>Declaration at line 635 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### hasBranchDivergence {#a233996b13b5fa2774af23282d8870204}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::hasBranchDivergence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if branch divergence exists.</p>


<p>Branch divergence has a significantly negative impact on GPU performance when threads in the same wavefront take different paths due to conditional branches.</p>


<p>If <span class="doxyComputerOutput">F</span> is passed, provides a context function. If <span class="doxyComputerOutput">F</span> is known to only execute in a single threaded environment, the target may choose to skip uniformity analysis and assume all values are uniform.</p>


<p>Declaration at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### instCombineIntrinsic {#a2c34992cf5a6125fc637fbde99b88890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Instruction * &gt; TargetTransformInfo::instCombineIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/instcombiner">InstCombiner</a> &amp; IC, <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; II)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Targets can implement their own combinations for target-specific intrinsics.</p>


<p>This function will be called from the InstCombine pass every time a target-specific intrinsic is encountered.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>std::nullopt to not do anything target specific or a value that will be returned from the <a href="/web-llvm/docs/api/classes/llvm/instcombiner">InstCombiner</a>. It is possible to return null and stop further processing of the intrinsic by returning nullptr.</p></dd>
</dl>


<p>Declaration at line 692 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>

</div>
</div>

### isAlwaysUniform {#a1b21625ceb4a9d9eb225fa18cbf951de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetTransformInfo::isAlwaysUniform (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isHardwareLoopProfitable {#aaae1d7de61213a91194e93174081ab4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isHardwareLoopProfitable (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * LibInfo, <a href="/web-llvm/docs/api/structs/llvm/hardwareloopinfo">HardwareLoopInfo</a> &amp; HWLoopInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Query the target whether it would be profitable to convert the given loop into a hardware loop.</p>

<p>Declaration at line 641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLoweredToCall {#aa8b08fb48c8c58e63aa231a1099475d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLoweredToCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether calls to a function lower to actual program function calls.</p>


<p>The idea is to test whether the program is likely to require a 'call' instruction or equivalent in order to call the given function.</p>


<p>FIXME: It's not clear that this is a good or useful query API. Client's should probably move to simpler cost metrics using the above. Alternatively, we could split the cost interface into distinct code-size and execution-speed costs. This would allow modelling the core of this query more accurately as a call is a single small instruction, but incurs significant execution cost.</p>


<p>Declaration at line 520 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### isNoopAddrSpaceCast {#a50c845c07da9fd93a05ec29509486166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isNoopAddrSpaceCast (unsigned FromAS, unsigned ToAS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isSingleThreaded {#a3ba50f0bbbe7b4ae53a66e70c614cce2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isSingleThreaded ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isSourceOfDivergence {#a787ddce53dcb1b93b5c173dbbba4d3f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isSourceOfDivergence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns whether V is a source of divergence.</p>


<p>This function provides the target-dependent information for the target-independent UniformityAnalysis.</p>


<p>Declaration at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

### isValidAddrSpaceCast {#ad61de27a7641e7ce57bc6e3fdc8cd8d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetTransformInfo::isValidAddrSpaceCast (unsigned FromAS, unsigned ToAS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Query the target whether the specified address space cast from FromAS to ToAS is valid.</p>

<p>Declaration at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### preferPredicateOverEpilogue {#ae953310cea2ff4ae78d8fcf9269f9259}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::preferPredicateOverEpilogue (<a href="/web-llvm/docs/api/structs/llvm/tailfoldinginfo">TailFoldingInfo</a> * TFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Query the target whether it would be prefered to create a predicated vector loop, which can avoid the need to emit a scalar epilogue loop.</p>

<p>Declaration at line 651 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### rewriteIntrinsicWithAddressSpace {#a88bd45e10d1f1069da1b4d216d0f5f73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * TargetTransformInfo::rewriteIntrinsicWithAddressSpace (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * II, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OldV, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rewrite intrinsic call <span class="doxyComputerOutput">II</span> such that <span class="doxyComputerOutput">OldV</span> will be replaced with <span class="doxyComputerOutput">NewV</span>, which has a different address space.</p>


<p>This should happen for every operand index that collectFlatAddressOperands returned for the intrinsic.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>nullptr if the intrinsic was not handled. Otherwise, returns the new value (which may be the original <span class="doxyComputerOutput">II</span> with modified operands).</p></dd>
</dl>


<p>Declaration at line 505 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>

</div>
</div>

### simplifyDemandedUseBitsIntrinsic {#ac17fdac44c73248d9e36df4fd8d93b28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Value * &gt; TargetTransformInfo::simplifyDemandedUseBitsIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/instcombiner">InstCombiner</a> &amp; IC, <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; II, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> DemandedMask, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, bool &amp; KnownBitsComputed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Can be used to implement target-specific instruction combining.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a2c34992cf5a6125fc637fbde99b88890">instCombineIntrinsic</a></p></dd>
</dl>


<p>Declaration at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>

</div>
</div>

### simplifyDemandedVectorEltsIntrinsic {#a3c63492d1e619b740c6e6d123efeb4f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Value * &gt; TargetTransformInfo::simplifyDemandedVectorEltsIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/instcombiner">InstCombiner</a> &amp; IC, <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; II, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> DemandedElts, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; UndefElts, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; UndefElts2, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; UndefElts3, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, unsigned, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;)&gt; SimplifyAndSetOp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Can be used to implement target-specific instruction combining.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a2c34992cf5a6125fc637fbde99b88890">instCombineIntrinsic</a></p></dd>
</dl>


<p>Declaration at line 701 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>

</div>
</div>

### TargetCostConstants {#ac44f6b9fdbb5f9cc199f8329cb0b272c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TargetTransformInfo::TargetCostConstants </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Underlying constants for 'cost' values in this interface.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCC_Free<a id="ac44f6b9fdbb5f9cc199f8329cb0b272ca89f768b1267e3083b4eb05b4ab77e717"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a> to fold away in lowering (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCC_Basic<a id="ac44f6b9fdbb5f9cc199f8329cb0b272cae46c9eecc49bd2dc253c607e78a0fb86"></a></td>
<td class="doxyEnumItemDescription">The cost of a typical 'add' instruction (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCC_Expensive<a id="ac44f6b9fdbb5f9cc199f8329cb0b272ca022565d444ccf496c0414bccefbcd9c8"></a></td>
<td class="doxyEnumItemDescription">The cost of a 'div' instruction on x86 (= 4)</td>
</tr>

</table>
</dd>
</dl>


<p>Many APIs in this interface return a cost. This enum defines the fundamental values that should be used to interpret (and produce) those costs. The costs are returned as an int rather than a member of this enumeration because it is expected that the cost of one IR instruction may have a multiplicative factor to it or otherwise won't fit directly into the enum. Moreover, it is common to sum or average costs which works better as simple integral values. Thus this enum only provides constants. Also note that the returned costs are signed integers to make it natural to add, subtract, and test with zero (a common boundary condition). It is not expected that 2^32 is a realistic cost to be modeling at any point.</p>


<p>Note that these costs should usually reflect the intersection of code-size cost and execution cost. A free instruction is typically one that folds into another instruction. For example, reg-to-reg moves can often be skipped by renaming the registers in the CPU, but they still are encoded and thus wouldn't be considered 'free' here.</p>


<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

### TargetCostKind {#a706f223f760b55668fbae74202b816bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TargetTransformInfo::TargetCostKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The kind of cost model.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCK_RecipThroughput<a id="a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b"></a></td>
<td class="doxyEnumItemDescription">Reciprocal throughput</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCK_Latency<a id="a706f223f760b55668fbae74202b816bba81b2c6f1f1e13e4a575e6d1c8b29b6e1"></a></td>
<td class="doxyEnumItemDescription">The latency of instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCK_CodeSize<a id="a706f223f760b55668fbae74202b816bba737cfc93e5a2ff961677d57186167e7c"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> code size</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCK_SizeAndLatency<a id="a706f223f760b55668fbae74202b816bba7f80055e1969cb850739546467460ad8"></a></td>
<td class="doxyEnumItemDescription">The weighted sum of size and latency</td>
</tr>

</table>
</dd>
</dl>


<p>There are several different cost models that can be customized by the target. The normalization of each cost model may be target specific. e.g. TCK_SizeAndLatency should be comparable to target thresholds such as those derived from <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#a74a33138b76ebc2cae1b3cf65411a9e6">MCSchedModel::LoopMicroOpBufferSize</a> etc.</p>


<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Scalar Target Information

### AddressingModeKind {#ad88649498463e1fe02380ad98886ce43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TargetTransformInfo::AddressingModeKind </td>
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
<td class="doxyEnumItemName">AMK_PreIndexed<a id="ad88649498463e1fe02380ad98886ce43a7cb26b7792c751612e634c36dce16f9a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMK_PostIndexed<a id="ad88649498463e1fe02380ad98886ce43a0e72bd25d3608a66eac09e4cfbb7c658"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMK_None<a id="ad88649498463e1fe02380ad98886ce43afcb500aacd74955fc04edc890f5e5d1a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 780 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

### allowsMisalignedMemoryAccesses {#a9e737ae000f542eba6ebc679637144d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::allowsMisalignedMemoryAccesses (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, unsigned BitWidth, unsigned AddressSpace=0, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment=<a href="/web-llvm/docs/api/structs/llvm/align">Align</a>(1), unsigned * Fast=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the target supports unaligned memory accesses.</p>

<p>Declaration at line 1028 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 685 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>.</p>

</div>
</div>

### canMacroFuseCmp {#ad5711c8e7ef4d1848c44e839242316c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::canMacroFuseCmp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target can fuse a compare and branch.</p>


<p>Loop-strength-reduction (LSR) uses that knowledge to adjust its cost calculation for the instructions in a loop.</p>


<p>Declaration at line 772 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### canSaveCmp {#a884326e08a0f3d72b4f5006cf31eb76f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::canSaveCmp (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> ** BI, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * LibInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target can save a compare for loop count, for example hardware loop saves a compare.</p>

<p>Declaration at line 776 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### enableAggressiveInterleaving {#a12f25864d2ad4955cb285d871a36345b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::enableAggressiveInterleaving (bool LoopHasReductions)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Don't restrict interleaved unrolling to small loops.</p>

<p>Declaration at line 958 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### enableInterleavedAccessVectorization {#ac501bf52c07df51c9e1242117cfc7b2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::enableInterleavedAccessVectorization ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable matching of interleaved access groups.</p>

<p>Declaration at line 1011 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### enableMaskedInterleavedAccessVectorization {#a6b0734de892207738014317d233c72ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::enableMaskedInterleavedAccessVectorization ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable matching of interleaved access groups that contain predicated accesses or gaps and therefore vectorized using masked vector loads/stores.</p>

<p>Declaration at line 1016 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### enableMemCmpExpansion {#a24629c2792a37162cf0ef4b1c38ba00c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo::MemCmpExpansionOptions TargetTransformInfo::enableMemCmpExpansion (bool OptSize, bool IsZeroCmp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 998 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### enableOrderedReductions {#a3e034d813ec5b7818252ac121d20a5aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::enableOrderedReductions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if we should be enabling ordered reductions for the target.</p>

<p>Declaration at line 843 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### enableSelectOptimize {#a72110d5a1a43e21651a36bd96cfdec98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::enableSelectOptimize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Should the Select Optimization pass be enabled and ran.</p>

<p>Declaration at line 1002 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### forceScalarizeMaskedGather {#a661bd4bd069ee48ef7bf8a7892790468}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::forceScalarizeMaskedGather (<a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * Type, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target forces scalarizing of llvm.masked.gather intrinsics.</p>

<p>Declaration at line 810 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### forceScalarizeMaskedScatter {#aebda4a819a6130c6c0f37a8b05dfac67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::forceScalarizeMaskedScatter (<a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * Type, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target forces scalarizing of llvm.masked.scatter intrinsics.</p>

<p>Declaration at line 813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getFPOpCost {#ad3b0e7df7704fa34e356e1178374b49e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getFPOpCost (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the expected cost of supporting the floating point operation of the specified type.</p>

<p>Declaration at line 1055 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getIntImmCodeSizeCost {#aa8771f57e56c0bc0e9ace92ede634839}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getIntImmCodeSizeCost (unsigned Opc, unsigned Idx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the expected cost for the given integer when optimising for size.</p>


<p>This is different than the other integer immediate cost functions in that it is subtarget agnostic. This is useful when you e.g. target one ISA such as Aarch32 but smaller encodings could be possible with another such as Thumb. This return value is used as a penalty when the total costs for a constant is calculated (the bigger the cost, the more beneficial constant hoisting is).</p>


<p>Declaration at line 1080 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 718 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getIntImmCost {#a8f708e28c4cf4fcdbbe363849b779a00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getIntImmCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="#a706f223f760b55668fbae74202b816bb">TargetCostKind</a> CostKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the expected cost of materializing for the given integer immediate of the specified type.</p>

<p>Declaration at line 1059 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 728 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>.</p>

</div>
</div>

### getIntImmCostInst {#a6c5798a479ce88e66e1b53d70d678332}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getIntImmCostInst (unsigned Opc, unsigned Idx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="#a706f223f760b55668fbae74202b816bb">TargetCostKind</a> CostKind, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the expected cost of materialization for the given integer immediate of the specified type for a given instruction.</p>


<p>The cost can be zero if the immediate can be folded into the specified instruction.</p>


<p>Declaration at line 1065 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 735 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>.</p>

</div>
</div>

### getIntImmCostIntrin {#a6abe636878bffb348ed313016ab1c21b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getIntImmCostIntrin (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IID, unsigned Idx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="#a706f223f760b55668fbae74202b816bb">TargetCostKind</a> CostKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1069 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 745 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>.</p>

</div>
</div>

### getOperandsScalarizationOverhead {#a296acd14b143ce1e1b0db86f4c221662}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getOperandsScalarizationOverhead (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Args, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Tys, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Estimate the overhead of scalarizing an instructions unique non-constant operands.</p>


<p>The (potentially vector) types to use for each of argument are passes via Tys.</p>


<p>Declaration at line 942 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>.</p>

</div>
</div>

### getPopcntSupport {#a6480799b120b617b9b34f1313afe6661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo::PopcntSupportKind TargetTransformInfo::getPopcntSupport (unsigned IntTyWidthInBit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return hardware support for population count.</p>

<p>Declaration at line 1034 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getPreferredAddressingMode {#aa89a5a037e90eef4edcffea07a423748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TTI::AddressingModeKind TargetTransformInfo::getPreferredAddressingMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the preferred addressing mode LSR should make efforts to generate.</p>

<p>Declaration at line 787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getRegUsageForType {#a5a6989eb41033f67be080858c27d840a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getRegUsageForType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the estimated number of registers required to represent <span class="doxyComputerOutput">Ty</span>.</p>

<p>Declaration at line 894 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getScalarizationOverhead {#ac4e134d18ed279fbb84c667a629fd047}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getScalarizationOverhead (<a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, bool Insert, bool Extract, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Estimate the overhead of scalarizing an instruction.</p>


<p>Insert and Extract are set if the demanded result elements need to be inserted and/or extracted from vectors. The involved values may be passed in VL if Insert is true.</p>


<p>Declaration at line 932 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>.</p>

</div>
</div>

### getScalingFactorCost {#ae36d969fb1c0d73ddfbadec73164ee9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getScalingFactorCost (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * BaseGV, <a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a> BaseOffset, bool HasBaseReg, int64_t Scale, unsigned AddrSpace=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the cost of the scaling factor used in the addressing mode represented by AM for this target, for a load/store of the specified type.</p>


<p>If the AM is supported, the return value must be &gt;= 0. If the AM is not supported, it returns a negative value. TODO: Handle pre/postinc as well.</p>


<p>Declaration at line 868 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### hasDivRemOp {#ac31bf22f119c5a99c36646d8e0eb2c0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::hasDivRemOp (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DataType, bool IsSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target has a unified operation to calculate division and remainder.</p>


<p>If so, the additional implicit multiplication and subtraction required to calculate a remainder from division are free. This can enable more aggressive transformations for division and remainder than would typically be allowed using throughput or size cost models.</p>


<p>Declaration at line 850 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### hasVolatileVariant {#ab33e1370498d06e0760c2861ff25e43a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::hasVolatileVariant (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, unsigned AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the given instruction (assumed to be a memory access instruction) has a volatile variant.</p>


<p>If that's the case then we can avoid addrspacecast to generic AS for volatile loads/stores. Default implementation returns false, which prevents address space inference for volatile loads/stores.</p>


<p>Declaration at line 857 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 551 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### haveFastSqrt {#aef998bb15ea045fc769232b62ad0d968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::haveFastSqrt (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the hardware has a fast square-root instruction.</p>

<p>Declaration at line 1037 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 699 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isExpensiveToSpeculativelyExecute {#a30646d63c1f1ca132d37dff17cf5daae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isExpensiveToSpeculativelyExecute (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the cost of the instruction is too high to speculatively execute and should be kept behind a branch.</p>


<p>This normally just wraps around a <a href="#ac77dbedcfd916a5c9b58e753b2678a98">getInstructionCost()</a> call, but some targets might report a low TCK_SizeAndLatency value that is incompatible with the fixed TCC_Expensive value. NOTE: This assumes the instruction passes <a href="/web-llvm/docs/api/namespaces/llvm/#a8601ff0320b6e29a13a2194200853425">isSafeToSpeculativelyExecute()</a>.</p>


<p>Declaration at line 1045 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 703 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### isFCmpOrdCheaperThanFCmpZero {#a199e3382d45514816f88cb65310decb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isFCmpOrdCheaperThanFCmpZero (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if it is faster to check if a floating-point value is NaN (or not-NaN) versus a comparison against a constant FP zero value.</p>


<p>Targets should override this if materializing a 0.0 for comparison is generally as cheap as checking for ordered/unordered.</p>


<p>Declaration at line 1051 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isFPVectorizationPotentiallyUnsafe {#ab75d51988243f8ea9086b110401f8758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isFPVectorizationPotentiallyUnsafe ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicate that it is potentially unsafe to automatically vectorize floating-point operations because the semantics of vector and scalar floating-point semantics may differ.</p>


<p>For example, <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> NEON v7 SIMD math does not support IEEE-754 denormal numbers, while depending on the platform, scalar floating-point math does. This applies to floating-point math operations and calls, not memory operations, shuffles, or casts.</p>


<p>Declaration at line 1025 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 680 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalAddImmediate {#a7f5c32f4b5bd13b1279016cd9a6db37b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalAddImmediate (int64_t Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified immediate is legal add immediate, that is the target has add instructions which can add a register with the immediate without having to materialize the immediate into a register.</p>

<p>Declaration at line 724 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalAddressingMode {#a6250994dada01a076d3de7e659506234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalAddressingMode (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * BaseGV, int64_t BaseOffset, bool HasBaseReg, int64_t Scale, unsigned AddrSpace=0, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr, int64_t ScalableOffset=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the addressing mode represented by AM is legal for this target, for a load/store of the specified type.</p>


<p>The type may be VoidTy, in which case only return true if the addressing mode is legal for a load/store of any legal type. If target returns true in <a href="#a4746d964f754f53ce75d48a418196674">LSRWithInstrQueries()</a>, I may be valid.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ScalableOffset</td>
<td class="doxyParamItemDescription"><p>represents a quantity of bytes multiplied by vscale, an invariant value known only at runtime. Most targets should not accept a scalable offset.</p></td>
</tr>
</table>
</dd>
</dl>

<p>TODO: Handle pre/postinc as well.</p>


<p>Declaration at line 748 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### isLegalAddScalableImmediate {#ac23902680c153a91d17e952e2623712c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalAddScalableImmediate (int64_t Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if adding the specified scalable immediate is legal, that is the target has add instructions which can add a register with the immediate (multiplied by vscale) without having to materialize the immediate into a register.</p>

<p>Declaration at line 730 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalAltInstr {#aae67acb89326f200683e3d0b872a5329}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalAltInstr (<a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * VecTy, unsigned Opcode0, unsigned Opcode1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; OpcodeMask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this is an alternating opcode pattern that can be lowered to a single instruction on the target.</p>


<p>In <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> this is for the addsub instruction which corrsponds to a Shuffle + Fadd + FSub pattern in IR. This function expectes two opcodes: <span class="doxyComputerOutput">Opcode1</span> and <span class="doxyComputerOutput">Opcode2</span> being selected by <span class="doxyComputerOutput">OpcodeMask</span>. The mask contains one bit per lane and is a <span class="doxyComputerOutput">0</span> when <span class="doxyComputerOutput">Opcode0</span> is selected and <span class="doxyComputerOutput">1</span> when Opcode1 is selected. <span class="doxyComputerOutput">VecTy</span> is the vector type of the instruction to be generated.</p>


<p>Declaration at line 839 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalBroadcastLoad {#a5a6b14ee0f0d259ea09d847875be536f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalBroadcastLoad (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementTy, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> NumElements)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\Returns true if the target supports broadcasting a load to a vector of type &lt;NumElements x ElementTy&gt;.</p>

<p>Declaration at line 802 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalICmpImmediate {#a78ff38d597ee5f9da28bb64c812520d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalICmpImmediate (int64_t Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified immediate is legal icmp immediate, that is the target has icmp instructions which can compare a register against the immediate without having to materialize the immediate into a register.</p>

<p>Declaration at line 736 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalInterleavedAccessType {#a59d32a2424444b535f76e4fb19791de8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalInterleavedAccessType (<a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * VTy, unsigned Factor, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, unsigned AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true is the target supports interleaved access for the given vector type <span class="doxyComputerOutput">VTy</span>, interleave factor <span class="doxyComputerOutput">Factor</span>, alignment <span class="doxyComputerOutput">Alignment</span> and address space <span class="doxyComputerOutput">AddrSpace</span>.</p>

<p>Declaration at line 826 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalMaskedCompressStore {#ab4ca31dadd4ea1a5510f43fcd2910475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalMaskedCompressStore (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DataType, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target supports masked compress store.</p>

<p>Declaration at line 816 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalMaskedExpandLoad {#a1f5ac2fb320afeb13101f5331cffa693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalMaskedExpandLoad (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DataType, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target supports masked expand load.</p>

<p>Declaration at line 818 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalMaskedGather {#a33ac7704be5bd5455f78caf0b5371012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalMaskedGather (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DataType, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target supports masked gather.</p>

<p>Declaration at line 807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalMaskedLoad {#aff5a70644f05b7731348861016ff2af1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalMaskedLoad (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DataType, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target supports masked load.</p>

<p>Declaration at line 793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalMaskedScatter {#a0a973aabc3b5429e5e05beee35892de0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalMaskedScatter (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DataType, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target supports masked scatter.</p>

<p>Declaration at line 805 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalMaskedStore {#ab9bcc7733985bba3ab58e5c2abbc129e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalMaskedStore (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DataType, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target supports masked store.</p>

<p>Declaration at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalMaskedVectorHistogram {#acb5014d79db9e7af67548e98a2680e7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalMaskedVectorHistogram (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * AddrType, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DataType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 830 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalNTLoad {#a7bdad414050f44dd51fe2c193b7992b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalNTLoad (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DataType, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target supports nontemporal load.</p>

<p>Declaration at line 798 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalNTStore {#a923b761c973df44658c12ab18b29365c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalNTStore (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DataType, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target supports nontemporal store.</p>

<p>Declaration at line 796 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalStridedLoadStore {#a6c88ba0590be06436d0183b1ae819924}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalStridedLoadStore (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DataType, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target supports strided load.</p>

<p>Declaration at line 821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLSRCostLess {#a1d57a8095a918e8a7ebe31f964c16bbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLSRCostLess (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/lsrcost">TargetTransformInfo::LSRCost</a> &amp; C1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/lsrcost">TargetTransformInfo::LSRCost</a> &amp; C2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if LSR cost of C1 is lower than C2.</p>

<p>Declaration at line 754 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isNumRegsMajorCostOfLSR {#acb09869158c4446f417427d102199632}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isNumRegsMajorCostOfLSR ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if LSR major cost is number of registers.</p>


<p>Targets which implement their own isLSRCostLess and unset number of registers as major cost should return false, otherwise return true.</p>


<p>Declaration at line 760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isProfitableLSRChainElement {#a2c5b11c76ffc12a4dde038d77dc4d5ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isProfitableLSRChainElement (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if LSR should not optimize a chain that includes <span class="doxyComputerOutput">I</span>.</p></dd>
</dl>


<p>Declaration at line 767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### isProfitableToHoist {#aafcbf4e3010950dd8ea0be1c4b0d3281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isProfitableToHoist (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if it is profitable to hoist instruction in the then/else to before if.</p>

<p>Declaration at line 886 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### isTargetIntrinsicTriviallyScalarizable {#a885d52cea242659c8a9380877cdfc33e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isTargetIntrinsicTriviallyScalarizable (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 911 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isTargetIntrinsicWithOverloadTypeAtArg {#aec1193377fa34888aa32de5f4bafb4fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isTargetIntrinsicWithOverloadTypeAtArg (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> ID, int OpdIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identifies if the vector form of the intrinsic is overloaded on the type of the operand at index <span class="doxyComputerOutput">OpdIdx</span>, or on the return type if <span class="doxyComputerOutput">OpdIdx</span> is -1.</p>

<p>Declaration at line 920 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isTargetIntrinsicWithScalarOpAtArg {#ac2e6aa364f319202922a886a9d6d37f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isTargetIntrinsicWithScalarOpAtArg (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> ID, unsigned ScalarOpdIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identifies if the vector form of the intrinsic has a scalar operand.</p>

<p>Declaration at line 914 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isTargetIntrinsicWithStructReturnOverloadAtField {#a82f6ed49c26d8e0213dcf8d1dcff998c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isTargetIntrinsicWithStructReturnOverloadAtField (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> ID, int RetIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identifies if the vector form of the intrinsic that returns a struct is overloaded at the struct element index <span class="doxyComputerOutput">RetIdx</span>.</p>

<p>Declaration at line 925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isTruncateFree {#ae3e55cf13c60a8b90145f1411367b975}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isTruncateFree (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty1, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if it's free to truncate a value of type Ty1 to type Ty2.</p>


<p>e.g. On x86 it's free to truncate a i32 value in register EAX to i16 by referencing its sub-register AX.</p>


<p>Declaration at line 882 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isTypeLegal {#a7a84209b8495d8fd3d2799eb01f1ab2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isTypeLegal (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this type is legal.</p>

<p>Declaration at line 891 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### LSRWithInstrQueries {#a4746d964f754f53ce75d48a418196674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::LSRWithInstrQueries ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the loop strength reduce pass should make Instruction* based <a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068">TTI</a> queries to <a href="#a6250994dada01a076d3de7e659506234">isLegalAddressingMode()</a>.</p>


<p>This is needed on <a href="/web-llvm/docs/api/namespaces/llvm/systemz">SystemZ</a>, where e.g. a memcpy can only have a 12 bit unsigned immediate offset and no index register.</p>


<p>Declaration at line 877 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### PopcntSupportKind {#aa4c17e89b1ef061ed69f42b7cee93dbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TargetTransformInfo::PopcntSupportKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flags indicating the kind of support for population count.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PSK_Software<a id="aa4c17e89b1ef061ed69f42b7cee93dbea0ce99a3a4fe2b7f2771a7b288a99ed2c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PSK_SlowHardware<a id="aa4c17e89b1ef061ed69f42b7cee93dbea01deb9d0bc6399399b0d8377bd09201d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PSK_FastHardware<a id="aa4c17e89b1ef061ed69f42b7cee93dbeac71465fd61f1ba8aa2c7c397722b5e05"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>Compared to the SW implementation, HW support is supposed to significantly boost the performance when the population is dense, and it may or may not degrade performance if the population is sparse. A HW support is considered as "Fast" if it can outperform, or is on a par with, SW implementation when the population is sparse; otherwise, it is considered as "Slow".</p>


<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

### prefersVectorizedAddressing {#a215ea3605f88c5b21ffbdf76a72a8554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::prefersVectorizedAddressing ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if target doesn't mind addresses in vectors.</p>

<p>Declaration at line 860 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### preferToKeepConstantsAttached {#a954be846c618b16d1e51108cf99168df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::preferToKeepConstantsAttached (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>It can be advantageous to detach complex constants from their uses to make their generation cheaper.</p>


<p>This hook allows targets to report when such transformations might negatively effect the code generation of the underlying operation. The motivating example is divides whereby hoisting constants prevents the code generator's ability to transform them into combinations of simpler operations.</p>


<p>Declaration at line 1089 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 754 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### shouldBuildLookupTables {#a0d5b47e1f017620a784b726852915d58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::shouldBuildLookupTables ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if switches should be turned into lookup tables for the target.</p>

<p>Declaration at line 898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### shouldBuildLookupTablesForConstant {#a265e334c170d96e5cbcf8b420db520d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::shouldBuildLookupTablesForConstant (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if switches should be turned into lookup tables containing this constant value for the target.</p>

<p>Declaration at line 902 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### shouldBuildRelLookupTables {#abcb1dfc8333359b25dda0d8cbef24e4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::shouldBuildRelLookupTables ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if lookup tables should be turned into relative lookup tables.</p>

<p>Declaration at line 905 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### shouldDropLSRSolutionIfLessProfitable {#a1c7e1bf2359f86a03f8c9cba2747ee2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::shouldDropLSRSolutionIfLessProfitable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if LSR should drop a found solution if it's calculated to be less profitable than the baseline.</p>

<p>Declaration at line 764 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### shouldTreatInstructionLikeSelect {#a50270e81abbcbbfe470af5ca01d54e75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::shouldTreatInstructionLikeSelect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Should the Select Optimization pass treat the given instruction like a select, potentially converting it to a conditional branch.</p>


<p>This can include select-like instructions like or(zext(c), x) that can be converted to selects.</p>


<p>Declaration at line 1008 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 667 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### supportsEfficientVectorElementLoadStore {#a1af0805a1dd7afabb0aa6cc1832b5011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::supportsEfficientVectorElementLoadStore ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If target has efficient vector element load/store instructions, it can return true here so that insertion/extraction costs are not added to the scalarization cost of a load/store.</p>

<p>Declaration at line 949 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### supportsTailCallFor {#a2c143ebdce9475bb57428828fe848e3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::supportsTailCallFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If target supports tail call on <span class="doxyComputerOutput">CB</span>.</p>

<p>Declaration at line 955 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### supportsTailCalls {#ad4d10c3084307035a3ae29cc2f420440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::supportsTailCalls ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the target supports tail calls.</p>

<p>Declaration at line 952 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### useAA {#a98deb6721fb0ac45c41f71b800700596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::useAA ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 888 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### useColdCCForColdCall {#ad30e432e7796aa46c87440cb54de2243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::useColdCCForColdCall (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the input function which is cold at all call sites, should use coldcc calling convention.</p>

<p>Declaration at line 909 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Vector Target Information

### areInlineCompatible {#ad2e1f19379514bb06cdcedb2bae8748d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::areInlineCompatible (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Callee)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the two functions have compatible attributes for inlining purposes.</p></dd>
</dl>


<p>Declaration at line 1676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1284 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### areTypesABICompatible {#a71773f01b77047575c95791e12f91246}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::areTypesABICompatible (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Callee, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp; Types)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the caller and callee agree on how <span class="doxyComputerOutput">Types</span> will be passed to or returned from the callee. to the callee.</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Types</td>
<td class="doxyParamItemDescription"><p>List of types to check.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1692 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1296 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### CacheLevel {#afbde4c30736df440ecdeee35a0608f6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::TargetTransformInfo::CacheLevel </td>
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

<p>The possible cache levels.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">L1D<a id="afbde4c30736df440ecdeee35a0608f6ba4ea39ed13dabbda09e2782f5529eb1ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">L2D<a id="afbde4c30736df440ecdeee35a0608f6baecc9f58d2b1c17e94659be202c01b55b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

### CastContextHint {#af84cce349a77262269fd3f6756f37a64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::TargetTransformInfo::CastContextHint : uint8_t</td>
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

<p>Represents a hint about the context in which a cast is used.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">None<a id="af84cce349a77262269fd3f6756f37a64a6adf97f83acf6453d4a6a4b1070f3754"></a></td>
<td class="doxyEnumItemDescription">The cast is not used with a load/store of any kind</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Normal<a id="af84cce349a77262269fd3f6756f37a64a960b44c579bc2f6818d2daaf9e4c16f0"></a></td>
<td class="doxyEnumItemDescription">The cast is used with a normal load/store</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Masked<a id="af84cce349a77262269fd3f6756f37a64a6864311f985d160ad4bd46a9fbe4a4d4"></a></td>
<td class="doxyEnumItemDescription">The cast is used with a masked load/store</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GatherScatter<a id="af84cce349a77262269fd3f6756f37a64afc2e3edeec59afcdc10f55205713f14b"></a></td>
<td class="doxyEnumItemDescription">The cast is used with a gather/scatter</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Interleave<a id="af84cce349a77262269fd3f6756f37a64ad392556b3674a98332cc2938ba0bfeb7"></a></td>
<td class="doxyEnumItemDescription">The cast is used with an interleaved load/store</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Reversed<a id="af84cce349a77262269fd3f6756f37a64a030aa94015bd11d183b897ddb541e4e3"></a></td>
<td class="doxyEnumItemDescription">The cast is used with a reversed load/store</td>
</tr>

</table>
</dd>
</dl>


<p>For zext/sext, the context of the cast is the operand, which must be a load of some kind. For trunc, the context is of the cast is the single user of the instruction, which must be a store of some kind.</p>


<p>This enum allows the vectorizer to give getCastInstrCost an idea of the type of cast it's dealing with, as not every cast is equal. For instance, the zext of a load may be free, but the zext of an interleaving load can be (very) expensive!</p>


<p>See <span class="doxyComputerOutput">getCastContextHint</span> to compute a <a href="#af84cce349a77262269fd3f6756f37a64">CastContextHint</a> from a cast Instruction*. Callers can use it if they don't need to override the context and just want it to be calculated from the instruction.</p>


<p>FIXME: This handles the types of load/store that the vectorizer can produce, which are the cases where the context instruction is most likely to be incorrect. There are other situations where that can happen too, which might be handled here but in the long run a more general solution of costing multiple instructions at the same times may be better.</p>


<p>Definition at line 1389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

### enableScalableVectorization {#ac912bf74dab55fe744b25c739e29d7b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::enableScalableVectorization ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true when scalable vectorization is preferred.</p></dd>
</dl>


<p>Declaration at line 1807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1420 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### enableWritePrefetching {#a4ec5838370bf4a0d0af43e443ee99325}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::enableWritePrefetching ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if prefetching should also be done for writes.</p></dd>
</dl>


<p>Declaration at line 1289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 858 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getAddressComputationCost {#a246f298958a4a730bf7d3a64440dd47b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getAddressComputationCost (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Ptr=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The cost of the address computation. For most targets this can be merged into the instruction indexing mode. Some targets might want to distinguish between address computation for memory operations on vector types and scalar types. Such targets should override this function. The 'SE' parameter holds pointer for the scalar evolution object which is used in order to get the Ptr step value in case of constant stride. The 'Ptr' parameter holds <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> of the access pointer.</p></dd>
</dl>


<p>Declaration at line 1628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1198 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### getAltInstrCost {#ac442c18de69f9270e02ee8e35113502c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getAltInstrCost (<a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * VecTy, unsigned Opcode0, unsigned Opcode1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; OpcodeMask, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind=<a href="#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">TTI::TCK_RecipThroughput</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the cost estimation for alternating opcode pattern that can be lowered to a single instruction on the target.</p>


<p>In <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> this is for the addsub instruction which corrsponds to a Shuffle + Fadd + FSub pattern in IR. This function expects two opcodes: <span class="doxyComputerOutput">Opcode1</span> and <span class="doxyComputerOutput">Opcode2</span> being selected by <span class="doxyComputerOutput">OpcodeMask</span>. The mask contains one bit per lane and is a <span class="doxyComputerOutput">0</span> when <span class="doxyComputerOutput">Opcode0</span> is selected and <span class="doxyComputerOutput">1</span> when Opcode1 is selected. <span class="doxyComputerOutput">VecTy</span> is the vector type of the instruction to be generated.</p>


<p>Declaration at line 1349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 967 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>.</p>

</div>
</div>

### getArithmeticInstrCost {#a713bb53f77454635f44dd95c53fc8684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getArithmeticInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind=<a href="#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">TTI::TCK_RecipThroughput</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/operandvalueinfo">TTI::OperandValueInfo</a> Opd1Info={<a href="#afa38851d75434d1476444ac93f94cb4ca9c0eecea29e9fa58e4dac7ee32b9b2ac">TTI::OK_AnyValue</a>, <a href="#a733fb237f3037c95ed59de6055b176c5a2bc39e3785b29fe7bc4af768842a2072">TTI::OP_None</a>}, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/operandvalueinfo">TTI::OperandValueInfo</a> Opd2Info={<a href="#afa38851d75434d1476444ac93f94cb4ca9c0eecea29e9fa58e4dac7ee32b9b2ac">TTI::OK_AnyValue</a>, <a href="#a733fb237f3037c95ed59de6055b176c5a2bc39e3785b29fe7bc4af768842a2072">TTI::OP_None</a>}, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Args={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLibInfo=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is an approximation of reciprocal throughput of a math/logic op.</p>


<p>A higher cost indicates less expected throughput. From Agner Fog's guides, reciprocal throughput is "the average number of
clock cycles per instruction when the instructions are not part of a
limiting dependency chain." Therefore, costs should be scaled to account for multiple execution units on the target that can process this type of instruction. For example, if there are 5 scalar integer units and 2 vector integer units that can calculate an 'add' in a single cycle, this model should indicate that the cost of the vector add instruction is 2.5 times the cost of the scalar add instruction. <span class="doxyComputerOutput">Args</span> is an optional argument which holds the instruction operands values so the <a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068">TTI</a> can analyze those values searching for special cases or optimizations based on those values. <span class="doxyComputerOutput">CxtI</span> is the optional original context instruction, if one exists, to provide even more information. <span class="doxyComputerOutput">TLibInfo</span> is used to search for platform specific vector library functions for instructions that might be converted to calls (e.g. frem).</p>


<p>Declaration at line 1334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 940 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#af67833027bb46ddb390684a6f0b75398">getCallInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a59632c5deb0423a518ad984bdd04d41f">llvm::VectorType::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a97cfbbed8869e3582142012a071a9052">llvm::TargetLibraryInfo::getLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#acee3b789f998e244c05ff9d65096178b">llvm::TargetLibraryInfo::getName</a> and <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#af2dc370c0f0b837f18b006c2d4b8b7cc">llvm::TargetLibraryInfo::isFunctionVectorizable</a>.</p>

</div>
</div>

### getArithmeticReductionCost {#a421ee26483edf3fd0cd1dca34513f45e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getArithmeticReductionCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * Ty, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> &gt; FMF, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind=<a href="#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">TTI::TCK_RecipThroughput</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate the cost of vector reduction intrinsics.</p>


<p>This is the cost of reducing the vector value of type <span class="doxyComputerOutput">Ty</span> to a scalar value using the operation denoted by <span class="doxyComputerOutput">Opcode</span>. The <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> parameter <span class="doxyComputerOutput">FMF</span> indicates what type of reduction we are performing:</p>


<ol class="doxyList" type="1">
<li>Tree-wise. This is the typical 'fast' reduction performed that involves successively splitting a vector into half and doing the operation on the pair of halves until you have a scalar value. For example: (v0, v1, v2, v3) ((v0+v2), (v1+v3), undef, undef) ((v0+v2+v1+v3), undef, undef, undef) This is the default behaviour for integer operations, whereas for floating point we only do this if <span class="doxyComputerOutput">FMF</span> indicates that reassociation is allowed.</li>
<li>Ordered. For a vector with N elements this involves performing N operations in lane order, starting with an initial scalar value, i.e. result = InitVal + v0 result = result + v1 result = result + v2 result = result + v3 This is only the case for FP operations and when reassociation is not allowed.</li>
</ol>

<p>Declaration at line 1580 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1215 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>.</p>

</div>
</div>

### getAtomicMemIntrinsicMaxElementSize {#a422b020a05731c432411d574a7728af5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getAtomicMemIntrinsicMaxElementSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The maximum element size, in bytes, for an element unordered-atomic memory intrinsic.</p></dd>
</dl>


<p>Declaration at line 1647 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1256 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getCacheAssociativity {#a7b210e7ba1c2c222ab9d01202a55f723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; TargetTransformInfo::getCacheAssociativity (<a href="#afbde4c30736df440ecdeee35a0608f6b">CacheLevel</a> Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The associativity of the cache level, if available.</p></dd>
</dl>


<p>Declaration at line 1252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 834 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getCacheLineSize {#a9d04cbecfee76b1c4a5ea83aa6bb113c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getCacheLineSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The size of a cache line in bytes.</p></dd>
</dl>


<p>Declaration at line 1236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 823 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp/#af6ab0b42b53810d4456cb51537349222">CacheLineSize</a>.</p>

</div>
</div>

### getCacheSize {#ac0d6473c3ac48c1d2d9436408e6b9e82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; TargetTransformInfo::getCacheSize (<a href="#afbde4c30736df440ecdeee35a0608f6b">CacheLevel</a> Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The size of the cache level in bytes, if available.</p></dd>
</dl>


<p>Declaration at line 1249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 829 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getCallInstrCost {#af67833027bb46ddb390684a6f0b75398}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getCallInstrCost (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Tys, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind=<a href="#a706f223f760b55668fbae74202b816bba7f80055e1969cb850739546467460ad8">TTI::TCK_SizeAndLatency</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The cost of Call instructions.</p></dd>
</dl>


<p>Declaration at line 1613 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1185 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a713bb53f77454635f44dd95c53fc8684">getArithmeticInstrCost</a>.</p>

</div>
</div>

### getCastContextHint {#a096c8b641174dc0e486006926c5202cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TTI::CastContextHint TargetTransformInfo::getCastContextHint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Calculates a <a href="#af84cce349a77262269fd3f6756f37a64">CastContextHint</a> from <span class="doxyComputerOutput">I</span>.</p>


<p>This should be used by callers of getCastInstrCost if they wish to determine the context from some instruction.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the <a href="#af84cce349a77262269fd3f6756f37a64">CastContextHint</a> for ZExt/SExt/Trunc, None if <span class="doxyComputerOutput">I</span> is nullptr, or if it's another type of cast.</p></dd>
</dl>


<p>Declaration at line 1403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 996 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#af84cce349a77262269fd3f6756f37a64afc2e3edeec59afcdc10f55205713f14b">GatherScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#af84cce349a77262269fd3f6756f37a64a6864311f985d160ad4bd46a9fbe4a4d4">Masked</a>, <a href="#af84cce349a77262269fd3f6756f37a64a6adf97f83acf6453d4a6a4b1070f3754">None</a> and <a href="#af84cce349a77262269fd3f6756f37a64a960b44c579bc2f6818d2daaf9e4c16f0">Normal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#aaa14b4fc802d9aa388b369deb1a1ef60">chainToBasePointerCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a95442a0e0980e874df3bf77d6c8dee44">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getInstructionCost</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a50016fb8102156a9c168cfd348b3509a">llvm::AArch64TargetLowering::optimizeExtendOrTruncateConversion</a>.</p>

</div>
</div>

### getCastInstrCost {#a425eab58717b81784602a0b169dd9ff8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getCastInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Dst, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Src, <a href="#af84cce349a77262269fd3f6756f37a64">TTI::CastContextHint</a> CCH, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind=<a href="#a706f223f760b55668fbae74202b816bba7f80055e1969cb850739546467460ad8">TTI::TCK_SizeAndLatency</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expected cost of cast instructions, such as bitcast, trunc, zext, etc. If there is an existing instruction that holds Opcode, it may be passed in the 'I' parameter.</p></dd>
</dl>


<p>Declaration at line 1409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1039 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getCFInstrCost {#af7b131843b386c6e3cc39bd6f8141357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getCFInstrCost (unsigned Opcode, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind=<a href="#a706f223f760b55668fbae74202b816bba7f80055e1969cb850739546467460ad8">TTI::TCK_SizeAndLatency</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expected cost of control-flow related instructions such as Phi, Ret, Br, Switch.</p></dd>
</dl>


<p>Declaration at line 1423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1058 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getCmpSelInstrCost {#a22d6c699561d5ad3862a043fde6b797d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getCmpSelInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ValTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * CondTy, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> VecPred, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind=<a href="#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">TTI::TCK_RecipThroughput</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/operandvalueinfo">OperandValueInfo</a> Op1Info={<a href="#afa38851d75434d1476444ac93f94cb4ca9c0eecea29e9fa58e4dac7ee32b9b2ac">OK_AnyValue</a>, <a href="#a733fb237f3037c95ed59de6055b176c5a2bc39e3785b29fe7bc4af768842a2072">OP_None</a>}, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/operandvalueinfo">OperandValueInfo</a> Op2Info={<a href="#afa38851d75434d1476444ac93f94cb4ca9c0eecea29e9fa58e4dac7ee32b9b2ac">OK_AnyValue</a>, <a href="#a733fb237f3037c95ed59de6055b176c5a2bc39e3785b29fe7bc4af768842a2072">OP_None</a>}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expected cost of compare and select instructions. If there is an existing instruction that holds Opcode, it may be passed in the 'I' parameter. The <span class="doxyComputerOutput">VecPred</span> parameter can be used to indicate the select is using a compare with the specified predicate as condition. When vector types are passed, <span class="doxyComputerOutput">VecPred</span> must be used for all lanes. For a comparison, the two operands are the natural values. For a select, the two operands are the <em>value</em> operands, not the condition operand.</p></dd>
</dl>


<p>Declaration at line 1435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1067 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getCostOfKeepingLiveOverCall {#a8920039419b33a0b7248a0957e262ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getCostOfKeepingLiveOverCall (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Tys)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The cost, if any, of keeping values of the given types alive over a callsite.</p></dd>
</dl>


<p>Some types may require the use of register classes that do not have any callee-saved registers, so would require a spill and fill.</p>


<p>Declaration at line 1637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1247 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getExtendedReductionCost {#a5f958d8d050bfd1a5b0ea73186f2e36e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getExtendedReductionCost (unsigned Opcode, bool IsUnsigned, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ResTy, <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind=<a href="#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">TTI::TCK_RecipThroughput</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate the cost of an extended reduction pattern, similar to getArithmeticReductionCost of a reduction with an extension.</p>


<p>This is the cost of as: ResTy vecreduce.opcode(ext(Ty A)).</p>


<p>Declaration at line 1601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1233 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>.</p>

</div>
</div>

### getExtractWithExtendCost {#acbea7151f5e66776f92f7b4e305418d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getExtractWithExtendCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Dst, <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * VecTy, unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expected cost of a sign- or zero-extended vector extract. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> Index = -1 to indicate that there is no information about the index value.</p></dd>
</dl>


<p>Declaration at line 1416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1050 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getGatherScatterOpCost {#aa0f4a801858ac7255f623ca0ec53394f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getGatherScatterOpCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DataTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, bool VariableMask, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind=<a href="#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">TTI::TCK_RecipThroughput</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The cost of Gather or Scatter operation <span class="doxyComputerOutput">Opcode</span> - is a type of memory access Load or Store <span class="doxyComputerOutput">DataTy</span> - a vector type of the data to be loaded or stored <span class="doxyComputerOutput">Ptr</span> - pointer [or vector of pointers] - address[es] in memory <span class="doxyComputerOutput">VariableMask</span> - true when the memory access is predicated with a mask that is not a compile-time constant <span class="doxyComputerOutput">Alignment</span> - alignment of single element <span class="doxyComputerOutput">I</span> - the optional original context instruction, if one exists, e.g. the load/store to transform or the call to the gather/scatter intrinsic</p></dd>
</dl>


<p>Declaration at line 1515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1146 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### getGISelRematGlobalCost {#acd2f1ef61f1c352da3b8121d4ea2c585}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getGISelRematGlobalCost ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the size cost of rematerializing a <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> address relative to a stack reload.</p></dd>
</dl>


<p>Declaration at line 1797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1408 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getInlineCallPenalty {#a2eae79e5ad5916c4e64cb73eb0b27323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getInlineCallPenalty (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call, unsigned DefaultCallPenalty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a penalty for invoking call <span class="doxyComputerOutput">Call</span> in <span class="doxyComputerOutput">F</span>.</p>


<p>For example, if a function F calls a function G, which in turn calls function H, then getInlineCallPenalty(F, H()) would return the penalty of calling H from F, e.g. after inlining G into F. <span class="doxyComputerOutput">DefaultCallPenalty</span> is passed to give a default penalty that the target can amend or override.</p>


<p>Declaration at line 1685 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1290 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### getInterleavedMemoryOpCost {#a38000267bdb6bb25b9c33f9fd7053b1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getInterleavedMemoryOpCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * VecTy, unsigned Factor, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Indices, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, unsigned AddressSpace, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind=<a href="#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">TTI::TCK_RecipThroughput</a>, bool UseMaskForCond=false, bool UseMaskForGaps=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The cost of the interleaved memory operation. <span class="doxyComputerOutput">Opcode</span> is the memory operation code <span class="doxyComputerOutput">VecTy</span> is the vector type of the interleaved access. <span class="doxyComputerOutput">Factor</span> is the interleave factor <span class="doxyComputerOutput">Indices</span> is the indices for interleaved load members (as interleaved load allows gaps) <span class="doxyComputerOutput">Alignment</span> is the alignment of the memory operation <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/nvptxas/#ad7d00b71af84502be65ae2de3f8d91dc">AddressSpace</a></span> is address space of the pointer. <span class="doxyComputerOutput">UseMaskForCond</span> indicates if the memory access is predicated. <span class="doxyComputerOutput">UseMaskForGaps</span> indicates if gaps should be masked.</p></dd>
</dl>


<p>Declaration at line 1544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1165 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>.</p>

</div>
</div>

### getIntrinsicInstrCost {#a4218f47749d093473e680ad0199fb239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getIntrinsicInstrCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsiccostattributes">IntrinsicCostAttributes</a> &amp; ICA, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>The cost of <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic">Intrinsic</a> instructions. Analyses the real arguments. Three cases are handled: 1. scalar instruction 2. vector instruction</p>


<ol class="doxyList" type="1">
<li>scalar instruction which is to be vectorized.</li>
</ol>
</dd>
</dl>


<p>Declaration at line 1609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1177 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>.</p>

</div>
</div>

### getLoadStoreVecRegBitWidth {#a5c9d2da3e41e4cc90c7a552258166277}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getLoadStoreVecRegBitWidth (unsigned AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The bitwidth of the largest vector type that should be used to load/store in the given address space.</p></dd>
</dl>


<p>Declaration at line 1712 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1312 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getLoadVectorFactor {#a84e51850e7e39c4bd2424ad98c12e700}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getLoadVectorFactor (unsigned VF, unsigned LoadSize, unsigned ChainSizeInBytes, <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * VecTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The new vector factor value if the target doesn't support <span class="doxyComputerOutput">SizeInBytes</span> loads or has a better vector factor.</p></dd>
</dl>


<p>Declaration at line 1737 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1345 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getMaskedMemoryOpCost {#a8718d4f9740c67449057887b386fb348}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getMaskedMemoryOpCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Src, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, unsigned AddressSpace, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind=<a href="#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">TTI::TCK_RecipThroughput</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The cost of masked Load and Store instructions.</p></dd>
</dl>


<p>Declaration at line 1502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1137 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>.</p>

</div>
</div>

### getMaximumVF {#a785bcc5cab17bd5d96f800247dad0649}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getMaximumVF (unsigned ElemWidth, unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The maximum vectorization factor for types of given element bit width and opcode, or 0 if there is no maximum VF. Currently only used by the SLP vectorizer.</p></dd>
</dl>


<p>Declaration at line 1216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 807 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getMaxInterleaveFactor {#ac8c60443d89e7ed0d199dfddafd5885f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getMaxInterleaveFactor (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The maximum interleave factor that any transform should try to perform for this target. This number depends on the level of parallelism and the number of execution units in the CPU.</p></dd>
</dl>


<p>Declaration at line 1311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 875 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getMaxPrefetchIterationsAhead {#a66cb8d0f215f1b7b66e4a7d6581b3a16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getMaxPrefetchIterationsAhead ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The maximum number of iterations to prefetch ahead. If the required number of iterations is more than this number, no prefetching is performed.</p></dd>
</dl>


<p>Declaration at line 1286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 854 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getMaxVScale {#a3586d4f687e1a068f879bf29b046eb3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; TargetTransformInfo::getMaxVScale ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The maximum value of vscale if the target specifies an architectural maximum vector length, and std::nullopt otherwise.</p></dd>
</dl>


<p>Declaration at line 1190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 785 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getMemcpyLoopLoweringType {#a1e5bbdb7bb28a7e509e6893d56ab60b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * TargetTransformInfo::getMemcpyLoopLoweringType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Length, unsigned SrcAddrSpace, unsigned DestAddrSpace, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> SrcAlign, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> DestAlign, std::optional&lt; uint32_t &gt; AtomicElementSize=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The type to use in a loop expansion of a memcpy call.</p></dd>
</dl>


<p>Declaration at line 1657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1265 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>.</p>

</div>
</div>

### getMemcpyLoopResidualLoweringType {#ae609e12c2691f94194afb835facb5c86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetTransformInfo::getMemcpyLoopResidualLoweringType (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp; OpsOut, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, unsigned RemainingBytes, unsigned SrcAddrSpace, unsigned DestAddrSpace, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> SrcAlign, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> DestAlign, std::optional&lt; uint32_t &gt; AtomicCpySize=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] OpsOut</td>
<td class="doxyParamItemDescription"><p>The operand types to copy RemainingBytes of memory.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RemainingBytes</td>
<td class="doxyParamItemDescription"><p>The number of bytes to copy.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Calculates the operand types to use when copying <span class="doxyComputerOutput">RemainingBytes</span> of memory, where source and destination alignments are <span class="doxyComputerOutput">SrcAlign</span> and <span class="doxyComputerOutput">DestAlign</span> respectively.</p>


<p>Declaration at line 1668 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1274 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getMemoryOpCost {#a34c987c590db0e5cff66d9869a34c556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getMemoryOpCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Src, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, unsigned AddressSpace, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind=<a href="#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">TTI::TCK_RecipThroughput</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/operandvalueinfo">OperandValueInfo</a> OpInfo={<a href="#afa38851d75434d1476444ac93f94cb4ca9c0eecea29e9fa58e4dac7ee32b9b2ac">OK_AnyValue</a>, <a href="#a733fb237f3037c95ed59de6055b176c5a2bc39e3785b29fe7bc4af768842a2072">OP_None</a>}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The cost of Load and Store instructions.</p></dd>
</dl>


<p>Declaration at line 1488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1125 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getMinimumVF {#a6a94a8710c9c41b64870559c9098f305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElementCount TargetTransformInfo::getMinimumVF (unsigned ElemWidth, bool IsScalable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The minimum vectorization factor for types of given element bit width, or 0 if there is no minimum VF. The returned value only applies when shouldMaximizeVectorBandwidth returns true. If IsScalable is true, the returned <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> must be a scalable VF.</p></dd>
</dl>


<p>Declaration at line 1211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 802 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getMinMaxReductionCost {#a6da1f2e3b471cce50680e800c05e4d6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getMinMaxReductionCost (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IID, <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF=<a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a>(), <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind=<a href="#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">TTI::TCK_RecipThroughput</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1584 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1224 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>.</p>

</div>
</div>

### getMinPageSize {#ab4e57c55018de258547a8248748cc667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; TargetTransformInfo::getMinPageSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The minimum architectural page size for the target.</p></dd>
</dl>


<p>Declaration at line 1255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 838 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp/#ac94ced33f9dba5c3cce727d419a5af27">MinPageSize</a>.</p>

</div>
</div>

### getMinPrefetchStride {#a8dcadecc95e9e49f77a70ab8b99a8c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getMinPrefetchStride (unsigned NumMemAccesses, unsigned NumStridedMemAccesses, unsigned NumPrefetches, bool HasCall)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Some HW prefetchers can handle accesses up to a certain constant stride.</p>


<p>Sometimes prefetching is beneficial even below the HW prefetcher limit, and the arguments provided are meant to serve as a basis for deciding this for a particular loop.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumMemAccesses</td>
<td class="doxyParamItemDescription"><p>Number of memory accesses in the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumStridedMemAccesses</td>
<td class="doxyParamItemDescription"><p>Number of the memory accesses that <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> could find a known stride for.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumPrefetches</td>
<td class="doxyParamItemDescription"><p>Number of software prefetches that will be emitted as determined by the addresses involved and the cache line size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasCall</td>
<td class="doxyParamItemDescription"><p>True if the loop contains a call.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>This is the minimum stride in bytes where it makes sense to start adding SW prefetches. The default is 1, i.e. prefetch with any stride.</p></dd>
</dl>


<p>Declaration at line 1279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 847 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getMinTripCountTailFoldingThreshold {#ac50791ac3dd33dc3dc522df16116a27b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getMinTripCountTailFoldingThreshold ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the lower bound of a trip count to decide on vectorization while tail-folding.</p></dd>
</dl>


<p>Declaration at line 1801 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1412 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getMinVectorRegisterBitWidth {#a8fa8b3631e74e836453f972aac6b4b65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getMinVectorRegisterBitWidth ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The width of the smallest vector register type.</p></dd>
</dl>


<p>Declaration at line 1186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 781 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getMulAccReductionCost {#a61fd571365b64379faf5eb0b3caa1b27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getMulAccReductionCost (bool IsUnsigned, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ResTy, <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * Ty, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind=<a href="#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">TTI::TCK_RecipThroughput</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate the cost of an extended reduction pattern, similar to getArithmeticReductionCost of an Add reduction with multiply and optional extensions.</p>


<p>This is the cost of as: ResTy vecreduce.add(mul (A, B)). ResTy vecreduce.add(mul(ext(Ty A), ext(Ty B)).</p>


<p>Declaration at line 1593 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1240 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>.</p>

</div>
</div>

### getNumberOfParts {#ad67b7e389a52ada1d5264e23d09f4cbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getNumberOfParts (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Tp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The number of pieces into which the provided type must be split during legalization. Zero is returned when the answer is unknown.</p></dd>
</dl>


<p>Declaration at line 1619 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1193 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getNumberOfRegisters {#aae0e8ca52658f54e5cc6214eb1a291ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getNumberOfRegisters (unsigned ClassID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the number of registers in the target-provided register class.</p></dd>
</dl>


<p>Declaration at line 1158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 759 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getOperandInfo {#a5fecba95c1ba20950ea8e2139127e621}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo::OperandValueInfo TargetTransformInfo::getOperandInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Collect properties of V used in cost analysis, e.g. OP_PowerOf2.</p>

<p>Declaration at line 1314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 880 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a48fc95f799e976fb8bf571d61e6337f5">llvm::getSplatValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#afa38851d75434d1476444ac93f94cb4ca9c0eecea29e9fa58e4dac7ee32b9b2ac">OK_AnyValue</a>, <a href="#afa38851d75434d1476444ac93f94cb4cacf63326297610dfbedd0ad408b54e3e4">OK_NonUniformConstantValue</a>, <a href="#afa38851d75434d1476444ac93f94cb4ca76d8855d96b8e66b9411ed74737ca8f7">OK_UniformConstantValue</a>, <a href="#afa38851d75434d1476444ac93f94cb4ca7aa61d9e9d33bdf28478754c69c59640">OK_UniformValue</a>, <a href="#a733fb237f3037c95ed59de6055b176c5a19af6b5f4f70eaefcc0b6734f1f06cd8">OP_NegatedPowerOf2</a>, <a href="#a733fb237f3037c95ed59de6055b176c5a2bc39e3785b29fe7bc4af768842a2072">OP_None</a>, <a href="#a733fb237f3037c95ed59de6055b176c5a974f46ced0fd416db695ce5da6059dcc">OP_PowerOf2</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a5b9bf50c6579a978e5c1104bf8787651">llvm::Splat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a95442a0e0980e874df3bf77d6c8dee44">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a> and <a href="/web-llvm/docs/api/structs/llvm/vpcostcontext/#a405f8a14bfc2cdbae99d57cb20349621">llvm::VPCostContext::getOperandInfo</a>.</p>

</div>
</div>

### getOrCreateResultFromMemIntrinsic {#ad5e18a8730e428b4967b375d57c2e401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * TargetTransformInfo::getOrCreateResultFromMemIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * Inst, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ExpectedType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A value which is the result of the given memory intrinsic. New instructions may be created to extract the result from the given intrinsic memory operation. Returns nullptr if the target cannot create a result from the given intrinsic.</p></dd>
</dl>


<p>Declaration at line 1653 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1260 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getPartialReductionCost {#adb33d253939bf13b4cb03af00b23a182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getPartialReductionCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * InputTypeA, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * InputTypeB, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * AccumType, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="#abd1dc2b46b5e2311e1f64d21b2991be9">PartialReductionExtendKind</a> OpAExtend, <a href="#abd1dc2b46b5e2311e1f64d21b2991be9">PartialReductionExtendKind</a> OpBExtend, std::optional&lt; unsigned &gt; BinOp=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The cost of a partial reduction, which is a reduction from a vector to another vector with fewer elements of larger size. They are represented by the llvm.experimental.partial.reduce.add intrinsic, which takes an accumulator and a binary operation operand that itself is fed by two extends. An example of an operation that uses a partial reduction is a dot product, which reduces two vectors to another of 4 times fewer and 4 times larger elements.</p></dd>
</dl>


<p>Declaration at line 1302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 866 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getPreferredExpandedReductionShuffle {#a5e995d547e3a71909c78baf33c3c6942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo::ReductionShuffle TargetTransformInfo::getPreferredExpandedReductionShuffle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * II)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The shuffle sequence pattern used to expand the given reduction intrinsic.</p></dd>
</dl>


<p>Declaration at line 1793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1403 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>

</div>
</div>

### getPrefetchDistance {#a1e3f3a3d549cf057479e744e7ecfd7e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getPrefetchDistance ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>How much before a load we should place the prefetch instruction. This is currently measured in number of instructions.</p></dd>
</dl>


<p>Declaration at line 1260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 843 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getRegisterBitWidth {#a2d30dd50c6b2d64ca3bc2826ca229fdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize TargetTransformInfo::getRegisterBitWidth (<a href="#a8bb3b1ccf19b8c85429b777dfa4a0166">RegisterKind</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The width of the largest scalar or vector register type.</p></dd>
</dl>


<p>Declaration at line 1183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 776 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getRegisterClassForType {#a623cced59353f83cc5eaba4068c57694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getRegisterClassForType (bool Vector, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the target-provided register class <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the provided type, accounting for type promotion and other type-legalization techniques that the target might apply. However, it specifically does not account for the scalarization or splitting of vector types. Should a vector type require scalarization or splitting into multiple underlying vector registers, that type should be mapped to a register class containing no registers. Specifically, this is designed to provide a simple, high-level view of the register allocation later performed by the backend. These register classes don't necessarily map onto the register classes used by the backend. FIXME: It's not currently possible to determine how many registers are used by the provided type.</p></dd>
</dl>


<p>Declaration at line 1175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 767 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">llvm::Vector</a>.</p>

</div>
</div>

### getRegisterClassName {#a97503ae3ef00c5f1eaffa5bbeb0a4357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * TargetTransformInfo::getRegisterClassName (unsigned ClassID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the target-provided register class name</p></dd>
</dl>


<p>Declaration at line 1178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 772 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getReplicationShuffleCost {#a35a3b8f44dff2cf349e66821606dfa8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getReplicationShuffleCost (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * EltTy, int ReplicationFactor, int VF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedDstElts, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The cost of replication shuffle of <span class="doxyComputerOutput">VF</span> elements typed <span class="doxyComputerOutput">EltTy</span> <span class="doxyComputerOutput">ReplicationFactor</span> times.</p></dd>
</dl>


<p>For example, the mask for <span class="doxyComputerOutput">ReplicationFactor=3</span> and <span class="doxyComputerOutput">VF=4</span> is: &lt;0,0,0,1,1,1,2,2,2,3,3,3&gt;</p>


<p>Declaration at line 1481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1116 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>.</p>

</div>
</div>

### getShuffleCost {#a8eebd7cdc98c9b46d8d4016143c7bdcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getShuffleCost (<a href="#af46433d0e36d3f80afc3a8c67b5c53ec">ShuffleKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * Tp, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask={}, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind=<a href="#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">TTI::TCK_RecipThroughput</a>, int Index=0, <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * SubTp=nullptr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Args={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The cost of a shuffle instruction of kind Kind and of type Tp. The exact mask may be passed as Mask, or else the array will be empty. The index and subtype parameters are used by the subvector insertion and extraction shuffle kinds to show the insert/extract point and the type of the subvector being inserted/extracted. The operands of the shuffle can be passed through <span class="doxyComputerOutput">Args</span>, which helps improve the cost estimation in some cases, like in broadcast loads. NOTE: For subvector extractions Tp represents the source type.</p></dd>
</dl>


<p>Declaration at line 1363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 976 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>.</p>

</div>
</div>

### getStoreMinimumVF {#abdf352ba0545cdb2ad70f4d72b594cfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getStoreMinimumVF (unsigned VF, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ScalarMemTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ScalarValTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The minimum vectorization factor for the store instruction. Given the initial estimation of the minimum vector factor and store value type, it tries to find possible lowest VF, which still might be profitable for the vectorization.</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">VF</td>
<td class="doxyParamItemDescription"><p>Initial estimation of the minimum vector factor.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ScalarMemTy</td>
<td class="doxyParamItemDescription"><p>Scalar memory type of the store operation.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ScalarValTy</td>
<td class="doxyParamItemDescription"><p>Scalar type of the stored value. Currently only used by the SLP vectorizer.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 812 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getStoreVectorFactor {#a47da5df7f765cada1df9036a3433e1a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetTransformInfo::getStoreVectorFactor (unsigned VF, unsigned StoreSize, unsigned ChainSizeInBytes, <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * VecTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The new vector factor value if the target doesn't support <span class="doxyComputerOutput">SizeInBytes</span> stores or has a better vector factor.</p></dd>
</dl>


<p>Declaration at line 1743 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1352 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getStridedMemoryOpCost {#a0b5066bc4acd72f9d474ebbf5eec6de3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getStridedMemoryOpCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DataTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, bool VariableMask, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind=<a href="#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">TTI::TCK_RecipThroughput</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The cost of strided memory operations. <span class="doxyComputerOutput">Opcode</span> - is a type of memory access Load or Store <span class="doxyComputerOutput">DataTy</span> - a vector type of the data to be loaded or stored <span class="doxyComputerOutput">Ptr</span> - pointer [or vector of pointers] - address[es] in memory <span class="doxyComputerOutput">VariableMask</span> - true when the memory access is predicated with a mask that is not a compile-time constant <span class="doxyComputerOutput">Alignment</span> - alignment of single element <span class="doxyComputerOutput">I</span> - the optional original context instruction, if one exists, e.g. the load/store to transform or the call to the gather/scatter intrinsic</p></dd>
</dl>


<p>Declaration at line 1529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1156 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### getTgtMemIntrinsic {#a02e4dcfc435f179592619b03330f643b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::getTgtMemIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * Inst, <a href="/web-llvm/docs/api/structs/llvm/memintrinsicinfo">MemIntrinsicInfo</a> &amp; Info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the intrinsic is a supported memory intrinsic. Info will contain additional information - whether the intrinsic may write or read to memory, volatility and the pointer. Info is undefined if false is returned.</p></dd>
</dl>


<p>Declaration at line 1643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1251 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getVectorInstrCost {#af37b2842424eb63440bdcacca0af9820}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getVectorInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Val, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, unsigned Index=-1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0=nullptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expected cost of vector Insert and Extract. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> -1 to indicate that there is no information on the index value. This is used when the instruction is not available; a typical use case is to provision the cost of vectorization/scalarization in vectorizer passes.</p></dd>
</dl>


<p>Declaration at line 1447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1079 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>.</p>

</div>
</div>

### getVectorInstrCost {#af7e3745e82595d80efba229ee7c4ec0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getVectorInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Val, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Scalar, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/user">User</a> *, int &gt; &gt; ScalarUserAndIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expected cost of vector Insert and Extract. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> -1 to indicate that there is no information on the index value. This is used when the instruction is not available; a typical use case is to provision the cost of vectorization/scalarization in vectorizer passes.</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ScalarUserAndIdx</td>
<td class="doxyParamItemDescription"><p>encodes the information about extracts from a vector with 'Scalar' being the value being extracted,'<a href="/web-llvm/docs/api/classes/llvm/user">User</a>' being the user of the <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/loopextractor-cpp/#a84dff14934298a71113ab11312c243f6">extract(nullptr if user is not known before vectorization)</a> and 'Idx' being the extract lane.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1091 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>.</p>

</div>
</div>

### getVectorInstrCost {#a8faf795a9033768e63f8907829339ccf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost TargetTransformInfo::getVectorInstrCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Val, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, unsigned Index=-1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expected cost of vector Insert and Extract. This is used when instruction is available, and implementation asserts 'I' is not nullptr.</p></dd>
</dl>


<p>A typical suitable use case is cost estimation when vector instruction exists (e.g., from basic blocks during transformation).</p>


<p>Declaration at line 1472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1105 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getVPMemoryOpCost {#a846e472a2fb24cec08762c2c26624a35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::TargetTransformInfo::getVPMemoryOpCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Src, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, unsigned AddressSpace, <a href="#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind=<a href="#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">TTI::TCK_RecipThroughput</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The cost of VP Load and Store instructions.</p></dd>
</dl>


<p>Definition at line 1496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">TCK_RecipThroughput</a>.</p>

</div>
</div>

### getVScaleForTuning {#a04394f31b3d57c89fd8211783a12736d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; TargetTransformInfo::getVScaleForTuning ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the value of vscale to tune the cost model for.</p></dd>
</dl>


<p>Declaration at line 1193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 789 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### hasConditionalLoadStoreForType {#ada0fe933e853c23312ff60304ce7e220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::hasConditionalLoadStoreForType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the target supports load/store that enables fault suppression of memory operands when the source condition is false.</p></dd>
</dl>


<p>Declaration at line 1162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 763 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isElementTypeLegalForScalableVector {#a64e28d7d5da07059305e09ff16ee5d0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isElementTypeLegalForScalableVector (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the given type is supported for scalable vectors</p></dd>
</dl>


<p>Declaration at line 1733 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1341 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isIndexedLoadLegal {#a7716bda26c61738e624214efa149e83e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isIndexedLoadLegal (enum <a href="#acf5cc8324c33cb1f59869456263f9f4b">MemIndexedMode</a> Mode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the specified indexed load for the given type is legal.</p></dd>
</dl>


<p>Declaration at line 1705 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1302 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isIndexedStoreLegal {#a5a768ef7bcf1b5059f409327c1f83591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isIndexedStoreLegal (enum <a href="#acf5cc8324c33cb1f59869456263f9f4b">MemIndexedMode</a> Mode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the specified indexed store for the given type is legal.</p></dd>
</dl>


<p>Declaration at line 1708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1307 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalToVectorizeLoad {#a03aaf2f1c4d2a4bb801bc9aeea94de3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalToVectorizeLoad (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the load instruction is legal to vectorize.</p></dd>
</dl>


<p>Declaration at line 1715 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1316 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalToVectorizeLoadChain {#aaaa75efd79296070e4c5f24fa3ea6f01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalToVectorizeLoadChain (unsigned ChainSizeInBytes, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, unsigned AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if it is legal to vectorize the given load chain.</p></dd>
</dl>


<p>Declaration at line 1721 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1324 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalToVectorizeReduction {#a7b174ae4841c69cd671ed4bf4834db64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalToVectorizeReduction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor">RecurrenceDescriptor</a> &amp; RdxDesc, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if it is legal to vectorize the given reduction kind.</p></dd>
</dl>


<p>Declaration at line 1729 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1336 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalToVectorizeStore {#a0de4290b00b162ec20705cad42047b64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalToVectorizeStore (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the store instruction is legal to vectorize.</p></dd>
</dl>


<p>Declaration at line 1718 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1320 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isLegalToVectorizeStoreChain {#a58b0dcd9d3ef39aa308b7d7371e5da88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isLegalToVectorizeStoreChain (unsigned ChainSizeInBytes, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, unsigned AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if it is legal to vectorize the given store chain.</p></dd>
</dl>


<p>Declaration at line 1725 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1330 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isVScaleKnownToBeAPowerOfTwo {#a761a2a864705382c56d6406a6a97e6fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isVScaleKnownToBeAPowerOfTwo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if vscale is known to be a power of 2</p></dd>
</dl>


<p>Declaration at line 1196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 793 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### MemIndexedMode {#acf5cc8324c33cb1f59869456263f9f4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TargetTransformInfo::MemIndexedMode </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type of load/store indexing.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MIM_Unindexed<a id="acf5cc8324c33cb1f59869456263f9f4ba24234938a33e357e0c86f1d71295a2f6"></a></td>
<td class="doxyEnumItemDescription">No indexing</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MIM_PreInc<a id="acf5cc8324c33cb1f59869456263f9f4baf049517e9a49117b5225ee67455f5dea"></a></td>
<td class="doxyEnumItemDescription">Pre-incrementing</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MIM_PreDec<a id="acf5cc8324c33cb1f59869456263f9f4ba7367f3267f2bfe1a200655097784f4a1"></a></td>
<td class="doxyEnumItemDescription">Pre-decrementing</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MIM_PostInc<a id="acf5cc8324c33cb1f59869456263f9f4ba3a471f30b7a193785b57c081776ad3cb"></a></td>
<td class="doxyEnumItemDescription">Post-incrementing</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MIM_PostDec<a id="acf5cc8324c33cb1f59869456263f9f4ba57dbcb88640a74d04f7e0ddeefa76d1b"></a></td>
<td class="doxyEnumItemDescription">Post-decrementing</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

### OperandValueKind {#afa38851d75434d1476444ac93f94cb4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TargetTransformInfo::OperandValueKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Additional information about an operand's possible values.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OK_AnyValue<a id="afa38851d75434d1476444ac93f94cb4ca9c0eecea29e9fa58e4dac7ee32b9b2ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OK_UniformValue<a id="afa38851d75434d1476444ac93f94cb4ca7aa61d9e9d33bdf28478754c69c59640"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OK_UniformConstantValue<a id="afa38851d75434d1476444ac93f94cb4ca76d8855d96b8e66b9411ed74737ca8f7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OK_NonUniformConstantValue<a id="afa38851d75434d1476444ac93f94cb4cacf63326297610dfbedd0ad408b54e3e4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

### OperandValueProperties {#a733fb237f3037c95ed59de6055b176c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TargetTransformInfo::OperandValueProperties </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Additional properties of an operand's values.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OP_None<a id="a733fb237f3037c95ed59de6055b176c5a2bc39e3785b29fe7bc4af768842a2072"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OP_PowerOf2<a id="a733fb237f3037c95ed59de6055b176c5a974f46ced0fd416db695ce5da6059dcc"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OP_NegatedPowerOf2<a id="a733fb237f3037c95ed59de6055b176c5a19af6b5f4f70eaefcc0b6734f1f06cd8"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

### preferEpilogueVectorization {#a987fde1294b059921cb381631fa3747b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::preferEpilogueVectorization ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the loop vectorizer should consider vectorizing an otherwise scalar epilogue loop.</p>

<p>Declaration at line 1782 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1373 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### preferFixedOverScalableIfEqualCost {#afc2ae54af36c42e74d1ed1dbb858e7e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::preferFixedOverScalableIfEqualCost ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the targets prefers fixed width vectorization if the loop vectorizer's cost-model assigns an equal cost to the fixed and scalable version of the vectorized loop.</p></dd>
</dl>


<p>Declaration at line 1760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1359 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### preferInLoopReduction {#a1a2b30bdeffa3fb4a4fd881e25d01817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::preferInLoopReduction (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/reductionflags">ReductionFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the target prefers reductions in loop.</p></dd>
</dl>


<p>Declaration at line 1763 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1363 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### preferPredicatedReductionSelect {#a8e8f7af4c35e8c6bc6e9a4f0850a7847}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::preferPredicatedReductionSelect (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/reductionflags">ReductionFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the target prefers reductions select kept in the loop when tail folding. i.e. loop: p = phi (0, s) a = add (p, x) s = select (mask, a, p) vecreduce.add(s)</p></dd>
</dl>


<p>As opposed to the normal scheme of p = phi (0, a) which allows the select to be pulled out of the loop. If the select(.., add, ..) can be predicated by the target, this can lead to cleaner code generation.</p>


<p>Declaration at line 1777 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1368 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### ReductionShuffle {#a0692c75c1b45226b6afb90ad609eb86a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::TargetTransformInfo::ReductionShuffle </td>
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
<td class="doxyEnumItemName">SplitHalf<a id="a0692c75c1b45226b6afb90ad609eb86aaae6207387f79edd0cadf44ec25c995b3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pairwise<a id="a0692c75c1b45226b6afb90ad609eb86aa327036a1ef7ccbd87697bb2a2197d9ae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

### RegisterKind {#a8bb3b1ccf19b8c85429b777dfa4a0166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TargetTransformInfo::RegisterKind </td>
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
<td class="doxyEnumItemName">RGK_Scalar<a id="a8bb3b1ccf19b8c85429b777dfa4a0166ad8f233645107107ed48d2e4a915152cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RGK_FixedWidthVector<a id="a8bb3b1ccf19b8c85429b777dfa4a0166a183020fbea95c99db23f6d3594f4c4af"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RGK_ScalableVector<a id="a8bb3b1ccf19b8c85429b777dfa4a0166a331413d3887a08546d0973091f6a4993"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

### requiresOrderedReduction {#a7aecc3cf03beff532c2b8bfe81e500c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetTransformInfo::requiresOrderedReduction (std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> &gt; FMF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A helper function to determine the type of reduction algorithm used for a given <span class="doxyComputerOutput">Opcode</span> and set of <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> <span class="doxyComputerOutput">FMF</span>.</p>

<p>Definition at line 1552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24fb14e02fa8e4a261838b46074e42fa">llvm::AArch64TTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5dcb8d597c1066eec7ef713b758f78f4">llvm::ARMTTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aacaa7d017eb34bf5050b2fb7f6dd91c4">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#afe02f4d6b04ada7f0864494bd23b83d7">llvm::GCNTTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1ffc644bb4865116b0a2f4db014e9bed">llvm::RISCVTTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#acbad6d70dd3351b812d5b74353574207">llvm::SystemZTTIImpl::getArithmeticReductionCost</a> and <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#aa0e22cc6f0e4ea9717d5ad07df6806ee">llvm::X86TTIImpl::getArithmeticReductionCost</a>.</p>

</div>
</div>

### shouldConsiderAddressTypePromotion {#a9880b7512930d879440db073b536d362}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::shouldConsiderAddressTypePromotion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, bool &amp; AllowPromotionWithoutCommonHeader)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if it should be considered for address type promotion. <span class="doxyComputerOutput">AllowPromotionWithoutCommonHeader</span> Set true if promoting <span class="doxyComputerOutput">I</span> is profitable without finding other extensions fed by the same input.</p></dd>
</dl>


<p>Declaration at line 1232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 817 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### shouldExpandReduction {#aefeefc63fa057f5050b78547c6cdf0e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::shouldExpandReduction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * II)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the target wants to expand the given reduction intrinsic into a shuffle sequence.</p></dd>
</dl>


<p>Declaration at line 1786 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1398 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>

</div>
</div>

### shouldMaximizeVectorBandwidth {#a525b5174ebf7ac1db045dde5f579ddcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::shouldMaximizeVectorBandwidth (<a href="#a8bb3b1ccf19b8c85429b777dfa4a0166">TargetTransformInfo::RegisterKind</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the vectorization factor should be chosen to make the vector of the smallest element type match the size of a vector register. For wider element types, this could result in creating vectors that span multiple vector registers. If false, the vectorization factor will be chosen based on the size of the widest element type. <span class="doxyComputerOutput">K</span> <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Kind for vectorization.</p></dd>
</dl>


<p>Declaration at line 1205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 797 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### shouldPrefetchAddressSpace {#a8f4eb225c0b7b93c8b8e6c0de860fb5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::shouldPrefetchAddressSpace (unsigned AS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>if target want to issue a prefetch in address space <span class="doxyComputerOutput">AS</span>.</p></dd>
</dl>


<p>Declaration at line 1292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 862 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### ShuffleKind {#af46433d0e36d3f80afc3a8c67b5c53ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TargetTransformInfo::ShuffleKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The various kinds of shuffle patterns for vector queries.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SK_Broadcast<a id="af46433d0e36d3f80afc3a8c67b5c53ecab1ac8982cdb119f39a5fe74610a46796"></a></td>
<td class="doxyEnumItemDescription">Broadcast element 0 to all other elements</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SK_Reverse<a id="af46433d0e36d3f80afc3a8c67b5c53ecaea788d98147161f25d5adc3ec6ce7e1f"></a></td>
<td class="doxyEnumItemDescription">Reverse the order of the vector</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SK_Select<a id="af46433d0e36d3f80afc3a8c67b5c53eca64d439485545faa793c20de7fbfd274c"></a></td>
<td class="doxyEnumItemDescription">Selects elements from the corresponding lane of either source operand</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SK_Transpose<a id="af46433d0e36d3f80afc3a8c67b5c53eca7cc176c1463af0d9820e7981c32db478"></a></td>
<td class="doxyEnumItemDescription">Transpose two vectors</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SK_InsertSubvector<a id="af46433d0e36d3f80afc3a8c67b5c53eca466a4d581cf3a553414b9c2e889b944a"></a></td>
<td class="doxyEnumItemDescription">InsertSubvector. Index indicates start offset</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SK_ExtractSubvector<a id="af46433d0e36d3f80afc3a8c67b5c53ecafd6c03f570400fcb24d861aa21ddffe9"></a></td>
<td class="doxyEnumItemDescription">ExtractSubvector Index indicates start offset</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SK_PermuteTwoSrc<a id="af46433d0e36d3f80afc3a8c67b5c53ecab4616961a3bfdaec42aedc4fc426ccfe"></a></td>
<td class="doxyEnumItemDescription">Merge elements from two source vectors into one with any shuffle mask</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SK_PermuteSingleSrc<a id="af46433d0e36d3f80afc3a8c67b5c53eca7beec9815d0197f2d31fac9968e9205b"></a></td>
<td class="doxyEnumItemDescription">Shuffle elements of single source vector with any shuffle mask</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SK_Splice<a id="af46433d0e36d3f80afc3a8c67b5c53ecaa9e18b2636661e341804da24971997df"></a></td>
<td class="doxyEnumItemDescription">Concatenates elements from the first input vector with elements of the second input vector</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1098 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

### supportsScalableVectors {#ab0215ddedbe9f8179c491308a56aaceb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::supportsScalableVectors ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the target supports scalable vectors.</p></dd>
</dl>


<p>Declaration at line 1804 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1416 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Vector Predication Information



<p>Whether the target supports the evl parameter of VP intrinsic efficiently in hardware, for the given opcode and type/alignment.</p>


<p>(see LLVM Language Reference - "Vector Predication Intrinsics"). <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> of evl is discouraged when that is not the case.</p>


### getVPLegalizationStrategy {#a4843aaa2647f4f1fb037f957beda8eaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo::VPLegalization TargetTransformInfo::getVPLegalizationStrategy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; PI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>How the target needs this vector-predicated operation to be transformed.</p></dd>
</dl>


<p>Declaration at line 1864 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1378 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### hasActiveVectorLength {#aa3898235ae1cbefb03b09d1ddebae0e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::hasActiveVectorLength (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DataType, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1815 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1424 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### isProfitableToSinkOperands {#ae553d04f4c990459f9827950e6c71e75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isProfitableToSinkOperands (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * &gt; &amp; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if sinking I's operands to the same basic block as I is profitable, e.g.</p>


<p>because the operands can be folded into a target instruction during instruction selection. After calling the function <span class="doxyComputerOutput">Ops</span> contains the Uses to sink ordered by dominance (dominating users come first).</p>


<p>Declaration at line 1823 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1429 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### isVectorShiftByScalarCheap {#aca4d7e4051f7cb81a1e79bb1e25f03d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetTransformInfo::isVectorShiftByScalarCheap (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if it's significantly cheaper to shift a vector by a uniform scalar than by an amount which will vary across each lane.</p>


<p>On x86 before AVX2 for example, there is a "psllw" instruction for the former case, but no simple instruction for a general "a &lt;&lt; b" operation on vectors. This should also apply to lowering for vector funnel shifts (rotates).</p>


<p>Declaration at line 1831 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 1434 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
