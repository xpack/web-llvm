---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/vpwidenloadrecipe
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `VPWidenLoadRecipe` Struct Reference

<p>A recipe for widening load operations, using the address to load from and an optional mask. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::VPWidenLoadRecipe { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a723d7043589bac799ae42c256c12a4e4">VPWidenLoadRecipe</a> (LoadInst &amp;Load, VPValue *Addr, VPValue *Mask, bool Consecutive, bool Reverse, DebugLoc DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe">VPWidenLoadRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cd41c107c1039e2a5550d777076db35">clone</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone the current recipe. <a href="#a8cd41c107c1039e2a5550d777076db35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04cd50581d6d587662f7e3e58042b37e">VP_CLASSOF_IMPL</a> (VPDef::VPWidenLoadSC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c2b787dbd70d3fbd4f3699342eec925">execute</a> (VPTransformState &amp;State) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate a wide load or gather. <a href="#a7c2b787dbd70d3fbd4f3699342eec925">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac293be3f7d76772b820f58925b6b14e1">print</a> (raw_ostream &amp;O, const Twine &amp;Indent, VPSlotTracker &amp;SlotTracker) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the recipe. <a href="#ac293be3f7d76772b820f58925b6b14e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a769d05569a9befd640244f159ba7f82a">onlyFirstLaneUsed</a> (const VPValue *Op) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recipe only uses the first lane of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#a769d05569a9befd640244f159ba7f82a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A recipe for widening load operations, using the address to load from and an optional mask.</p>

<p>Definition at line 3033 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VPWidenLoadRecipe() {#a723d7043589bac799ae42c256c12a4e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPWidenLoadRecipe::VPWidenLoadRecipe (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> &amp; Load, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Mask, bool Consecutive, bool Reverse, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL)</td>
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



<p>Definition at line 3034 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a62abe5cb2b696369276d5d429a59bb89">llvm::VPWidenMemoryRecipe::Consecutive</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a07ccf79fbeeda00be7ebc5a45b90355c">llvm::VPWidenMemoryRecipe::Reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a5df20a1ac93f5dbd76b326af478e39a8">llvm::VPValue::VPDef</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a8f2e5c044b5e7aad2e59cda1f5eb8ca8">llvm::VPValue::VPValue</a> and <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a683571dc9876623d7cffc7e6f0fd67f7">llvm::VPWidenMemoryRecipe::VPWidenMemoryRecipe</a>.</p>


<p>Referenced by <a href="#a8cd41c107c1039e2a5550d777076db35">clone</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#a8cd41c107c1039e2a5550d777076db35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPWidenLoadRecipe * llvm::VPWidenLoadRecipe::clone ()</td>
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

<p>Clone the current recipe.</p>

<p>Definition at line 3042 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a62abe5cb2b696369276d5d429a59bb89">llvm::VPWidenMemoryRecipe::Consecutive</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#af3caef2aa9a6ef6739a11c87df6f511f">llvm::VPWidenMemoryRecipe::getAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a733c4c530159a8b86223376c0696430e">llvm::VPRecipeBase::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a6dab5a878379d5ee92940853d3feb53d">llvm::VPWidenMemoryRecipe::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a4517e86770c6431f2e87adce2830db4f">llvm::VPWidenMemoryRecipe::Ingredient</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a07ccf79fbeeda00be7ebc5a45b90355c">llvm::VPWidenMemoryRecipe::Reverse</a> and <a href="#a723d7043589bac799ae42c256c12a4e4">VPWidenLoadRecipe</a>.</p>

</div>
</div>

### execute() {#a7c2b787dbd70d3fbd4f3699342eec925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPWidenLoadRecipe::execute (<a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> &amp; State)</td>
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

<p>Generate a wide load or gather.</p>

<p>Declaration at line 3051 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 2595 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#aa1b0638c63ba711320b3bb9c69367ed6">llvm::Value::addMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3313ae2d314fb689cebdaf062d86eec5">llvm::IRBuilderBase::CreateAlignedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#afa922043d31aa2d3410fe0be8791b795">llvm::IRBuilderBase::CreateMaskedGather</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a483f68557374e8fc58f8a294e7f1268e">llvm::IRBuilderBase::CreateMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a69d0103b83202f0339cfb6b018b3c78a">llvm::IRBuilderBase::CreateVectorReverse</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#af3caef2aa9a6ef6739a11c87df6f511f">llvm::VPWidenMemoryRecipe::getAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a733c4c530159a8b86223376c0696430e">llvm::VPRecipeBase::getDebugLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4370c1523db2ede8d9791b76da2ab798">llvm::getLoadStoreAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12126a4bea94833696dc67e0431e829">llvm::getLoadStoreType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a6dab5a878379d5ee92940853d3feb53d">llvm::VPWidenMemoryRecipe::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a4517e86770c6431f2e87adce2830db4f">llvm::VPWidenMemoryRecipe::Ingredient</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a12482914e64512048aec3bc1ae42eebb">llvm::VPWidenMemoryRecipe::isConsecutive</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#af584264f3ca2bb1134c9e8471fcc6ab7">llvm::VPWidenMemoryRecipe::isReverse</a> and <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a07ccf79fbeeda00be7ebc5a45b90355c">llvm::VPWidenMemoryRecipe::Reverse</a>.</p>

</div>
</div>

### onlyFirstLaneUsed() {#a769d05569a9befd640244f159ba7f82a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPWidenLoadRecipe::onlyFirstLaneUsed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Op)</td>
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

<p>Definition at line 3060 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#af3caef2aa9a6ef6739a11c87df6f511f">llvm::VPWidenMemoryRecipe::getAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a12482914e64512048aec3bc1ae42eebb">llvm::VPWidenMemoryRecipe::isConsecutive</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a11d83265a9e4ff6c6ecd3cf222ad0208">llvm::VPUser::operands</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a8f2e5c044b5e7aad2e59cda1f5eb8ca8">llvm::VPValue::VPValue</a>.</p>

</div>
</div>

### print() {#ac293be3f7d76772b820f58925b6b14e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPWidenLoadRecipe::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Indent, <a href="/web-llvm/docs/api/classes/llvm/vpslottracker">VPSlotTracker</a> &amp; SlotTracker)</td>
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

<p>Declaration at line 3055 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 2634 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a3fc47e93505e87044e0861e4142eca20">llvm::VPValue::printAsOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a0112474f9dc69912e4c067594692d15b">llvm::VPUser::printOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a12ceea61a3de5b2f0ff70850f66c5fdc">llvm::VPValue::VPSlotTracker</a>.</p>

</div>
</div>

### VP\_CLASSOF\_IMPL() {#a04cd50581d6d587662f7e3e58042b37e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPWidenLoadRecipe::VP_CLASSOF_IMPL (VPDef::VPWidenLoadSC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3048 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a12ceea61a3de5b2f0ff70850f66c5fdc">llvm::VPValue::VPSlotTracker</a>.</p>

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
