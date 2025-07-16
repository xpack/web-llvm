---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gbinop
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GBinOp` Class Reference

<p>Represents a binary operation, i.e, x = y op z. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GBinOp { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">llvm/CodeGen/GlobalISel/GenericMachineInstrs.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr">GenericMachineInstr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A base class for all GenericMachineInstrs. <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gfbinop">GFBinOp</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a floating point binary operation. <a href="/web-llvm/docs/api/classes/llvm/gfbinop/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gintbinop">GIntBinOp</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an integer binary operation. <a href="/web-llvm/docs/api/classes/llvm/gintbinop/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/glogicalbinop">GLogicalBinOp</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a logical binary operation. <a href="/web-llvm/docs/api/classes/llvm/glogicalbinop/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16344f792b3875c54ea12aaaa8adc790">getLHSReg</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4382d9d406beb612f27cd7e036f5c47">getRHSReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d88700afd4d842304fa031c572f2ffa">classof</a> (const MachineInstr *MI)</td>
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

<p>Represents a binary operation, i.e, x = y op z.</p>

<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getLHSReg() {#a16344f792b3875c54ea12aaaa8adc790}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::GBinOp::getLHSReg ()</td>
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



<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ab46d848f3726829246738eb9d78aebf9">llvm::CombinerHelper::matchAddOverflow</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a71eafce3200f8a358c6855e3b6ee0a51">llvm::CombinerHelper::matchFoldAMinusC1MinusC2</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a183457f9d99bea5ee1a2fd06ceb9bb99">llvm::CombinerHelper::matchFoldAMinusC1PlusC2</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a207867c80e7ad2da595e7a9adedcb612">llvm::CombinerHelper::matchFoldAPlusC1MinusC2</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a6b45fbac775c8ccd0b606e0a5ea671bf">llvm::CombinerHelper::matchFoldC1Minus2MinusC2</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a05e094eb5ea044b72cda4473bc6d78fc">llvm::CombinerHelper::matchFoldC2MinusAPlusC1</a> and <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ac88c813e35b6d1a4966b0ee24a5c8b9a">llvm::CombinerHelper::matchSubOfVScale</a>.</p>

</div>
</div>

### getRHSReg() {#ab4382d9d406beb612f27cd7e036f5c47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::GBinOp::getRHSReg ()</td>
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



<p>Definition at line 673 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ab46d848f3726829246738eb9d78aebf9">llvm::CombinerHelper::matchAddOverflow</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a82dc058091aed201fb1fbdd0ab8e5c3d">llvm::CombinerHelper::matchCombineSubToAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a71eafce3200f8a358c6855e3b6ee0a51">llvm::CombinerHelper::matchFoldAMinusC1MinusC2</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a183457f9d99bea5ee1a2fd06ceb9bb99">llvm::CombinerHelper::matchFoldAMinusC1PlusC2</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a207867c80e7ad2da595e7a9adedcb612">llvm::CombinerHelper::matchFoldAPlusC1MinusC2</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a6b45fbac775c8ccd0b606e0a5ea671bf">llvm::CombinerHelper::matchFoldC1Minus2MinusC2</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a05e094eb5ea044b72cda4473bc6d78fc">llvm::CombinerHelper::matchFoldC2MinusAPlusC1</a> and <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ac88c813e35b6d1a4966b0ee24a5c8b9a">llvm::CombinerHelper::matchSubOfVScale</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a4d88700afd4d842304fa031c572f2ffa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GBinOp::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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



<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
