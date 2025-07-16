---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprof/sampleprofilereaderbinary
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SampleProfileReaderBinary` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::sampleprof::SampleProfileReaderBinary { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">llvm/ProfileData/SampleProfReader.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader">SampleProfileReader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sample-based profile reader. <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase">SampleProfileReaderExtBinaryBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SampleProfileReaderExtBinaryBase/SampleProfileWriterExtBinaryBase defines the basic structure of the extensible binary format. <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderrawbinary">SampleProfileReaderRawBinary</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e504be88a1ea38cddc31af56ab20fb7">SampleProfileReaderBinary</a> (std::unique_ptr&lt; MemoryBuffer &gt; B, LLVMContext &amp;C, SampleProfileFormat Format=SPF_None)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36208a5b2efdedf5b0640c8b47e235b8">readHeader</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read and validate the file header. <a href="#a36208a5b2efdedf5b0640c8b47e235b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ad89ebfc9008ab04dbaf011e1f1e8db">readImpl</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read sample profiles from the associated file. <a href="#a5ad89ebfc9008ab04dbaf011e1f1e8db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2782bb0445386452efe46e050ba5e53">getNameTable</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>It includes all the names that have samples either in outline instance or inline instance. <a href="#af2782bb0445386452efe46e050ba5e53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a253ea7b225121d422aa3378a18dc2030">readNumber</a> () -&gt; <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read a numeric value of type T from the profile. <a href="#a253ea7b225121d422aa3378a18dc2030">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9c60d8b65cd491edeafb796ba396acf8">readUnencodedNumber</a> () -&gt; <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read a numeric value of type T from the profile. <a href="#a9c60d8b65cd491edeafb796ba396acf8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a136a5648f006c4f55171f4559f5ce4b0">readString</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read a string from the profile. <a href="#a136a5648f006c4f55171f4559f5ce4b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a0e8531ef8066ba96fe715e848b1261">readStringIndex</a> (T &amp;Table) -&gt; <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; size_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read the string index and check whether it overflows the table. <a href="#a7a0e8531ef8066ba96fe715e848b1261">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa172ac1d7f119592a8ef1bdd63ff5ccf">readFuncProfile</a> (const uint8_t *Start)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read the next function profile instance. <a href="#aa172ac1d7f119592a8ef1bdd63ff5ccf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52d0fff5d3fdc4368cb7b9a2edda2b6f">readFuncProfile</a> (const uint8_t *Start, SampleProfileMap &amp;Profiles)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0320040b070e4fc2904794078a64e46c">readProfile</a> (FunctionSamples &amp;FProfile)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read the contents of the given profile instance. <a href="#a0320040b070e4fc2904794078a64e46c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1e730478b6c28793c5298b372252601">readMagicIdent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read the contents of Magic number and Version number. <a href="#af1e730478b6c28793c5298b372252601">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec2ab856ea5858bcc170eaaf185693d6">readSummary</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read profile summary. <a href="#aec2ab856ea5858bcc170eaaf185693d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08a6c4a1c3536fa7e594a3151e0773f9">readNameTable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read the whole name table. <a href="#a08a6c4a1c3536fa7e594a3151e0773f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a675409b9aae66c892d13a9ea74cf11c7">readStringFromTable</a> (size_t *RetIdx=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read a string indirectly via the name table. Optionally return the index. <a href="#a675409b9aae66c892d13a9ea74cf11c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a737d65abec7fd88fdb10cfcd209391c2">SampleContextFrames</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dd6224720b47c4a75d37eac05f9192f">readContextFromTable</a> (size_t *RetIdx=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read a context indirectly via the CSNameTable. <a href="#a2dd6224720b47c4a75d37eac05f9192f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a>, uint64_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33a776d038d88cf9261e439f16455d50">readSampleContextFromTable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read a context indirectly via the CSNameTable if the profile has context, otherwise same as readStringFromTable, also return its hash value. <a href="#a33a776d038d88cf9261e439f16455d50">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac9043ff8213cb796822a22efbb559de">readSummaryEntry</a> (std::vector&lt; ProfileSummaryEntry &gt; &amp;Entries)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ef453a4622de3b765f0522284c4777e">verifySPMagic</a> (uint64_t Magic)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09a7b8c381919bc366c86a06bbde0e82">Data</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Points to the current location in the buffer. <a href="#a09a7b8c381919bc366c86a06bbde0e82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9204d2f85c4a30d8b6a1040ccb873eed">End</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Points to the end of the buffer. <a href="#a9204d2f85c4a30d8b6a1040ccb873eed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23fa14b75cb1c7f9e4265c625efa9874">NameTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> name table. <a href="#a23fa14b75cb1c7f9e4265c625efa9874">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#abc45b32c93302a515b730f86807dd80c">SampleContextFrameVector</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a0ac3887cefaae1c3266ec449e81a44">CSNameTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CSNameTable is used to save full context vectors. <a href="#a5a0ac3887cefaae1c3266ec449e81a44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76217402d91e07543ae74594c456f0a1">MD5SampleContextTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Table to cache <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> values of sample contexts corresponding to <a href="#a33a776d038d88cf9261e439f16455d50">readSampleContextFromTable()</a>, used to index into Profiles or FuncOffsetTable. <a href="#a76217402d91e07543ae74594c456f0a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a3860c4de3ad5e9bdb9f1b3f6919ba9">MD5SampleContextStart</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The starting address of the table of <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> values of sample contexts. <a href="#a3a3860c4de3ad5e9bdb9f1b3f6919ba9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SampleProfileReaderBinary() {#a6e504be88a1ea38cddc31af56ab20fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::SampleProfileReaderBinary::SampleProfileReaderBinary (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; B, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66ec">SampleProfileFormat</a> Format=<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66eca71fa511e217d0835567f7d919aab6d02">SPF_None</a>)</td>
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



<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a7cddd27e849335a576339995fc8feaa7">llvm::sampleprof::SampleProfileReader::Format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a7df3a90aaf7409ace0a2a56f5e539477">llvm::sampleprof::SampleProfileReader::SampleProfileReader</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66eca71fa511e217d0835567f7d919aab6d02">llvm::sampleprof::SPF_None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab6ffdd6df239a2e84804f57c4b7c7317">llvm::sampleprof::SampleProfileReaderExtBinaryBase::SampleProfileReaderExtBinaryBase</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderrawbinary/#a90d37b805071293af6ee34041153f44b">llvm::sampleprof::SampleProfileReaderRawBinary::SampleProfileReaderRawBinary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNameTable() {#af2782bb0445386452efe46e050ba5e53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; FunctionId &gt; * llvm::sampleprof::SampleProfileReaderBinary::getNameTable ()</td>
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

<p>It includes all the names that have samples either in outline instance or inline instance.</p>

<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Reference <a href="#a23fa14b75cb1c7f9e4265c625efa9874">NameTable</a>.</p>

</div>
</div>

### readHeader() {#a36208a5b2efdedf5b0640c8b47e235b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderBinary::readHeader ()</td>
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

<p>Read and validate the file header.</p>

<p>Declaration at line 641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1511 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a317d9b9a39f8213c84429fbf54a7055f">llvm::sampleprof::SampleProfileReader::Buffer</a>, <a href="#a09a7b8c381919bc366c86a06bbde0e82">Data</a>, <a href="#a9204d2f85c4a30d8b6a1040ccb873eed">End</a>, <a href="#af1e730478b6c28793c5298b372252601">readMagicIdent</a>, <a href="#a08a6c4a1c3536fa7e594a3151e0773f9">readNameTable</a>, <a href="#aec2ab856ea5858bcc170eaaf185693d6">readSummary</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>

</div>
</div>

### readImpl() {#a5ad89ebfc9008ab04dbaf011e1f1e8db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderBinary::readImpl ()</td>
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

<p>Read sample profiles from the associated file.</p>

<p>Declaration at line 644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="#a09a7b8c381919bc366c86a06bbde0e82">Data</a>, <a href="#a9204d2f85c4a30d8b6a1040ccb873eed">End</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ac78db34e62da1555e9b84b5b5b1d907d">llvm::sampleprof::FunctionSamples::ProfileIsFS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#ab3c8e7a5bebd5fa73b577fdc7677f7a5">llvm::sampleprof::SampleProfileReader::ProfileIsFS</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a93c1b2cdde2d2acc22f2a37f7eb36f2c">ProfileIsFSDisciminator</a>, <a href="#aa172ac1d7f119592a8ef1bdd63ff5ccf">readFuncProfile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### readContextFromTable() {#a2dd6224720b47c4a75d37eac05f9192f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; SampleContextFrames &gt; SampleProfileReaderBinary::readContextFromTable (size_t * RetIdx=nullptr)</td>
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

<p>Read a context indirectly via the CSNameTable.</p>


<p>Optionally return the index.</p>


<p>Declaration at line 698 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="#a5a0ac3887cefaae1c3266ec449e81a44">CSNameTable</a>, <a href="#a253ea7b225121d422aa3378a18dc2030">readNumber</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea98266342cea8a7fb97a2c17d98fd230a">llvm::truncated_name_table</a>.</p>


<p>Referenced by <a href="#a33a776d038d88cf9261e439f16455d50">readSampleContextFromTable</a>.</p>

</div>
</div>

### readFuncProfile() {#aa172ac1d7f119592a8ef1bdd63ff5ccf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderBinary::readFuncProfile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Start)</td>
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

<p>Read the next function profile instance.</p>

<p>Declaration at line 677 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#ad31357a0bab13543c1d9e22e22f33ec4">llvm::sampleprof::SampleProfileReader::Profiles</a> and <a href="#aa172ac1d7f119592a8ef1bdd63ff5ccf">readFuncProfile</a>.</p>


<p>Referenced by <a href="#aa172ac1d7f119592a8ef1bdd63ff5ccf">readFuncProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a727bcceedcf0fe170cb330513c25ab2a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncProfiles</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a873e0df967c1a3a622ee9e25c1a6fa00">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncProfiles</a> and <a href="#a5ad89ebfc9008ab04dbaf011e1f1e8db">readImpl</a>.</p>

</div>
</div>

### readFuncProfile() {#a52d0fff5d3fdc4368cb7b9a2edda2b6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderBinary::readFuncProfile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Start, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; Profiles)</td>
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



<p>Declaration at line 678 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a8dda47f9492c59e96d8b43fa6244af20">llvm::sampleprof::FunctionSamples::addHeadSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a1bd87b526bf1a09487cf4d75d9e638ef">llvm::sampleprof::SampleProfileReader::CSProfileCount</a>, <a href="#a09a7b8c381919bc366c86a06bbde0e82">Data</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#ad31357a0bab13543c1d9e22e22f33ec4">llvm::sampleprof::SampleProfileReader::Profiles</a>, <a href="#a253ea7b225121d422aa3378a18dc2030">readNumber</a>, <a href="#a0320040b070e4fc2904794078a64e46c">readProfile</a>, <a href="#a33a776d038d88cf9261e439f16455d50">readSampleContextFromTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ae6507284ccb03c1c44fe0e7d37650493">llvm::sampleprof::FunctionSamples::setContext</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>

</div>
</div>

### readMagicIdent() {#af1e730478b6c28793c5298b372252601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderBinary::readMagicIdent ()</td>
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

<p>Read the contents of Magic number and Version number.</p>

<p>Declaration at line 685 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1493 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="#a253ea7b225121d422aa3378a18dc2030">readNumber</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#aec06640e3197b264c40e6f84e9a7ad6a">llvm::sampleprof::SPVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea2af01f2c39c66a1641045dd660e839b5">llvm::unsupported_version</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="#a36208a5b2efdedf5b0640c8b47e235b8">readHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ae375ab166c92c7d215eea3a3f0277d46">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readHeader</a>.</p>

</div>
</div>

### readNameTable() {#a08a6c4a1c3536fa7e594a3151e0773f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderBinary::readNameTable ()</td>
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

<p>Read the whole name table.</p>

<p>Declaration at line 691 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1103 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid/#a5c097d6625bd9e8132f391309e787943">llvm::sampleprof::FunctionId::getHashCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a3a3860c4de3ad5e9bdb9f1b3f6919ba9">MD5SampleContextStart</a>, <a href="#a76217402d91e07543ae74594c456f0a1">MD5SampleContextTable</a>, <a href="#a23fa14b75cb1c7f9e4265c625efa9874">NameTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a53cef5334d9e6535928ce4d79e7529e3">llvm::sampleprof::SampleProfileReader::ProfileIsCS</a>, <a href="#a253ea7b225121d422aa3378a18dc2030">readNumber</a>, <a href="#a136a5648f006c4f55171f4559f5ce4b0">readString</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a2b5f844964866320a86d8bb53c84e6eb">llvm::sampleprof::SampleProfileReader::useMD5</a>.</p>


<p>Referenced by <a href="#a36208a5b2efdedf5b0640c8b47e235b8">readHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a79b534a93144bf69a0b42214dc7a62de">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readNameTableSec</a>.</p>

</div>
</div>

### readNumber() {#a253ea7b225121d422aa3378a18dc2030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; T &gt; SampleProfileReaderBinary::readNumber ()</td>
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

<p>Read a numeric value of type T from the profile.</p>


<p>If an error occurs during decoding, a diagnostic message is emitted and EC is set.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the read value.</p></dd>
</dl>


<p>Declaration at line 659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="#a09a7b8c381919bc366c86a06bbde0e82">Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3720bbfe79232f7792ab4b969dfbeed0">llvm::decodeULEB128</a>, <a href="#a9204d2f85c4a30d8b6a1040ccb873eed">End</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea7596fdd04dba990373ab2f3da0c7dd3f">llvm::malformed</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#af7db78adf47785867ea84d77ace26cc6">llvm::sampleprof::SampleProfileReader::reportError</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbeaac273a9aa2a7a6e63ef477fa7f6d1980">llvm::truncated</a>.</p>


<p>Referenced by <a href="#a2dd6224720b47c4a75d37eac05f9192f">readContextFromTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a272ffb93f3958019735d7a4ef9bf22d2">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readCSNameTableSec</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a9b9e845ee3096f8360407bfa4f0f3d1a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a008cc734a7a06814838c697a958ee982">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncOffsetTable</a>, <a href="#a52d0fff5d3fdc4368cb7b9a2edda2b6f">readFuncProfile</a>, <a href="#af1e730478b6c28793c5298b372252601">readMagicIdent</a>, <a href="#a08a6c4a1c3536fa7e594a3151e0773f9">readNameTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a79b534a93144bf69a0b42214dc7a62de">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readNameTableSec</a>, <a href="#a0320040b070e4fc2904794078a64e46c">readProfile</a>, <a href="#a7a0e8531ef8066ba96fe715e848b1261">readStringIndex</a> and <a href="#aec2ab856ea5858bcc170eaaf185693d6">readSummary</a>.</p>

</div>
</div>

### readProfile() {#a0320040b070e4fc2904794078a64e46c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderBinary::readProfile (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; FProfile)</td>
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

<p>Read the contents of the given profile instance.</p>

<p>Declaration at line 682 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ab38820a59b382631568b3735469b0890">llvm::sampleprof::FunctionSamples::addBodySamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a951ceadc1dc24cb5041d80ca661c8e3e">llvm::sampleprof::FunctionSamples::addCalledTargetSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a263b944b1e1d1b8906ccfa19a565d2ed">llvm::sampleprof::FunctionSamples::addTotalSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a9cb031e56118fb0d538ba72e408ec183">llvm::sampleprof::FunctionSamples::functionSamplesAt</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a8c0b29b235366b7d2447ab4dc39398ed">llvm::sampleprof::SampleProfileReader::getDiscriminatorMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a528869d42ce7fca106b21792fe00bf0a">isOffsetLegal</a>, <a href="#a253ea7b225121d422aa3378a18dc2030">readNumber</a>, <a href="#a0320040b070e4fc2904794078a64e46c">readProfile</a>, <a href="#a675409b9aae66c892d13a9ea74cf11c7">readStringFromTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a677a143b2118c3ffdf3ecf58384a49cd">llvm::sampleprof::FunctionSamples::setFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>


<p>Referenced by <a href="#a52d0fff5d3fdc4368cb7b9a2edda2b6f">readFuncProfile</a> and <a href="#a0320040b070e4fc2904794078a64e46c">readProfile</a>.</p>

</div>
</div>

### readSampleContextFromTable() {#a33a776d038d88cf9261e439f16455d50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::pair&lt; SampleContext, uint64_t &gt; &gt; SampleProfileReaderBinary::readSampleContextFromTable ()</td>
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

<p>Read a context indirectly via the CSNameTable if the profile has context, otherwise same as readStringFromTable, also return its hash value.</p>

<p>Declaration at line 702 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3a3860c4de3ad5e9bdb9f1b3f6919ba9">MD5SampleContextStart</a>, <a href="#a76217402d91e07543ae74594c456f0a1">MD5SampleContextTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a53cef5334d9e6535928ce4d79e7529e3">llvm::sampleprof::SampleProfileReader::ProfileIsCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0fa2f859066acd16820ab083040158c9">llvm::support::endian::read64le</a>, <a href="#a2dd6224720b47c4a75d37eac05f9192f">readContextFromTable</a>, <a href="#a675409b9aae66c892d13a9ea74cf11c7">readStringFromTable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a46eee35129898d0466b2af97eacb19ee">llvm::support::endian::write64le</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a077db87ff742498d2add620c1a7130db">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a9b9e845ee3096f8360407bfa4f0f3d1a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a008cc734a7a06814838c697a958ee982">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncOffsetTable</a> and <a href="#a52d0fff5d3fdc4368cb7b9a2edda2b6f">readFuncProfile</a>.</p>

</div>
</div>

### readString() {#a136a5648f006c4f55171f4559f5ce4b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; StringRef &gt; SampleProfileReaderBinary::readString ()</td>
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

<p>Read a string from the profile.</p>


<p>If an error occurs during decoding, a diagnostic message is emitted and EC is set.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the read value.</p></dd>
</dl>


<p>Declaration at line 671 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="#a09a7b8c381919bc366c86a06bbde0e82">Data</a>, <a href="#a9204d2f85c4a30d8b6a1040ccb873eed">End</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#af7db78adf47785867ea84d77ace26cc6">llvm::sampleprof::SampleProfileReader::reportError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbeaac273a9aa2a7a6e63ef477fa7f6d1980">llvm::truncated</a>.</p>


<p>Referenced by <a href="#a08a6c4a1c3536fa7e594a3151e0773f9">readNameTable</a>.</p>

</div>
</div>

### readStringFromTable() {#a675409b9aae66c892d13a9ea74cf11c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; FunctionId &gt; SampleProfileReaderBinary::readStringFromTable (size_t * RetIdx=nullptr)</td>
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

<p>Read a string indirectly via the name table. Optionally return the index.</p>

<p>Declaration at line 694 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="#a23fa14b75cb1c7f9e4265c625efa9874">NameTable</a> and <a href="#a7a0e8531ef8066ba96fe715e848b1261">readStringIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a272ffb93f3958019735d7a4ef9bf22d2">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readCSNameTableSec</a>, <a href="#a0320040b070e4fc2904794078a64e46c">readProfile</a> and <a href="#a33a776d038d88cf9261e439f16455d50">readSampleContextFromTable</a>.</p>

</div>
</div>

### readStringIndex() {#a7a0e8531ef8066ba96fe715e848b1261}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; size_t &gt; SampleProfileReaderBinary::readStringIndex (T &amp; Table)</td>
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

<p>Read the string index and check whether it overflows the table.</p>

<p>Declaration at line 674 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="#a253ea7b225121d422aa3378a18dc2030">readNumber</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea98266342cea8a7fb97a2c17d98fd230a">llvm::truncated_name_table</a>.</p>


<p>Referenced by <a href="#a675409b9aae66c892d13a9ea74cf11c7">readStringFromTable</a>.</p>

</div>
</div>

### readSummary() {#aec2ab856ea5858bcc170eaaf185693d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderBinary::readSummary ()</td>
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

<p>Read profile summary.</p>

<p>Declaration at line 688 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1544 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/profilesummary/#aa5aa682b3904e88749fa973b3da370c2a0c86eaeebf5b6120b601ecc93a1c2e3a">llvm::ProfileSummary::PSK_Sample</a>, <a href="#a253ea7b225121d422aa3378a18dc2030">readNumber</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a808d204826972c99cd36562eea139d23">llvm::sampleprof::SampleProfileReader::Summary</a>.</p>


<p>Referenced by <a href="#a36208a5b2efdedf5b0640c8b47e235b8">readHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab0c499972ec35ad7872cbceafa870704">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readOneSection</a>.</p>

</div>
</div>

### readUnencodedNumber() {#a9c60d8b65cd491edeafb796ba396acf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; T &gt; SampleProfileReaderBinary::readUnencodedNumber ()</td>
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

<p>Read a numeric value of type T from the profile.</p>


<p>The value is saved without encoded.</p>


<p>Declaration at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="#a09a7b8c381919bc366c86a06bbde0e82">Data</a>, <a href="#a9204d2f85c4a30d8b6a1040ccb873eed">End</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae6c58c37f5229487e86ce915afe1ba12">llvm::support::endian::readNext</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#af7db78adf47785867ea84d77ace26cc6">llvm::sampleprof::SampleProfileReader::reportError</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbeaac273a9aa2a7a6e63ef477fa7f6d1980">llvm::truncated</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a71d1634305839ada83dff4daee355a95">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readSecHdrTable</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a9f75738be57d967b82567631e51bd545">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readSecHdrTableEntry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### readSummaryEntry() {#aac9043ff8213cb796822a22efbb559de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderBinary::readSummaryEntry (std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/profilesummaryentry">ProfileSummaryEntry</a> &gt; &amp; Entries)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 729 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1526 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>

</div>
</div>

### verifySPMagic() {#a7ef453a4622de3b765f0522284c4777e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::error_code llvm::sampleprof::SampleProfileReaderBinary::verifySPMagic (uint64_t Magic)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CSNameTable {#a5a0ac3887cefaae1c3266ec449e81a44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SampleContextFrameVector&gt; llvm::sampleprof::SampleProfileReaderBinary::CSNameTable</td>
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

<p>CSNameTable is used to save full context vectors.</p>


<p>It is the backing buffer for <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a737d65abec7fd88fdb10cfcd209391c2">SampleContextFrames</a>.</p>


<p>Definition at line 715 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#a2dd6224720b47c4a75d37eac05f9192f">readContextFromTable</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a272ffb93f3958019735d7a4ef9bf22d2">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readCSNameTableSec</a>.</p>

</div>
</div>

### Data {#a09a7b8c381919bc366c86a06bbde0e82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t* llvm::sampleprof::SampleProfileReaderBinary::Data = nullptr</td>
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

<p>Points to the current location in the buffer.</p>

<p>Definition at line 705 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinary/#ac37600268c671eee29e31904b1532c17">llvm::sampleprof::SampleProfileReaderExtBinary::hasFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderrawbinary/#ac52edce1e67044bb74c9839d0b91445e">llvm::sampleprof::SampleProfileReaderRawBinary::hasFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a077db87ff742498d2add620c1a7130db">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a9b9e845ee3096f8360407bfa4f0f3d1a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a58cedb1356bab80647af0fa48bc1750a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>, <a href="#a52d0fff5d3fdc4368cb7b9a2edda2b6f">readFuncProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a727bcceedcf0fe170cb330513c25ab2a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncProfiles</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a873e0df967c1a3a622ee9e25c1a6fa00">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncProfiles</a>, <a href="#a36208a5b2efdedf5b0640c8b47e235b8">readHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ae375ab166c92c7d215eea3a3f0277d46">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readHeader</a>, <a href="#a5ad89ebfc9008ab04dbaf011e1f1e8db">readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#aa3075229a3db86f1b533efcc85f82d97">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a79b534a93144bf69a0b42214dc7a62de">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readNameTableSec</a>, <a href="#a253ea7b225121d422aa3378a18dc2030">readNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab0c499972ec35ad7872cbceafa870704">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readOneSection</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ae9691c4736a7e6c9c247e997383771f4">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readProfileSymbolList</a>, <a href="#a136a5648f006c4f55171f4559f5ce4b0">readString</a> and <a href="#a9c60d8b65cd491edeafb796ba396acf8">readUnencodedNumber</a>.</p>

</div>
</div>

### End {#a9204d2f85c4a30d8b6a1040ccb873eed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t* llvm::sampleprof::SampleProfileReaderBinary::End = nullptr</td>
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

<p>Points to the end of the buffer.</p>

<p>Definition at line 708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a077db87ff742498d2add620c1a7130db">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a9b9e845ee3096f8360407bfa4f0f3d1a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a58cedb1356bab80647af0fa48bc1750a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a727bcceedcf0fe170cb330513c25ab2a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncProfiles</a>, <a href="#a36208a5b2efdedf5b0640c8b47e235b8">readHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ae375ab166c92c7d215eea3a3f0277d46">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readHeader</a>, <a href="#a5ad89ebfc9008ab04dbaf011e1f1e8db">readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#aa3075229a3db86f1b533efcc85f82d97">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a79b534a93144bf69a0b42214dc7a62de">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readNameTableSec</a>, <a href="#a253ea7b225121d422aa3378a18dc2030">readNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab0c499972ec35ad7872cbceafa870704">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readOneSection</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ae9691c4736a7e6c9c247e997383771f4">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readProfileSymbolList</a>, <a href="#a136a5648f006c4f55171f4559f5ce4b0">readString</a> and <a href="#a9c60d8b65cd491edeafb796ba396acf8">readUnencodedNumber</a>.</p>

</div>
</div>

### MD5SampleContextStart {#a3a3860c4de3ad5e9bdb9f1b3f6919ba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t* llvm::sampleprof::SampleProfileReaderBinary::MD5SampleContextStart = nullptr</td>
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

<p>The starting address of the table of <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> values of sample contexts.</p>


<p>For fixed length <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> non-CS profile it is same as MD5NameMemStart because hashes of non-CS contexts are already in the profile. Otherwise it points to the start of MD5SampleContextTable.</p>


<p>Definition at line 726 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a272ffb93f3958019735d7a4ef9bf22d2">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readCSNameTableSec</a>, <a href="#a08a6c4a1c3536fa7e594a3151e0773f9">readNameTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a79b534a93144bf69a0b42214dc7a62de">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readNameTableSec</a> and <a href="#a33a776d038d88cf9261e439f16455d50">readSampleContextFromTable</a>.</p>

</div>
</div>

### MD5SampleContextTable {#a76217402d91e07543ae74594c456f0a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint64_t&gt; llvm::sampleprof::SampleProfileReaderBinary::MD5SampleContextTable</td>
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

<p>Table to cache <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> values of sample contexts corresponding to <a href="#a33a776d038d88cf9261e439f16455d50">readSampleContextFromTable()</a>, used to index into Profiles or FuncOffsetTable.</p>

<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a272ffb93f3958019735d7a4ef9bf22d2">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readCSNameTableSec</a>, <a href="#a08a6c4a1c3536fa7e594a3151e0773f9">readNameTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a79b534a93144bf69a0b42214dc7a62de">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readNameTableSec</a> and <a href="#a33a776d038d88cf9261e439f16455d50">readSampleContextFromTable</a>.</p>

</div>
</div>

### NameTable {#a23fa14b75cb1c7f9e4265c625efa9874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;FunctionId&gt; llvm::sampleprof::SampleProfileReaderBinary::NameTable</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> name table.</p>

<p>Definition at line 711 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#af2782bb0445386452efe46e050ba5e53">getNameTable</a>, <a href="#a08a6c4a1c3536fa7e594a3151e0773f9">readNameTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a79b534a93144bf69a0b42214dc7a62de">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readNameTableSec</a> and <a href="#a675409b9aae66c892d13a9ea74cf11c7">readStringFromTable</a>.</p>

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
