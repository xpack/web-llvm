---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/fixedpointbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FixedPointBuilder` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;class IRBuilderTy&gt;
class llvm::FixedPointBuilder&lt;IRBuilderTy&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">llvm/IR/FixedPointBuilder.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a3a93870678b48fd7dda605b92fe5584e">FixedPointBuilder</a> (IRBuilderTy &amp;Builder)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aea8a3d9cdba1bf31cb6ddc51e7d77012">CreateFixedToFixed</a> (Value *Src, const FixedPointSemantics &amp;SrcSema, const FixedPointSemantics &amp;DstSema)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert an integer value representing a fixed-point number from one fixed-point semantic to another fixed-point semantic. <a href="#aea8a3d9cdba1bf31cb6ddc51e7d77012">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1d99db3b205c5c656e11e25cc98b9917">CreateFixedToInteger</a> (Value *Src, const FixedPointSemantics &amp;SrcSema, unsigned DstWidth, bool DstIsSigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert an integer value representing a fixed-point number to an integer with the given bit width and signedness. <a href="#a1d99db3b205c5c656e11e25cc98b9917">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac2cb8d79fa94ae788233f1af991fd9c4">CreateIntegerToFixed</a> (Value *Src, unsigned SrcIsSigned, const FixedPointSemantics &amp;DstSema)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert an integer value with the given signedness to an integer value representing the given fixed-point semantic. <a href="#ac2cb8d79fa94ae788233f1af991fd9c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a00109923471ab72b20f0959d8eb230b9">CreateFixedToFloating</a> (Value *Src, const FixedPointSemantics &amp;SrcSema, Type *DstTy)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0a1c9934f39747a96a2b6b42d0bec03e">CreateFloatingToFixed</a> (Value *Src, const FixedPointSemantics &amp;DstSema)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa663208669ad36fe54f6eb540b5bbf9b">CreateAdd</a> (Value *LHS, const FixedPointSemantics &amp;LHSSema, Value *RHS, const FixedPointSemantics &amp;RHSSema)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add two fixed-point values and return the result in their common semantic. <a href="#aa663208669ad36fe54f6eb540b5bbf9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae314a9eee47df21fd46102d80f666b4d">CreateSub</a> (Value *LHS, const FixedPointSemantics &amp;LHSSema, Value *RHS, const FixedPointSemantics &amp;RHSSema)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subtract two fixed-point values and return the result in their common semantic. <a href="#ae314a9eee47df21fd46102d80f666b4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac1e07222d14c1bc6e996ca85ca126e93">CreateMul</a> (Value *LHS, const FixedPointSemantics &amp;LHSSema, Value *RHS, const FixedPointSemantics &amp;RHSSema)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Multiply two fixed-point values and return the result in their common semantic. <a href="#ac1e07222d14c1bc6e996ca85ca126e93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a05b24458637907fb6e27a842cc8dc0fc">CreateDiv</a> (Value *LHS, const FixedPointSemantics &amp;LHSSema, Value *RHS, const FixedPointSemantics &amp;RHSSema)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Divide two fixed-point values and return the result in their common semantic. <a href="#a05b24458637907fb6e27a842cc8dc0fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a27e29ec6d1cfc7d82adcefe7fef1cf56">CreateShl</a> (Value *LHS, const FixedPointSemantics &amp;LHSSema, Value *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Left shift a fixed-point value by an unsigned integer value. <a href="#a27e29ec6d1cfc7d82adcefe7fef1cf56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5dce930d90c103945d94b3aff2ea5653">CreateShr</a> (Value *LHS, const FixedPointSemantics &amp;LHSSema, Value *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Right shift a fixed-point value by an unsigned integer value. <a href="#a5dce930d90c103945d94b3aff2ea5653">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a47c75914368b0b4f257b3c360234e2c1">CreateEQ</a> (Value *LHS, const FixedPointSemantics &amp;LHSSema, Value *RHS, const FixedPointSemantics &amp;RHSSema)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare two fixed-point values for equality. <a href="#a47c75914368b0b4f257b3c360234e2c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a29cb4d018a186719bafb7def86c1a6c9">CreateNE</a> (Value *LHS, const FixedPointSemantics &amp;LHSSema, Value *RHS, const FixedPointSemantics &amp;RHSSema)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare two fixed-point values for inequality. <a href="#a29cb4d018a186719bafb7def86c1a6c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a353b3d0c354bb60b1c99949f1609a3be">CreateLT</a> (Value *LHS, const FixedPointSemantics &amp;LHSSema, Value *RHS, const FixedPointSemantics &amp;RHSSema)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare two fixed-point values as LHS &lt; RHS. <a href="#a353b3d0c354bb60b1c99949f1609a3be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a789c837fb34aac813ffa033c82d85a1d">CreateLE</a> (Value *LHS, const FixedPointSemantics &amp;LHSSema, Value *RHS, const FixedPointSemantics &amp;RHSSema)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare two fixed-point values as LHS &lt;= RHS. <a href="#a789c837fb34aac813ffa033c82d85a1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a19ea93f686819dec71fd4bd02ceaee58">CreateGT</a> (Value *LHS, const FixedPointSemantics &amp;LHSSema, Value *RHS, const FixedPointSemantics &amp;RHSSema)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare two fixed-point values as LHS &gt; RHS. <a href="#a19ea93f686819dec71fd4bd02ceaee58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab1dc5bdd56ea4c643f7137cbec3708ed">CreateGE</a> (Value *LHS, const FixedPointSemantics &amp;LHSSema, Value *RHS, const FixedPointSemantics &amp;RHSSema)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare two fixed-point values as LHS &gt;= RHS. <a href="#ab1dc5bdd56ea4c643f7137cbec3708ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9521babd8c72503788fee137cf83d821">Convert</a> (Value *Src, const FixedPointSemantics &amp;SrcSema, const FixedPointSemantics &amp;DstSema, bool DstIsInteger)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ade246096c6f0e526863a4cc4ce270bca">getCommonBinopSemantic</a> (const FixedPointSemantics &amp;LHSSema, const FixedPointSemantics &amp;RHSSema)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the common semantic for two semantics, with the added imposition that saturated padded types retain the padding bit. <a href="#ade246096c6f0e526863a4cc4ce270bca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaa75a5fbe790d656277566bbc8e0bc2e">getAccommodatingFloatType</a> (Type *Ty, const FixedPointSemantics &amp;Sema)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a floating point type and a fixed-point semantic, return a floating point type which can accommodate the fixed-point semantic. <a href="#aaa75a5fbe790d656277566bbc8e0bc2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IRBuilderTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">IRBuilderTy &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a89fd0b649ddfa3da66ad2a7c1d1f81a9">B</a></td>
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


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FixedPointBuilder() {#a3a93870678b48fd7dda605b92fe5584e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::FixedPointBuilder (IRBuilderTy &amp; Builder)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### CreateAdd() {#aa663208669ad36fe54f6eb540b5bbf9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateAdd (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; LHSSema, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; RHSSema)</td>
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

<p>Add two fixed-point values and return the result in their common semantic.</p>


<p><span class="doxyComputerOutput">LHS</span> - The left hand side <span class="doxyComputerOutput">LHSSema</span> - The semantic of the left hand side <span class="doxyComputerOutput">RHS</span> - The right hand side <span class="doxyComputerOutput">RHSSema</span> - The semantic of the right hand side</p>


<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>


<p>References <a href="#aea8a3d9cdba1bf31cb6ddc51e7d77012">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFixedToFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a6e44daa940bc6479c419855e43d5f765">llvm::FixedPointSemantics::getCommonSemantics</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### CreateDiv() {#a05b24458637907fb6e27a842cc8dc0fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateDiv (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; LHSSema, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; RHSSema)</td>
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

<p>Divide two fixed-point values and return the result in their common semantic.</p>


<p><span class="doxyComputerOutput">LHS</span> - The left hand side <span class="doxyComputerOutput">LHSSema</span> - The semantic of the left hand side <span class="doxyComputerOutput">RHS</span> - The right hand side <span class="doxyComputerOutput">RHSSema</span> - The semantic of the right hand side</p>


<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>


<p>References <a href="#aea8a3d9cdba1bf31cb6ddc51e7d77012">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFixedToFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a6e44daa940bc6479c419855e43d5f765">llvm::FixedPointSemantics::getCommonSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### CreateEQ() {#a47c75914368b0b4f257b3c360234e2c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateEQ (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; LHSSema, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; RHSSema)</td>
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

<p>Compare two fixed-point values for equality.</p>


<p><span class="doxyComputerOutput">LHS</span> - The left hand side <span class="doxyComputerOutput">LHSSema</span> - The semantic of the left hand side <span class="doxyComputerOutput">RHS</span> - The right hand side <span class="doxyComputerOutput">RHSSema</span> - The semantic of the right hand side</p>


<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>


<p>References <a href="#aea8a3d9cdba1bf31cb6ddc51e7d77012">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFixedToFixed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### CreateFixedToFixed() {#aea8a3d9cdba1bf31cb6ddc51e7d77012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFixedToFixed (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; SrcSema, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; DstSema)</td>
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

<p>Convert an integer value representing a fixed-point number from one fixed-point semantic to another fixed-point semantic.</p>


<p><span class="doxyComputerOutput">Src</span> - The source value <span class="doxyComputerOutput">SrcSema</span> - The fixed-point semantic of the source value <span class="doxyComputerOutput">DstSema</span> - The resulting fixed-point semantic</p>


<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>


<p>Referenced by <a href="#aa663208669ad36fe54f6eb540b5bbf9b">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateAdd</a>, <a href="#a05b24458637907fb6e27a842cc8dc0fc">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateDiv</a>, <a href="#a47c75914368b0b4f257b3c360234e2c1">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateEQ</a>, <a href="#ab1dc5bdd56ea4c643f7137cbec3708ed">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateGE</a>, <a href="#a19ea93f686819dec71fd4bd02ceaee58">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateGT</a>, <a href="#a789c837fb34aac813ffa033c82d85a1d">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateLE</a>, <a href="#a353b3d0c354bb60b1c99949f1609a3be">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateLT</a>, <a href="#ac1e07222d14c1bc6e996ca85ca126e93">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateMul</a>, <a href="#a29cb4d018a186719bafb7def86c1a6c9">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateNE</a> and <a href="#ae314a9eee47df21fd46102d80f666b4d">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateSub</a>.</p>

</div>
</div>

### CreateFixedToFloating() {#a00109923471ab72b20f0959d8eb230b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFixedToFloating (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; SrcSema, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DstTy)</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a5eb21a8a338a43390965253fb71d152d">llvm::FixedPointSemantics::getScale</a> and <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a05ad0838e692b5cdc021f49da8343187">llvm::FixedPointSemantics::isSigned</a>.</p>

</div>
</div>

### CreateFixedToInteger() {#a1d99db3b205c5c656e11e25cc98b9917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFixedToInteger (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; SrcSema, unsigned DstWidth, bool DstIsSigned)</td>
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

<p>Convert an integer value representing a fixed-point number to an integer with the given bit width and signedness.</p>


<p><span class="doxyComputerOutput">Src</span> - The source value <span class="doxyComputerOutput">SrcSema</span> - The fixed-point semantic of the source value <span class="doxyComputerOutput">DstWidth</span> - The bit width of the result value <span class="doxyComputerOutput">DstIsSigned</span> - The signedness of the result value</p>


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#aebc9b19a86db06690ffcc4904907e8be">llvm::FixedPointSemantics::GetIntegerSemantics</a>.</p>

</div>
</div>

### CreateFloatingToFixed() {#a0a1c9934f39747a96a2b6b42d0bec03e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFloatingToFixed (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; DstSema)</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a5eb21a8a338a43390965253fb71d152d">llvm::FixedPointSemantics::getScale</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a2f3dab29dd773a1faa002a701261db99">llvm::FixedPointSemantics::getWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a516540ad4950d71de2266507041b9c6e">llvm::FixedPointSemantics::hasUnsignedPadding</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a56da39babaf07b5638145d232de64949">llvm::FixedPointSemantics::isSaturated</a> and <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a05ad0838e692b5cdc021f49da8343187">llvm::FixedPointSemantics::isSigned</a>.</p>

</div>
</div>

### CreateGE() {#ab1dc5bdd56ea4c643f7137cbec3708ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateGE (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; LHSSema, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; RHSSema)</td>
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

<p>Compare two fixed-point values as LHS &gt;= RHS.</p>


<p><span class="doxyComputerOutput">LHS</span> - The left hand side <span class="doxyComputerOutput">LHSSema</span> - The semantic of the left hand side <span class="doxyComputerOutput">RHS</span> - The right hand side <span class="doxyComputerOutput">RHSSema</span> - The semantic of the right hand side</p>


<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>


<p>References <a href="#aea8a3d9cdba1bf31cb6ddc51e7d77012">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFixedToFixed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### CreateGT() {#a19ea93f686819dec71fd4bd02ceaee58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateGT (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; LHSSema, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; RHSSema)</td>
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

<p>Compare two fixed-point values as LHS &gt; RHS.</p>


<p><span class="doxyComputerOutput">LHS</span> - The left hand side <span class="doxyComputerOutput">LHSSema</span> - The semantic of the left hand side <span class="doxyComputerOutput">RHS</span> - The right hand side <span class="doxyComputerOutput">RHSSema</span> - The semantic of the right hand side</p>


<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>


<p>References <a href="#aea8a3d9cdba1bf31cb6ddc51e7d77012">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFixedToFixed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### CreateIntegerToFixed() {#ac2cb8d79fa94ae788233f1af991fd9c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateIntegerToFixed (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Src, unsigned SrcIsSigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; DstSema)</td>
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

<p>Convert an integer value with the given signedness to an integer value representing the given fixed-point semantic.</p>


<p><span class="doxyComputerOutput">Src</span> - The source value <span class="doxyComputerOutput">SrcIsSigned</span> - The signedness of the source value <span class="doxyComputerOutput">DstSema</span> - The resulting fixed-point semantic</p>


<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#aebc9b19a86db06690ffcc4904907e8be">llvm::FixedPointSemantics::GetIntegerSemantics</a>.</p>

</div>
</div>

### CreateLE() {#a789c837fb34aac813ffa033c82d85a1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateLE (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; LHSSema, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; RHSSema)</td>
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

<p>Compare two fixed-point values as LHS &lt;= RHS.</p>


<p><span class="doxyComputerOutput">LHS</span> - The left hand side <span class="doxyComputerOutput">LHSSema</span> - The semantic of the left hand side <span class="doxyComputerOutput">RHS</span> - The right hand side <span class="doxyComputerOutput">RHSSema</span> - The semantic of the right hand side</p>


<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>


<p>References <a href="#aea8a3d9cdba1bf31cb6ddc51e7d77012">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFixedToFixed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### CreateLT() {#a353b3d0c354bb60b1c99949f1609a3be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateLT (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; LHSSema, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; RHSSema)</td>
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

<p>Compare two fixed-point values as LHS &lt; RHS.</p>


<p><span class="doxyComputerOutput">LHS</span> - The left hand side <span class="doxyComputerOutput">LHSSema</span> - The semantic of the left hand side <span class="doxyComputerOutput">RHS</span> - The right hand side <span class="doxyComputerOutput">RHSSema</span> - The semantic of the right hand side</p>


<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>


<p>References <a href="#aea8a3d9cdba1bf31cb6ddc51e7d77012">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFixedToFixed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### CreateMul() {#ac1e07222d14c1bc6e996ca85ca126e93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateMul (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; LHSSema, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; RHSSema)</td>
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

<p>Multiply two fixed-point values and return the result in their common semantic.</p>


<p><span class="doxyComputerOutput">LHS</span> - The left hand side <span class="doxyComputerOutput">LHSSema</span> - The semantic of the left hand side <span class="doxyComputerOutput">RHS</span> - The right hand side <span class="doxyComputerOutput">RHSSema</span> - The semantic of the right hand side</p>


<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>


<p>References <a href="#aea8a3d9cdba1bf31cb6ddc51e7d77012">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFixedToFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a6e44daa940bc6479c419855e43d5f765">llvm::FixedPointSemantics::getCommonSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### CreateNE() {#a29cb4d018a186719bafb7def86c1a6c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateNE (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; LHSSema, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; RHSSema)</td>
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

<p>Compare two fixed-point values for inequality.</p>


<p><span class="doxyComputerOutput">LHS</span> - The left hand side <span class="doxyComputerOutput">LHSSema</span> - The semantic of the left hand side <span class="doxyComputerOutput">RHS</span> - The right hand side <span class="doxyComputerOutput">RHSSema</span> - The semantic of the right hand side</p>


<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>


<p>References <a href="#aea8a3d9cdba1bf31cb6ddc51e7d77012">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFixedToFixed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### CreateShl() {#a27e29ec6d1cfc7d82adcefe7fef1cf56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateShl (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; LHSSema, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS)</td>
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

<p>Left shift a fixed-point value by an unsigned integer value.</p>


<p>The integer value can be any bit width. <span class="doxyComputerOutput">LHS</span> - The left hand side <span class="doxyComputerOutput">LHSSema</span> - The semantic of the left hand side <span class="doxyComputerOutput">RHS</span> - The right hand side</p>


<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a516540ad4950d71de2266507041b9c6e">llvm::FixedPointSemantics::hasUnsignedPadding</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a56da39babaf07b5638145d232de64949">llvm::FixedPointSemantics::isSaturated</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a05ad0838e692b5cdc021f49da8343187">llvm::FixedPointSemantics::isSigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### CreateShr() {#a5dce930d90c103945d94b3aff2ea5653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateShr (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; LHSSema, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS)</td>
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

<p>Right shift a fixed-point value by an unsigned integer value.</p>


<p>The integer value can be any bit width. <span class="doxyComputerOutput">LHS</span> - The left hand side <span class="doxyComputerOutput">LHSSema</span> - The semantic of the left hand side <span class="doxyComputerOutput">RHS</span> - The right hand side</p>


<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a05ad0838e692b5cdc021f49da8343187">llvm::FixedPointSemantics::isSigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### CreateSub() {#ae314a9eee47df21fd46102d80f666b4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateSub (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; LHSSema, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; RHSSema)</td>
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

<p>Subtract two fixed-point values and return the result in their common semantic.</p>


<p><span class="doxyComputerOutput">LHS</span> - The left hand side <span class="doxyComputerOutput">LHSSema</span> - The semantic of the left hand side <span class="doxyComputerOutput">RHS</span> - The right hand side <span class="doxyComputerOutput">RHSSema</span> - The semantic of the right hand side</p>


<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>


<p>References <a href="#aea8a3d9cdba1bf31cb6ddc51e7d77012">llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::CreateFixedToFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#a6e44daa940bc6479c419855e43d5f765">llvm::FixedPointSemantics::getCommonSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### Convert() {#a9521babd8c72503788fee137cf83d821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::Convert (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; SrcSema, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; DstSema, bool DstIsInteger)</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>

</div>
</div>

### getAccommodatingFloatType() {#aaa75a5fbe790d656277566bbc8e0bc2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::getAccommodatingFloatType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; Sema)</td>
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

<p>Given a floating point type and a fixed-point semantic, return a floating point type which can accommodate the fixed-point semantic.</p>


<p>This is either <span class="doxyComputerOutput">Ty</span>, or a floating point type with a larger exponent than Ty.</p>


<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>

</div>
</div>

### getCommonBinopSemantic() {#ade246096c6f0e526863a4cc4ce270bca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedPointSemantics llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::getCommonBinopSemantic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; LHSSema, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics">FixedPointSemantics</a> &amp; RHSSema)</td>
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

<p>Get the common semantic for two semantics, with the added imposition that saturated padded types retain the padding bit.</p>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### B {#a89fd0b649ddfa3da66ad2a7c1d1f81a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IRBuilderTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRBuilderTy&amp; llvm::FixedPointBuilder&lt; IRBuilderTy &gt;::B</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fixedpointbuilder-h">FixedPointBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
