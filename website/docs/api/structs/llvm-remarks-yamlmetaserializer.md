---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/yamlmetaserializer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `YAMLMetaSerializer` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::YAMLMetaSerializer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">llvm/Remarks/YAMLRemarkSerializer.h</a>"
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

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabmetaserializer">YAMLStrTabMetaSerializer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0718fe9f550651ad24a84f4fff29112">YAMLMetaSerializer</a> (raw_ostream &amp;OS, std::optional&lt; StringRef &gt; ExternalFilename)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4f9732aa7dd0d4a322d2ff1006b97ef">emit</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dc3112c50bfad746a0a56032d8dee67">ExternalFilename</a></td>
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


<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### YAMLMetaSerializer() {#ab0718fe9f550651ad24a84f4fff29112}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::YAMLMetaSerializer::YAMLMetaSerializer (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; ExternalFilename)</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>.</p>


<p>References <a href="#a6dc3112c50bfad746a0a56032d8dee67">ExternalFilename</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/metaserializer/#a1cb3cac1778548d416c314cef4b40fb7">llvm::remarks::MetaSerializer::MetaSerializer</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/metaserializer/#a2c346057431cc76d6a8d6e080c1e79f9">llvm::remarks::MetaSerializer::OS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabmetaserializer/#a035a57f96826bd690912f4c015cf1edd">llvm::remarks::YAMLStrTabMetaSerializer::YAMLStrTabMetaSerializer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#af4f9732aa7dd0d4a322d2ff1006b97ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void YAMLMetaSerializer::emit ()</td>
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



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>, definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp">YAMLRemarkSerializer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#a232c76d4c06ded6c02597dfae877aca3">emitExternalFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#a6c011cb80a79745aa876f8e3efb35975">emitMagic</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#a381769de0e2dcfdc39d00d50ec961c66">emitStrTab</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#accf8f848dfab29077924750f922e320d">emitVersion</a>, <a href="#a6dc3112c50bfad746a0a56032d8dee67">ExternalFilename</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/metaserializer/#a2c346057431cc76d6a8d6e080c1e79f9">llvm::remarks::MetaSerializer::OS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ExternalFilename {#a6dc3112c50bfad746a0a56032d8dee67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;StringRef&gt; llvm::remarks::YAMLMetaSerializer::ExternalFilename</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#af4f9732aa7dd0d4a322d2ff1006b97ef">emit</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabmetaserializer/#a4f79875bf4c89a2d66e07aeac18d6ce8">llvm::remarks::YAMLStrTabMetaSerializer::emit</a>, <a href="#ab0718fe9f550651ad24a84f4fff29112">YAMLMetaSerializer</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabmetaserializer/#a035a57f96826bd690912f4c015cf1edd">llvm::remarks::YAMLStrTabMetaSerializer::YAMLStrTabMetaSerializer</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
