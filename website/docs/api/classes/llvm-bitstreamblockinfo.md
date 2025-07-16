---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/bitstreamblockinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BitstreamBlockInfo` Class Reference

<p>This class maintains the abbreviations read from a block info block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BitstreamBlockInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">llvm/Bitstream/BitstreamReader.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bitstreamblockinfo/blockinfo">BlockInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bffe358b2eeea6540e85a510d611f54">getBlockInfo</a> (unsigned BlockID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If there is block info for the specified <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, return it, otherwise return null. <a href="#a0bffe358b2eeea6540e85a510d611f54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bitstreamblockinfo/blockinfo">BlockInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3b3762cda136c6055a813e84957e3a3">getOrCreateBlockInfo</a> (unsigned BlockID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/bitstreamblockinfo/blockinfo">BlockInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba4ff0d3107abef4ff7fce62f012064a">BlockInfoRecords</a></td>
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

<p>This class maintains the abbreviations read from a block info block.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getBlockInfo() {#a0bffe358b2eeea6540e85a510d611f54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BlockInfo * llvm::BitstreamBlockInfo::getBlockInfo (unsigned BlockID)</td>
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

<p>If there is block info for the specified <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, return it, otherwise return null.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#a1a61b4058a0d8fdb477afc3020adee5b">GetBlockName</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#ad0ea28d901a2351fedec9ef3deec2663">GetCodeName</a> and <a href="#aa3b3762cda136c6055a813e84957e3a3">getOrCreateBlockInfo</a>.</p>

</div>
</div>

### getOrCreateBlockInfo() {#aa3b3762cda136c6055a813e84957e3a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockInfo &amp; llvm::BitstreamBlockInfo::getOrCreateBlockInfo (unsigned BlockID)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bitstreamblockinfo/blockinfo/#ab6be35664fc6ca0bcb84e05c87cef312">llvm::BitstreamBlockInfo::BlockInfo::BlockID</a> and <a href="#a0bffe358b2eeea6540e85a510d611f54">getBlockInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#aca82144243a4bbb08d09c0c72d636bd1">llvm::BitstreamCursor::ReadBlockInfoBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BlockInfoRecords {#aba4ff0d3107abef4ff7fce62f012064a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;BlockInfo&gt; llvm::BitstreamBlockInfo::BlockInfoRecords</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
