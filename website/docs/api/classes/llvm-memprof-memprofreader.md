---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memprof/memprofreader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MemProfReader` Class



## Declaration

<div class="doxyDeclaration">
class llvm::memprof::MemProfReader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">llvm/ProfileData/MemProfReader.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memprof/rawmemprofreader">RawMemProfReader</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memprof/yamlmemprofreader">YAMLMemProfReader</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae57b87972d9c822df3642f18cae4e8bb">GuidMemProfRecordPair</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/memprofrecord">MemProfRecord</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53ac2746fda3daf0505b915f19a792d0">Iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/instrprofiterator">InstrProfIterator</a>&lt; <a href="#ae57b87972d9c822df3642f18cae4e8bb">GuidMemProfRecordPair</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/memprofreader">MemProfReader</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0da4721c479803134de1785c67a11f4">MemProfReader</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90da5ac1ddfa6bb0fcb68a4c4b855464">MemProfReader</a> (IndexedMemProfData &amp;&amp;MemProfData)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a250101986513995959ddde626107bf6b">~MemProfReader</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6">InstrProfKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a626c1bf18a5f4b151ffb9ebd59b4b867">getProfileKind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a53ac2746fda3daf0505b915f19a792d0">Iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a572fd22db0d70baab5143a2d69c7da">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a53ac2746fda3daf0505b915f19a792d0">Iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c92c06cdddcf09a7c945e48832f82a1">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofdata">IndexedMemProfData</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bed33ef56b099beacf0c6e32e8c38ef">takeMemProfData</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ebfa82e2e3b9ec55997fbad3f2a8e0c">readNextRecord</a> (GuidMemProfRecordPair &amp;GuidRecord, std::function&lt; const Frame(const FrameId)&gt; Callback=nullptr)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memprof/frame">Frame</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24cde697b280becd4df6c0e2eace1700">idToFrame</a> (const FrameId Id) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofdata">IndexedMemProfData</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5433f28dd23b726c305096acb90b3f23">MemProfData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">llvm::MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofrecord">IndexedMemProfRecord</a> &gt;::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9e99c4516b416d029a11cf49b01e8c8">Iter</a></td>
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


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### GuidMemProfRecordPair {#ae57b87972d9c822df3642f18cae4e8bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::memprof::MemProfReader::GuidMemProfRecordPair =  std::pair&lt;GlobalValue::GUID, MemProfRecord&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>

</div>
</div>

### Iterator {#a53ac2746fda3daf0505b915f19a792d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::memprof::MemProfReader::Iterator =  InstrProfIterator&lt;GuidMemProfRecordPair, MemProfReader&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MemProfReader() {#ab0da4721c479803134de1785c67a11f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::MemProfReader::MemProfReader ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>

</div>
</div>

### MemProfReader() {#a90da5ac1ddfa6bb0fcb68a4c4b855464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::MemProfReader::MemProfReader (<a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofdata">IndexedMemProfData</a> &amp;&amp; MemProfData)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>


<p>References <a href="#a5433f28dd23b726c305096acb90b3f23">MemProfData</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MemProfReader() {#a250101986513995959ddde626107bf6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::memprof::MemProfReader::~MemProfReader ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a5c92c06cdddcf09a7c945e48832f82a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Iterator llvm::memprof::MemProfReader::begin ()</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>


<p>References <a href="#aa9e99c4516b416d029a11cf49b01e8c8">Iter</a> and <a href="#a5433f28dd23b726c305096acb90b3f23">MemProfData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memprof/rawmemprofreader/#aa8752e79c1ff428a443a4bd1e5d57bf9">llvm::memprof::RawMemProfReader::RawMemProfReader</a>.</p>

</div>
</div>

### end() {#a0a572fd22db0d70baab5143a2d69c7da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Iterator llvm::memprof::MemProfReader::end ()</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memprof/rawmemprofreader/#aa8752e79c1ff428a443a4bd1e5d57bf9">llvm::memprof::RawMemProfReader::RawMemProfReader</a>.</p>

</div>
</div>

### getProfileKind() {#a626c1bf18a5f4b151ffb9ebd59b4b867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfKind llvm::memprof::MemProfReader::getProfileKind ()</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a980f9179e8eb4d61f05bdd8337813d2a">llvm::MemProf</a>.</p>

</div>
</div>

### readNextRecord() {#a7ebfa82e2e3b9ec55997fbad3f2a8e0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::memprof::MemProfReader::readNextRecord (<a href="#ae57b87972d9c822df3642f18cae4e8bb">GuidMemProfRecordPair</a> &amp; GuidRecord, std::function&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memprof/frame">Frame</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ae2c822b1c6260b47be435d3eda363ccc">FrameId</a>)&gt; Callback=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086ade5265a961682187df776519cb087d50">llvm::empty_raw_profile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086a2e51b1ab42e8a4a67f3445174be5191b">llvm::eof</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086acb2fe3792bca163395ce75d581440847">llvm::hash_mismatch</a>, <a href="#a24cde697b280becd4df6c0e2eace1700">idToFrame</a>, <a href="#aa9e99c4516b416d029a11cf49b01e8c8">Iter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#a5433f28dd23b726c305096acb90b3f23">MemProfData</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofrecord/#afc57e2621fdbae98ec406478a0bb55a3">llvm::memprof::IndexedMemProfRecord::toMemProfRecord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memprof/rawmemprofreader/#aa35ea12116aa94322f977239282e6e1e">llvm::memprof::RawMemProfReader::readNextRecord</a>.</p>

</div>
</div>

### takeMemProfData() {#a2bed33ef56b099beacf0c6e32e8c38ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedMemProfData llvm::memprof::MemProfReader::takeMemProfData ()</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>


<p>Reference <a href="#a5433f28dd23b726c305096acb90b3f23">MemProfData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### idToFrame() {#a24cde697b280becd4df6c0e2eace1700}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Frame &amp; llvm::memprof::MemProfReader::idToFrame (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ae2c822b1c6260b47be435d3eda363ccc">FrameId</a> Id)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a5433f28dd23b726c305096acb90b3f23">MemProfData</a>.</p>


<p>Referenced by <a href="#a7ebfa82e2e3b9ec55997fbad3f2a8e0c">readNextRecord</a> and <a href="/web-llvm/docs/api/classes/llvm/memprof/rawmemprofreader/#aa35ea12116aa94322f977239282e6e1e">llvm::memprof::RawMemProfReader::readNextRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Iter {#aa9e99c4516b416d029a11cf49b01e8c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MapVector&lt;GlobalValue::GUID,IndexedMemProfRecord&gt;::iterator llvm::memprof::MemProfReader::Iter</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>


<p>Referenced by <a href="#a5c92c06cdddcf09a7c945e48832f82a1">begin</a>, <a href="#a7ebfa82e2e3b9ec55997fbad3f2a8e0c">readNextRecord</a> and <a href="/web-llvm/docs/api/classes/llvm/memprof/rawmemprofreader/#aa35ea12116aa94322f977239282e6e1e">llvm::memprof::RawMemProfReader::readNextRecord</a>.</p>

</div>
</div>

### MemProfData {#a5433f28dd23b726c305096acb90b3f23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedMemProfData llvm::memprof::MemProfReader::MemProfData</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>


<p>Referenced by <a href="#a5c92c06cdddcf09a7c945e48832f82a1">begin</a>, <a href="#a24cde697b280becd4df6c0e2eace1700">idToFrame</a>, <a href="#a90da5ac1ddfa6bb0fcb68a4c4b855464">MemProfReader</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/yamlmemprofreader/#aa050d96fe18573b4d459a769f576f1dc">llvm::memprof::YAMLMemProfReader::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/rawmemprofreader/#a2265dbec910f82a9711acc0619cfc1cb">llvm::memprof::RawMemProfReader::printYAML</a>, <a href="#a7ebfa82e2e3b9ec55997fbad3f2a8e0c">readNextRecord</a> and <a href="#a2bed33ef56b099beacf0c6e32e8c38ef">takeMemProfData</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
