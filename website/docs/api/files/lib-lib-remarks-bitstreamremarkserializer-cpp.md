---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/remarks/bitstreamremarkserializer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `BitstreamRemarkSerializer.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">llvm/Remarks/BitstreamRemarkSerializer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">llvm/Remarks/Remark.h</a>"
#include &lt;optional&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a720622fc32fd2435f7726d832d851ea6">push</a> (SmallVectorImpl&lt; uint64_t &gt; &amp;R, StringRef Str)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b2d5e08689d7bef5b9d6efd82da0aaf">setRecordName</a> (unsigned RecordID, BitstreamWriter &amp;Bitstream, SmallVectorImpl&lt; uint64_t &gt; &amp;R, StringRef Str)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a2d80c17cbc001470acf77ff302a63b">initBlock</a> (unsigned BlockID, BitstreamWriter &amp;Bitstream, SmallVectorImpl&lt; uint64_t &gt; &amp;R, StringRef Str)</td>
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

## Functions

### initBlock() {#a4a2d80c17cbc001470acf77ff302a63b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void initBlock (unsigned BlockID, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> &amp; Bitstream, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; R, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea0b79eab5aacf81d139c4eaec818a549a">llvm::remarks::Bitstream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a6860684558cab9835254eba26b2f7963a3ab749cc5d99cccffd681c29da02fa74">llvm::bitc::BLOCKINFO_CODE_BLOCKNAME</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a6860684558cab9835254eba26b2f7963acf72b4b5b2c1c5b1310721a6715ab010">llvm::bitc::BLOCKINFO_CODE_SETBID</a> and <a href="#a720622fc32fd2435f7726d832d851ea6">push</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#a193cc5f98c50ec99686f7eeb81e8a4ec">llvm::remarks::BitstreamRemarkSerializerHelper::setupMetaBlockInfo</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#a7c2860948a6b6b47e5bf3fa15a1e5311">llvm::remarks::BitstreamRemarkSerializerHelper::setupRemarkBlockInfo</a>.</p>

</div>
</div>

### push() {#a720622fc32fd2435f7726d832d851ea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void push (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; R, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a6a9bfa14b2dfa291c65ec9f5c6657d27">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::doBeforeLabelEmit</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/path/#ab252ce944fb2315d923f0d2f36523f0f">llvm::IntervalMapImpl::Path::fillLeft</a>, <a href="#a4a2d80c17cbc001470acf77ff302a63b">initBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a4e07e3e64caa97fc5dbc73fe0b20d311">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a0cacf6ffb7a5ce2195bd33f0e9c0087c">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a4a69d0dfd4a74bd71f02776f7c275b38">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::popAndPushWithSameSignature</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodaghvx-cpp-/resultstack/#adb7a655ccf9933c9d3d00f9b9a30fe33">anonymous{HexagonISelDAGToDAGHVX.cpp}::ResultStack::push</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoniseldagtodag-cpp-/leafprioqueue/#a7518fb8ba61e4fb42ac28952d0aa1396">anonymous{HexagonISelDAGToDAG.cpp}::LeafPrioQueue::pushToBottom</a> and <a href="#a7b2d5e08689d7bef5b9d6efd82da0aaf">setRecordName</a>.</p>

</div>
</div>

### setRecordName() {#a7b2d5e08689d7bef5b9d6efd82da0aaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setRecordName (unsigned RecordID, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> &amp; Bitstream, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; R, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea0b79eab5aacf81d139c4eaec818a549a">llvm::remarks::Bitstream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a6860684558cab9835254eba26b2f7963aad1225e67df2c8e94135a067eb3f212e">llvm::bitc::BLOCKINFO_CODE_SETRECORDNAME</a> and <a href="#a720622fc32fd2435f7726d832d851ea6">push</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#a193cc5f98c50ec99686f7eeb81e8a4ec">llvm::remarks::BitstreamRemarkSerializerHelper::setupMetaBlockInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#a902d073e6121eca59b75706548f013f6">llvm::remarks::BitstreamRemarkSerializerHelper::setupMetaExternalFile</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#aa45dbe007471b57fc449bb1e41458575">llvm::remarks::BitstreamRemarkSerializerHelper::setupMetaRemarkVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#ad62618367c258fda8b4979e7d1c501b0">llvm::remarks::BitstreamRemarkSerializerHelper::setupMetaStrTab</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#a7c2860948a6b6b47e5bf3fa15a1e5311">llvm::remarks::BitstreamRemarkSerializerHelper::setupRemarkBlockInfo</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
