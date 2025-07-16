---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/binarystreamref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BinaryStreamRef` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> is to <a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a> what <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> is to an Array. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BinaryStreamRef { ... }
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad79b93dab411be639514e8461d620880">WritableBinaryStreamRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7b5539f398381351a5474d6c0e5ff74">BinaryStreamRef</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82772ee4a96456ef2820de05792608a3">BinaryStreamRef</a> (BinaryStream &amp;Stream)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad224dee9fdde4a364476a1c9f8d2c210">BinaryStreamRef</a> (BinaryStream &amp;Stream, uint64_t Offset, std::optional&lt; uint64_t &gt; Length)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f6dfb05bf82ed251de988dfed56269d">BinaryStreamRef</a> (ArrayRef&lt; uint8_t &gt; Data, llvm::endianness Endian)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af18f204e2ccacb08c375a214ad6f44b3">BinaryStreamRef</a> (StringRef Data, llvm::endianness Endian)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e39bad2dd64314ae8fe83c4f1fdb9c8">BinaryStreamRef</a> (const BinaryStreamRef &amp;Other)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a041d6148ea0451863ac79db1d634eb1a">BinaryStreamRef</a> (BinaryStreamRef &amp;&amp;Other)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab21483836d3fe3bbbe811161da053857">BinaryStreamRef</a> (BinaryStreamRef &amp;S, uint64_t Offset, uint64_t Length)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b514cad0096803f94a9d7eb47e414c1">BinaryStreamRef</a> (std::shared_ptr&lt; BinaryStream &gt; Impl, uint64_t ViewOffset, std::optional&lt; uint64_t &gt; Length)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe6fa300fea20f281e9708881b0a32a8">operator=</a> (const BinaryStreamRef &amp;Other)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa12f010f0b85e0197d56f25dd867dcc">operator=</a> (BinaryStreamRef &amp;&amp;Other)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad588b860f21801af78f6623f679c94ae">readBytes</a> (uint64_t Offset, uint64_t Size, ArrayRef&lt; uint8_t &gt; &amp;Buffer) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an Offset into this StreamRef and a Size, return a reference to a buffer owned by the stream. <a href="#ad588b860f21801af78f6623f679c94ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a113ac5e2f45385477dca911a3830d801">readLongestContiguousChunk</a> (uint64_t Offset, ArrayRef&lt; uint8_t &gt; &amp;Buffer) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an Offset into this <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a>, return a reference to the largest buffer the stream could support without necessitating a copy. <a href="#a113ac5e2f45385477dca911a3830d801">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08f7016d7622b10f050a60dc289ca52c">BinaryStreamRefBase&lt; BinaryStreamRef, BinaryStream &gt;</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> is to <a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a> what <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> is to an Array.</p>


<p>It provides copy-semantics and read only access to a "window" of the underlying <a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a>. Note that <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> is <em>not</em> a <a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a>. That is to say, it does not inherit and override the methods of <a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a>. In general, you should not pass around pointers or references to BinaryStreams and use inheritance to achieve polymorphism. Instead, you should pass around BinaryStreamRefs by value and achieve polymorphism that way.</p>


<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<div class="doxySectionDef">

## Friends

### WritableBinaryStreamRef {#ad79b93dab411be639514e8461d620880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a49a0d2084d0b02ccf53238b2683b04b8">llvm::BinaryStreamRefBase&lt; BinaryStreamRef, BinaryStream &gt;::BinaryStreamRefBase</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a21140b1c590fc1d8b27660316e725648">llvm::BinaryStreamRefBase&lt; BinaryStreamRef, BinaryStream &gt;::Length</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a18d69c1ec33fe3424f1334fbc7eb2553">llvm::BinaryStreamRefBase&lt; BinaryStreamRef, BinaryStream &gt;::ViewOffset</a> and <a href="#ad79b93dab411be639514e8461d620880">WritableBinaryStreamRef</a>.</p>


<p>Referenced by <a href="#ad79b93dab411be639514e8461d620880">WritableBinaryStreamRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BinaryStreamRef() {#ae7b5539f398381351a5474d6c0e5ff74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinaryStreamRef::BinaryStreamRef ()</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a21140b1c590fc1d8b27660316e725648">llvm::BinaryStreamRefBase&lt; BinaryStreamRef, BinaryStream &gt;::Length</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### BinaryStreamRef() {#a82772ee4a96456ef2820de05792608a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamRef::BinaryStreamRef (<a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a> &amp; Stream)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamref-cpp">BinaryStreamRef.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a49a0d2084d0b02ccf53238b2683b04b8">llvm::BinaryStreamRefBase&lt; BinaryStreamRef, BinaryStream &gt;::BinaryStreamRefBase</a>.</p>

</div>
</div>

### BinaryStreamRef() {#ad224dee9fdde4a364476a1c9f8d2c210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamRef::BinaryStreamRef (<a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a> &amp; Stream, uint64_t Offset, std::optional&lt; uint64_t &gt; Length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamref-cpp">BinaryStreamRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a49a0d2084d0b02ccf53238b2683b04b8">llvm::BinaryStreamRefBase&lt; BinaryStreamRef, BinaryStream &gt;::BinaryStreamRefBase</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a21140b1c590fc1d8b27660316e725648">llvm::BinaryStreamRefBase&lt; BinaryStreamRef, BinaryStream &gt;::Length</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### BinaryStreamRef() {#a7f6dfb05bf82ed251de988dfed56269d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamRef::BinaryStreamRef (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> Endian)</td>
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



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>, definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamref-cpp">BinaryStreamRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a49a0d2084d0b02ccf53238b2683b04b8">llvm::BinaryStreamRefBase&lt; BinaryStreamRef, BinaryStream &gt;::BinaryStreamRefBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>

</div>
</div>

### BinaryStreamRef() {#af18f204e2ccacb08c375a214ad6f44b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamRef::BinaryStreamRef (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> Endian)</td>
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



<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamref-cpp">BinaryStreamRef.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>

</div>
</div>

### BinaryStreamRef() {#a9e39bad2dd64314ae8fe83c4f1fdb9c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinaryStreamRef::BinaryStreamRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> &amp; Other)</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### BinaryStreamRef() {#a041d6148ea0451863ac79db1d634eb1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinaryStreamRef::BinaryStreamRef (<a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> &amp;&amp; Other)</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### BinaryStreamRef() {#ab21483836d3fe3bbbe811161da053857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinaryStreamRef::BinaryStreamRef (<a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> &amp; S, uint64_t Offset, uint64_t Length)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a21140b1c590fc1d8b27660316e725648">llvm::BinaryStreamRefBase&lt; BinaryStreamRef, BinaryStream &gt;::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### BinaryStreamRef() {#a3b514cad0096803f94a9d7eb47e414c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinaryStreamRef::BinaryStreamRef (std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a> &gt; Impl, uint64_t ViewOffset, std::optional&lt; uint64_t &gt; Length)</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#afe6fa300fea20f281e9708881b0a32a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamRef &amp; llvm::BinaryStreamRef::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> &amp; Other)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator=() {#afa12f010f0b85e0197d56f25dd867dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamRef &amp; llvm::BinaryStreamRef::operator= (<a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> &amp;&amp; Other)</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### readBytes() {#ad588b860f21801af78f6623f679c94ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamRef::readBytes (uint64_t Offset, uint64_t Size, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &amp; Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an Offset into this StreamRef and a Size, return a reference to a buffer owned by the stream.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the entire range of data is within the bounds of this <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a>'s view and the implementation could read the data, and an appropriate error code otherwise.</p></dd>
</dl>


<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamref-cpp">BinaryStreamRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a57d4b980379fd31d3be943f4b66136c1">llvm::BinaryStreamRefBase&lt; BinaryStreamRef, BinaryStream &gt;::BorrowedImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a7b0ea3513329432068f5cca7d33e207a">llvm::BinaryStreamRefBase&lt; BinaryStreamRef, BinaryStream &gt;::checkOffsetForRead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a18d69c1ec33fe3424f1334fbc7eb2553">llvm::BinaryStreamRefBase&lt; BinaryStreamRef, BinaryStream &gt;::ViewOffset</a>.</p>

</div>
</div>

### readLongestContiguousChunk() {#a113ac5e2f45385477dca911a3830d801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamRef::readLongestContiguousChunk (uint64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &amp; Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an Offset into this <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a>, return a reference to the largest buffer the stream could support without necessitating a copy.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if implementation could read the data, and an appropriate error code otherwise.</p></dd>
</dl>


<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamref-cpp">BinaryStreamRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a57d4b980379fd31d3be943f4b66136c1">llvm::BinaryStreamRefBase&lt; BinaryStreamRef, BinaryStream &gt;::BorrowedImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a7b0ea3513329432068f5cca7d33e207a">llvm::BinaryStreamRefBase&lt; BinaryStreamRef, BinaryStream &gt;::checkOffsetForRead</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#af3f28458b55d3c2287703f1d631c8f23">llvm::BinaryStreamRefBase&lt; BinaryStreamRef, BinaryStream &gt;::getLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a18d69c1ec33fe3424f1334fbc7eb2553">llvm::BinaryStreamRefBase&lt; BinaryStreamRef, BinaryStream &gt;::ViewOffset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BinaryStreamRefBase&lt; BinaryStreamRef, BinaryStream &gt; {#a08f7016d7622b10f050a60dc289ca52c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::BinaryStreamRef::BinaryStreamRefBase&lt; BinaryStreamRef, BinaryStream &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
