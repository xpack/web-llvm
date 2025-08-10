---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/binarystreamwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BinaryStreamWriter` Class

<p>Provides write only access to a subclass of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/writablebinarystream">WritableBinaryStream</a></span>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BinaryStreamWriter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">llvm/Support/BinaryStreamWriter.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b48c0b6d2d024d4ee7e2c0be81da4f4">BinaryStreamWriter</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a201ead86d826cf76d5fe05c33d4612e9">BinaryStreamWriter</a> (WritableBinaryStreamRef Ref)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaadafcdc2e47871896329e789171f13c">BinaryStreamWriter</a> (WritableBinaryStream &amp;Stream)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9688b83ba27ff11e1e2b810fee451a2">BinaryStreamWriter</a> (MutableArrayRef&lt; uint8_t &gt; Data, llvm::endianness Endian)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9a1c46b68f7980efb50d5e8690aad71">BinaryStreamWriter</a> (const BinaryStreamWriter &amp;Other)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebfe229d75bfa736bf6a50350fa025d6">~BinaryStreamWriter</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter">BinaryStreamWriter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79b299b5d046562855094bc99c8cf21f">operator=</a> (const BinaryStreamWriter &amp;Other)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb614d7e749a1af26c1d719b28ba4fb7">writeBytes</a> (ArrayRef&lt; uint8_t &gt; Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the bytes specified in <span class="doxyComputerOutput">Buffer</span> to the underlying stream. <a href="#abb614d7e749a1af26c1d719b28ba4fb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a344647bc1c4a4b53334296eba145d408">writeInteger</a> (T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the integer <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> to the underlying stream in the specified endianness. <a href="#a344647bc1c4a4b53334296eba145d408">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad001fc0c44efb50fa7dab33c280dade5">writeEnum</a> (T Num)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to writeInteger. <a href="#ad001fc0c44efb50fa7dab33c280dade5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae052d37681500fb5caff81ae6f2911c1">writeULEB128</a> (uint64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the unsigned integer <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to the underlying stream using ULEB128 encoding. <a href="#ae052d37681500fb5caff81ae6f2911c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a381c9eed05264f07958dc647ed3aa301">writeSLEB128</a> (int64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the unsigned integer <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to the underlying stream using ULEB128 encoding. <a href="#a381c9eed05264f07958dc647ed3aa301">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07608f1ac2a8045b1b72108b840a8ca3">writeCString</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the string <span class="doxyComputerOutput">Str</span> to the underlying stream followed by a null terminator. <a href="#a07608f1ac2a8045b1b72108b840a8ca3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9c2dc641243ad8170ac9c0e69545f37">writeFixedString</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the string <span class="doxyComputerOutput">Str</span> to the underlying stream without a null terminator. <a href="#ac9c2dc641243ad8170ac9c0e69545f37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa08601ded5ad31dbdd5a5262a972f479">writeStreamRef</a> (BinaryStreamRef Ref)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Efficiently reads all data from <span class="doxyComputerOutput">Ref</span>, and writes it to this stream. <a href="#aa08601ded5ad31dbdd5a5262a972f479">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e81cda2da9491cb31a8896967aafdfc">writeStreamRef</a> (BinaryStreamRef Ref, uint64_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Efficiently reads <span class="doxyComputerOutput">Size</span> bytes from <span class="doxyComputerOutput">Ref</span>, and writes it to this stream. <a href="#a5e81cda2da9491cb31a8896967aafdfc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae73ad246f9f1adc35f0ce49fc089b52a">writeObject</a> (const T &amp;Obj)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Writes the object <span class="doxyComputerOutput">Obj</span> to the underlying stream, as if by using memcpy. <a href="#ae73ad246f9f1adc35f0ce49fc089b52a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1e5febb5c471f88c785519a211871b01">writeArray</a> (ArrayRef&lt; T &gt; Array)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Writes an array of objects of type T to the underlying stream, as if by using memcpy. <a href="#a1e5febb5c471f88c785519a211871b01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename U&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4201eb0cb78dcddb38a3c61f0cb1c5bd">writeArray</a> (VarStreamArray&lt; T, U &gt; Array)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Writes all data from the array <span class="doxyComputerOutput">Array</span> to the underlying stream. <a href="#a4201eb0cb78dcddb38a3c61f0cb1c5bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0ce699d9daa7adbc082f21d07ae60cc2">writeArray</a> (FixedStreamArray&lt; T &gt; Array)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Writes all elements from the array <span class="doxyComputerOutput">Array</span> to the underlying stream. <a href="#a0ce699d9daa7adbc082f21d07ae60cc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter">BinaryStreamWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter">BinaryStreamWriter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94a9f883b5505f96fc000d51c7dcf31a">split</a> (uint64_t Off) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Splits the Writer into two Writers at a given offset. <a href="#a94a9f883b5505f96fc000d51c7dcf31a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc41d0160054e1d9f2a166dbcdf95f37">setOffset</a> (uint64_t Off)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d1fbfecba0a643a1db961c9f9313b6e">getOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd4375595457f6ec3d6278f2e305f2cf">getLength</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a396d68393ffbcede5c0d7fd59c16f1c9">bytesRemaining</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc0de5f4d1abba3ccf0d201137be8c6d">padToAlignment</a> (uint32_t Align)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae33525fc426c499c8684ca2bcd44a291">Stream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e5692e307aba4f86e263a7d20695432">Offset</a> = 0</td>
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

<p>Provides write only access to a subclass of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/writablebinarystream">WritableBinaryStream</a></span>.</p>


<p>Provides bounds checking and helpers for writing certain common data types such as null-terminated strings, integers in various flavors of endianness, etc. Can be subclassed to provide reading and writing of custom datatypes, although no methods are overridable.</p>


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BinaryStreamWriter() {#a8b48c0b6d2d024d4ee7e2c0be81da4f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinaryStreamWriter::BinaryStreamWriter ()</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="#ae33525fc426c499c8684ca2bcd44a291">Stream</a>.</p>


<p>Referenced by <a href="#ae9a1c46b68f7980efb50d5e8690aad71">BinaryStreamWriter</a>, <a href="#a79b299b5d046562855094bc99c8cf21f">operator=</a> and <a href="#a94a9f883b5505f96fc000d51c7dcf31a">split</a>.</p>

</div>
</div>

### BinaryStreamWriter() {#a201ead86d826cf76d5fe05c33d4612e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamWriter::BinaryStreamWriter (<a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a> Ref)</td>
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



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamwriter-cpp">BinaryStreamWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="#ae33525fc426c499c8684ca2bcd44a291">Stream</a>.</p>

</div>
</div>

### BinaryStreamWriter() {#aaadafcdc2e47871896329e789171f13c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamWriter::BinaryStreamWriter (<a href="/web-llvm/docs/api/classes/llvm/writablebinarystream">WritableBinaryStream</a> &amp; Stream)</td>
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



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamwriter-cpp">BinaryStreamWriter.cpp</a>.</p>


<p>Reference <a href="#ae33525fc426c499c8684ca2bcd44a291">Stream</a>.</p>

</div>
</div>

### BinaryStreamWriter() {#af9688b83ba27ff11e1e2b810fee451a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamWriter::BinaryStreamWriter (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; uint8_t &gt; Data, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> Endian)</td>
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



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamwriter-cpp">BinaryStreamWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="#ae33525fc426c499c8684ca2bcd44a291">Stream</a>.</p>

</div>
</div>

### BinaryStreamWriter() {#ae9a1c46b68f7980efb50d5e8690aad71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinaryStreamWriter::BinaryStreamWriter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter">BinaryStreamWriter</a> &amp; Other)</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>.</p>


<p>References <a href="#a8b48c0b6d2d024d4ee7e2c0be81da4f4">BinaryStreamWriter</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~BinaryStreamWriter() {#aebfe229d75bfa736bf6a50350fa025d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::BinaryStreamWriter::~BinaryStreamWriter ()</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a79b299b5d046562855094bc99c8cf21f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamWriter &amp; llvm::BinaryStreamWriter::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter">BinaryStreamWriter</a> &amp; Other)</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>.</p>


<p>References <a href="#a8b48c0b6d2d024d4ee7e2c0be81da4f4">BinaryStreamWriter</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### bytesRemaining() {#a396d68393ffbcede5c0d7fd59c16f1c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BinaryStreamWriter::bytesRemaining ()</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>.</p>


<p>References <a href="#abd4375595457f6ec3d6278f2e305f2cf">getLength</a> and <a href="#a2d1fbfecba0a643a1db961c9f9313b6e">getOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistreambuilder/#a8dbe73960ff993f556bc2b82131983fb">llvm::pdb::DbiStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/infostreambuilder/#a9f34ad484130077743940295c4ea4dc7">llvm::pdb::InfoStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp/#a39370f41a63dc06ba5dc36059e555bc2">commitFpm</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptorbuilder/#a76899fd759b150059d1a8d2b2b475c78">llvm::pdb::DbiModuleDescriptorBuilder::commitSymbolStream</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream/#a7b203ff4a29296106a6614438fd462d8">llvm::msf::WritableMappedBlockStream::createFpmStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ad026ca61ae553f5da149349b2662e425">llvm::CodeViewYAML::toDebugH</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#af58593eb129f43d4702895fe00596dd9">llvm::CodeViewYAML::toDebugT</a>.</p>

</div>
</div>

### getLength() {#abd4375595457f6ec3d6278f2e305f2cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BinaryStreamWriter::getLength ()</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>.</p>


<p>Reference <a href="#ae33525fc426c499c8684ca2bcd44a291">Stream</a>.</p>


<p>Referenced by <a href="#a396d68393ffbcede5c0d7fd59c16f1c9">bytesRemaining</a> and <a href="#a94a9f883b5505f96fc000d51c7dcf31a">split</a>.</p>

</div>
</div>

### getOffset() {#a2d1fbfecba0a643a1db961c9f9313b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BinaryStreamWriter::getOffset ()</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>.</p>


<p>Reference <a href="#a2e5692e307aba4f86e263a7d20695432">Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/continuationrecordbuilder-cpp/#ae9446f182f86fd8c4dca65264de68235">addPadding</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/simpletypeserializer-cpp/#ae9446f182f86fd8c4dca65264de68235">addPadding</a>, <a href="#a396d68393ffbcede5c0d7fd59c16f1c9">bytesRemaining</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugstringtablesubsection/#ac47d08606b57a9fa3481222bbaf3219f">llvm::codeview::DebugStringTableSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionrecordbuilder/#a3b37d850ac5595f7549b90707d9b241f">llvm::codeview::DebugSubsectionRecordBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptorbuilder/#a76899fd759b150059d1a8d2b2b475c78">llvm::pdb::DbiModuleDescriptorBuilder::commitSymbolStream</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/simpletypeserializer/#ae10015a36f68325417d06aa9ab5bce62">llvm::codeview::SimpleTypeSerializer::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/compactunwindmanager/#af022b036126d33df3324995c04b55864">llvm::jitlink::CompactUnwindManager&lt; CURecTraits &gt;::writeUnwindInfo</a>.</p>

</div>
</div>

### padToAlignment() {#afc0de5f4d1abba3ccf0d201137be8c6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamWriter::padToAlignment (uint32_t Align)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamwriter-cpp">BinaryStreamWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="#a2e5692e307aba4f86e263a7d20695432">Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="#a1e5febb5c471f88c785519a211871b01">writeArray</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/debugchecksumssubsection/#a2996e2aecee50f2379910db2fd0d357e">llvm::codeview::DebugChecksumsSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionrecordbuilder/#a3b37d850ac5595f7549b90707d9b241f">llvm::codeview::DebugSubsectionRecordBuilder::commit</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptorbuilder/#a7df39993912ff56cb17c9f21d2a83455">llvm::pdb::DbiModuleDescriptorBuilder::commit</a>.</p>

</div>
</div>

### setOffset() {#acc41d0160054e1d9f2a166dbcdf95f37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BinaryStreamWriter::setOffset (uint64_t Off)</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>.</p>


<p>Reference <a href="#a2e5692e307aba4f86e263a7d20695432">Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/debugstringtablesubsection/#ac47d08606b57a9fa3481222bbaf3219f">llvm::codeview::DebugStringTableSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a6c98d361786661879be283e8abc78dbf">llvm::msf::MSFBuilder::commit</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptorbuilder/#a76899fd759b150059d1a8d2b2b475c78">llvm::pdb::DbiModuleDescriptorBuilder::commitSymbolStream</a>.</p>

</div>
</div>

### split() {#a94a9f883b5505f96fc000d51c7dcf31a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; BinaryStreamWriter, BinaryStreamWriter &gt; BinaryStreamWriter::split (uint64_t Off)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Splits the Writer into two Writers at a given offset.</p>

<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamwriter-cpp">BinaryStreamWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8b48c0b6d2d024d4ee7e2c0be81da4f4">BinaryStreamWriter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="#abd4375595457f6ec3d6278f2e305f2cf">getLength</a>, <a href="#a2e5692e307aba4f86e263a7d20695432">Offset</a> and <a href="#ae33525fc426c499c8684ca2bcd44a291">Stream</a>.</p>

</div>
</div>

### writeArray() {#a1e5febb5c471f88c785519a211871b01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::BinaryStreamWriter::writeArray (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; Array)</td>
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

<p>Writes an array of objects of type T to the underlying stream, as if by using memcpy.</p>


<p>It is up to the caller to ensure that type of <span class="doxyComputerOutput">Obj</span> can be safely copied in this fashion, as no checks are made to ensure that this is safe.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully written, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89da11f674242a86a560ba9f4b389bb0fc5a">llvm::invalid_array_size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#abb614d7e749a1af26c1d719b28ba4fb7">writeBytes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistreambuilder/#ab0e928a8582cc80c0c1a801fbafe5e3f">llvm::pdb::DbiStreamBuilder::addDbgStream</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugchecksumssubsection/#a2996e2aecee50f2379910db2fd0d357e">llvm::codeview::DebugChecksumsSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugcrossmoduleimportssubsection/#aebce5198b2ec2800c0f08a15e0dce8a6">llvm::codeview::DebugCrossModuleImportsSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugframedatasubsection/#a77473ec3667f5e75068779bc16a3d882">llvm::codeview::DebugFrameDataSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debuginlineelinessubsection/#a771a583e046704fd7ec99603a9ae724f">llvm::codeview::DebugInlineeLinesSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debuglinessubsection/#a9e5e9c47e7c77bd4e56b89a218e88a19">llvm::codeview::DebugLinesSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsymbolrvasubsection/#af7753e9c61b237727f4a23cb5a271ddb">llvm::codeview::DebugSymbolRVASubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a6c98d361786661879be283e8abc78dbf">llvm::msf::MSFBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistreambuilder/#a8dbe73960ff993f556bc2b82131983fb">llvm::pdb::DbiStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/structs/llvm/pdb/gsihashstreambuilder/#abdfe34c82754e6761b6a81728f151c2b">llvm::pdb::GSIHashStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistreambuilder/#a4dbf36873ea777c97316bb56cb47e78c">llvm::pdb::DbiStreamBuilder::finalizeMsfLayout</a> and <a href="#afc0de5f4d1abba3ccf0d201137be8c6d">padToAlignment</a>.</p>

</div>
</div>

### writeArray() {#a4201eb0cb78dcddb38a3c61f0cb1c5bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename U&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::BinaryStreamWriter::writeArray (<a href="/web-llvm/docs/api/classes/llvm/varstreamarray">VarStreamArray</a>&lt; T, U &gt; Array)</td>
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

<p>Writes all data from the array <span class="doxyComputerOutput">Array</span> to the underlying stream.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully written, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>.</p>


<p>Reference <a href="#aa08601ded5ad31dbdd5a5262a972f479">writeStreamRef</a>.</p>

</div>
</div>

### writeArray() {#a0ce699d9daa7adbc082f21d07ae60cc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::BinaryStreamWriter::writeArray (<a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray">FixedStreamArray</a>&lt; T &gt; Array)</td>
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

<p>Writes all elements from the array <span class="doxyComputerOutput">Array</span> to the underlying stream.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully written, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>.</p>


<p>Reference <a href="#aa08601ded5ad31dbdd5a5262a972f479">writeStreamRef</a>.</p>

</div>
</div>

### writeBytes() {#abb614d7e749a1af26c1d719b28ba4fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamWriter::writeBytes (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the bytes specified in <span class="doxyComputerOutput">Buffer</span> to the underlying stream.</p>


<p>On success, updates the offset so that subsequent writes will occur at the next unwritten position.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully written, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamwriter-cpp">BinaryStreamWriter.cpp</a>.</p>


<p>References <a href="#a2e5692e307aba4f86e263a7d20695432">Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="#ae33525fc426c499c8684ca2bcd44a291">Stream</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsymbolssubsection/#ad4d8120e6e6d45362656ef0be7837f7f">llvm::codeview::DebugSymbolsSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfilebuilder/#ac8da698510d6ae1fafa8234b0c0b7b92">llvm::pdb::PDBFileBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistreambuilder/#a82a7a598a05d2c0e837d924da348c414">llvm::pdb::TpiStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptorbuilder/#a76899fd759b150059d1a8d2b2b475c78">llvm::pdb::DbiModuleDescriptorBuilder::commitSymbolStream</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream/#a7b203ff4a29296106a6614438fd462d8">llvm::msf::WritableMappedBlockStream::createFpmStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#af58593eb129f43d4702895fe00596dd9">llvm::CodeViewYAML::toDebugT</a>, <a href="#a1e5febb5c471f88c785519a211871b01">writeArray</a>, <a href="#ac9c2dc641243ad8170ac9c0e69545f37">writeFixedString</a>, <a href="#a344647bc1c4a4b53334296eba145d408">writeInteger</a>, <a href="#ae73ad246f9f1adc35f0ce49fc089b52a">writeObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/gsistreambuilder-cpp/#aab81320800a686e576d9608a6bb470fe">writePublics</a>, <a href="#a381c9eed05264f07958dc647ed3aa301">writeSLEB128</a>, <a href="#a5e81cda2da9491cb31a8896967aafdfc">writeStreamRef</a> and <a href="#ae052d37681500fb5caff81ae6f2911c1">writeULEB128</a>.</p>

</div>
</div>

### writeCString() {#a07608f1ac2a8045b1b72108b840a8ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamWriter::writeCString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the string <span class="doxyComputerOutput">Str</span> to the underlying stream followed by a null terminator.</p>


<p>On success, updates the offset so that subsequent writes occur at the next unwritten position. <span class="doxyComputerOutput">Str</span> need not be null terminated on input.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully written, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamwriter-cpp">BinaryStreamWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#ac9c2dc641243ad8170ac9c0e69545f37">writeFixedString</a> and <a href="#ae73ad246f9f1adc35f0ce49fc089b52a">writeObject</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/debugstringtablesubsection/#ac47d08606b57a9fa3481222bbaf3219f">llvm::codeview::DebugStringTableSubsection::commit</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptorbuilder/#a7df39993912ff56cb17c9f21d2a83455">llvm::pdb::DbiModuleDescriptorBuilder::commit</a>.</p>

</div>
</div>

### writeEnum() {#ad001fc0c44efb50fa7dab33c280dade5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::BinaryStreamWriter::writeEnum (T Num)</td>
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

<p>Similar to writeInteger.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#a344647bc1c4a4b53334296eba145d408">writeInteger</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/debuginlineelinessubsection/#a771a583e046704fd7ec99603a9ae724f">llvm::codeview::DebugInlineeLinesSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistreambuilder/#a8dbe73960ff993f556bc2b82131983fb">llvm::pdb::DbiStreamBuilder::commit</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/infostreambuilder/#a9f34ad484130077743940295c4ea4dc7">llvm::pdb::InfoStreamBuilder::commit</a>.</p>

</div>
</div>

### writeFixedString() {#ac9c2dc641243ad8170ac9c0e69545f37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamWriter::writeFixedString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the string <span class="doxyComputerOutput">Str</span> to the underlying stream without a null terminator.</p>


<p>On success, updates the offset so that subsequent writes occur at the next unwritten position.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully written, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamwriter-cpp">BinaryStreamWriter.cpp</a>.</p>


<p>Reference <a href="#abb614d7e749a1af26c1d719b28ba4fb7">writeBytes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/namedstreammap/#a6253147b299d9a15f29775b79c273d3c">llvm::pdb::NamedStreamMap::commit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ad026ca61ae553f5da149349b2662e425">llvm::CodeViewYAML::toDebugH</a> and <a href="#a07608f1ac2a8045b1b72108b840a8ca3">writeCString</a>.</p>

</div>
</div>

### writeInteger() {#a344647bc1c4a4b53334296eba145d408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::BinaryStreamWriter::writeInteger (T Value)</td>
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

<p>Write the integer <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> to the underlying stream in the specified endianness.</p>


<p>On success, updates the offset so that subsequent writes occur at the next unwritten position.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully written, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>.</p>


<p>References <a href="#ae33525fc426c499c8684ca2bcd44a291">Stream</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a> and <a href="#abb614d7e749a1af26c1d719b28ba4fb7">writeBytes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/continuationrecordbuilder-cpp/#ae9446f182f86fd8c4dca65264de68235">addPadding</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/simpletypeserializer-cpp/#ae9446f182f86fd8c4dca65264de68235">addPadding</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugcrossmoduleexportssubsection/#a53282566910339ca555029c706ad38f8">llvm::codeview::DebugCrossModuleExportsSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugframedatasubsection/#a77473ec3667f5e75068779bc16a3d882">llvm::codeview::DebugFrameDataSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debuginlineelinessubsection/#a771a583e046704fd7ec99603a9ae724f">llvm::codeview::DebugInlineeLinesSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a6c98d361786661879be283e8abc78dbf">llvm::msf::MSFBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/hashtable/#a27e264b6aad589dd9c5013ca05d2fd55">llvm::pdb::const_iterator&lt; SrcHeaderBlockEntry &gt;::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistreambuilder/#a8dbe73960ff993f556bc2b82131983fb">llvm::pdb::DbiStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/infostreambuilder/#a9f34ad484130077743940295c4ea4dc7">llvm::pdb::InfoStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/namedstreammap/#a6253147b299d9a15f29775b79c273d3c">llvm::pdb::NamedStreamMap::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptorbuilder/#a76899fd759b150059d1a8d2b2b475c78">llvm::pdb::DbiModuleDescriptorBuilder::commitSymbolStream</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#a16f7e0099c6134ab100f80300b710e41">anonymous{PerfSupportPlugin.cpp}::createX64EHFrameHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#a92e5f360eac04874168e30f0df2bc5bb">llvm::jitlink::aarch64::lowerPointer64AuthEdgesToSigningFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ad026ca61ae553f5da149349b2662e425">llvm::CodeViewYAML::toDebugH</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp/#a7cc86b574116e1475520ba834befd71d">toDebugS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#af58593eb129f43d4702895fe00596dd9">llvm::CodeViewYAML::toDebugT</a>, <a href="#ad001fc0c44efb50fa7dab33c280dade5">writeEnum</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ae05f3870c8f629c981951b96ccbee160">llvm::pdb::writeSparseBitVector</a>.</p>

</div>
</div>

### writeObject() {#ae73ad246f9f1adc35f0ce49fc089b52a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::BinaryStreamWriter::writeObject (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; Obj)</td>
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

<p>Writes the object <span class="doxyComputerOutput">Obj</span> to the underlying stream, as if by using memcpy.</p>


<p>It is up to the caller to ensure that type of <span class="doxyComputerOutput">Obj</span> can be safely copied in this fashion, as no checks are made to ensure that this is safe.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully written, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#abb614d7e749a1af26c1d719b28ba4fb7">writeBytes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/debugchecksumssubsection/#a2996e2aecee50f2379910db2fd0d357e">llvm::codeview::DebugChecksumsSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugcrossmoduleimportssubsection/#aebce5198b2ec2800c0f08a15e0dce8a6">llvm::codeview::DebugCrossModuleImportsSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debuginlineelinessubsection/#a771a583e046704fd7ec99603a9ae724f">llvm::codeview::DebugInlineeLinesSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debuglinessubsection/#a9e5e9c47e7c77bd4e56b89a218e88a19">llvm::codeview::DebugLinesSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionrecordbuilder/#a3b37d850ac5595f7549b90707d9b241f">llvm::codeview::DebugSubsectionRecordBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a6c98d361786661879be283e8abc78dbf">llvm::msf::MSFBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/hashtable/#a27e264b6aad589dd9c5013ca05d2fd55">llvm::pdb::const_iterator&lt; SrcHeaderBlockEntry &gt;::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptorbuilder/#a7df39993912ff56cb17c9f21d2a83455">llvm::pdb::DbiModuleDescriptorBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistreambuilder/#a8dbe73960ff993f556bc2b82131983fb">llvm::pdb::DbiStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/structs/llvm/pdb/gsihashstreambuilder/#abdfe34c82754e6761b6a81728f151c2b">llvm::pdb::GSIHashStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/infostreambuilder/#a9f34ad484130077743940295c4ea4dc7">llvm::pdb::InfoStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistreambuilder/#a82a7a598a05d2c0e837d924da348c414">llvm::pdb::TpiStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp/#a39370f41a63dc06ba5dc36059e555bc2">commitFpm</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/simpletypeserializer/#ae10015a36f68325417d06aa9ab5bce62">llvm::codeview::SimpleTypeSerializer::serialize</a> and <a href="#a07608f1ac2a8045b1b72108b840a8ca3">writeCString</a>.</p>

</div>
</div>

### writeSLEB128() {#a381c9eed05264f07958dc647ed3aa301}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamWriter::writeSLEB128 (int64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the unsigned integer <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to the underlying stream using ULEB128 encoding.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully written, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamwriter-cpp">BinaryStreamWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac21006e81ffbbc79e8e51e44f7878053">llvm::encodeSLEB128</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#abb614d7e749a1af26c1d719b28ba4fb7">writeBytes</a>.</p>

</div>
</div>

### writeStreamRef() {#aa08601ded5ad31dbdd5a5262a972f479}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamWriter::writeStreamRef (<a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> Ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Efficiently reads all data from <span class="doxyComputerOutput">Ref</span>, and writes it to this stream.</p>


<p>This operation will not invoke any copies of the source data, regardless of the source stream's implementation.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully written, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamwriter-cpp">BinaryStreamWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="#aa08601ded5ad31dbdd5a5262a972f479">writeStreamRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionrecordbuilder/#a3b37d850ac5595f7549b90707d9b241f">llvm::codeview::DebugSubsectionRecordBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistreambuilder/#a8dbe73960ff993f556bc2b82131983fb">llvm::pdb::DbiStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistreambuilder/#a82a7a598a05d2c0e837d924da348c414">llvm::pdb::TpiStreamBuilder::commit</a>, <a href="#a0ce699d9daa7adbc082f21d07ae60cc2">writeArray</a>, <a href="#a4201eb0cb78dcddb38a3c61f0cb1c5bd">writeArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/gsistreambuilder-cpp/#ad280d8eb3c4e746fc3468c75755ac905">writeRecords</a> and <a href="#aa08601ded5ad31dbdd5a5262a972f479">writeStreamRef</a>.</p>

</div>
</div>

### writeStreamRef() {#a5e81cda2da9491cb31a8896967aafdfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamWriter::writeStreamRef (<a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> Ref, uint64_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Efficiently reads <span class="doxyComputerOutput">Size</span> bytes from <span class="doxyComputerOutput">Ref</span>, and writes it to this stream.</p>


<p>This operation will not invoke any copies of the source data, regardless of the source stream's implementation.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully written, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamwriter-cpp">BinaryStreamWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a81b49f753bf7db44da6cf4b0fc59b76e">llvm::BinaryStreamReader::bytesRemaining</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#aa580bf8bd5d8f755f546fa9df986260b">llvm::BinaryStreamReader::readLongestContiguousChunk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="#abb614d7e749a1af26c1d719b28ba4fb7">writeBytes</a>.</p>

</div>
</div>

### writeULEB128() {#ae052d37681500fb5caff81ae6f2911c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamWriter::writeULEB128 (uint64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the unsigned integer <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to the underlying stream using ULEB128 encoding.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully written, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamwriter-cpp">BinaryStreamWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#abb614d7e749a1af26c1d719b28ba4fb7">writeBytes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Offset {#a2e5692e307aba4f86e263a7d20695432}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BinaryStreamWriter::Offset = 0</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>.</p>


<p>Referenced by <a href="#a2d1fbfecba0a643a1db961c9f9313b6e">getOffset</a>, <a href="#afc0de5f4d1abba3ccf0d201137be8c6d">padToAlignment</a>, <a href="#acc41d0160054e1d9f2a166dbcdf95f37">setOffset</a>, <a href="#a94a9f883b5505f96fc000d51c7dcf31a">split</a> and <a href="#abb614d7e749a1af26c1d719b28ba4fb7">writeBytes</a>.</p>

</div>
</div>

### Stream {#ae33525fc426c499c8684ca2bcd44a291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WritableBinaryStreamRef llvm::BinaryStreamWriter::Stream</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a>.</p>


<p>Referenced by <a href="#a8b48c0b6d2d024d4ee7e2c0be81da4f4">BinaryStreamWriter</a>, <a href="#af9688b83ba27ff11e1e2b810fee451a2">BinaryStreamWriter</a>, <a href="#aaadafcdc2e47871896329e789171f13c">BinaryStreamWriter</a>, <a href="#a201ead86d826cf76d5fe05c33d4612e9">BinaryStreamWriter</a>, <a href="#abd4375595457f6ec3d6278f2e305f2cf">getLength</a>, <a href="#a94a9f883b5505f96fc000d51c7dcf31a">split</a>, <a href="#abb614d7e749a1af26c1d719b28ba4fb7">writeBytes</a> and <a href="#a344647bc1c4a4b53334296eba145d408">writeInteger</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">BinaryStreamWriter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamwriter-cpp">BinaryStreamWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
