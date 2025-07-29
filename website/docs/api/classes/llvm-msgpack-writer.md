---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/msgpack/writer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Writer` Class

<p>Writes MessagePack objects to an output stream, one at a time. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::msgpack::Writer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackwriter-h">llvm/BinaryFormat/MsgPackWriter.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c1d1c6bc2417d1b113c6cdf523348fa">Writer</a> (raw_ostream &amp;OS, bool Compatible=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a writer, optionally enabling "Compatibility Mode" as defined in the MessagePack specification. <a href="#a4c1d1c6bc2417d1b113c6cdf523348fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a608bc10b85684fe49e237f333ecf2c">Writer</a> (const Writer &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/writer">Writer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cdaf1056e144ba7ef1015126b7375fc">operator=</a> (const Writer &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0282d6201e15dba0d5fda1a4774e45df">writeNil</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a <em>Nil</em> to the output stream. <a href="#a0282d6201e15dba0d5fda1a4774e45df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc1743f31ddf3870711ebdcc210700c0">write</a> (bool b)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a <em>Boolean</em> to the output stream. <a href="#afc1743f31ddf3870711ebdcc210700c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae442502a977e2cd0cae79630b03ec1d2">write</a> (int64_t i)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a signed integer to the output stream. <a href="#ae442502a977e2cd0cae79630b03ec1d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00f9dc660226d9127008dd21ad2b9aa1">write</a> (uint64_t u)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write an unsigned integer to the output stream. <a href="#a00f9dc660226d9127008dd21ad2b9aa1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba7fd48bcabfaf2c252912ebe32e83fd">write</a> (double d)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a floating point number to the output stream. <a href="#aba7fd48bcabfaf2c252912ebe32e83fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3df0d1e99ef22c7868a727016afd661">write</a> (StringRef s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a string to the output stream. <a href="#aa3df0d1e99ef22c7868a727016afd661">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef4ecef7a05cd113a04ae7504c4ff08b">write</a> (MemoryBufferRef Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a memory buffer to the output stream. <a href="#aef4ecef7a05cd113a04ae7504c4ff08b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ed0ae40a1f440ec59f5e7d22b99a65c">writeArraySize</a> (uint32_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the header for an <em>Array</em> of the given size. <a href="#a8ed0ae40a1f440ec59f5e7d22b99a65c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50372c2c26c41e47324691f53269072a">writeMapSize</a> (uint32_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the header for a <em>Map</em> of the given size. <a href="#a50372c2c26c41e47324691f53269072a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac51fde5dfbfcac23216ca22b76b26bf5">writeExt</a> (int8_t Type, MemoryBufferRef Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a typed memory buffer (an extension type) to the output stream. <a href="#ac51fde5dfbfcac23216ca22b76b26bf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/support/endian/writer">support::endian::Writer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa650d025fb1c13342873dddbac9dc26">EW</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21edbfd6a97937973f9abd4a645db92e">Compatible</a></td>
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

<p>Writes MessagePack objects to an output stream, one at a time.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackwriter-h">MsgPackWriter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Writer() {#a4c1d1c6bc2417d1b113c6cdf523348fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Writer::Writer (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool Compatible=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a writer, optionally enabling "Compatibility Mode" as defined in the MessagePack specification.</p>


<p>When in <span class="doxyComputerOutput">Compatible</span> mode, the writer will write <span class="doxyComputerOutput">Str16</span> formats instead of <span class="doxyComputerOutput">Str8</span> formats, and will refuse to write any <span class="doxyComputerOutput">Bin</span> formats.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>stream to output MessagePack objects to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Compatible</td>
<td class="doxyParamItemDescription"><p>when set, write in "Compatibility Mode".</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackwriter-h">MsgPackWriter.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackwriter-cpp">MsgPackWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#a40f13de27f84f5bb290c911013c539e6">llvm::msgpack::Endianness</a>.</p>


<p>Referenced by <a href="#a1cdaf1056e144ba7ef1015126b7375fc">operator=</a> and <a href="#a6a608bc10b85684fe49e237f333ecf2c">Writer</a>.</p>

</div>
</div>

### Writer() {#a6a608bc10b85684fe49e237f333ecf2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::msgpack::Writer::Writer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/msgpack/writer">Writer</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackwriter-h">MsgPackWriter.h</a>.</p>


<p>Reference <a href="#a4c1d1c6bc2417d1b113c6cdf523348fa">Writer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a1cdaf1056e144ba7ef1015126b7375fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Writer &amp; llvm::msgpack::Writer::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/msgpack/writer">Writer</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackwriter-h">MsgPackWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#a4c1d1c6bc2417d1b113c6cdf523348fa">Writer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### write() {#afc1743f31ddf3870711ebdcc210700c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Writer::write (bool b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write a <em>Boolean</em> to the output stream.</p>


<p>The output will be a <em>bool</em> format.</p>


<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackwriter-h">MsgPackWriter.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackwriter-cpp">MsgPackWriter.cpp</a>.</p>


<p>Referenced by <a href="#ae442502a977e2cd0cae79630b03ec1d2">write</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a8f94c9dc628a8565363014088523a0fa">llvm::msgpack::Document::writeToBlob</a>.</p>

</div>
</div>

### write() {#ae442502a977e2cd0cae79630b03ec1d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Writer::write (int64_t i)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write a signed integer to the output stream.</p>


<p>The output will be in the smallest possible <em>int</em> format.</p>


<p>The format chosen may be for an unsigned integer.</p>


<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackwriter-h">MsgPackWriter.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackwriter-cpp">MsgPackWriter.cpp</a>.</p>


<p>Reference <a href="#afc1743f31ddf3870711ebdcc210700c0">write</a>.</p>

</div>
</div>

### write() {#a00f9dc660226d9127008dd21ad2b9aa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Writer::write (uint64_t u)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write an unsigned integer to the output stream.</p>


<p>The output will be in the smallest possible <em>int</em> format.</p>


<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackwriter-h">MsgPackWriter.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackwriter-cpp">MsgPackWriter.cpp</a>.</p>

</div>
</div>

### write() {#aba7fd48bcabfaf2c252912ebe32e83fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Writer::write (double d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write a floating point number to the output stream.</p>


<p>The output will be in the smallest possible <em>float</em> format.</p>


<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackwriter-h">MsgPackWriter.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackwriter-cpp">MsgPackWriter.cpp</a>.</p>

</div>
</div>

### write() {#aa3df0d1e99ef22c7868a727016afd661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Writer::write (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write a string to the output stream.</p>


<p>The output will be in the smallest possible <em>str</em> format.</p>


<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackwriter-h">MsgPackWriter.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackwriter-cpp">MsgPackWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### write() {#aef4ecef7a05cd113a04ae7504c4ff08b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Writer::write (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write a memory buffer to the output stream.</p>


<p>The output will be in the smallest possible <em>bin</em> format.</p>



:::warning
<p>Do not use this overload if in <span class="doxyComputerOutput">Compatible</span> mode.</p>
:::


<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackwriter-h">MsgPackWriter.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackwriter-cpp">MsgPackWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a2036a4973d159e49dcc471488205656f">llvm::MemoryBufferRef::getBufferSize</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a62b2843b74e5f05930ebf5c63766a668">llvm::MemoryBufferRef::getBufferStart</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### writeArraySize() {#a8ed0ae40a1f440ec59f5e7d22b99a65c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Writer::writeArraySize (uint32_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the header for an <em>Array</em> of the given size.</p>


<p>The output will be in the smallest possible <em>array</em> format. The header contains an identifier for the <em>array</em> format used, as well as an encoding of the size of the array.</p>


<p>N.B. The caller must subsequently call <span class="doxyComputerOutput">Write</span> an additional <span class="doxyComputerOutput">Size</span> times to complete the array.</p>


<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackwriter-h">MsgPackWriter.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackwriter-cpp">MsgPackWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a8f94c9dc628a8565363014088523a0fa">llvm::msgpack::Document::writeToBlob</a>.</p>

</div>
</div>

### writeExt() {#ac51fde5dfbfcac23216ca22b76b26bf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Writer::writeExt (int8_t Type, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write a typed memory buffer (an extension type) to the output stream.</p>


<p>The output will be in the smallest possible <em>ext</em> format.</p>


<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackwriter-h">MsgPackWriter.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackwriter-cpp">MsgPackWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a2036a4973d159e49dcc471488205656f">llvm::MemoryBufferRef::getBufferSize</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a62b2843b74e5f05930ebf5c63766a668">llvm::MemoryBufferRef::getBufferStart</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### writeMapSize() {#a50372c2c26c41e47324691f53269072a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Writer::writeMapSize (uint32_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the header for a <em>Map</em> of the given size.</p>


<p>The output will be in the smallest possible <em>map</em> format. The header contains an identifier for the <em>map</em> format used, as well as an encoding of the size of the map.</p>


<p>N.B. The caller must subsequently call <span class="doxyComputerOutput">Write</span> and additional <span class="doxyComputerOutput">Size*2</span> times to complete the map. Each even numbered call to <span class="doxyComputerOutput">Write</span> defines a new key, and each odd numbered call defines the previous key's value.</p>


<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackwriter-h">MsgPackWriter.h</a>, definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackwriter-cpp">MsgPackWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a8f94c9dc628a8565363014088523a0fa">llvm::msgpack::Document::writeToBlob</a>.</p>

</div>
</div>

### writeNil() {#a0282d6201e15dba0d5fda1a4774e45df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Writer::writeNil ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write a <em>Nil</em> to the output stream.</p>


<p>The output will be the <em>nil</em> format.</p>


<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackwriter-h">MsgPackWriter.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackwriter-cpp">MsgPackWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a8f94c9dc628a8565363014088523a0fa">llvm::msgpack::Document::writeToBlob</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Compatible {#a21edbfd6a97937973f9abd4a645db92e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::msgpack::Writer::Compatible</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackwriter-h">MsgPackWriter.h</a>.</p>

</div>
</div>

### EW {#afa650d025fb1c13342873dddbac9dc26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::endian::Writer llvm::msgpack::Writer::EW</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackwriter-h">MsgPackWriter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackwriter-h">MsgPackWriter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackwriter-cpp">MsgPackWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
