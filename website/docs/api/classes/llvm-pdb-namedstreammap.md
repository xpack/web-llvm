---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pdb/namedstreammap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `NamedStreamMap` Class



## Declaration

<div class="doxyDeclaration">
class llvm::pdb::NamedStreamMap { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/namedstreammap-h">llvm/DebugInfo/PDB/Native/NamedStreamMap.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf4de0999770849f43b219a64bc84b7b">NamedStreamMapBuilder</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61d11937602094f0221d127e85969e9e">NamedStreamMap</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f4507809faf33bf017aeb193cf9d617">load</a> (BinaryStreamReader &amp;Stream)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6253147b299d9a15f29775b79c273d3c">commit</a> (BinaryStreamWriter &amp;Writer) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae90efe8b7671ce6760aabbf744a119a1">calculateSerializedLength</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada4e5b750986027affba61be5b5bcdc1">size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fd4c4000c48a4c15423dbccea18d1e8">get</a> (StringRef Stream, uint32_t &amp;StreamNo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0985a55ec581f9ab41c52a816366ab6b">set</a> (StringRef Stream, uint32_t StreamNo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bef284bcaf877c808f6067d1992b122">appendStringData</a> (StringRef S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6efaae52bb754bffbda4d7b17a71852">getString</a> (uint32_t Offset) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66430d1ebb79c786efbf8b5a1921bca8">hashString</a> (uint32_t Offset) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b4e33382cf6ebc9442fded9aefb5627">entries</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/pdb/namedstreammaptraits">NamedStreamMapTraits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f8d8834b9ec052ac4c742379e7a7572">HashTraits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/hashtable">HashTable</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a673ea69728d75616f0c4b606302c1543">OffsetIndexMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Closed hash table from Offset -&gt; StreamNumber, where Offset is the offset of the stream name in NamesBuffer. <a href="#a673ea69728d75616f0c4b606302c1543">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; char &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87dad79aa24e4a9bd7b4bd4dda517907">NamesBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Buffer of string data. <a href="#a87dad79aa24e4a9bd7b4bd4dda517907">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/namedstreammap-h">NamedStreamMap.h</a>.</p>


<div class="doxySectionDef">

## Friends

### NamedStreamMapBuilder {#adf4de0999770849f43b219a64bc84b7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class NamedStreamMapBuilder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/namedstreammap-h">NamedStreamMap.h</a>.</p>


<p>References <a href="#adf4de0999770849f43b219a64bc84b7b">NamedStreamMapBuilder</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadfd0a82c4bf37b1e90b690a22a20692e">llvm::pdb::Offset</a>.</p>


<p>Referenced by <a href="#adf4de0999770849f43b219a64bc84b7b">NamedStreamMapBuilder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### NamedStreamMap() {#a61d11937602094f0221d127e85969e9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedStreamMap::NamedStreamMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/namedstreammap-h">NamedStreamMap.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/namedstreammap-cpp">NamedStreamMap.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### appendStringData() {#a6bef284bcaf877c808f6067d1992b122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t NamedStreamMap::appendStringData (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/namedstreammap-h">NamedStreamMap.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/namedstreammap-cpp">NamedStreamMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadfd0a82c4bf37b1e90b690a22a20692e">llvm::pdb::Offset</a>.</p>

</div>
</div>

### calculateSerializedLength() {#ae90efe8b7671ce6760aabbf744a119a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t NamedStreamMap::calculateSerializedLength ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/namedstreammap-h">NamedStreamMap.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/namedstreammap-cpp">NamedStreamMap.cpp</a>.</p>

</div>
</div>

### commit() {#a6253147b299d9a15f29775b79c273d3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error NamedStreamMap::commit (<a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter">BinaryStreamWriter</a> &amp; Writer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/namedstreammap-h">NamedStreamMap.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/namedstreammap-cpp">NamedStreamMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30baf6068daa29dbb05a7ead1e3b5a48bbee">llvm::pdb::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#ac9c2dc641243ad8170ac9c0e69545f37">llvm::BinaryStreamWriter::writeFixedString</a> and <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#a344647bc1c4a4b53334296eba145d408">llvm::BinaryStreamWriter::writeInteger</a>.</p>

</div>
</div>

### entries() {#a4b4e33382cf6ebc9442fded9aefb5627}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt; uint32_t &gt; NamedStreamMap::entries ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/namedstreammap-h">NamedStreamMap.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/namedstreammap-cpp">NamedStreamMap.cpp</a>.</p>

</div>
</div>

### get() {#a9fd4c4000c48a4c15423dbccea18d1e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NamedStreamMap::get (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Stream, uint32_t &amp; StreamNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/namedstreammap-h">NamedStreamMap.h</a>, definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/namedstreammap-cpp">NamedStreamMap.cpp</a>.</p>

</div>
</div>

### getString() {#ac6efaae52bb754bffbda4d7b17a71852}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef NamedStreamMap::getString (uint32_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/namedstreammap-h">NamedStreamMap.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/namedstreammap-cpp">NamedStreamMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadfd0a82c4bf37b1e90b690a22a20692e">llvm::pdb::Offset</a>.</p>


<p>Referenced by <a href="#a66430d1ebb79c786efbf8b5a1921bca8">hashString</a>.</p>

</div>
</div>

### hashString() {#a66430d1ebb79c786efbf8b5a1921bca8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t NamedStreamMap::hashString (uint32_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/namedstreammap-h">NamedStreamMap.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/namedstreammap-cpp">NamedStreamMap.cpp</a>.</p>


<p>References <a href="#ac6efaae52bb754bffbda4d7b17a71852">getString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a1737ab2b5a4c39b8eb3fcbd2e47abb65">llvm::pdb::hashStringV1</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadfd0a82c4bf37b1e90b690a22a20692e">llvm::pdb::Offset</a>.</p>

</div>
</div>

### load() {#a1f4507809faf33bf017aeb193cf9d617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error NamedStreamMap::load (<a href="/web-llvm/docs/api/classes/llvm/binarystreamreader">BinaryStreamReader</a> &amp; Stream)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/namedstreammap-h">NamedStreamMap.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/namedstreammap-cpp">NamedStreamMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a573bcbbea76b4d72b33de1e392cc14aea8c4fdeb9f0256322a364cd1347a6ffd6">llvm::pdb::corrupt_file</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#aac42f02dfb2a8bbe2f6bedea0ff7b29c">llvm::BinaryStreamReader::readFixedString</a> and <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a6bb348b0b716cb9d060ecaef7a49dcc6">llvm::BinaryStreamReader::readInteger</a>.</p>

</div>
</div>

### set() {#a0985a55ec581f9ab41c52a816366ab6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NamedStreamMap::set (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Stream, uint32_t StreamNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/namedstreammap-h">NamedStreamMap.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/namedstreammap-cpp">NamedStreamMap.cpp</a>.</p>

</div>
</div>

### size() {#ada4e5b750986027affba61be5b5bcdc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t NamedStreamMap::size ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/namedstreammap-h">NamedStreamMap.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/namedstreammap-cpp">NamedStreamMap.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### HashTraits {#a3f8d8834b9ec052ac4c742379e7a7572}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedStreamMapTraits llvm::pdb::NamedStreamMap::HashTraits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/namedstreammap-h">NamedStreamMap.h</a>.</p>

</div>
</div>

### NamesBuffer {#a87dad79aa24e4a9bd7b4bd4dda517907}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;char&gt; llvm::pdb::NamedStreamMap::NamesBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Buffer of string data.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/namedstreammap-h">NamedStreamMap.h</a>.</p>

</div>
</div>

### OffsetIndexMap {#a673ea69728d75616f0c4b606302c1543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashTable&lt;support::ulittle32_t&gt; llvm::pdb::NamedStreamMap::OffsetIndexMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Closed hash table from Offset -&gt; StreamNumber, where Offset is the offset of the stream name in NamesBuffer.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/namedstreammap-h">NamedStreamMap.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/namedstreammap-h">NamedStreamMap.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/namedstreammap-cpp">NamedStreamMap.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
