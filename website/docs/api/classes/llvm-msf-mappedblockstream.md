---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/msf/mappedblockstream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MappedBlockStream` Class

<p><a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream">MappedBlockStream</a> represents data stored in an MSF file into chunks of a particular size (called the Block Size), and whose chunks may not be necessarily contiguous. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::msf::MappedBlockStream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">llvm/DebugInfo/MSF/MappedBlockStream.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An interface for accessing data in a stream-like format, but which discourages copying. <a href="/web-llvm/docs/api/classes/llvm/binarystream/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9b3eb84fc7e73a5190e8540bc70ca76">CacheEntry</a> = <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; uint8_t &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45ebfdb4e5d404fa458bb8d6cc8516be">WritableMappedBlockStream</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa809cfcf212be1d0fccd98f2f14e4dd2">MappedBlockStream</a> (uint32_t BlockSize, const MSFStreamLayout &amp;StreamLayout, BinaryStreamRef MsfData, BumpPtrAllocator &amp;Allocator)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7017ab3898f5632054f3319a41a1fc15">getEndian</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a421432438b984e24590ea8169dc589">readBytes</a> (uint64_t Offset, uint64_t Size, ArrayRef&lt; uint8_t &gt; &amp;Buffer) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an offset into the stream and a number of bytes, attempt to read the bytes and set the output <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> to point to data owned by the stream. <a href="#a1a421432438b984e24590ea8169dc589">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a232c212f81250213c8bf658375e5aa3d">readLongestContiguousChunk</a> (uint64_t Offset, ArrayRef&lt; uint8_t &gt; &amp;Buffer) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an offset into the stream, read as much as possible without copying any data. <a href="#a232c212f81250213c8bf658375e5aa3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6053141c93022251dc3e8d2728591e0">getLength</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of bytes of data in this stream. <a href="#ad6053141c93022251dc3e8d2728591e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d171b28101ca3d995bfdf7221961447">getAllocator</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68772231524fb689e30d2ad36290d16d">invalidateCache</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7b82d4df6704c55438d1c3af1bd6f59">getBlockSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e4c30b3f72ba049cb470f5a84386f39">getNumBlocks</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77e0e1cdd88cf3a41742d0bcbb029219">getStreamLength</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/msf/msfstreamlayout">MSFStreamLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bcfc540f0c1b74f22753ad35b1fd05e">getStreamLayout</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78d38d1e2ac8a285e98cc60e71aa1777">fixCacheAfterWrite</a> (uint64_t Offset, ArrayRef&lt; uint8_t &gt; Data) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a016e2e07804576b57e88664934ce5796">readBytes</a> (uint64_t Offset, MutableArrayRef&lt; uint8_t &gt; Buffer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dc39e71cfa9d9fd041585d07cad6e74">tryReadContiguously</a> (uint64_t Offset, uint64_t Size, ArrayRef&lt; uint8_t &gt; &amp;Buffer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5461fc654a6f21cb8f536191811908f">BlockSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/msf/msfstreamlayout">MSFStreamLayout</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af34285086a39db25cb5e66488839e283">StreamLayout</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7c3c090eefb9b013181f8c21ff47056">MsfData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03cb4e1292635873fe678335a58b32d4">Allocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint32_t, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">CacheEntry</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a705e74b7fa72965edc1efa4d04cf226e">CacheMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream">MappedBlockStream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42594a94d5394378bab96f2d642f8e63">createStream</a> (uint32_t BlockSize, const MSFStreamLayout &amp;Layout, BinaryStreamRef MsfData, BumpPtrAllocator &amp;Allocator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream">MappedBlockStream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17d9ec7154acf6bc5c1a090db9ef2936">createIndexedStream</a> (const MSFLayout &amp;Layout, BinaryStreamRef MsfData, uint32_t StreamIndex, BumpPtrAllocator &amp;Allocator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream">MappedBlockStream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca02a882851c4f44d12552f22d5fb9d7">createFpmStream</a> (const MSFLayout &amp;Layout, BinaryStreamRef MsfData, BumpPtrAllocator &amp;Allocator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream">MappedBlockStream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb227e93ab0981688803772c461a0aa2">createDirectoryStream</a> (const MSFLayout &amp;Layout, BinaryStreamRef MsfData, BumpPtrAllocator &amp;Allocator)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream">MappedBlockStream</a> represents data stored in an MSF file into chunks of a particular size (called the Block Size), and whose chunks may not be necessarily contiguous.</p>


<p>The arrangement of these chunks MSF the file is described by some other metadata contained within the MSF file. In the case of a standard MSF Stream, the layout of the stream's blocks is described by the MSF "directory", but in the case of the directory itself, the layout is described by an array at a fixed location within the MSF. <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream">MappedBlockStream</a> provides methods for reading from and writing to one of these streams transparently, as if it were a contiguous sequence of bytes.</p>


<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### CacheEntry {#ab9b3eb84fc7e73a5190e8540bc70ca76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::msf::MappedBlockStream::CacheEntry =  MutableArrayRef&lt;uint8_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### WritableMappedBlockStream {#a45ebfdb4e5d404fa458bb8d6cc8516be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream">WritableMappedBlockStream</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>


<p>Reference <a href="#a45ebfdb4e5d404fa458bb8d6cc8516be">WritableMappedBlockStream</a>.</p>


<p>Referenced by <a href="#a45ebfdb4e5d404fa458bb8d6cc8516be">WritableMappedBlockStream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### MappedBlockStream() {#aa809cfcf212be1d0fccd98f2f14e4dd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MappedBlockStream::MappedBlockStream (uint32_t BlockSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/msf/msfstreamlayout">MSFStreamLayout</a> &amp; StreamLayout, <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> MsfData, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator)</td>
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



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAllocator() {#a2d171b28101ca3d995bfdf7221961447}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator &amp; llvm::msf::MappedBlockStream::getAllocator ()</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>

</div>
</div>

### getBlockSize() {#ac7b82d4df6704c55438d1c3af1bd6f59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::msf::MappedBlockStream::getBlockSize ()</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>

</div>
</div>

### getEndian() {#a7017ab3898f5632054f3319a41a1fc15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::endianness llvm::msf::MappedBlockStream::getEndian ()</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>.</p>

</div>
</div>

### getLength() {#ad6053141c93022251dc3e8d2728591e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MappedBlockStream::getLength ()</td>
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

<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>

</div>
</div>

### getNumBlocks() {#a7e4c30b3f72ba049cb470f5a84386f39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::msf::MappedBlockStream::getNumBlocks ()</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>


<p>Referenced by <a href="#a232c212f81250213c8bf658375e5aa3d">readLongestContiguousChunk</a>.</p>

</div>
</div>

### getStreamLength() {#a77e0e1cdd88cf3a41742d0bcbb029219}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::msf::MappedBlockStream::getStreamLength ()</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>

</div>
</div>

### invalidateCache() {#a68772231524fb689e30d2ad36290d16d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MappedBlockStream::invalidateCache ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>

</div>
</div>

### readBytes() {#a1a421432438b984e24590ea8169dc589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MappedBlockStream::readBytes (uint64_t Offset, uint64_t Size, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &amp; Buffer)</td>
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

<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab356ea3c8e676945f863322b38df3e14">llvm::AbsoluteDifference</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystream/#af20acc8b7134ce7ffa54c05a7f295fb6">llvm::BinaryStream::checkOffsetForRead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae085940412a44fb6c730f254a17c9820">llvm::intersect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a1a421432438b984e24590ea8169dc589">readBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a1a421432438b984e24590ea8169dc589">readBytes</a>.</p>

</div>
</div>

### readLongestContiguousChunk() {#a232c212f81250213c8bf658375e5aa3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MappedBlockStream::readLongestContiguousChunk (uint64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &amp; Buffer)</td>
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

<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a249763e47d375bbd4d125417d8d62728">llvm::msf::blockToOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystream/#af20acc8b7134ce7ffa54c05a7f295fb6">llvm::BinaryStream::checkOffsetForRead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="#a7e4c30b3f72ba049cb470f5a84386f39">getNumBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### fixCacheAfterWrite() {#a78d38d1e2ac8a285e98cc60e71aa1777}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MappedBlockStream::fixCacheAfterWrite (uint64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>

</div>
</div>

### getStreamLayout() {#a9bcfc540f0c1b74f22753ad35b1fd05e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MSFStreamLayout &amp; llvm::msf::MappedBlockStream::getStreamLayout ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>

</div>
</div>

### readBytes() {#a016e2e07804576b57e88664934ce5796}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MappedBlockStream::readBytes (uint64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; uint8_t &gt; Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>

</div>
</div>

### tryReadContiguously() {#a7dc39e71cfa9d9fd041585d07cad6e74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MappedBlockStream::tryReadContiguously (uint64_t Offset, uint64_t Size, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &amp; Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allocator {#a03cb4e1292635873fe678335a58b32d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator&amp; llvm::msf::MappedBlockStream::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>

</div>
</div>

### BlockSize {#aa5461fc654a6f21cb8f536191811908f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t llvm::msf::MappedBlockStream::BlockSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>

</div>
</div>

### CacheMap {#a705e74b7fa72965edc1efa4d04cf226e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;uint32_t, std::vector&lt;CacheEntry&gt; &gt; llvm::msf::MappedBlockStream::CacheMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>

</div>
</div>

### MsfData {#ad7c3c090eefb9b013181f8c21ff47056}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamRef llvm::msf::MappedBlockStream::MsfData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>

</div>
</div>

### StreamLayout {#af34285086a39db25cb5e66488839e283}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MSFStreamLayout llvm::msf::MappedBlockStream::StreamLayout</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createDirectoryStream() {#abb227e93ab0981688803772c461a0aa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MappedBlockStream &gt; MappedBlockStream::createDirectoryStream (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout">MSFLayout</a> &amp; Layout, <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> MsfData, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator)</td>
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



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/msf/msfstreamlayout/#a8ff01bfb0db5e159e59ecb411d020342">llvm::msf::MSFStreamLayout::Blocks</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/superblock/#a4792a3763eaca59db556d1c9305741cd">llvm::msf::SuperBlock::BlockSize</a>, <a href="#a42594a94d5394378bab96f2d642f8e63">createStream</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout/#ae7cbd23b097e66cbdeccccce85704da6">llvm::msf::MSFLayout::DirectoryBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/msfstreamlayout/#a84f5daa710f9284284e3137fe3d93280">llvm::msf::MSFStreamLayout::Length</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/superblock/#a97837d9ad6f03bda18f25c7079cdb1f5">llvm::msf::SuperBlock::NumDirectoryBytes</a> and <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout/#ae81e213efb629de31c7e833c0f1c7e0d">llvm::msf::MSFLayout::SB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#a0ccdac4b6ec6b7a67a2dc7e3bd83985b">llvm::pdb::PDBFile::parseStreamData</a>.</p>

</div>
</div>

### createFpmStream() {#aca02a882851c4f44d12552f22d5fb9d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MappedBlockStream &gt; MappedBlockStream::createFpmStream (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout">MSFLayout</a> &amp; Layout, <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> MsfData, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator)</td>
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



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/msf/superblock/#a4792a3763eaca59db556d1c9305741cd">llvm::msf::SuperBlock::BlockSize</a>, <a href="#a42594a94d5394378bab96f2d642f8e63">createStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a71744b158ac455bfc08863560e6f99a0">llvm::msf::getFpmStreamLayout</a> and <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout/#ae81e213efb629de31c7e833c0f1c7e0d">llvm::msf::MSFLayout::SB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#aa8016724ba063de217ed1ccf4ddc095d">llvm::pdb::PDBFile::parseFileHeaders</a>.</p>

</div>
</div>

### createIndexedStream() {#a17d9ec7154acf6bc5c1a090db9ef2936}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MappedBlockStream &gt; MappedBlockStream::createIndexedStream (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout">MSFLayout</a> &amp; Layout, <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> MsfData, uint32_t StreamIndex, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator)</td>
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



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/msfstreamlayout/#a8ff01bfb0db5e159e59ecb411d020342">llvm::msf::MSFStreamLayout::Blocks</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/superblock/#a4792a3763eaca59db556d1c9305741cd">llvm::msf::SuperBlock::BlockSize</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/msfstreamlayout/#a84f5daa710f9284284e3137fe3d93280">llvm::msf::MSFStreamLayout::Length</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout/#ae81e213efb629de31c7e833c0f1c7e0d">llvm::msf::MSFLayout::SB</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout/#afe9788018b09e6d690be1f10d5059e07">llvm::msf::MSFLayout::StreamMap</a> and <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout/#a85d9674028dfa1734478fc520cd979af">llvm::msf::MSFLayout::StreamSizes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#af19aa92bb14252a64ac03c4ff7bf36a1">llvm::pdb::PDBFile::createIndexedStream</a>.</p>

</div>
</div>

### createStream() {#a42594a94d5394378bab96f2d642f8e63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MappedBlockStream &gt; MappedBlockStream::createStream (uint32_t BlockSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/msf/msfstreamlayout">MSFStreamLayout</a> &amp; Layout, <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> MsfData, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator)</td>
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



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">MappedBlockStream.h</a>, definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp">MappedBlockStream.cpp</a>.</p>


<p>Referenced by <a href="#abb227e93ab0981688803772c461a0aa2">createDirectoryStream</a> and <a href="#aca02a882851c4f44d12552f22d5fb9d7">createFpmStream</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
