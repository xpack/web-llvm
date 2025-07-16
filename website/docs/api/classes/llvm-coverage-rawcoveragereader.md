---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/coverage/rawcoveragereader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RawCoverageReader` Class Reference

<p>Base class for the raw coverage mapping and filenames data readers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::coverage::RawCoverageReader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingreader-h">llvm/ProfileData/Coverage/CoverageMappingReader.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragefilenamesreader">RawCoverageFilenamesReader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reader for the raw coverage filenames. <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragefilenamesreader/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragemappingdummychecker">RawCoverageMappingDummyChecker</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the given coverage mapping data is exported for an unused function. <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragemappingdummychecker/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragemappingreader">RawCoverageMappingReader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reader for the raw coverage mapping data. <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragemappingreader/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae072814303bd97e3da2cc91521a5d101">RawCoverageReader</a> (StringRef Data)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca96acd10163f3b8e78eea75ba200fd1">readULEB128</a> (uint64_t &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac41bb2d81feba1123acffc3b1fbe9822">readIntMax</a> (uint64_t &amp;Result, uint64_t MaxPlus1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65df07e7c47afbd5567446dbf28b0d83">readSize</a> (uint64_t &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad324d5af303f97b9842a951c98137931">readString</a> (StringRef &amp;Result)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04fce5a386ab40bd21e742bc2f11a2ef">Data</a></td>
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

<p>Base class for the raw coverage mapping and filenames data readers.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingreader-h">CoverageMappingReader.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### RawCoverageReader() {#ae072814303bd97e3da2cc91521a5d101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::RawCoverageReader::RawCoverageReader (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingreader-h">CoverageMappingReader.h</a>.</p>


<p>Reference <a href="#a04fce5a386ab40bd21e742bc2f11a2ef">Data</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragefilenamesreader/#a446531ff972fdf249d78326a65329568">llvm::coverage::RawCoverageFilenamesReader::RawCoverageFilenamesReader</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragemappingdummychecker/#a2057f23f02d105a15f132ea01e91d132">llvm::coverage::RawCoverageMappingDummyChecker::RawCoverageMappingDummyChecker</a> and <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragemappingreader/#afb362035e30e152968785823faf7fd32">llvm::coverage::RawCoverageMappingReader::RawCoverageMappingReader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### readIntMax() {#ac41bb2d81feba1123acffc3b1fbe9822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error RawCoverageReader::readIntMax (uint64_t &amp; Result, uint64_t MaxPlus1)</td>
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



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingreader-h">CoverageMappingReader.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#ab7cd3c4d014c0e03d0e0dbcc94c192e6a7596fdd04dba990373ab2f3da0c7dd3f">llvm::coverage::malformed</a>, <a href="#aca96acd10163f3b8e78eea75ba200fd1">readULEB128</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragemappingdummychecker/#a02a619697e2e3577af7a448f62bcc728">llvm::coverage::RawCoverageMappingDummyChecker::isDummy</a> and <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragemappingreader/#a6f328f5f8d7e388b876dc55edd2d7da8">llvm::coverage::RawCoverageMappingReader::read</a>.</p>

</div>
</div>

### readSize() {#a65df07e7c47afbd5567446dbf28b0d83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error RawCoverageReader::readSize (uint64_t &amp; Result)</td>
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



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingreader-h">CoverageMappingReader.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<p>References <a href="#a04fce5a386ab40bd21e742bc2f11a2ef">Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#ab7cd3c4d014c0e03d0e0dbcc94c192e6a7596fdd04dba990373ab2f3da0c7dd3f">llvm::coverage::malformed</a>, <a href="#aca96acd10163f3b8e78eea75ba200fd1">readULEB128</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragemappingdummychecker/#a02a619697e2e3577af7a448f62bcc728">llvm::coverage::RawCoverageMappingDummyChecker::isDummy</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragefilenamesreader/#ab1e2363d08ff779aade90747e730bfd9">llvm::coverage::RawCoverageFilenamesReader::read</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragemappingreader/#a6f328f5f8d7e388b876dc55edd2d7da8">llvm::coverage::RawCoverageMappingReader::read</a> and <a href="#ad324d5af303f97b9842a951c98137931">readString</a>.</p>

</div>
</div>

### readString() {#ad324d5af303f97b9842a951c98137931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error RawCoverageReader::readString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Result)</td>
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



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingreader-h">CoverageMappingReader.h</a>, definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<p>References <a href="#a04fce5a386ab40bd21e742bc2f11a2ef">Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="#a65df07e7c47afbd5567446dbf28b0d83">readSize</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### readULEB128() {#aca96acd10163f3b8e78eea75ba200fd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error RawCoverageReader::readULEB128 (uint64_t &amp; Result)</td>
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



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingreader-h">CoverageMappingReader.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<p>References <a href="#a04fce5a386ab40bd21e742bc2f11a2ef">Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3720bbfe79232f7792ab4b969dfbeed0">llvm::decodeULEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#ab7cd3c4d014c0e03d0e0dbcc94c192e6a7596fdd04dba990373ab2f3da0c7dd3f">llvm::coverage::malformed</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#ab7cd3c4d014c0e03d0e0dbcc94c192e6aac273a9aa2a7a6e63ef477fa7f6d1980">llvm::coverage::truncated</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragefilenamesreader/#ab1e2363d08ff779aade90747e730bfd9">llvm::coverage::RawCoverageFilenamesReader::read</a>, <a href="#ac41bb2d81feba1123acffc3b1fbe9822">readIntMax</a> and <a href="#a65df07e7c47afbd5567446dbf28b0d83">readSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Data {#a04fce5a386ab40bd21e742bc2f11a2ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::coverage::RawCoverageReader::Data</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingreader-h">CoverageMappingReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragefilenamesreader/#a446531ff972fdf249d78326a65329568">llvm::coverage::RawCoverageFilenamesReader::RawCoverageFilenamesReader</a>, <a href="#ae072814303bd97e3da2cc91521a5d101">RawCoverageReader</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragefilenamesreader/#ab1e2363d08ff779aade90747e730bfd9">llvm::coverage::RawCoverageFilenamesReader::read</a>, <a href="#a65df07e7c47afbd5567446dbf28b0d83">readSize</a>, <a href="#ad324d5af303f97b9842a951c98137931">readString</a> and <a href="#aca96acd10163f3b8e78eea75ba200fd1">readULEB128</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingreader-h">CoverageMappingReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
