---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/writablebinarystream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WritableBinaryStream` Class

<p>A <a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a> which can be read from as well as written to. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::WritableBinaryStream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystream-h">llvm/Support/BinaryStream.h</a>"
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-binarystreamref-cpp-/mutablearrayrefimpl">MutableArrayRefImpl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/appendingbinarybytestream">AppendingBinaryByteStream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An implementation of <a href="/web-llvm/docs/api/classes/llvm/writablebinarystream">WritableBinaryStream</a> which can write at its end causing the underlying data to grow. <a href="/web-llvm/docs/api/classes/llvm/appendingbinarybytestream/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/filebufferbytestream">FileBufferByteStream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An implementation of <a href="/web-llvm/docs/api/classes/llvm/writablebinarystream">WritableBinaryStream</a> backed by an llvm <a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer">FileOutputBuffer</a>. <a href="/web-llvm/docs/api/classes/llvm/filebufferbytestream/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mutablebinarybytestream">MutableBinaryByteStream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An implementation of <a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a> which holds its entire data set in a single contiguous buffer. <a href="/web-llvm/docs/api/classes/llvm/mutablebinarybytestream/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream">WritableMappedBlockStream</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1951f11a9daefbc17e25647258f46bac">~WritableBinaryStream</a> () override=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a815a7df4e61a61d9ef36e21867f17fe4">writeBytes</a> (uint64_t Offset, ArrayRef&lt; uint8_t &gt; Data)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to write the given bytes into the stream at the desired offset. <a href="#a815a7df4e61a61d9ef36e21867f17fe4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addf522a96d8130e76dd777fbe0b32ec3">commit</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For buffered streams, commits changes to the backing store. <a href="#addf522a96d8130e76dd777fbe0b32ec3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a2ef78585311fc208693b30e27c7f8af1">BinaryStreamFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfe63cd2f7c2bd3d4f1421901ad91320">getFlags</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the properties of this stream. <a href="#acfe63cd2f7c2bd3d4f1421901ad91320">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a054c634299df770d4d683d28e2b3cb7b">checkOffsetForWrite</a> (uint64_t Offset, uint64_t DataSize)</td>
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

<p>A <a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a> which can be read from as well as written to.</p>


<p>Note that writing to a <a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a> always necessitates copying from the input buffer to the stream's backing store. Streams are assumed to be buffered so that to be portable it is necessary to call <a href="#addf522a96d8130e76dd777fbe0b32ec3">commit()</a> on the stream when all data has been written.</p>


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystream-h">BinaryStream.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~WritableBinaryStream() {#a1951f11a9daefbc17e25647258f46bac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WritableBinaryStream::~WritableBinaryStream ()</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystream-h">BinaryStream.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### commit() {#addf522a96d8130e76dd777fbe0b32ec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::WritableBinaryStream::commit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For buffered streams, commits changes to the backing store.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystream-h">BinaryStream.h</a>.</p>

</div>
</div>

### getFlags() {#acfe63cd2f7c2bd3d4f1421901ad91320}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamFlags llvm::WritableBinaryStream::getFlags ()</td>
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

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystream-h">BinaryStream.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a2ef78585311fc208693b30e27c7f8af1a850609e2d24218411280f5d2a7d87bc2">llvm::BSF_Write</a>.</p>


<p>Referenced by <a href="#a054c634299df770d4d683d28e2b3cb7b">checkOffsetForWrite</a>.</p>

</div>
</div>

### writeBytes() {#a815a7df4e61a61d9ef36e21867f17fe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::WritableBinaryStream::writeBytes (uint64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to write the given bytes into the stream at the desired offset.</p>


<p>This will always necessitate a copy. Cannot shrink or grow the stream, only writes into existing allocated space.</p>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystream-h">BinaryStream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### checkOffsetForWrite() {#a054c634299df770d4d683d28e2b3cb7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::WritableBinaryStream::checkOffsetForWrite (uint64_t Offset, uint64_t DataSize)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystream-h">BinaryStream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2ef78585311fc208693b30e27c7f8af1a63b9fe189175224612d598cd657eba21">llvm::BSF_Append</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystream/#af20acc8b7134ce7ffa54c05a7f295fb6">llvm::BinaryStream::checkOffsetForRead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b9d675b34f20ba67f1f3213e63935d6">llvm::DataSize</a>, <a href="#acfe63cd2f7c2bd3d4f1421901ad91320">getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystream/#a2dde414ac3eb762ffcab71c96af04922">llvm::BinaryStream::getLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89daf6579f9fbeb5034d9165fe820866b23b">llvm::invalid_offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/appendingbinarybytestream/#acbb5be14a8102feef6f84e1d2adfaeb7">llvm::AppendingBinaryByteStream::readBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/appendingbinarybytestream/#acc2ef96d39a2d4d967fc235188ef4797">llvm::AppendingBinaryByteStream::readLongestContiguousChunk</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream/#abe3861e116c9da3ce15c4dd46a1bfaf7">llvm::msf::WritableMappedBlockStream::writeBytes</a> and <a href="/web-llvm/docs/api/classes/llvm/mutablebinarybytestream/#ab01e4768ed6edae5181351ec2fc8be15">llvm::MutableBinaryByteStream::writeBytes</a>.</p>

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
