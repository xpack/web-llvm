---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/epiloguevectorizerepilogueloop
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `EpilogueVectorizerEpilogueLoop` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::EpilogueVectorizerEpilogueLoop { ... }
</div>

## Base class

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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e73500e74115783c3ab0282829aee26">EpilogueVectorizerEpilogueLoop</a> (Loop *OrigLoop, PredicatedScalarEvolution &amp;PSE, LoopInfo *LI, DominatorTree *DT, const TargetLibraryInfo *TLI, const TargetTransformInfo *TTI, AssumptionCache *AC, OptimizationRemarkEmitter *ORE, EpilogueLoopVectorizationInfo &amp;EPI, LoopVectorizationLegality *LVL, llvm::LoopVectorizationCostModel *CM, BlockFrequencyInfo *BFI, ProfileSummaryInfo *PSI, GeneratedRTChecks &amp;Checks, VPlan &amp;Plan)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1b4c0caba0fac3a1486890cd2445040">createEpilogueVectorizedLoopSkeleton</a> (const SCEV2ValueTy &amp;ExpandedSCEVs) final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implements the interface for creating a vectorized skeleton using the <em>epilogue loop</em> strategy (ie the second pass of vplan execution). <a href="#ad1b4c0caba0fac3a1486890cd2445040">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04c0081718b0f5113134aa563e1a56ca">emitMinimumVectorEpilogueIterCountCheck</a> (BasicBlock *Bypass, BasicBlock *Insert)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits an iteration count bypass check after the main vector loop has finished to see if there are any iterations left to execute by either the vector epilogue or the scalar epilogue. <a href="#a04c0081718b0f5113134aa563e1a56ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d4052b05414daf596711bada5c5e94b">printDebugTracesAtStart</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow subclasses to override and print debug traces before/after vplan execution, when trace information is requested. <a href="#a9d4052b05414daf596711bada5c5e94b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07454ac2b11a89ba60771243779a58e4">printDebugTracesAtEnd</a> () override</td>
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


<p>Definition at line 788 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### EpilogueVectorizerEpilogueLoop() {#a2e73500e74115783c3ab0282829aee26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::EpilogueVectorizerEpilogueLoop::EpilogueVectorizerEpilogueLoop (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * OrigLoop, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE, <a href="/web-llvm/docs/api/structs/llvm/epilogueloopvectorizationinfo">EpilogueLoopVectorizationInfo</a> &amp; EPI, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality">LoopVectorizationLegality</a> * LVL, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel">llvm::LoopVectorizationCostModel</a> * CM, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, GeneratedRTChecks &amp; Checks, <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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



<p>Definition at line 790 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#aa7526ec0b5613cd07130c3d097799534">llvm::InnerLoopVectorizer::AC</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a34df1386ff3adb63b4b4bf65409e716b">llvm::InnerLoopVectorizer::BFI</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a909bc9150f12c6ee1f276b2bb58508ff">llvm::InnerLoopVectorizer::DT</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#ae920fcb4fb4b5099acbbf972af04447e">llvm::InnerLoopAndEpilogueVectorizer::EPI</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#a0a9465c209525e66b0e00ff32fe4495d">llvm::InnerLoopAndEpilogueVectorizer::InnerLoopAndEpilogueVectorizer</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a7d4ba65978a0ecb42764cb2b25edc071">llvm::InnerLoopVectorizer::LI</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a42f4c06af5cd58b1f8a7e54b3ae4316a">llvm::InnerLoopVectorizer::ORE</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#af550e4457b9c8a2840a80627713611a9">llvm::InnerLoopVectorizer::OrigLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a7084dff77ae071151848a0ca10125184">llvm::InnerLoopVectorizer::Plan</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a79a00ec9570d7ae0b7fd17387e3d151f">llvm::InnerLoopVectorizer::PSE</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a866b987577621ecd4c7adfebaa57de15">llvm::InnerLoopVectorizer::PSI</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a0e1902405fb476065f5fd61c563f3567">llvm::InnerLoopVectorizer::TLI</a> and <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a0937fe0c707a3cd1198cea4467fa37c0">llvm::InnerLoopVectorizer::TripCount</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createEpilogueVectorizedLoopSkeleton() {#ad1b4c0caba0fac3a1486890cd2445040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * EpilogueVectorizerEpilogueLoop::createEpilogueVectorizedLoopSkeleton (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SCEV2ValueTy &amp; ExpandedSCEVs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implements the interface for creating a vectorized skeleton using the <em>epilogue loop</em> strategy (ie the second pass of vplan execution).</p>


<p>This function is partially responsible for generating the control flow depicted in <a href="https://llvm.org/docs/Vectorizers.html#epilogue-vectorization">https://llvm.org/docs/Vectorizers.html#epilogue-vectorization</a>.</p>


