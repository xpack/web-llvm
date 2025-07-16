---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprof/sampleprofilewriterbinary
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SampleProfileWriterBinary` Class Reference

<p>Sample-based profile writer (binary format). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sampleprof::SampleProfileWriterBinary { ... }
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase">SampleProfileWriterExtBinaryBase</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterrawbinary">SampleProfileWriterRawBinary</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dc0d64eb352acfe499cccd772a04dbe">SampleProfileWriterBinary</a> (std::unique_ptr&lt; raw_ostream &gt; &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8f09f0411e75db5fd532622f3e169bc">writeSample</a> (const FunctionSamples &amp;S) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write samples of a top-level function to a binary file. <a href="#aa8f09f0411e75db5fd532622f3e169bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, uint32_t &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae61448f10e29218721fb7c5a2054fb14">getNameTable</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a704b84bdc47710f22197508b631e1d09">writeMagicIdent</a> (SampleProfileFormat Format)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61e7926d242ffc3cac8fc92591b4178d">writeNameTable</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7422586efd8f803b17475cfc2e97329">writeHeader</a> (const SampleProfileMap &amp;ProfileMap) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a file header for the profile file. <a href="#ab7422586efd8f803b17475cfc2e97329">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74c686413929f11d2301cb47bec0fcdb">writeSummary</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eeb1d8193a4b8b08677a877534aca74">writeContextIdx</a> (const SampleContext &amp;Context)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af63eb7fece187a61531bdb743120f3c7">writeNameIdx</a> (FunctionId FName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7c088ecf1befc97ec9b4d36f30ae06d">writeBody</a> (const FunctionSamples &amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a9843c8238bc35707b209597d873d9b">stablizeNameTable</a> (MapVector&lt; FunctionId, uint32_t &gt; &amp;NameTable, std::set&lt; FunctionId &gt; &amp;V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa66076e59337700916195677d4437a7">addName</a> (FunctionId FName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55ca4222d45a32a3756a1cb72695ef1c">addContext</a> (const SampleContext &amp;Context)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a880b4a9e6f81baaa1c9a1fe9a2151cfd">addNames</a> (const FunctionSamples &amp;S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a845681147d133c5df69046907e725abf">NameTable</a></td>
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

<p>Sample-based profile writer (binary format).</p>

<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


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


<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a365a5ded4e755f745dc95795c798fa84">llvm::sampleprof::SampleProfileWriter::Format</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SampleProfileWriterBinary() {#a0dc0d64eb352acfe499cccd772a04dbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::SampleProfileWriterBinary::SampleProfileWriterBinary (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &gt; &amp; OS)</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a05982c1b3c99df840aa15e0fe16eddf1">llvm::sampleprof::SampleProfileWriter::SampleProfileWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### writeSample() {#aa8f09f0411e75db5fd532622f3e169bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterBinary::writeSample (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; S)</td>
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

<p>Write samples of a top-level function to a binary file.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the samples were written successfully, false otherwise.</p></dd>
</dl>


<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 871 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a6206d4ca96e6f63a40327a7fa147f2a4">llvm::sampleprof::FunctionSamples::getHeadSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a6bc387785b288e17a87e9494b57cb937">llvm::sampleprof::SampleProfileWriter::OutputStream</a> and <a href="#ae7c088ecf1befc97ec9b4d36f30ae06d">writeBody</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addContext() {#a55ca4222d45a32a3756a1cb72695ef1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileWriterBinary::addContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a> &amp; Context)</td>
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



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>Reference <a href="#afa66076e59337700916195677d4437a7">addName</a>.</p>


<p>Referenced by <a href="#ab7422586efd8f803b17475cfc2e97329">writeHeader</a>.</p>

</div>
</div>

### addName() {#afa66076e59337700916195677d4437a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileWriterBinary::addName (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> FName)</td>
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



<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>Reference <a href="#ae61448f10e29218721fb7c5a2054fb14">getNameTable</a>.</p>


<p>Referenced by <a href="#a55ca4222d45a32a3756a1cb72695ef1c">addContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#abb0eaeeea93bca26cb7055c7ab9e94ed">llvm::sampleprof::SampleProfileWriterExtBinaryBase::addContext</a> and <a href="#a880b4a9e6f81baaa1c9a1fe9a2151cfd">addNames</a>.</p>

</div>
</div>

### addNames() {#a880b4a9e6f81baaa1c9a1fe9a2151cfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileWriterBinary::addNames (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; S)</td>
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



<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="#afa66076e59337700916195677d4437a7">addName</a>, <a href="#a880b4a9e6f81baaa1c9a1fe9a2151cfd">addNames</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#afd62779d71a74d2db69f4fde48b37893">llvm::sampleprof::FunctionSamples::getBodySamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ae216a9dc4cce5948cec7fbf16ff462dd">llvm::sampleprof::FunctionSamples::getCallsiteSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplerecord/#a643e540a629559bc145405a68f3f0cbb">llvm::sampleprof::SampleRecord::getCallTargets</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a7ff8c2d016ae9169f35cdd1d1aaa1564">llvm::sampleprof::FunctionSamples::getFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a880b4a9e6f81baaa1c9a1fe9a2151cfd">addNames</a>, <a href="#ab7422586efd8f803b17475cfc2e97329">writeHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a01496927b6d3c4676bc9b45276fd4237">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeNameTableSection</a>.</p>

</div>
</div>

### getNameTable() {#ae61448f10e29218721fb7c5a2054fb14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MapVector&lt; FunctionId, uint32_t &gt; &amp; llvm::sampleprof::SampleProfileWriterBinary::getNameTable ()</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Reference <a href="#a845681147d133c5df69046907e725abf">NameTable</a>.</p>


<p>Referenced by <a href="#afa66076e59337700916195677d4437a7">addName</a> and <a href="#af63eb7fece187a61531bdb743120f3c7">writeNameIdx</a>.</p>

</div>
</div>

### stablizeNameTable() {#a3a9843c8238bc35707b209597d873d9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileWriterBinary::stablizeNameTable (<a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, uint32_t &gt; &amp; NameTable, std::set&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &gt; &amp; V)</td>
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



<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 683 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a845681147d133c5df69046907e725abf">NameTable</a>.</p>


<p>Referenced by <a href="#a61e7926d242ffc3cac8fc92591b4178d">writeNameTable</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a8da3b86e5070140af1716c64925a0495">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeNameTable</a>.</p>

</div>
</div>

### writeBody() {#ae7c088ecf1befc97ec9b4d36f30ae06d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterBinary::writeBody (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; S)</td>
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



<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 824 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#afd62779d71a74d2db69f4fde48b37893">llvm::sampleprof::FunctionSamples::getBodySamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ae216a9dc4cce5948cec7fbf16ff462dd">llvm::sampleprof::FunctionSamples::getCallsiteSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplerecord/#a643e540a629559bc145405a68f3f0cbb">llvm::sampleprof::SampleRecord::getCallTargets</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ad117577730085f895045fc7ff90d8fc2">llvm::sampleprof::FunctionSamples::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplerecord/#a6e5033adccbe0a93cc7c77cd89ed2fec">llvm::sampleprof::SampleRecord::getSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplerecord/#abe2b5ee88eea4c21f9efe473183744ed">llvm::sampleprof::SampleRecord::getSortedCallTargets</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#adb2786061d3e569b42b7d661ccc57484">llvm::sampleprof::FunctionSamples::getTotalSamples</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a6bc387785b288e17a87e9494b57cb937">llvm::sampleprof::SampleProfileWriter::OutputStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>, <a href="#ae7c088ecf1befc97ec9b4d36f30ae06d">writeBody</a>, <a href="#a8eeb1d8193a4b8b08677a877534aca74">writeContextIdx</a> and <a href="#af63eb7fece187a61531bdb743120f3c7">writeNameIdx</a>.</p>


<p>Referenced by <a href="#ae7c088ecf1befc97ec9b4d36f30ae06d">writeBody</a>, <a href="#aa8f09f0411e75db5fd532622f3e169bc">writeSample</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#af5cddc155fef09dd03f4493e99524109">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeSample</a>.</p>

</div>
</div>

### writeContextIdx() {#a8eeb1d8193a4b8b08677a877534aca74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterBinary::writeContextIdx (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a> &amp; Context)</td>
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



<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#af63eb7fece187a61531bdb743120f3c7">writeNameIdx</a>.</p>


<p>Referenced by <a href="#ae7c088ecf1befc97ec9b4d36f30ae06d">writeBody</a>.</p>

</div>
</div>

### writeHeader() {#ab7422586efd8f803b17475cfc2e97329}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterBinary::writeHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; ProfileMap)</td>
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

<p>Write a file header for the profile file.</p>

<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 717 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="#a55ca4222d45a32a3756a1cb72695ef1c">addContext</a>, <a href="#a880b4a9e6f81baaa1c9a1fe9a2151cfd">addNames</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a4f8b2ab39ae70cd859c323fd97219c23">llvm::sampleprof::SampleProfileWriter::computeSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a365a5ded4e755f745dc95795c798fa84">llvm::sampleprof::SampleProfileWriter::Format</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a845681147d133c5df69046907e725abf">NameTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>, <a href="#a704b84bdc47710f22197508b631e1d09">writeMagicIdent</a>, <a href="#a61e7926d242ffc3cac8fc92591b4178d">writeNameTable</a> and <a href="#a74c686413929f11d2301cb47bec0fcdb">writeSummary</a>.</p>

</div>
</div>

### writeMagicIdent() {#a704b84bdc47710f22197508b631e1d09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterBinary::writeMagicIdent (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a373137ee5de445ffb3a1dbc685cf66ec">SampleProfileFormat</a> Format)</td>
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



<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a365a5ded4e755f745dc95795c798fa84">llvm::sampleprof::SampleProfileWriter::Format</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a6bc387785b288e17a87e9494b57cb937">llvm::sampleprof::SampleProfileWriter::OutputStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a197283c05a4797bf186135efd511ceaf">llvm::sampleprof::SPMagic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#aec06640e3197b264c40e6f84e9a7ad6a">llvm::sampleprof::SPVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>


<p>Referenced by <a href="#ab7422586efd8f803b17475cfc2e97329">writeHeader</a>.</p>

</div>
</div>

### writeNameIdx() {#af63eb7fece187a61531bdb743120f3c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterBinary::writeNameIdx (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> FName)</td>
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



<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="#ae61448f10e29218721fb7c5a2054fb14">getNameTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a6bc387785b288e17a87e9494b57cb937">llvm::sampleprof::SampleProfileWriter::OutputStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea98266342cea8a7fb97a2c17d98fd230a">llvm::truncated_name_table</a>.</p>


<p>Referenced by <a href="#ae7c088ecf1befc97ec9b4d36f30ae06d">writeBody</a>, <a href="#a8eeb1d8193a4b8b08677a877534aca74">writeContextIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#af4e88367a9ab641e74700f89be2db0b4">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeContextIdx</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a449a2a9cd2cebab93b804f4a6cbaea5a">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeCSNameTableSection</a>.</p>

</div>
</div>

### writeNameTable() {#a61e7926d242ffc3cac8fc92591b4178d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterBinary::writeNameTable ()</td>
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



<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 693 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a845681147d133c5df69046907e725abf">NameTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a6bc387785b288e17a87e9494b57cb937">llvm::sampleprof::SampleProfileWriter::OutputStream</a>, <a href="#a3a9843c8238bc35707b209597d873d9b">stablizeNameTable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>


<p>Referenced by <a href="#ab7422586efd8f803b17475cfc2e97329">writeHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a8da3b86e5070140af1716c64925a0495">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeNameTable</a>.</p>

</div>
</div>

### writeSummary() {#a74c686413929f11d2301cb47bec0fcdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterBinary::writeSummary ()</td>
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



<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 808 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a6bc387785b288e17a87e9494b57cb937">llvm::sampleprof::SampleProfileWriter::OutputStream</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a24354d300d134c2a879f6d8a64cca025">llvm::sampleprof::SampleProfileWriter::Summary</a>.</p>


<p>Referenced by <a href="#ab7422586efd8f803b17475cfc2e97329">writeHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a33203b3c9366fd57c4d7d30f1f4c83b3">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeOneSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### NameTable {#a845681147d133c5df69046907e725abf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;FunctionId, uint32_t&gt; llvm::sampleprof::SampleProfileWriterBinary::NameTable</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Referenced by <a href="#ae61448f10e29218721fb7c5a2054fb14">getNameTable</a>, <a href="#a3a9843c8238bc35707b209597d873d9b">stablizeNameTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#af1c9e525ff3c6c6034850b0778f8e42d">llvm::sampleprof::SampleProfileWriterExtBinaryBase::write</a>, <a href="#ab7422586efd8f803b17475cfc2e97329">writeHeader</a>, <a href="#a61e7926d242ffc3cac8fc92591b4178d">writeNameTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a8da3b86e5070140af1716c64925a0495">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeNameTable</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a01496927b6d3c4676bc9b45276fd4237">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeNameTableSection</a>.</p>

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
