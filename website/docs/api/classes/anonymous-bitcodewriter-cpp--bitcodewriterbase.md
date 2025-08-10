---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BitcodeWriterBase` Class

<p>Abstract class to manage the bitcode writing, subclassed for each bitcode file type. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{BitcodeWriter.cpp}::BitcodeWriterBase { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/indexbitcodewriter">IndexBitcodeWriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to manage the bitcode writing for a combined index. <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/indexbitcodewriter/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase">ModuleBitcodeWriterBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class to manage the module bitcode writing, currently subclassed for <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter">ModuleBitcodeWriter</a> and <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/thinlinkbitcodewriter">ThinLinkBitcodeWriter</a>. <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad88d45a4534c867c5b0fab73d70f176f">BitcodeWriterBase</a> (BitstreamWriter &amp;Stream, StringTableBuilder &amp;StrtabBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs a <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase">BitcodeWriterBase</a> object that writes to the provided <span class="doxyComputerOutput">Stream</span>. <a href="#ad88d45a4534c867c5b0fab73d70f176f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a505f027441489e465875cc1b95d98b39">writeModuleVersion</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31291fbb3033f9d35b27cc4cd51c90c2">Stream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The stream created and owned by the client. <a href="#a31291fbb3033f9d35b27cc4cd51c90c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25c3139775b4aef5f6a1cb287f304430">StrtabBuilder</a></td>
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

<p>Abstract class to manage the bitcode writing, subclassed for each bitcode file type.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BitcodeWriterBase() {#ad88d45a4534c867c5b0fab73d70f176f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BitcodeWriter.cpp}::BitcodeWriterBase::BitcodeWriterBase (<a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> &amp; Stream, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a> &amp; StrtabBuilder)</td>
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

<p>Constructs a <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase">BitcodeWriterBase</a> object that writes to the provided <span class="doxyComputerOutput">Stream</span>.</p>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="#a31291fbb3033f9d35b27cc4cd51c90c2">Stream</a> and <a href="#a25c3139775b4aef5f6a1cb287f304430">StrtabBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/indexbitcodewriter/#a8723cbabc5c7064728c2fdcc5b14b771">anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::IndexBitcodeWriter</a> and <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase/#a75538db633297fb9c0b91ea5a16c5b72">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::ModuleBitcodeWriterBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### writeModuleVersion() {#a505f027441489e465875cc1b95d98b39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{BitcodeWriter.cpp}::BitcodeWriterBase::writeModuleVersion ()</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a9d51b2066d2ce0b9fe4f39f1a80f7c81a163b11eb41c06566dbc6e03e9273cc59">llvm::bitc::MODULE_CODE_VERSION</a> and <a href="#a31291fbb3033f9d35b27cc4cd51c90c2">Stream</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/indexbitcodewriter/#aaade9f75fd9ed6de54fefd2d0e0bb2e8">anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::write</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter/#a3ad01919d5d625704d2d69f86d3136b2">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriter::write</a> and <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/thinlinkbitcodewriter/#a2cf0ff7f0ad397fc8d9799b9e0747b90">anonymous{BitcodeWriter.cpp}::ThinLinkBitcodeWriter::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Stream {#a31291fbb3033f9d35b27cc4cd51c90c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamWriter&amp; anonymous{BitcodeWriter.cpp}::BitcodeWriterBase::Stream</td>
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

<p>The stream created and owned by the client.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>Referenced by <a href="#ad88d45a4534c867c5b0fab73d70f176f">BitcodeWriterBase</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/indexbitcodewriter/#a8723cbabc5c7064728c2fdcc5b14b771">anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::IndexBitcodeWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter/#ab776cf27f2a3afc4627ca879136a9377">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriter::ModuleBitcodeWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase/#a75538db633297fb9c0b91ea5a16c5b72">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::ModuleBitcodeWriterBase</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/thinlinkbitcodewriter/#a22a9b53882754492e326c9b7b2f5f4d5">anonymous{BitcodeWriter.cpp}::ThinLinkBitcodeWriter::ThinLinkBitcodeWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/indexbitcodewriter/#aaade9f75fd9ed6de54fefd2d0e0bb2e8">anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::write</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter/#a3ad01919d5d625704d2d69f86d3136b2">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriter::write</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/thinlinkbitcodewriter/#a2cf0ff7f0ad397fc8d9799b9e0747b90">anonymous{BitcodeWriter.cpp}::ThinLinkBitcodeWriter::write</a>, <a href="#a505f027441489e465875cc1b95d98b39">writeModuleVersion</a> and <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase/#ad8b12ebb23f57815dfdaa7a14562aa5f">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::writePerModuleGlobalValueSummary</a>.</p>

</div>
</div>

### StrtabBuilder {#a25c3139775b4aef5f6a1cb287f304430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder&amp; anonymous{BitcodeWriter.cpp}::BitcodeWriterBase::StrtabBuilder</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>Referenced by <a href="#ad88d45a4534c867c5b0fab73d70f176f">BitcodeWriterBase</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/indexbitcodewriter/#a8723cbabc5c7064728c2fdcc5b14b771">anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::IndexBitcodeWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter/#ab776cf27f2a3afc4627ca879136a9377">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriter::ModuleBitcodeWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase/#a75538db633297fb9c0b91ea5a16c5b72">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::ModuleBitcodeWriterBase</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/thinlinkbitcodewriter/#a22a9b53882754492e326c9b7b2f5f4d5">anonymous{BitcodeWriter.cpp}::ThinLinkBitcodeWriter::ThinLinkBitcodeWriter</a> and <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase/#ad8b12ebb23f57815dfdaa7a14562aa5f">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::writePerModuleGlobalValueSummary</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
