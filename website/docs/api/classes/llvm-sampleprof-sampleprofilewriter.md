---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprof/sampleprofilewriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SampleProfileWriter` Class Reference

<p>Sample-based profile writer. Base class. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sampleprof::SampleProfileWriter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">llvm/ProfileData/SampleProfWriter.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary">SampleProfileWriterBinary</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sample-based profile writer (binary format). <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext">SampleProfileWriterText</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sample-based profile writer (text format). <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05982c1b3c99df840aa15e0fe16eddf1">SampleProfileWriter</a> (std::unique_ptr&lt; raw_ostream &gt; &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af47a62f713da29b669d9bae9d535de4f">~SampleProfileWriter</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e194ca6bd68c52a092c42d99196797f">writeSample</a> (const FunctionSamples &amp;S)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write sample profiles in <span class="doxyComputerOutput">S</span>. <a href="#a2e194ca6bd68c52a092c42d99196797f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6beceed7eead102e4005a27cc641a42">write</a> (const SampleProfileMap &amp;ProfileMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write all the sample profiles in the given map of samples. <a href="#af6beceed7eead102e4005a27cc641a42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9283506633cf544e4a6163c0133fc769">writeWithSizeLimit</a> (SampleProfileMap &amp;ProfileMap, size_t OutputSizeLimit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write sample profiles up to given size limit, using the pruning strategy to drop some functions if necessary. <a href="#a9283506633cf544e4a6163c0133fc769">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a472d2f43996e9c2f61ef72460c43cc48">getOutputStream</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aae683827b6e507aa9603eb09a8dae4">setProfileSymbolList</a> (ProfileSymbolList *PSL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a799178723556c0d4635386ac4300b3fd">setToCompressAllSections</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b3ae82a37986d0efed005e5511408ba">setUseMD5</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a583b5d3f2d92a51c0c153277d24faa4e">setPartialProfile</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a026f3b1f5652dd6bbe5393979ed3b39d">setUseCtxSplitLayout</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acca4b6e94c0b8a5b7c5d7cda43f7d997">writeHeader</a> (const SampleProfileMap &amp;ProfileMap)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a file header for the profile file. <a href="#acca4b6e94c0b8a5b7c5d7cda43f7d997">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6467bcd55ce5f034a9c0f4007ff92889">writeFuncProfiles</a> (const SampleProfileMap &amp;ProfileMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a383a9c6d7b337512fa69de542cec0375">writeWithSizeLimitInternal</a> (SampleProfileMap &amp;ProfileMap, size_t OutputSizeLimit, FunctionPruningStrategy *Strategy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f8b2ab39ae70cd859c323fd97219c23">computeSummary</a> (const SampleProfileMap &amp;ProfileMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute summary for this profile. <a href="#a4f8b2ab39ae70cd859c323fd97219c23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9e64ece161ef85d0a4741f4890762a7">LineCount</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For writeWithSizeLimit in text mode, each newline takes 1 additional byte on Windows when actually written to the file, but not written to a memory buffer. <a href="#ac9e64ece161ef85d0a4741f4890762a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bc387785b288e17a87e9494b57cb937">OutputStream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Output stream where to emit the profile to. <a href="#a6bc387785b288e17a87e9494b57cb937">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/profilesummary">ProfileSummary</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24354d300d134c2a879f6d8a64cca025">Summary</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Profile summary. <a href="#a24354d300d134c2a879f6d8a64cca025">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66ec">SampleProfileFormat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a365a5ded4e755f745dc95795c798fa84">Format</a> = <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66eca71fa511e217d0835567f7d919aab6d02">SPF_None</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Profile format. <a href="#a365a5ded4e755f745dc95795c798fa84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter">SampleProfileWriter</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9f37e421f903ad877a91c1ca056f4ee">create</a> (StringRef Filename, SampleProfileFormat Format)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Profile writer factory. <a href="#ac9f37e421f903ad877a91c1ca056f4ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter">SampleProfileWriter</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61029509fbcbee90e8fc145701a79f07">create</a> (std::unique_ptr&lt; raw_ostream &gt; &amp;OS, SampleProfileFormat Format)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new stream writer based on the value of <span class="doxyComputerOutput">Format</span>. <a href="#a61029509fbcbee90e8fc145701a79f07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Sample-based profile writer. Base class.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### SampleProfileWriter() {#a05982c1b3c99df840aa15e0fe16eddf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::SampleProfileWriter::SampleProfileWriter (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &gt; &amp; OS)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a6bc387785b288e17a87e9494b57cb937">OutputStream</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a0dc0d64eb352acfe499cccd772a04dbe">llvm::sampleprof::SampleProfileWriterBinary::SampleProfileWriterBinary</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#a1abeacbefd30b57fbd69b76be62790c0">llvm::sampleprof::SampleProfileWriterText::SampleProfileWriterText</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SampleProfileWriter() {#af47a62f713da29b669d9bae9d535de4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::sampleprof::SampleProfileWriter::~SampleProfileWriter ()</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getOutputStream() {#a472d2f43996e9c2f61ef72460c43cc48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; llvm::sampleprof::SampleProfileWriter::getOutputStream ()</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Reference <a href="#a6bc387785b288e17a87e9494b57cb937">OutputStream</a>.</p>

</div>
</div>

### setPartialProfile() {#a583b5d3f2d92a51c0c153277d24faa4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::sampleprof::SampleProfileWriter::setPartialProfile ()</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

### setProfileSymbolList() {#a9aae683827b6e507aa9603eb09a8dae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::sampleprof::SampleProfileWriter::setProfileSymbolList (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/profilesymbollist">ProfileSymbolList</a> * PSL)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

### setToCompressAllSections() {#a799178723556c0d4635386ac4300b3fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::sampleprof::SampleProfileWriter::setToCompressAllSections ()</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

### setUseCtxSplitLayout() {#a026f3b1f5652dd6bbe5393979ed3b39d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::sampleprof::SampleProfileWriter::setUseCtxSplitLayout ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

### setUseMD5() {#a9b3ae82a37986d0efed005e5511408ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::sampleprof::SampleProfileWriter::setUseMD5 ()</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

### write() {#af6beceed7eead102e4005a27cc641a42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriter::write (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; ProfileMap)</td>
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

<p>Write all the sample profiles in the given map of samples.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>status code of the file update operation.</p></dd>
</dl>


<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>, <a href="#a6467bcd55ce5f034a9c0f4007ff92889">writeFuncProfiles</a> and <a href="#acca4b6e94c0b8a5b7c5d7cda43f7d997">writeHeader</a>.</p>


<p>Referenced by <a href="#a383a9c6d7b337512fa69de542cec0375">writeWithSizeLimitInternal</a>.</p>

</div>
</div>

### writeSample() {#a2e194ca6bd68c52a092c42d99196797f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::error_code llvm::sampleprof::SampleProfileWriter::writeSample (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write sample profiles in <span class="doxyComputerOutput">S</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>status code of the file update operation.</p></dd>
</dl>


<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Referenced by <a href="#a6467bcd55ce5f034a9c0f4007ff92889">writeFuncProfiles</a>.</p>

</div>
</div>

### writeWithSizeLimit() {#a9283506633cf544e4a6163c0133fc769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FunctionPruningStrategy = DefaultFunctionPruningStrategy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::sampleprof::SampleProfileWriter::writeWithSizeLimit (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; ProfileMap, size_t OutputSizeLimit)</td>
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

<p>Write sample profiles up to given size limit, using the pruning strategy to drop some functions if necessary.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>status code of the file update operation.</p></dd>
</dl>


<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Reference <a href="#a383a9c6d7b337512fa69de542cec0375">writeWithSizeLimitInternal</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### computeSummary() {#a4f8b2ab39ae70cd859c323fd97219c23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileWriter::computeSummary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; ProfileMap)</td>
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

<p>Compute summary for this profile.</p>

<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 933 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprofilesummarybuilder/#aa77c45e5b6c316812092a7e8a1e30143">llvm::SampleProfileSummaryBuilder::computeSummaryForProfiles</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#a9b2e51220aabb88a132d3bc8fbdf5a66">llvm::ProfileSummaryBuilder::DefaultCutoffs</a> and <a href="#a24354d300d134c2a879f6d8a64cca025">Summary</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#ab7422586efd8f803b17475cfc2e97329">llvm::sampleprof::SampleProfileWriterBinary::writeHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a33203b3c9366fd57c4d7d30f1f4c83b3">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeOneSection</a>.</p>

</div>
</div>

### writeFuncProfiles() {#a6467bcd55ce5f034a9c0f4007ff92889}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriter::writeFuncProfiles (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; ProfileMap)</td>
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



<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a11f675e2f1396d64eefeaf67cdce624e">llvm::sampleprof::sortFuncProfiles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a> and <a href="#a2e194ca6bd68c52a092c42d99196797f">writeSample</a>.</p>


<p>Referenced by <a href="#af6beceed7eead102e4005a27cc641a42">write</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a33203b3c9366fd57c4d7d30f1f4c83b3">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeOneSection</a>.</p>

</div>
</div>

### writeHeader() {#acca4b6e94c0b8a5b7c5d7cda43f7d997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::error_code llvm::sampleprof::SampleProfileWriter::writeHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; ProfileMap)</td>
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

<p>Write a file header for the profile file.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Referenced by <a href="#af6beceed7eead102e4005a27cc641a42">write</a>.</p>

</div>
</div>

### writeWithSizeLimitInternal() {#a383a9c6d7b337512fa69de542cec0375}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriter::writeWithSizeLimitInternal (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; ProfileMap, size_t OutputSizeLimit, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionpruningstrategy">FunctionPruningStrategy</a> * Strategy)</td>
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



<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a7b68be12c974b6b70bc86062f221a344">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionpruningstrategy/#a3bb7affe9c405afd71075e2e56513db4">llvm::sampleprof::FunctionPruningStrategy::Erase</a>, <a href="#a365a5ded4e755f745dc95795c798fa84">Format</a>, <a href="#ac9e64ece161ef85d0a4741f4890762a7">LineCount</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a6bc387785b288e17a87e9494b57cb937">OutputStream</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66ecaeaa49c6cfdca426288f7d4bc9378db35">llvm::sampleprof::SPF_Text</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea7a45a1d1bfe36a2c1205fbd1b450d80a">llvm::too_large</a> and <a href="#af6beceed7eead102e4005a27cc641a42">write</a>.</p>


<p>Referenced by <a href="#a9283506633cf544e4a6163c0133fc769">writeWithSizeLimit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Format {#a365a5ded4e755f745dc95795c798fa84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SampleProfileFormat llvm::sampleprof::SampleProfileWriter::Format = <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66eca71fa511e217d0835567f7d919aab6d02">SPF_None</a></td>
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

<p>Profile format.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Referenced by <a href="#a61029509fbcbee90e8fc145701a79f07">create</a>, <a href="#ac9f37e421f903ad877a91c1ca056f4ee">create</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a1d1f868a7aef12e52549932a3b0dea3f">llvm::sampleprof::SampleProfileWriterBinary::SampleProfileWriter::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#a1d1f868a7aef12e52549932a3b0dea3f">llvm::sampleprof::SampleProfileWriterText::SampleProfileWriter::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#ab7422586efd8f803b17475cfc2e97329">llvm::sampleprof::SampleProfileWriterBinary::writeHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a704b84bdc47710f22197508b631e1d09">llvm::sampleprof::SampleProfileWriterBinary::writeMagicIdent</a> and <a href="#a383a9c6d7b337512fa69de542cec0375">writeWithSizeLimitInternal</a>.</p>

</div>
</div>

### LineCount {#ac9e64ece161ef85d0a4741f4890762a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::sampleprof::SampleProfileWriter::LineCount</td>
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

<p>For writeWithSizeLimit in text mode, each newline takes 1 additional byte on Windows when actually written to the file, but not written to a memory buffer.</p>


<p>This needs to be accounted for when rewriting the profile.</p>


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#a4342baa58c95a690388087e0adee6a03">llvm::sampleprof::SampleProfileWriterText::writeHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#acdb8f85283e93399278cbe5363f944da">llvm::sampleprof::SampleProfileWriterText::writeSample</a> and <a href="#a383a9c6d7b337512fa69de542cec0375">writeWithSizeLimitInternal</a>.</p>

</div>
</div>

### OutputStream {#a6bc387785b288e17a87e9494b57cb937}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;raw_ostream&gt; llvm::sampleprof::SampleProfileWriter::OutputStream</td>
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

<p>Output stream where to emit the profile to.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#abcb41826a24e17e2c7a615abcf988cab">llvm::sampleprof::SampleProfileWriterExtBinaryBase::addNewSection</a>, <a href="#a472d2f43996e9c2f61ef72460c43cc48">getOutputStream</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#ab6d9741f6d03790df898209e50342f2b">llvm::sampleprof::SampleProfileWriterExtBinaryBase::markSectionStart</a>, <a href="#a05982c1b3c99df840aa15e0fe16eddf1">SampleProfileWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#ae7c088ecf1befc97ec9b4d36f30ae06d">llvm::sampleprof::SampleProfileWriterBinary::writeBody</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a4bc88eec2b14372dd70f9274feeee6bb">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeCSNameIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a449a2a9cd2cebab93b804f4a6cbaea5a">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeCSNameTableSection</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a96315b9b9bda521e4026e537c7d9f139">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a3b40af607c43587edc28f8788e07cefd">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeFuncOffsetTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a704b84bdc47710f22197508b631e1d09">llvm::sampleprof::SampleProfileWriterBinary::writeMagicIdent</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#af63eb7fece187a61531bdb743120f3c7">llvm::sampleprof::SampleProfileWriterBinary::writeNameIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a61e7926d242ffc3cac8fc92591b4178d">llvm::sampleprof::SampleProfileWriterBinary::writeNameTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a8da3b86e5070140af1716c64925a0495">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeNameTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a33203b3c9366fd57c4d7d30f1f4c83b3">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeOneSection</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#aac620f9ad115b9f0db02f271dde1b586">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeProfileSymbolListSection</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#aa8f09f0411e75db5fd532622f3e169bc">llvm::sampleprof::SampleProfileWriterBinary::writeSample</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#af5cddc155fef09dd03f4493e99524109">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeSample</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#acdb8f85283e93399278cbe5363f944da">llvm::sampleprof::SampleProfileWriterText::writeSample</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a74c686413929f11d2301cb47bec0fcdb">llvm::sampleprof::SampleProfileWriterBinary::writeSummary</a> and <a href="#a383a9c6d7b337512fa69de542cec0375">writeWithSizeLimitInternal</a>.</p>

</div>
</div>

### Summary {#a24354d300d134c2a879f6d8a64cca025}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ProfileSummary&gt; llvm::sampleprof::SampleProfileWriter::Summary</td>
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

<p>Profile summary.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Referenced by <a href="#a4f8b2ab39ae70cd859c323fd97219c23">computeSummary</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a74c686413929f11d2301cb47bec0fcdb">llvm::sampleprof::SampleProfileWriterBinary::writeSummary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#ac9f37e421f903ad877a91c1ca056f4ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; SampleProfileWriter &gt; &gt; SampleProfileWriter::create (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66ec">SampleProfileFormat</a> Format)</td>
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

<p>Profile writer factory.</p>


<p>Create a sample profile file writer based on the specified format.</p>


<p>Create a new file writer based on the value of <span class="doxyComputerOutput">Format</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Filename</td>
<td class="doxyParamItemDescription"><p>The file to create.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Format</td>
<td class="doxyParamItemDescription"><p>Encoding format for the profile file.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an error code indicating the status of the created writer.</p></dd>
</dl>


<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 884 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="#ac9f37e421f903ad877a91c1ca056f4ee">create</a>, <a href="#a365a5ded4e755f745dc95795c798fa84">Format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a8ae6a0a158ab49e5bbe92cbc2cabcbcd">llvm::sys::fs::OF_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695ab505c2c79499fbe180989bffbf108a50">llvm::sys::fs::OF_TextWithCRLF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66eca32718b681c57eb77010cc459b8176cc3">llvm::sampleprof::SPF_Binary</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66eca46bc649d3816ce5a94ef37c9e826c8ff">llvm::sampleprof::SPF_Ext_Binary</a>.</p>


<p>Referenced by <a href="#ac9f37e421f903ad877a91c1ca056f4ee">create</a>.</p>

</div>
</div>

### create() {#a61029509fbcbee90e8fc145701a79f07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; SampleProfileWriter &gt; &gt; SampleProfileWriter::create (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &gt; &amp; OS, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66ec">SampleProfileFormat</a> Format)</td>
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

<p>Create a new stream writer based on the value of <span class="doxyComputerOutput">Format</span>.</p>


<p>Create a sample profile stream writer based on the specified format.</p>


<p>For testing.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>The output stream to store the profile data to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Format</td>
<td class="doxyParamItemDescription"><p>Encoding format for the profile file.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an error code indicating the status of the created writer.</p></dd>
</dl>


<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 905 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="#a365a5ded4e755f745dc95795c798fa84">Format</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa37fe7429ffcf70c306c27a55d714d31">llvm::sampleprof::FunctionSamples::ProfileIsProbeBased</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66eca32718b681c57eb77010cc459b8176cc3">llvm::sampleprof::SPF_Binary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66eca46bc649d3816ce5a94ef37c9e826c8ff">llvm::sampleprof::SPF_Ext_Binary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66eca4f20635356824ecd5dac2016c1dfc018">llvm::sampleprof::SPF_GCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66ecaeaa49c6cfdca426288f7d4bc9378db35">llvm::sampleprof::SPF_Text</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbead5b649348c44c8f1f89cb53fe7604f64">llvm::unrecognized_format</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea8d902aa3f1e5c961bc0aab5ac41ccbe2">llvm::unsupported_writing_format</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
