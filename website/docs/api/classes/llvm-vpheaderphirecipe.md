---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vpheaderphirecipe
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VPHeaderPHIRecipe` Class Reference

<p>A pure virtual base class for all recipes modeling header phis, including phis for first order recurrences, pointer inductions and reductions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPHeaderPHIRecipe { ... }
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpactivelanemaskphirecipe">VPActiveLaneMaskPHIRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe for generating the active lane mask for the vector loop that is used to predicate the vector operations. <a href="/web-llvm/docs/api/classes/llvm/vpactivelanemaskphirecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe">VPCanonicalIVPHIRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Canonical scalar induction phi of the vector loop. <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpevlbasedivphirecipe">VPEVLBasedIVPHIRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe for generating the phi node for the current index of elements, adjusted in accordance with EVL value. <a href="/web-llvm/docs/api/classes/llvm/vpevlbasedivphirecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vpfirstorderrecurrencephirecipe">VPFirstOrderRecurrencePHIRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe for handling first-order recurrence phis. <a href="/web-llvm/docs/api/structs/llvm/vpfirstorderrecurrencephirecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe">VPReductionPHIRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe for handling reduction phis. <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpscalarphirecipe">VPScalarPHIRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recipe to generate a scalar PHI. <a href="/web-llvm/docs/api/classes/llvm/vpscalarphirecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpwideninductionrecipe">VPWidenInductionRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for widened induction (<a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe">VPWidenIntOrFpInductionRecipe</a> and <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe">VPWidenPointerInductionRecipe</a>), providing shared functionality, including retrieving the step value, induction descriptor and original phi node. <a href="/web-llvm/docs/api/classes/llvm/vpwideninductionrecipe/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7251449378efb98a9e3f03a2016a060d">VPHeaderPHIRecipe</a> (unsigned char VPDefID, Instruction *UnderlyingInstr, VPValue *Start=nullptr, DebugLoc DL={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeffa5132afc1f721074900099ec90df0">~VPHeaderPHIRecipe</a> () override=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0b705cdf4fbdbd156a783c836252a17">execute</a> (VPTransformState &amp;State) override=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate the phi nodes. <a href="#ad0b705cdf4fbdbd156a783c836252a17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f6de5ec7362818ba04f034f8cbdfe8">computeCost</a> (ElementCount VF, VPCostContext &amp;Ctx) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cost of this header phi recipe. <a href="#a14f6de5ec7362818ba04f034f8cbdfe8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a23f4c83091068b3a8246e49f350fad">print</a> (raw_ostream &amp;O, const Twine &amp;Indent, VPSlotTracker &amp;SlotTracker) const override=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the recipe. <a href="#a7a23f4c83091068b3a8246e49f350fad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92c12c8e69e03cc781dd010cdaa5f0e6">getStartValue</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the start value of the phi, if one is set. <a href="#a92c12c8e69e03cc781dd010cdaa5f0e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0c5343977fde1fa159ea1d190267b23">getStartValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a977dedf43194597a17f6a7a3e58b7c75">setStartValue</a> (VPValue *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the start value of the recipe. <a href="#a977dedf43194597a17f6a7a3e58b7c75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80333e8d5f353fb9e929388e577a593f">getBackedgeValue</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the incoming value from the loop backedge. <a href="#a80333e8d5f353fb9e929388e577a593f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0e7e250d23299e4e75f62c916bbf681">getBackedgeRecipe</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the backedge value as a recipe. <a href="#ad0e7e250d23299e4e75f62c916bbf681">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbb274f33c22255e1b9d5d5d92f07fb2">classof</a> (const VPRecipeBase *B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Method to support type inquiry through isa, cast, and dyn_cast. <a href="#acbb274f33c22255e1b9d5d5d92f07fb2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dd66bab02a6246d34e83951c9bc1e1d">classof</a> (const VPValue *V)</td>
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

<p>A pure virtual base class for all recipes modeling header phis, including phis for first order recurrences, pointer inductions and reductions.</p>


<p>The start value is the first operand of the recipe and the incoming value from the backedge is the second operand.</p>


<p>Inductions are modeled using the following sub-classes:</p>


<ul class="doxyList ">
<li><a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe">VPCanonicalIVPHIRecipe</a>: Canonical scalar induction of the vector loop, starting at a specified value (zero for the main vector loop, the resume value for the epilogue vector loop) and stepping by 1. The induction controls exiting of the vector loop by comparing against the vector trip count. Produces a single scalar PHI for the induction value per iteration.</li>
<li><a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe">VPWidenIntOrFpInductionRecipe</a>: Generates vector values for integer and floating point inductions with arbitrary start and step values. Produces a vector PHI per-part.</li>
<li><a href="/web-llvm/docs/api/classes/llvm/vpderivedivrecipe">VPDerivedIVRecipe</a>: Converts the canonical IV value to the corresponding value of an IV with different start and step values. Produces a single scalar value per iteration</li>
<li><a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe">VPScalarIVStepsRecipe</a>: Generates scalar values per-lane based on a canonical or derived induction.</li>
<li><a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe">VPWidenPointerInductionRecipe</a>: Generate vector and scalar values for a pointer induction. Produces either a vector PHI per-part or scalar values per-lane based on the canonical induction.</li>
</ul>

<p>Definition at line 2031 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### VPHeaderPHIRecipe() {#a7251449378efb98a9e3f03a2016a060d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPHeaderPHIRecipe::VPHeaderPHIRecipe (unsigned char VPDefID, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * UnderlyingInstr, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Start=nullptr, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={})</td>
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



<p>Definition at line 2033 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpactivelanemaskphirecipe/#a32354b1cd2ce53a609b8e4e837c55130">llvm::VPActiveLaneMaskPHIRecipe::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#a568e7be2bddeae465781cd63c76564c3">llvm::VPCanonicalIVPHIRecipe::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vpevlbasedivphirecipe/#a3d45d04fecce555d9abeda535442a35c">llvm::VPEVLBasedIVPHIRecipe::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/vpfirstorderrecurrencephirecipe/#abf255079aef43722bfb39b1aea028ee3">llvm::VPFirstOrderRecurrencePHIRecipe::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#adbdd829708c7d8dc1da022001477c6a6">llvm::VPReductionPHIRecipe::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwideninductionrecipe/#a9feeb8456fdcc48d2a51eaf5ac284b60">llvm::VPWidenInductionRecipe::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vpactivelanemaskphirecipe/#ac59cec278c6c5dc3953ea0d1e0a6199c">llvm::VPActiveLaneMaskPHIRecipe::VPActiveLaneMaskPHIRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#a96ec91692f40a935592e3c7916339214">llvm::VPCanonicalIVPHIRecipe::VPCanonicalIVPHIRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpevlbasedivphirecipe/#ae1557d743fa5530298b711b41ecb37ac">llvm::VPEVLBasedIVPHIRecipe::VPEVLBasedIVPHIRecipe</a>, <a href="/web-llvm/docs/api/structs/llvm/vpfirstorderrecurrencephirecipe/#a34d6e37e9b9cb3ddeb08e1fd639e497e">llvm::VPFirstOrderRecurrencePHIRecipe::VPFirstOrderRecurrencePHIRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#a6a383304fe78111e6564377dcbae4666">llvm::VPReductionPHIRecipe::VPReductionPHIRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarphirecipe/#a0d27908ed27f8a71770249b7330c16cb">llvm::VPScalarPHIRecipe::VPScalarPHIRecipe</a> and <a href="/web-llvm/docs/api/classes/llvm/vpwideninductionrecipe/#a6df9383fcb4e6c458747b018afc83e15">llvm::VPWidenInductionRecipe::VPWidenInductionRecipe</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VPHeaderPHIRecipe() {#aeffa5132afc1f721074900099ec90df0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPHeaderPHIRecipe::~VPHeaderPHIRecipe ()</td>
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



<p>Definition at line 2041 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### computeCost() {#a14f6de5ec7362818ba04f034f8cbdfe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost VPHeaderPHIRecipe::computeCost (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="/web-llvm/docs/api/structs/llvm/vpcostcontext">VPCostContext</a> &amp; Ctx)</td>
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

<p>Return the cost of this header phi recipe.</p>

<p>Declaration at line 2058 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 1701 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>

</div>
</div>

### execute() {#ad0b705cdf4fbdbd156a783c836252a17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPHeaderPHIRecipe::execute (<a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> &amp; State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate the phi nodes.</p>

<p>Definition at line 2055 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### getBackedgeRecipe() {#ad0e7e250d23299e4e75f62c916bbf681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual VPRecipeBase &amp; llvm::VPHeaderPHIRecipe::getBackedgeRecipe ()</td>
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

<p>Returns the backedge value as a recipe.</p>


<p>The backedge value is guaranteed to be a recipe.</p>


<p>Definition at line 2085 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="#a80333e8d5f353fb9e929388e577a593f">getBackedgeValue</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a3be8d7833df422f3538ddb13af69bd70">llvm::VPValue::getDefiningRecipe</a>.</p>

</div>
</div>

### getBackedgeValue() {#a80333e8d5f353fb9e929388e577a593f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual VPValue * llvm::VPHeaderPHIRecipe::getBackedgeValue ()</td>
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

<p>Returns the incoming value from the loop backedge.</p>

<p>Definition at line 2079 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a6e1b252a9bbdc1a440fb57a6257b97f4">llvm::VPUser::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#a79f07fcd4bfc94aa84346e34ad963f4e">llvm::VPCanonicalIVPHIRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#a28cfe0563ab668a94408a75e7a852f06">llvm::VPReductionPHIRecipe::clone</a> and <a href="#ad0e7e250d23299e4e75f62c916bbf681">getBackedgeRecipe</a>.</p>

</div>
</div>

### getStartValue() {#a92c12c8e69e03cc781dd010cdaa5f0e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPHeaderPHIRecipe::getStartValue ()</td>
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

<p>Returns the start value of the phi, if one is set.</p>

<p>Definition at line 2068 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a5b21038d9b822b20c59e7ce5b12582e1">llvm::VPUser::getNumOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a6e1b252a9bbdc1a440fb57a6257b97f4">llvm::VPUser::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a20c2e870e2c105fbf0945df09a9a5c4d">addResumePhiRecipeForInduction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#a53a0f613b760cdb5f775c434e3c61af3">llvm::VPWidenIntOrFpInductionRecipe::clone</a>, <a href="/web-llvm/docs/api/structs/llvm/vpfirstorderrecurrencephirecipe/#a141e9946f635323d4da5e8b4b3f64e44">llvm::VPFirstOrderRecurrencePHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#ad481483dac767c09d773266ba8b877e5">llvm::VPReductionPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarphirecipe/#ab94cd5f70a441ccaad6de9c85f583741">llvm::VPScalarPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#a98d8cca54a99e8b64eb406f898565323">llvm::VPWidenIntOrFpInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#ac53a5d033ba641288b6e15344d880186">llvm::VPWidenPointerInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#ac8744d8abf2a7ed185cc14f0a305cf8e">llvm::VPCanonicalIVPHIRecipe::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#aebed30683f6b89d62f06d2a10786c2e3">llvm::VPWidenIntOrFpInductionRecipe::isCanonical</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a13368acf4fbb5816c3d82099b11519b1">preparePlanForMainVectorLoop</a> and <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#acb6e3f81767df2fcf8a7d2875cda28d4">llvm::VPWidenPointerInductionRecipe::print</a>.</p>

</div>
</div>

### getStartValue() {#ac0c5343977fde1fa159ea1d190267b23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPHeaderPHIRecipe::getStartValue ()</td>
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



<p>Definition at line 2071 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a5b21038d9b822b20c59e7ce5b12582e1">llvm::VPUser::getNumOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a6e1b252a9bbdc1a440fb57a6257b97f4">llvm::VPUser::getOperand</a>.</p>

</div>
</div>

### print() {#a7a23f4c83091068b3a8246e49f350fad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPHeaderPHIRecipe::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Indent, <a href="/web-llvm/docs/api/classes/llvm/vpslottracker">VPSlotTracker</a> &amp; SlotTracker)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the recipe.</p>

<p>Definition at line 2063 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### setStartValue() {#a977dedf43194597a17f6a7a3e58b7c75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPHeaderPHIRecipe::setStartValue (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * V)</td>
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

<p>Update the start value of the recipe.</p>

<p>Definition at line 2076 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a19c3591dc1eeb5648552b33f70e04b65">llvm::VPUser::setOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#acbb274f33c22255e1b9d5d5d92f07fb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPHeaderPHIRecipe::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> * B)</td>
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

<p>Method to support type inquiry through isa, cast, and dyn_cast.</p>

<p>Definition at line 2044 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

</div>
</div>

### classof() {#a5dd66bab02a6246d34e83951c9bc1e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPHeaderPHIRecipe::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * V)</td>
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



<p>Definition at line 2048 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

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
