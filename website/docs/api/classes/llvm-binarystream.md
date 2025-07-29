---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/binarystream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BinaryStream` Class

<p>An interface for accessing data in a stream-like format, but which discourages copying. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BinaryStream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystream-h">llvm/Support/BinaryStream.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-binarystreamref-cpp-/arrayrefimpl">ArrayRefImpl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binarybytestream">BinaryByteStream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An implementation of <a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a> which holds its entire data set in a single contiguous buffer. <a href="/web-llvm/docs/api/classes/llvm/binarybytestream/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binaryitemstream">BinaryItemStream&lt;T, Traits&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/binaryitemstream">BinaryItemStream</a> represents a sequence of objects stored in some kind of external container but for which it is useful to view as a stream of contiguous bytes. <a href="/web-llvm/docs/api/classes/llvm/binaryitemstream/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream">MappedBlockStream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream">MappedBlockStream</a> represents data stored in an MSF file into chunks of a particular size (called the Block Size), and whose chunks may not be necessarily contiguous. <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33868be4958cfb04cb16b14e1046a607">~BinaryStream</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ed26dade18771443e8c2a5256ddacb0">getEndian</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6df0a05b122a4a65b21f7c09882e4cb">readBytes</a> (uint64_t Offset, uint64_t Size, ArrayRef&lt; uint8_t &gt; &amp;Buffer)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an offset into the stream and a number of bytes, attempt to read the bytes and set the output <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> to point to data owned by the stream. <a href="#ab6df0a05b122a4a65b21f7c09882e4cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8fe39e341ca7c7b08a620877d548fcb">readLongestContiguousChunk</a> (uint64_t Offset, ArrayRef&lt; uint8_t &gt; &amp;Buffer)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an offset into the stream, read as much as possible without copying any data. <a href="#ad8fe39e341ca7c7b08a620877d548fcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dde414ac3eb762ffcab71c96af04922">getLength</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of bytes of data in this stream. <a href="#a2dde414ac3eb762ffcab71c96af04922">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a2ef78585311fc208693b30e27c7f8af1">BinaryStreamFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af122114352680521290a95a71f6842bd">getFlags</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the properties of this stream. <a href="#af122114352680521290a95a71f6842bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af20acc8b7134ce7ffa54c05a7f295fb6">checkOffsetForRead</a> (uint64_t Offset, uint64_t DataSize)</td>
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

<p>An interface for accessing data in a stream-like format, but which discourages copying.</p>


<p>Instead of specifying a buffer in which to copy data on a read, the API returns an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> to data owned by the stream's implementation. Since implementations may not necessarily store data in a single contiguous buffer (or even in memory at all), in such cases a it may be necessary for an implementation to cache such a buffer so that it can return it.</p>


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystream-h">BinaryStream.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~BinaryStream() {#a33868be4958cfb04cb16b14e1046a607}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::BinaryStream::~BinaryStream ()</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystream-h">BinaryStream.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getEndian() {#a0ed26dade18771443e8c2a5256ddacb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::endianness llvm::BinaryStream::getEndian ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystream-h">BinaryStream.h</a>.</p>

</div>
</div>

### getFlags() {#af122114352680521290a95a71f6842bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual BinaryStreamFlags llvm::BinaryStream::getFlags ()</td>
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

<p>Return the properties of this stream.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystream-h">BinaryStream.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a2ef78585311fc208693b30e27c7f8af1a532610776ca00601bf24807aff719482">llvm::BSF_None</a>.</p>

</div>
</div>

### getLength() {#a2dde414ac3eb762ffcab71c96af04922}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::BinaryStream::getLength ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of bytes of data in this stream.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystream-h">BinaryStream.h</a>.</p>


<p>Referenced by <a href="#af20acc8b7134ce7ffa54c05a7f295fb6">checkOffsetForRead</a>, <a href="/web-llvm/docs/api/classes/llvm/writablebinarystream/#a054c634299df770d4d683d28e2b3cb7b">llvm::WritableBinaryStream::checkOffsetForWrite</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/anonymous-nativeenuminjectedsources-cpp-/#a07dc8e4dc3f58faff0b8c71baca5cbe8">llvm::pdb::anonymous{NativeEnumInjectedSources.cpp}::readStreamData</a>.</p>

</div>
</div>

### readBytes() {#ab6df0a05b122a4a65b21f7c09882e4cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::BinaryStream::readBytes (uint64_t Offset, uint64_t Size, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &amp; Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an offset into the stream and a number of bytes, attempt to read the bytes and set the output <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> to point to data owned by the stream.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystream-h">BinaryStream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### readLongestContiguousChunk() {#ad8fe39e341ca7c7b08a620877d548fcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::BinaryStream::readLongestContiguousChunk (uint64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &amp; Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an offset into the stream, read as much as possible without copying any data.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystream-h">BinaryStream.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/pdb/anonymous-nativeenuminjectedsources-cpp-/#a07dc8e4dc3f58faff0b8c71baca5cbe8">llvm::pdb::anonymous{NativeEnumInjectedSources.cpp}::readStreamData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### checkOffsetForRead() {#af20acc8b7134ce7ffa54c05a7f295fb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::BinaryStream::checkOffsetForRead (uint64_t Offset, uint64_t DataSize)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystream-h">BinaryStream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3b9d675b34f20ba67f1f3213e63935d6">llvm::DataSize</a>, <a href="#a2dde414ac3eb762ffcab71c96af04922">getLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89daf6579f9fbeb5034d9165fe820866b23b">llvm::invalid_offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89dad88b43968f2dd7eb3d9d40060fbacc98">llvm::stream_too_short</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/writablebinarystream/#a054c634299df770d4d683d28e2b3cb7b">llvm::WritableBinaryStream::checkOffsetForWrite</a>, <a href="/web-llvm/docs/api/classes/llvm/binarybytestream/#a4e42d67aeb85b158d2954d3eab60fdd6">llvm::BinaryByteStream::readBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryitemstream/#a6f2c735b75cbf7437533bbe15c76563a">llvm::BinaryItemStream&lt; T, Traits &gt;::readBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream/#a1a421432438b984e24590ea8169dc589">llvm::msf::MappedBlockStream::readBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/binarybytestream/#a1d2da883a476269ff26f1963dcfa47e7">llvm::BinaryByteStream::readLongestContiguousChunk</a> and <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream/#a232c212f81250213c8bf658375e5aa3d">llvm::msf::MappedBlockStream::readLongestContiguousChunk</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystream-h">BinaryStream.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
