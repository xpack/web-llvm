---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/codeview/globallyhashedtype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `GloballyHashedType` Struct Reference

<p>A globally hashed type represents a hash value that is sufficient to uniquely identify a record across multiple type streams or type sequences. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::codeview::GloballyHashedType { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">llvm/DebugInfo/CodeView/TypeHashing.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb717a0de847b653248386cd876bb769">operator==</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe715f25e75d67f1cd3af29f74b6b7a2">operator!=</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d71869a4b3222d94a767d6acaf44bfb">GloballyHashedType</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6187e62765a3436e1a54be53185b2851">GloballyHashedType</a> (StringRef H)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb0a4bd82eb78f6b5d05100ecda36ca3">GloballyHashedType</a> (ArrayRef&lt; uint8_t &gt; H)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab008cff866a105b3ac98224eae319368">empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; uint8_t, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af39bc903015b6ff04b69408fd3d540e8">Hash</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc7b052c15351bf328b64c17027eae9d">hashType</a> (ArrayRef&lt; uint8_t &gt; RecordData, ArrayRef&lt; GloballyHashedType &gt; PreviousTypes, ArrayRef&lt; GloballyHashedType &gt; PreviousIds)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a sequence of bytes representing a record, compute a global hash for this record. <a href="#acc7b052c15351bf328b64c17027eae9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a255d317ab4d329682e293822425f1b8a">hashType</a> (CVType Type, ArrayRef&lt; GloballyHashedType &gt; PreviousTypes, ArrayRef&lt; GloballyHashedType &gt; PreviousIds)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a sequence of bytes representing a record, compute a global hash for this record. <a href="#a255d317ab4d329682e293822425f1b8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Range&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5f7fce68e7d728ac1022557a7b957a44">hashTypes</a> (Range &amp;&amp;Records) -&gt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a sequence of combined type and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> records, compute global hashes for each of them, returning the results in a vector of hashed types. <a href="#a5f7fce68e7d728ac1022557a7b957a44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Range&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a408fc14381e372f9f2a0ec355c67851e">hashIds</a> (Range &amp;&amp;Records, ArrayRef&lt; GloballyHashedType &gt; TypeHashes) -&gt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a sequence of combined type and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> records, compute global hashes for each of them, returning the results in a vector of hashed types. <a href="#a408fc14381e372f9f2a0ec355c67851e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a3fdd368e8b044861dc2fcf239df3b0">hashTypeCollection</a> (TypeCollection &amp;Types)</td>
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

<p>A globally hashed type represents a hash value that is sufficient to uniquely identify a record across multiple type streams or type sequences.</p>


<p>This works by, for any given record A which references B, replacing the <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> that refers to B with a previously-computed global hash for B. As this is a recursive algorithm (e.g. the global hash of B also depends on the global hashes of the types that B refers to), a global hash can uniquely identify that A occurs in another stream that has a completely different graph structure. Although the hash itself is slower to compute, probing is much faster with a globally hashed type, because the hash itself is considered "as good as" the original type. Since type records can be quite large, this makes the equality comparison of the hash much faster than equality comparison of a full record.</p>


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a>.</p>


<div class="doxySectionDef">

## Friends

### operator!= {#afe715f25e75d67f1cd3af29f74b6b7a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a> &amp; R</td>
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


<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a>.</p>


<p>Reference <a href="#a9d71869a4b3222d94a767d6acaf44bfb">GloballyHashedType</a>.</p>

</div>
</div>

### operator== {#abb717a0de847b653248386cd876bb769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a> &amp; R</td>
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


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a>.</p>


<p>Reference <a href="#a9d71869a4b3222d94a767d6acaf44bfb">GloballyHashedType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GloballyHashedType() {#a9d71869a4b3222d94a767d6acaf44bfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::GloballyHashedType::GloballyHashedType ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a>.</p>


<p>Referenced by <a href="#a6187e62765a3436e1a54be53185b2851">GloballyHashedType</a>, <a href="#a255d317ab4d329682e293822425f1b8a">hashType</a>, <a href="#a5f7fce68e7d728ac1022557a7b957a44">hashTypes</a>, <a href="#afe715f25e75d67f1cd3af29f74b6b7a2">operator!=</a> and <a href="#abb717a0de847b653248386cd876bb769">operator==</a>.</p>

</div>
</div>

### GloballyHashedType() {#a6187e62765a3436e1a54be53185b2851}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::GloballyHashedType::GloballyHashedType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> H)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a>.</p>


<p>References <a href="#a9d71869a4b3222d94a767d6acaf44bfb">GloballyHashedType</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>.</p>

</div>
</div>

### GloballyHashedType() {#abb0a4bd82eb78f6b5d05100ecda36ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::GloballyHashedType::GloballyHashedType (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; H)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a> and <a href="#af39bc903015b6ff04b69408fd3d540e8">Hash</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### empty() {#ab008cff866a105b3ac98224eae319368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codeview::GloballyHashedType::empty ()</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a>.</p>


<p>Reference <a href="#af39bc903015b6ff04b69408fd3d540e8">Hash</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Hash {#af39bc903015b6ff04b69408fd3d540e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;uint8_t, 8&gt; llvm::codeview::GloballyHashedType::Hash</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a>.</p>


<p>Referenced by <a href="#ab008cff866a105b3ac98224eae319368">empty</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-faf352d6e414689b835e290211af46e2/#a054cdb56eaed77c31e2d3d75e0570305">llvm::DenseMapInfo&lt; codeview::GloballyHashedType &gt;::getHashValue</a> and <a href="#abb0a4bd82eb78f6b5d05100ecda36ca3">GloballyHashedType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### hashIds() {#a408fc14381e372f9f2a0ec355c67851e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Range&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; GloballyHashedType &gt; llvm::codeview::GloballyHashedType::hashIds (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> &amp;&amp; Records, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a> &gt; TypeHashes)</td>
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

<p>Given a sequence of combined type and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> records, compute global hashes for each of them, returning the results in a vector of hashed types.</p>

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a>.</p>


<p>References <a href="#acc7b052c15351bf328b64c17027eae9d">hashType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

### hashType() {#acc7b052c15351bf328b64c17027eae9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GloballyHashedType GloballyHashedType::hashType (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; RecordData, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a> &gt; PreviousTypes, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a> &gt; PreviousIds)</td>
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

<p>Given a sequence of bytes representing a record, compute a global hash for this record.</p>


<p>Due to the nature of global hashes incorporating the hashes of referenced records, this function requires a list of types and ids that RecordData might reference, indexable by <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a>.</p>


<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp">TypeHashing.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a472577b022e0997fbd409d82078df025">llvm::codeview::discoverTypeIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a55089293ebaccd683a82d97170041376">llvm::ArrayRef&lt; T &gt;::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/truncatedblake3/#a289292a235757336d881f2d2786b09bd">llvm::TruncatedBLAKE3&lt; NumBytes &gt;::final</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a15b96719effacbb3d6e211f4ef768d98ae4b32150368e5a8a701eb52dc75c769f">llvm::codeview::IndexRef</a>, <a href="/web-llvm/docs/api/classes/llvm/blake3/#ac459cabc1efbb1af18f617940113eccb">llvm::BLAKE3::init</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a33da2ddf6f447892591c86d9d3771b9c">llvm::ArrayRef&lt; T &gt;::take_front</a> and <a href="/web-llvm/docs/api/classes/llvm/blake3/#ad247de2450380eeba2fab0e794d5e44f">llvm::BLAKE3::update</a>.</p>


<p>Referenced by <a href="#a408fc14381e372f9f2a0ec355c67851e">hashIds</a>, <a href="#a255d317ab4d329682e293822425f1b8a">hashType</a>, <a href="#a8a3fdd368e8b044861dc2fcf239df3b0">hashTypeCollection</a>, <a href="#a5f7fce68e7d728ac1022557a7b957a44">hashTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/globaltypetablebuilder/#a77a93c8bf83d76706a8486e7df17c5d7">llvm::codeview::GlobalTypeTableBuilder::insertRecordBytes</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/globaltypetablebuilder/#aa8b7c684352cfa5cebef256df3df6955">llvm::codeview::GlobalTypeTableBuilder::replaceType</a>.</p>

</div>
</div>

### hashType() {#a255d317ab4d329682e293822425f1b8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GloballyHashedType llvm::codeview::GloballyHashedType::hashType (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> Type, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a> &gt; PreviousTypes, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a> &gt; PreviousIds)</td>
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

<p>Given a sequence of bytes representing a record, compute a global hash for this record.</p>


<p>Due to the nature of global hashes incorporating the hashes of referenced records, this function requires a list of types and ids that RecordData might reference, indexable by <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a>.</p>


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a>.</p>


<p>References <a href="#a9d71869a4b3222d94a767d6acaf44bfb">GloballyHashedType</a> and <a href="#acc7b052c15351bf328b64c17027eae9d">hashType</a>.</p>

</div>
</div>

### hashTypeCollection() {#a8a3fdd368e8b044861dc2fcf239df3b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; GloballyHashedType &gt; llvm::codeview::GloballyHashedType::hashTypeCollection (<a href="/web-llvm/docs/api/classes/llvm/codeview/typecollection">TypeCollection</a> &amp; Types)</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a>.</p>


<p>Reference <a href="#acc7b052c15351bf328b64c17027eae9d">hashType</a>.</p>

</div>
</div>

### hashTypes() {#a5f7fce68e7d728ac1022557a7b957a44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Range&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; GloballyHashedType &gt; llvm::codeview::GloballyHashedType::hashTypes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> &amp;&amp; Records)</td>
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

<p>Given a sequence of combined type and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> records, compute global hashes for each of them, returning the results in a vector of hashed types.</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a>.</p>


<p>References <a href="#a9d71869a4b3222d94a767d6acaf44bfb">GloballyHashedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="#acc7b052c15351bf328b64c17027eae9d">hashType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp">TypeHashing.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
