---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/innerloopvectorizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InnerLoopVectorizer` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer">InnerLoopVectorizer</a> vectorizes loops which contain only one basic block to a specified vectorization factor (VF). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::InnerLoopVectorizer { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer">InnerLoopAndEpilogueVectorizer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An extension of the inner loop vectorizer that creates a skeleton for a vectorized loop that has its epilogue (residual) also vectorized. <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a409249e01d3e65716e4c76fa3369a4e0">LoopVectorizationPlanner</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a> (Loop *OrigLoop, PredicatedScalarEvolution &amp;PSE, LoopInfo *LI, DominatorTree *DT, const TargetLibraryInfo *TLI, const TargetTransformInfo *TTI, AssumptionCache *AC, OptimizationRemarkEmitter *ORE, ElementCount VecWidth, ElementCount MinProfitableTripCount, unsigned UnrollFactor, LoopVectorizationLegality *LVL, LoopVectorizationCostModel *CM, BlockFrequencyInfo *BFI, ProfileSummaryInfo *PSI, GeneratedRTChecks &amp;RTChecks, VPlan &amp;Plan)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecacb69b3a2334317cce2a7856f7d30d">~InnerLoopVectorizer</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31f933a6eada9926c9e320db27dfb775">createVectorizedLoopSkeleton</a> (const SCEV2ValueTy &amp;ExpandedSCEVs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new empty loop that will contain vectorized instructions later on, while the old loop will be used as the scalar remainder. <a href="#a31f933a6eada9926c9e320db27dfb775">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9484786140efebf774cde8f072894246">fixVectorizedLoop</a> (VPTransformState &amp;State)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fix the vectorized code, taking care of header phi's, and more. <a href="#a9484786140efebf774cde8f072894246">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e066ef7bc9673cbb2a825189491577d">areSafetyChecksAdded</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4690286163882c35068b1908f4d752fd">scalarizeInstruction</a> (const Instruction *Instr, VPReplicateRecipe *RepRecipe, const VPLane &amp;Lane, VPTransformState &amp;State)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper function to scalarize a single <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> in the innermost loop. <a href="#a4690286163882c35068b1908f4d752fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accb5ce221150790c36b2d96af1be821c">fixNonInductionPHIs</a> (VPTransformState &amp;State)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fix the non-induction PHIs in <span class="doxyComputerOutput">Plan</span>. <a href="#accb5ce221150790c36b2d96af1be821c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35de654dc8297fa810c78922102bb696">getTripCount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the original loop trip count. <a href="#a35de654dc8297fa810c78922102bb696">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9160ed9f749a9c4df711061181288e13">setTripCount</a> (Value *TC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to set the trip count after ILV's construction and after the preheader block has been executed. <a href="#a9160ed9f749a9c4df711061181288e13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86acbbb5785d46e5a10d2ed34c779dd9">getInductionAdditionalBypassValue</a> (PHINode *OrigPhi) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>induction header phi. <a href="#a86acbbb5785d46e5a10d2ed34c779dd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f2e87f456c35fdad0ec24e7c71a92a5">getAdditionalBypassBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the additional bypass block which targets the scalar loop by skipping the epilogue loop after completing the main loop. <a href="#a8f2e87f456c35fdad0ec24e7c71a92a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a5c60e5cebd520f95b9813fd9807016">sinkScalarOperands</a> (Instruction *PredInst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iteratively sink the scalarized operands of a predicated instruction into the block that was created for it. <a href="#a0a5c60e5cebd520f95b9813fd9807016">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa83b181aa14d5afe1390faad388f91a4">getOrCreateVectorTripCount</a> (BasicBlock *InsertBlock)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns (and creates if needed) the trip count of the widened loop. <a href="#aa83b181aa14d5afe1390faad388f91a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72c491cdf8cf0283d87008831431f917">emitIterationCountCheck</a> (BasicBlock *Bypass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a bypass check to see if the vector trip count is zero, including if it overflows. <a href="#a72c491cdf8cf0283d87008831431f917">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30c4bcea7beb42c7eb075a578bc3bc3e">emitSCEVChecks</a> (BasicBlock *Bypass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a bypass check to see if all of the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> assumptions we've had to make are correct. <a href="#a30c4bcea7beb42c7eb075a578bc3bc3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a625caa931f0d8ef201041febbfe42cca">emitMemRuntimeChecks</a> (BasicBlock *Bypass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit bypass checks to check any memory assumptions we may have made. <a href="#a625caa931f0d8ef201041febbfe42cca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e719da4709193fd5b4632da4bc69795">createVectorLoopSkeleton</a> (StringRef Prefix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit basic blocks (prefixed with <span class="doxyComputerOutput">Prefix</span>) for the iteration check, vector loop preheader, middle block and scalar preheader. <a href="#a5e719da4709193fd5b4632da4bc69795">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69c116deda6ae831a71558a4630323cb">createInductionAdditionalBypassValues</a> (const SCEV2ValueTy &amp;ExpandedSCEVs, Value *MainVectorTripCount)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create and record the values for induction variables to resume coming from the additional bypass block. <a href="#a69c116deda6ae831a71558a4630323cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00579d597c88e5f3c51754bcd9ec5658">printDebugTracesAtStart</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow subclasses to override and print debug traces before/after vplan execution, when trace information is requested. <a href="#a00579d597c88e5f3c51754bcd9ec5658">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e275f16680d4f09dbcc0dd7d323a075">printDebugTracesAtEnd</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5222866a9b2208ea05c3e3ed61a313e9">introduceCheckBlockInVPlan</a> (BasicBlock *CheckIRBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Introduces a new <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> for <span class="doxyComputerOutput">CheckIRBB</span> to Plan between the vector preheader and its predecessor, also connecting the new block to the scalar preheader. <a href="#a5222866a9b2208ea05c3e3ed61a313e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af550e4457b9c8a2840a80627713611a9">OrigLoop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The original loop. <a href="#af550e4457b9c8a2840a80627713611a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79a00ec9570d7ae0b7fd17387e3d151f">PSE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A wrapper around <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> used to add runtime <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> checks. <a href="#a79a00ec9570d7ae0b7fd17387e3d151f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d4ba65978a0ecb42764cb2b25edc071">LI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> Info. <a href="#a7d4ba65978a0ecb42764cb2b25edc071">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a909bc9150f12c6ee1f276b2bb58508ff">DT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dominator Tree. <a href="#a909bc9150f12c6ee1f276b2bb58508ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e1902405fb476065f5fd61c563f3567">TLI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Library Info. <a href="#a0e1902405fb476065f5fd61c563f3567">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a238e95d82d095fec9241f2f5b81db3c5">TTI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Transform Info. <a href="#a238e95d82d095fec9241f2f5b81db3c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7526ec0b5613cd07130c3d097799534">AC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assumption Cache. <a href="#aa7526ec0b5613cd07130c3d097799534">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42f4c06af5cd58b1f8a7e54b3ae4316a">ORE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface to emit optimization remarks. <a href="#a42f4c06af5cd58b1f8a7e54b3ae4316a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3ab15d9c94890e913009977bae315ce">VF</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The vectorization SIMD factor to use. <a href="#af3ab15d9c94890e913009977bae315ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f52585230b8a3cb8bf4a30f8e51bfb4">MinProfitableTripCount</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1d8518bd0c514e739180737faf538be">UF</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The vectorization unroll factor to use. <a href="#ae1d8518bd0c514e739180737faf538be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3679e1fff2d21c2034c7ce14df24bf7">Builder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The builder that we use. <a href="#ac3679e1fff2d21c2034c7ce14df24bf7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99d1430a4b51d71f77d78febb40f9d32">LoopVectorPreHeader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The vector-loop preheader. <a href="#a99d1430a4b51d71f77d78febb40f9d32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68ebc27127cd32d3fa276621fb69342b">LoopScalarPreHeader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The scalar-loop preheader. <a href="#a68ebc27127cd32d3fa276621fb69342b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38e6f65b6ccbdebbf2c7a8b078936115">LoopMiddleBlock</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Middle Block between the vector and the scalar. <a href="#a38e6f65b6ccbdebbf2c7a8b078936115">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7cdd6a7370c1f81936d1b17a6f7c701">LoopBypassBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of all bypass blocks. The first block is the entry of the loop. <a href="#ae7cdd6a7370c1f81936d1b17a6f7c701">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47eab9fa7cfa73af0b164da3fca49a0f">PredicatedInstructions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Store instructions that were predicated. <a href="#a47eab9fa7cfa73af0b164da3fca49a0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0937fe0c707a3cd1198cea4467fa37c0">TripCount</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Trip count of the original loop. <a href="#a0937fe0c707a3cd1198cea4467fa37c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c95f95757d9c56b7a89d7f8b3278581">VectorTripCount</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Trip count of the widened loop (TripCount - TripCount % (VF*UF)) <a href="#a2c95f95757d9c56b7a89d7f8b3278581">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality">LoopVectorizationLegality</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bb946cd99f8c37f0145265914aea778">Legal</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The legality analysis. <a href="#a6bb946cd99f8c37f0145265914aea778">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel">LoopVectorizationCostModel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a325b208d89f2e70ee7b565dbc671fbfd">Cost</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The profitablity analysis. <a href="#a325b208d89f2e70ee7b565dbc671fbfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a645c5c5c1e89cb56be66db8db877001d">AddedSafetyChecks</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34df1386ff3adb63b4b4bf65409e716b">BFI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BFI and PSI are used to check for profile guided size optimizations. <a href="#a34df1386ff3adb63b4b4bf65409e716b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a866b987577621ecd4c7adfebaa57de15">PSI</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93a8f97a1e57c3bce2e7c3473d592c01">OptForSizeBasedOnProfile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">GeneratedRTChecks &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9880a8edd20b3b9b1527ecd5a03ac8c">RTChecks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Structure to hold information about generated runtime checks, responsible for cleaning the checks, if vectorization turns out unprofitable. <a href="#ae9880a8edd20b3b9b1527ecd5a03ac8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48c4aed6852a39d4dcc584ac75cc1055">Induction2AdditionalBypassValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping of induction phis to their additional bypass values. <a href="#a48c4aed6852a39d4dcc584ac75cc1055">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a329ce2a6185c5e632406d1d2fc75610e">AdditionalBypassBlock</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The additional bypass block which conditionally skips over the epilogue loop after executing the main loop. <a href="#a329ce2a6185c5e632406d1d2fc75610e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7084dff77ae071151848a0ca10125184">Plan</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b18db1093ed5460e67e9058b89e385b">VectorPHVPB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The vector preheader block of <span class="doxyComputerOutput">Plan</span>, used as target for check blocks introduced during skeleton creation. <a href="#a6b18db1093ed5460e67e9058b89e385b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer">InnerLoopVectorizer</a> vectorizes loops which contain only one basic block to a specified vectorization factor (VF).</p>


<p>This class performs the widening of scalars into vectors, or multiple scalars. This class also implements the following features:</p>


<ul class="doxyList ">
<li>It inserts an epilogue loop for handling loops that don't have iteration counts that are known to be a multiple of the vectorization factor.</li>
<li>It handles the code generation for reduction variables.</li>
<li>Scalarization (implementation using scalars) of un-vectorizable instructions. <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer">InnerLoopVectorizer</a> does not perform any vectorization-legality checks, and relies on the caller to check for the different legality aspects. The <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer">InnerLoopVectorizer</a> relies on the <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality">LoopVectorizationLegality</a> class to provide information about the induction and reduction variables that were found to a given vectorization factor.</li>
</ul>

<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<div class="doxySectionDef">

## Friends

### LoopVectorizationPlanner {#a409249e01d3e65716e4c76fa3369a4e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner">LoopVectorizationPlanner</a></td>
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


<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Reference <a href="#a409249e01d3e65716e4c76fa3369a4e0">LoopVectorizationPlanner</a>.</p>


<p>Referenced by <a href="#a409249e01d3e65716e4c76fa3369a4e0">LoopVectorizationPlanner</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InnerLoopVectorizer() {#a6c7095217b0d803a65548373bd4db3cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InnerLoopVectorizer::InnerLoopVectorizer (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * OrigLoop, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VecWidth, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> MinProfitableTripCount, unsigned UnrollFactor, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality">LoopVectorizationLegality</a> * LVL, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel">LoopVectorizationCostModel</a> * CM, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, GeneratedRTChecks &amp; RTChecks, <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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



<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="#aa7526ec0b5613cd07130c3d097799534">AC</a>, <a href="#a34df1386ff3adb63b4b4bf65409e716b">BFI</a>, <a href="#ac3679e1fff2d21c2034c7ce14df24bf7">Builder</a>, <a href="#a325b208d89f2e70ee7b565dbc671fbfd">Cost</a>, <a href="#a909bc9150f12c6ee1f276b2bb58508ff">DT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec7c967a5416fa6e154433965357a50ea089e7eb4db258e05f70eef4ed5aa10bb">llvm::IRPass</a>, <a href="#a6bb946cd99f8c37f0145265914aea778">Legal</a>, <a href="#a7d4ba65978a0ecb42764cb2b25edc071">LI</a>, <a href="#a1f52585230b8a3cb8bf4a30f8e51bfb4">MinProfitableTripCount</a>, <a href="#a93a8f97a1e57c3bce2e7c3473d592c01">OptForSizeBasedOnProfile</a>, <a href="#a42f4c06af5cd58b1f8a7e54b3ae4316a">ORE</a>, <a href="#af550e4457b9c8a2840a80627713611a9">OrigLoop</a>, <a href="#a7084dff77ae071151848a0ca10125184">Plan</a>, <a href="#a79a00ec9570d7ae0b7fd17387e3d151f">PSE</a>, <a href="#a866b987577621ecd4c7adfebaa57de15">PSI</a>, <a href="#ae9880a8edd20b3b9b1527ecd5a03ac8c">RTChecks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3af72f14ea20f2c762c751d2d49e5ea3">llvm::shouldOptimizeForSize</a>, <a href="#a0e1902405fb476065f5fd61c563f3567">TLI</a>, <a href="#a238e95d82d095fec9241f2f5b81db3c5">TTI</a>, <a href="#ae1d8518bd0c514e739180737faf538be">UF</a>, <a href="#a6b18db1093ed5460e67e9058b89e385b">VectorPHVPB</a> and <a href="#af3ab15d9c94890e913009977bae315ce">VF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#a0a9465c209525e66b0e00ff32fe4495d">llvm::InnerLoopAndEpilogueVectorizer::InnerLoopAndEpilogueVectorizer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~InnerLoopVectorizer() {#aecacb69b3a2334317cce2a7856f7d30d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::InnerLoopVectorizer::~InnerLoopVectorizer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### areSafetyChecksAdded() {#a2e066ef7bc9673cbb2a825189491577d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InnerLoopVectorizer::areSafetyChecksAdded ()</td>
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



<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Reference <a href="#a645c5c5c1e89cb56be66db8db877001d">AddedSafetyChecks</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### createVectorizedLoopSkeleton() {#a31f933a6eada9926c9e320db27dfb775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * InnerLoopVectorizer::createVectorizedLoopSkeleton (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SCEV2ValueTy &amp; ExpandedSCEVs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new empty loop that will contain vectorized instructions later on, while the old loop will be used as the scalar remainder.</p>


<p>Control flow is generated around the vectorized (and scalar epilogue) loops consisting of various checks and bypasses. Return the pre-header block of the new loop. In the case of epilogue vectorization, this function is overriden to handle the more complex control flow around the loops. <span class="doxyComputerOutput">ExpandedSCEVs</span> is used to look up <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expansions for expressions needed during skeleton creation.</p>


<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="#a5e719da4709193fd5b4632da4bc69795">createVectorLoopSkeleton</a>, <a href="#a72c491cdf8cf0283d87008831431f917">emitIterationCountCheck</a>, <a href="#a625caa931f0d8ef201041febbfe42cca">emitMemRuntimeChecks</a>, <a href="#a30c4bcea7beb42c7eb075a578bc3bc3e">emitSCEVChecks</a>, <a href="#a68ebc27127cd32d3fa276621fb69342b">LoopScalarPreHeader</a> and <a href="#a99d1430a4b51d71f77d78febb40f9d32">LoopVectorPreHeader</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>.</p>

</div>
</div>

### fixNonInductionPHIs() {#accb5ce221150790c36b2d96af1be821c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InnerLoopVectorizer::fixNonInductionPHIs (<a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> &amp; State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fix the non-induction PHIs in <span class="doxyComputerOutput">Plan</span>.</p>

<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a0360eea6cebcb1470f84b11f7ba51f16">llvm::VPBlockUtils::blocksOnly</a>, <a href="#ac3679e1fff2d21c2034c7ce14df24bf7">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenphirecipe/#afbde244c417036adb55cbc687de70971">llvm::VPWidenPHIRecipe::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenphirecipe/#a48a84a2d77d942f724c87bc7657c4355">llvm::VPWidenPHIRecipe::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a5b21038d9b822b20c59e7ce5b12582e1">llvm::VPUser::getNumOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a7084dff77ae071151848a0ca10125184">Plan</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a495c27cd70886cb8647df0ecdd9cc63d">llvm::vp_depth_first_deep</a>.</p>


<p>Referenced by <a href="#a9484786140efebf774cde8f072894246">fixVectorizedLoop</a>.</p>

</div>
</div>

### fixVectorizedLoop() {#a9484786140efebf774cde8f072894246}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InnerLoopVectorizer::fixVectorizedLoop (<a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> &amp; State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fix the vectorized code, taking care of header phi's, and more.</p>

<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#acc13ee8b8985399901ac09b51822e21a">cse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ef0a19ea2267182eb0da4f6e191b59b">llvm::EnableVPlanNativePath</a>, <a href="#accb5ce221150790c36b2d96af1be821c">fixNonInductionPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="#a7d4ba65978a0ecb42764cb2b25edc071">LI</a>, <a href="#af550e4457b9c8a2840a80627713611a9">OrigLoop</a>, <a href="#a47eab9fa7cfa73af0b164da3fca49a0f">PredicatedInstructions</a>, <a href="#a79a00ec9570d7ae0b7fd17387e3d151f">PSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaf345c258e6fd97a551e4d5b41607e32">llvm::setProfileInfoAfterUnrolling</a>, <a href="#a0a5c60e5cebd520f95b9813fd9807016">sinkScalarOperands</a>, <a href="#ae1d8518bd0c514e739180737faf538be">UF</a> and <a href="#af3ab15d9c94890e913009977bae315ce">VF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>.</p>

</div>
</div>

### getAdditionalBypassBlock() {#a8f2e87f456c35fdad0ec24e7c71a92a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::InnerLoopVectorizer::getAdditionalBypassBlock ()</td>
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

<p>Return the additional bypass block which targets the scalar loop by skipping the epilogue loop after completing the main loop.</p>

<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="#a329ce2a6185c5e632406d1d2fc75610e">AdditionalBypassBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a69c116deda6ae831a71558a4630323cb">createInductionAdditionalBypassValues</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>.</p>

</div>
</div>

### getInductionAdditionalBypassValue() {#a86acbbb5785d46e5a10d2ed34c779dd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::InnerLoopVectorizer::getInductionAdditionalBypassValue (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * OrigPhi)</td>
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

<p>induction header phi.</p>

<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Reference <a href="#a48c4aed6852a39d4dcc584ac75cc1055">Induction2AdditionalBypassValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>.</p>

</div>
</div>

### getTripCount() {#a35de654dc8297fa810c78922102bb696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::InnerLoopVectorizer::getTripCount ()</td>
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

<p>Returns the original loop trip count.</p>

<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Reference <a href="#a0937fe0c707a3cd1198cea4467fa37c0">TripCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aeeb47f904372b9e25b9f7ba606158b25">llvm::EpilogueVectorizerMainLoop::emitIterationCountCheck</a>, <a href="#a72c491cdf8cf0283d87008831431f917">emitIterationCountCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>, <a href="#aa83b181aa14d5afe1390faad388f91a4">getOrCreateVectorTripCount</a> and <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### scalarizeInstruction() {#a4690286163882c35068b1908f4d752fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InnerLoopVectorizer::scalarizeInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Instr, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe">VPReplicateRecipe</a> * RepRecipe, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vplane">VPLane</a> &amp; Lane, <a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> &amp; State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A helper function to scalarize a single <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> in the innermost loop.</p>


<p>Generates a sequence of scalar instances for each lane between <span class="doxyComputerOutput">MinLane</span> and <span class="doxyComputerOutput">MaxLane</span>, times each part between <span class="doxyComputerOutput">MinPart</span> and <span class="doxyComputerOutput">MaxPart</span>, inclusive. Uses the <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> operands from <span class="doxyComputerOutput">RepRecipe</span> instead of <span class="doxyComputerOutput">Instr's</span> operands.</p>


<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="#aa7526ec0b5613cd07130c3d097799534">AC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/classes/llvm/vplane/#af6be7b0459911799a13a8174138c7020">llvm::VPLane::getFirstLane</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a09de70cbaf2f15aa3b0697b5f378cc9d">llvm::VPBlockBase::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a6c88376daf23b16ad26b7ac6c224d21e">llvm::VPRecipeBase::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a8d57e2fe646928a51e97714005eefdc7">llvm::VPBlockBase::getPlan</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a24555c6ed92715d80348f0991a6d55df">llvm::VPRegionBlock::isReplicator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a002a77cdbc23293b8f7a8458ffd0f905">llvm::vputils::isUniformAfterVectorization</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a11d83265a9e4ff6c6ecd3cf222ad0208">llvm::VPUser::operands</a>, <a href="#a47eab9fa7cfa73af0b164da3fca49a0f">PredicatedInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#a3864f5d4ddd326182fa0499094807f2a">llvm::VPRecipeWithIRFlags::setFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a5fa9b8e1842b354f64c1ba6be0a4a17f">llvm::User::setOperand</a>.</p>

</div>
</div>

### setTripCount() {#a9160ed9f749a9c4df711061181288e13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InnerLoopVectorizer::setTripCount (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * TC)</td>
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

<p>Used to set the trip count after ILV's construction and after the preheader block has been executed.</p>


<p>Note that this always holds the trip count of the original loop for both main loop and epilogue vectorization.</p>


<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Reference <a href="#a0937fe0c707a3cd1198cea4467fa37c0">TripCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a> and <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### createInductionAdditionalBypassValues() {#a69c116deda6ae831a71558a4630323cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InnerLoopVectorizer::createInductionAdditionalBypassValues (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SCEV2ValueTy &amp; ExpandedSCEVs, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * MainVectorTripCount)</td>
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

<p>Create and record the values for induction variables to resume coming from the additional bypass block.</p>

<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a23f5821d9ac264ae25dd087747e2c181">emitTransformedIndex</a>, <a href="#a8f2e87f456c35fdad0ec24e7c71a92a5">getAdditionalBypassBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aa8d4cfce02b245d616238ce8eed74718">getExpandedStep</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#a48c4aed6852a39d4dcc584ac75cc1055">Induction2AdditionalBypassValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4956305191cdba7f9995569d011a5ab7">llvm::isa_and_nonnull</a>, <a href="#a6bb946cd99f8c37f0145265914aea778">Legal</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6370e29617c71c8081bbbc68d6058403">llvm::IRBuilderBase::setFastMathFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#ad1b4c0caba0fac3a1486890cd2445040">llvm::EpilogueVectorizerEpilogueLoop::createEpilogueVectorizedLoopSkeleton</a>.</p>

</div>
</div>

### createVectorLoopSkeleton() {#a5e719da4709193fd5b4632da4bc69795}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InnerLoopVectorizer::createVectorLoopSkeleton (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix)</td>
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

<p>Emit basic blocks (prefixed with <span class="doxyComputerOutput">Prefix</span>) for the iteration check, vector loop preheader, middle block and scalar preheader.</p>

<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a325b208d89f2e70ee7b565dbc671fbfd">Cost</a>, <a href="#a909bc9150f12c6ee1f276b2bb58508ff">DT</a>, <a href="#a7d4ba65978a0ecb42764cb2b25edc071">LI</a>, <a href="#a38e6f65b6ccbdebbf2c7a8b078936115">LoopMiddleBlock</a>, <a href="#a68ebc27127cd32d3fa276621fb69342b">LoopScalarPreHeader</a>, <a href="#a99d1430a4b51d71f77d78febb40f9d32">LoopVectorPreHeader</a>, <a href="#af550e4457b9c8a2840a80627713611a9">OrigLoop</a>, <a href="#a7084dff77ae071151848a0ca10125184">Plan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a3a8743a69fac5e7fa9c2b02604b2cf2f">replaceVPBBWithIRVPBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6c9ffe7979754415f4ca0d677174bc2">llvm::SplitBlock</a> and <a href="#af3ab15d9c94890e913009977bae315ce">VF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#ad1b4c0caba0fac3a1486890cd2445040">llvm::EpilogueVectorizerEpilogueLoop::createEpilogueVectorizedLoopSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aa8b67f13fbf902634ecd95060a1cd85f">llvm::EpilogueVectorizerMainLoop::createEpilogueVectorizedLoopSkeleton</a> and <a href="#a31f933a6eada9926c9e320db27dfb775">createVectorizedLoopSkeleton</a>.</p>

</div>
</div>

### emitIterationCountCheck() {#a72c491cdf8cf0283d87008831431f917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InnerLoopVectorizer::emitIterationCountCheck (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Bypass)</td>
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

<p>Emit a bypass check to see if the vector trip count is zero, including if it overflows.</p>

<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad146072469181af4ccb7ef03c28999ba">llvm::ScalarEvolution::applyLoopGuards</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac3679e1fff2d21c2034c7ce14df24bf7">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a325b208d89f2e70ee7b565dbc671fbfd">Cost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a9f40e42226cee617c16cb1c447b115c5">llvm::BranchInst::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4156fb8bcc6a7e29ee021b01d22551e">llvm::createStepForVF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdda41105c5fe36c41d2246b18c1724fa2ff">llvm::DataAndControlFlowWithoutRuntimeCheck</a>, <a href="#a909bc9150f12c6ee1f276b2bb58508ff">DT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a30bd18ac905eacf3601bc6a553a9ff49">llvm::ScalarEvolution::getSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aef9e9fcf4c5dfce90276ca16d91b8e46">llvm::BasicBlock::getTerminator</a>, <a href="#a35de654dc8297fa810c78922102bb696">getTripCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add2fce2ce0e32b20e41b0aa9f8ca70c2">llvm::hasBranchWeightMD</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="#a5222866a9b2208ea05c3e3ed61a313e9">introduceCheckBlockInVPlan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#ab7edde995b7986f98c3f59788b960eba">isIndvarOverflowCheckKnownFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#af74112dae88db73eb5484821b6f0fccd">llvm::ScalarEvolution::isKnownPredicate</a>, <a href="#a7d4ba65978a0ecb42764cb2b25edc071">LI</a>, <a href="#ae7cdd6a7370c1f81936d1b17a6f7c701">LoopBypassBlocks</a>, <a href="#a99d1430a4b51d71f77d78febb40f9d32">LoopVectorPreHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a629884e9a99a9f49106db9e5e6252fcb">MinItersBypassWeights</a>, <a href="#a1f52585230b8a3cb8bf4a30f8e51bfb4">MinProfitableTripCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdda6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="#af550e4457b9c8a2840a80627713611a9">OrigLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a79a00ec9570d7ae0b7fd17387e3d151f">PSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a016a85f7487f995fe80141e102a7a5ae">llvm::ReplaceInstWithInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6cf82c052d63a1b464be8e48ff38c48e">llvm::setBranchWeights</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6c9ffe7979754415f4ca0d677174bc2">llvm::SplitBlock</a>, <a href="#ae1d8518bd0c514e739180737faf538be">UF</a> and <a href="#af3ab15d9c94890e913009977bae315ce">VF</a>.</p>


<p>Referenced by <a href="#a31f933a6eada9926c9e320db27dfb775">createVectorizedLoopSkeleton</a>.</p>

</div>
</div>

### emitMemRuntimeChecks() {#a625caa931f0d8ef201041febbfe42cca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * InnerLoopVectorizer::emitMemRuntimeChecks (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Bypass)</td>
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

<p>Emit bypass checks to check any memory assumptions we may have made.</p>


<p>Returns the block containing the checks or nullptr if no checks have been added.</p>


<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="#a645c5c5c1e89cb56be66db8db877001d">AddedSafetyChecks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a325b208d89f2e70ee7b565dbc671fbfd">Cost</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ef0a19ea2267182eb0da4f6e191b59b">llvm::EnableVPlanNativePath</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a55ab1072c44295ad279535d714a0f33ea278ca681847fb2bad9707f76d899b231">llvm::LoopVectorizeHints::FK_Enabled</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a1b4bf7c97cdc8159fd73d48063f0b250">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a1c455e007178a24dfb18ac0e200ea02c">llvm::Function::hasOptSize</a>, <a href="#a5222866a9b2208ea05c3e3ed61a313e9">introduceCheckBlockInVPlan</a>, <a href="#ae7cdd6a7370c1f81936d1b17a6f7c701">LoopBypassBlocks</a>, <a href="#a99d1430a4b51d71f77d78febb40f9d32">LoopVectorPreHeader</a>, <a href="#a93a8f97a1e57c3bce2e7c3473d592c01">OptForSizeBasedOnProfile</a>, <a href="#a42f4c06af5cd58b1f8a7e54b3ae4316a">ORE</a>, <a href="#af550e4457b9c8a2840a80627713611a9">OrigLoop</a> and <a href="#ae9880a8edd20b3b9b1527ecd5a03ac8c">RTChecks</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aa8b67f13fbf902634ecd95060a1cd85f">llvm::EpilogueVectorizerMainLoop::createEpilogueVectorizedLoopSkeleton</a> and <a href="#a31f933a6eada9926c9e320db27dfb775">createVectorizedLoopSkeleton</a>.</p>

</div>
</div>

### emitSCEVChecks() {#a30c4bcea7beb42c7eb075a578bc3bc3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * InnerLoopVectorizer::emitSCEVChecks (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Bypass)</td>
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

<p>Emit a bypass check to see if all of the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> assumptions we've had to make are correct.</p>


<p>Returns the block containing the checks or nullptr if no checks have been added.</p>


<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="#a645c5c5c1e89cb56be66db8db877001d">AddedSafetyChecks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a325b208d89f2e70ee7b565dbc671fbfd">Cost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a55ab1072c44295ad279535d714a0f33ea278ca681847fb2bad9707f76d899b231">llvm::LoopVectorizeHints::FK_Enabled</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a1b4bf7c97cdc8159fd73d48063f0b250">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a1c455e007178a24dfb18ac0e200ea02c">llvm::Function::hasOptSize</a>, <a href="#a5222866a9b2208ea05c3e3ed61a313e9">introduceCheckBlockInVPlan</a>, <a href="#ae7cdd6a7370c1f81936d1b17a6f7c701">LoopBypassBlocks</a>, <a href="#a99d1430a4b51d71f77d78febb40f9d32">LoopVectorPreHeader</a>, <a href="#a93a8f97a1e57c3bce2e7c3473d592c01">OptForSizeBasedOnProfile</a> and <a href="#ae9880a8edd20b3b9b1527ecd5a03ac8c">RTChecks</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aa8b67f13fbf902634ecd95060a1cd85f">llvm::EpilogueVectorizerMainLoop::createEpilogueVectorizedLoopSkeleton</a> and <a href="#a31f933a6eada9926c9e320db27dfb775">createVectorizedLoopSkeleton</a>.</p>

</div>
</div>

### getOrCreateVectorTripCount() {#aa83b181aa14d5afe1390faad388f91a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * InnerLoopVectorizer::getOrCreateVectorTripCount (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * InsertBlock)</td>
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

<p>Returns (and creates if needed) the trip count of the widened loop.</p>

<p>Definition at line 551 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac3679e1fff2d21c2034c7ce14df24bf7">Builder</a>, <a href="#a325b208d89f2e70ee7b565dbc671fbfd">Cost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4156fb8bcc6a7e29ee021b01d22551e">llvm::createStepForVF</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aef9e9fcf4c5dfce90276ca16d91b8e46">llvm::BasicBlock::getTerminator</a>, <a href="#a35de654dc8297fa810c78922102bb696">getTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="#ae1d8518bd0c514e739180737faf538be">UF</a>, <a href="#a2c95f95757d9c56b7a89d7f8b3278581">VectorTripCount</a> and <a href="#af3ab15d9c94890e913009977bae315ce">VF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aa8b67f13fbf902634ecd95060a1cd85f">llvm::EpilogueVectorizerMainLoop::createEpilogueVectorizedLoopSkeleton</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>.</p>

</div>
</div>

### introduceCheckBlockInVPlan() {#a5222866a9b2208ea05c3e3ed61a313e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InnerLoopVectorizer::introduceCheckBlockInVPlan (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * CheckIRBB)</td>
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

<p>Introduces a new <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> for <span class="doxyComputerOutput">CheckIRBB</span> to Plan between the vector preheader and its predecessor, also connecting the new block to the scalar preheader.</p>

<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a40bc7fec35d7093efcdbadf566d6b5ee">llvm::VPBlockUtils::connectBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a2c13ffed8c55e1b8dd38fedc7e71e7a8">llvm::VPBlockBase::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aeccf6a036968755c6d86e2d2bb17673a">llvm::VPBlockBase::getSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a2057d0749eedf6749f9e1cc6694eb1fd">llvm::VPBlockUtils::insertOnEdge</a>, <a href="#a7084dff77ae071151848a0ca10125184">Plan</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a43f7e15ac1a813112684effc1e5593a4">llvm::VPBlockBase::swapSuccessors</a> and <a href="#a6b18db1093ed5460e67e9058b89e385b">VectorPHVPB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aeeb47f904372b9e25b9f7ba606158b25">llvm::EpilogueVectorizerMainLoop::emitIterationCountCheck</a>, <a href="#a72c491cdf8cf0283d87008831431f917">emitIterationCountCheck</a>, <a href="#a625caa931f0d8ef201041febbfe42cca">emitMemRuntimeChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a04c0081718b0f5113134aa563e1a56ca">llvm::EpilogueVectorizerEpilogueLoop::emitMinimumVectorEpilogueIterCountCheck</a> and <a href="#a30c4bcea7beb42c7eb075a578bc3bc3e">emitSCEVChecks</a>.</p>

</div>
</div>

### printDebugTracesAtEnd() {#a9e275f16680d4f09dbcc0dd7d323a075}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::InnerLoopVectorizer::printDebugTracesAtEnd ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>.</p>

</div>
</div>

### printDebugTracesAtStart() {#a00579d597c88e5f3c51754bcd9ec5658}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::InnerLoopVectorizer::printDebugTracesAtStart ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow subclasses to override and print debug traces before/after vplan execution, when trace information is requested.</p>

<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>.</p>

</div>
</div>

### sinkScalarOperands() {#a0a5c60e5cebd520f95b9813fd9807016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InnerLoopVectorizer::sinkScalarOperands (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * PredInst)</td>
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

<p>Iteratively sink the scalarized operands of a predicated instruction into the block that was created for it.</p>

<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ac178f4fc4e4a0642610c374256b9fb27">llvm::SetVector&lt; T, Vector, Set, N &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aca414c43a6d42c13998208463637a20d">llvm::PHINode::getIncomingValueNumForOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a7d4ba65978a0ecb42764cb2b25edc071">LI</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a2eeb1c7ed1cfe403f2ae0470e36c07e2">llvm::User::op_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#af41f58e730804d10b91fcff39b035f74">llvm::User::op_end</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af9880d625c506aacc716ee1c9a29ff8b">llvm::SetVector&lt; T, Vector, Set, N &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a9484786140efebf774cde8f072894246">fixVectorizedLoop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AC {#aa7526ec0b5613cd07130c3d097799534}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache* llvm::InnerLoopVectorizer::AC</td>
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

<p>Assumption Cache.</p>

<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a2e73500e74115783c3ab0282829aee26">llvm::EpilogueVectorizerEpilogueLoop::EpilogueVectorizerEpilogueLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aacb166cc55976b03684f0d3671cf1179">llvm::EpilogueVectorizerMainLoop::EpilogueVectorizerMainLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#a0a9465c209525e66b0e00ff32fe4495d">llvm::InnerLoopAndEpilogueVectorizer::InnerLoopAndEpilogueVectorizer</a>, <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a> and <a href="#a4690286163882c35068b1908f4d752fd">scalarizeInstruction</a>.</p>

</div>
</div>

### AddedSafetyChecks {#a645c5c5c1e89cb56be66db8db877001d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InnerLoopVectorizer::AddedSafetyChecks = false</td>
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



<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a2e066ef7bc9673cbb2a825189491577d">areSafetyChecksAdded</a>, <a href="#a625caa931f0d8ef201041febbfe42cca">emitMemRuntimeChecks</a> and <a href="#a30c4bcea7beb42c7eb075a578bc3bc3e">emitSCEVChecks</a>.</p>

</div>
</div>

### AdditionalBypassBlock {#a329ce2a6185c5e632406d1d2fc75610e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* llvm::InnerLoopVectorizer::AdditionalBypassBlock = nullptr</td>
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

<p>The additional bypass block which conditionally skips over the epilogue loop after executing the main loop.</p>


<p>Needed to resume inductions and reductions during epilogue vectorization.</p>


<p>Definition at line 677 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#ad1b4c0caba0fac3a1486890cd2445040">llvm::EpilogueVectorizerEpilogueLoop::createEpilogueVectorizedLoopSkeleton</a> and <a href="#a8f2e87f456c35fdad0ec24e7c71a92a5">getAdditionalBypassBlock</a>.</p>

</div>
</div>

### BFI {#a34df1386ff3adb63b4b4bf65409e716b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfo* llvm::InnerLoopVectorizer::BFI</td>
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

<p>BFI and PSI are used to check for profile guided size optimizations.</p>

<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a2e73500e74115783c3ab0282829aee26">llvm::EpilogueVectorizerEpilogueLoop::EpilogueVectorizerEpilogueLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aacb166cc55976b03684f0d3671cf1179">llvm::EpilogueVectorizerMainLoop::EpilogueVectorizerMainLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#a0a9465c209525e66b0e00ff32fe4495d">llvm::InnerLoopAndEpilogueVectorizer::InnerLoopAndEpilogueVectorizer</a> and <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a>.</p>

</div>
</div>

### Builder {#ac3679e1fff2d21c2034c7ce14df24bf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRBuilder llvm::InnerLoopVectorizer::Builder</td>
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

<p>The builder that we use.</p>

<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aeeb47f904372b9e25b9f7ba606158b25">llvm::EpilogueVectorizerMainLoop::emitIterationCountCheck</a>, <a href="#a72c491cdf8cf0283d87008831431f917">emitIterationCountCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a04c0081718b0f5113134aa563e1a56ca">llvm::EpilogueVectorizerEpilogueLoop::emitMinimumVectorEpilogueIterCountCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>, <a href="#accb5ce221150790c36b2d96af1be821c">fixNonInductionPHIs</a>, <a href="#aa83b181aa14d5afe1390faad388f91a4">getOrCreateVectorTripCount</a> and <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a>.</p>

</div>
</div>

### Cost {#a325b208d89f2e70ee7b565dbc671fbfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopVectorizationCostModel* llvm::InnerLoopVectorizer::Cost</td>
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

<p>The profitablity analysis.</p>

<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a5e719da4709193fd5b4632da4bc69795">createVectorLoopSkeleton</a>, <a href="#a72c491cdf8cf0283d87008831431f917">emitIterationCountCheck</a>, <a href="#a625caa931f0d8ef201041febbfe42cca">emitMemRuntimeChecks</a>, <a href="#a30c4bcea7beb42c7eb075a578bc3bc3e">emitSCEVChecks</a>, <a href="#aa83b181aa14d5afe1390faad388f91a4">getOrCreateVectorTripCount</a> and <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a>.</p>

</div>
</div>

### DT {#a909bc9150f12c6ee1f276b2bb58508ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* llvm::InnerLoopVectorizer::DT</td>
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

<p>Dominator Tree.</p>

<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#ad1b4c0caba0fac3a1486890cd2445040">llvm::EpilogueVectorizerEpilogueLoop::createEpilogueVectorizedLoopSkeleton</a>, <a href="#a5e719da4709193fd5b4632da4bc69795">createVectorLoopSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aeeb47f904372b9e25b9f7ba606158b25">llvm::EpilogueVectorizerMainLoop::emitIterationCountCheck</a>, <a href="#a72c491cdf8cf0283d87008831431f917">emitIterationCountCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a04c0081718b0f5113134aa563e1a56ca">llvm::EpilogueVectorizerEpilogueLoop::emitMinimumVectorEpilogueIterCountCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a2e73500e74115783c3ab0282829aee26">llvm::EpilogueVectorizerEpilogueLoop::EpilogueVectorizerEpilogueLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aacb166cc55976b03684f0d3671cf1179">llvm::EpilogueVectorizerMainLoop::EpilogueVectorizerMainLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#a0a9465c209525e66b0e00ff32fe4495d">llvm::InnerLoopAndEpilogueVectorizer::InnerLoopAndEpilogueVectorizer</a> and <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a>.</p>

</div>
</div>

### Induction2AdditionalBypassValue {#a48c4aed6852a39d4dcc584ac75cc1055}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;PHINode *, Value *&gt; llvm::InnerLoopVectorizer::Induction2AdditionalBypassValue</td>
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

<p>Mapping of induction phis to their additional bypass values.</p>


<p>They need to be added as operands to phi nodes in the scalar loop preheader after the epilogue skeleton has been created.</p>


<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a69c116deda6ae831a71558a4630323cb">createInductionAdditionalBypassValues</a> and <a href="#a86acbbb5785d46e5a10d2ed34c779dd9">getInductionAdditionalBypassValue</a>.</p>

</div>
</div>

### Legal {#a6bb946cd99f8c37f0145265914aea778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopVectorizationLegality* llvm::InnerLoopVectorizer::Legal</td>
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

<p>The legality analysis.</p>

<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a69c116deda6ae831a71558a4630323cb">createInductionAdditionalBypassValues</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a> and <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a>.</p>

</div>
</div>

### LI {#a7d4ba65978a0ecb42764cb2b25edc071}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* llvm::InnerLoopVectorizer::LI</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> Info.</p>

<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#ad1b4c0caba0fac3a1486890cd2445040">llvm::EpilogueVectorizerEpilogueLoop::createEpilogueVectorizedLoopSkeleton</a>, <a href="#a5e719da4709193fd5b4632da4bc69795">createVectorLoopSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aeeb47f904372b9e25b9f7ba606158b25">llvm::EpilogueVectorizerMainLoop::emitIterationCountCheck</a>, <a href="#a72c491cdf8cf0283d87008831431f917">emitIterationCountCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a2e73500e74115783c3ab0282829aee26">llvm::EpilogueVectorizerEpilogueLoop::EpilogueVectorizerEpilogueLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aacb166cc55976b03684f0d3671cf1179">llvm::EpilogueVectorizerMainLoop::EpilogueVectorizerMainLoop</a>, <a href="#a9484786140efebf774cde8f072894246">fixVectorizedLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#a0a9465c209525e66b0e00ff32fe4495d">llvm::InnerLoopAndEpilogueVectorizer::InnerLoopAndEpilogueVectorizer</a>, <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a> and <a href="#a0a5c60e5cebd520f95b9813fd9807016">sinkScalarOperands</a>.</p>

</div>
</div>

### LoopBypassBlocks {#ae7cdd6a7370c1f81936d1b17a6f7c701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;BasicBlock *, 4&gt; llvm::InnerLoopVectorizer::LoopBypassBlocks</td>
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

<p>A list of all bypass blocks. The first block is the entry of the loop.</p>

<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#ad1b4c0caba0fac3a1486890cd2445040">llvm::EpilogueVectorizerEpilogueLoop::createEpilogueVectorizedLoopSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aeeb47f904372b9e25b9f7ba606158b25">llvm::EpilogueVectorizerMainLoop::emitIterationCountCheck</a>, <a href="#a72c491cdf8cf0283d87008831431f917">emitIterationCountCheck</a>, <a href="#a625caa931f0d8ef201041febbfe42cca">emitMemRuntimeChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a04c0081718b0f5113134aa563e1a56ca">llvm::EpilogueVectorizerEpilogueLoop::emitMinimumVectorEpilogueIterCountCheck</a> and <a href="#a30c4bcea7beb42c7eb075a578bc3bc3e">emitSCEVChecks</a>.</p>

</div>
</div>

### LoopMiddleBlock {#a38e6f65b6ccbdebbf2c7a8b078936115}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* llvm::InnerLoopVectorizer::LoopMiddleBlock</td>
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

<p>Middle Block between the vector and the scalar.</p>

<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a5e719da4709193fd5b4632da4bc69795">createVectorLoopSkeleton</a>.</p>

</div>
</div>

### LoopScalarPreHeader {#a68ebc27127cd32d3fa276621fb69342b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* llvm::InnerLoopVectorizer::LoopScalarPreHeader</td>
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

<p>The scalar-loop preheader.</p>

<p>Definition at line 631 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#ad1b4c0caba0fac3a1486890cd2445040">llvm::EpilogueVectorizerEpilogueLoop::createEpilogueVectorizedLoopSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aa8b67f13fbf902634ecd95060a1cd85f">llvm::EpilogueVectorizerMainLoop::createEpilogueVectorizedLoopSkeleton</a>, <a href="#a31f933a6eada9926c9e320db27dfb775">createVectorizedLoopSkeleton</a> and <a href="#a5e719da4709193fd5b4632da4bc69795">createVectorLoopSkeleton</a>.</p>

</div>
</div>

### LoopVectorPreHeader {#a99d1430a4b51d71f77d78febb40f9d32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* llvm::InnerLoopVectorizer::LoopVectorPreHeader</td>
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

<p>The vector-loop preheader.</p>

<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#ad1b4c0caba0fac3a1486890cd2445040">llvm::EpilogueVectorizerEpilogueLoop::createEpilogueVectorizedLoopSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aa8b67f13fbf902634ecd95060a1cd85f">llvm::EpilogueVectorizerMainLoop::createEpilogueVectorizedLoopSkeleton</a>, <a href="#a31f933a6eada9926c9e320db27dfb775">createVectorizedLoopSkeleton</a>, <a href="#a5e719da4709193fd5b4632da4bc69795">createVectorLoopSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aeeb47f904372b9e25b9f7ba606158b25">llvm::EpilogueVectorizerMainLoop::emitIterationCountCheck</a>, <a href="#a72c491cdf8cf0283d87008831431f917">emitIterationCountCheck</a>, <a href="#a625caa931f0d8ef201041febbfe42cca">emitMemRuntimeChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a04c0081718b0f5113134aa563e1a56ca">llvm::EpilogueVectorizerEpilogueLoop::emitMinimumVectorEpilogueIterCountCheck</a>, <a href="#a30c4bcea7beb42c7eb075a578bc3bc3e">emitSCEVChecks</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>.</p>

</div>
</div>

### MinProfitableTripCount {#a1f52585230b8a3cb8bf4a30f8e51bfb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElementCount llvm::InnerLoopVectorizer::MinProfitableTripCount</td>
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



<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a72c491cdf8cf0283d87008831431f917">emitIterationCountCheck</a> and <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a>.</p>

</div>
</div>

### OptForSizeBasedOnProfile {#a93a8f97a1e57c3bce2e7c3473d592c01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InnerLoopVectorizer::OptForSizeBasedOnProfile</td>
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



<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a625caa931f0d8ef201041febbfe42cca">emitMemRuntimeChecks</a>, <a href="#a30c4bcea7beb42c7eb075a578bc3bc3e">emitSCEVChecks</a> and <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a>.</p>

</div>
</div>

### ORE {#a42f4c06af5cd58b1f8a7e54b3ae4316a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter* llvm::InnerLoopVectorizer::ORE</td>
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

<p>Interface to emit optimization remarks.</p>

<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a625caa931f0d8ef201041febbfe42cca">emitMemRuntimeChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a2e73500e74115783c3ab0282829aee26">llvm::EpilogueVectorizerEpilogueLoop::EpilogueVectorizerEpilogueLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aacb166cc55976b03684f0d3671cf1179">llvm::EpilogueVectorizerMainLoop::EpilogueVectorizerMainLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#a0a9465c209525e66b0e00ff32fe4495d">llvm::InnerLoopAndEpilogueVectorizer::InnerLoopAndEpilogueVectorizer</a> and <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a>.</p>

</div>
</div>

### OrigLoop {#af550e4457b9c8a2840a80627713611a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* llvm::InnerLoopVectorizer::OrigLoop</td>
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

<p>The original loop.</p>

<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a5e719da4709193fd5b4632da4bc69795">createVectorLoopSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aeeb47f904372b9e25b9f7ba606158b25">llvm::EpilogueVectorizerMainLoop::emitIterationCountCheck</a>, <a href="#a72c491cdf8cf0283d87008831431f917">emitIterationCountCheck</a>, <a href="#a625caa931f0d8ef201041febbfe42cca">emitMemRuntimeChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a04c0081718b0f5113134aa563e1a56ca">llvm::EpilogueVectorizerEpilogueLoop::emitMinimumVectorEpilogueIterCountCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a2e73500e74115783c3ab0282829aee26">llvm::EpilogueVectorizerEpilogueLoop::EpilogueVectorizerEpilogueLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aacb166cc55976b03684f0d3671cf1179">llvm::EpilogueVectorizerMainLoop::EpilogueVectorizerMainLoop</a>, <a href="#a9484786140efebf774cde8f072894246">fixVectorizedLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#a0a9465c209525e66b0e00ff32fe4495d">llvm::InnerLoopAndEpilogueVectorizer::InnerLoopAndEpilogueVectorizer</a>, <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a07454ac2b11a89ba60771243779a58e4">llvm::EpilogueVectorizerEpilogueLoop::printDebugTracesAtEnd</a> and <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#a87a0c8bda4e9e23e896e46d0a2208c17">llvm::EpilogueVectorizerMainLoop::printDebugTracesAtEnd</a>.</p>

</div>
</div>

### Plan {#a7084dff77ae071151848a0ca10125184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPlan&amp; llvm::InnerLoopVectorizer::Plan</td>
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



<p>Definition at line 679 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a5e719da4709193fd5b4632da4bc69795">createVectorLoopSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a04c0081718b0f5113134aa563e1a56ca">llvm::EpilogueVectorizerEpilogueLoop::emitMinimumVectorEpilogueIterCountCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a2e73500e74115783c3ab0282829aee26">llvm::EpilogueVectorizerEpilogueLoop::EpilogueVectorizerEpilogueLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aacb166cc55976b03684f0d3671cf1179">llvm::EpilogueVectorizerMainLoop::EpilogueVectorizerMainLoop</a>, <a href="#accb5ce221150790c36b2d96af1be821c">fixNonInductionPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#a0a9465c209525e66b0e00ff32fe4495d">llvm::InnerLoopAndEpilogueVectorizer::InnerLoopAndEpilogueVectorizer</a>, <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a> and <a href="#a5222866a9b2208ea05c3e3ed61a313e9">introduceCheckBlockInVPlan</a>.</p>

</div>
</div>

### PredicatedInstructions {#a47eab9fa7cfa73af0b164da3fca49a0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction *, 4&gt; llvm::InnerLoopVectorizer::PredicatedInstructions</td>
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

<p>Store instructions that were predicated.</p>

<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a9484786140efebf774cde8f072894246">fixVectorizedLoop</a> and <a href="#a4690286163882c35068b1908f4d752fd">scalarizeInstruction</a>.</p>

</div>
</div>

### PSE {#a79a00ec9570d7ae0b7fd17387e3d151f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredicatedScalarEvolution&amp; llvm::InnerLoopVectorizer::PSE</td>
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

<p>A wrapper around <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> used to add runtime <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> checks.</p>


<p>Applies dynamic knowledge to simplify <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expressions and converts them to a more usable form.</p>


<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a72c491cdf8cf0283d87008831431f917">emitIterationCountCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a2e73500e74115783c3ab0282829aee26">llvm::EpilogueVectorizerEpilogueLoop::EpilogueVectorizerEpilogueLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aacb166cc55976b03684f0d3671cf1179">llvm::EpilogueVectorizerMainLoop::EpilogueVectorizerMainLoop</a>, <a href="#a9484786140efebf774cde8f072894246">fixVectorizedLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#a0a9465c209525e66b0e00ff32fe4495d">llvm::InnerLoopAndEpilogueVectorizer::InnerLoopAndEpilogueVectorizer</a> and <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a>.</p>

</div>
</div>

### PSI {#a866b987577621ecd4c7adfebaa57de15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfileSummaryInfo* llvm::InnerLoopVectorizer::PSI</td>
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



<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a2e73500e74115783c3ab0282829aee26">llvm::EpilogueVectorizerEpilogueLoop::EpilogueVectorizerEpilogueLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aacb166cc55976b03684f0d3671cf1179">llvm::EpilogueVectorizerMainLoop::EpilogueVectorizerMainLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#a0a9465c209525e66b0e00ff32fe4495d">llvm::InnerLoopAndEpilogueVectorizer::InnerLoopAndEpilogueVectorizer</a> and <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a>.</p>

</div>
</div>

### RTChecks {#ae9880a8edd20b3b9b1527ecd5a03ac8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GeneratedRTChecks&amp; llvm::InnerLoopVectorizer::RTChecks</td>
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

<p>Structure to hold information about generated runtime checks, responsible for cleaning the checks, if vectorization turns out unprofitable.</p>

<p>Definition at line 667 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a625caa931f0d8ef201041febbfe42cca">emitMemRuntimeChecks</a>, <a href="#a30c4bcea7beb42c7eb075a578bc3bc3e">emitSCEVChecks</a> and <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a>.</p>

</div>
</div>

### TLI {#a0e1902405fb476065f5fd61c563f3567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo* llvm::InnerLoopVectorizer::TLI</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Library Info.</p>

<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a2e73500e74115783c3ab0282829aee26">llvm::EpilogueVectorizerEpilogueLoop::EpilogueVectorizerEpilogueLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aacb166cc55976b03684f0d3671cf1179">llvm::EpilogueVectorizerMainLoop::EpilogueVectorizerMainLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#a0a9465c209525e66b0e00ff32fe4495d">llvm::InnerLoopAndEpilogueVectorizer::InnerLoopAndEpilogueVectorizer</a> and <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a>.</p>

</div>
</div>

### TripCount {#a0937fe0c707a3cd1198cea4467fa37c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::InnerLoopVectorizer::TripCount = nullptr</td>
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

<p>Trip count of the original loop.</p>

<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a2e73500e74115783c3ab0282829aee26">llvm::EpilogueVectorizerEpilogueLoop::EpilogueVectorizerEpilogueLoop</a>, <a href="#a35de654dc8297fa810c78922102bb696">getTripCount</a> and <a href="#a9160ed9f749a9c4df711061181288e13">setTripCount</a>.</p>

</div>
</div>

### TTI {#a238e95d82d095fec9241f2f5b81db3c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetTransformInfo* llvm::InnerLoopVectorizer::TTI</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Transform Info.</p>

<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#a0a9465c209525e66b0e00ff32fe4495d">llvm::InnerLoopAndEpilogueVectorizer::InnerLoopAndEpilogueVectorizer</a> and <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a>.</p>

</div>
</div>

### UF {#ae1d8518bd0c514e739180737faf538be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::InnerLoopVectorizer::UF</td>
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

<p>The vectorization unroll factor to use.</p>


<p>Each scalar is vectorized to this many different vector instructions.</p>


<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aeeb47f904372b9e25b9f7ba606158b25">llvm::EpilogueVectorizerMainLoop::emitIterationCountCheck</a>, <a href="#a72c491cdf8cf0283d87008831431f917">emitIterationCountCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a04c0081718b0f5113134aa563e1a56ca">llvm::EpilogueVectorizerEpilogueLoop::emitMinimumVectorEpilogueIterCountCheck</a>, <a href="#a9484786140efebf774cde8f072894246">fixVectorizedLoop</a>, <a href="#aa83b181aa14d5afe1390faad388f91a4">getOrCreateVectorTripCount</a> and <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a>.</p>

</div>
</div>

### VectorPHVPB {#a6b18db1093ed5460e67e9058b89e385b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBlockBase* llvm::InnerLoopVectorizer::VectorPHVPB</td>
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

<p>The vector preheader block of <span class="doxyComputerOutput">Plan</span>, used as target for check blocks introduced during skeleton creation.</p>

<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a> and <a href="#a5222866a9b2208ea05c3e3ed61a313e9">introduceCheckBlockInVPlan</a>.</p>

</div>
</div>

### VectorTripCount {#a2c95f95757d9c56b7a89d7f8b3278581}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::InnerLoopVectorizer::VectorTripCount = nullptr</td>
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

<p>Trip count of the widened loop (TripCount - TripCount % (VF*UF))</p>

<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#aa83b181aa14d5afe1390faad388f91a4">getOrCreateVectorTripCount</a>.</p>

</div>
</div>

### VF {#af3ab15d9c94890e913009977bae315ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElementCount llvm::InnerLoopVectorizer::VF</td>
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

<p>The vectorization SIMD factor to use.</p>


<p>Each vector will have this many vector elements.</p>


<p>Definition at line 614 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a5e719da4709193fd5b4632da4bc69795">createVectorLoopSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aeeb47f904372b9e25b9f7ba606158b25">llvm::EpilogueVectorizerMainLoop::emitIterationCountCheck</a>, <a href="#a72c491cdf8cf0283d87008831431f917">emitIterationCountCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a04c0081718b0f5113134aa563e1a56ca">llvm::EpilogueVectorizerEpilogueLoop::emitMinimumVectorEpilogueIterCountCheck</a>, <a href="#a9484786140efebf774cde8f072894246">fixVectorizedLoop</a>, <a href="#aa83b181aa14d5afe1390faad388f91a4">getOrCreateVectorTripCount</a> and <a href="#a6c7095217b0d803a65548373bd4db3cf">InnerLoopVectorizer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
