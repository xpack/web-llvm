---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-bitcodereader-cpp-/bitcodereaderbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BitcodeReaderBase` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{BitcodeReader.cpp}::BitcodeReaderBase { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader">BitcodeReader</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader">ModuleSummaryIndexBitcodeReader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to manage reading and parsing function summary index bitcode files/sections. <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a0d125f481ab8e82010f86ab22bc3a3">BitcodeReaderBase</a> (BitstreamCursor Stream, StringRef Strtab)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07768b10e40ef48e376f169fa695357b">parseVersionRecord</a> (ArrayRef&lt; uint64_t &gt; Record)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafd9537e3f52adde4974da00a91cc31a">readNameFromStrtab</a> (ArrayRef&lt; uint64_t &gt; Record)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this module uses a string table, pop the reference to the string table and return the referenced string and the rest of the record. <a href="#aafd9537e3f52adde4974da00a91cc31a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad04f7d6a08ad25b673e16a64825f640c">readBlockInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aa88beff46b705033cfc09293ba298a">error</a> (const Twine &amp;Message)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitstreamblockinfo">BitstreamBlockInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3644024aaeaa32d9ea0790cba19a4521">BlockInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad08058cbd0be023ecb41322986993cd7">Stream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a591454abad1d73b04a12f610819bd8a9">Strtab</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39904e89e51e7aeb6242100c6d008178">UseStrtab</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In version 2 of the bitcode we store names of global values and comdats in a string table rather than in the VST. <a href="#a39904e89e51e7aeb6242100c6d008178">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dc983de42ec7ccaf7dddce3a4a696e4">ProducerIdentification</a></td>
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


<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### BitcodeReaderBase() {#a5a0d125f481ab8e82010f86ab22bc3a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BitcodeReader.cpp}::BitcodeReaderBase::BitcodeReaderBase (<a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> Stream, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Strtab)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="#a3644024aaeaa32d9ea0790cba19a4521">BlockInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a61af784d0feec1cac2175f4d3b4aeb6f">llvm::BitstreamCursor::setBlockInfo</a>, <a href="#ad08058cbd0be023ecb41322986993cd7">Stream</a> and <a href="#a591454abad1d73b04a12f610819bd8a9">Strtab</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#a5a5e39178a2a06d4c19b77650aa23b33">anonymous{BitcodeReader.cpp}::BitcodeReader::BitcodeReader</a> and <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader/#a0f120c3d0b6eac0bf0e5969e53e47fed">anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::ModuleSummaryIndexBitcodeReader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### error() {#a3aa88beff46b705033cfc09293ba298a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BitcodeReaderBase::error (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Message)</td>
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



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="#a5dc983de42ec7ccaf7dddce3a4a696e4">ProducerIdentification</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a>.</p>

</div>
</div>

### parseVersionRecord() {#a07768b10e40ef48e376f169fa695357b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; unsigned &gt; BitcodeReaderBase::parseVersionRecord (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Record)</td>
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



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a> and <a href="#a39904e89e51e7aeb6242100c6d008178">UseStrtab</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader/#ae9f86888a27590c2d447d2f98b5f7cf8">anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::parseModule</a>.</p>

</div>
</div>

### readBlockInfo() {#ad04f7d6a08ad25b673e16a64825f640c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BitcodeReaderBase::readBlockInfo ()</td>
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



<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="#a3644024aaeaa32d9ea0790cba19a4521">BlockInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#ad08058cbd0be023ecb41322986993cd7">Stream</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader/#ae9f86888a27590c2d447d2f98b5f7cf8">anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::parseModule</a>.</p>

</div>
</div>

### readNameFromStrtab() {#aafd9537e3f52adde4974da00a91cc31a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; StringRef, ArrayRef&lt; uint64_t &gt; &gt; BitcodeReaderBase::readNameFromStrtab (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Record)</td>
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

<p>If this module uses a string table, pop the reference to the string table and return the referenced string and the rest of the record.</p>


<p>Otherwise just return the record itself.</p>


<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="#a591454abad1d73b04a12f610819bd8a9">Strtab</a> and <a href="#a39904e89e51e7aeb6242100c6d008178">UseStrtab</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader/#ae9f86888a27590c2d447d2f98b5f7cf8">anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::parseModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### BlockInfo {#a3644024aaeaa32d9ea0790cba19a4521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamBlockInfo anonymous{BitcodeReader.cpp}::BitcodeReaderBase::BlockInfo</td>
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



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>Referenced by <a href="#a5a0d125f481ab8e82010f86ab22bc3a3">BitcodeReaderBase</a> and <a href="#ad04f7d6a08ad25b673e16a64825f640c">readBlockInfo</a>.</p>

</div>
</div>

### ProducerIdentification {#a5dc983de42ec7ccaf7dddce3a4a696e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{BitcodeReader.cpp}::BitcodeReaderBase::ProducerIdentification</td>
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



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#a5a5e39178a2a06d4c19b77650aa23b33">anonymous{BitcodeReader.cpp}::BitcodeReader::BitcodeReader</a> and <a href="#a3aa88beff46b705033cfc09293ba298a">error</a>.</p>

</div>
</div>

### Stream {#ad08058cbd0be023ecb41322986993cd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamCursor anonymous{BitcodeReader.cpp}::BitcodeReaderBase::Stream</td>
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



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#a5a5e39178a2a06d4c19b77650aa23b33">anonymous{BitcodeReader.cpp}::BitcodeReader::BitcodeReader</a>, <a href="#a5a0d125f481ab8e82010f86ab22bc3a3">BitcodeReaderBase</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#a9154b11bdab240adc9c8acd18cf89717">anonymous{BitcodeReader.cpp}::BitcodeReader::materialize</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#aefaf2c952edc95af7870970731295b45">anonymous{BitcodeReader.cpp}::BitcodeReader::materializeMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#a005f50b6325168255c4f8a67ee9b6e33">anonymous{BitcodeReader.cpp}::BitcodeReader::parseBitcodeInto</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader/#ae9f86888a27590c2d447d2f98b5f7cf8">anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::parseModule</a> and <a href="#ad04f7d6a08ad25b673e16a64825f640c">readBlockInfo</a>.</p>

</div>
</div>

### Strtab {#a591454abad1d73b04a12f610819bd8a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{BitcodeReader.cpp}::BitcodeReaderBase::Strtab</td>
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



<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#a5a5e39178a2a06d4c19b77650aa23b33">anonymous{BitcodeReader.cpp}::BitcodeReader::BitcodeReader</a>, <a href="#a5a0d125f481ab8e82010f86ab22bc3a3">BitcodeReaderBase</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader/#a0f120c3d0b6eac0bf0e5969e53e47fed">anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::ModuleSummaryIndexBitcodeReader</a> and <a href="#aafd9537e3f52adde4974da00a91cc31a">readNameFromStrtab</a>.</p>

</div>
</div>

### UseStrtab {#a39904e89e51e7aeb6242100c6d008178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{BitcodeReader.cpp}::BitcodeReaderBase::UseStrtab = false</td>
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

<p>In version 2 of the bitcode we store names of global values and comdats in a string table rather than in the VST.</p>

<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader/#ae9f86888a27590c2d447d2f98b5f7cf8">anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::parseModule</a>, <a href="#a07768b10e40ef48e376f169fa695357b">parseVersionRecord</a> and <a href="#aafd9537e3f52adde4974da00a91cc31a">readNameFromStrtab</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
