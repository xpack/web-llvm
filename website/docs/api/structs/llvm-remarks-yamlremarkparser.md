---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/yamlremarkparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `YAMLRemarkParser` Struct

<p>Regular YAML to <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> parser. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::YAMLRemarkParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">Remarks/YAMLRemarkParser.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/remarkparser">RemarkParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parser used to parse a raw buffer to <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">remarks::Remark</a> objects. <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkparser/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkparser">YAMLStrTabRemarkParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>YAML with a string table to <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> parser. <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkparser/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a272e234cbfd8e7b233a68c6499b388">YAMLRemarkParser</a> (StringRef Buf)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af68bc601b3b9224bc60c53304275ce53">YAMLRemarkParser</a> (StringRef Buf, std::optional&lt; ParsedStringTable &gt; StrTab)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb5c8bd7367e9f8df487f08bdd08bc27">next</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If no error occurs, this returns a valid <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> object. <a href="#acb5c8bd7367e9f8df487f08bdd08bc27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fe1e5bb33e59ff69fdfadb26e53d6db">error</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/remarks/yamlparseerror">YAMLParseError</a> error from an existing error generated by the YAML parser. <a href="#a0fe1e5bb33e59ff69fdfadb26e53d6db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e07fabab63f8337f2efab1a6a9b86c5">error</a> (StringRef Message, yaml::Node &amp;Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/remarks/yamlparseerror">YAMLParseError</a> error referencing a specific node. <a href="#a1e07fabab63f8337f2efab1a6a9b86c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4d29f90f81ea8264f49bb0736faf1d0">parseRemark</a> (yaml::Document &amp;Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a YAML remark to a <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">remarks::Remark</a> object. <a href="#ac4d29f90f81ea8264f49bb0736faf1d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527f">Type</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe5f8ff50f8bc8d22acbe211ed9e19df">parseType</a> (yaml::MappingNode &amp;Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the type of a remark to an enum type. <a href="#afe5f8ff50f8bc8d22acbe211ed9e19df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b42231adc50f0683abb19c6cf809d03">parseKey</a> (yaml::KeyValueNode &amp;Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse one key to a string. <a href="#a7b42231adc50f0683abb19c6cf809d03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a6ec3a40008d26820e59354d6989c13">parseStr</a> (yaml::KeyValueNode &amp;Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse one value to a string. <a href="#a6a6ec3a40008d26820e59354d6989c13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11e6e321a8189217a9efb42d058dbbd7">parseUnsigned</a> (yaml::KeyValueNode &amp;Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse one value to an unsigned. <a href="#a11e6e321a8189217a9efb42d058dbbd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/remarklocation">RemarkLocation</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66625e87299e9c2a860b373e0f4d5b80">parseDebugLoc</a> (yaml::KeyValueNode &amp;Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a debug location. <a href="#a66625e87299e9c2a860b373e0f4d5b80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/argument">Argument</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abda1ebf8585492b9082471af74921703">parseArg</a> (yaml::Node &amp;Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an argument. <a href="#abda1ebf8585492b9082471af74921703">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/parsedstringtable">ParsedStringTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51652a3fdbbe3c87d09cf38e3167c4b4">StrTab</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The string table used for parsing strings. <a href="#a51652a3fdbbe3c87d09cf38e3167c4b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefdd1cf50d22772e50425d40dc7b6998">LastErrorMessage</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Last error message that can come from the YAML parser diagnostics. <a href="#aefdd1cf50d22772e50425d40dc7b6998">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6f75a674fa35e5c666f95e6e1fdcaf7">SM</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Source manager for better error messages. <a href="#ad6f75a674fa35e5c666f95e6e1fdcaf7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/stream">yaml::Stream</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15c8d2dba74180a884b74f763fd1a809">Stream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stream for yaml parsing. <a href="#a15c8d2dba74180a884b74f763fd1a809">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/document-iterator">yaml::document_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dc5c761322ed747dd927c1876e5ec68">YAMLIt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterator in the YAML stream. <a href="#a0dc5c761322ed747dd927c1876e5ec68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a72b6dc5e513ac03007e8ac9ee20307">SeparateBuf</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we parse remark metadata in separate mode, we need to open a new file and parse that. <a href="#a5a72b6dc5e513ac03007e8ac9ee20307">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6b60b1a48be520f93b115fa62c87986">classof</a> (const RemarkParser *P)</td>
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

