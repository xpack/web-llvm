---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-loopfuse-cpp-/loopfuser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `LoopFuser` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{LoopFuse.cpp}::LoopFuser { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa45e97b4464564abfedc01683fcbef5d">LoopFuser</a> (LoopInfo &amp;LI, DominatorTree &amp;DT, DependenceInfo &amp;DI, ScalarEvolution &amp;SE, PostDominatorTree &amp;PDT, OptimizationRemarkEmitter &amp;ORE, const DataLayout &amp;DL, AssumptionCache &amp;AC, const TargetTransformInfo &amp;TTI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ce251220e1d2d9ea7bcc51ffa076a22">fuseLoops</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the main entry point for loop fusion. <a href="#a3ce251220e1d2d9ea7bcc51ffa076a22">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05c30accd81ec61fed4720ced9128ac4">isControlFlowEquivalent</a> (const FusionCandidate &amp;FC0, const FusionCandidate &amp;FC1) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if two fusion candidates are control flow equivalent. <a href="#a05c30accd81ec61fed4720ced9128ac4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dd2353449adf65146830ce2f61c9b63">collectFusionCandidates</a> (const LoopVector &amp;LV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterate over all loops in the given loop set and identify the loops that are eligible for fusion. <a href="#a5dd2353449adf65146830ce2f61c9b63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65800391c0022f4478c8dd488395bbee">isBeneficialFusion</a> (const FusionCandidate &amp;FC0, const FusionCandidate &amp;FC1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if it is beneficial to fuse two loops. <a href="#a65800391c0022f4478c8dd488395bbee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; bool, std::optional&lt; unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae676c45652dfb7654743768f0c9ffd7e">haveIdenticalTripCounts</a> (const FusionCandidate &amp;FC0, const FusionCandidate &amp;FC1) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if two fusion candidates have the same trip count (i.e., they execute the same number of iterations). <a href="#ae676c45652dfb7654743768f0c9ffd7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16115ad892134413541446df538312d6">peelFusionCandidate</a> (FusionCandidate &amp;FC0, const FusionCandidate &amp;FC1, unsigned PeelCount)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5711fd429c82c37cb28f6bb605263a27">fuseCandidates</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Walk each set of control flow equivalent fusion candidates and attempt to fuse them. <a href="#a5711fd429c82c37cb28f6bb605263a27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada8d91d8f45d5827318d829980b4c79c">canHoistInst</a> (Instruction &amp;I, const SmallVector&lt; Instruction *, 4 &gt; &amp;SafeToHoist, const SmallVector&lt; Instruction *, 4 &gt; &amp;NotHoisting, const FusionCandidate &amp;FC0) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11a7d20477f8a93854469f01d7e59d06">canSinkInst</a> (Instruction &amp;I, const FusionCandidate &amp;FC1) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5aff02cc01db07e09a9e7f6921c7a77">collectMovablePreheaderInsts</a> (const FusionCandidate &amp;FC0, const FusionCandidate &amp;FC1, SmallVector&lt; Instruction *, 4 &gt; &amp;SafeToHoist, SmallVector&lt; Instruction *, 4 &gt; &amp;SafeToSink) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect instructions in the <span class="doxyComputerOutput">FC1</span> Preheader that can be hoisted to the <span class="doxyComputerOutput">FC0</span> Preheader or sunk into the <span class="doxyComputerOutput">FC1</span> Body. <a href="#ad5aff02cc01db07e09a9e7f6921c7a77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a486f98a45bf025ab1cc6843a17f74f25">accessDiffIsPositive</a> (const Loop &amp;L0, const Loop &amp;L1, Instruction &amp;I0, Instruction &amp;I1, bool EqualIsInvalid)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return false if the access functions of <span class="doxyComputerOutput">I0</span> and <span class="doxyComputerOutput">I1</span> could cause a negative dependence. <a href="#a486f98a45bf025ab1cc6843a17f74f25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa849789733ae6ff21ad54a32643c279c">dependencesAllowFusion</a> (const FusionCandidate &amp;FC0, const FusionCandidate &amp;FC1, Instruction &amp;I0, Instruction &amp;I1, bool AnyDep, FusionDependenceAnalysisChoice DepChoice)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the dependences between <span class="doxyComputerOutput">I0</span> (in <span class="doxyComputerOutput">L0</span>) and <span class="doxyComputerOutput">I1</span> (in <span class="doxyComputerOutput">L1</span>) allow loop fusion of <span class="doxyComputerOutput">L0</span> and <span class="doxyComputerOutput">L1</span>. <a href="#aa849789733ae6ff21ad54a32643c279c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae97dd90c16efa665fda4a0599c5e16bf">dependencesAllowFusion</a> (const FusionCandidate &amp;FC0, const FusionCandidate &amp;FC1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a dependence check and return if <span class="doxyComputerOutput">FC0</span> and <span class="doxyComputerOutput">FC1</span> can be fused. <a href="#ae97dd90c16efa665fda4a0599c5e16bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3cc552627ead496e41304b6a7f97edf">isAdjacent</a> (const FusionCandidate &amp;FC0, const FusionCandidate &amp;FC1) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if two fusion candidates are adjacent in the CFG. <a href="#ab3cc552627ead496e41304b6a7f97edf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a653ebf5dcb5bce24fbf8cab96c808852">isEmptyPreheader</a> (const FusionCandidate &amp;FC) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28b92c16cacd13358da7c1378558dc6e">movePreheaderInsts</a> (const FusionCandidate &amp;FC0, const FusionCandidate &amp;FC1, SmallVector&lt; Instruction *, 4 &gt; &amp;HoistInsts, SmallVector&lt; Instruction *, 4 &gt; &amp;SinkInsts) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hoist <span class="doxyComputerOutput">FC1</span> Preheader instructions to <span class="doxyComputerOutput">FC0</span> Preheader and sink others into the body of <span class="doxyComputerOutput">FC1</span>. <a href="#a28b92c16cacd13358da7c1378558dc6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a067d7d87dd0e9626f6873a870f2669b7">haveIdenticalGuards</a> (const FusionCandidate &amp;FC0, const FusionCandidate &amp;FC1) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if two fusion candidates have identical guards. <a href="#a067d7d87dd0e9626f6873a870f2669b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dc1334be3c29eae4ec7eeca2d2fe36f">simplifyLatchBranch</a> (const FusionCandidate &amp;FC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Modify the latch branch of FC to be unconditional since successors of the branch are the same. <a href="#a5dc1334be3c29eae4ec7eeca2d2fe36f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac69be9427845cdd1454cf5bf9a16ae2">mergeLatch</a> (const FusionCandidate &amp;FC0, const FusionCandidate &amp;FC1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move instructions from FC0.Latch to FC1.Latch. <a href="#aac69be9427845cdd1454cf5bf9a16ae2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb3f820bc8f2f50d63c2754583bea46e">performFusion</a> (const FusionCandidate &amp;FC0, const FusionCandidate &amp;FC1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fuse two fusion candidates, creating a new fused loop. <a href="#afb3f820bc8f2f50d63c2754583bea46e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename RemarkKind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a11c1d751ede6c549a897fa4ccd9235af">reportLoopFusion</a> (const FusionCandidate &amp;FC0, const FusionCandidate &amp;FC1, llvm::Statistic &amp;Stat)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Report details on loop fusion opportunities. <a href="#a11c1d751ede6c549a897fa4ccd9235af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8825f42be24b54d0f7cebf785d797672">fuseGuardedLoops</a> (const FusionCandidate &amp;FC0, const FusionCandidate &amp;FC1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fuse two guarded fusion candidates, creating a new fused loop. <a href="#a8825f42be24b54d0f7cebf785d797672">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-loopfuse-cpp-/#a44fb48936a12b31b5ea5ee46a68bdb5b">FusionCandidateCollection</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb67d4180e9ffbe46338154766d69adb">FusionCandidates</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/loopdepthtree">LoopDepthTree</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a922b060aa7b90f5f261a408f7abda659">LDT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c7fb1efd47f4500d62bea6201db5be3">DTU</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa004002522f4dce712b1efba12c94e9d">LI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4f345716a2a27b9930dda34c3568e18">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dependenceinfo">DependenceInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ada457943fb5e6e57944850537e32a6">DI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39a5af40892a6284281472856c469ad0">SE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fcaacce9f4cf3b26830a29ca4bb1581">PDT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d5a40178b406bb47a7f64165b941ebc">ORE</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c733143a5438255a342fc4c4ffba327">AC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a506e174f2ce2840d603a77b4dbfdc617">TTI</a></td>
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


<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoopFuser() {#aa45e97b4464564abfedc01683fcbef5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopFuse.cpp}::LoopFuser::LoopFuser (<a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo">DependenceInfo</a> &amp; DI, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> &amp; PDT, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI)</td>
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



<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### fuseLoops() {#a3ce251220e1d2d9ea7bcc51ffa076a22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::LoopFuser::fuseLoops (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>This is the main entry point for loop fusion.</p>


<p>It will traverse the specified function and collect candidate loops to fuse, starting at the outermost nesting level and working inwards.</p>


<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loopfuse-cpp-/#a8186e787c97d26329af95c09c8a14949">anonymous{LoopFuse.cpp}::printLoopVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp/#ab393082393415266716b656010c0852a">VerboseFusionDebugging</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### accessDiffIsPositive() {#a486f98a45bf025ab1cc6843a17f74f25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::LoopFuser::accessDiffIsPositive (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L1, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I0, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I1, bool EqualIsInvalid)</td>
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

<p>Return false if the access functions of <span class="doxyComputerOutput">I0</span> and <span class="doxyComputerOutput">I1</span> could cause a negative dependence.</p>

<p>Definition at line 1270 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### canHoistInst() {#ada8d91d8f45d5827318d829980b4c79c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::LoopFuser::canHoistInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt; &amp; SafeToHoist, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt; &amp; NotHoisting, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC0)</td>
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



<p>Definition at line 1072 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### canSinkInst() {#a11a7d20477f8a93854469f01d7e59d06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::LoopFuser::canSinkInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC1)</td>
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



<p>Definition at line 1138 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### collectFusionCandidates() {#a5dd2353449adf65146830ce2f61c9b63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopFuse.cpp}::LoopFuser::collectFusionCandidates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-loopfuse-cpp-/#a9d85c23b999467640f95976e638879c5">LoopVector</a> &amp; LV)</td>
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

<p>Iterate over all loops in the given loop set and identify the loops that are eligible for fusion.</p>


<p>Place all eligible fusion candidates into Control Flow Equivalent sets, sorted by dominance.</p>


<p>Definition at line 667 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### collectMovablePreheaderInsts() {#ad5aff02cc01db07e09a9e7f6921c7a77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::LoopFuser::collectMovablePreheaderInsts (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC1, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt; &amp; SafeToHoist, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt; &amp; SafeToSink)</td>
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

<p>Collect instructions in the <span class="doxyComputerOutput">FC1</span> Preheader that can be hoisted to the <span class="doxyComputerOutput">FC0</span> Preheader or sunk into the <span class="doxyComputerOutput">FC1</span> Body.</p>

<p>Definition at line 1180 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### dependencesAllowFusion() {#aa849789733ae6ff21ad54a32643c279c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::LoopFuser::dependencesAllowFusion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC1, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I0, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I1, bool AnyDep, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp/#ab2ce98edbf00ac5582eba4ec2630b50b">FusionDependenceAnalysisChoice</a> DepChoice)</td>
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

<p>Return true if the dependences between <span class="doxyComputerOutput">I0</span> (in <span class="doxyComputerOutput">L0</span>) and <span class="doxyComputerOutput">I1</span> (in <span class="doxyComputerOutput">L1</span>) allow loop fusion of <span class="doxyComputerOutput">L0</span> and <span class="doxyComputerOutput">L1</span>.</p>


<p>The dependence analyses specified by <span class="doxyComputerOutput">DepChoice</span> are used to determine this.</p>


<p>Definition at line 1324 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### dependencesAllowFusion() {#ae97dd90c16efa665fda4a0599c5e16bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::LoopFuser::dependencesAllowFusion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC1)</td>
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

<p>Perform a dependence check and return if <span class="doxyComputerOutput">FC0</span> and <span class="doxyComputerOutput">FC1</span> can be fused.</p>

<p>Definition at line 1371 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### fuseCandidates() {#a5711fd429c82c37cb28f6bb605263a27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::LoopFuser::fuseCandidates ()</td>
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

<p>Walk each set of control flow equivalent fusion candidates and attempt to fuse them.</p>


<p>This does a single linear traversal of all candidates in the set. The conditions for legal fusion are checked at this point. If a pair of fusion candidates passes all legality checks, they are fused together and a new fusion candidate is created and added to the <a href="/web-llvm/docs/api/namespaces/anonymous-loopfuse-cpp-/#a8974eb1cd0d99da470c576c3b3388bf6">FusionCandidateSet</a>. The original fusion candidates are then removed, as they are no longer valid.</p>


<p>Definition at line 857 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### fuseGuardedLoops() {#a8825f42be24b54d0f7cebf785d797672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop * anonymous{LoopFuse.cpp}::LoopFuser::fuseGuardedLoops (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC1)</td>
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

<p>Fuse two guarded fusion candidates, creating a new fused loop.</p>


<p>Fusing guarded loops is handled much the same way as fusing non-guarded loops. The rewiring of the CFG is slightly different though, because of the presence of the guards around the loops and the exit blocks after the loop body. As such, the new loop is rewired as follows:</p>


<ol class="doxyList" type="1">
<li>Keep the guard branch from FC0 and use the non-loop block target from the FC1 guard branch.</li>
<li>Remove the exit block from FC0 (this exit block should be empty right now).</li>
<li>Remove the guard branch for FC1</li>
<li>Remove the preheader for FC1. The exit block successor for the latch of FC0 is updated to be the header of FC1 and the non-exit block successor of the latch of FC1 is updated to be the header of FC0, thus creating the fused loop.</li>
</ol>

<p>Definition at line 1815 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### haveIdenticalGuards() {#a067d7d87dd0e9626f6873a870f2669b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::LoopFuser::haveIdenticalGuards (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC1)</td>
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

<p>Determine if two fusion candidates have identical guards.</p>


<p>This method will determine if two fusion candidates have the same guards. The guards are considered the same if:</p>


<ol class="doxyList" type="1">
<li>The instructions to compute the condition used in the compare are identical.</li>
<li>The successors of the guard have the same flow into/around the loop. If the compare instructions are identical, then the first successor of the guard must go to the same place (either the preheader of the loop or the NonLoopBlock). In other words, the first successor of both loops must both go into the loop (i.e., the preheader) or go around the loop (i.e., the NonLoopBlock). The same must be true for the second successor.</li>
</ol>

<p>Definition at line 1497 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### haveIdenticalTripCounts() {#ae676c45652dfb7654743768f0c9ffd7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; bool, std::optional&lt; unsigned &gt; &gt; anonymous{LoopFuse.cpp}::LoopFuser::haveIdenticalTripCounts (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC1)</td>
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

<p>Determine if two fusion candidates have the same trip count (i.e., they execute the same number of iterations).</p>


<p>This function will return a pair of values. The first is a boolean, stating whether or not the two candidates are known at compile time to have the same TripCount. The second is the difference in the two TripCounts. This information can be used later to determine whether or not peeling can be performed on either one of the candidates.</p>


<p>Definition at line 727 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### isAdjacent() {#ab3cc552627ead496e41304b6a7f97edf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::LoopFuser::isAdjacent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC1)</td>
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

<p>Determine if two fusion candidates are adjacent in the CFG.</p>


<p>This method will determine if there are additional basic blocks in the CFG between the exit of <span class="doxyComputerOutput">FC0</span> and the entry of <span class="doxyComputerOutput">FC1</span>. If the two candidates are guarded loops, then it checks whether the non-loop successor of the <span class="doxyComputerOutput">FC0</span> guard branch is the entry block of <span class="doxyComputerOutput">FC1</span>. If not, then the loops are not adjacent. If the two candidates are not guarded loops, then it checks whether the exit block of <span class="doxyComputerOutput">FC0</span> is the preheader of <span class="doxyComputerOutput">FC1</span>.</p>


<p>Definition at line 1435 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### isBeneficialFusion() {#a65800391c0022f4478c8dd488395bbee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::LoopFuser::isBeneficialFusion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC1)</td>
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

<p>Determine if it is beneficial to fuse two loops.</p>


<p>For now, this method simply returns true because we want to fuse as much as possible (primarily to test the pass). This method will evolve, over time, to add heuristics for profitability of fusion.</p>


<p>Definition at line 713 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### isControlFlowEquivalent() {#a05c30accd81ec61fed4720ced9128ac4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::LoopFuser::isControlFlowEquivalent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC1)</td>
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

<p>Determine if two fusion candidates are control flow equivalent.</p>


<p>Two fusion candidates are control flow equivalent if when one executes, the other is guaranteed to execute. This is determined using dominators and post-dominators: if A dominates B and B post-dominates A then A and B are control-flow equivalent.</p>


<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### isEmptyPreheader() {#a653ebf5dcb5bce24fbf8cab96c808852}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::LoopFuser::isEmptyPreheader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC)</td>
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



<p>Definition at line 1444 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### mergeLatch() {#aac69be9427845cdd1454cf5bf9a16ae2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopFuse.cpp}::LoopFuser::mergeLatch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC1)</td>
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

<p>Move instructions from FC0.Latch to FC1.Latch.</p>


<p>If FC0.Latch has an unique successor, then merge FC0.Latch with its unique successor.</p>


<p>Definition at line 1534 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### movePreheaderInsts() {#a28b92c16cacd13358da7c1378558dc6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopFuse.cpp}::LoopFuser::movePreheaderInsts (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC1, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt; &amp; HoistInsts, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt; &amp; SinkInsts)</td>
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

<p>Hoist <span class="doxyComputerOutput">FC1</span> Preheader instructions to <span class="doxyComputerOutput">FC0</span> Preheader and sink others into the body of <span class="doxyComputerOutput">FC1</span>.</p>

<p>Definition at line 1450 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### peelFusionCandidate() {#a16115ad892134413541446df538312d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopFuse.cpp}::LoopFuser::peelFusionCandidate (<a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC1, unsigned PeelCount)</td>
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



<p>Definition at line 785 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### performFusion() {#afb3f820bc8f2f50d63c2754583bea46e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop * anonymous{LoopFuse.cpp}::LoopFuser::performFusion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC1)</td>
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

<p>Fuse two fusion candidates, creating a new fused loop.</p>


<p>This method contains the mechanics of fusing two loops, represented by <span class="doxyComputerOutput">FC0</span> and <span class="doxyComputerOutput">FC1</span>. It is assumed that <span class="doxyComputerOutput">FC0</span> dominates <span class="doxyComputerOutput">FC1</span> and <span class="doxyComputerOutput">FC1</span> postdominates <span class="doxyComputerOutput">FC0</span> (making them control flow equivalent). It also assumes that the other conditions for fusion have been met: adjacent, identical trip counts, and no negative distance dependencies exist that would prevent fusion. Thus, there is no checking for these conditions in this method.</p>


<p>Fusion is performed by rewiring the CFG to update successor blocks of the components of tho loop. Specifically, the following changes are done:</p>


<ol class="doxyList" type="1">
<li>The preheader of <span class="doxyComputerOutput">FC1</span> is removed as it is no longer necessary (because it is currently only a single statement block).</li>
<li>The latch of <span class="doxyComputerOutput">FC0</span> is modified to jump to the header of <span class="doxyComputerOutput">FC1</span>.</li>
<li>The latch of <span class="doxyComputerOutput">FC1</span> i modified to jump to the header of <span class="doxyComputerOutput">FC0</span>.</li>
<li>All blocks from <span class="doxyComputerOutput">FC1</span> are removed from FC1 and added to FC0.</li>
</ol>

<p>All of these modifications are done with dominator tree updates, thus keeping the dominator (and post dominator) information up-to-date.</p>


<p>This can be improved in the future by actually merging blocks during fusion. For example, the preheader of <span class="doxyComputerOutput">FC1</span> can be merged with the preheader of <span class="doxyComputerOutput">FC0</span>. This would allow loops with more than a single statement in the preheader to be fused. Similarly, the latch blocks of the two loops could also be fused into a single block. This will require analysis to prove it is safe to move the contents of the block past existing code, which currently has not been implemented.</p>


<p>Definition at line 1571 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### reportLoopFusion() {#a11c1d751ede6c549a897fa4ccd9235af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RemarkKind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopFuse.cpp}::LoopFuser::reportLoopFusion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC1, <a href="/web-llvm/docs/api/namespaces/llvm/#a6412c3ea6550f1aeab7571b6d38a2bf3">llvm::Statistic</a> &amp; Stat)</td>
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

<p>Report details on loop fusion opportunities.</p>


<p>This template function can be used to report both successful and missed loop fusion opportunities, based on the RemarkKind. The RemarkKind should be one of:</p>


<ul class="doxyList ">
<li><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed">OptimizationRemarkMissed</a> to report when loop fusion is unsuccessful given two valid fusion candidates.</li>
<li><a href="/web-llvm/docs/api/classes/llvm/optimizationremark">OptimizationRemark</a> to report successful fusion of two fusion candidates. The remarks will be printed using the form: &lt;path/filename&gt;:&lt;line number&gt;:&lt;column number&gt;: [&lt;function name&gt;]: &lt;Cand1 Preheader&gt; and &lt;Cand2 Preheader&gt;: &lt;Stat Description&gt;</li>
</ul>

<p>Definition at line 1784 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### simplifyLatchBranch() {#a5dc1334be3c29eae4ec7eeca2d2fe36f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopFuse.cpp}::LoopFuser::simplifyLatchBranch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; FC)</td>
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

<p>Modify the latch branch of FC to be unconditional since successors of the branch are the same.</p>

<p>Definition at line 1520 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AC {#a9c733143a5438255a342fc4c4ffba327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache&amp; anonymous{LoopFuse.cpp}::LoopFuser::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### DI {#a0ada457943fb5e6e57944850537e32a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DependenceInfo&amp; anonymous{LoopFuse.cpp}::LoopFuser::DI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### DT {#ab4f345716a2a27b9930dda34c3568e18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree&amp; anonymous{LoopFuse.cpp}::LoopFuser::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### DTU {#a1c7fb1efd47f4500d62bea6201db5be3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeUpdater anonymous{LoopFuse.cpp}::LoopFuser::DTU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### FusionCandidates {#abb67d4180e9ffbe46338154766d69adb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FusionCandidateCollection anonymous{LoopFuse.cpp}::LoopFuser::FusionCandidates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### LDT {#a922b060aa7b90f5f261a408f7abda659}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopDepthTree anonymous{LoopFuse.cpp}::LoopFuser::LDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### LI {#aa004002522f4dce712b1efba12c94e9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo&amp; anonymous{LoopFuse.cpp}::LoopFuser::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### ORE {#a1d5a40178b406bb47a7f64165b941ebc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter&amp; anonymous{LoopFuse.cpp}::LoopFuser::ORE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 574 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### PDT {#a2fcaacce9f4cf3b26830a29ca4bb1581}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PostDominatorTree&amp; anonymous{LoopFuse.cpp}::LoopFuser::PDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### SE {#a39a5af40892a6284281472856c469ad0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution&amp; anonymous{LoopFuse.cpp}::LoopFuser::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 572 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### TTI {#a506e174f2ce2840d603a77b4dbfdc617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetTransformInfo&amp; anonymous{LoopFuse.cpp}::LoopFuser::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