<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a329ce2a6185c5e632406d1d2fc75610e">llvm::InnerLoopVectorizer::AdditionalBypassBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a69c116deda6ae831a71558a4630323cb">llvm::InnerLoopVectorizer::createInductionAdditionalBypassValues</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a5e719da4709193fd5b4632da4bc69795">llvm::InnerLoopVectorizer::createVectorLoopSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a909bc9150f12c6ee1f276b2bb58508ff">llvm::InnerLoopVectorizer::DT</a>, <a href="#a04c0081718b0f5113134aa563e1a56ca">emitMinimumVectorEpilogueIterCountCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#ae920fcb4fb4b5099acbbf972af04447e">llvm::InnerLoopAndEpilogueVectorizer::EPI</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a59fb91d1691350f7d1b8e8a114e3f2a4">llvm::BasicBlock::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a7d4ba65978a0ecb42764cb2b25edc071">llvm::InnerLoopVectorizer::LI</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#ae7cdd6a7370c1f81936d1b17a6f7c701">llvm::InnerLoopVectorizer::LoopBypassBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a68ebc27127cd32d3fa276621fb69342b">llvm::InnerLoopVectorizer::LoopScalarPreHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a99d1430a4b51d71f77d78febb40f9d32">llvm::InnerLoopVectorizer::LoopVectorPreHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a13da92d2694197fbcb5b95fd94e7570d">llvm::BasicBlock::phis</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac6c9ffe7979754415f4ca0d677174bc2">llvm::SplitBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### emitMinimumVectorEpilogueIterCountCheck() {#a04c0081718b0f5113134aa563e1a56ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * EpilogueVectorizerEpilogueLoop::emitMinimumVectorEpilogueIterCountCheck (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Bypass, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Insert)</td>
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

<p>Emits an iteration count bypass check after the main vector loop has finished to see if there are any iterations left to execute by either the vector epilogue or the scalar epilogue.</p>

<p>Definition at line 811 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#ac3679e1fff2d21c2034c7ce14df24bf7">llvm::InnerLoopVectorizer::Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a9f40e42226cee617c16cb1c447b115c5">llvm::BranchInst::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4156fb8bcc6a7e29ee021b01d22551e">llvm::createStepForVF</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a909bc9150f12c6ee1f276b2bb58508ff">llvm::InnerLoopVectorizer::DT</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#ae920fcb4fb4b5099acbbf972af04447e">llvm::InnerLoopAndEpilogueVectorizer::EPI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add2fce2ce0e32b20e41b0aa9f8ca70c2">llvm::hasBranchWeightMD</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a5222866a9b2208ea05c3e3ed61a313e9">llvm::InnerLoopVectorizer::introduceCheckBlockInVPlan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#ae7cdd6a7370c1f81936d1b17a6f7c701">llvm::InnerLoopVectorizer::LoopBypassBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a99d1430a4b51d71f77d78febb40f9d32">llvm::InnerLoopVectorizer::LoopVectorPreHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#af550e4457b9c8a2840a80627713611a9">llvm::InnerLoopVectorizer::OrigLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a7084dff77ae071151848a0ca10125184">llvm::InnerLoopVectorizer::Plan</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a63345282cd67ea46202fb33523be1408">llvm::VPBlockUtils::reassociateBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a016a85f7487f995fe80141e102a7a5ae">llvm::ReplaceInstWithInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6cf82c052d63a1b464be8e48ff38c48e">llvm::setBranchWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#ae1d8518bd0c514e739180737faf538be">llvm::InnerLoopVectorizer::UF</a> and <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#af3ab15d9c94890e913009977bae315ce">llvm::InnerLoopVectorizer::VF</a>.</p>


<p>Referenced by <a href="#ad1b4c0caba0fac3a1486890cd2445040">createEpilogueVectorizedLoopSkeleton</a>.</p>

</div>
</div>

### printDebugTracesAtEnd() {#a07454ac2b11a89ba60771243779a58e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EpilogueVectorizerEpilogueLoop::printDebugTracesAtEnd ()</td>
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



<p>Definition at line 815 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#af550e4457b9c8a2840a80627713611a9">llvm::InnerLoopVectorizer::OrigLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#ab3595005ef7c117f30d4c18201190bbb">VerboseDebug</a>.</p>

</div>
</div>

### printDebugTracesAtStart() {#a9d4052b05414daf596711bada5c5e94b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EpilogueVectorizerEpilogueLoop::printDebugTracesAtStart ()</td>
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

<p>Allow subclasses to override and print debug traces before/after vplan execution, when trace information is requested.</p>

<p>Definition at line 814 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#ae920fcb4fb4b5099acbbf972af04447e">llvm::InnerLoopAndEpilogueVectorizer::EPI</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

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
