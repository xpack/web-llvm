---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/remarks/bitstreamremarkparser-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `BitstreamRemarkParser.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkparser-h">llvm/Remarks/BitstreamRemarkParser.h</a>"
#include "BitstreamRemarkParser.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">llvm/Remarks/Remark.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">llvm/Support/MemoryBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include &lt;optional&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae71b1adcbe2ef2bdde5e8163a1d0349">unknownRecord</a> (const char *BlockName, unsigned RecordID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a599a75448e2154c1977208a327bb1a6c">malformedRecord</a> (const char *BlockName, const char *RecordName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a614e714a8963e8f854ecac210dde3125">parseRecord</a> (BitstreamMetaParserHelper &amp;Parser, unsigned Code)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a record and fill in the fields in the parser. <a href="#a614e714a8963e8f854ecac210dde3125">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a384d242ae8d66e4ea84344784426e3a7">parseRecord</a> (BitstreamRemarkParserHelper &amp;Parser, unsigned Code)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a record and fill in the fields in the parser. <a href="#a384d242ae8d66e4ea84344784426e3a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9e3af87f6a7494ee71b0cdbf0c4d153c">parseBlock</a> (T &amp;ParserHelper, unsigned BlockID, const char *BlockName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad83a1def9d17dbb6fe203bac539c6f53">isBlock</a> (BitstreamCursor &amp;Stream, unsigned BlockID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6062a9632d9d9c4d35afd3e82970887e">validateMagicNumber</a> (StringRef MagicNumber)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7a2a8c8926efbbd98b5e02b989d58bf">advanceToMetaBlock</a> (BitstreamParserHelper &amp;Helper)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab380b488629f55df87400a566043f37">processStrTab</a> (BitstreamRemarkParser &amp;P, std::optional&lt; StringRef &gt; StrTabBuf)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37c014ff1e40aad67d394566e65800bf">processRemarkVersion</a> (BitstreamRemarkParser &amp;P, std::optional&lt; uint64_t &gt; RemarkVersion)</td>
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


<div class="doxySectionDef">

## Functions

### advanceToMetaBlock() {#ae7a2a8c8926efbbd98b5e02b989d58bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error advanceToMetaBlock (<a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamparserhelper">BitstreamParserHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamparserhelper/#ab34732668c30428cb7a7f9b87044a959">llvm::remarks::BitstreamParserHelper::isMetaBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamparserhelper/#aef087e7464b791f0ab26613736065520">llvm::remarks::BitstreamParserHelper::parseBlockInfoBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamparserhelper/#a91864eac8a4794fffda30075186a5d8f">llvm::remarks::BitstreamParserHelper::parseMagic</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="#a6062a9632d9d9c4d35afd3e82970887e">validateMagicNumber</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparser/#a13a75a9e36c3356534d09baa92151faf">llvm::remarks::BitstreamRemarkParser::parseMeta</a>.</p>

</div>
</div>

### isBlock() {#ad83a1def9d17dbb6fe203bac539c6f53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; isBlock (<a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp; Stream, unsigned BlockID)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a49c750caac5ed5f8a5333e14ada8d5ed">llvm::BitstreamCursor::advance</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaff48a2349df5a9fe16c80d1d6e32e479">llvm::BitstreamEntry::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a1dfc6241f79207e8c0a44d6c2ffb0801">llvm::BitstreamCursor::GetCurrentBitNo</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a003287dcd6e4d73526b117b2709e2347">llvm::BitstreamCursor::JumpToBit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a> and <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaac45aef6d995e5c810f2824a40fb1e2a">llvm::BitstreamEntry::SubBlock</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamparserhelper/#ab34732668c30428cb7a7f9b87044a959">llvm::remarks::BitstreamParserHelper::isMetaBlock</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamparserhelper/#a3bd057f2051ce4adb1cf5d39f525c674">llvm::remarks::BitstreamParserHelper::isRemarkBlock</a>.</p>

</div>
</div>

### malformedRecord() {#a599a75448e2154c1977208a327bb1a6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error malformedRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * BlockName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * RecordName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>.</p>


<p>Referenced by <a href="#a614e714a8963e8f854ecac210dde3125">parseRecord</a> and <a href="#a384d242ae8d66e4ea84344784426e3a7">parseRecord</a>.</p>

</div>
</div>

### parseBlock() {#a9e3af87f6a7494ee71b0cdbf0c4d153c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error parseBlock (T &amp; ParserHelper, unsigned BlockID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * BlockName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a49c750caac5ed5f8a5333e14ada8d5ed">llvm::BitstreamCursor::advance</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a0b2540236df88a84a8b8ea3f7158ae47">llvm::BitstreamCursor::AtEndOfStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea69bcb0a249ff563515ad5c77bc19ebfe">llvm::BitstreamEntry::EndBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a6ced3cd5539e8a620f270f3dbb0c48ab">llvm::BitstreamCursor::EnterSubBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaff48a2349df5a9fe16c80d1d6e32e479">llvm::BitstreamEntry::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>, <a href="#a614e714a8963e8f854ecac210dde3125">parseRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea05d3cc255293715b2712b9bbdfc6011c">llvm::BitstreamEntry::Record</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaac45aef6d995e5c810f2824a40fb1e2a">llvm::BitstreamEntry::SubBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaparserhelper/#a826ea9c4393f00429edd20d09fb16e75">llvm::remarks::BitstreamMetaParserHelper::parse</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparserhelper/#afe31085cbd69c4097cd149a4ac07c0f5">llvm::remarks::BitstreamRemarkParserHelper::parse</a>.</p>

</div>
</div>

### parseRecord() {#a614e714a8963e8f854ecac210dde3125}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error parseRecord (<a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaparserhelper">BitstreamMetaParserHelper</a> &amp; Parser, unsigned Code)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a record and fill in the fields in the parser.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaparserhelper/#ae56a7ef95081de9d8658bc25e67ce029">llvm::remarks::BitstreamMetaParserHelper::ContainerType</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaparserhelper/#a084f2fb5445566ed92c4fe9d3ea93ec3">llvm::remarks::BitstreamMetaParserHelper::ContainerVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaparserhelper/#ae0ffd7425e984e6b5b3062ab718706df">llvm::remarks::BitstreamMetaParserHelper::ExternalFilePath</a>, <a href="#a599a75448e2154c1977208a327bb1a6c">malformedRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a677592abe148dbc3de1ec00f3d9904c5">llvm::BitstreamCursor::readRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fab594601a3780245b09d12bc9827eaafa">llvm::remarks::RECORD_META_CONTAINER_INFO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83faec8eaa274dde3835551571eb0fe9a985">llvm::remarks::RECORD_META_EXTERNAL_FILE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fa3257414078656415dda5988b7a497fbf">llvm::remarks::RECORD_META_REMARK_VERSION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fa67132c432a4ef085fa04581bf9964ee9">llvm::remarks::RECORD_META_STRTAB</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaparserhelper/#a221e8fddc1c8a587642ef5baa478472d">llvm::remarks::BitstreamMetaParserHelper::RemarkVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaparserhelper/#a3452edb46677839de43c54d212848655">llvm::remarks::BitstreamMetaParserHelper::Stream</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreammetaparserhelper/#acac316133cc6fd177c8346968e986d02">llvm::remarks::BitstreamMetaParserHelper::StrTabBuf</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="#aae71b1adcbe2ef2bdde5e8163a1d0349">unknownRecord</a>.</p>


<p>Referenced by <a href="#a9e3af87f6a7494ee71b0cdbf0c4d153c">parseBlock</a>.</p>

</div>
</div>

### parseRecord() {#a384d242ae8d66e4ea84344784426e3a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error parseRecord (<a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparserhelper">BitstreamRemarkParserHelper</a> &amp; Parser, unsigned Code)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a record and fill in the fields in the parser.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparserhelper/#a03e0ae3c26607b39bb3e68ccecd97f57">llvm::remarks::BitstreamRemarkParserHelper::Args</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparserhelper/#a70fa0994181a7103ddd9bbc488a96e28">llvm::remarks::BitstreamRemarkParserHelper::FunctionNameIdx</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparserhelper/#af93a189fc0f40271d62ba7f5d3568cf0">llvm::remarks::BitstreamRemarkParserHelper::Hotness</a>, <a href="#a599a75448e2154c1977208a327bb1a6c">malformedRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparserhelper/#a323d8a7adcd935236d9340232301a93b">llvm::remarks::BitstreamRemarkParserHelper::PassNameIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a677592abe148dbc3de1ec00f3d9904c5">llvm::BitstreamCursor::readRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fab47a0f52d7a068b383bb8efa7bc4c964">llvm::remarks::RECORD_REMARK_ARG_WITH_DEBUGLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83faaf1240d15cbcc04f12c9c7c36d796a7b">llvm::remarks::RECORD_REMARK_ARG_WITHOUT_DEBUGLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fad5259ac7c5361f20e4ee591fb5d1c536">llvm::remarks::RECORD_REMARK_DEBUG_LOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fad48248d7c205d6a54125b2b6c10bb5cb">llvm::remarks::RECORD_REMARK_HEADER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fab81a5e37436c29b092e2a6a6db252d7b">llvm::remarks::RECORD_REMARK_HOTNESS</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparserhelper/#aac1680930daf95ad4c258709b8518e8b">llvm::remarks::BitstreamRemarkParserHelper::RemarkNameIdx</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparserhelper/#a661066f9e650f6e38a4f7940797c5530">llvm::remarks::BitstreamRemarkParserHelper::SourceColumn</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparserhelper/#a9f55da3885c489bb87753fc8c1664002">llvm::remarks::BitstreamRemarkParserHelper::SourceFileNameIdx</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparserhelper/#aa402ec5953c76f4f911909f25633e775">llvm::remarks::BitstreamRemarkParserHelper::SourceLine</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparserhelper/#a3be772eabb34a2b1d5241bfb064b3a36">llvm::remarks::BitstreamRemarkParserHelper::Stream</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparserhelper/#a6c9cbad7c034b4117c94b60dee3900ba">llvm::remarks::BitstreamRemarkParserHelper::TmpArgs</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparserhelper/#a01fa10e16ec7e17fb31b0b8934de7ea9">llvm::remarks::BitstreamRemarkParserHelper::Type</a> and <a href="#aae71b1adcbe2ef2bdde5e8163a1d0349">unknownRecord</a>.</p>

</div>
</div>

### processRemarkVersion() {#a37c014ff1e40aad67d394566e65800bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error processRemarkVersion (<a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparser">BitstreamRemarkParser</a> &amp; P, std::optional&lt; uint64_t &gt; RemarkVersion)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### processStrTab() {#aab380b488629f55df87400a566043f37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error processStrTab (<a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparser">BitstreamRemarkParser</a> &amp; P, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; StrTabBuf)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### unknownRecord() {#aae71b1adcbe2ef2bdde5e8163a1d0349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error unknownRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * BlockName, unsigned RecordID)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>.</p>


<p>Referenced by <a href="#a614e714a8963e8f854ecac210dde3125">parseRecord</a> and <a href="#a384d242ae8d66e4ea84344784426e3a7">parseRecord</a>.</p>

</div>
</div>

### validateMagicNumber() {#a6062a9632d9d9c4d35afd3e82970887e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error validateMagicNumber (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> MagicNumber)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp">BitstreamRemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#acc638ffc46bd235e04176e244948a300">llvm::remarks::ContainerMagic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#ae7a2a8c8926efbbd98b5e02b989d58bf">advanceToMetaBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a2d4315e24acdc204396b98bcc90a1399">llvm::remarks::createBitstreamParserFromMeta</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
