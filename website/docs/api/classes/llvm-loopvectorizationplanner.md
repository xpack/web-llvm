---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loopvectorizationplanner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoopVectorizationPlanner` Class Reference

<p>Planner drives the vectorization process after having passed Legality checks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LoopVectorizationPlanner { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">Transforms/Vectorize/LoopVectorizationPlanner.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10f5f9dfddb412ebb8bd33683ff31af9">LoopVectorizationPlanner</a> (Loop *L, LoopInfo *LI, DominatorTree *DT, const TargetLibraryInfo *TLI, const TargetTransformInfo &amp;TTI, LoopVectorizationLegality *Legal, LoopVectorizationCostModel &amp;CM, InterleavedAccessInfo &amp;IAI, PredicatedScalarEvolution &amp;PSE, const LoopVectorizeHints &amp;Hints, OptimizationRemarkEmitter *ORE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca6160bb3d669e9ce01f91b124e7e0a1">plan</a> (ElementCount UserVF, unsigned UserIC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build VPlans for the specified <span class="doxyComputerOutput">UserVF</span> and <span class="doxyComputerOutput">UserIC</span> if they are non-zero or all applicable candidate VFs otherwise. <a href="#aca6160bb3d669e9ce01f91b124e7e0a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor">VectorizationFactor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2206e77c573f4947146faa681ea8855e">planInVPlanNativePath</a> (ElementCount UserVF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the VPlan-native path to plan how to best vectorize, return the best VF and its cost. <a href="#a2206e77c573f4947146faa681ea8855e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10f355c5a55dd7e98d31c2f7e0b590aa">getPlanFor</a> (ElementCount VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> for <span class="doxyComputerOutput">VF</span>. <a href="#a10f355c5a55dd7e98d31c2f7e0b590aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor">VectorizationFactor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4adc69fc8f74164e990cce6afc1e061b">computeBestVF</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute and return the most profitable vectorization factor. <a href="#a4adc69fc8f74164e990cce6afc1e061b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbe2feb9e960936a43c845a1fa8eaba4">executePlan</a> (ElementCount VF, unsigned UF, VPlan &amp;BestPlan, InnerLoopVectorizer &amp;LB, DominatorTree *DT, bool VectorizingEpilogue, const DenseMap&lt; const SCEV *, Value * &gt; *ExpandedSCEVs=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate the IR code for the vectorized loop captured in <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> <span class="doxyComputerOutput">BestPlan</span> according to the best selected <span class="doxyComputerOutput">VF</span> and <span class="doxyComputerOutput">UF</span>. <a href="#acbe2feb9e960936a43c845a1fa8eaba4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3a6a342405e61ad992020460a530dc4">printPlans</a> (raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adce80172b05bc0a227fbd5e3d7bb80f2">hasPlanWithVF</a> (ElementCount VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look through the existing plans and return true if we have one with vectorization factor <span class="doxyComputerOutput">VF</span>. <a href="#adce80172b05bc0a227fbd5e3d7bb80f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor">VectorizationFactor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b6b1ae088cb8ca3aa4f26c4098daa3d">selectEpilogueVectorizationFactor</a> (const ElementCount MaxVF, unsigned IC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa216c2cbc8d9610dc20db065aca671d3">emitInvalidCostRemarks</a> (OptimizationRemarkEmitter *ORE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit remarks for recipes with invalid costs in the available VPlans. <a href="#aa216c2cbc8d9610dc20db065aca671d3">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36d6728b8c3cfca0a9bd02c3f0273477">buildVPlans</a> (ElementCount MinVF, ElementCount MaxVF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build VPlans for power-of-2 VF's between <span class="doxyComputerOutput">MinVF</span> and <span class="doxyComputerOutput">MaxVF</span> inclusive, according to the information gathered by Legal when it checked if it is legal to vectorize the loop. <a href="#a36d6728b8c3cfca0a9bd02c3f0273477">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6f45b1c4385eaec2d3ea11a0e03af10">cost</a> (VPlan &amp;Plan, ElementCount VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the cost of <span class="doxyComputerOutput">Plan</span> for vectorization factor <span class="doxyComputerOutput">VF</span>. <a href="#ab6f45b1c4385eaec2d3ea11a0e03af10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fa50111fc2f7ba85b04efad04e91a47">precomputeCosts</a> (VPlan &amp;Plan, ElementCount VF, VPCostContext &amp;CostCtx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Precompute costs for certain instructions using the legacy cost model. <a href="#a4fa50111fc2f7ba85b04efad04e91a47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aefc42f3cefc5a839ca925b4cb3ae4a7b">VPlanPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c9c8066fac537fa7f0c7be798288ce5">buildVPlan</a> (VFRange &amp;Range)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> according to the information gathered by Legal. <a href="#a0c9c8066fac537fa7f0c7be798288ce5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aefc42f3cefc5a839ca925b4cb3ae4a7b">VPlanPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88155f88d9b77ba6acc351bf80d23218">tryToBuildVPlanWithVPRecipes</a> (VFRange &amp;Range)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> using VPRecipes according to the information gather by Legal. <a href="#a88155f88d9b77ba6acc351bf80d23218">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaab3e45a523804650c3186f55f35d44a">buildVPlansWithVPRecipes</a> (ElementCount MinVF, ElementCount MaxVF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build VPlans for power-of-2 VF's between <span class="doxyComputerOutput">MinVF</span> and <span class="doxyComputerOutput">MaxVF</span> inclusive, according to the information gathered by Legal when it checked if it is legal to vectorize the loop. <a href="#aaab3e45a523804650c3186f55f35d44a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaae9982889ac6cda0245c6499776716a">adjustRecipesForReductions</a> (VPlanPtr &amp;Plan, VPRecipeBuilder &amp;RecipeBuilder, ElementCount MinVF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor">VectorizationFactor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ffe660d859d01250e0a188f72f2ab5f">selectVectorizationFactor</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a526b44862dff38eb540d05c7b15c44ea">isMoreProfitable</a> (const VectorizationFactor &amp;A, const VectorizationFactor &amp;B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the per-lane cost of <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor">VectorizationFactor</a> A is lower than that of B. <a href="#a526b44862dff38eb540d05c7b15c44ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24813bbab468d2eb08910c8772416e32">isMoreProfitable</a> (const VectorizationFactor &amp;A, const VectorizationFactor &amp;B, const unsigned MaxTripCount) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the per-lane cost of <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor">VectorizationFactor</a> A is lower than that of B in the context of vectorizing a loop with known <span class="doxyComputerOutput">MaxTripCount</span>. <a href="#a24813bbab468d2eb08910c8772416e32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3db6eb8e8386f3bc9414066aa78985d">isCandidateForEpilogueVectorization</a> (const ElementCount VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determines if we have the infrastructure to vectorize the loop and its epilogue, assuming the main loop is vectorized by <span class="doxyComputerOutput">VF</span>. <a href="#ac3db6eb8e8386f3bc9414066aa78985d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7b9296672d17d182b0267a5a3bbe15e">OrigLoop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The loop that we evaluate. <a href="#ad7b9296672d17d182b0267a5a3bbe15e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af80ba3afd391e2fe56630552bc45e512">LI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> Info analysis. <a href="#af80ba3afd391e2fe56630552bc45e512">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e12ddc73809314d0396f4dfd4648f7a">DT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The dominator tree. <a href="#a2e12ddc73809314d0396f4dfd4648f7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab65c14e1101056e342382e505e69ade">TLI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Library Info. <a href="#aab65c14e1101056e342382e505e69ade">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafd7131aeaee71b3406d9261bdbdb026">TTI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Transform Info. <a href="#aafd7131aeaee71b3406d9261bdbdb026">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality">LoopVectorizationLegality</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af53bfd0c68a9ef5269281ca4cb742832">Legal</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The legality analysis. <a href="#af53bfd0c68a9ef5269281ca4cb742832">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel">LoopVectorizationCostModel</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af02869c9831c6fa212ec58cfaf3ddd0c">CM</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The profitability analysis. <a href="#af02869c9831c6fa212ec58cfaf3ddd0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/interleavedaccessinfo">InterleavedAccessInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a112619c3c66beb072360ba34f3871b47">IAI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The interleaved access analysis. <a href="#a112619c3c66beb072360ba34f3871b47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d8157fe745be67bcf8855f2c420bd93">PSE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints">LoopVectorizeHints</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d85e0981dbfb69b6720470453568c90">Hints</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e412d8cd7dd6d8d442acfbaf005f2e6">ORE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aefc42f3cefc5a839ca925b4cb3ae4a7b">VPlanPtr</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fc0a613c639ff94cc7b1a92ce24d8aa">VPlans</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor">VectorizationFactor</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcd3c802247abd1cf3b7bd3c79395f47">ProfitableVFs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Profitable vector factors. <a href="#afcd3c802247abd1cf3b7bd3c79395f47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbuilder">VPBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d79b326968a7f668c5ab209e75d3883">Builder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A builder used to construct the current plan. <a href="#a8d79b326968a7f668c5ab209e75d3883">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe3531f2a6e2a86c1d35958794805785">getDecisionAndClampRange</a> (const std::function&lt; bool(ElementCount)&gt; &amp;Predicate, VFRange &amp;Range)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/predicate">Predicate</a></span> on a <span class="doxyComputerOutput">Range</span> of VF's. <a href="#abe3531f2a6e2a86c1d35958794805785">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Planner drives the vectorization process after having passed Legality checks.</p>

<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoopVectorizationPlanner() {#a10f5f9dfddb412ebb8bd33683ff31af9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoopVectorizationPlanner::LoopVectorizationPlanner (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality">LoopVectorizationLegality</a> * Legal, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel">LoopVectorizationCostModel</a> &amp; CM, <a href="/web-llvm/docs/api/classes/llvm/interleavedaccessinfo">InterleavedAccessInfo</a> &amp; IAI, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints">LoopVectorizeHints</a> &amp; Hints, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE)</td>
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



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### computeBestVF() {#a4adc69fc8f74164e990cce6afc1e061b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorizationFactor LoopVectorizationPlanner::computeBestVF ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute and return the most profitable vectorization factor.</p>


<p>Also collect all profitable VFs in ProfitableVFs.</p>


<p>Declaration at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 7457 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor/#a048d568675a5cc69c3fb85206882316d">llvm::VectorizationFactor::Cost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor/#acd24dfdad4f887e1f7b10c9039a05930">llvm::VectorizationFactor::Disabled</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a55ab1072c44295ad279535d714a0f33ea278ca681847fb2bad9707f76d899b231">llvm::LoopVectorizeHints::FK_Enabled</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a6de26b938774385a0a4fb0d0b2a32d48">llvm::InstructionCost::getMax</a>, <a href="#a10f355c5a55dd7e98d31c2f7e0b590aa">getPlanFor</a>, <a href="#adce80172b05bc0a227fbd5e3d7bb80f2">hasPlanWithVF</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a696283c30308704d020a9d86065aa3ae">planContainsAdditionalSimplifications</a>, <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor/#a76f716c04dfa813b98e1c112bc642d34">llvm::VectorizationFactor::ScalarCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba737cfc93e5a2ff961677d57186167e7c">llvm::TargetTransformInfo::TCK_CodeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba81b2c6f1f1e13e4a575e6d1c8b29b6e1">llvm::TargetTransformInfo::TCK_Latency</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">llvm::TargetTransformInfo::TCK_RecipThroughput</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba7f80055e1969cb850739546467460ad8">llvm::TargetTransformInfo::TCK_SizeAndLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a3aac2593ea2eaac537de30053e8e05fd">llvm::VPlan::vectorFactors</a>, <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor/#a3a4e23fea2c7cec4fd3c2bf27351679c">llvm::VectorizationFactor::Width</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#af378bb1e037306d9cfd4bb0b49ba55f9">willGenerateVectors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### emitInvalidCostRemarks() {#aa216c2cbc8d9610dc20db065aca671d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVectorizationPlanner::emitInvalidCostRemarks (<a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit remarks for recipes with invalid costs in the available VPlans.</p>

<p>Declaration at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 4326 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a0360eea6cebcb1470f84b11f7ba51f16">llvm::VPBlockUtils::blocksOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/typeswitch/#a78c545287cbe57529ce7751e25c815a5">llvm::TypeSwitch&lt; T, ResultT &gt;::Case</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a53408c95a7bfb5443b43fb2134c3eb23">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9affd129d19aae669647eb0d1c91f793">llvm::Instruction::getOpcodeName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">Int</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa22517ece6258e8db44e22e5a8d85249">llvm::reportVectorizationInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad6e9c0ff694f0fca0222e79e772b647e">llvm::CallingConv::Tail</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a495c27cd70886cb8647df0ecdd9cc63d">llvm::vp_depth_first_deep</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### executePlan() {#acbe2feb9e960936a43c845a1fa8eaba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; const SCEV *, Value * &gt; LoopVectorizationPlanner::executePlan (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, unsigned UF, <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; BestPlan, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer">InnerLoopVectorizer</a> &amp; LB, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, bool VectorizingEpilogue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; * ExpandedSCEVs=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate the IR code for the vectorized loop captured in <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> <span class="doxyComputerOutput">BestPlan</span> according to the best selected <span class="doxyComputerOutput">VF</span> and <span class="doxyComputerOutput">UF</span>.</p>


<p>TODO: <span class="doxyComputerOutput">VectorizingEpilogue</span> indicates if the executed <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> is for the epilogue vector loop. It should be removed once the re-use issue has been fixed. <span class="doxyComputerOutput">ExpandedSCEVs</span> is passed during execution of the plan for epilogue loop to re-use expansion results generated during main plan execution.</p>


<p>Returns a mapping of SCEVs to their expanded IR values. Note that this is a temporary workaround needed due to the current epilogue handling.</p>


<p>Declaration at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 7639 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a033bb363914fbd3c2cd990330959036c">addRuntimeUnrollDisableMetaData</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#ac3679e1fff2d21c2034c7ce14df24bf7">llvm::InnerLoopVectorizer::Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a63e564d621011fac5978d18138121e5c">llvm::VPlanTransforms::convertToConcreteRecipes</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a31f933a6eada9926c9e320db27dfb775">llvm::InnerLoopVectorizer::createVectorizedLoopSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#aeb3dd295f833ecc508d7586df94a76f3">llvm::VPBasicBlock::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a305d2f13922c7da4206b299861370a80">llvm::VPBasicBlock::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad80b94848142a7c633976aff96d4c408">llvm::VPlan::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a90ad8ccd396152c749068f986f2b751a">fixReductionScalarResumeWhenVectorizingEpilog</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a9484786140efebf774cde8f072894246">llvm::InnerLoopVectorizer::fixVectorizedLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a8f2e87f456c35fdad0ec24e7c71a92a5">llvm::InnerLoopVectorizer::getAdditionalBypassBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking/#ac837a7d2828c8fe9e84140095d003d51">llvm::RuntimePointerChecking::getChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking/#a741849368bb652fdaba99d70c36b527f">llvm::RuntimePointerChecking::getDiffChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a1c868dfd250ff9592c06dd61a7fb0bcf">llvm::VPlan::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a86acbbb5785d46e5a10d2ed34c779dd9">llvm::InnerLoopVectorizer::getInductionAdditionalBypassValue</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#ab5632546144c4db5bbe1f975aeebd9d2">llvm::LoopVectorizationLegality::getLAI</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a995b2a034ffc26dcd2f3a679f9d2feea">llvm::VPlan::getMiddleBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#aa83b181aa14d5afe1390faad388f91a4">llvm::InnerLoopVectorizer::getOrCreateVectorTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo/#a3aedf5694dc5b1e81a79658b126a9b43">llvm::LoopAccessInfo::getRuntimePointerChecking</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aebc0e1a3379ed4fd614889e24b8ea48c">llvm::VPBlockBase::getSingleSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a35de654dc8297fa810c78922102bb696">llvm::InnerLoopVectorizer::getTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a2f5fc19caa67daeca8a1316c7e055e3c">llvm::VPlan::getTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a532045d23e6f3efd21732fd342f99f09">llvm::VPlan::getUF</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add2fce2ce0e32b20e41b0aa9f8ca70c2">llvm::hasBranchWeightMD</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a6e9c2a69cd9bc0e46626f5302a03d3da">llvm::VPlan::hasUF</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#ab22ff9e23f7f27234c8f6ec76db0c1f3">llvm::LoopVectorizationLegality::hasUncountableEarlyExit</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a633dd97e642c10e8aa1dff2bd2874edb">llvm::VPlan::hasVF</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a6bb946cd99f8c37f0145265914aea778">llvm::InnerLoopVectorizer::Legal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a3bf55ccbbeedcfb8cd2a1bd62c0ad91a">LLVMLoopVectorizeFollowupAll</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a99050b417d193e1cc1117e5bbd4bfbce">LLVMLoopVectorizeFollowupVectorized</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a99d1430a4b51d71f77d78febb40f9d32">llvm::InnerLoopVectorizer::LoopVectorPreHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a368216c9c116e3f30d8dd352ce1370fc">llvm::makeFollowupLoopID</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a143bc5faeb35f7363570e97bccf76e53">llvm::VPlan::prepareToExecute</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a9e275f16680d4f09dbcc0dd7d323a075">llvm::InnerLoopVectorizer::printDebugTracesAtEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a00579d597c88e5f3c51754bcd9ec5658">llvm::InnerLoopVectorizer::printDebugTracesAtStart</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aaca9dd97d4c523d8c65274654abe4eb9">llvm::VPlanTransforms::removeDeadRecipes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a3a8743a69fac5e7fa9c2b02604b2cf2f">replaceVPBBWithIRVPBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6cf82c052d63a1b464be8e48ff38c48e">llvm::setBranchWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a9160ed9f749a9c4df711061181288e13">llvm::InnerLoopVectorizer::setTripCount</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a7a1cca51bb9bce4efad1063dcf158967">llvm::VPlanTransforms::unrollByUF</a> and <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a5d4cb9fb552657b2138b925b44315d21">llvm::TargetTransformInfo::UnrollingPreferences::UnrollVectorizedLoop</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#adeb41c907ebde15846bc643325909f95">processLoopInVPlanNativePath</a>.</p>

</div>
</div>

### getPlanFor() {#a10f355c5a55dd7e98d31c2f7e0b590aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPlan &amp; LoopVectorizationPlanner::getPlanFor (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> for <span class="doxyComputerOutput">VF</span>.</p>


<p>At the moment, there is always a single <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> for each VF.</p>


<p>Declaration at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 1639 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a633dd97e642c10e8aa1dff2bd2874edb">llvm::VPlan::hasVF</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/#ac0b363a134c3bfac25ba209704ef3ee3">llvm::VPTransformState::Plan</a> and <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/#adeaf44a788c3e001582a71790894b78d">llvm::VPTransformState::VF</a>.</p>


<p>Referenced by <a href="#a4adc69fc8f74164e990cce6afc1e061b">computeBestVF</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#adeb41c907ebde15846bc643325909f95">processLoopInVPlanNativePath</a> and <a href="#a0b6b1ae088cb8ca3aa4f26c4098daa3d">selectEpilogueVectorizationFactor</a>.</p>

</div>
</div>

### hasPlanWithVF() {#adce80172b05bc0a227fbd5e3d7bb80f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationPlanner::hasPlanWithVF (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
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

<p>Look through the existing plans and return true if we have one with vectorization factor <span class="doxyComputerOutput">VF</span>.</p>

<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>.</p>


<p>Referenced by <a href="#a4adc69fc8f74164e990cce6afc1e061b">computeBestVF</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a> and <a href="#a0b6b1ae088cb8ca3aa4f26c4098daa3d">selectEpilogueVectorizationFactor</a>.</p>

</div>
</div>

### plan() {#aca6160bb3d669e9ce01f91b124e7e0a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVectorizationPlanner::plan (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> UserVF, unsigned UserIC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build VPlans for the specified <span class="doxyComputerOutput">UserVF</span> and <span class="doxyComputerOutput">UserIC</span> if they are non-zero or all applicable candidate VFs otherwise.</p>


<p>If vectorization and interleaving should be avoided up-front, no plans are generated.</p>


<p>Declaration at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 7094 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/fixedscalablevfpair/#a25a62c28e80eac3b4cc08470ae0770bd">llvm::FixedScalableVFPair::FixedVF</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a1bddc4949ab247dd1474f79b9bc6e34e">llvm::ElementCount::getScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a338ba7ca7a526243ab1853d07d90fe38">llvm::details::FixedOrScalableQuantity&lt; ElementCount, unsigned &gt;::isKnownLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a098a514da47d00e1176aa2e16eacfb70">llvm::ElementCount::isVector</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ac3a6a342405e61ad992020460a530dc4">printPlans</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa22517ece6258e8db44e22e5a8d85249">llvm::reportVectorizationInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/fixedscalablevfpair/#a25f82f8ef3355c335a7ddae4ad0b6965">llvm::FixedScalableVFPair::ScalableVF</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#adf8d8fb6f39b9c0cf21d55b7229d35e2">useMaskedInterleavedAccesses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### planInVPlanNativePath() {#a2206e77c573f4947146faa681ea8855e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorizationFactor LoopVectorizationPlanner::planInVPlanNativePath (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> UserVF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the VPlan-native path to plan how to best vectorize, return the best VF and its cost.</p>

<p>Declaration at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 7043 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a36d6728b8c3cfca0a9bd02c3f0273477">buildVPlans</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a0b91e092434338369b2e1995b87f0c5b">determineVPlanVF</a>, <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor/#acd24dfdad4f887e1f7b10c9039a05930">llvm::VectorizationFactor::Disabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ef0a19ea2267182eb0da4f6e191b59b">llvm::EnableVPlanNativePath</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a48035e22b43c905a2961c90e5470b2f0">ForceTargetSupportsScalableVectors</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ad96fee81c3174ef427bf779d73fb1ef2">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isZero</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab425bb10a0f4af749bbb29aa07fc6854">llvm::reportVectorizationFailure</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a9f30855a6efcd4a12875deb88880b510">VPlanBuildStressTest</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#adeb41c907ebde15846bc643325909f95">processLoopInVPlanNativePath</a>.</p>

</div>
</div>

### printPlans() {#ac3a6a342405e61ad992020460a530dc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVectorizationPlanner::printPlans (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 1653 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/#ac0b363a134c3bfac25ba209704ef3ee3">llvm::VPTransformState::Plan</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#adef61e4746c6f7f0e2e75da307e77c42">llvm::VPlan::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a064c339f401589b34437e61d8108d8d8">llvm::VPlan::printDOT</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#aee1acb431b730623631ccbf80bea3b84">PrintVPlansInDotFormat</a>.</p>


<p>Referenced by <a href="#aca6160bb3d669e9ce01f91b124e7e0a1">plan</a>.</p>

</div>
</div>

### selectEpilogueVectorizationFactor() {#a0b6b1ae088cb8ca3aa4f26c4098daa3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorizationFactor LoopVectorizationPlanner::selectEpilogueVectorizationFactor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> MaxVF, unsigned IC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The most profitable vectorization factor and the cost of that VF for vectorizing the epilogue. Returns <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor/#acd24dfdad4f887e1f7b10c9039a05930">VectorizationFactor::Disabled</a> if epilogue vectorization is not supported for the loop.</p></dd>
</dl>


<p>Declaration at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 4676 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor/#acd24dfdad4f887e1f7b10c9039a05930">llvm::VectorizationFactor::Disabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a8bb0da83afffaf803b396b1d055ba5e0">EnableEpilogueVectorization</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a01340df86c9d26b281ff1ab9288c28ce">EpilogueVectorizationForceVF</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a2eb94d079d8416118f4aaed865ab05d7">llvm::ScalarEvolution::getConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#ab3df41ae1ed3978e3b825bc4dd50ae8d">getEstimatedRuntimeVF</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#a10f355c5a55dd7e98d31c2f7e0b590aa">getPlanFor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a5999b0390c92ee4af2544fe9772454bf">llvm::vputils::getSCEVExprForVPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a2f5fc19caa67daeca8a1316c7e055e3c">llvm::VPlan::getTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ac8de32f4d40eae96f0e26f0728682c2e">llvm::ScalarEvolution::getUnsignedRangeMax</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a13b9eb961d35ad9ecb3b633f5703253a">llvm::ScalarEvolution::getURemExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="#adce80172b05bc0a227fbd5e3d7bb80f2">hasPlanWithVF</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#afb486f9022a26e1cc53ff189710dbde5">llvm::details::FixedOrScalableQuantity&lt; ElementCount, unsigned &gt;::isKnownGE</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#addaa86bfa4ca26b7f366cbdd868f99bf">llvm::details::FixedOrScalableQuantity&lt; ElementCount, unsigned &gt;::isKnownGT</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#af74112dae88db73eb5484821b6f0fccd">llvm::ScalarEvolution::isKnownPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### buildVPlans() {#a36d6728b8c3cfca0a9bd02c3f0273477}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVectorizationPlanner::buildVPlans (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> MinVF, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> MaxVF)</td>
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

<p>Build VPlans for power-of-2 VF's between <span class="doxyComputerOutput">MinVF</span> and <span class="doxyComputerOutput">MaxVF</span> inclusive, according to the information gathered by Legal when it checked if it is legal to vectorize the loop.</p>


<p>Build VPlans for the full range of feasible VF's = {<span class="doxyComputerOutput">MinVF</span>, 2 * <span class="doxyComputerOutput">MinVF</span>, 4 * <span class="doxyComputerOutput">MinVF</span>, ..., <span class="doxyComputerOutput">MaxVF}</span> by repeatedly building a <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> for a sub-range of VF's starting at a given VF and extending it as much as possible.</p>


<p>Each vectorization decision can potentially shorten this sub-range during buildVPlan().</p>


<p>Declaration at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 1624 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/vfrange/#a8f3e6ec0ac823874aa93cc9d98081701">llvm::VFRange::End</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#add3be1d1d9e5b1ee2014c32d21bf2b5b">llvm::VPRegionBlock::getExiting</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a83e6442f8ebefccdb5e089732fe397ac">llvm::details::FixedOrScalableQuantity&lt; ElementCount, unsigned &gt;::isKnownLT</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae3449b993cd1c459995c2fe13ef50892">llvm::VPlanTransforms::optimize</a>, <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/#ac0b363a134c3bfac25ba209704ef3ee3">llvm::VPTransformState::Plan</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a2bd1c53f9607876b22c6fd3ec1e28a50">llvm::VPBlockBase::setName</a> and <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/#adeaf44a788c3e001582a71790894b78d">llvm::VPTransformState::VF</a>.</p>


<p>Referenced by <a href="#a2206e77c573f4947146faa681ea8855e">planInVPlanNativePath</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### adjustRecipesForReductions() {#aaae9982889ac6cda0245c6499776716a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVectorizationPlanner::adjustRecipesForReductions (<a href="/web-llvm/docs/api/namespaces/llvm/#aefc42f3cefc5a839ca925b4cb3ae4a7b">VPlanPtr</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder">VPRecipeBuilder</a> &amp; RecipeBuilder, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> MinVF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 9557 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### buildVPlan() {#a0c9c8066fac537fa7f0c7be798288ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPlanPtr LoopVectorizationPlanner::buildVPlan (<a href="/web-llvm/docs/api/structs/llvm/vfrange">VFRange</a> &amp; Range)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build a <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> according to the information gathered by Legal.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> for vectorization factors <span class="doxyComputerOutput">Range.Start</span> and up to <span class="doxyComputerOutput">Range.End</span> exclusive, possibly decreasing <span class="doxyComputerOutput">Range.End</span>.</p></dd>
</dl>


<p>Declaration at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 9495 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### buildVPlansWithVPRecipes() {#aaab3e45a523804650c3186f55f35d44a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVectorizationPlanner::buildVPlansWithVPRecipes (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> MinVF, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> MaxVF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build VPlans for power-of-2 VF's between <span class="doxyComputerOutput">MinVF</span> and <span class="doxyComputerOutput">MaxVF</span> inclusive, according to the information gathered by Legal when it checked if it is legal to vectorize the loop.</p>


<p>This method creates VPlans using VPRecipes.</p>


<p>Declaration at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 8903 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### cost() {#ab6f45b1c4385eaec2d3ea11a0e03af10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost LoopVectorizationPlanner::cost (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Computes the cost of <span class="doxyComputerOutput">Plan</span> for vectorization factor <span class="doxyComputerOutput">VF</span>.</p>


<p>The current implementation requires access to the <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality">LoopVectorizationLegality</a> to handle inductions and reductions, which is why it is kept separate from the VPlan-only cost infrastructure.</p>


<p>TODO: Move to <a href="/web-llvm/docs/api/classes/llvm/vplan/#a8d2ce995a1feaa7a65ff40f77f073db3">VPlan::cost</a> once the use of <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality">LoopVectorizationLegality</a> has been retired.</p>


<p>Declaration at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 7382 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### isCandidateForEpilogueVectorization() {#ac3db6eb8e8386f3bc9414066aa78985d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVectorizationPlanner::isCandidateForEpilogueVectorization (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determines if we have the infrastructure to vectorize the loop and its epilogue, assuming the main loop is vectorized by <span class="doxyComputerOutput">VF</span>.</p>

<p>Declaration at line 540 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 4606 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### isMoreProfitable() {#a526b44862dff38eb540d05c7b15c44ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVectorizationPlanner::isMoreProfitable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor">VectorizationFactor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor">VectorizationFactor</a> &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the per-lane cost of <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor">VectorizationFactor</a> A is lower than that of B.</p>

<p>Declaration at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 4320 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### isMoreProfitable() {#a24813bbab468d2eb08910c8772416e32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVectorizationPlanner::isMoreProfitable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor">VectorizationFactor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor">VectorizationFactor</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned MaxTripCount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the per-lane cost of <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor">VectorizationFactor</a> A is lower than that of B in the context of vectorizing a loop with known <span class="doxyComputerOutput">MaxTripCount</span>.</p>

<p>Declaration at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 4266 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### precomputeCosts() {#a4fa50111fc2f7ba85b04efad04e91a47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost LoopVectorizationPlanner::precomputeCosts (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="/web-llvm/docs/api/structs/llvm/vpcostcontext">VPCostContext</a> &amp; CostCtx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Precompute costs for certain instructions using the legacy cost model.</p>


<p>The function is used to bring up the VPlan-based cost model to initially avoid taking different decisions due to inaccuracies in the legacy cost model.</p>


<p>Declaration at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 7184 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### selectVectorizationFactor() {#a4ffe660d859d01250e0a188f72f2ab5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorizationFactor LoopVectorizationPlanner::selectVectorizationFactor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The most profitable vectorization factor for the available VPlans and the cost of that VF. This is now only used to verify the decisions by the new VPlan-based cost-model and will be retired once the VPlan-based cost-model is stabilized.</p></dd>
</dl>


<p>Declaration at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 4536 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### tryToBuildVPlanWithVPRecipes() {#a88155f88d9b77ba6acc351bf80d23218}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPlanPtr LoopVectorizationPlanner::tryToBuildVPlanWithVPRecipes (<a href="/web-llvm/docs/api/structs/llvm/vfrange">VFRange</a> &amp; Range)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build a <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> using VPRecipes according to the information gather by Legal.</p>


<p>This method is only used for the legacy inner loop vectorizer. <span class="doxyComputerOutput">Range's</span> largest included VF is restricted to the maximum VF the returned <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> is valid for. If no <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> can be built for the input range, set the largest included VF to the maximum VF for which no plan could be built.</p>


<p>Declaration at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 9213 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Builder {#a8d79b326968a7f668c5ab209e75d3883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBuilder llvm::LoopVectorizationPlanner::Builder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A builder used to construct the current plan.</p>

<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### CM {#af02869c9831c6fa212ec58cfaf3ddd0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopVectorizationCostModel&amp; llvm::LoopVectorizationPlanner::CM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The profitability analysis.</p>

<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### DT {#a2e12ddc73809314d0396f4dfd4648f7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* llvm::LoopVectorizationPlanner::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The dominator tree.</p>

<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### Hints {#a6d85e0981dbfb69b6720470453568c90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopVectorizeHints&amp; llvm::LoopVectorizationPlanner::Hints</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### IAI {#a112619c3c66beb072360ba34f3871b47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InterleavedAccessInfo&amp; llvm::LoopVectorizationPlanner::IAI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The interleaved access analysis.</p>

<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### Legal {#af53bfd0c68a9ef5269281ca4cb742832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopVectorizationLegality* llvm::LoopVectorizationPlanner::Legal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The legality analysis.</p>

<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### LI {#af80ba3afd391e2fe56630552bc45e512}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* llvm::LoopVectorizationPlanner::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> Info analysis.</p>

<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### ORE {#a2e412d8cd7dd6d8d442acfbaf005f2e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter* llvm::LoopVectorizationPlanner::ORE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### OrigLoop {#ad7b9296672d17d182b0267a5a3bbe15e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* llvm::LoopVectorizationPlanner::OrigLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The loop that we evaluate.</p>

<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### ProfitableVFs {#afcd3c802247abd1cf3b7bd3c79395f47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;VectorizationFactor, 8&gt; llvm::LoopVectorizationPlanner::ProfitableVFs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Profitable vector factors.</p>

<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### PSE {#a0d8157fe745be67bcf8855f2c420bd93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredicatedScalarEvolution&amp; llvm::LoopVectorizationPlanner::PSE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### TLI {#aab65c14e1101056e342382e505e69ade}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo* llvm::LoopVectorizationPlanner::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Library Info.</p>

<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### TTI {#aafd7131aeaee71b3406d9261bdbdb026}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetTransformInfo&amp; llvm::LoopVectorizationPlanner::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Transform Info.</p>

<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### VPlans {#a9fc0a613c639ff94cc7b1a92ce24d8aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;VPlanPtr, 4&gt; llvm::LoopVectorizationPlanner::VPlans</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getDecisionAndClampRange() {#abe3531f2a6e2a86c1d35958794805785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVectorizationPlanner::getDecisionAndClampRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a>)&gt; &amp; Predicate, <a href="/web-llvm/docs/api/structs/llvm/vfrange">VFRange</a> &amp; Range)</td>
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

<p>Test a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/predicate">Predicate</a></span> on a <span class="doxyComputerOutput">Range</span> of VF's.</p>


<p>Return the value of applying <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/predicate">Predicate</a></span> on Range.Start, possibly decreasing Range.End such that the returned value holds for the entire <span class="doxyComputerOutput">Range</span>.</p>


<p>Declaration at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>, definition at line 1605 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a2c36c7d44a38145e7c72340d1b0e34d8">llvm::VPRecipeBuilder::handleReplication</a> and <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a760fb390c24b907500c0a181fada9590">llvm::VPRecipeBuilder::tryToCreateWidenRecipe</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
