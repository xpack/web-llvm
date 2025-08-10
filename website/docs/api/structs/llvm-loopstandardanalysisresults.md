---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/loopstandardanalysisresults
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `LoopStandardAnalysisResults` Struct

<p>The adaptor from a function pass to a loop pass computes these analyses and makes them available to the loop passes "for free". <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::LoopStandardAnalysisResults { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">llvm/Analysis/LoopAnalysisManager.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd7da877be8576011299f4fcaaf299be">AA</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a902b4712394a3b3450893634b3302893">AC</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa96df870a1b3d7ffc56bec3eb0b0cff">DT</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa09379aa4435be95eb717dd9b5d8b4c5">LI</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a124376878e24aef4252795ba9fea420f">SE</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e363c1eaf112166372e2d52704981fb">TLI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3444a9359f5f17f1694f82c41d5fd574">TTI</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fbd3535a2ca32937aebf75738e854fb">BFI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66fd46237ac20849263a779489ce5d55">BPI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cfb392c267da10531478c2f42baa603">MSSA</a></td>
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

<p>The adaptor from a function pass to a loop pass computes these analyses and makes them available to the loop passes "for free".</p>


<p>Each loop pass is expected to update these analyses if necessary to ensure they're valid after it runs.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### AA {#abd7da877be8576011299f4fcaaf299be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAResults&amp; llvm::LoopStandardAnalysisResults::AA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cachecost/#aa74e490a12ab54ad9687e6844fe605f1">llvm::CacheCost::getCacheCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ddganalysis/#a8bf8dae172bff3a34088acd3372e1739">llvm::DDGAnalysis::run</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonloopidiomrecognitionpass/#ad008d67ca81f40a0890b9e0d69377ba7">llvm::HexagonLoopIdiomRecognitionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/licmpass/#aa540c3d95adfef29cc520491ce4ebdab">llvm::LICMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lnicmpass/#a1ddd3ffe6782be6b893dcf33dcf4e3c0">llvm::LNICMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopcacheprinterpass/#aa35925026f576bd3c47e2f91cd2eb737">llvm::LoopCachePrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopflattenpass/#af1670b8924fecfd8a7f0c4dc140bf603">llvm::LoopFlattenPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopidiomrecognizepass/#a4a3aed1996ede85e98aa361e6f5d74a2">llvm::LoopIdiomRecognizePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/loopinterchangepass/#a99a46045e2cc7182d6a786d400604d76">llvm::LoopInterchangePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looppredicationpass/#ae0a08563a94fcfe8107a3d45564b881e">llvm::LoopPredicationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopunrollandjampass/#aceae0aba9cc69bf89d3241d61190b9ec">llvm::LoopUnrollAndJamPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopversioninglicmpass/#ac248c8958e091a1497a9b5ca728e4e78">llvm::LoopVersioningLICMPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/simpleloopunswitchpass/#ae7088b7b5c8bd069497f13e3e1990eff">llvm::SimpleLoopUnswitchPass::run</a>.</p>

</div>
</div>

### AC {#a902b4712394a3b3450893634b3302893}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache&amp; llvm::LoopStandardAnalysisResults::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a587d87d22706668ca92092a65fc8e1e7">llvm::getBestSimplifyQuery</a>, <a href="/web-llvm/docs/api/structs/llvm/guardwideningpass/#a37a71785c3d451d302d2cb9e108f5424">llvm::GuardWideningPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ivusersanalysis/#ae94045fa22bbbbbf5d941452605f73a2">llvm::IVUsersAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/licmpass/#aa540c3d95adfef29cc520491ce4ebdab">llvm::LICMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lnicmpass/#a1ddd3ffe6782be6b893dcf33dcf4e3c0">llvm::LNICMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopflattenpass/#af1670b8924fecfd8a7f0c4dc140bf603">llvm::LoopFlattenPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopfullunrollpass/#aacf97677dabaa7e583a690244bde44ea">llvm::LoopFullUnrollPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinstsimplifypass/#a3e829edc978ccb3a88ff5532faf75879">llvm::LoopInstSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looprotatepass/#aa87b74697e2ab3e760eddd32b866c508">llvm::LoopRotatePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopstrengthreducepass/#a4e475c0fcd6ade09109db20acb073a77">llvm::LoopStrengthReducePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopunrollandjampass/#aceae0aba9cc69bf89d3241d61190b9ec">llvm::LoopUnrollAndJamPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/simpleloopunswitchpass/#ae7088b7b5c8bd069497f13e3e1990eff">llvm::SimpleLoopUnswitchPass::run</a>.</p>

</div>
</div>

### BFI {#a0fbd3535a2ca32937aebf75738e854fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfo* llvm::LoopStandardAnalysisResults::BFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simpleloopunswitchpass/#ae7088b7b5c8bd069497f13e3e1990eff">llvm::SimpleLoopUnswitchPass::run</a>.</p>

</div>
</div>

### BPI {#a66fd46237ac20849263a779489ce5d55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbabilityInfo* llvm::LoopStandardAnalysisResults::BPI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>

</div>
</div>

### DT {#aaa96df870a1b3d7ffc56bec3eb0b0cff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree&amp; llvm::LoopStandardAnalysisResults::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a587d87d22706668ca92092a65fc8e1e7">llvm::getBestSimplifyQuery</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalizefreezeinloopspass/#a8bc859057e091c18fffefa68d8dcd3e6">llvm::CanonicalizeFreezeInLoopsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a>, <a href="/web-llvm/docs/api/structs/llvm/guardwideningpass/#a37a71785c3d451d302d2cb9e108f5424">llvm::GuardWideningPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonloopidiomrecognitionpass/#ad008d67ca81f40a0890b9e0d69377ba7">llvm::HexagonLoopIdiomRecognitionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/indvarsimplifypass/#a00bd6521a4f23d764d5d1403e7728e8f">llvm::IndVarSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ivusersanalysis/#ae94045fa22bbbbbf5d941452605f73a2">llvm::IVUsersAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/licmpass/#aa540c3d95adfef29cc520491ce4ebdab">llvm::LICMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lnicmpass/#a1ddd3ffe6782be6b893dcf33dcf4e3c0">llvm::LNICMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopboundsplitpass/#a488751cbcea1a2e3da39c4e67ecfd98c">llvm::LoopBoundSplitPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopdeletionpass/#adc91b7d6d8d4770240d4cce7adf7fb01">llvm::LoopDeletionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopflattenpass/#af1670b8924fecfd8a7f0c4dc140bf603">llvm::LoopFlattenPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopfullunrollpass/#aacf97677dabaa7e583a690244bde44ea">llvm::LoopFullUnrollPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopidiomrecognizepass/#a4a3aed1996ede85e98aa361e6f5d74a2">llvm::LoopIdiomRecognizePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopidiomvectorizepass/#a0b63cb3362045110398f3faf3ddbee74">llvm::LoopIdiomVectorizePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinstsimplifypass/#a3e829edc978ccb3a88ff5532faf75879">llvm::LoopInstSimplifyPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/loopinterchangepass/#a99a46045e2cc7182d6a786d400604d76">llvm::LoopInterchangePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looppredicationpass/#ae0a08563a94fcfe8107a3d45564b881e">llvm::LoopPredicationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looprotatepass/#aa87b74697e2ab3e760eddd32b866c508">llvm::LoopRotatePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsimplifycfgpass/#a6080bbb0e8e74dbaf955a64f844978a4">llvm::LoopSimplifyCFGPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopstrengthreducepass/#a4e475c0fcd6ade09109db20acb073a77">llvm::LoopStrengthReducePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looptermfoldpass/#abefaee9143bf56e20b254a2f9a1bae56">llvm::LoopTermFoldPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopunrollandjampass/#aceae0aba9cc69bf89d3241d61190b9ec">llvm::LoopUnrollAndJamPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopversioninglicmpass/#ac248c8958e091a1497a9b5ca728e4e78">llvm::LoopVersioningLICMPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/simpleloopunswitchpass/#ae7088b7b5c8bd069497f13e3e1990eff">llvm::SimpleLoopUnswitchPass::run</a>.</p>

</div>
</div>

### LI {#aa09379aa4435be95eb717dd9b5d8b4c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo&amp; llvm::LoopStandardAnalysisResults::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cachecost/#aa74e490a12ab54ad9687e6844fe605f1">llvm::CacheCost::getCacheCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ddganalysis/#a8bf8dae172bff3a34088acd3372e1739">llvm::DDGAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a>, <a href="/web-llvm/docs/api/structs/llvm/guardwideningpass/#a37a71785c3d451d302d2cb9e108f5424">llvm::GuardWideningPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonloopidiomrecognitionpass/#ad008d67ca81f40a0890b9e0d69377ba7">llvm::HexagonLoopIdiomRecognitionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/indvarsimplifypass/#a00bd6521a4f23d764d5d1403e7728e8f">llvm::IndVarSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ivusersanalysis/#ae94045fa22bbbbbf5d941452605f73a2">llvm::IVUsersAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/licmpass/#aa540c3d95adfef29cc520491ce4ebdab">llvm::LICMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lnicmpass/#a1ddd3ffe6782be6b893dcf33dcf4e3c0">llvm::LNICMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopboundsplitpass/#a488751cbcea1a2e3da39c4e67ecfd98c">llvm::LoopBoundSplitPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopcacheprinterpass/#aa35925026f576bd3c47e2f91cd2eb737">llvm::LoopCachePrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopdeletionpass/#adc91b7d6d8d4770240d4cce7adf7fb01">llvm::LoopDeletionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopflattenpass/#af1670b8924fecfd8a7f0c4dc140bf603">llvm::LoopFlattenPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopfullunrollpass/#aacf97677dabaa7e583a690244bde44ea">llvm::LoopFullUnrollPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopidiomrecognizepass/#a4a3aed1996ede85e98aa361e6f5d74a2">llvm::LoopIdiomRecognizePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopidiomvectorizepass/#a0b63cb3362045110398f3faf3ddbee74">llvm::LoopIdiomVectorizePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinstsimplifypass/#a3e829edc978ccb3a88ff5532faf75879">llvm::LoopInstSimplifyPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/loopinterchangepass/#a99a46045e2cc7182d6a786d400604d76">llvm::LoopInterchangePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looppredicationpass/#ae0a08563a94fcfe8107a3d45564b881e">llvm::LoopPredicationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looprotatepass/#aa87b74697e2ab3e760eddd32b866c508">llvm::LoopRotatePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsimplifycfgpass/#a6080bbb0e8e74dbaf955a64f844978a4">llvm::LoopSimplifyCFGPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopstrengthreducepass/#a4e475c0fcd6ade09109db20acb073a77">llvm::LoopStrengthReducePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looptermfoldpass/#abefaee9143bf56e20b254a2f9a1bae56">llvm::LoopTermFoldPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopunrollandjampass/#aceae0aba9cc69bf89d3241d61190b9ec">llvm::LoopUnrollAndJamPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopversioninglicmpass/#ac248c8958e091a1497a9b5ca728e4e78">llvm::LoopVersioningLICMPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/simpleloopunswitchpass/#ae7088b7b5c8bd069497f13e3e1990eff">llvm::SimpleLoopUnswitchPass::run</a>.</p>

</div>
</div>

### MSSA {#a1cfb392c267da10531478c2f42baa603}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSA* llvm::LoopStandardAnalysisResults::MSSA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a>, <a href="/web-llvm/docs/api/structs/llvm/guardwideningpass/#a37a71785c3d451d302d2cb9e108f5424">llvm::GuardWideningPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/indvarsimplifypass/#a00bd6521a4f23d764d5d1403e7728e8f">llvm::IndVarSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/licmpass/#aa540c3d95adfef29cc520491ce4ebdab">llvm::LICMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lnicmpass/#a1ddd3ffe6782be6b893dcf33dcf4e3c0">llvm::LNICMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopdeletionpass/#adc91b7d6d8d4770240d4cce7adf7fb01">llvm::LoopDeletionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopflattenpass/#af1670b8924fecfd8a7f0c4dc140bf603">llvm::LoopFlattenPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopidiomrecognizepass/#a4a3aed1996ede85e98aa361e6f5d74a2">llvm::LoopIdiomRecognizePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinstsimplifypass/#a3e829edc978ccb3a88ff5532faf75879">llvm::LoopInstSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looppredicationpass/#ae0a08563a94fcfe8107a3d45564b881e">llvm::LoopPredicationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looprotatepass/#aa87b74697e2ab3e760eddd32b866c508">llvm::LoopRotatePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsimplifycfgpass/#a6080bbb0e8e74dbaf955a64f844978a4">llvm::LoopSimplifyCFGPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopstrengthreducepass/#a4e475c0fcd6ade09109db20acb073a77">llvm::LoopStrengthReducePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looptermfoldpass/#abefaee9143bf56e20b254a2f9a1bae56">llvm::LoopTermFoldPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/simpleloopunswitchpass/#ae7088b7b5c8bd069497f13e3e1990eff">llvm::SimpleLoopUnswitchPass::run</a>.</p>

</div>
</div>

### SE {#a124376878e24aef4252795ba9fea420f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution&amp; llvm::LoopStandardAnalysisResults::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cachecost/#aa74e490a12ab54ad9687e6844fe605f1">llvm::CacheCost::getCacheCost</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalizefreezeinloopspass/#a8bc859057e091c18fffefa68d8dcd3e6">llvm::CanonicalizeFreezeInLoopsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ddganalysis/#a8bf8dae172bff3a34088acd3372e1739">llvm::DDGAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonloopidiomrecognitionpass/#ad008d67ca81f40a0890b9e0d69377ba7">llvm::HexagonLoopIdiomRecognitionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/indvarsimplifypass/#a00bd6521a4f23d764d5d1403e7728e8f">llvm::IndVarSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ivusersanalysis/#ae94045fa22bbbbbf5d941452605f73a2">llvm::IVUsersAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/licmpass/#aa540c3d95adfef29cc520491ce4ebdab">llvm::LICMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lnicmpass/#a1ddd3ffe6782be6b893dcf33dcf4e3c0">llvm::LNICMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopboundsplitpass/#a488751cbcea1a2e3da39c4e67ecfd98c">llvm::LoopBoundSplitPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopcacheprinterpass/#aa35925026f576bd3c47e2f91cd2eb737">llvm::LoopCachePrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopdeletionpass/#adc91b7d6d8d4770240d4cce7adf7fb01">llvm::LoopDeletionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopflattenpass/#af1670b8924fecfd8a7f0c4dc140bf603">llvm::LoopFlattenPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopfullunrollpass/#aacf97677dabaa7e583a690244bde44ea">llvm::LoopFullUnrollPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopidiomrecognizepass/#a4a3aed1996ede85e98aa361e6f5d74a2">llvm::LoopIdiomRecognizePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/loopinterchangepass/#a99a46045e2cc7182d6a786d400604d76">llvm::LoopInterchangePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopnestprinterpass/#aaf9544eaca7fe1e7b473639f38a3b094">llvm::LoopNestPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looppredicationpass/#ae0a08563a94fcfe8107a3d45564b881e">llvm::LoopPredicationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looprotatepass/#aa87b74697e2ab3e760eddd32b866c508">llvm::LoopRotatePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsimplifycfgpass/#a6080bbb0e8e74dbaf955a64f844978a4">llvm::LoopSimplifyCFGPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopstrengthreducepass/#a4e475c0fcd6ade09109db20acb073a77">llvm::LoopStrengthReducePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looptermfoldpass/#abefaee9143bf56e20b254a2f9a1bae56">llvm::LoopTermFoldPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopunrollandjampass/#aceae0aba9cc69bf89d3241d61190b9ec">llvm::LoopUnrollAndJamPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopversioninglicmpass/#ac248c8958e091a1497a9b5ca728e4e78">llvm::LoopVersioningLICMPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/simpleloopunswitchpass/#ae7088b7b5c8bd069497f13e3e1990eff">llvm::SimpleLoopUnswitchPass::run</a>.</p>

</div>
</div>

### TLI {#a9e363c1eaf112166372e2d52704981fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfo&amp; llvm::LoopStandardAnalysisResults::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a587d87d22706668ca92092a65fc8e1e7">llvm::getBestSimplifyQuery</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonloopidiomrecognitionpass/#ad008d67ca81f40a0890b9e0d69377ba7">llvm::HexagonLoopIdiomRecognitionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/indvarsimplifypass/#a00bd6521a4f23d764d5d1403e7728e8f">llvm::IndVarSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/licmpass/#aa540c3d95adfef29cc520491ce4ebdab">llvm::LICMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lnicmpass/#a1ddd3ffe6782be6b893dcf33dcf4e3c0">llvm::LNICMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopidiomrecognizepass/#a4a3aed1996ede85e98aa361e6f5d74a2">llvm::LoopIdiomRecognizePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinstsimplifypass/#a3e829edc978ccb3a88ff5532faf75879">llvm::LoopInstSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopstrengthreducepass/#a4e475c0fcd6ade09109db20acb073a77">llvm::LoopStrengthReducePass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/looptermfoldpass/#abefaee9143bf56e20b254a2f9a1bae56">llvm::LoopTermFoldPass::run</a>.</p>

</div>
</div>

### TTI {#a3444a9359f5f17f1694f82c41d5fd574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo&amp; llvm::LoopStandardAnalysisResults::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cachecost/#aa74e490a12ab54ad9687e6844fe605f1">llvm::CacheCost::getCacheCost</a>, <a href="/web-llvm/docs/api/classes/llvm/indvarsimplifypass/#a00bd6521a4f23d764d5d1403e7728e8f">llvm::IndVarSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/licmpass/#aa540c3d95adfef29cc520491ce4ebdab">llvm::LICMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lnicmpass/#a1ddd3ffe6782be6b893dcf33dcf4e3c0">llvm::LNICMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopflattenpass/#af1670b8924fecfd8a7f0c4dc140bf603">llvm::LoopFlattenPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopfullunrollpass/#aacf97677dabaa7e583a690244bde44ea">llvm::LoopFullUnrollPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopidiomrecognizepass/#a4a3aed1996ede85e98aa361e6f5d74a2">llvm::LoopIdiomRecognizePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopidiomvectorizepass/#a0b63cb3362045110398f3faf3ddbee74">llvm::LoopIdiomVectorizePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looprotatepass/#aa87b74697e2ab3e760eddd32b866c508">llvm::LoopRotatePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopstrengthreducepass/#a4e475c0fcd6ade09109db20acb073a77">llvm::LoopStrengthReducePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looptermfoldpass/#abefaee9143bf56e20b254a2f9a1bae56">llvm::LoopTermFoldPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopunrollandjampass/#aceae0aba9cc69bf89d3241d61190b9ec">llvm::LoopUnrollAndJamPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/simpleloopunswitchpass/#ae7088b7b5c8bd069497f13e3e1990eff">llvm::SimpleLoopUnswitchPass::run</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
