---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/gsym/callsiteinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `CallSiteInfo` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::gsym::CallSiteInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">llvm/DebugInfo/GSYM/CallSiteInfo.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Flags : uint8_t { <a href="#aced76967548a86d559ae0b349755c0f7">...</a> }</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd5d38d17b8b312c47cbf8b0d3cc9376">operator==</a> (const CallSiteInfo &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Equality comparison operator for <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo">CallSiteInfo</a>. <a href="#abd5d38d17b8b312c47cbf8b0d3cc9376">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56fe3d55410364f902be67311073b0d0">operator!=</a> (const CallSiteInfo &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inequality comparison operator for <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo">CallSiteInfo</a>. <a href="#a56fe3d55410364f902be67311073b0d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04a75849a90c95c00d22f3894a196bc5">encode</a> (FileWriter &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode this <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo">CallSiteInfo</a> object into a <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> stream. <a href="#a04a75849a90c95c00d22f3894a196bc5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26c0bff4e03d1b8593ffd2590c20efcb">ReturnOffset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The return offset of the call site - relative to the function start. <a href="#a26c0bff4e03d1b8593ffd2590c20efcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04c72564fa58d17a8082073d5efcf101">MatchRegex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offsets into the string table for function names regex patterns. <a href="#a04c72564fa58d17a8082073d5efcf101">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90d7c81a5c2fb69ae18c91d0820ed0f0">Flags</a> = <a href="#aced76967548a86d559ae0b349755c0f7a1e0e4b3343db783006649575e4a9b7ef">CallSiteInfo::Flags::None</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bitwise OR of <a href="#aced76967548a86d559ae0b349755c0f7">CallSiteInfo::Flags</a> values. <a href="#a90d7c81a5c2fb69ae18c91d0820ed0f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo">CallSiteInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a596705578fd132b4b9793bb9e0a454d4">decode</a> (DataExtractor &amp;Data, uint64_t &amp;Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode a <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo">CallSiteInfo</a> object from a binary data stream. <a href="#a596705578fd132b4b9793bb9e0a454d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">CallSiteInfo.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Flags {#aced76967548a86d559ae0b349755c0f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::gsym::CallSiteInfo::Flags : uint8_t</td>
</tr>
</table>
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
<td class="doxyEnumItemName">None<a id="aced76967548a86d559ae0b349755c0f7a1e0e4b3343db783006649575e4a9b7ef"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InternalCall<a id="aced76967548a86d559ae0b349755c0f7a6df5bef433fbaea29a0f93375ffebc36"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExternalCall<a id="aced76967548a86d559ae0b349755c0f7ae0cc01e472339cb43229324899820e47"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVM_MARK_AS_BITMASK_ENUM<a id="aced76967548a86d559ae0b349755c0f7a037c3e2c9fb314f23ae9a17108096b72"></a></td>
<td class="doxyEnumItemDescription"> (=( ExternalCall))</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">CallSiteInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a56fe3d55410364f902be67311073b0d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gsym::CallSiteInfo::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo">CallSiteInfo</a> &amp; RHS)</td>
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

<p>Inequality comparison operator for <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo">CallSiteInfo</a>.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">CallSiteInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#abd5d38d17b8b312c47cbf8b0d3cc9376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gsym::CallSiteInfo::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo">CallSiteInfo</a> &amp; RHS)</td>
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

<p>Equality comparison operator for <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo">CallSiteInfo</a>.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">CallSiteInfo.h</a>.</p>


<p>References <a href="#a04c72564fa58d17a8082073d5efcf101">MatchRegex</a>, <a href="#a26c0bff4e03d1b8593ffd2590c20efcb">ReturnOffset</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### encode() {#a04a75849a90c95c00d22f3894a196bc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CallSiteInfo::encode (<a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encode this <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo">CallSiteInfo</a> object into a <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> stream.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">O</td>
<td class="doxyParamItemDescription"><p>The binary stream to write the data to.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An error object that indicates success or failure.</p></dd>
</dl>


<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">CallSiteInfo.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/callsiteinfo-cpp">CallSiteInfo.cpp</a>.</p>


<p>References <a href="#a04a75849a90c95c00d22f3894a196bc5">encode</a>, <a href="#a04c72564fa58d17a8082073d5efcf101">MatchRegex</a>, <a href="#a26c0bff4e03d1b8593ffd2590c20efcb">ReturnOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a04a75849a90c95c00d22f3894a196bc5">encode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Flags {#a90d7c81a5c2fb69ae18c91d0820ed0f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::gsym::CallSiteInfo::Flags = <a href="#aced76967548a86d559ae0b349755c0f7a1e0e4b3343db783006649575e4a9b7ef">CallSiteInfo::Flags::None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Bitwise OR of <a href="#aced76967548a86d559ae0b349755c0f7">CallSiteInfo::Flags</a> values.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">CallSiteInfo.h</a>.</p>

</div>
</div>

### MatchRegex {#a04c72564fa58d17a8082073d5efcf101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint32_t&gt; llvm::gsym::CallSiteInfo::MatchRegex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offsets into the string table for function names regex patterns.</p>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">CallSiteInfo.h</a>.</p>


<p>Referenced by <a href="#a596705578fd132b4b9793bb9e0a454d4">decode</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a40a7cf3120a64f2f2e563bc820b9d846">llvm::gsym::GsymReader::dump</a>, <a href="#a04a75849a90c95c00d22f3894a196bc5">encode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a15f42fd0953ecc13d8122847660c0e5b">llvm::gsym::operator&lt;&lt;</a> and <a href="#abd5d38d17b8b312c47cbf8b0d3cc9376">operator==</a>.</p>

</div>
</div>

### ReturnOffset {#a26c0bff4e03d1b8593ffd2590c20efcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::gsym::CallSiteInfo::ReturnOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The return offset of the call site - relative to the function start.</p>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">CallSiteInfo.h</a>.</p>


<p>Referenced by <a href="#a596705578fd132b4b9793bb9e0a454d4">decode</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a40a7cf3120a64f2f2e563bc820b9d846">llvm::gsym::GsymReader::dump</a>, <a href="#a04a75849a90c95c00d22f3894a196bc5">encode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a15f42fd0953ecc13d8122847660c0e5b">llvm::gsym::operator&lt;&lt;</a> and <a href="#abd5d38d17b8b312c47cbf8b0d3cc9376">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### decode() {#a596705578fd132b4b9793bb9e0a454d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; CallSiteInfo &gt; CallSiteInfo::decode (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &amp; Data, uint64_t &amp; Offset)</td>
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

<p>Decode a <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo">CallSiteInfo</a> object from a binary data stream.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Data</td>
<td class="doxyParamItemDescription"><p>The binary stream to read the data from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Offset</td>
<td class="doxyParamItemDescription"><p>The current offset within the data stream.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo">CallSiteInfo</a> or an error describing the issue.</p></dd>
</dl>


<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">CallSiteInfo.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/callsiteinfo-cpp">CallSiteInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a04c72564fa58d17a8082073d5efcf101">MatchRegex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a26c0bff4e03d1b8593ffd2590c20efcb">ReturnOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfocollection/#ade8c3030c7854f2dce476b50e2102815">llvm::gsym::CallSiteInfoCollection::decode</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">CallSiteInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/callsiteinfo-cpp">CallSiteInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
