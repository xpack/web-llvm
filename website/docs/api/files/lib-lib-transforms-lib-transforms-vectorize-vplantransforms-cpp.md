---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `VPlanTransforms.cpp` File

<p>This file implements a set of utility <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> to <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> transformations. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplananalysis-h">VPlanAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplancfg-h">VPlanCFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplandominatortree-h">VPlanDominatorTree.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanpatternmatch-h">VPlanPatternMatch.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanutils-h">VPlanUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/postorderiterator-h">llvm/ADT/PostOrderIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/typeswitch-h">llvm/ADT/TypeSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">llvm/Analysis/IVDescriptors.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">llvm/Analysis/VectorUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1536feae2abb3570ac032768a53ddd00">sinkScalarOperands</a> (VPlan &amp;Plan)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae50d60234bec0a277dc087edad8901e1">getPredicatedMask</a> (VPRegionBlock *R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">R</span> is a region with a <a href="/web-llvm/docs/api/classes/llvm/vpbranchonmaskrecipe">VPBranchOnMaskRecipe</a> in the entry block, return the mask. <a href="#ae50d60234bec0a277dc087edad8901e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac99a45549c3cc25c2540f1bffd99944c">getPredicatedThenBlock</a> (VPRegionBlock *R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">R</span> is a triangle region, return the 'then' block of the triangle. <a href="#ac99a45549c3cc25c2540f1bffd99944c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b251734aba716917922f4ab216436c1">mergeReplicateRegionsIntoSuccessors</a> (VPlan &amp;Plan)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac967ad551e77554a15e20cac14877ac7">createReplicateRegion</a> (VPReplicateRecipe *PredRecipe, VPlan &amp;Plan)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e46200e5b228c903356e02904987051">addReplicateRegions</a> (VPlan &amp;Plan)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a528aff11b730581c8d7cfae0e5fb6254">mergeBlocksIntoPredecessors</a> (VPlan &amp;Plan)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove redundant VPBasicBlocks by merging them into their predecessor if the predecessor has a single successor. <a href="#a528aff11b730581c8d7cfae0e5fb6254">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ff7a57c84a06ee83b0a28763db85c3f">removeRedundantInductionCasts</a> (VPlan &amp;Plan)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove redundant casts of inductions. <a href="#a2ff7a57c84a06ee83b0a28763db85c3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefd03ef5fc77c520e27fe794e8ec93e9">removeRedundantCanonicalIVs</a> (VPlan &amp;Plan)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to replace VPWidenCanonicalIVRecipes with a widened canonical IV recipe, if it exists. <a href="#aefd03ef5fc77c520e27fe794e8ec93e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ba2ffb17342f2a0c54adaba2344cab0">isDeadRecipe</a> (VPRecipeBase &amp;R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">R</span> is dead and can be removed. <a href="#a6ba2ffb17342f2a0c54adaba2344cab0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe">VPScalarIVStepsRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c91ec836b0d1e340e17bff8eec31390">createScalarIVSteps</a> (VPlan &amp;Plan, InductionDescriptor::InductionKind Kind, Instruction::BinaryOps InductionOpcode, FPMathOperator *FPBinOp, Instruction *TruncI, VPValue *StartV, VPValue *Step, DebugLoc DL, VPBuilder &amp;Builder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa70c8f392e8295a96bfd493337e122fa">collectUsersRecursively</a> (VPValue *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bc9d4e47e8a41e60f4bedae712f0c03">legalizeAndOptimizeInductions</a> (VPlan &amp;Plan)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe">VPWidenPointerInductionRecipe</a>, by replacing it with a PtrAdd (IndStart, ScalarIVSteps (0, Step)) if only its scalar values are used, as <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe">VPWidenPointerInductionRecipe</a> will generate vectors only. <a href="#a6bc9d4e47e8a41e60f4bedae712f0c03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/vpwideninductionrecipe">VPWidenInductionRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa35433def455d3f76738769247678052">getOptimizableIVOf</a> (VPValue *VPV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">VPV</span> is an untruncated wide induction, either before or after the increment. <a href="#aa35433def455d3f76738769247678052">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a0202a443a527ba17fcd111497feb7d">removeRedundantExpandSCEVRecipes</a> (VPlan &amp;Plan)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove redundant EpxandSCEVRecipes in <span class="doxyComputerOutput">Plan's</span> entry block by replacing them with already existing recipes expanding the same <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression. <a href="#a8a0202a443a527ba17fcd111497feb7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5d43362c1fefd60d9bfcc1e28ba4688">recursivelyDeleteDeadRecipes</a> (VPValue *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a842c12e686e91a515dfd30a4bf70d740">simplifyRecipe</a> (VPRecipeBase &amp;R, VPTypeAnalysis &amp;TypeInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to simplify recipe <span class="doxyComputerOutput">R</span>. <a href="#a842c12e686e91a515dfd30a4bf70d740">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74cb3294789bc24526bcadbf6b466714">simplifyRecipes</a> (VPlan &amp;Plan, Type *CanonicalIVTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to simplify the recipes in <span class="doxyComputerOutput">Plan</span>. <a href="#a74cb3294789bc24526bcadbf6b466714">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a5b1db18197a65d0f6a487f2e236921">sinkRecurrenceUsersAfterPrevious</a> (VPFirstOrderRecurrencePHIRecipe *FOR, VPRecipeBase *Previous, VPDominatorTree &amp;VPDT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sink users of <span class="doxyComputerOutput">FOR</span> after the recipe defining the previous value <span class="doxyComputerOutput">Previous</span> of the recurrence. <a href="#a4a5b1db18197a65d0f6a487f2e236921">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9396319801f74828cfbd94177f38eabc">hoistPreviousBeforeFORUsers</a> (VPFirstOrderRecurrencePHIRecipe *FOR, VPRecipeBase *Previous, VPDominatorTree &amp;VPDT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to hoist <span class="doxyComputerOutput">Previous</span> and its operands before all users of <span class="doxyComputerOutput">FOR</span>. <a href="#a9396319801f74828cfbd94177f38eabc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd081c92500bd333555e7bd6102b4d3e">licm</a> (VPlan &amp;Plan)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move loop-invariant recipes out of the vector loop region in <span class="doxyComputerOutput">Plan</span>. <a href="#afd081c92500bd333555e7bd6102b4d3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/vpactivelanemaskphirecipe">VPActiveLaneMaskPHIRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a9cb34d61fa4930ff585649d1d5b2ed">addVPLaneMaskPhiAndUpdateExitBranch</a> (VPlan &amp;Plan, bool DataAndControlFlowWithoutRuntimeCheck)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d0c6052d21638f0a385e226db3bd92f">collectAllHeaderMasks</a> (VPlan &amp;Plan)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect all VPValues representing a header mask through the (ICMP_ULE, WideCanonicalIV, backedge-taken-count) pattern. <a href="#a8d0c6052d21638f0a385e226db3bd92f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0faf4b8ff1cf3306958d056dcb2fde2">createEVLRecipe</a> (VPValue *HeaderMask, VPRecipeBase &amp;CurRecipe, VPTypeAnalysis &amp;TypeInfo, VPValue &amp;AllOneMask, VPValue &amp;EVL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to convert <span class="doxyComputerOutput">CurRecipe</span> to a corresponding EVL-based recipe. <a href="#ad0faf4b8ff1cf3306958d056dcb2fde2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f39858b5d6d72b92c138916c64c90ba">transformRecipestoEVLRecipes</a> (VPlan &amp;Plan, VPValue &amp;EVL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace recipes with their EVL variants. <a href="#a5f39858b5d6d72b92c138916c64c90ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This file implements a set of utility <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> to <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> transformations.</p>

<div class="doxySectionDef">

## Functions

### addReplicateRegions() {#a6e46200e5b228c903356e02904987051}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addReplicateRegions (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a0360eea6cebcb1470f84b11f7ba51f16">llvm::VPBlockUtils::blocksOnly</a>, <a href="#ac967ad551e77554a15e20cac14877ac7">createReplicateRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a1c868dfd250ff9592c06dd61a7fb0bcf">llvm::VPlan::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a09de70cbaf2f15aa3b0697b5f378cc9d">llvm::VPBlockBase::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ad9d88ae321b98d8a3b7f394977ae6d7f">llvm::Value::hasName</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a2057d0749eedf6749f9e1cc6694eb1fd">llvm::VPBlockUtils::insertOnEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a9b75fcd70de89596b8f04904aa42e2cd">llvm::VPBasicBlock::splitAt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6c9ffe7979754415f4ca0d677174bc2">llvm::SplitBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a495c27cd70886cb8647df0ecdd9cc63d">llvm::vp_depth_first_deep</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a42d43068c576be2a1cd514f620246004">llvm::VPlanTransforms::createAndOptimizeReplicateRegions</a>.</p>

</div>
</div>

### addVPLaneMaskPhiAndUpdateExitBranch() {#a5a9cb34d61fa4930ff585649d1d5b2ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPActiveLaneMaskPHIRecipe * addVPLaneMaskPhiAndUpdateExitBranch (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, bool DataAndControlFlowWithoutRuntimeCheck)</td>
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



<p>Definition at line 1490 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2a79a53c84dbac24c496a4c9a6cf70596c">llvm::VPInstruction::ActiveLaneMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#af4a3b471097ab37b1672a0d88869ea51">llvm::VPUser::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2a0062eccdb4956531f7b6a3cf71c3320c">llvm::VPInstruction::BranchOnCond</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2add61254acc7408bb3c3bb55765481418">llvm::VPInstruction::CalculateTripCountMinusVF</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2ad271d9d05bf5644dfa1487b3fc42a131">llvm::VPInstruction::CanonicalIVIncrementForPart</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#accbbcc76f9eb947b3804ad96beb2bbd2">llvm::VPBuilder::createNaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#acf2cdb4ec71a22869d4c491e220d6f0b">llvm::VPBuilder::createNot</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#ab3b191f35221f351f77883447fef4019">llvm::VPBuilder::createOverflowingOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdda41105c5fe36c41d2246b18c1724fa2ff">llvm::DataAndControlFlowWithoutRuntimeCheck</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#aac9dfb61b37082dca00de284bb3309e8">llvm::VPRecipeBase::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad9053d6ed9627166c144b8895d1c1010">llvm::VPlan::getCanonicalIV</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a28da654f916bf44da5513b6f1788835c">llvm::VPBlockBase::getExitingBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#ac98e46fa8ff66b24ce678ddea88a23ac">llvm::VPBasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a2f5fc19caa67daeca8a1316c7e055e3c">llvm::VPlan::getTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#aee894572833ce02ad06c067d44f65b48">llvm::VPlan::getVectorPreheader</a> and <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#afc190306945dd17129c24477566099ce">llvm::VPBuilder::setInsertPoint</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae1d2d60cd9edd9f7ca98c50789747c95">llvm::VPlanTransforms::addActiveLaneMask</a>.</p>

</div>
</div>

### collectAllHeaderMasks() {#a8d0c6052d21638f0a385e226db3bd92f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; VPValue * &gt; collectAllHeaderMasks (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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

<p>Collect all VPValues representing a header mask through the (ICMP_ULE, WideCanonicalIV, backedge-taken-count) pattern.</p>


<p>TODO: Introduce explicit recipe for header-mask instead of searching for the header-mask pattern manually.</p>


<p>Definition at line 1565 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/iterator-range/#aa0344673da91896d39f1b35755ee5d4e">llvm::iterator_range&lt; IteratorT &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad9053d6ed9627166c144b8895d1c1010">llvm::VPlan::getCanonicalIV</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a96c706ef30193e00ac057bf24cf5719d">llvm::vputils::isHeaderMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a668c6f14a461ccf0ee11c9c7a076a901">llvm::VPBasicBlock::phis</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#af0932bb43954178036c87ea2ee5f112c">llvm::VPValue::users</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae1d2d60cd9edd9f7ca98c50789747c95">llvm::VPlanTransforms::addActiveLaneMask</a> and <a href="#a5f39858b5d6d72b92c138916c64c90ba">transformRecipestoEVLRecipes</a>.</p>

</div>
</div>

### collectUsersRecursively() {#aa70c8f392e8295a96bfd493337e122fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; VPUser * &gt; collectUsersRecursively (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * V)</td>
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



<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdef/#a5b7aa8b207f721cee2e80ebd99682563">llvm::VPDef::definedValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#a4e5b9edb51eec9dbca592075eb64dfcb">Users</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ace9e1e6e7295914973dec18350b382ca">llvm::VPlanTransforms::clearReductionWrapFlags</a>, <a href="#a6bc9d4e47e8a41e60f4bedae712f0c03">legalizeAndOptimizeInductions</a> and <a href="#a5f39858b5d6d72b92c138916c64c90ba">transformRecipestoEVLRecipes</a>.</p>

</div>
</div>

### createEVLRecipe() {#ad0faf4b8ff1cf3306958d056dcb2fde2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPRecipeBase * createEVLRecipe (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * HeaderMask, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> &amp; CurRecipe, <a href="/web-llvm/docs/api/classes/llvm/vptypeanalysis">VPTypeAnalysis</a> &amp; TypeInfo, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> &amp; AllOneMask, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> &amp; EVL)</td>
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

<p>Try to convert <span class="doxyComputerOutput">CurRecipe</span> to a corresponding EVL-based recipe.</p>


<p>Returns nullptr if no EVL-based recipe could be created. <span class="doxyComputerOutput">HeaderMask</span> Header Mask. <span class="doxyComputerOutput">CurRecipe</span> Recipe to be transform. <span class="doxyComputerOutput">TypeInfo</span> VPlan-based type analysis. <span class="doxyComputerOutput">AllOneMask</span> The vector mask parameter of vector-predication intrinsics. <span class="doxyComputerOutput">EVL</span> The explicit vector length parameter of vector-predication intrinsics.</p>


<p>Definition at line 1647 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/typeswitch/#a78c545287cbe57529ce7751e25c815a5">llvm::TypeSwitch&lt; T, ResultT &gt;::Case</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a733c4c530159a8b86223376c0696430e">llvm::VPRecipeBase::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#ad05203f409c9382a22a69ba01873f7fd">llvm::VPIntrinsic::getForIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a9c6880bafe83a767fa4a27bff91db390">llvm::VPIntrinsic::getForOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a6dab5a878379d5ee92940853d3feb53d">llvm::VPWidenMemoryRecipe::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a15c8605718d066667e36c9dc890ad40a">llvm::VPIntrinsic::getMaskParamPos</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a88782f243be6d837a183d7abfe7b1a3c">llvm::VPIntrinsic::getVectorLengthParamPos</a>, <a href="/web-llvm/docs/api/classes/llvm/vptypeanalysis/#aac3fb75b481d61e325b6d869d0f5f278">llvm::VPTypeAnalysis::inferScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5c88132322ca3f46f242f7c023a57010">llvm::Instruction::isBinaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae6249022aded13ad98775c11881bc117">llvm::Instruction::isUnaryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3ccd94f6a7507492b47c7351e3fb78c6">llvm::PatternMatch::m_Select</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#abce81cbd0e36ab26b74909f7d9135bf5">llvm::VPlanPatternMatch::m_VPValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a35fedf4db6d756bd82501607f93c1e79aab5fb650050f184fa7c19c26abde5226">llvm::Intrinsic::not_intrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a11d83265a9e4ff6c6ecd3cf222ad0208">llvm::VPUser::operands</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a5f39858b5d6d72b92c138916c64c90ba">transformRecipestoEVLRecipes</a>.</p>

</div>
</div>

### createReplicateRegion() {#ac967ad551e77554a15e20cac14877ac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPRegionBlock * createReplicateRegion (<a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe">VPReplicateRecipe</a> * PredRecipe, <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a40bc7fec35d7093efcdbadf566d6b5ee">llvm::VPBlockUtils::connectBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#aa1202b66a60b632b7adbdee13a20ad7e">llvm::VPlan::createVPBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a229a878bb15506314b99639e3d6dca41">llvm::VPlan::createVPRegionBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#aac9dfb61b37082dca00de284bb3309e8">llvm::VPRecipeBase::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#aec678e1ae306c61d14f856a3eb0d6bac">llvm::VPReplicateRecipe::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#ac3acda1aa682fbb8f8b95b0816eea879">llvm::VPValue::getNumUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/vpsingledefrecipe/#a12b12fbdf160f2cf70973e09adbf97d4">llvm::VPSingleDefRecipe::getUnderlyingInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a3a43b6445802190031bda62347e97453">llvm::VPBlockUtils::insertTwoBlocksAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#a8bb23947220a946748e3f1e6e6825155">llvm::VPReplicateRecipe::isUniform</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a6b1fcd7575eca39b654ed96202958e14">llvm::VPUser::op_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a634b1fa5443baf5d70ede2f674c46e54">llvm::VPUser::op_end</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#abaad22a81f7fa4ce5b60ec619ac14c37">llvm::VPValue::replaceAllUsesWith</a> and <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a19c3591dc1eeb5648552b33f70e04b65">llvm::VPUser::setOperand</a>.</p>


<p>Referenced by <a href="#a6e46200e5b228c903356e02904987051">addReplicateRegions</a>.</p>

</div>
</div>

### createScalarIVSteps() {#a3c91ec836b0d1e340e17bff8eec31390}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPScalarIVStepsRecipe * createScalarIVSteps (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#ac2d32589e2e153088b8a35db1a9eabcc">InductionDescriptor::InductionKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> InductionOpcode, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator">FPMathOperator</a> * FPBinOp, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * TruncI, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * StartV, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Step, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder">VPBuilder</a> &amp; Builder)</td>
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



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#a3d75b91bc4016f3078bab29877d8b68e">llvm::VPBuilder::createDerivedIV</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#a7651e884685052147f007e0e0fe0c774">llvm::VPBuilder::createScalarCast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#a9bdebe594005618b27255ea3ea2d2cdb">llvm::VPBuilder::createScalarIVSteps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad9053d6ed9627166c144b8895d1c1010">llvm::VPlan::getCanonicalIV</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#ac8744d8abf2a7ed185cc14f0a305cf8e">llvm::VPCanonicalIVPHIRecipe::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aeb7f03f5f68b01423a16a5dd469ddc71">llvm::VPBlockBase::getSingleHierarchicalPredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/vptypeanalysis/#aac3fb75b481d61e325b6d869d0f5f278">llvm::VPTypeAnalysis::inferScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a> and <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#afc190306945dd17129c24477566099ce">llvm::VPBuilder::setInsertPoint</a>.</p>


<p>Referenced by <a href="#a6bc9d4e47e8a41e60f4bedae712f0c03">legalizeAndOptimizeInductions</a>.</p>

</div>
</div>

### getOptimizableIVOf() {#aa35433def455d3f76738769247678052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPWidenInductionRecipe * getOptimizableIVOf (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * VPV)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">VPV</span> is an untruncated wide induction, either before or after the increment.</p>


<p>If so return the header IV (before the increment), otherwise return null.</p>


<p>Definition at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a3be8d7833df422f3538ddb13af69bd70">llvm::VPValue::getDefiningRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#ac6f0bd9ed63fe4a784697d73ae3b6fa0">llvm::VPValue::getLiveInIRValue</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#ac2d32589e2e153088b8a35db1a9eabccab61689ca7d0a024fc4ff52a74d691ae2">llvm::InductionDescriptor::IK_PtrInduction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#add6179d3564ac5ea4736366b93d23829">llvm::VPValue::isLiveIn</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#a5693223ba55481975ccee9dbaa716d6f">llvm::VPlanPatternMatch::m_Binary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#afd2774999cdb5e105b5de1910aadc21a">llvm::VPlanPatternMatch::m_c_Binary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#a48b3e852725673dc15409c7048803b14">llvm::VPlanPatternMatch::m_GetElementPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#abce81cbd0e36ab26b74909f7d9135bf5">llvm::VPlanPatternMatch::m_VPValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a3a573419fed83f23b6bf70ac6731dbfa">llvm::VPlanTransforms::optimizeInductionExitUsers</a>.</p>

</div>
</div>

### getPredicatedMask() {#ae50d60234bec0a277dc087edad8901e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * getPredicatedMask (<a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> * R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If <span class="doxyComputerOutput">R</span> is a region with a <a href="/web-llvm/docs/api/classes/llvm/vpbranchonmaskrecipe">VPBranchOnMaskRecipe</a> in the entry block, return the mask.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a4b251734aba716917922f4ab216436c1">mergeReplicateRegionsIntoSuccessors</a>.</p>

</div>
</div>

### getPredicatedThenBlock() {#ac99a45549c3cc25c2540f1bffd99944c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBasicBlock * getPredicatedThenBlock (<a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> * R)</td>
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

<p>If <span class="doxyComputerOutput">R</span> is a triangle region, return the 'then' block of the triangle.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#a4b251734aba716917922f4ab216436c1">mergeReplicateRegionsIntoSuccessors</a>.</p>

</div>
</div>

### hoistPreviousBeforeFORUsers() {#a9396319801f74828cfbd94177f38eabc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hoistPreviousBeforeFORUsers (<a href="/web-llvm/docs/api/structs/llvm/vpfirstorderrecurrencephirecipe">VPFirstOrderRecurrencePHIRecipe</a> * FOR, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> * Previous, <a href="/web-llvm/docs/api/classes/llvm/vpdominatortree">VPDominatorTree</a> &amp; VPDT)</td>
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

<p>Try to hoist <span class="doxyComputerOutput">Previous</span> and its operands before all users of <span class="doxyComputerOutput">FOR</span>.</p>

<p>Definition at line 1112 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a7ce23b4d08f0bd28ea1f676d527ae1d3">llvm::VPBasicBlock::getEnclosingLoopRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdef/#a31492b9d8412415c2dae85e33e2748fd">llvm::VPDef::getNumDefinedValues</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a09de70cbaf2f15aa3b0697b5f378cc9d">llvm::VPBlockBase::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a6c88376daf23b16ad26b7ac6c224d21e">llvm::VPRecipeBase::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdef/#a76a983b694720483a3dd9fe57314e39b">llvm::VPDef::getVPSingleValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a2408a88276528d80adefefa00995705a">llvm::VPRecipeBase::mayHaveSideEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a00bc7da040562d501bcc0e0635a2b53c">llvm::VPRecipeBase::mayReadFromMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a11d83265a9e4ff6c6ecd3cf222ad0208">llvm::VPUser::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdominatortree/#a044ef784dc6a77995842977a9956013f">llvm::VPDominatorTree::properlyDominates</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae64d6953a1334207d9e7d9cd2587ee9f">llvm::VPlanTransforms::adjustFixedOrderRecurrences</a>.</p>

</div>
</div>

### isDeadRecipe() {#a6ba2ffb17342f2a0c54adaba2344cab0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isDeadRecipe (<a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> &amp; R)</td>
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

<p>Returns true if <span class="doxyComputerOutput">R</span> is dead and can be removed.</p>

<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="#ab5d43362c1fefd60d9bfcc1e28ba4688">recursivelyDeleteDeadRecipes</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aaca9dd97d4c523d8c65274654abe4eb9">llvm::VPlanTransforms::removeDeadRecipes</a>.</p>

</div>
</div>

### legalizeAndOptimizeInductions() {#a6bc9d4e47e8a41e60f4bedae712f0c03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void legalizeAndOptimizeInductions (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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

<p>Legalize <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe">VPWidenPointerInductionRecipe</a>, by replacing it with a PtrAdd (IndStart, ScalarIVSteps (0, Step)) if only its scalar values are used, as <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe">VPWidenPointerInductionRecipe</a> will generate vectors only.</p>


<p>If some users require vectors while other require scalars, the scalar uses need to extract the scalars from the generated vectors (Note that this is different to how int/fp inductions are handled). Legalize extract-from-ends using uniform <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe">VPReplicateRecipe</a> of wide inductions to use regular <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe">VPReplicateRecipe</a>, so the correct end value is available. Also optimize <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe">VPWidenIntOrFpInductionRecipe</a>, if any of its users needs scalar values, by providing them scalar steps built on the canonical scalar IV and update the original IV's users. This is an optional optimization to reduce the needs of vector extracts.</p>


<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aa70c8f392e8295a96bfd493337e122fa">collectUsersRecursively</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#a4098fdd65180c4601108d663dc6618c9">llvm::VPBuilder::createPtrAdd</a>, <a href="#a3c91ec836b0d1e340e17bff8eec31390">createScalarIVSteps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a733c4c530159a8b86223376c0696430e">llvm::VPRecipeBase::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a72533c6b54501809628b9daee79b9d18">llvm::VPBasicBlock::getFirstNonPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ac38d49d70b5f78779e83abdf4dcb4be0">llvm::VPlan::getOrAddLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a18b96ac619241bd2248a355af718a192">llvm::VPlan::hasScalableVF</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a633dd97e642c10e8aa1dff2bd2874edb">llvm::VPlan::hasVF</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#ac2d32589e2e153088b8a35db1a9eabccaf0191e822c9708e106d7bb58aa9ec947">llvm::InductionDescriptor::IK_IntInduction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a002a77cdbc23293b8f7a8458ffd0f905">llvm::vputils::isUniformAfterVectorization</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a5e3c306be8d629a994f3644765421d5f">llvm::vputils::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a668c6f14a461ccf0ee11c9c7a076a901">llvm::VPBasicBlock::phis</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#abaad22a81f7fa4ce5b60ec619ac14c37">llvm::VPValue::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#a4e5b9edb51eec9dbca592075eb64dfcb">Users</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae3449b993cd1c459995c2fe13ef50892">llvm::VPlanTransforms::optimize</a>.</p>

</div>
</div>

### licm() {#afd081c92500bd333555e7bd6102b4d3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void licm (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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

<p>Move loop-invariant recipes out of the vector loop region in <span class="doxyComputerOutput">Plan</span>.</p>

<p>Definition at line 1275 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a0360eea6cebcb1470f84b11f7ba51f16">llvm::VPBlockUtils::blocksOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a4a7f4b8433e9a788149ffd94a0a07051">llvm::VPBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a1ae2cb3c63b4d67324ddc947fb9696fc">llvm::VPRegionBlock::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#aee894572833ce02ad06c067d44f65b48">llvm::VPlan::getVectorPreheader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4474bfb1e0ca062e5bfe2a35980e7d19">llvm::vp_depth_first_shallow</a>.</p>

</div>
</div>

### mergeBlocksIntoPredecessors() {#a528aff11b730581c8d7cfae0e5fb6254}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool mergeBlocksIntoPredecessors (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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

<p>Remove redundant VPBasicBlocks by merging them into their predecessor if the predecessor has a single successor.</p>

<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a0360eea6cebcb1470f84b11f7ba51f16">llvm::VPBlockUtils::blocksOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a40bc7fec35d7093efcdbadf566d6b5ee">llvm::VPBlockUtils::connectBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a61f1451694a3638db85170c7f55d5581">llvm::VPBlockUtils::disconnectBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a4a7f4b8433e9a788149ffd94a0a07051">llvm::VPBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a1c868dfd250ff9592c06dd61a7fb0bcf">llvm::VPlan::getEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a886094eaed7ce32029ea52a641142b88">llvm::to_vector</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a495c27cd70886cb8647df0ecdd9cc63d">llvm::vp_depth_first_deep</a>.</p>

</div>
</div>

### mergeReplicateRegionsIntoSuccessors() {#a4b251734aba716917922f4ab216436c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool mergeReplicateRegionsIntoSuccessors (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a0360eea6cebcb1470f84b11f7ba51f16">llvm::VPBlockUtils::blocksOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a40bc7fec35d7093efcdbadf566d6b5ee">llvm::VPBlockUtils::connectBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#af74676a3c7447be34bd2c1da76ec0c48">llvm::SmallPtrSetImpl&lt; PtrType &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a61f1451694a3638db85170c7f55d5581">llvm::VPBlockUtils::disconnectBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#af8a50544090e81ac83601aff8f4b0142">llvm::SmallPtrSetImplBase::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a1c868dfd250ff9592c06dd61a7fb0bcf">llvm::VPlan::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a72533c6b54501809628b9daee79b9d18">llvm::VPBasicBlock::getFirstNonPhi</a>, <a href="#ae50d60234bec0a277dc087edad8901e1">getPredicatedMask</a>, <a href="#ac99a45549c3cc25c2540f1bffd99944c">getPredicatedThenBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aebc0e1a3379ed4fd614889e24b8ea48c">llvm::VPBlockBase::getSingleSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#ae3773dd8f9c831f0dde091319b2ff7d0">llvm::VPValue::replaceUsesWithIf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a495c27cd70886cb8647df0ecdd9cc63d">llvm::vp_depth_first_deep</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a42d43068c576be2a1cd514f620246004">llvm::VPlanTransforms::createAndOptimizeReplicateRegions</a>.</p>

</div>
</div>

### recursivelyDeleteDeadRecipes() {#ab5d43362c1fefd60d9bfcc1e28ba4688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void recursivelyDeleteDeadRecipes (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * V)</td>
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



<p>Definition at line 814 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a3be8d7833df422f3538ddb13af69bd70">llvm::VPValue::getDefiningRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#a6ba2ffb17342f2a0c54adaba2344cab0">isDeadRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a842c12e686e91a515dfd30a4bf70d740">simplifyRecipe</a> and <a href="#a5f39858b5d6d72b92c138916c64c90ba">transformRecipestoEVLRecipes</a>.</p>

</div>
</div>

### removeRedundantCanonicalIVs() {#aefd03ef5fc77c520e27fe794e8ec93e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void removeRedundantCanonicalIVs (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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

<p>Try to replace VPWidenCanonicalIVRecipes with a widened canonical IV recipe, if it exists.</p>

<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#aac9dfb61b37082dca00de284bb3309e8">llvm::VPRecipeBase::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad9053d6ed9627166c144b8895d1c1010">llvm::VPlan::getCanonicalIV</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a5e3c306be8d629a994f3644765421d5f">llvm::vputils::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a668c6f14a461ccf0ee11c9c7a076a901">llvm::VPBasicBlock::phis</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#abaad22a81f7fa4ce5b60ec619ac14c37">llvm::VPValue::replaceAllUsesWith</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#af0932bb43954178036c87ea2ee5f112c">llvm::VPValue::users</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae3449b993cd1c459995c2fe13ef50892">llvm::VPlanTransforms::optimize</a>.</p>

</div>
</div>

### removeRedundantExpandSCEVRecipes() {#a8a0202a443a527ba17fcd111497feb7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void removeRedundantExpandSCEVRecipes (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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

<p>Remove redundant EpxandSCEVRecipes in <span class="doxyComputerOutput">Plan's</span> entry block by replacing them with already existing recipes expanding the same <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression.</p>

<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a1c868dfd250ff9592c06dd61a7fb0bcf">llvm::VPlan::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae3449b993cd1c459995c2fe13ef50892">llvm::VPlanTransforms::optimize</a>.</p>

</div>
</div>

### removeRedundantInductionCasts() {#a2ff7a57c84a06ee83b0a28763db85c3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void removeRedundantInductionCasts (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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

<p>Remove redundant casts of inductions.</p>


<p>Such redundant casts are casts of induction variables that can be ignored, because we already proved that the casted phi is equal to the uncasted phi in the vectorized loop. There is no need to vectorize the cast - the same value can be used for both the phi and casts in the vector loop.</p>


<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a668c6f14a461ccf0ee11c9c7a076a901">llvm::VPBasicBlock::phis</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#abaad22a81f7fa4ce5b60ec619ac14c37">llvm::VPValue::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#af0932bb43954178036c87ea2ee5f112c">llvm::VPValue::users</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae3449b993cd1c459995c2fe13ef50892">llvm::VPlanTransforms::optimize</a>.</p>

</div>
</div>

### simplifyRecipe() {#a842c12e686e91a515dfd30a4bf70d740}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void simplifyRecipe (<a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> &amp; R, <a href="/web-llvm/docs/api/classes/llvm/vptypeanalysis">VPTypeAnalysis</a> &amp; TypeInfo)</td>
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

<p>Try to simplify recipe <span class="doxyComputerOutput">R</span>.</p>

<p>Definition at line 834 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#abf73a826b5d6f739eb4af48ddf14c5b4">llvm::SmallPtrSetImpl&lt; PtrType &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/vptypeanalysis/#aac3fb75b481d61e325b6d869d0f5f278">llvm::VPTypeAnalysis::inferScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#a27cb031d5b7fd1ff6f33a45d823866d7">llvm::VPlanPatternMatch::m_c_BinaryOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af10813bee5ce9c7b412807aac434deef">llvm::PatternMatch::m_c_Mul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#a8a1bf026bda785519069e37d7a7de192">llvm::VPlanPatternMatch::m_DerivedIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#a857db44d5e19818efc62c9ed25e6b4ea">llvm::VPlanPatternMatch::m_False</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#acf8c16eed89e5ee1a10b6dfc08a33b3a">llvm::PatternMatch::m_LogicalAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae5cf2b09af0c75d08cf9e5e8f2818a66">llvm::PatternMatch::m_SExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2471be3f1b50002f54bf45c590d8d41b">llvm::PatternMatch::m_SpecificInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1b8442c10c9ed6e0e07160b54541450e">llvm::PatternMatch::m_Trunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#abce81cbd0e36ab26b74909f7d9135bf5">llvm::VPlanPatternMatch::m_VPValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab9dc78a306f2befc7dc7f1da8c9eaca2">llvm::PatternMatch::m_ZExtOrSExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#ab5d43362c1fefd60d9bfcc1e28ba4688">recursivelyDeleteDeadRecipes</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#abaad22a81f7fa4ce5b60ec619ac14c37">llvm::VPValue::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a0e1c3175b0ac22fe3853651c28e1ecb8">llvm::SmallPtrSetImplBase::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="#a74cb3294789bc24526bcadbf6b466714">simplifyRecipes</a>.</p>

</div>
</div>

### simplifyRecipes() {#a74cb3294789bc24526bcadbf6b466714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void simplifyRecipes (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * CanonicalIVTy)</td>
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

<p>Try to simplify the recipes in <span class="doxyComputerOutput">Plan</span>.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <span class="doxyComputerOutput">CanonicalIVTy</span> as type for all un-typed live-ins in <a href="/web-llvm/docs/api/classes/llvm/vptypeanalysis">VPTypeAnalysis</a>.</p>


<p>Definition at line 967 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a0360eea6cebcb1470f84b11f7ba51f16">llvm::VPBlockUtils::blocksOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a1c868dfd250ff9592c06dd61a7fb0bcf">llvm::VPlan::getEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a> and <a href="#a842c12e686e91a515dfd30a4bf70d740">simplifyRecipe</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae3449b993cd1c459995c2fe13ef50892">llvm::VPlanTransforms::optimize</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a>.</p>

</div>
</div>

### sinkRecurrenceUsersAfterPrevious() {#a4a5b1db18197a65d0f6a487f2e236921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool sinkRecurrenceUsersAfterPrevious (<a href="/web-llvm/docs/api/structs/llvm/vpfirstorderrecurrencephirecipe">VPFirstOrderRecurrencePHIRecipe</a> * FOR, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> * Previous, <a href="/web-llvm/docs/api/classes/llvm/vpdominatortree">VPDominatorTree</a> &amp; VPDT)</td>
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

<p>Sink users of <span class="doxyComputerOutput">FOR</span> after the recipe defining the previous value <span class="doxyComputerOutput">Previous</span> of the recurrence.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if all users of <span class="doxyComputerOutput">FOR</span> could be re-arranged as needed or false if it is not possible.</p></dd>
</dl>


<p>Definition at line 1057 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdef/#a31492b9d8412415c2dae85e33e2748fd">llvm::VPDef::getNumDefinedValues</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdef/#a76a983b694720483a3dd9fe57314e39b">llvm::VPDef::getVPSingleValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdominatortree/#a044ef784dc6a77995842977a9956013f">llvm::VPDominatorTree::properlyDominates</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#af0932bb43954178036c87ea2ee5f112c">llvm::VPValue::users</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae64d6953a1334207d9e7d9cd2587ee9f">llvm::VPlanTransforms::adjustFixedOrderRecurrences</a>.</p>

</div>
</div>

### sinkScalarOperands() {#a1536feae2abb3570ac032768a53ddd00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool sinkScalarOperands (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a0360eea6cebcb1470f84b11f7ba51f16">llvm::VPBlockUtils::blocksOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a1c868dfd250ff9592c06dd61a7fb0bcf">llvm::VPlan::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a28da654f916bf44da5513b6f1788835c">llvm::VPBlockBase::getExitingBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a72533c6b54501809628b9daee79b9d18">llvm::VPBasicBlock::getFirstNonPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a6c88376daf23b16ad26b7ac6c224d21e">llvm::VPRecipeBase::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aebc0e1a3379ed4fd614889e24b8ea48c">llvm::VPBlockBase::getSingleSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aeccf6a036968755c6d86e2d2bb17673a">llvm::VPBlockBase::getSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpsingledefrecipe/#a12b12fbdf160f2cf70973e09adbf97d4">llvm::VPSingleDefRecipe::getUnderlyingInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad30bf062f18fd6e56e36bfecefbbb386">llvm::VPlan::hasScalarVFOnly</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a2408a88276528d80adefefa00995705a">llvm::VPRecipeBase::mayHaveSideEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a15ab200cb0259f0c13b4e068acfd7fc6">llvm::VPRecipeBase::mayReadOrWriteMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a83c9341e2d36f67d5cad25ba91e862e1">llvm::VPRecipeBase::moveBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a11d83265a9e4ff6c6ecd3cf222ad0208">llvm::VPUser::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#ae3773dd8f9c831f0dde091319b2ff7d0">llvm::VPValue::replaceUsesWithIf</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#af0932bb43954178036c87ea2ee5f112c">llvm::VPValue::users</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a495c27cd70886cb8647df0ecdd9cc63d">llvm::vp_depth_first_deep</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a42d43068c576be2a1cd514f620246004">llvm::VPlanTransforms::createAndOptimizeReplicateRegions</a>.</p>

</div>
</div>

### transformRecipestoEVLRecipes() {#a5f39858b5d6d72b92c138916c64c90ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void transformRecipestoEVLRecipes (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> &amp; EVL)</td>
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

<p>Replace recipes with their EVL variants.</p>

<p>Definition at line 1726 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a8d0c6052d21638f0a385e226db3bd92f">collectAllHeaderMasks</a>, <a href="#aa70c8f392e8295a96bfd493337e122fa">collectUsersRecursively</a>, <a href="#ad0faf4b8ff1cf3306958d056dcb2fde2">createEVLRecipe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad9053d6ed9627166c144b8895d1c1010">llvm::VPlan::getCanonicalIV</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdef/#a31492b9d8412415c2dae85e33e2748fd">llvm::VPDef::getNumDefinedValues</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ac38d49d70b5f78779e83abdf4dcb4be0">llvm::VPlan::getOrAddLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#ac8744d8abf2a7ed185cc14f0a305cf8e">llvm::VPCanonicalIVPHIRecipe::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a2dffed680cc551f7ac6d92b3cd365d11">llvm::VPlan::getVF</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdef/#a76a983b694720483a3dd9fe57314e39b">llvm::VPDef::getVPSingleValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a8859e5e8cad5653b278964f47414fd84">llvm::VPRecipeBase::insertBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#ab5d43362c1fefd60d9bfcc1e28ba4688">recursivelyDeleteDeadRecipes</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#abaad22a81f7fa4ce5b60ec619ac14c37">llvm::VPValue::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a886094eaed7ce32029ea52a641142b88">llvm::to_vector</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#af0932bb43954178036c87ea2ee5f112c">llvm::VPValue::users</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad16bff9364e25351de81704fe81fd229">llvm::VPlanTransforms::tryAddExplicitVectorLength</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
