---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/metaserializer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MetaSerializer` Struct Reference

<p>This is the base class for a remark metadata serializer. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::MetaSerializer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkserializer-h">llvm/Remarks/RemarkSerializer.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaserializer">BitstreamMetaSerializer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Serializer of metadata for bitstream remarks. <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaserializer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/yamlmetaserializer">YAMLMetaSerializer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cb3cac1778548d416c314cef4b40fb7">MetaSerializer</a> (raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9059149b1ec4346a759310b28530d9bd">~MetaSerializer</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is just an interface. <a href="#a9059149b1ec4346a759310b28530d9bd">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0127be2f36d1c1fa93cc08df861a8d56">emit</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c346057431cc76d6a8d6e080c1e79f9">OS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The open <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that the metadata is emitted to. <a href="#a2c346057431cc76d6a8d6e080c1e79f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This is the base class for a remark metadata serializer.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkserializer-h">RemarkSerializer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MetaSerializer() {#a1cb3cac1778548d416c314cef4b40fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::MetaSerializer::MetaSerializer (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkserializer-h">RemarkSerializer.h</a>.</p>


<p>Reference <a href="#a2c346057431cc76d6a8d6e080c1e79f9">OS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaserializer/#a54dc14102bdaa9db7b4d8457a3b00f69">llvm::remarks::BitstreamMetaSerializer::BitstreamMetaSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaserializer/#ad019b75bb524aeedbedcae44f58a1151">llvm::remarks::BitstreamMetaSerializer::BitstreamMetaSerializer</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlmetaserializer/#ab0718fe9f550651ad24a84f4fff29112">llvm::remarks::YAMLMetaSerializer::YAMLMetaSerializer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MetaSerializer() {#a9059149b1ec4346a759310b28530d9bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::remarks::MetaSerializer::~MetaSerializer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is just an interface.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkserializer-h">RemarkSerializer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#a0127be2f36d1c1fa93cc08df861a8d56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::remarks::MetaSerializer::emit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkserializer-h">RemarkSerializer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializer/#a7e6b2c791986011c32c7a0d37739bd49">llvm::remarks::BitstreamRemarkSerializer::emit</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkserializer/#ac321611d7f64e5a3712b6d0ea9d21826">llvm::remarks::YAMLStrTabRemarkSerializer::emit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### OS {#a2c346057431cc76d6a8d6e080c1e79f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream&amp; llvm::remarks::MetaSerializer::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The open <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that the metadata is emitted to.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkserializer-h">RemarkSerializer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaserializer/#a54dc14102bdaa9db7b4d8457a3b00f69">llvm::remarks::BitstreamMetaSerializer::BitstreamMetaSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaserializer/#ad019b75bb524aeedbedcae44f58a1151">llvm::remarks::BitstreamMetaSerializer::BitstreamMetaSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaserializer/#ab95abf1cab50acbd270759579390714f">llvm::remarks::BitstreamMetaSerializer::emit</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlmetaserializer/#af4f9732aa7dd0d4a322d2ff1006b97ef">llvm::remarks::YAMLMetaSerializer::emit</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabmetaserializer/#a4f79875bf4c89a2d66e07aeac18d6ce8">llvm::remarks::YAMLStrTabMetaSerializer::emit</a>, <a href="#a1cb3cac1778548d416c314cef4b40fb7">MetaSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlmetaserializer/#ab0718fe9f550651ad24a84f4fff29112">llvm::remarks::YAMLMetaSerializer::YAMLMetaSerializer</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabmetaserializer/#a035a57f96826bd690912f4c015cf1edd">llvm::remarks::YAMLStrTabMetaSerializer::YAMLStrTabMetaSerializer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkserializer-h">RemarkSerializer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