<p>Regular YAML to <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> parser.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### YAMLRemarkParser() {#a3a272e234cbfd8e7b233a68c6499b388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">YAMLRemarkParser::YAMLRemarkParser (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buf)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>, definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp">YAMLRemarkParser.cpp</a>.</p>


<p>Reference <a href="#a3a272e234cbfd8e7b233a68c6499b388">YAMLRemarkParser</a>.</p>


<p>Referenced by <a href="#a3a272e234cbfd8e7b233a68c6499b388">YAMLRemarkParser</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkparser/#a45bd58ea6c75bf2ab0a63b70ff5a29af">llvm::remarks::YAMLStrTabRemarkParser::YAMLStrTabRemarkParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### YAMLRemarkParser() {#af68bc601b3b9224bc60c53304275ce53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">YAMLRemarkParser::YAMLRemarkParser (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buf, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/parsedstringtable">ParsedStringTable</a> &gt; StrTab)</td>
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



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>, definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp">YAMLRemarkParser.cpp</a>.</p>


<p>References <a href="#aefdd1cf50d22772e50425d40dc7b6998">LastErrorMessage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkparser/#a6030e67087fde04ece4556c929c0d42d">llvm::remarks::RemarkParser::RemarkParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp/#a08be5fbbd5b0a3cc5ddc2a582fbd200d">setupSM</a>, <a href="#ad6f75a674fa35e5c666f95e6e1fdcaf7">SM</a>, <a href="#a15c8d2dba74180a884b74f763fd1a809">Stream</a>, <a href="#a51652a3fdbbe3c87d09cf38e3167c4b4">StrTab</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea9463f87bbed1fcdacfb8d40e185ca2bc">llvm::remarks::YAML</a> and <a href="#a0dc5c761322ed747dd927c1876e5ec68">YAMLIt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### next() {#acb5c8bd7367e9f8df487f08bdd08bc27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; Remark &gt; &gt; YAMLRemarkParser::next ()</td>
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

<p>If no error occurs, this returns a valid <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> object.</p>


<p>If an error of type <a href="/web-llvm/docs/api/classes/llvm/remarks/endoffileerror">EndOfFileError</a> occurs, it is safe to recover from it by stopping the parsing. If any other error occurs, it should be propagated to the user. The pointer should never be null.</p>


<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>, definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp">YAMLRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#ac4d29f90f81ea8264f49bb0736faf1d0">parseRemark</a>, <a href="#a15c8d2dba74180a884b74f763fd1a809">Stream</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="#a0dc5c761322ed747dd927c1876e5ec68">YAMLIt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### error() {#a0fe1e5bb33e59ff69fdfadb26e53d6db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error YAMLRemarkParser::error ()</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/remarks/yamlparseerror">YAMLParseError</a> error from an existing error generated by the YAML parser.</p>


<p>If there is no error, this returns Success.</p>


<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>, definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp">YAMLRemarkParser.cpp</a>.</p>


<p>References <a href="#aefdd1cf50d22772e50425d40dc7b6998">LastErrorMessage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#abda1ebf8585492b9082471af74921703">parseArg</a>, <a href="#a66625e87299e9c2a860b373e0f4d5b80">parseDebugLoc</a>, <a href="#a7b42231adc50f0683abb19c6cf809d03">parseKey</a>, <a href="#ac4d29f90f81ea8264f49bb0736faf1d0">parseRemark</a>, <a href="#a6a6ec3a40008d26820e59354d6989c13">parseStr</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkparser/#a221158c7ce70843476db9502693e8234">llvm::remarks::YAMLStrTabRemarkParser::parseStr</a>, <a href="#afe5f8ff50f8bc8d22acbe211ed9e19df">parseType</a> and <a href="#a11e6e321a8189217a9efb42d058dbbd7">parseUnsigned</a>.</p>

