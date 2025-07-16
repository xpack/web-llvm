---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/targettransforminfo/unrollingpreferences
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `UnrollingPreferences` Struct Reference

<p>Parameters that control the generic loop unrolling transformation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::TargetTransformInfo::UnrollingPreferences { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21e7febf468c370793f606da5cd0e6fe">Threshold</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost threshold for the unrolled loop. <a href="#a21e7febf468c370793f606da5cd0e6fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63a7a13b9f772e6c656e94fb7e251d46">MaxPercentThresholdBoost</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If complete unrolling will reduce the cost of the loop, we will boost the Threshold by a certain percent to allow more aggressive complete unrolling. <a href="#a63a7a13b9f772e6c656e94fb7e251d46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9a7105299bd43b8b61c803f26e4a31b">OptSizeThreshold</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost threshold for the unrolled loop when optimizing for size (set to UINT_MAX to disable). <a href="#af9a7105299bd43b8b61c803f26e4a31b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae28e05c1aac288aa7e4a49d858b35c46">PartialThreshold</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost threshold for the unrolled loop, like Threshold, but used for partial/runtime unrolling (set to UINT_MAX to disable). <a href="#ae28e05c1aac288aa7e4a49d858b35c46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54b17420c467d2bb9edd2f79e54d2b6f">PartialOptSizeThreshold</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost threshold for the unrolled loop when optimizing for size, like OptSizeThreshold, but used for partial/runtime unrolling (set to UINT_MAX to disable). <a href="#a54b17420c467d2bb9edd2f79e54d2b6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19cc5df79c699ab1e137118b8c472a9e">Count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A forced unrolling factor (the number of concatenated bodies of the original loop in the unrolled loop body). <a href="#a19cc5df79c699ab1e137118b8c472a9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ebdb0ee911db5f4304bc6b92b0fed98">DefaultUnrollRuntimeCount</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default unroll count for loops with run-time trip count. <a href="#a5ebdb0ee911db5f4304bc6b92b0fed98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e3eba5cd35140f30d54eb8ef1fb0215">MaxCount</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc0d01a3d1fda6a5702b045b4bcfa56c">MaxUpperBound</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the maximum upper bound of trip count. <a href="#afc0d01a3d1fda6a5702b045b4bcfa56c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9d35cceaeac03c999997e0b4d3ebcb6">FullUnrollMaxCount</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the maximum unrolling factor for full unrolling. <a href="#ac9d35cceaeac03c999997e0b4d3ebcb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc2a7ecc1c0355035c91448ed850390f">BEInsns</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af01349dac5ea8d7fc1d5bedcc82a17b8">Partial</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow partial unrolling (unrolling of loops to expand the size of the loop body, not only to eliminate small constant-trip-count loops). <a href="#af01349dac5ea8d7fc1d5bedcc82a17b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae31307b4efc5ce5311752041e7ff7cdc">Runtime</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow runtime unrolling (unrolling of loops to expand the size of the loop body even when the number of loop iterations is not known at compile time). <a href="#ae31307b4efc5ce5311752041e7ff7cdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb51de50739e767745339e9bb2aa31a4">AllowRemainder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow generation of a loop remainder (extra iterations after unroll). <a href="#abb51de50739e767745339e9bb2aa31a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaa4eb31d0f39aa8c7ac8d081a39fec5">AllowExpensiveTripCount</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow emitting expensive instructions (such as divisions) when computing the trip count of a loop for runtime unrolling. <a href="#afaa4eb31d0f39aa8c7ac8d081a39fec5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4217ba2e3d1295f8e9e6b49cef2a8b76">Force</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply loop unroll on any kind of loop (mainly to loops that fail runtime unrolling). <a href="#a4217ba2e3d1295f8e9e6b49cef2a8b76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20a872a70cd97f4915f64fb9470c32d0">UpperBound</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow using trip count upper bound to unroll loops. <a href="#a20a872a70cd97f4915f64fb9470c32d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0713be3d080bf7e023ddb524f6eabe7">UnrollRemainder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow unrolling of all the iterations of the runtime loop remainder. <a href="#ac0713be3d080bf7e023ddb524f6eabe7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbdf27d466fda1df8f9ce6f256026cce">UnrollAndJam</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow unroll and jam. Used to enable unroll and jam for the target. <a href="#abbdf27d466fda1df8f9ce6f256026cce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83395d28f9c1d9063aa6d9eb40dd2e7a">UnrollAndJamInnerLoopThreshold</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Threshold for unroll and jam, for inner loop size. <a href="#a83395d28f9c1d9063aa6d9eb40dd2e7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab826709c552acec43be43f958b750105">MaxIterationsCountToAnalyze</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Don't allow loop unrolling to simulate more than this number of iterations when checking full unroll profitability. <a href="#ab826709c552acec43be43f958b750105">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d4cb9fb552657b2138b925b44315d21">UnrollVectorizedLoop</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Don't disable runtime unroll for the loops which were vectorized. <a href="#a5d4cb9fb552657b2138b925b44315d21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b1e34c2a72a2036de22e33ab5e88627">SCEVExpansionBudget</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Don't allow runtime unrolling if expanding the trip count takes more than SCEVExpansionBudget. <a href="#a7b1e34c2a72a2036de22e33ab5e88627">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75cdb3cba77995d63d624a2d632ed2e3">RuntimeUnrollMultiExit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow runtime unrolling multi-exit loops. <a href="#a75cdb3cba77995d63d624a2d632ed2e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Parameters that control the generic loop unrolling transformation.</p>

<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### AllowExpensiveTripCount {#afaa4eb31d0f39aa8c7ac8d081a39fec5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetTransformInfo::UnrollingPreferences::AllowExpensiveTripCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow emitting expensive instructions (such as divisions) when computing the trip count of a loop for runtime unrolling.</p>

<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a6801a1b19bf8856a09f270d85fe25e9b">llvm::PPCTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a99733e87982c752be1218b2d87e592b9">llvm::SystemZTTIImpl::getUnrollingPreferences</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a>.</p>

</div>
</div>

### AllowRemainder {#abb51de50739e767745339e9bb2aa31a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetTransformInfo::UnrollingPreferences::AllowRemainder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow generation of a loop remainder (extra iterations after unroll).</p>

<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a3f16b49acc2669722d78d71f3163bbe6">computeUnrollAndJamCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a8ee3ddc86c52a6b3ae82ccf0dcdd023d">shouldPartialUnroll</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#aa34e1c78e0b01952be32ffe53cbabe27">shouldPragmaUnroll</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a>.</p>

</div>
</div>

### BEInsns {#acc2a7ecc1c0355035c91448ed850390f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::UnrollingPreferences::BEInsns</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a946282957319b8c23ab9f169abb504c4">computeHeuristicUnrollFactor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a4c7ad5d6975830f45286fdee3adf7bd5">getUnrollAndJammedLoopSize</a>, <a href="/web-llvm/docs/api/classes/llvm/unrollcostestimator/#a5518251657ad8fecd98181257aab6e35">llvm::UnrollCostEstimator::getUnrolledLoopSize</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputtiimpl/#a99fc6c25163b324f8642658b54e77687">llvm::AMDGPUTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a1017f6873c8e5d75aa472aa3f06b48e3">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyttiimpl/#acaa381079caefe69853af81f25e67928">llvm::WebAssemblyTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a8ee3ddc86c52a6b3ae82ccf0dcdd023d">shouldPartialUnroll</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a>.</p>

</div>
</div>

### Count {#a19cc5df79c699ab1e137118b8c472a9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::UnrollingPreferences::Count</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A forced unrolling factor (the number of concatenated bodies of the original loop in the unrolled loop body).</p>


<p>When set to 0, the unrolling transformation will select an unrolling factor based on the current cost threshold and other factors.</p>


<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a946282957319b8c23ab9f169abb504c4">computeHeuristicUnrollFactor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a3f16b49acc2669722d78d71f3163bbe6">computeUnrollAndJamCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a4c7ad5d6975830f45286fdee3adf7bd5">getUnrollAndJammedLoopSize</a>, <a href="/web-llvm/docs/api/classes/llvm/unrollcostestimator/#a5518251657ad8fecd98181257aab6e35">llvm::UnrollCostEstimator::getUnrolledLoopSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a8ee3ddc86c52a6b3ae82ccf0dcdd023d">shouldPartialUnroll</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a>.</p>

</div>
</div>

### DefaultUnrollRuntimeCount {#a5ebdb0ee911db5f4304bc6b92b0fed98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::UnrollingPreferences::DefaultUnrollRuntimeCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Default unroll count for loops with run-time trip count.</p>

<p>Definition at line 572 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a78171da3a30a449d469ccebbff57760e">getAppleRuntimeUnrollPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#acfeb0fc40745a019c14fcfd5aadd9e70">llvm::AArch64TTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6c22989c03e43928e4b09cfa60a804f5">llvm::ARMTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a99733e87982c752be1218b2d87e592b9">llvm::SystemZTTIImpl::getUnrollingPreferences</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a8ee3ddc86c52a6b3ae82ccf0dcdd023d">shouldPartialUnroll</a>.</p>

</div>
</div>

### Force {#a4217ba2e3d1295f8e9e6b49cef2a8b76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetTransformInfo::UnrollingPreferences::Force</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply loop unroll on any kind of loop (mainly to loops that fail runtime unrolling).</p>

<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a946282957319b8c23ab9f169abb504c4">computeHeuristicUnrollFactor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a3f16b49acc2669722d78d71f3163bbe6">computeUnrollAndJamCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6c22989c03e43928e4b09cfa60a804f5">llvm::ARMTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a978825baa870839107dcb64531311bca">llvm::RISCVTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a99733e87982c752be1218b2d87e592b9">llvm::SystemZTTIImpl::getUnrollingPreferences</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a>.</p>

</div>
</div>

### FullUnrollMaxCount {#ac9d35cceaeac03c999997e0b4d3ebcb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::UnrollingPreferences::FullUnrollMaxCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the maximum unrolling factor for full unrolling.</p>


<p>Like MaxCount, but applies even if full unrolling is selected. This allows a target to fall back to Partial unrolling if full unrolling is above FullUnrollMaxCount.</p>


<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a99733e87982c752be1218b2d87e592b9">llvm::SystemZTTIImpl::getUnrollingPreferences</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a76ff47379fde965c509112d7a0c5c5bd">shouldFullUnroll</a>.</p>

</div>
</div>

### MaxCount {#a0e3eba5cd35140f30d54eb8ef1fb0215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::UnrollingPreferences::MaxCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a0ef183a0f2f6e678cc5f7223aca82535">getFalkorUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputtiimpl/#a99fc6c25163b324f8642658b54e77687">llvm::AMDGPUTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a99733e87982c752be1218b2d87e592b9">llvm::SystemZTTIImpl::getUnrollingPreferences</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a8ee3ddc86c52a6b3ae82ccf0dcdd023d">shouldPartialUnroll</a>.</p>

</div>
</div>

### MaxIterationsCountToAnalyze {#ab826709c552acec43be43f958b750105}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::UnrollingPreferences::MaxIterationsCountToAnalyze</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Don't allow loop unrolling to simulate more than this number of iterations when checking full unroll profitability.</p>

<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputtiimpl/#a99fc6c25163b324f8642658b54e77687">llvm::AMDGPUTTIImpl::getUnrollingPreferences</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a76ff47379fde965c509112d7a0c5c5bd">shouldFullUnroll</a>.</p>

</div>
</div>

### MaxPercentThresholdBoost {#a63a7a13b9f772e6c656e94fb7e251d46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::UnrollingPreferences::MaxPercentThresholdBoost</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If complete unrolling will reduce the cost of the loop, we will boost the Threshold by a certain percent to allow more aggressive complete unrolling.</p>


<p>This value provides the maximum boost percentage that we can apply to Threshold (The value should be no less than 100). BoostedThreshold = Threshold * min(RolledCost / UnrolledCost, MaxPercentThresholdBoost / 100) E.g. if complete unrolling reduces the loop execution time by 50% then we boost the threshold by the factor of 2x. If unrolling is not expected to reduce the running time, then we do not increase the threshold.</p>


<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a76ff47379fde965c509112d7a0c5c5bd">shouldFullUnroll</a>.</p>

</div>
</div>

### MaxUpperBound {#afc0d01a3d1fda6a5702b045b4bcfa56c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::UnrollingPreferences::MaxUpperBound</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the maximum upper bound of trip count.</p>


<p>Allowing the MaxUpperBound to be overrided by a target gives more flexiblity on certain cases. By default, MaxUpperBound uses UnrollMaxUpperBound which value is 8.</p>


<p>Definition at line 581 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#aa34e1c78e0b01952be32ffe53cbabe27">shouldPragmaUnroll</a>.</p>

</div>
</div>

### OptSizeThreshold {#af9a7105299bd43b8b61c803f26e4a31b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::UnrollingPreferences::OptSizeThreshold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost threshold for the unrolled loop when optimizing for size (set to UINT_MAX to disable).</p>

<p>Definition at line 558 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a946282957319b8c23ab9f169abb504c4">computeHeuristicUnrollFactor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6c22989c03e43928e4b09cfa60a804f5">llvm::ARMTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a1017f6873c8e5d75aa472aa3f06b48e3">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a978825baa870839107dcb64531311bca">llvm::RISCVTTIImpl::getUnrollingPreferences</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblyttiimpl/#acaa381079caefe69853af81f25e67928">llvm::WebAssemblyTTIImpl::getUnrollingPreferences</a>.</p>

</div>
</div>

### Partial {#af01349dac5ea8d7fc1d5bedcc82a17b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetTransformInfo::UnrollingPreferences::Partial</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow partial unrolling (unrolling of loops to expand the size of the loop body, not only to eliminate small constant-trip-count loops).</p>

<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#acfeb0fc40745a019c14fcfd5aadd9e70">llvm::AArch64TTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputtiimpl/#a99fc6c25163b324f8642658b54e77687">llvm::AMDGPUTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6c22989c03e43928e4b09cfa60a804f5">llvm::ARMTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a1017f6873c8e5d75aa472aa3f06b48e3">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#a2b6140cc716c4bf1dc53ea56de9ec18e">llvm::HexagonTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxttiimpl/#a71ea7d50adb4500b9ca52778c045e4fc">llvm::NVPTXTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a6801a1b19bf8856a09f270d85fe25e9b">llvm::PPCTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a978825baa870839107dcb64531311bca">llvm::RISCVTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a99733e87982c752be1218b2d87e592b9">llvm::SystemZTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyttiimpl/#acaa381079caefe69853af81f25e67928">llvm::WebAssemblyTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a8ee3ddc86c52a6b3ae82ccf0dcdd023d">shouldPartialUnroll</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a>.</p>

</div>
</div>

### PartialOptSizeThreshold {#a54b17420c467d2bb9edd2f79e54d2b6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::UnrollingPreferences::PartialOptSizeThreshold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost threshold for the unrolled loop when optimizing for size, like OptSizeThreshold, but used for partial/runtime unrolling (set to UINT_MAX to disable).</p>

<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a946282957319b8c23ab9f169abb504c4">computeHeuristicUnrollFactor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#acfeb0fc40745a019c14fcfd5aadd9e70">llvm::AArch64TTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6c22989c03e43928e4b09cfa60a804f5">llvm::ARMTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a1017f6873c8e5d75aa472aa3f06b48e3">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a978825baa870839107dcb64531311bca">llvm::RISCVTTIImpl::getUnrollingPreferences</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblyttiimpl/#acaa381079caefe69853af81f25e67928">llvm::WebAssemblyTTIImpl::getUnrollingPreferences</a>.</p>

</div>
</div>

### PartialThreshold {#ae28e05c1aac288aa7e4a49d858b35c46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::UnrollingPreferences::PartialThreshold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost threshold for the unrolled loop, like Threshold, but used for partial/runtime unrolling (set to UINT_MAX to disable).</p>

<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a946282957319b8c23ab9f169abb504c4">computeHeuristicUnrollFactor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#acfeb0fc40745a019c14fcfd5aadd9e70">llvm::AArch64TTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputtiimpl/#a99fc6c25163b324f8642658b54e77687">llvm::AMDGPUTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a1017f6873c8e5d75aa472aa3f06b48e3">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxttiimpl/#a71ea7d50adb4500b9ca52778c045e4fc">llvm::NVPTXTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a99733e87982c752be1218b2d87e592b9">llvm::SystemZTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyttiimpl/#acaa381079caefe69853af81f25e67928">llvm::WebAssemblyTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a8ee3ddc86c52a6b3ae82ccf0dcdd023d">shouldPartialUnroll</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a>.</p>

</div>
</div>

### Runtime {#ae31307b4efc5ce5311752041e7ff7cdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetTransformInfo::UnrollingPreferences::Runtime</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow runtime unrolling (unrolling of loops to expand the size of the loop body even when the number of loop iterations is not known at compile time).</p>

<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a3f16b49acc2669722d78d71f3163bbe6">computeUnrollAndJamCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a78171da3a30a449d469ccebbff57760e">getAppleRuntimeUnrollPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#acfeb0fc40745a019c14fcfd5aadd9e70">llvm::AArch64TTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputtiimpl/#a99fc6c25163b324f8642658b54e77687">llvm::AMDGPUTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6c22989c03e43928e4b09cfa60a804f5">llvm::ARMTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a1017f6873c8e5d75aa472aa3f06b48e3">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#a2b6140cc716c4bf1dc53ea56de9ec18e">llvm::HexagonTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxttiimpl/#a71ea7d50adb4500b9ca52778c045e4fc">llvm::NVPTXTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a6801a1b19bf8856a09f270d85fe25e9b">llvm::PPCTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a978825baa870839107dcb64531311bca">llvm::RISCVTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a99733e87982c752be1218b2d87e592b9">llvm::SystemZTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyttiimpl/#acaa381079caefe69853af81f25e67928">llvm::WebAssemblyTTIImpl::getUnrollingPreferences</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a>.</p>

</div>
</div>

### RuntimeUnrollMultiExit {#a75cdb3cba77995d63d624a2d632ed2e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetTransformInfo::UnrollingPreferences::RuntimeUnrollMultiExit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow runtime unrolling multi-exit loops.</p>


<p>Should only be set if the target determined that multi-exit unrolling is profitable for the loop. Fall back to the generic logic to determine whether multi-exit unrolling is profitable if set to false.</p>


<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a>.</p>

</div>
</div>

### SCEVExpansionBudget {#a7b1e34c2a72a2036de22e33ab5e88627}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::UnrollingPreferences::SCEVExpansionBudget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Don't allow runtime unrolling if expanding the trip count takes more than SCEVExpansionBudget.</p>

<p>Definition at line 624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a78171da3a30a449d469ccebbff57760e">getAppleRuntimeUnrollPreferences</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a>.</p>

</div>
</div>

### Threshold {#a21e7febf468c370793f606da5cd0e6fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::UnrollingPreferences::Threshold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost threshold for the unrolled loop.</p>


<p>Should be relative to the getInstructionCost values returned by this API, and the expectation is that the unrolled loop's instructions when run through that interface should not exceed this cost. However, this is only an estimate. Also, specific loops may be unrolled even with a cost above this threshold if deemed profitable. Set this to UINT_MAX to disable the loop body cost restriction.</p>


<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a946282957319b8c23ab9f169abb504c4">computeHeuristicUnrollFactor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a3f16b49acc2669722d78d71f3163bbe6">computeUnrollAndJamCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputtiimpl/#a99fc6c25163b324f8642658b54e77687">llvm::AMDGPUTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxttiimpl/#a71ea7d50adb4500b9ca52778c045e4fc">llvm::NVPTXTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a76ff47379fde965c509112d7a0c5c5bd">shouldFullUnroll</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#aa34e1c78e0b01952be32ffe53cbabe27">shouldPragmaUnroll</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a>.</p>

</div>
</div>

### UnrollAndJam {#abbdf27d466fda1df8f9ce6f256026cce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetTransformInfo::UnrollingPreferences::UnrollAndJam</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow unroll and jam. Used to enable unroll and jam for the target.</p>

<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#acfeb0fc40745a019c14fcfd5aadd9e70">llvm::AArch64TTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6c22989c03e43928e4b09cfa60a804f5">llvm::ARMTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a978825baa870839107dcb64531311bca">llvm::RISCVTTIImpl::getUnrollingPreferences</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a>.</p>

</div>
</div>

### UnrollAndJamInnerLoopThreshold {#a83395d28f9c1d9063aa6d9eb40dd2e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::UnrollingPreferences::UnrollAndJamInnerLoopThreshold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Threshold for unroll and jam, for inner loop size.</p>


<p>The 'Threshold' value above is used during unroll and jam for the outer loop size. This value is used in the same manner to limit the size of the inner loop.</p>


<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a3f16b49acc2669722d78d71f3163bbe6">computeUnrollAndJamCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#acfeb0fc40745a019c14fcfd5aadd9e70">llvm::AArch64TTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6c22989c03e43928e4b09cfa60a804f5">llvm::ARMTTIImpl::getUnrollingPreferences</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a>.</p>

</div>
</div>

### UnrollRemainder {#ac0713be3d080bf7e023ddb524f6eabe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetTransformInfo::UnrollingPreferences::UnrollRemainder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow unrolling of all the iterations of the runtime loop remainder.</p>

<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#acfeb0fc40745a019c14fcfd5aadd9e70">llvm::AArch64TTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6c22989c03e43928e4b09cfa60a804f5">llvm::ARMTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a978825baa870839107dcb64531311bca">llvm::RISCVTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a>.</p>

</div>
</div>

### UnrollVectorizedLoop {#a5d4cb9fb552657b2138b925b44315d21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetTransformInfo::UnrollingPreferences::UnrollVectorizedLoop = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Don't disable runtime unroll for the loops which were vectorized.</p>

<p>Definition at line 621 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputtiimpl/#a99fc6c25163b324f8642658b54e77687">llvm::AMDGPUTTIImpl::getUnrollingPreferences</a>.</p>

</div>
</div>

### UpperBound {#a20a872a70cd97f4915f64fb9470c32d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetTransformInfo::UnrollingPreferences::UpperBound</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow using trip count upper bound to unroll loops.</p>

<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd642fa74effc122158e6fb11da78600">llvm::gatherUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#acfeb0fc40745a019c14fcfd5aadd9e70">llvm::AArch64TTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6c22989c03e43928e4b09cfa60a804f5">llvm::ARMTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a1017f6873c8e5d75aa472aa3f06b48e3">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a978825baa870839107dcb64531311bca">llvm::RISCVTTIImpl::getUnrollingPreferences</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblyttiimpl/#acaa381079caefe69853af81f25e67928">llvm::WebAssemblyTTIImpl::getUnrollingPreferences</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
