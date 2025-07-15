---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/coverage/rawcoveragefilenamesreader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RawCoverageFilenamesReader` Class Reference

<p>Reader for the raw coverage filenames. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::coverage::RawCoverageFilenamesReader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingreader-h">llvm/ProfileData/Coverage/CoverageMappingReader.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragereader">RawCoverageReader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for the raw coverage mapping and filenames data readers. <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragereader/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a446531ff972fdf249d78326a65329568">RawCoverageFilenamesReader</a> (StringRef Data, std::vector&lt; std::string &gt; &amp;Filenames, StringRef CompilationDir="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3131fe3f878fec54fc3a785261e84a1">RawCoverageFilenamesReader</a> (const RawCoverageFilenamesReader &amp;)=delete</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragefilenamesreader">RawCoverageFilenamesReader</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc1f91edc95373890d3c5f40788b2cdb">operator=</a> (const RawCoverageFilenamesReader &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1e2363d08ff779aade90747e730bfd9">read</a> (CovMapVersion Version)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a497653e09263da740aaf8647685af972">readUncompressed</a> (CovMapVersion Version, uint64_t NumFilenames)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a479d5f2957d0ca8b5a346295804a1e52">Filenames</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d635cba7c10c8551eeccb9cd5d84b9b">CompilationDir</a></td>
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

<p>Reader for the raw coverage filenames.</p>

<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingreader-h">CoverageMappingReader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RawCoverageFilenamesReader() {#a446531ff972fdf249d78326a65329568}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::RawCoverageFilenamesReader::RawCoverageFilenamesReader (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data, std::vector&lt; std::string &gt; &amp; Filenames, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CompilationDir="")</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingreader-h">CoverageMappingReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragereader/#a04fce5a386ab40bd21e742bc2f11a2ef">llvm::coverage::RawCoverageReader::Data</a> and <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragereader/#ae072814303bd97e3da2cc91521a5d101">llvm::coverage::RawCoverageReader::RawCoverageReader</a>.</p>


<p>Referenced by <a href="#afc1f91edc95373890d3c5f40788b2cdb">operator=</a>, <a href="#ac3131fe3f878fec54fc3a785261e84a1">RawCoverageFilenamesReader</a> and <a href="#ab1e2363d08ff779aade90747e730bfd9">read</a>.</p>

</div>
</div>

### RawCoverageFilenamesReader() {#ac3131fe3f878fec54fc3a785261e84a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::RawCoverageFilenamesReader::RawCoverageFilenamesReader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragefilenamesreader">RawCoverageFilenamesReader</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingreader-h">CoverageMappingReader.h</a>.</p>


<p>Reference <a href="#a446531ff972fdf249d78326a65329568">RawCoverageFilenamesReader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#afc1f91edc95373890d3c5f40788b2cdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RawCoverageFilenamesReader &amp; llvm::coverage::RawCoverageFilenamesReader::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragefilenamesreader">RawCoverageFilenamesReader</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingreader-h">CoverageMappingReader.h</a>.</p>


<p>References <a href="#a446531ff972fdf249d78326a65329568">RawCoverageFilenamesReader</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### read() {#ab1e2363d08ff779aade90747e730bfd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error RawCoverageFilenamesReader::read (<a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a1f74a57a4d0c2ea7ebb8fb8767d66000">CovMapVersion</a> Version)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingreader-h">CoverageMappingReader.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1b144823e66f38f789fb4909c29b8bec">llvm::arrayRefFromStringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragereader/#a04fce5a386ab40bd21e742bc2f11a2ef">llvm::coverage::RawCoverageReader::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/compression/zlib/#a1f2be1038afa2414d1df3da720de0c55">llvm::compression::zlib::decompress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#ab7cd3c4d014c0e03d0e0dbcc94c192e6a73ad943efe9cf4a2f54364da2bd68049">llvm::coverage::decompression_failed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/compression/zlib/#a369da242fd5c0d70a31ffcd3374a0909">llvm::compression::zlib::isAvailable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#ab7cd3c4d014c0e03d0e0dbcc94c192e6a7596fdd04dba990373ab2f3da0c7dd3f">llvm::coverage::malformed</a>, <a href="#a446531ff972fdf249d78326a65329568">RawCoverageFilenamesReader</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragereader/#a65df07e7c47afbd5567446dbf28b0d83">llvm::coverage::RawCoverageReader::readSize</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragereader/#aca96acd10163f3b8e78eea75ba200fd1">llvm::coverage::RawCoverageReader::readULEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeeb5973ff74c4c4d279e275b34b7ef54">llvm::toStringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a1f74a57a4d0c2ea7ebb8fb8767d66000a5462463e282d6c019363628ddaebbf3c">llvm::coverage::Version4</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-coveragemappingreader-cpp-/versionedcovmapfuncrecordreader/#a8c67cee70433798d45a0759d4fddad92">anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::readCoverageHeader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### readUncompressed() {#a497653e09263da740aaf8647685af972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error RawCoverageFilenamesReader::readUncompressed (<a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a1f74a57a4d0c2ea7ebb8fb8767d66000">CovMapVersion</a> Version, uint64_t NumFilenames)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingreader-h">CoverageMappingReader.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CompilationDir {#a0d635cba7c10c8551eeccb9cd5d84b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::coverage::RawCoverageFilenamesReader::CompilationDir</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingreader-h">CoverageMappingReader.h</a>.</p>

</div>
</div>

### Filenames {#a479d5f2957d0ca8b5a346295804a1e52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::string&gt;&amp; llvm::coverage::RawCoverageFilenamesReader::Filenames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingreader-h">CoverageMappingReader.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
