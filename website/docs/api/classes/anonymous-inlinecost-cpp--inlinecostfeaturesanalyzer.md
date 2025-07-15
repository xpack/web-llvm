---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-inlinecost-cpp-/inlinecostfeaturesanalyzer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InlineCostFeaturesAnalyzer` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43085a138ca8d8072dde11d52a003a43">InlineCostFeaturesAnalyzer</a> (const TargetTransformInfo &amp;TTI, function_ref&lt; AssumptionCache &amp;(Function &amp;)&gt; &amp;GetAssumptionCache, function_ref&lt; BlockFrequencyInfo &amp;(Function &amp;)&gt; GetBFI, function_ref&lt; const TargetLibraryInfo &amp;(Function &amp;)&gt; GetTLI, ProfileSummaryInfo *PSI, OptimizationRemarkEmitter *ORE, Function &amp;Callee, CallBase &amp;Call)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#afb378b039e7d3081903c430bc6bafe0e">InlineCostFeatures</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a521a6316df4bef89467e1a3d7ba3689f">features</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62bb1b24d5cdbc0f1c104f3654a7b2cf">increment</a> (InlineCostFeatureIndex Feature, int64_t Delta=1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf0086a7fc7a1845562a9772f553a982">set</a> (InlineCostFeatureIndex Feature, int64_t Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1edc8f5096c98e3549c2998c67e101b">onDisableSROA</a> (AllocaInst *Arg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called if the analysis engine decides SROA cannot be done for the given alloca. <a href="#ac1edc8f5096c98e3549c2998c67e101b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c5c6b9953055acbb86b4fbef77518a5">onDisableLoadElimination</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called the analysis engine determines load elimination won't happen. <a href="#a7c5c6b9953055acbb86b4fbef77518a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7f8340222220979e27e3d78c4864cbc">onCallPenalty</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for a call. <a href="#ab7f8340222220979e27e3d78c4864cbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a917bf64e58dedbb1c36cdf14694731f3">onCallArgumentSetup</a> (const CallBase &amp;Call) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for the cost of argument setup for the Call in the callee's body (not the callsite currently under analysis). <a href="#a917bf64e58dedbb1c36cdf14694731f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa4e3444175f219db6c84b448ce5855a">onLoadRelativeIntrinsic</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for a load relative intrinsic. <a href="#afa4e3444175f219db6c84b448ce5855a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e82e1b9f77775b1ac646d5ad669b720">onLoweredCall</a> (Function *F, CallBase &amp;Call, bool IsIndirectCall) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for a lowered call. <a href="#a4e82e1b9f77775b1ac646d5ad669b720">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c11157c83ed1388315107b2ce807c06">onFinalizeSwitch</a> (unsigned JumpTableSize, unsigned NumCaseCluster, bool DefaultDestUndefined) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called at the end of processing a switch instruction, with the given number of case clusters. <a href="#a6c11157c83ed1388315107b2ce807c06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad971ce95070363d34e073180cec53124">onMissedSimplification</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for any other instruction not specifically accounted for. <a href="#ad971ce95070363d34e073180cec53124">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73151b2be2d8000c5101837c6844e2bc">onInitializeSROAArg</a> (AllocaInst *Arg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start accounting potential benefits due to SROA for the given alloca. <a href="#a73151b2be2d8000c5101837c6844e2bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84ebe74e28954375ed22331d82189743">onAggregateSROAUse</a> (AllocaInst *Arg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Account SROA savings for the <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> value. <a href="#a84ebe74e28954375ed22331d82189743">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae28d0daf96eeb81b14522e18c0b47ef9">onBlockAnalyzed</a> (const BasicBlock *BB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called after a basic block was analyzed. <a href="#ae28d0daf96eeb81b14522e18c0b47ef9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineresult">InlineResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a878d4e2508f2ea3a506a1ba6f996cec5">finalizeAnalysis</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called at the end of the analysis of the callsite. <a href="#a878d4e2508f2ea3a506a1ba6f996cec5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad4aedf845228e3d5669f90c7e504c91">shouldStop</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called when we're about to start processing a basic block, and every time we are done processing an instruction. <a href="#aad4aedf845228e3d5669f90c7e504c91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ad724bfd80234aa5a1cec05228dbaad">onLoadEliminationOpportunity</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for the expectation the inlining would result in a load elimination. <a href="#a3ad724bfd80234aa5a1cec05228dbaad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineresult">InlineResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a242ba901b6d8649850afa9a7f34333a9">onAnalysisStart</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called before the analysis of the callee body starts (with callsite contexts propagated). <a href="#a242ba901b6d8649850afa9a7f34333a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#afb378b039e7d3081903c430bc6bafe0e">InlineCostFeatures</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85d109ae927dec401ba27e0bd0b60207">Cost</a> = {}</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9bab947d6b8d72d70b3775ec9ac1a04">SROACostSavingOpportunities</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5444a567c00e859052b1b6ed80b456b">VectorBonus</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc6b3f4e5100da41c5a1687bd5bca320">SingleBBBonus</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5b7bcd6e39d1345a27979f7d40b6d17">Threshold</a> = 5</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff1cd133a4221ac70c5c13b46f2b9032">SROACosts</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeedca765d50899920c7fb69e00c2d5c1">JTCostMultiplier</a> = 2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0ca3282b4230fbbe6e10e0c504ad9db">CaseClusterCostMultiplier</a> = 2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e567d48ba2ea90d6e970e118da4caa6">SwitchDefaultDestCostMultiplier</a> = 2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada7f67e58868b34822b4d16ee91ff3d1">SwitchCostMultiplier</a> = 2</td>
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


<p>Definition at line 1172 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InlineCostFeaturesAnalyzer() {#a43085a138ca8d8072dde11d52a003a43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::InlineCostFeaturesAnalyzer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; &amp; GetAssumptionCache, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GetBFI, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GetTLI, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Callee, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call)</td>
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



<p>Definition at line 1371 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#afe415d5ca807552e9ab9180b7821f04d">anonymous{InlineCost.cpp}::CallAnalyzer::CallAnalyzer</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#acbdd4c0e06dc866ad2e68d57e194743e">anonymous{InlineCost.cpp}::CallAnalyzer::GetAssumptionCache</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a9d83f245e02c2d598444b73ea9a05459">anonymous{InlineCost.cpp}::CallAnalyzer::GetBFI</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#abef6e3800bbcc3d80dca77ce58b0eaa8">anonymous{InlineCost.cpp}::CallAnalyzer::GetTLI</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#aeee19cfe3d54e41a640e29f36056ecfb">anonymous{InlineCost.cpp}::CallAnalyzer::ORE</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a8c79183f67d088e0c9cd34511c3f848d">anonymous{InlineCost.cpp}::CallAnalyzer::PSI</a> and <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a453497ae3e6c0033f5609b932d472b11">anonymous{InlineCost.cpp}::CallAnalyzer::TTI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a8bc682ff4e05f8bbb181be693c717dd8">llvm::getInliningCostFeatures</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### features() {#a521a6316df4bef89467e1a3d7ba3689f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InlineCostFeatures &amp; anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::features ()</td>
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



<p>Definition at line 1381 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### finalizeAnalysis() {#a878d4e2508f2ea3a506a1ba6f996cec5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineResult anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::finalizeAnalysis ()</td>
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


<p>Definition at line 1309 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### increment() {#a62bb1b24d5cdbc0f1c104f3654a7b2cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::increment (<a href="/web-llvm/docs/api/namespaces/llvm/#a7ef78f96e07a124af3b346d8df9010cc">InlineCostFeatureIndex</a> Feature, int64_t Delta=1)</td>
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



<p>Definition at line 1193 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onAggregateSROAUse() {#a84ebe74e28954375ed22331d82189743}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::onAggregateSROAUse (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * V)</td>
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

<p>Definition at line 1298 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onAnalysisStart() {#a242ba901b6d8649850afa9a7f34333a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineResult anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::onAnalysisStart ()</td>
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


<p>Definition at line 1346 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onBlockAnalyzed() {#ae28d0daf96eeb81b14522e18c0b47ef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::onBlockAnalyzed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Definition at line 1303 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onCallArgumentSetup() {#a917bf64e58dedbb1c36cdf14694731f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::onCallArgumentSetup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call)</td>
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

<p>Definition at line 1219 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onCallPenalty() {#ab7f8340222220979e27e3d78c4864cbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::onCallPenalty ()</td>
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

<p>Definition at line 1215 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onDisableLoadElimination() {#a7c5c6b9953055acbb86b4fbef77518a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::onDisableLoadElimination ()</td>
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

<p>Definition at line 1211 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onDisableSROA() {#ac1edc8f5096c98e3549c2998c67e101b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::onDisableSROA (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * Arg)</td>
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

<p>Definition at line 1201 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onFinalizeSwitch() {#a6c11157c83ed1388315107b2ce807c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::onFinalizeSwitch (unsigned JumpTableSize, unsigned NumCaseCluster, bool DefaultDestUndefined)</td>
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

<p>Definition at line 1260 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onInitializeSROAArg() {#a73151b2be2d8000c5101837c6844e2bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::onInitializeSROAArg (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * Arg)</td>
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

<p>Definition at line 1292 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onLoadEliminationOpportunity() {#a3ad724bfd80234aa5a1cec05228dbaad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::onLoadEliminationOpportunity ()</td>
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

<p>Definition at line 1342 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onLoadRelativeIntrinsic() {#afa4e3444175f219db6c84b448ce5855a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::onLoadRelativeIntrinsic ()</td>
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

<p>Definition at line 1224 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onLoweredCall() {#a4e82e1b9f77775b1ac646d5ad669b720}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::onLoweredCall (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call, bool IsIndirectCall)</td>
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

<p>Definition at line 1228 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onMissedSimplification() {#ad971ce95070363d34e073180cec53124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::onMissedSimplification ()</td>
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

<p>Definition at line 1287 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### set() {#aaf0086a7fc7a1845562a9772f553a982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::set (<a href="/web-llvm/docs/api/namespaces/llvm/#a7ef78f96e07a124af3b346d8df9010cc">InlineCostFeatureIndex</a> Feature, int64_t Value)</td>
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



<p>Definition at line 1197 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### shouldStop() {#aad4aedf845228e3d5669f90c7e504c91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::shouldStop ()</td>
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


<p>Definition at line 1340 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Cost {#a85d109ae927dec401ba27e0bd0b60207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineCostFeatures anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::Cost = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1174 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### SingleBBBonus {#abc6b3f4e5100da41c5a1687bd5bca320}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::SingleBBBonus = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1188 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### SROACosts {#aff1cd133a4221ac70c5c13b46f2b9032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;AllocaInst *, unsigned&gt; anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::SROACosts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1191 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### SROACostSavingOpportunities {#aa9bab947d6b8d72d70b3775ec9ac1a04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::SROACostSavingOpportunities = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1186 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### Threshold {#ae5b7bcd6e39d1345a27979f7d40b6d17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::Threshold = 5</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1189 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### VectorBonus {#aa5444a567c00e859052b1b6ed80b456b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::VectorBonus = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1187 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### CaseClusterCostMultiplier {#af0ca3282b4230fbbe6e10e0c504ad9db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::CaseClusterCostMultiplier = 2</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1180 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### JTCostMultiplier {#aeedca765d50899920c7fb69e00c2d5c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::JTCostMultiplier = 2</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1179 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### SwitchCostMultiplier {#ada7f67e58868b34822b4d16ee91ff3d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::SwitchCostMultiplier = 2</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1182 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### SwitchDefaultDestCostMultiplier {#a3e567d48ba2ea90d6e970e118da4caa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::SwitchDefaultDestCostMultiplier = 2</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1181 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

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
