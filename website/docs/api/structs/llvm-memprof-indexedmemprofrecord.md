---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/memprof/indexedmemprofrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `IndexedMemProfRecord` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::memprof::IndexedMemProfRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">llvm/ProfileData/MemProf.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd63e1b91e368bb63bf690792370edce">operator==</a> (const IndexedMemProfRecord &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04b71e5480ab3f5a67ca460f01f9b178">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9324cc9b2703c6746d8e1c0095a89b9">merge</a> (const IndexedMemProfRecord &amp;Other)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a676ef01c0e07151ce1ecba7f39ca0980">serializedSize</a> (const MemProfSchema &amp;Schema, IndexedVersion Version) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74d38b755f6339404dae0b4627bd7a78">serialize</a> (const MemProfSchema &amp;Schema, raw_ostream &amp;OS, IndexedVersion Version, llvm::DenseMap&lt; CallStackId, LinearCallStackId &gt; *MemProfCallStackIndexes=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/memprof/memprofrecord">MemProfRecord</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc57e2621fdbae98ec406478a0bb55a3">toMemProfRecord</a> (llvm::function_ref&lt; std::vector&lt; Frame &gt;(const CallStackId)&gt; Callback) const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedallocationinfo">IndexedAllocationInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41e6206cdacc4b9e172f1dd222f439fe">AllocSites</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acccd58d8f1e260d41aec72e4ce5e847f">CallStackId</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21be5df80ae1f2034f2479fabcfa5d3e">CallSiteIds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofrecord">IndexedMemProfRecord</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90bbb2d6a11e3047ec5be620482cd6d6">deserialize</a> (const MemProfSchema &amp;Schema, const unsigned char *Buffer, IndexedVersion Version)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace5015b378d124a205da5a1eaf98061e">getGUID</a> (const StringRef FunctionName)</td>
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


<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator==() {#abd63e1b91e368bb63bf690792370edce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::memprof::IndexedMemProfRecord::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofrecord">IndexedMemProfRecord</a> &amp; Other)</td>
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



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>References <a href="#a41e6206cdacc4b9e172f1dd222f439fe">AllocSites</a>, <a href="#a21be5df80ae1f2034f2479fabcfa5d3e">CallSiteIds</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#a04b71e5480ab3f5a67ca460f01f9b178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::memprof::IndexedMemProfRecord::clear ()</td>
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



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### merge() {#af9324cc9b2703c6746d8e1c0095a89b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::memprof::IndexedMemProfRecord::merge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofrecord">IndexedMemProfRecord</a> &amp; Other)</td>
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



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>References <a href="#a41e6206cdacc4b9e172f1dd222f439fe">AllocSites</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### serialize() {#a74d38b755f6339404dae0b4627bd7a78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::memprof::IndexedMemProfRecord::serialize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a4c0e5dd93f0bc1942fcd93ae8e7a23ea">MemProfSchema</a> &amp; Schema, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecb">IndexedVersion</a> Version, <a href="/web-llvm/docs/api/classes/llvm/densemap">llvm::DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acccd58d8f1e260d41aec72e4ce5e847f">CallStackId</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a271f954222d61bd5dc7f5cb5dd836b52">LinearCallStackId</a> &gt; * MemProfCallStackIndexes=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprof-cpp">MemProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#abf906f72a8e8c44574d1cfcfd020701f">llvm::memprof::serializeV2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a2e8afc6631c5a017ffef151a9d1fe7f6">llvm::memprof::serializeV3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecbaa4580b818c5644cc40399914cc86c227">llvm::memprof::Version2</a> and <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecbafe029208a9df98e11b723897a0f19b8d">llvm::memprof::Version3</a>.</p>

</div>
</div>

### serializedSize() {#a676ef01c0e07151ce1ecba7f39ca0980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::memprof::IndexedMemProfRecord::serializedSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a4c0e5dd93f0bc1942fcd93ae8e7a23ea">MemProfSchema</a> &amp; Schema, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecb">IndexedVersion</a> Version)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprof-cpp">MemProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a49bcf18527d9a40d5eee1eb44821cbcb">llvm::memprof::serializedSizeV2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a5f06862de128b8a111f2ac9183fa2dee">llvm::memprof::serializedSizeV3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecbaa4580b818c5644cc40399914cc86c227">llvm::memprof::Version2</a> and <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecbafe029208a9df98e11b723897a0f19b8d">llvm::memprof::Version3</a>.</p>

</div>
</div>

### toMemProfRecord() {#afc57e2621fdbae98ec406478a0bb55a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemProfRecord llvm::memprof::IndexedMemProfRecord::toMemProfRecord (<a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/memprof/frame">Frame</a> &gt;(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acccd58d8f1e260d41aec72e4ce5e847f">CallStackId</a>)&gt; Callback)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>, definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprof-cpp">MemProf.cpp</a>.</p>


<p>References <a href="#a41e6206cdacc4b9e172f1dd222f439fe">AllocSites</a>, <a href="#a21be5df80ae1f2034f2479fabcfa5d3e">CallSiteIds</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/allocationinfo/#a09e66c1a54259cfb1ba348abef976058">llvm::memprof::AllocationInfo::CallStack</a> and <a href="/web-llvm/docs/api/structs/llvm/memprof/allocationinfo/#a3752a895ac142ca07c83615a33bd5740">llvm::memprof::AllocationInfo::Info</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#ae36ae2256fb0b0ad06486d65f4237cfb">getMemProfRecordV2</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#ae3e9115aa20b0cbd4f800f0892e82153">getMemProfRecordV3</a> and <a href="/web-llvm/docs/api/classes/llvm/memprof/memprofreader/#a7ebfa82e2e3b9ec55997fbad3f2a8e0c">llvm::memprof::MemProfReader::readNextRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AllocSites {#a41e6206cdacc4b9e172f1dd222f439fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallVector&lt;IndexedAllocationInfo&gt; llvm::memprof::IndexedMemProfRecord::AllocSites</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>Referenced by <a href="#af9324cc9b2703c6746d8e1c0095a89b9">merge</a>, <a href="#abd63e1b91e368bb63bf690792370edce">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/yamlmemprofreader/#aa050d96fe18573b4d459a769f576f1dc">llvm::memprof::YAMLMemProfReader::parse</a> and <a href="#afc57e2621fdbae98ec406478a0bb55a3">toMemProfRecord</a>.</p>

</div>
</div>

### CallSiteIds {#a21be5df80ae1f2034f2479fabcfa5d3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallVector&lt;CallStackId&gt; llvm::memprof::IndexedMemProfRecord::CallSiteIds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>Referenced by <a href="#abd63e1b91e368bb63bf690792370edce">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/yamlmemprofreader/#aa050d96fe18573b4d459a769f576f1dc">llvm::memprof::YAMLMemProfReader::parse</a> and <a href="#afc57e2621fdbae98ec406478a0bb55a3">toMemProfRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### deserialize() {#a90bbb2d6a11e3047ec5be620482cd6d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedMemProfRecord llvm::memprof::IndexedMemProfRecord::deserialize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a4c0e5dd93f0bc1942fcd93ae8e7a23ea">MemProfSchema</a> &amp; Schema, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * Buffer, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecb">IndexedVersion</a> Version)</td>
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



<p>Declaration at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprof-cpp">MemProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acaa5a5ff92b2d28c6d06e8c933f6b532">llvm::memprof::deserializeV2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a2ac7af3ec53f7157147c7537fb810e96">llvm::memprof::deserializeV3</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecbaa4580b818c5644cc40399914cc86c227">llvm::memprof::Version2</a> and <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecbafe029208a9df98e11b723897a0f19b8d">llvm::memprof::Version3</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memprof/recordlookuptrait/#a211fcde1bf18afc34c9bfe934758285d">llvm::memprof::RecordLookupTrait::ReadData</a>.</p>

</div>
</div>

### getGUID() {#ace5015b378d124a205da5a1eaf98061e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalValue::GUID llvm::memprof::IndexedMemProfRecord::getGUID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FunctionName)</td>
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



<p>Declaration at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>, definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprof-cpp">MemProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa7122a07ea48e47fc71083e68b829003">llvm::sampleprof::FunctionSamples::getCanonicalFnName</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a71ee7e63264e4997a3340a781d44832e">llvm::GlobalValue::getGUID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a632491c0fb6b223c9661724d5f14fd31">llvm::memprof::extractCallsFromIR</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-82dfc8fdcf1a7d905277eea83929c8be/#a0e0953b3d0f992087e7c16fd37e61437">llvm::yaml::ScalarTraits&lt; memprof::GUIDHex64 &gt;::input</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprof-cpp">MemProf.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
