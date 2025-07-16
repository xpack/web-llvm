---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/bitstreamremarkparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BitstreamRemarkParser` Struct Reference

<p>Parses and holds the state of the latest parsed remark. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::BitstreamRemarkParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">Remarks/BitstreamRemarkParser.h</a>"
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87b9d7dbab269fcc020ca77e5de6b2ea">BitstreamRemarkParser</a> (StringRef Buf)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a parser that expects to find a string table embedded in the stream. <a href="#a87b9d7dbab269fcc020ca77e5de6b2ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a807136b05ed045dc36620215addd4bdf">BitstreamRemarkParser</a> (StringRef Buf, ParsedStringTable StrTab)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a parser that uses a pre-parsed string table. <a href="#a807136b05ed045dc36620215addd4bdf">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74eaa072e891d07610135a6406c752b3">next</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If no error occurs, this returns a valid <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> object. <a href="#a74eaa072e891d07610135a6406c752b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13a75a9e36c3356534d09baa92151faf">parseMeta</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse and process the metadata of the buffer. <a href="#a13a75a9e36c3356534d09baa92151faf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3df773f35f667f55b21ba89fd05472eb">parseRemark</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a Bitstream remark. <a href="#a3df773f35f667f55b21ba89fd05472eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80e1c38495931c7750e236664206f9f9">processCommonMeta</a> (BitstreamMetaParserHelper &amp;Helper)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper functions. <a href="#a80e1c38495931c7750e236664206f9f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56f89f8032fbf30e07413a92ac576cae">processStandaloneMeta</a> (BitstreamMetaParserHelper &amp;Helper)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa010c2ec53dcbdfd45102fff43924f8">processSeparateRemarksFileMeta</a> (BitstreamMetaParserHelper &amp;Helper)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0eaa3da49041ea81b242ac03a261462">processSeparateRemarksMetaMeta</a> (BitstreamMetaParserHelper &amp;Helper)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac23379cec923ddb6ed3e0a3e1cfd9969">processRemark</a> (BitstreamRemarkParserHelper &amp;Helper)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66cb6145d206feaec0f2d24512e3653d">processExternalFilePath</a> (std::optional&lt; StringRef &gt; ExternalFilePath)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamparserhelper">BitstreamParserHelper</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a625266002409dda843a29cd9ce1d6935">ParserHelper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The buffer to parse. <a href="#a625266002409dda843a29cd9ce1d6935">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/parsedstringtable">ParsedStringTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20c5b83786147f32ecb09f7514759cd6">StrTab</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The string table used for parsing strings. <a href="#a20c5b83786147f32ecb09f7514759cd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4db6dace08308bb9072db850fcfe7ad3">TmpRemarkBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Temporary remark buffer used when the remarks are stored separately. <a href="#a4db6dace08308bb9072db850fcfe7ad3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a578377c716c174dea0cb33b37418a654">ContainerVersion</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The common metadata used to decide how to parse the buffer. <a href="#a578377c716c174dea0cb33b37418a654">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d3659edef1822167d765d9a31a4525a">RemarkVersion</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1e">BitstreamRemarkContainerType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accd11b1bf999ed5625fef25190123c63">ContainerType</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9f1e6a87ddd2ec08cedc692e87bf3c4">ReadyToParseRemarks</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wether the parser is ready to parse remarks. <a href="#af9f1e6a87ddd2ec08cedc692e87bf3c4">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ccbc7f748e9c8288e37949e48a7e1f4">classof</a> (const RemarkParser *P)</td>
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

<p>Parses and holds the state of the latest parsed remark.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BitstreamRemarkParser() {#a87b9d7dbab269fcc020ca77e5de6b2ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::BitstreamRemarkParser::BitstreamRemarkParser (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buf)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a parser that expects to find a string table embedded in the stream.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea0b79eab5aacf81d139c4eaec818a549a">llvm::remarks::Bitstream</a>, <a href="#a625266002409dda843a29cd9ce1d6935">ParserHelper</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkparser/#a6030e67087fde04ece4556c929c0d42d">llvm::remarks::RemarkParser::RemarkParser</a>.</p>

</div>
</div>

### BitstreamRemarkParser() {#a807136b05ed045dc36620215addd4bdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::BitstreamRemarkParser::BitstreamRemarkParser (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buf, <a href="/web-llvm/docs/api/structs/llvm/remarks/parsedstringtable">ParsedStringTable</a> StrTab)</td>
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

<p>Create a parser that uses a pre-parsed string table.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea0b79eab5aacf81d139c4eaec818a549a">llvm::remarks::Bitstream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#a625266002409dda843a29cd9ce1d6935">ParserHelper</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkparser/#a6030e67087fde04ece4556c929c0d42d">llvm::remarks::RemarkParser::RemarkParser</a> and <a href="#a20c5b83786147f32ecb09f7514759cd6">StrTab</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### next() {#a74eaa072e891d07610135a6406c752b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; Remark &gt; &gt; BitstreamRemarkParser::next ()</td>
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


<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>, definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#a13a75a9e36c3356534d09baa92151faf">parseMeta</a>, <a href="#a3df773f35f667f55b21ba89fd05472eb">parseRemark</a>, <a href="#a625266002409dda843a29cd9ce1d6935">ParserHelper</a> and <a href="#af9f1e6a87ddd2ec08cedc692e87bf3c4">ReadyToParseRemarks</a>.</p>

</div>
</div>

### parseMeta() {#a13a75a9e36c3356534d09baa92151faf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BitstreamRemarkParser::parseMeta ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse and process the metadata of the buffer.</p>

<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>, definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#ae7a2a8c8926efbbd98b5e02b989d58bf">advanceToMetaBlock</a>, <a href="#accd11b1bf999ed5625fef25190123c63">ContainerType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaparserhelper/#a826ea9c4393f00429edd20d09fb16e75">llvm::remarks::BitstreamMetaParserHelper::parse</a>, <a href="#a625266002409dda843a29cd9ce1d6935">ParserHelper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1ea2a431092369d68b3ddf5f61852fee1a9">llvm::remarks::SeparateRemarksFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1ea4169738237fc9d6c1463bd5260de6c91">llvm::remarks::SeparateRemarksMeta</a> and <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1ea5c80f101108a356211fcb26b3f83eabb">llvm::remarks::Standalone</a>.</p>


<p>Referenced by <a href="#a74eaa072e891d07610135a6406c752b3">next</a>.</p>

</div>
</div>

### parseRemark() {#a3df773f35f667f55b21ba89fd05472eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; Remark &gt; &gt; BitstreamRemarkParser::parseRemark ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a Bitstream remark.</p>

<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>, definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparserhelper/#afe31085cbd69c4097cd149a4ac07c0f5">llvm::remarks::BitstreamRemarkParserHelper::parse</a> and <a href="#a625266002409dda843a29cd9ce1d6935">ParserHelper</a>.</p>


<p>Referenced by <a href="#a74eaa072e891d07610135a6406c752b3">next</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### processCommonMeta() {#a80e1c38495931c7750e236664206f9f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BitstreamRemarkParser::processCommonMeta (<a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaparserhelper">BitstreamMetaParserHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper functions.</p>

<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>, definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>

</div>
</div>

### processExternalFilePath() {#a66cb6145d206feaec0f2d24512e3653d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BitstreamRemarkParser::processExternalFilePath (std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; ExternalFilePath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>, definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>

</div>
</div>

### processRemark() {#ac23379cec923ddb6ed3e0a3e1cfd9969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; Remark &gt; &gt; BitstreamRemarkParser::processRemark (<a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparserhelper">BitstreamRemarkParserHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>, definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>

</div>
</div>

### processSeparateRemarksFileMeta() {#afa010c2ec53dcbdfd45102fff43924f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BitstreamRemarkParser::processSeparateRemarksFileMeta (<a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaparserhelper">BitstreamMetaParserHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>, definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>

</div>
</div>

### processSeparateRemarksMetaMeta() {#aa0eaa3da49041ea81b242ac03a261462}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BitstreamRemarkParser::processSeparateRemarksMetaMeta (<a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaparserhelper">BitstreamMetaParserHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>, definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>

</div>
</div>

### processStandaloneMeta() {#a56f89f8032fbf30e07413a92ac576cae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BitstreamRemarkParser::processStandaloneMeta (<a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaparserhelper">BitstreamMetaParserHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>, definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ContainerType {#accd11b1bf999ed5625fef25190123c63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamRemarkContainerType llvm::remarks::BitstreamRemarkParser::ContainerType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1ea5c80f101108a356211fcb26b3f83eabb">BitstreamRemarkContainerType::Standalone</a>
</div>
</dd>
</dl>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="#a13a75a9e36c3356534d09baa92151faf">parseMeta</a>.</p>

</div>
</div>

### ContainerVersion {#a578377c716c174dea0cb33b37418a654}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::remarks::BitstreamRemarkParser::ContainerVersion = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The common metadata used to decide how to parse the buffer.</p>


<p>This is filled when parsing the metadata block.</p>


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>

</div>
</div>

### ParserHelper {#a625266002409dda843a29cd9ce1d6935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamParserHelper llvm::remarks::BitstreamRemarkParser::ParserHelper</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The buffer to parse.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="#a87b9d7dbab269fcc020ca77e5de6b2ea">BitstreamRemarkParser</a>, <a href="#a807136b05ed045dc36620215addd4bdf">BitstreamRemarkParser</a>, <a href="#a74eaa072e891d07610135a6406c752b3">next</a>, <a href="#a13a75a9e36c3356534d09baa92151faf">parseMeta</a> and <a href="#a3df773f35f667f55b21ba89fd05472eb">parseRemark</a>.</p>

</div>
</div>

### ReadyToParseRemarks {#af9f1e6a87ddd2ec08cedc692e87bf3c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::remarks::BitstreamRemarkParser::ReadyToParseRemarks = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Wether the parser is ready to parse remarks.</p>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="#a74eaa072e891d07610135a6406c752b3">next</a>.</p>

</div>
</div>

### RemarkVersion {#a4d3659edef1822167d765d9a31a4525a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::remarks::BitstreamRemarkParser::RemarkVersion = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>

</div>
</div>

### StrTab {#a20c5b83786147f32ecb09f7514759cd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;ParsedStringTable&gt; llvm::remarks::BitstreamRemarkParser::StrTab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The string table used for parsing strings.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="#a807136b05ed045dc36620215addd4bdf">BitstreamRemarkParser</a>.</p>

</div>
</div>

### TmpRemarkBuffer {#a4db6dace08308bb9072db850fcfe7ad3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemoryBuffer&gt; llvm::remarks::BitstreamRemarkParser::TmpRemarkBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Temporary remark buffer used when the remarks are stored separately.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a7ccbc7f748e9c8288e37949e48a7e1f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::remarks::BitstreamRemarkParser::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkparser">RemarkParser</a> * P)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea0b79eab5aacf81d139c4eaec818a549a">llvm::remarks::Bitstream</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkparser/#a6030e67087fde04ece4556c929c0d42d">llvm::remarks::RemarkParser::RemarkParser</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
