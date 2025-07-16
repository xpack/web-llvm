---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/ms-demangle/primitivetypenode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PrimitiveTypeNode` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::ms_demangle::PrimitiveTypeNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">llvm/Demangle/MicrosoftDemangleNodes.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/typenode">TypeNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba9333d2f5f794c688cdc1668d7a74d9">PrimitiveTypeNode</a> (PrimitiveKind K)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88fdf21e5fba4ee1f1e45d5fbd5decda">outputPre</a> (OutputBuffer &amp;OB, OutputFlags Flags) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae660fe1daca351f63e70447853ff3b38">outputPost</a> (OutputBuffer &amp;OB, OutputFlags Flags) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1">PrimitiveKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85a637334fd8a89836c01b4306c93c47">PrimKind</a></td>
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


<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PrimitiveTypeNode() {#aba9333d2f5f794c688cdc1668d7a74d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ms_demangle::PrimitiveTypeNode::PrimitiveTypeNode (<a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1">PrimitiveKind</a> K)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a234f091f9559c82176ae3e89447add46ac2d18c0838a320f641b24829355f48ef">llvm::ms_demangle::PrimitiveType</a>, <a href="#a85a637334fd8a89836c01b4306c93c47">PrimKind</a> and <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/typenode/#a4c498ca8535b565f0cd03672c7f4a55a">llvm::ms_demangle::TypeNode::TypeNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### outputPost() {#ae660fe1daca351f63e70447853ff3b38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ms_demangle::PrimitiveTypeNode::outputPost (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9e06032afffbcfd197a80acc92afce93">OutputFlags</a> Flags)</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>

</div>
</div>

### outputPre() {#a88fdf21e5fba4ee1f1e45d5fbd5decda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PrimitiveTypeNode::outputPre (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9e06032afffbcfd197a80acc92afce93">OutputFlags</a> Flags)</td>
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



<p>Declaration at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp">MicrosoftDemangleNodes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1a06b9281e396db002010bde1de57262eb">llvm::ms_demangle::Auto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1ac26f15e86e3de4c398a8273272aba034">llvm::ms_demangle::Bool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1a8e95e84813830072b7516cfaa7dbc1a9">llvm::ms_demangle::Char</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1a94c7a25562cb140db514fd2458aa6e38">llvm::ms_demangle::Char16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1a221653b38aed9471349e9b5449b309f9">llvm::ms_demangle::Char32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1ae73841b97be8701f8d5b8b6147f55b11">llvm::ms_demangle::Char8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1abc8996323c1df06aae8a1696d4fa486b">llvm::ms_demangle::DecltypeAuto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1ad909d38d705ce75386dd86e611a82f5b">llvm::ms_demangle::Double</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1a22ae0e2b89e5e3d477f988cc36d3272b">llvm::ms_demangle::Float</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1a1686a6c336b71b36d77354cea19a8b52">llvm::ms_demangle::Int</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1afbde23b11d7e59af7828e81144c8b487">llvm::ms_demangle::Int64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1aebbecd9031014adee502625dab080d2c">llvm::ms_demangle::Ldouble</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1a8394f0347c184cf156ac5924dccb773b">llvm::ms_demangle::Long</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1a7cbb6d0a6d025ed7e346afe53a3aa462">llvm::ms_demangle::Nullptr</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp/#a466fa40be0d81cf6c0c12d5402439b91">OUTPUT_ENUM_CLASS_VALUE</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp/#a9e879fc145b1a29b5e6e304b32bc4848">outputQualifiers</a>, <a href="#a85a637334fd8a89836c01b4306c93c47">PrimKind</a>, <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/typenode/#a52b0ebeb73b31f45a974e773d1d872ec">llvm::ms_demangle::TypeNode::Quals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1a2e154e79b37bc776a87e4c1a5c52c90e">llvm::ms_demangle::Schar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1a30bb747c98bccdd11b3f89e644c4d0ad">llvm::ms_demangle::Short</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1aa27208aef48fb8e56b6cb4f3c185e46c">llvm::ms_demangle::Uchar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1afa28cf323a8d44edbf80f68165f4f75b">llvm::ms_demangle::Uint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1ac970503874fb72afdf908cb54a4c10ee">llvm::ms_demangle::Uint64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1a0814836ee4b68ba3373811f351e786e2">llvm::ms_demangle::Ulong</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1adba9e5ee771da57168d0ec2b3aede0b7">llvm::ms_demangle::Ushort</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1a81ceb48a978444906d80119200aa358d">llvm::ms_demangle::Void</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a6e56bbb0ce2a793f5d906686bcb279c1a1aa876df01a4d617fc4b8a3591afba7c">llvm::ms_demangle::Wchar</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### PrimKind {#a85a637334fd8a89836c01b4306c93c47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PrimitiveKind llvm::ms_demangle::PrimitiveTypeNode::PrimKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<p>Referenced by <a href="#a88fdf21e5fba4ee1f1e45d5fbd5decda">outputPre</a> and <a href="#aba9333d2f5f794c688cdc1668d7a74d9">PrimitiveTypeNode</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp">MicrosoftDemangleNodes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
