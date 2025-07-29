---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/epiloguevectorizermainloop
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `EpilogueVectorizerMainLoop` Class

<p>A specialized derived class of inner loop vectorizer that performs vectorization of <em>main</em> loops in the process of vectorizing loops and their epilogues. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::EpilogueVectorizerMainLoop { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacb166cc55976b03684f0d3671cf1179">EpilogueVectorizerMainLoop</a> (Loop *OrigLoop, PredicatedScalarEvolution &amp;PSE, LoopInfo *LI, DominatorTree *DT, const TargetLibraryInfo *TLI, const TargetTransformInfo *TTI, AssumptionCache *AC, OptimizationRemarkEmitter *ORE, EpilogueLoopVectorizationInfo &amp;EPI, LoopVectorizationLegality *LVL, llvm::LoopVectorizationCostModel *CM, BlockFrequencyInfo *BFI, ProfileSummaryInfo *PSI, GeneratedRTChecks &amp;Check, VPlan &amp;Plan)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8b67f13fbf902634ecd95060a1cd85f">createEpilogueVectorizedLoopSkeleton</a> (const SCEV2ValueTy &amp;ExpandedSCEVs) final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implements the interface for creating a vectorized skeleton using the <em>main loop</em> strategy (ie the first pass of vplan execution). <a href="#aa8b67f13fbf902634ecd95060a1cd85f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeb47f904372b9e25b9f7ba606158b25">emitIterationCountCheck</a> (BasicBlock *Bypass, bool ForEpilogue)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits an iteration count bypass check once for the main loop (when <span class="doxyComputerOutput">ForEpilogue</span> is false) and once for the epilogue loop (when <span class="doxyComputerOutput">ForEpilogue</span> is true). <a href="#aeeb47f904372b9e25b9f7ba606158b25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad9eb57dcbd9a2c3fd1993685783d7f7">printDebugTracesAtStart</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow subclasses to override and print debug traces before/after vplan execution, when trace information is requested. <a href="#aad9eb57dcbd9a2c3fd1993685783d7f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87a0c8bda4e9e23e896e46d0a2208c17">printDebugTracesAtEnd</a> () override</td>
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

<p>A specialized derived class of inner loop vectorizer that performs vectorization of <em>main</em> loops in the process of vectorizing loops and their epilogues.</p>

<p>Definition at line 759 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### EpilogueVectorizerMainLoop() {#aacb166cc55976b03684f0d3671cf1179}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::EpilogueVectorizerMainLoop::EpilogueVectorizerMainLoop (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * OrigLoop, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE, <a href="/web-llvm/docs/api/structs/llvm/epilogueloopvectorizationinfo">EpilogueLoopVectorizationInfo</a> &amp; EPI, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality">LoopVectorizationLegality</a> * LVL, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel">llvm::LoopVectorizationCostModel</a> * CM, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, GeneratedRTChecks &amp; Check, <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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



<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#aa7526ec0b5613cd07130c3d097799534">llvm::InnerLoopVectorizer::AC</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a34df1386ff3adb63b4b4bf65409e716b">llvm::InnerLoopVectorizer::BFI</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a909bc9150f12c6ee1f276b2bb58508ff">llvm::InnerLoopVectorizer::DT</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#ae920fcb4fb4b5099acbbf972af04447e">llvm::InnerLoopAndEpilogueVectorizer::EPI</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#a0a9465c209525e66b0e00ff32fe4495d">llvm::InnerLoopAndEpilogueVectorizer::InnerLoopAndEpilogueVectorizer</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a7d4ba65978a0ecb42764cb2b25edc071">llvm::InnerLoopVectorizer::LI</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a42f4c06af5cd58b1f8a7e54b3ae4316a">llvm::InnerLoopVectorizer::ORE</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#af550e4457b9c8a2840a80627713611a9">llvm::InnerLoopVectorizer::OrigLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a7084dff77ae071151848a0ca10125184">llvm::InnerLoopVectorizer::Plan</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a79a00ec9570d7ae0b7fd17387e3d151f">llvm::InnerLoopVectorizer::PSE</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a866b987577621ecd4c7adfebaa57de15">llvm::InnerLoopVectorizer::PSI</a> and <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a0e1902405fb476065f5fd61c563f3567">llvm::InnerLoopVectorizer::TLI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createEpilogueVectorizedLoopSkeleton() {#aa8b67f13fbf902634ecd95060a1cd85f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * EpilogueVectorizerMainLoop::createEpilogueVectorizedLoopSkeleton (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SCEV2ValueTy &amp; ExpandedSCEVs)</td>
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

<p>Implements the interface for creating a vectorized skeleton using the <em>main loop</em> strategy (ie the first pass of vplan execution).</p>


<p>This function is partially responsible for generating the control flow depicted in <a href="https://llvm.org/docs/Vectorizers.html#epilogue-vectorization">https://llvm.org/docs/Vectorizers.html#epilogue-vectorization</a>.</p>


<p>Definition at line 774 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a5e719da4709193fd5b4632da4bc69795">llvm::InnerLoopVectorizer::createVectorLoopSkeleton</a>, <a href="#aeeb47f904372b9e25b9f7ba606158b25">emitIterationCountCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a625caa931f0d8ef201041febbfe42cca">llvm::InnerLoopVectorizer::emitMemRuntimeChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a30c4bcea7beb42c7eb075a578bc3bc3e">llvm::InnerLoopVectorizer::emitSCEVChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#ae920fcb4fb4b5099acbbf972af04447e">llvm::InnerLoopAndEpilogueVectorizer::EPI</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#aa83b181aa14d5afe1390faad388f91a4">llvm::InnerLoopVectorizer::getOrCreateVectorTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a68ebc27127cd32d3fa276621fb69342b">llvm::InnerLoopVectorizer::LoopScalarPreHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a99d1430a4b51d71f77d78febb40f9d32">llvm::InnerLoopVectorizer::LoopVectorPreHeader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### emitIterationCountCheck() {#aeeb47f904372b9e25b9f7ba606158b25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * EpilogueVectorizerMainLoop::emitIterationCountCheck (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Bypass, bool ForEpilogue)</td>
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

<p>Emits an iteration count bypass check once for the main loop (when <span class="doxyComputerOutput">ForEpilogue</span> is false) and once for the epilogue loop (when <span class="doxyComputerOutput">ForEpilogue</span> is true).</p>

<p>Definition at line 780 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#ac3679e1fff2d21c2034c7ce14df24bf7">llvm::InnerLoopVectorizer::Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a9f40e42226cee617c16cb1c447b115c5">llvm::BranchInst::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4156fb8bcc6a7e29ee021b01d22551e">llvm::createStepForVF</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a909bc9150f12c6ee1f276b2bb58508ff">llvm::InnerLoopVectorizer::DT</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopandepiloguevectorizer/#ae920fcb4fb4b5099acbbf972af04447e">llvm::InnerLoopAndEpilogueVectorizer::EPI</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a35de654dc8297fa810c78922102bb696">llvm::InnerLoopVectorizer::getTripCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add2fce2ce0e32b20e41b0aa9f8ca70c2">llvm::hasBranchWeightMD</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a5222866a9b2208ea05c3e3ed61a313e9">llvm::InnerLoopVectorizer::introduceCheckBlockInVPlan</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a7d4ba65978a0ecb42764cb2b25edc071">llvm::InnerLoopVectorizer::LI</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#ae7cdd6a7370c1f81936d1b17a6f7c701">llvm::InnerLoopVectorizer::LoopBypassBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a99d1430a4b51d71f77d78febb40f9d32">llvm::InnerLoopVectorizer::LoopVectorPreHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a629884e9a99a9f49106db9e5e6252fcb">MinItersBypassWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#af550e4457b9c8a2840a80627713611a9">llvm::InnerLoopVectorizer::OrigLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a016a85f7487f995fe80141e102a7a5ae">llvm::ReplaceInstWithInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6cf82c052d63a1b464be8e48ff38c48e">llvm::setBranchWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6c9ffe7979754415f4ca0d677174bc2">llvm::SplitBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#ae1d8518bd0c514e739180737faf538be">llvm::InnerLoopVectorizer::UF</a> and <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#af3ab15d9c94890e913009977bae315ce">llvm::InnerLoopVectorizer::VF</a>.</p>


<p>Referenced by <a href="#aa8b67f13fbf902634ecd95060a1cd85f">createEpilogueVectorizedLoopSkeleton</a>.</p>

</div>
</div>

### printDebugTracesAtEnd() {#a87a0c8bda4e9e23e896e46d0a2208c17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EpilogueVectorizerMainLoop::printDebugTracesAtEnd ()</td>
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



<p>Definition at line 782 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#af550e4457b9c8a2840a80627713611a9">llvm::InnerLoopVectorizer::OrigLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#ab3595005ef7c117f30d4c18201190bbb">VerboseDebug</a>.</p>

</div>
</div>

### printDebugTracesAtStart() {#aad9eb57dcbd9a2c3fd1993685783d7f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EpilogueVectorizerMainLoop::printDebugTracesAtStart ()</td>
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

<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
