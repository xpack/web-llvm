---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/vpwidenstoreevlrecipe
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `VPWidenStoreEVLRecipe` Struct Reference

<p>A recipe for widening store operations with vector-predication intrinsics, using the value to store, the address to store to, the explicit vector length and an optional mask. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::VPWidenStoreEVLRecipe { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">Transforms/Vectorize/VPlan.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe">VPWidenMemoryRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A common base class for widening memory operations. <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf7c8c81965f29eb6190b3eaf03e7e10">VPWidenStoreEVLRecipe</a> (VPWidenStoreRecipe &amp;S, VPValue &amp;EVL, VPValue *Mask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a9373eaa0b8d7072cd86c71a783e6b0">getStoredValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the address accessed by this recipe. <a href="#a0a9373eaa0b8d7072cd86c71a783e6b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2ed3e1edcea346d3a7e76e766b2ff51">getEVL</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the EVL operand. <a href="#ae2ed3e1edcea346d3a7e76e766b2ff51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c719942d2fa4ca51fe66c92b9ab834c">execute</a> (VPTransformState &amp;State) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate the wide store or scatter. <a href="#a1c719942d2fa4ca51fe66c92b9ab834c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac85fcb83463051a6b34aa7e323cbeb3d">computeCost</a> (ElementCount VF, VPCostContext &amp;Ctx) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cost of this <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe">VPWidenStoreEVLRecipe</a>. <a href="#ac85fcb83463051a6b34aa7e323cbeb3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62d6c125728278eddd0bf38364a471f9">print</a> (raw_ostream &amp;O, const Twine &amp;Indent, VPSlotTracker &amp;SlotTracker) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the recipe. <a href="#a62d6c125728278eddd0bf38364a471f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a37ffac00db5fca0c5df19b1ebe4980">onlyFirstLaneUsed</a> (const VPValue *Op) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recipe only uses the first lane of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#a7a37ffac00db5fca0c5df19b1ebe4980">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A recipe for widening store operations with vector-predication intrinsics, using the value to store, the address to store to, the explicit vector length and an optional mask.</p>

<p>Definition at line 3152 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VPWidenStoreEVLRecipe() {#abf7c8c81965f29eb6190b3eaf03e7e10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPWidenStoreEVLRecipe::VPWidenStoreEVLRecipe (<a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe">VPWidenStoreRecipe</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> &amp; EVL, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Mask)</td>
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



<p>Definition at line 3153 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#af3caef2aa9a6ef6739a11c87df6f511f">llvm::VPWidenMemoryRecipe::getAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a629e42fdc4157d2642a1f5d565d3d538">llvm::VPWidenMemoryRecipe::getIngredient</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a93408766f5852c2fd01c55ffd668bcbc">llvm::VPWidenStoreRecipe::getStoredValue</a> and <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a683571dc9876623d7cffc7e6f0fd67f7">llvm::VPWidenMemoryRecipe::VPWidenMemoryRecipe</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### computeCost() {#ac85fcb83463051a6b34aa7e323cbeb3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost VPWidenStoreEVLRecipe::computeCost (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="/web-llvm/docs/api/structs/llvm/vpcostcontext">VPCostContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the cost of this <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe">VPWidenStoreEVLRecipe</a>.</p>

<p>Declaration at line 3172 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 2816 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a515cd094f92579b8b4ae0b01e7f92257">llvm::VPWidenMemoryRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a62abe5cb2b696369276d5d429a59bb89">llvm::VPWidenMemoryRecipe::Consecutive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d97f0780a320d53641729a2d8371b74">llvm::getLoadStoreAddressSpace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4370c1523db2ede8d9791b76da2ab798">llvm::getLoadStoreAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12126a4bea94833696dc67e0431e829">llvm::getLoadStoreType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a4517e86770c6431f2e87adce2830db4f">llvm::VPWidenMemoryRecipe::Ingredient</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a0193b5e5ddbf6965dc1aabf875e591e2">llvm::VPWidenMemoryRecipe::IsMasked</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a07ccf79fbeeda00be7ebc5a45b90355c">llvm::VPWidenMemoryRecipe::Reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ecaea788d98147161f25d5adc3ec6ce7e1f">llvm::TargetTransformInfo::SK_Reverse</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae5262cc0e3a55bc74891cb8751d3b188">llvm::toVectorTy</a>.</p>

</div>
</div>

### execute() {#a1c719942d2fa4ca51fe66c92b9ab834c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPWidenStoreEVLRecipe::execute (<a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> &amp; State)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate the wide store or scatter.</p>

<p>Declaration at line 3169 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 2776 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ae5d05ec2b9a60806746addff3f2a71a9">llvm::CallBase::addParamAttr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#a154fa9a8453f440902ba70defcb9ba44">createReverseEVL</a>, <a href="/web-llvm/docs/api/classes/llvm/vectorbuilder/#af67c409374664799941513c682357a75">llvm::VectorBuilder::createVectorInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a40ed7274ff11f079e5b5eae34c818c51">llvm::IRBuilderBase::CreateVectorSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#af3caef2aa9a6ef6739a11c87df6f511f">llvm::VPWidenMemoryRecipe::getAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a733c4c530159a8b86223376c0696430e">llvm::VPRecipeBase::getDebugLoc</a>, <a href="#ae2ed3e1edcea346d3a7e76e766b2ff51">getEVL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4370c1523db2ede8d9791b76da2ab798">llvm::getLoadStoreAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a6dab5a878379d5ee92940853d3feb53d">llvm::VPWidenMemoryRecipe::getMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c184773989d9b05fcc2bf4f5840c1db">llvm::getStoredValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a42ce8aa34864a9d974958b9d3d36ad17">llvm::IRBuilderBase::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#afb8975f28d8418cad8ea770575736b81">llvm::Attribute::getWithAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a4517e86770c6431f2e87adce2830db4f">llvm::VPWidenMemoryRecipe::Ingredient</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a12482914e64512048aec3bc1ae42eebb">llvm::VPWidenMemoryRecipe::isConsecutive</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#af584264f3ca2bb1134c9e8471fcc6ab7">llvm::VPWidenMemoryRecipe::isReverse</a>, <a href="/web-llvm/docs/api/classes/llvm/vectorbuilder/#a5cd4fcdcc6ed6c8bba3f46c06c17a2a3">llvm::VectorBuilder::setEVL</a> and <a href="/web-llvm/docs/api/classes/llvm/vectorbuilder/#ab0c56056ac6ee6a08c82ba4323df216e">llvm::VectorBuilder::setMask</a>.</p>

</div>
</div>

### getEVL() {#ae2ed3e1edcea346d3a7e76e766b2ff51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPWidenStoreEVLRecipe::getEVL ()</td>
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

<p>Return the EVL operand.</p>

<p>Definition at line 3166 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a6e1b252a9bbdc1a440fb57a6257b97f4">llvm::VPUser::getOperand</a>.</p>


<p>Referenced by <a href="#a1c719942d2fa4ca51fe66c92b9ab834c">execute</a> and <a href="#a7a37ffac00db5fca0c5df19b1ebe4980">onlyFirstLaneUsed</a>.</p>

</div>
</div>

### getStoredValue() {#a0a9373eaa0b8d7072cd86c71a783e6b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPWidenStoreEVLRecipe::getStoredValue ()</td>
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

<p>Return the address accessed by this recipe.</p>

<p>Definition at line 3163 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a6e1b252a9bbdc1a440fb57a6257b97f4">llvm::VPUser::getOperand</a> and <a href="#a0a9373eaa0b8d7072cd86c71a783e6b0">getStoredValue</a>.</p>


<p>Referenced by <a href="#a0a9373eaa0b8d7072cd86c71a783e6b0">getStoredValue</a> and <a href="#a7a37ffac00db5fca0c5df19b1ebe4980">onlyFirstLaneUsed</a>.</p>

</div>
</div>

### onlyFirstLaneUsed() {#a7a37ffac00db5fca0c5df19b1ebe4980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPWidenStoreEVLRecipe::onlyFirstLaneUsed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Op)</td>
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

<p>Returns true if the recipe only uses the first lane of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>

<p>Definition at line 3182 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#af3caef2aa9a6ef6739a11c87df6f511f">llvm::VPWidenMemoryRecipe::getAddr</a>, <a href="#ae2ed3e1edcea346d3a7e76e766b2ff51">getEVL</a>, <a href="#a0a9373eaa0b8d7072cd86c71a783e6b0">getStoredValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a12482914e64512048aec3bc1ae42eebb">llvm::VPWidenMemoryRecipe::isConsecutive</a> and <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a11d83265a9e4ff6c6ecd3cf222ad0208">llvm::VPUser::operands</a>.</p>

</div>
</div>

### print() {#a62d6c125728278eddd0bf38364a471f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPWidenStoreEVLRecipe::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Indent, <a href="/web-llvm/docs/api/classes/llvm/vpslottracker">VPSlotTracker</a> &amp; SlotTracker)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the recipe.</p>

<p>Declaration at line 3177 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 2842 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a0112474f9dc69912e4c067594692d15b">llvm::VPUser::printOperands</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
