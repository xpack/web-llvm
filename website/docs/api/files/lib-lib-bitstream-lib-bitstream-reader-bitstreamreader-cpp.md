---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/bitstream/lib/bitstream/reader/bitstreamreader-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `BitstreamReader.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">llvm/Bitstream/BitstreamReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include &lt;cassert&gt;
#include &lt;optional&gt;
#include &lt;string&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a616042a5d0c25160868506a6162aa590">error</a> (const char *Message)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f3f6e32f057400eb4132cecf266c4c3">readAbbreviatedField</a> (BitstreamCursor &amp;Cursor, const BitCodeAbbrevOp &amp;Op)</td>
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

### error() {#a616042a5d0c25160868506a6162aa590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error error (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Message)</td>
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



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/bitstream/lib/bitstream/reader/bitstreamreader-cpp">BitstreamReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>.</p>

</div>
</div>

### readAbbreviatedField() {#a0f3f6e32f057400eb4132cecf266c4c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; readAbbreviatedField (<a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp; Cursor, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop">BitCodeAbbrevOp</a> &amp; Op)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/bitstream/lib/bitstream/reader/bitstreamreader-cpp">BitstreamReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672ac45cef5b964b589fb0741ccc577eaf2c">llvm::BitCodeAbbrevOp::Array</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672a35cc66c7fc730d5572ae851efc3f3f47">llvm::BitCodeAbbrevOp::Blob</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672a5a7811cd25e6ed838a03c49776237b4a">llvm::BitCodeAbbrevOp::Char6</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#adcc0f2fa34728fc1a9d84a554d68b8e5">llvm::BitCodeAbbrevOp::DecodeChar6</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672abfdef4054ace82e3ddb8794bc5ca471c">llvm::BitCodeAbbrevOp::Fixed</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a3c466b40cd38391f58d202c44f9d04f4">llvm::BitstreamCursor::MaxChunkSize</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a455d3003d7f58d83850c9f33c259d3bf">llvm::BitstreamCursor::Read</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a24cc6d3ef39604b4b923083583efe349">llvm::BitstreamCursor::ReadVBR64</a> and <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672ade2457e8051855ad2911d62202458e20">llvm::BitCodeAbbrevOp::VBR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a677592abe148dbc3de1ec00f3d9904c5">llvm::BitstreamCursor::readRecord</a> and <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a8b13d5acaf9ffcc5a0f9969888a7db33">llvm::BitstreamCursor::skipRecord</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
