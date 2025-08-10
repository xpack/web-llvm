---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/yamlstrtabremarkparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `YAMLStrTabRemarkParser` Struct

<p>YAML with a string table to <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> parser. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::YAMLStrTabRemarkParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">Remarks/YAMLRemarkParser.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser">YAMLRemarkParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Regular YAML to <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> parser. <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45bd58ea6c75bf2ab0a63b70ff5a29af">YAMLStrTabRemarkParser</a> (StringRef Buf, ParsedStringTable StrTab)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a221158c7ce70843476db9502693e8234">parseStr</a> (yaml::KeyValueNode &amp;Node) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse one value to a string. <a href="#a221158c7ce70843476db9502693e8234">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5beb0e25347b6cde7bff829d703a3443">classof</a> (const RemarkParser *P)</td>
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

<p>YAML with a string table to <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> parser.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### YAMLStrTabRemarkParser() {#a45bd58ea6c75bf2ab0a63b70ff5a29af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::YAMLStrTabRemarkParser::YAMLStrTabRemarkParser (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buf, <a href="/web-llvm/docs/api/structs/llvm/remarks/parsedstringtable">ParsedStringTable</a> StrTab)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#a51652a3fdbbe3c87d09cf38e3167c4b4">llvm::remarks::YAMLRemarkParser::StrTab</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#a3a272e234cbfd8e7b233a68c6499b388">llvm::remarks::YAMLRemarkParser::YAMLRemarkParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### parseStr() {#a221158c7ce70843476db9502693e8234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; YAMLStrTabRemarkParser::parseStr (<a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode">yaml::KeyValueNode</a> &amp; Node)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse one value to a string.</p>

<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>, definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp">YAMLRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#a0fe1e5bb33e59ff69fdfadb26e53d6db">llvm::remarks::YAMLRemarkParser::error</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/blockscalarnode/#afc7b0100cf3ac59f52e3dc04fb9279b4">llvm::yaml::BlockScalarNode::getValue</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#a11e6e321a8189217a9efb42d058dbbd7">llvm::remarks::YAMLRemarkParser::parseUnsigned</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#a51652a3fdbbe3c87d09cf38e3167c4b4">llvm::remarks::YAMLRemarkParser::StrTab</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a5beb0e25347b6cde7bff829d703a3443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::remarks::YAMLStrTabRemarkParser::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkparser">RemarkParser</a> * P)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea8bc4f729719767dd102c6ac3e55adf1d">llvm::remarks::YAMLStrTab</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp">YAMLRemarkParser.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
