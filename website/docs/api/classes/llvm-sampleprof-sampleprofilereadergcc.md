---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprof/sampleprofilereadergcc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SampleProfileReaderGCC` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::sampleprof::SampleProfileReaderGCC { ... }
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78d594511a420e0aa288e6cada80638a">SampleProfileReaderGCC</a> (std::unique_ptr&lt; MemoryBuffer &gt; B, LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e2ac14aece78da6927b8e8e698c5ce1">readHeader</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read and validate the file header. <a href="#a7e2ac14aece78da6927b8e8e698c5ce1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eafbdaec23df0b928d64cf6d16c2831">readImpl</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read sample profiles from the associated file. <a href="#a4eafbdaec23df0b928d64cf6d16c2831">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a622597173a279123bf79b590ee419180">readNameTable</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98a6af42792c32db070dee8826e1412e">readOneFunctionProfile</a> (const InlineCallStack &amp;InlineStack, bool Update, uint32_t Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa53d5b8b15dd26564754966d3159f822">readFunctionProfiles</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5bbfe5b0f863708d31b6ce2e126ec0c">skipNextWord</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3692dc50c07c5eda5e01f891cc03047c">readNumber</a> () -&gt; <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; T &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e54d8ccf59b2b783a1254168ce468d7">readString</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af817ec9dd6d3474c66b2212251c6e338">readSectionTag</a> (uint32_t Expected)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read the section tag and check that it's the same as <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a></span>. <a href="#af817ec9dd6d3474c66b2212251c6e338">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcovbuffer">GCOVBuffer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a392e2d3a5ec6cbcf083b943c63f4fdeb">GcovBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/gcov">GCOV</a> buffer containing the profile. <a href="#a392e2d3a5ec6cbcf083b943c63f4fdeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e59b0f8cf7428c8692ef42b6bc36a1b">Names</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> names in this profile. <a href="#a4e59b0f8cf7428c8692ef42b6bc36a1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade9bafe407ebfb2eed960233a4f5da22">hasFormat</a> (const MemoryBuffer &amp;Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">Buffer</span> is in the format supported by this class. <a href="#ade9bafe407ebfb2eed960233a4f5da22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5c8f538e3e9aa9a3aecec509ee8d178">GCOVTagAFDOFileNames</a> = 0xaa000000</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/gcov">GCOV</a> tags used to separate sections in the profile file. <a href="#aa5c8f538e3e9aa9a3aecec509ee8d178">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94582c22716e5b7c7ec357d5d2d8de97">GCOVTagAFDOFunction</a> = 0xac000000</td>
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


<p>Definition at line 881 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SampleProfileReaderGCC() {#a78d594511a420e0aa288e6cada80638a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::SampleProfileReaderGCC::SampleProfileReaderGCC (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; B, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Definition at line 883 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a317d9b9a39f8213c84429fbf54a7055f">llvm::sampleprof::SampleProfileReader::Buffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a392e2d3a5ec6cbcf083b943c63f4fdeb">GcovBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a7df3a90aaf7409ace0a2a56f5e539477">llvm::sampleprof::SampleProfileReader::SampleProfileReader</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66eca4f20635356824ecd5dac2016c1dfc018">llvm::sampleprof::SPF_GCC</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### readHeader() {#a7e2ac14aece78da6927b8e8e698c5ce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderGCC::readHeader ()</td>
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

<p>Declaration at line 888 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1626 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="#a392e2d3a5ec6cbcf083b943c63f4fdeb">GcovBuffer</a>, <a href="#ab5bbfe5b0f863708d31b6ce2e126ec0c">skipNextWord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbead5b649348c44c8f1f89cb53fe7604f64">llvm::unrecognized_format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea2af01f2c39c66a1641045dd660e839b5">llvm::unsupported_version</a> and <a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08a28fc20af08dacec19f1191703628427b">llvm::GCOV::V407</a>.</p>

</div>
</div>

### readImpl() {#a4eafbdaec23df0b928d64cf6d16c2831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderGCC::readImpl ()</td>
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


<p>Read a GCC AutoFDO profile.</p>


<p>This format is generated by the Linux Perf conversion tool at <a href="https://github.com/google/autofdo">https://github.com/google/autofdo</a>.</p>


<p>Declaration at line 891 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1823 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a93c1b2cdde2d2acc22f2a37f7eb36f2c">ProfileIsFSDisciminator</a>, <a href="#aa53d5b8b15dd26564754966d3159f822">readFunctionProfiles</a>, <a href="#a622597173a279123bf79b590ee419180">readNameTable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### readFunctionProfiles() {#aa53d5b8b15dd26564754966d3159f822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderGCC::readFunctionProfiles ()</td>
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



<p>Declaration at line 900 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1679 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a862a85fc052e3da0f7109bc54ef4998d">llvm::sampleprof::SampleProfileReader::computeSummary</a>, <a href="#a392e2d3a5ec6cbcf083b943c63f4fdeb">GcovBuffer</a>, <a href="#a94582c22716e5b7c7ec357d5d2d8de97">GCOVTagAFDOFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a98a6af42792c32db070dee8826e1412e">readOneFunctionProfile</a>, <a href="#af817ec9dd6d3474c66b2212251c6e338">readSectionTag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbeaac273a9aa2a7a6e63ef477fa7f6d1980">llvm::truncated</a>.</p>


<p>Referenced by <a href="#a4eafbdaec23df0b928d64cf6d16c2831">readImpl</a>.</p>

</div>
</div>

### readNameTable() {#a622597173a279123bf79b590ee419180}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderGCC::readNameTable ()</td>
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



<p>Declaration at line 897 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1661 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="#a392e2d3a5ec6cbcf083b943c63f4fdeb">GcovBuffer</a>, <a href="#aa5c8f538e3e9aa9a3aecec509ee8d178">GCOVTagAFDOFileNames</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a4e59b0f8cf7428c8692ef42b6bc36a1b">Names</a>, <a href="#af817ec9dd6d3474c66b2212251c6e338">readSectionTag</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbeaac273a9aa2a7a6e63ef477fa7f6d1980">llvm::truncated</a>.</p>


<p>Referenced by <a href="#a4eafbdaec23df0b928d64cf6d16c2831">readImpl</a>.</p>

</div>
</div>

### readNumber() {#a3692dc50c07c5eda5e01f891cc03047c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; T &gt; SampleProfileReaderGCC::readNumber ()</td>
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



<p>Declaration at line 902 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1603 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="#a392e2d3a5ec6cbcf083b943c63f4fdeb">GcovBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea7596fdd04dba990373ab2f3da0c7dd3f">llvm::malformed</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#af7db78adf47785867ea84d77ace26cc6">llvm::sampleprof::SampleProfileReader::reportError</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### readOneFunctionProfile() {#a98a6af42792c32db070dee8826e1412e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderGCC::readOneFunctionProfile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ae5dc26bf897525252cc02f75db0f1578">InlineCallStack</a> &amp; InlineStack, bool Update, uint32_t Offset)</td>
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



<p>Declaration at line 898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1696 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ab38820a59b382631568b3735469b0890">llvm::sampleprof::FunctionSamples::addBodySamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a951ceadc1dc24cb5041d80ca661c8e3e">llvm::sampleprof::FunctionSamples::addCalledTargetSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a8dda47f9492c59e96d8b43fa6244af20">llvm::sampleprof::FunctionSamples::addHeadSamples</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a58dc840fc84420b7f0b773794b8101c1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a9cb031e56118fb0d538ba72e408ec183">llvm::sampleprof::FunctionSamples::functionSamplesAt</a>, <a href="#a392e2d3a5ec6cbcf083b943c63f4fdeb">GcovBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#adb2786061d3e569b42b7d661ccc57484">llvm::sampleprof::FunctionSamples::getTotalSamples</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a7fbf1e7e1c95fffa247e7bba9f850584a525ad6441353eaf3d43be721b6d743c1">llvm::sampleprof::HIST_TYPE_INDIR_CALL_TOPN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea7596fdd04dba990373ab2f3da0c7dd3f">llvm::malformed</a>, <a href="#a4e59b0f8cf7428c8692ef42b6bc36a1b">Names</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#ad31357a0bab13543c1d9e22e22f33ec4">llvm::sampleprof::SampleProfileReader::Profiles</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a98a6af42792c32db070dee8826e1412e">readOneFunctionProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a677a143b2118c3ffdf3ecf58384a49cd">llvm::sampleprof::FunctionSamples::setFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbeaac273a9aa2a7a6e63ef477fa7f6d1980">llvm::truncated</a>.</p>


<p>Referenced by <a href="#aa53d5b8b15dd26564754966d3159f822">readFunctionProfiles</a> and <a href="#a98a6af42792c32db070dee8826e1412e">readOneFunctionProfile</a>.</p>

</div>
</div>

### readSectionTag() {#af817ec9dd6d3474c66b2212251c6e338}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderGCC::readSectionTag (uint32_t Expected)</td>
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

<p>Read the section tag and check that it's the same as <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a></span>.</p>

<p>Declaration at line 906 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1647 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="#a392e2d3a5ec6cbcf083b943c63f4fdeb">GcovBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea7596fdd04dba990373ab2f3da0c7dd3f">llvm::malformed</a>, <a href="#ab5bbfe5b0f863708d31b6ce2e126ec0c">skipNextWord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbeaac273a9aa2a7a6e63ef477fa7f6d1980">llvm::truncated</a>.</p>


<p>Referenced by <a href="#aa53d5b8b15dd26564754966d3159f822">readFunctionProfiles</a> and <a href="#a622597173a279123bf79b590ee419180">readNameTable</a>.</p>

</div>
</div>

### readString() {#a8e54d8ccf59b2b783a1254168ce468d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; StringRef &gt; SampleProfileReaderGCC::readString ()</td>
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



<p>Declaration at line 903 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1619 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="#a392e2d3a5ec6cbcf083b943c63f4fdeb">GcovBuffer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbeaac273a9aa2a7a6e63ef477fa7f6d1980">llvm::truncated</a>.</p>

</div>
</div>

### skipNextWord() {#ab5bbfe5b0f863708d31b6ce2e126ec0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderGCC::skipNextWord ()</td>
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



<p>Declaration at line 901 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1596 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="#a392e2d3a5ec6cbcf083b943c63f4fdeb">GcovBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbeaac273a9aa2a7a6e63ef477fa7f6d1980">llvm::truncated</a>.</p>


<p>Referenced by <a href="#a7e2ac14aece78da6927b8e8e698c5ce1">readHeader</a> and <a href="#af817ec9dd6d3474c66b2212251c6e338">readSectionTag</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### GcovBuffer {#a392e2d3a5ec6cbcf083b943c63f4fdeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCOVBuffer llvm::sampleprof::SampleProfileReaderGCC::GcovBuffer</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/gcov">GCOV</a> buffer containing the profile.</p>

<p>Definition at line 909 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#aa53d5b8b15dd26564754966d3159f822">readFunctionProfiles</a>, <a href="#a7e2ac14aece78da6927b8e8e698c5ce1">readHeader</a>, <a href="#a622597173a279123bf79b590ee419180">readNameTable</a>, <a href="#a3692dc50c07c5eda5e01f891cc03047c">readNumber</a>, <a href="#a98a6af42792c32db070dee8826e1412e">readOneFunctionProfile</a>, <a href="#af817ec9dd6d3474c66b2212251c6e338">readSectionTag</a>, <a href="#a8e54d8ccf59b2b783a1254168ce468d7">readString</a>, <a href="#a78d594511a420e0aa288e6cada80638a">SampleProfileReaderGCC</a> and <a href="#ab5bbfe5b0f863708d31b6ce2e126ec0c">skipNextWord</a>.</p>

</div>
</div>

### Names {#a4e59b0f8cf7428c8692ef42b6bc36a1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::string&gt; llvm::sampleprof::SampleProfileReaderGCC::Names</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> names in this profile.</p>

<p>Definition at line 912 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#a622597173a279123bf79b590ee419180">readNameTable</a> and <a href="#a98a6af42792c32db070dee8826e1412e">readOneFunctionProfile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### hasFormat() {#ade9bafe407ebfb2eed960233a4f5da22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileReaderGCC::hasFormat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &amp; Buffer)</td>
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

<p>Return true if <span class="doxyComputerOutput">Buffer</span> is in the format supported by this class.</p>

<p>Declaration at line 894 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 1836 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a317d9b9a39f8213c84429fbf54a7055f">llvm::sampleprof::SampleProfileReader::Buffer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#aa13d9a01b470d4ae7e0f1ea117f2e3dc">llvm::sampleprof::SampleProfileReader::create</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Attributes

### GCOVTagAFDOFileNames {#aa5c8f538e3e9aa9a3aecec509ee8d178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t llvm::sampleprof::SampleProfileReaderGCC::GCOVTagAFDOFileNames = 0xaa000000</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/gcov">GCOV</a> tags used to separate sections in the profile file.</p>

<p>Definition at line 915 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#a622597173a279123bf79b590ee419180">readNameTable</a>.</p>

</div>
</div>

### GCOVTagAFDOFunction {#a94582c22716e5b7c7ec357d5d2d8de97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t llvm::sampleprof::SampleProfileReaderGCC::GCOVTagAFDOFunction = 0xac000000</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 916 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Referenced by <a href="#aa53d5b8b15dd26564754966d3159f822">readFunctionProfiles</a>.</p>

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
