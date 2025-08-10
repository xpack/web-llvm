---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/bitstreamparserhelper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `BitstreamParserHelper` Struct

<p>Helper to parse any bitstream remark container. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::BitstreamParserHelper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">llvm/Remarks/BitstreamRemarkParser.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d4c73941ebc30cf7b9875675099c666">BitstreamParserHelper</a> (StringRef Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start parsing at <span class="doxyComputerOutput">Buffer</span>. <a href="#a1d4c73941ebc30cf7b9875675099c666">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::array&lt; char, 4 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91864eac8a4794fffda30075186a5d8f">parseMagic</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the magic number. <a href="#a91864eac8a4794fffda30075186a5d8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef087e7464b791f0ab26613736065520">parseBlockInfoBlock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the block info block containing all the abbrevs. <a href="#aef087e7464b791f0ab26613736065520">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab34732668c30428cb7a7f9b87044a959">isMetaBlock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the next block is a META_BLOCK. <a href="#ab34732668c30428cb7a7f9b87044a959">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bd057f2051ce4adb1cf5d39f525c674">isRemarkBlock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the next block is a REMARK_BLOCK. <a href="#a3bd057f2051ce4adb1cf5d39f525c674">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a654a19befcb5dcbbc4f0c4ce022e5d93">atEndOfStream</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the parser reached the end of the stream. <a href="#a654a19befcb5dcbbc4f0c4ce022e5d93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6893eab5fa87782d27235a0a9e09528a">skipToEnd</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Jump to the end of the stream, skipping everything. <a href="#a6893eab5fa87782d27235a0a9e09528a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2e7f2b1dba80a9a20f70ae50c7f3a78">Stream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The Bitstream reader. <a href="#ab2e7f2b1dba80a9a20f70ae50c7f3a78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitstreamblockinfo">BitstreamBlockInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c4ce9e20247516d25c9f1b8e9ff436e">BlockInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The block info block. <a href="#a9c4ce9e20247516d25c9f1b8e9ff436e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper to parse any bitstream remark container.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BitstreamParserHelper() {#a1d4c73941ebc30cf7b9875675099c666}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamParserHelper::BitstreamParserHelper (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Start parsing at <span class="doxyComputerOutput">Buffer</span>.</p>

<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>Reference <a href="#ab2e7f2b1dba80a9a20f70ae50c7f3a78">Stream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### atEndOfStream() {#a654a19befcb5dcbbc4f0c4ce022e5d93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::remarks::BitstreamParserHelper::atEndOfStream ()</td>
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

<p>Return true if the parser reached the end of the stream.</p>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Reference <a href="#ab2e7f2b1dba80a9a20f70ae50c7f3a78">Stream</a>.</p>

</div>
</div>

### isMetaBlock() {#ab34732668c30428cb7a7f9b87044a959}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; BitstreamParserHelper::isMetaBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the next block is a META_BLOCK.</p>


<p>This function does not move the cursor.</p>


<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>, definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#ad83a1def9d17dbb6fe203bac539c6f53">isBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a30a2d98c5581ada910c6b48afde25d7fa96cbb9f0138fc55670ed8eced6af857d">llvm::remarks::META_BLOCK_ID</a> and <a href="#ab2e7f2b1dba80a9a20f70ae50c7f3a78">Stream</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#ae7a2a8c8926efbbd98b5e02b989d58bf">advanceToMetaBlock</a>.</p>

</div>
</div>

### isRemarkBlock() {#a3bd057f2051ce4adb1cf5d39f525c674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; BitstreamParserHelper::isRemarkBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the next block is a REMARK_BLOCK.</p>


<p>This function does not move the cursor.</p>


<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#ad83a1def9d17dbb6fe203bac539c6f53">isBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a30a2d98c5581ada910c6b48afde25d7fa96cbb9f0138fc55670ed8eced6af857d">llvm::remarks::META_BLOCK_ID</a> and <a href="#ab2e7f2b1dba80a9a20f70ae50c7f3a78">Stream</a>.</p>

</div>
</div>

### parseBlockInfoBlock() {#aef087e7464b791f0ab26613736065520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BitstreamParserHelper::parseBlockInfoBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the block info block containing all the abbrevs.</p>


<p>This needs to be called before calling any other parsing function.</p>


<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>, definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>References <a href="#a9c4ce9e20247516d25c9f1b8e9ff436e">BlockInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a8cd4dd534ba6c31e93a88ca286c4f0e5a9c269366c4dc4af235c9bb24fa46f915">llvm::bitc::BLOCKINFO_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>, <a href="#ab2e7f2b1dba80a9a20f70ae50c7f3a78">Stream</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaac45aef6d995e5c810f2824a40fb1e2a">llvm::BitstreamEntry::SubBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#ae7a2a8c8926efbbd98b5e02b989d58bf">advanceToMetaBlock</a>.</p>

</div>
</div>

### parseMagic() {#a91864eac8a4794fffda30075186a5d8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::array&lt; char, 4 &gt; &gt; BitstreamParserHelper::parseMagic ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the magic number.</p>

<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>, definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>Reference <a href="#ab2e7f2b1dba80a9a20f70ae50c7f3a78">Stream</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#ae7a2a8c8926efbbd98b5e02b989d58bf">advanceToMetaBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a2d4315e24acdc204396b98bcc90a1399">llvm::remarks::createBitstreamParserFromMeta</a>.</p>

</div>
</div>

### skipToEnd() {#a6893eab5fa87782d27235a0a9e09528a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::remarks::BitstreamParserHelper::skipToEnd ()</td>
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

<p>Jump to the end of the stream, skipping everything.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Reference <a href="#ab2e7f2b1dba80a9a20f70ae50c7f3a78">Stream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BlockInfo {#a9c4ce9e20247516d25c9f1b8e9ff436e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamBlockInfo llvm::remarks::BitstreamParserHelper::BlockInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The block info block.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="#aef087e7464b791f0ab26613736065520">parseBlockInfoBlock</a>.</p>

</div>
</div>

### Stream {#ab2e7f2b1dba80a9a20f70ae50c7f3a78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamCursor llvm::remarks::BitstreamParserHelper::Stream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The Bitstream reader.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">BitstreamRemarkParser.h</a>.</p>


<p>Referenced by <a href="#a654a19befcb5dcbbc4f0c4ce022e5d93">atEndOfStream</a>, <a href="#a1d4c73941ebc30cf7b9875675099c666">BitstreamParserHelper</a>, <a href="#ab34732668c30428cb7a7f9b87044a959">isMetaBlock</a>, <a href="#a3bd057f2051ce4adb1cf5d39f525c674">isRemarkBlock</a>, <a href="#aef087e7464b791f0ab26613736065520">parseBlockInfoBlock</a>, <a href="#a91864eac8a4794fffda30075186a5d8f">parseMagic</a> and <a href="#a6893eab5fa87782d27235a0a9e09528a">skipToEnd</a>.</p>

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
