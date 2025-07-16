---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/msf/msfbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MSFBuilder` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::msf::MSFBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">llvm/DebugInfo/MSF/MSFBuilder.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff191f1bd9f63d366e1f83f695ad3443">BlockList</a> = std::vector&lt; uint32_t &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a093cb5c774dd6ce97c1a03dc942506c5">MSFBuilder</a> (uint32_t BlockSize, uint32_t MinBlockCount, bool CanGrow, BumpPtrAllocator &amp;Allocator)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1af64821af285e06f73d4f9bae60b68a">setBlockMapAddr</a> (uint32_t Addr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Request the block map to be at a specific block address. <a href="#a1af64821af285e06f73d4f9bae60b68a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3da93abaa67b0e96193734c8084fd3ce">setDirectoryBlocksHint</a> (ArrayRef&lt; uint32_t &gt; DirBlocks)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81dc1a77bc37730b480a4156fd73acbf">setFreePageMap</a> (uint32_t Fpm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af49f1e6ad306896b15614ee4c85dae63">setUnknown1</a> (uint32_t Unk1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4a2024c4c2cee5d75b2146a5bc544d4">addStream</a> (uint32_t Size, ArrayRef&lt; uint32_t &gt; Blocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a stream to the MSF file with the given size, occupying the given list of blocks. <a href="#af4a2024c4c2cee5d75b2146a5bc544d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf419bcec077ae6a195e0dcb3f14e255">addStream</a> (uint32_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a stream to the MSF file with the given size, occupying any available blocks that the builder decides to use. <a href="#acf419bcec077ae6a195e0dcb3f14e255">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66e6af17e700be6707740c63b7a6a63a">setStreamSize</a> (uint32_t Idx, uint32_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the size of an existing stream. <a href="#a66e6af17e700be6707740c63b7a6a63a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a4c287c2a21d1b468046e9a1c2c65e9">getNumStreams</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the total number of streams in the MSF layout. <a href="#a1a4c287c2a21d1b468046e9a1c2c65e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83b60b1263dc7b45aa324789cea86b2e">getStreamSize</a> (uint32_t StreamIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the size of a stream by index. <a href="#a83b60b1263dc7b45aa324789cea86b2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cb0641d54f97a3c059cf843833efdd9">getStreamBlocks</a> (uint32_t StreamIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the list of blocks allocated to a particular stream. <a href="#a2cb0641d54f97a3c059cf843833efdd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeea8e76793f05963e0e39ce7302eac0">getNumUsedBlocks</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the total number of blocks that will be allocated to actual data in this MSF file. <a href="#adeea8e76793f05963e0e39ce7302eac0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56ce626295d844880a5a783965f03b0c">getNumFreeBlocks</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the total number of blocks that exist in the MSF file but are not allocated to any valid data. <a href="#a56ce626295d844880a5a783965f03b0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51f60aa0d067106219360c6b42b2607f">getTotalBlockCount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the total number of blocks in the MSF file. <a href="#a51f60aa0d067106219360c6b42b2607f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a742ea3d26a3604448c76c64f7a9341ab">isBlockFree</a> (uint32_t Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether a particular block is allocated or free. <a href="#a742ea3d26a3604448c76c64f7a9341ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout">MSFLayout</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fc9c4f6f23dfa2eb0a1b8feb680ac92">generateLayout</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize the layout and build the headers and structures that describe the MSF layout and can be written directly to the MSF file. <a href="#a6fc9c4f6f23dfa2eb0a1b8feb680ac92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/filebufferbytestream">FileBufferByteStream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c98d361786661879be283e8abc78dbf">commit</a> (StringRef Path, MSFLayout &amp;Layout)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the MSF layout to the underlying file. <a href="#a6c98d361786661879be283e8abc78dbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a625ab5cfc095eb1bd884cd6191373d89">getAllocator</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95a12b018905ec7f7b7a99999e8bab62">allocateBlocks</a> (uint32_t NumBlocks, MutableArrayRef&lt; uint32_t &gt; Blocks)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a979cc426963344f7b841af01301d0ed2">computeDirectoryByteSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a258ef180d477640b7804c6ca0bb1b60c">Allocator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cda01cfa9f65576a8de8e3f194f792f">IsGrowable</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ad8f0024a1f06e67770315af7f0d751">FreePageMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3736b1b32cca074d0f89f43c99b9f05">Unknown1</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe07639f7d9f837040bc5858d818c22c">BlockSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80101416f0cc7f88de50d1977d82cbcd">BlockMapAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a364b2cb46885ac1b86fe2bf51407cc7a">FreeBlocks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a423efaf47dc3c07eb4b2aec17c6f5d84">DirectoryBlocks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; uint32_t, BlockList &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6e7c56e1a1f9a34f586546ee8ea4c46">StreamData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder">MSFBuilder</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c21485958080726f29f691b4cbfcf00">create</a> (BumpPtrAllocator &amp;Allocator, uint32_t BlockSize, uint32_t MinBlockCount=0, bool CanGrow=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder">MSFBuilder</a></span>. <a href="#a8c21485958080726f29f691b4cbfcf00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BlockList {#aff191f1bd9f63d366e1f83f695ad3443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::msf::MSFBuilder::BlockList =  std::vector&lt;uint32_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### MSFBuilder() {#a093cb5c774dd6ce97c1a03dc942506c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MSFBuilder::MSFBuilder (uint32_t BlockSize, uint32_t MinBlockCount, bool CanGrow, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addStream() {#af4a2024c4c2cee5d75b2146a5bc544d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint32_t &gt; MSFBuilder::addStream (uint32_t Size, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt; Blocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a stream to the MSF file with the given size, occupying the given list of blocks.</p>


<p>This is useful when reading a MSF file and you want a particular stream to occupy the original set of blocks. If the given blocks are already allocated, or if the number of blocks specified is incorrect for the given stream size, this function will return an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>.</p>


<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#abe111677aa4b3df2bb68f54d4351a72d">llvm::msf::bytesToBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873fa8e40c21d17487b141e798359ee241411">llvm::msf::invalid_format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873fad415f0e30c471dfdd9bc4f827329ef48">llvm::msf::unspecified</a>.</p>

</div>
</div>

### addStream() {#acf419bcec077ae6a195e0dcb3f14e255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint32_t &gt; MSFBuilder::addStream (uint32_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a stream to the MSF file with the given size, occupying any available blocks that the builder decides to use.</p>


<p>This is useful when building a new PDB file from scratch and you don't care what blocks a stream occupies but you just want it to work.</p>


<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msf/#abe111677aa4b3df2bb68f54d4351a72d">llvm::msf::bytesToBlocks</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### commit() {#a6c98d361786661879be283e8abc78dbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; FileBufferByteStream &gt; MSFBuilder::commit (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path, <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout">MSFLayout</a> &amp; Layout)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the MSF layout to the underlying file.</p>

<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/msf/superblock/#ab34f9d84245709af8ed19817a18c59ce">llvm::msf::SuperBlock::BlockMapAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/superblock/#a4792a3763eaca59db556d1c9305741cd">llvm::msf::SuperBlock::BlockSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a249763e47d375bbd4d125417d8d62728">llvm::msf::blockToOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#abe111677aa4b3df2bb68f54d4351a72d">llvm::msf::bytesToBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp/#a39370f41a63dc06ba5dc36059e555bc2">commitFpm</a>, <a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer/#a3a10ce8cad8fee5d6a4c55270866aa05">llvm::FileOutputBuffer::create</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream/#a882f086ce986358c3aff75c298823739">llvm::msf::WritableMappedBlockStream::createDirectoryStream</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout/#ae7cbd23b097e66cbdeccccce85704da6">llvm::msf::MSFLayout::DirectoryBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="#a6fc9c4f6f23dfa2eb0a1b8feb680ac92">generateLayout</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a2a59ea127a795915eef6b3dafabc5991">llvm::msf::getMaxFileSizeFromBlockSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/superblock/#a1426565e730f0681edc1bfec6d59c5d5">llvm::msf::SuperBlock::NumBlocks</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/superblock/#a97837d9ad6f03bda18f25c7079cdb1f5">llvm::msf::SuperBlock::NumDirectoryBytes</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout/#ae81e213efb629de31c7e833c0f1c7e0d">llvm::msf::MSFLayout::SB</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#acc41d0160054e1d9f2a166dbcdf95f37">llvm::BinaryStreamWriter::setOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873fa14762d2711ff5375899e75da45df68b4">llvm::msf::size_overflow_16384</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873facd7aa32ba229e33a15ddca2fede88071">llvm::msf::size_overflow_32768</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873fa9176c1a7eb168fb985b8d06a0b7e71d4">llvm::msf::size_overflow_4096</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873fabbd9a1474b25700e3efa35ba7242b07a">llvm::msf::size_overflow_8192</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873fa3192cccfba56c4afe73c51444ceb8432">llvm::msf::stream_directory_overflow</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout/#afe9788018b09e6d690be1f10d5059e07">llvm::msf::MSFLayout::StreamMap</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/msflayout/#a85d9674028dfa1734478fc520cd979af">llvm::msf::MSFLayout::StreamSizes</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#a1e5febb5c471f88c785519a211871b01">llvm::BinaryStreamWriter::writeArray</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#a344647bc1c4a4b53334296eba145d408">llvm::BinaryStreamWriter::writeInteger</a> and <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#ae73ad246f9f1adc35f0ce49fc089b52a">llvm::BinaryStreamWriter::writeObject</a>.</p>

</div>
</div>

### generateLayout() {#a6fc9c4f6f23dfa2eb0a1b8feb680ac92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; MSFLayout &gt; MSFBuilder::generateLayout ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalize the layout and build the headers and structures that describe the MSF layout and can be written directly to the MSF file.</p>

<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/superblock/#ab34f9d84245709af8ed19817a18c59ce">llvm::msf::SuperBlock::BlockMapAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/superblock/#a4792a3763eaca59db556d1c9305741cd">llvm::msf::SuperBlock::BlockSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#abe111677aa4b3df2bb68f54d4351a72d">llvm::msf::bytesToBlocks</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/superblock/#afeef5352d9e16638b909465adff58aff">llvm::msf::SuperBlock::FreeBlockMapBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#afa98ccc224894a8f32ec9ed84776e709">llvm::msf::Magic</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/superblock/#a6791908bd8cd2e51e4449fe74af55a86">llvm::msf::SuperBlock::MagicBytes</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/superblock/#a1426565e730f0681edc1bfec6d59c5d5">llvm::msf::SuperBlock::NumBlocks</a>, <a href="/web-llvm/docs/api/structs/llvm/msf/superblock/#a97837d9ad6f03bda18f25c7079cdb1f5">llvm::msf::SuperBlock::NumDirectoryBytes</a> and <a href="/web-llvm/docs/api/structs/llvm/msf/superblock/#a4db179fae3660a4a9d9fcbe1b3797e50">llvm::msf::SuperBlock::Unknown1</a>.</p>


<p>Referenced by <a href="#a6c98d361786661879be283e8abc78dbf">commit</a>.</p>

</div>
</div>

### getAllocator() {#a625ab5cfc095eb1bd884cd6191373d89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator &amp; llvm::msf::MSFBuilder::getAllocator ()</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>.</p>

</div>
</div>

### getNumFreeBlocks() {#a56ce626295d844880a5a783965f03b0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t MSFBuilder::getNumFreeBlocks ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the total number of blocks that exist in the MSF file but are not allocated to any valid data.</p>

<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>


<p>Referenced by <a href="#adeea8e76793f05963e0e39ce7302eac0">getNumUsedBlocks</a>.</p>

</div>
</div>

### getNumStreams() {#a1a4c287c2a21d1b468046e9a1c2c65e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t MSFBuilder::getNumStreams ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the total number of streams in the MSF layout.</p>


<p>This should return 1 for every call to <span class="doxyComputerOutput">addStream</span>.</p>


<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>

</div>
</div>

### getNumUsedBlocks() {#adeea8e76793f05963e0e39ce7302eac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t MSFBuilder::getNumUsedBlocks ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the total number of blocks that will be allocated to actual data in this MSF file.</p>

<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>


<p>References <a href="#a56ce626295d844880a5a783965f03b0c">getNumFreeBlocks</a> and <a href="#a51f60aa0d067106219360c6b42b2607f">getTotalBlockCount</a>.</p>

</div>
</div>

### getStreamBlocks() {#a2cb0641d54f97a3c059cf843833efdd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint32_t &gt; MSFBuilder::getStreamBlocks (uint32_t StreamIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the list of blocks allocated to a particular stream.</p>

<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>

</div>
</div>

### getStreamSize() {#a83b60b1263dc7b45aa324789cea86b2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t MSFBuilder::getStreamSize (uint32_t StreamIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the size of a stream by index.</p>

<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>


<p>Referenced by <a href="#a66e6af17e700be6707740c63b7a6a63a">setStreamSize</a>.</p>

</div>
</div>

### getTotalBlockCount() {#a51f60aa0d067106219360c6b42b2607f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t MSFBuilder::getTotalBlockCount ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the total number of blocks in the MSF file.</p>


<p>In practice this is equal to <span class="doxyComputerOutput"><a href="#adeea8e76793f05963e0e39ce7302eac0">getNumUsedBlocks()</a> + <a href="#a56ce626295d844880a5a783965f03b0c">getNumFreeBlocks()</a></span>.</p>


<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>


<p>Referenced by <a href="#adeea8e76793f05963e0e39ce7302eac0">getNumUsedBlocks</a>.</p>

</div>
</div>

### isBlockFree() {#a742ea3d26a3604448c76c64f7a9341ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MSFBuilder::isBlockFree (uint32_t Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether a particular block is allocated or free.</p>

<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>


<p>Referenced by <a href="#a1af64821af285e06f73d4f9bae60b68a">setBlockMapAddr</a> and <a href="#a3da93abaa67b0e96193734c8084fd3ce">setDirectoryBlocksHint</a>.</p>

</div>
</div>

### setBlockMapAddr() {#a1af64821af285e06f73d4f9bae60b68a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MSFBuilder::setBlockMapAddr (uint32_t Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Request the block map to be at a specific block address.</p>


<p>This is useful when editing a MSF and you want the layout to be as stable as possible.</p>


<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873fa87c1c463ae3beee04ac2905a77fa425c">llvm::msf::block_in_use</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873fa30d5ef9a8eb9e9530b28192db6bd88b0">llvm::msf::insufficient_buffer</a>, <a href="#a742ea3d26a3604448c76c64f7a9341ab">isBlockFree</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### setDirectoryBlocksHint() {#a3da93abaa67b0e96193734c8084fd3ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MSFBuilder::setDirectoryBlocksHint (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt; DirBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a742ea3d26a3604448c76c64f7a9341ab">isBlockFree</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873fad415f0e30c471dfdd9bc4f827329ef48">llvm::msf::unspecified</a>.</p>

</div>
</div>

### setFreePageMap() {#a81dc1a77bc37730b480a4156fd73acbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MSFBuilder::setFreePageMap (uint32_t Fpm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>

</div>
</div>

### setStreamSize() {#a66e6af17e700be6707740c63b7a6a63a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MSFBuilder::setStreamSize (uint32_t Idx, uint32_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the size of an existing stream.</p>


<p>This will allocate or deallocate blocks as needed to match the requested size. This can fail if <span class="doxyComputerOutput">CanGrow</span> was set to false when initializing the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder">MSFBuilder</a></span>.</p>


<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#abe111677aa4b3df2bb68f54d4351a72d">llvm::msf::bytesToBlocks</a>, <a href="#a83b60b1263dc7b45aa324789cea86b2e">getStreamSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### setUnknown1() {#af49f1e6ad306896b15614ee4c85dae63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MSFBuilder::setUnknown1 (uint32_t Unk1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### allocateBlocks() {#a95a12b018905ec7f7b7a99999e8bab62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MSFBuilder::allocateBlocks (uint32_t NumBlocks, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; uint32_t &gt; Blocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>

</div>
</div>

### computeDirectoryByteSize() {#a979cc426963344f7b841af01301d0ed2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t MSFBuilder::computeDirectoryByteSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allocator {#a258ef180d477640b7804c6ca0bb1b60c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator&amp; llvm::msf::MSFBuilder::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>.</p>

</div>
</div>

### BlockMapAddr {#a80101416f0cc7f88de50d1977d82cbcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::msf::MSFBuilder::BlockMapAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>.</p>

</div>
</div>

### BlockSize {#abe07639f7d9f837040bc5858d818c22c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::msf::MSFBuilder::BlockSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>.</p>

</div>
</div>

### DirectoryBlocks {#a423efaf47dc3c07eb4b2aec17c6f5d84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint32_t&gt; llvm::msf::MSFBuilder::DirectoryBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>.</p>

</div>
</div>

### FreeBlocks {#a364b2cb46885ac1b86fe2bf51407cc7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::msf::MSFBuilder::FreeBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>.</p>

</div>
</div>

### FreePageMap {#a7ad8f0024a1f06e67770315af7f0d751}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::msf::MSFBuilder::FreePageMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>.</p>

</div>
</div>

### IsGrowable {#a0cda01cfa9f65576a8de8e3f194f792f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::msf::MSFBuilder::IsGrowable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>.</p>

</div>
</div>

### StreamData {#ad6e7c56e1a1f9a34f586546ee8ea4c46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;uint32_t, BlockList&gt; &gt; llvm::msf::MSFBuilder::StreamData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>.</p>

</div>
</div>

### Unknown1 {#ab3736b1b32cca074d0f89f43c99b9f05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::msf::MSFBuilder::Unknown1 = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a8c21485958080726f29f691b4cbfcf00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; MSFBuilder &gt; MSFBuilder::create (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, uint32_t BlockSize, uint32_t MinBlockCount=0, bool CanGrow=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Create a new <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder">MSFBuilder</a></span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BlockSize</td>
<td class="doxyParamItemDescription"><p>The internal block size used by the PDB file. See <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a44e810a6a219aa5149a2830a83068175">isValidBlockSize()</a> for a list of valid block sizes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MinBlockCount</td>
<td class="doxyParamItemDescription"><p>Causes the builder to reserve up front space for at least <span class="doxyComputerOutput">MinBlockCount</span> blocks. This is useful when using <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder">MSFBuilder</a></span> to read an existing MSF that you want to write back out later. The original MSF file's <a href="/web-llvm/docs/api/structs/llvm/msf/superblock">SuperBlock</a> contains the exact number of blocks used by the file, so is a good hint as to how many blocks the new MSF file will contain. Furthermore, it is actually necessary in this case. To preserve stability of the file's layout, it is helpful to try to keep all streams mapped to their original block numbers. To ensure that this is possible, space for all blocks must be allocated beforehand so that streams can be assigned to them.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CanGrow</td>
<td class="doxyParamItemDescription"><p>If true, any operation which results in an attempt to locate a free block when all available blocks have been exhausted will allocate a new block, thereby growing the size of the final MSF file. When false, any such attempt will result in an error. This is especially useful in testing scenarios when you know your test isn't going to do anything to increase the size of the file, so having an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> returned if it were to happen would catch a programming error</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an <a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a> representing whether the operation succeeded or failed. Currently the only way this can fail is if an invalid block size is specified, or <span class="doxyComputerOutput">MinBlockCount</span> does not leave enough room for the mandatory reserved blocks required by an MSF file.</p></dd>
</dl>


<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a038745079fe999b8dd728d61ad0d12b5">llvm::msf::getMinimumBlockCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873fa8e40c21d17487b141e798359ee241411">llvm::msf::invalid_format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a44e810a6a219aa5149a2830a83068175">llvm::msf::isValidBlockSize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfilebuilder/#aa83f310901cbf7688e792d7b1dcbd58f">llvm::pdb::PDBFileBuilder::initialize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfbuilder-h">MSFBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp">MSFBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
