---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/yamlstrtabremarkserializer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `YAMLStrTabRemarkSerializer` Struct

<p>Serialize the remarks to YAML using a string table. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::YAMLStrTabRemarkSerializer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">llvm/Remarks/YAMLRemarkSerializer.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1538564a561d291841240ba62c98ee82">YAMLStrTabRemarkSerializer</a> (raw_ostream &amp;OS, SerializerMode Mode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13c03c1f5dd1b7e0c9dec4bd7210dfe6">YAMLStrTabRemarkSerializer</a> (raw_ostream &amp;OS, SerializerMode Mode, StringTable StrTab)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac321611d7f64e5a3712b6d0ea9d21826">emit</a> (const Remark &amp;Remark) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Override to emit the metadata if necessary. <a href="#ac321611d7f64e5a3712b6d0ea9d21826">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/metaserializer">MetaSerializer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fd63507b71878474a5782e7fa8e10f2">metaSerializer</a> (raw_ostream &amp;OS, std::optional&lt; StringRef &gt; ExternalFilename=std::nullopt) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the corresponding metadata serializer. <a href="#a6fd63507b71878474a5782e7fa8e10f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae42485b75dd5ba8645c328b5612afc64">DidEmitMeta</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wether we already emitted the metadata in standalone mode. <a href="#ae42485b75dd5ba8645c328b5612afc64">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c4a0345364e9d846274bf2e786193d5">classof</a> (const RemarkSerializer *S)</td>
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

<p>Serialize the remarks to YAML using a string table.</p>


<p>An remark entry looks like the regular YAML remark but instead of string entries it's using numbers that map to an index in the string table.</p>


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### YAMLStrTabRemarkSerializer() {#a1538564a561d291841240ba62c98ee82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::YAMLStrTabRemarkSerializer::YAMLStrTabRemarkSerializer (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae5b0a3a7cf356fc6c7602b8279061a66">SerializerMode</a> Mode)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#a0bd374f9c556edbdf166ed6d981f5b6f">llvm::remarks::RemarkSerializer::Mode</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#ac7d21a17c33bd0fbb700107a19468973">llvm::remarks::RemarkSerializer::OS</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#aa72574e7bd50aa35940e878f31635e1a">llvm::remarks::RemarkSerializer::StrTab</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkserializer/#a9ee042fb735b4a3f85c542f1f2470f5a">llvm::remarks::YAMLRemarkSerializer::YAMLRemarkSerializer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea8bc4f729719767dd102c6ac3e55adf1d">llvm::remarks::YAMLStrTab</a>.</p>

</div>
</div>

### YAMLStrTabRemarkSerializer() {#a13c03c1f5dd1b7e0c9dec4bd7210dfe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::YAMLStrTabRemarkSerializer::YAMLStrTabRemarkSerializer (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae5b0a3a7cf356fc6c7602b8279061a66">SerializerMode</a> Mode, <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a> StrTab)</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#a0bd374f9c556edbdf166ed6d981f5b6f">llvm::remarks::RemarkSerializer::Mode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#ac7d21a17c33bd0fbb700107a19468973">llvm::remarks::RemarkSerializer::OS</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#aa72574e7bd50aa35940e878f31635e1a">llvm::remarks::RemarkSerializer::StrTab</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkserializer/#a9ee042fb735b4a3f85c542f1f2470f5a">llvm::remarks::YAMLRemarkSerializer::YAMLRemarkSerializer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea8bc4f729719767dd102c6ac3e55adf1d">llvm::remarks::YAMLStrTab</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#ac321611d7f64e5a3712b6d0ea9d21826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void YAMLStrTabRemarkSerializer::emit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &amp; Remark)</td>
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

<p>Override to emit the metadata if necessary.</p>

<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>, definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp">YAMLRemarkSerializer.cpp</a>.</p>


<p>References <a href="#ae42485b75dd5ba8645c328b5612afc64">DidEmitMeta</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/metaserializer/#a0127be2f36d1c1fa93cc08df861a8d56">llvm::remarks::MetaSerializer::emit</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkserializer/#acebdec0acf70451585df4afff45e9fd5">llvm::remarks::YAMLRemarkSerializer::emit</a>, <a href="#a6fd63507b71878474a5782e7fa8e10f2">metaSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#a0bd374f9c556edbdf166ed6d981f5b6f">llvm::remarks::RemarkSerializer::Mode</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#ac7d21a17c33bd0fbb700107a19468973">llvm::remarks::RemarkSerializer::OS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae5b0a3a7cf356fc6c7602b8279061a66a5c80f101108a356211fcb26b3f83eabb">llvm::remarks::Standalone</a>.</p>

</div>
</div>

### metaSerializer() {#a6fd63507b71878474a5782e7fa8e10f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MetaSerializer &gt; YAMLStrTabRemarkSerializer::metaSerializer (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; ExternalFilename=std::nullopt)</td>
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

<p>Return the corresponding metadata serializer.</p>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp">YAMLRemarkSerializer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#ac7d21a17c33bd0fbb700107a19468973">llvm::remarks::RemarkSerializer::OS</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#aa72574e7bd50aa35940e878f31635e1a">llvm::remarks::RemarkSerializer::StrTab</a>.</p>


<p>Referenced by <a href="#ac321611d7f64e5a3712b6d0ea9d21826">emit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DidEmitMeta {#ae42485b75dd5ba8645c328b5612afc64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::remarks::YAMLStrTabRemarkSerializer::DidEmitMeta = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Wether we already emitted the metadata in standalone mode.</p>


<p>This should be set to true after the first invocation of <span class="doxyComputerOutput">emit</span>.</p>


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#ac321611d7f64e5a3712b6d0ea9d21826">emit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a0c4a0345364e9d846274bf2e786193d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::remarks::YAMLStrTabRemarkSerializer::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer">RemarkSerializer</a> * S)</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#a062e25757dafc42e1222cb5df962d267">llvm::remarks::RemarkSerializer::SerializerFormat</a> and <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea8bc4f729719767dd102c6ac3e55adf1d">llvm::remarks::YAMLStrTab</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp">YAMLRemarkSerializer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
