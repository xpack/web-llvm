---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/writablebinarystreamref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WritableBinaryStreamRef` Class



## Declaration

<div class="doxyDeclaration">
class llvm::WritableBinaryStreamRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">llvm/Support/BinaryStreamRef.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase">BinaryStreamRefBase&lt;RefType, StreamType&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common stuff for mutable and immutable StreamRefs. <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c952847936900ca9c610a11368bfc74">WritableBinaryStreamRef</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af568ae5bed394faf437752e8be0fbfe1">WritableBinaryStreamRef</a> (WritableBinaryStream &amp;Stream)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47e6dc88dd26b78ac8b38dcd5f26a04b">WritableBinaryStreamRef</a> (WritableBinaryStream &amp;Stream, uint64_t Offset, std::optional&lt; uint64_t &gt; Length)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7039ed2a2b555d1b371144132826b5a">WritableBinaryStreamRef</a> (MutableArrayRef&lt; uint8_t &gt; Data, llvm::endianness Endian)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58d1f216849f736bad719b21b4a16073">WritableBinaryStreamRef</a> (const WritableBinaryStreamRef &amp;Other)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5832831fa83b640533a6adbf0a83dfe">WritableBinaryStreamRef</a> (WritableBinaryStreamRef &amp;&amp;Other)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab27516cf8232753abf7043f11c283fbe">WritableBinaryStreamRef</a> (WritableBinaryStreamRef &amp;S, uint64_t Offset, uint64_t Length)=delete</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15b31e4862b16c8b793a894e27a2b1d6">WritableBinaryStreamRef</a> (std::shared_ptr&lt; WritableBinaryStream &gt; Impl, uint64_t ViewOffset, std::optional&lt; uint64_t &gt; Length)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a332e6cf3fcb2e0ef5f9899c45f91cde5">operator=</a> (const WritableBinaryStreamRef &amp;Other)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7ee30f7bbd394022d8358fee7bb13d3">operator=</a> (WritableBinaryStreamRef &amp;&amp;Other)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b51f54bfddfe3aa3804b05e7f5bbbc8">operator BinaryStreamRef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Conver this <a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a> to a read-only <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a>. <a href="#a0b51f54bfddfe3aa3804b05e7f5bbbc8">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd7a4936fd39218e5df5cb21a557c77b">writeBytes</a> (uint64_t Offset, ArrayRef&lt; uint8_t &gt; Data) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an Offset into this <a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a> and some input data, writes the data to the underlying stream. <a href="#abd7a4936fd39218e5df5cb21a557c77b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae236e174f6c6dce2c0f980acbd30e59a">commit</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For buffered streams, commits changes to the backing store. <a href="#ae236e174f6c6dce2c0f980acbd30e59a">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3df12fbd24120a7704b4f2afecd7a66b">checkOffsetForWrite</a> (uint64_t Offset, uint64_t DataSize) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69d59779e5450e8b2421322504ac9bb9">BinaryStreamRefBase&lt; WritableBinaryStreamRef, WritableBinaryStream &gt;</a></td>
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


<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WritableBinaryStreamRef() {#a7c952847936900ca9c610a11368bfc74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WritableBinaryStreamRef::WritableBinaryStreamRef ()</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a21140b1c590fc1d8b27660316e725648">llvm::BinaryStreamRefBase&lt; WritableBinaryStreamRef, WritableBinaryStream &gt;::Length</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### WritableBinaryStreamRef() {#af568ae5bed394faf437752e8be0fbfe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WritableBinaryStreamRef::WritableBinaryStreamRef (<a href="/web-llvm/docs/api/classes/llvm/writablebinarystream">WritableBinaryStream</a> &amp; Stream)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamref-cpp">BinaryStreamRef.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a49a0d2084d0b02ccf53238b2683b04b8">llvm::BinaryStreamRefBase&lt; WritableBinaryStreamRef, WritableBinaryStream &gt;::BinaryStreamRefBase</a>.</p>

</div>
</div>

### WritableBinaryStreamRef() {#a47e6dc88dd26b78ac8b38dcd5f26a04b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WritableBinaryStreamRef::WritableBinaryStreamRef (<a href="/web-llvm/docs/api/classes/llvm/writablebinarystream">WritableBinaryStream</a> &amp; Stream, uint64_t Offset, std::optional&lt; uint64_t &gt; Length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>, definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamref-cpp">BinaryStreamRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a49a0d2084d0b02ccf53238b2683b04b8">llvm::BinaryStreamRefBase&lt; WritableBinaryStreamRef, WritableBinaryStream &gt;::BinaryStreamRefBase</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a21140b1c590fc1d8b27660316e725648">llvm::BinaryStreamRefBase&lt; WritableBinaryStreamRef, WritableBinaryStream &gt;::Length</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### WritableBinaryStreamRef() {#ae7039ed2a2b555d1b371144132826b5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WritableBinaryStreamRef::WritableBinaryStreamRef (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; uint8_t &gt; Data, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> Endian)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamref-cpp">BinaryStreamRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a49a0d2084d0b02ccf53238b2683b04b8">llvm::BinaryStreamRefBase&lt; WritableBinaryStreamRef, WritableBinaryStream &gt;::BinaryStreamRefBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>

</div>
</div>

### WritableBinaryStreamRef() {#a58d1f216849f736bad719b21b4a16073}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WritableBinaryStreamRef::WritableBinaryStreamRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a> &amp; Other)</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### WritableBinaryStreamRef() {#aa5832831fa83b640533a6adbf0a83dfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WritableBinaryStreamRef::WritableBinaryStreamRef (<a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a> &amp;&amp; Other)</td>
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



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### WritableBinaryStreamRef() {#ab27516cf8232753abf7043f11c283fbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WritableBinaryStreamRef::WritableBinaryStreamRef (<a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a> &amp; S, uint64_t Offset, uint64_t Length)</td>
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



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a21140b1c590fc1d8b27660316e725648">llvm::BinaryStreamRefBase&lt; WritableBinaryStreamRef, WritableBinaryStream &gt;::Length</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### WritableBinaryStreamRef() {#a15b31e4862b16c8b793a894e27a2b1d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WritableBinaryStreamRef::WritableBinaryStreamRef (std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/writablebinarystream">WritableBinaryStream</a> &gt; Impl, uint64_t ViewOffset, std::optional&lt; uint64_t &gt; Length)</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator BinaryStreamRef() {#a0b51f54bfddfe3aa3804b05e7f5bbbc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WritableBinaryStreamRef::operator BinaryStreamRef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Conver this <a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a> to a read-only <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a>.</p>

<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>, definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamref-cpp">BinaryStreamRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a57d4b980379fd31d3be943f4b66136c1">llvm::BinaryStreamRefBase&lt; WritableBinaryStreamRef, WritableBinaryStream &gt;::BorrowedImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a21140b1c590fc1d8b27660316e725648">llvm::BinaryStreamRefBase&lt; WritableBinaryStreamRef, WritableBinaryStream &gt;::Length</a> and <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a18d69c1ec33fe3424f1334fbc7eb2553">llvm::BinaryStreamRefBase&lt; WritableBinaryStreamRef, WritableBinaryStream &gt;::ViewOffset</a>.</p>

</div>
</div>

### operator=() {#a332e6cf3fcb2e0ef5f9899c45f91cde5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WritableBinaryStreamRef &amp; llvm::WritableBinaryStreamRef::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a> &amp; Other)</td>
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



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator=() {#ad7ee30f7bbd394022d8358fee7bb13d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WritableBinaryStreamRef &amp; llvm::WritableBinaryStreamRef::operator= (<a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a> &amp;&amp; Other)</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### commit() {#ae236e174f6c6dce2c0f980acbd30e59a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WritableBinaryStreamRef::commit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For buffered streams, commits changes to the backing store.</p>

<p>Declaration at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamref-cpp">BinaryStreamRef.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a57d4b980379fd31d3be943f4b66136c1">llvm::BinaryStreamRefBase&lt; WritableBinaryStreamRef, WritableBinaryStream &gt;::BorrowedImpl</a>.</p>

</div>
</div>

### writeBytes() {#abd7a4936fd39218e5df5cb21a557c77b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WritableBinaryStreamRef::writeBytes (uint64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an Offset into this <a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a> and some input data, writes the data to the underlying stream.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data could fit within the underlying stream at the specified location and the implementation could write the data, and an appropriate error code otherwise.</p></dd>
</dl>


<p>Declaration at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamref-cpp">BinaryStreamRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a57d4b980379fd31d3be943f4b66136c1">llvm::BinaryStreamRefBase&lt; WritableBinaryStreamRef, WritableBinaryStream &gt;::BorrowedImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a18d69c1ec33fe3424f1334fbc7eb2553">llvm::BinaryStreamRefBase&lt; WritableBinaryStreamRef, WritableBinaryStream &gt;::ViewOffset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### checkOffsetForWrite() {#a3df12fbd24120a7704b4f2afecd7a66b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::WritableBinaryStreamRef::checkOffsetForWrite (uint64_t Offset, uint64_t DataSize)</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BinaryStreamRefBase&lt; WritableBinaryStreamRef, WritableBinaryStream &gt; {#a69d59779e5450e8b2421322504ac9bb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::WritableBinaryStreamRef::BinaryStreamRefBase&lt; WritableBinaryStreamRef, WritableBinaryStream &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamref-cpp">BinaryStreamRef.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
