---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprof/sampleprofilereadertext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SampleProfileReaderText` Class



## Declaration

<div class="doxyDeclaration">
class llvm::sampleprof::SampleProfileReaderText { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a287358d6113997c07bad1ba25060c1fd">SampleProfileReaderText</a> (std::unique_ptr&lt; MemoryBuffer &gt; B, LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ddd0f30c68d03e690fb07d5b436beb4">readHeader</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read and validate the file header. <a href="#a6ddd0f30c68d03e690fb07d5b436beb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8f17958c50ff564f5817c64850da276">readImpl</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read sample profiles from the associated file. <a href="#aa8f17958c50ff564f5817c64850da276">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d7cac62a20fd2eb109d1331077ad4af">setProfileUseMD5</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Text format sample profile does not support <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> for now. <a href="#a4d7cac62a20fd2eb109d1331077ad4af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::list&lt; <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#abc45b32c93302a515b730f86807dd80c">SampleContextFrameVector</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24c2f2b3819abaf335a793f55edd40e9">CSNameTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CSNameTable is used to save full context vectors. <a href="#a24c2f2b3819abaf335a793f55edd40e9">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6f6906a46a807e4f041c463b04511fa">hasFormat</a> (const MemoryBuffer &amp;Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">Buffer</span> is in the format supported by this class. <a href="#ac6f6906a46a807e4f041c463b04511fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SampleProfileReaderText() {#a287358d6113997c07bad1ba25060c1fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::SampleProfileReaderText::SampleProfileReaderText (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; B, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a7df3a90aaf7409ace0a2a56f5e539477">llvm::sampleprof::SampleProfileReader::SampleProfileReader</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66ecaeaa49c6cfdca426288f7d4bc9378db35">llvm::sampleprof::SPF_Text</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### readHeader() {#a6ddd0f30c68d03e690fb07d5b436beb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::sampleprof::SampleProfileReaderText::readHeader ()</td>
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

<p>Read and validate the file header.</p>

<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>

</div>
</div>

### readImpl() {#aa8f17958c50ff564f5817c64850da276}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileReaderText::readImpl ()</td>
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


<p>Load samples from a text file.</p>


<p>See the documentation at the top of the file for an explanation of the expected format.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the file was loaded successfully, false otherwise.</p></dd>
</dl>


<p>Declaration at line 620 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ab38820a59b382631568b3735469b0890">llvm::sampleprof::FunctionSamples::addBodySamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a951ceadc1dc24cb5041d80ca661c8e3e">llvm::sampleprof::FunctionSamples::addCalledTargetSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a8dda47f9492c59e96d8b43fa6244af20">llvm::sampleprof::FunctionSamples::addHeadSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a263b944b1e1d1b8906ccfa19a565d2ed">llvm::sampleprof::FunctionSamples::addTotalSamples</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp/#a5a7ac0d6f6157bfa62400fdc021157dc">Attributes</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#afd074c27ba0a2809258258751b754f52ae9d5d3b62ee70cbc11df84c2f39d9f12">BodyProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a317d9b9a39f8213c84429fbf54a7055f">llvm::sampleprof::SampleProfileReader::Buffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#afd074c27ba0a2809258258751b754f52aa0e878d937063b60d7579f0a8dd6c413">CallSiteProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a862a85fc052e3da0f7109bc54ef4998d">llvm::sampleprof::SampleProfileReader::computeSummary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a9c9cec0dc85381494fb418ae0e88a40fa9a35039dfc5e52a8ee9289957a726bee">llvm::sampleprof::ContextShouldBeInlined</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a1bd87b526bf1a09487cf4d75d9e638ef">llvm::sampleprof::SampleProfileReader::CSProfileCount</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#afe19488a2996e10c93bccbe3d332ca93">llvm::sampleprof::SampleProfileReader::Ctx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1cde8c8828756cdaf2a93260e247ae31">llvm::DS_Warning</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae851887270f35d2a2670a79b9833d45b">llvm::StringRef::find_first_not_of</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ad117577730085f895045fc7ff90d8fc2">llvm::sampleprof::FunctionSamples::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a8c0b29b235366b7d2447ab4dc39398ed">llvm::sampleprof::SampleProfileReader::getDiscriminatorMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#a3f47a41fc180017373f06a00976d7c5c">llvm::sampleprof::SampleContext::hasContext</a>, <a href="/web-llvm/docs/api/classes/llvm/line-iterator/#a617941704a472090ba3304c9daf1c37f">llvm::line_iterator::is_at_eof</a>, <a href="/web-llvm/docs/api/classes/llvm/line-iterator/#a51eb9a429555dd682d9b265cff7f869f">llvm::line_iterator::line_number</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea7596fdd04dba990373ab2f3da0c7dd3f">llvm::malformed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6af78b474302640c3fd76f2e8031f9f9">llvm::mergeSampleProfErrors</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#afd074c27ba0a2809258258751b754f52ace21470ab49d1d1976bc3dc72438c183">Metadata</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a1fd43a2ed35eec1123b619bf7237c8e0">ParseHead</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a8e11393a870b05fc975c383371854ed5">ParseLine</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a53cef5334d9e6535928ce4d79e7529e3">llvm::sampleprof::SampleProfileReader::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ac78db34e62da1555e9b84b5b5b1d907d">llvm::sampleprof::FunctionSamples::ProfileIsFS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#ab3c8e7a5bebd5fa73b577fdc7677f7a5">llvm::sampleprof::SampleProfileReader::ProfileIsFS</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a93c1b2cdde2d2acc22f2a37f7eb36f2c">ProfileIsFSDisciminator</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a08b33b498078ac3694a992f4ab8a5761">llvm::sampleprof::FunctionSamples::ProfileIsPreInlined</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a09599626d454548b75a8508733b742ce">llvm::sampleprof::SampleProfileReader::ProfileIsPreInlined</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa37fe7429ffcf70c306c27a55d714d31">llvm::sampleprof::FunctionSamples::ProfileIsProbeBased</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#af3bd0368cb44b2cc97123f03de71efaa">llvm::sampleprof::SampleProfileReader::ProfileIsProbeBased</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#ad31357a0bab13543c1d9e22e22f33ec4">llvm::sampleprof::SampleProfileReader::Profiles</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#af7db78adf47785867ea84d77ace26cc6">llvm::sampleprof::SampleProfileReader::reportError</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#aa7894022c49174ef967469c3ddd81857">llvm::sampleprof::SampleContext::setAllAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a677a143b2118c3ffdf3ecf58384a49cd">llvm::sampleprof::FunctionSamples::setFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ac015e530d60203906c93e241682e8359">llvm::sampleprof::FunctionSamples::setFunctionHash</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a3a8cd3b6849f62c8ff4b44233374747d">llvm::sampleprof::SampleProfileReader::SkipFlatProf</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>

</div>
</div>

### setProfileUseMD5() {#a4d7cac62a20fd2eb109d1331077ad4af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleProfileReaderText::setProfileUseMD5 ()</td>
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

<p>Text format sample profile does not support <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> for now.</p>

<p>Definition at line 626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CSNameTable {#a24c2f2b3819abaf335a793f55edd40e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::list&lt;SampleContextFrameVector&gt; llvm::sampleprof::SampleProfileReaderText::CSNameTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CSNameTable is used to save full context vectors.</p>


<p>This serves as an underlying immutable buffer for all clients.</p>


<p>Definition at line 631 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### hasFormat() {#ac6f6906a46a807e4f041c463b04511fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileReaderText::hasFormat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &amp; Buffer)</td>
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

<p>Declaration at line 623 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">SampleProfReader.h</a>, definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp">SampleProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a317d9b9a39f8213c84429fbf54a7055f">llvm::sampleprof::SampleProfileReader::Buffer</a>, <a href="/web-llvm/docs/api/classes/llvm/line-iterator/#a617941704a472090ba3304c9daf1c37f">llvm::line_iterator::is_at_eof</a> and <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a1fd43a2ed35eec1123b619bf7237c8e0">ParseHead</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#aa13d9a01b470d4ae7e0f1ea117f2e3dc">llvm::sampleprof::SampleProfileReader::create</a>.</p>

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
