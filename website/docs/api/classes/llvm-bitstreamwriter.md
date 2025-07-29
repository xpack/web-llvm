---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/bitstreamwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BitstreamWriter` Class



## Declaration

<div class="doxyDeclaration">
class llvm::BitstreamWriter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">llvm/Bitstream/BitstreamWriter.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f6ee363763723bf98da451e95bb1d1c">BitstreamWriter</a> (raw_ostream &amp;OutStream, uint32_t FlushThreshold=512)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> over a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> <span class="doxyComputerOutput">OutStream</span>. <a href="#a5f6ee363763723bf98da451e95bb1d1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cbc68c0f33ec6c72b69a595c36d15c1">BitstreamWriter</a> (SmallVectorImpl&lt; char &gt; &amp;Buff)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience constructor for users that start with a vector - avoids needing to wrap it in a <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream">raw_svector_ostream</a>. <a href="#a3cbc68c0f33ec6c72b69a595c36d15c1">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf7d55f3e39ce028c1594f34967d06b3">~BitstreamWriter</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a063bf32f685de649ee8239a8e54da868">markAndBlockFlushing</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For scenarios where the user wants to access a section of the stream to (for example) compute some checksum, disable flushing and remember the position in the internal buffer where that happened. <a href="#a063bf32f685de649ee8239a8e54da868">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1817d94003400d1a95d6a35a5efe574f">getMarkedBufferAndResumeFlushing</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>resumes flushing, but does not flush, and returns the section in the internal buffer starting from the position marked with markAndBlockFlushing. <a href="#a1817d94003400d1a95d6a35a5efe574f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6a2b975dd3ba4ab436c4de2199da5ee">GetCurrentBitNo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the current position in the stream, in bits. <a href="#af6a2b975dd3ba4ab436c4de2199da5ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3254f4c3d4874089f1113157cb4494e">GetAbbrevIDWidth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the number of bits currently used to encode an abbrev <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#af3254f4c3d4874089f1113157cb4494e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61b26222d7ecfe417406eec38edba698">BackpatchByte</a> (uint64_t BitNo, uint8_t NewByte)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Backpatch a byte in the output at the given bit offset with the specified value. <a href="#a61b26222d7ecfe417406eec38edba698">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae431728f61d5b52efa59fc13f834085f">BackpatchHalfWord</a> (uint64_t BitNo, uint16_t Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e13da25204783390ddfc17dcf55a1c2">BackpatchWord</a> (uint64_t BitNo, unsigned Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4ad7b052bd7dcf08ff26ad92351f1b5">BackpatchWord64</a> (uint64_t BitNo, uint64_t Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40de93ba2d72dc6bccd7a1fdde996718">Emit</a> (uint32_t Val, unsigned NumBits)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87d4d8efe6bca7b041b0837d30add275">FlushToWord</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d3d121556c01aab6e6ebfc830e17dbb">EmitVBR</a> (uint32_t Val, unsigned NumBits)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a765ce2a472e2eedad6b7ed02b6674a00">EmitVBR64</a> (uint64_t Val, unsigned NumBits)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47cd6c37f5dc6cee1e2337f909452c85">EmitCode</a> (unsigned Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitCode - Emit the specified code. <a href="#a47cd6c37f5dc6cee1e2337f909452c85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">BlockInfo *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75bf3c7fbbde90c257abf2fb5a89badf">getBlockInfo</a> (unsigned BlockID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getBlockInfo - If there is block info for the specified <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, return it, otherwise return null. <a href="#a75bf3c7fbbde90c257abf2fb5a89badf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6a40b4a5ea89bb8b5076c26e0d0b638">EnterSubblock</a> (unsigned BlockID, unsigned CodeLen)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e8488041d80c56389002659004c6af7">ExitBlock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class UIntTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a42a0cfa56ebe2de750170da9db67f927">emitBlob</a> (ArrayRef&lt; UIntTy &gt; Bytes, bool ShouldEmitSize=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a blob, including flushing before and tail-padding. <a href="#a42a0cfa56ebe2de750170da9db67f927">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7a72ed69b91577b81089ff1a7a57197">emitBlob</a> (StringRef Bytes, bool ShouldEmitSize=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Container&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2a492ce167a19107e75ec372f68e8d7a">EmitRecord</a> (unsigned Code, const Container &amp;Vals, unsigned Abbrev=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitRecord - Emit the specified record to the stream, using an abbrev if we have one to compress the output. <a href="#a2a492ce167a19107e75ec372f68e8d7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Container&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af948971b2d980eb419383bc379a757fd">EmitRecordWithAbbrev</a> (unsigned Abbrev, const Container &amp;Vals)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitRecordWithAbbrev - Emit a record with the specified abbreviation. <a href="#af948971b2d980eb419383bc379a757fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Container&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5f4f488b3478316b8d6bb3582b158673">EmitRecordWithBlob</a> (unsigned Abbrev, const Container &amp;Vals, StringRef Blob)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitRecordWithBlob - Emit the specified record to the stream, using an abbrev that includes a blob at the end. <a href="#a5f4f488b3478316b8d6bb3582b158673">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Container&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4e635d4d3026cb830212fb071e2024a1">EmitRecordWithBlob</a> (unsigned Abbrev, const Container &amp;Vals, const char *BlobData, unsigned BlobLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Container&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a78a7f3e3174bd721b9b3c268e621273c">EmitRecordWithArray</a> (unsigned Abbrev, const Container &amp;Vals, StringRef Array)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitRecordWithArray - Just like EmitRecordWithBlob, works with records that end with an array. <a href="#a78a7f3e3174bd721b9b3c268e621273c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Container&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4f8ae2680f67165a8ab818db76e89967">EmitRecordWithArray</a> (unsigned Abbrev, const Container &amp;Vals, const char *ArrayData, unsigned ArrayLen)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a032ac42ce93b41ccad6f2380a3efa207">EmitAbbrev</a> (std::shared_ptr&lt; BitCodeAbbrev &gt; Abbv)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the abbreviation <span class="doxyComputerOutput">Abbv</span> to the stream. <a href="#a032ac42ce93b41ccad6f2380a3efa207">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d9f43e5e75f1cd3eac411cd4dc2c6a3">EnterBlockInfoBlock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EnterBlockInfoBlock - Start emitting the BLOCKINFO_BLOCK. <a href="#a8d9f43e5e75f1cd3eac411cd4dc2c6a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7507fea7693cf3d8124918eca60eef85">EmitBlockInfoAbbrev</a> (unsigned BlockID, std::shared_ptr&lt; BitCodeAbbrev &gt; Abbv)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitBlockInfoAbbrev - Emit a DEFINE_ABBREV record for the specified BlockID. <a href="#a7507fea7693cf3d8124918eca60eef85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70783880da8a7556d0e92d0f89b6c47d">WriteWord</a> (unsigned Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb0ad261dcbdb4a4227cbfabcd6c0fdb">GetNumOfFlushedBytes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeafca1048e303aa7eb6455ef59d842e2">GetBufferOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87d3b03e4906ce3b8bfc3c37d11db034">GetWordIndex</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fb41acd1af04214cd799b9be19bfc3a">flushAndClear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15d6f1a9a10e0e7cb39cc0cff8b2fbe5">FlushToFile</a> (bool OnClosing=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the related file stream is a <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream">raw_fd_stream</a>, flush the buffer if its size is above a threshold. <a href="#a15d6f1a9a10e0e7cb39cc0cff8b2fbe5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream">raw_fd_stream</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73f4b5500e66c3ad3fe993c7046dd3a7">fdStream</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream">raw_fd_stream</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26feb2e509746dfd2031bc9e316d2b51">fdStream</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d1b520088b8459f85b51d8f001f3a18">getInternalBufferFromStream</a> (raw_ostream &amp;OutStream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename uintty&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5e80f04829f1010a860168717649779b">EmitAbbreviatedLiteral</a> (const BitCodeAbbrevOp &amp;Op, uintty V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitAbbreviatedLiteral - Emit a literal value according to its abbrev record. <a href="#a5e80f04829f1010a860168717649779b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename uintty&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5d3eca41964e33be3c53683bc22d13d8">EmitAbbreviatedField</a> (const BitCodeAbbrevOp &amp;Op, uintty V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitAbbreviatedField - Emit a single scalar field value with the specified encoding. <a href="#a5d3eca41964e33be3c53683bc22d13d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename uintty&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a43f7317873888110025bf0f2369d38d4">EmitRecordWithAbbrevImpl</a> (unsigned Abbrev, ArrayRef&lt; uintty &gt; Vals, StringRef Blob, std::optional&lt; unsigned &gt; Code)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitRecordWithAbbrevImpl - This is the core implementation of the record emission code. <a href="#a43f7317873888110025bf0f2369d38d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fea53b98f31666ed5294cf4bb4a1f26">EncodeAbbrev</a> (const BitCodeAbbrev &amp;Abbv)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ddc20e767e065238be211b4a6b8fdf1">SwitchToBlockID</a> (unsigned BlockID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SwitchToBlockID - If we aren't already talking about the specified block <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, emit a BLOCKINFO_CODE_SETBID record. <a href="#a5ddc20e767e065238be211b4a6b8fdf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">BlockInfo &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fe74e9d3cfee803da8b405bee658e96">getOrCreateBlockInfo</a> (unsigned BlockID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; char, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14aae74d5fd9e837b895fbdccfcf6470">OwnBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Owned buffer, used to init Buffer if the provided stream doesn't happen to be a buffer itself. <a href="#a14aae74d5fd9e837b895fbdccfcf6470">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cf20fe6d1f21cc4812de07c62596cd2">Buffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Internal buffer for unflushed bytes (unless there is no stream to flush to, case in which these are "the bytes"). <a href="#a8cf20fe6d1f21cc4812de07c62596cd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad396113421e9eea552c282d2cc4a23f1">FS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FS - The file stream that Buffer flushes to. <a href="#ad396113421e9eea552c282d2cc4a23f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdcc5f2bdac2b9e7e35e9a002bb17b51">FlushThreshold</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FlushThreshold - this is the threshold (unit B) to flush to FS, if FS is a <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream">raw_fd_stream</a>. <a href="#afdcc5f2bdac2b9e7e35e9a002bb17b51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a50d2956097016e3e238292d1f0b08d">CurBit</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CurBit - Always between 0 and 31 inclusive, specifies the next bit to use. <a href="#a4a50d2956097016e3e238292d1f0b08d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91494138910feec0d1ce89fd19ab0b9b">CurValue</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CurValue - The current value. Only bits &lt; CurBit are valid. <a href="#a91494138910feec0d1ce89fd19ab0b9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a698d15dd7fab2e68baade7bace4537c9">CurCodeSize</a> = 2</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CurCodeSize - This is the declared size of code values used for the current block, in bits. <a href="#a698d15dd7fab2e68baade7bace4537c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee5498cd81a59c8b001d6896c4d04f35">BlockInfoCurBID</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BlockInfoCurBID - When emitting a BLOCKINFO_BLOCK, this is the currently selected BLOCK <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#aee5498cd81a59c8b001d6896c4d04f35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrev">BitCodeAbbrev</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2067231e69bbf9b1133cce389a81d588">CurAbbrevs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CurAbbrevs - Abbrevs installed at in this block. <a href="#a2067231e69bbf9b1133cce389a81d588">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83624eb7826c7d09b1bb9a47ecd4d194">BlockFlushingStartPos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; Block &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a933414e414dc06e3aa0d9fdeb0fb24c9">BlockScope</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BlockScope - This tracks the current blocks that we have entered. <a href="#a933414e414dc06e3aa0d9fdeb0fb24c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; BlockInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b2d475674070a6c40a8582ab686633f">BlockInfoRecords</a></td>
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


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BitstreamWriter() {#a5f6ee363763723bf98da451e95bb1d1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitstreamWriter::BitstreamWriter (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OutStream, uint32_t FlushThreshold=512)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> over a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> <span class="doxyComputerOutput">OutStream</span>.</p>


<p>If <span class="doxyComputerOutput">OutStream</span> is a <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream">raw_svector_ostream</a>, the <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> will write directly to the latter's buffer. In all other cases, the <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> will use an internal buffer and flush at the end of its lifetime.</p>


<p>In addition, if <span class="doxyComputerOutput">is</span> a <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream">raw_fd_stream</a> supporting seek, tell, and read (besides write), the <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> will also flush incrementally, when a subblock is finished, and if the FlushThreshold is passed.</p>


<p>NOTE: <span class="doxyComputerOutput">FlushThreshold's</span> unit is <a href="/web-llvm/docs/api/classes/mb">MB</a>.</p>


<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### BitstreamWriter() {#a3cbc68c0f33ec6c72b69a595c36d15c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitstreamWriter::BitstreamWriter (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Buff)</td>
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

<p>Convenience constructor for users that start with a vector - avoids needing to wrap it in a <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream">raw_svector_ostream</a>.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~BitstreamWriter() {#abf7d55f3e39ce028c1594f34967d06b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitstreamWriter::~BitstreamWriter ()</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a87d4d8efe6bca7b041b0837d30add275">FlushToWord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### BackpatchByte() {#a61b26222d7ecfe417406eec38edba698}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::BackpatchByte (uint64_t BitNo, uint8_t NewByte)</td>
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

<p>Backpatch a byte in the output at the given bit offset with the specified value.</p>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a6d9995bf8da2a0fed6fa31bce97aeebd">llvm::support::endian::readAtBitAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/#a92fe024386465eeb8aeb7c78371549d7af6b11e8bcea1b0b70051b197f2cb3f84">llvm::support::unaligned</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a60b7cc9c00de00b23725cfa29e75ca3f">llvm::support::endian::writeAtBitAlignment</a>.</p>


<p>Referenced by <a href="#ae431728f61d5b52efa59fc13f834085f">BackpatchHalfWord</a>.</p>

</div>
</div>

### BackpatchHalfWord() {#ae431728f61d5b52efa59fc13f834085f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::BackpatchHalfWord (uint64_t BitNo, uint16_t Val)</td>
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



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>Reference <a href="#a61b26222d7ecfe417406eec38edba698">BackpatchByte</a>.</p>


<p>Referenced by <a href="#a9e13da25204783390ddfc17dcf55a1c2">BackpatchWord</a>.</p>

</div>
</div>

### BackpatchWord() {#a9e13da25204783390ddfc17dcf55a1c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::BackpatchWord (uint64_t BitNo, unsigned Val)</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>Reference <a href="#ae431728f61d5b52efa59fc13f834085f">BackpatchHalfWord</a>.</p>


<p>Referenced by <a href="#aa4ad7b052bd7dcf08ff26ad92351f1b5">BackpatchWord64</a> and <a href="#a5e8488041d80c56389002659004c6af7">ExitBlock</a>.</p>

</div>
</div>

### BackpatchWord64() {#aa4ad7b052bd7dcf08ff26ad92351f1b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::BackpatchWord64 (uint64_t BitNo, uint64_t Val)</td>
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



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>Reference <a href="#a9e13da25204783390ddfc17dcf55a1c2">BackpatchWord</a>.</p>

</div>
</div>

### Emit() {#a40de93ba2d72dc6bccd7a1fdde996718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::Emit (uint32_t Val, unsigned NumBits)</td>
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



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a47cd6c37f5dc6cee1e2337f909452c85">EmitCode</a>, <a href="#a9d3d121556c01aab6e6ebfc830e17dbb">EmitVBR</a>, <a href="#a765ce2a472e2eedad6b7ed02b6674a00">EmitVBR64</a>, <a href="#ae6a40b4a5ea89bb8b5076c26e0d0b638">EnterSubblock</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a90f3f0ae5027fb62fc0090c0b0722d0f">writeBitcodeHeader</a>.</p>

</div>
</div>

### EmitAbbrev() {#a032ac42ce93b41ccad6f2380a3efa207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BitstreamWriter::EmitAbbrev (std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrev">BitCodeAbbrev</a> &gt; Abbv)</td>
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

<p>Emits the abbreviation <span class="doxyComputerOutput">Abbv</span> to the stream.</p>

<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#ab7a76f80792b96a4291e2d1dd1403887a81e1f263b022b7989aa71fb623b62be8">llvm::bitc::FIRST_APPLICATION_ABBREV</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a71e02e853cce26400683e76984e82529">writeIdentificationBlock</a>.</p>

</div>
</div>

### emitBlob() {#a42a0cfa56ebe2de750170da9db67f927}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class UIntTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::emitBlob (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; UIntTy &gt; Bytes, bool ShouldEmitSize=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Emit a blob, including flushing before and tail-padding.</p>

<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="#a9d3d121556c01aab6e6ebfc830e17dbb">EmitVBR</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="#a87d4d8efe6bca7b041b0837d30add275">FlushToWord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#ac7a72ed69b91577b81089ff1a7a57197">emitBlob</a>.</p>

</div>
</div>

### emitBlob() {#ac7a72ed69b91577b81089ff1a7a57197}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::emitBlob (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Bytes, bool ShouldEmitSize=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 563 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="#a42a0cfa56ebe2de750170da9db67f927">emitBlob</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### EmitBlockInfoAbbrev() {#a7507fea7693cf3d8124918eca60eef85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BitstreamWriter::EmitBlockInfoAbbrev (unsigned BlockID, std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrev">BitCodeAbbrev</a> &gt; Abbv)</td>
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

<p>EmitBlockInfoAbbrev - Emit a DEFINE_ABBREV record for the specified BlockID.</p>

<p>Definition at line 693 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#ab7a76f80792b96a4291e2d1dd1403887a81e1f263b022b7989aa71fb623b62be8">llvm::bitc::FIRST_APPLICATION_ABBREV</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>.</p>

</div>
</div>

### EmitCode() {#a47cd6c37f5dc6cee1e2337f909452c85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::EmitCode (unsigned Val)</td>
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

<p>EmitCode - Emit the specified code.</p>

<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>Reference <a href="#a40de93ba2d72dc6bccd7a1fdde996718">Emit</a>.</p>


<p>Referenced by <a href="#a2a492ce167a19107e75ec372f68e8d7a">EmitRecord</a>, <a href="#ae6a40b4a5ea89bb8b5076c26e0d0b638">EnterSubblock</a> and <a href="#a5e8488041d80c56389002659004c6af7">ExitBlock</a>.</p>

</div>
</div>

### EmitRecord() {#a2a492ce167a19107e75ec372f68e8d7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Container&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::EmitRecord (unsigned Code, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Container &amp; Vals, unsigned Abbrev=0)</td>
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

<p>EmitRecord - Emit the specified record to the stream, using an abbrev if we have one to compress the output.</p>

<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a47cd6c37f5dc6cee1e2337f909452c85">EmitCode</a>, <a href="#a9d3d121556c01aab6e6ebfc830e17dbb">EmitVBR</a>, <a href="#a765ce2a472e2eedad6b7ed02b6674a00">EmitVBR64</a> and <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#ab7a76f80792b96a4291e2d1dd1403887a5436567dadf1048914764efde6bcc891">llvm::bitc::UNABBREV_RECORD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a0850c8a2472500d4a79b9f48495a1d2f">writeFunctionHeapProfileRecords</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#ac7e865e854ff6b0ba0eb2147e0ccb5cc">writeFunctionTypeMetadataRecords</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a71e02e853cce26400683e76984e82529">writeIdentificationBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a6ddafba4af9c27c785a0d873fd3cb661">writeMemoryProfileRadixTree</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#ad375d674219d643fe0ba85db2b7f172a">writeStringRecord</a>.</p>

</div>
</div>

### EmitRecordWithAbbrev() {#af948971b2d980eb419383bc379a757fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Container&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::EmitRecordWithAbbrev (unsigned Abbrev, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Container &amp; Vals)</td>
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

<p>EmitRecordWithAbbrev - Emit a record with the specified abbreviation.</p>


<p>Unlike EmitRecord, the code for the record should be included in Vals as the first entry.</p>


<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding-e92e567fbcfc8afd44242d623ff29b96/#af70bb0d684f2600b57a140823fb2b07c">llvm::detail::BCRecordCoding&lt; BCArray&lt; ElementTy &gt; &gt;::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding-e92e567fbcfc8afd44242d623ff29b96/#a61bdddf1cd33672bac411390387451de">llvm::detail::BCRecordCoding&lt; BCArray&lt; ElementTy &gt; &gt;::emit</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding-7416a4930392106d56f3af1734eb69d7/#a7b37e8210c0732bf6de45a3216e1702e">llvm::detail::BCRecordCoding&lt; ElementTy &gt;::emit</a>.</p>

</div>
</div>

### EmitRecordWithArray() {#a78a7f3e3174bd721b9b3c268e621273c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Container&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::EmitRecordWithArray (unsigned Abbrev, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Container &amp; Vals, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Array)</td>
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

<p>EmitRecordWithArray - Just like EmitRecordWithBlob, works with records that end with an array.</p>

<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding-e92e567fbcfc8afd44242d623ff29b96/#a2d08ccaf46363d002d905b3f3beb50fb">llvm::detail::BCRecordCoding&lt; BCArray&lt; ElementTy &gt; &gt;::emit</a>.</p>

</div>
</div>

### EmitRecordWithArray() {#a4f8ae2680f67165a8ab818db76e89967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Container&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::EmitRecordWithArray (unsigned Abbrev, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Container &amp; Vals, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ArrayData, unsigned ArrayLen)</td>
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



<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>

</div>
</div>

### EmitRecordWithBlob() {#a5f4f488b3478316b8d6bb3582b158673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Container&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::EmitRecordWithBlob (unsigned Abbrev, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Container &amp; Vals, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Blob)</td>
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

<p>EmitRecordWithBlob - Emit the specified record to the stream, using an abbrev that includes a blob at the end.</p>


<p>The blob data to emit is specified by the pointer and length specified at the end. In contrast to EmitRecord, this routine expects that the first entry in Vals is the code of the record.</p>


<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding-b9c0cc53cb17fcebab888745f2cdc703/#a044776af18211267893a1a87eaff5c19">llvm::detail::BCRecordCoding&lt; BCBlob &gt;::emit</a>.</p>

</div>
</div>

### EmitRecordWithBlob() {#a4e635d4d3026cb830212fb071e2024a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Container&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::EmitRecordWithBlob (unsigned Abbrev, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Container &amp; Vals, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * BlobData, unsigned BlobLen)</td>
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



<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>

</div>
</div>

### EmitVBR() {#a9d3d121556c01aab6e6ebfc830e17dbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::EmitVBR (uint32_t Val, unsigned NumBits)</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a40de93ba2d72dc6bccd7a1fdde996718">Emit</a>.</p>


<p>Referenced by <a href="#a42a0cfa56ebe2de750170da9db67f927">emitBlob</a>, <a href="#a2a492ce167a19107e75ec372f68e8d7a">EmitRecord</a>, <a href="#a765ce2a472e2eedad6b7ed02b6674a00">EmitVBR64</a> and <a href="#ae6a40b4a5ea89bb8b5076c26e0d0b638">EnterSubblock</a>.</p>

</div>
</div>

### EmitVBR64() {#a765ce2a472e2eedad6b7ed02b6674a00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::EmitVBR64 (uint64_t Val, unsigned NumBits)</td>
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



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a40de93ba2d72dc6bccd7a1fdde996718">Emit</a> and <a href="#a9d3d121556c01aab6e6ebfc830e17dbb">EmitVBR</a>.</p>


<p>Referenced by <a href="#a2a492ce167a19107e75ec372f68e8d7a">EmitRecord</a>.</p>

</div>
</div>

### EnterBlockInfoBlock() {#a8d9f43e5e75f1cd3eac411cd4dc2c6a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::EnterBlockInfoBlock ()</td>
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

<p>EnterBlockInfoBlock - Start emitting the BLOCKINFO_BLOCK.</p>

<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a8cd4dd534ba6c31e93a88ca286c4f0e5a9c269366c4dc4af235c9bb24fa46f915">llvm::bitc::BLOCKINFO_BLOCK_ID</a> and <a href="#ae6a40b4a5ea89bb8b5076c26e0d0b638">EnterSubblock</a>.</p>

</div>
</div>

### EnterSubblock() {#ae6a40b4a5ea89bb8b5076c26e0d0b638}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::EnterSubblock (unsigned BlockID, unsigned CodeLen)</td>
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



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a9bbccfa3e710e59b93cc5a5bf8908cf9a4ae63f558586ca60ba786b672433ed5b">llvm::bitc::BlockIDWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a9bbccfa3e710e59b93cc5a5bf8908cf9aa1212eb73e20141e515bcf2f6cba192b">llvm::bitc::BlockSizeWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a9bbccfa3e710e59b93cc5a5bf8908cf9a81e88c5ec4ef96d2e57203df2ca9c7f8">llvm::bitc::CodeLenWidth</a>, <a href="#a40de93ba2d72dc6bccd7a1fdde996718">Emit</a>, <a href="#a47cd6c37f5dc6cee1e2337f909452c85">EmitCode</a>, <a href="#a9d3d121556c01aab6e6ebfc830e17dbb">EmitVBR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#ab7a76f80792b96a4291e2d1dd1403887a8ade579114e64f6e93e5c2335d9790b3">llvm::bitc::ENTER_SUBBLOCK</a>, <a href="#a87d4d8efe6bca7b041b0837d30add275">FlushToWord</a>, <a href="#a75bf3c7fbbde90c257abf2fb5a89badf">getBlockInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>.</p>


<p>Referenced by <a href="#a8d9f43e5e75f1cd3eac411cd4dc2c6a3">EnterBlockInfoBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a71e02e853cce26400683e76984e82529">writeIdentificationBlock</a>.</p>

</div>
</div>

### ExitBlock() {#a5e8488041d80c56389002659004c6af7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::ExitBlock ()</td>
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



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a9e13da25204783390ddfc17dcf55a1c2">BackpatchWord</a>, <a href="#a47cd6c37f5dc6cee1e2337f909452c85">EmitCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#ab7a76f80792b96a4291e2d1dd1403887aee620990aa08180f9ede6fd5c8440620">llvm::bitc::END_BLOCK</a> and <a href="#a87d4d8efe6bca7b041b0837d30add275">FlushToWord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a71e02e853cce26400683e76984e82529">writeIdentificationBlock</a>.</p>

</div>
</div>

### FlushToWord() {#a87d4d8efe6bca7b041b0837d30add275}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::FlushToWord ()</td>
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



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>Referenced by <a href="#a42a0cfa56ebe2de750170da9db67f927">emitBlob</a>, <a href="#ae6a40b4a5ea89bb8b5076c26e0d0b638">EnterSubblock</a>, <a href="#a5e8488041d80c56389002659004c6af7">ExitBlock</a> and <a href="#abf7d55f3e39ce028c1594f34967d06b3">~BitstreamWriter</a>.</p>

</div>
</div>

### GetAbbrevIDWidth() {#af3254f4c3d4874089f1113157cb4494e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BitstreamWriter::GetAbbrevIDWidth ()</td>
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

<p>Retrieve the number of bits currently used to encode an abbrev <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### getBlockInfo() {#a75bf3c7fbbde90c257abf2fb5a89badf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockInfo * llvm::BitstreamWriter::getBlockInfo (unsigned BlockID)</td>
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

<p>getBlockInfo - If there is block info for the specified <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, return it, otherwise return null.</p>

<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>Referenced by <a href="#ae6a40b4a5ea89bb8b5076c26e0d0b638">EnterSubblock</a>.</p>

</div>
</div>

### GetCurrentBitNo() {#af6a2b975dd3ba4ab436c4de2199da5ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BitstreamWriter::GetCurrentBitNo ()</td>
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

<p>Retrieve the current position in the stream, in bits.</p>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### getMarkedBufferAndResumeFlushing() {#a1817d94003400d1a95d6a35a5efe574f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::BitstreamWriter::getMarkedBufferAndResumeFlushing ()</td>
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

<p>resumes flushing, but does not flush, and returns the section in the internal buffer starting from the position marked with markAndBlockFlushing.</p>


<p>The return should be processed before any additional calls to this object, because those may cause a flush and invalidate the return.</p>


<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### markAndBlockFlushing() {#a063bf32f685de649ee8239a8e54da868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::markAndBlockFlushing ()</td>
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

<p>For scenarios where the user wants to access a section of the stream to (for example) compute some checksum, disable flushing and remember the position in the internal buffer where that happened.</p>


<p>Must be paired with a call to getMarkedBufferAndResumeFlushing.</p>


<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### EmitAbbreviatedField() {#a5d3eca41964e33be3c53683bc22d13d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename uintty&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::EmitAbbreviatedField (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop">BitCodeAbbrevOp</a> &amp; Op, uintty V)</td>
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

<p>EmitAbbreviatedField - Emit a single scalar field value with the specified encoding.</p>

<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### EmitAbbreviatedLiteral() {#a5e80f04829f1010a860168717649779b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename uintty&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::EmitAbbreviatedLiteral (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop">BitCodeAbbrevOp</a> &amp; Op, uintty V)</td>
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

<p>EmitAbbreviatedLiteral - Emit a literal value according to its abbrev record.</p>


<p>This is a no-op, since the abbrev specifies the literal to use.</p>


<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### EmitRecordWithAbbrevImpl() {#a43f7317873888110025bf0f2369d38d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename uintty&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::EmitRecordWithAbbrevImpl (unsigned Abbrev, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uintty &gt; Vals, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Blob, std::optional&lt; unsigned &gt; Code)</td>
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

<p>EmitRecordWithAbbrevImpl - This is the core implementation of the record emission code.</p>


<p>If BlobData is non-null, then it specifies an array of data that should be emitted as part of the Blob or Array operand that is known to exist at the end of the record. If Code is specified, then it is the record code to emit before the Vals, which must not contain the code.</p>


<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### EncodeAbbrev() {#a9fea53b98f31666ed5294cf4bb4a1f26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::EncodeAbbrev (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrev">BitCodeAbbrev</a> &amp; Abbv)</td>
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



<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### fdStream() {#a73f4b5500e66c3ad3fe993c7046dd3a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_fd_stream * llvm::BitstreamWriter::fdStream ()</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### fdStream() {#a26feb2e509746dfd2031bc9e316d2b51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const raw_fd_stream * llvm::BitstreamWriter::fdStream ()</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### flushAndClear() {#a5fb41acd1af04214cd799b9be19bfc3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::flushAndClear ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### FlushToFile() {#a15d6f1a9a10e0e7cb39cc0cff8b2fbe5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::FlushToFile (bool OnClosing=false)</td>
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

<p>If the related file stream is a <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream">raw_fd_stream</a>, flush the buffer if its size is above a threshold.</p>


<p>If <span class="doxyComputerOutput">OnClosing</span> is true, flushing happens regardless of thresholds.</p>


<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### GetBufferOffset() {#aeafca1048e303aa7eb6455ef59d842e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::BitstreamWriter::GetBufferOffset ()</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### getInternalBufferFromStream() {#a4d1b520088b8459f85b51d8f001f3a18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; char &gt; &amp; llvm::BitstreamWriter::getInternalBufferFromStream (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OutStream)</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### GetNumOfFlushedBytes() {#afb0ad261dcbdb4a4227cbfabcd6c0fdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BitstreamWriter::GetNumOfFlushedBytes ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### getOrCreateBlockInfo() {#a5fe74e9d3cfee803da8b405bee658e96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockInfo &amp; llvm::BitstreamWriter::getOrCreateBlockInfo (unsigned BlockID)</td>
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



<p>Definition at line 679 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### GetWordIndex() {#a87d3b03e4906ce3b8bfc3c37d11db034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::BitstreamWriter::GetWordIndex ()</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### SwitchToBlockID() {#a5ddc20e767e065238be211b4a6b8fdf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::SwitchToBlockID (unsigned BlockID)</td>
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

<p>SwitchToBlockID - If we aren't already talking about the specified block <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, emit a BLOCKINFO_CODE_SETBID record.</p>

<p>Definition at line 671 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### WriteWord() {#a70783880da8a7556d0e92d0f89b6c47d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamWriter::WriteWord (unsigned Value)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BlockFlushingStartPos {#a83624eb7826c7d09b1bb9a47ecd4d194}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;size_t&gt; llvm::BitstreamWriter::BlockFlushingStartPos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### BlockInfoCurBID {#aee5498cd81a59c8b001d6896c4d04f35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BitstreamWriter::BlockInfoCurBID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>BlockInfoCurBID - When emitting a BLOCKINFO_BLOCK, this is the currently selected BLOCK <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### BlockInfoRecords {#a6b2d475674070a6c40a8582ab686633f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;BlockInfo&gt; llvm::BitstreamWriter::BlockInfoRecords</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### BlockScope {#a933414e414dc06e3aa0d9fdeb0fb24c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Block&gt; llvm::BitstreamWriter::BlockScope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>BlockScope - This tracks the current blocks that we have entered.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### Buffer {#a8cf20fe6d1f21cc4812de07c62596cd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt;char&gt;&amp; llvm::BitstreamWriter::Buffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Internal buffer for unflushed bytes (unless there is no stream to flush to, case in which these are "the bytes").</p>


<p>The writer backpatches, so it is efficient to buffer.</p>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### CurAbbrevs {#a2067231e69bbf9b1133cce389a81d588}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::shared_ptr&lt;BitCodeAbbrev&gt; &gt; llvm::BitstreamWriter::CurAbbrevs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CurAbbrevs - Abbrevs installed at in this block.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### CurBit {#a4a50d2956097016e3e238292d1f0b08d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BitstreamWriter::CurBit = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CurBit - Always between 0 and 31 inclusive, specifies the next bit to use.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### CurCodeSize {#a698d15dd7fab2e68baade7bace4537c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BitstreamWriter::CurCodeSize = 2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CurCodeSize - This is the declared size of code values used for the current block, in bits.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### CurValue {#a91494138910feec0d1ce89fd19ab0b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::BitstreamWriter::CurValue = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CurValue - The current value. Only bits &lt; CurBit are valid.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### FlushThreshold {#afdcc5f2bdac2b9e7e35e9a002bb17b51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t llvm::BitstreamWriter::FlushThreshold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FlushThreshold - this is the threshold (unit B) to flush to FS, if FS is a <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream">raw_fd_stream</a>.</p>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### FS {#ad396113421e9eea552c282d2cc4a23f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream* const llvm::BitstreamWriter::FS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FS - The file stream that Buffer flushes to.</p>


<p>If FS is a <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream">raw_fd_stream</a>, the writer will incrementally flush at subblock boundaries. Otherwise flushing will happen at the end of <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a>'s lifetime.</p>


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

### OwnBuffer {#a14aae74d5fd9e837b895fbdccfcf6470}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;char, 0&gt; llvm::BitstreamWriter::OwnBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Owned buffer, used to init Buffer if the provided stream doesn't happen to be a buffer itself.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">BitstreamWriter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
