---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/bitcodeanalyzer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BitcodeAnalyzer` Class



## Declaration

<div class="doxyDeclaration">
class llvm::BitcodeAnalyzer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeanalyzer-h">llvm/Bitcode/BitcodeAnalyzer.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbf4b3f2a6ff52fa62c2a038be90a0d6">BitcodeAnalyzer</a> (StringRef Buffer, std::optional&lt; StringRef &gt; BlockInfoBuffer=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add391ff06a593c4b9cb8f05b23882a51">analyze</a> (std::optional&lt; BCDumpOptions &gt; O=std::nullopt, std::optional&lt; StringRef &gt; CheckHash=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze the bitcode file. <a href="#add391ff06a593c4b9cb8f05b23882a51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaad4f1a2df47f25ea7e274d175c1b4e">printStats</a> (BCDumpOptions O, std::optional&lt; StringRef &gt; Filename=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print stats about the bitcode file. <a href="#aeaad4f1a2df47f25ea7e274d175c1b4e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae82cebf206024c85f5e7360869a5b5f3">parseBlock</a> (unsigned BlockID, unsigned IndentLevel, std::optional&lt; BCDumpOptions &gt; O=std::nullopt, std::optional&lt; StringRef &gt; CheckHash=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read a block, updating statistics, etc. <a href="#ae82cebf206024c85f5e7360869a5b5f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a470f5d771adb4e2cbdf31446be93d22d">decodeMetadataStringsBlob</a> (StringRef Indent, ArrayRef&lt; uint64_t &gt; Record, StringRef Blob, raw_ostream &amp;OS)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a435a4b7c635bc4cb95cdd550cd1b521a">Stream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitstreamblockinfo">BitstreamBlockInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9088b675723829deb11cc6760351e6ff">BlockInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ab313f8a023b8259fb27cc18af0d999d3">CurStreamTypeType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acecb087fd071bfbe4e65de0312ff8c02">CurStreamType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6fcb0f6ed10b9cf5ef17641ba1f20ce">BlockInfoStream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5097181609a8f6a2ca85f3e6dc989252">NumTopBlocks</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; unsigned, PerBlockIDStats &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad21f797dd9407031e0fb62627713d8ff">BlockIDStats</a></td>
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


<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeanalyzer-h">BitcodeAnalyzer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BitcodeAnalyzer() {#abbf4b3f2a6ff52fa62c2a038be90a0d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitcodeAnalyzer::BitcodeAnalyzer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; BlockInfoBuffer=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeanalyzer-h">BitcodeAnalyzer.h</a>, definition at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp">BitcodeAnalyzer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### analyze() {#add391ff06a593c4b9cb8f05b23882a51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BitcodeAnalyzer::analyze (std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/bcdumpoptions">BCDumpOptions</a> &gt; O=std::nullopt, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; CheckHash=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze the bitcode file.</p>

<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeanalyzer-h">BitcodeAnalyzer.h</a>, definition at line 572 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp">BitcodeAnalyzer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#aebcf13b2162f23607396fffbf2b6ef7e">analyzeHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a0b2540236df88a84a8b8ea3f7158ae47">llvm::BitstreamCursor::AtEndOfStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a8cd4dd534ba6c31e93a88ca286c4f0e5a9c269366c4dc4af235c9bb24fa46f915">llvm::bitc::BLOCKINFO_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#ab7a76f80792b96a4291e2d1dd1403887a8ade579114e64f6e93e5c2335d9790b3">llvm::bitc::ENTER_SUBBLOCK</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#aca82144243a4bbb08d09c0c72d636bd1">llvm::BitstreamCursor::ReadBlockInfoBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#aa6e15164c86a2bbfb1cc735578788810">llvm::BitstreamCursor::ReadCode</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a2f0e780a42d43b287c0b9c4208499369">llvm::BitstreamCursor::ReadSubBlockID</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#aecb8af888c92e0b415ae5021d9c7a59a">reportError</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a73257c6f5ab8032f22e06c1da0bc109f">llvm::BitstreamCursor::SkipBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### printStats() {#aeaad4f1a2df47f25ea7e274d175c1b4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitcodeAnalyzer::printStats (<a href="/web-llvm/docs/api/structs/llvm/bcdumpoptions">BCDumpOptions</a> O, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Filename=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print stats about the bitcode file.</p>

<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeanalyzer-h">BitcodeAnalyzer.h</a>, definition at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp">BitcodeAnalyzer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab313f8a023b8259fb27cc18af0d999d3ad79dda94ab5cce4dd8c7c36d833f77c2">llvm::ClangSerializedASTBitstream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab313f8a023b8259fb27cc18af0d999d3a6cf666b14a022d64dec209e643149350">llvm::ClangSerializedDiagnosticsBitstream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#a1a61b4058a0d8fdb477afc3020adee5b">GetBlockName</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#ad0ea28d901a2351fedec9ef3deec2663">GetCodeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab313f8a023b8259fb27cc18af0d999d3adbcc2ed1fc45de2b53775e8bc8a748e1">llvm::LLVMBitstreamRemarks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab313f8a023b8259fb27cc18af0d999d3ac2f3b5457891c08d4e42919a16542475">llvm::LLVMIRBitstream</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#ad53301988259f6d90d009aedb2caf8d1">printSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a086f939e29b718dc5a01e4bcfe6af2a1">Stats</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab313f8a023b8259fb27cc18af0d999d3a58a116f7665129a297e7d7135bcd0853">llvm::UnknownBitstream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### decodeMetadataStringsBlob() {#a470f5d771adb4e2cbdf31446be93d22d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BitcodeAnalyzer::decodeMetadataStringsBlob (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Indent, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Record, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Blob, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeanalyzer-h">BitcodeAnalyzer.h</a>, definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp">BitcodeAnalyzer.cpp</a>.</p>

</div>
</div>

### parseBlock() {#ae82cebf206024c85f5e7360869a5b5f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BitcodeAnalyzer::parseBlock (unsigned BlockID, unsigned IndentLevel, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/bcdumpoptions">BCDumpOptions</a> &gt; O=std::nullopt, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; CheckHash=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read a block, updating statistics, etc.</p>

<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeanalyzer-h">BitcodeAnalyzer.h</a>, definition at line 742 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp">BitcodeAnalyzer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BlockIDStats {#ad21f797dd9407031e0fb62627713d8ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;unsigned, PerBlockIDStats&gt; llvm::BitcodeAnalyzer::BlockIDStats</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeanalyzer-h">BitcodeAnalyzer.h</a>.</p>

</div>
</div>

### BlockInfo {#a9088b675723829deb11cc6760351e6ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamBlockInfo llvm::BitcodeAnalyzer::BlockInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeanalyzer-h">BitcodeAnalyzer.h</a>.</p>

</div>
</div>

### BlockInfoStream {#aa6fcb0f6ed10b9cf5ef17641ba1f20ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;BitstreamCursor&gt; llvm::BitcodeAnalyzer::BlockInfoStream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeanalyzer-h">BitcodeAnalyzer.h</a>.</p>

</div>
</div>

### CurStreamType {#acecb087fd071bfbe4e65de0312ff8c02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CurStreamTypeType llvm::BitcodeAnalyzer::CurStreamType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeanalyzer-h">BitcodeAnalyzer.h</a>.</p>

</div>
</div>

### NumTopBlocks {#a5097181609a8f6a2ca85f3e6dc989252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BitcodeAnalyzer::NumTopBlocks = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeanalyzer-h">BitcodeAnalyzer.h</a>.</p>

</div>
</div>

### Stream {#a435a4b7c635bc4cb95cdd550cd1b521a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamCursor llvm::BitcodeAnalyzer::Stream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeanalyzer-h">BitcodeAnalyzer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeanalyzer-h">BitcodeAnalyzer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp">BitcodeAnalyzer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
