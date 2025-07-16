---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/profiledata/sampleprofreader-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SampleProfReader.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">llvm/ProfileData/SampleProfReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/profilesummary-h">llvm/IR/ProfileSummary.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">llvm/ProfileData/ProfileCommon.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">llvm/ProfileData/SampleProf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">llvm/Support/Compression.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">llvm/Support/ErrorOr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">llvm/Support/JSON.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/leb128-h">llvm/Support/LEB128.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lineiterator-h">llvm/Support/LineIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">llvm/Support/MD5.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">llvm/Support/MemoryBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">llvm/Support/VirtualFileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;algorithm&gt;
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;limits&gt;
#include &lt;memory&gt;
#include &lt;system_error&gt;
#include &lt;vector&gt;
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LineType { <a href="#afd074c27ba0a2809258258751b754f52">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f66983ff782c5a6bc67a19058c7ea6b">dumpFunctionProfileJson</a> (const FunctionSamples &amp;S, json::OStream &amp;JOS, bool TopLevel=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fd43a2ed35eec1123b619bf7237c8e0">ParseHead</a> (const StringRef &amp;Input, StringRef &amp;FName, uint64_t &amp;NumSamples, uint64_t &amp;NumHeadSamples)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/input">Input</a></span> as function head. <a href="#a1fd43a2ed35eec1123b619bf7237c8e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a528869d42ce7fca106b21792fe00bf0a">isOffsetLegal</a> (unsigned L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if line offset <span class="doxyComputerOutput">L</span> is legal (only has 16 bits). <a href="#a528869d42ce7fca106b21792fe00bf0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee16ef63867cb58a1e046d39fb99e49f">parseMetadata</a> (const StringRef &amp;Input, uint64_t &amp;FunctionHash, uint32_t &amp;Attributes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/input">Input</a></span> that contains metadata. <a href="#aee16ef63867cb58a1e046d39fb99e49f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e11393a870b05fc975c383371854ed5">ParseLine</a> (const StringRef &amp;Input, LineType &amp;LineTy, uint32_t &amp;Depth, uint64_t &amp;NumSamples, uint32_t &amp;LineOffset, uint32_t &amp;Discriminator, StringRef &amp;CalleeName, DenseMap&lt; StringRef, uint64_t &gt; &amp;TargetCountMap, uint64_t &amp;FunctionHash, uint32_t &amp;Attributes, bool &amp;IsFlat)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/input">Input</a></span> as line sample. <a href="#a8e11393a870b05fc975c383371854ed5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1579cd3c85df19630fb1ca933b2679c">getSecFlagsStr</a> (const SecHdrTableEntry &amp;Entry)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c882627d1252f1c30eb5bd284ed093b">setupMemoryBuffer</a> (const Twine &amp;Filename, vfs::FileSystem &amp;FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prepare a memory buffer for the contents of <span class="doxyComputerOutput">Filename</span>. <a href="#a0c882627d1252f1c30eb5bd284ed093b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93c1b2cdde2d2acc22f2a37f7eb36f2c">ProfileIsFSDisciminator</a>("profile-isfs", cl::Hidden, cl::init(false), cl::desc("Profile uses flow sensitive discriminators"))</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"samplepgo-reader"</td>
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

## Enumerations

### LineType {#afd074c27ba0a2809258258751b754f52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class LineType </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CallSiteProfile<a id="afd074c27ba0a2809258258751b754f52aa0e878d937063b60d7579f0a8dd6c413"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BodyProfile<a id="afd074c27ba0a2809258258751b754f52ae9d5d3b62ee70cbc11df84c2f39d9f12"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Metadata<a id="afd074c27ba0a2809258258751b754f52ace21470ab49d1d1976bc3dc72438c183"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### dumpFunctionProfileJson() {#a3f66983ff782c5a6bc67a19058c7ea6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void dumpFunctionProfileJson (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/json/ostream">json::OStream</a> &amp; JOS, bool TopLevel=false)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#a4754bca88e59468dba45df18b849920a">llvm::json::OStream::attribute</a>, <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#a7ff67320cc541a438d8fc170124af74f">llvm::json::OStream::attributeArray</a>, <a href="#a3f66983ff782c5a6bc67a19058c7ea6b">dumpFunctionProfileJson</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#afd62779d71a74d2db69f4fde48b37893">llvm::sampleprof::FunctionSamples::getBodySamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ae216a9dc4cce5948cec7fbf16ff462dd">llvm::sampleprof::FunctionSamples::getCallsiteSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a7ff8c2d016ae9169f35cdd1d1aaa1564">llvm::sampleprof::FunctionSamples::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a6206d4ca96e6f63a40327a7fa147f2a4">llvm::sampleprof::FunctionSamples::getHeadSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplerecord/#a6e5033adccbe0a93cc7c77cd89ed2fec">llvm::sampleprof::SampleRecord::getSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplerecord/#abe2b5ee88eea4c21f9efe473183744ed">llvm::sampleprof::SampleRecord::getSortedCallTargets</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#adb2786061d3e569b42b7d661ccc57484">llvm::sampleprof::FunctionSamples::getTotalSamples</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#a06d556674c46c15e5906f2f645f4fbe5">llvm::json::OStream::object</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid/#ac33ae101b77f66bd6b558c770a6256bc">llvm::sampleprof::FunctionId::str</a>.</p>


<p>Referenced by <a href="#a3f66983ff782c5a6bc67a19058c7ea6b">dumpFunctionProfileJson</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#ad1a3cf9f9ad94831f204a4654a423906">llvm::sampleprof::SampleProfileReader::dumpJson</a>.</p>

</div>
</div>

### getSecFlagsStr() {#aa1579cd3c85df19630fb1ca933b2679c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string getSecFlagsStr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sampleprof/sechdrtableentry">SecHdrTableEntry</a> &amp; Entry)</td>
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



<p>Definition at line 1424 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a3efc74fee0efccc34cb5a64de6b1d84a">llvm::sampleprof::hasSecFlag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a249a6a299581a44359596da9619a4b19a16052b6981a5cb6f18149f985d66ab87">llvm::sampleprof::SecFlagCompress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a7d0799e340cf7553a27f898ef20ad6f7a5121eb700a5270cadcb8ec87c2593288">llvm::sampleprof::SecFlagFixedLengthMD5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a249a6a299581a44359596da9619a4b19a303d1d200e078b6e1510e624147dfe0e">llvm::sampleprof::SecFlagFlat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#aa229d20f76a2d8473f321b97cb494462abbe7033a4a1f24db956320bb1a7b7ce3">llvm::sampleprof::SecFlagFSDiscriminator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#aa229d20f76a2d8473f321b97cb494462ad8375f4e079a5af243f36f91334691e7">llvm::sampleprof::SecFlagFullContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ad2f473dc3a871939a4781efc92f0931ba4771c0f8db64857edd1ee64cfde3edca">llvm::sampleprof::SecFlagHasAttribute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#aa229d20f76a2d8473f321b97cb494462a6517bd773ca68b78f926ec08f55daac3">llvm::sampleprof::SecFlagIsPreInlined</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ad2f473dc3a871939a4781efc92f0931ba538d11ebcb8192686ae93eb46ec92ebc">llvm::sampleprof::SecFlagIsProbeBased</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a7d0799e340cf7553a27f898ef20ad6f7a1780ac16db816da7bda99433dbdb73bf">llvm::sampleprof::SecFlagMD5Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#abed83dc828c8bfb55967efc3b9313758a3cc23f4782f1fd246c14392b45a2646f">llvm::sampleprof::SecFlagOrdered</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#aa229d20f76a2d8473f321b97cb494462ab8c5c1b9457b958b7c66a02adb2dc97a">llvm::sampleprof::SecFlagPartial</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a7d0799e340cf7553a27f898ef20ad6f7a27ba0d92f39f8d4651a98190c098df5d">llvm::sampleprof::SecFlagUniqSuffix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85aaa2da63cc16b51f0005debd3ae000a18">llvm::sampleprof::SecFuncMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85ae3b5e1c40206f7ac0a1e8b9c1f4fa4d7">llvm::sampleprof::SecFuncOffsetTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85a04e75d4659b0c502eb2280e6d6fd6378">llvm::sampleprof::SecNameTable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85a8c51d0a5a19b4b2ae76846092b479354">llvm::sampleprof::SecProfSummary</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#ab0f3253a66867b0999fc9d2be549268c">llvm::sampleprof::SampleProfileReaderExtBinaryBase::dumpSectionInfo</a>.</p>

</div>
</div>

### isOffsetLegal() {#a528869d42ce7fca106b21792fe00bf0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isOffsetLegal (unsigned L)</td>
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

<p>Returns true if line offset <span class="doxyComputerOutput">L</span> is legal (only has 16 bits).</p>

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>Referenced by <a href="#a8e11393a870b05fc975c383371854ed5">ParseLine</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a272ffb93f3958019735d7a4ef9bf22d2">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readCSNameTableSec</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a0320040b070e4fc2904794078a64e46c">llvm::sampleprof::SampleProfileReaderBinary::readProfile</a>.</p>

</div>
</div>

### ParseHead() {#a1fd43a2ed35eec1123b619bf7237c8e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ParseHead (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Input, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; FName, uint64_t &amp; NumSamples, uint64_t &amp; NumHeadSamples)</td>
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

<p>Parse <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/input">Input</a></span> as function head.</p>


<p>Parse one line of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/input">Input</a></span>, and update function name in <span class="doxyComputerOutput">FName</span>, function's total sample count in <span class="doxyComputerOutput">NumSamples</span>, function's entry count in <span class="doxyComputerOutput">NumHeadSamples</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if parsing is successful.</p></dd>
</dl>


<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#ac6f6906a46a807e4f041c463b04511fa">llvm::sampleprof::SampleProfileReaderText::hasFormat</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>.</p>

</div>
</div>

### ParseLine() {#a8e11393a870b05fc975c383371854ed5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ParseLine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Input, <a href="#afd074c27ba0a2809258258751b754f52">LineType</a> &amp; LineTy, uint32_t &amp; Depth, uint64_t &amp; NumSamples, uint32_t &amp; LineOffset, uint32_t &amp; Discriminator, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; CalleeName, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, uint64_t &gt; &amp; TargetCountMap, uint64_t &amp; FunctionHash, uint32_t &amp; Attributes, bool &amp; IsFlat)</td>
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

<p>Parse <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/input">Input</a></span> as line sample.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/input"&gt;Input&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>input line.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineTy</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of this line.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Depth</td>
<td class="doxyParamItemDescription"><p>the depth of the inline stack.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumSamples</td>
<td class="doxyParamItemDescription"><p>total samples of the line/inlined callsite.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineOffset</td>
<td class="doxyParamItemDescription"><p>line offset to the start of the function.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Discriminator</td>
<td class="doxyParamItemDescription"><p>discriminator of the line.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TargetCountMap</td>
<td class="doxyParamItemDescription"><p>map from indirect call target to count.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FunctionHash</td>
<td class="doxyParamItemDescription"><p>the function's CFG hash, used by pseudo probe.</p></td>
</tr>
</table>
</dd>
</dl>

<p>returns true if parsing is successful.</p>


<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp/#a5a7ac0d6f6157bfa62400fdc021157dc">Attributes</a>, <a href="#afd074c27ba0a2809258258751b754f52ae9d5d3b62ee70cbc11df84c2f39d9f12">BodyProfile</a>, <a href="#afd074c27ba0a2809258258751b754f52aa0e878d937063b60d7579f0a8dd6c413">CallSiteProfile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aab312a8386488873bac2eddfc67c22be">llvm::StringRef::find</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae851887270f35d2a2670a79b9833d45b">llvm::StringRef::find_first_not_of</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a93b15a8c0022febbe39d17ab933737a8">llvm::StringRef::find_first_of</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7a7c222449f3208a532168c90bfb654d">llvm::StringRef::find_last_of</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1881146f2dcc2ca57c9c5f77f938db9d">llvm::StringRef::getAsInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a12d4f37888b638bcbd9fc0201492c776">isDigit</a>, <a href="#a528869d42ce7fca106b21792fe00bf0a">isOffsetLegal</a>, <a href="#afd074c27ba0a2809258258751b754f52ace21470ab49d1d1976bc3dc72438c183">Metadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref/#ad0f54a163ac500b144590640c6f1eb6b">anonymous{Path.cpp}::StringRef::npos</a>, <a href="#aee16ef63867cb58a1e046d39fb99e49f">parseMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>.</p>

</div>
</div>

### parseMetadata() {#aee16ef63867cb58a1e046d39fb99e49f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool parseMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Input, uint64_t &amp; FunctionHash, uint32_t &amp; Attributes)</td>
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

<p>Parse <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/input">Input</a></span> that contains metadata.</p>


<p>Possible metadata:</p>


<ul class="doxyList ">
<li>CFG Checksum information: !CFGChecksum: 12345</li>
<li>CFG Checksum information: !Attributes: 1 Stores the FunctionHash (a.k.a. CFG Checksum) into <span class="doxyComputerOutput">FunctionHash</span>.</li>
</ul>

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp/#a5a7ac0d6f6157bfa62400fdc021157dc">Attributes</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1881146f2dcc2ca57c9c5f77f938db9d">llvm::StringRef::getAsInteger</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/metadataloader/#a1d7b1e6efd2239f16d80d9eebf7cf721">llvm::MetadataLoader::parseFunctionMetadata</a>, <a href="#a8e11393a870b05fc975c383371854ed5">ParseLine</a> and <a href="/web-llvm/docs/api/classes/llvm/metadataloader/#a9d55ca912c114ec1720fcaf32dd4360d">llvm::MetadataLoader::parseModuleMetadata</a>.</p>

</div>
</div>

### setupMemoryBuffer() {#a0c882627d1252f1c30eb5bd284ed093b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; MemoryBuffer &gt; &gt; setupMemoryBuffer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Filename, <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a> &amp; FS)</td>
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

<p>Prepare a memory buffer for the contents of <span class="doxyComputerOutput">Filename</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an error code indicating the status of the buffer.</p></dd>
</dl>


<p>Definition at line 1883 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#ae56e946cf4266646c30b0898033b88bc">llvm::MemoryBuffer::getSTDIN</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ProfileIsFSDisciminator {#a93c1b2cdde2d2acc22f2a37f7eb36f2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ProfileIsFSDisciminator("profile-isfs", cl::Hidden, cl::init(false), cl::desc("Profile uses flow sensitive discriminators"))</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a5ad89ebfc9008ab04dbaf011e1f1e8db">llvm::sampleprof::SampleProfileReaderBinary::readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadergcc/#a4eafbdaec23df0b928d64cf6d16c2831">llvm::sampleprof::SampleProfileReaderGCC::readImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"samplepgo-reader"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