</div>
</div>

### error() {#a1e07fabab63f8337f2efab1a6a9b86c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error YAMLRemarkParser::error (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Message, <a href="/web-llvm/docs/api/classes/llvm/yaml/node">yaml::Node</a> &amp; Node)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/remarks/yamlparseerror">YAMLParseError</a> error referencing a specific node.</p>

<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp">YAMLRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#ad6f75a674fa35e5c666f95e6e1fdcaf7">SM</a> and <a href="#a15c8d2dba74180a884b74f763fd1a809">Stream</a>.</p>

</div>
</div>

### parseArg() {#abda1ebf8585492b9082471af74921703}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Argument &gt; YAMLRemarkParser::parseArg (<a href="/web-llvm/docs/api/classes/llvm/yaml/node">yaml::Node</a> &amp; Node)</td>
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

<p>Parse an argument.</p>

<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>, definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp">YAMLRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a0fe1e5bb33e59ff69fdfadb26e53d6db">error</a>, <a href="#a66625e87299e9c2a860b373e0f4d5b80">parseDebugLoc</a>, <a href="#a7b42231adc50f0683abb19c6cf809d03">parseKey</a>, <a href="#a6a6ec3a40008d26820e59354d6989c13">parseStr</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#ac4d29f90f81ea8264f49bb0736faf1d0">parseRemark</a>.</p>

</div>
</div>

### parseDebugLoc() {#a66625e87299e9c2a860b373e0f4d5b80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; RemarkLocation &gt; YAMLRemarkParser::parseDebugLoc (<a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode">yaml::KeyValueNode</a> &amp; Node)</td>
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

<p>Parse a debug location.</p>

<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>, definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp">YAMLRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a0fe1e5bb33e59ff69fdfadb26e53d6db">error</a>, <a href="#a7b42231adc50f0683abb19c6cf809d03">parseKey</a>, <a href="#a6a6ec3a40008d26820e59354d6989c13">parseStr</a>, <a href="#a11e6e321a8189217a9efb42d058dbbd7">parseUnsigned</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#abda1ebf8585492b9082471af74921703">parseArg</a> and <a href="#ac4d29f90f81ea8264f49bb0736faf1d0">parseRemark</a>.</p>

</div>
</div>

### parseKey() {#a7b42231adc50f0683abb19c6cf809d03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; YAMLRemarkParser::parseKey (<a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode">yaml::KeyValueNode</a> &amp; Node)</td>
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

<p>Parse one key to a string.</p>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>, definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp">YAMLRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a0fe1e5bb33e59ff69fdfadb26e53d6db">error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>


<p>Referenced by <a href="#abda1ebf8585492b9082471af74921703">parseArg</a>, <a href="#a66625e87299e9c2a860b373e0f4d5b80">parseDebugLoc</a> and <a href="#ac4d29f90f81ea8264f49bb0736faf1d0">parseRemark</a>.</p>

</div>
</div>

### parseRemark() {#ac4d29f90f81ea8264f49bb0736faf1d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; Remark &gt; &gt; YAMLRemarkParser::parseRemark (<a href="/web-llvm/docs/api/classes/llvm/yaml/document">yaml::Document</a> &amp; Remark)</td>
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

<p>Parse a YAML remark to a <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">remarks::Remark</a> object.</p>

