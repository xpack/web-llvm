---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vpblendrecipe
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VPBlendRecipe` Class

<p>A recipe for vectorizing a phi-node as a sequence of mask-based select instructions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPBlendRecipe { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">Transforms/Vectorize/VPlan.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpsingledefrecipe">VPSingleDefRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>VPSingleDef is a base class for recipes for modeling a sequence of one or more output IR that define a single result <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>. <a href="/web-llvm/docs/api/classes/llvm/vpsingledefrecipe/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06a43099cff6ce62ba54dbdb91b394c2">VPBlendRecipe</a> (PHINode *Phi, ArrayRef&lt; VPValue * &gt; Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The blend operation is a <a href="/web-llvm/docs/api/classes/llvm/user">User</a> of the incoming values and of their respective masks, ordered [I0, M0, I1, M1, I2, M2, ...]. <a href="#a06a43099cff6ce62ba54dbdb91b394c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpblendrecipe">VPBlendRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad05094de15d05295d9e769d815cd076d">clone</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone the current recipe. <a href="#ad05094de15d05295d9e769d815cd076d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af90bcb1df94143ecfb840bfe359f86d1">isNormalized</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A normalized blend is one that has an odd number of operands, whereby the first operand does not have an associated mask. <a href="#af90bcb1df94143ecfb840bfe359f86d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f0a937b4e04952fc07607effb9866a7">getNumIncomingValues</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of incoming values, taking into account when normalized the first incoming value will have no mask. <a href="#a4f0a937b4e04952fc07607effb9866a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2019700bf97441cc4fcf162a09247210">getIncomingValue</a> (unsigned Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return incoming value number <span class="doxyComputerOutput">Idx</span>. <a href="#a2019700bf97441cc4fcf162a09247210">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26df1ec06cf75ead168070b305c1344d">getMask</a> (unsigned Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return mask number <span class="doxyComputerOutput">Idx</span>. <a href="#a26df1ec06cf75ead168070b305c1344d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d96b296e589e5d8318e526b5d2ff92">execute</a> (VPTransformState &amp;State) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate the phi/select nodes. <a href="#af1d96b296e589e5d8318e526b5d2ff92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cf81ee784fd5dea0b9353a51f4f4fee">computeCost</a> (ElementCount VF, VPCostContext &amp;Ctx) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cost of this <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe">VPWidenMemoryRecipe</a>. <a href="#a0cf81ee784fd5dea0b9353a51f4f4fee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09354bbed6835f538ce6b7b995a02b46">print</a> (raw_ostream &amp;O, const Twine &amp;Indent, VPSlotTracker &amp;SlotTracker) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the recipe. <a href="#a09354bbed6835f538ce6b7b995a02b46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dc849c5a55d8fc876ea6deca991b264">onlyFirstLaneUsed</a> (const VPValue *Op) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recipe only uses the first lane of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#a0dc849c5a55d8fc876ea6deca991b264">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A recipe for vectorizing a phi-node as a sequence of mask-based select instructions.</p>

<p>Definition at line 2497 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VPBlendRecipe() {#a06a43099cff6ce62ba54dbdb91b394c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPBlendRecipe::VPBlendRecipe (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands)</td>
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

<p>The blend operation is a <a href="/web-llvm/docs/api/classes/llvm/user">User</a> of the incoming values and of their respective masks, ordered [I0, M0, I1, M1, I2, M2, ...].</p>


<p>Note that M0 can be omitted (implied by passing an odd number of operands) in which case all other incoming values are merged into it.</p>


<p>Definition at line 2503 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a733c4c530159a8b86223376c0696430e">llvm::VPRecipeBase::getDebugLoc</a> and <a href="/web-llvm/docs/api/classes/llvm/vpsingledefrecipe/#a698c2c1cbd9f6caace410d3733bb17b9">llvm::VPSingleDefRecipe::VPSingleDefRecipe</a>.</p>


<p>Referenced by <a href="#ad05094de15d05295d9e769d815cd076d">clone</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#ad05094de15d05295d9e769d815cd076d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBlendRecipe * llvm::VPBlendRecipe::clone ()</td>
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

<p>Definition at line 2508 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a5fe7dd2466300bd8747d81384a7ced5d">llvm::VPValue::getUnderlyingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a11d83265a9e4ff6c6ecd3cf222ad0208">llvm::VPUser::operands</a> and <a href="#a06a43099cff6ce62ba54dbdb91b394c2">VPBlendRecipe</a>.</p>

</div>
</div>

### computeCost() {#a0cf81ee784fd5dea0b9353a51f4f4fee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost VPBlendRecipe::computeCost (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="/web-llvm/docs/api/structs/llvm/vpcostcontext">VPCostContext</a> &amp; Ctx)</td>
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

<p>Declaration at line 2540 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 2180 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba07aee43ffb66908a25c55c77ce4c0d05">llvm::CmpInst::BAD_ICMP_PREDICATE</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="#a4f0a937b4e04952fc07607effb9866a7">getNumIncomingValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a5e3c306be8d629a994f3644765421d5f">llvm::vputils::onlyFirstLaneUsed</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae5262cc0e3a55bc74891cb8751d3b188">llvm::toVectorTy</a>.</p>

</div>
</div>

### execute() {#af1d96b296e589e5d8318e526b5d2ff92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPBlendRecipe::execute (<a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> &amp; State)</td>
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

<p>Generate the phi/select nodes.</p>

<p>Declaration at line 2537 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 2143 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a733c4c530159a8b86223376c0696430e">llvm::VPRecipeBase::getDebugLoc</a>, <a href="#a2019700bf97441cc4fcf162a09247210">getIncomingValue</a>, <a href="#a26df1ec06cf75ead168070b305c1344d">getMask</a>, <a href="#a4f0a937b4e04952fc07607effb9866a7">getNumIncomingValues</a>, <a href="#af90bcb1df94143ecfb840bfe359f86d1">isNormalized</a> and <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a5e3c306be8d629a994f3644765421d5f">llvm::vputils::onlyFirstLaneUsed</a>.</p>

</div>
</div>

### getIncomingValue() {#a2019700bf97441cc4fcf162a09247210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPBlendRecipe::getIncomingValue (unsigned Idx)</td>
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

<p>Return incoming value number <span class="doxyComputerOutput">Idx</span>.</p>

<p>Definition at line 2526 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a6e1b252a9bbdc1a440fb57a6257b97f4">llvm::VPUser::getOperand</a> and <a href="#af90bcb1df94143ecfb840bfe359f86d1">isNormalized</a>.</p>


<p>Referenced by <a href="#af1d96b296e589e5d8318e526b5d2ff92">execute</a> and <a href="#a09354bbed6835f538ce6b7b995a02b46">print</a>.</p>

</div>
</div>

### getMask() {#a26df1ec06cf75ead168070b305c1344d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPBlendRecipe::getMask (unsigned Idx)</td>
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

<p>Return mask number <span class="doxyComputerOutput">Idx</span>.</p>

<p>Definition at line 2531 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a6e1b252a9bbdc1a440fb57a6257b97f4">llvm::VPUser::getOperand</a> and <a href="#af90bcb1df94143ecfb840bfe359f86d1">isNormalized</a>.</p>


<p>Referenced by <a href="#af1d96b296e589e5d8318e526b5d2ff92">execute</a> and <a href="#a09354bbed6835f538ce6b7b995a02b46">print</a>.</p>

</div>
</div>

### getNumIncomingValues() {#a4f0a937b4e04952fc07607effb9866a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VPBlendRecipe::getNumIncomingValues ()</td>
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

<p>Return the number of incoming values, taking into account when normalized the first incoming value will have no mask.</p>

<p>Definition at line 2521 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a5b21038d9b822b20c59e7ce5b12582e1">llvm::VPUser::getNumOperands</a> and <a href="#af90bcb1df94143ecfb840bfe359f86d1">isNormalized</a>.</p>


<p>Referenced by <a href="#a0cf81ee784fd5dea0b9353a51f4f4fee">computeCost</a>, <a href="#af1d96b296e589e5d8318e526b5d2ff92">execute</a> and <a href="#a09354bbed6835f538ce6b7b995a02b46">print</a>.</p>

</div>
</div>

### isNormalized() {#af90bcb1df94143ecfb840bfe359f86d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPBlendRecipe::isNormalized ()</td>
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

<p>A normalized blend is one that has an odd number of operands, whereby the first operand does not have an associated mask.</p>

<p>Definition at line 2517 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a5b21038d9b822b20c59e7ce5b12582e1">llvm::VPUser::getNumOperands</a> and <a href="#af90bcb1df94143ecfb840bfe359f86d1">isNormalized</a>.</p>


<p>Referenced by <a href="#af1d96b296e589e5d8318e526b5d2ff92">execute</a>, <a href="#a2019700bf97441cc4fcf162a09247210">getIncomingValue</a>, <a href="#a26df1ec06cf75ead168070b305c1344d">getMask</a>, <a href="#a4f0a937b4e04952fc07607effb9866a7">getNumIncomingValues</a> and <a href="#af90bcb1df94143ecfb840bfe359f86d1">isNormalized</a>.</p>

</div>
</div>

### onlyFirstLaneUsed() {#a0dc849c5a55d8fc876ea6deca991b264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPBlendRecipe::onlyFirstLaneUsed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Op)</td>
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

<p>Definition at line 2550 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a11d83265a9e4ff6c6ecd3cf222ad0208">llvm::VPUser::operands</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#af0932bb43954178036c87ea2ee5f112c">llvm::VPValue::users</a>.</p>

</div>
</div>

### print() {#a09354bbed6835f538ce6b7b995a02b46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPBlendRecipe::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Indent, <a href="/web-llvm/docs/api/classes/llvm/vpslottracker">VPSlotTracker</a> &amp; SlotTracker)</td>
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

<p>Declaration at line 2545 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 2195 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="#a2019700bf97441cc4fcf162a09247210">getIncomingValue</a>, <a href="#a26df1ec06cf75ead168070b305c1344d">getMask</a>, <a href="#a4f0a937b4e04952fc07607effb9866a7">getNumIncomingValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a3fc47e93505e87044e0861e4142eca20">llvm::VPValue::printAsOperand</a>.</p>

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
