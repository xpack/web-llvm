---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `LoopUnrollPass.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">llvm/Transforms/Scalar/LoopUnrollPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemapinfo-h">llvm/ADT/DenseMapInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/denseset-h">llvm/ADT/DenseSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">llvm/Analysis/AssumptionCache.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">llvm/Analysis/BlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">llvm/Analysis/CodeMetrics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">llvm/Analysis/LoopAnalysisManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">llvm/Analysis/LoopPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopunrollanalyzer-h">llvm/Analysis/LoopUnrollAnalyzer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">llvm/Analysis/MemorySSA.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">llvm/Analysis/OptimizationRemarkEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">llvm/Analysis/ProfileSummaryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">llvm/Analysis/ScalarEvolution.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cfg-h">llvm/IR/CFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/scalar-h">llvm/Transforms/Scalar.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/looppassmanager-h">llvm/Transforms/Scalar/LoopPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/utils-h">llvm/Transforms/Utils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/looppeel-h">llvm/Transforms/Utils/LoopPeel.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopsimplify-h">llvm/Transforms/Utils/LoopSimplify.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/looputils-h">llvm/Transforms/Utils/LoopUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">llvm/Transforms/Utils/ScalarEvolutionExpander.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sizeopts-h">llvm/Transforms/Utils/SizeOpts.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/unrollloop-h">llvm/Transforms/Utils/UnrollLoop.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;limits&gt;
#include &lt;optional&gt;
#include &lt;string&gt;
#include &lt;tuple&gt;
#include &lt;utility&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-loopunrollpass-cpp-">anonymous{LoopUnrollPass.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-loopunrollpass-cpp-/unrolledinststate">UnrolledInstState</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A struct to densely store the state of an instruction after unrolling at each iteration. <a href="/web-llvm/docs/api/structs/anonymous-loopunrollpass-cpp-/unrolledinststate/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-loopunrollpass-cpp-/unrolledinststatekeyinfo">UnrolledInstStateKeyInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hashing and equality testing for a set of the instruction states. <a href="/web-llvm/docs/api/structs/anonymous-loopunrollpass-cpp-/unrolledinststatekeyinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-loopunrollpass-cpp-/estimatedunrollcost">EstimatedUnrollCost</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-loopunrollpass-cpp-/pragmainfo">PragmaInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-loopunrollpass-cpp-/loopunroll">LoopUnroll</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; EstimatedUnrollCost &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76ff59dafad74689cfe1966b0ed9fa3c">analyzeLoopUnrollCost</a> (const Loop *L, unsigned TripCount, DominatorTree &amp;DT, ScalarEvolution &amp;SE, const SmallPtrSetImpl&lt; const Value * &gt; &amp;EphValues, const TargetTransformInfo &amp;TTI, unsigned MaxUnrolledLoopSize, unsigned MaxIterationsCountToAnalyze)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Figure out if the loop is worth full unrolling. <a href="#a76ff59dafad74689cfe1966b0ed9fa3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ca734cad6f7bad1e0803fcafcd71825">getUnrollMetadataForLoop</a> (const Loop *L, StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47df9ca203042ef85332754224d91218">hasUnrollFullPragma</a> (const Loop *L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f99182190ead9c0b0ab19cf46019386">hasUnrollEnablePragma</a> (const Loop *L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac94e9ab3d7f1774d783c54ca0bc9a538">hasRuntimeUnrollDisablePragma</a> (const Loop *L)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f441813911ba060dc9457d93d289527">unrollCountPragmaValue</a> (const Loop *L)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbbbc7e7d7a179db52a59d70392a1e9c">getFullUnrollBoostingFactor</a> (const EstimatedUnrollCost &amp;Cost, unsigned MaxPercentThresholdBoost)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa34e1c78e0b01952be32ffe53cbabe27">shouldPragmaUnroll</a> (Loop *L, const PragmaInfo &amp;PInfo, const unsigned TripMultiple, const unsigned TripCount, unsigned MaxTripCount, const UnrollCostEstimator UCE, const TargetTransformInfo::UnrollingPreferences &amp;UP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76ff47379fde965c509112d7a0c5c5bd">shouldFullUnroll</a> (Loop *L, const TargetTransformInfo &amp;TTI, DominatorTree &amp;DT, ScalarEvolution &amp;SE, const SmallPtrSetImpl&lt; const Value * &gt; &amp;EphValues, const unsigned FullUnrollTripCount, const UnrollCostEstimator UCE, const TargetTransformInfo::UnrollingPreferences &amp;UP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ee3ddc86c52a6b3ae82ccf0dcdd023d">shouldPartialUnroll</a> (const unsigned LoopSize, const unsigned TripCount, const UnrollCostEstimator UCE, const TargetTransformInfo::UnrollingPreferences &amp;UP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a8c861ddf753ab3690437dceaadf5c7e1">LoopUnrollResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a> (Loop *L, DominatorTree &amp;DT, LoopInfo *LI, ScalarEvolution &amp;SE, const TargetTransformInfo &amp;TTI, AssumptionCache &amp;AC, OptimizationRemarkEmitter &amp;ORE, BlockFrequencyInfo *BFI, ProfileSummaryInfo *PSI, bool PreserveLCSSA, int OptLevel, bool OnlyFullUnroll, bool OnlyWhenForced, bool ForgetAllSCEV, std::optional&lt; unsigned &gt; ProvidedCount, std::optional&lt; unsigned &gt; ProvidedThreshold, std::optional&lt; bool &gt; ProvidedAllowPartial, std::optional&lt; bool &gt; ProvidedRuntime, std::optional&lt; bool &gt; ProvidedUpperBound, std::optional&lt; bool &gt; ProvidedAllowPeeling, std::optional&lt; bool &gt; ProvidedAllowProfileBasedPeeling, std::optional&lt; unsigned &gt; ProvidedFullUnrollMaxCount, AAResults *AA=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5709dc220a64908090b46d1d1f6309b">UnrollThreshold</a>("unroll-threshold", cl::Hidden, cl::desc("The cost threshold for loop unrolling"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2da13c41bd3e916a0924c0c01b014451">UnrollOptSizeThreshold</a>("unroll-optsize-threshold", cl::init(0), cl::Hidden, cl::desc("The cost threshold for loop unrolling when optimizing for " "size"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e49d89441ec06d7187568cb0adcf1c2">UnrollPartialThreshold</a>("unroll-partial-threshold", cl::Hidden, cl::desc("The cost threshold for partial loop unrolling"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae467abf6e23fad8a3238fcadcd8d36d0">UnrollMaxPercentThresholdBoost</a>("unroll-max-percent-threshold-boost", cl::init(400), cl::Hidden, cl::desc("The maximum 'boost' (represented as a percentage >= 100) applied " "to the threshold when aggressively unrolling a loop due to the " "dynamic cost savings. If completely unrolling a loop will reduce " "the total runtime from X to Y, we boost the loop unroll " "threshold to DefaultThreshold*std::min(MaxPercentThresholdBoost, " "X/Y). This limit avoids excessive code bloat."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad737ffd92e44c2b3c20c996ec086cc7b">UnrollMaxIterationsCountToAnalyze</a>("unroll-max-iteration-count-to-analyze", cl::init(10), cl::Hidden, cl::desc("Don't allow loop unrolling to simulate more than this number of " "iterations when checking full unroll profitability"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0623a79f9be44774a206d71ccced388e">UnrollCount</a>("unroll-count", cl::Hidden, cl::desc("Use this unroll count for all loops including those with " "unroll_count pragma values, for testing purposes"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03384de1aaf68851bc758d5f93e70717">UnrollMaxCount</a>("unroll-max-count", cl::Hidden, cl::desc("Set the max unroll count for partial and runtime unrolling, for" "testing purposes"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dfbe5cfe55145abbfba19021cb34771">UnrollFullMaxCount</a>("unroll-full-max-count", cl::Hidden, cl::desc("Set the max unroll count for full unrolling, for testing purposes"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeef786995f3e797e000d856135b36b21">UnrollAllowPartial</a>("unroll-allow-partial", cl::Hidden, cl::desc("Allows loops to be partially unrolled until " "-unroll-threshold loop size is reached."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ea895a3cf11f08534d53045318df8f8">UnrollAllowRemainder</a>("unroll-allow-remainder", cl::Hidden, cl::desc("Allow generation of a loop remainder (extra iterations) " "when unrolling a loop."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5e974f53e2f109486e38068cb467273">UnrollRuntime</a>("unroll-runtime", cl::Hidden, cl::desc("Unroll loops with run-time trip counts"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64e96407611c9592708be5bebff9b529">UnrollMaxUpperBound</a>("unroll-max-upperbound", cl::init(8), cl::Hidden, cl::desc("The max of trip count upper bound that is considered in unrolling"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed926bb2602046eac2597c1a527e2872">PragmaUnrollThreshold</a>("pragma-unroll-threshold", cl::init(16 *1024), cl::Hidden, cl::desc("Unrolled size limit for loops with an unroll(full) or " "unroll_count pragma."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a154caa5c4e4265d0af53c109c7a36922">FlatLoopTripCountThreshold</a>("flat-loop-tripcount-threshold", cl::init(5), cl::Hidden, cl::desc("If the runtime tripcount for the loop is lower than the " "threshold, the loop is considered as flat and will be less " "aggressively unrolled."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ec8c2b4db0e83cb3937fdd1abdf5ae8">UnrollUnrollRemainder</a>("unroll-remainder", cl::Hidden, cl::desc("Allow the loop remainder to be unrolled."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab03face15c6ea88b8f87cd795f20b482">UnrollRevisitChildLoops</a>("unroll-revisit-child-loops", cl::Hidden, cl::desc("Enqueue and re-visit child loops in the loop PM after unrolling. " "This shouldn't typically be needed as child loops (or their " "clones) were already visited."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2c71f14ba4c76bf737efdb1ab90fcef">UnrollThresholdAggressive</a>("unroll-threshold-aggressive", cl::init(300), cl::Hidden, cl::desc("Threshold (max size of unrolled loop) to use in aggressive (O3) " "optimizations"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ffb0acc72a4cbe6d1a63b5ea8bcf153">UnrollThresholdDefault</a>("unroll-threshold-default", cl::init(150), cl::Hidden, cl::desc("Default threshold (max size of unrolled " "loop), used in all but O3 optimizations"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c3d66d6daf18cee04a20feac03ff3d4">PragmaUnrollFullMaxIterations</a>("pragma-unroll-full-max-iterations", cl::init(1 '000 '000), cl::Hidden, cl::desc("Maximum allowed iterations to unroll under pragma unroll full."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2e7d58f32215958839220d8ffbde13b">NoThreshold</a> = std::numeric_limits&lt;unsigned&gt;::max()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A magic value for use with the Threshold parameter to indicate that the loop unroll should be performed regardless of how much code expansion would result. <a href="#aa2e7d58f32215958839220d8ffbde13b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"loop-unroll"</td>
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

### analyzeLoopUnrollCost() {#a76ff59dafad74689cfe1966b0ed9fa3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; EstimatedUnrollCost &gt; analyzeLoopUnrollCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, unsigned TripCount, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; EphValues, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, unsigned MaxUnrolledLoopSize, unsigned MaxIterationsCountToAnalyze)</td>
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

<p>Figure out if the loop is worth full unrolling.</p>


<p>Complete loop unrolling can make some loads constant, and we need to know if that would expose any further optimization opportunities. This routine estimates this optimization. It computes cost of unrolled loop (UnrolledCost) and dynamic cost of the original loop (RolledDynamicCost). By dynamic cost we mean that we won't count costs of blocks that are known not to be executed (i.e. if we have a branch in the loop and we know that at the given iteration its condition would be resolved to true, we won't add up the cost of the 'false'-block).</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Optional value, holding the RolledDynamicCost and UnrolledCost. If the analysis failed (no benefits expected from the unrolling, or the loop is too big to analyze), the returned value is std::nullopt.</p></dd>
</dl>


<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adf4e7878fc0b3b8dcde545178564190d">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a9c50882381abd28ec385bec769b8928b">llvm::SetVector&lt; T, Vector, Set, N &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a53408c95a7bfb5443b43fb2134c3eb23">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ac178f4fc4e4a0642610c374256b9fb27">llvm::SetVector&lt; T, Vector, Set, N &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a8cd802dcaed35e1f28ea3cbe4af4eff5">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a56034ec173ce8feff8568c0e29462094">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aef9e9fcf4c5dfce90276ca16d91b8e46">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a9b642067999075ba996ecdee40b52b68">llvm::InstructionCost::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a548cfb9440f36ba67fc5566b8e967fc6">llvm::Function::hasMinSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#ae01c5ced9fe2fe50f421ae121483ef04">llvm::InstructionCost::isValid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0b2ca98dc28c61793ff5c90d23e5f14e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::lookup</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af9880d625c506aacc716ee1c9a29ff8b">llvm::SetVector&lt; T, Vector, Set, N &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba737cfc93e5a2ff961677d57186167e7c">llvm::TargetTransformInfo::TCK_CodeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba7f80055e1969cb850739546467460ad8">llvm::TargetTransformInfo::TCK_SizeAndLatency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a615619b0b2879029152b9a20e96624bc">llvm::transform</a> and <a href="/web-llvm/docs/api/classes/llvm/unrolledinstanalyzer/#ae02b1d8f7118696de142a7de27b59e67">llvm::UnrolledInstAnalyzer::visit</a>.</p>


<p>Referenced by <a href="#a76ff47379fde965c509112d7a0c5c5bd">shouldFullUnroll</a>.</p>

</div>
</div>

### getFullUnrollBoostingFactor() {#acbbbc7e7d7a179db52a59d70392a1e9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getFullUnrollBoostingFactor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> EstimatedUnrollCost &amp; Cost, unsigned MaxPercentThresholdBoost)</td>
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



<p>Definition at line 785 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="#a76ff47379fde965c509112d7a0c5c5bd">shouldFullUnroll</a>.</p>

</div>
</div>

### getUnrollMetadataForLoop() {#a2ca734cad6f7bad1e0803fcafcd71825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * getUnrollMetadataForLoop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 743 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#af455c80b53029287f35a7e3441eed512">llvm::GetUnrollMetadata</a>.</p>

</div>
</div>

### hasRuntimeUnrollDisablePragma() {#ac94e9ab3d7f1774d783c54ca0bc9a538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasRuntimeUnrollDisablePragma (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
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



<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a2ca734cad6f7bad1e0803fcafcd71825">getUnrollMetadataForLoop</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>.</p>

</div>
</div>

### hasUnrollEnablePragma() {#a4f99182190ead9c0b0ab19cf46019386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasUnrollEnablePragma (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
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



<p>Definition at line 756 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a2ca734cad6f7bad1e0803fcafcd71825">getUnrollMetadataForLoop</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>.</p>

</div>
</div>

### hasUnrollFullPragma() {#a47df9ca203042ef85332754224d91218}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasUnrollFullPragma (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
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



<p>Definition at line 750 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a2ca734cad6f7bad1e0803fcafcd71825">getUnrollMetadataForLoop</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>.</p>

</div>
</div>

### shouldFullUnroll() {#a76ff47379fde965c509112d7a0c5c5bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; shouldFullUnroll (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; EphValues, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned FullUnrollTripCount, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/unrollcostestimator">UnrollCostEstimator</a> UCE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences">TargetTransformInfo::UnrollingPreferences</a> &amp; UP)</td>
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



<p>Definition at line 838 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>References <a href="#a76ff59dafad74689cfe1966b0ed9fa3c">analyzeLoopUnrollCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#ac9d35cceaeac03c999997e0b4d3ebcb6">llvm::TargetTransformInfo::UnrollingPreferences::FullUnrollMaxCount</a>, <a href="#acbbbc7e7d7a179db52a59d70392a1e9c">getFullUnrollBoostingFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/unrollcostestimator/#a5518251657ad8fecd98181257aab6e35">llvm::UnrollCostEstimator::getUnrolledLoopSize</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#ab826709c552acec43be43f958b750105">llvm::TargetTransformInfo::UnrollingPreferences::MaxIterationsCountToAnalyze</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a63a7a13b9f772e6c656e94fb7e251d46">llvm::TargetTransformInfo::UnrollingPreferences::MaxPercentThresholdBoost</a> and <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a21e7febf468c370793f606da5cd0e6fe">llvm::TargetTransformInfo::UnrollingPreferences::Threshold</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>.</p>

</div>
</div>

### shouldPartialUnroll() {#a8ee3ddc86c52a6b3ae82ccf0dcdd023d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; shouldPartialUnroll (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned LoopSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned TripCount, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/unrollcostestimator">UnrollCostEstimator</a> UCE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences">TargetTransformInfo::UnrollingPreferences</a> &amp; UP)</td>
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



<p>Definition at line 869 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#abb51de50739e767745339e9bb2aa31a4">llvm::TargetTransformInfo::UnrollingPreferences::AllowRemainder</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#acc2a7ecc1c0355035c91448ed850390f">llvm::TargetTransformInfo::UnrollingPreferences::BEInsns</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a19cc5df79c699ab1e137118b8c472a9e">llvm::TargetTransformInfo::UnrollingPreferences::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a5ebdb0ee911db5f4304bc6b92b0fed98">llvm::TargetTransformInfo::UnrollingPreferences::DefaultUnrollRuntimeCount</a>, <a href="/web-llvm/docs/api/classes/llvm/unrollcostestimator/#a5518251657ad8fecd98181257aab6e35">llvm::UnrollCostEstimator::getUnrolledLoopSize</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a0e3eba5cd35140f30d54eb8ef1fb0215">llvm::TargetTransformInfo::UnrollingPreferences::MaxCount</a>, <a href="#aa2e7d58f32215958839220d8ffbde13b">NoThreshold</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#af01349dac5ea8d7fc1d5bedcc82a17b8">llvm::TargetTransformInfo::UnrollingPreferences::Partial</a> and <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#ae28e05c1aac288aa7e4a49d858b35c46">llvm::TargetTransformInfo::UnrollingPreferences::PartialThreshold</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>.</p>

</div>
</div>

### shouldPragmaUnroll() {#aa34e1c78e0b01952be32ffe53cbabe27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; shouldPragmaUnroll (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PragmaInfo &amp; PInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned TripMultiple, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned TripCount, unsigned MaxTripCount, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/unrollcostestimator">UnrollCostEstimator</a> UCE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences">TargetTransformInfo::UnrollingPreferences</a> &amp; UP)</td>
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



<p>Definition at line 798 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#abb51de50739e767745339e9bb2aa31a4">llvm::TargetTransformInfo::UnrollingPreferences::AllowRemainder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/unrollcostestimator/#a5518251657ad8fecd98181257aab6e35">llvm::UnrollCostEstimator::getUnrolledLoopSize</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#afc0d01a3d1fda6a5702b045b4bcfa56c">llvm::TargetTransformInfo::UnrollingPreferences::MaxUpperBound</a>, <a href="#a9c3d66d6daf18cee04a20feac03ff3d4">PragmaUnrollFullMaxIterations</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a21e7febf468c370793f606da5cd0e6fe">llvm::TargetTransformInfo::UnrollingPreferences::Threshold</a> and <a href="#a0623a79f9be44774a206d71ccced388e">UnrollCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>.</p>

</div>
</div>

### tryToUnrollLoop() {#ab6df82212b20d28e61ff9417744420ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopUnrollResult tryToUnrollLoop (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, bool PreserveLCSSA, int OptLevel, bool OnlyFullUnroll, bool OnlyWhenForced, bool ForgetAllSCEV, std::optional&lt; unsigned &gt; ProvidedCount, std::optional&lt; unsigned &gt; ProvidedThreshold, std::optional&lt; bool &gt; ProvidedAllowPartial, std::optional&lt; bool &gt; ProvidedRuntime, std::optional&lt; bool &gt; ProvidedUpperBound, std::optional&lt; bool &gt; ProvidedAllowPeeling, std::optional&lt; bool &gt; ProvidedAllowProfileBasedPeeling, std::optional&lt; unsigned &gt; ProvidedFullUnrollMaxCount, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> * AA=nullptr)</td>
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



<p>Definition at line 1158 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#afaa4eb31d0f39aa8c7ac8d081a39fec5">llvm::TargetTransformInfo::UnrollingPreferences::AllowExpensiveTripCount</a>, <a href="/web-llvm/docs/api/structs/llvm/unrollloopoptions/#a72709ed73867283dd45477f372c2f6b5">llvm::UnrollLoopOptions::AllowExpensiveTripCount</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#abb51de50739e767745339e9bb2aa31a4">llvm::TargetTransformInfo::UnrollingPreferences::AllowRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#acc2a7ecc1c0355035c91448ed850390f">llvm::TargetTransformInfo::UnrollingPreferences::BEInsns</a>, <a href="/web-llvm/docs/api/classes/llvm/unrollcostestimator/#a8170d7668dde15a0223b899ffc3380e5">llvm::UnrollCostEstimator::canUnroll</a>, <a href="/web-llvm/docs/api/structs/llvm/codemetrics/#a7e174506b52ad46ea1f746a7f727d999">llvm::CodeMetrics::collectEphemeralValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>, <a href="/web-llvm/docs/api/classes/llvm/unrollcostestimator/#a46822d4760e877c2f2c6f8198facc13b">llvm::UnrollCostEstimator::ConvergenceAllowsRuntime</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a19cc5df79c699ab1e137118b8c472a9e">llvm::TargetTransformInfo::UnrollingPreferences::Count</a>, <a href="/web-llvm/docs/api/structs/llvm/unrollloopoptions/#a6430dceedf36358dec517d3b7b33ff8a">llvm::UnrollLoopOptions::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter/#aae6a98aea85aa3af87357cc5448db499">llvm::OptimizationRemarkEmitter::emit</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a4217ba2e3d1295f8e9e6b49cef2a8b76">llvm::TargetTransformInfo::UnrollingPreferences::Force</a>, <a href="/web-llvm/docs/api/structs/llvm/unrollloopoptions/#a6dad0efbe15aa28f9e2a161d518a2443">llvm::UnrollLoopOptions::Force</a>, <a href="/web-llvm/docs/api/structs/llvm/unrollloopoptions/#a8cc60d0e22615680d0410f2e13501ac0">llvm::UnrollLoopOptions::ForgetAllSCEV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c861ddf753ab3690437dceaadf5c7e1add722bdf19fff3e686f559790c6124d8">llvm::FullyUnrolled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6e86d0ac2e968adc60290ca52da02e42">llvm::gatherPeelingPreferences</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ff3bf3190a09af37c0a2eee8b5a367c">llvm::getLoopConvergenceHeart</a>, <a href="/web-llvm/docs/api/classes/llvm/unrollcostestimator/#afcdc5884d4a759a519a679fc4293c0e0">llvm::UnrollCostEstimator::getRolledLoopSize</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a4c58444d7945f3d5eda96b9b4fb095b6">llvm::ScalarEvolution::getSmallConstantMaxTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#abec0c616087c002528fcf80c6583eadd">llvm::ScalarEvolution::getSmallConstantTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a29ee697fe94374eae9689321e811f5e9">llvm::ScalarEvolution::getSmallConstantTripMultiple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7386405e9217844550433e1debb58ef7">llvm::hasUnrollAndJamTransformation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a868145c1795173f9642f99c354f91a7d">llvm::hasUnrollTransformation</a>, <a href="/web-llvm/docs/api/structs/llvm/unrollloopoptions/#a3bb9090d262314058df58db624ddd9f7">llvm::UnrollLoopOptions::Heart</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a57a6829dad387e7075a6325e3ec6ace5">llvm::ScalarEvolution::isBackedgeTakenCountMaxOrZero</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9e3f06a77c19d1098df61d28499fcf3b">llvm::LLVMLoopUnrollFollowupAll</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac127703689b2c3771640f7fa800d61dc">llvm::LLVMLoopUnrollFollowupRemainder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac955f7402a9bb544b17efcff58f5a401">llvm::LLVMLoopUnrollFollowupUnrolled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a368216c9c116e3f30d8dd352ce1370fc">llvm::makeFollowupLoopID</a>, <a href="/web-llvm/docs/api/classes/llvm/unrollcostestimator/#ab4438faa7fe9a577736755e75fe23f2b">llvm::UnrollCostEstimator::NumInlineCandidates</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#af01349dac5ea8d7fc1d5bedcc82a17b8">llvm::TargetTransformInfo::UnrollingPreferences::Partial</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c861ddf753ab3690437dceaadf5c7e1a17f29ed218b7407dfd14e9a3ec8bd011">llvm::PartiallyUnrolled</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#ae28e05c1aac288aa7e4a49d858b35c46">llvm::TargetTransformInfo::UnrollingPreferences::PartialThreshold</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/peelingpreferences/#a93102207c7c9430df6ef02447446de9b">llvm::TargetTransformInfo::PeelingPreferences::PeelCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdb3eec2f46233c924c30c0838a3c8fe">llvm::peelLoop</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/peelingpreferences/#a89c02eecae37f89bf86f71336630858d">llvm::TargetTransformInfo::PeelingPreferences::PeelProfiledIterations</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#ae31307b4efc5ce5311752041e7ff7cdc">llvm::TargetTransformInfo::UnrollingPreferences::Runtime</a>, <a href="/web-llvm/docs/api/structs/llvm/unrollloopoptions/#a020442efb4f0bf105d9e189a6aa12bf4">llvm::UnrollLoopOptions::Runtime</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a75cdb3cba77995d63d624a2d632ed2e3">llvm::TargetTransformInfo::UnrollingPreferences::RuntimeUnrollMultiExit</a>, <a href="/web-llvm/docs/api/structs/llvm/unrollloopoptions/#a66d0e385f8fa2fd431707a6dc97376af">llvm::UnrollLoopOptions::RuntimeUnrollMultiExit</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a7b1e34c2a72a2036de22e33ab5e88627">llvm::TargetTransformInfo::UnrollingPreferences::SCEVExpansionBudget</a>, <a href="/web-llvm/docs/api/structs/llvm/unrollloopoptions/#af7463c2ecfc75a1ba12c7042b276a6bf">llvm::UnrollLoopOptions::SCEVExpansionBudget</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#adf4be757fa30ca7fe3e8b119438100f0">llvm::Loop::setLoopID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f380ccafb36b01f687b5507c39d3c6e">llvm::simplifyLoopAfterUnroll</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a21e7febf468c370793f606da5cd0e6fe">llvm::TargetTransformInfo::UnrollingPreferences::Threshold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3e837c0d2a0521b4a4680071cac0dcbaa70bd8f3da4232ad809b2ffdcc1254bd">llvm::TM_Disable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3e837c0d2a0521b4a4680071cac0dcbac3977ea14dd68d93d147c91a34de4bb3">llvm::TM_Enable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3e837c0d2a0521b4a4680071cac0dcbaa1c649bc8228a2e36e04b8454851bfc5">llvm::TM_ForcedByUser</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c861ddf753ab3690437dceaadf5c7e1aac5e6ff0bb9cd22f9f55570e7b318c84">llvm::Unmodified</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#ac0713be3d080bf7e023ddb524f6eabe7">llvm::TargetTransformInfo::UnrollingPreferences::UnrollRemainder</a> and <a href="/web-llvm/docs/api/structs/llvm/unrollloopoptions/#a6ba8279ac1a377af2a6e26eb0c007002">llvm::UnrollLoopOptions::UnrollRemainder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopfullunrollpass/#aacf97677dabaa7e583a690244bde44ea">llvm::LoopFullUnrollPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopunrollpass/#a62ed17cf8aa893362e6c3c1f6d8a0898">llvm::LoopUnrollPass::run</a> and <a href="/web-llvm/docs/api/classes/anonymous-loopunrollpass-cpp-/loopunroll/#a176b0f7a9dc90d996cae2767b3aea0ca">anonymous{LoopUnrollPass.cpp}::LoopUnroll::runOnLoop</a>.</p>

</div>
</div>

### unrollCountPragmaValue() {#a4f441813911ba060dc9457d93d289527}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned unrollCountPragmaValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
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



<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a2ca734cad6f7bad1e0803fcafcd71825">getUnrollMetadataForLoop</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### FlatLoopTripCountThreshold {#a154caa5c4e4265d0af53c109c7a36922}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; FlatLoopTripCountThreshold("flat-loop-tripcount-threshold", cl::init(5), cl::Hidden, cl::desc("If the runtime tripcount for the loop is lower than the " "threshold, the loop is considered as flat and will be less " "aggressively unrolled."))</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>.</p>

</div>
</div>

### NoThreshold {#aa2e7d58f32215958839220d8ffbde13b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned NoThreshold = std::numeric_limits&lt;unsigned&gt;::max()</td>
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

<p>A magic value for use with the Threshold parameter to indicate that the loop unroll should be performed regardless of how much code expansion would result.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a> and <a href="#a8ee3ddc86c52a6b3ae82ccf0dcdd023d">shouldPartialUnroll</a>.</p>

</div>
</div>

### PragmaUnrollFullMaxIterations {#a9c3d66d6daf18cee04a20feac03ff3d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; PragmaUnrollFullMaxIterations("pragma-unroll-full-max-iterations", cl::init(1 '000 '000), cl::Hidden, cl::desc("Maximum allowed iterations to unroll under pragma unroll full."))</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="#aa34e1c78e0b01952be32ffe53cbabe27">shouldPragmaUnroll</a>.</p>

</div>
</div>

### PragmaUnrollThreshold {#aed926bb2602046eac2597c1a527e2872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; PragmaUnrollThreshold("pragma-unroll-threshold", cl::init(16 *1024), cl::Hidden, cl::desc("Unrolled size limit for loops with an unroll(full) or " "unroll_count pragma."))</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>.</p>

</div>
</div>

### UnrollAllowPartial {#aeef786995f3e797e000d856135b36b21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UnrollAllowPartial("unroll-allow-partial", cl::Hidden, cl::desc("Allows loops to be partially unrolled until " "-unroll-threshold loop size is reached."))</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>.</p>

</div>
</div>

### UnrollAllowRemainder {#a7ea895a3cf11f08534d53045318df8f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UnrollAllowRemainder("unroll-allow-remainder", cl::Hidden, cl::desc("Allow generation of a loop remainder (extra iterations) " "when unrolling a loop."))</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>.</p>

</div>
</div>

### UnrollCount {#a0623a79f9be44774a206d71ccced388e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; UnrollCount("unroll-count", cl::Hidden, cl::desc("Use this unroll count for all loops including those with " "unroll_count pragma values, for testing purposes"))</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6c22989c03e43928e4b09cfa60a804f5">llvm::ARMTTIImpl::getUnrollingPreferences</a> and <a href="#aa34e1c78e0b01952be32ffe53cbabe27">shouldPragmaUnroll</a>.</p>

</div>
</div>

### UnrollFullMaxCount {#a5dfbe5cfe55145abbfba19021cb34771}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; UnrollFullMaxCount("unroll-full-max-count", cl::Hidden, cl::desc( "Set the max unroll count for full unrolling, for testing purposes"))</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>.</p>

</div>
</div>

### UnrollMaxCount {#a03384de1aaf68851bc758d5f93e70717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; UnrollMaxCount("unroll-max-count", cl::Hidden, cl::desc("Set the max unroll count for partial and runtime unrolling, for" "testing purposes"))</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>.</p>

</div>
</div>

### UnrollMaxIterationsCountToAnalyze {#ad737ffd92e44c2b3c20c996ec086cc7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; UnrollMaxIterationsCountToAnalyze("unroll-max-iteration-count-to-analyze", cl::init(10), cl::Hidden, cl::desc("Don't allow loop unrolling to simulate more than this number of " "iterations when checking full unroll profitability"))</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>.</p>

</div>
</div>

### UnrollMaxPercentThresholdBoost {#ae467abf6e23fad8a3238fcadcd8d36d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; UnrollMaxPercentThresholdBoost("unroll-max-percent-threshold-boost", cl::init(400), cl::Hidden, cl::desc("The maximum 'boost' (represented as a percentage &gt;= 100) applied " "to the threshold when aggressively unrolling a loop due to the " "dynamic cost savings. If completely unrolling a loop will reduce " "the total runtime from X to Y, we boost the loop unroll " "threshold to DefaultThreshold*std::min(MaxPercentThresholdBoost, " "X/Y). This limit avoids excessive code bloat."))</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>.</p>

</div>
</div>

### UnrollMaxUpperBound {#a64e96407611c9592708be5bebff9b529}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; UnrollMaxUpperBound("unroll-max-upperbound", cl::init(8), cl::Hidden, cl::desc( "The max of trip count upper bound that is considered in unrolling"))</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>.</p>

</div>
</div>

### UnrollOptSizeThreshold {#a2da13c41bd3e916a0924c0c01b014451}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; UnrollOptSizeThreshold("unroll-optsize-threshold", cl::init(0), cl::Hidden, cl::desc("The cost threshold for loop unrolling when optimizing for " "size"))</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>.</p>

</div>
</div>

### UnrollPartialThreshold {#a7e49d89441ec06d7187568cb0adcf1c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; UnrollPartialThreshold("unroll-partial-threshold", cl::Hidden, cl::desc("The cost threshold for partial loop unrolling"))</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>.</p>

</div>
</div>

### UnrollRevisitChildLoops {#ab03face15c6ea88b8f87cd795f20b482}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UnrollRevisitChildLoops("unroll-revisit-child-loops", cl::Hidden, cl::desc("Enqueue and re-visit child loops in the loop PM after unrolling. " "This shouldn't typically be needed as child loops (or their " "clones) were already visited."))</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopfullunrollpass/#aacf97677dabaa7e583a690244bde44ea">llvm::LoopFullUnrollPass::run</a>.</p>

</div>
</div>

### UnrollRuntime {#ab5e974f53e2f109486e38068cb467273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UnrollRuntime("unroll-runtime", cl::Hidden, cl::desc("Unroll loops with run-time trip counts"))</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>.</p>

</div>
</div>

### UnrollThreshold {#ab5709dc220a64908090b46d1d1f6309b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; UnrollThreshold("unroll-threshold", cl::Hidden, cl::desc("The cost threshold for loop unrolling"))</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>.</p>

</div>
</div>

### UnrollThresholdAggressive {#ad2c71f14ba4c76bf737efdb1ab90fcef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; UnrollThresholdAggressive("unroll-threshold-aggressive", cl::init(300), cl::Hidden, cl::desc("Threshold (max size of unrolled loop) to use in aggressive (O3) " "optimizations"))</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>.</p>

</div>
</div>

### UnrollThresholdDefault {#a0ffb0acc72a4cbe6d1a63b5ea8bcf153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; UnrollThresholdDefault("unroll-threshold-default", cl::init(150), cl::Hidden, cl::desc("Default threshold (max size of unrolled " "loop), used in all but O3 optimizations"))</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>.</p>

</div>
</div>

### UnrollUnrollRemainder {#a4ec8c2b4db0e83cb3937fdd1abdf5ae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UnrollUnrollRemainder("unroll-remainder", cl::Hidden, cl::desc("Allow the loop remainder to be unrolled."))</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"loop-unroll"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
