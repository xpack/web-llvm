---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vpvectorpointerrecipe
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VPVectorPointerRecipe` Class

<p>A recipe to compute the pointers for widened memory accesses of IndexTy. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPVectorPointerRecipe { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">Transforms/Vectorize/VPlan.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags">VPRecipeWithIRFlags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to record LLVM IR flag for a recipe along with it. <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpunrollpartaccessor">VPUnrollPartAccessor&lt;PartOpIdx&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to access the operand that contains the unroll part for this recipe after unrolling. <a href="/web-llvm/docs/api/classes/llvm/vpunrollpartaccessor/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7651c65171e0ddf854f4f9cb0d231097">VPVectorPointerRecipe</a> (VPValue *Ptr, Type *IndexedTy, GEPNoWrapFlags GEPFlags, DebugLoc DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82d57109b0437debe570e7dae895f3e3">execute</a> (VPTransformState &amp;State) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The method which generates the output IR instructions that correspond to this VPRecipe, thereby "executing" the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>. <a href="#a82d57109b0437debe570e7dae895f3e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4c5a9c1b0255e0baad70069e8daca8e">onlyFirstLaneUsed</a> (const VPValue *Op) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> only uses the first lane of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#ae4c5a9c1b0255e0baad70069e8daca8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abad9bb37a7a01ad5276ca2ec9a9bc31d">onlyFirstPartUsed</a> (const VPValue *Op) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recipe only uses the first part of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#abad9bb37a7a01ad5276ca2ec9a9bc31d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvectorpointerrecipe">VPVectorPointerRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0756969ccfa0f31807a67c9b0caf92f">clone</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone the current recipe. <a href="#af0756969ccfa0f31807a67c9b0caf92f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed39c9bfbb9cadd5d8c268c3f3632cf7">computeCost</a> (ElementCount VF, VPCostContext &amp;Ctx) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cost of this <a href="/web-llvm/docs/api/classes/llvm/vpheaderphirecipe">VPHeaderPHIRecipe</a>. <a href="#aed39c9bfbb9cadd5d8c268c3f3632cf7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a240688a9252bdfe411b157159b5aaf69">print</a> (raw_ostream &amp;O, const Twine &amp;Indent, VPSlotTracker &amp;SlotTracker) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the recipe. <a href="#a240688a9252bdfe411b157159b5aaf69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a759e3dd21ea8cbbf4a0d7afb35014e10">IndexedTy</a></td>
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

<p>A recipe to compute the pointers for widened memory accesses of IndexTy.</p>

<p>Definition at line 1960 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VPVectorPointerRecipe() {#a7651c65171e0ddf854f4f9cb0d231097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPVectorPointerRecipe::VPVectorPointerRecipe (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * IndexedTy, <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a> GEPFlags, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL)</td>
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



<p>Definition at line 1965 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#a8e2e3852ea03bfa9505e2212c609c3cd">llvm::VPRecipeWithIRFlags::GEPFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#afbcee996669bdac73eae32d28d2e4bd6">llvm::VPRecipeWithIRFlags::VPRecipeWithIRFlags</a>.</p>


<p>Referenced by <a href="#af0756969ccfa0f31807a67c9b0caf92f">clone</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#af0756969ccfa0f31807a67c9b0caf92f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPVectorPointerRecipe * llvm::VPVectorPointerRecipe::clone ()</td>
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

<p>Definition at line 1989 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a733c4c530159a8b86223376c0696430e">llvm::VPRecipeBase::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#a2241b30dd473ac42773e63edc55fdec6">llvm::VPRecipeWithIRFlags::getGEPNoWrapFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a6e1b252a9bbdc1a440fb57a6257b97f4">llvm::VPUser::getOperand</a> and <a href="#a7651c65171e0ddf854f4f9cb0d231097">VPVectorPointerRecipe</a>.</p>

</div>
</div>

### computeCost() {#aed39c9bfbb9cadd5d8c268c3f3632cf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::VPVectorPointerRecipe::computeCost (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="/web-llvm/docs/api/structs/llvm/vpcostcontext">VPCostContext</a> &amp; Ctx)</td>
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

<p>Return the cost of this <a href="/web-llvm/docs/api/classes/llvm/vpheaderphirecipe">VPHeaderPHIRecipe</a>.</p>

<p>Definition at line 1995 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### execute() {#a82d57109b0437debe570e7dae895f3e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPVectorPointerRecipe::execute (<a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> &amp; State)</td>
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

<p>The method which generates the output IR instructions that correspond to this VPRecipe, thereby "executing" the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>.</p>

<p>Declaration at line 1973 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 2117 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73e0482b96d9d0cdfcc90c0a34f5b0db">llvm::IRBuilderBase::CreateGEP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4156fb8bcc6a7e29ee021b01d22551e">llvm::createStepForVF</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a733c4c530159a8b86223376c0696430e">llvm::VPRecipeBase::getDebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#ad5b9a4518a164330f914a84969ca7cce">getGEPIndexTy</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#a2241b30dd473ac42773e63edc55fdec6">llvm::VPRecipeWithIRFlags::getGEPNoWrapFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a6e1b252a9bbdc1a440fb57a6257b97f4">llvm::VPUser::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vpunrollpartaccessor/#ae3b05f8b5cd223b95134b839cec5aecd">llvm::VPUnrollPartAccessor&lt; 1 &gt;::getUnrollPart</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### onlyFirstLaneUsed() {#ae4c5a9c1b0255e0baad70069e8daca8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPVectorPointerRecipe::onlyFirstLaneUsed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Op)</td>
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

<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> only uses the first lane of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>


<p>Conservatively returns false.</p>


<p>Definition at line 1975 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a11d83265a9e4ff6c6ecd3cf222ad0208">llvm::VPUser::operands</a>.</p>

</div>
</div>

### onlyFirstPartUsed() {#abad9bb37a7a01ad5276ca2ec9a9bc31d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPVectorPointerRecipe::onlyFirstPartUsed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Op)</td>
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

<p>Returns true if the recipe only uses the first part of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>

<p>Definition at line 1982 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a5b21038d9b822b20c59e7ce5b12582e1">llvm::VPUser::getNumOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a11d83265a9e4ff6c6ecd3cf222ad0208">llvm::VPUser::operands</a>.</p>

</div>
</div>

### print() {#a240688a9252bdfe411b157159b5aaf69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPVectorPointerRecipe::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Indent, <a href="/web-llvm/docs/api/classes/llvm/vpslottracker">VPSlotTracker</a> &amp; SlotTracker)</td>
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

<p>Declaration at line 2003 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 2133 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a3fc47e93505e87044e0861e4142eca20">llvm::VPValue::printAsOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a0112474f9dc69912e4c067594692d15b">llvm::VPUser::printOperands</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IndexedTy {#a759e3dd21ea8cbbf4a0d7afb35014e10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::VPVectorPointerRecipe::IndexedTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1962 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

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
