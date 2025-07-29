---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-coveragemappingreader-cpp-/versionedcovmapfuncrecordreader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VersionedCovMapFuncRecordReader` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;
class anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt;Version, IntPtrT, Endian&gt; { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-coveragemappingreader-cpp-/covmapfuncrecordreader">CovMapFuncRecordReader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The interface to read coverage mapping function records for a module. <a href="/web-llvm/docs/api/structs/anonymous-coveragemappingreader-cpp-/covmapfuncrecordreader/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a998ea9ab993566f63f7822b852e9f0b3">FuncRecordType</a> = typename <a href="/web-llvm/docs/api/structs/llvm/coverage/covmaptraits">CovMapTraits</a>&lt; Version, IntPtrT &gt;::CovMapFuncRecordType</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26c516cca06f7a625bb063d4540cdaf9">NameRefType</a> = typename <a href="/web-llvm/docs/api/structs/llvm/coverage/covmaptraits">CovMapTraits</a>&lt; Version, IntPtrT &gt;::NameRefType</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#adfdbc9f15d9551e7cf191b05cb5675a8">VersionedCovMapFuncRecordReader</a> (InstrProfSymtab &amp;P, std::vector&lt; BinaryCoverageReader::ProfileMappingRecord &gt; &amp;R, StringRef D, std::vector&lt; std::string &gt; &amp;F)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ad4de3e194aac24746663035cd67b2da1">~VersionedCovMapFuncRecordReader</a> () override=default</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8c67cee70433798d45a0759d4fddad92">readCoverageHeader</a> (const char *CovBuf, const char *CovBufEnd) override -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7e1679b2628896a1b7e2299c92776503">readFunctionRecords</a> (const char *FuncRecBuf, const char *FuncRecBufEnd, std::optional&lt; FilenameRange &gt; OutOfLineFileRange, const char *OutOfLineMappingBuf, const char *OutOfLineMappingBufEnd) override</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4694095b147e964ba8a8fb0e65690bd0">insertFunctionRecordIfNeeded</a> (const FuncRecordType *CFR, StringRef Mapping, FilenameRange FileRange)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; NameRefType, size_t &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ada770b76eba2a19af40f89babbad6760">FunctionRecords</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0fb8eee386f255f2c032d05c1ee24582">ProfileNames</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a210dcf83c7d0876a36d7648ac320205c">CompilationDir</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::vector&lt; std::string &gt; &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac84e1108060aed56ebe14726c6dc2a4c">Filenames</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/binarycoveragereader/profilemappingrecord">BinaryCoverageReader::ProfileMappingRecord</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad7e811f464f7cb5b116fd763f84c73f6">Records</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/structs/filenamerange">FilenameRange</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a373f3e5c5e9e57abfcd34a835eb43df3">FileRangeMap</a></td>
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


<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### FuncRecordType {#a998ea9ab993566f63f7822b852e9f0b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::FuncRecordType = 
      typename CovMapTraits&lt;Version, IntPtrT&gt;::CovMapFuncRecordType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 594 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>

</div>
</div>

### NameRefType {#a26c516cca06f7a625bb063d4540cdaf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::NameRefType =  typename CovMapTraits&lt;Version, IntPtrT&gt;::NameRefType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VersionedCovMapFuncRecordReader() {#adfdbc9f15d9551e7cf191b05cb5675a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::VersionedCovMapFuncRecordReader (<a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> &amp; P, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/binarycoveragereader/profilemappingrecord">BinaryCoverageReader::ProfileMappingRecord</a> &gt; &amp; R, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> D, std::vector&lt; std::string &gt; &amp; F)</td>
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



<p>Definition at line 661 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VersionedCovMapFuncRecordReader() {#ad4de3e194aac24746663035cd67b2da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::~VersionedCovMapFuncRecordReader ()</td>
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



<p>Definition at line 667 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### readCoverageHeader() {#a8c67cee70433798d45a0759d4fddad92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const char * &gt; anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::readCoverageHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CovBuf, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CovBufEnd)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 669 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/indexedinstrprof/#a26647986f25d6168afc4204fd79873df">llvm::IndexedInstrProf::ComputeHash</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a36651fd9f7261a163f7b43e208e5a9b3">llvm::CoverageSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22dd9498509fb83a7a82d8c8f1b2d41e">llvm::FilenamesSize</a>, <a href="/web-llvm/docs/api/structs/filenamerange/#a37475eae00e558a1d7ebc8c116234fc4">FilenameRange::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#ab7cd3c4d014c0e03d0e0dbcc94c192e6a7596fdd04dba990373ab2f3da0c7dd3f">llvm::coverage::malformed</a>, <a href="/web-llvm/docs/api/structs/filenamerange/#a73a47c0a9dcaef4e805c51df3d33920c">FilenameRange::markInvalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae3d5e0ec9e672d782ec89ff9296efc69">llvm::NRecords</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b564a3b7523ad942e2df7aceec2d17d">llvm::offsetToAlignedAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragefilenamesreader/#ab1e2363d08ff779aade90747e730bfd9">llvm::coverage::RawCoverageFilenamesReader::read</a>, <a href="#a7e1679b2628896a1b7e2299c92776503">anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::readFunctionRecords</a>, <a href="/web-llvm/docs/api/structs/filenamerange/#a26e5dea7580e45a5d1c881aa92f93972">FilenameRange::StartingIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a1f74a57a4d0c2ea7ebb8fb8767d66000a5462463e282d6c019363628ddaebbf3c">llvm::coverage::Version4</a>.</p>

</div>
</div>

### readFunctionRecords() {#a7e1679b2628896a1b7e2299c92776503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::readFunctionRecords (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * FuncRecBuf, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * FuncRecBufEnd, std::optional&lt; <a href="/web-llvm/docs/api/structs/filenamerange">FilenameRange</a> &gt; OutOfLineFileRange, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * OutOfLineMappingBuf, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * OutOfLineMappingBufEnd)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 762 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#ab7cd3c4d014c0e03d0e0dbcc94c192e6a7596fdd04dba990373ab2f3da0c7dd3f">llvm::coverage::malformed</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a1f74a57a4d0c2ea7ebb8fb8767d66000a5462463e282d6c019363628ddaebbf3c">llvm::coverage::Version4</a>.</p>


<p>Referenced by <a href="#a8c67cee70433798d45a0759d4fddad92">anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::readCoverageHeader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### insertFunctionRecordIfNeeded() {#a4694095b147e964ba8a8fb0e65690bd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::insertFunctionRecordIfNeeded (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncRecordType * CFR, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Mapping, <a href="/web-llvm/docs/api/structs/filenamerange">FilenameRange</a> FileRange)</td>
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



<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CompilationDir {#a210dcf83c7d0876a36d7648ac320205c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::CompilationDir</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>

</div>
</div>

### Filenames {#ac84e1108060aed56ebe14726c6dc2a4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::string&gt;&amp; anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::Filenames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>

</div>
</div>

### FileRangeMap {#a373f3e5c5e9e57abfcd34a835eb43df3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;uint64_t, FilenameRange&gt; anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::FileRangeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>

</div>
</div>

### FunctionRecords {#ada770b76eba2a19af40f89babbad6760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;NameRefType, size_t&gt; anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::FunctionRecords</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>

</div>
</div>

### ProfileNames {#a0fb8eee386f255f2c032d05c1ee24582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfSymtab&amp; anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::ProfileNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>

</div>
</div>

### Records {#ad7e811f464f7cb5b116fd763f84c73f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;CovMapVersion Version, class IntPtrT, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;BinaryCoverageReader::ProfileMappingRecord&gt;&amp; anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::Records</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
