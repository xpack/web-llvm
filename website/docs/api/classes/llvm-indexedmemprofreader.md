---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/indexedmemprofreader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `IndexedMemProfReader` Class



## Declaration

<div class="doxyDeclaration">
class llvm::IndexedMemProfReader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">llvm/ProfileData/InstrProfReader.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a303d48b32fedd50a36fb5acf854a16">IndexedMemProfReader</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7907bad312db28b49d4a53468ef4d0b1">deserialize</a> (const unsigned char *Start, uint64_t MemProfOffset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/memprof/memprofrecord">memprof::MemProfRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae96b3f3d1078d9b8da4d3e39a84e9443">getMemProfRecord</a> (const uint64_t FuncNameHash) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a7d02be07b1a797a9f076b58e810e93a1">memprof::CallEdgeTy</a>, 0 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af543f9026f539064b643534a8acf1ae5">getMemProfCallerCalleePairs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/memprof/allmemprofdata">memprof::AllMemProfData</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2a7ea6e7dab7888d02b35c22317b1a8">getAllMemProfData</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c8a890ecc9fe28f6ce98236f30c1ddf">deserializeV2</a> (const unsigned char *Start, const unsigned char *Ptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a099d36ac69b435e711a08b00fc99845b">deserializeV3</a> (const unsigned char *Start, const unsigned char *Ptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecb">memprof::IndexedVersion</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42942b0630d32930461c62fa9273dd20">Version</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The MemProf version. <a href="#a42942b0630d32930461c62fa9273dd20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a4c0e5dd93f0bc1942fcd93ae8e7a23ea">memprof::MemProfSchema</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac73628495225ebed4c5cf4eb9c5c8ad9">Schema</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MemProf profile schema (if available). <a href="#ac73628495225ebed4c5cf4eb9c5c8ad9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a1d5cc5c81fcb1313cd593c40563f34d2">MemProfRecordHashTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac48701b6a83f5bedb4ecb96fdb4a489">MemProfRecordTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MemProf record profile data on-disk indexed via llvm::md5(FunctionName). <a href="#aac48701b6a83f5bedb4ecb96fdb4a489">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8171615dec1015e65096a8a43a6a0467">MemProfFrameHashTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89b9bb2c3b50e4a5a5fc713ad4a75fdb">MemProfFrameTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MemProf frame profile data on-disk indexed via frame id. <a href="#a89b9bb2c3b50e4a5a5fc713ad4a75fdb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a77f63fa243b53ceb57767cc145cbba67">MemProfCallStackHashTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f1f4e490765f3c7d80ef3994259658c">MemProfCallStackTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MemProf call stack data on-disk indexed via call stack id. <a href="#a9f1f4e490765f3c7d80ef3994259658c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e06be98efd01f7d495e11d3dd5465f1">FrameBase</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The starting address of the frame array. <a href="#a1e06be98efd01f7d495e11d3dd5465f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab55b8335281d5d72b18590d44fb61c88">CallStackBase</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The starting address of the call stack array. <a href="#ab55b8335281d5d72b18590d44fb61c88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca9636c58f183173f64dbaf9c00f8e9d">RadixTreeSize</a> = 0</td>
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


<p>Definition at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IndexedMemProfReader() {#a3a303d48b32fedd50a36fb5acf854a16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IndexedMemProfReader::IndexedMemProfReader ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 711 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### deserialize() {#a7907bad312db28b49d4a53468ef4d0b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error IndexedMemProfReader::deserialize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * Start, uint64_t MemProfOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 713 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>, definition at line 1322 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a229923f8cb950f9899eb443578242800">llvm::memprof::MaximumSupportedVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a721d2b84586b0bc5723c14c390570f61">llvm::memprof::MinimumSupportedVersion</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae6c58c37f5229487e86ce915afe1ba12">llvm::support::endian::readNext</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086a2af01f2c39c66a1641045dd660e839b5">llvm::unsupported_version</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecbaa4580b818c5644cc40399914cc86c227">llvm::memprof::Version2</a> and <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecbafe029208a9df98e11b723897a0f19b8d">llvm::memprof::Version3</a>.</p>

</div>
</div>

### getAllMemProfData() {#ab2a7ea6e7dab7888d02b35c22317b1a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">memprof::AllMemProfData IndexedMemProfReader::getAllMemProfData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 722 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>, definition at line 1667 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>


<p>References <a href="#ae96b3f3d1078d9b8da4d3e39a84e9443">getMemProfRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/guidmemprofrecordpair/#a9c5f6669213ef8adae6db26bcd60ee57">llvm::memprof::GUIDMemProfRecordPair::GUID</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/allmemprofdata/#aba83a912e4af27518f6cb08095ac1c48">llvm::memprof::AllMemProfData::HeapProfileRecords</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/structs/llvm/memprof/guidmemprofrecordpair/#a46641ef1c55295fdfb4622df993cdadc">llvm::memprof::GUIDMemProfRecordPair::Record</a>.</p>

</div>
</div>

### getMemProfCallerCalleePairs() {#af543f9026f539064b643534a8acf1ae5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; uint64_t, SmallVector&lt; memprof::CallEdgeTy, 0 &gt; &gt; IndexedMemProfReader::getMemProfCallerCalleePairs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>, definition at line 1629 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedallocationinfo/#a848ebb2867b90eeec510ce14878b398e">llvm::memprof::IndexedAllocationInfo::CSId</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#aa56c07cdb4f03ddef7dfdf460811d36e">llvm::BitVector::set_bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a48f85da577c6ce7d9aed90437dc0d07c">llvm::unique</a> and <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecbafe029208a9df98e11b723897a0f19b8d">llvm::memprof::Version3</a>.</p>

</div>
</div>

### getMemProfRecord() {#ae96b3f3d1078d9b8da4d3e39a84e9443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; memprof::MemProfRecord &gt; IndexedMemProfReader::getMemProfRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t FuncNameHash)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 716 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>, definition at line 1593 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#ae36ae2256fb0b0ad06486d65f4237cfb">getMemProfRecordV2</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#ae3e9115aa20b0cbd4f800f0892e82153">getMemProfRecordV3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086aca78730e8bc0cd42986be66e3f0dc14c">llvm::invalid_prof</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a229923f8cb950f9899eb443578242800">llvm::memprof::MaximumSupportedVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a721d2b84586b0bc5723c14c390570f61">llvm::memprof::MinimumSupportedVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086ab87eee819cec0e1d8b2dfa938d14a77a">llvm::unknown_function</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086a2af01f2c39c66a1641045dd660e839b5">llvm::unsupported_version</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecbaa4580b818c5644cc40399914cc86c227">llvm::memprof::Version2</a> and <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecbafe029208a9df98e11b723897a0f19b8d">llvm::memprof::Version3</a>.</p>


<p>Referenced by <a href="#ab2a7ea6e7dab7888d02b35c22317b1a8">getAllMemProfData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### deserializeV2() {#a1c8a890ecc9fe28f6ce98236f30c1ddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error IndexedMemProfReader::deserializeV2 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * Start, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * Ptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 707 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>, definition at line 1233 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>

</div>
</div>

### deserializeV3() {#a099d36ac69b435e711a08b00fc99845b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error IndexedMemProfReader::deserializeV3 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * Start, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * Ptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>, definition at line 1285 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CallStackBase {#ab55b8335281d5d72b18590d44fb61c88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned char* llvm::IndexedMemProfReader::CallStackBase = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The starting address of the call stack array.</p>

<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>

</div>
</div>

### FrameBase {#a1e06be98efd01f7d495e11d3dd5465f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned char* llvm::IndexedMemProfReader::FrameBase = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The starting address of the frame array.</p>

<p>Definition at line 701 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>

</div>
</div>

### MemProfCallStackTable {#a9f1f4e490765f3c7d80ef3994259658c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemProfCallStackHashTable&gt; llvm::IndexedMemProfReader::MemProfCallStackTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MemProf call stack data on-disk indexed via call stack id.</p>

<p>Definition at line 699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>

</div>
</div>

### MemProfFrameTable {#a89b9bb2c3b50e4a5a5fc713ad4a75fdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemProfFrameHashTable&gt; llvm::IndexedMemProfReader::MemProfFrameTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MemProf frame profile data on-disk indexed via frame id.</p>

<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>

</div>
</div>

### MemProfRecordTable {#aac48701b6a83f5bedb4ecb96fdb4a489}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemProfRecordHashTable&gt; llvm::IndexedMemProfReader::MemProfRecordTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MemProf record profile data on-disk indexed via llvm::md5(FunctionName).</p>

<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>

</div>
</div>

### RadixTreeSize {#aca9636c58f183173f64dbaf9c00f8e9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IndexedMemProfReader::RadixTreeSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 705 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>

</div>
</div>

### Schema {#ac73628495225ebed4c5cf4eb9c5c8ad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">memprof::MemProfSchema llvm::IndexedMemProfReader::Schema</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MemProf profile schema (if available).</p>

<p>Definition at line 693 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>

</div>
</div>

### Version {#a42942b0630d32930461c62fa9273dd20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">memprof::IndexedVersion llvm::IndexedMemProfReader::Version</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The MemProf version.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      static_cast&lt;<a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecb">memprof::IndexedVersion</a>&gt;(<a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a721d2b84586b0bc5723c14c390570f61">memprof::MinimumSupportedVersion</a>)
</div>
</dd>
</dl>

<p>Definition at line 690 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
