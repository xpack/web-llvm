---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `LoopVectorize.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">llvm/Transforms/Vectorize/LoopVectorize.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplananalysis-h">VPlanAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-h">VPlanHCFGBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanpatternmatch-h">VPlanPatternMatch.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanverifier-h">VPlanVerifier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemapinfo-h">llvm/ADT/DenseMapInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">llvm/ADT/Hashing.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">llvm/ADT/MapVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/typeswitch-h">llvm/ADT/TypeSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/iterator-range-h">llvm/ADT/iterator_range.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">llvm/Analysis/AssumptionCache.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/basicaliasanalysis-h">llvm/Analysis/BasicAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">llvm/Analysis/BlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfg-h">llvm/Analysis/CFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">llvm/Analysis/CodeMetrics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">llvm/Analysis/DemandedBits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/globalsmodref-h">llvm/Analysis/GlobalsModRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">llvm/Analysis/LoopAccessAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">llvm/Analysis/LoopAnalysisManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopiterator-h">llvm/Analysis/LoopIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">llvm/Analysis/OptimizationRemarkEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">llvm/Analysis/ProfileSummaryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">llvm/Analysis/ScalarEvolution.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">llvm/Analysis/ScalarEvolutionExpressions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">llvm/Analysis/VectorUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cfg-h">llvm/IR/CFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">llvm/IR/DebugInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">llvm/IR/DebugLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">llvm/IR/MDBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">llvm/IR/Operator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/profdatautils-h">llvm/IR/ProfDataUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">llvm/IR/Use.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">llvm/IR/User.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">llvm/IR/Verifier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">llvm/Support/InstructionCost.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/nativeformatting-h">llvm/Support/NativeFormatting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">llvm/Transforms/Utils/BasicBlockUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/injecttlimappings-h">llvm/Transforms/Utils/InjectTLIMappings.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/local-h">llvm/Transforms/Utils/Local.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopsimplify-h">llvm/Transforms/Utils/LoopSimplify.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/looputils-h">llvm/Transforms/Utils/LoopUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">llvm/Transforms/Utils/LoopVersioning.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">llvm/Transforms/Utils/ScalarEvolutionExpander.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sizeopts-h">llvm/Transforms/Utils/SizeOpts.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorizationlegality-h">llvm/Transforms/Vectorize/LoopVectorizationLegality.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;functional&gt;
#include &lt;iterator&gt;
#include &lt;limits&gt;
#include &lt;memory&gt;
#include &lt;string&gt;
#include &lt;tuple&gt;
#include &lt;utility&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/preferpredicatety">PreferPredicateTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-loopvectorize-cpp-">anonymous{LoopVectorize.cpp}</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/epilogueloopvectorizationinfo">EpilogueLoopVectorizationInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encapsulate information regarding vectorization of a loop and its epilogue. <a href="/web-llvm/docs/api/structs/llvm/epilogueloopvectorizationinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel">LoopVectorizationCostModel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel">LoopVectorizationCostModel</a> - estimates the expected speedups due to vectorization. <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loopvectorizationcostmodel/registerusage">RegisterUsage</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A struct that represents some properties of the register usage of a loop. <a href="/web-llvm/docs/api/structs/llvm/loopvectorizationcostmodel/registerusage/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loopvectorizationcostmodel/callwideningdecision">CallWideningDecision</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks">GeneratedRTChecks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper struct to manage generating runtime checks for vectorization. <a href="/web-llvm/docs/api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-loopvectorize-cpp-/csedensemapinfo">CSEDenseMapInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8318a653242df10df04853e090cc21f">STATISTIC</a> (LoopsVectorized, "Number of loops vectorized")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefd85537796668463b24d5ab5b225407">STATISTIC</a> (LoopsAnalyzed, "Number of loops analyzed for vectorization")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a683da38156d0f59a8d6a0cc83dc7ae14">STATISTIC</a> (LoopsEpilogueVectorized, "Number of epilogues vectorized")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa407c2e7d895ed29af8cc68563c03065">hasIrregularType</a> (Type *Ty, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper function that returns true if the given type is irregular. <a href="#aa407c2e7d895ed29af8cc68563c03065">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84375e6536d9214c7895013078055aff">getSmallBestKnownTC</a> (PredicatedScalarEvolution &amp;PSE, Loop *L, bool CanUseConstantMax=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns "best known" trip count for the specified loop <span class="doxyComputerOutput">L</span> as defined by the following procedure: 1) Returns exact trip count if it is known. <a href="#a84375e6536d9214c7895013078055aff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29c708de8e758ac420523c94c797b501">getDebugLocFromInstOrOperands</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look for a meaningful debug location on the instruction or its operands. <a href="#a29c708de8e758ac420523c94c797b501">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a861c376095fff2ee736b0a743cc44e">debugVectorizationMessage</a> (const StringRef Prefix, const StringRef DebugMsg, Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a <span class="doxyComputerOutput">DebugMsg</span> about vectorization to the debug output stream. <a href="#a1a861c376095fff2ee736b0a743cc44e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis">OptimizationRemarkAnalysis</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afec6951f3043e25ada2b61437bd60725">createLVAnalysis</a> (const char *PassName, StringRef RemarkName, Loop *TheLoop, Instruction *I, DebugLoc DL={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an analysis remark that explains why vectorization failed. <a href="#afec6951f3043e25ada2b61437bd60725">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae88a50a9a37f9a745939e3e726837e6">useActiveLaneMask</a> (TailFoldingStyle Style)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e445204e48d57b1e23e55869146b7ce">useActiveLaneMaskForControlFlow</a> (TailFoldingStyle Style)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a806ec23d6f44b02ad8cf3b1e61c05495">isExplicitVecOuterLoop</a> (Loop *OuterLp, OptimizationRemarkEmitter *ORE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00315ff11c9068aab97e5780bdfa5eef">collectSupportedLoops</a> (Loop &amp;L, LoopInfo *LI, OptimizationRemarkEmitter *ORE, SmallVectorImpl&lt; Loop * &gt; &amp;V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23f5821d9ac264ae25dd087747e2c181">emitTransformedIndex</a> (IRBuilderBase &amp;B, Value *Index, Value *StartValue, Value *Step, InductionDescriptor::InductionKind InductionKind, const BinaryOperator *InductionBinOp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the transformed value of Index at offset StartValue using step StepValue. <a href="#a23f5821d9ac264ae25dd087747e2c181">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a604c96744d2e46447f11e2d3aab9a9b2">getMaxVScale</a> (const Function &amp;F, const TargetTransformInfo &amp;TTI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7edde995b7986f98c3f59788b960eba">isIndvarOverflowCheckKnownFalse</a> (const LoopVectorizationCostModel *Cost, ElementCount VF, std::optional&lt; unsigned &gt; UF=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the given VF and UF and maximum trip count computed for the loop, return whether the induction variable might overflow in the vectorized loop. <a href="#ab7edde995b7986f98c3f59788b960eba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf8d8fb6f39b9c0cf21d55b7229d35e2">useMaskedInterleavedAccesses</a> (const TargetTransformInfo &amp;TTI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a8743a69fac5e7fa9c2b02604b2cf2f">replaceVPBBWithIRVPBB</a> (VPBasicBlock *VPBB, BasicBlock *IRBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace <span class="doxyComputerOutput">VPBB</span> with a <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> wrapping <span class="doxyComputerOutput">IRBB</span>. <a href="#a3a8743a69fac5e7fa9c2b02604b2cf2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8d4cfce02b245d616238ce8eed74718">getExpandedStep</a> (const InductionDescriptor &amp;ID, const SCEV2ValueTy &amp;ExpandedSCEVs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the expanded step for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span> using <span class="doxyComputerOutput">ExpandedSCEVs</span> to look up <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expansion results. <a href="#aa8d4cfce02b245d616238ce8eed74718">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ababcaf6e2e00fc3fc8791ea2c3acbda5">addFullyUnrolledInstructionsToIgnore</a> (Loop *L, const LoopVectorizationLegality::InductionList &amp;IL, SmallPtrSetImpl&lt; Instruction * &gt; &amp;InstsToIgnore)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Knowing that loop <span class="doxyComputerOutput">L</span> executes a single vector iteration, add instructions that will get simplified and thus should not have any cost to <span class="doxyComputerOutput">InstsToIgnore</span>. <a href="#ababcaf6e2e00fc3fc8791ea2c3acbda5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc13ee8b8985399901ac09b51822e21a">cse</a> (BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform cse of induction variable instructions. <a href="#acc13ee8b8985399901ac09b51822e21a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83114915b4f7fec94a20efa3834a8250">maybeVectorizeType</a> (Type *Elt, ElementCount VF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e108201f94f2fe89865e7868390bbf6">getVScaleForTuning</a> (const Loop *L, const TargetTransformInfo &amp;TTI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience function that returns the value of vscale_range iff vscale_range.min == vscale_range.max or otherwise returns the value returned by the corresponding <a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068">TTI</a> method. <a href="#a4e108201f94f2fe89865e7868390bbf6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3df41ae1ed3978e3b825bc4dd50ae8d">getEstimatedRuntimeVF</a> (const Loop *L, const TargetTransformInfo &amp;TTI, ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function attempts to return a value that represents the vectorization factor at runtime. <a href="#ab3df41ae1ed3978e3b825bc4dd50ae8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af378bb1e037306d9cfd4bb0b49ba55f9">willGenerateVectors</a> (VPlan &amp;Plan, ElementCount VF, const TargetTransformInfo &amp;TTI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if any recipe of <span class="doxyComputerOutput">Plan</span> will generate a vector value, which will be assigned a vector register. <a href="#af378bb1e037306d9cfd4bb0b49ba55f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad27a81251d238dbfdc4d0253a64d6267">getAddressAccessSCEV</a> (Value *Ptr, LoopVectorizationLegality *Legal, PredicatedScalarEvolution &amp;PSE, const Loop *TheLoop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets Address Access <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> after verifying that the access pattern is loop invariant except the induction variable dependence. <a href="#ad27a81251d238dbfdc4d0253a64d6267">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b91e092434338369b2e1995b87f0c5b">determineVPlanVF</a> (const TargetTransformInfo &amp;TTI, LoopVectorizationCostModel &amp;CM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a696283c30308704d020a9d86065aa3ae">planContainsAdditionalSimplifications</a> (VPlan &amp;Plan, VPCostContext &amp;CostCtx, Loop *TheLoop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the original loop \ TheLoop contains any instructions that do not have corresponding recipes in <span class="doxyComputerOutput">Plan</span> and are not marked to be ignored in <span class="doxyComputerOutput">CostCtx</span>. <a href="#a696283c30308704d020a9d86065aa3ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a033bb363914fbd3c2cd990330959036c">addRuntimeUnrollDisableMetaData</a> (Loop *L)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90ad8ccd396152c749068f986f2b751a">fixReductionScalarResumeWhenVectorizingEpilog</a> (VPRecipeBase *R, VPTransformState &amp;State, BasicBlock *LoopMiddleBlock, BasicBlock *BypassBlock)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe">VPWidenIntOrFpInductionRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9336eb7b4fbcee561dbb8c52d9eabe64">createWidenInductionRecipes</a> (PHINode *Phi, Instruction *PhiOrTrunc, VPValue *Start, const InductionDescriptor &amp;IndDesc, VPlan &amp;Plan, ScalarEvolution &amp;SE, Loop &amp;OrigLoop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a VPWidenIntOrFpInductionRecpipe for <span class="doxyComputerOutput">Phi</span>. <a href="#a9336eb7b4fbcee561dbb8c52d9eabe64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d2a943e39c98ccce6fd53e8df9c5c2b">addCanonicalIVRecipes</a> (VPlan &amp;Plan, Type *IdxTy, bool HasNUW, DebugLoc DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20c2e870e2c105fbf0945df09a9a5c4d">addResumePhiRecipeForInduction</a> (VPWidenInductionRecipe *WideIV, VPBuilder &amp;VectorPHBuilder, VPBuilder &amp;ScalarPHBuilder, VPTypeAnalysis &amp;TypeInfo, VPValue *VectorTC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create and return a ResumePhi for <span class="doxyComputerOutput">WideIV</span>, unless it is truncated. <a href="#a20c2e870e2c105fbf0945df09a9a5c4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02106664ead4e0c4e755457dbac7f7b3">addScalarResumePhis</a> (VPRecipeBuilder &amp;Builder, VPlan &amp;Plan, DenseMap&lt; VPValue *, VPValue * &gt; &amp;IVEndValues)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create resume phis in the scalar preheader for first-order recurrences, reductions and inductions, and update the VPIRInstructions wrapping the original phis in the scalar header. <a href="#a02106664ead4e0c4e755457dbac7f7b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction">VPIRInstruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a435b95efad7ea03299bd527b55b4708a">collectUsersInExitBlocks</a> (Loop *OrigLoop, VPRecipeBuilder &amp;Builder, VPlan &amp;Plan)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af34d746d08a380c672cae45176f9df87">addUsersInExitBlocks</a> (VPlan &amp;Plan, const SetVector&lt; VPIRInstruction * &gt; &amp;ExitUsersToFix)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a453563e4ed7e249a7f3e92b98b9052df">addExitUsersForFirstOrderRecurrences</a> (VPlan &amp;Plan, SetVector&lt; VPIRInstruction * &gt; &amp;ExitUsersToFix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle users in the exit block for first order reductions in the original exit block. <a href="#a453563e4ed7e249a7f3e92b98b9052df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#ab5d4f35a197e7b0f2320bdbbf518bd9d">ScalarEpilogueLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cde912cc23c18f493e4e5005c85748b">getScalarEpilogueLowering</a> (Function *F, Loop *L, LoopVectorizeHints &amp;Hints, ProfileSummaryInfo *PSI, BlockFrequencyInfo *BFI, TargetTransformInfo *TTI, TargetLibraryInfo *TLI, LoopVectorizationLegality &amp;LVL, InterleavedAccessInfo *IAI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeb41c907ebde15846bc643325909f95">processLoopInVPlanNativePath</a> (Loop *L, PredicatedScalarEvolution &amp;PSE, LoopInfo *LI, DominatorTree *DT, LoopVectorizationLegality *LVL, TargetTransformInfo *TTI, TargetLibraryInfo *TLI, DemandedBits *DB, AssumptionCache *AC, OptimizationRemarkEmitter *ORE, BlockFrequencyInfo *BFI, ProfileSummaryInfo *PSI, LoopVectorizeHints &amp;Hints, LoopVectorizationRequirements &amp;Requirements)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1fba45879c49d4839b11ec30afd7532">checkMixedPrecision</a> (Loop *L, OptimizationRemarkEmitter *ORE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a362f793f3254317c698e3560548788a5">areRuntimeChecksProfitable</a> (GeneratedRTChecks &amp;Checks, VectorizationFactor &amp;VF, Loop *L, const TargetTransformInfo &amp;TTI, PredicatedScalarEvolution &amp;PSE, ScalarEpilogueLowering SEL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13368acf4fbb5816c3d82099b11519b1">preparePlanForMainVectorLoop</a> (VPlan &amp;MainPlan, VPlan &amp;EpiPlan)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prepare <span class="doxyComputerOutput">MainPlan</span> for vectorizing the main vector loop during epilogue vectorization. <a href="#a13368acf4fbb5816c3d82099b11519b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae23f7e6fc37b0f1bb756f938023512c">preparePlanForEpilogueVectorLoop</a> (VPlan &amp;Plan, Loop *L, const SCEV2ValueTy &amp;ExpandedSCEVs, const EpilogueLoopVectorizationInfo &amp;EPI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prepare <span class="doxyComputerOutput">Plan</span> for vectorizing the epilogue loop. <a href="#aae23f7e6fc37b0f1bb756f938023512c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bf55ccbbeedcfb8cd2a1bd62c0ad91a">LLVMLoopVectorizeFollowupAll</a>[] = "llvm.loop.vectorize.followup_all"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99050b417d193e1cc1117e5bbd4bfbce">LLVMLoopVectorizeFollowupVectorized</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadedae9de069f3bcef6fa7a90ce4a630">LLVMLoopVectorizeFollowupEpilogue</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eba8b6f7c3e69bf4d4efd92cd74b5a6">VerboseDebug</a>[] = <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> "-verbose"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bb0da83afffaf803b396b1d055ba5e0">EnableEpilogueVectorization</a>("enable-epilogue-vectorization", cl::init(true), cl::Hidden, cl::desc("Enable vectorization of epilogue loops."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01340df86c9d26b281ff1ab9288c28ce">EpilogueVectorizationForceVF</a>("epilogue-vectorization-force-VF", cl::init(1), cl::Hidden, cl::desc("When epilogue vectorization is enabled, and a value greater than " "1 is specified, forces the given VF for all applicable epilogue " "loops."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01070590fdc156c181654c2db7b9ddcc">EpilogueVectorizationMinVF</a>("epilogue-vectorization-minimum-VF", cl::Hidden, cl::desc("Only loops with vectorization factor equal to or larger than " "the specified value are considered for epilogue vectorization."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15320a2d7ced6e62766048ae7b6f8b13">TinyTripCountVectorThreshold</a>("vectorizer-min-trip-count", cl::init(16), cl::Hidden, cl::desc("Loops with a constant trip count that is smaller than this " "value are vectorized only if no scalar iteration overheads " "are incurred."))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loops with a known constant trip count below this number are vectorized only if no scalar iteration overheads are incurred. <a href="#a15320a2d7ced6e62766048ae7b6f8b13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1293f02da7fffb33096a44f1b1768b3f">VectorizeMemoryCheckThreshold</a>("vectorize-memory-check-threshold", cl::init(128), cl::Hidden, cl::desc("The maximum allowed number of runtime memory checks"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/preferpredicatety/#ab00d54c73f16daa1e1f9f65f77db0cda">PreferPredicateTy::Option</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe3c68238712d04bbe3a70f3a8f483f5">PreferPredicateOverEpilogue</a>("prefer-predicate-over-epilogue", cl::init(PreferPredicateTy::ScalarEpilogue), cl::Hidden, cl::desc("Tail-folding and predication preferences over creating a scalar " "epilogue loop."), cl::values(clEnumValN(PreferPredicateTy::ScalarEpilogue, "scalar-epilogue", "Don't tail-predicate loops, create scalar epilogue"), clEnumValN(PreferPredicateTy::PredicateElseScalarEpilogue, "predicate-else-scalar-epilogue", "prefer tail-folding, create scalar epilogue if tail " "folding fails."), clEnumValN(PreferPredicateTy::PredicateOrDontVectorize, "predicate-dont-vectorize", "prefers tail-folding, don't attempt vectorization if " "tail-folding fails.")))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdd">TailFoldingStyle</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8959791a22c7d3cfb4136777fd244535">ForceTailFoldingStyle</a>("force-tail-folding-style", cl::desc("Force the tail folding style"), cl::init(TailFoldingStyle::None), cl::values(clEnumValN(TailFoldingStyle::None, "none", "Disable tail folding"), clEnumValN(TailFoldingStyle::Data, "data", "Create lane mask for data only, using active.lane.mask intrinsic"), clEnumValN(TailFoldingStyle::DataWithoutLaneMask, "data-without-lane-mask", "Create lane mask with compare/stepvector"), clEnumValN(TailFoldingStyle::DataAndControlFlow, "data-and-control", "Create lane mask using active.lane.mask intrinsic, and use " "it for both data and control flow"), clEnumValN(TailFoldingStyle::DataAndControlFlowWithoutRuntimeCheck, "data-and-control-without-rt-check", "Similar to data-and-control, but remove the runtime check"), clEnumValN(TailFoldingStyle::DataWithEVL, "data-with-evl", "Use predicated EVL instructions for tail folding. If EVL " "is unsupported, fallback to data-without-lane-mask.")))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe9b34c22ec9e2cc84d61d437f82936d">MaximizeBandwidth</a>("vectorizer-maximize-bandwidth", cl::init(false), cl::Hidden, cl::desc("Maximize bandwidth when selecting vectorization factor which " "will be determined by the smallest type in loop."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3af17aa5bce5ef8c3aa82faeacfc456">EnableInterleavedMemAccesses</a>("enable-interleaved-mem-accesses", cl::init(false), cl::Hidden, cl::desc("Enable vectorization on interleaved memory accesses in a loop"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac68ad295befb7187ae293cc0faaa3ac3">EnableMaskedInterleavedMemAccesses</a>("enable-masked-interleaved-mem-accesses", cl::init(false), cl::Hidden, cl::desc("Enable vectorization on masked interleaved memory accesses in a loop"))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An interleave-group may need masking if it resides in a block that needs predication, or in order to mask away gaps. <a href="#ac68ad295befb7187ae293cc0faaa3ac3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62baadf3a5bf03eddf58bf048724acb1">ForceTargetNumScalarRegs</a>("force-target-num-scalar-regs", cl::init(0), cl::Hidden, cl::desc("A flag that overrides the target's number of scalar registers."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d952aa72676eecd8065aa2c29ea458c">ForceTargetNumVectorRegs</a>("force-target-num-vector-regs", cl::init(0), cl::Hidden, cl::desc("A flag that overrides the target's number of vector registers."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee1082071c43958a6ef5e6e9f665ae4a">ForceTargetMaxScalarInterleaveFactor</a>("force-target-max-scalar-interleave", cl::init(0), cl::Hidden, cl::desc("A flag that overrides the target's max interleave factor for " "scalar loops."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade5aad46b91dc51c831acf1e69ee9863">ForceTargetMaxVectorInterleaveFactor</a>("force-target-max-vector-interleave", cl::init(0), cl::Hidden, cl::desc("A flag that overrides the target's max interleave factor for " "vectorized loops."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eae6074e6a1bb62e365ef65f3e26196">ForceTargetInstructionCost</a>("force-target-instruction-cost", cl::init(0), cl::Hidden, cl::desc("A flag that overrides the target's expected cost for " "an instruction to a single constant value. Mostly " "useful for getting consistent testing."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48035e22b43c905a2961c90e5470b2f0">ForceTargetSupportsScalableVectors</a>("force-target-supports-scalable-vectors", cl::init(false), cl::Hidden, cl::desc("Pretend that scalable vectors are supported, even if the target does " "not support them. This flag should only be used for testing."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71899f6c73fcc8e2fc977dadc1fb1520">SmallLoopCost</a>("small-loop-cost", cl::init(20), cl::Hidden, cl::desc("The cost of a loop that is considered 'small' by the interleaver."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5a50c0ac98e2ed63da85783ca102cf8">LoopVectorizeWithBlockFrequency</a>("loop-vectorize-with-block-frequency", cl::init(true), cl::Hidden, cl::desc("Enable the use of the block frequency analysis to access PGO " "heuristics minimizing code growth in cold regions and being more " "aggressive in hot regions."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99a396adb2c0f9fb93b7ff8ea8b2e2ef">EnableLoadStoreRuntimeInterleave</a>("enable-loadstore-runtime-interleave", cl::init(true), cl::Hidden, cl::desc("Enable runtime interleaving until load/store ports are saturated"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae11c08aa35785a118bda788836cab423">NumberOfStoresToPredicate</a>("vectorize-num-stores-pred", cl::init(1), cl::Hidden, cl::desc("Max number of stores to be predicated behind an if."))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of stores in a loop that are allowed to need predication. <a href="#ae11c08aa35785a118bda788836cab423">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8122656ed2c776067b43d9ae34ccecb6">EnableIndVarRegisterHeur</a>("enable-ind-var-reg-heur", cl::init(true), cl::Hidden, cl::desc("Count the induction variable only once when interleaving"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b67aba558e56b48dbb2891b6e5fe5b8">EnableCondStoresVectorization</a>("enable-cond-stores-vec", cl::init(true), cl::Hidden, cl::desc("Enable if predication of stores during vectorization."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae75965df4671fa34c6ffc5a6e404843a">MaxNestedScalarReductionIC</a>("max-nested-scalar-reduction-interleave", cl::init(2), cl::Hidden, cl::desc("The maximum interleave count to use when interleaving a scalar " "reduction in a nested loop."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96ef6bd4742763bf1b85aaf1a4150620">PreferInLoopReductions</a>("prefer-inloop-reductions", cl::init(false), cl::Hidden, cl::desc("Prefer in-loop vector reductions, " "overriding the targets preference."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb0b374f69dc6867357f0aa5e93ab33d">ForceOrderedReductions</a>("force-ordered-reductions", cl::init(false), cl::Hidden, cl::desc("Enable the vectorisation of loops with in-order (strict) " "FP reductions"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a927ef1cfd7c981c5b9b9e8c67b1d13c3">PreferPredicatedReductionSelect</a>("prefer-predicated-reduction-select", cl::init(false), cl::Hidden, cl::desc("Prefer predicating a reduction operation over an after loop select."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f30855a6efcd4a12875deb88880b510">VPlanBuildStressTest</a>("vplan-build-stress-test", cl::init(false), cl::Hidden, cl::desc("Build VPlan for every supported loop nest in the function and bail " "out right after the build (stress test the VPlan H-CFG construction " "in the VPlan-native vectorization path)."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44">cl::boolOrDefault</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad69cf8bf5c6b79c5642327ecb6be38cd">ForceSafeDivisor</a>("force-widen-divrem-via-safe-divisor", cl::Hidden, cl::desc("Override cost based safe divisor widening for div/rem instructions"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a639c83322f3d5f0e24e9bde998a516fd">UseWiderVFIfCallVariantsPresent</a>("vectorizer-maximize-bandwidth-for-vector-calls", cl::init(true), cl::Hidden, cl::desc("Try wider VFs if they enable the use of vector variants"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7af1b4bf03205c80dcba0a6324c4f21">EnableEarlyExitVectorization</a>("enable-early-exit-vectorization", cl::init(false), cl::Hidden, cl::desc("Enable vectorization of early exit loops with uncountable exits."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a968a5c2971ffa9e8ef81ff86eebaf514">SCEVCheckBypassWeights</a>[] = {1, 127}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a502070b20fa467fb54ba49d6736cf2d3">MemCheckBypassWeights</a>[] = {1, 127}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a629884e9a99a9f49106db9e5e6252fcb">MinItersBypassWeights</a>[] = {1, 127}</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eff4a8bccb143ae91e197e6a59d4692">LV_NAME</a>&nbsp;&nbsp;&nbsp;"loop-vectorize"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp/#a0eff4a8bccb143ae91e197e6a59d4692">LV_NAME</a></td>
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

### addCanonicalIVRecipes() {#a4d2a943e39c98ccce6fd53e8df9c5c2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addCanonicalIVRecipes (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * IdxTy, bool HasNUW, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 8930 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpuser/#af4a3b471097ab37b1672a0d88869ea51">llvm::VPUser::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2a49dcace93798ddd457a9d4e584bbc9a2">llvm::VPInstruction::BranchOnCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#accbbcc76f9eb947b3804ad96beb2bbd2">llvm::VPBuilder::createNaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#ab3b191f35221f351f77883447fef4019">llvm::VPBuilder::createOverflowingOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a28da654f916bf44da5513b6f1788835c">llvm::VPBlockBase::getExitingBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ac38d49d70b5f78779e83abdf4dcb4be0">llvm::VPlan::getOrAddLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a233848f0bf7aef1aca22e6172e5d900d">llvm::VPlan::getVectorTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a2d53ff30dd2a706e91c30d4f50982e3d">llvm::VPlan::getVFxUF</a> and <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#adfdd504b078cce3b90e7c5cf1f5164db">llvm::VPBasicBlock::insert</a>.</p>

</div>
</div>

### addExitUsersForFirstOrderRecurrences() {#a453563e4ed7e249a7f3e92b98b9052df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addExitUsersForFirstOrderRecurrences (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction">VPIRInstruction</a> * &gt; &amp; ExitUsersToFix)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle users in the exit block for first order reductions in the original exit block.</p>


<p>The penultimate value of recurrences is fed to their LCSSA phi users in the original exit block using the <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction">VPIRInstruction</a> wrapping to the LCSSA phi.</p>


<p>Definition at line 9112 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#accbbcc76f9eb947b3804ad96beb2bbd2">llvm::VPBuilder::createNaryOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2ad6b029191d02f4c7a7dda59e44c88ab6">llvm::VPInstruction::ExtractFromEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad9053d6ed9627166c144b8895d1c1010">llvm::VPlan::getCanonicalIV</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a995b2a034ffc26dcd2f3a679f9d2feea">llvm::VPlan::getMiddleBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ac38d49d70b5f78779e83abdf4dcb4be0">llvm::VPlan::getOrAddLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad5f29ccf71b0494fc179323427eb1e11">llvm::VPlan::getScalarPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#ac8744d8abf2a7ed185cc14f0a305cf8e">llvm::VPCanonicalIVPHIRecipe::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aebc0e1a3379ed4fd614889e24b8ea48c">llvm::VPBlockBase::getSingleSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a668c6f14a461ccf0ee11c9c7a076a901">llvm::VPBasicBlock::phis</a> and <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a19c3591dc1eeb5648552b33f70e04b65">llvm::VPUser::setOperand</a>.</p>

</div>
</div>

### addFullyUnrolledInstructionsToIgnore() {#ababcaf6e2e00fc3fc8791ea2c3acbda5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addFullyUnrolledInstructionsToIgnore (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#a063c4d98febe7ef90dddbfedcfc59d16">LoopVectorizationLegality::InductionList</a> &amp; IL, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; InstsToIgnore)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Knowing that loop <span class="doxyComputerOutput">L</span> executes a single vector iteration, add instructions that will get simplified and thus should not have any cost to <span class="doxyComputerOutput">InstsToIgnore</span>.</p>

<p>Definition at line 2662 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ae4c50e6300599d50ba706c0d2b780502">llvm::LoopVectorizationCostModel::expectedCost</a>.</p>

</div>
</div>

### addResumePhiRecipeForInduction() {#a20c2e870e2c105fbf0945df09a9a5c4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPInstruction * addResumePhiRecipeForInduction (<a href="/web-llvm/docs/api/classes/llvm/vpwideninductionrecipe">VPWidenInductionRecipe</a> * WideIV, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder">VPBuilder</a> &amp; VectorPHBuilder, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder">VPBuilder</a> &amp; ScalarPHBuilder, <a href="/web-llvm/docs/api/classes/llvm/vptypeanalysis">VPTypeAnalysis</a> &amp; TypeInfo, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * VectorTC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create and return a ResumePhi for <span class="doxyComputerOutput">WideIV</span>, unless it is truncated.</p>


<p>If the induction recipe is not canonical, creates a <a href="/web-llvm/docs/api/classes/llvm/vpderivedivrecipe">VPDerivedIVRecipe</a> to compute the end value of the induction.</p>


<p>Definition at line 8956 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#a3d75b91bc4016f3078bab29877d8b68e">llvm::VPBuilder::createDerivedIV</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#accbbcc76f9eb947b3804ad96beb2bbd2">llvm::VPBuilder::createNaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#a7651e884685052147f007e0e0fe0c774">llvm::VPBuilder::createScalarCast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a733c4c530159a8b86223376c0696430e">llvm::VPRecipeBase::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwideninductionrecipe/#a82694b8412f0f864ede96af458b2fb87">llvm::VPWidenInductionRecipe::getInductionDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/vpheaderphirecipe/#a92c12c8e69e03cc781dd010cdaa5f0e6">llvm::VPHeaderPHIRecipe::getStartValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwideninductionrecipe/#a74f9beabcc57857ae7a7ba943e72776b">llvm::VPWidenInductionRecipe::getStepValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vptypeanalysis/#aac3fb75b481d61e325b6d869d0f5f278">llvm::VPTypeAnalysis::inferScalarType</a> and <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2a36144832b0ebcda13ce881d2b60eaf91">llvm::VPInstruction::ResumePhi</a>.</p>


<p>Referenced by <a href="#a02106664ead4e0c4e755457dbac7f7b3">addScalarResumePhis</a>.</p>

</div>
</div>

### addRuntimeUnrollDisableMetaData() {#a033bb363914fbd3c2cd990330959036c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addRuntimeUnrollDisableMetaData (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 7545 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a160e9e1a4fd597f83034c8b2ba316984">llvm::MDNode::replaceOperandWith</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a> and <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### addScalarResumePhis() {#a02106664ead4e0c4e755457dbac7f7b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addScalarResumePhis (<a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder">VPRecipeBuilder</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; &amp; IVEndValues)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create resume phis in the scalar preheader for first-order recurrences, reductions and inductions, and update the VPIRInstructions wrapping the original phis in the scalar header.</p>


<p>End values for inductions are added to <span class="doxyComputerOutput">IVEndValues</span>.</p>


<p>Definition at line 8994 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpuser/#af4a3b471097ab37b1672a0d88869ea51">llvm::VPUser::addOperand</a>, <a href="#a20c2e870e2c105fbf0945df09a9a5c4d">addResumePhiRecipeForInduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#accbbcc76f9eb947b3804ad96beb2bbd2">llvm::VPBuilder::createNaryOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2ad6b029191d02f4c7a7dda59e44c88ab6">llvm::VPInstruction::ExtractFromEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad9053d6ed9627166c144b8895d1c1010">llvm::VPlan::getCanonicalIV</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a995b2a034ffc26dcd2f3a679f9d2feea">llvm::VPlan::getMiddleBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ac38d49d70b5f78779e83abdf4dcb4be0">llvm::VPlan::getOrAddLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#af5f874dc688e86699e648825bfcbf495">llvm::VPRecipeBuilder::getRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ae56a6505c6bfa319e686fc23acd52495">llvm::VPlan::getScalarHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad5f29ccf71b0494fc179323427eb1e11">llvm::VPlan::getScalarPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#ac8744d8abf2a7ed185cc14f0a305cf8e">llvm::VPCanonicalIVPHIRecipe::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aa1bb4808c7a5db9f8ed3f479c78c4b5e">llvm::VPBlockBase::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aebc0e1a3379ed4fd614889e24b8ea48c">llvm::VPBlockBase::getSingleSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a233848f0bf7aef1aca22e6172e5d900d">llvm::VPlan::getVectorTripCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2a36144832b0ebcda13ce881d2b60eaf91">llvm::VPInstruction::ResumePhi</a>.</p>

</div>
</div>

### addUsersInExitBlocks() {#af34d746d08a380c672cae45176f9df87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addUsersInExitBlocks (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction">VPIRInstruction</a> * &gt; &amp; ExitUsersToFix)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 9089 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ac178f4fc4e4a0642610c374256b9fb27">llvm::SetVector&lt; T, Vector, Set, N &gt;::empty</a> and <a href="/web-llvm/docs/api/classes/llvm/vplan/#a995b2a034ffc26dcd2f3a679f9d2feea">llvm::VPlan::getMiddleBlock</a>.</p>

</div>
</div>

### areRuntimeChecksProfitable() {#a362f793f3254317c698e3560548788a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool areRuntimeChecksProfitable (GeneratedRTChecks &amp; Checks, <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor">VectorizationFactor</a> &amp; VF, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5d4f35a197e7b0f2320bdbbf518bd9d">ScalarEpilogueLowering</a> SEL)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 10054 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5d4f35a197e7b0f2320bdbbf518bd9da65f7ef37c3a0cd826b5e361e8cf32cf7">llvm::CM_ScalarEpilogueAllowed</a>, <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor/#a048d568675a5cc69c3fb85206882316d">llvm::VectorizationFactor::Cost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a>, <a href="#ab3df41ae1ed3978e3b825bc4dd50ae8d">getEstimatedRuntimeVF</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="#a84375e6536d9214c7895013078055aff">getSmallBestKnownTC</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a9b642067999075ba996ecdee40b52b68">llvm::InstructionCost::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a83e6442f8ebefccdb5e089732fe397ac">llvm::details::FixedOrScalableQuantity&lt; ElementCount, unsigned &gt;::isKnownLT</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#ae01c5ced9fe2fe50f421ae121483ef04">llvm::InstructionCost::isValid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor/#a0c1900dc8fe6b998c1de1880f300dcfa">llvm::VectorizationFactor::MinProfitableTripCount</a>, <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor/#a76f716c04dfa813b98e1c112bc642d34">llvm::VectorizationFactor::ScalarCost</a>, <a href="#a1293f02da7fffb33096a44f1b1768b3f">VectorizeMemoryCheckThreshold</a> and <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor/#a3a4e23fea2c7cec4fd3c2bf27351679c">llvm::VectorizationFactor::Width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### checkMixedPrecision() {#af1fba45879c49d4839b11ec30afd7532}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void checkMixedPrecision (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 10013 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter/#aae6a98aea85aa3af87357cc5448db499">llvm::OptimizationRemarkEmitter::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp/#a0eff4a8bccb143ae91e197e6a59d4692">LV_NAME</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### collectSupportedLoops() {#a00315ff11c9068aab97e5780bdfa5eef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void collectSupportedLoops (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * &gt; &amp; V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2179 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="#a00315ff11c9068aab97e5780bdfa5eef">collectSupportedLoops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dadcd5de1248b4d9893c409e7398c21">llvm::containsIrreducibleCFG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ef0a19ea2267182eb0da4f6e191b59b">llvm::EnableVPlanNativePath</a>, <a href="#a806ec23d6f44b02ad8cf3b1e61c05495">isExplicitVecOuterLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopblocksrpo/#aeab06fd248333b13725e55754883b570">llvm::LoopBlocksRPO::perform</a> and <a href="#a9f30855a6efcd4a12875deb88880b510">VPlanBuildStressTest</a>.</p>


<p>Referenced by <a href="#a00315ff11c9068aab97e5780bdfa5eef">collectSupportedLoops</a> and <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a0d3ab70393b799b3be4875c3334a4f42">llvm::LoopVectorizePass::runImpl</a>.</p>

</div>
</div>

### collectUsersInExitBlocks() {#a435b95efad7ea03299bd527b55b4708a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt; VPIRInstruction * &gt; collectUsersInExitBlocks (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * OrigLoop, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder">VPRecipeBuilder</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 9055 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a85800ca7a821f540ad2d6d4d3c2d4208">llvm::VPlan::getExitBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a995b2a034ffc26dcd2f3a679f9d2feea">llvm::VPlan::getMiddleBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a7951985b28c0786b4ca50f061172ff22">llvm::VPRecipeBuilder::getVPValueOrAddLiveIn</a> and <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>.</p>

</div>
</div>

### createLVAnalysis() {#afec6951f3043e25ada2b61437bd60725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkAnalysis createLVAnalysis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PassName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemarkName, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * TheLoop, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={})</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an analysis remark that explains why vectorization failed.</p>


<p><span class="doxyComputerOutput">PassName</span> is the name of the pass (e.g. can be AlwaysPrint). <span class="doxyComputerOutput">RemarkName</span> is the identifier for the remark. If <span class="doxyComputerOutput">I</span> is passed it is an instruction that prevents vectorization. Otherwise <span class="doxyComputerOutput">TheLoop</span> is used for the location of the remark. If <span class="doxyComputerOutput">DL</span> is passed, use it as debug location for the remark.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the remark object that can be streamed to.</p></dd>
</dl>


<p>Definition at line 860 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab425bb10a0f4af749bbb29aa07fc6854">llvm::reportVectorizationFailure</a>.</p>

</div>
</div>

### createWidenInductionRecipes() {#a9336eb7b4fbcee561dbb8c52d9eabe64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPWidenIntOrFpInductionRecipe * createWidenInductionRecipes (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * PhiOrTrunc, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Start, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor">InductionDescriptor</a> &amp; IndDesc, <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; OrigLoop)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a VPWidenIntOrFpInductionRecpipe for <span class="doxyComputerOutput">Phi</span>.</p>


<p>If needed, it will also insert a recipe to expand the step for the induction recipe.</p>


<p>Definition at line 8317 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ac3280e7f76f955403fe17eacf126b90d">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopPreheader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a064976a6c7458b10c24021b7334cec2a">llvm::vputils::getOrCreateVPValueForSCEVExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#aea63dae61a488e20e237f5f517ed1491">llvm::InductionDescriptor::getStartValue</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#a83b5b65084a0c1de3a76f36f198b1b0c">llvm::InductionDescriptor::getStep</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a2dffed680cc551f7ac6d92b3cd365d11">llvm::VPlan::getVF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5a19768af81df7e5fe571bc08dcd48b3">llvm::ScalarEvolution::isLoopInvariant</a>.</p>

</div>
</div>

### cse() {#acc13ee8b8985399901ac09b51822e21a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void cse (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform cse of induction variable instructions.</p>

<p>Definition at line 2811 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-loopvectorize-cpp-/csedensemapinfo/#a64e393e021291b440c6638be61fe249b">anonymous{LoopVectorize.cpp}::CSEDenseMapInfo::canHandle</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0b2ca98dc28c61793ff5c90d23e5f14e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::lookup</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a9484786140efebf774cde8f072894246">llvm::InnerLoopVectorizer::fixVectorizedLoop</a>.</p>

</div>
</div>

### debugVectorizationMessage() {#a1a861c376095fff2ee736b0a743cc44e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void debugVectorizationMessage (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> DebugMsg, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write a <span class="doxyComputerOutput">DebugMsg</span> about vectorization to the debug output stream.</p>


<p>If <span class="doxyComputerOutput">I</span> is passed, the message relates to that particular instruction.</p>


<p>Definition at line 840 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0c19b37908311872f655348755e8d003">llvm::reportVectorization</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab425bb10a0f4af749bbb29aa07fc6854">llvm::reportVectorizationFailure</a>.</p>

</div>
</div>

### determineVPlanVF() {#a0b91e092434338369b2e1995b87f0c5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElementCount determineVPlanVF (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel">LoopVectorizationCostModel</a> &amp; CM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 7027 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a79ea372f9aa69492fccfafc0e5a1589c">llvm::ElementCount::get</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a1fa63b37ad2ac06f289e9962a3703e9e">llvm::LoopVectorizationCostModel::getSmallestAndWidestTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a9c374320ed4e895f9afa199987182bd2">RegSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166a183020fbea95c99db23f6d3594f4c4af">llvm::TargetTransformInfo::RGK_FixedWidthVector</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166a331413d3887a08546d0973091f6a4993">llvm::TargetTransformInfo::RGK_ScalableVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a2206e77c573f4947146faa681ea8855e">llvm::LoopVectorizationPlanner::planInVPlanNativePath</a>.</p>

</div>
</div>

### emitTransformedIndex() {#a23f5821d9ac264ae25dd087747e2c181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * emitTransformedIndex (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Index, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * StartValue, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Step, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#ac2d32589e2e153088b8a35db1a9eabcc">InductionDescriptor::InductionKind</a> InductionKind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * InductionBinOp)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the transformed value of Index at offset StartValue using step StepValue.</p>


<p>For integer induction, returns StartValue + Index * StepValue. For pointer induction, returns StartValue[Index * StepValue]. FIXME: The newly created binary instructions should contain nsw/nuw flags, which can be found from the original scalar operations.</p>


<p>Definition at line 2216 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a4b946333b7fb96fec126f22534cf3794">CreateAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a3621b702ef72b987959cdd7242c13d47">CreateMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#ac2d32589e2e153088b8a35db1a9eabccab0b71801de025f26b088a8cb22825f79">llvm::InductionDescriptor::IK_FpInduction</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#ac2d32589e2e153088b8a35db1a9eabccaf0191e822c9708e106d7bb58aa9ec947">llvm::InductionDescriptor::IK_IntInduction</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#ac2d32589e2e153088b8a35db1a9eabcca85d6fca1e5ba292e9d884797aa73f545">llvm::InductionDescriptor::IK_NoInduction</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#ac2d32589e2e153088b8a35db1a9eabccab61689ca7d0a024fc4ff52a74d691ae2">llvm::InductionDescriptor::IK_PtrInduction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a69c116deda6ae831a71558a4630323cb">llvm::InnerLoopVectorizer::createInductionAdditionalBypassValues</a> and <a href="/web-llvm/docs/api/classes/llvm/vpderivedivrecipe/#a0f37fe11b57d14686c7ca5e7a3846174">llvm::VPDerivedIVRecipe::execute</a>.</p>

</div>
</div>

### fixReductionScalarResumeWhenVectorizingEpilog() {#a90ad8ccd396152c749068f986f2b751a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void fixReductionScalarResumeWhenVectorizingEpilog (<a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> * R, <a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> &amp; State, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * LoopMiddleBlock, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BypassBlock)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 7582 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2ad9b4011dc2ac58da0fecd16d99f1f17d">llvm::VPInstruction::ComputeReductionResult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ab2db7609ec72b1af2f91d47e40dc3722">llvm::PHINode::getIncomingValueForBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a89e9d5a5838c63159df1aed56f600ef1">llvm::RecurrenceDescriptor::getRecurrenceKind</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a61351428b7eb226cbad866ccf2382817">llvm::RecurrenceDescriptor::getRecurrenceStartValue</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#aed10715d943d3e1b4ca75b585ea96ab8">llvm::RecurrenceDescriptor::getSentinelValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a69df67c7d92481ae63a5d8017e96c716">llvm::RecurrenceDescriptor::isAnyOfRecurrenceKind</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a7bc46d4489f4d6cb4a4e486ce5f6184b">llvm::RecurrenceDescriptor::isFindLastIVRecurrenceKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3ccd94f6a7507492b47c7351e3fb78c6">llvm::PatternMatch::m_Select</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a6924ab881778c340b66e1e693154b1a8">llvm::PatternMatch::m_SpecificICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>.</p>

</div>
</div>

### getAddressAccessSCEV() {#ad27a81251d238dbfdc4d0253a64d6267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * getAddressAccessSCEV (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality">LoopVectorizationLegality</a> * Legal, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * TheLoop)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets Address Access <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> after verifying that the access pattern is loop invariant except the induction variable dependence.</p>


<p>This <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> can be sent to the <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> in order to estimate the address calculation cost.</p>


<p>Definition at line 5587 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#ae0994d8207b94ad22ecebc1a6bc580f1">llvm::PredicatedScalarEvolution::getSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#a10ca5eacc61b5669880de2f8b0cff33c">llvm::PredicatedScalarEvolution::getSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bda8f7357506e00d8cd0694f948f909865d">llvm::IRSimilarity::Legal</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### getDebugLocFromInstOrOperands() {#a29c708de8e758ac420523c94c797b501}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc getDebugLocFromInstOrOperands (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look for a meaningful debug location on the instruction or its operands.</p>

<p>Definition at line 820 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp/#a066f917f4a73ce07260b0e4262be92ba">DenseMapInfo&lt; LocallyHashedType &gt;::Empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getEstimatedRuntimeVF() {#ab3df41ae1ed3978e3b825bc4dd50ae8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getEstimatedRuntimeVF (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function attempts to return a value that represents the vectorization factor at runtime.</p>


<p>For fixed-width VFs we know this precisely at compile time, but for scalable VFs we calculate it based on an estimate of the vscale value.</p>


<p>Definition at line 4255 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#a4e108201f94f2fe89865e7868390bbf6">getVScaleForTuning</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>.</p>


<p>Referenced by <a href="#a362f793f3254317c698e3560548788a5">areRuntimeChecksProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a07db8a5919c9879e3327549f20cda2f9">llvm::LoopVectorizationCostModel::isEpilogueVectorizationProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a0b6b1ae088cb8ca3aa4f26c4098daa3d">llvm::LoopVectorizationPlanner::selectEpilogueVectorizationFactor</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#af9f62350ccdebd24858be552f3fc051c">llvm::LoopVectorizationCostModel::selectInterleaveCount</a>.</p>

</div>
</div>

### getExpandedStep() {#aa8d4cfce02b245d616238ce8eed74718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * getExpandedStep (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor">InductionDescriptor</a> &amp; ID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SCEV2ValueTy &amp; ExpandedSCEVs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the expanded step for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span> using <span class="doxyComputerOutput">ExpandedSCEVs</span> to look up <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expansion results.</p>

<p>Definition at line 2647 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a69c116deda6ae831a71558a4630323cb">llvm::InnerLoopVectorizer::createInductionAdditionalBypassValues</a>.</p>

</div>
</div>

### getMaxVScale() {#a604c96744d2e46447f11e2d3aab9a9b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; getMaxVScale (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2295 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a65ab4267c6c132d06451b5d97bc9ee83">llvm::LoopVectorizationCostModel::computeMaxVF</a> and <a href="#ab7edde995b7986f98c3f59788b960eba">isIndvarOverflowCheckKnownFalse</a>.</p>

</div>
</div>

### getScalarEpilogueLowering() {#a8cde912cc23c18f493e4e5005c85748b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEpilogueLowering getScalarEpilogueLowering (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints">LoopVectorizeHints</a> &amp; Hints, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality">LoopVectorizationLegality</a> &amp; LVL, <a href="/web-llvm/docs/api/classes/llvm/interleavedaccessinfo">InterleavedAccessInfo</a> * IAI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 9897 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab5d4f35a197e7b0f2320bdbbf518bd9da65f7ef37c3a0cd826b5e361e8cf32cf7">llvm::CM_ScalarEpilogueAllowed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5d4f35a197e7b0f2320bdbbf518bd9da4f61afe29426363c5cf62d4ee93199b7">llvm::CM_ScalarEpilogueNotAllowedOptSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5d4f35a197e7b0f2320bdbbf518bd9dab8edd8f39c728bd8b0045b64768ef206">llvm::CM_ScalarEpilogueNotAllowedUsePredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5d4f35a197e7b0f2320bdbbf518bd9da34c20b2dbd2edddfd1b013f073a32354">llvm::CM_ScalarEpilogueNotNeededUsePredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a55ab1072c44295ad279535d714a0f33ea980c2c6e59ca5dcf413baa325d8bc385">llvm::LoopVectorizeHints::FK_Disabled</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a55ab1072c44295ad279535d714a0f33ea278ca681847fb2bad9707f76d899b231">llvm::LoopVectorizeHints::FK_Enabled</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a20ecacbd54e401685d798d86161af6cf">llvm::LoopVectorizeHints::getForce</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a7592f6d851162d7f66f26408f40e9388">llvm::LoopVectorizeHints::getPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec7c967a5416fa6e154433965357a50ea089e7eb4db258e05f70eef4ed5aa10bb">llvm::IRPass</a>, <a href="/web-llvm/docs/api/namespaces/preferpredicatety/#ab00d54c73f16daa1e1f9f65f77db0cdaa3111b239a92c1674cea87d025e818091">PreferPredicateTy::PredicateElseScalarEpilogue</a>, <a href="/web-llvm/docs/api/namespaces/preferpredicatety/#ab00d54c73f16daa1e1f9f65f77db0cdaa5e6f0abe1c426939c61d8924cfa02e5a">PreferPredicateTy::PredicateOrDontVectorize</a>, <a href="#abe3c68238712d04bbe3a70f3a8f483f5">PreferPredicateOverEpilogue</a>, <a href="/web-llvm/docs/api/namespaces/preferpredicatety/#ab00d54c73f16daa1e1f9f65f77db0cdaa114bc9020d046f551b06f41f6f4539f7">PreferPredicateTy::ScalarEpilogue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3af72f14ea20f2c762c751d2d49e5ea3">llvm::shouldOptimizeForSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a> and <a href="#adeb41c907ebde15846bc643325909f95">processLoopInVPlanNativePath</a>.</p>

</div>
</div>

### getSmallBestKnownTC() {#a84375e6536d9214c7895013078055aff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; getSmallBestKnownTC (<a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, bool CanUseConstantMax=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns "best known" trip count for the specified loop <span class="doxyComputerOutput">L</span> as defined by the following procedure: 1) Returns exact trip count if it is known.</p>


<p>2) Returns expected trip count according to profile data if any. 3) Returns upper bound estimate if known, and if <span class="doxyComputerOutput">CanUseConstantMax</span>. 4) Returns std::nullopt if all of the above failed.</p>


<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0b3c6dc8e7df65d2385acfe9657abd03">llvm::getLoopEstimatedTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#a10ca5eacc61b5669880de2f8b0cff33c">llvm::PredicatedScalarEvolution::getSE</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#aacf376f9963d73732052a7362c5afabd">llvm::PredicatedScalarEvolution::getSmallConstantMaxTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#abec0c616087c002528fcf80c6583eadd">llvm::ScalarEvolution::getSmallConstantTripCount</a> and <a href="#aa5a50c0ac98e2ed63da85783ca102cf8">LoopVectorizeWithBlockFrequency</a>.</p>


<p>Referenced by <a href="#a362f793f3254317c698e3560548788a5">areRuntimeChecksProfitable</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks/#ad7b44d9befce70f070d4355d10ffc419">anonymous{LoopVectorize.cpp}::GeneratedRTChecks::getCost</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#af9f62350ccdebd24858be552f3fc051c">llvm::LoopVectorizationCostModel::selectInterleaveCount</a>.</p>

</div>
</div>

### getVScaleForTuning() {#a4e108201f94f2fe89865e7868390bbf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; getVScaleForTuning (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convenience function that returns the value of vscale_range iff vscale_range.min == vscale_range.max or otherwise returns the value returned by the corresponding <a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068">TTI</a> method.</p>

<p>Definition at line 4238 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a4c319db4fe05c27cfe55bd133a87414d">llvm::Function::getFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a2340c9d2c47ffa7fc07568ba059b62a2">llvm::Attribute::getVScaleRangeMin</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>.</p>


<p>Referenced by <a href="#ab3df41ae1ed3978e3b825bc4dd50ae8d">getEstimatedRuntimeVF</a>.</p>

</div>
</div>

### hasIrregularType() {#aa407c2e7d895ed29af8cc68563c03065}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasIrregularType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A helper function that returns true if the given type is irregular.</p>


<p>The type is irregular if its allocated size doesn't equal the store size of an element of the corresponding vector type.</p>


<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a5964ce9ba38fe5a4d372242ac39e3f1d">llvm::LoopVectorizationCostModel::interleavedAccessCanBeWidened</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a59a6dd7531c8683174f886ff7698cc63">llvm::LoopVectorizationCostModel::memoryInstructionCanBeWidened</a>.</p>

</div>
</div>

### isExplicitVecOuterLoop() {#a806ec23d6f44b02ad8cf3b1e61c05495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isExplicitVecOuterLoop (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * OuterLp, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2151 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a21b6d9e2aa12c8c68d8e2f122ec7ecec">llvm::LoopVectorizeHints::allowVectorization</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a440979b6103588bef39bd2d62065d5ff">llvm::LoopVectorizeHints::emitRemarkWithHints</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a55ab1072c44295ad279535d714a0f33ea8914fe2dbf82d457456e8e4faa201b87">llvm::LoopVectorizeHints::FK_Undefined</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a20ecacbd54e401685d798d86161af6cf">llvm::LoopVectorizeHints::getForce</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#ad98353127dbeb649d41ca07da5074b49">llvm::LoopVectorizeHints::getInterleave</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a16165c1e5da45acaa086c3a54a188d34">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInnermost</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#a00315ff11c9068aab97e5780bdfa5eef">collectSupportedLoops</a>.</p>

</div>
</div>

### isIndvarOverflowCheckKnownFalse() {#ab7edde995b7986f98c3f59788b960eba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isIndvarOverflowCheckKnownFalse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel">LoopVectorizationCostModel</a> * Cost, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, std::optional&lt; unsigned &gt; UF=std::nullopt)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For the given VF and UF and maximum trip count computed for the loop, return whether the induction variable might overflow in the vectorized loop.</p>


<p>If not, then we know a runtime overflow check always evaluates to false and can be removed.</p>


<p>Definition at line 2310 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#a604c96744d2e46447f11e2d3aab9a9b2">getMaxVScale</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a72c491cdf8cf0283d87008831431f917">llvm::InnerLoopVectorizer::emitIterationCountCheck</a>.</p>

</div>
</div>

### maybeVectorizeType() {#a83114915b4f7fec94a20efa3834a8250}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * maybeVectorizeType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Elt, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2858 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#abf313eff420b7c6c8e322a2e9c53cd90">llvm::Type::isIntOrPtrTy</a> and <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a5abced3ab870d7abf57f2b35a02cd041">llvm::LoopVectorizationCostModel::getVectorIntrinsicCost</a>.</p>

</div>
</div>

### planContainsAdditionalSimplifications() {#a696283c30308704d020a9d86065aa3ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool planContainsAdditionalSimplifications (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/structs/llvm/vpcostcontext">VPCostContext</a> &amp; CostCtx, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * TheLoop)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the original loop \ TheLoop contains any instructions that do not have corresponding recipes in <span class="doxyComputerOutput">Plan</span> and are not marked to be ignored in <span class="doxyComputerOutput">CostCtx</span>.</p>


<p>This means the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> contains simplification that the legacy cost-model did not account for.</p>


<p>Definition at line 7409 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a78bec3084b9a47ee11cc2e56f9004717">llvm::LoopBase&lt; BlockT, LoopT &gt;::blocks</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a0360eea6cebcb1470f84b11f7ba51f16">llvm::VPBlockUtils::blocksOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a1ae2cb3c63b4d67324ddc947fb9696fc">llvm::VPRegionBlock::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a495c27cd70886cb8647df0ecdd9cc63d">llvm::vp_depth_first_deep</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a4adc69fc8f74164e990cce6afc1e061b">llvm::LoopVectorizationPlanner::computeBestVF</a>.</p>

</div>
</div>

### preparePlanForEpilogueVectorLoop() {#aae23f7e6fc37b0f1bb756f938023512c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void preparePlanForEpilogueVectorLoop (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SCEV2ValueTy &amp; ExpandedSCEVs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/epilogueloopvectorizationinfo">EpilogueLoopVectorizationInfo</a> &amp; EPI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prepare <span class="doxyComputerOutput">Plan</span> for vectorizing the epilogue loop.</p>


<p>That is, re-use expanded SCEVs from <span class="doxyComputerOutput">ExpandedSCEVs</span> and set resume values for header recipes.</p>


<p>Definition at line 10210 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8c75539a39f167f352b37ccdd788a7e4">llvm::IRBuilderBase::CreateICmpEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f6975e193997c4e0183e96774a7cb39">llvm::find_singleton</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a1c868dfd250ff9592c06dd61a7fb0bcf">llvm::VPlan::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a362b5e6097732cbc0d2fb555a1f73400">llvm::BasicBlock::getFirstNonPHIIt</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ab2db7609ec72b1af2f91d47e40dc3722">llvm::PHINode::getIncomingValueForBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ac38d49d70b5f78779e83abdf4dcb4be0">llvm::VPlan::getOrAddLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a89e9d5a5838c63159df1aed56f600ef1">llvm::RecurrenceDescriptor::getRecurrenceKind</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a61351428b7eb226cbad866ccf2382817">llvm::RecurrenceDescriptor::getRecurrenceStartValue</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#aed10715d943d3e1b4ca75b585ea96ab8">llvm::RecurrenceDescriptor::getSentinelValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a2f5fc19caa67daeca8a1316c7e055e3c">llvm::VPlan::getTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a69df67c7d92481ae63a5d8017e96c716">llvm::RecurrenceDescriptor::isAnyOfRecurrenceKind</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a7bc46d4489f4d6cb4a4e486ce5f6184b">llvm::RecurrenceDescriptor::isFindLastIVRecurrenceKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#abaad22a81f7fa4ce5b60ec619ac14c37">llvm::VPValue::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a9bb77d906fd1ae7e241f0c95dcba094b">llvm::VPlan::resetTripCount</a> and <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a2bd1c53f9607876b22c6fd3ec1e28a50">llvm::VPBlockBase::setName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### preparePlanForMainVectorLoop() {#a13368acf4fbb5816c3d82099b11519b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void preparePlanForMainVectorLoop (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; MainPlan, <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; EpiPlan)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prepare <span class="doxyComputerOutput">MainPlan</span> for vectorizing the main vector loop during epilogue vectorization.</p>


<p>Remove ResumePhis from <span class="doxyComputerOutput">MainPlan</span> for inductions that don't have a corresponding wide induction in <span class="doxyComputerOutput">EpiPlan</span>.</p>


<p>Definition at line 10159 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a4e30ea9d413dd86c802fee94aa8b5805">llvm::VPBasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#af74676a3c7447be34bd2c1da76ec0c48">llvm::SmallPtrSetImpl&lt; PtrType &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#accbbcc76f9eb947b3804ad96beb2bbd2">llvm::VPBuilder::createNaryOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#aac9dfb61b37082dca00de284bb3309e8">llvm::VPRecipeBase::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad9053d6ed9627166c144b8895d1c1010">llvm::VPlan::getCanonicalIV</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a3be8d7833df422f3538ddb13af69bd70">llvm::VPValue::getDefiningRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a6e1b252a9bbdc1a440fb57a6257b97f4">llvm::VPUser::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ae56a6505c6bfa319e686fc23acd52495">llvm::VPlan::getScalarHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad5f29ccf71b0494fc179323427eb1e11">llvm::VPlan::getScalarPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/vpheaderphirecipe/#a92c12c8e69e03cc781dd010cdaa5f0e6">llvm::VPHeaderPHIRecipe::getStartValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a233848f0bf7aef1aca22e6172e5d900d">llvm::VPlan::getVectorTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2471be3f1b50002f54bf45c590d8d41b">llvm::PatternMatch::m_SpecificInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a668c6f14a461ccf0ee11c9c7a076a901">llvm::VPBasicBlock::phis</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aaca9dd97d4c523d8c65274654abe4eb9">llvm::VPlanTransforms::removeDeadRecipes</a> and <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2a36144832b0ebcda13ce881d2b60eaf91">llvm::VPInstruction::ResumePhi</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### processLoopInVPlanNativePath() {#adeb41c907ebde15846bc643325909f95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool processLoopInVPlanNativePath (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality">LoopVectorizationLegality</a> * LVL, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/classes/llvm/demandedbits">DemandedBits</a> * DB, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints">LoopVectorizeHints</a> &amp; Hints, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationrequirements">LoopVectorizationRequirements</a> &amp; Requirements)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 9946 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a06f5d9725a2b1f7b06e8bf51f7d31417">llvm::LoopVectorizationCostModel::collectElementTypesForWidening</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a686506cbb75808c52247608065bc6596">llvm::LoopVectorizationCostModel::CostKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor/#acd24dfdad4f887e1f7b10c9039a05930">llvm::VectorizationFactor::Disabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ef0a19ea2267182eb0da4f6e191b59b">llvm::EnableVPlanNativePath</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#ada1db826f3d2266fe2c4d06218d8d342">llvm::PredicatedScalarEvolution::getBackedgeTakenCount</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#ab5632546144c4db5bbe1f975aeebd9d2">llvm::LoopVectorizationLegality::getLAI</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a10f355c5a55dd7e98d31c2f7e0b590aa">llvm::LoopVectorizationPlanner::getPlanFor</a>, <a href="#a8cde912cc23c18f493e4e5005c85748b">getScalarEpilogueLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a50cae5c2df432357d50f182d310ce7b7">llvm::LoopVectorizeHints::getWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add2fce2ce0e32b20e41b0aa9f8ca70c2">llvm::hasBranchWeightMD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a2206e77c573f4947146faa681ea8855e">llvm::LoopVectorizationPlanner::planInVPlanNativePath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c19b37908311872f655348755e8d003">llvm::reportVectorization</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#aa2f5ef2d522fb80de283a23d5bed6d86">llvm::LoopVectorizeHints::setAlreadyVectorized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26389c546573f058ad8ecbdc5c1933cf">llvm::verifyFunction</a>, <a href="#a9f30855a6efcd4a12875deb88880b510">VPlanBuildStressTest</a> and <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor/#a3a4e23fea2c7cec4fd3c2bf27351679c">llvm::VectorizationFactor::Width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### replaceVPBBWithIRVPBB() {#a3a8743a69fac5e7fa9c2b02604b2cf2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void replaceVPBBWithIRVPBB (<a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> * VPBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * IRBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace <span class="doxyComputerOutput">VPBB</span> with a <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> wrapping <span class="doxyComputerOutput">IRBB</span>.</p>


<p>All recipes from <span class="doxyComputerOutput">VPBB</span> are moved to the end of the newly created <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a>. VPBB must have a single predecessor, which is rewired to the new <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a>. All successors of VPBB, if any, are rewired to the new <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a>.</p>


<p>Definition at line 2617 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#aa12c0d3acb3f625ee09d2919907d4067">llvm::VPlan::createVPIRBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a4a7f4b8433e9a788149ffd94a0a07051">llvm::VPBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a8d57e2fe646928a51e97714005eefdc7">llvm::VPBlockBase::getPlan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a> and <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a63345282cd67ea46202fb33523be1408">llvm::VPBlockUtils::reassociateBlocks</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a5e719da4709193fd5b4632da4bc69795">llvm::InnerLoopVectorizer::createVectorLoopSkeleton</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>.</p>

</div>
</div>

### STATISTIC() {#ad8318a653242df10df04853e090cc21f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (LoopsVectorized, "Number of <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp/#a49ae40a9c91d665793aaed656c26ca30">loops</a> vectorized")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#aefd85537796668463b24d5ab5b225407}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (LoopsAnalyzed, "Number of <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp/#a49ae40a9c91d665793aaed656c26ca30">loops</a> analyzed <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> vectorization")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a683da38156d0f59a8d6a0cc83dc7ae14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (LoopsEpilogueVectorized, "Number of epilogues vectorized")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### useActiveLaneMask() {#aae88a50a9a37f9a745939e3e726837e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool useActiveLaneMask (<a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdd">TailFoldingStyle</a> Style)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2126 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bddaf6068daa29dbb05a7ead1e3b5a48bbee">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bddad817e2199b89933da1a3cd7e130cd782">llvm::DataAndControlFlow</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdda41105c5fe36c41d2246b18c1724fa2ff">llvm::DataAndControlFlowWithoutRuntimeCheck</a>.</p>

</div>
</div>

### useActiveLaneMaskForControlFlow() {#a4e445204e48d57b1e23e55869146b7ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool useActiveLaneMaskForControlFlow (<a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdd">TailFoldingStyle</a> Style)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2132 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bddad817e2199b89933da1a3cd7e130cd782">llvm::DataAndControlFlow</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdda41105c5fe36c41d2246b18c1724fa2ff">llvm::DataAndControlFlowWithoutRuntimeCheck</a>.</p>

</div>
</div>

### useMaskedInterleavedAccesses() {#adf8d8fb6f39b9c0cf21d55b7229d35e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool useMaskedInterleavedAccesses (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2341 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Reference <a href="#ac68ad295befb7187ae293cc0faaa3ac3">EnableMaskedInterleavedMemAccesses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a65ab4267c6c132d06451b5d97bc9ee83">llvm::LoopVectorizationCostModel::computeMaxVF</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a5964ce9ba38fe5a4d372242ac39e3f1d">llvm::LoopVectorizationCostModel::interleavedAccessCanBeWidened</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#aca6160bb3d669e9ce01f91b124e7e0a1">llvm::LoopVectorizationPlanner::plan</a> and <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### willGenerateVectors() {#af378bb1e037306d9cfd4bb0b49ba55f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool willGenerateVectors (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if any recipe of <span class="doxyComputerOutput">Plan</span> will generate a vector value, which will be assigned a vector register.</p>

<p>Definition at line 4439 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a0360eea6cebcb1470f84b11f7ba51f16">llvm::VPBlockUtils::blocksOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62219a4c97e27d64593245e4e9187cd1">llvm::collectEphemeralRecipesForVPlan</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad9053d6ed9627166c144b8895d1c1010">llvm::VPlan::getCanonicalIV</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a1ae2cb3c63b4d67324ddc947fb9696fc">llvm::VPRegionBlock::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#ac8744d8abf2a7ed185cc14f0a305cf8e">llvm::VPCanonicalIVPHIRecipe::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/vptypeanalysis/#aac3fb75b481d61e325b6d869d0f5f278">llvm::VPTypeAnalysis::inferScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a098a514da47d00e1176aa2e16eacfb70">llvm::ElementCount::isVector</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae5262cc0e3a55bc74891cb8751d3b188">llvm::toVectorTy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4474bfb1e0ca062e5bfe2a35980e7d19">llvm::vp_depth_first_shallow</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a4adc69fc8f74164e990cce6afc1e061b">llvm::LoopVectorizationPlanner::computeBestVF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### EnableCondStoresVectorization {#a1b67aba558e56b48dbb2891b6e5fe5b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableCondStoresVectorization("enable-cond-stores-vec", cl::init(true), cl::Hidden, cl::desc("Enable if predication of stores during vectorization."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### EnableEarlyExitVectorization {#af7af1b4bf03205c80dcba0a6324c4f21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableEarlyExitVectorization("enable-early-exit-vectorization", cl::init(false), cl::Hidden, cl::desc( "Enable vectorization of early exit loops with uncountable exits."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a913ab9c8291000dd3a1c3739194b03e4">llvm::LoopVectorizationCostModel::requiresScalarEpilogue</a>.</p>

</div>
</div>

### EnableEpilogueVectorization {#a8bb0da83afffaf803b396b1d055ba5e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableEpilogueVectorization("enable-epilogue-vectorization", cl::init(true), cl::Hidden, cl::desc("Enable vectorization of epilogue loops."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a0b6b1ae088cb8ca3aa4f26c4098daa3d">llvm::LoopVectorizationPlanner::selectEpilogueVectorizationFactor</a>.</p>

</div>
</div>

### EnableIndVarRegisterHeur {#a8122656ed2c776067b43d9ae34ccecb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableIndVarRegisterHeur("enable-ind-var-reg-heur", cl::init(true), cl::Hidden, cl::desc("Count the induction variable only once when interleaving"))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#af9f62350ccdebd24858be552f3fc051c">llvm::LoopVectorizationCostModel::selectInterleaveCount</a>.</p>

</div>
</div>

### EnableInterleavedMemAccesses {#ac3af17aa5bce5ef8c3aa82faeacfc456}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableInterleavedMemAccesses("enable-interleaved-mem-accesses", cl::init(false), cl::Hidden, cl::desc("Enable vectorization on interleaved memory accesses in a loop"))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### EnableLoadStoreRuntimeInterleave {#a99a396adb2c0f9fb93b7ff8ea8b2e2ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableLoadStoreRuntimeInterleave("enable-loadstore-runtime-interleave", cl::init(true), cl::Hidden, cl::desc( "Enable runtime interleaving until load/store ports are saturated"))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#af9f62350ccdebd24858be552f3fc051c">llvm::LoopVectorizationCostModel::selectInterleaveCount</a>.</p>

</div>
</div>

### EnableMaskedInterleavedMemAccesses {#ac68ad295befb7187ae293cc0faaa3ac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableMaskedInterleavedMemAccesses("enable-masked-interleaved-mem-accesses", cl::init(false), cl::Hidden, cl::desc("Enable vectorization on masked interleaved memory accesses in a loop"))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An interleave-group may need masking if it resides in a block that needs predication, or in order to mask away gaps.</p>

<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#adf8d8fb6f39b9c0cf21d55b7229d35e2">useMaskedInterleavedAccesses</a>.</p>

</div>
</div>

### EpilogueVectorizationForceVF {#a01340df86c9d26b281ff1ab9288c28ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; EpilogueVectorizationForceVF("epilogue-vectorization-force-VF", cl::init(1), cl::Hidden, cl::desc("When epilogue vectorization is enabled, and a value greater than " "1 is specified, forces the given VF for all applicable epilogue " "loops."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a0b6b1ae088cb8ca3aa4f26c4098daa3d">llvm::LoopVectorizationPlanner::selectEpilogueVectorizationFactor</a>.</p>

</div>
</div>

### EpilogueVectorizationMinVF {#a01070590fdc156c181654c2db7b9ddcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; EpilogueVectorizationMinVF("epilogue-vectorization-minimum-VF", cl::Hidden, cl::desc("Only loops with vectorization factor equal to or larger than " "the specified value are considered for epilogue vectorization."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a07db8a5919c9879e3327549f20cda2f9">llvm::LoopVectorizationCostModel::isEpilogueVectorizationProfitable</a>.</p>

</div>
</div>

### ForceOrderedReductions {#acb0b374f69dc6867357f0aa5e93ab33d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ForceOrderedReductions("force-ordered-reductions", cl::init(false), cl::Hidden, cl::desc("Enable the vectorisation of loops with in-order (strict) " "FP reductions"))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### ForceSafeDivisor {#ad69cf8bf5c6b79c5642327ecb6be38cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; cl::boolOrDefault &gt; ForceSafeDivisor("force-widen-divrem-via-safe-divisor", cl::Hidden, cl::desc( "Override cost based safe divisor widening for div/rem instructions"))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#add43c346a11ae1deb49142ba968eb07e">llvm::LoopVectorizationCostModel::isDivRemScalarWithPredication</a>.</p>

</div>
</div>

### ForceTailFoldingStyle {#a8959791a22c7d3cfb4136777fd244535}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; TailFoldingStyle &gt; ForceTailFoldingStyle("force-tail-folding-style", cl::desc("Force the tail folding style"), cl::init(TailFoldingStyle::None), cl::values( clEnumValN(TailFoldingStyle::None, "none", "Disable tail folding"), clEnumValN( TailFoldingStyle::Data, "data", "Create lane mask for data only, using active.lane.mask intrinsic"), clEnumValN(TailFoldingStyle::DataWithoutLaneMask, "data-without-lane-mask", "Create lane mask with compare/stepvector"), clEnumValN(TailFoldingStyle::DataAndControlFlow, "data-and-control", "Create lane mask using active.lane.mask intrinsic, and use " "it for both data and control flow"), clEnumValN(TailFoldingStyle::DataAndControlFlowWithoutRuntimeCheck, "data-and-control-without-rt-check", "Similar to data-and-control, but remove the runtime check"), clEnumValN(TailFoldingStyle::DataWithEVL, "data-with-evl", "Use predicated EVL instructions for tail folding. If EVL " "is unsupported, fallback to data-without-lane-mask.")))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ab8eb89837d2853e4853ea14379ae3972">llvm::LoopVectorizationCostModel::setTailFoldingStyles</a>.</p>

</div>
</div>

### ForceTargetInstructionCost {#a5eae6074e6a1bb62e365ef65f3e26196}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; ForceTargetInstructionCost("force-target-instruction-cost", cl::init(0), cl::Hidden, cl::desc("A flag that overrides the target's expected cost for " "an instruction to a single constant value. Mostly " "useful for getting consistent testing."))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a45ff90e525c3f3879a1a7f5297d8857d">llvm::VPReductionRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#ac84a2bc6b484c5d3a03e80ce40f0a14c">llvm::VPRecipeBase::cost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#aa948ba905ff37c533b3c85068f94fd24">llvm::VPRegionBlock::cost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ae4c50e6300599d50ba706c0d2b780502">llvm::LoopVectorizationCostModel::expectedCost</a> and <a href="/web-llvm/docs/api/structs/llvm/vpcostcontext/#a79d75561901a5fc0d187b229afd5a745">llvm::VPCostContext::getLegacyCost</a>.</p>

</div>
</div>

### ForceTargetMaxScalarInterleaveFactor {#aee1082071c43958a6ef5e6e9f665ae4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; ForceTargetMaxScalarInterleaveFactor("force-target-max-scalar-interleave", cl::init(0), cl::Hidden, cl::desc("A flag that overrides the target's max interleave factor for " "scalar loops."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#af9f62350ccdebd24858be552f3fc051c">llvm::LoopVectorizationCostModel::selectInterleaveCount</a>.</p>

</div>
</div>

### ForceTargetMaxVectorInterleaveFactor {#ade5aad46b91dc51c831acf1e69ee9863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; ForceTargetMaxVectorInterleaveFactor("force-target-max-vector-interleave", cl::init(0), cl::Hidden, cl::desc("A flag that overrides the target's max interleave factor for " "vectorized loops."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#af9f62350ccdebd24858be552f3fc051c">llvm::LoopVectorizationCostModel::selectInterleaveCount</a>.</p>

</div>
</div>

### ForceTargetNumScalarRegs {#a62baadf3a5bf03eddf58bf048724acb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; ForceTargetNumScalarRegs("force-target-num-scalar-regs", cl::init(0), cl::Hidden, cl::desc("A flag that overrides the target's number of scalar registers."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#af9f62350ccdebd24858be552f3fc051c">llvm::LoopVectorizationCostModel::selectInterleaveCount</a>.</p>

</div>
</div>

### ForceTargetNumVectorRegs {#a7d952aa72676eecd8065aa2c29ea458c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; ForceTargetNumVectorRegs("force-target-num-vector-regs", cl::init(0), cl::Hidden, cl::desc("A flag that overrides the target's number of vector registers."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#af9f62350ccdebd24858be552f3fc051c">llvm::LoopVectorizationCostModel::selectInterleaveCount</a>.</p>

</div>
</div>

### ForceTargetSupportsScalableVectors {#a48035e22b43c905a2961c90e5470b2f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ForceTargetSupportsScalableVectors("force-target-supports-scalable-vectors", cl::init(false), cl::Hidden, cl::desc( "Pretend that scalable vectors are supported, even if the target does " "not support them. This flag should only be used for testing."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a2206e77c573f4947146faa681ea8855e">llvm::LoopVectorizationPlanner::planInVPlanNativePath</a>.</p>

</div>
</div>

### LLVMLoopVectorizeFollowupAll {#a3bf55ccbbeedcfb8cd2a1bd62c0ad91a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char LLVMLoopVectorizeFollowupAll[] = "llvm.loop.vectorize.followup_all"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> attribute names</p>


<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a> and <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### LLVMLoopVectorizeFollowupEpilogue {#aadedae9de069f3bcef6fa7a90ce4a630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char LLVMLoopVectorizeFollowupEpilogue[]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "llvm.loop.vectorize.followup_epilogue"
</div>
</dd>
</dl>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### LLVMLoopVectorizeFollowupVectorized {#a99050b417d193e1cc1117e5bbd4bfbce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char LLVMLoopVectorizeFollowupVectorized[]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "llvm.loop.vectorize.followup_vectorized"
</div>
</dd>
</dl>

<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>.</p>

</div>
</div>

### LoopVectorizeWithBlockFrequency {#aa5a50c0ac98e2ed63da85783ca102cf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; LoopVectorizeWithBlockFrequency("loop-vectorize-with-block-frequency", cl::init(true), cl::Hidden, cl::desc("Enable the use of the block frequency analysis to access PGO " "heuristics minimizing code growth in cold regions and being more " "aggressive in hot regions."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a84375e6536d9214c7895013078055aff">getSmallBestKnownTC</a>.</p>

</div>
</div>

### MaximizeBandwidth {#afe9b34c22ec9e2cc84d61d437f82936d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; MaximizeBandwidth("vectorizer-maximize-bandwidth", cl::init(false), cl::Hidden, cl::desc("Maximize bandwidth when selecting vectorization factor which " "will be determined by the smallest type in loop."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### MaxNestedScalarReductionIC {#ae75965df4671fa34c6ffc5a6e404843a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MaxNestedScalarReductionIC("max-nested-scalar-reduction-interleave", cl::init(2), cl::Hidden, cl::desc("The maximum interleave count to use when interleaving a scalar " "reduction in a nested loop."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#af9f62350ccdebd24858be552f3fc051c">llvm::LoopVectorizationCostModel::selectInterleaveCount</a>.</p>

</div>
</div>

### MemCheckBypassWeights {#a502070b20fa467fb54ba49d6736cf2d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t MemCheckBypassWeights[] = {1, 127}</td>
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



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks/#af15e3fefdfa2f5ea86ef5b8eacfa3517">anonymous{LoopVectorize.cpp}::GeneratedRTChecks::emitMemRuntimeChecks</a>.</p>

</div>
</div>

### MinItersBypassWeights {#a629884e9a99a9f49106db9e5e6252fcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t MinItersBypassWeights[] = {1, 127}</td>
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



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aeeb47f904372b9e25b9f7ba606158b25">llvm::EpilogueVectorizerMainLoop::emitIterationCountCheck</a> and <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a72c491cdf8cf0283d87008831431f917">llvm::InnerLoopVectorizer::emitIterationCountCheck</a>.</p>

</div>
</div>

### NumberOfStoresToPredicate {#ae11c08aa35785a118bda788836cab423}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; NumberOfStoresToPredicate("vectorize-num-stores-pred", cl::init(1), cl::Hidden, cl::desc("Max number of stores to be predicated behind an if."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of stores in a loop that are allowed to need predication.</p>

<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### PreferInLoopReductions {#a96ef6bd4742763bf1b85aaf1a4150620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PreferInLoopReductions("prefer-inloop-reductions", cl::init(false), cl::Hidden, cl::desc("Prefer in-loop vector reductions, " "overriding the targets preference."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a06f5d9725a2b1f7b06e8bf51f7d31417">llvm::LoopVectorizationCostModel::collectElementTypesForWidening</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a12d2850f420726c4acb262b626e95b7d">llvm::LoopVectorizationCostModel::collectInLoopReductions</a>.</p>

</div>
</div>

### PreferPredicatedReductionSelect {#a927ef1cfd7c981c5b9b9e8c67b1d13c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PreferPredicatedReductionSelect("prefer-predicated-reduction-select", cl::init(false), cl::Hidden, cl::desc( "Prefer predicating a reduction operation over an after loop select."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a23c31233960bfc62d1cc93bb4a5f5148">llvm::LoopVectorizationCostModel::usePredicatedReductionSelect</a>.</p>

</div>
</div>

### PreferPredicateOverEpilogue {#abe3c68238712d04bbe3a70f3a8f483f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; PreferPredicateTy::Option &gt; PreferPredicateOverEpilogue("prefer-predicate-over-epilogue", cl::init(PreferPredicateTy::ScalarEpilogue), cl::Hidden, cl::desc("Tail-folding and predication preferences over creating a scalar " "epilogue loop."), cl::values(clEnumValN(PreferPredicateTy::ScalarEpilogue, "scalar-epilogue", "Don't tail-predicate loops, create scalar epilogue"), clEnumValN(PreferPredicateTy::PredicateElseScalarEpilogue, "predicate-else-scalar-epilogue", "prefer tail-folding, create scalar epilogue if tail " "folding fails."), clEnumValN(PreferPredicateTy::PredicateOrDontVectorize, "predicate-dont-vectorize", "prefers tail-folding, don't attempt vectorization if " "tail-folding fails.")))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a8cde912cc23c18f493e4e5005c85748b">getScalarEpilogueLowering</a>.</p>

</div>
</div>

### SCEVCheckBypassWeights {#a968a5c2971ffa9e8ef81ff86eebaf514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t SCEVCheckBypassWeights[] = {1, 127}</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks/#aa55563b1c40f6c6c94622a87dd7b5dcb">anonymous{LoopVectorize.cpp}::GeneratedRTChecks::emitSCEVChecks</a>.</p>

</div>
</div>

### SmallLoopCost {#a71899f6c73fcc8e2fc977dadc1fb1520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; SmallLoopCost("small-loop-cost", cl::init(20), cl::Hidden, cl::desc( "The cost of a loop that is considered 'small' by the interleaver."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#af9f62350ccdebd24858be552f3fc051c">llvm::LoopVectorizationCostModel::selectInterleaveCount</a>.</p>

</div>
</div>

### TinyTripCountVectorThreshold {#a15320a2d7ced6e62766048ae7b6f8b13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; TinyTripCountVectorThreshold("vectorizer-min-trip-count", cl::init(16), cl::Hidden, cl::desc("Loops with a constant trip count that is smaller than this " "value are vectorized only if no scalar iteration overheads " "are incurred."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Loops with a known constant trip count below this number are vectorized only if no scalar iteration overheads are incurred.</p>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### UseWiderVFIfCallVariantsPresent {#a639c83322f3d5f0e24e9bde998a516fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UseWiderVFIfCallVariantsPresent("vectorizer-maximize-bandwidth-for-vector-calls", cl::init(true), cl::Hidden, cl::desc("Try wider VFs if they enable the use of vector variants"))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### VectorizeMemoryCheckThreshold {#a1293f02da7fffb33096a44f1b1768b3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; VectorizeMemoryCheckThreshold("vectorize-memory-check-threshold", cl::init(128), cl::Hidden, cl::desc("The maximum allowed number of runtime memory checks"))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a362f793f3254317c698e3560548788a5">areRuntimeChecksProfitable</a> and <a href="/web-llvm/docs/api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks/#aae3714d6fe11a1e8c559880caf67fbc7">anonymous{LoopVectorize.cpp}::GeneratedRTChecks::create</a>.</p>

</div>
</div>

### VerboseDebug {#a8eba8b6f7c3e69bf4d4efd92cd74b5a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char VerboseDebug[] = <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> "-verbose"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### VPlanBuildStressTest {#a9f30855a6efcd4a12875deb88880b510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; VPlanBuildStressTest("vplan-build-stress-test", cl::init(false), cl::Hidden, cl::desc( "Build VPlan for every supported loop nest in the function and bail " "out right after the build (stress test the VPlan H-CFG construction " "in the VPlan-native vectorization path)."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a00315ff11c9068aab97e5780bdfa5eef">collectSupportedLoops</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a2206e77c573f4947146faa681ea8855e">llvm::LoopVectorizationPlanner::planInVPlanNativePath</a> and <a href="#adeb41c907ebde15846bc643325909f95">processLoopInVPlanNativePath</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp/#a0eff4a8bccb143ae91e197e6a59d4692">LV_NAME</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### LV\_NAME {#a0eff4a8bccb143ae91e197e6a59d4692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LV_NAME&nbsp;&nbsp;&nbsp;"loop-vectorize"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
