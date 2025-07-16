---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-coveragemappingreader-cpp-/covmapfuncrecordreader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CovMapFuncRecordReader` Struct Reference

<p>The interface to read coverage mapping function records for a module. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{CoverageMappingReader.cpp}::CovMapFuncRecordReader { ... }
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-coveragemappingreader-cpp-/versionedcovmapfuncrecordreader">VersionedCovMapFuncRecordReader&lt;Version, IntPtrT, Endian&gt;</a></td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73fc9eb4e6d48ebc028e6305be588265">~CovMapFuncRecordReader</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a184d909d3c4938ca927596cef648bacc">readCoverageHeader</a> (const char *CovBuf, const char *CovBufEnd)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a343fc4c3327395488de765179128a960">readFunctionRecords</a> (const char *FuncRecBuf, const char *FuncRecBufEnd, std::optional&lt; FilenameRange &gt; OutOfLineFileRange, const char *OutOfLineMappingBuf, const char *OutOfLineMappingBufEnd)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab608bdea2ae9497800386d62a2c77a1f">get</a> (CovMapVersion Version, InstrProfSymtab &amp;P, std::vector&lt; BinaryCoverageReader::ProfileMappingRecord &gt; &amp;R, StringRef D, std::vector&lt; std::string &gt; &amp;F) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-coveragemappingreader-cpp-/covmapfuncrecordreader">CovMapFuncRecordReader</a> &gt; &gt;</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a438e1dd8389f92a855040fef7e78aaa4">get</a> (CovMapVersion Version, InstrProfSymtab &amp;P, std::vector&lt; BinaryCoverageReader::ProfileMappingRecord &gt; &amp;R, StringRef D, std::vector&lt; std::string &gt; &amp;F) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-coveragemappingreader-cpp-/covmapfuncrecordreader">CovMapFuncRecordReader</a> &gt; &gt;</td>
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

<p>The interface to read coverage mapping function records for a module.</p>

<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~CovMapFuncRecordReader() {#a73fc9eb4e6d48ebc028e6305be588265}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual anonymous{CoverageMappingReader.cpp}::CovMapFuncRecordReader::~CovMapFuncRecordReader ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### get() {#ab608bdea2ae9497800386d62a2c77a1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; CovMapFuncRecordReader &gt; &gt; anonymous{CoverageMappingReader.cpp}::CovMapFuncRecordReader::get (<a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a1f74a57a4d0c2ea7ebb8fb8767d66000">CovMapVersion</a> Version, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> &amp; P, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/binarycoveragereader/profilemappingrecord">BinaryCoverageReader::ProfileMappingRecord</a> &gt; &amp; R, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> D, std::vector&lt; std::string &gt; &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 817 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a1f74a57a4d0c2ea7ebb8fb8767d66000ac87113f1fce86a8944a1e88d61108773">llvm::coverage::Version1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a1f74a57a4d0c2ea7ebb8fb8767d66000a67e333b0689c7d394665875e30c2325e">llvm::coverage::Version2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a1f74a57a4d0c2ea7ebb8fb8767d66000a92655f7feff4c4b05206ebde377063bb">llvm::coverage::Version3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a1f74a57a4d0c2ea7ebb8fb8767d66000a5462463e282d6c019363628ddaebbf3c">llvm::coverage::Version4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a1f74a57a4d0c2ea7ebb8fb8767d66000a3fe9f5e5b0f3ae1e6fd219d43963a805">llvm::coverage::Version5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a1f74a57a4d0c2ea7ebb8fb8767d66000aee9f0ed431e9615b6b541e8cff42abf1">llvm::coverage::Version6</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a1f74a57a4d0c2ea7ebb8fb8767d66000a8ccd4bfeb157b968ada04b5095c029b3">llvm::coverage::Version7</a>.</p>

</div>
</div>

### readCoverageHeader() {#a184d909d3c4938ca927596cef648bacc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; const char * &gt; anonymous{CoverageMappingReader.cpp}::CovMapFuncRecordReader::readCoverageHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CovBuf, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CovBufEnd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>

</div>
</div>

### readFunctionRecords() {#a343fc4c3327395488de765179128a960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error anonymous{CoverageMappingReader.cpp}::CovMapFuncRecordReader::readFunctionRecords (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * FuncRecBuf, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * FuncRecBufEnd, std::optional&lt; <a href="/web-llvm/docs/api/structs/filenamerange">FilenameRange</a> &gt; OutOfLineFileRange, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * OutOfLineMappingBuf, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * OutOfLineMappingBufEnd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#a438e1dd8389f92a855040fef7e78aaa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; CovMapFuncRecordReader &gt; &gt; anonymous{CoverageMappingReader.cpp}::CovMapFuncRecordReader::get (<a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a1f74a57a4d0c2ea7ebb8fb8767d66000">CovMapVersion</a> Version, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> &amp; P, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/binarycoveragereader/profilemappingrecord">BinaryCoverageReader::ProfileMappingRecord</a> &gt; &amp; R, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> D, std::vector&lt; std::string &gt; &amp; F)</td>
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



<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp/#a10b27eac23635b8f40370fe8a4d19967">readCoverageMappingData</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
