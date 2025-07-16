---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/yamlstrtabmetaserializer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `YAMLStrTabMetaSerializer` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::YAMLStrTabMetaSerializer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">llvm/Remarks/YAMLRemarkSerializer.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a035a57f96826bd690912f4c015cf1edd">YAMLStrTabMetaSerializer</a> (raw_ostream &amp;OS, std::optional&lt; StringRef &gt; ExternalFilename, const StringTable &amp;StrTab)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f79875bf4c89a2d66e07aeac18d6ce8">emit</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a631588b293ed592ea7b03e758dc2c620">StrTab</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The string table is part of the metadata. <a href="#a631588b293ed592ea7b03e758dc2c620">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### YAMLStrTabMetaSerializer() {#a035a57f96826bd690912f4c015cf1edd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::YAMLStrTabMetaSerializer::YAMLStrTabMetaSerializer (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; ExternalFilename, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a> &amp; StrTab)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlmetaserializer/#a6dc3112c50bfad746a0a56032d8dee67">llvm::remarks::YAMLMetaSerializer::ExternalFilename</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/metaserializer/#a2c346057431cc76d6a8d6e080c1e79f9">llvm::remarks::MetaSerializer::OS</a>, <a href="#a631588b293ed592ea7b03e758dc2c620">StrTab</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlmetaserializer/#ab0718fe9f550651ad24a84f4fff29112">llvm::remarks::YAMLMetaSerializer::YAMLMetaSerializer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#a4f79875bf4c89a2d66e07aeac18d6ce8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void YAMLStrTabMetaSerializer::emit ()</td>
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



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>, definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp">YAMLRemarkSerializer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#a232c76d4c06ded6c02597dfae877aca3">emitExternalFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#a6c011cb80a79745aa876f8e3efb35975">emitMagic</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#a381769de0e2dcfdc39d00d50ec961c66">emitStrTab</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#accf8f848dfab29077924750f922e320d">emitVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlmetaserializer/#a6dc3112c50bfad746a0a56032d8dee67">llvm::remarks::YAMLMetaSerializer::ExternalFilename</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/metaserializer/#a2c346057431cc76d6a8d6e080c1e79f9">llvm::remarks::MetaSerializer::OS</a> and <a href="#a631588b293ed592ea7b03e758dc2c620">StrTab</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### StrTab {#a631588b293ed592ea7b03e758dc2c620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StringTable&amp; llvm::remarks::YAMLStrTabMetaSerializer::StrTab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The string table is part of the metadata.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#a4f79875bf4c89a2d66e07aeac18d6ce8">emit</a> and <a href="#a035a57f96826bd690912f4c015cf1edd">YAMLStrTabMetaSerializer</a>.</p>

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
