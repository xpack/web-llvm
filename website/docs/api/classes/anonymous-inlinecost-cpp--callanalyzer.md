---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-inlinecost-cpp-/callanalyzer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CallAnalyzer` Class Reference

<p>Carry out call site analysis, in order to evaluate inlinability. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{InlineCost.cpp}::CallAnalyzer { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instvisitor">InstVisitor&lt;SubClass, RetTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for instruction visitors. <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer">InlineCostCallAnalyzer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FIXME: if it is necessary to derive from <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer">InlineCostCallAnalyzer</a>, note the FIXME in onLoweredCall, when instantiating an <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer">InlineCostCallAnalyzer</a>. <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostfeaturesanalyzer">InlineCostFeaturesAnalyzer</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instvisitor">InstVisitor</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer">CallAnalyzer</a>, bool &gt; <a href="#a3e634481c023c076fdaacf8c8298bea5">Base</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a913f61550aa33ca03dce67a8d0496bf4">InstVisitor&lt; CallAnalyzer, bool &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe415d5ca807552e9ab9180b7821f04d">CallAnalyzer</a> (Function &amp;Callee, CallBase &amp;Call, const TargetTransformInfo &amp;TTI, function_ref&lt; AssumptionCache &amp;(Function &amp;)&gt; GetAssumptionCache, function_ref&lt; BlockFrequencyInfo &amp;(Function &amp;)&gt; GetBFI=nullptr, function_ref&lt; const TargetLibraryInfo &amp;(Function &amp;)&gt; GetTLI=nullptr, ProfileSummaryInfo *PSI=nullptr, OptimizationRemarkEmitter *ORE=nullptr)</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad269155fe1134581774b5da96e058901">~CallAnalyzer</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineresult">InlineResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze a call site for potential inlining. <a href="#a75514cc4632af88b58a31912c8bd9ecc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc1eb7f69eb6521e8d6b95e56f9507e0">getSimplifiedValue</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a717d4e1b4a02858b89c6d30a00e193da">dump</a> ()</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b9315ae40e6ab186a2ab8f8fbebcb00">onBlockStart</a> (const BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/extension">Extension</a> points for handling callsite features. <a href="#a5b9315ae40e6ab186a2ab8f8fbebcb00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37d759f043baaec8ec56bfc32e37b542">onBlockAnalyzed</a> (const BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called after a basic block was analyzed. <a href="#a37d759f043baaec8ec56bfc32e37b542">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa70f9c2689335ec7da9021e4b07e4186">onInstructionAnalysisStart</a> (const Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called before an instruction was analyzed. <a href="#aa70f9c2689335ec7da9021e4b07e4186">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7df683bd660c4ebe87fc3a1887632c2">onInstructionAnalysisFinish</a> (const Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called after an instruction was analyzed. <a href="#af7df683bd660c4ebe87fc3a1887632c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineresult">InlineResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7896a35fbca2436be392ec036dc8ddcf">finalizeAnalysis</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called at the end of the analysis of the callsite. <a href="#a7896a35fbca2436be392ec036dc8ddcf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af55600dce1a5561029506eaeb04db883">shouldStop</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called when we're about to start processing a basic block, and every time we are done processing an instruction. <a href="#af55600dce1a5561029506eaeb04db883">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineresult">InlineResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a562c4d99c3b86a6aed450011e796e2bf">onAnalysisStart</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called before the analysis of the callee body starts (with callsite contexts propagated). <a href="#a562c4d99c3b86a6aed450011e796e2bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afff99d7ead8a904458585b9575d4741e">onDisableSROA</a> (AllocaInst *Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called if the analysis engine decides SROA cannot be done for the given alloca. <a href="#afff99d7ead8a904458585b9575d4741e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6685b1c786d51e013f017789b21203a9">onDisableLoadElimination</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called the analysis engine determines load elimination won't happen. <a href="#a6685b1c786d51e013f017789b21203a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f3106adceeff67611da8e779b430992">onCallBaseVisitStart</a> (CallBase &amp;Call)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called when we visit a <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a>, before the analysis starts. <a href="#a1f3106adceeff67611da8e779b430992">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f344ebc1a6712ea865fb247c9529370">onCallPenalty</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for a call. <a href="#a5f344ebc1a6712ea865fb247c9529370">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd3d774e9a5084bcb94c24d93b02eb75">onMemAccess</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for a load or store. <a href="#abd3d774e9a5084bcb94c24d93b02eb75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9f09a27eaeea42942250f54a904a313">onLoadEliminationOpportunity</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for the expectation the inlining would result in a load elimination. <a href="#af9f09a27eaeea42942250f54a904a313">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a088deee3b0d6b7b1e01591ab3ff642e2">onCallArgumentSetup</a> (const CallBase &amp;Call)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for the cost of argument setup for the Call in the callee's body (not the callsite currently under analysis). <a href="#a088deee3b0d6b7b1e01591ab3ff642e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bf5b0a160668ce33c6979218aab047b">onLoadRelativeIntrinsic</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for a load relative intrinsic. <a href="#a7bf5b0a160668ce33c6979218aab047b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbe0f81b770474e05444f01f04ef40d8">onLoweredCall</a> (Function *F, CallBase &amp;Call, bool IsIndirectCall)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for a lowered call. <a href="#adbe0f81b770474e05444f01f04ef40d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb402e883ef3ee6a887279fc91fe5bc3">onJumpTable</a> (unsigned JumpTableSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Account for a jump table of given size. <a href="#abb402e883ef3ee6a887279fc91fe5bc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcf97fb54e3ee18ee8ca1cd3607367f8">onCaseCluster</a> (unsigned NumCaseCluster)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Account for a case cluster of given size. <a href="#abcf97fb54e3ee18ee8ca1cd3607367f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab86e085c1db1d8f6c05a1f42cf6905fa">onFinalizeSwitch</a> (unsigned JumpTableSize, unsigned NumCaseCluster, bool DefaultDestUndefined)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called at the end of processing a switch instruction, with the given number of case clusters. <a href="#ab86e085c1db1d8f6c05a1f42cf6905fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82b9146fe4fa59ad91ff072fa1e3e7db">onMissedSimplification</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to account for any other instruction not specifically accounted for. <a href="#a82b9146fe4fa59ad91ff072fa1e3e7db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90d8614f92705f7e0c10a3191c1740bb">onInitializeSROAArg</a> (AllocaInst *Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start accounting potential benefits due to SROA for the given alloca. <a href="#a90d8614f92705f7e0c10a3191c1740bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f02814b67b7dbb3ea2d209772e9266b">onAggregateSROAUse</a> (AllocaInst *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Account SROA savings for the <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> value. <a href="#a0f02814b67b7dbb3ea2d209772e9266b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88a00622ca09943b559df33fd3ab5368">handleSROA</a> (Value *V, bool DoNotDisable)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21e542376017e5ca79b65d8e7e88bb7e">getSROAArgForValueOrNull</a> (Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a50892c7dc3861ea72c3c405ca11c9ade">getDirectOrSimplifiedValue</a> (Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> a value in its given form directly if possible, otherwise try looking for it in SimplifiedValues. <a href="#a50892c7dc3861ea72c3c405ca11c9ade">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b78c476557e705479c1441daad05710">isAllocaDerivedArg</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the given value is an Alloca-derived function argument. <a href="#a7b78c476557e705479c1441daad05710">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5496199bfbb2bef5b08262bc8c719e35">disableSROAForArg</a> (AllocaInst *SROAArg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1206e5afb15409ca7e5bc27ee39fad2c">disableSROA</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If 'V' maps to a SROA candidate, disable SROA for it. <a href="#a1206e5afb15409ca7e5bc27ee39fad2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5c8e1b8ca1f8eb101829d9fe2062c4e">findDeadBlocks</a> (BasicBlock *CurrBB, BasicBlock *NextBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find dead blocks due to deleted CFG edges during inlining. <a href="#af5c8e1b8ca1f8eb101829d9fe2062c4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab715ffbc71efba180f5c27d28a6e0340">disableLoadElimination</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cd79b520cf0ecc13ef7f9fe36db74fc">isGEPFree</a> (GetElementPtrInst &amp;GEP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> TTI to check whether a GEP is free. <a href="#a6cd79b520cf0ecc13ef7f9fe36db74fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa21914d28815e593b0354ca4923e1e22">canFoldInboundsGEP</a> (GetElementPtrInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check we can fold GEPs of constant-offset call site argument pointers. <a href="#aa21914d28815e593b0354ca4923e1e22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec8a5b489575aed066c15608ea3b9b81">accumulateGEPOffset</a> (GEPOperator &amp;GEP, APInt &amp;Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accumulate a constant GEP offset into an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> if possible. <a href="#aec8a5b489575aed066c15608ea3b9b81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d4c970d99f3ffebfe1e07a3be697b09">simplifyCallSite</a> (Function *F, CallBase &amp;Call)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to simplify a call site. <a href="#a5d4c970d99f3ffebfe1e07a3be697b09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7df35706e1cddf8fa5565622850e1fc7">simplifyInstruction</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simplify <span class="doxyComputerOutput">I</span> if its operands are constants and update SimplifiedValues. <a href="#a7df35706e1cddf8fa5565622850e1fc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a020bb3b63fcf4ec2941fd868101f8914">simplifyIntrinsicCallIsConstant</a> (CallBase &amp;CB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to simplify a call to llvm.is.constant. <a href="#a020bb3b63fcf4ec2941fd868101f8914">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb999adbc0664256b33b94d266a8b9da">simplifyIntrinsicCallObjectSize</a> (CallBase &amp;CB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fd3732392fdbdbc5a4436c0f1262999">stripAndComputeInBoundsConstantOffsets</a> (Value *&amp;V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the base pointer and cumulative constant offsets for V. <a href="#a0fd3732392fdbdbc5a4436c0f1262999">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f1d4c503f57491de3cad8ff6d1512c4">isLoweredToCall</a> (Function *F, CallBase &amp;Call)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22be0f88c5ce84cfb46410c66ddd79a9">paramHasAttr</a> (Argument *A, Attribute::AttrKind Attr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given argument to the function being considered for inlining has the given attribute set either at the call site or the function declaration. <a href="#a22be0f88c5ce84cfb46410c66ddd79a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd9970e2a4ba6e031330672eb089504a">isKnownNonNullInCallee</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given value is known non null within the callee if inlined through this particular callsite. <a href="#acd9970e2a4ba6e031330672eb089504a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a944dede4b00a3db0322e30dd22af8cde">allowSizeGrowth</a> (CallBase &amp;Call)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if size growth is allowed when inlining the callee at <span class="doxyComputerOutput">Call</span>. <a href="#a944dede4b00a3db0322e30dd22af8cde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineresult">InlineResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a> (BasicBlock *BB, SmallPtrSetImpl&lt; const Value * &gt; &amp;EphValues)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze a basic block for its contribution to the inline cost. <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91d6a0c115261ac2a9a8cae93214d141">visit</a> (Module *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea8de7d26e5d948fdcaafbcccd644f41">visit</a> (Module &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7869bc3bb0c3adae6d1323e233e562f8">visit</a> (Function *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5be3a8f92ab5179eff41697cbd4a9cc6">visit</a> (Function &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13342c73041eccefc6eaae7f16dd67ff">visit</a> (BasicBlock *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a> (BasicBlock &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dbd891d0d59986f7c113e438672df0b">visitInstruction</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac200dd1657275c933c8a4acc7fa0f57">visitAlloca</a> (AllocaInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f8ae02669694e3f056dc0e083b3ebbf">visitPHI</a> (PHINode &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa99e14a7059ad7f3028d950ac47c6877">visitGetElementPtr</a> (GetElementPtrInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f196ca25e9a1989af2b7f5b8e2a582f">visitBitCast</a> (BitCastInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6ae551b875c8a176bd745beea48ce52">visitPtrToInt</a> (PtrToIntInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad778e917372e690fc3098b635b6d615c">visitIntToPtr</a> (IntToPtrInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cc7f5478ccf8b005f1cf5110e2069ce">visitCastInst</a> (CastInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee291a74c02dc725df8472084fab1377">visitCmpInst</a> (CmpInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1db98282963c5e756ec5ea85661d9627">visitSub</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5293e25f888cdf9f581c2e451e202e5">visitBinaryOperator</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afafedd81571bcf8dcc76d0e6688cc3e1">visitFNeg</a> (UnaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af36c571c9d12be5e0f8cbfdd19d48e40">visitLoad</a> (LoadInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ccb3c3fafb73d9b68db47a4ee22080e">visitStore</a> (StoreInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab00dc4d624643140d27f5174991c31a3">visitExtractValue</a> (ExtractValueInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae4a0baa949621cec86c8566b21eb879">visitInsertValue</a> (InsertValueInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a> (CallBase &amp;Call)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabb7899117ee8c00f2095b4bc6c1d7da">visitReturnInst</a> (ReturnInst &amp;RI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a070509ca4afed69062174feb05ef7022">visitBranchInst</a> (BranchInst &amp;BI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30ffae9770fcd56cb0245c1a7a0e9a9d">visitSelectInst</a> (SelectInst &amp;SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1233ad338a28e192e52c0f891285d2e4">visitSwitchInst</a> (SwitchInst &amp;SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8f07bb2f659c26f6d223037859aa01e">visitIndirectBrInst</a> (IndirectBrInst &amp;IBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02f0e0d29d63db2e01675e7caa6be873">visitResumeInst</a> (ResumeInst &amp;RI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93a27ef49052815cbd0da76923620dff">visitCleanupReturnInst</a> (CleanupReturnInst &amp;RI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6880f58987f823c1969bbbbbc489c203">visitCatchReturnInst</a> (CatchReturnInst &amp;RI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50409139e337f2e5e106830a69a63692">visitUnreachableInst</a> (UnreachableInst &amp;I)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5635dea24d14ac5e3840263d19e63a6a">NumConstantArgs</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46dd2f959cdfce95cee14bf9f5fd750b">NumConstantOffsetPtrArgs</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3a1ead12644ce26ba1d064b4271df7e">NumAllocaArgs</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a446676eb6e2a94add6ae60b02a13335e">NumConstantPtrCmps</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae257151eedfc737f3db3fe122deade01">NumConstantPtrDiffs</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab90e06182887adcb3b5fe8cd59afb68a">NumInstructionsSimplified</a> = 0</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a453497ae3e6c0033f5609b932d472b11">TTI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> available for this compilation. <a href="#a453497ae3e6c0033f5609b932d472b11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbdd4c0e06dc866ad2e68d57e194743e">GetAssumptionCache</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Getter for the cache of @llvm.assume intrinsics. <a href="#acbdd4c0e06dc866ad2e68d57e194743e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d83f245e02c2d598444b73ea9a05459">GetBFI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Getter for <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a>. <a href="#a9d83f245e02c2d598444b73ea9a05459">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abef6e3800bbcc3d80dca77ce58b0eaa8">GetTLI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Getter for <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a>. <a href="#abef6e3800bbcc3d80dca77ce58b0eaa8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c79183f67d088e0c9cd34511c3f848d">PSI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Profile summary information. <a href="#a8c79183f67d088e0c9cd34511c3f848d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0d73af9a3aaefb80f59550a218c40f2">F</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The called function. <a href="#aa0d73af9a3aaefb80f59550a218c40f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa28926a931a607351c475a9c093b0e6c">DL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeee19cfe3d54e41a640e29f36056ecfb">ORE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> available for this compilation. <a href="#aeee19cfe3d54e41a640e29f36056ecfb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf27e0fe73330b76c1ffd00ea2116e78">CandidateCall</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The candidate callsite being analyzed. <a href="#aaf27e0fe73330b76c1ffd00ea2116e78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af69c5ad959fb12d6a57ad0e564d8fcdb">IsCallerRecursive</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc765c96c7d8d3e3edd98ee1e3fcd890">IsRecursiveCall</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27264677757b771cd51f78d572ab6f35">ExposesReturnsTwice</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99810ffb5ff5fca01b564419989d13f2">HasDynamicAlloca</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9600de48f592771fe50cad7071b6fcb3">ContainsNoDuplicateCall</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aabb7a01a2a512e3166793f6da18119">HasReturn</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8570f46f65e53caf3255df66b9c86dbd">HasIndirectBr</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ad9dcd777748306a37b25db1479b97a">HasUninlineableIntrinsic</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9d5185e99bb36b8cb0cfd0128fa37d8">InitsVargArgs</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae50139d45349e59707efe9f1aa1dbb56">AllocatedSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of bytes allocated statically by the callee. <a href="#ae50139d45349e59707efe9f1aa1dbb56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a779e8a97453bc9d5ab3a09e2be4b864d">NumInstructions</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b7a6043a133a09e178d84fb077a28cf">NumVectorInstructions</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae6549033be6c24910989a2f8d4952b0">SimplifiedValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>While we walk the potentially-inlined instructions, we build up and maintain a mapping of simplified values specific to this callsite. <a href="#aae6549033be6c24910989a2f8d4952b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3be51cd1c47211784cfe67351f08f005">SROAArgValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of the values which map back (through function arguments) to allocas on the caller stack which could be simplified through SROA. <a href="#a3be51cd1c47211784cfe67351f08f005">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3038b138382170af89523fc9fd83dac9">EnabledSROAAllocas</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of Allocas for which we believe we may get SROA optimization. <a href="#a3038b138382170af89523fc9fd83dac9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a735b8e924de5ae9d3a55f897a7df3d97">ConstantOffsetPtrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of values which map to a pointer base and constant offset. <a href="#a735b8e924de5ae9d3a55f897a7df3d97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d4623a1bd5b3ffd272898c0a9160f9f">DeadBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of dead blocks due to the constant arguments. <a href="#a0d4623a1bd5b3ffd272898c0a9160f9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bae74199b4bcb353a5ae36e9136a368">KnownSuccessors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The mapping of the blocks to their known unique successors due to the constant arguments. <a href="#a0bae74199b4bcb353a5ae36e9136a368">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93bb085a370b19e25c700d9885f3440d">EnableLoadElimination</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Model the elimination of repeated loads that is expected to happen whenever we simplify away the stores that would otherwise cause them to be loads. <a href="#a93bb085a370b19e25c700d9885f3440d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1d2fb22fed73c219030de9b2d8dfa43">AllowRecursiveCall</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether we allow inlining for recursive call. <a href="#aa1d2fb22fed73c219030de9b2d8dfa43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe3ab2ee40110e35408b8b6700f1ca3a">LoadAddrSet</a></td>
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

<p>Carry out call site analysis, in order to evaluate inlinability.</p>


<p>NOTE: the type is currently used as implementation detail of functions such as <a href="/web-llvm/docs/api/namespaces/llvm/#a5f5f248d08aa55c63e5bc7a8304a7319">llvm::getInlineCost</a>. Note the <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a> constructor parameters - the expectation is that they come from the outer scope, from the wrapper functions. If we want to support constructing <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer">CallAnalyzer</a> objects where lambdas are provided inline at construction, or where the object needs to otherwise survive past the scope of the provided functions, we need to revisit the argument types.</p>


<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### Base {#a3e634481c023c076fdaacf8c8298bea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef InstVisitor&lt;CallAnalyzer, bool&gt; anonymous{InlineCost.cpp}::CallAnalyzer::Base</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### InstVisitor&lt; CallAnalyzer, bool &gt; {#a913f61550aa33ca03dce67a8d0496bf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/instvisitor">InstVisitor</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer">CallAnalyzer</a>, bool &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Reference <a href="#afe415d5ca807552e9ab9180b7821f04d">CallAnalyzer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CallAnalyzer() {#afe415d5ca807552e9ab9180b7821f04d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InlineCost.cpp}::CallAnalyzer::CallAnalyzer (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Callee, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GetAssumptionCache, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GetBFI=nullptr, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GetTLI=nullptr, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI=nullptr, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE=nullptr)</td>
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



<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#aaf27e0fe73330b76c1ffd00ea2116e78">CandidateCall</a>, <a href="#aa28926a931a607351c475a9c093b0e6c">DL</a>, <a href="#aa0d73af9a3aaefb80f59550a218c40f2">F</a>, <a href="#acbdd4c0e06dc866ad2e68d57e194743e">GetAssumptionCache</a>, <a href="#a9d83f245e02c2d598444b73ea9a05459">GetBFI</a>, <a href="#abef6e3800bbcc3d80dca77ce58b0eaa8">GetTLI</a>, <a href="#aeee19cfe3d54e41a640e29f36056ecfb">ORE</a>, <a href="#a8c79183f67d088e0c9cd34511c3f848d">PSI</a> and <a href="#a453497ae3e6c0033f5609b932d472b11">TTI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer/#a55d07c23093e29dd03456b0197d64f69">anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::InlineCostCallAnalyzer</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostfeaturesanalyzer/#a43085a138ca8d8072dde11d52a003a43">anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::InlineCostFeaturesAnalyzer</a> and <a href="#a913f61550aa33ca03dce67a8d0496bf4">InstVisitor&lt; CallAnalyzer, bool &gt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~CallAnalyzer() {#ad269155fe1134581774b5da96e058901}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual anonymous{InlineCost.cpp}::CallAnalyzer::~CallAnalyzer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### analyze() {#a75514cc4632af88b58a31912c8bd9ecc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineResult CallAnalyzer::analyze ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze a call site for potential inlining.</p>


<p>Returns true if inlining this call is viable, and false if it is not viable. It computes the cost and adjusts the threshold based on numerous factors and heuristics. If this method returns false but the computed cost is below the computed threshold, then inlining was forcibly disabled by some artifact of the routine.</p>


<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#ae50139d45349e59707efe9f1aa1dbb56">AllocatedSize</a>, <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#aaf27e0fe73330b76c1ffd00ea2116e78">CandidateCall</a>, <a href="/web-llvm/docs/api/structs/llvm/codemetrics/#a7e174506b52ad46ea1f746a7f727d999">llvm::CodeMetrics::collectEphemeralValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="#a735b8e924de5ae9d3a55f897a7df3d97">ConstantOffsetPtrs</a>, <a href="#a9600de48f592771fe50cad7071b6fcb3">ContainsNoDuplicateCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a266367eb01c634406b32f816d2d9c6bf">llvm::BasicBlock::empty</a>, <a href="#a3038b138382170af89523fc9fd83dac9">EnabledSROAAllocas</a>, <a href="#aa0d73af9a3aaefb80f59550a218c40f2">F</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineresult/#a77027fdc657b15aa5dd3d022e0fc07d3">llvm::InlineResult::failure</a>, <a href="#a7896a35fbca2436be392ec036dc8ddcf">finalizeAnalysis</a>, <a href="#af5c8e1b8ca1f8eb101829d9fe2062c4e">findDeadBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/blockaddress/#af6e2f535824d8f9b4bf1b1a75e5ab57c">llvm::BlockAddress::get</a>, <a href="#acbdd4c0e06dc866ad2e68d57e194743e">GetAssumptionCache</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a24380444e7b6b5af3e742282c87d4219">llvm::getStringFnAttrAsInt</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a315f26c899f5ea8a780db4740ba95ef4">llvm::BasicBlock::hasAddressTaken</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#af69c5ad959fb12d6a57ad0e564d8fcdb">IsCallerRecursive</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-inlinecost-cpp-/#aaa4a24113a96ba45e9dc3e45a42a5b57">anonymous{InlineCost.cpp}::isSoleCallToLocalFunction</a>, <a href="#a0bae74199b4bcb353a5ae36e9136a368">KnownSuccessors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/inlineconstants/#aaa82a5af56de7ce383f94bd9f4e2bee3">llvm::InlineConstants::MaxInlineStackSizeAttributeName</a>, <a href="#af3a1ead12644ce26ba1d064b4271df7e">NumAllocaArgs</a>, <a href="#a5635dea24d14ac5e3840263d19e63a6a">NumConstantArgs</a>, <a href="#a46dd2f959cdfce95cee14bf9f5fd750b">NumConstantOffsetPtrArgs</a>, <a href="#a562c4d99c3b86a6aed450011e796e2bf">onAnalysisStart</a>, <a href="#a37d759f043baaec8ec56bfc32e37b542">onBlockAnalyzed</a>, <a href="#a5b9315ae40e6ab186a2ab8f8fbebcb00">onBlockStart</a>, <a href="#a90d8614f92705f7e0c10a3191c1740bb">onInitializeSROAArg</a>, <a href="#af55600dce1a5561029506eaeb04db883">shouldStop</a>, <a href="#aae6549033be6c24910989a2f8d4952b0">SimplifiedValues</a>, <a href="#a3be51cd1c47211784cfe67351f08f005">SROAArgValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp/#a5e2872a6754754edd122ed397dcc68ad">StackSizeThreshold</a>, <a href="#a0fd3732392fdbdbc5a4436c0f1262999">stripAndComputeInBoundsConstantOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineresult/#a364fcb5fb838e7ca83b9fc379bcb4a0a">llvm::InlineResult::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#ac2f338c3f467b3d09613e190d73044a5">users</a>.</p>

</div>
</div>

### dump() {#a717d4e1b4a02858b89c6d30a00e193da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::CallAnalyzer::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### getSimplifiedValue() {#acc1eb7f69eb6521e8d6b95e56f9507e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Constant * &gt; anonymous{InlineCost.cpp}::CallAnalyzer::getSimplifiedValue (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#aae6549033be6c24910989a2f8d4952b0">SimplifiedValues</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### accumulateGEPOffset() {#aec8a5b489575aed066c15608ea3b9b81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::accumulateGEPOffset (<a href="/web-llvm/docs/api/classes/llvm/gepoperator">GEPOperator</a> &amp; GEP, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Offset)</td>
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

<p>Accumulate a constant GEP offset into an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> if possible.</p>


<p>Returns false if unable to compute the offset for any reason. Respects any simplified values known during the analysis of this callsite.</p>


<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa28926a931a607351c475a9c093b0e6c">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac828b9b52935f87659a4adf237f820a3">llvm::gep_type_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a43c6ebb4fd35ebd815d66a2df4eed0b9">llvm::gep_type_end</a>, <a href="#a50892c7dc3861ea72c3c405ca11c9ade">getDirectOrSimplifiedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/structlayout/#a3932cc53acb297750961bfdaa86425bc">llvm::StructLayout::getElementOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#af7e1934ed72a405ef073ea5f9bbe828e">llvm::ConstantInt::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#ac09a21c371a9c535cbc13e8f82503aec">llvm::ConstantInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a882d55a6aa2028e1a5ad708b275334e0">llvm::ConstantInt::isZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a9b5fc98b47d44d1150d3610bdfab1430">llvm::APInt::sextOrTrunc</a>.</p>


<p>Referenced by <a href="#aa21914d28815e593b0354ca4923e1e22">canFoldInboundsGEP</a> and <a href="#a0fd3732392fdbdbc5a4436c0f1262999">stripAndComputeInBoundsConstantOffsets</a>.</p>

</div>
</div>

### allowSizeGrowth() {#a944dede4b00a3db0322e30dd22af8cde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::allowSizeGrowth (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call)</td>
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

<p>Return true if size growth is allowed when inlining the callee at <span class="doxyComputerOutput">Call</span>.</p>

<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### analyzeBlock() {#ace15c0f86fa672d5a700a5f76b8b43e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineResult CallAnalyzer::analyzeBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; EphValues)</td>
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

<p>Analyze a basic block for its contribution to the inline cost.</p>


<p>This method walks the analyzer over every instruction in the given basic block and accounts for their cost during inlining at this callsite. It aborts early if the threshold has been exceeded or an impossible to inline construct has been detected. It returns false if inlining is no longer viable, and true if inlining remains viable.</p>


<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#ae50139d45349e59707efe9f1aa1dbb56">AllocatedSize</a>, <a href="#aa1d2fb22fed73c219030de9b2d8dfa43">AllowRecursiveCall</a>, <a href="#aaf27e0fe73330b76c1ffd00ea2116e78">CandidateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="#a27264677757b771cd51f78d572ab6f35">ExposesReturnsTwice</a>, <a href="#aa0d73af9a3aaefb80f59550a218c40f2">F</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineresult/#a77027fdc657b15aa5dd3d022e0fc07d3">llvm::InlineResult::failure</a>, <a href="#a99810ffb5ff5fca01b564419989d13f2">HasDynamicAlloca</a>, <a href="#a8570f46f65e53caf3255df66b9c86dbd">HasIndirectBr</a>, <a href="#a2ad9dcd777748306a37b25db1479b97a">HasUninlineableIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aa9d5185e99bb36b8cb0cfd0128fa37d8">InitsVargArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#af69c5ad959fb12d6a57ad0e564d8fcdb">IsCallerRecursive</a>, <a href="#afc765c96c7d8d3e3edd98ee1e3fcd890">IsRecursiveCall</a>, <a href="#a779e8a97453bc9d5ab3a09e2be4b864d">NumInstructions</a>, <a href="#ab90e06182887adcb3b5fe8cd59afb68a">NumInstructionsSimplified</a>, <a href="#a5b7a6043a133a09e178d84fb077a28cf">NumVectorInstructions</a>, <a href="#af7df683bd660c4ebe87fc3a1887632c2">onInstructionAnalysisFinish</a>, <a href="#aa70f9c2689335ec7da9021e4b07e4186">onInstructionAnalysisStart</a>, <a href="#a82b9146fe4fa59ad91ff072fa1e3e7db">onMissedSimplification</a>, <a href="#aeee19cfe3d54e41a640e29f36056ecfb">ORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp/#a3fde05a477a4d3ca1cc14119a46dfee9">RecurStackSizeThreshold</a>, <a href="#af55600dce1a5561029506eaeb04db883">shouldStop</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineresult/#a364fcb5fb838e7ca83b9fc379bcb4a0a">llvm::InlineResult::success</a> and <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a6352e72d11377a9c62f24434ae869bf0">llvm::InstVisitor&lt; CallAnalyzer, bool &gt;::visit</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a>.</p>

</div>
</div>

### canFoldInboundsGEP() {#aa21914d28815e593b0354ca4923e1e22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::canFoldInboundsGEP (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> &amp; I)</td>
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

<p>Check we can fold GEPs of constant-offset call site argument pointers.</p>


<p>This requires target data and inbounds GEPs.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the specified GEP can be folded.</p></dd>
</dl>


<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#aec8a5b489575aed066c15608ea3b9b81">accumulateGEPOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a735b8e924de5ae9d3a55f897a7df3d97">ConstantOffsetPtrs</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#aa99e14a7059ad7f3028d950ac47c6877">visitGetElementPtr</a>.</p>

</div>
</div>

### disableLoadElimination() {#ab715ffbc71efba180f5c27d28a6e0340}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallAnalyzer::disableLoadElimination ()</td>
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



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#a93bb085a370b19e25c700d9885f3440d">EnableLoadElimination</a> and <a href="#a6685b1c786d51e013f017789b21203a9">onDisableLoadElimination</a>.</p>


<p>Referenced by <a href="#a5496199bfbb2bef5b08262bc8c719e35">disableSROAForArg</a>, <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a> and <a href="#a1ccb3c3fafb73d9b68db47a4ee22080e">visitStore</a>.</p>

</div>
</div>

### disableSROA() {#a1206e5afb15409ca7e5bc27ee39fad2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallAnalyzer::disableSROA (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>If 'V' maps to a SROA candidate, disable SROA for it.</p>

<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#a5496199bfbb2bef5b08262bc8c719e35">disableSROAForArg</a> and <a href="#a21e542376017e5ca79b65d8e7e88bb7e">getSROAArgForValueOrNull</a>.</p>


<p>Referenced by <a href="#aac200dd1657275c933c8a4acc7fa0f57">visitAlloca</a>, <a href="#ac5293e25f888cdf9f581c2e451e202e5">visitBinaryOperator</a>, <a href="#a0cc7f5478ccf8b005f1cf5110e2069ce">visitCastInst</a>, <a href="#afafedd81571bcf8dcc76d0e6688cc3e1">visitFNeg</a> and <a href="#a2dbd891d0d59986f7c113e438672df0b">visitInstruction</a>.</p>

</div>
</div>

### disableSROAForArg() {#a5496199bfbb2bef5b08262bc8c719e35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallAnalyzer::disableSROAForArg (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * SROAArg)</td>
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



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#ab715ffbc71efba180f5c27d28a6e0340">disableLoadElimination</a>, <a href="#a3038b138382170af89523fc9fd83dac9">EnabledSROAAllocas</a> and <a href="#afff99d7ead8a904458585b9575d4741e">onDisableSROA</a>.</p>


<p>Referenced by <a href="#a1206e5afb15409ca7e5bc27ee39fad2c">disableSROA</a>, <a href="#a88a00622ca09943b559df33fd3ab5368">handleSROA</a> and <a href="#aa99e14a7059ad7f3028d950ac47c6877">visitGetElementPtr</a>.</p>

</div>
</div>

### finalizeAnalysis() {#a7896a35fbca2436be392ec036dc8ddcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual InlineResult anonymous{InlineCost.cpp}::CallAnalyzer::finalizeAnalysis ()</td>
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

<p>Called at the end of the analysis of the callsite.</p>


<p>Return the outcome of the analysis, i.e. 'InlineResult(true)' if the inlining may happen, or the reason it can't.</p>


<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/inlineresult/#a364fcb5fb838e7ca83b9fc379bcb4a0a">llvm::InlineResult::success</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a>.</p>

</div>
</div>

### findDeadBlocks() {#af5c8e1b8ca1f8eb101829d9fe2062c4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallAnalyzer::findDeadBlocks (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * CurrBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * NextBB)</td>
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

<p>Find dead blocks due to deleted CFG edges during inlining.</p>


<p>If we know the successor of the current block, <span class="doxyComputerOutput">CurrBB</span>, has to be <span class="doxyComputerOutput">NextBB</span>, the other successors of <span class="doxyComputerOutput">CurrBB</span> are dead if these successors have no live incoming CFG edges. If one block is found to be dead, we can continue growing the dead block list by checking the successors of the dead blocks to see if all their incoming edges are dead or not.</p>


<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="#a0d4623a1bd5b3ffd272898c0a9160f9f">DeadBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a0bae74199b4bcb353a5ae36e9136a368">KnownSuccessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a>.</p>

</div>
</div>

### getDirectOrSimplifiedValue() {#a50892c7dc3861ea72c3c405ca11c9ade}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * anonymous{InlineCost.cpp}::CallAnalyzer::getDirectOrSimplifiedValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> a value in its given form directly if possible, otherwise try looking for it in SimplifiedValues.</p>

<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a> and <a href="#aae6549033be6c24910989a2f8d4952b0">SimplifiedValues</a>.</p>


<p>Referenced by <a href="#aec8a5b489575aed066c15608ea3b9b81">accumulateGEPOffset</a>, <a href="#a7f1d4c503f57491de3cad8ff6d1512c4">isLoweredToCall</a>, <a href="#a5d4c970d99f3ffebfe1e07a3be697b09">simplifyCallSite</a>, <a href="#a7df35706e1cddf8fa5565622850e1fc7">simplifyInstruction</a>, <a href="#a020bb3b63fcf4ec2941fd868101f8914">simplifyIntrinsicCallIsConstant</a>, <a href="#ac5293e25f888cdf9f581c2e451e202e5">visitBinaryOperator</a>, <a href="#a070509ca4afed69062174feb05ef7022">visitBranchInst</a>, <a href="#afafedd81571bcf8dcc76d0e6688cc3e1">visitFNeg</a>, <a href="#aa99e14a7059ad7f3028d950ac47c6877">visitGetElementPtr</a>, <a href="#a0f8ae02669694e3f056dc0e083b3ebbf">visitPHI</a>, <a href="#a30ffae9770fcd56cb0245c1a7a0e9a9d">visitSelectInst</a> and <a href="#a1233ad338a28e192e52c0f891285d2e4">visitSwitchInst</a>.</p>

</div>
</div>

### getSROAArgForValueOrNull() {#a21e542376017e5ca79b65d8e7e88bb7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst * anonymous{InlineCost.cpp}::CallAnalyzer::getSROAArgForValueOrNull (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#a3038b138382170af89523fc9fd83dac9">EnabledSROAAllocas</a> and <a href="#a3be51cd1c47211784cfe67351f08f005">SROAArgValues</a>.</p>


<p>Referenced by <a href="#a1206e5afb15409ca7e5bc27ee39fad2c">disableSROA</a>, <a href="#a88a00622ca09943b559df33fd3ab5368">handleSROA</a>, <a href="#a0f196ca25e9a1989af2b7f5b8e2a582f">visitBitCast</a>, <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a>, <a href="#aa99e14a7059ad7f3028d950ac47c6877">visitGetElementPtr</a>, <a href="#ad778e917372e690fc3098b635b6d615c">visitIntToPtr</a>, <a href="#a0f8ae02669694e3f056dc0e083b3ebbf">visitPHI</a>, <a href="#ad6ae551b875c8a176bd745beea48ce52">visitPtrToInt</a> and <a href="#a30ffae9770fcd56cb0245c1a7a0e9a9d">visitSelectInst</a>.</p>

</div>
</div>

### handleSROA() {#a88a00622ca09943b559df33fd3ab5368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::CallAnalyzer::handleSROA (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, bool DoNotDisable)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#a5496199bfbb2bef5b08262bc8c719e35">disableSROAForArg</a>, <a href="#a21e542376017e5ca79b65d8e7e88bb7e">getSROAArgForValueOrNull</a> and <a href="#a0f02814b67b7dbb3ea2d209772e9266b">onAggregateSROAUse</a>.</p>


<p>Referenced by <a href="#aee291a74c02dc725df8472084fab1377">visitCmpInst</a>, <a href="#af36c571c9d12be5e0f8cbfdd19d48e40">visitLoad</a> and <a href="#a1ccb3c3fafb73d9b68db47a4ee22080e">visitStore</a>.</p>

</div>
</div>

### isAllocaDerivedArg() {#a7b78c476557e705479c1441daad05710}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::isAllocaDerivedArg (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Test whether the given value is an Alloca-derived function argument.</p>

<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Reference <a href="#a3be51cd1c47211784cfe67351f08f005">SROAArgValues</a>.</p>


<p>Referenced by <a href="#acd9970e2a4ba6e031330672eb089504a">isKnownNonNullInCallee</a>.</p>

</div>
</div>

### isGEPFree() {#a6cd79b520cf0ecc13ef7f9fe36db74fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::isGEPFree (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> &amp; GEP)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> TTI to check whether a GEP is free.</p>


<p>Respects any simplified values known during the analysis of this callsite.</p>


<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#aae6549033be6c24910989a2f8d4952b0">SimplifiedValues</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272ca89f768b1267e3083b4eb05b4ab77e717">llvm::TargetTransformInfo::TCC_Free</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba7f80055e1969cb850739546467460ad8">llvm::TargetTransformInfo::TCK_SizeAndLatency</a> and <a href="#a453497ae3e6c0033f5609b932d472b11">TTI</a>.</p>


<p>Referenced by <a href="#aa99e14a7059ad7f3028d950ac47c6877">visitGetElementPtr</a>.</p>

</div>
</div>

### isKnownNonNullInCallee() {#acd9970e2a4ba6e031330672eb089504a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::isKnownNonNullInCallee (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Return true if the given value is known non null within the callee if inlined through this particular callsite.</p>

<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a7b78c476557e705479c1441daad05710">isAllocaDerivedArg</a> and <a href="#a22be0f88c5ce84cfb46410c66ddd79a9">paramHasAttr</a>.</p>


<p>Referenced by <a href="#aee291a74c02dc725df8472084fab1377">visitCmpInst</a>.</p>

</div>
</div>

### isLoweredToCall() {#a7f1d4c503f57491de3cad8ff6d1512c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::isLoweredToCall (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call)</td>
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



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#aa0d73af9a3aaefb80f59550a218c40f2">F</a>, <a href="#a50892c7dc3861ea72c3c405ca11c9ade">getDirectOrSimplifiedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a97cfbbed8869e3582142012a071a9052">llvm::TargetLibraryInfo::getLibFunc</a>, <a href="#abef6e3800bbcc3d80dca77ce58b0eaa8">GetTLI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a54699e3f128acda6003afc11d3027f6c">llvm::TargetLibraryInfo::has</a> and <a href="#a453497ae3e6c0033f5609b932d472b11">TTI</a>.</p>


<p>Referenced by <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a>.</p>

</div>
</div>

### onAggregateSROAUse() {#a0f02814b67b7dbb3ea2d209772e9266b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{InlineCost.cpp}::CallAnalyzer::onAggregateSROAUse (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * V)</td>
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

<p>Account SROA savings for the <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> value.</p>

<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a88a00622ca09943b559df33fd3ab5368">handleSROA</a>.</p>

</div>
</div>

### onAnalysisStart() {#a562c4d99c3b86a6aed450011e796e2bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual InlineResult anonymous{InlineCost.cpp}::CallAnalyzer::onAnalysisStart ()</td>
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

<p>Called before the analysis of the callee body starts (with callsite contexts propagated).</p>


<p>It checks callsite-specific information. Return a reason analysis can't continue if that's the case, or 'true' if it may continue.</p>


<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/inlineresult/#a364fcb5fb838e7ca83b9fc379bcb4a0a">llvm::InlineResult::success</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a>.</p>

</div>
</div>

### onBlockAnalyzed() {#a37d759f043baaec8ec56bfc32e37b542}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{InlineCost.cpp}::CallAnalyzer::onBlockAnalyzed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Called after a basic block was analyzed.</p>

<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a>.</p>

</div>
</div>

### onBlockStart() {#a5b9315ae40e6ab186a2ab8f8fbebcb00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{InlineCost.cpp}::CallAnalyzer::onBlockStart (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p><a href="/web-llvm/docs/api/structs/extension">Extension</a> points for handling callsite features.</p>

<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a>.</p>

</div>
</div>

### onCallArgumentSetup() {#a088deee3b0d6b7b1e01591ab3ff642e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{InlineCost.cpp}::CallAnalyzer::onCallArgumentSetup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call)</td>
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

<p>Called to account for the cost of argument setup for the Call in the callee's body (not the callsite currently under analysis).</p>

<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a>.</p>

</div>
</div>

### onCallBaseVisitStart() {#a1f3106adceeff67611da8e779b430992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{InlineCost.cpp}::CallAnalyzer::onCallBaseVisitStart (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call)</td>
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

<p>Called when we visit a <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a>, before the analysis starts.</p>


<p>Return false to stop further processing of the instruction.</p>


<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a>.</p>

</div>
</div>

### onCallPenalty() {#a5f344ebc1a6712ea865fb247c9529370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{InlineCost.cpp}::CallAnalyzer::onCallPenalty ()</td>
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

<p>Called to account for a call.</p>

<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#ac5293e25f888cdf9f581c2e451e202e5">visitBinaryOperator</a> and <a href="#a0cc7f5478ccf8b005f1cf5110e2069ce">visitCastInst</a>.</p>

</div>
</div>

### onCaseCluster() {#abcf97fb54e3ee18ee8ca1cd3607367f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{InlineCost.cpp}::CallAnalyzer::onCaseCluster (unsigned NumCaseCluster)</td>
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

<p>Account for a case cluster of given size.</p>


<p>Return false to stop further processing of the instruction.</p>


<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onDisableLoadElimination() {#a6685b1c786d51e013f017789b21203a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{InlineCost.cpp}::CallAnalyzer::onDisableLoadElimination ()</td>
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

<p>Called the analysis engine determines load elimination won't happen.</p>

<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#ab715ffbc71efba180f5c27d28a6e0340">disableLoadElimination</a>.</p>

</div>
</div>

### onDisableSROA() {#afff99d7ead8a904458585b9575d4741e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{InlineCost.cpp}::CallAnalyzer::onDisableSROA (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * Arg)</td>
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

<p>Called if the analysis engine decides SROA cannot be done for the given alloca.</p>

<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a5496199bfbb2bef5b08262bc8c719e35">disableSROAForArg</a>.</p>

</div>
</div>

### onFinalizeSwitch() {#ab86e085c1db1d8f6c05a1f42cf6905fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{InlineCost.cpp}::CallAnalyzer::onFinalizeSwitch (unsigned JumpTableSize, unsigned NumCaseCluster, bool DefaultDestUndefined)</td>
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

<p>Called at the end of processing a switch instruction, with the given number of case clusters.</p>

<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a1233ad338a28e192e52c0f891285d2e4">visitSwitchInst</a>.</p>

</div>
</div>

### onInitializeSROAArg() {#a90d8614f92705f7e0c10a3191c1740bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{InlineCost.cpp}::CallAnalyzer::onInitializeSROAArg (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * Arg)</td>
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

<p>Start accounting potential benefits due to SROA for the given alloca.</p>

<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a>.</p>

</div>
</div>

### onInstructionAnalysisFinish() {#af7df683bd660c4ebe87fc3a1887632c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{InlineCost.cpp}::CallAnalyzer::onInstructionAnalysisFinish (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Called after an instruction was analyzed.</p>

<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a>.</p>

</div>
</div>

### onInstructionAnalysisStart() {#aa70f9c2689335ec7da9021e4b07e4186}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{InlineCost.cpp}::CallAnalyzer::onInstructionAnalysisStart (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Called before an instruction was analyzed.</p>

<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a>.</p>

</div>
</div>

### onJumpTable() {#abb402e883ef3ee6a887279fc91fe5bc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{InlineCost.cpp}::CallAnalyzer::onJumpTable (unsigned JumpTableSize)</td>
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

<p>Account for a jump table of given size.</p>


<p>Return false to stop further processing the switch instruction</p>


<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### onLoadEliminationOpportunity() {#af9f09a27eaeea42942250f54a904a313}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{InlineCost.cpp}::CallAnalyzer::onLoadEliminationOpportunity ()</td>
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

<p>Called to account for the expectation the inlining would result in a load elimination.</p>

<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#af36c571c9d12be5e0f8cbfdd19d48e40">visitLoad</a>.</p>

</div>
</div>

### onLoadRelativeIntrinsic() {#a7bf5b0a160668ce33c6979218aab047b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{InlineCost.cpp}::CallAnalyzer::onLoadRelativeIntrinsic ()</td>
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

<p>Called to account for a load relative intrinsic.</p>

<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a>.</p>

</div>
</div>

### onLoweredCall() {#adbe0f81b770474e05444f01f04ef40d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{InlineCost.cpp}::CallAnalyzer::onLoweredCall (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call, bool IsIndirectCall)</td>
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

<p>Called to account for a lowered call.</p>

<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Reference <a href="#aa0d73af9a3aaefb80f59550a218c40f2">F</a>.</p>


<p>Referenced by <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a>.</p>

</div>
</div>

### onMemAccess() {#abd3d774e9a5084bcb94c24d93b02eb75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{InlineCost.cpp}::CallAnalyzer::onMemAccess ()</td>
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

<p>Called to account for a load or store.</p>

<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#af36c571c9d12be5e0f8cbfdd19d48e40">visitLoad</a> and <a href="#a1ccb3c3fafb73d9b68db47a4ee22080e">visitStore</a>.</p>

</div>
</div>

### onMissedSimplification() {#a82b9146fe4fa59ad91ff072fa1e3e7db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{InlineCost.cpp}::CallAnalyzer::onMissedSimplification ()</td>
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

<p>Called to account for any other instruction not specifically accounted for.</p>

<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a>.</p>

</div>
</div>

### paramHasAttr() {#a22be0f88c5ce84cfb46410c66ddd79a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::paramHasAttr (<a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> * A, Attribute::AttrKind Attr)</td>
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

<p>Return true if the given argument to the function being considered for inlining has the given attribute set either at the call site or the function declaration.</p>


<p>Primarily used to inspect call site specific attributes since these can be more precise than the ones on the callee itself.</p>


<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#aaf27e0fe73330b76c1ffd00ea2116e78">CandidateCall</a>.</p>


<p>Referenced by <a href="#acd9970e2a4ba6e031330672eb089504a">isKnownNonNullInCallee</a>.</p>

</div>
</div>

### shouldStop() {#af55600dce1a5561029506eaeb04db883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{InlineCost.cpp}::CallAnalyzer::shouldStop ()</td>
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

<p>Called when we're about to start processing a basic block, and every time we are done processing an instruction.</p>


<p>Return true if there is no point in continuing the analysis (e.g. we've determined already the call site is too expensive to inline)</p>


<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a> and <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a>.</p>

</div>
</div>

### simplifyCallSite() {#a5d4c970d99f3ffebfe1e07a3be697b09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::simplifyCallSite (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call)</td>
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

<p>Try to simplify a call site.</p>


<p>Takes a concrete function and callsite and tries to actually simplify it by analyzing the arguments and call itself with instsimplify. Returns true if it has simplified the callsite to some other entity (a constant), making it free.</p>


<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20f356124998d05f7e605549cc2dda91">llvm::canConstantFoldCallTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4e3a3843bf5e85d3d55c2a252ec235bd">llvm::ConstantFoldCall</a>, <a href="#aa0d73af9a3aaefb80f59550a218c40f2">F</a>, <a href="#a50892c7dc3861ea72c3c405ca11c9ade">getDirectOrSimplifiedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a> and <a href="#aae6549033be6c24910989a2f8d4952b0">SimplifiedValues</a>.</p>


<p>Referenced by <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a>.</p>

</div>
</div>

### simplifyInstruction() {#a7df35706e1cddf8fa5565622850e1fc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::simplifyInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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

<p>Simplify <span class="doxyComputerOutput">I</span> if its operands are constants and update SimplifiedValues.</p>

<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bd5f9b3852cfb092d927ef2b04c7f6b">llvm::ConstantFoldInstOperands</a>, <a href="#aa28926a931a607351c475a9c093b0e6c">DL</a>, <a href="#a50892c7dc3861ea72c3c405ca11c9ade">getDirectOrSimplifiedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#aae6549033be6c24910989a2f8d4952b0">SimplifiedValues</a>.</p>

</div>
</div>

### simplifyIntrinsicCallIsConstant() {#a020bb3b63fcf4ec2941fd868101f8914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::simplifyIntrinsicCallIsConstant (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
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

<p>Try to simplify a call to llvm.is.constant.</p>


<p>Duplicate the argument checking from <a href="#a5d4c970d99f3ffebfe1e07a3be697b09">CallAnalyzer::simplifyCallSite</a> since we expect calls of this specific intrinsic to be infrequent.</p>


<p>FIXME: Given that we know CB's parent (F) caller (CandidateCall-&gt;<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent()</a>-&gt;<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent()</a>), we might be able to determine whether inlining F into F's caller would change how the call to llvm.is.constant would evaluate.</p>


<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="#a50892c7dc3861ea72c3c405ca11c9ade">getDirectOrSimplifiedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac3c35bd078a268a207f607d0f57dadba">llvm::CallBase::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#ad65790aa94dd4678a1d339d8304e1965">llvm::FunctionType::getReturnType</a> and <a href="#aae6549033be6c24910989a2f8d4952b0">SimplifiedValues</a>.</p>


<p>Referenced by <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a>.</p>

</div>
</div>

### simplifyIntrinsicCallObjectSize() {#acb999adbc0664256b33b94d266a8b9da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::simplifyIntrinsicCallObjectSize (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
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



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aa28926a931a607351c475a9c093b0e6c">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f635b6d5c5f74d0c2e359897a5e7498">llvm::lowerObjectSizeCall</a> and <a href="#aae6549033be6c24910989a2f8d4952b0">SimplifiedValues</a>.</p>


<p>Referenced by <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a>.</p>

</div>
</div>

### stripAndComputeInBoundsConstantOffsets() {#a0fd3732392fdbdbc5a4436c0f1262999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantInt * CallAnalyzer::stripAndComputeInBoundsConstantOffsets (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; V)</td>
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

<p>Compute the base pointer and cumulative constant offsets for V.</p>


<p>This strips all constant offsets off of V, leaving it the base pointer, and accumulates the total constant offset applied in the returned constant. It returns 0 if V is not a pointer, and returns the constant '0' if there are no constant offsets applied.</p>


<p>Definition at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#aec8a5b489575aed066c15608ea3b9b81">accumulateGEPOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aa28926a931a607351c475a9c093b0e6c">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5ab2d0b0f0b8ceec3b907184e7567197">llvm::Type::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a>.</p>

</div>
</div>

### visit() {#a91d6a0c115261ac2a9a8cae93214d141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::CallAnalyzer::visit (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *)</td>
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



<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### visit() {#aea8de7d26e5d948fdcaafbcccd644f41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::CallAnalyzer::visit (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;)</td>
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



<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### visit() {#a7869bc3bb0c3adae6d1323e233e562f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::CallAnalyzer::visit (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *)</td>
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



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### visit() {#a5be3a8f92ab5179eff41697cbd4a9cc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::CallAnalyzer::visit (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)</td>
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



<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### visit() {#a13342c73041eccefc6eaae7f16dd67ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::CallAnalyzer::visit (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *)</td>
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



<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>

</div>
</div>

### visit() {#acdd9fb7bd7964559bd3a32c508786eaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineCost.cpp}::CallAnalyzer::visit (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp;)</td>
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



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aac200dd1657275c933c8a4acc7fa0f57">visitAlloca</a>, <a href="#ac5293e25f888cdf9f581c2e451e202e5">visitBinaryOperator</a>, <a href="#a0f196ca25e9a1989af2b7f5b8e2a582f">visitBitCast</a>, <a href="#a070509ca4afed69062174feb05ef7022">visitBranchInst</a>, <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a>, <a href="#a0cc7f5478ccf8b005f1cf5110e2069ce">visitCastInst</a>, <a href="#a6880f58987f823c1969bbbbbc489c203">visitCatchReturnInst</a>, <a href="#a93a27ef49052815cbd0da76923620dff">visitCleanupReturnInst</a>, <a href="#aee291a74c02dc725df8472084fab1377">visitCmpInst</a>, <a href="#ab00dc4d624643140d27f5174991c31a3">visitExtractValue</a>, <a href="#afafedd81571bcf8dcc76d0e6688cc3e1">visitFNeg</a>, <a href="#aa99e14a7059ad7f3028d950ac47c6877">visitGetElementPtr</a>, <a href="#ad8f07bb2f659c26f6d223037859aa01e">visitIndirectBrInst</a>, <a href="#aae4a0baa949621cec86c8566b21eb879">visitInsertValue</a>, <a href="#a2dbd891d0d59986f7c113e438672df0b">visitInstruction</a>, <a href="#ad778e917372e690fc3098b635b6d615c">visitIntToPtr</a>, <a href="#af36c571c9d12be5e0f8cbfdd19d48e40">visitLoad</a>, <a href="#a0f8ae02669694e3f056dc0e083b3ebbf">visitPHI</a>, <a href="#ad6ae551b875c8a176bd745beea48ce52">visitPtrToInt</a>, <a href="#a02f0e0d29d63db2e01675e7caa6be873">visitResumeInst</a>, <a href="#aabb7899117ee8c00f2095b4bc6c1d7da">visitReturnInst</a>, <a href="#a30ffae9770fcd56cb0245c1a7a0e9a9d">visitSelectInst</a>, <a href="#a1ccb3c3fafb73d9b68db47a4ee22080e">visitStore</a>, <a href="#a1db98282963c5e756ec5ea85661d9627">visitSub</a>, <a href="#a1233ad338a28e192e52c0f891285d2e4">visitSwitchInst</a> and <a href="#a50409139e337f2e5e106830a69a63692">visitUnreachableInst</a>.</p>

</div>
</div>

### visitAlloca() {#aac200dd1657275c933c8a4acc7fa0f57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitAlloca (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; I)</td>
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



<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#ae50139d45349e59707efe9f1aa1dbb56">AllocatedSize</a>, <a href="#a1206e5afb15409ca7e5bc27ee39fad2c">disableSROA</a>, <a href="#aa28926a931a607351c475a9c093b0e6c">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#a99810ffb5ff5fca01b564419989d13f2">HasDynamicAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/inlineconstants/#a63bd3eb481440ad11d4b4905d2372f5e">llvm::InlineConstants::MaxSimplifiedDynamicAllocaToInline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6b6948bfc113c3aa2f2dc474496fd6e">llvm::SaturatingAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84836a719cdf82a516d556ae66cc8dc0">llvm::SaturatingMultiplyAdd</a>, <a href="#aae6549033be6c24910989a2f8d4952b0">SimplifiedValues</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitBinaryOperator() {#ac5293e25f888cdf9f581c2e451e202e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitBinaryOperator (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a1206e5afb15409ca7e5bc27ee39fad2c">disableSROA</a>, <a href="#aa28926a931a607351c475a9c093b0e6c">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#a50892c7dc3861ea72c3c405ca11c9ade">getDirectOrSimplifiedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aba7473bfa862dd9eadf04a6fefc6aa69">llvm::PatternMatch::m_FNeg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="#a5f344ebc1a6712ea865fb247c9529370">onCallPenalty</a>, <a href="#aae6549033be6c24910989a2f8d4952b0">SimplifiedValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa750395459fa1eb7130d6de8e3d074f6">llvm::simplifyBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272ca022565d444ccf496c0414bccefbcd9c8">llvm::TargetTransformInfo::TCC_Expensive</a> and <a href="#a453497ae3e6c0033f5609b932d472b11">TTI</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitBitCast() {#a0f196ca25e9a1989af2b7f5b8e2a582f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitBitCast (<a href="/web-llvm/docs/api/classes/llvm/bitcastinst">BitCastInst</a> &amp; I)</td>
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



<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#a735b8e924de5ae9d3a55f897a7df3d97">ConstantOffsetPtrs</a>, <a href="#a21e542376017e5ca79b65d8e7e88bb7e">getSROAArgForValueOrNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57feb935aaafd1bd4bfbb8dc56ad2129">llvm::simplifyInstruction</a> and <a href="#a3be51cd1c47211784cfe67351f08f005">SROAArgValues</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitBranchInst() {#a070509ca4afed69062174feb05ef7022}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitBranchInst (<a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> &amp; BI)</td>
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



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aebd4af5642453ce3169094f08dd3d7b8">llvm::BranchInst::getCondition</a>, <a href="#a50892c7dc3861ea72c3c405ca11c9ade">getDirectOrSimplifiedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6c09737e146b2d816c911a047ac67ba4">llvm::Instruction::getMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/branchinst/#ad56f6a9b5cd05940017c4544df48bc30">llvm::BranchInst::isUnconditional</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitCallBase() {#aec376d051e6a0ef8d3bc3d6acc5cd2f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitCallBase (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call)</td>
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



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#aa1d2fb22fed73c219030de9b2d8dfa43">AllowRecursiveCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a9600de48f592771fe50cad7071b6fcb3">ContainsNoDuplicateCall</a>, <a href="#ab715ffbc71efba180f5c27d28a6e0340">disableLoadElimination</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#a27264677757b771cd51f78d572ab6f35">ExposesReturnsTwice</a>, <a href="#aa0d73af9a3aaefb80f59550a218c40f2">F</a>, <a href="#a21e542376017e5ca79b65d8e7e88bb7e">getSROAArgForValueOrNull</a>, <a href="#a2ad9dcd777748306a37b25db1479b97a">HasUninlineableIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#aa9d5185e99bb36b8cb0cfd0128fa37d8">InitsVargArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1f2f83d3af349e89d62c6277ba668b4f">llvm::isAssumeLikeIntrinsic</a>, <a href="#a7f1d4c503f57491de3cad8ff6d1512c4">isLoweredToCall</a>, <a href="#afc765c96c7d8d3e3edd98ee1e3fcd890">IsRecursiveCall</a>, <a href="#a088deee3b0d6b7b1e01591ab3ff642e2">onCallArgumentSetup</a>, <a href="#a1f3106adceeff67611da8e779b430992">onCallBaseVisitStart</a>, <a href="#a7bf5b0a160668ce33c6979218aab047b">onLoadRelativeIntrinsic</a>, <a href="#adbe0f81b770474e05444f01f04ef40d8">onLoweredCall</a>, <a href="#aae6549033be6c24910989a2f8d4952b0">SimplifiedValues</a>, <a href="#a5d4c970d99f3ffebfe1e07a3be697b09">simplifyCallSite</a>, <a href="#a020bb3b63fcf4ec2941fd868101f8914">simplifyIntrinsicCallIsConstant</a>, <a href="#acb999adbc0664256b33b94d266a8b9da">simplifyIntrinsicCallObjectSize</a>, <a href="#a3be51cd1c47211784cfe67351f08f005">SROAArgValues</a> and <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a22ae80c2045ac48274ba65b1d91d89e7">llvm::InstVisitor&lt; CallAnalyzer, bool &gt;::visitCallBase</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitCastInst() {#a0cc7f5478ccf8b005f1cf5110e2069ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitCastInst (<a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> &amp; I)</td>
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



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#a1206e5afb15409ca7e5bc27ee39fad2c">disableSROA</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a5f344ebc1a6712ea865fb247c9529370">onCallPenalty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57feb935aaafd1bd4bfbb8dc56ad2129">llvm::simplifyInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272ca022565d444ccf496c0414bccefbcd9c8">llvm::TargetTransformInfo::TCC_Expensive</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272ca89f768b1267e3083b4eb05b4ab77e717">llvm::TargetTransformInfo::TCC_Free</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba7f80055e1969cb850739546467460ad8">llvm::TargetTransformInfo::TCK_SizeAndLatency</a> and <a href="#a453497ae3e6c0033f5609b932d472b11">TTI</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitCatchReturnInst() {#a6880f58987f823c1969bbbbbc489c203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitCatchReturnInst (<a href="/web-llvm/docs/api/classes/llvm/catchreturninst">CatchReturnInst</a> &amp; RI)</td>
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



<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitCleanupReturnInst() {#a93a27ef49052815cbd0da76923620dff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitCleanupReturnInst (<a href="/web-llvm/docs/api/classes/llvm/cleanupreturninst">CleanupReturnInst</a> &amp; RI)</td>
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



<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitCmpInst() {#aee291a74c02dc725df8472084fab1377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitCmpInst (<a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> &amp; I)</td>
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



<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a5769f1da829d6f6400b486d8e34e317f">llvm::ICmpInst::compare</a>, <a href="#a735b8e924de5ae9d3a55f897a7df3d97">ConstantOffsetPtrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#afe7d477c6022fe7123b90e3b39c58e69">llvm::ConstantInt::getBool</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="#a88a00622ca09943b559df33fd3ab5368">handleSROA</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#acd9970e2a4ba6e031330672eb089504a">isKnownNonNullInCallee</a>, <a href="#a446676eb6e2a94add6ae60b02a13335e">NumConstantPtrCmps</a>, <a href="#aae6549033be6c24910989a2f8d4952b0">SimplifiedValues</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a57feb935aaafd1bd4bfbb8dc56ad2129">llvm::simplifyInstruction</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitExtractValue() {#ab00dc4d624643140d27f5174991c31a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitExtractValue (<a href="/web-llvm/docs/api/classes/llvm/extractvalueinst">ExtractValueInst</a> &amp; I)</td>
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



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a57feb935aaafd1bd4bfbb8dc56ad2129">llvm::simplifyInstruction</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitFNeg() {#afafedd81571bcf8dcc76d0e6688cc3e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitFNeg (<a href="/web-llvm/docs/api/classes/llvm/unaryoperator">UnaryOperator</a> &amp; I)</td>
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



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a1206e5afb15409ca7e5bc27ee39fad2c">disableSROA</a>, <a href="#aa28926a931a607351c475a9c093b0e6c">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#a50892c7dc3861ea72c3c405ca11c9ade">getDirectOrSimplifiedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aae6549033be6c24910989a2f8d4952b0">SimplifiedValues</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6e06e93488a2f32aeb56f86797a78c33">llvm::simplifyFNegInst</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitGetElementPtr() {#aa99e14a7059ad7f3028d950ac47c6877}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitGetElementPtr (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> &amp; I)</td>
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



<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#aa21914d28815e593b0354ca4923e1e22">canFoldInboundsGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp/#aedc756f157d5e023dfc41a90e455274d">DisableGEPConstOperand</a>, <a href="#a5496199bfbb2bef5b08262bc8c719e35">disableSROAForArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="#a50892c7dc3861ea72c3c405ca11c9ade">getDirectOrSimplifiedValue</a>, <a href="#a21e542376017e5ca79b65d8e7e88bb7e">getSROAArgForValueOrNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a6cd79b520cf0ecc13ef7f9fe36db74fc">isGEPFree</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57feb935aaafd1bd4bfbb8dc56ad2129">llvm::simplifyInstruction</a> and <a href="#a3be51cd1c47211784cfe67351f08f005">SROAArgValues</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitIndirectBrInst() {#ad8f07bb2f659c26f6d223037859aa01e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitIndirectBrInst (<a href="/web-llvm/docs/api/classes/llvm/indirectbrinst">IndirectBrInst</a> &amp; IBI)</td>
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



<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Reference <a href="#a8570f46f65e53caf3255df66b9c86dbd">HasIndirectBr</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitInsertValue() {#aae4a0baa949621cec86c8566b21eb879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitInsertValue (<a href="/web-llvm/docs/api/classes/llvm/insertvalueinst">InsertValueInst</a> &amp; I)</td>
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



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a57feb935aaafd1bd4bfbb8dc56ad2129">llvm::simplifyInstruction</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitInstruction() {#a2dbd891d0d59986f7c113e438672df0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#a1206e5afb15409ca7e5bc27ee39fad2c">disableSROA</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272ca89f768b1267e3083b4eb05b4ab77e717">llvm::TargetTransformInfo::TCC_Free</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba7f80055e1969cb850739546467460ad8">llvm::TargetTransformInfo::TCK_SizeAndLatency</a> and <a href="#a453497ae3e6c0033f5609b932d472b11">TTI</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitIntToPtr() {#ad778e917372e690fc3098b635b6d615c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitIntToPtr (<a href="/web-llvm/docs/api/classes/llvm/inttoptrinst">IntToPtrInst</a> &amp; I)</td>
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



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#a735b8e924de5ae9d3a55f897a7df3d97">ConstantOffsetPtrs</a>, <a href="#aa28926a931a607351c475a9c093b0e6c">DL</a>, <a href="#a21e542376017e5ca79b65d8e7e88bb7e">getSROAArgForValueOrNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57feb935aaafd1bd4bfbb8dc56ad2129">llvm::simplifyInstruction</a>, <a href="#a3be51cd1c47211784cfe67351f08f005">SROAArgValues</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272ca89f768b1267e3083b4eb05b4ab77e717">llvm::TargetTransformInfo::TCC_Free</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba7f80055e1969cb850739546467460ad8">llvm::TargetTransformInfo::TCK_SizeAndLatency</a> and <a href="#a453497ae3e6c0033f5609b932d472b11">TTI</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitLoad() {#af36c571c9d12be5e0f8cbfdd19d48e40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitLoad (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> &amp; I)</td>
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



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#a93bb085a370b19e25c700d9885f3440d">EnableLoadElimination</a>, <a href="#a88a00622ca09943b559df33fd3ab5368">handleSROA</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#afe3ab2ee40110e35408b8b6700f1ca3a">LoadAddrSet</a>, <a href="#af9f09a27eaeea42942250f54a904a313">onLoadEliminationOpportunity</a> and <a href="#abd3d774e9a5084bcb94c24d93b02eb75">onMemAccess</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitPHI() {#a0f8ae02669694e3f056dc0e083b3ebbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitPHI (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> &amp; I)</td>
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



<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a735b8e924de5ae9d3a55f897a7df3d97">ConstantOffsetPtrs</a>, <a href="#a0d4623a1bd5b3ffd272898c0a9160f9f">DeadBlocks</a>, <a href="#aa28926a931a607351c475a9c093b0e6c">DL</a>, <a href="#a50892c7dc3861ea72c3c405ca11c9ade">getDirectOrSimplifiedValue</a>, <a href="#a21e542376017e5ca79b65d8e7e88bb7e">getSROAArgForValueOrNull</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0bae74199b4bcb353a5ae36e9136a368">KnownSuccessors</a>, <a href="#aae6549033be6c24910989a2f8d4952b0">SimplifiedValues</a> and <a href="#a3be51cd1c47211784cfe67351f08f005">SROAArgValues</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitPtrToInt() {#ad6ae551b875c8a176bd745beea48ce52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitPtrToInt (<a href="/web-llvm/docs/api/classes/llvm/ptrtointinst">PtrToIntInst</a> &amp; I)</td>
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



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#a735b8e924de5ae9d3a55f897a7df3d97">ConstantOffsetPtrs</a>, <a href="#aa28926a931a607351c475a9c093b0e6c">DL</a>, <a href="#a21e542376017e5ca79b65d8e7e88bb7e">getSROAArgForValueOrNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57feb935aaafd1bd4bfbb8dc56ad2129">llvm::simplifyInstruction</a>, <a href="#a3be51cd1c47211784cfe67351f08f005">SROAArgValues</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272ca89f768b1267e3083b4eb05b4ab77e717">llvm::TargetTransformInfo::TCC_Free</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba7f80055e1969cb850739546467460ad8">llvm::TargetTransformInfo::TCK_SizeAndLatency</a> and <a href="#a453497ae3e6c0033f5609b932d472b11">TTI</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitResumeInst() {#a02f0e0d29d63db2e01675e7caa6be873}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitResumeInst (<a href="/web-llvm/docs/api/classes/llvm/resumeinst">ResumeInst</a> &amp; RI)</td>
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



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitReturnInst() {#aabb7899117ee8c00f2095b4bc6c1d7da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitReturnInst (<a href="/web-llvm/docs/api/classes/llvm/returninst">ReturnInst</a> &amp; RI)</td>
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



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1ab24ce0cd392a5b0b8dedc66c25213594">llvm::Free</a> and <a href="#a3aabb7a01a2a512e3166793f6da18119">HasReturn</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitSelectInst() {#a30ffae9770fcd56cb0245c1a7a0e9a9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitSelectInst (<a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> &amp; SI)</td>
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



<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11c89e0918b007ef2cf1d6b03c4b4948">llvm::ConstantFoldSelectInstruction</a>, <a href="#a735b8e924de5ae9d3a55f897a7df3d97">ConstantOffsetPtrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#a50892c7dc3861ea72c3c405ca11c9ade">getDirectOrSimplifiedValue</a>, <a href="#a21e542376017e5ca79b65d8e7e88bb7e">getSROAArgForValueOrNull</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a662be1e66a5af621d46fa1c7a8aa1004">llvm::Constant::isAllOnesValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#ae4b6abe77abf42fb02081a6cc41a0132">llvm::Constant::isNullValue</a>, <a href="#aae6549033be6c24910989a2f8d4952b0">SimplifiedValues</a>, <a href="#a3be51cd1c47211784cfe67351f08f005">SROAArgValues</a> and <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#aeb67eff747cfcdb17ca1079aff8ed9ca">llvm::InstVisitor&lt; CallAnalyzer, bool &gt;::visitSelectInst</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitStore() {#a1ccb3c3fafb73d9b68db47a4ee22080e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitStore (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> &amp; I)</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#ab715ffbc71efba180f5c27d28a6e0340">disableLoadElimination</a>, <a href="#a88a00622ca09943b559df33fd3ab5368">handleSROA</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#abd3d774e9a5084bcb94c24d93b02eb75">onMemAccess</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitSub() {#a1db98282963c5e756ec5ea85661d9627}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitSub (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a735b8e924de5ae9d3a55f897a7df3d97">ConstantOffsetPtrs</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a554ab77949b0a16670a83ec3307501eb">llvm::ConstantExpr::getSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ae257151eedfc737f3db3fe122deade01">NumConstantPtrDiffs</a> and <a href="#aae6549033be6c24910989a2f8d4952b0">SimplifiedValues</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitSwitchInst() {#a1233ad338a28e192e52c0f891285d2e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitSwitchInst (<a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> &amp; SI)</td>
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



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#aa0d73af9a3aaefb80f59550a218c40f2">F</a>, <a href="#a9d83f245e02c2d598444b73ea9a05459">GetBFI</a>, <a href="#a50892c7dc3861ea72c3c405ca11c9ade">getDirectOrSimplifiedValue</a>, <a href="#ab86e085c1db1d8f6c05a1f42cf6905fa">onFinalizeSwitch</a>, <a href="#a8c79183f67d088e0c9cd34511c3f848d">PSI</a> and <a href="#a453497ae3e6c0033f5609b932d472b11">TTI</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

### visitUnreachableInst() {#a50409139e337f2e5e106830a69a63692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallAnalyzer::visitUnreachableInst (<a href="/web-llvm/docs/api/classes/llvm/unreachableinst">UnreachableInst</a> &amp; I)</td>
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



<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#acdd9fb7bd7964559bd3a32c508786eaa">visit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### NumAllocaArgs {#af3a1ead12644ce26ba1d064b4271df7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{InlineCost.cpp}::CallAnalyzer::NumAllocaArgs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a> and <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer/#a2c1cb0941fc8289abfffced96bb006f6">anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::print</a>.</p>

</div>
</div>

### NumConstantArgs {#a5635dea24d14ac5e3840263d19e63a6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{InlineCost.cpp}::CallAnalyzer::NumConstantArgs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a> and <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer/#a2c1cb0941fc8289abfffced96bb006f6">anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::print</a>.</p>

</div>
</div>

### NumConstantOffsetPtrArgs {#a46dd2f959cdfce95cee14bf9f5fd750b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{InlineCost.cpp}::CallAnalyzer::NumConstantOffsetPtrArgs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a> and <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer/#a2c1cb0941fc8289abfffced96bb006f6">anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::print</a>.</p>

</div>
</div>

### NumConstantPtrCmps {#a446676eb6e2a94add6ae60b02a13335e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{InlineCost.cpp}::CallAnalyzer::NumConstantPtrCmps = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer/#a2c1cb0941fc8289abfffced96bb006f6">anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::print</a> and <a href="#aee291a74c02dc725df8472084fab1377">visitCmpInst</a>.</p>

</div>
</div>

### NumConstantPtrDiffs {#ae257151eedfc737f3db3fe122deade01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{InlineCost.cpp}::CallAnalyzer::NumConstantPtrDiffs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer/#a2c1cb0941fc8289abfffced96bb006f6">anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::print</a> and <a href="#a1db98282963c5e756ec5ea85661d9627">visitSub</a>.</p>

</div>
</div>

### NumInstructionsSimplified {#ab90e06182887adcb3b5fe8cd59afb68a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{InlineCost.cpp}::CallAnalyzer::NumInstructionsSimplified = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a> and <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer/#a2c1cb0941fc8289abfffced96bb006f6">anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AllocatedSize {#ae50139d45349e59707efe9f1aa1dbb56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{InlineCost.cpp}::CallAnalyzer::AllocatedSize = 0</td>
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

<p>Number of bytes allocated statically by the callee.</p>

<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a>, <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a> and <a href="#aac200dd1657275c933c8a4acc7fa0f57">visitAlloca</a>.</p>

</div>
</div>

### AllowRecursiveCall {#aa1d2fb22fed73c219030de9b2d8dfa43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::CallAnalyzer::AllowRecursiveCall = false</td>
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

<p>Whether we allow inlining for recursive call.</p>

<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer/#a55d07c23093e29dd03456b0197d64f69">anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::InlineCostCallAnalyzer</a> and <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a>.</p>

</div>
</div>

### CandidateCall {#aaf27e0fe73330b76c1ffd00ea2116e78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallBase&amp; anonymous{InlineCost.cpp}::CallAnalyzer::CandidateCall</td>
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

<p>The candidate callsite being analyzed.</p>


<p>Please do not use this to do analysis in the caller function; we want the inline cost query to be easily cacheable. Instead, use the cover function paramHasAttr.</p>


<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a>, <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a>, <a href="#afe415d5ca807552e9ab9180b7821f04d">CallAnalyzer</a> and <a href="#a22be0f88c5ce84cfb46410c66ddd79a9">paramHasAttr</a>.</p>

</div>
</div>

### ConstantOffsetPtrs {#a735b8e924de5ae9d3a55f897a7df3d97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, std::pair&lt;Value *, APInt&gt; &gt; anonymous{InlineCost.cpp}::CallAnalyzer::ConstantOffsetPtrs</td>
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

<p>Keep track of values which map to a pointer base and constant offset.</p>

<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a>, <a href="#aa21914d28815e593b0354ca4923e1e22">canFoldInboundsGEP</a>, <a href="#a0f196ca25e9a1989af2b7f5b8e2a582f">visitBitCast</a>, <a href="#aee291a74c02dc725df8472084fab1377">visitCmpInst</a>, <a href="#ad778e917372e690fc3098b635b6d615c">visitIntToPtr</a>, <a href="#a0f8ae02669694e3f056dc0e083b3ebbf">visitPHI</a>, <a href="#ad6ae551b875c8a176bd745beea48ce52">visitPtrToInt</a>, <a href="#a30ffae9770fcd56cb0245c1a7a0e9a9d">visitSelectInst</a> and <a href="#a1db98282963c5e756ec5ea85661d9627">visitSub</a>.</p>

</div>
</div>

### ContainsNoDuplicateCall {#a9600de48f592771fe50cad7071b6fcb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::CallAnalyzer::ContainsNoDuplicateCall = false</td>
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



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer/#a2c1cb0941fc8289abfffced96bb006f6">anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::print</a> and <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a>.</p>

</div>
</div>

### DeadBlocks {#a0d4623a1bd5b3ffd272898c0a9160f9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;BasicBlock *, 16&gt; anonymous{InlineCost.cpp}::CallAnalyzer::DeadBlocks</td>
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

<p>Keep track of dead blocks due to the constant arguments.</p>

<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#af5c8e1b8ca1f8eb101829d9fe2062c4e">findDeadBlocks</a> and <a href="#a0f8ae02669694e3f056dc0e083b3ebbf">visitPHI</a>.</p>

</div>
</div>

### DL {#aa28926a931a607351c475a9c093b0e6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; anonymous{InlineCost.cpp}::CallAnalyzer::DL</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#aec8a5b489575aed066c15608ea3b9b81">accumulateGEPOffset</a>, <a href="#afe415d5ca807552e9ab9180b7821f04d">CallAnalyzer</a>, <a href="#a7df35706e1cddf8fa5565622850e1fc7">simplifyInstruction</a>, <a href="#acb999adbc0664256b33b94d266a8b9da">simplifyIntrinsicCallObjectSize</a>, <a href="#a0fd3732392fdbdbc5a4436c0f1262999">stripAndComputeInBoundsConstantOffsets</a>, <a href="#aac200dd1657275c933c8a4acc7fa0f57">visitAlloca</a>, <a href="#ac5293e25f888cdf9f581c2e451e202e5">visitBinaryOperator</a>, <a href="#afafedd81571bcf8dcc76d0e6688cc3e1">visitFNeg</a>, <a href="#ad778e917372e690fc3098b635b6d615c">visitIntToPtr</a>, <a href="#a0f8ae02669694e3f056dc0e083b3ebbf">visitPHI</a> and <a href="#ad6ae551b875c8a176bd745beea48ce52">visitPtrToInt</a>.</p>

</div>
</div>

### EnabledSROAAllocas {#a3038b138382170af89523fc9fd83dac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;AllocaInst *&gt; anonymous{InlineCost.cpp}::CallAnalyzer::EnabledSROAAllocas</td>
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

<p>Keep track of Allocas for which we believe we may get SROA optimization.</p>

<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a>, <a href="#a5496199bfbb2bef5b08262bc8c719e35">disableSROAForArg</a> and <a href="#a21e542376017e5ca79b65d8e7e88bb7e">getSROAArgForValueOrNull</a>.</p>

</div>
</div>

### EnableLoadElimination {#a93bb085a370b19e25c700d9885f3440d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::CallAnalyzer::EnableLoadElimination = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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

<p>Model the elimination of repeated loads that is expected to happen whenever we simplify away the stores that would otherwise cause them to be loads.</p>

<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#ab715ffbc71efba180f5c27d28a6e0340">disableLoadElimination</a> and <a href="#af36c571c9d12be5e0f8cbfdd19d48e40">visitLoad</a>.</p>

</div>
</div>

### ExposesReturnsTwice {#a27264677757b771cd51f78d572ab6f35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::CallAnalyzer::ExposesReturnsTwice = false</td>
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



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a> and <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a>.</p>

</div>
</div>

### F {#aa0d73af9a3aaefb80f59550a218c40f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{InlineCost.cpp}::CallAnalyzer::F</td>
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

<p>The called function.</p>

<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a>, <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a>, <a href="#afe415d5ca807552e9ab9180b7821f04d">CallAnalyzer</a>, <a href="#a7f1d4c503f57491de3cad8ff6d1512c4">isLoweredToCall</a>, <a href="#adbe0f81b770474e05444f01f04ef40d8">onLoweredCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer/#a2c1cb0941fc8289abfffced96bb006f6">anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::print</a>, <a href="#a5d4c970d99f3ffebfe1e07a3be697b09">simplifyCallSite</a>, <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a> and <a href="#a1233ad338a28e192e52c0f891285d2e4">visitSwitchInst</a>.</p>

</div>
</div>

### GetAssumptionCache {#acbdd4c0e06dc866ad2e68d57e194743e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">function_ref&lt;AssumptionCache &amp;(Function &amp;)&gt; anonymous{InlineCost.cpp}::CallAnalyzer::GetAssumptionCache</td>
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

<p>Getter for the cache of @llvm.assume intrinsics.</p>

<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a>, <a href="#afe415d5ca807552e9ab9180b7821f04d">CallAnalyzer</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer/#a55d07c23093e29dd03456b0197d64f69">anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::InlineCostCallAnalyzer</a> and <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostfeaturesanalyzer/#a43085a138ca8d8072dde11d52a003a43">anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::InlineCostFeaturesAnalyzer</a>.</p>

</div>
</div>

### GetBFI {#a9d83f245e02c2d598444b73ea9a05459}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">function_ref&lt;BlockFrequencyInfo &amp;(Function &amp;)&gt; anonymous{InlineCost.cpp}::CallAnalyzer::GetBFI</td>
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

<p>Getter for <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a>.</p>

<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#afe415d5ca807552e9ab9180b7821f04d">CallAnalyzer</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer/#a55d07c23093e29dd03456b0197d64f69">anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::InlineCostCallAnalyzer</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostfeaturesanalyzer/#a43085a138ca8d8072dde11d52a003a43">anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::InlineCostFeaturesAnalyzer</a> and <a href="#a1233ad338a28e192e52c0f891285d2e4">visitSwitchInst</a>.</p>

</div>
</div>

### GetTLI {#abef6e3800bbcc3d80dca77ce58b0eaa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">function_ref&lt;const TargetLibraryInfo &amp;(Function &amp;)&gt; anonymous{InlineCost.cpp}::CallAnalyzer::GetTLI</td>
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

<p>Getter for <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a>.</p>

<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#afe415d5ca807552e9ab9180b7821f04d">CallAnalyzer</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer/#a55d07c23093e29dd03456b0197d64f69">anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::InlineCostCallAnalyzer</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostfeaturesanalyzer/#a43085a138ca8d8072dde11d52a003a43">anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::InlineCostFeaturesAnalyzer</a> and <a href="#a7f1d4c503f57491de3cad8ff6d1512c4">isLoweredToCall</a>.</p>

</div>
</div>

### HasDynamicAlloca {#a99810ffb5ff5fca01b564419989d13f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::CallAnalyzer::HasDynamicAlloca = false</td>
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



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a> and <a href="#aac200dd1657275c933c8a4acc7fa0f57">visitAlloca</a>.</p>

</div>
</div>

### HasIndirectBr {#a8570f46f65e53caf3255df66b9c86dbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::CallAnalyzer::HasIndirectBr = false</td>
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



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a> and <a href="#ad8f07bb2f659c26f6d223037859aa01e">visitIndirectBrInst</a>.</p>

</div>
</div>

### HasReturn {#a3aabb7a01a2a512e3166793f6da18119}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::CallAnalyzer::HasReturn = false</td>
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



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#aabb7899117ee8c00f2095b4bc6c1d7da">visitReturnInst</a>.</p>

</div>
</div>

### HasUninlineableIntrinsic {#a2ad9dcd777748306a37b25db1479b97a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::CallAnalyzer::HasUninlineableIntrinsic = false</td>
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



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a> and <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a>.</p>

</div>
</div>

### InitsVargArgs {#aa9d5185e99bb36b8cb0cfd0128fa37d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::CallAnalyzer::InitsVargArgs = false</td>
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



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a> and <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a>.</p>

</div>
</div>

### IsCallerRecursive {#af69c5ad959fb12d6a57ad0e564d8fcdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::CallAnalyzer::IsCallerRecursive = false</td>
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



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a> and <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a>.</p>

</div>
</div>

### IsRecursiveCall {#afc765c96c7d8d3e3edd98ee1e3fcd890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::CallAnalyzer::IsRecursiveCall = false</td>
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



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a> and <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a>.</p>

</div>
</div>

### KnownSuccessors {#a0bae74199b4bcb353a5ae36e9136a368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;BasicBlock *, BasicBlock *&gt; anonymous{InlineCost.cpp}::CallAnalyzer::KnownSuccessors</td>
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

<p>The mapping of the blocks to their known unique successors due to the constant arguments.</p>

<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a>, <a href="#af5c8e1b8ca1f8eb101829d9fe2062c4e">findDeadBlocks</a> and <a href="#a0f8ae02669694e3f056dc0e083b3ebbf">visitPHI</a>.</p>

</div>
</div>

### LoadAddrSet {#afe3ab2ee40110e35408b8b6700f1ca3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Value *, 16&gt; anonymous{InlineCost.cpp}::CallAnalyzer::LoadAddrSet</td>
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



<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#af36c571c9d12be5e0f8cbfdd19d48e40">visitLoad</a>.</p>

</div>
</div>

### NumInstructions {#a779e8a97453bc9d5ab3a09e2be4b864d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{InlineCost.cpp}::CallAnalyzer::NumInstructions = 0</td>
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



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a> and <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer/#a2c1cb0941fc8289abfffced96bb006f6">anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::print</a>.</p>

</div>
</div>

### NumVectorInstructions {#a5b7a6043a133a09e178d84fb077a28cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{InlineCost.cpp}::CallAnalyzer::NumVectorInstructions = 0</td>
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



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a>.</p>

</div>
</div>

### ORE {#aeee19cfe3d54e41a640e29f36056ecfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter* anonymous{InlineCost.cpp}::CallAnalyzer::ORE</td>
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

<p>The <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> available for this compilation.</p>

<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#ace15c0f86fa672d5a700a5f76b8b43e9">analyzeBlock</a>, <a href="#afe415d5ca807552e9ab9180b7821f04d">CallAnalyzer</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer/#a55d07c23093e29dd03456b0197d64f69">anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::InlineCostCallAnalyzer</a> and <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostfeaturesanalyzer/#a43085a138ca8d8072dde11d52a003a43">anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::InlineCostFeaturesAnalyzer</a>.</p>

</div>
</div>

### PSI {#a8c79183f67d088e0c9cd34511c3f848d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfileSummaryInfo* anonymous{InlineCost.cpp}::CallAnalyzer::PSI</td>
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

<p>Profile summary information.</p>

<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#afe415d5ca807552e9ab9180b7821f04d">CallAnalyzer</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer/#a55d07c23093e29dd03456b0197d64f69">anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::InlineCostCallAnalyzer</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostfeaturesanalyzer/#a43085a138ca8d8072dde11d52a003a43">anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::InlineCostFeaturesAnalyzer</a> and <a href="#a1233ad338a28e192e52c0f891285d2e4">visitSwitchInst</a>.</p>

</div>
</div>

### SimplifiedValues {#aae6549033be6c24910989a2f8d4952b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, Constant *&gt; anonymous{InlineCost.cpp}::CallAnalyzer::SimplifiedValues</td>
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

<p>While we walk the potentially-inlined instructions, we build up and maintain a mapping of simplified values specific to this callsite.</p>


<p>The idea is to propagate any special information we have about arguments to this call through the inlinable section of the function, and account for likely simplifications post-inlining. The most important aspect we track is CFG altering simplifications – when we prove a basic block dead, that can cause dramatic shifts in the cost of inlining a function.</p>


<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a>, <a href="#a50892c7dc3861ea72c3c405ca11c9ade">getDirectOrSimplifiedValue</a>, <a href="#acc1eb7f69eb6521e8d6b95e56f9507e0">getSimplifiedValue</a>, <a href="#a6cd79b520cf0ecc13ef7f9fe36db74fc">isGEPFree</a>, <a href="#a5d4c970d99f3ffebfe1e07a3be697b09">simplifyCallSite</a>, <a href="#a7df35706e1cddf8fa5565622850e1fc7">simplifyInstruction</a>, <a href="#a020bb3b63fcf4ec2941fd868101f8914">simplifyIntrinsicCallIsConstant</a>, <a href="#acb999adbc0664256b33b94d266a8b9da">simplifyIntrinsicCallObjectSize</a>, <a href="#aac200dd1657275c933c8a4acc7fa0f57">visitAlloca</a>, <a href="#ac5293e25f888cdf9f581c2e451e202e5">visitBinaryOperator</a>, <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a>, <a href="#aee291a74c02dc725df8472084fab1377">visitCmpInst</a>, <a href="#afafedd81571bcf8dcc76d0e6688cc3e1">visitFNeg</a>, <a href="#a0f8ae02669694e3f056dc0e083b3ebbf">visitPHI</a>, <a href="#a30ffae9770fcd56cb0245c1a7a0e9a9d">visitSelectInst</a> and <a href="#a1db98282963c5e756ec5ea85661d9627">visitSub</a>.</p>

</div>
</div>

### SROAArgValues {#a3be51cd1c47211784cfe67351f08f005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, AllocaInst *&gt; anonymous{InlineCost.cpp}::CallAnalyzer::SROAArgValues</td>
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

<p>Keep track of the values which map back (through function arguments) to allocas on the caller stack which could be simplified through SROA.</p>

<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a75514cc4632af88b58a31912c8bd9ecc">analyze</a>, <a href="#a21e542376017e5ca79b65d8e7e88bb7e">getSROAArgForValueOrNull</a>, <a href="#a7b78c476557e705479c1441daad05710">isAllocaDerivedArg</a>, <a href="#a0f196ca25e9a1989af2b7f5b8e2a582f">visitBitCast</a>, <a href="#aec376d051e6a0ef8d3bc3d6acc5cd2f7">visitCallBase</a>, <a href="#aa99e14a7059ad7f3028d950ac47c6877">visitGetElementPtr</a>, <a href="#ad778e917372e690fc3098b635b6d615c">visitIntToPtr</a>, <a href="#a0f8ae02669694e3f056dc0e083b3ebbf">visitPHI</a>, <a href="#ad6ae551b875c8a176bd745beea48ce52">visitPtrToInt</a> and <a href="#a30ffae9770fcd56cb0245c1a7a0e9a9d">visitSelectInst</a>.</p>

</div>
</div>

### TTI {#a453497ae3e6c0033f5609b932d472b11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetTransformInfo&amp; anonymous{InlineCost.cpp}::CallAnalyzer::TTI</td>
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

<p>The <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> available for this compilation.</p>

<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#afe415d5ca807552e9ab9180b7821f04d">CallAnalyzer</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer/#a55d07c23093e29dd03456b0197d64f69">anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::InlineCostCallAnalyzer</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostfeaturesanalyzer/#a43085a138ca8d8072dde11d52a003a43">anonymous{InlineCost.cpp}::InlineCostFeaturesAnalyzer::InlineCostFeaturesAnalyzer</a>, <a href="#a6cd79b520cf0ecc13ef7f9fe36db74fc">isGEPFree</a>, <a href="#a7f1d4c503f57491de3cad8ff6d1512c4">isLoweredToCall</a>, <a href="#ac5293e25f888cdf9f581c2e451e202e5">visitBinaryOperator</a>, <a href="#a0cc7f5478ccf8b005f1cf5110e2069ce">visitCastInst</a>, <a href="#a2dbd891d0d59986f7c113e438672df0b">visitInstruction</a>, <a href="#ad778e917372e690fc3098b635b6d615c">visitIntToPtr</a>, <a href="#ad6ae551b875c8a176bd745beea48ce52">visitPtrToInt</a> and <a href="#a1233ad338a28e192e52c0f891285d2e4">visitSwitchInst</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
