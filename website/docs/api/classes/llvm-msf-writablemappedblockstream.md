---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/msf/writablemappedblockstream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WritableMappedBlockStream` Class



## Declaration

<div class="doxyDeclaration">
class llvm::msf::WritableMappedBlockStream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">llvm/DebugInfo/MSF/MappedBlockStream.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/writablebinarystream">WritableBinaryStream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a> which can be read from as well as written to. <a href="/web-llvm/docs/api/classes/llvm/writablebinarystream/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54041159b8c116fedec43c2b81807c41">WritableMappedBlockStream</a> (uint32_t BlockSize, const MSFStreamLayout &amp;StreamLayout, WritableBinaryStreamRef MsfData, BumpPtrAllocator &amp;Allocator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac916b1992a1656ad646f24a3318b52c8">getEndian</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64fe2dbc55371ed1d4af1f7cd73eda0d">readBytes</a> (uint64_t Offset, uint64_t Size, ArrayRef&lt; uint8_t &gt; &amp;Buffer) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an offset into the stream and a number of bytes, attempt to read the bytes and set the output <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> to point to data owned by the stream. <a href="#a64fe2dbc55371ed1d4af1f7cd73eda0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab49149254c2839e939f2ade05b24bdd1">readLongestContiguousChunk</a> (uint64_t Offset, ArrayRef&lt; uint8_t &gt; &amp;Buffer) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an offset into the stream, read as much as possible without copying any data. <a href="#ab49149254c2839e939f2ade05b24bdd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89adcd5492d323603faa252ed9256da8">getLength</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of bytes of data in this stream. <a href="#a89adcd5492d323603faa252ed9256da8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe3861e116c9da3ce15c4dd46a1bfaf7">writeBytes</a> (uint64_t Offset, ArrayRef&lt; uint8_t &gt; Buffer) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to write the given bytes into the stream at the desired offset. <a href="#abe3861e116c9da3ce15c4dd46a1bfaf7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bcbf02c4c5c4ba076daaf45298dfa9e">commit</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For buffered streams, commits changes to the backing store. <a href="#a4bcbf02c4c5c4ba076daaf45298dfa9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/msf/msfstreamlayout">MSFStreamLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadf12ea7b0a467ea9b8597e630ceefe3">getStreamLayout</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa810a2bc5c9c28de7758ff7eadd39cba">getBlockSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5d1de432b7adbbee660af31507fba7d">getNumBlocks</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19d7558dbb63bf3c406dd24203f646d4">getStreamLength</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream">MappedBlockStream</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af26f4dc0d4ff8bfd57afae2a4f30fc08">ReadInterface</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb08b9748420aa682e15231f9a1ff5e6">WriteInterface</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream">WritableMappedBlockStream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d0cc695b52f5a60416c542723f40b2f">createStream</a> (uint32_t BlockSize, const MSFStreamLayout &amp;Layout, WritableBinaryStreamRef MsfData, BumpPtrAllocator &amp;Allocator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream">WritableMappedBlockStream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08d954d5d32ab48f6e656250700f8fc2">createIndexedStream</a> (const MSFLayout &amp;Layout, WritableBinaryStreamRef MsfData, uint32_t StreamIndex, BumpPtrAllocator &amp;Allocator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream">WritableMappedBlockStream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a882f086ce986358c3aff75c298823739">createDirectoryStream</a> (const MSFLayout &amp;Layout, WritableBinaryStreamRef MsfData, BumpPtrAllocator &amp;Allocator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream">WritableMappedBlockStream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b203ff4a29296106a6614438fd462d8">createFpmStream</a> (const MSFLayout &amp;Layout, WritableBinaryStreamRef MsfData, BumpPtrAllocator &amp;Allocator, bool AltFpm=false)</td>
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


<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### WritableMappedBlockStream() {#a54041159b8c116fedec43c2b81807c41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WritableMappedBlockStream::WritableMappedBlockStream (uint32_t BlockSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/msf/msfstreamlayout">MSFStreamLayout</a> &amp; StreamLayout, <a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a> MsfData, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator)</td>
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



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/tarwriter-cpp/#aac035f4156e2604bfa42ba22c17b83ee">BlockSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### commit() {#a4bcbf02c4c5c4ba076daaf45298dfa9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WritableMappedBlockStream::commit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For buffered streams, commits changes to the backing store.</p>

<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>

</div>
</div>

### getBlockSize() {#aa810a2bc5c9c28de7758ff7eadd39cba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::msf::WritableMappedBlockStream::getBlockSize ()</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>


<p>Referenced by <a href="#abe3861e116c9da3ce15c4dd46a1bfaf7">writeBytes</a>.</p>

</div>
</div>

### getEndian() {#ac916b1992a1656ad646f24a3318b52c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::endianness llvm::msf::WritableMappedBlockStream::getEndian ()</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>.</p>

</div>
</div>

### getLength() {#a89adcd5492d323603faa252ed9256da8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t WritableMappedBlockStream::getLength ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of bytes of data in this stream.</p>

<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>

</div>
</div>

### getNumBlocks() {#ab5d1de432b7adbbee660af31507fba7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::msf::WritableMappedBlockStream::getNumBlocks ()</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>

</div>
</div>

### getStreamLayout() {#aadf12ea7b0a467ea9b8597e630ceefe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MSFStreamLayout &amp; llvm::msf::WritableMappedBlockStream::getStreamLayout ()</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>


<p>Referenced by <a href="#abe3861e116c9da3ce15c4dd46a1bfaf7">writeBytes</a>.</p>

</div>
</div>

### getStreamLength() {#a19d7558dbb63bf3c406dd24203f646d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::msf::WritableMappedBlockStream::getStreamLength ()</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>

</div>
</div>

### readBytes() {#a64fe2dbc55371ed1d4af1f7cd73eda0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WritableMappedBlockStream::readBytes (uint64_t Offset, uint64_t Size, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &amp; Buffer)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an offset into the stream and a number of bytes, attempt to read the bytes and set the output <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> to point to data owned by the stream.</p>

<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### readLongestContiguousChunk() {#ab49149254c2839e939f2ade05b24bdd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WritableMappedBlockStream::readLongestContiguousChunk (uint64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &amp; Buffer)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an offset into the stream, read as much as possible without copying any data.</p>

<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### writeBytes() {#abe3861e116c9da3ce15c4dd46a1bfaf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WritableMappedBlockStream::writeBytes (uint64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to write the given bytes into the stream at the desired offset.</p>


<p>This will always necessitate a copy. Cannot shrink or grow the stream, only writes into existing allocated space.</p>


<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/msf/msfstreamlayout/#a8ff01bfb0db5e159e59ecb411d020342">llvm::msf::MSFStreamLayout::Blocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a249763e47d375bbd4d125417d8d62728">llvm::msf::blockToOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/writablebinarystream/#a054c634299df770d4d683d28e2b3cb7b">llvm::WritableBinaryStream::checkOffsetForWrite</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="#aa810a2bc5c9c28de7758ff7eadd39cba">getBlockSize</a>, <a href="#aadf12ea7b0a467ea9b8597e630ceefe3">getStreamLayout</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ReadInterface {#af26f4dc0d4ff8bfd57afae2a4f30fc08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MappedBlockStream llvm::msf::WritableMappedBlockStream::ReadInterface</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>

</div>
</div>

### WriteInterface {#aeb08b9748420aa682e15231f9a1ff5e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WritableBinaryStreamRef llvm::msf::WritableMappedBlockStream::WriteInterface</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createDirectoryStream() {#a882f086ce986358c3aff75c298823739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; WritableMappedBlockStream &gt; WritableMappedBlockStream::createDirectoryStream (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout">MSFLayout</a> &amp; Layout, <a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a> MsfData, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator)</td>
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



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/msf/msfstreamlayout/#a8ff01bfb0db5e159e59ecb411d020342">llvm::msf::MSFStreamLayout::Blocks</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/superblock/#a4792a3763eaca59db556d1c9305741cd">llvm::msf::SuperBlock::BlockSize</a>, <a href="#a1d0cc695b52f5a60416c542723f40b2f">createStream</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout/#ae7cbd23b097e66cbdeccccce85704da6">llvm::msf::MSFLayout::DirectoryBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/msfstreamlayout/#a84f5daa710f9284284e3137fe3d93280">llvm::msf::MSFStreamLayout::Length</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/superblock/#a97837d9ad6f03bda18f25c7079cdb1f5">llvm::msf::SuperBlock::NumDirectoryBytes</a> and <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout/#ae81e213efb629de31c7e833c0f1c7e0d">llvm::msf::MSFLayout::SB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a6c98d361786661879be283e8abc78dbf">llvm::msf::MSFBuilder::commit</a>.</p>

</div>
</div>

### createFpmStream() {#a7b203ff4a29296106a6614438fd462d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; WritableMappedBlockStream &gt; WritableMappedBlockStream::createFpmStream (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout">MSFLayout</a> &amp; Layout, <a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a> MsfData, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, bool AltFpm=false)</td>
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



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/msf/superblock/#a4792a3763eaca59db556d1c9305741cd">llvm::msf::SuperBlock::BlockSize</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#a396d68393ffbcede5c0d7fd59c16f1c9">llvm::BinaryStreamWriter::bytesRemaining</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="#a1d0cc695b52f5a60416c542723f40b2f">createStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a71744b158ac455bfc08863560e6f99a0">llvm::msf::getFpmStreamLayout</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout/#ae81e213efb629de31c7e833c0f1c7e0d">llvm::msf::MSFLayout::SB</a> and <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#abb614d7e749a1af26c1d719b28ba4fb7">llvm::BinaryStreamWriter::writeBytes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp/#a39370f41a63dc06ba5dc36059e555bc2">commitFpm</a>.</p>

</div>
</div>

### createIndexedStream() {#a08d954d5d32ab48f6e656250700f8fc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; WritableMappedBlockStream &gt; WritableMappedBlockStream::createIndexedStream (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout">MSFLayout</a> &amp; Layout, <a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a> MsfData, uint32_t StreamIndex, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator)</td>
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



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/msfstreamlayout/#a8ff01bfb0db5e159e59ecb411d020342">llvm::msf::MSFStreamLayout::Blocks</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/superblock/#a4792a3763eaca59db556d1c9305741cd">llvm::msf::SuperBlock::BlockSize</a>, <a href="#a1d0cc695b52f5a60416c542723f40b2f">createStream</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/msfstreamlayout/#a84f5daa710f9284284e3137fe3d93280">llvm::msf::MSFStreamLayout::Length</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout/#ae81e213efb629de31c7e833c0f1c7e0d">llvm::msf::MSFLayout::SB</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout/#afe9788018b09e6d690be1f10d5059e07">llvm::msf::MSFLayout::StreamMap</a> and <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout/#a85d9674028dfa1734478fc520cd979af">llvm::msf::MSFLayout::StreamSizes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistreambuilder/#a8dbe73960ff993f556bc2b82131983fb">llvm::pdb::DbiStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/gsistreambuilder/#a76533b678e31f0285dc183e2378d39db">llvm::pdb::GSIStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/infostreambuilder/#a9f34ad484130077743940295c4ea4dc7">llvm::pdb::InfoStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfilebuilder/#ac8da698510d6ae1fafa8234b0c0b7b92">llvm::pdb::PDBFileBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistreambuilder/#a82a7a598a05d2c0e837d924da348c414">llvm::pdb::TpiStreamBuilder::commit</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptorbuilder/#a76899fd759b150059d1a8d2b2b475c78">llvm::pdb::DbiModuleDescriptorBuilder::commitSymbolStream</a>.</p>

</div>
</div>

### createStream() {#a1d0cc695b52f5a60416c542723f40b2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; WritableMappedBlockStream &gt; WritableMappedBlockStream::createStream (uint32_t BlockSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/msf/msfstreamlayout">MSFStreamLayout</a> &amp; Layout, <a href="/web-llvm/docs/api/classes/llvm/writablebinarystreamref">WritableBinaryStreamRef</a> MsfData, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator)</td>
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



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/tarwriter-cpp/#aac035f4156e2604bfa42ba22c17b83ee">BlockSize</a>.</p>


<p>Referenced by <a href="#a882f086ce986358c3aff75c298823739">createDirectoryStream</a>, <a href="#a7b203ff4a29296106a6614438fd462d8">createFpmStream</a> and <a href="#a08d954d5d32ab48f6e656250700f8fc2">createIndexedStream</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