<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>, definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp">YAMLRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/remarks/remark/#ad43b86418150167e66360c78b004daae">llvm::remarks::Remark::Args</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="#a0fe1e5bb33e59ff69fdfadb26e53d6db">error</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remark/#aa22dc5b75c24c27c88fda7c86be9e16a">llvm::remarks::Remark::FunctionName</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/document/#a673e9ef8fd2171ea34096f60eed3c74d">llvm::yaml::Document::getRoot</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remark/#a55696a404b259163add62a3fc346de3b">llvm::remarks::Remark::Hotness</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remark/#a357123bac089573c87522957e3eb12e3">llvm::remarks::Remark::Loc</a>, <a href="#abda1ebf8585492b9082471af74921703">parseArg</a>, <a href="#a66625e87299e9c2a860b373e0f4d5b80">parseDebugLoc</a>, <a href="#a7b42231adc50f0683abb19c6cf809d03">parseKey</a>, <a href="#a6a6ec3a40008d26820e59354d6989c13">parseStr</a>, <a href="#afe5f8ff50f8bc8d22acbe211ed9e19df">parseType</a>, <a href="#a11e6e321a8189217a9efb42d058dbbd7">parseUnsigned</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remark/#a35431065aaa52c0d81d719b2468697ed">llvm::remarks::Remark::PassName</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remark/#a8560e9790fc6522f5ac5ec7e4e3e1f95">llvm::remarks::Remark::RemarkName</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remark/#a241d25fa7a832abc5c8583bc728ec1f1">llvm::remarks::Remark::RemarkType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527fa88183b946cc5f0e8c96b2e66e1c74a7e">llvm::remarks::Unknown</a>.</p>


<p>Referenced by <a href="#acb5c8bd7367e9f8df487f08bdd08bc27">next</a>.</p>

</div>
</div>

### parseStr() {#a6a6ec3a40008d26820e59354d6989c13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; YAMLRemarkParser::parseStr (<a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode">yaml::KeyValueNode</a> &amp; Node)</td>
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

<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>, definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp">YAMLRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a0fe1e5bb33e59ff69fdfadb26e53d6db">error</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/blockscalarnode/#afc7b0100cf3ac59f52e3dc04fb9279b4">llvm::yaml::BlockScalarNode::getValue</a>.</p>


<p>Referenced by <a href="#abda1ebf8585492b9082471af74921703">parseArg</a>, <a href="#a66625e87299e9c2a860b373e0f4d5b80">parseDebugLoc</a> and <a href="#ac4d29f90f81ea8264f49bb0736faf1d0">parseRemark</a>.</p>

</div>
</div>

### parseType() {#afe5f8ff50f8bc8d22acbe211ed9e19df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Type &gt; YAMLRemarkParser::parseType (<a href="/web-llvm/docs/api/classes/llvm/yaml/mappingnode">yaml::MappingNode</a> &amp; Node)</td>
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

<p>Parse the type of a remark to an enum type.</p>

<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>, definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp">YAMLRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527fa739e6d2a73723ec7b1919fa5a51f9b07">llvm::remarks::Analysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527fa0b3099ea02e918671e4f2f122c3cbb22">llvm::remarks::AnalysisAliasing</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527fa23628109ba8dd4d9e96c506db0738e77">llvm::remarks::AnalysisFPCommute</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="#a0fe1e5bb33e59ff69fdfadb26e53d6db">error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527fae139a585510a502bbf1841cf589f5086">llvm::remarks::Failure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527faca9e83a6c347b2bdf7f00ef202a331ad">llvm::remarks::Missed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527faa0d0628f6b4e4d78d2ffef4d4d1c4b15">llvm::remarks::Passed</a> and <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527fa88183b946cc5f0e8c96b2e66e1c74a7e">llvm::remarks::Unknown</a>.</p>


<p>Referenced by <a href="#ac4d29f90f81ea8264f49bb0736faf1d0">parseRemark</a>.</p>

</div>
</div>

