---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/yamlremarkserializer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `YAMLRemarkSerializer` Struct Reference

<p>Serialize the remarks to YAML. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::YAMLRemarkSerializer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">llvm/Remarks/YAMLRemarkSerializer.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer">RemarkSerializer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the base class for a remark serializer. <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkserializer">YAMLStrTabRemarkSerializer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Serialize the remarks to YAML using a string table. <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkserializer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ee042fb735b4a3f85c542f1f2470f5a">YAMLRemarkSerializer</a> (raw_ostream &amp;OS, SerializerMode Mode, std::optional&lt; StringTable &gt; StrTab=std::nullopt)</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a243726aeaa333962ad56ea7a8c1cb900">YAMLRemarkSerializer</a> (Format SerializerFormat, raw_ostream &amp;OS, SerializerMode Mode, std::optional&lt; StringTable &gt; StrTab=std::nullopt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acebdec0acf70451585df4afff45e9fd5">emit</a> (const Remark &amp;Remark) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a remark to the stream. <a href="#acebdec0acf70451585df4afff45e9fd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/metaserializer">MetaSerializer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87a149d14b01d4cd2ee817b0d4512f7b">metaSerializer</a> (raw_ostream &amp;OS, std::optional&lt; StringRef &gt; ExternalFilename=std::nullopt) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the corresponding metadata serializer. <a href="#a87a149d14b01d4cd2ee817b0d4512f7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/output">yaml::Output</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3b62e6d4b9873faebab0f6292bc6ad7">YAMLOutput</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The YAML streamer. <a href="#ad3b62e6d4b9873faebab0f6292bc6ad7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accf7ee322df6d247bc8f7bc7646f22cd">classof</a> (const RemarkSerializer *S)</td>
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

<p>Serialize the remarks to YAML.</p>


<p>One remark entry looks like this: — !&lt;TYPE&gt; <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a>: &lt;PASSNAME&gt; Name: &lt;REMARKNAME&gt; <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>: { File: &lt;SOURCEFILENAME&gt;, Line: &lt;SOURCELINE&gt;, Column: &lt;SOURCECOLUMN&gt; } <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>: &lt;FUNCTIONNAME&gt; Args:</p>


<ul class="doxyList ">
<li>&lt;KEY&gt;:</li>
</ul>

<p><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>: { File: &lt;FILE&gt;, Line: &lt;LINE&gt;, Column: &lt;COL&gt; } ...</p>


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### YAMLRemarkSerializer() {#a9ee042fb735b4a3f85c542f1f2470f5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">YAMLRemarkSerializer::YAMLRemarkSerializer (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae5b0a3a7cf356fc6c7602b8279061a66">SerializerMode</a> Mode, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a> &gt; StrTab=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp">YAMLRemarkSerializer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#a0bd374f9c556edbdf166ed6d981f5b6f">llvm::remarks::RemarkSerializer::Mode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#ac7d21a17c33bd0fbb700107a19468973">llvm::remarks::RemarkSerializer::OS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea9463f87bbed1fcdacfb8d40e185ca2bc">llvm::remarks::YAML</a> and <a href="#a9ee042fb735b4a3f85c542f1f2470f5a">YAMLRemarkSerializer</a>.</p>


<p>Referenced by <a href="#a9ee042fb735b4a3f85c542f1f2470f5a">YAMLRemarkSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkserializer/#a1538564a561d291841240ba62c98ee82">llvm::remarks::YAMLStrTabRemarkSerializer::YAMLStrTabRemarkSerializer</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkserializer/#a13c03c1f5dd1b7e0c9dec4bd7210dfe6">llvm::remarks::YAMLStrTabRemarkSerializer::YAMLStrTabRemarkSerializer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### YAMLRemarkSerializer() {#a243726aeaa333962ad56ea7a8c1cb900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">YAMLRemarkSerializer::YAMLRemarkSerializer (<a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0be">Format</a> SerializerFormat, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae5b0a3a7cf356fc6c7602b8279061a66">SerializerMode</a> Mode, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a> &gt; StrTab=std::nullopt)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp">YAMLRemarkSerializer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#a0bd374f9c556edbdf166ed6d981f5b6f">llvm::remarks::RemarkSerializer::Mode</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#ac7d21a17c33bd0fbb700107a19468973">llvm::remarks::RemarkSerializer::OS</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#a78423a0a6a3684579a42b75fb2e85875">llvm::remarks::RemarkSerializer::RemarkSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#a062e25757dafc42e1222cb5df962d267">llvm::remarks::RemarkSerializer::SerializerFormat</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#aa72574e7bd50aa35940e878f31635e1a">llvm::remarks::RemarkSerializer::StrTab</a> and <a href="#ad3b62e6d4b9873faebab0f6292bc6ad7">YAMLOutput</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#acebdec0acf70451585df4afff45e9fd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void YAMLRemarkSerializer::emit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &amp; Remark)</td>
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

<p>Emit a remark to the stream.</p>

<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>, definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp">YAMLRemarkSerializer.cpp</a>.</p>


<p>Reference <a href="#ad3b62e6d4b9873faebab0f6292bc6ad7">YAMLOutput</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkserializer/#ac321611d7f64e5a3712b6d0ea9d21826">llvm::remarks::YAMLStrTabRemarkSerializer::emit</a>.</p>

</div>
</div>

### metaSerializer() {#a87a149d14b01d4cd2ee817b0d4512f7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MetaSerializer &gt; YAMLRemarkSerializer::metaSerializer (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; ExternalFilename=std::nullopt)</td>
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

<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp">YAMLRemarkSerializer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#ac7d21a17c33bd0fbb700107a19468973">llvm::remarks::RemarkSerializer::OS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### YAMLOutput {#ad3b62e6d4b9873faebab0f6292bc6ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::Output llvm::remarks::YAMLRemarkSerializer::YAMLOutput</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The YAML streamer.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#acebdec0acf70451585df4afff45e9fd5">emit</a> and <a href="#a243726aeaa333962ad56ea7a8c1cb900">YAMLRemarkSerializer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#accf7ee322df6d247bc8f7bc7646f22cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::remarks::YAMLRemarkSerializer::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer">RemarkSerializer</a> * S)</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/yamlremarkserializer-h">YAMLRemarkSerializer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#a78423a0a6a3684579a42b75fb2e85875">llvm::remarks::RemarkSerializer::RemarkSerializer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#a062e25757dafc42e1222cb5df962d267">llvm::remarks::RemarkSerializer::SerializerFormat</a> and <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea9463f87bbed1fcdacfb8d40e185ca2bc">llvm::remarks::YAML</a>.</p>

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
