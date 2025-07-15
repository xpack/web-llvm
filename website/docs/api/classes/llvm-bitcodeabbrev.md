---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/bitcodeabbrev
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BitCodeAbbrev` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrev">BitCodeAbbrev</a> - This class represents an abbreviation record. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BitCodeAbbrev { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitcodes-h">llvm/Bitstream/BitCodes.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af24573416131d18b7f37bba85f7deac5">BitCodeAbbrev</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f48b6c9af682e45902defcf34067b76">BitCodeAbbrev</a> (std::initializer_list&lt; BitCodeAbbrevOp &gt; OperandList)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ca29bb80c1ac943509a6d7e3cf613e2">getNumOperandInfos</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop">BitCodeAbbrevOp</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99bd594ca88426eba9b6581d9f292766">getOperandInfo</a> (unsigned N) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9725f01774c8e2c6748fec5c57439b63">Add</a> (const BitCodeAbbrevOp &amp;OpInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop">BitCodeAbbrevOp</a>, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fd2a08a3e2fb6ca4fe3a16400d7803c">OperandList</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrev">BitCodeAbbrev</a> - This class represents an abbreviation record.</p>


<p>An abbreviation allows a complex record that has redundancy to be stored in a specialized format instead of the fully-general, fully-vbr, format.</p>


<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitcodes-h">BitCodes.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BitCodeAbbrev() {#af24573416131d18b7f37bba85f7deac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitCodeAbbrev::BitCodeAbbrev ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitcodes-h">BitCodes.h</a>.</p>

</div>
</div>

### BitCodeAbbrev() {#a0f48b6c9af682e45902defcf34067b76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitCodeAbbrev::BitCodeAbbrev (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop">BitCodeAbbrevOp</a> &gt; OperandList)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitcodes-h">BitCodes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Add() {#a9725f01774c8e2c6748fec5c57439b63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitCodeAbbrev::Add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop">BitCodeAbbrevOp</a> &amp; OpInfo)</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitcodes-h">BitCodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bcarray/#ab6ac0fabd6449680e3eda2025d1a50ec">llvm::BCArray&lt; ElementTy &gt;::emitOp</a>, <a href="/web-llvm/docs/api/classes/llvm/bcblob/#aa7f7ef55083b0adc089a39f5c6b4e284">llvm::BCBlob::emitOp</a>, <a href="/web-llvm/docs/api/classes/llvm/bcchar6/#ac6026e5a353841acb51d7c14284b25b3">llvm::BCChar6::emitOp</a>, <a href="/web-llvm/docs/api/classes/llvm/bcfixed/#a4bcdfe9e4c30c74586f9a5c3ac0e15ba">llvm::BCFixed&lt; Width &gt;::emitOp</a>, <a href="/web-llvm/docs/api/classes/llvm/bcliteral/#a613aadda0e36b9beacdcbc168cb206e4">llvm::BCLiteral&lt; Value &gt;::emitOp</a> and <a href="/web-llvm/docs/api/classes/llvm/bcvbr/#aa008880c615fd500ba15ebfdc91bb0e7">llvm::BCVBR&lt; Width &gt;::emitOp</a>.</p>

</div>
</div>

### getNumOperandInfos() {#a2ca29bb80c1ac943509a6d7e3cf613e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BitCodeAbbrev::getNumOperandInfos ()</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitcodes-h">BitCodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a677592abe148dbc3de1ec00f3d9904c5">llvm::BitstreamCursor::readRecord</a> and <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a8b13d5acaf9ffcc5a0f9969888a7db33">llvm::BitstreamCursor::skipRecord</a>.</p>

</div>
</div>

### getOperandInfo() {#a99bd594ca88426eba9b6581d9f292766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BitCodeAbbrevOp &amp; llvm::BitCodeAbbrev::getOperandInfo (unsigned N)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitcodes-h">BitCodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a677592abe148dbc3de1ec00f3d9904c5">llvm::BitstreamCursor::readRecord</a> and <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a8b13d5acaf9ffcc5a0f9969888a7db33">llvm::BitstreamCursor::skipRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### OperandList {#a8fd2a08a3e2fb6ca4fe3a16400d7803c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;BitCodeAbbrevOp, 32&gt; llvm::BitCodeAbbrev::OperandList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitcodes-h">BitCodes.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitcodes-h">BitCodes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
