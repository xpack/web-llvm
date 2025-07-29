---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jamcrc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `JamCRC` Class



## Declaration

<div class="doxyDeclaration">
class llvm::JamCRC { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crc-h">llvm/Support/CRC.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfdc2599e8f94e4ca9d49f6b7d2a54ec">JamCRC</a> (uint32_t Init=0xFFFFFFFFU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4c43564c4a47b6d9741736e3962e279">update</a> (ArrayRef&lt; uint8_t &gt; Data)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90e799935e361788dee83dfb9b2d5099">getCRC</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae650b7ae1b5e20b24fd1f86249dd3e5f">CRC</a></td>
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


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crc-h">CRC.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### JamCRC() {#abfdc2599e8f94e4ca9d49f6b7d2a54ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::JamCRC::JamCRC (uint32_t Init=0xFFFFFFFFU)</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crc-h">CRC.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCRC() {#a90e799935e361788dee83dfb9b2d5099}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::JamCRC::getCRC ()</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crc-h">CRC.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/blockcoverageinference/#a09b2833329e8e77c280ce50d1f6f560e">llvm::BlockCoverageInference::getInstrumentedBlocksHash</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a70e7a3749d35a58e1620b36a1a4183c1">llvm::pdb::hashBufferV8</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a69bf231aca848ed614fb954ea4d65ff2">llvm::pdb::hashTypeRecord</a>.</p>

</div>
</div>

### update() {#af4c43564c4a47b6d9741736e3962e279}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void JamCRC::update (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crc-h">CRC.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crc-cpp">CRC.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9b39f29a121496d294af31158c65740b">llvm::crc32</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/blockcoverageinference/#a09b2833329e8e77c280ce50d1f6f560e">llvm::BlockCoverageInference::getInstrumentedBlocksHash</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a70e7a3749d35a58e1620b36a1a4183c1">llvm::pdb::hashBufferV8</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a69bf231aca848ed614fb954ea4d65ff2">llvm::pdb::hashTypeRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CRC {#ae650b7ae1b5e20b24fd1f86249dd3e5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::JamCRC::CRC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crc-h">CRC.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crc-h">CRC.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/crc-cpp">CRC.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
