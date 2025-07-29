---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mcelfstreamer/attributeitem
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `AttributeItem` Struct

<p><a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> object attributes section emission support. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MCELFStreamer::AttributeItem { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfstreamer-h">llvm/MC/MCELFStreamer.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Types { <a href="#a90bf14bde35d9a80a6a3191d2a6013aa">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34f36ab6768686360817688ce9f65df4">AttributeItem</a> (Types Ty, unsigned Tg, unsigned IV, std::string SV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="#a90bf14bde35d9a80a6a3191d2a6013aa">llvm::MCELFStreamer::AttributeItem::Types</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74f3c7deff4fdf903439dd40f4bb31d7">Type</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adba1ead9da2611bb13a8dabb5cf0416e">Tag</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25188942b501c0041f79016d45670d44">IntValue</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a480c85132bc35981d9ab1a6acb2cb305">StringValue</a></td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> object attributes section emission support.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfstreamer-h">MCELFStreamer.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Types {#a90bf14bde35d9a80a6a3191d2a6013aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCELFStreamer::AttributeItem::Types </td>
</tr>
</table>
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
<td class="doxyEnumItemName">HiddenAttribute<a id="a90bf14bde35d9a80a6a3191d2a6013aaad319842fd315e8fa76487a91f91e9221"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumericAttribute<a id="a90bf14bde35d9a80a6a3191d2a6013aaa2882f0f03bbc46d88d31fccbdcf85fe0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TextAttribute<a id="a90bf14bde35d9a80a6a3191d2a6013aaad68c03de7ce9a3e8d9d6ea2721bb22a9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumericAndTextAttributes<a id="a90bf14bde35d9a80a6a3191d2a6013aaa54a5f5f3f477f0f5d671c6c09ab1350b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfstreamer-h">MCELFStreamer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AttributeItem() {#a34f36ab6768686360817688ce9f65df4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCELFStreamer::AttributeItem::AttributeItem (<a href="#a90bf14bde35d9a80a6a3191d2a6013aa">Types</a> Ty, unsigned Tg, unsigned IV, std::string SV)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfstreamer-h">MCELFStreamer.h</a>.</p>


<p>References <a href="#a25188942b501c0041f79016d45670d44">IntValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="#a480c85132bc35981d9ab1a6acb2cb305">StringValue</a>, <a href="#adba1ead9da2611bb13a8dabb5cf0416e">Tag</a> and <a href="#a74f3c7deff4fdf903439dd40f4bb31d7">Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IntValue {#a25188942b501c0041f79016d45670d44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCELFStreamer::AttributeItem::IntValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfstreamer-h">MCELFStreamer.h</a>.</p>


<p>Referenced by <a href="#a34f36ab6768686360817688ce9f65df4">AttributeItem</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a9781e70abbf0d410b270711d57097666">llvm::AArch64TargetStreamer::emitAttribute</a>.</p>

</div>
</div>

### StringValue {#a480c85132bc35981d9ab1a6acb2cb305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::MCELFStreamer::AttributeItem::StringValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfstreamer-h">MCELFStreamer.h</a>.</p>


<p>Referenced by <a href="#a34f36ab6768686360817688ce9f65df4">AttributeItem</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a9781e70abbf0d410b270711d57097666">llvm::AArch64TargetStreamer::emitAttribute</a>.</p>

</div>
</div>

### Tag {#adba1ead9da2611bb13a8dabb5cf0416e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCELFStreamer::AttributeItem::Tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfstreamer-h">MCELFStreamer.h</a>.</p>


<p>Referenced by <a href="#a34f36ab6768686360817688ce9f65df4">AttributeItem</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a9781e70abbf0d410b270711d57097666">llvm::AArch64TargetStreamer::emitAttribute</a>.</p>

</div>
</div>

### Type {#a74f3c7deff4fdf903439dd40f4bb31d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCELFStreamer::AttributeItem::Types llvm::MCELFStreamer::AttributeItem::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfstreamer-h">MCELFStreamer.h</a>.</p>


<p>Referenced by <a href="#a34f36ab6768686360817688ce9f65df4">AttributeItem</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfstreamer-h">MCELFStreamer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
