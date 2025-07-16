---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/bitstreammetaserializer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BitstreamMetaSerializer` Struct Reference

<p>Serializer of metadata for bitstream remarks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::BitstreamMetaSerializer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">llvm/Remarks/BitstreamRemarkSerializer.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/metaserializer">MetaSerializer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the base class for a remark metadata serializer. <a href="/web-llvm/docs/api/structs/llvm/remarks/metaserializer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54dc14102bdaa9db7b4d8457a3b00f69">BitstreamMetaSerializer</a> (raw_ostream &amp;OS, BitstreamRemarkContainerType ContainerType, std::optional&lt; const StringTable * &gt; StrTab=std::nullopt, std::optional&lt; StringRef &gt; ExternalFilename=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new meta serializer based on <span class="doxyComputerOutput">ContainerType</span>. <a href="#a54dc14102bdaa9db7b4d8457a3b00f69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad019b75bb524aeedbedcae44f58a1151">BitstreamMetaSerializer</a> (raw_ostream &amp;OS, BitstreamRemarkSerializerHelper &amp;Helper, std::optional&lt; const StringTable * &gt; StrTab=std::nullopt, std::optional&lt; StringRef &gt; ExternalFilename=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new meta serializer based on a previously built <span class="doxyComputerOutput">Helper</span>. <a href="#ad019b75bb524aeedbedcae44f58a1151">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab95abf1cab50acbd270759579390714f">emit</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper">BitstreamRemarkSerializerHelper</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad14c90e3b9b65e18878f4ccb283d2cc">TmpHelper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class can be used with [1] a pre-constructed <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper">BitstreamRemarkSerializerHelper</a>, or with [2] one that is owned by the meta serializer. <a href="#aad14c90e3b9b65e18878f4ccb283d2cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper">BitstreamRemarkSerializerHelper</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addcc80ca6ffda434cc24a4798d6b0d23">Helper</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The actual helper, that can point to <span class="doxyComputerOutput">TmpHelper</span> or to an external helper object. <a href="#addcc80ca6ffda434cc24a4798d6b0d23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1ea72baa2d557f772b5c98d8ac0dcb0">StrTab</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a351b29287eec89f90e19023020e1d776">ExternalFilename</a></td>
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

<p>Serializer of metadata for bitstream remarks.</p>

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BitstreamMetaSerializer() {#a54dc14102bdaa9db7b4d8457a3b00f69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::BitstreamMetaSerializer::BitstreamMetaSerializer (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1e">BitstreamRemarkContainerType</a> ContainerType, std::optional&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a> * &gt; StrTab=std::nullopt, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; ExternalFilename=std::nullopt)</td>
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

<p>Create a new meta serializer based on <span class="doxyComputerOutput">ContainerType</span>.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>References <a href="#a351b29287eec89f90e19023020e1d776">ExternalFilename</a>, <a href="#addcc80ca6ffda434cc24a4798d6b0d23">Helper</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/metaserializer/#a1cb3cac1778548d416c314cef4b40fb7">llvm::remarks::MetaSerializer::MetaSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/metaserializer/#a2c346057431cc76d6a8d6e080c1e79f9">llvm::remarks::MetaSerializer::OS</a>, <a href="#ad1ea72baa2d557f772b5c98d8ac0dcb0">StrTab</a> and <a href="#aad14c90e3b9b65e18878f4ccb283d2cc">TmpHelper</a>.</p>

</div>
</div>

### BitstreamMetaSerializer() {#ad019b75bb524aeedbedcae44f58a1151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::BitstreamMetaSerializer::BitstreamMetaSerializer (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper">BitstreamRemarkSerializerHelper</a> &amp; Helper, std::optional&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a> * &gt; StrTab=std::nullopt, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; ExternalFilename=std::nullopt)</td>
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

<p>Create a new meta serializer based on a previously built <span class="doxyComputerOutput">Helper</span>.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>References <a href="#a351b29287eec89f90e19023020e1d776">ExternalFilename</a>, <a href="#addcc80ca6ffda434cc24a4798d6b0d23">Helper</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/metaserializer/#a1cb3cac1778548d416c314cef4b40fb7">llvm::remarks::MetaSerializer::MetaSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/metaserializer/#a2c346057431cc76d6a8d6e080c1e79f9">llvm::remarks::MetaSerializer::OS</a>, <a href="#ad1ea72baa2d557f772b5c98d8ac0dcb0">StrTab</a> and <a href="#aad14c90e3b9b65e18878f4ccb283d2cc">TmpHelper</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#ab95abf1cab50acbd270759579390714f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitstreamMetaSerializer::emit ()</td>
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



<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>, definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a3f42c1ba51663eaef716aaed6589efce">llvm::remarks::CurrentContainerVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ab38ef7cc779e59ba675a15f886a2eaf7">llvm::remarks::CurrentRemarkVersion</a>, <a href="#a351b29287eec89f90e19023020e1d776">ExternalFilename</a>, <a href="#addcc80ca6ffda434cc24a4798d6b0d23">Helper</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/metaserializer/#a2c346057431cc76d6a8d6e080c1e79f9">llvm::remarks::MetaSerializer::OS</a> and <a href="#ad1ea72baa2d557f772b5c98d8ac0dcb0">StrTab</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ExternalFilename {#a351b29287eec89f90e19023020e1d776}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;StringRef&gt; llvm::remarks::BitstreamMetaSerializer::ExternalFilename</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#a54dc14102bdaa9db7b4d8457a3b00f69">BitstreamMetaSerializer</a>, <a href="#ad019b75bb524aeedbedcae44f58a1151">BitstreamMetaSerializer</a> and <a href="#ab95abf1cab50acbd270759579390714f">emit</a>.</p>

</div>
</div>

### Helper {#addcc80ca6ffda434cc24a4798d6b0d23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamRemarkSerializerHelper* llvm::remarks::BitstreamMetaSerializer::Helper = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The actual helper, that can point to <span class="doxyComputerOutput">TmpHelper</span> or to an external helper object.</p>

<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#a54dc14102bdaa9db7b4d8457a3b00f69">BitstreamMetaSerializer</a>, <a href="#ad019b75bb524aeedbedcae44f58a1151">BitstreamMetaSerializer</a> and <a href="#ab95abf1cab50acbd270759579390714f">emit</a>.</p>

</div>
</div>

### StrTab {#ad1ea72baa2d557f772b5c98d8ac0dcb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;const StringTable *&gt; llvm::remarks::BitstreamMetaSerializer::StrTab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#a54dc14102bdaa9db7b4d8457a3b00f69">BitstreamMetaSerializer</a>, <a href="#ad019b75bb524aeedbedcae44f58a1151">BitstreamMetaSerializer</a> and <a href="#ab95abf1cab50acbd270759579390714f">emit</a>.</p>

</div>
</div>

### TmpHelper {#aad14c90e3b9b65e18878f4ccb283d2cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;BitstreamRemarkSerializerHelper&gt; llvm::remarks::BitstreamMetaSerializer::TmpHelper</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This class can be used with [1] a pre-constructed <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper">BitstreamRemarkSerializerHelper</a>, or with [2] one that is owned by the meta serializer.</p>


<p>In case of [1], we need to be able to store a reference to the object, while in case of [2] we need to store the whole object.</p>


<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#a54dc14102bdaa9db7b4d8457a3b00f69">BitstreamMetaSerializer</a> and <a href="#ad019b75bb524aeedbedcae44f58a1151">BitstreamMetaSerializer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
