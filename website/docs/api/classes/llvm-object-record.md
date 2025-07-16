---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/record
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Record` Class Reference

<p>Represents a <a href="/web-llvm/docs/api/namespaces/llvm/goff">GOFF</a> physical record. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::object::Record { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">llvm/Object/GOFF.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/endrecord">ENDRecord</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/esdrecord">ESDRecord</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/hdrrecord">HDRRecord</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/txtrecord">TXTRecord</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68447fd5872ee1b7ff3b7bd7d39e0077">getContinuousData</a> (const uint8_t *Record, uint16_t DataLength, int DataIndex, SmallString&lt; 256 &gt; &amp;CompleteData)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a637f36dc9f57cc59c8339f12f6c3c0bc">isContinued</a> (const uint8_t *Record)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc30306974172eceb9ab361af8eff518">isContinuation</a> (const uint8_t *Record)</td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a621bf457e53725ae30708875b8d33bec">getBits</a> (const uint8_t *Bytes, uint8_t ByteIndex, uint8_t BitIndex, uint8_t Length, uint8_t &amp;Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get bit field of specified byte. <a href="#a621bf457e53725ae30708875b8d33bec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a817de5ee95a965cf8ba4aa8b19bfd8ea">get</a> (const uint8_t *Bytes, uint8_t ByteIndex, T &amp;Value)</td>
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

<p>Represents a <a href="/web-llvm/docs/api/namespaces/llvm/goff">GOFF</a> physical record.</p>


<p>Specifies protected member functions to manipulate the record. These should be called from deriving classes to change values as that record specifies.</p>


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### getContinuousData() {#a68447fd5872ee1b7ff3b7bd7d39e0077}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error Record::getContinuousData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record, uint16_t DataLength, int DataIndex, <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 256 &gt; &amp; CompleteData)</td>
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



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>, definition at line 596 of file <a href="/web-llvm/docs/api/files/lib/lib/object/goffobjectfile-cpp">GOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ac22cf1a1c08b7ccaefc51508536312a4">llvm::SmallString&lt; InternalLen &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#abc30306974172eceb9ab361af8eff518">isContinuation</a>, <a href="#a637f36dc9f57cc59c8339f12f6c3c0bc">isContinued</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/goff/#a414fbaaa77a3d0c16629520bff7f4804">llvm::GOFF::PayloadLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/goff/#a9bd094a5bc04f1a61bde1d43568b595f">llvm::GOFF::RecordLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/goff/#a2a7ab7644506c3e3c97730808c86ac0f">llvm::GOFF::RecordPrefixLength</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/endrecord/#a23dc9276377c60b4714b77e41f8da16e">llvm::object::ENDRecord::getData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a41be86591fdf189a06549d4f79778363">llvm::object::ESDRecord::getData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/hdrrecord/#a464dca003843fef58bf9e9d218666138">llvm::object::HDRRecord::getData</a> and <a href="/web-llvm/docs/api/classes/llvm/object/txtrecord/#ad0de1da35f63c2f230b4b0dfcb79071c">llvm::object::TXTRecord::getData</a>.</p>

</div>
</div>

### isContinuation() {#abc30306974172eceb9ab361af8eff518}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::Record::isContinuation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="#a621bf457e53725ae30708875b8d33bec">getBits</a>.</p>


<p>Referenced by <a href="#a68447fd5872ee1b7ff3b7bd7d39e0077">getContinuousData</a>.</p>

</div>
</div>

### isContinued() {#a637f36dc9f57cc59c8339f12f6c3c0bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::Record::isContinued (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Record)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>Reference <a href="#a621bf457e53725ae30708875b8d33bec">getBits</a>.</p>


<p>Referenced by <a href="#a68447fd5872ee1b7ff3b7bd7d39e0077">getContinuousData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### get() {#a817de5ee95a965cf8ba4aa8b19bfd8ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::Record::get (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Bytes, uint8_t ByteIndex, T &amp; Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#acfdf941f45bc58470ed8423b98862486">llvm::support::endian::read</a>, <a href="/web-llvm/docs/api/namespaces/llvm/goff/#a9bd094a5bc04f1a61bde1d43568b595f">llvm::GOFF::RecordLength</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a516f3f99075b03a2827823a26d20a0f4">llvm::object::ESDRecord::getAdaEsdId</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a6858cfaa9e9d289d7a4134a204c90089">llvm::object::ESDRecord::getAmode</a>, <a href="#a621bf457e53725ae30708875b8d33bec">getBits</a>, <a href="/web-llvm/docs/api/classes/llvm/object/txtrecord/#a95100266e2327854dfedc66a2ed41e72">llvm::object::TXTRecord::getDataLength</a>, <a href="/web-llvm/docs/api/classes/llvm/object/txtrecord/#a575f5ce490a26a414a489f3f7e515cd0">llvm::object::TXTRecord::getElementEsdId</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a3d2201cdad88bd4981c06028e8b4c87a">llvm::object::ESDRecord::getEsdId</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a8b8a9f52f85cbdbbbb9f3f30ec001460">llvm::object::ESDRecord::getFillByteValue</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a4c2b4d5d089d12bb5f0e83ed0f37e28c">llvm::object::ESDRecord::getLength</a>, <a href="/web-llvm/docs/api/classes/llvm/object/endrecord/#a8a53cb59b6bc56479a9aaac1f4ce61eb">llvm::object::ENDRecord::getNameLength</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#aa9aaf80f8b8b1af0fa63cd19126f2a2b">llvm::object::ESDRecord::getNameLength</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#ad76249510a3813e5688338c252b271d5">llvm::object::ESDRecord::getNameSpaceId</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a20245bf07f26c7c93be4aa8707e1a27b">llvm::object::ESDRecord::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/txtrecord/#ae15f56285eb5f2e538b4a2c4b9170df0">llvm::object::TXTRecord::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a89665782cf8d112a3547acdc66cc0a1c">llvm::object::ESDRecord::getParentEsdId</a>, <a href="/web-llvm/docs/api/classes/llvm/object/hdrrecord/#a74011747fe024db673758bc5a2eba060">llvm::object::HDRRecord::getPropertyModuleLength</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a7eea7ffc710777d6561cda7a5e4f8c57">llvm::object::ESDRecord::getRmode</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a7f484a3f5cbdee1f8208afcc1b12038c">llvm::object::ESDRecord::getSortPriority</a> and <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a8f69c62cb368a82f813d20559b771afd">llvm::object::ESDRecord::getSymbolType</a>.</p>

</div>
</div>

### getBits() {#a621bf457e53725ae30708875b8d33bec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::Record::getBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Bytes, uint8_t ByteIndex, uint8_t BitIndex, uint8_t Length, uint8_t &amp; Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get bit field of specified byte.</p>


<p>Used to pack bit fields into one byte. Fields are packed left to right. Bit index zero is the most significant bit of the byte.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ByteIndex</td>
<td class="doxyParamItemDescription"><p>index of byte the field is in.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BitIndex</td>
<td class="doxyParamItemDescription"><p>index of first bit of field.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Length</td>
<td class="doxyParamItemDescription"><p>length of bit field.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>value of bit field.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a817de5ee95a965cf8ba4aa8b19bfd8ea">get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a> and <a href="/web-llvm/docs/api/namespaces/llvm/goff/#a9bd094a5bc04f1a61bde1d43568b595f">llvm::GOFF::RecordLength</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#aa5f23fb26bc4072fd103b50f0a4053fb">llvm::object::ESDRecord::getAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a597ed0b588d19008d10c83ff5ee5ef88">llvm::object::ESDRecord::getBindingAlgorithm</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#ac96e2aa558f44e2345459cf2492944a3">llvm::object::ESDRecord::getBindingScope</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a10feb91fb4edb2fa3e1e4bc1e219be35">llvm::object::ESDRecord::getBindingStrength</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a249517638648cd2af36d179fa0c603ba">llvm::object::ESDRecord::getDuplicateSeverity</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#ac7266dc4718ccfa5af3e1e34ba75fd3d">llvm::object::ESDRecord::getExecutable</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a445dd802984ef710b1ccaf5a5ada2b8f">llvm::object::ESDRecord::getFillBytePresent</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a071c9b7f13b2e3a77ea1939a6d2b0f54">llvm::object::ESDRecord::getIndirectReference</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#aa762348109ffca6f7c3564c26659ecb2">llvm::object::ESDRecord::getLinkageType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a3f871ae083a28c89da507e24096e77a2">llvm::object::ESDRecord::getLoadingBehavior</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a41e6bf13951edb895a30fd3beab7fcce">llvm::object::ESDRecord::getNameMangled</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a7c2fb6f2f3b28850625cb896809b4e5a">llvm::object::ESDRecord::getReadOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#aea77b214dc8f83c7edf8b7db1666c269">llvm::object::ESDRecord::getRemovable</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#af40849e67ad6b5f296a7b695e5d06fbe">llvm::object::ESDRecord::getRenamable</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#a4258b2abc2bf3967873ba3d9ce436303">llvm::object::ESDRecord::getTaskingBehavior</a>, <a href="/web-llvm/docs/api/classes/llvm/object/esdrecord/#aa2e6ab7ae3094d97a45352feb7dc7758">llvm::object::ESDRecord::getTextStyle</a>, <a href="#abc30306974172eceb9ab361af8eff518">isContinuation</a> and <a href="#a637f36dc9f57cc59c8339f12f6c3c0bc">isContinued</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/goff-h">GOFF.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/goffobjectfile-cpp">GOFFObjectFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
