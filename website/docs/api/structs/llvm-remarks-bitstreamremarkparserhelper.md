---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/bitstreamremarkparserhelper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BitstreamRemarkParserHelper` Struct Reference

<p>Helper to parse a REMARK_BLOCK for a bitstream remark container. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::BitstreamRemarkParserHelper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">llvm/Remarks/BitstreamRemarkParser.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad557da4c58f76f8b5582eb7cbf2699f">BitstreamRemarkParserHelper</a> (BitstreamCursor &amp;Stream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Continue parsing with <span class="doxyComputerOutput">Stream</span>. <a href="#aad557da4c58f76f8b5582eb7cbf2699f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe31085cbd69c4097cd149a4ac07c0f5">parse</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the REMARK_BLOCK and fill the available entries. <a href="#afe31085cbd69c4097cd149a4ac07c0f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3be772eabb34a2b1d5241bfb064b3a36">Stream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The Bitstream reader. <a href="#a3be772eabb34a2b1d5241bfb064b3a36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01fa10e16ec7e17fb31b0b8934de7ea9">Type</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The parsed content: depending on the remark, some fields might be empty. <a href="#a01fa10e16ec7e17fb31b0b8934de7ea9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac1680930daf95ad4c258709b8518e8b">RemarkNameIdx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a323d8a7adcd935236d9340232301a93b">PassNameIdx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70fa0994181a7103ddd9bbc488a96e28">FunctionNameIdx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f55da3885c489bb87753fc8c1664002">SourceFileNameIdx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa402ec5953c76f4f911909f25633e775">SourceLine</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a661066f9e650f6e38a4f7940797c5530">SourceColumn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af93a189fc0f40271d62ba7f5d3568cf0">Hotness</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparserhelper/argument">Argument</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03e0ae3c26607b39bb3e68ccecd97f57">Args</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparserhelper/argument">Argument</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c9cbad7c034b4117c94b60dee3900ba">TmpArgs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Avoid re-allocating a vector every time. <a href="#a6c9cbad7c034b4117c94b60dee3900ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper to parse a REMARK_BLOCK for a bitstream remark container.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BitstreamRemarkParserHelper() {#aad557da4c58f76f8b5582eb7cbf2699f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamRemarkParserHelper::BitstreamRemarkParserHelper (<a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp; Stream)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Continue parsing with <span class="doxyComputerOutput">Stream</span>.</p>


<p><span class="doxyComputerOutput">Stream</span> is expected to contain a ENTER_SUBBLOCK to the REMARK_BLOCK at the current position. <span class="doxyComputerOutput">Stream</span> is expected to have a BLOCKINFO_BLOCK set and to have already parsed the META_BLOCK.</p>


<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>Reference <a href="#a3be772eabb34a2b1d5241bfb064b3a36">Stream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### parse() {#afe31085cbd69c4097cd149a4ac07c0f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BitstreamRemarkParserHelper::parse ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the REMARK_BLOCK and fill the available entries.</p>


<p>This helper does not check for the validity of the fields.</p>


<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>, definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a9e3af87f6a7494ee71b0cdbf0c4d153c">parseBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a30a2d98c5581ada910c6b48afde25d7fa6bbe4805277c5857c0c4b7abe5253525">llvm::remarks::REMARK_BLOCK_ID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparser/#a3df773f35f667f55b21ba89fd05472eb">llvm::remarks::BitstreamRemarkParser::parseRemark</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Args {#a03e0ae3c26607b39bb3e68ccecd97f57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;ArrayRef&lt;Argument&gt; &gt; llvm::remarks::BitstreamRemarkParserHelper::Args</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a384d242ae8d66e4ea84344784426e3a7">parseRecord</a>.</p>

</div>
</div>

### FunctionNameIdx {#a70fa0994181a7103ddd9bbc488a96e28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::remarks::BitstreamRemarkParserHelper::FunctionNameIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a384d242ae8d66e4ea84344784426e3a7">parseRecord</a>.</p>

</div>
</div>

### Hotness {#af93a189fc0f40271d62ba7f5d3568cf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::remarks::BitstreamRemarkParserHelper::Hotness</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a384d242ae8d66e4ea84344784426e3a7">parseRecord</a>.</p>

</div>
</div>

### PassNameIdx {#a323d8a7adcd935236d9340232301a93b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::remarks::BitstreamRemarkParserHelper::PassNameIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a384d242ae8d66e4ea84344784426e3a7">parseRecord</a>.</p>

</div>
</div>

### RemarkNameIdx {#aac1680930daf95ad4c258709b8518e8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::remarks::BitstreamRemarkParserHelper::RemarkNameIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a384d242ae8d66e4ea84344784426e3a7">parseRecord</a>.</p>

</div>
</div>

### SourceColumn {#a661066f9e650f6e38a4f7940797c5530}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint32_t&gt; llvm::remarks::BitstreamRemarkParserHelper::SourceColumn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a384d242ae8d66e4ea84344784426e3a7">parseRecord</a>.</p>

</div>
</div>

### SourceFileNameIdx {#a9f55da3885c489bb87753fc8c1664002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::remarks::BitstreamRemarkParserHelper::SourceFileNameIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a384d242ae8d66e4ea84344784426e3a7">parseRecord</a>.</p>

</div>
</div>

### SourceLine {#aa402ec5953c76f4f911909f25633e775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint32_t&gt; llvm::remarks::BitstreamRemarkParserHelper::SourceLine</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a384d242ae8d66e4ea84344784426e3a7">parseRecord</a>.</p>

</div>
</div>

### Stream {#a3be772eabb34a2b1d5241bfb064b3a36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamCursor&amp; llvm::remarks::BitstreamRemarkParserHelper::Stream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The Bitstream reader.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="#aad557da4c58f76f8b5582eb7cbf2699f">BitstreamRemarkParserHelper</a> and <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a384d242ae8d66e4ea84344784426e3a7">parseRecord</a>.</p>

</div>
</div>

### TmpArgs {#a6c9cbad7c034b4117c94b60dee3900ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Argument, 8&gt; llvm::remarks::BitstreamRemarkParserHelper::TmpArgs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Avoid re-allocating a vector every time.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a384d242ae8d66e4ea84344784426e3a7">parseRecord</a>.</p>

</div>
</div>

### Type {#a01fa10e16ec7e17fb31b0b8934de7ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint8_t&gt; llvm::remarks::BitstreamRemarkParserHelper::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The parsed content: depending on the remark, some fields might be empty.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a384d242ae8d66e4ea84344784426e3a7">parseRecord</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
