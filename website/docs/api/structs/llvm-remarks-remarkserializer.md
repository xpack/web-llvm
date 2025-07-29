---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/remarkserializer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `RemarkSerializer` Struct

<p>This is the base class for a remark serializer. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::RemarkSerializer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkserializer-h">llvm/Remarks/RemarkSerializer.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializer">BitstreamRemarkSerializer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementation of the remark serializer using LLVM bitstream. <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkserializer">YAMLRemarkSerializer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Serialize the remarks to YAML. <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkserializer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78423a0a6a3684579a42b75fb2e85875">RemarkSerializer</a> (Format SerializerFormat, raw_ostream &amp;OS, SerializerMode Mode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6224b630643e01c29bdc240b01c24c5">~RemarkSerializer</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is just an interface. <a href="#ad6224b630643e01c29bdc240b01c24c5">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3932b8a65f2865895789b0240d56f87">emit</a> (const Remark &amp;Remark)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a remark to the stream. <a href="#af3932b8a65f2865895789b0240d56f87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/metaserializer">MetaSerializer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32959a5adbb33f8e60a6a1616bebe34b">metaSerializer</a> (raw_ostream &amp;OS, std::optional&lt; StringRef &gt; ExternalFilename=std::nullopt)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the corresponding metadata serializer. <a href="#a32959a5adbb33f8e60a6a1616bebe34b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0be">Format</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a062e25757dafc42e1222cb5df962d267">SerializerFormat</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The format of the serializer. <a href="#a062e25757dafc42e1222cb5df962d267">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7d21a17c33bd0fbb700107a19468973">OS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The open <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that the remark diagnostics are emitted to. <a href="#ac7d21a17c33bd0fbb700107a19468973">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae5b0a3a7cf356fc6c7602b8279061a66">SerializerMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bd374f9c556edbdf166ed6d981f5b6f">Mode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The serialization mode. <a href="#a0bd374f9c556edbdf166ed6d981f5b6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa72574e7bd50aa35940e878f31635e1a">StrTab</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The string table containing all the unique strings used in the output. <a href="#aa72574e7bd50aa35940e878f31635e1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This is the base class for a remark serializer.</p>


<p>It includes support for using a string table while emitting.</p>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkserializer-h">RemarkSerializer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RemarkSerializer() {#a78423a0a6a3684579a42b75fb2e85875}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::RemarkSerializer::RemarkSerializer (<a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0be">Format</a> SerializerFormat, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae5b0a3a7cf356fc6c7602b8279061a66">SerializerMode</a> Mode)</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkserializer-h">RemarkSerializer.h</a>.</p>


<p>References <a href="#a0bd374f9c556edbdf166ed6d981f5b6f">Mode</a>, <a href="#ac7d21a17c33bd0fbb700107a19468973">OS</a> and <a href="#a062e25757dafc42e1222cb5df962d267">SerializerFormat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializer/#a42696d420acd17e7e8ab585db9f0b5c4">llvm::remarks::BitstreamRemarkSerializer::BitstreamRemarkSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializer/#ad29d9a4e5bd223b77ecd204b5061ca00">llvm::remarks::BitstreamRemarkSerializer::BitstreamRemarkSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializer/#a6ad59c8c4d42d338abf808697597855a">llvm::remarks::BitstreamRemarkSerializer::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkserializer/#accf7ee322df6d247bc8f7bc7646f22cd">llvm::remarks::YAMLRemarkSerializer::classof</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkserializer/#a243726aeaa333962ad56ea7a8c1cb900">llvm::remarks::YAMLRemarkSerializer::YAMLRemarkSerializer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RemarkSerializer() {#ad6224b630643e01c29bdc240b01c24c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::remarks::RemarkSerializer::~RemarkSerializer ()</td>
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

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkserializer-h">RemarkSerializer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#af3932b8a65f2865895789b0240d56f87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::remarks::RemarkSerializer::emit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &amp; Remark)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a remark to the stream.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkserializer-h">RemarkSerializer.h</a>.</p>

</div>
</div>

### metaSerializer() {#a32959a5adbb33f8e60a6a1616bebe34b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::unique_ptr&lt; MetaSerializer &gt; llvm::remarks::RemarkSerializer::metaSerializer (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; ExternalFilename=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the corresponding metadata serializer.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkserializer-h">RemarkSerializer.h</a>.</p>


<p>Reference <a href="#ac7d21a17c33bd0fbb700107a19468973">OS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#adf30b8e853482f81fa3fa77818e4d2f7">llvm::AsmPrinter::emitRemarksSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Mode {#a0bd374f9c556edbdf166ed6d981f5b6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SerializerMode llvm::remarks::RemarkSerializer::Mode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The serialization mode.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkserializer-h">RemarkSerializer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializer/#a42696d420acd17e7e8ab585db9f0b5c4">llvm::remarks::BitstreamRemarkSerializer::BitstreamRemarkSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializer/#ad29d9a4e5bd223b77ecd204b5061ca00">llvm::remarks::BitstreamRemarkSerializer::BitstreamRemarkSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkserializer/#ac321611d7f64e5a3712b6d0ea9d21826">llvm::remarks::YAMLStrTabRemarkSerializer::emit</a>, <a href="#a78423a0a6a3684579a42b75fb2e85875">RemarkSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkserializer/#a243726aeaa333962ad56ea7a8c1cb900">llvm::remarks::YAMLRemarkSerializer::YAMLRemarkSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkserializer/#a9ee042fb735b4a3f85c542f1f2470f5a">llvm::remarks::YAMLRemarkSerializer::YAMLRemarkSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkserializer/#a1538564a561d291841240ba62c98ee82">llvm::remarks::YAMLStrTabRemarkSerializer::YAMLStrTabRemarkSerializer</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkserializer/#a13c03c1f5dd1b7e0c9dec4bd7210dfe6">llvm::remarks::YAMLStrTabRemarkSerializer::YAMLStrTabRemarkSerializer</a>.</p>

</div>
</div>

### OS {#ac7d21a17c33bd0fbb700107a19468973}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream&amp; llvm::remarks::RemarkSerializer::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The open <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that the remark diagnostics are emitted to.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkserializer-h">RemarkSerializer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializer/#a42696d420acd17e7e8ab585db9f0b5c4">llvm::remarks::BitstreamRemarkSerializer::BitstreamRemarkSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializer/#ad29d9a4e5bd223b77ecd204b5061ca00">llvm::remarks::BitstreamRemarkSerializer::BitstreamRemarkSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializer/#a7e6b2c791986011c32c7a0d37739bd49">llvm::remarks::BitstreamRemarkSerializer::emit</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkserializer/#ac321611d7f64e5a3712b6d0ea9d21826">llvm::remarks::YAMLStrTabRemarkSerializer::emit</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializer/#abc127a6ed6eab26d127985ec8c38ef0f">llvm::remarks::BitstreamRemarkSerializer::metaSerializer</a>, <a href="#a32959a5adbb33f8e60a6a1616bebe34b">metaSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkserializer/#a87a149d14b01d4cd2ee817b0d4512f7b">llvm::remarks::YAMLRemarkSerializer::metaSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkserializer/#a6fd63507b71878474a5782e7fa8e10f2">llvm::remarks::YAMLStrTabRemarkSerializer::metaSerializer</a>, <a href="#a78423a0a6a3684579a42b75fb2e85875">RemarkSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkserializer/#a243726aeaa333962ad56ea7a8c1cb900">llvm::remarks::YAMLRemarkSerializer::YAMLRemarkSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkserializer/#a9ee042fb735b4a3f85c542f1f2470f5a">llvm::remarks::YAMLRemarkSerializer::YAMLRemarkSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkserializer/#a1538564a561d291841240ba62c98ee82">llvm::remarks::YAMLStrTabRemarkSerializer::YAMLStrTabRemarkSerializer</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkserializer/#a13c03c1f5dd1b7e0c9dec4bd7210dfe6">llvm::remarks::YAMLStrTabRemarkSerializer::YAMLStrTabRemarkSerializer</a>.</p>

</div>
</div>

### SerializerFormat {#a062e25757dafc42e1222cb5df962d267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Format llvm::remarks::RemarkSerializer::SerializerFormat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The format of the serializer.</p>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkserializer-h">RemarkSerializer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializer/#a6ad59c8c4d42d338abf808697597855a">llvm::remarks::BitstreamRemarkSerializer::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkserializer/#accf7ee322df6d247bc8f7bc7646f22cd">llvm::remarks::YAMLRemarkSerializer::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkserializer/#a0c4a0345364e9d846274bf2e786193d5">llvm::remarks::YAMLStrTabRemarkSerializer::classof</a>, <a href="#a78423a0a6a3684579a42b75fb2e85875">RemarkSerializer</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkserializer/#a243726aeaa333962ad56ea7a8c1cb900">llvm::remarks::YAMLRemarkSerializer::YAMLRemarkSerializer</a>.</p>

</div>
</div>

### StrTab {#aa72574e7bd50aa35940e878f31635e1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;StringTable&gt; llvm::remarks::RemarkSerializer::StrTab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The string table containing all the unique strings used in the output.</p>


<p>The table can be serialized to be consumed after the compilation.</p>


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkserializer-h">RemarkSerializer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializer/#a42696d420acd17e7e8ab585db9f0b5c4">llvm::remarks::BitstreamRemarkSerializer::BitstreamRemarkSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializer/#ad29d9a4e5bd223b77ecd204b5061ca00">llvm::remarks::BitstreamRemarkSerializer::BitstreamRemarkSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializer/#a7e6b2c791986011c32c7a0d37739bd49">llvm::remarks::BitstreamRemarkSerializer::emit</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializer/#abc127a6ed6eab26d127985ec8c38ef0f">llvm::remarks::BitstreamRemarkSerializer::metaSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkserializer/#a6fd63507b71878474a5782e7fa8e10f2">llvm::remarks::YAMLStrTabRemarkSerializer::metaSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkserializer/#a243726aeaa333962ad56ea7a8c1cb900">llvm::remarks::YAMLRemarkSerializer::YAMLRemarkSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkserializer/#a1538564a561d291841240ba62c98ee82">llvm::remarks::YAMLStrTabRemarkSerializer::YAMLStrTabRemarkSerializer</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkserializer/#a13c03c1f5dd1b7e0c9dec4bd7210dfe6">llvm::remarks::YAMLStrTabRemarkSerializer::YAMLStrTabRemarkSerializer</a>.</p>

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
