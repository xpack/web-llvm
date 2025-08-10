---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/innerloopandepiloguevectorizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InnerLoopAndEpilogueVectorizer` Class

<p>An extension of the inner loop vectorizer that creates a skeleton for a vectorized loop that has its epilogue (residual) also vectorized. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::InnerLoopAndEpilogueVectorizer { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer">InnerLoopVectorizer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer">InnerLoopVectorizer</a> vectorizes loops which contain only one basic block to a specified vectorization factor (VF). <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop">EpilogueVectorizerEpilogueLoop</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop">EpilogueVectorizerMainLoop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A specialized derived class of inner loop vectorizer that performs vectorization of <em>main</em> loops in the process of vectorizing loops and their epilogues. <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a9465c209525e66b0e00ff32fe4495d">InnerLoopAndEpilogueVectorizer</a> (Loop *OrigLoop, PredicatedScalarEvolution &amp;PSE, LoopInfo *LI, DominatorTree *DT, const TargetLibraryInfo *TLI, const TargetTransformInfo *TTI, AssumptionCache *AC, OptimizationRemarkEmitter *ORE, EpilogueLoopVectorizationInfo &amp;EPI, LoopVectorizationLegality *LVL, llvm::LoopVectorizationCostModel *CM, BlockFrequencyInfo *BFI, ProfileSummaryInfo *PSI, GeneratedRTChecks &amp;Checks, VPlan &amp;Plan)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a513e6b49c17c28104aab6dc635ce86b3">createVectorizedLoopSkeleton</a> (const SCEV2ValueTy &amp;ExpandedSCEVs) final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new empty loop that will contain vectorized instructions later on, while the old loop will be used as the scalar remainder. <a href="#a513e6b49c17c28104aab6dc635ce86b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89ba81e424489963bac21757a4687fe7">createEpilogueVectorizedLoopSkeleton</a> (const SCEV2ValueTy &amp;ExpandedSCEVs)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The interface for creating a vectorized skeleton using one of two different strategies, each corresponding to one execution of the vplan as described above. <a href="#a89ba81e424489963bac21757a4687fe7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/epilogueloopvectorizationinfo">EpilogueLoopVectorizationInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae920fcb4fb4b5099acbbf972af04447e">EPI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds and updates state information required to vectorize the main loop and its epilogue in two separate passes. <a href="#ae920fcb4fb4b5099acbbf972af04447e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An extension of the inner loop vectorizer that creates a skeleton for a vectorized loop that has its epilogue (residual) also vectorized.</p>


<p>The idea is to run the vplan on a given loop twice, firstly to setup the skeleton and vectorize the main loop, and secondly to complete the skeleton from the first step and vectorize the epilogue. This is achieved by deriving two concrete strategy classes from this base class and invoking them in succession from the loop vectorizer planner.</p>


<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InnerLoopAndEpilogueVectorizer() {#a0a9465c209525e66b0e00ff32fe4495d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InnerLoopAndEpilogueVectorizer::InnerLoopAndEpilogueVectorizer (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * OrigLoop, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE, <a href="/web-llvm/docs/api/structs/llvm/epilogueloopvectorizationinfo">EpilogueLoopVectorizationInfo</a> &amp; EPI, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality">LoopVectorizationLegality</a> * LVL, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel">llvm::LoopVectorizationCostModel</a> * CM, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, GeneratedRTChecks &amp; Checks, <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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



<p>Definition at line 721 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#aa7526ec0b5613cd07130c3d097799534">llvm::InnerLoopVectorizer::AC</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a34df1386ff3adb63b4b4bf65409e716b">llvm::InnerLoopVectorizer::BFI</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a909bc9150f12c6ee1f276b2bb58508ff">llvm::InnerLoopVectorizer::DT</a>, <a href="#ae920fcb4fb4b5099acbbf972af04447e">EPI</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a6c7095217b0d803a65548373bd4db3cf">llvm::InnerLoopVectorizer::InnerLoopVectorizer</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a7d4ba65978a0ecb42764cb2b25edc071">llvm::InnerLoopVectorizer::LI</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a42f4c06af5cd58b1f8a7e54b3ae4316a">llvm::InnerLoopVectorizer::ORE</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#af550e4457b9c8a2840a80627713611a9">llvm::InnerLoopVectorizer::OrigLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a7084dff77ae071151848a0ca10125184">llvm::InnerLoopVectorizer::Plan</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a79a00ec9570d7ae0b7fd17387e3d151f">llvm::InnerLoopVectorizer::PSE</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a866b987577621ecd4c7adfebaa57de15">llvm::InnerLoopVectorizer::PSI</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a0e1902405fb476065f5fd61c563f3567">llvm::InnerLoopVectorizer::TLI</a> and <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a238e95d82d095fec9241f2f5b81db3c5">llvm::InnerLoopVectorizer::TTI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a2e73500e74115783c3ab0282829aee26">llvm::EpilogueVectorizerEpilogueLoop::EpilogueVectorizerEpilogueLoop</a> and <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aacb166cc55976b03684f0d3671cf1179">llvm::EpilogueVectorizerMainLoop::EpilogueVectorizerMainLoop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createEpilogueVectorizedLoopSkeleton() {#a89ba81e424489963bac21757a4687fe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual BasicBlock * llvm::InnerLoopAndEpilogueVectorizer::createEpilogueVectorizedLoopSkeleton (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SCEV2ValueTy &amp; ExpandedSCEVs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The interface for creating a vectorized skeleton using one of two different strategies, each corresponding to one execution of the vplan as described above.</p>

<p>Definition at line 745 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a513e6b49c17c28104aab6dc635ce86b3">createVectorizedLoopSkeleton</a>.</p>

</div>
</div>

### createVectorizedLoopSkeleton() {#a513e6b49c17c28104aab6dc635ce86b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::InnerLoopAndEpilogueVectorizer::createVectorizedLoopSkeleton (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SCEV2ValueTy &amp; ExpandedSCEVs)</td>
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

<p>Create a new empty loop that will contain vectorized instructions later on, while the old loop will be used as the scalar remainder.</p>


<p>Control flow is generated around the vectorized (and scalar epilogue) loops consisting of various checks and bypasses. Return the pre-header block of the new loop. In the case of epilogue vectorization, this function is overriden to handle the more complex control flow around the loops. <span class="doxyComputerOutput">ExpandedSCEVs</span> is used to look up <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expansions for expressions needed during skeleton creation.</p>


<p>Definition at line 737 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Reference <a href="#a89ba81e424489963bac21757a4687fe7">createEpilogueVectorizedLoopSkeleton</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### EPI {#ae920fcb4fb4b5099acbbf972af04447e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EpilogueLoopVectorizationInfo&amp; llvm::InnerLoopAndEpilogueVectorizer::EPI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds and updates state information required to vectorize the main loop and its epilogue in two separate passes.</p>


<p>This setup helps us avoid regenerating and recomputing runtime safety checks. It also helps us to shorten the iteration-count-check path length for the cases where the iteration count of the loop is so small that the main vector loop is completely skipped.</p>


<p>Definition at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#ad1b4c0caba0fac3a1486890cd2445040">llvm::EpilogueVectorizerEpilogueLoop::createEpilogueVectorizedLoopSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aa8b67f13fbf902634ecd95060a1cd85f">llvm::EpilogueVectorizerMainLoop::createEpilogueVectorizedLoopSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aeeb47f904372b9e25b9f7ba606158b25">llvm::EpilogueVectorizerMainLoop::emitIterationCountCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a04c0081718b0f5113134aa563e1a56ca">llvm::EpilogueVectorizerEpilogueLoop::emitMinimumVectorEpilogueIterCountCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a2e73500e74115783c3ab0282829aee26">llvm::EpilogueVectorizerEpilogueLoop::EpilogueVectorizerEpilogueLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aacb166cc55976b03684f0d3671cf1179">llvm::EpilogueVectorizerMainLoop::EpilogueVectorizerMainLoop</a>, <a href="#a0a9465c209525e66b0e00ff32fe4495d">InnerLoopAndEpilogueVectorizer</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a9d4052b05414daf596711bada5c5e94b">llvm::EpilogueVectorizerEpilogueLoop::printDebugTracesAtStart</a> and <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aad9eb57dcbd9a2c3fd1993685783d7f7">llvm::EpilogueVectorizerMainLoop::printDebugTracesAtStart</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
