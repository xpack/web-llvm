---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprof/sampleprofilewritertext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SampleProfileWriterText` Class Reference

<p>Sample-based profile writer (text format). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sampleprof::SampleProfileWriterText { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">llvm/ProfileData/SampleProfWriter.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter">SampleProfileWriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sample-based profile writer. Base class. <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter">SampleProfileWriter</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d1f868a7aef12e52549932a3b0dea3f">SampleProfileWriter::create</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1abeacbefd30b57fbd69b76be62790c0">SampleProfileWriterText</a> (std::unique_ptr&lt; raw_ostream &gt; &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdb8f85283e93399278cbe5363f944da">writeSample</a> (const FunctionSamples &amp;S) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write samples to a text file. <a href="#acdb8f85283e93399278cbe5363f944da">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4342baa58c95a690388087e0adee6a03">writeHeader</a> (const SampleProfileMap &amp;ProfileMap) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a file header for the profile file. <a href="#a4342baa58c95a690388087e0adee6a03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51a6ef00bcfe92b4150da135a27e4bdf">setUseCtxSplitLayout</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab33d18250a9ddd3675d2c81c8718aa46">Indent</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indent level to use when writing. <a href="#ab33d18250a9ddd3675d2c81c8718aa46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b8422817129882c5629dcbad13f3aeb">MarkFlatProfiles</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If set, writes metadata "!Flat" to functions without inlined functions. <a href="#a3b8422817129882c5629dcbad13f3aeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Sample-based profile writer (text format).</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<div class="doxySectionDef">

## Friends

### SampleProfileWriter::create {#a1d1f868a7aef12e52549932a3b0dea3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter">SampleProfileWriter</a> &gt; &gt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &gt; &amp; OS, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66ec">SampleProfileFormat</a> Format</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a365a5ded4e755f745dc95795c798fa84">llvm::sampleprof::SampleProfileWriter::Format</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### SampleProfileWriterText() {#a1abeacbefd30b57fbd69b76be62790c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::SampleProfileWriterText::SampleProfileWriterText (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &gt; &amp; OS)</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a05982c1b3c99df840aa15e0fe16eddf1">llvm::sampleprof::SampleProfileWriter::SampleProfileWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### writeSample() {#acdb8f85283e93399278cbe5363f944da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterText::writeSample (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; S)</td>
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

<p>Write samples to a text file.</p>


<p>Note: it may be tempting to implement this in terms of <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#adca18b92b535ad86d151efc86442027d">FunctionSamples::print()</a>. Please don't. The dump functionality is intended for debugging and has no specified form.</p>


<p>The format used here is more structured and deliberate because it needs to be parsed by the <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext">SampleProfileReaderText</a> class.</p>


<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplesorter/#a63724eb0b03848a61809932b0d5a63a7">llvm::sampleprof::SampleSorter&lt; LocationT, SampleT &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#ac14fcf43c57c449e8398370de8d9a2dc">llvm::sampleprof::SampleContext::getAllAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#afd62779d71a74d2db69f4fde48b37893">llvm::sampleprof::FunctionSamples::getBodySamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ae216a9dc4cce5948cec7fbf16ff462dd">llvm::sampleprof::FunctionSamples::getCallsiteSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ad117577730085f895045fc7ff90d8fc2">llvm::sampleprof::FunctionSamples::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a7ff8c2d016ae9169f35cdd1d1aaa1564">llvm::sampleprof::FunctionSamples::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a7ffff5be739dfce8ccdb944c3f485306">llvm::sampleprof::FunctionSamples::getFunctionHash</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a6206d4ca96e6f63a40327a7fa147f2a4">llvm::sampleprof::FunctionSamples::getHeadSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplerecord/#a6e5033adccbe0a93cc7c77cd89ed2fec">llvm::sampleprof::SampleRecord::getSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplerecord/#abe2b5ee88eea4c21f9efe473183744ed">llvm::sampleprof::SampleRecord::getSortedCallTargets</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#adb2786061d3e569b42b7d661ccc57484">llvm::sampleprof::FunctionSamples::getTotalSamples</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#ac9e64ece161ef85d0a4741f4890762a7">llvm::sampleprof::SampleProfileWriter::LineCount</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a6bc387785b288e17a87e9494b57cb937">llvm::sampleprof::SampleProfileWriter::OutputStream</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa37fe7429ffcf70c306c27a55d714d31">llvm::sampleprof::FunctionSamples::ProfileIsProbeBased</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#ade2e9346cc9a993d02dab4742aff2bdf">llvm::sampleprof::SampleContext::toString</a> and <a href="#acdb8f85283e93399278cbe5363f944da">writeSample</a>.</p>


<p>Referenced by <a href="#acdb8f85283e93399278cbe5363f944da">writeSample</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### setUseCtxSplitLayout() {#a51a6ef00bcfe92b4150da135a27e4bdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleProfileWriterText::setUseCtxSplitLayout ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

### writeHeader() {#a4342baa58c95a690388087e0adee6a03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::sampleprof::SampleProfileWriterText::writeHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; ProfileMap)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write a file header for the profile file.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#ac9e64ece161ef85d0a4741f4890762a7">llvm::sampleprof::SampleProfileWriter::LineCount</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Indent {#ab33d18250a9ddd3675d2c81c8718aa46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sampleprof::SampleProfileWriterText::Indent = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indent level to use when writing.</p>


<p>This is used when printing inlined callees.</p>


<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

### MarkFlatProfiles {#a3b8422817129882c5629dcbad13f3aeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleProfileWriterText::MarkFlatProfiles = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If set, writes metadata "!Flat" to functions without inlined functions.</p>


<p>This flag is for manual inspection only, it has no effect for the profile reader because a text sample profile is read sequentially and functions cannot be skipped.</p>


<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
