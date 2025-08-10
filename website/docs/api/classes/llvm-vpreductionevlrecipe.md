---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vpreductionevlrecipe
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VPReductionEVLRecipe` Class

<p>A recipe to represent inloop reduction operations with vector-predication intrinsics, performing a reduction on a vector operand with the explicit vector length (EVL) into a scalar value, and adding the result to a chain. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPReductionEVLRecipe { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">Transforms/Vectorize/VPlan.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe">VPReductionRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe to represent inloop reduction operations, performing a reduction on a vector operand into a scalar value, and adding the result to a chain. <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad028e9af49070bb3368ec53b2cd816cd">VPReductionEVLRecipe</a> (VPReductionRecipe &amp;R, VPValue &amp;EVL, VPValue *CondOp)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd3eabdfb64f34f6c1d20850fb05d92c">~VPReductionEVLRecipe</a> () override=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpreductionevlrecipe">VPReductionEVLRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada21a55fb2ac208fab4ec54038c49229">clone</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone the current recipe. <a href="#ada21a55fb2ac208fab4ec54038c49229">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26b8ad3bd938e53e6e4cbc5f6d1b6318">execute</a> (VPTransformState &amp;State) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate the reduction in the loop. <a href="#a26b8ad3bd938e53e6e4cbc5f6d1b6318">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee1dbc25df0d2b70bd4eb984cd3be380">print</a> (raw_ostream &amp;O, const Twine &amp;Indent, VPSlotTracker &amp;SlotTracker) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the recipe. <a href="#aee1dbc25df0d2b70bd4eb984cd3be380">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fb58a50b3b232848a0ad7a641559586">getEVL</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> of the explicit vector length. <a href="#a5fb58a50b3b232848a0ad7a641559586">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a327c7ee2465b3f3afa825f94bb9b1ef8">onlyFirstLaneUsed</a> (const VPValue *Op) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recipe only uses the first lane of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#a327c7ee2465b3f3afa825f94bb9b1ef8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A recipe to represent inloop reduction operations with vector-predication intrinsics, performing a reduction on a vector operand with the explicit vector length (EVL) into a scalar value, and adding the result to a chain.</p>


<p>The Operands are {ChainOp, VecOp, EVL, [Condition]}.</p>


<p>Definition at line 2739 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VPReductionEVLRecipe() {#ad028e9af49070bb3368ec53b2cd816cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPReductionEVLRecipe::VPReductionEVLRecipe (<a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe">VPReductionRecipe</a> &amp; R, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> &amp; EVL, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * CondOp)</td>
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



<p>Definition at line 2741 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a4f7efc4e859cdb4e4c7dca9d10777a86">llvm::VPReductionRecipe::getRecurrenceDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a5fe7dd2466300bd8747d81384a7ced5d">llvm::VPValue::getUnderlyingValue</a> and <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a1f66dc01846bbe322d2a8268c86d9f9b">llvm::VPReductionRecipe::VPReductionRecipe</a>.</p>


<p>Referenced by <a href="#ada21a55fb2ac208fab4ec54038c49229">clone</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VPReductionEVLRecipe() {#afd3eabdfb64f34f6c1d20850fb05d92c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPReductionEVLRecipe::~VPReductionEVLRecipe ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2748 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#ada21a55fb2ac208fab4ec54038c49229}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPReductionEVLRecipe * llvm::VPReductionEVLRecipe::clone ()</td>
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

<p>Definition at line 2750 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#ad028e9af49070bb3368ec53b2cd816cd">VPReductionEVLRecipe</a>.</p>

</div>
</div>

### execute() {#a26b8ad3bd938e53e6e4cbc5f6d1b6318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPReductionEVLRecipe::execute (<a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> &amp; State)</td>
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

<p>Generate the reduction in the loop.</p>

<p>Declaration at line 2757 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 2268 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aba5d97f3a14427982c1b86dafd033320">llvm::IRBuilderBase::CreateBinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52fcded779c8029fdafaa9897cd3b238">llvm::createMinMaxOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f987d5b55845b1a4658e7998a3ecefb">llvm::createOrderedReduction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a03f2d52898c4faf266a30cfc126e3f02">llvm::createSimpleReduction</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a40ed7274ff11f079e5b5eae34c818c51">llvm::IRBuilderBase::CreateVectorSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a917ddbb65611fb8da66ee02a75742696">llvm::VPReductionRecipe::getChainOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a5a5560ef4d8c8565cb319d9b4f25fb8e">llvm::VPReductionRecipe::getCondOp</a>, <a href="#a5fb58a50b3b232848a0ad7a641559586">getEVL</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a4f7efc4e859cdb4e4c7dca9d10777a86">llvm::VPReductionRecipe::getRecurrenceDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a42ce8aa34864a9d974958b9d3d36ad17">llvm::IRBuilderBase::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a4dce99c106a96a31be97370d5c7b0e22">llvm::VPReductionRecipe::getVecOp</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#af08d243545b64f4b77161992d0e2366e">llvm::RecurrenceDescriptor::isMinMaxRecurrenceKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp/#af21791a898355d83b502fd655b90e061">isOrdered</a>, <a href="/web-llvm/docs/api/classes/llvm/vectorbuilder/#a5cd4fcdcc6ed6c8bba3f46c06c17a2a3">llvm::VectorBuilder::setEVL</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6370e29617c71c8081bbbc68d6058403">llvm::IRBuilderBase::setFastMathFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/vectorbuilder/#ab0c56056ac6ee6a08c82ba4323df216e">llvm::VectorBuilder::setMask</a>.</p>

</div>
</div>

### getEVL() {#a5fb58a50b3b232848a0ad7a641559586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPReductionEVLRecipe::getEVL ()</td>
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

<p>The <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> of the explicit vector length.</p>

<p>Definition at line 2766 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a6e1b252a9bbdc1a440fb57a6257b97f4">llvm::VPUser::getOperand</a>.</p>


<p>Referenced by <a href="#a26b8ad3bd938e53e6e4cbc5f6d1b6318">execute</a>, <a href="#a327c7ee2465b3f3afa825f94bb9b1ef8">onlyFirstLaneUsed</a> and <a href="#aee1dbc25df0d2b70bd4eb984cd3be380">print</a>.</p>

</div>
</div>

### onlyFirstLaneUsed() {#a327c7ee2465b3f3afa825f94bb9b1ef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPReductionEVLRecipe::onlyFirstLaneUsed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Op)</td>
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

<p>Definition at line 2769 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5fb58a50b3b232848a0ad7a641559586">getEVL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a11d83265a9e4ff6c6ecd3cf222ad0208">llvm::VPUser::operands</a>.</p>

</div>
</div>

### print() {#aee1dbc25df0d2b70bd4eb984cd3be380}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPReductionEVLRecipe::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Indent, <a href="/web-llvm/docs/api/classes/llvm/vpslottracker">VPSlotTracker</a> &amp; SlotTracker)</td>
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

<p>Declaration at line 2761 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 2361 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a917ddbb65611fb8da66ee02a75742696">llvm::VPReductionRecipe::getChainOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a5a5560ef4d8c8565cb319d9b4f25fb8e">llvm::VPReductionRecipe::getCondOp</a>, <a href="#a5fb58a50b3b232848a0ad7a641559586">getEVL</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9a167f91db810097d281b1ed627f4575">llvm::Instruction::getFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9affd129d19aae669647eb0d1c91f793">llvm::Instruction::getOpcodeName</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a4f7efc4e859cdb4e4c7dca9d10777a86">llvm::VPReductionRecipe::getRecurrenceDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/vpsingledefrecipe/#a12b12fbdf160f2cf70973e09adbf97d4">llvm::VPSingleDefRecipe::getUnderlyingInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a4dce99c106a96a31be97370d5c7b0e22">llvm::VPReductionRecipe::getVecOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a0615e1d175f17b3c47b1d1755e6f7cab">llvm::VPReductionRecipe::isConditional</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a3fc47e93505e87044e0861e4142eca20">llvm::VPValue::printAsOperand</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
