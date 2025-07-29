---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vprecipewithirflags
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VPRecipeWithIRFlags` Class

<p>Class to record LLVM IR flag for a recipe along with it. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPRecipeWithIRFlags { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a concrete Recipe that models a single VPlan-level instruction. <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe">VPReplicateRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe">VPReplicateRecipe</a> replicates a given instruction producing multiple scalar copies of the original scalar type, one per lane, instead of producing a single copy of widened type for all lanes. <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpreversevectorpointerrecipe">VPReverseVectorPointerRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe to compute the pointers for widened memory accesses of IndexTy in reverse order. <a href="/web-llvm/docs/api/classes/llvm/vpreversevectorpointerrecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe">VPScalarIVStepsRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe for handling phi nodes of integer and floating-point inductions, producing their scalar values. <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvectorpointerrecipe">VPVectorPointerRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe to compute the pointers for widened memory accesses of IndexTy. <a href="/web-llvm/docs/api/classes/llvm/vpvectorpointerrecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe">VPWidenCallRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe for widening Call instructions using library calls. <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe">VPWidenCastRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe">VPWidenCastRecipe</a> is a recipe to create vector cast instructions. <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpwidengeprecipe">VPWidenGEPRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe for handling GEP instructions. <a href="/web-llvm/docs/api/classes/llvm/vpwidengeprecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe">VPWidenIntrinsicRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe for widening vector intrinsics. <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe">VPWidenRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe">VPWidenRecipe</a> is a recipe for producing a widened instruction using the opcode and operands of the recipe. <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe">VPWidenSelectRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe for widening select instructions. <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OperationType : unsigned char { <a href="#a911daa1df45ab131dff5f9508d3d3944">...</a> }</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#afbcee996669bdac73eae32d28d2e4bd6">VPRecipeWithIRFlags</a> (const unsigned char SC, IterT Operands, DebugLoc DL={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a76fb233396e6e9451f58b35eb03681da">VPRecipeWithIRFlags</a> (const unsigned char SC, IterT Operands, Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a2d2ea4f32a1b1ab480f71ff57f333a29">VPRecipeWithIRFlags</a> (const unsigned char SC, IterT Operands, CmpInst::Predicate Pred, DebugLoc DL={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a7a3f9df557af00dc340a53baa72b82fa">VPRecipeWithIRFlags</a> (const unsigned char SC, IterT Operands, WrapFlagsTy WrapFlags, DebugLoc DL={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a5f0ce1cd8078c5d26d4f1371418167a2">VPRecipeWithIRFlags</a> (const unsigned char SC, IterT Operands, FastMathFlags FMFs, DebugLoc DL={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a8b2445177ae907329f54dd1e2f1ad2ea">VPRecipeWithIRFlags</a> (const unsigned char SC, IterT Operands, DisjointFlagsTy DisjointFlags, DebugLoc DL={})</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a449030719f82e4ad91df7b147633ed31">VPRecipeWithIRFlags</a> (const unsigned char SC, IterT Operands, GEPNoWrapFlags GEPFlags, DebugLoc DL={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a632a4f81f86235824e44d9a175d7c42d">dropPoisonGeneratingFlags</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop all poison-generating flags. <a href="#a632a4f81f86235824e44d9a175d7c42d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3864f5d4ddd326182fa0499094807f2a">setFlags</a> (Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the IR flags for <span class="doxyComputerOutput">I</span>. <a href="#a3864f5d4ddd326182fa0499094807f2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebf13d184ccc53ceece6f88d73482e62">getPredicate</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2241b30dd473ac42773e63edc55fdec6">getGEPNoWrapFlags</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a648f12184c1f646e80420b0ab9817fa0">hasFastMathFlags</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recipe has fast-math flags. <a href="#a648f12184c1f646e80420b0ab9817fa0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af44641b38a715b1326e5000ae611c9ea">getFastMathFlags</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8c104e0e107052a474c7b2c69c381f6">hasNoUnsignedWrap</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec727f399d69f1ddfc8b5017b428eec1">hasNoSignedWrap</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6a97204510d9673b83f77dd7802d2c2">isDisjoint</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6a91bbf1cfed2d6ba572ca974c94161">printFlags</a> (raw_ostream &amp;O) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a940d57a4e61a82b43fbc6179a0946951">transferFlags</a> (VPRecipeWithIRFlags &amp;Other)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ad7ab1d782abf24bd0e0821f61ff84d">CmpPredicate</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vprecipewithirflags/wrapflagsty">WrapFlagsTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3a63ff3b45bc15bb37319586c23f61f">WrapFlags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vprecipewithirflags/disjointflagsty">DisjointFlagsTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77a22de076f064aa8fe2df2a8ae35132">DisjointFlags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ExactFlagsTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01354ff4b56aad0b847022223aca4862">ExactFlags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e2e3852ea03bfa9505e2212c609c3cd">GEPFlags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">NonNegFlagsTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12d37e09da8dcccb963cb3f737aae3e2">NonNegFlags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FastMathFlagsTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03dfa6aae22c9aaa0ce5808161d42c45">FMFs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dc5ae9a82b893c11ba3d7f374b18313">AllFlags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">OperationType</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3deb7cde9b0c6ded4b089c2a143be191">OpType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags">llvm::VPRecipeWithIRFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a378adffc949f1c9a4fa0c65d06a2e601"></a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54d2904ac21ce6bde6f585c3de70393e">classof</a> (const VPRecipeBase *R)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3cb42045db6b2aa5a9491d48d5f573c">classof</a> (const VPUser *U)</td>
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

<p>Class to record LLVM IR flag for a recipe along with it.</p>

<p>Definition at line 922 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### OperationType {#a911daa1df45ab131dff5f9508d3d3944}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::VPRecipeWithIRFlags::OperationType : unsigned char</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Cmp<a id="a911daa1df45ab131dff5f9508d3d3944ac9b4c62f6dc1bc5caf3c768b687cbf7e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OverflowingBinOp<a id="a911daa1df45ab131dff5f9508d3d3944a7eb1ed04124a3bceb46afde183aa234a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DisjointOp<a id="a911daa1df45ab131dff5f9508d3d3944af2c4c0f69ad5a794fcf81c5bc7e4288a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PossiblyExactOp<a id="a911daa1df45ab131dff5f9508d3d3944a5aa73e9a46192158baa5d73a5c00ef71"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GEPOp<a id="a911daa1df45ab131dff5f9508d3d3944a050b71a6c1d6d68d04963d2b434d2817"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FPMathOp<a id="a911daa1df45ab131dff5f9508d3d3944a62ab14388ce6fe91aec46c445b80e73f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NonNegOp<a id="a911daa1df45ab131dff5f9508d3d3944a35eaf42c700d5c66ff2c98c9216d3659"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Other<a id="a911daa1df45ab131dff5f9508d3d3944a6311ae17c1ee52b36e68aaf4ad066387"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 923 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VPRecipeWithIRFlags() {#afbcee996669bdac73eae32d28d2e4bd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPRecipeWithIRFlags::VPRecipeWithIRFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char SC, IterT Operands, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={})</td>
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



<p>Definition at line 987 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a940d57a4e61a82b43fbc6179a0946951">transferFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a432b57e3924afb475fc91aafb56b5e0d">llvm::VPInstruction::VPInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a48a72267f2f64714199a91155da60888">llvm::VPInstruction::VPInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a256e4c0d88c74db616499748f0a224a1">llvm::VPInstruction::VPInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#acb424057b318d4f0d94f58c87edb8e54">llvm::VPReplicateRecipe::VPReplicateRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreversevectorpointerrecipe/#adc1e615953be3e42a0485494617fc578">llvm::VPReverseVectorPointerRecipe::VPReverseVectorPointerRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#a86f8e3e79f9e3f33b9d5096454eeb57f">llvm::VPScalarIVStepsRecipe::VPScalarIVStepsRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvectorpointerrecipe/#a7651c65171e0ddf854f4f9cb0d231097">llvm::VPVectorPointerRecipe::VPVectorPointerRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#a89da8eb8fa05341729766c14d53f3760">llvm::VPWidenCastRecipe::VPWidenCastRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#a0403c9b207ba733675ef20cb8828d00c">llvm::VPWidenCastRecipe::VPWidenCastRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidengeprecipe/#ae1555a62444119fa96252a26dcf4894a">llvm::VPWidenGEPRecipe::VPWidenGEPRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#ab536824eb33f00c91befa326c11c1570">llvm::VPWidenRecipe::VPWidenRecipe</a> and <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#a15b2d34037ce5ecddecce8d53a2ce7cf">llvm::VPWidenSelectRecipe::VPWidenSelectRecipe</a>.</p>

</div>
</div>

### VPRecipeWithIRFlags() {#a76fb233396e6e9451f58b35eb03681da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPRecipeWithIRFlags::VPRecipeWithIRFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char SC, IterT Operands, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 994 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="#a3dc5ae9a82b893c11ba3d7f374b18313">AllFlags</a>, <a href="#a1ad7ab1d782abf24bd0e0821f61ff84d">CmpPredicate</a>, <a href="#a77a22de076f064aa8fe2df2a8ae35132">DisjointFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a01354ff4b56aad0b847022223aca4862">ExactFlags</a>, <a href="#a03dfa6aae22c9aaa0ce5808161d42c45">FMFs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="#a8e2e3852ea03bfa9505e2212c609c3cd">GEPFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a733c4c530159a8b86223376c0696430e">llvm::VPRecipeBase::getDebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a12d37e09da8dcccb963cb3f737aae3e2">NonNegFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/vpsingledefrecipe/#a698c2c1cbd9f6caace410d3733bb17b9">llvm::VPSingleDefRecipe::VPSingleDefRecipe</a> and <a href="#ab3a63ff3b45bc15bb37319586c23f61f">WrapFlags</a>.</p>

</div>
</div>

### VPRecipeWithIRFlags() {#a2d2ea4f32a1b1ab480f71ff57f333a29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPRecipeWithIRFlags::VPRecipeWithIRFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char SC, IterT Operands, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={})</td>
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



<p>Definition at line 1024 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### VPRecipeWithIRFlags() {#a7a3f9df557af00dc340a53baa72b82fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPRecipeWithIRFlags::VPRecipeWithIRFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char SC, IterT Operands, <a href="/web-llvm/docs/api/structs/llvm/vprecipewithirflags/wrapflagsty">WrapFlagsTy</a> WrapFlags, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={})</td>
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



<p>Definition at line 1030 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="#ab3a63ff3b45bc15bb37319586c23f61f">WrapFlags</a>.</p>

</div>
</div>

### VPRecipeWithIRFlags() {#a5f0ce1cd8078c5d26d4f1371418167a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPRecipeWithIRFlags::VPRecipeWithIRFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char SC, IterT Operands, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMFs, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={})</td>
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



<p>Definition at line 1036 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="#a03dfa6aae22c9aaa0ce5808161d42c45">FMFs</a>.</p>

</div>
</div>

### VPRecipeWithIRFlags() {#a8b2445177ae907329f54dd1e2f1ad2ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPRecipeWithIRFlags::VPRecipeWithIRFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char SC, IterT Operands, <a href="/web-llvm/docs/api/structs/llvm/vprecipewithirflags/disjointflagsty">DisjointFlagsTy</a> DisjointFlags, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={})</td>
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



<p>Definition at line 1042 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="#a77a22de076f064aa8fe2df2a8ae35132">DisjointFlags</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### VPRecipeWithIRFlags() {#a449030719f82e4ad91df7b147633ed31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPRecipeWithIRFlags::VPRecipeWithIRFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char SC, IterT Operands, <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a> GEPFlags, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={})</td>
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



<p>Definition at line 1049 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="#a8e2e3852ea03bfa9505e2212c609c3cd">GEPFlags</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dropPoisonGeneratingFlags() {#a632a4f81f86235824e44d9a175d7c42d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPRecipeWithIRFlags::dropPoisonGeneratingFlags ()</td>
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

<p>Drop all poison-generating flags.</p>

<p>Definition at line 1073 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="#a77a22de076f064aa8fe2df2a8ae35132">DisjointFlags</a>, <a href="#a01354ff4b56aad0b847022223aca4862">ExactFlags</a>, <a href="#a03dfa6aae22c9aaa0ce5808161d42c45">FMFs</a>, <a href="#a8e2e3852ea03bfa9505e2212c609c3cd">GEPFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags/#ad41d3c975038ec4a4fc791601729124e">llvm::GEPNoWrapFlags::none</a>, <a href="#a12d37e09da8dcccb963cb3f737aae3e2">NonNegFlags</a> and <a href="#ab3a63ff3b45bc15bb37319586c23f61f">WrapFlags</a>.</p>

</div>
</div>

### getFastMathFlags() {#af44641b38a715b1326e5000ae611c9ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastMathFlags VPRecipeWithIRFlags::getFastMathFlags ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1148 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a03dfa6aae22c9aaa0ce5808161d42c45">FMFs</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a17e649128903d9aec55cf75d3c14c545">llvm::FastMathFlags::setAllowContract</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#abd093480248d834428a5e8f9ad5a22dd">llvm::FastMathFlags::setAllowReassoc</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a449c5c7d9356857fe89132ab9223069a">llvm::FastMathFlags::setAllowReciprocal</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#acc2bf5d2312d38f951004a8900fc4f7f">llvm::FastMathFlags::setApproxFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ad5fb387bdc497f49b0f556ed9f900560">llvm::FastMathFlags::setNoInfs</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#abbceb1c6e5c4b49f53b381a8fad9e12a">llvm::FastMathFlags::setNoNaNs</a> and <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a9b87b2b5c4b6b7d083212a0c93684f72">llvm::FastMathFlags::setNoSignedZeros</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#a80d30778f28687b5c3bddf019b55478c">llvm::VPScalarIVStepsRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#ae8d6a4dd88f6b0c4ac0c4c8a46b024e0">llvm::VPWidenIntrinsicRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#af2ef259f4a63359fe35f05b8b67a911b">llvm::VPInstruction::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#acdd340f122251b99aaee3308d31f1230">llvm::VPScalarIVStepsRecipe::execute</a>, <a href="#ae6a91bbf1cfed2d6ba572ca974c94161">printFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#a71852a79224b1fc11ef13ea5055fe0fb">llvm::VPScalarIVStepsRecipe::VPScalarIVStepsRecipe</a>.</p>

</div>
</div>

### getGEPNoWrapFlags() {#a2241b30dd473ac42773e63edc55fdec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPNoWrapFlags llvm::VPRecipeWithIRFlags::getGEPNoWrapFlags ()</td>
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



<p>Definition at line 1143 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="#a8e2e3852ea03bfa9505e2212c609c3cd">GEPFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpreversevectorpointerrecipe/#a35baec6b7c56d47b6b7e002a92b0621f">llvm::VPReverseVectorPointerRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvectorpointerrecipe/#af0756969ccfa0f31807a67c9b0caf92f">llvm::VPVectorPointerRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreversevectorpointerrecipe/#ab76c8b759635aabfadc49dc1292aec2c">llvm::VPReverseVectorPointerRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvectorpointerrecipe/#a82d57109b0437debe570e7dae895f3e3">llvm::VPVectorPointerRecipe::execute</a> and <a href="/web-llvm/docs/api/classes/llvm/vpwidengeprecipe/#a1b84446d2e199358a8406e7c92f51f03">llvm::VPWidenGEPRecipe::execute</a>.</p>

</div>
</div>

### getPredicate() {#aebf13d184ccc53ceece6f88d73482e62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst::Predicate llvm::VPRecipeWithIRFlags::getPredicate ()</td>
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



<p>Definition at line 1137 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a1ad7ab1d782abf24bd0e0821f61ff84d">CmpPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a0075161c54fc525d16130fa2e1891ad2">llvm::VPWidenRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a1217df326ed753111e60d3eaef272ded">llvm::VPWidenRecipe::execute</a> and <a href="#ae6a91bbf1cfed2d6ba572ca974c94161">printFlags</a>.</p>

</div>
</div>

### hasFastMathFlags() {#a648f12184c1f646e80420b0ab9817fa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPRecipeWithIRFlags::hasFastMathFlags ()</td>
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

<p>Returns true if the recipe has fast-math flags.</p>

<p>Definition at line 1146 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#a80d30778f28687b5c3bddf019b55478c">llvm::VPScalarIVStepsRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#ae8d6a4dd88f6b0c4ac0c4c8a46b024e0">llvm::VPWidenIntrinsicRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#af2ef259f4a63359fe35f05b8b67a911b">llvm::VPInstruction::execute</a> and <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#acdd340f122251b99aaee3308d31f1230">llvm::VPScalarIVStepsRecipe::execute</a>.</p>

</div>
</div>

### hasNoSignedWrap() {#aec727f399d69f1ddfc8b5017b428eec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPRecipeWithIRFlags::hasNoSignedWrap ()</td>
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



<p>Definition at line 1156 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ab3a63ff3b45bc15bb37319586c23f61f">WrapFlags</a>.</p>

</div>
</div>

### hasNoUnsignedWrap() {#ab8c104e0e107052a474c7b2c69c381f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPRecipeWithIRFlags::hasNoUnsignedWrap ()</td>
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



<p>Definition at line 1150 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ab3a63ff3b45bc15bb37319586c23f61f">WrapFlags</a>.</p>

</div>
</div>

### isDisjoint() {#ad6a97204510d9673b83f77dd7802d2c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPRecipeWithIRFlags::isDisjoint ()</td>
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



<p>Definition at line 1162 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a77a22de076f064aa8fe2df2a8ae35132">DisjointFlags</a>.</p>

</div>
</div>

### printFlags() {#ae6a91bbf1cfed2d6ba572ca974c94161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPRecipeWithIRFlags::printFlags (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1169 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 1363 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="#a77a22de076f064aa8fe2df2a8ae35132">DisjointFlags</a>, <a href="#a01354ff4b56aad0b847022223aca4862">ExactFlags</a>, <a href="#a8e2e3852ea03bfa9505e2212c609c3cd">GEPFlags</a>, <a href="#af44641b38a715b1326e5000ae611c9ea">getFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a5b21038d9b822b20c59e7ce5b12582e1">llvm::VPUser::getNumOperands</a>, <a href="#aebf13d184ccc53ceece6f88d73482e62">getPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa68a2d2c06a10b1e5a5bc778a107c0ba">llvm::CmpInst::getPredicateName</a>, <a href="#a12d37e09da8dcccb963cb3f737aae3e2">NonNegFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a82446fc88a017bf06a8e090573334b78">llvm::FastMathFlags::print</a> and <a href="#ab3a63ff3b45bc15bb37319586c23f61f">WrapFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#aca839409ad4f4fb66241f6b97da6674f">llvm::VPInstruction::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#a202af2dd775be9a857e92e8ca6190b4f">llvm::VPReplicateRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreversevectorpointerrecipe/#a9c7a98f9a6cf962c378e7e733295a009">llvm::VPReverseVectorPointerRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#a039c5bd63f390c0b66e2548b69a372c5">llvm::VPWidenCallRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#a30fd23ee3def3f12fad8496e85755c2a">llvm::VPWidenCastRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a64949951a81f6c67ecbd51ad90374828">llvm::VPWidenEVLRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidengeprecipe/#a0bc2944c24608efc8476b4bb1bc5606f">llvm::VPWidenGEPRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a5ad4e4df14b5a3c6905892a8f4bcb580">llvm::VPWidenRecipe::print</a> and <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#a75740005a7cfb534940606c60654527e">llvm::VPWidenSelectRecipe::print</a>.</p>

</div>
</div>

### setFlags() {#a3864f5d4ddd326182fa0499094807f2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPRecipeWithIRFlags::setFlags (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Set the IR flags for <span class="doxyComputerOutput">I</span>.</p>

<p>Definition at line 1104 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a77a22de076f064aa8fe2df2a8ae35132">DisjointFlags</a>, <a href="#a01354ff4b56aad0b847022223aca4862">ExactFlags</a>, <a href="#a03dfa6aae22c9aaa0ce5808161d42c45">FMFs</a>, <a href="#a8e2e3852ea03bfa9505e2212c609c3cd">GEPFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a12d37e09da8dcccb963cb3f737aae3e2">NonNegFlags</a> and <a href="#ab3a63ff3b45bc15bb37319586c23f61f">WrapFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#acd93ffe413319e78d7c62688cc86eb6c">llvm::VPWidenCallRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#a9b432a2a53b6ec71e9290e6f9d7582ea">llvm::VPWidenCastRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a703a08e4f8a8f64b8be733d194070cd1">llvm::VPWidenEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#ad6ab589f9da183bfc7227344c30aab78">llvm::VPWidenIntrinsicRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a1217df326ed753111e60d3eaef272ded">llvm::VPWidenRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#a8ab6a201a32f4db51d8f030c5d3ba5c6">llvm::VPWidenSelectRecipe::execute</a> and <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a4690286163882c35068b1908f4d752fd">llvm::InnerLoopVectorizer::scalarizeInstruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### transferFlags() {#a940d57a4e61a82b43fbc6179a0946951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPRecipeWithIRFlags::transferFlags (<a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags">VPRecipeWithIRFlags</a> &amp; Other)</td>
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



<p>Definition at line 980 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="#a3dc5ae9a82b893c11ba3d7f374b18313">AllFlags</a> and <a href="#afbcee996669bdac73eae32d28d2e4bd6">VPRecipeWithIRFlags</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AllFlags {#a3dc5ae9a82b893c11ba3d7f374b18313}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VPRecipeWithIRFlags::AllFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 976 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a940d57a4e61a82b43fbc6179a0946951">transferFlags</a> and <a href="#a76fb233396e6e9451f58b35eb03681da">VPRecipeWithIRFlags</a>.</p>

</div>
</div>

### CmpPredicate {#a1ad7ab1d782abf24bd0e0821f61ff84d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst::Predicate llvm::VPRecipeWithIRFlags::CmpPredicate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 969 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#aebf13d184ccc53ceece6f88d73482e62">getPredicate</a> and <a href="#a76fb233396e6e9451f58b35eb03681da">VPRecipeWithIRFlags</a>.</p>

</div>
</div>

### DisjointFlags {#a77a22de076f064aa8fe2df2a8ae35132}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DisjointFlagsTy llvm::VPRecipeWithIRFlags::DisjointFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 971 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a632a4f81f86235824e44d9a175d7c42d">dropPoisonGeneratingFlags</a>, <a href="#ad6a97204510d9673b83f77dd7802d2c2">isDisjoint</a>, <a href="#ae6a91bbf1cfed2d6ba572ca974c94161">printFlags</a>, <a href="#a3864f5d4ddd326182fa0499094807f2a">setFlags</a>, <a href="#a8b2445177ae907329f54dd1e2f1ad2ea">VPRecipeWithIRFlags</a> and <a href="#a76fb233396e6e9451f58b35eb03681da">VPRecipeWithIRFlags</a>.</p>

</div>
</div>

### ExactFlags {#a01354ff4b56aad0b847022223aca4862}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExactFlagsTy llvm::VPRecipeWithIRFlags::ExactFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 972 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a632a4f81f86235824e44d9a175d7c42d">dropPoisonGeneratingFlags</a>, <a href="#ae6a91bbf1cfed2d6ba572ca974c94161">printFlags</a>, <a href="#a3864f5d4ddd326182fa0499094807f2a">setFlags</a> and <a href="#a76fb233396e6e9451f58b35eb03681da">VPRecipeWithIRFlags</a>.</p>

</div>
</div>

### FMFs {#a03dfa6aae22c9aaa0ce5808161d42c45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastMathFlagsTy llvm::VPRecipeWithIRFlags::FMFs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 975 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a632a4f81f86235824e44d9a175d7c42d">dropPoisonGeneratingFlags</a>, <a href="#af44641b38a715b1326e5000ae611c9ea">getFastMathFlags</a>, <a href="#a3864f5d4ddd326182fa0499094807f2a">setFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a256e4c0d88c74db616499748f0a224a1">llvm::VPInstruction::VPInstruction</a>, <a href="#a5f0ce1cd8078c5d26d4f1371418167a2">VPRecipeWithIRFlags</a>, <a href="#a76fb233396e6e9451f58b35eb03681da">VPRecipeWithIRFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#a86f8e3e79f9e3f33b9d5096454eeb57f">llvm::VPScalarIVStepsRecipe::VPScalarIVStepsRecipe</a>.</p>

</div>
</div>

### GEPFlags {#a8e2e3852ea03bfa9505e2212c609c3cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPNoWrapFlags llvm::VPRecipeWithIRFlags::GEPFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 973 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a632a4f81f86235824e44d9a175d7c42d">dropPoisonGeneratingFlags</a>, <a href="#a2241b30dd473ac42773e63edc55fdec6">getGEPNoWrapFlags</a>, <a href="#ae6a91bbf1cfed2d6ba572ca974c94161">printFlags</a>, <a href="#a3864f5d4ddd326182fa0499094807f2a">setFlags</a>, <a href="#a449030719f82e4ad91df7b147633ed31">VPRecipeWithIRFlags</a>, <a href="#a76fb233396e6e9451f58b35eb03681da">VPRecipeWithIRFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreversevectorpointerrecipe/#adc1e615953be3e42a0485494617fc578">llvm::VPReverseVectorPointerRecipe::VPReverseVectorPointerRecipe</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvectorpointerrecipe/#a7651c65171e0ddf854f4f9cb0d231097">llvm::VPVectorPointerRecipe::VPVectorPointerRecipe</a>.</p>

</div>
</div>

### NonNegFlags {#a12d37e09da8dcccb963cb3f737aae3e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NonNegFlagsTy llvm::VPRecipeWithIRFlags::NonNegFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 974 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a632a4f81f86235824e44d9a175d7c42d">dropPoisonGeneratingFlags</a>, <a href="#ae6a91bbf1cfed2d6ba572ca974c94161">printFlags</a>, <a href="#a3864f5d4ddd326182fa0499094807f2a">setFlags</a> and <a href="#a76fb233396e6e9451f58b35eb03681da">VPRecipeWithIRFlags</a>.</p>

</div>
</div>

### WrapFlags {#ab3a63ff3b45bc15bb37319586c23f61f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WrapFlagsTy llvm::VPRecipeWithIRFlags::WrapFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 970 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a632a4f81f86235824e44d9a175d7c42d">dropPoisonGeneratingFlags</a>, <a href="#aec727f399d69f1ddfc8b5017b428eec1">hasNoSignedWrap</a>, <a href="#ab8c104e0e107052a474c7b2c69c381f6">hasNoUnsignedWrap</a>, <a href="#ae6a91bbf1cfed2d6ba572ca974c94161">printFlags</a>, <a href="#a3864f5d4ddd326182fa0499094807f2a">setFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#aa008922f90e2a3966fb4582c3abd4f1d">llvm::VPInstruction::VPInstruction</a>, <a href="#a76fb233396e6e9451f58b35eb03681da">VPRecipeWithIRFlags</a> and <a href="#a7a3f9df557af00dc340a53baa72b82fa">VPRecipeWithIRFlags</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#a378adffc949f1c9a4fa0c65d06a2e601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::VPRecipeWithIRFlags llvm::VPRecipeWithIRFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 977 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### OpType {#a3deb7cde9b0c6ded4b089c2a143be191}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OperationType llvm::VPRecipeWithIRFlags::OpType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 966 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a54d2904ac21ce6bde6f585c3de70393e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPRecipeWithIRFlags::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> * R)</td>
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



<p>Definition at line 1055 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#af3cb42045db6b2aa5a9491d48d5f573c">classof</a>.</p>

</div>
</div>

### classof() {#af3cb42045db6b2aa5a9491d48d5f573c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPRecipeWithIRFlags::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> * U)</td>
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



<p>Definition at line 1067 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="#a54d2904ac21ce6bde6f585c3de70393e">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

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
