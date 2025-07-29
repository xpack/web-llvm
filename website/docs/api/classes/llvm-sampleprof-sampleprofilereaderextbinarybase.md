---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SampleProfileReaderExtBinaryBase` Class

<p>SampleProfileReaderExtBinaryBase/SampleProfileWriterExtBinaryBase defines the basic structure of the extensible binary format. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sampleprof::SampleProfileReaderExtBinaryBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">llvm/ProfileData/SampleProfReader.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary">SampleProfileReaderBinary</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinary">SampleProfileReaderExtBinary</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6ffdd6df239a2e84804f57c4b7c7317">SampleProfileReaderExtBinaryBase</a> (std::unique_ptr&lt; MemoryBuffer &gt; B, LLVMContext &amp;C, SampleProfileFormat Format)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3075229a3db86f1b533efcc85f82d97">readImpl</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read sample profiles in extensible format from the associated file. <a href="#aa3075229a3db86f1b533efcc85f82d97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a192f65175b8cab2ec3ce9ff6bfd38ebb">getSectionSize</a> (SecType Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the total size of all <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></span> sections. <a href="#a192f65175b8cab2ec3ce9ff6bfd38ebb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5212e24c2c507eb51d7ad201800cbfc">getFileSize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the total size of header and all sections. <a href="#ae5212e24c2c507eb51d7ad201800cbfc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0f3253a66867b0999fc9d2be549268c">dumpSectionInfo</a> (raw_ostream &amp;OS=dbgs()) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d0cdeb3cf9845558d9577f37fc326b3">collectFuncsFromModule</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect functions with definitions in <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> M. <a href="#a0d0cdeb3cf9845558d9577f37fc326b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profilesymbollist">ProfileSymbolList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa05dfff9baa25b88665df394ec32f5a5">getProfileSymbolList</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f75738be57d967b82567631e51bd545">readSecHdrTableEntry</a> (uint64_t Idx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71d1634305839ada83dff4daee355a95">readSecHdrTable</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58cedb1356bab80647af0fa48bc1750a">readFuncMetadata</a> (bool ProfileHasAttribute, SampleProfileMap &amp;Profiles)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a077db87ff742498d2add620c1a7130db">readFuncMetadata</a> (bool ProfileHasAttribute)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b9e845ee3096f8360407bfa4f0f3d1a">readFuncMetadata</a> (bool ProfileHasAttribute, FunctionSamples *FProfile)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a008cc734a7a06814838c697a958ee982">readFuncOffsetTable</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a727bcceedcf0fe170cb330513c25ab2a">readFuncProfiles</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a873e0df967c1a3a622ee9e25c1a6fa00">readFuncProfiles</a> (const DenseSet&lt; StringRef &gt; &amp;FuncsToUse, SampleProfileMap &amp;Profiles)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79b534a93144bf69a0b42214dc7a62de">readNameTableSec</a> (bool IsMD5, bool FixedLengthMD5)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a272ffb93f3958019735d7a4ef9bf22d2">readCSNameTableSec</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9691c4736a7e6c9c247e997383771f4">readProfileSymbolList</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae375ab166c92c7d215eea3a3f0277d46">readHeader</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read and validate the file header. <a href="#ae375ab166c92c7d215eea3a3f0277d46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab62f4de0484410fceefb50f7f3acb84f">verifySPMagic</a> (uint64_t Magic) override=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0c499972ec35ad7872cbceafa870704">readOneSection</a> (const uint8_t *Start, uint64_t Size, const SecHdrTableEntry &amp;Entry)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3603fe57b2751d6366d8fc860de40078">readCustomSection</a> (const SecHdrTableEntry &amp;Entry)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a749c376568365b892c49529c92ed7499">useFuncOffsetList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine which container <a href="#a008cc734a7a06814838c697a958ee982">readFuncOffsetTable()</a> should populate, the list FuncOffsetList or the map FuncOffsetTable. <a href="#a749c376568365b892c49529c92ed7499">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c72cebeb1e19f6345d0cbea372b7223">decompressSection</a> (const uint8_t *SecStart, const uint64_t SecSize, const uint8_t *&amp;DecompressBuf, uint64_t &amp;DecompressBufSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ad95f5337c96a2fcbe6cee6df1002e9">read</a> (const DenseSet&lt; StringRef &gt; &amp;FuncsToUse, SampleProfileMap &amp;Profiles) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read the profiles on-demand for the given functions. <a href="#a7ad95f5337c96a2fcbe6cee6df1002e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/sampleprof/sechdrtableentry">SecHdrTableEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00abab1c900c6b6eec7e9dcb44d248fb">SecHdrTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profilesymbollist">ProfileSymbolList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a634fd1a32a2d1831d0fc9c8874ca6abc">ProfSymList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a>, uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb05340f4153393eede497cb6210ec53">FuncOffsetTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The table mapping from a function context's <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> to the offset of its FunctionSample towards file start. <a href="#adb05340f4153393eede497cb6210ec53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a>, uint64_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c2242c2960947a793dfd7995fed38d5">FuncOffsetList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list version of FuncOffsetTable. <a href="#a3c2242c2960947a793dfd7995fed38d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bf2495c6c16f17a97e4c69ce4a68ffd">FuncsToUse</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set containing the functions to use when compiling a module. <a href="#a4bf2495c6c16f17a97e4c69ce4a68ffd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50b4a8ef050103d3e796a29054e467dc">Allocator</a></td>
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

<p>SampleProfileReaderExtBinaryBase/SampleProfileWriterExtBinaryBase defines the basic structure of the extensible binary format.</p>


<p>The format is organized in sections except the magic and version number at the beginning. There is a section table before all the sections, and each entry in the table describes the entry type, start, size and attributes. The format in each section is defined by the section itself.</p>


<p>It is easy to add a new section while maintaining the backward compatibility of the profile. Nothing extra needs to be done. If we want to extend an existing section, like add cache misses information in addition to the sample count in the profile body, we can add a new section with the extension and retire the existing section, and we could choose to keep the parser of the old section if we want the reader to be able to read both new and old format profile.</p>


<p>SampleProfileReaderExtBinary/SampleProfileWriterExtBinary define the commonly used sections of a profile in extensible binary format. It is possible to define other types of profile inherited from SampleProfileReaderExtBinaryBase/SampleProfileWriterExtBinaryBase.</p>


<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SampleProfileReaderExtBinaryBase() {#ab6ffdd6df239a2e84804f57c4b7c7317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::SampleProfileReaderExtBinaryBase::SampleProfileReaderExtBinaryBase (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; B, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66ec">SampleProfileFormat</a> Format)</td>
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



<p>Definition at line 818 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a7cddd27e849335a576339995fc8feaa7">llvm::sampleprof::SampleProfileReader::Format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a6e504be88a1ea38cddc31af56ab20fb7">llvm::sampleprof::SampleProfileReaderBinary::SampleProfileReaderBinary</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinary/#a94ba09b9a0e98ad630527780bbd33d12">llvm::sampleprof::SampleProfileReaderExtBinary::SampleProfileReaderExtBinary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### collectFuncsFromModule() {#a0d0cdeb3cf9845558d9577f37fc326b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileReaderExtBinaryBase::collectFuncsFromModule ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect functions with definitions in <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> M.</p>


<p>Return true if the reader has been given a module.</p>


<p>Declaration at line 833 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 840 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a4bf2495c6c16f17a97e4c69ce4a68ffd">FuncsToUse</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa7122a07ea48e47fc71083e68b829003">llvm::sampleprof::FunctionSamples::getCanonicalFnName</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a2be68a56c1386faa6c75baf21a462df7">llvm::sampleprof::SampleProfileReader::M</a>.</p>


<p>Referenced by <a href="#a727bcceedcf0fe170cb330513c25ab2a">readFuncProfiles</a>.</p>

</div>
</div>

### dumpSectionInfo() {#ab0f3253a66867b0999fc9d2be549268c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileReaderExtBinaryBase::dumpSectionInfo (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS=<a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs</a>())</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 829 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1474 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae5212e24c2c507eb51d7ad201800cbfc">getFileSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#aa1579cd3c85df19630fb1ca933b2679c">getSecFlagsStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#adb8cd928bc57ee59a1e5dfb79f023c75">llvm::sampleprof::getSecName</a> and <a href="#a00abab1c900c6b6eec7e9dcb44d248fb">SecHdrTable</a>.</p>

</div>
</div>

### getFileSize() {#ae5212e24c2c507eb51d7ad201800cbfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t SampleProfileReaderExtBinaryBase::getFileSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the total size of header and all sections.</p>

<p>Declaration at line 828 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1411 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>Reference <a href="#a00abab1c900c6b6eec7e9dcb44d248fb">SecHdrTable</a>.</p>


<p>Referenced by <a href="#ab0f3253a66867b0999fc9d2be549268c">dumpSectionInfo</a>.</p>

</div>
</div>

### getProfileSymbolList() {#aa05dfff9baa25b88665df394ec32f5a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; ProfileSymbolList &gt; llvm::sampleprof::SampleProfileReaderExtBinaryBase::getProfileSymbolList ()</td>
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



<p>Definition at line 835 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Reference <a href="#a634fd1a32a2d1831d0fc9c8874ca6abc">ProfSymList</a>.</p>

</div>
</div>

### getSectionSize() {#a192f65175b8cab2ec3ce9ff6bfd38ebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t SampleProfileReaderExtBinaryBase::getSectionSize (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85">SecType</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the total size of all <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></span> sections.</p>

<p>Declaration at line 826 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1402 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="#a00abab1c900c6b6eec7e9dcb44d248fb">SecHdrTable</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### readImpl() {#aa3075229a3db86f1b533efcc85f82d97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderExtBinaryBase::readImpl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read sample profiles in extensible format from the associated file.</p>

<p>Declaration at line 823 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1045 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a317d9b9a39f8213c84429fbf54a7055f">llvm::sampleprof::SampleProfileReader::Buffer</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a09a7b8c381919bc366c86a06bbde0e82">llvm::sampleprof::SampleProfileReaderBinary::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a9204d2f85c4a30d8b6a1040ccb873eed">llvm::sampleprof::SampleProfileReaderBinary::End</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a3efc74fee0efccc34cb5a64de6b1d84a">llvm::sampleprof::hasSecFlag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea7596fdd04dba990373ab2f3da0c7dd3f">llvm::malformed</a>, <a href="#ab0c499972ec35ad7872cbceafa870704">readOneSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a249a6a299581a44359596da9619a4b19a16052b6981a5cb6f18149f985d66ab87">llvm::sampleprof::SecFlagCompress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a249a6a299581a44359596da9619a4b19a303d1d200e078b6e1510e624147dfe0e">llvm::sampleprof::SecFlagFlat</a>, <a href="#a00abab1c900c6b6eec7e9dcb44d248fb">SecHdrTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a3a8cd3b6849f62c8ff4b44233374747d">llvm::sampleprof::SampleProfileReader::SkipFlatProf</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### readCSNameTableSec() {#a272ffb93f3958019735d7a4ef9bf22d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderExtBinaryBase::readCSNameTableSec ()</td>
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



<p>Declaration at line 789 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1203 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a5a0ac3887cefaae1c3266ec449e81a44">llvm::sampleprof::SampleProfileReaderBinary::CSNameTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a528869d42ce7fca106b21792fe00bf0a">isOffsetLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a3a3860c4de3ad5e9bdb9f1b3f6919ba9">llvm::sampleprof::SampleProfileReaderBinary::MD5SampleContextStart</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a76217402d91e07543ae74594c456f0a1">llvm::sampleprof::SampleProfileReaderBinary::MD5SampleContextTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a53cef5334d9e6535928ce4d79e7529e3">llvm::sampleprof::SampleProfileReader::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a253ea7b225121d422aa3378a18dc2030">llvm::sampleprof::SampleProfileReaderBinary::readNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a675409b9aae66c892d13a9ea74cf11c7">llvm::sampleprof::SampleProfileReaderBinary::readStringFromTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>


<p>Referenced by <a href="#ab0c499972ec35ad7872cbceafa870704">readOneSection</a>.</p>

</div>
</div>

### readCustomSection() {#a3603fe57b2751d6366d8fc860de40078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::error_code llvm::sampleprof::SampleProfileReaderExtBinaryBase::readCustomSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sampleprof/sechdrtableentry">SecHdrTableEntry</a> &amp; Entry)</td>
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



<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#ab0c499972ec35ad7872cbceafa870704">readOneSection</a>.</p>

</div>
</div>

### readFuncMetadata() {#a58cedb1356bab80647af0fa48bc1750a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderExtBinaryBase::readFuncMetadata (bool ProfileHasAttribute, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; Profiles)</td>
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



<p>Declaration at line 779 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1304 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a09a7b8c381919bc366c86a06bbde0e82">llvm::sampleprof::SampleProfileReaderBinary::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a9204d2f85c4a30d8b6a1040ccb873eed">llvm::sampleprof::SampleProfileReaderBinary::End</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a0e2d3f775d9437f33d03a025671010a9">llvm::sampleprof::SampleProfileReader::FuncMetadataIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ad117577730085f895045fc7ff90d8fc2">llvm::sampleprof::FunctionSamples::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#aa974f8c265b1f6334ffd5df3507371f3">llvm::sampleprof::SampleContext::getHashCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a3493b1a9313f04d70a4c843d827d42a9">llvm::sampleprof::SampleProfileReader::ProfileHasAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#ad31357a0bab13543c1d9e22e22f33ec4">llvm::sampleprof::SampleProfileReader::Profiles</a>, <a href="#a58cedb1356bab80647af0fa48bc1750a">readFuncMetadata</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>


<p>Referenced by <a href="#a077db87ff742498d2add620c1a7130db">readFuncMetadata</a>, <a href="#a9b9e845ee3096f8360407bfa4f0f3d1a">readFuncMetadata</a>, <a href="#a58cedb1356bab80647af0fa48bc1750a">readFuncMetadata</a> and <a href="#ab0c499972ec35ad7872cbceafa870704">readOneSection</a>.</p>

</div>
</div>

### readFuncMetadata() {#a077db87ff742498d2add620c1a7130db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderExtBinaryBase::readFuncMetadata (bool ProfileHasAttribute)</td>
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



<p>Declaration at line 781 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1325 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a09a7b8c381919bc366c86a06bbde0e82">llvm::sampleprof::SampleProfileReaderBinary::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a9204d2f85c4a30d8b6a1040ccb873eed">llvm::sampleprof::SampleProfileReaderBinary::End</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a0e2d3f775d9437f33d03a025671010a9">llvm::sampleprof::SampleProfileReader::FuncMetadataIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a3493b1a9313f04d70a4c843d827d42a9">llvm::sampleprof::SampleProfileReader::ProfileHasAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#ad31357a0bab13543c1d9e22e22f33ec4">llvm::sampleprof::SampleProfileReader::Profiles</a>, <a href="#a58cedb1356bab80647af0fa48bc1750a">readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a33a776d038d88cf9261e439f16455d50">llvm::sampleprof::SampleProfileReaderBinary::readSampleContextFromTable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>

</div>
</div>

### readFuncMetadata() {#a9b9e845ee3096f8360407bfa4f0f3d1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderExtBinaryBase::readFuncMetadata (bool ProfileHasAttribute, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> * FProfile)</td>
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



<p>Declaration at line 782 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1247 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp/#a5a7ac0d6f6157bfa62400fdc021157dc">Attributes</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a09a7b8c381919bc366c86a06bbde0e82">llvm::sampleprof::SampleProfileReaderBinary::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a9204d2f85c4a30d8b6a1040ccb873eed">llvm::sampleprof::SampleProfileReaderBinary::End</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a9cb031e56118fb0d538ba72e408ec183">llvm::sampleprof::FunctionSamples::functionSamplesAt</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ad117577730085f895045fc7ff90d8fc2">llvm::sampleprof::FunctionSamples::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a3493b1a9313f04d70a4c843d827d42a9">llvm::sampleprof::SampleProfileReader::ProfileHasAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a53cef5334d9e6535928ce4d79e7529e3">llvm::sampleprof::SampleProfileReader::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#af3bd0368cb44b2cc97123f03de71efaa">llvm::sampleprof::SampleProfileReader::ProfileIsProbeBased</a>, <a href="#a58cedb1356bab80647af0fa48bc1750a">readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a253ea7b225121d422aa3378a18dc2030">llvm::sampleprof::SampleProfileReaderBinary::readNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a33a776d038d88cf9261e439f16455d50">llvm::sampleprof::SampleProfileReaderBinary::readSampleContextFromTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#aa7894022c49174ef967469c3ddd81857">llvm::sampleprof::SampleContext::setAllAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ac015e530d60203906c93e241682e8359">llvm::sampleprof::FunctionSamples::setFunctionHash</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>

</div>
</div>

### readFuncOffsetTable() {#a008cc734a7a06814838c697a958ee982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderExtBinaryBase::readFuncOffsetTable ()</td>
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



<p>Declaration at line 784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 849 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="#a3c2242c2960947a793dfd7995fed38d5">FuncOffsetList</a>, <a href="#adb05340f4153393eede497cb6210ec53">FuncOffsetTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a253ea7b225121d422aa3378a18dc2030">llvm::sampleprof::SampleProfileReaderBinary::readNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a33a776d038d88cf9261e439f16455d50">llvm::sampleprof::SampleProfileReaderBinary::readSampleContextFromTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a> and <a href="#a749c376568365b892c49529c92ed7499">useFuncOffsetList</a>.</p>


<p>Referenced by <a href="#ab0c499972ec35ad7872cbceafa870704">readOneSection</a>.</p>

</div>
</div>

### readFuncProfiles() {#a727bcceedcf0fe170cb330513c25ab2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderExtBinaryBase::readFuncProfiles ()</td>
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



<p>Declaration at line 785 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 977 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0d0cdeb3cf9845558d9577f37fc326b3">collectFuncsFromModule</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a1bd87b526bf1a09487cf4d75d9e638ef">llvm::sampleprof::SampleProfileReader::CSProfileCount</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a09a7b8c381919bc366c86a06bbde0e82">llvm::sampleprof::SampleProfileReaderBinary::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a9204d2f85c4a30d8b6a1040ccb873eed">llvm::sampleprof::SampleProfileReaderBinary::End</a>, <a href="#a4bf2495c6c16f17a97e4c69ce4a68ffd">FuncsToUse</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a53cef5334d9e6535928ce4d79e7529e3">llvm::sampleprof::SampleProfileReader::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#ad31357a0bab13543c1d9e22e22f33ec4">llvm::sampleprof::SampleProfileReader::Profiles</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#aa172ac1d7f119592a8ef1bdd63ff5ccf">llvm::sampleprof::SampleProfileReaderBinary::readFuncProfile</a>, <a href="#a727bcceedcf0fe170cb330513c25ab2a">readFuncProfiles</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>


<p>Referenced by <a href="#a727bcceedcf0fe170cb330513c25ab2a">readFuncProfiles</a> and <a href="#ab0c499972ec35ad7872cbceafa870704">readOneSection</a>.</p>

</div>
</div>

### readFuncProfiles() {#a873e0df967c1a3a622ee9e25c1a6fa00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderExtBinaryBase::readFuncProfiles (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; FuncsToUse, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; Profiles)</td>
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



<p>Declaration at line 786 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 886 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#afe504aa31a6a354cec13f5b32d0b1d9d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a09a7b8c381919bc366c86a06bbde0e82">llvm::sampleprof::SampleProfileReaderBinary::Data</a>, <a href="#a3c2242c2960947a793dfd7995fed38d5">FuncOffsetList</a>, <a href="#adb05340f4153393eede497cb6210ec53">FuncOffsetTable</a>, <a href="#a4bf2495c6c16f17a97e4c69ce4a68ffd">FuncsToUse</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#aaec6c587638c9dedc9041f186e598196">llvm::sampleprof::SampleContext::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6811428caf500217f319c74e80900c14">llvm::GlobalValue::getGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid/#a5c097d6625bd9e8132f391309e787943">llvm::sampleprof::FunctionId::getHashCode</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#afe13f78db01d9c3d12b2cf017bd9fbeb">llvm::sampleprof::SampleContext::isPrefixOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a8e89e6935aaf48cde9d60fd12a3dae0f">llvm::sampleprof::MD5Hash</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a53cef5334d9e6535928ce4d79e7529e3">llvm::sampleprof::SampleProfileReader::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#ad31357a0bab13543c1d9e22e22f33ec4">llvm::sampleprof::SampleProfileReader::Profiles</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#aa172ac1d7f119592a8ef1bdd63ff5ccf">llvm::sampleprof::SampleProfileReaderBinary::readFuncProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a31a0b1a6e53cb0a08dbf78fc3cebc224">llvm::sampleprof::SampleProfileReader::Remapper</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid/#a36a977f1e2f4b4b0fca324a11d3e3313">llvm::sampleprof::FunctionId::stringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>, <a href="#a749c376568365b892c49529c92ed7499">useFuncOffsetList</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a2b5f844964866320a86d8bb53c84e6eb">llvm::sampleprof::SampleProfileReader::useMD5</a>.</p>

</div>
</div>

### readHeader() {#ae375ab166c92c7d215eea3a3f0277d46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderExtBinaryBase::readHeader ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read and validate the file header.</p>

<p>Declaration at line 792 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1387 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a317d9b9a39f8213c84429fbf54a7055f">llvm::sampleprof::SampleProfileReader::Buffer</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a09a7b8c381919bc366c86a06bbde0e82">llvm::sampleprof::SampleProfileReaderBinary::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a9204d2f85c4a30d8b6a1040ccb873eed">llvm::sampleprof::SampleProfileReaderBinary::End</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#af1e730478b6c28793c5298b372252601">llvm::sampleprof::SampleProfileReaderBinary::readMagicIdent</a>, <a href="#a71d1634305839ada83dff4daee355a95">readSecHdrTable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>

</div>
</div>

### readNameTableSec() {#a79b534a93144bf69a0b42214dc7a62de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderExtBinaryBase::readNameTableSec (bool IsMD5, bool FixedLengthMD5)</td>
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



<p>Declaration at line 788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1144 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a09a7b8c381919bc366c86a06bbde0e82">llvm::sampleprof::SampleProfileReaderBinary::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a9204d2f85c4a30d8b6a1040ccb873eed">llvm::sampleprof::SampleProfileReaderBinary::End</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a3a3860c4de3ad5e9bdb9f1b3f6919ba9">llvm::sampleprof::SampleProfileReaderBinary::MD5SampleContextStart</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a76217402d91e07543ae74594c456f0a1">llvm::sampleprof::SampleProfileReaderBinary::MD5SampleContextTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a23fa14b75cb1c7f9e4265c625efa9874">llvm::sampleprof::SampleProfileReaderBinary::NameTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a53cef5334d9e6535928ce4d79e7529e3">llvm::sampleprof::SampleProfileReader::ProfileIsCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#acfdf941f45bc58470ed8423b98862486">llvm::support::endian::read</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a08a6c4a1c3536fa7e594a3151e0773f9">llvm::sampleprof::SampleProfileReaderBinary::readNameTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a253ea7b225121d422aa3378a18dc2030">llvm::sampleprof::SampleProfileReaderBinary::readNumber</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbeaac273a9aa2a7a6e63ef477fa7f6d1980">llvm::truncated</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a46eee35129898d0466b2af97eacb19ee">llvm::support::endian::write64le</a>.</p>


<p>Referenced by <a href="#ab0c499972ec35ad7872cbceafa870704">readOneSection</a>.</p>

</div>
</div>

### readOneSection() {#ab0c499972ec35ad7872cbceafa870704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderExtBinaryBase::readOneSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Start, uint64_t Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sampleprof/sechdrtableentry">SecHdrTableEntry</a> &amp; Entry)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 794 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 723 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a09a7b8c381919bc366c86a06bbde0e82">llvm::sampleprof::SampleProfileReaderBinary::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a9204d2f85c4a30d8b6a1040ccb873eed">llvm::sampleprof::SampleProfileReaderBinary::End</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a3efc74fee0efccc34cb5a64de6b1d84a">llvm::sampleprof::hasSecFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ad20fb2a274b13a7820568739fbcba383">llvm::sampleprof::FunctionSamples::HasUniqSuffix</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a2be68a56c1386faa6c75baf21a462df7">llvm::sampleprof::SampleProfileReader::M</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a3493b1a9313f04d70a4c843d827d42a9">llvm::sampleprof::SampleProfileReader::ProfileHasAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a53cef5334d9e6535928ce4d79e7529e3">llvm::sampleprof::SampleProfileReader::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ac78db34e62da1555e9b84b5b5b1d907d">llvm::sampleprof::FunctionSamples::ProfileIsFS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#ab3c8e7a5bebd5fa73b577fdc7677f7a5">llvm::sampleprof::SampleProfileReader::ProfileIsFS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a549796a96109cea2cceae7d708fa5955">llvm::sampleprof::SampleProfileReader::ProfileIsMD5</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a08b33b498078ac3694a992f4ab8a5761">llvm::sampleprof::FunctionSamples::ProfileIsPreInlined</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a09599626d454548b75a8508733b742ce">llvm::sampleprof::SampleProfileReader::ProfileIsPreInlined</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa37fe7429ffcf70c306c27a55d714d31">llvm::sampleprof::FunctionSamples::ProfileIsProbeBased</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#af3bd0368cb44b2cc97123f03de71efaa">llvm::sampleprof::SampleProfileReader::ProfileIsProbeBased</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a03fdd01c4b2069f558380547824c7373">llvm::sampleprof::SampleProfileReader::ProfileSecRange</a>, <a href="#a272ffb93f3958019735d7a4ef9bf22d2">readCSNameTableSec</a>, <a href="#a3603fe57b2751d6366d8fc860de40078">readCustomSection</a>, <a href="#a58cedb1356bab80647af0fa48bc1750a">readFuncMetadata</a>, <a href="#a008cc734a7a06814838c697a958ee982">readFuncOffsetTable</a>, <a href="#a727bcceedcf0fe170cb330513c25ab2a">readFuncProfiles</a>, <a href="#a79b534a93144bf69a0b42214dc7a62de">readNameTableSec</a>, <a href="#ae9691c4736a7e6c9c247e997383771f4">readProfileSymbolList</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#aec2ab856ea5858bcc170eaaf185693d6">llvm::sampleprof::SampleProfileReaderBinary::readSummary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85a99873f635fc6dccc55e1bc82ef297827">llvm::sampleprof::SecCSNameTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a7d0799e340cf7553a27f898ef20ad6f7a5121eb700a5270cadcb8ec87c2593288">llvm::sampleprof::SecFlagFixedLengthMD5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#aa229d20f76a2d8473f321b97cb494462abbe7033a4a1f24db956320bb1a7b7ce3">llvm::sampleprof::SecFlagFSDiscriminator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#aa229d20f76a2d8473f321b97cb494462ad8375f4e079a5af243f36f91334691e7">llvm::sampleprof::SecFlagFullContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ad2f473dc3a871939a4781efc92f0931ba4771c0f8db64857edd1ee64cfde3edca">llvm::sampleprof::SecFlagHasAttribute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#aa229d20f76a2d8473f321b97cb494462a6517bd773ca68b78f926ec08f55daac3">llvm::sampleprof::SecFlagIsPreInlined</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ad2f473dc3a871939a4781efc92f0931ba538d11ebcb8192686ae93eb46ec92ebc">llvm::sampleprof::SecFlagIsProbeBased</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a7d0799e340cf7553a27f898ef20ad6f7a1780ac16db816da7bda99433dbdb73bf">llvm::sampleprof::SecFlagMD5Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#abed83dc828c8bfb55967efc3b9313758a3cc23f4782f1fd246c14392b45a2646f">llvm::sampleprof::SecFlagOrdered</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#aa229d20f76a2d8473f321b97cb494462ab8c5c1b9457b958b7c66a02adb2dc97a">llvm::sampleprof::SecFlagPartial</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a7d0799e340cf7553a27f898ef20ad6f7a27ba0d92f39f8d4651a98190c098df5d">llvm::sampleprof::SecFlagUniqSuffix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85aaa2da63cc16b51f0005debd3ae000a18">llvm::sampleprof::SecFuncMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85ae3b5e1c40206f7ac0a1e8b9c1f4fa4d7">llvm::sampleprof::SecFuncOffsetTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85a0e83cbbb890deaad56570290e86506ed">llvm::sampleprof::SecLBRProfile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85a04e75d4659b0c502eb2280e6d6fd6378">llvm::sampleprof::SecNameTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85ac77da6bc3aa6f736acc11b4fa1c59857">llvm::sampleprof::SecProfileSymbolList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85a8c51d0a5a19b4b2ae76846092b479354">llvm::sampleprof::SecProfSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a808d204826972c99cd36562eea139d23">llvm::sampleprof::SampleProfileReader::Summary</a>.</p>


<p>Referenced by <a href="#aa3075229a3db86f1b533efcc85f82d97">readImpl</a>.</p>

</div>
</div>

### readProfileSymbolList() {#ae9691c4736a7e6c9c247e997383771f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderExtBinaryBase::readProfileSymbolList ()</td>
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



<p>Declaration at line 790 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1007 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a09a7b8c381919bc366c86a06bbde0e82">llvm::sampleprof::SampleProfileReaderBinary::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a9204d2f85c4a30d8b6a1040ccb873eed">llvm::sampleprof::SampleProfileReaderBinary::End</a>, <a href="#a634fd1a32a2d1831d0fc9c8874ca6abc">ProfSymList</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>


<p>Referenced by <a href="#ab0c499972ec35ad7872cbceafa870704">readOneSection</a>.</p>

</div>
</div>

### readSecHdrTable() {#a71d1634305839ada83dff4daee355a95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderExtBinaryBase::readSecHdrTable ()</td>
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



<p>Declaration at line 777 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1375 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="#a9f75738be57d967b82567631e51bd545">readSecHdrTableEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a9c60d8b65cd491edeafb796ba396acf8">llvm::sampleprof::SampleProfileReaderBinary::readUnencodedNumber</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>


<p>Referenced by <a href="#ae375ab166c92c7d215eea3a3f0277d46">readHeader</a>.</p>

</div>
</div>

### readSecHdrTableEntry() {#a9f75738be57d967b82567631e51bd545}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderExtBinaryBase::readSecHdrTableEntry (uint64_t Idx)</td>
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



<p>Declaration at line 776 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1348 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a9c60d8b65cd491edeafb796ba396acf8">llvm::sampleprof::SampleProfileReaderBinary::readUnencodedNumber</a>, <a href="#a00abab1c900c6b6eec7e9dcb44d248fb">SecHdrTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>


<p>Referenced by <a href="#a71d1634305839ada83dff4daee355a95">readSecHdrTable</a>.</p>

</div>
</div>

### useFuncOffsetList() {#a749c376568365b892c49529c92ed7499}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileReaderExtBinaryBase::useFuncOffsetList ()</td>
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

<p>Determine which container <a href="#a008cc734a7a06814838c697a958ee982">readFuncOffsetTable()</a> should populate, the list FuncOffsetList or the map FuncOffsetTable.</p>

<p>Declaration at line 801 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 798 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a53cef5334d9e6535928ce4d79e7529e3">llvm::sampleprof::SampleProfileReader::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a31a0b1a6e53cb0a08dbf78fc3cebc224">llvm::sampleprof::SampleProfileReader::Remapper</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a2b5f844964866320a86d8bb53c84e6eb">llvm::sampleprof::SampleProfileReader::useMD5</a>.</p>


<p>Referenced by <a href="#a008cc734a7a06814838c697a958ee982">readFuncOffsetTable</a> and <a href="#a873e0df967c1a3a622ee9e25c1a6fa00">readFuncProfiles</a>.</p>

</div>
</div>

### verifySPMagic() {#ab62f4de0484410fceefb50f7f3acb84f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::sampleprof::SampleProfileReaderExtBinaryBase::verifySPMagic (uint64_t Magic)</td>
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



<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### decompressSection() {#a7c72cebeb1e19f6345d0cbea372b7223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderExtBinaryBase::decompressSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * SecStart, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t SecSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *&amp; DecompressBuf, uint64_t &amp; DecompressBufSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1018 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>

</div>
</div>

### read() {#a7ad95f5337c96a2fcbe6cee6df1002e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderExtBinaryBase::read (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; FuncsToUse, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; Profiles)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read the profiles on-demand for the given functions.</p>


<p>This is used after stale call graph matching finds new functions whose profiles aren't loaded at the beginning and we need to loaded the profiles explicitly for potential matching.</p>


<p>Declaration at line 844 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 827 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### FuncOffsetList {#a3c2242c2960947a793dfd7995fed38d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;SampleContext, uint64_t&gt; &gt; llvm::sampleprof::SampleProfileReaderExtBinaryBase::FuncOffsetList</td>
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

<p>The list version of FuncOffsetTable.</p>


<p>This is used if every entry is being accessed.</p>


<p>Definition at line 812 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#a008cc734a7a06814838c697a958ee982">readFuncOffsetTable</a> and <a href="#a873e0df967c1a3a622ee9e25c1a6fa00">readFuncProfiles</a>.</p>

</div>
</div>

### FuncOffsetTable {#adb05340f4153393eede497cb6210ec53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;hash_code, uint64_t&gt; llvm::sampleprof::SampleProfileReaderExtBinaryBase::FuncOffsetTable</td>
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

<p>The table mapping from a function context's <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> to the offset of its FunctionSample towards file start.</p>


<p>At most one of FuncOffsetTable and FuncOffsetList is populated.</p>


<p>Definition at line 808 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#a008cc734a7a06814838c697a958ee982">readFuncOffsetTable</a> and <a href="#a873e0df967c1a3a622ee9e25c1a6fa00">readFuncProfiles</a>.</p>

</div>
</div>

### FuncsToUse {#a4bf2495c6c16f17a97e4c69ce4a68ffd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;StringRef&gt; llvm::sampleprof::SampleProfileReaderExtBinaryBase::FuncsToUse</td>
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

<p>The set containing the functions to use when compiling a module.</p>

<p>Definition at line 815 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#a0d0cdeb3cf9845558d9577f37fc326b3">collectFuncsFromModule</a>, <a href="#a727bcceedcf0fe170cb330513c25ab2a">readFuncProfiles</a> and <a href="#a873e0df967c1a3a622ee9e25c1a6fa00">readFuncProfiles</a>.</p>

</div>
</div>

### ProfSymList {#a634fd1a32a2d1831d0fc9c8874ca6abc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ProfileSymbolList&gt; llvm::sampleprof::SampleProfileReaderExtBinaryBase::ProfSymList</td>
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



<p>Definition at line 803 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#aa05dfff9baa25b88665df394ec32f5a5">getProfileSymbolList</a> and <a href="#ae9691c4736a7e6c9c247e997383771f4">readProfileSymbolList</a>.</p>

</div>
</div>

### SecHdrTable {#a00abab1c900c6b6eec7e9dcb44d248fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SecHdrTableEntry&gt; llvm::sampleprof::SampleProfileReaderExtBinaryBase::SecHdrTable</td>
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



<p>Definition at line 775 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#ab0f3253a66867b0999fc9d2be549268c">dumpSectionInfo</a>, <a href="#ae5212e24c2c507eb51d7ad201800cbfc">getFileSize</a>, <a href="#a192f65175b8cab2ec3ce9ff6bfd38ebb">getSectionSize</a>, <a href="#aa3075229a3db86f1b533efcc85f82d97">readImpl</a> and <a href="#a9f75738be57d967b82567631e51bd545">readSecHdrTableEntry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allocator {#a50b4a8ef050103d3e796a29054e467dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::sampleprof::SampleProfileReaderExtBinaryBase::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 772 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