### parseUnsigned() {#a11e6e321a8189217a9efb42d058dbbd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; unsigned &gt; YAMLRemarkParser::parseUnsigned (<a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode">yaml::KeyValueNode</a> &amp; Node)</td>
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

<p>Parse one value to an unsigned.</p>

<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>, definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp">YAMLRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#a0fe1e5bb33e59ff69fdfadb26e53d6db">error</a>.</p>


<p>Referenced by <a href="#a66625e87299e9c2a860b373e0f4d5b80">parseDebugLoc</a>, <a href="#ac4d29f90f81ea8264f49bb0736faf1d0">parseRemark</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkparser/#a221158c7ce70843476db9502693e8234">llvm::remarks::YAMLStrTabRemarkParser::parseStr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### LastErrorMessage {#aefdd1cf50d22772e50425d40dc7b6998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::remarks::YAMLRemarkParser::LastErrorMessage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Last error message that can come from the YAML parser diagnostics.</p>


<p>We need this for catching errors in the constructor.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>.</p>


<p>Referenced by <a href="#a0fe1e5bb33e59ff69fdfadb26e53d6db">error</a> and <a href="#af68bc601b3b9224bc60c53304275ce53">YAMLRemarkParser</a>.</p>

</div>
</div>

### SeparateBuf {#a5a72b6dc5e513ac03007e8ac9ee20307}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemoryBuffer&gt; llvm::remarks::YAMLRemarkParser::SeparateBuf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If we parse remark metadata in separate mode, we need to open a new file and parse that.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>.</p>

</div>
</div>

### SM {#ad6f75a674fa35e5c666f95e6e1fdcaf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceMgr llvm::remarks::YAMLRemarkParser::SM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Source manager for better error messages.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>.</p>


<p>Referenced by <a href="#a1e07fabab63f8337f2efab1a6a9b86c5">error</a> and <a href="#af68bc601b3b9224bc60c53304275ce53">YAMLRemarkParser</a>.</p>

</div>
</div>

### Stream {#a15c8d2dba74180a884b74f763fd1a809}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::Stream llvm::remarks::YAMLRemarkParser::Stream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stream for yaml parsing.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>.</p>


<p>Referenced by <a href="#a1e07fabab63f8337f2efab1a6a9b86c5">error</a>, <a href="#acb5c8bd7367e9f8df487f08bdd08bc27">next</a> and <a href="#af68bc601b3b9224bc60c53304275ce53">YAMLRemarkParser</a>.</p>

</div>
</div>

### StrTab {#a51652a3fdbbe3c87d09cf38e3167c4b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;ParsedStringTable&gt; llvm::remarks::YAMLRemarkParser::StrTab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The string table used for parsing strings.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkparser/#a221158c7ce70843476db9502693e8234">llvm::remarks::YAMLStrTabRemarkParser::parseStr</a>, <a href="#af68bc601b3b9224bc60c53304275ce53">YAMLRemarkParser</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlstrtabremarkparser/#a45bd58ea6c75bf2ab0a63b70ff5a29af">llvm::remarks::YAMLStrTabRemarkParser::YAMLStrTabRemarkParser</a>.</p>

</div>
</div>

### YAMLIt {#a0dc5c761322ed747dd927c1876e5ec68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::document_iterator llvm::remarks::YAMLRemarkParser::YAMLIt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterator in the YAML stream.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>.</p>


<p>Referenced by <a href="#acb5c8bd7367e9f8df487f08bdd08bc27">next</a> and <a href="#af68bc601b3b9224bc60c53304275ce53">YAMLRemarkParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ac6b60b1a48be520f93b115fa62c87986}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::remarks::YAMLRemarkParser::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkparser">RemarkParser</a> * P)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkparser/#a6030e67087fde04ece4556c929c0d42d">llvm::remarks::RemarkParser::RemarkParser</a> and <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea9463f87bbed1fcdacfb8d40e185ca2bc">llvm::remarks::YAML</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
