---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `LoopUnrollAndJamPass.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollandjampass-h">llvm/Transforms/Scalar/LoopUnrollAndJamPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">llvm/ADT/PriorityWorklist.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">llvm/Analysis/AssumptionCache.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">llvm/Analysis/CodeMetrics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dependenceanalysis-h">llvm/Analysis/DependenceAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">llvm/Analysis/LoopAnalysisManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopnestanalysis-h">llvm/Analysis/LoopNestAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">llvm/Analysis/LoopPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">llvm/Analysis/OptimizationRemarkEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">llvm/Analysis/ScalarEvolution.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/looppassmanager-h">llvm/Transforms/Scalar/LoopPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/looppeel-h">llvm/Transforms/Utils/LoopPeel.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/looputils-h">llvm/Transforms/Utils/LoopUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/unrollloop-h">llvm/Transforms/Utils/UnrollLoop.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

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

</table>

## Functions Index

<table class="doxyMembersIndex">

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9919c2ab68b72db8776ce21a276a6ba6">hasAnyUnrollPragma</a> (const Loop *L, StringRef Prefix)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8d5b5da30c6c42adfd25e777e5c8c8b">hasUnrollAndJamEnablePragma</a> (const Loop *L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba61ac3543c189773a7afba5d9a6b333">unrollAndJamCountPragmaValue</a> (const Loop *L)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c7ad5d6975830f45286fdee3adf7bd5">getUnrollAndJammedLoopSize</a> (unsigned LoopSize, TargetTransformInfo::UnrollingPreferences &amp;UP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f16b49acc2669722d78d71f3163bbe6">computeUnrollAndJamCount</a> (Loop *L, Loop *SubLoop, const TargetTransformInfo &amp;TTI, DominatorTree &amp;DT, LoopInfo *LI, AssumptionCache *AC, ScalarEvolution &amp;SE, const SmallPtrSetImpl&lt; const Value * &gt; &amp;EphValues, OptimizationRemarkEmitter *ORE, unsigned OuterTripCount, unsigned OuterTripMultiple, const UnrollCostEstimator &amp;OuterUCE, unsigned InnerTripCount, unsigned InnerLoopSize, TargetTransformInfo::UnrollingPreferences &amp;UP, TargetTransformInfo::PeelingPreferences &amp;PP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a> (Loop *L, DominatorTree &amp;DT, LoopInfo *LI, ScalarEvolution &amp;SE, const TargetTransformInfo &amp;TTI, AssumptionCache &amp;AC, DependenceInfo &amp;DI, OptimizationRemarkEmitter &amp;ORE, int OptLevel)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0da6529029f6f71768e36765c25d54d5">tryToUnrollAndJamLoop</a> (LoopNest &amp;LN, DominatorTree &amp;DT, LoopInfo &amp;LI, ScalarEvolution &amp;SE, const TargetTransformInfo &amp;TTI, AssumptionCache &amp;AC, DependenceInfo &amp;DI, OptimizationRemarkEmitter &amp;ORE, int OptLevel, LPMUpdater &amp;U)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb4f1be6fbfffefe83da0d845258d454">LLVMLoopUnrollAndJamFollowupAll</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a061da973ca16e3e3f882b60545d8b535">LLVMLoopUnrollAndJamFollowupInner</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d1c960785118c886423d33b6488d452">LLVMLoopUnrollAndJamFollowupOuter</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ef63cf31b624021769be70754669c33">LLVMLoopUnrollAndJamFollowupRemainderInner</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16a3a2f3b98ed6aae1f30ca378df2e30">LLVMLoopUnrollAndJamFollowupRemainderOuter</a> = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c3c254927dbf3410e7eb7904c0d8363">AllowUnrollAndJam</a>("allow-unroll-and-jam", cl::Hidden, cl::desc("Allows loops to be unroll-and-jammed."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e4fe24f780802d9585a37a57baad388">UnrollAndJamCount</a>("unroll-and-jam-count", cl::Hidden, cl::desc("Use this unroll count for all loops including those with " "unroll_and_jam_count pragma values, for testing purposes"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad705de2594fdc07a954f5e47420aeef">UnrollAndJamThreshold</a>("unroll-and-jam-threshold", cl::init(60), cl::Hidden, cl::desc("Threshold to use for inner loop when doing unroll and jam."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3bc48b5f70282fa22b5be223bfbbef7">PragmaUnrollAndJamThreshold</a>("pragma-unroll-and-jam-threshold", cl::init(1024), cl::Hidden, cl::desc("Unrolled size limit for loops with an unroll_and_jam(full) or " "unroll_count pragma."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"loop-unroll-and-jam"</td>
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

### computeUnrollAndJamCount() {#a3f16b49acc2669722d78d71f3163bbe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool computeUnrollAndJamCount (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * SubLoop, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; EphValues, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE, unsigned OuterTripCount, unsigned OuterTripMultiple, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/unrollcostestimator">UnrollCostEstimator</a> &amp; OuterUCE, unsigned InnerTripCount, unsigned InnerLoopSize, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences">TargetTransformInfo::UnrollingPreferences</a> &amp; UP, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/peelingpreferences">TargetTransformInfo::PeelingPreferences</a> &amp; PP)</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#abb51de50739e767745339e9bb2aa31a4">llvm::TargetTransformInfo::UnrollingPreferences::AllowRemainder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a19cc5df79c699ab1e137118b8c472a9e">llvm::TargetTransformInfo::UnrollingPreferences::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a4217ba2e3d1295f8e9e6b49cef2a8b76">llvm::TargetTransformInfo::UnrollingPreferences::Force</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ac94e1f7398df9df2508957f58a82279a">llvm::LoopBase&lt; BlockT, LoopT &gt;::getBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/unrollcostestimator/#afcdc5884d4a759a519a679fc4293c0e0">llvm::UnrollCostEstimator::getRolledLoopSize</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a21d6ee82eed29080d911dbb548a8bb68">llvm::ScalarEvolution::getSCEVAtScope</a>, <a href="#a4c7ad5d6975830f45286fdee3adf7bd5">getUnrollAndJammedLoopSize</a>, <a href="#ac8d5b5da30c6c42adfd25e777e5c8c8b">hasUnrollAndJamEnablePragma</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5a19768af81df7e5fe571bc08dcd48b3">llvm::ScalarEvolution::isLoopInvariant</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aa3bc48b5f70282fa22b5be223bfbbef7">PragmaUnrollAndJamThreshold</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#ae31307b4efc5ce5311752041e7ff7cdc">llvm::TargetTransformInfo::UnrollingPreferences::Runtime</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a21e7febf468c370793f606da5cd0e6fe">llvm::TargetTransformInfo::UnrollingPreferences::Threshold</a>, <a href="#a5e4fe24f780802d9585a37a57baad388">UnrollAndJamCount</a>, <a href="#aba61ac3543c189773a7afba5d9a6b333">unrollAndJamCountPragmaValue</a> and <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a83395d28f9c1d9063aa6d9eb40dd2e7a">llvm::TargetTransformInfo::UnrollingPreferences::UnrollAndJamInnerLoopThreshold</a>.</p>


<p>Referenced by <a href="#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a>.</p>

</div>
</div>

### getUnrollAndJammedLoopSize() {#a4c7ad5d6975830f45286fdee3adf7bd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getUnrollAndJammedLoopSize (unsigned LoopSize, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences">TargetTransformInfo::UnrollingPreferences</a> &amp; UP)</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#acc2a7ecc1c0355035c91448ed850390f">llvm::TargetTransformInfo::UnrollingPreferences::BEInsns</a> and <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a19cc5df79c699ab1e137118b8c472a9e">llvm::TargetTransformInfo::UnrollingPreferences::Count</a>.</p>


<p>Referenced by <a href="#a3f16b49acc2669722d78d71f3163bbe6">computeUnrollAndJamCount</a>.</p>

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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#af455c80b53029287f35a7e3441eed512">llvm::GetUnrollMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ac94e9ab3d7f1774d783c54ca0bc9a538">hasRuntimeUnrollDisablePragma</a>, <a href="#ac8d5b5da30c6c42adfd25e777e5c8c8b">hasUnrollAndJamEnablePragma</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a4f99182190ead9c0b0ab19cf46019386">hasUnrollEnablePragma</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a47df9ca203042ef85332754224d91218">hasUnrollFullPragma</a>, <a href="#aba61ac3543c189773a7afba5d9a6b333">unrollAndJamCountPragmaValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a4f441813911ba060dc9457d93d289527">unrollCountPragmaValue</a>.</p>

</div>
</div>

### hasAnyUnrollPragma() {#a9919c2ab68b72db8776ce21a276a6ba6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasAnyUnrollPragma (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#ae44259d9edd71181ea8b89d18f27a967">llvm::MDString::getString</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>


<p>Referenced by <a href="#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a>.</p>

</div>
</div>

### hasUnrollAndJamEnablePragma() {#ac8d5b5da30c6c42adfd25e777e5c8c8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasUnrollAndJamEnablePragma (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a>.</p>


<p>Reference <a href="#a2ca734cad6f7bad1e0803fcafcd71825">getUnrollMetadataForLoop</a>.</p>


<p>Referenced by <a href="#a3f16b49acc2669722d78d71f3163bbe6">computeUnrollAndJamCount</a>.</p>

</div>
</div>

### tryToUnrollAndJamLoop() {#a671b52d0f3cddc29dcd1f5acfcd1e664}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopUnrollResult tryToUnrollAndJamLoop (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo">DependenceInfo</a> &amp; DI, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE, int OptLevel)</td>
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



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a>.</p>


<p>References <a href="#a4c3c254927dbf3410e7eb7904c0d8363">AllowUnrollAndJam</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#acc2a7ecc1c0355035c91448ed850390f">llvm::TargetTransformInfo::UnrollingPreferences::BEInsns</a>, <a href="/web-llvm/docs/api/classes/llvm/unrollcostestimator/#a8170d7668dde15a0223b899ffc3380e5">llvm::UnrollCostEstimator::canUnroll</a>, <a href="/web-llvm/docs/api/structs/llvm/codemetrics/#a7e174506b52ad46ea1f746a7f727d999">llvm::CodeMetrics::collectEphemeralValues</a>, <a href="#a3f16b49acc2669722d78d71f3163bbe6">computeUnrollAndJamCount</a>, <a href="/web-llvm/docs/api/classes/llvm/unrollcostestimator/#a38c330eeb22431f892ebe64f293fcab4">llvm::UnrollCostEstimator::Convergence</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a19cc5df79c699ab1e137118b8c472a9e">llvm::TargetTransformInfo::UnrollingPreferences::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c861ddf753ab3690437dceaadf5c7e1add722bdf19fff3e686f559790c6124d8">llvm::FullyUnrolled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6e86d0ac2e968adc60290ca52da02e42">llvm::gatherPeelingPreferences</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#afbcd78588d5235f99698b5c30f591382">llvm::Loop::getLoopID</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/unrollcostestimator/#afcdc5884d4a759a519a679fc4293c0e0">llvm::UnrollCostEstimator::getRolledLoopSize</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#abec0c616087c002528fcf80c6583eadd">llvm::ScalarEvolution::getSmallConstantTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a29ee697fe94374eae9689321e811f5e9">llvm::ScalarEvolution::getSmallConstantTripMultiple</a>, <a href="#a9919c2ab68b72db8776ce21a276a6ba6">hasAnyUnrollPragma</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7386405e9217844550433e1debb58ef7">llvm::hasUnrollAndJamTransformation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02e1ff75cab81386059f88d395054b1c">llvm::isSafeToUnrollAndJam</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#afb4f1be6fbfffefe83da0d845258d454">LLVMLoopUnrollAndJamFollowupAll</a>, <a href="#a061da973ca16e3e3f882b60545d8b535">LLVMLoopUnrollAndJamFollowupInner</a>, <a href="#a2d1c960785118c886423d33b6488d452">LLVMLoopUnrollAndJamFollowupOuter</a>, <a href="#a0ef63cf31b624021769be70754669c33">LLVMLoopUnrollAndJamFollowupRemainderInner</a>, <a href="#a16a3a2f3b98ed6aae1f30ca378df2e30">LLVMLoopUnrollAndJamFollowupRemainderOuter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a368216c9c116e3f30d8dd352ce1370fc">llvm::makeFollowupLoopID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a177a8536e97483817917ecaa40ca1b69a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/unrollcostestimator/#ab4438faa7fe9a577736755e75fe23f2b">llvm::UnrollCostEstimator::NumInlineCandidates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c861ddf753ab3690437dceaadf5c7e1a17f29ed218b7407dfd14e9a3ec8bd011">llvm::PartiallyUnrolled</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#adf4be757fa30ca7fe3e8b119438100f0">llvm::Loop::setLoopID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3e837c0d2a0521b4a4680071cac0dcbaa70bd8f3da4232ad809b2ffdcc1254bd">llvm::TM_Disable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3e837c0d2a0521b4a4680071cac0dcbaa1c649bc8228a2e36e04b8454851bfc5">llvm::TM_ForcedByUser</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c861ddf753ab3690437dceaadf5c7e1aac5e6ff0bb9cd22f9f55570e7b318c84">llvm::Unmodified</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#abbdf27d466fda1df8f9ce6f256026cce">llvm::TargetTransformInfo::UnrollingPreferences::UnrollAndJam</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a83395d28f9c1d9063aa6d9eb40dd2e7a">llvm::TargetTransformInfo::UnrollingPreferences::UnrollAndJamInnerLoopThreshold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>, <a href="#aad705de2594fdc07a954f5e47420aeef">UnrollAndJamThreshold</a> and <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#ac0713be3d080bf7e023ddb524f6eabe7">llvm::TargetTransformInfo::UnrollingPreferences::UnrollRemainder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopunrollandjampass/#aceae0aba9cc69bf89d3241d61190b9ec">llvm::LoopUnrollAndJamPass::run</a> and <a href="#a0da6529029f6f71768e36765c25d54d5">tryToUnrollAndJamLoop</a>.</p>

</div>
</div>

### tryToUnrollAndJamLoop() {#a0da6529029f6f71768e36765c25d54d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool tryToUnrollAndJamLoop (<a href="/web-llvm/docs/api/classes/llvm/loopnest">LoopNest</a> &amp; LN, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo">DependenceInfo</a> &amp; DI, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE, int OptLevel, <a href="/web-llvm/docs/api/classes/llvm/lpmupdater">LPMUpdater</a> &amp; U)</td>
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



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab7a106c600cf32852298d9041e8c8044">llvm::appendLoopsToWorklist</a>, <a href="/web-llvm/docs/api/classes/llvm/priorityworklist/#adc2ef5f0964becc28dfa58a7abc2f1e7">llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c861ddf753ab3690437dceaadf5c7e1add722bdf19fff3e686f559790c6124d8">llvm::FullyUnrolled</a>, <a href="/web-llvm/docs/api/classes/llvm/loopnest/#a2b8c1f7e00ee579ae55bad5bb1b44b31">llvm::LoopNest::getLoops</a>, <a href="/web-llvm/docs/api/classes/llvm/loopnest/#aeb26e0f4ad96cecfa73f0abbed21b61f">llvm::LoopNest::getOutermostLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp/#ada7c1594a393ede3ce32602d64d7ddb2">Loops</a>, <a href="/web-llvm/docs/api/classes/llvm/priorityworklist/#ab89ceb7695256590499de818b5360c54">llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::pop_back_val</a>, <a href="#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8c861ddf753ab3690437dceaadf5c7e1aac5e6ff0bb9cd22f9f55570e7b318c84">llvm::Unmodified</a>.</p>

</div>
</div>

### unrollAndJamCountPragmaValue() {#aba61ac3543c189773a7afba5d9a6b333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned unrollAndJamCountPragmaValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a> and <a href="#a2ca734cad6f7bad1e0803fcafcd71825">getUnrollMetadataForLoop</a>.</p>


<p>Referenced by <a href="#a3f16b49acc2669722d78d71f3163bbe6">computeUnrollAndJamCount</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AllowUnrollAndJam {#a4c3c254927dbf3410e7eb7904c0d8363}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; AllowUnrollAndJam("allow-unroll-and-jam", cl::Hidden, cl::desc("Allows loops to be unroll-and-jammed."))</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a>.</p>


<p>Referenced by <a href="#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a>.</p>

</div>
</div>

### LLVMLoopUnrollAndJamFollowupAll {#afb4f1be6fbfffefe83da0d845258d454}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* const LLVMLoopUnrollAndJamFollowupAll</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "llvm.loop.unroll_and_jam.followup_all"
</div>
</dd>
</dl>


<p><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> attribute names</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a>.</p>


<p>Referenced by <a href="#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a>.</p>

</div>
</div>

### LLVMLoopUnrollAndJamFollowupInner {#a061da973ca16e3e3f882b60545d8b535}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* const LLVMLoopUnrollAndJamFollowupInner</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "llvm.loop.unroll_and_jam.followup_inner"
</div>
</dd>
</dl>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a>.</p>


<p>Referenced by <a href="#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a>.</p>

</div>
</div>

### LLVMLoopUnrollAndJamFollowupOuter {#a2d1c960785118c886423d33b6488d452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* const LLVMLoopUnrollAndJamFollowupOuter</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "llvm.loop.unroll_and_jam.followup_outer"
</div>
</dd>
</dl>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a>.</p>


<p>Referenced by <a href="#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a>.</p>

</div>
</div>

### LLVMLoopUnrollAndJamFollowupRemainderInner {#a0ef63cf31b624021769be70754669c33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* const LLVMLoopUnrollAndJamFollowupRemainderInner</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "llvm.loop.unroll_and_jam.followup_remainder_inner"
</div>
</dd>
</dl>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a>.</p>


<p>Referenced by <a href="#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a>.</p>

</div>
</div>

### LLVMLoopUnrollAndJamFollowupRemainderOuter {#a16a3a2f3b98ed6aae1f30ca378df2e30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* const LLVMLoopUnrollAndJamFollowupRemainderOuter</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "llvm.loop.unroll_and_jam.followup_remainder_outer"
</div>
</dd>
</dl>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a>.</p>


<p>Referenced by <a href="#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a>.</p>

</div>
</div>

### PragmaUnrollAndJamThreshold {#aa3bc48b5f70282fa22b5be223bfbbef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; PragmaUnrollAndJamThreshold("pragma-unroll-and-jam-threshold", cl::init(1024), cl::Hidden, cl::desc("Unrolled size limit for loops with an unroll_and_jam(full) or " "unroll_count pragma."))</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a>.</p>


<p>Referenced by <a href="#a3f16b49acc2669722d78d71f3163bbe6">computeUnrollAndJamCount</a>.</p>

</div>
</div>

### UnrollAndJamCount {#a5e4fe24f780802d9585a37a57baad388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; UnrollAndJamCount("unroll-and-jam-count", cl::Hidden, cl::desc("Use this unroll count for all loops including those with " "unroll_and_jam_count pragma values, for testing purposes"))</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a>.</p>


<p>Referenced by <a href="#a3f16b49acc2669722d78d71f3163bbe6">computeUnrollAndJamCount</a>.</p>

</div>
</div>

### UnrollAndJamThreshold {#aad705de2594fdc07a954f5e47420aeef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; UnrollAndJamThreshold("unroll-and-jam-threshold", cl::init(60), cl::Hidden, cl::desc("Threshold to use for inner loop when doing unroll and jam."))</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a>.</p>


<p>Referenced by <a href="#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"loop-unroll-and-jam"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
