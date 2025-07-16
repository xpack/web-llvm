---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/binarystreamreader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BinaryStreamReader` Class Reference

<p>Provides read only access to a subclass of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a></span>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BinaryStreamReader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">llvm/Support/BinaryStreamReader.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee04105b2bd81c2242327b1b7ec03ef">BinaryStreamReader</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad574356e3c8569802971901a8d986767">BinaryStreamReader</a> (BinaryStreamRef Ref)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdbcd18b4d4b4085cbe869e5175057dc">BinaryStreamReader</a> (BinaryStream &amp;Stream)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a389e2f12249e4cc264f42f69b3ee8b8a">BinaryStreamReader</a> (ArrayRef&lt; uint8_t &gt; Data, llvm::endianness Endian)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25fd1787ed55be73cde9da848522cb44">BinaryStreamReader</a> (StringRef Data, llvm::endianness Endian)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9fd5983dd6d0cb6b925982bca69a6a1">BinaryStreamReader</a> (const BinaryStreamReader &amp;Other)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add493759410ed176450520da24924492">~BinaryStreamReader</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binarystreamreader">BinaryStreamReader</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a043558fbead80d9fefef092530af7120">operator=</a> (const BinaryStreamReader &amp;Other)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa580bf8bd5d8f755f546fa9df986260b">readLongestContiguousChunk</a> (ArrayRef&lt; uint8_t &gt; &amp;Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read as much as possible from the underlying string at the current offset without invoking a copy, and set <span class="doxyComputerOutput">Buffer</span> to the resulting data slice. <a href="#aa580bf8bd5d8f755f546fa9df986260b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d56063bcd6039c9372e485e609cf692">readBytes</a> (ArrayRef&lt; uint8_t &gt; &amp;Buffer, uint32_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read <span class="doxyComputerOutput">Size</span> bytes from the underlying stream at the current offset and and set <span class="doxyComputerOutput">Buffer</span> to the resulting data slice. <a href="#a2d56063bcd6039c9372e485e609cf692">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6bb348b0b716cb9d060ecaef7a49dcc6">readInteger</a> (T &amp;Dest)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read an integer of the specified endianness into <span class="doxyComputerOutput">Dest</span> and update the stream's offset. <a href="#a6bb348b0b716cb9d060ecaef7a49dcc6">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6a4349bd091677944d67764f80b6fbe0">readEnum</a> (T &amp;Dest)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to readInteger. <a href="#a6a4349bd091677944d67764f80b6fbe0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9f41a80bcb29a219eff47dfac886cce">readULEB128</a> (uint64_t &amp;Dest)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read an unsigned LEB128 encoded value. <a href="#ab9f41a80bcb29a219eff47dfac886cce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa386dbcb508e02e5910438040aed2cac">readSLEB128</a> (int64_t &amp;Dest)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read a signed LEB128 encoded value. <a href="#aa386dbcb508e02e5910438040aed2cac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cbc5251f13ad42510760ed61c71e874">readCString</a> (StringRef &amp;Dest)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read a null terminated string from <span class="doxyComputerOutput">Dest</span>. <a href="#a1cbc5251f13ad42510760ed61c71e874">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3228237a59c80b85e37a5180ff9a352c">readWideString</a> (ArrayRef&lt; UTF16 &gt; &amp;Dest)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to readCString, however read a null-terminated <a href="/web-llvm/docs/api/namespaces/llvm/#a17701f48ffa18ce5f16797db84617db2">UTF16</a> string instead. <a href="#a3228237a59c80b85e37a5180ff9a352c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac42f02dfb2a8bbe2f6bedea0ff7b29c">readFixedString</a> (StringRef &amp;Dest, uint32_t Length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read a <span class="doxyComputerOutput">Length</span> byte string into <span class="doxyComputerOutput">Dest</span>. <a href="#aac42f02dfb2a8bbe2f6bedea0ff7b29c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03bf40efbeb72552b33026fa1608280b">readStreamRef</a> (BinaryStreamRef &amp;Ref)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read the entire remainder of the underlying stream into <span class="doxyComputerOutput">Ref</span>. <a href="#a03bf40efbeb72552b33026fa1608280b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4364664daec8a6dd65d2161b883cf5fc">readStreamRef</a> (BinaryStreamRef &amp;Ref, uint32_t Length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read <span class="doxyComputerOutput">Length</span> bytes from the underlying stream into <span class="doxyComputerOutput">Ref</span>. <a href="#a4364664daec8a6dd65d2161b883cf5fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a520983e8f7f744a446b4b6501d6ccb03">readSubstream</a> (BinarySubstreamRef &amp;Ref, uint32_t Length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read <span class="doxyComputerOutput">Length</span> bytes from the underlying stream into <span class="doxyComputerOutput">Ref</span>. <a href="#a520983e8f7f744a446b4b6501d6ccb03">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a07e25e055f92f545f94821c4a3cbded8">readObject</a> (const T *&amp;Dest)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a pointer to an object of type T from the underlying stream, as if by memcpy, and store the result into <span class="doxyComputerOutput">Dest</span>. <a href="#a07e25e055f92f545f94821c4a3cbded8">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab88a8b3835c1028f8fd6c2b23f396d30">readArray</a> (ArrayRef&lt; T &gt; &amp;Array, uint32_t NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a reference to a <span class="doxyComputerOutput">NumElements</span> element array of objects of type T from the underlying stream as if by memcpy, and store the resulting array slice into <span class="doxyComputerOutput">array</span>. <a href="#ab88a8b3835c1028f8fd6c2b23f396d30">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adb4cfdc89c66954507c06d25ec1e267f">readArray</a> (VarStreamArray&lt; T, U &gt; &amp;Array, uint32_t Size, uint32_t Skew=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read a <a href="/web-llvm/docs/api/classes/llvm/varstreamarray">VarStreamArray</a> of size <span class="doxyComputerOutput">Size</span> bytes and store the result into <span class="doxyComputerOutput">Array</span>. <a href="#adb4cfdc89c66954507c06d25ec1e267f">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a24cb794c8858cc968924505f3a5ac37b">readArray</a> (FixedStreamArray&lt; T &gt; &amp;Array, uint32_t NumItems)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read a <a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray">FixedStreamArray</a> of <span class="doxyComputerOutput">NumItems</span> elements and store the result into <span class="doxyComputerOutput">Array</span>. <a href="#a24cb794c8858cc968924505f3a5ac37b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85689faff97c850c60750cc7c365dba2">empty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab56b001a0bd245c9e73972be0ac5d593">setOffset</a> (uint64_t Off)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa132a8414842bf6ee8325fb27fc531f1">getOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a59b9b7a08a681571bcfce21119e0a4">getLength</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81b49f753bf7db44da6cf4b0fc59b76e">bytesRemaining</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc2a22c2ff5b4d3254d0ac4c35797c97">skip</a> (uint64_t Amount)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Advance the stream's offset by <span class="doxyComputerOutput">Amount</span> bytes. <a href="#abc2a22c2ff5b4d3254d0ac4c35797c97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31521a2e6c1afa0308811515bc86c88f">peek</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examine the next byte of the underlying stream without advancing the stream's offset. <a href="#a31521a2e6c1afa0308811515bc86c88f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6d7082e2e2b6f40870974a1f974f7ec">padToAlignment</a> (uint32_t Align)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader">BinaryStreamReader</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader">BinaryStreamReader</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf48de29dad2ea81b4923dce73738350">split</a> (uint64_t Offset) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70eadf914618f89abc0a4a2393f468b5">Stream</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55df7e03f29978b5f8eec0bf67108a94">Offset</a> = 0</td>
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

<p>Provides read only access to a subclass of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a></span>.</p>


<p>Provides bounds checking and helpers for writing certain common data types such as null-terminated strings, integers in various flavors of endianness, etc. Can be subclassed to provide reading of custom datatypes, although no are overridable.</p>


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BinaryStreamReader() {#a7ee04105b2bd81c2242327b1b7ec03ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinaryStreamReader::BinaryStreamReader ()</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>


<p>Referenced by <a href="#ad9fd5983dd6d0cb6b925982bca69a6a1">BinaryStreamReader</a>, <a href="#a043558fbead80d9fefef092530af7120">operator=</a> and <a href="#aaf48de29dad2ea81b4923dce73738350">split</a>.</p>

</div>
</div>

### BinaryStreamReader() {#ad574356e3c8569802971901a8d986767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamReader::BinaryStreamReader (<a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> Ref)</td>
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



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamreader-cpp">BinaryStreamReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

### BinaryStreamReader() {#acdbcd18b4d4b4085cbe869e5175057dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamReader::BinaryStreamReader (<a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a> &amp; Stream)</td>
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



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamreader-cpp">BinaryStreamReader.cpp</a>.</p>

</div>
</div>

### BinaryStreamReader() {#a389e2f12249e4cc264f42f69b3ee8b8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamReader::BinaryStreamReader (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> Endian)</td>
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



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamreader-cpp">BinaryStreamReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>

</div>
</div>

### BinaryStreamReader() {#a25fd1787ed55be73cde9da848522cb44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamReader::BinaryStreamReader (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> Endian)</td>
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



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamreader-cpp">BinaryStreamReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>

</div>
</div>

### BinaryStreamReader() {#ad9fd5983dd6d0cb6b925982bca69a6a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinaryStreamReader::BinaryStreamReader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader">BinaryStreamReader</a> &amp; Other)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>.</p>


<p>References <a href="#a7ee04105b2bd81c2242327b1b7ec03ef">BinaryStreamReader</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~BinaryStreamReader() {#add493759410ed176450520da24924492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::BinaryStreamReader::~BinaryStreamReader ()</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a043558fbead80d9fefef092530af7120}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamReader &amp; llvm::BinaryStreamReader::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader">BinaryStreamReader</a> &amp; Other)</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>.</p>


<p>References <a href="#a7ee04105b2bd81c2242327b1b7ec03ef">BinaryStreamReader</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### bytesRemaining() {#a81b49f753bf7db44da6cf4b0fc59b76e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BinaryStreamReader::bytesRemaining ()</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>.</p>


<p>References <a href="#a4a59b9b7a08a681571bcfce21119e0a4">getLength</a> and <a href="#aa132a8414842bf6ee8325fb27fc531f1">getOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a83d01751277dc50e5ff1fd6f42bce119">llvm::codeview::consume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ae52387012c8cce7d6a25b2a464597b55">llvm::codeview::consume</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/serialize-arrayref-tail-impl/#ac6357d35b26ab1527b77136bc3d4fd45">llvm::codeview::serialize_arrayref_tail_impl&lt; T &gt;::deserialize</a>, <a href="#a85689faff97c850c60750cc7c365dba2">empty</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/lineprinter/#a37bafcfeb658e650c7c5841e0badc421">llvm::pdb::LinePrinter::formatMsfStreamData</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlstringtablesubsection/#a4f338238a79ff08b58e7caf51b4e4986">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLStringTableSubsection::fromCodeViewSubsection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ae656922d1c902f1107654bd1ae01501a">llvm::CodeViewYAML::fromDebugH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ae58982dc6f589fa99671f5f76adfc8d3">llvm::CodeViewYAML::fromDebugS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#abeca1104e840a7079510842fcb583505">llvm::CodeViewYAML::fromDebugT</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#ae335ef8883662c8098907e284abfc085">llvm::pdb::PDBFile::getStringTable</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugchecksumssubsectionref/#a5418329d4baefd380763f927734915ce">llvm::codeview::DebugChecksumsSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugcrossmoduleexportssubsectionref/#a8d48189b79fa37589f26d60c63622f88">llvm::codeview::DebugCrossModuleExportsSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugcrossmoduleimportssubsectionref/#a96c8b8995d83c6be3aae8e3d6bf567d7">llvm::codeview::DebugCrossModuleImportsSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugframedatasubsectionref/#a4be3e06f1f1b68440c1bb73617393f11">llvm::codeview::DebugFrameDataSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debuginlineelinessubsectionref/#ad817270ee6ed5e68b96642b3fddafa23">llvm::codeview::DebugInlineeLinesSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debuglinessubsectionref/#a5a4cbef7cf1ea9971675734047e5dde8">llvm::codeview::DebugLinesSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsymbolrvasubsectionref/#a55082e6517e92987e33ee8bc22075e94">llvm::codeview::DebugSymbolRVASubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/inputfile-cpp/#aae56fcb4a814efb5721c69338ad00a51">isCodeViewDebugSubsection</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/inputfile-cpp/#a0a52cc9d72477d7e3b4d1df5e0b0b23f">isDebugSSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/inputfile-cpp/#aac12eb790a6b797f6c39df86eae6e908">isDebugTSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp/#a0b78b1abf96c2d0e83ad6a5e5466ba59">loadSectionContribs</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#aa8016724ba063de217ed1ccf4ddc095d">llvm::pdb::PDBFile::parseFileHeaders</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#a0ccdac4b6ec6b7a67a2dc7e3bd83985b">llvm::pdb::PDBFile::parseStreamData</a>, <a href="#a03bf40efbeb72552b33026fa1608280b">readStreamRef</a>, <a href="#a4364664daec8a6dd65d2161b883cf5fc">readStreamRef</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistream/#a6f720d4ce41d82acda3ab73ee832ca34">llvm::pdb::DbiStream::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/injectedsourcestream/#a043e266ce01be332168911cd5805dee5">llvm::pdb::InjectedSourceStream::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/moduledebugstreamref/#a0384c62524bcae12ec581fe7872a091a">llvm::pdb::ModuleDebugStreamRef::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbstringtable/#a354a564eed91819d8ebc8466a6123741">llvm::pdb::PDBStringTable::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/publicsstream/#a621f37e5ea285041541ad8bcaa3dab0d">llvm::pdb::PublicsStream::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistream/#a9ac5083ab574d806ebe0ccb7faec0fea">llvm::pdb::TpiStream::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection/#a88666e96d35b7e7e26892eb8424728b3">llvm::codeview::LazyRandomTypeCollection::reset</a>, <a href="#abc2a22c2ff5b4d3254d0ac4c35797c97">skip</a> and <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#a5e81cda2da9491cb31a8896967aafdfc">llvm::BinaryStreamWriter::writeStreamRef</a>.</p>

</div>
</div>

### empty() {#a85689faff97c850c60750cc7c365dba2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BinaryStreamReader::empty ()</td>
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



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>.</p>


<p>Reference <a href="#a81b49f753bf7db44da6cf4b0fc59b76e">bytesRemaining</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2ad6c377fd2a8b40546a94f9b191f79f">llvm::codeview::consume</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/serialize-null-term-string-array-impl/#af8e5565c1a3f4eb4bd46133fa6ad4b58">llvm::codeview::serialize_null_term_string_array_impl::deserialize</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/serialize-vector-tail-impl/#ae99d0aac9a8dcb44986944245c335118">llvm::codeview::serialize_vector_tail_impl&lt; T &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/infostream/#a8061dd23eb1daa95b6fca9bf53dad3a5">llvm::pdb::InfoStream::reload</a> and <a href="/web-llvm/docs/api/classes/anonymous-cvtypevisitor-cpp-/cvtypevisitor/#a100392649274fd023e5e2add981ca9a8">anonymous{CVTypeVisitor.cpp}::CVTypeVisitor::visitFieldListMemberStream</a>.</p>

</div>
</div>

### getLength() {#a4a59b9b7a08a681571bcfce21119e0a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BinaryStreamReader::getLength ()</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>.</p>


<p>Referenced by <a href="#a81b49f753bf7db44da6cf4b0fc59b76e">bytesRemaining</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsymbolssubsectionref/#ae6368206ab9eec78ceae06cd41e53c07">llvm::codeview::DebugSymbolsSubsectionRef::initialize</a> and <a href="#aaf48de29dad2ea81b4923dce73738350">split</a>.</p>

</div>
</div>

### getOffset() {#aa132a8414842bf6ee8325fb27fc531f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BinaryStreamReader::getOffset ()</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>.</p>


<p>Referenced by <a href="#a81b49f753bf7db44da6cf4b0fc59b76e">bytesRemaining</a>, <a href="#a1cbc5251f13ad42510760ed61c71e874">readCString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acf48e185563b71d058905dfdad656cfd">llvm::object::readStringOrId</a>, <a href="#a520983e8f7f744a446b4b6501d6ccb03">readSubstream</a>, <a href="#a3228237a59c80b85e37a5180ff9a352c">readWideString</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/infostream/#a8061dd23eb1daa95b6fca9bf53dad3a5">llvm::pdb::InfoStream::reload</a>.</p>

</div>
</div>

### padToAlignment() {#aa6d7082e2e2b6f40870974a1f974f7ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamReader::padToAlignment (uint32_t Align)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamreader-cpp">BinaryStreamReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a> and <a href="#abc2a22c2ff5b4d3254d0ac4c35797c97">skip</a>.</p>

</div>
</div>

### peek() {#a31521a2e6c1afa0308811515bc86c88f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t BinaryStreamReader::peek ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Examine the next byte of the underlying stream without advancing the stream's offset.</p>


<p>If the stream is empty the behavior is undefined.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the next byte in the stream.</p></dd>
</dl>


<p>Declaration at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>, definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamreader-cpp">BinaryStreamReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/codeview/serialize-null-term-string-array-impl/#af8e5565c1a3f4eb4bd46133fa6ad4b58">llvm::codeview::serialize_null_term_string_array_impl::deserialize</a> and <a href="/web-llvm/docs/api/structs/llvm/codeview/serialize-vector-tail-impl/#ae99d0aac9a8dcb44986944245c335118">llvm::codeview::serialize_vector_tail_impl&lt; T &gt;::deserialize</a>.</p>

</div>
</div>

### readArray() {#ab88a8b3835c1028f8fd6c2b23f396d30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::BinaryStreamReader::readArray (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; &amp; Array, uint32_t NumElements)</td>
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

<p>Get a reference to a <span class="doxyComputerOutput">NumElements</span> element array of objects of type T from the underlying stream as if by memcpy, and store the resulting array slice into <span class="doxyComputerOutput">array</span>.</p>


<p>It is up to the caller to ensure that objects of type T can be safely treated in this manner. Updates the stream's offset to point after the newly read object. Whether a copy occurs depends upon the implementation of the underlying stream.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully read, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89da11f674242a86a560ba9f4b389bb0fc5a">llvm::invalid_array_size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af9992f46ab43b45770fddfdefef7c237">llvm::isAddrAligned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/structs/llvm/align/#a35d8c4da117386fb67db052a36ecce50">llvm::Align::Of</a>, <a href="#a2d56063bcd6039c9372e485e609cf692">readBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/codeview/serialize-array-impl/#a859df25293b52d50c6710268771b5096">llvm::codeview::serialize_array_impl&lt; T, U &gt;::deserialize</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/serialize-arrayref-tail-impl/#ac6357d35b26ab1527b77136bc3d4fd45">llvm::codeview::serialize_arrayref_tail_impl&lt; T &gt;::deserialize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ae58982dc6f589fa99671f5f76adfc8d3">llvm::CodeViewYAML::fromDebugS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#abeca1104e840a7079510842fcb583505">llvm::CodeViewYAML::fromDebugT</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugchecksumssubsectionref/#a5418329d4baefd380763f927734915ce">llvm::codeview::DebugChecksumsSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugcrossmoduleexportssubsectionref/#a8d48189b79fa37589f26d60c63622f88">llvm::codeview::DebugCrossModuleExportsSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugcrossmoduleimportssubsectionref/#a96c8b8995d83c6be3aae8e3d6bf567d7">llvm::codeview::DebugCrossModuleImportsSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugframedatasubsectionref/#a4be3e06f1f1b68440c1bb73617393f11">llvm::codeview::DebugFrameDataSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debuginlineelinessubsectionref/#ad817270ee6ed5e68b96642b3fddafa23">llvm::codeview::DebugInlineeLinesSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debuglinessubsectionref/#a5a4cbef7cf1ea9971675734047e5dde8">llvm::codeview::DebugLinesSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsymbolrvasubsectionref/#a55082e6517e92987e33ee8bc22075e94">llvm::codeview::DebugSymbolRVASubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsymbolssubsectionref/#ae6368206ab9eec78ceae06cd41e53c07">llvm::codeview::DebugSymbolsSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/inputfile-cpp/#a0a52cc9d72477d7e3b4d1df5e0b0b23f">isDebugSSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/inputfile-cpp/#aac12eb790a6b797f6c39df86eae6e908">isDebugTSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp/#a0b78b1abf96c2d0e83ad6a5e5466ba59">loadSectionContribs</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/linecolumnextractor/#ac30e456e648c6aa3b5de74279adbb0d5">llvm::codeview::LineColumnExtractor::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#aa8016724ba063de217ed1ccf4ddc095d">llvm::pdb::PDBFile::parseFileHeaders</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#a0ccdac4b6ec6b7a67a2dc7e3bd83985b">llvm::pdb::PDBFile::parseStreamData</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/globalsstream-cpp/#a47db0d3530f3a43617019d711cbae24f">readGSIHashBuckets</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/globalsstream-cpp/#a5ae02ec2318ccbef9898227128b7320f">readGSIHashRecords</a>, <a href="#a3228237a59c80b85e37a5180ff9a352c">readWideString</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistream/#a6f720d4ce41d82acda3ab73ee832ca34">llvm::pdb::DbiStream::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/publicsstream/#a621f37e5ea285041541ad8bcaa3dab0d">llvm::pdb::PublicsStream::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/symbolstream/#a881bfdf4698e1253b2bbdf5ee9754708">llvm::pdb::SymbolStream::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistream/#a9ac5083ab574d806ebe0ccb7faec0fea">llvm::pdb::TpiStream::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection/#a88666e96d35b7e7e26892eb8424728b3">llvm::codeview::LazyRandomTypeCollection::reset</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a350ae3fe286b68175d7eee301904506c">resolveTypeIndexReferences</a>.</p>

</div>
</div>

### readArray() {#adb4cfdc89c66954507c06d25ec1e267f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename U&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::BinaryStreamReader::readArray (<a href="/web-llvm/docs/api/classes/llvm/varstreamarray">VarStreamArray</a>&lt; T, U &gt; &amp; Array, uint32_t Size, uint32_t Skew=0)</td>
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

<p>Read a <a href="/web-llvm/docs/api/classes/llvm/varstreamarray">VarStreamArray</a> of size <span class="doxyComputerOutput">Size</span> bytes and store the result into <span class="doxyComputerOutput">Array</span>.</p>


<p>Updates the stream's offset to point after the newly read array. Never causes a copy (although iterating the elements of the <a href="/web-llvm/docs/api/classes/llvm/varstreamarray">VarStreamArray</a> may, depending upon the implementation of the underlying stream).</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully read, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>.</p>


<p>References <a href="#a03bf40efbeb72552b33026fa1608280b">readStreamRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### readArray() {#a24cb794c8858cc968924505f3a5ac37b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::BinaryStreamReader::readArray (<a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray">FixedStreamArray</a>&lt; T &gt; &amp; Array, uint32_t NumItems)</td>
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

<p>Read a <a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray">FixedStreamArray</a> of <span class="doxyComputerOutput">NumItems</span> elements and store the result into <span class="doxyComputerOutput">Array</span>.</p>


<p>Updates the stream's offset to point after the newly read array. Never causes a copy (although iterating the elements of the <a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray">FixedStreamArray</a> may, depending upon the implementation of the underlying stream).</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully read, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89da11f674242a86a560ba9f4b389bb0fc5a">llvm::invalid_array_size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#a03bf40efbeb72552b33026fa1608280b">readStreamRef</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### readBytes() {#a2d56063bcd6039c9372e485e609cf692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamReader::readBytes (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &amp; Buffer, uint32_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read <span class="doxyComputerOutput">Size</span> bytes from the underlying stream at the current offset and and set <span class="doxyComputerOutput">Buffer</span> to the resulting data slice.</p>


<p>Whether a copy occurs depends on the implementation of the underlying stream. Updates the stream's offset to point after the newly read data.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully read, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamreader-cpp">BinaryStreamReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/lineprinter/#a37bafcfeb658e650c7c5841e0badc421">llvm::pdb::LinePrinter::formatMsfStreamData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ae656922d1c902f1107654bd1ae01501a">llvm::CodeViewYAML::fromDebugH</a>, <a href="/web-llvm/docs/api/structs/llvm/varstreamarrayextractor/#a4e7a87abc173694df4fd4f9255636528">llvm::VarStreamArrayExtractor&lt; T &gt;::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#aa8016724ba063de217ed1ccf4ddc095d">llvm::pdb::PDBFile::parseFileHeaders</a>, <a href="#ab88a8b3835c1028f8fd6c2b23f396d30">readArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#afd9de9e2724a77a812e6f3d243de9a59">llvm::codeview::readCVRecordFromStream</a>, <a href="#aac42f02dfb2a8bbe2f6bedea0ff7b29c">readFixedString</a>, <a href="#a6bb348b0b716cb9d060ecaef7a49dcc6">readInteger</a>, <a href="#a07e25e055f92f545f94821c4a3cbded8">readObject</a>, <a href="#aa386dbcb508e02e5910438040aed2cac">readSLEB128</a> and <a href="#ab9f41a80bcb29a219eff47dfac886cce">readULEB128</a>.</p>

</div>
</div>

### readCString() {#a1cbc5251f13ad42510760ed61c71e874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamReader::readCString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read a null terminated string from <span class="doxyComputerOutput">Dest</span>.</p>


<p>Whether a copy occurs depends on the implementation of the underlying stream. Updates the stream's offset to point after the newly read data.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully read, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamreader-cpp">BinaryStreamReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a93b15a8c0022febbe39d17ab933737a8">llvm::StringRef::find_first_of</a>, <a href="#aa132a8414842bf6ee8325fb27fc531f1">getOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ae5b35beb6f127e5f47269e9124b886fb">LLVM_LIKELY</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="#aac42f02dfb2a8bbe2f6bedea0ff7b29c">readFixedString</a>, <a href="#aa580bf8bd5d8f755f546fa9df986260b">readLongestContiguousChunk</a>, <a href="#ab56b001a0bd245c9e73972be0ac5d593">setOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2ad6c377fd2a8b40546a94f9b191f79f">llvm::codeview::consume</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/serialize-null-term-string-array-impl/#af8e5565c1a3f4eb4bd46133fa6ad4b58">llvm::codeview::serialize_null_term_string_array_impl::deserialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlstringtablesubsection/#a4f338238a79ff08b58e7caf51b4e4986">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLStringTableSubsection::fromCodeViewSubsection</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugstringtablesubsectionref/#a89f91fb97bacfa2e66d5f5b912a85304">llvm::codeview::DebugStringTableSubsectionRef::getString</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptor/#a8989add5b1e916623998fe78f3e003cb">llvm::pdb::DbiModuleDescriptor::initialize</a>.</p>

</div>
</div>

### readEnum() {#a6a4349bd091677944d67764f80b6fbe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::BinaryStreamReader::readEnum (T &amp; Dest)</td>
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

<p>Similar to readInteger.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a6bb348b0b716cb9d060ecaef7a49dcc6">readInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/debuginlineelinessubsectionref/#ad817270ee6ed5e68b96642b3fddafa23">llvm::codeview::DebugInlineeLinesSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/infostream/#a8061dd23eb1daa95b6fca9bf53dad3a5">llvm::pdb::InfoStream::reload</a> and <a href="/web-llvm/docs/api/classes/anonymous-cvtypevisitor-cpp-/cvtypevisitor/#a100392649274fd023e5e2add981ca9a8">anonymous{CVTypeVisitor.cpp}::CVTypeVisitor::visitFieldListMemberStream</a>.</p>

</div>
</div>

### readFixedString() {#aac42f02dfb2a8bbe2f6bedea0ff7b29c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamReader::readFixedString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Dest, uint32_t Length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read a <span class="doxyComputerOutput">Length</span> byte string into <span class="doxyComputerOutput">Dest</span>.</p>


<p>Whether a copy occurs depends on the implementation of the underlying stream. Updates the stream's offset to point after the newly read data.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully read, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamreader-cpp">BinaryStreamReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="#a2d56063bcd6039c9372e485e609cf692">readBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/namedstreammap/#a1f4507809faf33bf017aeb193cf9d617">llvm::pdb::NamedStreamMap::load</a> and <a href="#a1cbc5251f13ad42510760ed61c71e874">readCString</a>.</p>

</div>
</div>

### readInteger() {#a6bb348b0b716cb9d060ecaef7a49dcc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::BinaryStreamReader::readInteger (T &amp; Dest)</td>
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

<p>Read an integer of the specified endianness into <span class="doxyComputerOutput">Dest</span> and update the stream's offset.</p>


<p>The data is always copied from the stream's underlying buffer into <span class="doxyComputerOutput">Dest</span>. Updates the stream's offset to point after the newly read data.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully read, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#acfdf941f45bc58470ed8423b98862486">llvm::support::endian::read</a>, <a href="#a2d56063bcd6039c9372e485e609cf692">readBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a810901bf1e6c5f3228de79e7a61ef36b">llvm::codeview::consume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#af7c66a024988186225020af44c3cccef">llvm::codeview::consume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a02f8b46889521bdf31c026e27d51cd95">llvm::codeview::consume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ae656922d1c902f1107654bd1ae01501a">llvm::CodeViewYAML::fromDebugH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ae58982dc6f589fa99671f5f76adfc8d3">llvm::CodeViewYAML::fromDebugS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#abeca1104e840a7079510842fcb583505">llvm::CodeViewYAML::fromDebugT</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/inputfile-cpp/#aae56fcb4a814efb5721c69338ad00a51">isCodeViewDebugSubsection</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/hashtable/#a0d7b4512480e721249639c7fa64636ce">llvm::pdb::const_iterator&lt; SrcHeaderBlockEntry &gt;::load</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/namedstreammap/#a1f4507809faf33bf017aeb193cf9d617">llvm::pdb::NamedStreamMap::load</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#a0ccdac4b6ec6b7a67a2dc7e3bd83985b">llvm::pdb::PDBFile::parseStreamData</a>, <a href="#a6a4349bd091677944d67764f80b6fbe0">readEnum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#abb261b1e80159e16ee57e79ed2d77494">llvm::pdb::readSparseBitVector</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#acf48e185563b71d058905dfdad656cfd">llvm::object::readStringOrId</a>.</p>

</div>
</div>

### readLongestContiguousChunk() {#aa580bf8bd5d8f755f546fa9df986260b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamReader::readLongestContiguousChunk (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &amp; Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read as much as possible from the underlying string at the current offset without invoking a copy, and set <span class="doxyComputerOutput">Buffer</span> to the resulting data slice.</p>


<p>Updates the stream's offset to point after the newly read data.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully read, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamreader-cpp">BinaryStreamReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a1cbc5251f13ad42510760ed61c71e874">readCString</a> and <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#a5e81cda2da9491cb31a8896967aafdfc">llvm::BinaryStreamWriter::writeStreamRef</a>.</p>

</div>
</div>

### readObject() {#a07e25e055f92f545f94821c4a3cbded8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::BinaryStreamReader::readObject (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T *&amp; Dest)</td>
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

<p>Get a pointer to an object of type T from the underlying stream, as if by memcpy, and store the result into <span class="doxyComputerOutput">Dest</span>.</p>


<p>It is up to the caller to ensure that objects of type T can be safely treated in this manner. Updates the stream's offset to point after the newly read object. Whether a copy occurs depends upon the implementation of the underlying stream.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully read, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="#a2d56063bcd6039c9372e485e609cf692">readBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a906f518050c1f38a2479950b5fc9c68f">llvm::codeview::consume</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugframedatasubsectionref/#a4be3e06f1f1b68440c1bb73617393f11">llvm::codeview::DebugFrameDataSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debuglinessubsectionref/#a5a4cbef7cf1ea9971675734047e5dde8">llvm::codeview::DebugLinesSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionrecord/#a2d6b180a6430d3f25c49ab5777d63d59">llvm::codeview::DebugSubsectionRecord::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptor/#a8989add5b1e916623998fe78f3e003cb">llvm::pdb::DbiModuleDescriptor::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/hashtable/#a0d7b4512480e721249639c7fa64636ce">llvm::pdb::const_iterator&lt; SrcHeaderBlockEntry &gt;::load</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/linecolumnextractor/#ac30e456e648c6aa3b5de74279adbb0d5">llvm::codeview::LineColumnExtractor::operator()</a>, <a href="/web-llvm/docs/api/structs/llvm/varstreamarrayextractor/#a4e7a87abc173694df4fd4f9255636528">llvm::VarStreamArrayExtractor&lt; T &gt;::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#aa8016724ba063de217ed1ccf4ddc095d">llvm::pdb::PDBFile::parseFileHeaders</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#afd9de9e2724a77a812e6f3d243de9a59">llvm::codeview::readCVRecordFromStream</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/globalsstream-cpp/#a44dd8d2be786070c9fde64a4892d8044">readGSIHashHeader</a>, <a href="#a3228237a59c80b85e37a5180ff9a352c">readWideString</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistream/#a6f720d4ce41d82acda3ab73ee832ca34">llvm::pdb::DbiStream::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/infostream/#a8061dd23eb1daa95b6fca9bf53dad3a5">llvm::pdb::InfoStream::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/injectedsourcestream/#a043e266ce01be332168911cd5805dee5">llvm::pdb::InjectedSourceStream::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/publicsstream/#a621f37e5ea285041541ad8bcaa3dab0d">llvm::pdb::PublicsStream::reload</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistream/#a9ac5083ab574d806ebe0ccb7faec0fea">llvm::pdb::TpiStream::reload</a>.</p>

</div>
</div>

### readSLEB128() {#aa386dbcb508e02e5910438040aed2cac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamReader::readSLEB128 (int64_t &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read a signed LEB128 encoded value.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully read, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamreader-cpp">BinaryStreamReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a405b6cecd013148b4b443dd37854b4c4">llvm::decodeSLEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a2d56063bcd6039c9372e485e609cf692">readBytes</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### readStreamRef() {#a03bf40efbeb72552b33026fa1608280b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamReader::readStreamRef (<a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> &amp; Ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read the entire remainder of the underlying stream into <span class="doxyComputerOutput">Ref</span>.</p>


<p>This is equivalent to calling getUnderlyingStream().slice(Offset). Updates the stream's offset to point to the end of the stream. Never causes a copy.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully read, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamreader-cpp">BinaryStreamReader.cpp</a>.</p>


<p>References <a href="#a81b49f753bf7db44da6cf4b0fc59b76e">bytesRemaining</a>, <a href="#a03bf40efbeb72552b33026fa1608280b">readStreamRef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/debugstringtablesubsectionref/#a5029e1e658cdad46cadff17a42cc3545">llvm::codeview::DebugStringTableSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionrecord/#a2d6b180a6430d3f25c49ab5777d63d59">llvm::codeview::DebugSubsectionRecord::initialize</a>, <a href="#a24cb794c8858cc968924505f3a5ac37b">readArray</a>, <a href="#adb4cfdc89c66954507c06d25ec1e267f">readArray</a>, <a href="#a03bf40efbeb72552b33026fa1608280b">readStreamRef</a> and <a href="#a520983e8f7f744a446b4b6501d6ccb03">readSubstream</a>.</p>

</div>
</div>

### readStreamRef() {#a4364664daec8a6dd65d2161b883cf5fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamReader::readStreamRef (<a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> &amp; Ref, uint32_t Length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read <span class="doxyComputerOutput">Length</span> bytes from the underlying stream into <span class="doxyComputerOutput">Ref</span>.</p>


<p>This is equivalent to calling getUnderlyingStream().slice(Offset, Length). Updates the stream's offset to point after the newly read object. Never causes a copy.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully read, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>, definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamreader-cpp">BinaryStreamReader.cpp</a>.</p>


<p>References <a href="#a81b49f753bf7db44da6cf4b0fc59b76e">bytesRemaining</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89dad88b43968f2dd7eb3d9d40060fbacc98">llvm::stream_too_short</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### readSubstream() {#a520983e8f7f744a446b4b6501d6ccb03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamReader::readSubstream (<a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a> &amp; Ref, uint32_t Length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read <span class="doxyComputerOutput">Length</span> bytes from the underlying stream into <span class="doxyComputerOutput">Ref</span>.</p>


<p>This is equivalent to calling getUnderlyingStream().slice(Offset, Length). Updates the stream's offset to point after the newly read object. Never causes a copy.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully read, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamreader-cpp">BinaryStreamReader.cpp</a>.</p>


<p>References <a href="#aa132a8414842bf6ee8325fb27fc531f1">getOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="#a03bf40efbeb72552b33026fa1608280b">readStreamRef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistream/#a6f720d4ce41d82acda3ab73ee832ca34">llvm::pdb::DbiStream::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/infostream/#a8061dd23eb1daa95b6fca9bf53dad3a5">llvm::pdb::InfoStream::reload</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistream/#a9ac5083ab574d806ebe0ccb7faec0fea">llvm::pdb::TpiStream::reload</a>.</p>

</div>
</div>

### readULEB128() {#ab9f41a80bcb29a219eff47dfac886cce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamReader::readULEB128 (uint64_t &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read an unsigned LEB128 encoded value.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully read, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamreader-cpp">BinaryStreamReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3720bbfe79232f7792ab4b969dfbeed0">llvm::decodeULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a2d56063bcd6039c9372e485e609cf692">readBytes</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### readWideString() {#a3228237a59c80b85e37a5180ff9a352c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamReader::readWideString (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a17701f48ffa18ce5f16797db84617db2">UTF16</a> &gt; &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similar to readCString, however read a null-terminated <a href="/web-llvm/docs/api/namespaces/llvm/#a17701f48ffa18ce5f16797db84617db2">UTF16</a> string instead.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if the data was successfully read, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamreader-cpp">BinaryStreamReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#aa132a8414842bf6ee8325fb27fc531f1">getOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="#ab88a8b3835c1028f8fd6c2b23f396d30">readArray</a>, <a href="#a07e25e055f92f545f94821c4a3cbded8">readObject</a>, <a href="#ab56b001a0bd245c9e73972be0ac5d593">setOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/object/#acf48e185563b71d058905dfdad656cfd">llvm::object::readStringOrId</a>.</p>

</div>
</div>

### setOffset() {#ab56b001a0bd245c9e73972be0ac5d593}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BinaryStreamReader::setOffset (uint64_t Off)</td>
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



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/debugstringtablesubsectionref/#a89f91fb97bacfa2e66d5f5b912a85304">llvm::codeview::DebugStringTableSubsectionRef::getString</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#aa8016724ba063de217ed1ccf4ddc095d">llvm::pdb::PDBFile::parseFileHeaders</a>, <a href="#a1cbc5251f13ad42510760ed61c71e874">readCString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#afd9de9e2724a77a812e6f3d243de9a59">llvm::codeview::readCVRecordFromStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acf48e185563b71d058905dfdad656cfd">llvm::object::readStringOrId</a>, <a href="#a3228237a59c80b85e37a5180ff9a352c">readWideString</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/infostream/#a8061dd23eb1daa95b6fca9bf53dad3a5">llvm::pdb::InfoStream::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistream/#a9ac5083ab574d806ebe0ccb7faec0fea">llvm::pdb::TpiStream::reload</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a350ae3fe286b68175d7eee301904506c">resolveTypeIndexReferences</a>.</p>

</div>
</div>

### skip() {#abc2a22c2ff5b4d3254d0ac4c35797c97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryStreamReader::skip (uint64_t Amount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Advance the stream's offset by <span class="doxyComputerOutput">Amount</span> bytes.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a success error code if at least <span class="doxyComputerOutput">Amount</span> bytes remain in the stream, otherwise returns an appropriate error code.</p></dd>
</dl>


<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>, definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamreader-cpp">BinaryStreamReader.cpp</a>.</p>


<p>References <a href="#a81b49f753bf7db44da6cf4b0fc59b76e">bytesRemaining</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89dad88b43968f2dd7eb3d9d40060fbacc98">llvm::stream_too_short</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/codeview/serialize-null-term-string-array-impl/#af8e5565c1a3f4eb4bd46133fa6ad4b58">llvm::codeview::serialize_null_term_string_array_impl::deserialize</a> and <a href="#aa6d7082e2e2b6f40870974a1f974f7ec">padToAlignment</a>.</p>

</div>
</div>

### split() {#aaf48de29dad2ea81b4923dce73738350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; BinaryStreamReader, BinaryStreamReader &gt; BinaryStreamReader::split (uint64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>, definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamreader-cpp">BinaryStreamReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7ee04105b2bd81c2242327b1b7ec03ef">BinaryStreamReader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a> and <a href="#a4a59b9b7a08a681571bcfce21119e0a4">getLength</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbstringtable/#a354a564eed91819d8ebc8466a6123741">llvm::pdb::PDBStringTable::reload</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Offset {#a55df7e03f29978b5f8eec0bf67108a94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BinaryStreamReader::Offset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>.</p>

</div>
</div>

### Stream {#a70eadf914618f89abc0a4a2393f468b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamRef llvm::BinaryStreamReader::Stream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">BinaryStreamReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/binarystreamreader-cpp">BinaryStreamReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
