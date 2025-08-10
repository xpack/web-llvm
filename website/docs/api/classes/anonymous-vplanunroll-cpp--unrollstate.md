---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-vplanunroll-cpp-/unrollstate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `UnrollState` Class

<p>Helper to hold state needed for unrolling. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{VPlanUnroll.cpp}::UnrollState { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae04902368ea328ca1b0eb393a0f0dd4e">UnrollState</a> (VPlan &amp;Plan, unsigned UF, LLVMContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9965cb8e010ad82f02434a0762cddf1e">unrollBlock</a> (VPBlockBase *VPB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8defa175c07f36ea3c3cf47dfdd4c349">getValueForPart</a> (VPValue *V, unsigned Part)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9d451e46e072fa57afbc34788c93f44">addRecipeForPart</a> (VPRecipeBase *OrigR, VPRecipeBase *CopyR, unsigned Part)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a single original recipe <span class="doxyComputerOutput">OrigR</span> (of part zero), and its copy <span class="doxyComputerOutput">CopyR</span> for part <span class="doxyComputerOutput">Part</span>, map every <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> defined by <span class="doxyComputerOutput">OrigR</span> to its corresponding <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> defined by <span class="doxyComputerOutput">CopyR</span>. <a href="#ab9d451e46e072fa57afbc34788c93f44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad84a0ee13c95a817ac63639f9754dd33">addUniformForAllParts</a> (VPSingleDefRecipe *R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a uniform recipe <span class="doxyComputerOutput">R</span>, add it for all parts. <a href="#ad84a0ee13c95a817ac63639f9754dd33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9f6dc4785a445bb17b9726ecdefd607">contains</a> (VPValue *VPV) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97d25d446423ce3582fb7179d309d88b">remapOperand</a> (VPRecipeBase *R, unsigned OpIdx, unsigned Part)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">R's</span> operand at <span class="doxyComputerOutput">OpIdx</span> with its corresponding <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> for part <span class="doxyComputerOutput">P</span>. <a href="#a97d25d446423ce3582fb7179d309d88b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab38da9aa6896dbc776952fcb8ea1d1aa">remapOperands</a> (VPRecipeBase *R, unsigned Part)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">R's</span> operands with their corresponding VPValues for part <span class="doxyComputerOutput">P</span>. <a href="#ab38da9aa6896dbc776952fcb8ea1d1aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26ca0104927e456e1e39c2c0d5c86cdf">unrollReplicateRegionByUF</a> (VPRegionBlock *VPR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unroll replicate region <span class="doxyComputerOutput">VPR</span> by cloning the region UF - 1 times. <a href="#a26ca0104927e456e1e39c2c0d5c86cdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe55e318270a0809a930841f9d0dcc44">unrollRecipeByUF</a> (VPRecipeBase &amp;R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unroll recipe <span class="doxyComputerOutput">R</span> by cloning it UF - 1 times, unless it is uniform across all parts. <a href="#abe55e318270a0809a930841f9d0dcc44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa773bd1bfec647796608e37830e153c8">unrollHeaderPHIByUF</a> (VPHeaderPHIRecipe *R, VPBasicBlock::iterator InsertPtForPhi)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unroll header phi recipe <span class="doxyComputerOutput">R</span>. <a href="#aa773bd1bfec647796608e37830e153c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a850b2232cb34e05083a58fc3334facef">unrollWidenInductionByUF</a> (VPWidenIntOrFpInductionRecipe *IV, VPBasicBlock::iterator InsertPtForPhi)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unroll a widen induction recipe <span class="doxyComputerOutput">IV</span>. <a href="#a850b2232cb34e05083a58fc3334facef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a040cba2e04491728fe73a6f137b32d33">getConstantVPV</a> (unsigned Part)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9d968986d126c77267bd6b3accfb55f">Plan</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Plan to unroll. <a href="#af9d968986d126c77267bd6b3accfb55f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdcf77cde1368634ec6a4b884419c134">UF</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unroll factor to unroll by. <a href="#abdcf77cde1368634ec6a4b884419c134">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vptypeanalysis">VPTypeAnalysis</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4106da9a52db0ea424b0fda5ff114c54">TypeInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analysis for types. <a href="#a4106da9a52db0ea424b0fda5ff114c54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad77c7061f6d3f33d3ebccc34196809c6">ToSkip</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unrolling may create recipes that should not be unrolled themselves. <a href="#ad77c7061f6d3f33d3ebccc34196809c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5cdaee96dd7c573a02c5120625c0e6b">VPV2Parts</a></td>
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

<p>Helper to hold state needed for unrolling.</p>


<p>It holds the Plan to unroll by UF. It also holds copies of VPValues across UF-1 unroll parts to facilitate the unrolling transformation, where the original VPValues are retained for part zero.</p>


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### UnrollState() {#ae04902368ea328ca1b0eb393a0f0dd4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{VPlanUnroll.cpp}::UnrollState::UnrollState (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, unsigned UF, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addRecipeForPart() {#ab9d451e46e072fa57afbc34788c93f44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{VPlanUnroll.cpp}::UnrollState::addRecipeForPart (<a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> * OrigR, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> * CopyR, unsigned Part)</td>
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

<p>Given a single original recipe <span class="doxyComputerOutput">OrigR</span> (of part zero), and its copy <span class="doxyComputerOutput">CopyR</span> for part <span class="doxyComputerOutput">Part</span>, map every <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> defined by <span class="doxyComputerOutput">OrigR</span> to its corresponding <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> defined by <span class="doxyComputerOutput">CopyR</span>.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdef/#a5b7aa8b207f721cee2e80ebd99682563">llvm::VPDef::definedValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a> and <a href="/web-llvm/docs/api/classes/llvm/vpdef/#a9264a7c042631ed72c3bca345fc24003">llvm::VPDef::getVPValue</a>.</p>

</div>
</div>

### addUniformForAllParts() {#ad84a0ee13c95a817ac63639f9754dd33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{VPlanUnroll.cpp}::UnrollState::addUniformForAllParts (<a href="/web-llvm/docs/api/classes/llvm/vpsingledefrecipe">VPSingleDefRecipe</a> * R)</td>
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

<p>Given a uniform recipe <span class="doxyComputerOutput">R</span>, add it for all parts.</p>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a9965cb8e010ad82f02434a0762cddf1e">unrollBlock</a>.</p>

</div>
</div>

### contains() {#ad9f6dc4785a445bb17b9726ecdefd607}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{VPlanUnroll.cpp}::UnrollState::contains (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * VPV)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>

</div>
</div>

### getValueForPart() {#a8defa175c07f36ea3c3cf47dfdd4c349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * anonymous{VPlanUnroll.cpp}::UnrollState::getValueForPart (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * V, unsigned Part)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a97d25d446423ce3582fb7179d309d88b">remapOperand</a>, <a href="#ab38da9aa6896dbc776952fcb8ea1d1aa">remapOperands</a> and <a href="#a9965cb8e010ad82f02434a0762cddf1e">unrollBlock</a>.</p>

</div>
</div>

### remapOperand() {#a97d25d446423ce3582fb7179d309d88b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{VPlanUnroll.cpp}::UnrollState::remapOperand (<a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> * R, unsigned OpIdx, unsigned Part)</td>
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

<p>Update <span class="doxyComputerOutput">R's</span> operand at <span class="doxyComputerOutput">OpIdx</span> with its corresponding <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> for part <span class="doxyComputerOutput">P</span>.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>


<p>Reference <a href="#a8defa175c07f36ea3c3cf47dfdd4c349">getValueForPart</a>.</p>

</div>
</div>

### remapOperands() {#ab38da9aa6896dbc776952fcb8ea1d1aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{VPlanUnroll.cpp}::UnrollState::remapOperands (<a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> * R, unsigned Part)</td>
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

<p>Update <span class="doxyComputerOutput">R's</span> operands with their corresponding VPValues for part <span class="doxyComputerOutput">P</span>.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a> and <a href="#a8defa175c07f36ea3c3cf47dfdd4c349">getValueForPart</a>.</p>


<p>Referenced by <a href="#a9965cb8e010ad82f02434a0762cddf1e">unrollBlock</a>.</p>

</div>
</div>

### unrollBlock() {#a9965cb8e010ad82f02434a0762cddf1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UnrollState::unrollBlock (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * VPB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>


<p>References <a href="#ad84a0ee13c95a817ac63639f9754dd33">addUniformForAllParts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a1ae2cb3c63b4d67324ddc947fb9696fc">llvm::VPRegionBlock::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a72533c6b54501809628b9daee79b9d18">llvm::VPBasicBlock::getFirstNonPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#ac6f0bd9ed63fe4a784697d73ae3b6fa0">llvm::VPValue::getLiveInIRValue</a>, <a href="#a8defa175c07f36ea3c3cf47dfdd4c349">getValueForPart</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a24555c6ed92715d80348f0991a6d55df">llvm::VPRegionBlock::isReplicator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a0c663bf15e8398176f591270e7676f96">llvm::vputils::isUniformAcrossVFsAndUFs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#a5438a63c52f3576904c86e1bf0c7a9ab">llvm::VPlanPatternMatch::m_VPInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vplanpatternmatch/#abce81cbd0e36ab26b74909f7d9135bf5">llvm::VPlanPatternMatch::m_VPValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#ab38da9aa6896dbc776952fcb8ea1d1aa">remapOperands</a> and <a href="#a9965cb8e010ad82f02434a0762cddf1e">unrollBlock</a>.</p>


<p>Referenced by <a href="#a9965cb8e010ad82f02434a0762cddf1e">unrollBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getConstantVPV() {#a040cba2e04491728fe73a6f137b32d33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * anonymous{VPlanUnroll.cpp}::UnrollState::getConstantVPV (unsigned Part)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>

</div>
</div>

### unrollHeaderPHIByUF() {#aa773bd1bfec647796608e37830e153c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UnrollState::unrollHeaderPHIByUF (<a href="/web-llvm/docs/api/classes/llvm/vpheaderphirecipe">VPHeaderPHIRecipe</a> * R, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a2fc75e7b63babbf776ed29cfed87ae65">VPBasicBlock::iterator</a> InsertPtForPhi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unroll header phi recipe <span class="doxyComputerOutput">R</span>.</p>


<p>How exactly the recipe gets unrolled depends on the concrete header phi. Inserts newly created recipes at <span class="doxyComputerOutput">InsertPtForPhi</span>.</p>


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>

</div>
</div>

### unrollRecipeByUF() {#abe55e318270a0809a930841f9d0dcc44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UnrollState::unrollRecipeByUF (<a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> &amp; R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unroll recipe <span class="doxyComputerOutput">R</span> by cloning it UF - 1 times, unless it is uniform across all parts.</p>


<p>Handle non-header-phi recipes.</p>


<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>

</div>
</div>

### unrollReplicateRegionByUF() {#a26ca0104927e456e1e39c2c0d5c86cdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UnrollState::unrollReplicateRegionByUF (<a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> * VPR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unroll replicate region <span class="doxyComputerOutput">VPR</span> by cloning the region UF - 1 times.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>

</div>
</div>

### unrollWidenInductionByUF() {#a850b2232cb34e05083a58fc3334facef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UnrollState::unrollWidenInductionByUF (<a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe">VPWidenIntOrFpInductionRecipe</a> * IV, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a2fc75e7b63babbf776ed29cfed87ae65">VPBasicBlock::iterator</a> InsertPtForPhi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unroll a widen induction recipe <span class="doxyComputerOutput">IV</span>.</p>


<p>This introduces recipes to compute the induction steps for each part.</p>


<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Plan {#af9d968986d126c77267bd6b3accfb55f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPlan&amp; anonymous{VPlanUnroll.cpp}::UnrollState::Plan</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Plan to unroll.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>

</div>
</div>

### ToSkip {#ad77c7061f6d3f33d3ebccc34196809c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;VPRecipeBase *, 8&gt; anonymous{VPlanUnroll.cpp}::UnrollState::ToSkip</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unrolling may create recipes that should not be unrolled themselves.</p>


<p>Those are tracked in ToSkip.</p>


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>

</div>
</div>

### TypeInfo {#a4106da9a52db0ea424b0fda5ff114c54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPTypeAnalysis anonymous{VPlanUnroll.cpp}::UnrollState::TypeInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analysis for types.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>

</div>
</div>

### UF {#abdcf77cde1368634ec6a4b884419c134}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{VPlanUnroll.cpp}::UnrollState::UF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unroll factor to unroll by.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>

</div>
</div>

### VPV2Parts {#af5cdaee96dd7c573a02c5120625c0e6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;VPValue *, SmallVector&lt;VPValue *&gt; &gt; anonymous{VPlanUnroll.cpp}::UnrollState::VPV2Parts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanunroll-cpp">VPlanUnroll.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
