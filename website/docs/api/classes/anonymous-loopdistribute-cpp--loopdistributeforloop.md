---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LoopDistributeForLoop` Class

<p>The actual class performing the per-loop work. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{LoopDistribute.cpp}::LoopDistributeForLoop { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d2a9f983336be7740745ff4f80c65fd">LoopDistributeForLoop</a> (Loop *L, Function *F, LoopInfo *LI, DominatorTree *DT, ScalarEvolution *SE, LoopAccessInfoManager &amp;LAIs, OptimizationRemarkEmitter *ORE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c63565a36daca6f3bae8a75238ffd50">processLoop</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to distribute an inner-most loop. <a href="#a3c63565a36daca6f3bae8a75238ffd50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e1e58ca451be96cbbff94a01658c988">fail</a> (StringRef RemarkName, StringRef Message)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide diagnostics then. <a href="#a7e1e58ca451be96cbbff94a01658c988">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; bool &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f5fde523aac0f9086c8572e53f7ae72">isForced</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return if distribution forced to be enabled/disabled for the loop. <a href="#a5f5fde523aac0f9086c8572e53f7ae72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a12b6596f3de8ec2382209b04c2b5444c">RuntimePointerCheck</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86d64629e20bf172b2932f93b2649747">includeOnlyCrossPartitionChecks</a> (const SmallVectorImpl&lt; RuntimePointerCheck &gt; &amp;AllChecks, const SmallVectorImpl&lt; int &gt; &amp;PtrToPartition, const RuntimePointerChecking *RtPtrChecking)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Filter out checks between pointers from the same partition. <a href="#a86d64629e20bf172b2932f93b2649747">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae54bdc5cbf490fa7f0a78ffe764dfdd9">setForced</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check whether the loop metadata is forcing distribution to be enabled/disabled. <a href="#ae54bdc5cbf490fa7f0a78ffe764dfdd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca5b85ba6eac33f7744767f6bc5b9f12">L</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51c43c34c33ae20c66eccf058bd7fcb7">F</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac283e082082c6242d2f12a12da22c1a4">LI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo">LoopAccessInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa317295758050394475dcb1cde3fe733">LAI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00029e3633f616a85d3531c0e0a9ea77">DT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a891936e19f27d325698b97db82de8135">SE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopaccessinfomanager">LoopAccessInfoManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3ee6b8e74fa3cf206dd316434a12bfa">LAIs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dccb300c81f84bee745a7ecee2d7be5">ORE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13d03c04d2d8387a0221986716d0af07">IsForced</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates whether distribution is forced to be enabled/disabled for the loop. <a href="#a13d03c04d2d8387a0221986716d0af07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The actual class performing the per-loop work.</p>

<p>Definition at line 647 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoopDistributeForLoop() {#a2d2a9f983336be7740745ff4f80c65fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::LoopDistributeForLoop (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfomanager">LoopAccessInfoManager</a> &amp; LAIs, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE)</td>
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



<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp/#ae2710e7a8aa8c356be9fd34647605cad">runImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### fail() {#a7e1e58ca451be96cbbff94a01658c988}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::fail (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemarkName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Message)</td>
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

<p>Provide diagnostics then.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>with false.</p></dd>
</dl>


<p>Definition at line 854 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#aa17011a05879d3698f829ff869dc9a88">llvm::OptimizationRemarkAnalysis::AlwaysPrint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a5f5fde523aac0f9086c8572e53f7ae72">isForced</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp/#a77bc1cce3ba138324f4c8a8a107dd0cc">LDIST_NAME</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### isForced() {#a5f5fde523aac0f9086c8572e53f7ae72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::optional&lt; bool &gt; &amp; anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::isForced ()</td>
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

<p>Return if distribution forced to be enabled/disabled for the loop.</p>


<p>If the optional has a value, it indicates whether distribution was forced to be enabled (true) or disabled (false). If the optional has no value distribution was not forced either way.</p>


<p>Definition at line 891 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>Referenced by <a href="#a7e1e58ca451be96cbbff94a01658c988">fail</a>.</p>

</div>
</div>

### processLoop() {#a3c63565a36daca6f3bae8a75238ffd50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop ()</td>
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

<p>Try to distribute an inner-most loop.</p>

<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer/#ad3b1855aab0d6db5fca73b22ba442b50">anonymous{LoopDistribute.cpp}::InstPartitionContainer::addToCyclicPartition</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer/#ae2c300c4031c2ec4a11e3099f7997826">anonymous{LoopDistribute.cpp}::InstPartitionContainer::addToNewNonCyclicPartition</a>, <a href="/web-llvm/docs/api/classes/llvm/loopversioning/#a080fd063ce509a69475d5f80e8b2d973">llvm::LoopVersioning::annotateLoopWithNoAlias</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer/#a36f7b9a37f452349ad02d4d7f7d33972">anonymous{LoopDistribute.cpp}::InstPartitionContainer::cloneLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer/#a223e50a7d4a7c2c8290b0697da780758">anonymous{LoopDistribute.cpp}::InstPartitionContainer::computePartitionSetForPointers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp/#a3afb426cceed7f815ad7d1829ed9de17">DistributeSCEVCheckThreshold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp/#ab794ca855b323cdcfbf21f4a2205bdcf">fail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6880d6c7da94499220b6d7dfcc3c88d4">llvm::findDefsUsedOutsideOfLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#a77779b1cb3dd7968c598f9d6de68282e">llvm::MemoryDepChecker::getMemoryInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/loopversioning/#afc32c640645a5caeb9fe788699d4f75b">llvm::LoopVersioning::getNonVersionedLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a59fb91d1691350f7d1b8e8a114e3f2a4">llvm::BasicBlock::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer/#aea5fae58d0253105a0c4dc9001b8c50d">anonymous{LoopDistribute.cpp}::InstPartitionContainer::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d25a8a9d14a556b1ca44f8fe0dfdd8b">llvm::hasDisableAllTransformsHint</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp/#a77bc1cce3ba138324f4c8a8a107dd0cc">LDIST_NAME</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp/#afd9cd8cdf64e5348184acb41a0dab5e1">LDistVerify</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp/#aabc8ed42404f2c38c26bcf05be144fe8">LLVMLoopDistributeFollowupAll</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp/#ad745c62caa5526f1182d11cb604f5107">LLVMLoopDistributeFollowupFallback</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a368216c9c116e3f30d8dd352ce1370fc">llvm::makeFollowupLoopID</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer/#ad99eb06dcdc7a4ab5c404219aa0243ab">anonymous{LoopDistribute.cpp}::InstPartitionContainer::mergeBeforePopulating</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer/#a154fa6f1a3465a4e2e103cf22d888a33">anonymous{LoopDistribute.cpp}::InstPartitionContainer::mergeToAvoidDuplicatedLoads</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer/#aa6393b11eb9a82951bc6ee17d009d59b">anonymous{LoopDistribute.cpp}::InstPartitionContainer::populateUsedSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp/#ace5e53fe02180406461dcacca5400df9">PragmaDistributeSCEVCheckThreshold</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer/#a2066acdcb85397ee8c9e420d2905eaf9">anonymous{LoopDistribute.cpp}::InstPartitionContainer::printBlocks</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer/#a74d7b9265d85cb5468e8e3dc3893c0df">anonymous{LoopDistribute.cpp}::InstPartitionContainer::removeUnusedInsts</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#adf4be757fa30ca7fe3e8b119438100f0">llvm::Loop::setLoopID</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer/#ab0c3d2072470aea6c24a409f9995e177">anonymous{LoopDistribute.cpp}::InstPartitionContainer::setupPartitionIdOnInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6c9ffe7979754415f4ca0d677174bc2">llvm::SplitBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/loopversioning/#a65b5f9f4aa48ceb121d65679d8b1a689">llvm::LoopVersioning::versionLoop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### includeOnlyCrossPartitionChecks() {#a86d64629e20bf172b2932f93b2649747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; RuntimePointerCheck, 4 &gt; anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::includeOnlyCrossPartitionChecks (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a12b6596f3de8ec2382209b04c2b5444c">RuntimePointerCheck</a> &gt; &amp; AllChecks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; PtrToPartition, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking">RuntimePointerChecking</a> * RtPtrChecking)</td>
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

<p>Filter out checks between pointers from the same partition.</p>


<p><span class="doxyComputerOutput">PtrToPartition</span> contains the partition number for pointers. Partition number -1 means that the pointer is used in multiple partitions. In this case we can't safely omit the check.</p>


<p>Definition at line 899 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### setForced() {#ae54bdc5cbf490fa7f0a78ffe764dfdd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::setForced ()</td>
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

<p>Check whether the loop metadata is forcing distribution to be enabled/disabled.</p>

<p>Definition at line 934 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DT {#a00029e3633f616a85d3531c0e0a9ea77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 951 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### F {#a51c43c34c33ae20c66eccf058bd7fcb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 946 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### IsForced {#a13d03c04d2d8387a0221986716d0af07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::IsForced</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicates whether distribution is forced to be enabled/disabled for the loop.</p>


<p>If the optional has a value, it indicates whether distribution was forced to be enabled (true) or disabled (false). If the optional has no value distribution was not forced either way.</p>


<p>Definition at line 962 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### L {#aca5b85ba6eac33f7744767f6bc5b9f12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 945 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### LAI {#aa317295758050394475dcb1cde3fe733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopAccessInfo* anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::LAI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 950 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### LAIs {#ae3ee6b8e74fa3cf206dd316434a12bfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopAccessInfoManager&amp; anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::LAIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 953 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### LI {#ac283e082082c6242d2f12a12da22c1a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 949 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### ORE {#a7dccb300c81f84bee745a7ecee2d7be5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter* anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::ORE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 954 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### SE {#a891936e19f27d325698b97db82de8135}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution* anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 952 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
