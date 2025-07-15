---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AMDGPURewriteUndefForPHI.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpu-h">AMDGPU.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/uniformityanalysis-h">llvm/Analysis/UniformityAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-amdgpurewriteundefforphi-cpp-">anonymous{AMDGPURewriteUndefForPHI.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteundefforphi-cpp-/amdgpurewriteundefforphilegacy">AMDGPURewriteUndefForPHILegacy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca7cdd32c08e551ff6c01a4a54ae03b1">INITIALIZE_PASS_BEGIN</a> (AMDGPURewriteUndefForPHILegacy, DEBUG_TYPE, "Rewrite undef for PHI", false, false) INITIALIZE_PASS_END(AMDGPURewriteUndefForPHILegacy</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Rewrite undef <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> false bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cadcdd1750ca8ba3197c1266052c059">rewritePHIs</a> (Function &amp;F, UniformityInfo &amp;UA, DominatorTree *DT)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030569d5a541b6110f2ae1b6a3413a58">DEBUG_TYPE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Rewrite undef <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Rewrite undef <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ac33cf9eb6f786561e923d425a6be91">false</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"amdgpu-rewrite-undef-<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a>-phi"</td>
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

## Functions

### INITIALIZE\_PASS\_BEGIN() {#aca7cdd32c08e551ff6c01a4a54ae03b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (AMDGPURewriteUndefForPHILegacy, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, "Rewrite undef <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> PHI", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp">AMDGPURewriteUndefForPHI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### rewritePHIs() {#a2cadcdd1750ca8ba3197c1266052c059}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Rewrite undef for false bool rewritePHIs (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/namespaces/llvm/#a00a2f5a62b5d5d5b6b0e143c4d30041f">UniformityInfo</a> &amp; UA, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp">AMDGPURewriteUndefForPHI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aef9e9fcf4c5dfce90276ca16d91b8e46">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a2cadcdd1750ca8ba3197c1266052c059">rewritePHIs</a>.</p>


<p>Referenced by <a href="#a2cadcdd1750ca8ba3197c1266052c059">rewritePHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpurewriteundefforphipass/#a389937d71bd8740fe3be1c396949e0bb">llvm::AMDGPURewriteUndefForPHIPass::run</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteundefforphi-cpp-/amdgpurewriteundefforphilegacy/#ad0b2e5aeb5c1fc55f6614e0c8c9cbfba">anonymous{AMDGPURewriteUndefForPHI.cpp}::AMDGPURewriteUndefForPHILegacy::runOnFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DEBUG\_TYPE {#a030569d5a541b6110f2ae1b6a3413a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DEBUG_TYPE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp">AMDGPURewriteUndefForPHI.cpp</a>.</p>

</div>
</div>

### false {#a5ac33cf9eb6f786561e923d425a6be91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Rewrite undef for false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp">AMDGPURewriteUndefForPHI.cpp</a>.</p>

</div>
</div>

