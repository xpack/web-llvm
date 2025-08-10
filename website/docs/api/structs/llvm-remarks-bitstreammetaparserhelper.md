---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/bitstreammetaparserhelper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `BitstreamMetaParserHelper` Struct

<p>Helper to parse a META_BLOCK for a bitstream remark container. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::BitstreamMetaParserHelper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">llvm/Remarks/BitstreamRemarkParser.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac68bb7d5a2b3927673738c771a092207">BitstreamMetaParserHelper</a> (BitstreamCursor &amp;Stream, BitstreamBlockInfo &amp;BlockInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Continue parsing with <span class="doxyComputerOutput">Stream</span>. <a href="#ac68bb7d5a2b3927673738c771a092207">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a826ea9c4393f00429edd20d09fb16e75">parse</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the META_BLOCK and fill the available entries. <a href="#a826ea9c4393f00429edd20d09fb16e75">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3452edb46677839de43c54d212848655">Stream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The Bitstream reader. <a href="#a3452edb46677839de43c54d212848655">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitstreamblockinfo">BitstreamBlockInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e30bed02f49f216f0928d79961d2229">BlockInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reference to the storage for the block info. <a href="#a8e30bed02f49f216f0928d79961d2229">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a084f2fb5445566ed92c4fe9d3ea93ec3">ContainerVersion</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The parsed content: depending on the container type, some fields might be empty. <a href="#a084f2fb5445566ed92c4fe9d3ea93ec3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae56a7ef95081de9d8658bc25e67ce029">ContainerType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acac316133cc6fd177c8346968e986d02">StrTabBuf</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0ffd7425e984e6b5b3062ab718706df">ExternalFilePath</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a221e8fddc1c8a587642ef5baa478472d">RemarkVersion</a></td>
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

<p>Helper to parse a META_BLOCK for a bitstream remark container.</p>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BitstreamMetaParserHelper() {#ac68bb7d5a2b3927673738c771a092207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamMetaParserHelper::BitstreamMetaParserHelper (<a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp; Stream, <a href="/web-llvm/docs/api/classes/llvm/bitstreamblockinfo">BitstreamBlockInfo</a> &amp; BlockInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Continue parsing with <span class="doxyComputerOutput">Stream</span>.</p>


<p><span class="doxyComputerOutput">Stream</span> is expected to contain a ENTER_SUBBLOCK to the META_BLOCK at the current position. <span class="doxyComputerOutput">Stream</span> is expected to have a BLOCKINFO_BLOCK set.</p>


<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>References <a href="#a8e30bed02f49f216f0928d79961d2229">BlockInfo</a> and <a href="#a3452edb46677839de43c54d212848655">Stream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### parse() {#a826ea9c4393f00429edd20d09fb16e75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BitstreamMetaParserHelper::parse ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the META_BLOCK and fill the available entries.</p>


<p>This helper does not check for the validity of the fields.</p>


<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>, definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a30a2d98c5581ada910c6b48afde25d7fa96cbb9f0138fc55670ed8eced6af857d">llvm::remarks::META_BLOCK_ID</a> and <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a9e3af87f6a7494ee71b0cdbf0c4d153c">parseBlock</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparser/#a13a75a9e36c3356534d09baa92151faf">llvm::remarks::BitstreamRemarkParser::parseMeta</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BlockInfo {#a8e30bed02f49f216f0928d79961d2229}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamBlockInfo&amp; llvm::remarks::BitstreamMetaParserHelper::BlockInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reference to the storage for the block info.</p>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="#ac68bb7d5a2b3927673738c771a092207">BitstreamMetaParserHelper</a>.</p>

</div>
</div>

### ContainerType {#ae56a7ef95081de9d8658bc25e67ce029}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint8_t&gt; llvm::remarks::BitstreamMetaParserHelper::ContainerType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a614e714a8963e8f854ecac210dde3125">parseRecord</a>.</p>

</div>
</div>

### ContainerVersion {#a084f2fb5445566ed92c4fe9d3ea93ec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::remarks::BitstreamMetaParserHelper::ContainerVersion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The parsed content: depending on the container type, some fields might be empty.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a614e714a8963e8f854ecac210dde3125">parseRecord</a>.</p>

</div>
</div>

### ExternalFilePath {#ae0ffd7425e984e6b5b3062ab718706df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;StringRef&gt; llvm::remarks::BitstreamMetaParserHelper::ExternalFilePath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a614e714a8963e8f854ecac210dde3125">parseRecord</a>.</p>

</div>
</div>

### RemarkVersion {#a221e8fddc1c8a587642ef5baa478472d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::remarks::BitstreamMetaParserHelper::RemarkVersion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a614e714a8963e8f854ecac210dde3125">parseRecord</a>.</p>

</div>
</div>

### Stream {#a3452edb46677839de43c54d212848655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamCursor&amp; llvm::remarks::BitstreamMetaParserHelper::Stream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The Bitstream reader.</p>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="#ac68bb7d5a2b3927673738c771a092207">BitstreamMetaParserHelper</a> and <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a614e714a8963e8f854ecac210dde3125">parseRecord</a>.</p>

</div>
</div>

### StrTabBuf {#acac316133cc6fd177c8346968e986d02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;StringRef&gt; llvm::remarks::BitstreamMetaParserHelper::StrTabBuf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a614e714a8963e8f854ecac210dde3125">parseRecord</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
