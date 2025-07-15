---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/ms-demangle/encodedstringliteralnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `EncodedStringLiteralNode` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::ms_demangle::EncodedStringLiteralNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">llvm/Demangle/MicrosoftDemangleNodes.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/symbolnode">SymbolNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfeafdc5b5f635def688a5273720a171">EncodedStringLiteralNode</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27b186e4b5ba550278321bba2ebf0310">output</a> (OutputBuffer &amp;OB, OutputFlags Flags) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string_view</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69b2c6c1d2c54e81f9c5a23381e4567e">DecodedString</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4703865841587bf23bcc3a315f5417a0">IsTruncated</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9229cb95642bf8b1d9ad122defe43d64">CharKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14a32edc8cac7f3c36a70c40548b15da">Char</a> = CharKind::Char</td>
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


<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### EncodedStringLiteralNode() {#adfeafdc5b5f635def688a5273720a171}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ms_demangle::EncodedStringLiteralNode::EncodedStringLiteralNode ()</td>
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



<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a234f091f9559c82176ae3e89447add46ac8c483c3e678aa357ea68a11997cb036">llvm::ms_demangle::EncodedStringLiteral</a> and <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/symbolnode/#a9811a0bfaa307fd7b2cbd3b166d415bd">llvm::ms_demangle::SymbolNode::SymbolNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### output() {#a27b186e4b5ba550278321bba2ebf0310}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EncodedStringLiteralNode::output (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9e06032afffbcfd197a80acc92afce93">OutputFlags</a> Flags)</td>
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



<p>Declaration at line 604 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp">MicrosoftDemangleNodes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9229cb95642bf8b1d9ad122defe43d64a8e95e84813830072b7516cfaa7dbc1a9">llvm::ms_demangle::Char</a>, <a href="#a14a32edc8cac7f3c36a70c40548b15da">Char</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9229cb95642bf8b1d9ad122defe43d64a94c7a25562cb140db514fd2458aa6e38">llvm::ms_demangle::Char16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9229cb95642bf8b1d9ad122defe43d64a221653b38aed9471349e9b5449b309f9">llvm::ms_demangle::Char32</a>, <a href="#a69b2c6c1d2c54e81f9c5a23381e4567e">DecodedString</a>, <a href="#a4703865841587bf23bcc3a315f5417a0">IsTruncated</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9229cb95642bf8b1d9ad122defe43d64a1aa876df01a4d617fc4b8a3591afba7c">llvm::ms_demangle::Wchar</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Char {#a14a32edc8cac7f3c36a70c40548b15da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CharKind llvm::ms_demangle::EncodedStringLiteralNode::Char = CharKind::Char</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<p>Referenced by <a href="#a27b186e4b5ba550278321bba2ebf0310">output</a>.</p>

</div>
</div>

### DecodedString {#a69b2c6c1d2c54e81f9c5a23381e4567e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string_view llvm::ms_demangle::EncodedStringLiteralNode::DecodedString</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<p>Referenced by <a href="#a27b186e4b5ba550278321bba2ebf0310">output</a>.</p>

</div>
</div>

### IsTruncated {#a4703865841587bf23bcc3a315f5417a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ms_demangle::EncodedStringLiteralNode::IsTruncated = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<p>Referenced by <a href="#a27b186e4b5ba550278321bba2ebf0310">output</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
