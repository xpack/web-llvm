---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/vpwidenloadevlrecipe
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `VPWidenLoadEVLRecipe` Struct

<p>A recipe for widening load operations with vector-predication intrinsics, using the address to load from, the explicit vector length and an optional mask. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::VPWidenLoadEVLRecipe { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">Transforms/Vectorize/VPlan.h</a>"
</div>

## Base structs

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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae123bdc95f3d36b528edae0a4ff321df">VPWidenLoadEVLRecipe</a> (VPWidenLoadRecipe &amp;L, VPValue &amp;EVL, VPValue *Mask)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aa813347887ce533adf6f76c42c4bf0">getEVL</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the EVL operand. <a href="#a6aa813347887ce533adf6f76c42c4bf0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16471f19bad1ca5212ccbd52c21b8b54">execute</a> (VPTransformState &amp;State) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate the wide load or gather. <a href="#a16471f19bad1ca5212ccbd52c21b8b54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65f435dbf3cc980ce5c58191e436e72f">computeCost</a> (ElementCount VF, VPCostContext &amp;Ctx) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cost of this <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe">VPWidenLoadEVLRecipe</a>. <a href="#a65f435dbf3cc980ce5c58191e436e72f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86fd40dcbb7bf4bd5c2765ff07353fef">print</a> (raw_ostream &amp;O, const Twine &amp;Indent, VPSlotTracker &amp;SlotTracker) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the recipe. <a href="#a86fd40dcbb7bf4bd5c2765ff07353fef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abed0bd6ee69b8083deba69aa189aebc3">onlyFirstLaneUsed</a> (const VPValue *Op) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recipe only uses the first lane of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#abed0bd6ee69b8083deba69aa189aebc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A recipe for widening load operations with vector-predication intrinsics, using the address to load from, the explicit vector length and an optional mask.</p>

<p>Definition at line 3072 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VPWidenLoadEVLRecipe() {#ae123bdc95f3d36b528edae0a4ff321df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPWidenLoadEVLRecipe::VPWidenLoadEVLRecipe (<a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe">VPWidenLoadRecipe</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> &amp; EVL, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Mask)</td>
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



<p>Definition at line 3073 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a629e42fdc4157d2642a1f5d565d3d538">llvm::VPWidenMemoryRecipe::getIngredient</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a5df20a1ac93f5dbd76b326af478e39a8">llvm::VPValue::VPDef</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a8f2e5c044b5e7aad2e59cda1f5eb8ca8">llvm::VPValue::VPValue</a> and <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a683571dc9876623d7cffc7e6f0fd67f7">llvm::VPWidenMemoryRecipe::VPWidenMemoryRecipe</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### computeCost() {#a65f435dbf3cc980ce5c58191e436e72f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost VPWidenLoadEVLRecipe::computeCost (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="/web-llvm/docs/api/structs/llvm/vpcostcontext">VPCostContext</a> &amp; Ctx)</td>
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

<p>Return the cost of this <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe">VPWidenLoadEVLRecipe</a>.</p>

<p>Declaration at line 3090 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 2695 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a515cd094f92579b8b4ae0b01e7f92257">llvm::VPWidenMemoryRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a62abe5cb2b696369276d5d429a59bb89">llvm::VPWidenMemoryRecipe::Consecutive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d97f0780a320d53641729a2d8371b74">llvm::getLoadStoreAddressSpace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4370c1523db2ede8d9791b76da2ab798">llvm::getLoadStoreAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12126a4bea94833696dc67e0431e829">llvm::getLoadStoreType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a4517e86770c6431f2e87adce2830db4f">llvm::VPWidenMemoryRecipe::Ingredient</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a0193b5e5ddbf6965dc1aabf875e591e2">llvm::VPWidenMemoryRecipe::IsMasked</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a07ccf79fbeeda00be7ebc5a45b90355c">llvm::VPWidenMemoryRecipe::Reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ecaea788d98147161f25d5adc3ec6ce7e1f">llvm::TargetTransformInfo::SK_Reverse</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae5262cc0e3a55bc74891cb8751d3b188">llvm::toVectorTy</a>.</p>

</div>
</div>

### execute() {#a16471f19bad1ca5212ccbd52c21b8b54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPWidenLoadEVLRecipe::execute (<a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> &amp; State)</td>
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

<p>Generate the wide load or gather.</p>

<p>Declaration at line 3087 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 2654 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ae5d05ec2b9a60806746addff3f2a71a9">llvm::CallBase::addParamAttr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#a154fa9a8453f440902ba70defcb9ba44">createReverseEVL</a>, <a href="/web-llvm/docs/api/classes/llvm/vectorbuilder/#af67c409374664799941513c682357a75">llvm::VectorBuilder::createVectorInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a40ed7274ff11f079e5b5eae34c818c51">llvm::IRBuilderBase::CreateVectorSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#af3caef2aa9a6ef6739a11c87df6f511f">llvm::VPWidenMemoryRecipe::getAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a733c4c530159a8b86223376c0696430e">llvm::VPRecipeBase::getDebugLoc</a>, <a href="#a6aa813347887ce533adf6f76c42c4bf0">getEVL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4370c1523db2ede8d9791b76da2ab798">llvm::getLoadStoreAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12126a4bea94833696dc67e0431e829">llvm::getLoadStoreType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a6dab5a878379d5ee92940853d3feb53d">llvm::VPWidenMemoryRecipe::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a42ce8aa34864a9d974958b9d3d36ad17">llvm::IRBuilderBase::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#afb8975f28d8418cad8ea770575736b81">llvm::Attribute::getWithAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a4517e86770c6431f2e87adce2830db4f">llvm::VPWidenMemoryRecipe::Ingredient</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a12482914e64512048aec3bc1ae42eebb">llvm::VPWidenMemoryRecipe::isConsecutive</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#af584264f3ca2bb1134c9e8471fcc6ab7">llvm::VPWidenMemoryRecipe::isReverse</a>, <a href="/web-llvm/docs/api/classes/llvm/vectorbuilder/#a5cd4fcdcc6ed6c8bba3f46c06c17a2a3">llvm::VectorBuilder::setEVL</a>, <a href="/web-llvm/docs/api/classes/llvm/vectorbuilder/#ab0c56056ac6ee6a08c82ba4323df216e">llvm::VectorBuilder::setMask</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a8f2e5c044b5e7aad2e59cda1f5eb8ca8">llvm::VPValue::VPValue</a>.</p>

</div>
</div>

### getEVL() {#a6aa813347887ce533adf6f76c42c4bf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPWidenLoadEVLRecipe::getEVL ()</td>
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

<p>Definition at line 3084 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="#a6aa813347887ce533adf6f76c42c4bf0">getEVL</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a6e1b252a9bbdc1a440fb57a6257b97f4">llvm::VPUser::getOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a8f2e5c044b5e7aad2e59cda1f5eb8ca8">llvm::VPValue::VPValue</a>.</p>


<p>Referenced by <a href="#a16471f19bad1ca5212ccbd52c21b8b54">execute</a>, <a href="#a6aa813347887ce533adf6f76c42c4bf0">getEVL</a> and <a href="#abed0bd6ee69b8083deba69aa189aebc3">onlyFirstLaneUsed</a>.</p>

</div>
</div>

### onlyFirstLaneUsed() {#abed0bd6ee69b8083deba69aa189aebc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPWidenLoadEVLRecipe::onlyFirstLaneUsed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Op)</td>
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

<p>Definition at line 3100 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#af3caef2aa9a6ef6739a11c87df6f511f">llvm::VPWidenMemoryRecipe::getAddr</a>, <a href="#a6aa813347887ce533adf6f76c42c4bf0">getEVL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a12482914e64512048aec3bc1ae42eebb">llvm::VPWidenMemoryRecipe::isConsecutive</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a11d83265a9e4ff6c6ecd3cf222ad0208">llvm::VPUser::operands</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a8f2e5c044b5e7aad2e59cda1f5eb8ca8">llvm::VPValue::VPValue</a>.</p>

</div>
</div>

### print() {#a86fd40dcbb7bf4bd5c2765ff07353fef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPWidenLoadEVLRecipe::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Indent, <a href="/web-llvm/docs/api/classes/llvm/vpslottracker">VPSlotTracker</a> &amp; SlotTracker)</td>
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

<p>Declaration at line 3095 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 2721 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a3fc47e93505e87044e0861e4142eca20">llvm::VPValue::printAsOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a0112474f9dc69912e4c067594692d15b">llvm::VPUser::printOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a12ceea61a3de5b2f0ff70850f66c5fdc">llvm::VPValue::VPSlotTracker</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
