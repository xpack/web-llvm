---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InlineCostCallAnalyzer` Class Reference

<p>FIXME: if it is necessary to derive from <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer">InlineCostCallAnalyzer</a>, note the FIXME in onLoweredCall, when instantiating an <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer">InlineCostCallAnalyzer</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{InlineCost.cpp}::InlineCostCallAnalyzer { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer">CallAnalyzer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Carry out call site analysis, in order to evaluate inlinability. <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55d07c23093e29dd03456b0197d64f69">InlineCostCallAnalyzer</a> (Function &amp;Callee, CallBase &amp;Call, const InlineParams &amp;Params, const TargetTransformInfo &amp;TTI, function_ref&lt; AssumptionCache &amp;(Function &amp;)&gt; GetAssumptionCache, function_ref&lt; BlockFrequencyInfo &amp;(Function &amp;)&gt; GetBFI=nullptr, function_ref&lt; const TargetLibraryInfo &amp;(Function &amp;)&gt; GetTLI=nullptr, ProfileSummaryInfo *PSI=nullptr, OptimizationRemarkEmitter *ORE=nullptr, bool BoostIndirect=true, bool IgnoreThreshold=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1f089894af1d602b64f028fa8951ba4">~InlineCostCallAnalyzer</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabcb13bec5e6f9ba8dc996af8a10cc10">dump</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump stats about this call's analysis. <a href="#aabcb13bec5e6f9ba8dc996af8a10cc10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c1cb0941fc8289abfffced96bb006f6">print</a> (raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/anonymous-inlinecost-cpp-/instructioncostdetail">InstructionCostDetail</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6b04b8621a2d890ebcb6856d8f092fd">getCostDetails</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb1d0df80d9694dec13c124cacfba9fb">getThreshold</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46fe03997116e029acecf085b9fd92bd">getCost</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab97d504842644a911797eaa17c246c42">getStaticBonusApplied</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/costbenefitpair">CostBenefitPair</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2a8dc97688455623dcad813b233b2ac">getCostBenefitPair</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2084684013a7a4b5a6006db05cd2bc62">wasDecidedByCostBenefit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c6d7a11458895b50a5943db3b2eeb8d">wasDecidedByCostThreshold</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b845776e7517a221d67fab362cf77ce">isColdCallSite</a> (CallBase &amp;Call, BlockFrequencyInfo *CallerBFI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">Call</span> is a cold callsite. <a href="#a6b845776e7517a221d67fab362cf77ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c691b0f71f23818b50648cb8f9f6817">updateThreshold</a> (CallBase &amp;Call, Function &amp;Callee)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update Threshold based on callsite properties such as callee attributes and callee hotness for PGO builds. <a href="#a1c691b0f71f23818b50648cb8f9f6817">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5034832c872b26354bf09cd60925f7a1">getHotCallSiteThreshold</a> (CallBase &amp;Call, BlockFrequencyInfo *CallerBFI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a higher threshold if <span class="doxyComputerOutput">Call</span> is a hot callsite. <a href="#a5034832c872b26354bf09cd60925f7a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd43d90534e4717277a6d937a69038eb">addCost</a> (int64_t Inc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle a capped 'int' increment for Cost. <a href="#abd43d90534e4717277a6d937a69038eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae442e9e3da86e5cd62cee5639590e0ac">onDisableSROA</a> (AllocaInst *Arg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called if the analysis engine decides SROA cannot be done for the given alloca. <a href="#ae442e9e3da86e5cd62cee5639590e0ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7da858f18c7a03458aeb08226e9372a9">onDisableLoadElimination</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called the analysis engine determines load elimination won't happen. <a href="#a7da858f18c7a03458aeb08226e9372a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0e6bd8dbef28bdfd3489be6f5136df0">onCallBaseVisitStart</a> (CallBase &amp;Call) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called when we visit a <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a>, before the analysis starts. <a href="#aa0e6bd8dbef28bdfd3489be6f5136df0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b2deb019415338a4a09bb15811fc640">onCallPenalty</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for a call. <a href="#a9b2deb019415338a4a09bb15811fc640">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bff49e0104b0cc58ff53e92d7ecc01f">onMemAccess</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for a load or store. <a href="#a9bff49e0104b0cc58ff53e92d7ecc01f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5025660cfc46ce020a253c5c59a90f97">onCallArgumentSetup</a> (const CallBase &amp;Call) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for the cost of argument setup for the Call in the callee's body (not the callsite currently under analysis). <a href="#a5025660cfc46ce020a253c5c59a90f97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae387e4eac119b3cf2879cd1ae1683122">onLoadRelativeIntrinsic</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for a load relative intrinsic. <a href="#ae387e4eac119b3cf2879cd1ae1683122">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4ffd0cd2f242d6a633b8bb4d24ef3ce">onLoweredCall</a> (Function *F, CallBase &amp;Call, bool IsIndirectCall) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for a lowered call. <a href="#ae4ffd0cd2f242d6a633b8bb4d24ef3ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5656b4a23e5d2de32dda72eb7ca21c35">onFinalizeSwitch</a> (unsigned JumpTableSize, unsigned NumCaseCluster, bool DefaultDestUndefined) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called at the end of processing a switch instruction, with the given number of case clusters. <a href="#a5656b4a23e5d2de32dda72eb7ca21c35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e474f3b935b0ed1db8194cdf9d08ebf">onMissedSimplification</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for any other instruction not specifically accounted for. <a href="#a3e474f3b935b0ed1db8194cdf9d08ebf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa58288940d85aaefbc01968af456c248">onInitializeSROAArg</a> (AllocaInst *Arg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start accounting potential benefits due to SROA for the given alloca. <a href="#aa58288940d85aaefbc01968af456c248">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7d6b38d5018035718aab8b576366e58">onAggregateSROAUse</a> (AllocaInst *SROAArg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Account SROA savings for the <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> value. <a href="#ab7d6b38d5018035718aab8b576366e58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1632e461a3ea9810f907078d4738e301">onBlockStart</a> (const BasicBlock *BB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/extension">Extension</a> points for handling callsite features. <a href="#a1632e461a3ea9810f907078d4738e301">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2696f606e14ab3d036b0bb3887198742">onBlockAnalyzed</a> (const BasicBlock *BB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called after a basic block was analyzed. <a href="#a2696f606e14ab3d036b0bb3887198742">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55b6b3f70e1525d8943e32cc3bac6498">onInstructionAnalysisStart</a> (const Instruction *I) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called before an instruction was analyzed. <a href="#a55b6b3f70e1525d8943e32cc3bac6498">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9407d52b8ad783ac2890246728fd5078">onInstructionAnalysisFinish</a> (const Instruction *I) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called after an instruction was analyzed. <a href="#a9407d52b8ad783ac2890246728fd5078">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9702b707641af254cfae0851bf063a05">isCostBenefitAnalysisEnabled</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae72ab7d4c57a23774536c2e555cb1302">getInliningCostBenefitAnalysisSavingsMultiplier</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a601353c11d3c975cec2b67bc8a6a18d9">getInliningCostBenefitAnalysisProfitableMultiplier</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea34b9f810cfab5171844976f736353d">OverrideCycleSavingsAndSizeForTesting</a> (APInt &amp;CycleSavings, int &amp;Size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8ff599fad62dc4b4d261ce7a4cb20dc">costBenefitAnalysis</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineresult">InlineResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20425d55badf2ff3a492910c0901b967">finalizeAnalysis</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called at the end of the analysis of the callsite. <a href="#a20425d55badf2ff3a492910c0901b967">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a242df7e489a6d485f2c31caefe583ab2">shouldStop</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called when we're about to start processing a basic block, and every time we are done processing an instruction. <a href="#a242df7e489a6d485f2c31caefe583ab2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60c66f621969fecf819ffca27b9659d1">onLoadEliminationOpportunity</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for the expectation the inlining would result in a load elimination. <a href="#a60c66f621969fecf819ffca27b9659d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineresult">InlineResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e02e10d33d21688beaf715849c4c6ce">onAnalysisStart</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called before the analysis of the callee body starts (with callsite contexts propagated). <a href="#a4e02e10d33d21688beaf715849c4c6ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostannotationwriter">InlineCostAnnotationWriter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11be613022253844628248a4922817d6">Writer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Annotation Writer for instruction details. <a href="#a11be613022253844628248a4922817d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac123ef981d1b1fcf6b6dcf4a5d1c8572">ComputeFullInlineCost</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac253cec66c9a63250750a9ea07cf0f82">LoadEliminationCost</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f6f1654097008a1ce8c3c0ac26d8594">VectorBonus</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bonus to be applied when percentage of vector instructions in callee is high (see more details in updateThreshold). <a href="#a2f6f1654097008a1ce8c3c0ac26d8594">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a179fd61141b50c15f988bc83b2b7efd4">SingleBBBonus</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bonus to be applied when the callee has only one reachable basic block. <a href="#a179fd61141b50c15f988bc83b2b7efd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/inlineparams">InlineParams</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1632fc82a67ad0a673cd3e670618d77a">Params</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tunable parameters that control the analysis. <a href="#a1632fc82a67ad0a673cd3e670618d77a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/structs/anonymous-inlinecost-cpp-/instructioncostdetail">InstructionCostDetail</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a879831754efb86bf5bbe27809e64ed35">InstructionCostDetailMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a767c4d60fc8ec155bd386cde5e0d12cf">Threshold</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Upper bound for the inlining cost. <a href="#a767c4d60fc8ec155bd386cde5e0d12cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a114aa98686cf9af5c2b3b27333ee63fe">StaticBonusApplied</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The amount of StaticBonus applied. <a href="#a114aa98686cf9af5c2b3b27333ee63fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc4c0caeca05f8d15338ac907c67b7e2">BoostIndirectCalls</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to evaluate indirect calls to boost its inline cost. <a href="#acc4c0caeca05f8d15338ac907c67b7e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a282bdd4b2444cf1a17d5a10ecaaaed65">IgnoreThreshold</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ignore the threshold when finalizing analysis. <a href="#a282bdd4b2444cf1a17d5a10ecaaaed65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff7e4e8702f2fec82d1fbec2f9c36e1d">CostBenefitAnalysisEnabled</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eea997174c85f43a28dce42cf27c116">Cost</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inlining cost measured in abstract units, accounts for all the instructions expected to be executed for a given function invocation. <a href="#a9eea997174c85f43a28dce42cf27c116">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae0664ccf0aed3faa0504eb775eb0667">CostAtBBStart</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f4fae8e459a5271bf00e607b35157d7">ColdSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d16867943b98d472247eae8fc0cb54f">DecidedByCostThreshold</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ea5953e8d955f5297b244186c68299f">DecidedByCostBenefit</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/costbenefitpair">CostBenefitPair</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f0e9dc8c8099d45c30cbc8f3fad6906">CostBenefit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65698928eddb5c730f5988aaf2562912">SingleBB</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5bfd85bc6db696ef5c4d8c3fcae564c">SROACostSavings</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf9654d8f36ecf211715df80c62ccb4c">SROACostSavingsLost</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62f7dd2876e111bb5df3e9efc962c350">SROAArgCosts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The mapping of caller Alloca values to their accumulated cost savings. <a href="#a62f7dd2876e111bb5df3e9efc962c350">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>FIXME: if it is necessary to derive from <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer">InlineCostCallAnalyzer</a>, note the FIXME in onLoweredCall, when instantiating an <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer">InlineCostCallAnalyzer</a>.</p>

<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InlineCostCallAnalyzer() {#a55d07c23093e29dd03456b0197d64f69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::InlineCostCallAnalyzer (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Callee, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/inlineparams">InlineParams</a> &amp; Params, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GetAssumptionCache, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GetBFI=nullptr, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GetTLI=nullptr, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI=nullptr, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE=nullptr, bool BoostIndirect=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool IgnoreThreshold=false)</td>
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



<p>Definition at line 1119 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#aa1d2fb22fed73c219030de9b2d8dfa43">anonymous{InlineCost.cpp}::CallAnalyzer::AllowRecursiveCall</a>, <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#afe415d5ca807552e9ab9180b7821f04d">anonymous{InlineCost.cpp}::CallAnalyzer::CallAnalyzer</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp/#af56434886ef866260b6a2d88844515dd">DefaultThreshold</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#acbdd4c0e06dc866ad2e68d57e194743e">anonymous{InlineCost.cpp}::CallAnalyzer::GetAssumptionCache</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a9d83f245e02c2d598444b73ea9a05459">anonymous{InlineCost.cpp}::CallAnalyzer::GetBFI</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#abef6e3800bbcc3d80dca77ce58b0eaa8">anonymous{InlineCost.cpp}::CallAnalyzer::GetTLI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp/#aa9f9313b0e118f02bf2356e3c3055ba7">OptComputeFullInlineCost</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#aeee19cfe3d54e41a640e29f36056ecfb">anonymous{InlineCost.cpp}::CallAnalyzer::ORE</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a8c79183f67d088e0c9cd34511c3f848d">anonymous{InlineCost.cpp}::CallAnalyzer::PSI</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a453497ae3e6c0033f5609b932d472b11">anonymous{InlineCost.cpp}::CallAnalyzer::TTI</a> and <a href="#a11be613022253844628248a4922817d6">Writer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a11326a8194a8022478ebafeba2b5ccb5">llvm::getInlineCost</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9362dadd20c02f3227f93421cb8829d">llvm::getInliningCostEstimate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~InlineCostCallAnalyzer() {#aa1f089894af1d602b64f028fa8951ba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::~InlineCostCallAnalyzer ()</td>
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



<p>Definition at line 1156 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#aabcb13bec5e6f9ba8dc996af8a10cc10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void InlineCostCallAnalyzer::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump stats about this call's analysis.</p>

<p>Definition at line 1143 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a2c1cb0941fc8289abfffced96bb006f6">print</a>.</p>

</div>
</div>

### getCost() {#a46fe03997116e029acecf085b9fd92bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::getCost ()</td>
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



<p>Definition at line 1158 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### getCostBenefitPair() {#ab2a8dc97688455623dcad813b233b2ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CostBenefitPair &gt; anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::getCostBenefitPair ()</td>
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



<p>Definition at line 1160 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### getCostDetails() {#ae6b04b8621a2d890ebcb6856d8f092fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; InstructionCostDetail &gt; anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::getCostDetails (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 1149 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getStaticBonusApplied() {#ab97d504842644a911797eaa17c246c42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::getStaticBonusApplied ()</td>
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



<p>Definition at line 1159 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### getThreshold() {#acb1d0df80d9694dec13c124cacfba9fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::getThreshold ()</td>
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



<p>Definition at line 1157 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### print() {#a2c1cb0941fc8289abfffced96bb006f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InlineCostCallAnalyzer::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1147 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a9600de48f592771fe50cad7071b6fcb3">anonymous{InlineCost.cpp}::CallAnalyzer::ContainsNoDuplicateCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp/#ab2134ebaeaea50d7cf9be53c567777eb">DEBUG_PRINT_STAT</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#aa0d73af9a3aaefb80f59550a218c40f2">anonymous{InlineCost.cpp}::CallAnalyzer::F</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#af3a1ead12644ce26ba1d064b4271df7e">anonymous{InlineCost.cpp}::CallAnalyzer::NumAllocaArgs</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a5635dea24d14ac5e3840263d19e63a6a">anonymous{InlineCost.cpp}::CallAnalyzer::NumConstantArgs</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a46dd2f959cdfce95cee14bf9f5fd750b">anonymous{InlineCost.cpp}::CallAnalyzer::NumConstantOffsetPtrArgs</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a446676eb6e2a94add6ae60b02a13335e">anonymous{InlineCost.cpp}::CallAnalyzer::NumConstantPtrCmps</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#ae257151eedfc737f3db3fe122deade01">anonymous{InlineCost.cpp}::CallAnalyzer::NumConstantPtrDiffs</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a779e8a97453bc9d5ab3a09e2be4b864d">anonymous{InlineCost.cpp}::CallAnalyzer::NumInstructions</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#ab90e06182887adcb3b5fe8cd59afb68a">anonymous{InlineCost.cpp}::CallAnalyzer::NumInstructionsSimplified</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp/#a4759abeba02cb7646272d5253f36343d">PrintInstructionComments</a> and <a href="#a11be613022253844628248a4922817d6">Writer</a>.</p>


<p>Referenced by <a href="#aabcb13bec5e6f9ba8dc996af8a10cc10">dump</a>.</p>

</div>
</div>

### wasDecidedByCostBenefit() {#a2084684013a7a4b5a6006db05cd2bc62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::wasDecidedByCostBenefit ()</td>
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



<p>Definition at line 1161 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### wasDecidedByCostThreshold() {#a0c6d7a11458895b50a5943db3b2eeb8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::wasDecidedByCostThreshold ()</td>
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



<p>Definition at line 1162 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addCost() {#abd43d90534e4717277a6d937a69038eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::addCost (int64_t Inc)</td>
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

<p>Handle a capped 'int' increment for Cost.</p>

<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### costBenefitAnalysis() {#ae8ff599fad62dc4b4d261ce7a4cb20dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::costBenefitAnalysis ()</td>
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



<p>Definition at line 881 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### finalizeAnalysis() {#a20425d55badf2ff3a492910c0901b967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineResult anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::finalizeAnalysis ()</td>
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

<p>Called at the end of the analysis of the callsite.</p>


<p>Return the outcome of the analysis, i.e. 'InlineResult(true)' if the inlining may happen, or the reason it can't.</p>


<p>Definition at line 998 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### getHotCallSiteThreshold() {#a5034832c872b26354bf09cd60925f7a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; int &gt; InlineCostCallAnalyzer::getHotCallSiteThreshold (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * CallerBFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a higher threshold if <span class="doxyComputerOutput">Call</span> is a hot callsite.</p>

<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### getInliningCostBenefitAnalysisProfitableMultiplier() {#a601353c11d3c975cec2b67bc8a6a18d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::getInliningCostBenefitAnalysisProfitableMultiplier ()</td>
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



<p>Definition at line 860 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### getInliningCostBenefitAnalysisSavingsMultiplier() {#ae72ab7d4c57a23774536c2e555cb1302}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::getInliningCostBenefitAnalysisSavingsMultiplier ()</td>
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



<p>Definition at line 853 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### isColdCallSite() {#a6b845776e7517a221d67fab362cf77ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InlineCostCallAnalyzer::isColdCallSite (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * CallerBFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">Call</span> is a cold callsite.</p>

<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### isCostBenefitAnalysisEnabled() {#a9702b707641af254cfae0851bf063a05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::isCostBenefitAnalysisEnabled ()</td>
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



<p>Definition at line 811 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onAggregateSROAUse() {#ab7d6b38d5018035718aab8b576366e58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::onAggregateSROAUse (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * V)</td>
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

<p>Account SROA savings for the <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> value.</p>

<p>Definition at line 759 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onAnalysisStart() {#a4e02e10d33d21688beaf715849c4c6ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineResult anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::onAnalysisStart ()</td>
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

<p>Called before the analysis of the callee body starts (with callsite contexts propagated).</p>


<p>It checks callsite-specific information. Return a reason analysis can't continue if that's the case, or 'true' if it may continue.</p>


<p>Definition at line 1071 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onBlockAnalyzed() {#a2696f606e14ab3d036b0bb3887198742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::onBlockAnalyzed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Called after a basic block was analyzed.</p>

<p>Definition at line 769 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onBlockStart() {#a1632e461a3ea9810f907078d4738e301}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::onBlockStart (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p><a href="/web-llvm/docs/api/structs/extension">Extension</a> points for handling callsite features.</p>

<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onCallArgumentSetup() {#a5025660cfc46ce020a253c5c59a90f97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::onCallArgumentSetup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call)</td>
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

<p>Called to account for the cost of argument setup for the Call in the callee's body (not the callsite currently under analysis).</p>

<p>Definition at line 679 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onCallBaseVisitStart() {#aa0e6bd8dbef28bdfd3489be6f5136df0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::onCallBaseVisitStart (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call)</td>
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

<p>Called when we visit a <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a>, before the analysis starts.</p>


<p>Return false to stop further processing of the instruction.</p>


<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onCallPenalty() {#a9b2deb019415338a4a09bb15811fc640}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::onCallPenalty ()</td>
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

<p>Called to account for a call.</p>

<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onDisableLoadElimination() {#a7da858f18c7a03458aeb08226e9372a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::onDisableLoadElimination ()</td>
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

<p>Called the analysis engine determines load elimination won't happen.</p>

<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onDisableSROA() {#ae442e9e3da86e5cd62cee5639590e0ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::onDisableSROA (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * Arg)</td>
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

<p>Called if the analysis engine decides SROA cannot be done for the given alloca.</p>

<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onFinalizeSwitch() {#a5656b4a23e5d2de32dda72eb7ca21c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::onFinalizeSwitch (unsigned JumpTableSize, unsigned NumCaseCluster, bool DefaultDestUndefined)</td>
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

<p>Called at the end of processing a switch instruction, with the given number of case clusters.</p>

<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onInitializeSROAArg() {#aa58288940d85aaefbc01968af456c248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::onInitializeSROAArg (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * Arg)</td>
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

<p>Start accounting potential benefits due to SROA for the given alloca.</p>

<p>Definition at line 751 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onInstructionAnalysisFinish() {#a9407d52b8ad783ac2890246728fd5078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::onInstructionAnalysisFinish (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Called after an instruction was analyzed.</p>

<p>Definition at line 802 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onInstructionAnalysisStart() {#a55b6b3f70e1525d8943e32cc3bac6498}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::onInstructionAnalysisStart (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Called before an instruction was analyzed.</p>

<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onLoadEliminationOpportunity() {#a60c66f621969fecf819ffca27b9659d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::onLoadEliminationOpportunity ()</td>
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

<p>Called to account for the expectation the inlining would result in a load elimination.</p>

<p>Definition at line 1067 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onLoadRelativeIntrinsic() {#ae387e4eac119b3cf2879cd1ae1683122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::onLoadRelativeIntrinsic ()</td>
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

<p>Called to account for a load relative intrinsic.</p>

<p>Definition at line 684 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onLoweredCall() {#ae4ffd0cd2f242d6a633b8bb4d24ef3ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::onLoweredCall (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call, bool IsIndirectCall)</td>
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

<p>Called to account for a lowered call.</p>

<p>Definition at line 688 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onMemAccess() {#a9bff49e0104b0cc58ff53e92d7ecc01f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::onMemAccess ()</td>
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

<p>Called to account for a load or store.</p>

<p>Definition at line 677 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onMissedSimplification() {#a3e474f3b935b0ed1db8194cdf9d08ebf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::onMissedSimplification ()</td>
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

<p>Called to account for any other instruction not specifically accounted for.</p>

<p>Definition at line 749 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### OverrideCycleSavingsAndSizeForTesting() {#aea34b9f810cfab5171844976f736353d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::OverrideCycleSavingsAndSizeForTesting (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; CycleSavings, int &amp; Size)</td>
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



<p>Definition at line 866 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### shouldStop() {#a242df7e489a6d485f2c31caefe583ab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::shouldStop ()</td>
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

<p>Called when we're about to start processing a basic block, and every time we are done processing an instruction.</p>


<p>Return true if there is no point in continuing the analysis (e.g. we've determined already the call site is too expensive to inline)</p>


<p>Definition at line 1056 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### updateThreshold() {#a1c691b0f71f23818b50648cb8f9f6817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InlineCostCallAnalyzer::updateThreshold (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Callee)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update Threshold based on callsite properties such as callee attributes and callee hotness for PGO builds.</p>


<p>The Callee is explicitly passed to support analyzing indirect calls whose target is inferred by analysis.</p>


<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Writer {#a11be613022253844628248a4922817d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineCostAnnotationWriter anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::Writer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Annotation Writer for instruction details.</p>

<p>Definition at line 1141 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a55d07c23093e29dd03456b0197d64f69">InlineCostCallAnalyzer</a> and <a href="#a2c1cb0941fc8289abfffced96bb006f6">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BoostIndirectCalls {#acc4c0caeca05f8d15338ac907c67b7e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::BoostIndirectCalls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to evaluate indirect calls to boost its inline cost.</p>

<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### ColdSize {#a8f4fae8e459a5271bf00e607b35157d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::ColdSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### ComputeFullInlineCost {#ac123ef981d1b1fcf6b6dcf4a5d1c8572}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::ComputeFullInlineCost</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### Cost {#a9eea997174c85f43a28dce42cf27c116}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::Cost = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Inlining cost measured in abstract units, accounts for all the instructions expected to be executed for a given function invocation.</p>


<p>Instructions that are statically proven to be dead based on call-site arguments are not counted here.</p>


<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### CostAtBBStart {#aae0664ccf0aed3faa0504eb775eb0667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::CostAtBBStart = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### CostBenefit {#a4f0e9dc8c8099d45c30cbc8f3fad6906}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;CostBenefitPair&gt; anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::CostBenefit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### CostBenefitAnalysisEnabled {#aff7e4e8702f2fec82d1fbec2f9c36e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::CostBenefitAnalysisEnabled</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### DecidedByCostBenefit {#a2ea5953e8d955f5297b244186c68299f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::DecidedByCostBenefit = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### DecidedByCostThreshold {#a6d16867943b98d472247eae8fc0cb54f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::DecidedByCostThreshold = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### IgnoreThreshold {#a282bdd4b2444cf1a17d5a10ecaaaed65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::IgnoreThreshold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Ignore the threshold when finalizing analysis.</p>

<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### InstructionCostDetailMap {#a879831754efb86bf5bbe27809e64ed35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Instruction *, InstructionCostDetail&gt; anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::InstructionCostDetailMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### LoadEliminationCost {#ac253cec66c9a63250750a9ea07cf0f82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::LoadEliminationCost = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### Params {#a1632fc82a67ad0a673cd3e670618d77a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InlineParams&amp; anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::Params</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tunable parameters that control the analysis.</p>

<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### SingleBB {#a65698928eddb5c730f5988aaf2562912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::SingleBB = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### SingleBBBonus {#a179fd61141b50c15f988bc83b2b7efd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::SingleBBBonus = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Bonus to be applied when the callee has only one reachable basic block.</p>

<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### SROAArgCosts {#a62f7dd2876e111bb5df3e9efc962c350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;AllocaInst *, int&gt; anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::SROAArgCosts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The mapping of caller Alloca values to their accumulated cost savings.</p>


<p>If we have to disable SROA for one of the allocas, this tells us how much cost must be added.</p>


<p>Definition at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### SROACostSavings {#ad5bfd85bc6db696ef5c4d8c3fcae564c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::SROACostSavings = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### SROACostSavingsLost {#acf9654d8f36ecf211715df80c62ccb4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::SROACostSavingsLost = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### StaticBonusApplied {#a114aa98686cf9af5c2b3b27333ee63fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::StaticBonusApplied = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The amount of StaticBonus applied.</p>

<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### Threshold {#a767c4d60fc8ec155bd386cde5e0d12cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::Threshold = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Upper bound for the inlining cost.</p>


<p>Bonuses are being applied to account for speculative "expected profit" of the inlining decision.</p>


<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### VectorBonus {#a2f6f1654097008a1ce8c3c0ac26d8594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::VectorBonus = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Bonus to be applied when percentage of vector instructions in callee is high (see more details in updateThreshold).</p>

<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
