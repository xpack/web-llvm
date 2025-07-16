---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vpwidenmemoryrecipe
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VPWidenMemoryRecipe` Class Reference

<p>A common base class for widening memory operations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPWidenMemoryRecipe { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">Transforms/Vectorize/VPlan.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> is a base class modeling a sequence of one or more output IR instructions. <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe">VPWidenLoadEVLRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe for widening load operations with vector-predication intrinsics, using the address to load from, the explicit vector length and an optional mask. <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe">VPWidenLoadRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe for widening load operations, using the address to load from and an optional mask. <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe">VPWidenStoreEVLRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe for widening store operations with vector-predication intrinsics, using the value to store, the address to store to, the explicit vector length and an optional mask. <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe">VPWidenStoreRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe for widening store operations, using the stored value, the address to store to and an optional mask. <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a683571dc9876623d7cffc7e6f0fd67f7">VPWidenMemoryRecipe</a> (const char unsigned SC, Instruction &amp;I, std::initializer_list&lt; VPValue * &gt; Operands, bool Consecutive, bool Reverse, DebugLoc DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe">VPWidenMemoryRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5009f8c3fbc7246d33d2a15a25cbe02a">clone</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone the current recipe. <a href="#a5009f8c3fbc7246d33d2a15a25cbe02a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12482914e64512048aec3bc1ae42eebb">isConsecutive</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the loaded-from / stored-to addresses are consecutive. <a href="#a12482914e64512048aec3bc1ae42eebb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af584264f3ca2bb1134c9e8471fcc6ab7">isReverse</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the consecutive loaded/stored addresses are in reverse order. <a href="#af584264f3ca2bb1134c9e8471fcc6ab7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3caef2aa9a6ef6739a11c87df6f511f">getAddr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the address accessed by this recipe. <a href="#af3caef2aa9a6ef6739a11c87df6f511f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc90988129c309da1be7cbe2ca3c7d05">isMasked</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recipe is masked. <a href="#adc90988129c309da1be7cbe2ca3c7d05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dab5a878379d5ee92940853d3feb53d">getMask</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the mask used by this recipe. <a href="#a6dab5a878379d5ee92940853d3feb53d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21723dcbc61b904461e5717f2ba0071b">execute</a> (VPTransformState &amp;State) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate the wide load/store. <a href="#a21723dcbc61b904461e5717f2ba0071b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a515cd094f92579b8b4ae0b01e7f92257">computeCost</a> (ElementCount VF, VPCostContext &amp;Ctx) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cost of this <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe">VPWidenMemoryRecipe</a>. <a href="#a515cd094f92579b8b4ae0b01e7f92257">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a629e42fdc4157d2642a1f5d565d3d538">getIngredient</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae98489d1a78f9b06b62f2ef84ead26b6">setMask</a> (VPValue *Mask)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4517e86770c6431f2e87adce2830db4f">Ingredient</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62abe5cb2b696369276d5d429a59bb89">Consecutive</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the accessed addresses are consecutive. <a href="#a62abe5cb2b696369276d5d429a59bb89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07ccf79fbeeda00be7ebc5a45b90355c">Reverse</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the consecutive accessed addresses are in reverse order. <a href="#a07ccf79fbeeda00be7ebc5a45b90355c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0193b5e5ddbf6965dc1aabf875e591e2">IsMasked</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the memory access is masked. <a href="#a0193b5e5ddbf6965dc1aabf875e591e2">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63f38beaba4e25370544f46d3d0b26fd">classof</a> (const VPRecipeBase *R)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ab4a2c32df2ae50e568b61c18563384">classof</a> (const VPUser *U)</td>
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

## Description {#details}

<p>A common base class for widening memory operations.</p>


<p>An optional mask can be provided as the last operand.</p>


<p>Definition at line 2953 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### VPWidenMemoryRecipe() {#a683571dc9876623d7cffc7e6f0fd67f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPWidenMemoryRecipe::VPWidenMemoryRecipe (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char unsigned SC, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands, bool Consecutive, bool Reverse, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2974 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a62abe5cb2b696369276d5d429a59bb89">Consecutive</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a4517e86770c6431f2e87adce2830db4f">Ingredient</a>, <a href="#a07ccf79fbeeda00be7ebc5a45b90355c">Reverse</a> and <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#aaf68139c582775191f8535403942e5f2">llvm::VPRecipeBase::VPRecipeBase</a>.</p>


<p>Referenced by <a href="#a5009f8c3fbc7246d33d2a15a25cbe02a">clone</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#ae123bdc95f3d36b528edae0a4ff321df">llvm::VPWidenLoadEVLRecipe::VPWidenLoadEVLRecipe</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a723d7043589bac799ae42c256c12a4e4">llvm::VPWidenLoadRecipe::VPWidenLoadRecipe</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#abf7c8c81965f29eb6190b3eaf03e7e10">llvm::VPWidenStoreEVLRecipe::VPWidenStoreEVLRecipe</a> and <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a315c60103278fb6da64704799489f135">llvm::VPWidenStoreRecipe::VPWidenStoreRecipe</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#a5009f8c3fbc7246d33d2a15a25cbe02a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPWidenMemoryRecipe * llvm::VPWidenMemoryRecipe::clone ()</td>
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

<p>Definition at line 2983 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#a683571dc9876623d7cffc7e6f0fd67f7">VPWidenMemoryRecipe</a>.</p>

</div>
</div>

### computeCost() {#a515cd094f92579b8b4ae0b01e7f92257}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost VPWidenMemoryRecipe::computeCost (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="/web-llvm/docs/api/structs/llvm/vpcostcontext">VPCostContext</a> &amp; Ctx)</td>
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

<p>Return the cost of this <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe">VPWidenMemoryRecipe</a>.</p>

<p>Declaration at line 3025 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 2556 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a62abe5cb2b696369276d5d429a59bb89">Consecutive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d97f0780a320d53641729a2d8371b74">llvm::getLoadStoreAddressSpace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4370c1523db2ede8d9791b76da2ab798">llvm::getLoadStoreAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2922c0c507ccec5bea4642aff9e2e328">llvm::getLoadStorePointerOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12126a4bea94833696dc67e0431e829">llvm::getLoadStoreType</a>, <a href="#a4517e86770c6431f2e87adce2830db4f">Ingredient</a>, <a href="#a0193b5e5ddbf6965dc1aabf875e591e2">IsMasked</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="#a07ccf79fbeeda00be7ebc5a45b90355c">Reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ecaea788d98147161f25d5adc3ec6ce7e1f">llvm::TargetTransformInfo::SK_Reverse</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae5262cc0e3a55bc74891cb8751d3b188">llvm::toVectorTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a65f435dbf3cc980ce5c58191e436e72f">llvm::VPWidenLoadEVLRecipe::computeCost</a> and <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#ac85fcb83463051a6b34aa7e323cbeb3d">llvm::VPWidenStoreEVLRecipe::computeCost</a>.</p>

</div>
</div>

### execute() {#a21723dcbc61b904461e5717f2ba0071b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPWidenMemoryRecipe::execute (<a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> &amp; State)</td>
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

<p>Generate the wide load/store.</p>

<p>Definition at line 3020 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getAddr() {#af3caef2aa9a6ef6739a11c87df6f511f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPWidenMemoryRecipe::getAddr ()</td>
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

<p>Definition at line 3007 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a6e1b252a9bbdc1a440fb57a6257b97f4">llvm::VPUser::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a8cd41c107c1039e2a5550d777076db35">llvm::VPWidenLoadRecipe::clone</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a97c6d18aca1810dbc2ae1efede7331ee">llvm::VPWidenStoreRecipe::clone</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a16471f19bad1ca5212ccbd52c21b8b54">llvm::VPWidenLoadEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a7c2b787dbd70d3fbd4f3699342eec925">llvm::VPWidenLoadRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#a1c719942d2fa4ca51fe66c92b9ab834c">llvm::VPWidenStoreEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a0fd82e391d2d015065516e32f62870c1">llvm::VPWidenStoreRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#abed0bd6ee69b8083deba69aa189aebc3">llvm::VPWidenLoadEVLRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a769d05569a9befd640244f159ba7f82a">llvm::VPWidenLoadRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#a7a37ffac00db5fca0c5df19b1ebe4980">llvm::VPWidenStoreEVLRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a1ea8913439b690e47eae67c829cf0d24">llvm::VPWidenStoreRecipe::onlyFirstLaneUsed</a> and <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#abf7c8c81965f29eb6190b3eaf03e7e10">llvm::VPWidenStoreEVLRecipe::VPWidenStoreEVLRecipe</a>.</p>

</div>
</div>

### getIngredient() {#a629e42fdc4157d2642a1f5d565d3d538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction &amp; llvm::VPWidenMemoryRecipe::getIngredient ()</td>
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



<p>Definition at line 3028 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="#a4517e86770c6431f2e87adce2830db4f">Ingredient</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#ae123bdc95f3d36b528edae0a4ff321df">llvm::VPWidenLoadEVLRecipe::VPWidenLoadEVLRecipe</a> and <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#abf7c8c81965f29eb6190b3eaf03e7e10">llvm::VPWidenStoreEVLRecipe::VPWidenStoreEVLRecipe</a>.</p>

</div>
</div>

### getMask() {#a6dab5a878379d5ee92940853d3feb53d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPWidenMemoryRecipe::getMask ()</td>
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

<p>Return the mask used by this recipe.</p>


<p>Note that a full mask is represented by a nullptr.</p>


<p>Definition at line 3014 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a5b21038d9b822b20c59e7ce5b12582e1">llvm::VPUser::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a6e1b252a9bbdc1a440fb57a6257b97f4">llvm::VPUser::getOperand</a> and <a href="#adc90988129c309da1be7cbe2ca3c7d05">isMasked</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a8cd41c107c1039e2a5550d777076db35">llvm::VPWidenLoadRecipe::clone</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a97c6d18aca1810dbc2ae1efede7331ee">llvm::VPWidenStoreRecipe::clone</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#ad0faf4b8ff1cf3306958d056dcb2fde2">createEVLRecipe</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a16471f19bad1ca5212ccbd52c21b8b54">llvm::VPWidenLoadEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a7c2b787dbd70d3fbd4f3699342eec925">llvm::VPWidenLoadRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#a1c719942d2fa4ca51fe66c92b9ab834c">llvm::VPWidenStoreEVLRecipe::execute</a> and <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a0fd82e391d2d015065516e32f62870c1">llvm::VPWidenStoreRecipe::execute</a>.</p>

</div>
</div>

### isConsecutive() {#a12482914e64512048aec3bc1ae42eebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPWidenMemoryRecipe::isConsecutive ()</td>
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

<p>Return whether the loaded-from / stored-to addresses are consecutive.</p>

<p>Definition at line 3000 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="#a62abe5cb2b696369276d5d429a59bb89">Consecutive</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a16471f19bad1ca5212ccbd52c21b8b54">llvm::VPWidenLoadEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a7c2b787dbd70d3fbd4f3699342eec925">llvm::VPWidenLoadRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#a1c719942d2fa4ca51fe66c92b9ab834c">llvm::VPWidenStoreEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a0fd82e391d2d015065516e32f62870c1">llvm::VPWidenStoreRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#abed0bd6ee69b8083deba69aa189aebc3">llvm::VPWidenLoadEVLRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a769d05569a9befd640244f159ba7f82a">llvm::VPWidenLoadRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#a7a37ffac00db5fca0c5df19b1ebe4980">llvm::VPWidenStoreEVLRecipe::onlyFirstLaneUsed</a> and <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a1ea8913439b690e47eae67c829cf0d24">llvm::VPWidenStoreRecipe::onlyFirstLaneUsed</a>.</p>

</div>
</div>

### isMasked() {#adc90988129c309da1be7cbe2ca3c7d05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPWidenMemoryRecipe::isMasked ()</td>
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

<p>Returns true if the recipe is masked.</p>

<p>Definition at line 3010 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="#a0193b5e5ddbf6965dc1aabf875e591e2">IsMasked</a>.</p>


<p>Referenced by <a href="#a6dab5a878379d5ee92940853d3feb53d">getMask</a>.</p>

</div>
</div>

### isReverse() {#af584264f3ca2bb1134c9e8471fcc6ab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPWidenMemoryRecipe::isReverse ()</td>
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

<p>Return whether the consecutive loaded/stored addresses are in reverse order.</p>

<p>Definition at line 3004 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="#a07ccf79fbeeda00be7ebc5a45b90355c">Reverse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a16471f19bad1ca5212ccbd52c21b8b54">llvm::VPWidenLoadEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a7c2b787dbd70d3fbd4f3699342eec925">llvm::VPWidenLoadRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#a1c719942d2fa4ca51fe66c92b9ab834c">llvm::VPWidenStoreEVLRecipe::execute</a> and <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a0fd82e391d2d015065516e32f62870c1">llvm::VPWidenStoreRecipe::execute</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### setMask() {#ae98489d1a78f9b06b62f2ef84ead26b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPWidenMemoryRecipe::setMask (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Mask)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2966 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpuser/#af4a3b471097ab37b1672a0d88869ea51">llvm::VPUser::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a0193b5e5ddbf6965dc1aabf875e591e2">IsMasked</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Consecutive {#a62abe5cb2b696369276d5d429a59bb89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPWidenMemoryRecipe::Consecutive</td>
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

<p>Whether the accessed addresses are consecutive.</p>

<p>Definition at line 2958 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a8cd41c107c1039e2a5550d777076db35">llvm::VPWidenLoadRecipe::clone</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a97c6d18aca1810dbc2ae1efede7331ee">llvm::VPWidenStoreRecipe::clone</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a65f435dbf3cc980ce5c58191e436e72f">llvm::VPWidenLoadEVLRecipe::computeCost</a>, <a href="#a515cd094f92579b8b4ae0b01e7f92257">computeCost</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#ac85fcb83463051a6b34aa7e323cbeb3d">llvm::VPWidenStoreEVLRecipe::computeCost</a>, <a href="#a12482914e64512048aec3bc1ae42eebb">isConsecutive</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a723d7043589bac799ae42c256c12a4e4">llvm::VPWidenLoadRecipe::VPWidenLoadRecipe</a>, <a href="#a683571dc9876623d7cffc7e6f0fd67f7">VPWidenMemoryRecipe</a> and <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a315c60103278fb6da64704799489f135">llvm::VPWidenStoreRecipe::VPWidenStoreRecipe</a>.</p>

</div>
</div>

### Ingredient {#a4517e86770c6431f2e87adce2830db4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction&amp; llvm::VPWidenMemoryRecipe::Ingredient</td>
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



<p>Definition at line 2955 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a8cd41c107c1039e2a5550d777076db35">llvm::VPWidenLoadRecipe::clone</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a97c6d18aca1810dbc2ae1efede7331ee">llvm::VPWidenStoreRecipe::clone</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a65f435dbf3cc980ce5c58191e436e72f">llvm::VPWidenLoadEVLRecipe::computeCost</a>, <a href="#a515cd094f92579b8b4ae0b01e7f92257">computeCost</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#ac85fcb83463051a6b34aa7e323cbeb3d">llvm::VPWidenStoreEVLRecipe::computeCost</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a16471f19bad1ca5212ccbd52c21b8b54">llvm::VPWidenLoadEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a7c2b787dbd70d3fbd4f3699342eec925">llvm::VPWidenLoadRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#a1c719942d2fa4ca51fe66c92b9ab834c">llvm::VPWidenStoreEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a0fd82e391d2d015065516e32f62870c1">llvm::VPWidenStoreRecipe::execute</a>, <a href="#a629e42fdc4157d2642a1f5d565d3d538">getIngredient</a> and <a href="#a683571dc9876623d7cffc7e6f0fd67f7">VPWidenMemoryRecipe</a>.</p>

</div>
</div>

### IsMasked {#a0193b5e5ddbf6965dc1aabf875e591e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPWidenMemoryRecipe::IsMasked = false</td>
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

<p>Whether the memory access is masked.</p>

<p>Definition at line 2964 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a65f435dbf3cc980ce5c58191e436e72f">llvm::VPWidenLoadEVLRecipe::computeCost</a>, <a href="#a515cd094f92579b8b4ae0b01e7f92257">computeCost</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#ac85fcb83463051a6b34aa7e323cbeb3d">llvm::VPWidenStoreEVLRecipe::computeCost</a>, <a href="#adc90988129c309da1be7cbe2ca3c7d05">isMasked</a> and <a href="#ae98489d1a78f9b06b62f2ef84ead26b6">setMask</a>.</p>

</div>
</div>

### Reverse {#a07ccf79fbeeda00be7ebc5a45b90355c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPWidenMemoryRecipe::Reverse</td>
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

<p>Whether the consecutive accessed addresses are in reverse order.</p>

<p>Definition at line 2961 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a8cd41c107c1039e2a5550d777076db35">llvm::VPWidenLoadRecipe::clone</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a97c6d18aca1810dbc2ae1efede7331ee">llvm::VPWidenStoreRecipe::clone</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a65f435dbf3cc980ce5c58191e436e72f">llvm::VPWidenLoadEVLRecipe::computeCost</a>, <a href="#a515cd094f92579b8b4ae0b01e7f92257">computeCost</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#ac85fcb83463051a6b34aa7e323cbeb3d">llvm::VPWidenStoreEVLRecipe::computeCost</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a7c2b787dbd70d3fbd4f3699342eec925">llvm::VPWidenLoadRecipe::execute</a>, <a href="#af584264f3ca2bb1134c9e8471fcc6ab7">isReverse</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a723d7043589bac799ae42c256c12a4e4">llvm::VPWidenLoadRecipe::VPWidenLoadRecipe</a>, <a href="#a683571dc9876623d7cffc7e6f0fd67f7">VPWidenMemoryRecipe</a> and <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a315c60103278fb6da64704799489f135">llvm::VPWidenStoreRecipe::VPWidenStoreRecipe</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a63f38beaba4e25370544f46d3d0b26fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPWidenMemoryRecipe::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> * R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2987 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#aaf68139c582775191f8535403942e5f2">llvm::VPRecipeBase::VPRecipeBase</a>.</p>


<p>Referenced by <a href="#a1ab4a2c32df2ae50e568b61c18563384">classof</a>.</p>

</div>
</div>

### classof() {#a1ab4a2c32df2ae50e568b61c18563384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPWidenMemoryRecipe::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> * U)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2994 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="#a63f38beaba4e25370544f46d3d0b26fd">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