### PHI {#a2e83cb1bc3f5e8986cbd14575755a134}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Rewrite undef for PHI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp">AMDGPURewriteUndefForPHI.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-36e5fa5b110a1852d0627da33930e4d4/#a84a697406586a81c7ece9b9818929ab6">llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::AddPHIOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd/#a9f9292339308898a6ebf6021c35d3034">llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::AddPHIOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-7a064c1d92ba5b8b002a38239caa8eb3/#a7dbe4f9e5825611510efd0ab7516fc96">llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::AddPHIOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a76ff59dafad74689cfe1966b0ed9fa3c">analyzeLoopUnrollCost</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aa09e8f13910a43ba1b8edc182c7a212c">llvm::CombinerHelper::applyExtendThroughPhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#ad50c8a25364117c5dd799586dd5b0904">areInnerLoopExitPHIsSupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#ac0eeb33419165d13b0fa5c5f6fc69505">areInnerLoopLatchPHIsSupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a6080253e27bfa816dce219371e6a820c">areOuterLoopExitPHIsSupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a1891367518cb08743d89cb5da8cf74d8">breakSelfRecursivePHI</a>, <a href="/web-llvm/docs/api/classes/anonymous-looppeel-cpp-/phianalyzer/#ab8be64c7a0b759236a80e76938e501f0">anonymous{LoopPeel.cpp}::PhiAnalyzer::calculateIterationsToPeel</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a9e6b15b1005dd460a35359f104cb06fe">canRewriteGEPAsOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a361f4564a774bbb16b4a27667256c5ad">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::CheckIfPHIMatches</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a8478b291f8a10892334ba0bcf6a18528">cloneLoopBlocks</a>, <a href="/web-llvm/docs/api/classes/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph/#ab582ba603d84d0ebf312a5f065c11dcf">anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::collectPotentialReductions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a944b77cb28ad77cdf28380c4453f8d02">convertToParamAS</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-36e5fa5b110a1852d0627da33930e4d4/#a1ba7a4f9025c38ba1d2d612e49551dcb">llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::CreateEmptyPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd/#a0db03d5e2c460331af4ee0afaaec953a">llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::CreateEmptyPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-7a064c1d92ba5b8b002a38239caa8eb3/#a6280f6984dd0e0455b73f22b3a5800c2">llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::CreateEmptyPHI</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a7497538730b6264d4783b4cbd71db816">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::createPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp/#a4600a84c9449d3d1b52872727fd4f15f">dependsOnLocalPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a5e53eb62d81882a5586764e2a9378a49">DoFlattenLoopPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a5bb62631ba6a4be0ae02f7365ee4a7d7">ensureValueAvailableInSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a6039b71ec6a83438538f637df2080cd7">llvm::JumpThreadingPass::evaluateOnPredecessorEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ab930da454be280eb307c612727543eb6">expandToSwitch</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a3d50f3f3bb104fb854ac8de326c5bb64">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindAvailableVals</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangelegality/#a4664ad33bbb85ca296ac1a1d74dffc1f">anonymous{LoopInterchange.cpp}::LoopInterchangeLegality::findInductions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a206a95af7fd1177ef8396cd69b888de2">findInnerReductionPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a48e98416c61da7bdde42d88ea460723c">findPHIForConditionForwarding</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acad657182350311f85bc33387733e506">llvm::InstCombinerImpl::foldAggregateConstructionIntoAggregateReuse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a4e1612deb487473177dba9b03302386c">foldMemChr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#ad90e75a757d18b106c964a680d010c6c">followLCSSA</a>, <a href="/web-llvm/docs/api/structs/llvm/valuedfs-compare/#a025277d3135d6afe0bda3b482611eff5">llvm::ValueDFS_Compare::getBlockEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a31070c67db84f4caef376dcb7906c4fb">getCaseResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#af278ae155bd811822054e98b8f056c56">getConstantEvolvingPHIOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp/#a995c9f54308d436b9046a8741b149671">getInsertPointForUses</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#abb21f77ed3dc15eb330b93b3efaa94ba">llvm::AMDGPURegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7d8410ca3fc6fb227416067d3c2535d2">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getNonAliasingPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/trace/#ad7ced8a37469610d46bf6b393953ae1f">llvm::MachineTraceMetrics::Trace::getPHIDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-36e5fa5b110a1852d0627da33930e4d4/#ac588486afd7ad9e56feeeaf30a2db1c0">llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::GetPHIValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd/#a253173e83f9dfeafd7e3d2fd5e57f999">llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::GetPHIValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-7a064c1d92ba5b8b002a38239caa8eb3/#a9632410a5210b4858d5ba8219f01161f">llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::GetPHIValue</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo/#ad10df0e6ccca0fc951b845e3a007e385">llvm::LazyValueInfo::getPredicateAt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfoimpl/#ae5eb92f05b5c0c082472775da1e6cace">llvm::LazyValueInfoImpl::getValueAtUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aac69c9cf4e552a52d5065e94dc023f82">HandleInlinedEHPad</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ad0fe28a9dccc66e85a05b9447f4141ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handlePHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a1b6e5f6033c80dff3f9b4c6fb40499c2">llvm::LiveIntervals::hasPHIKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a95851c48d68c2406ef12a7cca9c65f76">initializeUniqueCases</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ad19c7559d6302321172436f45c771171">insertDbgVariableRecordsForPHIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4dfea19770364b880a77c3f0c1c0f67c">llvm::insertDebugValuesForPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a025e6664b2f55d2c217543c34eb1f64e">llvm::TargetLoweringBase::InstructionOpcodeToISD</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a78cf0931abfbc70e124e7c225584b686">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp/#aa8af038511783f111fd72d2361df7506">IsEquivalentPHI</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinefunction-cpp-/landingpadinlininginfo/#a95303df5888c9384c3ba02c12ca9cb3e">anonymous{InlineFunction.cpp}::LandingPadInliningInfo::LandingPadInliningInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a7e4935f6285534875f64d5399fd6836c">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::manifest</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a5fd133d3cc0d8e1b33fe7ae34657d45c">llvm::CombinerHelper::matchExtendThroughPhis</a>, <a href="/web-llvm/docs/api/classes/llvm/insertphistrategy/#a55f9b306ebb441abea69179650c2a4ad">llvm::InsertPHIStrategy::mutate</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-instrrefbasedimpl-cpp-/#ae4e827155ec83031396ab9007538d268">anonymous{InstrRefBasedImpl.cpp}::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#ae812aaa917422c3c4b067cda1b1d7019">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::optimizeAMXCastFromPhi</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#a86f2353949000eecd69fbbe3c669efc4">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::optimizeLiveRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#aa35ddcfd60c7c4587ea25cb27e25968e">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::optimizeWaterfallLiveRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdb3eec2f46233c924c30c0838a3c8fe">llvm::peelLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-36e5fa5b110a1852d0627da33930e4d4/#a77330dfa97bc91b53a5e9e1d6f75cab1">llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::PHI_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd/#a172ab6463bb885a8b2621054bb3330ae">llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::PHI_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-7a064c1d92ba5b8b002a38239caa8eb3/#a7234490e9abb681a170ebcea530ce0c6">llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::PHI_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-36e5fa5b110a1852d0627da33930e4d4/#af172763cc276913cd13e89b5b2bcbc69">llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::PHI_end</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd/#abaa16ef06748b0b306b83535b94cb8f8">llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::PHI_end</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-7a064c1d92ba5b8b002a38239caa8eb3/#acd0e2a55c9c480f7aa81c6a41bd180ab">llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::PHI_end</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#acc9ee85c11fa2173c85a1ba82797d9fb">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::propagateStoredValueToLoadUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/swifterrorvaluetracking/#afc960ff953a4a9d9fbf91baf590222d2">llvm::SwiftErrorValueTracking::propagateVRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a15993d541998ac409f0fe09abfef6fe8">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::RecordMatchingPHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a0ceff22bcbbcc85abecced9a3a395ccf">removeSwitchAfterSelectFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#af04adca83664ebd947723470c4da58aa">removeUndefIntroducingPredecessor</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86volatiletiledata/#a08cafff5f8ac9e8fa42633409bc04d90">anonymous{X86LowerAMXType.cpp}::X86VolatileTileData::replacePhiDefWithLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a0aa7c68d8c3095ffc271ecceab16c86e">rewriteGEPAsOffset</a>, <a href="#a2cadcdd1750ca8ba3197c1266052c059">rewritePHIs</a>, <a href="/web-llvm/docs/api/classes/anonymous-canonicalizefreezeinloops-cpp-/canonicalizefreezeinloopsimpl/#aff534de0962628bba1821ef3c0821308">anonymous{CanonicalizeFreezeInLoops.cpp}::CanonicalizeFreezeInLoopsImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-indvarsimplify-cpp-/indvarsimplify/#a145b6ea5ff08ca6373ed24389ca97c40">anonymous{IndVarSimplify.cpp}::IndVarSimplify::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-objcarccontract-cpp-/objcarccontract/#a6b6cfbee1f1d7c9f17eb52722c89564d">anonymous{ObjCARCContract.cpp}::ObjCARCContract::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#ac8e72cc39ee52ef30175aa8278cd0dfc">setInsertionPoint</a>, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/simplificationtracker/#ac632fa4ac33de997f4fc1b02b416462c">anonymous{CodeGenPrepare.cpp}::SimplificationTracker::Simplify</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a32b5360bb5f3831163d348fc96fc1198">llvm::fuzzerop::splitBlockDescriptor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a17772fd1beeccd740ec6412abad098f9">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldPhiAGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a794d3a5f46134c24aade41b327d8418e">trySwitchToSelect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanonnullfloating/#a4b1fa4ad98c736b05369d73702328439">anonymous{AttributorAttributes.cpp}::AANonNullFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaunderlyingobjectsimpl/#a5853fd1282daf0510e9eb037ffe23f8a">anonymous{AttributorAttributes.cpp}::AAUnderlyingObjectsImpl::updateImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constanthoisting-cpp/#a0b724dd85384f743a87c3815aace6037">updateOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-36e5fa5b110a1852d0627da33930e4d4/#ac74aed32bcd3712e2746bbf208229c2e">llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::ValueIsNewPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd/#a032cc4ff4828960913e831e32eb9f036">llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::ValueIsNewPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-7a064c1d92ba5b8b002a38239caa8eb3/#a7200de2cd7730b48c991d9d4062e90e7">llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::ValueIsNewPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0a89a6b25b8a92fb896a994a36b74241">llvm::InstCombinerImpl::visitAdd</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvcodegenprepare-cpp-/riscvcodegenprepare/#a57b88264f7380a02c07ac2572482f8e0">anonymous{RISCVCodeGenPrepare.cpp}::RISCVCodeGenPrepare::visitIntrinsicInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a727ca99d2c9f3600398ababdc6db15c7">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#a80ffa3d3c6977a0e2d2289b33952a8be">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#aad366457d1195492d31f22a03881697e">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#ae75cbdfc7f0c17ecb54537cd70261301">DataScalarizerVisitor::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetevaluator/#a9a06c7811f1ea67a51787ab0de806b5a">llvm::ObjectSizeOffsetEvaluator::visitPHINode</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86volatiletiledata/#a4f767b83cb14d5a70423c68254648c18">anonymous{X86LowerAMXType.cpp}::X86VolatileTileData::volatileTilePHI</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"amdgpu-rewrite-undef-<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a>-phi"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp">AMDGPURewriteUndefForPHI.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
