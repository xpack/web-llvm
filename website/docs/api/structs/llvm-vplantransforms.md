---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/vplantransforms
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `VPlanTransforms` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::VPlanTransforms { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">Transforms/Vectorize/VPlanTransforms.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad210afaefb4884ac5008dd5fbaf1cbf8">VPInstructionsToVPRecipes</a> (VPlanPtr &amp;Plan, function_ref&lt; const InductionDescriptor *(PHINode *)&gt; GetIntOrFpInductionDescriptor, ScalarEvolution &amp;SE, const TargetLibraryInfo &amp;TLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replaces the VPInstructions in <span class="doxyComputerOutput">Plan</span> with corresponding widen recipes. <a href="#ad210afaefb4884ac5008dd5fbaf1cbf8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae64d6953a1334207d9e7d9cd2587ee9f">adjustFixedOrderRecurrences</a> (VPlan &amp;Plan, VPBuilder &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to have all users of fixed-order recurrences appear after the recipe defining their previous value, by either sinking users or hoisting recipes defining their previous value (and its operands). <a href="#ae64d6953a1334207d9e7d9cd2587ee9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace9e1e6e7295914973dec18350b382ca">clearReductionWrapFlags</a> (VPlan &amp;Plan)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear NSW/NUW flags from reduction instructions if necessary. <a href="#ace9e1e6e7295914973dec18350b382ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a1cca51bb9bce4efad1063dcf158967">unrollByUF</a> (VPlan &amp;Plan, unsigned UF, LLVMContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Explicitly unroll <span class="doxyComputerOutput">Plan</span> by <span class="doxyComputerOutput">UF</span>. <a href="#a7a1cca51bb9bce4efad1063dcf158967">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af25d938764b8634e70e95ff3f0c35129">optimizeForVFAndUF</a> (VPlan &amp;Plan, ElementCount BestVF, unsigned BestUF, PredicatedScalarEvolution &amp;PSE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize <span class="doxyComputerOutput">Plan</span> based on <span class="doxyComputerOutput">BestVF</span> and <span class="doxyComputerOutput">BestUF</span>. <a href="#af25d938764b8634e70e95ff3f0c35129">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3449b993cd1c459995c2fe13ef50892">optimize</a> (VPlan &amp;Plan)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply VPlan-to-VPlan optimizations to <span class="doxyComputerOutput">Plan</span>, including induction recipe optimizations, dead recipe removal, replicate region optimizations and block merging. <a href="#ae3449b993cd1c459995c2fe13ef50892">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42d43068c576be2a1cd514f620246004">createAndOptimizeReplicateRegions</a> (VPlan &amp;Plan)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrap predicated VPReplicateRecipes with a mask operand in an if-then region block and remove the mask operand. <a href="#a42d43068c576be2a1cd514f620246004">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1d2d60cd9edd9f7ca98c50789747c95">addActiveLaneMask</a> (VPlan &amp;Plan, bool UseActiveLaneMaskForControlFlow, bool DataAndControlFlowWithoutRuntimeCheck)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace (ICMP_ULE, wide canonical IV, backedge-taken-count) checks with an (active-lane-mask recipe, wide canonical IV, trip-count). <a href="#ae1d2d60cd9edd9f7ca98c50789747c95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae61793492431f138869f097a5f31bd32">truncateToMinimalBitwidths</a> (VPlan &amp;Plan, const MapVector&lt; Instruction *, uint64_t &gt; &amp;MinBWs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert truncates and extends for any truncated recipe. <a href="#ae61793492431f138869f097a5f31bd32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0f143b8d4693978b984f0639c90e508">dropPoisonGeneratingRecipes</a> (VPlan &amp;Plan, function_ref&lt; bool(BasicBlock *)&gt; BlockNeedsPredication)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop poison flags from recipes that may generate a poison value that is used after vectorization, even when their operands are not poison. <a href="#aa0f143b8d4693978b984f0639c90e508">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad16bff9364e25351de81704fe81fd229">tryAddExplicitVectorLength</a> (VPlan &amp;Plan, const std::optional&lt; unsigned &gt; &amp;MaxEVLSafeElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a <a href="/web-llvm/docs/api/classes/llvm/vpevlbasedivphirecipe">VPEVLBasedIVPHIRecipe</a> and related recipes to <span class="doxyComputerOutput">Plan</span> and replaces all uses except the canonical IV increment of <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe">VPCanonicalIVPHIRecipe</a> with a <a href="/web-llvm/docs/api/classes/llvm/vpevlbasedivphirecipe">VPEVLBasedIVPHIRecipe</a>. <a href="#ad16bff9364e25351de81704fe81fd229">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa88371693bc18186386b04e8c45a30e4">createInterleaveGroups</a> (VPlan &amp;Plan, const SmallPtrSetImpl&lt; const InterleaveGroup&lt; Instruction &gt; * &gt; &amp;InterleaveGroups, VPRecipeBuilder &amp;RecipeBuilder, bool ScalarEpilogueAllowed)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaca9dd97d4c523d8c65274654abe4eb9">removeDeadRecipes</a> (VPlan &amp;Plan)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove dead recipes from <span class="doxyComputerOutput">Plan</span>. <a href="#aaca9dd97d4c523d8c65274654abe4eb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2fcd61c17c94d7e9d10b24b718c812e">handleUncountableEarlyExit</a> (VPlan &amp;Plan, ScalarEvolution &amp;SE, Loop *OrigLoop, BasicBlock *UncountableExitingBlock, VPRecipeBuilder &amp;RecipeBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">Plan</span> to account for the uncountable early exit block in <span class="doxyComputerOutput">UncountableExitingBlock</span> by. <a href="#ac2fcd61c17c94d7e9d10b24b718c812e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63e564d621011fac5978d18138121e5c">convertToConcreteRecipes</a> (VPlan &amp;Plan)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower abstract recipes to concrete ones, that can be codegen'd. <a href="#a63e564d621011fac5978d18138121e5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a573419fed83f23b6bf70ac6731dbfa">optimizeInductionExitUsers</a> (VPlan &amp;Plan, DenseMap&lt; VPValue *, VPValue * &gt; &amp;EndValues)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If there's a single exit block, optimize its phi recipes that use exiting IV values by feeding them precomputed end values instead, possibly taken one step backwards. <a href="#a3a573419fed83f23b6bf70ac6731dbfa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### addActiveLaneMask() {#ae1d2d60cd9edd9f7ca98c50789747c95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPlanTransforms::addActiveLaneMask (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, bool UseActiveLaneMaskForControlFlow, bool DataAndControlFlowWithoutRuntimeCheck)</td>
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

<p>Replace (ICMP_ULE, wide canonical IV, backedge-taken-count) checks with an (active-lane-mask recipe, wide canonical IV, trip-count).</p>


<p>If <span class="doxyComputerOutput">UseActiveLaneMaskForControlFlow</span> is true, introduce an <a href="/web-llvm/docs/api/classes/llvm/vpactivelanemaskphirecipe">VPActiveLaneMaskPHIRecipe</a>. If <span class="doxyComputerOutput">DataAndControlFlowWithoutRuntimeCheck</span> is true, no minimum-iteration runtime check will be created (during skeleton creation) and instead it is handled using active-lane-mask. <span class="doxyComputerOutput">DataAndControlFlowWithoutRuntimeCheck</span> implies <span class="doxyComputerOutput">UseActiveLaneMaskForControlFlow</span>.</p>


<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a>, definition at line 1606 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2a79a53c84dbac24c496a4c9a6cf70596c">llvm::VPInstruction::ActiveLaneMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5a9cb34d61fa4930ff585649d1d5b2ed">addVPLaneMaskPhiAndUpdateExitBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a8d0c6052d21638f0a385e226db3bd92f">collectAllHeaderMasks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdda41105c5fe36c41d2246b18c1724fa2ff">llvm::DataAndControlFlowWithoutRuntimeCheck</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad9053d6ed9627166c144b8895d1c1010">llvm::VPlan::getCanonicalIV</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#a84fe82982cb89a345442baaa710e949a">llvm::VPBuilder::getToInsertAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a2f5fc19caa67daeca8a1316c7e055e3c">llvm::VPlan::getTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#abaad22a81f7fa4ce5b60ec619ac14c37">llvm::VPValue::replaceAllUsesWith</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#af0932bb43954178036c87ea2ee5f112c">llvm::VPValue::users</a>.</p>

</div>
</div>

### adjustFixedOrderRecurrences() {#ae64d6953a1334207d9e7d9cd2587ee9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPlanTransforms::adjustFixedOrderRecurrences (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder">VPBuilder</a> &amp; Builder)</td>
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

<p>Try to have all users of fixed-order recurrences appear after the recipe defining their previous value, by either sinking users or hoisting recipes defining their previous value (and its operands).</p>


<p>Then introduce FirstOrderRecurrenceSplice VPInstructions to combine the value from the recurrence phis and previous values.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if all users of fixed-order recurrences could be re-arranged as needed or false if it is not possible. In the latter case, <span class="doxyComputerOutput">Plan</span> is not valid.</p></dd>
</dl>


<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a>, definition at line 1208 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#accbbcc76f9eb947b3804ad96beb2bbd2">llvm::VPBuilder::createNaryOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2a811727530f9a54b651d638943d34aa61">llvm::VPInstruction::FirstOrderRecurrenceSplice</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a1ae2cb3c63b4d67324ddc947fb9696fc">llvm::VPRegionBlock::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a72533c6b54501809628b9daee79b9d18">llvm::VPBasicBlock::getFirstNonPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a6c88376daf23b16ad26b7ac6c224d21e">llvm::VPRecipeBase::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a9396319801f74828cfbd94177f38eabc">hoistPreviousBeforeFORUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a668c6f14a461ccf0ee11c9c7a076a901">llvm::VPBasicBlock::phis</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#aa0641ae965656ff9988d67a35140e4d9">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::recalculate</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#afc190306945dd17129c24477566099ce">llvm::VPBuilder::setInsertPoint</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a4a5b1db18197a65d0f6a487f2e236921">sinkRecurrenceUsersAfterPrevious</a>.</p>

</div>
</div>

### clearReductionWrapFlags() {#ace9e1e6e7295914973dec18350b382ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPlanTransforms::clearReductionWrapFlags (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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

<p>Clear NSW/NUW flags from reduction instructions if necessary.</p>

<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a>, definition at line 1256 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#aa70c8f392e8295a96bfd493337e122fa">collectUsersRecursively</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a89e9d5a5838c63159df1aed56f600ef1">llvm::RecurrenceDescriptor::getRecurrenceKind</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea62b6d55816cf737bfc6f42e60df1a3f2">llvm::Mul</a> and <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a668c6f14a461ccf0ee11c9c7a076a901">llvm::VPBasicBlock::phis</a>.</p>

</div>
</div>

### convertToConcreteRecipes() {#a63e564d621011fac5978d18138121e5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPlanTransforms::convertToConcreteRecipes (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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

<p>Lower abstract recipes to concrete ones, that can be codegen'd.</p>

<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a>, definition at line 2046 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a0360eea6cebcb1470f84b11f7ba51f16">llvm::VPBlockUtils::blocksOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a1c868dfd250ff9592c06dd61a7fb0bcf">llvm::VPlan::getEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a495c27cd70886cb8647df0ecdd9cc63d">llvm::vp_depth_first_deep</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>.</p>

</div>
</div>

### createAndOptimizeReplicateRegions() {#a42d43068c576be2a1cd514f620246004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPlanTransforms::createAndOptimizeReplicateRegions (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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

<p>Wrap predicated VPReplicateRecipes with a mask operand in an if-then region block and remove the mask operand.</p>


<p>Optimize the created regions by iteratively sinking scalar operands into the region, followed by merging regions until no improvements are remaining.</p>


<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a>, definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6e46200e5b228c903356e02904987051">addReplicateRegions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsimplifycfg-cpp/#a5a5d8a7a6d46886bfb6350ed47c0f225">mergeBlocksIntoPredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a4b251734aba716917922f4ab216436c1">mergeReplicateRegionsIntoSuccessors</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a1536feae2abb3570ac032768a53ddd00">sinkScalarOperands</a>.</p>


<p>Referenced by <a href="#ae3449b993cd1c459995c2fe13ef50892">optimize</a>.</p>

</div>
</div>

### createInterleaveGroups() {#aa88371693bc18186386b04e8c45a30e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPlanTransforms::createInterleaveGroups (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/interleavegroup">InterleaveGroup</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &gt; * &gt; &amp; InterleaveGroups, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder">VPRecipeBuilder</a> &amp; RecipeBuilder, bool ScalarEpilogueAllowed)</td>
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



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a>, definition at line 1970 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#aac9dfb61b37082dca00de284bb3309e8">llvm::VPRecipeBase::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af65afd02332c4f21c2fab7d217d6600f">llvm::Instruction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a3be8d7833df422f3538ddb13af69bd70">llvm::VPValue::getDefiningRecipe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2922c0c507ccec5bea4642aff9e2e328">llvm::getLoadStorePointerOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12126a4bea94833696dc67e0431e829">llvm::getLoadStoreType</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ac38d49d70b5f78779e83abdf4dcb4be0">llvm::VPlan::getOrAddLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#af5f874dc688e86699e648825bfcbf495">llvm::VPRecipeBuilder::getRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdef/#a76a983b694720483a3dd9fe57314e39b">llvm::VPDef::getVPSingleValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdominatortree/#a044ef784dc6a77995842977a9956013f">llvm::VPDominatorTree::properlyDominates</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#aa0641ae965656ff9988d67a35140e4d9">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::recalculate</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#abaad22a81f7fa4ce5b60ec619ac14c37">llvm::VPValue::replaceAllUsesWith</a>.</p>

</div>
</div>

### dropPoisonGeneratingRecipes() {#aa0f143b8d4693978b984f0639c90e508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPlanTransforms::dropPoisonGeneratingRecipes (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *)&gt; BlockNeedsPredication)</td>
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

<p>Drop poison flags from recipes that may generate a poison value that is used after vectorization, even when their operands are not poison.</p>


<p>Those recipes meet the following conditions:</p>


<ul class="doxyList ">
<li>Contribute to the address computation of a recipe generating a widen memory load/store (VPWidenMemoryInstructionRecipe or <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe">VPInterleaveRecipe</a>).</li>
<li>Such a widen memory load/store has at least one underlying <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> that is in a basic block that needs predication and after vectorization the generated instruction won't be predicated. Uses <span class="doxyComputerOutput">BlockNeedsPredication</span> to check if a block needs predicating. TODO: Replace BlockNeedsPredication callback with retrieving info from <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> directly.</li>
</ul>

<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a>, definition at line 1873 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a0360eea6cebcb1470f84b11f7ba51f16">llvm::VPBlockUtils::blocksOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#ab3b191f35221f351f77883447fef4019">llvm::VPBuilder::createOverflowingOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a1c868dfd250ff9592c06dd61a7fb0bcf">llvm::VPlan::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavegroup/#a5085afe1fa721f3ef5bf09ca7fc7537c">llvm::InterleaveGroup&lt; InstTy &gt;::getMember</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavegroup/#af81c826ee51addc3321e4ef1c1934696">llvm::InterleaveGroup&lt; InstTy &gt;::getNumMembers</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a5fe7dd2466300bd8747d81384a7ced5d">llvm::VPValue::getUnderlyingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdef/#a76a983b694720483a3dd9fe57314e39b">llvm::VPDef::getVPSingleValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#a146cd384ae370a9b6de9cd181ad4ec14">llvm::VPlanPatternMatch::m_BinaryOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#abce81cbd0e36ab26b74909f7d9135bf5">llvm::VPlanPatternMatch::m_VPValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a11d83265a9e4ff6c6ecd3cf222ad0208">llvm::VPUser::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a495c27cd70886cb8647df0ecdd9cc63d">llvm::vp_depth_first_deep</a>.</p>

</div>
</div>

### handleUncountableEarlyExit() {#ac2fcd61c17c94d7e9d10b24b718c812e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPlanTransforms::handleUncountableEarlyExit (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * OrigLoop, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * UncountableExitingBlock, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder">VPRecipeBuilder</a> &amp; RecipeBuilder)</td>
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

<p>Update <span class="doxyComputerOutput">Plan</span> to account for the uncountable early exit block in <span class="doxyComputerOutput">UncountableExitingBlock</span> by.</p>


<ul class="doxyList ">
<li>updating the condition exiting the vector loop to include the early exit conditions</li>
<li>splitting the original middle block to branch to the early exit block if taken.</li>
</ul>

<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a>, definition at line 2065 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2aeb4304c45f6343ca9188dbe52456a969">llvm::VPInstruction::AnyOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2a0062eccdb4956531f7b6a3cf71c3320c">llvm::VPInstruction::BranchOnCond</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2a49dcace93798ddd457a9d4e584bbc9a2">llvm::VPInstruction::BranchOnCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a40bc7fec35d7093efcdbadf566d6b5ee">llvm::VPBlockUtils::connectBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#a0b968ad86013a173bed6701425715dfb">llvm::VPBuilder::createICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#accbbcc76f9eb947b3804ad96beb2bbd2">llvm::VPBuilder::createNaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#acf2cdb4ec71a22869d4c491e220d6f0b">llvm::VPBuilder::createNot</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#aa1202b66a60b632b7adbdee13a20ad7e">llvm::VPlan::createVPBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#aa12c0d3acb3f625ee09d2919907d4067">llvm::VPlan::createVPIRBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#aac9dfb61b37082dca00de284bb3309e8">llvm::VPRecipeBase::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a38a607d72d35cad5060b4cd7b5934bb5">llvm::VPRecipeBuilder::getBlockInMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#add3be1d1d9e5b1ee2014c32d21bf2b5b">llvm::VPRegionBlock::getExiting</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a995b2a034ffc26dcd2f3a679f9d2feea">llvm::VPlan::getMiddleBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#afd50c2de451ac9fc0865dc747dd2d485">llvm::LoopBase&lt; BlockT, LoopT &gt;::getUniqueExitBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a7951985b28c0786b4ca50f061172ff22">llvm::VPRecipeBuilder::getVPValueOrAddLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a2057d0749eedf6749f9e1cc6694eb1fd">llvm::VPBlockUtils::insertOnEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#add6179d3564ac5ea4736366b93d23829">llvm::VPValue::isLiveIn</a> and <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a43f7e15ac1a813112684effc1e5593a4">llvm::VPBlockBase::swapSuccessors</a>.</p>

</div>
</div>

### optimize() {#ae3449b993cd1c459995c2fe13ef50892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPlanTransforms::optimize (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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

<p>Apply VPlan-to-VPlan optimizations to <span class="doxyComputerOutput">Plan</span>, including induction recipe optimizations, dead recipe removal, replicate region optimizations and block merging.</p>

<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a>, definition at line 1441 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="#a42d43068c576be2a1cd514f620246004">createAndOptimizeReplicateRegions</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad9053d6ed9627166c144b8895d1c1010">llvm::VPlan::getCanonicalIV</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#ac8744d8abf2a7ed185cc14f0a305cf8e">llvm::VPCanonicalIVPHIRecipe::getScalarType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6bc9d4e47e8a41e60f4bedae712f0c03">legalizeAndOptimizeInductions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a9daa918c2c6be9aa9ca401f69cc75302">licm</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsimplifycfg-cpp/#a5a5d8a7a6d46886bfb6350ed47c0f225">mergeBlocksIntoPredecessors</a>, <a href="#aaca9dd97d4c523d8c65274654abe4eb9">removeDeadRecipes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#aefd03ef5fc77c520e27fe794e8ec93e9">removeRedundantCanonicalIVs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a8a0202a443a527ba17fcd111497feb7d">removeRedundantExpandSCEVRecipes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a2ff7a57c84a06ee83b0a28763db85c3f">removeRedundantInductionCasts</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a74cb3294789bc24526bcadbf6b466714">simplifyRecipes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a36d6728b8c3cfca0a9bd02c3f0273477">llvm::LoopVectorizationPlanner::buildVPlans</a>.</p>

</div>
</div>

### optimizeForVFAndUF() {#af25d938764b8634e70e95ff3f0c35129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPlanTransforms::optimizeForVFAndUF (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> BestVF, unsigned BestUF, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE)</td>
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

<p>Optimize <span class="doxyComputerOutput">Plan</span> based on <span class="doxyComputerOutput">BestVF</span> and <span class="doxyComputerOutput">BestUF</span>.</p>


<p>This may restrict the resulting plan to <span class="doxyComputerOutput">BestVF</span> and <span class="doxyComputerOutput">BestUF</span>.</p>


<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a>, definition at line 978 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a23773e962f9a56c9bdf13f7668b063a5">llvm::VPBasicBlock::appendRecipe</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#ad0efc053a4e5325214b6de6f9f6e49d7">llvm::VPBasicBlock::back</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2a0062eccdb4956531f7b6a3cf71c3320c">llvm::VPInstruction::BranchOnCond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a40bc7fec35d7093efcdbadf566d6b5ee">llvm::VPBlockUtils::connectBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a61f1451694a3638db85170c7f55d5581">llvm::VPBlockUtils::disconnectBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad9053d6ed9627166c144b8895d1c1010">llvm::VPlan::getCanonicalIV</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aff9e533399d91febd63fa4bfe82a42a7">llvm::ScalarEvolution::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#adfad3d829fd98014f225d55b4a924819">llvm::ScalarEvolution::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a1ae2cb3c63b4d67324ddc947fb9696fc">llvm::VPRegionBlock::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a28da654f916bf44da5513b6f1788835c">llvm::VPBlockBase::getExitingBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ac38d49d70b5f78779e83abdf4dcb4be0">llvm::VPlan::getOrAddLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#ac8744d8abf2a7ed185cc14f0a305cf8e">llvm::VPCanonicalIVPHIRecipe::getScalarType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a5999b0390c92ee4af2544fe9772454bf">llvm::vputils::getSCEVExprForVPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#a10ca5eacc61b5669880de2f8b0cff33c">llvm::PredicatedScalarEvolution::getSE</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aa1bb4808c7a5db9f8ed3f479c78c4b5e">llvm::VPBlockBase::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aebc0e1a3379ed4fd614889e24b8ea48c">llvm::VPBlockBase::getSingleSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a2f5fc19caa67daeca8a1316c7e055e3c">llvm::VPlan::getTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a6e9c2a69cd9bc0e46626f5302a03d3da">llvm::VPlan::hasUF</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a633dd97e642c10e8aa1dff2bd2874edb">llvm::VPlan::hasVF</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a445c0cf40cd4a28c8b53579dfab9a193">llvm::IsaPred</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#af74112dae88db73eb5484821b6f0fccd">llvm::ScalarEvolution::isKnownPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#a4541962f9c18aacceb7243520eb15e1f">llvm::SCEV::isZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#a35cc851a200ea1bb42140e0db2bd3274">llvm::VPlanPatternMatch::m_ActiveLaneMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#ab0e78b42dfbac0cbe15c785c4b815ba4">llvm::VPlanPatternMatch::m_BranchOnCond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#a781b43897f427e5c19a39c57259146ed">llvm::VPlanPatternMatch::m_BranchOnCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#abce81cbd0e36ab26b74909f7d9135bf5">llvm::VPlanPatternMatch::m_VPValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#aa5b3e822013fe51665e9bddc4874cd48">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::multiplyCoefficientBy</a>, <a href="#aaca9dd97d4c523d8c65274654abe4eb9">removeDeadRecipes</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#af1d539e508015e09e4b9fdb7d020da0e">llvm::VPlan::setUF</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a7ee6ab8541efab3e456a38d6c1fa1be2">llvm::VPlan::setVF</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a74cb3294789bc24526bcadbf6b466714">simplifyRecipes</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4474bfb1e0ca062e5bfe2a35980e7d19">llvm::vp_depth_first_shallow</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>.</p>

</div>
</div>

### optimizeInductionExitUsers() {#a3a573419fed83f23b6bf70ac6731dbfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPlanTransforms::optimizeInductionExitUsers (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; &amp; EndValues)</td>
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

<p>If there's a single exit block, optimize its phi recipes that use exiting IV values by feeding them precomputed end values instead, possibly taken one step backwards.</p>

<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a>, definition at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad9053d6ed9627166c144b8895d1c1010">llvm::VPlan::getCanonicalIV</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a85800ca7a821f540ad2d6d4d3c2d4208">llvm::VPlan::getExitBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#ac6f0bd9ed63fe4a784697d73ae3b6fa0">llvm::VPValue::getLiveInIRValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a995b2a034ffc26dcd2f3a679f9d2feea">llvm::VPlan::getMiddleBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#aa35433def455d3f76738769247678052">getOptimizableIVOf</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ac38d49d70b5f78779e83abdf4dcb4be0">llvm::VPlan::getOrAddLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#ac8744d8abf2a7ed185cc14f0a305cf8e">llvm::VPCanonicalIVPHIRecipe::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aa1bb4808c7a5db9f8ed3f479c78c4b5e">llvm::VPBlockBase::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#ac98e46fa8ff66b24ce678ddea88a23ac">llvm::VPBasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/vptypeanalysis/#aac3fb75b481d61e325b6d869d0f5f278">llvm::VPTypeAnalysis::inferScalarType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0b2ca98dc28c61793ff5c90d23e5f14e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::lookup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2471be3f1b50002f54bf45c590d8d41b">llvm::PatternMatch::m_SpecificInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#a5438a63c52f3576904c86e1bf0c7a9ab">llvm::VPlanPatternMatch::m_VPInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#abce81cbd0e36ab26b74909f7d9135bf5">llvm::VPlanPatternMatch::m_VPValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### removeDeadRecipes() {#aaca9dd97d4c523d8c65274654abe4eb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPlanTransforms::removeDeadRecipes (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
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

<p>Remove dead recipes from <span class="doxyComputerOutput">Plan</span>.</p>

<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a>, definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a0360eea6cebcb1470f84b11f7ba51f16">llvm::VPBlockUtils::blocksOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a1c868dfd250ff9592c06dd61a7fb0bcf">llvm::VPlan::getEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6ba2ffb17342f2a0c54adaba2344cab0">isDeadRecipe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>, <a href="#ae3449b993cd1c459995c2fe13ef50892">optimize</a>, <a href="#af25d938764b8634e70e95ff3f0c35129">optimizeForVFAndUF</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a13368acf4fbb5816c3d82099b11519b1">preparePlanForMainVectorLoop</a> and <a href="#a7a1cca51bb9bce4efad1063dcf158967">unrollByUF</a>.</p>

</div>
</div>

### truncateToMinimalBitwidths() {#ae61793492431f138869f097a5f31bd32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPlanTransforms::truncateToMinimalBitwidths (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, uint64_t &gt; &amp; MinBWs)</td>
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

<p>Insert truncates and extends for any truncated recipe.</p>


<p>Redundant casts will be folded later.</p>


<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a>, definition at line 1308 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a23773e962f9a56c9bdf13f7668b063a5">llvm::VPBasicBlock::appendRecipe</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a0360eea6cebcb1470f84b11f7ba51f16">llvm::VPBlockUtils::blocksOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a836d9cba6deced0bb1fa7333ce5afd3a">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a8757ce7071547a0410c82cc096b1ec9a">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad9053d6ed9627166c144b8895d1c1010">llvm::VPlan::getCanonicalIV</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#ac8744d8abf2a7ed185cc14f0a305cf8e">llvm::VPCanonicalIVPHIRecipe::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a5fe7dd2466300bd8747d81384a7ced5d">llvm::VPValue::getUnderlyingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#aee894572833ce02ad06c067d44f65b48">llvm::VPlan::getVectorPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/vptypeanalysis/#aac3fb75b481d61e325b6d869d0f5f278">llvm::VPTypeAnalysis::inferScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a8859e5e8cad5653b278964f47414fd84">llvm::VPRecipeBase::insertBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a445c0cf40cd4a28c8b53579dfab9a193">llvm::IsaPred</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#abca23bddf517f69d28c6d30c58a7b6f9">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::lookup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#a5693223ba55481975ccee9dbaa716d6f">llvm::VPlanPatternMatch::m_Binary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#abce81cbd0e36ab26b74909f7d9135bf5">llvm::VPlanPatternMatch::m_VPValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#abaad22a81f7fa4ce5b60ec619ac14c37">llvm::VPValue::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#acf4c09e1f30cdd4e0b5b1b8a236ead34">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a495c27cd70886cb8647df0ecdd9cc63d">llvm::vp_depth_first_deep</a>.</p>

</div>
</div>

### tryAddExplicitVectorLength() {#ad16bff9364e25351de81704fe81fd229}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPlanTransforms::tryAddExplicitVectorLength (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; unsigned &gt; &amp; MaxSafeElements)</td>
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

<p>Add a <a href="/web-llvm/docs/api/classes/llvm/vpevlbasedivphirecipe">VPEVLBasedIVPHIRecipe</a> and related recipes to <span class="doxyComputerOutput">Plan</span> and replaces all uses except the canonical IV increment of <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe">VPCanonicalIVPHIRecipe</a> with a <a href="/web-llvm/docs/api/classes/llvm/vpevlbasedivphirecipe">VPEVLBasedIVPHIRecipe</a>.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe">VPCanonicalIVPHIRecipe</a> is only used to control the loop after this transformation.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the transformation succeeds, or false if it doesn't.</p></dd>
</dl>


<p><a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe">VPCanonicalIVPHIRecipe</a> is used only for loop iterations counting after this transformation.</p>


<p>The function uses the following definitions: StartV is the canonical induction start value.</p>


<p>The function adds the following recipes:</p>


<p>vector.ph: ...</p>


<p>vector.body: ... EVLPhi = EXPLICIT-VECTOR-LENGTH-BASED-IV-PHI [ StartV, vector.ph ], [ NextEVLIV, vector.body ] AVL = sub original TC, EVLPhi VPEVL = EXPLICIT-VECTOR-LENGTH AVL ... NextEVLIV = add IVSize (cast i32 VPEVVL to IVSize), EVLPhi ...</p>


<p>If MaxSafeElements is provided, the function adds the following recipes: vector.ph: ...</p>


<p>vector.body: ... EVLPhi = EXPLICIT-VECTOR-LENGTH-BASED-IV-PHI [ StartV, vector.ph ], [ NextEVLIV, vector.body ] AVL = sub original TC, EVLPhi cmp = cmp ult AVL, MaxSafeElements SAFE_AVL = select cmp, AVL, MaxSafeElements VPEVL = EXPLICIT-VECTOR-LENGTH SAFE_AVL ... NextEVLIV = add IVSize (cast i32 VPEVL to IVSize), EVLPhi ...</p>


<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a>, definition at line 1812 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#a0b968ad86013a173bed6701425715dfb">llvm::VPBuilder::createICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#accbbcc76f9eb947b3804ad96beb2bbd2">llvm::VPBuilder::createNaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#aebcef96452964d918ecdf28d1835115e">llvm::VPBuilder::createSelect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2a8c9deab6571a0b4db0c69c64c0d682eb">llvm::VPInstruction::ExplicitVectorLength</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad9053d6ed9627166c144b8895d1c1010">llvm::VPlan::getCanonicalIV</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a733c4c530159a8b86223376c0696430e">llvm::VPRecipeBase::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ac38d49d70b5f78779e83abdf4dcb4be0">llvm::VPlan::getOrAddLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a2f5fc19caa67daeca8a1316c7e055e3c">llvm::VPlan::getTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a8859e5e8cad5653b278964f47414fd84">llvm::VPRecipeBase::insertBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a445c0cf40cd4a28c8b53579dfab9a193">llvm::IsaPred</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#af1d539e508015e09e4b9fdb7d020da0e">llvm::VPlan::setUF</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5f39858b5d6d72b92c138916c64c90ba">transformRecipestoEVLRecipes</a>.</p>

</div>
</div>

### unrollByUF() {#a7a1cca51bb9bce4efad1063dcf158967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPlanTransforms::unrollByUF (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, unsigned UF, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx)</td>
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

<p>Explicitly unroll <span class="doxyComputerOutput">Plan</span> by <span class="doxyComputerOutput">UF</span>.</p>

<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a>, definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a0360eea6cebcb1470f84b11f7ba51f16">llvm::VPBlockUtils::blocksOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2ad271d9d05bf5644dfa1487b3fc42a131">llvm::VPInstruction::CanonicalIVIncrementForPart</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/httpclient-cpp/#a0b91b2b50d54e38aa1e8e31e56c31357">Cleanup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a1c868dfd250ff9592c06dd61a7fb0bcf">llvm::VPlan::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af45c4dc83c083c5ae914d96fd3ce96">llvm::make_scope_exit</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a668c6f14a461ccf0ee11c9c7a076a901">llvm::VPBasicBlock::phis</a>, <a href="#aaca9dd97d4c523d8c65274654abe4eb9">removeDeadRecipes</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#af1d539e508015e09e4b9fdb7d020da0e">llvm::VPlan::setUF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a495c27cd70886cb8647df0ecdd9cc63d">llvm::vp_depth_first_deep</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>.</p>

</div>
</div>

### VPInstructionsToVPRecipes() {#ad210afaefb4884ac5008dd5fbaf1cbf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPlanTransforms::VPInstructionsToVPRecipes (<a href="/web-llvm/docs/api/namespaces/llvm/#aefc42f3cefc5a839ca925b4cb3ae4a7b">VPlanPtr</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor">InductionDescriptor</a> *(<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *)&gt; GetIntOrFpInductionDescriptor, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI)</td>
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

<p>Replaces the VPInstructions in <span class="doxyComputerOutput">Plan</span> with corresponding widen recipes.</p>

<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a0360eea6cebcb1470f84b11f7ba51f16">llvm::VPBlockUtils::blocksOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdef/#a31492b9d8412415c2dae85e33e2748fd">llvm::VPDef::getNumDefinedValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a064976a6c7458b10c24021b7334cec2a">llvm::vputils::getOrCreateVPValueForSCEVExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a5fe7dd2466300bd8747d81384a7ced5d">llvm::VPValue::getUnderlyingValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11c66d01880f53332fc7ad53f565b039">llvm::getVectorIntrinsicIDForCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdef/#a76a983b694720483a3dd9fe57314e39b">llvm::VPDef::getVPSingleValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a8859e5e8cad5653b278964f47414fd84">llvm::VPRecipeBase::insertBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a0b931781aa589c6ebe64a76c1447e5b2">llvm::User::operands</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#abaad22a81f7fa4ce5b60ec619ac14c37">llvm::VPValue::replaceAllUsesWith</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp">VPlanTransforms.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-h">VPlanTransforms.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
