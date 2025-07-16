---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/bitstreamcursor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BitstreamCursor` Class Reference

<p>This represents a position within a bitcode file, implemented on top of a <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor">SimpleBitstreamCursor</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BitstreamCursor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">llvm/Bitstream/BitstreamReader.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor">SimpleBitstreamCursor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This represents a position within a bitstream. <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#aa57605bf1cc8d80678df30809f88b773">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flags that modify the behavior of <a href="#a49c750caac5ed5f8a5333e14ada8d5ed">advance()</a>. <a href="#aa57605bf1cc8d80678df30809f88b773">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d1732732f7044a9a75362b378fc969c">BitstreamCursor</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9577a4c24ce4600953feae25628bbc8c">BitstreamCursor</a> (ArrayRef&lt; uint8_t &gt; BitcodeBytes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02e4fe0b4a8bc9480c0590675fd10190">BitstreamCursor</a> (StringRef BitcodeBytes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51ab610e54cb1561ae658ae2afbd0372">BitstreamCursor</a> (MemoryBufferRef BitcodeBytes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6c806eb300db46115dd871361f232a0">getAbbrevIDWidth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of bits used to encode an abbrev #. <a href="#af6c806eb300db46115dd871361f232a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry">BitstreamEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49c750caac5ed5f8a5333e14ada8d5ed">advance</a> (unsigned Flags=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Advance the current bitstream, returning the next entry in the stream. <a href="#a49c750caac5ed5f8a5333e14ada8d5ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry">BitstreamEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55da7252b067167e5ec22e4456503e6d">advanceSkippingSubblocks</a> (unsigned Flags=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a convenience function for clients that don't expect any subblocks. <a href="#a55da7252b067167e5ec22e4456503e6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6e15164c86a2bbfb1cc735578788810">ReadCode</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f0e780a42d43b287c0b9c4208499369">ReadSubBlockID</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Having read the ENTER_SUBBLOCK code, read the BlockID for the block. <a href="#a2f0e780a42d43b287c0b9c4208499369">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73257c6f5ab8032f22e06c1da0bc109f">SkipBlock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Having read the ENTER_SUBBLOCK abbrevid and a BlockID, skip over the body of this block. <a href="#a73257c6f5ab8032f22e06c1da0bc109f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ced3cd5539e8a620f270f3dbb0c48ab">EnterSubBlock</a> (unsigned BlockID, unsigned *NumWordsP=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Having read the ENTER_SUBBLOCK abbrevid, and enter the block. <a href="#a6ced3cd5539e8a620f270f3dbb0c48ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cb0eff2f0f34b18550402964cdb0b3b">ReadBlockEnd</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrev">BitCodeAbbrev</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cbd9b6a8f22f525a7f126db913ae197">getAbbrev</a> (unsigned AbbrevID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the abbreviation for the specified AbbrevId. <a href="#a5cbd9b6a8f22f525a7f126db913ae197">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b13d5acaf9ffcc5a0f9969888a7db33">skipRecord</a> (unsigned AbbrevID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read the current record and discard it, returning the code for the record. <a href="#a8b13d5acaf9ffcc5a0f9969888a7db33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a677592abe148dbc3de1ec00f3d9904c5">readRecord</a> (unsigned AbbrevID, SmallVectorImpl&lt; uint64_t &gt; &amp;Vals, StringRef *Blob=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18edc8cef7ae17b03b6d4f3ad2cda8b3">ReadAbbrevRecord</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/bitstreamblockinfo">BitstreamBlockInfo</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca82144243a4bbb08d09c0c72d636bd1">ReadBlockInfoBlock</a> (bool ReadBlockInfoNames=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read and return a block info block from the bitstream. <a href="#aca82144243a4bbb08d09c0c72d636bd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61af784d0feec1cac2175f4d3b4aeb6f">setBlockInfo</a> (BitstreamBlockInfo *BI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the block info to be used by this <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> to interpret abbreviated records. <a href="#a61af784d0feec1cac2175f4d3b4aeb6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b2540236df88a84a8b8ea3f7158ae47">AtEndOfStream</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af93d0598951039581a9c4700247d5ee7">canSkipToPos</a> (size_t pos) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3b93b659d4c4f5aeaaedc892916d1bf">fillCurWord</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c1e5edb0f7b3cf4e57e2a4c3933d641">getBitcodeBytes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dfc6241f79207e8c0a44d6c2ffb0801">GetCurrentBitNo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the bit # of the bit we are reading. <a href="#a1dfc6241f79207e8c0a44d6c2ffb0801">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98307e99cc128407dc5fb370e17d8ed0">getCurrentByteNo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66592b9b07a6394cc085a39c1b5c3d0d">getPointerToByte</a> (uint64_t ByteNo, uint64_t NumBytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a pointer into the bitstream at the specified byte offset. <a href="#a66592b9b07a6394cc085a39c1b5c3d0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a003287dcd6e4d73526b117b2709e2347">JumpToBit</a> (uint64_t BitNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset the stream to the specified bit number. <a href="#a003287dcd6e4d73526b117b2709e2347">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor/#a844fc5e45f6ac94e7da1f7f5a94dc604">word_t</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a455d3003d7f58d83850c9f33c259d3bf">Read</a> (unsigned NumBits)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4203a4bfd3d7e5cc1a1e43a76dc4188">ReadVBR</a> (const unsigned NumBits)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24cc6d3ef39604b4b923083583efe349">ReadVBR64</a> (const unsigned NumBits)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25f9ab880898c32f17c238fb8b7fe2b3">SizeInBytes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size of the stream in bytes. <a href="#a25f9ab880898c32f17c238fb8b7fe2b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf41858523e5da924205475408bac982">skipToEnd</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Skip to the end of the file. <a href="#abf41858523e5da924205475408bac982">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab521913a1498449caf16a8ac6056afbc">popBlockScope</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8138a493d1f9f04481c310f4a94700f">CurCodeSize</a> = 2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrev">BitCodeAbbrev</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae161fb8619188f66fc31b95a5125ebbe">CurAbbrevs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abbrevs installed at in this block. <a href="#ae161fb8619188f66fc31b95a5125ebbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; Block, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3f212e0ea7a51a1d0a423ae94660b49">BlockScope</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This tracks the codesize of parent blocks. <a href="#aa3f212e0ea7a51a1d0a423ae94660b49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitstreamblockinfo">BitstreamBlockInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbc3c828a36535a9cf76a3152921e774">BlockInfo</a> = nullptr</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c466b40cd38391f58d202c44f9d04f4">MaxChunkSize</a> = 32</td>
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

<p>This represents a position within a bitcode file, implemented on top of a <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor">SimpleBitstreamCursor</a>.</p>


<p>Unlike iterators, BitstreamCursors are heavy-weight objects that should not be passed by value.</p>


<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#aa57605bf1cc8d80678df30809f88b773}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flags that modify the behavior of <a href="#a49c750caac5ed5f8a5333e14ada8d5ed">advance()</a>.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AF_DontPopBlockAtEnd<a id="aa57605bf1cc8d80678df30809f88b773a5fa70cd4fed0c4307ec20d1add4bd7bd"></a></td>
<td class="doxyEnumItemDescription">If this flag is used, the <a href="#a49c750caac5ed5f8a5333e14ada8d5ed">advance()</a> method does not automatically pop the block scope when the end of a block is reached (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AF_DontAutoprocessAbbrevs<a id="aa57605bf1cc8d80678df30809f88b773a5a16c31409f59d7c3dd21948608d204a"></a></td>
<td class="doxyEnumItemDescription">If this flag is used, abbrev entries are returned just like normal records (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BitstreamCursor() {#a9d1732732f7044a9a75362b378fc969c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitstreamCursor::BitstreamCursor ()</td>
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



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>

</div>
</div>

### BitstreamCursor() {#a9577a4c24ce4600953feae25628bbc8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitstreamCursor::BitstreamCursor (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; BitcodeBytes)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor/#a25f3276dea5a6789ed5c341a4708564c">llvm::SimpleBitstreamCursor::SimpleBitstreamCursor</a>.</p>

</div>
</div>

### BitstreamCursor() {#a02e4fe0b4a8bc9480c0590675fd10190}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitstreamCursor::BitstreamCursor (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> BitcodeBytes)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor/#a25f3276dea5a6789ed5c341a4708564c">llvm::SimpleBitstreamCursor::SimpleBitstreamCursor</a>.</p>

</div>
</div>

### BitstreamCursor() {#a51ab610e54cb1561ae658ae2afbd0372}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitstreamCursor::BitstreamCursor (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> BitcodeBytes)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor/#a25f3276dea5a6789ed5c341a4708564c">llvm::SimpleBitstreamCursor::SimpleBitstreamCursor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### advance() {#a49c750caac5ed5f8a5333e14ada8d5ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; BitstreamEntry &gt; llvm::BitstreamCursor::advance (unsigned Flags=0)</td>
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

<p>Advance the current bitstream, returning the next entry in the stream.</p>

<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>References <a href="#aa57605bf1cc8d80678df30809f88b773a5a16c31409f59d7c3dd21948608d204a">AF_DontAutoprocessAbbrevs</a>, <a href="#aa57605bf1cc8d80678df30809f88b773a5fa70cd4fed0c4307ec20d1add4bd7bd">AF_DontPopBlockAtEnd</a>, <a href="#a0b2540236df88a84a8b8ea3f7158ae47">AtEndOfStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#ab7a76f80792b96a4291e2d1dd1403887a0353c03d98b211f15e10bad35397bf8d">llvm::bitc::DEFINE_ABBREV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#ab7a76f80792b96a4291e2d1dd1403887aee620990aa08180f9ede6fd5c8440620">llvm::bitc::END_BLOCK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#ab7a76f80792b96a4291e2d1dd1403887a8ade579114e64f6e93e5c2335d9790b3">llvm::bitc::ENTER_SUBBLOCK</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#ac90f034e3c9a47ad7714f7fd7576be7b">llvm::BitstreamEntry::getEndBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aea11c6c31db67b3503babeb70b19e596">llvm::BitstreamEntry::getError</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#ab417733d8c007ff045cfcbe674d70dc3">llvm::BitstreamEntry::getRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#a4a36d8b9e3f92d8b06fb189f8817cadd">llvm::BitstreamEntry::getSubBlock</a>, <a href="#a18edc8cef7ae17b03b6d4f3ad2cda8b3">ReadAbbrevRecord</a>, <a href="#a9cb0eff2f0f34b18550402964cdb0b3b">ReadBlockEnd</a>, <a href="#aa6e15164c86a2bbfb1cc735578788810">ReadCode</a>, <a href="#a2f0e780a42d43b287c0b9c4208499369">ReadSubBlockID</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#a55da7252b067167e5ec22e4456503e6d">advanceSkippingSubblocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a73888ec542d14d981f9b9c49c247fa">llvm::getBitcodeFileContents</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule/#a9508697fd741b13841d7563c897e01f3">llvm::BitcodeModule::getLTOInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#aac3e993fa38b2fd4caaacd62e4e152a4">hasObjCCategory</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#ad83a1def9d17dbb6fe203bac539c6f53">isBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a5fca99afcf20fdf62a04843e8825d03f">jumpToValueSymbolTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a9e3af87f6a7494ee71b0cdbf0c4d153c">parseBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ad3dcdf576f07a261c70f7eac121b3eec">readBlobInRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#adfdf631a8d0d417904f24c6ff6d9ed03">readIdentificationBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a9f6235e5cdcd03f0d0dbb533debac0d9">readIdentificationCode</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a42cc3ae15d37346d7ca743801b572770">readTriple</a>.</p>

</div>
</div>

### advanceSkippingSubblocks() {#a55da7252b067167e5ec22e4456503e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; BitstreamEntry &gt; llvm::BitstreamCursor::advanceSkippingSubblocks (unsigned Flags=0)</td>
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

<p>This is a convenience function for clients that don't expect any subblocks.</p>


<p>This just skips over them automatically.</p>


<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>References <a href="#a49c750caac5ed5f8a5333e14ada8d5ed">advance</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#a73257c6f5ab8032f22e06c1da0bc109f">SkipBlock</a> and <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaac45aef6d995e5c810f2824a40fb1e2a">llvm::BitstreamEntry::SubBlock</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a3d0c0fef256a92c13760a52971b805b5">getEnableSplitLTOUnitAndUnifiedFlag</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a62f979fde2fca6e52e8789ff96ad830e">hasObjCCategoryInModule</a>, <a href="#aca82144243a4bbb08d09c0c72d636bd1">ReadBlockInfoBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#afa9c01a1d03b3af4714df3976056d46b">readModuleTriple</a>.</p>

</div>
</div>

### AtEndOfStream() {#a0b2540236df88a84a8b8ea3f7158ae47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SimpleBitstreamCursor::AtEndOfStream ()</td>
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



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>Referenced by <a href="#a49c750caac5ed5f8a5333e14ada8d5ed">advance</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeanalyzer/#add391ff06a593c4b9cb8f05b23882a51">llvm::BitcodeAnalyzer::analyze</a>, <a href="#a6ced3cd5539e8a620f270f3dbb0c48ab">EnterSubBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a9e3af87f6a7494ee71b0cdbf0c4d153c">parseBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a9f6235e5cdcd03f0d0dbb533debac0d9">readIdentificationCode</a> and <a href="#a73257c6f5ab8032f22e06c1da0bc109f">SkipBlock</a>.</p>

</div>
</div>

### canSkipToPos() {#af93d0598951039581a9c4700247d5ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SimpleBitstreamCursor::canSkipToPos (size_t pos)</td>
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



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a95e3a85203eeaf11c26b7161a4557934">hasInvalidBitcodeHeader</a>, <a href="#a677592abe148dbc3de1ec00f3d9904c5">readRecord</a>, <a href="#a73257c6f5ab8032f22e06c1da0bc109f">SkipBlock</a> and <a href="#a8b13d5acaf9ffcc5a0f9969888a7db33">skipRecord</a>.</p>

</div>
</div>

### EnterSubBlock() {#a6ced3cd5539e8a620f270f3dbb0c48ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BitstreamCursor::EnterSubBlock (unsigned BlockID, unsigned * NumWordsP=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Having read the ENTER_SUBBLOCK abbrevid, and enter the block.</p>


<p>Having read the ENTER_SUBBLOCK abbrevid, enter the block.</p>


<p>Declaration at line 515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/bitstream/lib/bitstream/reader/bitstreamreader-cpp">BitstreamReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="#a0b2540236df88a84a8b8ea3f7158ae47">AtEndOfStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a9bbccfa3e710e59b93cc5a5bf8908cf9aa1212eb73e20141e515bcf2f6cba192b">llvm::bitc::BlockSizeWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a9bbccfa3e710e59b93cc5a5bf8908cf9a81e88c5ec4ef96d2e57203df2ca9c7f8">llvm::bitc::CodeLenWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#a3c466b40cd38391f58d202c44f9d04f4">MaxChunkSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a171c000a87a56f9b4c9b4e3f43c5facfa33af1aad55fa136e2ab54409f4b4891f">llvm::Read</a>, <a href="#ae4203a4bfd3d7e5cc1a1e43a76dc4188">ReadVBR</a>, <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor/#a930bfa038e1487c6c2c88488fea17d6a">llvm::SimpleBitstreamCursor::SkipToFourByteBoundary</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a3d0c0fef256a92c13760a52971b805b5">getEnableSplitLTOUnitAndUnifiedFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule/#a9508697fd741b13841d7563c897e01f3">llvm::BitcodeModule::getLTOInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a62f979fde2fca6e52e8789ff96ad830e">hasObjCCategoryInModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a9e3af87f6a7494ee71b0cdbf0c4d153c">parseBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ad3dcdf576f07a261c70f7eac121b3eec">readBlobInRecord</a>, <a href="#aca82144243a4bbb08d09c0c72d636bd1">ReadBlockInfoBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#adfdf631a8d0d417904f24c6ff6d9ed03">readIdentificationBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#afa9c01a1d03b3af4714df3976056d46b">readModuleTriple</a>.</p>

</div>
</div>

### fillCurWord() {#ae3b93b659d4c4f5aeaaedc892916d1bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::SimpleBitstreamCursor::fillCurWord ()</td>
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



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>

</div>
</div>

### getAbbrev() {#a5cbd9b6a8f22f525a7f126db913ae197}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const BitCodeAbbrev * &gt; llvm::BitstreamCursor::getAbbrev (unsigned AbbrevID)</td>
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

<p>Return the abbreviation for the specified AbbrevId.</p>

<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#ab7a76f80792b96a4291e2d1dd1403887a81e1f263b022b7989aa71fb623b62be8">llvm::bitc::FIRST_APPLICATION_ABBREV</a>.</p>


<p>Referenced by <a href="#a677592abe148dbc3de1ec00f3d9904c5">readRecord</a> and <a href="#a8b13d5acaf9ffcc5a0f9969888a7db33">skipRecord</a>.</p>

</div>
</div>

### getAbbrevIDWidth() {#af6c806eb300db46115dd871361f232a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BitstreamCursor::getAbbrevIDWidth ()</td>
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

<p>Return the number of bits used to encode an abbrev #.</p>

<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>

</div>
</div>

### getBitcodeBytes() {#a3c1e5edb0f7b3cf4e57e2a4c3933d641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; llvm::SimpleBitstreamCursor::getBitcodeBytes ()</td>
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



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#aebcf13b2162f23607396fffbf2b6ef7e">analyzeHeader</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3a73888ec542d14d981f9b9c49c247fa">llvm::getBitcodeFileContents</a>.</p>

</div>
</div>

### GetCurrentBitNo() {#a1dfc6241f79207e8c0a44d6c2ffb0801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::SimpleBitstreamCursor::GetCurrentBitNo ()</td>
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

<p>Return the bit # of the bit we are reading.</p>

<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3a73888ec542d14d981f9b9c49c247fa">llvm::getBitcodeFileContents</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#ad83a1def9d17dbb6fe203bac539c6f53">isBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a5fca99afcf20fdf62a04843e8825d03f">jumpToValueSymbolTable</a>, <a href="#a677592abe148dbc3de1ec00f3d9904c5">readRecord</a>, <a href="#a73257c6f5ab8032f22e06c1da0bc109f">SkipBlock</a> and <a href="#a8b13d5acaf9ffcc5a0f9969888a7db33">skipRecord</a>.</p>

</div>
</div>

### getCurrentByteNo() {#a98307e99cc128407dc5fb370e17d8ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::SimpleBitstreamCursor::getCurrentByteNo ()</td>
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



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3a73888ec542d14d981f9b9c49c247fa">llvm::getBitcodeFileContents</a>.</p>

</div>
</div>

### getPointerToByte() {#a66592b9b07a6394cc085a39c1b5c3d0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t * llvm::SimpleBitstreamCursor::getPointerToByte (uint64_t ByteNo, uint64_t NumBytes)</td>
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

<p>Get a pointer into the bitstream at the specified byte offset.</p>

<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>

</div>
</div>

### JumpToBit() {#a003287dcd6e4d73526b117b2709e2347}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::SimpleBitstreamCursor::JumpToBit (uint64_t BitNo)</td>
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

<p>Reset the stream to the specified bit number.</p>

<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule/#a9508697fd741b13841d7563c897e01f3">llvm::BitcodeModule::getLTOInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule/#a8c3f83a2551791b8b6bc2859aa258f02">llvm::BitcodeModule::getSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#ad83a1def9d17dbb6fe203bac539c6f53">isBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a5fca99afcf20fdf62a04843e8825d03f">jumpToValueSymbolTable</a>, <a href="#a677592abe148dbc3de1ec00f3d9904c5">readRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule/#ab6e0b0fddee91c9c5def6803934868b5">llvm::BitcodeModule::readSummary</a>, <a href="#a73257c6f5ab8032f22e06c1da0bc109f">SkipBlock</a> and <a href="#a8b13d5acaf9ffcc5a0f9969888a7db33">skipRecord</a>.</p>

</div>
</div>

### Read() {#a455d3003d7f58d83850c9f33c259d3bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; word_t &gt; llvm::SimpleBitstreamCursor::Read (unsigned NumBits)</td>
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



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a95e3a85203eeaf11c26b7161a4557934">hasInvalidBitcodeHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitstream/lib/bitstream/reader/bitstreamreader-cpp/#a0f3f6e32f057400eb4132cecf266c4c3">readAbbreviatedField</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#aa5668bfbe38566ca0b785a2361a4dcf8">ReadSignature</a>.</p>

</div>
</div>

### ReadAbbrevRecord() {#a18edc8cef7ae17b03b6d4f3ad2cda8b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BitstreamCursor::ReadAbbrevRecord ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>, definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/bitstream/lib/bitstream/reader/bitstreamreader-cpp">BitstreamReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672abfdef4054ace82e3ddb8794bc5ca471c">llvm::BitCodeAbbrevOp::Fixed</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a4bd23dfb57d0c2de37906bcfd6cfa4b0">llvm::BitCodeAbbrevOp::hasEncodingData</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a1e36d5beb226a6e34370d47cf0d76b70">llvm::BitCodeAbbrevOp::isValidEncoding</a>, <a href="#a3c466b40cd38391f58d202c44f9d04f4">MaxChunkSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a171c000a87a56f9b4c9b4e3f43c5facfa33af1aad55fa136e2ab54409f4b4891f">llvm::Read</a>, <a href="#ae4203a4bfd3d7e5cc1a1e43a76dc4188">ReadVBR</a>, <a href="#a24cc6d3ef39604b4b923083583efe349">ReadVBR64</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672ade2457e8051855ad2911d62202458e20">llvm::BitCodeAbbrevOp::VBR</a>.</p>


<p>Referenced by <a href="#a49c750caac5ed5f8a5333e14ada8d5ed">advance</a> and <a href="#aca82144243a4bbb08d09c0c72d636bd1">ReadBlockInfoBlock</a>.</p>

</div>
</div>

### ReadBlockEnd() {#a9cb0eff2f0f34b18550402964cdb0b3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitstreamCursor::ReadBlockEnd ()</td>
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



<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor/#a930bfa038e1487c6c2c88488fea17d6a">llvm::SimpleBitstreamCursor::SkipToFourByteBoundary</a>.</p>


<p>Referenced by <a href="#a49c750caac5ed5f8a5333e14ada8d5ed">advance</a>.</p>

</div>
</div>

### ReadBlockInfoBlock() {#aca82144243a4bbb08d09c0c72d636bd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::optional&lt; BitstreamBlockInfo &gt; &gt; BitstreamCursor::ReadBlockInfoBlock (bool ReadBlockInfoNames=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read and return a block info block from the bitstream.</p>


<p>If an error was encountered, return std::nullopt.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReadBlockInfoNames</td>
<td class="doxyParamItemDescription"><p>Whether to read block/record name information in the BlockInfo block. Only llvm-bcanalyzer uses this.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 568 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>, definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/bitstream/lib/bitstream/reader/bitstreamreader-cpp">BitstreamReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bitstreamblockinfo/blockinfo/#ac3f292fcf27048bdc85257e2f10a8c21">llvm::BitstreamBlockInfo::BlockInfo::Abbrevs</a>, <a href="#a55da7252b067167e5ec22e4456503e6d">advanceSkippingSubblocks</a>, <a href="#aa57605bf1cc8d80678df30809f88b773a5a16c31409f59d7c3dd21948608d204a">AF_DontAutoprocessAbbrevs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a8cd4dd534ba6c31e93a88ca286c4f0e5a9c269366c4dc4af235c9bb24fa46f915">llvm::bitc::BLOCKINFO_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a6860684558cab9835254eba26b2f7963a3ab749cc5d99cccffd681c29da02fa74">llvm::bitc::BLOCKINFO_CODE_BLOCKNAME</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a6860684558cab9835254eba26b2f7963acf72b4b5b2c1c5b1310721a6715ab010">llvm::bitc::BLOCKINFO_CODE_SETBID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a6860684558cab9835254eba26b2f7963aad1225e67df2c8e94135a067eb3f212e">llvm::bitc::BLOCKINFO_CODE_SETRECORDNAME</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#ab7a76f80792b96a4291e2d1dd1403887a0353c03d98b211f15e10bad35397bf8d">llvm::bitc::DEFINE_ABBREV</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea69bcb0a249ff563515ad5c77bc19ebfe">llvm::BitstreamEntry::EndBlock</a>, <a href="#a6ced3cd5539e8a620f270f3dbb0c48ab">EnterSubBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaff48a2349df5a9fe16c80d1d6e32e479">llvm::BitstreamEntry::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamblockinfo/#aa3b3762cda136c6055a813e84957e3a3">llvm::BitstreamBlockInfo::getOrCreateBlockInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamblockinfo/blockinfo/#a1d4c5002a3d66dc60d7924b05a8daf8e">llvm::BitstreamBlockInfo::BlockInfo::Name</a>, <a href="#a18edc8cef7ae17b03b6d4f3ad2cda8b3">ReadAbbrevRecord</a>, <a href="#a677592abe148dbc3de1ec00f3d9904c5">readRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea05d3cc255293715b2712b9bbdfc6011c">llvm::BitstreamEntry::Record</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamblockinfo/blockinfo/#a1abec3aeeb97771e58b8329fa36a5c97">llvm::BitstreamBlockInfo::BlockInfo::RecordNames</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaac45aef6d995e5c810f2824a40fb1e2a">llvm::BitstreamEntry::SubBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitcodeanalyzer/#add391ff06a593c4b9cb8f05b23882a51">llvm::BitcodeAnalyzer::analyze</a>.</p>

</div>
</div>

### ReadCode() {#aa6e15164c86a2bbfb1cc735578788810}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; unsigned &gt; llvm::BitstreamCursor::ReadCode ()</td>
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



<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a171c000a87a56f9b4c9b4e3f43c5facfa33af1aad55fa136e2ab54409f4b4891f">llvm::Read</a>.</p>


<p>Referenced by <a href="#a49c750caac5ed5f8a5333e14ada8d5ed">advance</a> and <a href="/web-llvm/docs/api/classes/llvm/bitcodeanalyzer/#add391ff06a593c4b9cb8f05b23882a51">llvm::BitcodeAnalyzer::analyze</a>.</p>

</div>
</div>

### readRecord() {#a677592abe148dbc3de1ec00f3d9904c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; unsigned &gt; BitstreamCursor::readRecord (unsigned AbbrevID, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Vals, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> * Blob=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>, definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/bitstream/lib/bitstream/reader/bitstreamreader-cpp">BitstreamReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672ac45cef5b964b589fb0741ccc577eaf2c">llvm::BitCodeAbbrevOp::Array</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672a35cc66c7fc730d5572ae851efc3f3f47">llvm::BitCodeAbbrevOp::Blob</a>, <a href="#af93d0598951039581a9c4700247d5ee7">canSkipToPos</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672a5a7811cd25e6ed838a03c49776237b4a">llvm::BitCodeAbbrevOp::Char6</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#adcc0f2fa34728fc1a9d84a554d68b8e5">llvm::BitCodeAbbrevOp::DecodeChar6</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672abfdef4054ace82e3ddb8794bc5ca471c">llvm::BitCodeAbbrevOp::Fixed</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#a5cbd9b6a8f22f525a7f126db913ae197">getAbbrev</a>, <a href="#a1dfc6241f79207e8c0a44d6c2ffb0801">GetCurrentBitNo</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#ada35e1af0081a146ef125b96ffef7c37">llvm::BitCodeAbbrevOp::getEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#af7ce5e3c7c6d19179148ae60888aeae5">llvm::BitCodeAbbrevOp::getEncodingData</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a0bc6f7bc37fa086d3161c2c9094d45f7">llvm::BitCodeAbbrevOp::getLiteralValue</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrev/#a2ca29bb80c1ac943509a6d7e3cf613e2">llvm::BitCodeAbbrev::getNumOperandInfos</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrev/#a99bd594ca88426eba9b6581d9f292766">llvm::BitCodeAbbrev::getOperandInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor/#a131119f53d5ea7341390cf63ca0fcdee">llvm::SimpleBitstreamCursor::getPointerToBit</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a76df75acf1c2d256650e9a1f48ec6841">llvm::BitCodeAbbrevOp::isEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a6f1603f92a466f1b509194b8a81bb126">llvm::BitCodeAbbrevOp::isLiteral</a>, <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor/#ab17fb6242cdd9d2b2f580c0b309bec3f">llvm::SimpleBitstreamCursor::isSizePlausible</a>, <a href="#a003287dcd6e4d73526b117b2709e2347">JumpToBit</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a171c000a87a56f9b4c9b4e3f43c5facfa33af1aad55fa136e2ab54409f4b4891f">llvm::Read</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitstream/lib/bitstream/reader/bitstreamreader-cpp/#a0f3f6e32f057400eb4132cecf266c4c3">readAbbreviatedField</a>, <a href="#ae4203a4bfd3d7e5cc1a1e43a76dc4188">ReadVBR</a>, <a href="#a24cc6d3ef39604b4b923083583efe349">ReadVBR64</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor/#a930bfa038e1487c6c2c88488fea17d6a">llvm::SimpleBitstreamCursor::SkipToFourByteBoundary</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#ab7a76f80792b96a4291e2d1dd1403887a5436567dadf1048914764efde6bcc891">llvm::bitc::UNABBREV_RECORD</a> and <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672ade2457e8051855ad2911d62202458e20">llvm::BitCodeAbbrevOp::VBR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a3d0c0fef256a92c13760a52971b805b5">getEnableSplitLTOUnitAndUnifiedFlag</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a62f979fde2fca6e52e8789ff96ad830e">hasObjCCategoryInModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a614e714a8963e8f854ecac210dde3125">parseRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a384d242ae8d66e4ea84344784426e3a7">parseRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ad3dcdf576f07a261c70f7eac121b3eec">readBlobInRecord</a>, <a href="#aca82144243a4bbb08d09c0c72d636bd1">ReadBlockInfoBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#adfdf631a8d0d417904f24c6ff6d9ed03">readIdentificationBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#afa9c01a1d03b3af4714df3976056d46b">readModuleTriple</a>.</p>

</div>
</div>

### ReadSubBlockID() {#a2f0e780a42d43b287c0b9c4208499369}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; unsigned &gt; llvm::BitstreamCursor::ReadSubBlockID ()</td>
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

<p>Having read the ENTER_SUBBLOCK code, read the BlockID for the block.</p>

<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a9bbccfa3e710e59b93cc5a5bf8908cf9a4ae63f558586ca60ba786b672433ed5b">llvm::bitc::BlockIDWidth</a> and <a href="#ae4203a4bfd3d7e5cc1a1e43a76dc4188">ReadVBR</a>.</p>


<p>Referenced by <a href="#a49c750caac5ed5f8a5333e14ada8d5ed">advance</a> and <a href="/web-llvm/docs/api/classes/llvm/bitcodeanalyzer/#add391ff06a593c4b9cb8f05b23882a51">llvm::BitcodeAnalyzer::analyze</a>.</p>

</div>
</div>

### ReadVBR() {#ae4203a4bfd3d7e5cc1a1e43a76dc4188}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint32_t &gt; llvm::SimpleBitstreamCursor::ReadVBR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned NumBits)</td>
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



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>Referenced by <a href="#a6ced3cd5539e8a620f270f3dbb0c48ab">EnterSubBlock</a>, <a href="#a18edc8cef7ae17b03b6d4f3ad2cda8b3">ReadAbbrevRecord</a>, <a href="#a677592abe148dbc3de1ec00f3d9904c5">readRecord</a>, <a href="#a2f0e780a42d43b287c0b9c4208499369">ReadSubBlockID</a>, <a href="#a73257c6f5ab8032f22e06c1da0bc109f">SkipBlock</a> and <a href="#a8b13d5acaf9ffcc5a0f9969888a7db33">skipRecord</a>.</p>

</div>
</div>

### ReadVBR64() {#a24cc6d3ef39604b4b923083583efe349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; llvm::SimpleBitstreamCursor::ReadVBR64 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned NumBits)</td>
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



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitstream/lib/bitstream/reader/bitstreamreader-cpp/#a0f3f6e32f057400eb4132cecf266c4c3">readAbbreviatedField</a>, <a href="#a18edc8cef7ae17b03b6d4f3ad2cda8b3">ReadAbbrevRecord</a>, <a href="#a677592abe148dbc3de1ec00f3d9904c5">readRecord</a> and <a href="#a8b13d5acaf9ffcc5a0f9969888a7db33">skipRecord</a>.</p>

</div>
</div>

### setBlockInfo() {#a61af784d0feec1cac2175f4d3b4aeb6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamCursor::setBlockInfo (<a href="/web-llvm/docs/api/classes/llvm/bitstreamblockinfo">BitstreamBlockInfo</a> * BI)</td>
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

<p>Set the block info to be used by this <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> to interpret abbreviated records.</p>

<p>Definition at line 572 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereaderbase/#a5a0d125f481ab8e82010f86ab22bc3a3">anonymous{BitcodeReader.cpp}::BitcodeReaderBase::BitcodeReaderBase</a>.</p>

</div>
</div>

### SizeInBytes() {#a25f9ab880898c32f17c238fb8b7fe2b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SimpleBitstreamCursor::SizeInBytes ()</td>
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

<p>Return the size of the stream in bytes.</p>

<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>

</div>
</div>

### SkipBlock() {#a73257c6f5ab8032f22e06c1da0bc109f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::BitstreamCursor::SkipBlock ()</td>
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

<p>Having read the ENTER_SUBBLOCK abbrevid and a BlockID, skip over the body of this block.</p>

<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>References <a href="#a0b2540236df88a84a8b8ea3f7158ae47">AtEndOfStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a9bbccfa3e710e59b93cc5a5bf8908cf9aa1212eb73e20141e515bcf2f6cba192b">llvm::bitc::BlockSizeWidth</a>, <a href="#af93d0598951039581a9c4700247d5ee7">canSkipToPos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a9bbccfa3e710e59b93cc5a5bf8908cf9a81e88c5ec4ef96d2e57203df2ca9c7f8">llvm::bitc::CodeLenWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#a1dfc6241f79207e8c0a44d6c2ffb0801">GetCurrentBitNo</a>, <a href="#a003287dcd6e4d73526b117b2709e2347">JumpToBit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a171c000a87a56f9b4c9b4e3f43c5facfa33af1aad55fa136e2ab54409f4b4891f">llvm::Read</a>, <a href="#ae4203a4bfd3d7e5cc1a1e43a76dc4188">ReadVBR</a>, <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor/#a930bfa038e1487c6c2c88488fea17d6a">llvm::SimpleBitstreamCursor::SkipToFourByteBoundary</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#a55da7252b067167e5ec22e4456503e6d">advanceSkippingSubblocks</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeanalyzer/#add391ff06a593c4b9cb8f05b23882a51">llvm::BitcodeAnalyzer::analyze</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a73888ec542d14d981f9b9c49c247fa">llvm::getBitcodeFileContents</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule/#a9508697fd741b13841d7563c897e01f3">llvm::BitcodeModule::getLTOInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#aac3e993fa38b2fd4caaacd62e4e152a4">hasObjCCategory</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ad3dcdf576f07a261c70f7eac121b3eec">readBlobInRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a9f6235e5cdcd03f0d0dbb533debac0d9">readIdentificationCode</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a42cc3ae15d37346d7ca743801b572770">readTriple</a>.</p>

</div>
</div>

### skipRecord() {#a8b13d5acaf9ffcc5a0f9969888a7db33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; unsigned &gt; BitstreamCursor::skipRecord (unsigned AbbrevID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read the current record and discard it, returning the code for the record.</p>


<p>skipRecord - Read the current record and discard it.</p>


<p>Declaration at line 551 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>, definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/bitstream/lib/bitstream/reader/bitstreamreader-cpp">BitstreamReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672ac45cef5b964b589fb0741ccc577eaf2c">llvm::BitCodeAbbrevOp::Array</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672a35cc66c7fc730d5572ae851efc3f3f47">llvm::BitCodeAbbrevOp::Blob</a>, <a href="#af93d0598951039581a9c4700247d5ee7">canSkipToPos</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672a5a7811cd25e6ed838a03c49776237b4a">llvm::BitCodeAbbrevOp::Char6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672abfdef4054ace82e3ddb8794bc5ca471c">llvm::BitCodeAbbrevOp::Fixed</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#a5cbd9b6a8f22f525a7f126db913ae197">getAbbrev</a>, <a href="#a1dfc6241f79207e8c0a44d6c2ffb0801">GetCurrentBitNo</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#ada35e1af0081a146ef125b96ffef7c37">llvm::BitCodeAbbrevOp::getEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#af7ce5e3c7c6d19179148ae60888aeae5">llvm::BitCodeAbbrevOp::getEncodingData</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a0bc6f7bc37fa086d3161c2c9094d45f7">llvm::BitCodeAbbrevOp::getLiteralValue</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrev/#a2ca29bb80c1ac943509a6d7e3cf613e2">llvm::BitCodeAbbrev::getNumOperandInfos</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrev/#a99bd594ca88426eba9b6581d9f292766">llvm::BitCodeAbbrev::getOperandInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a6f1603f92a466f1b509194b8a81bb126">llvm::BitCodeAbbrevOp::isLiteral</a>, <a href="#a003287dcd6e4d73526b117b2709e2347">JumpToBit</a>, <a href="#a3c466b40cd38391f58d202c44f9d04f4">MaxChunkSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitstream/lib/bitstream/reader/bitstreamreader-cpp/#a0f3f6e32f057400eb4132cecf266c4c3">readAbbreviatedField</a>, <a href="#ae4203a4bfd3d7e5cc1a1e43a76dc4188">ReadVBR</a>, <a href="#a24cc6d3ef39604b4b923083583efe349">ReadVBR64</a>, <a href="#abf41858523e5da924205475408bac982">skipToEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor/#a930bfa038e1487c6c2c88488fea17d6a">llvm::SimpleBitstreamCursor::SkipToFourByteBoundary</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#ab7a76f80792b96a4291e2d1dd1403887a5436567dadf1048914764efde6bcc891">llvm::bitc::UNABBREV_RECORD</a> and <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672ade2457e8051855ad2911d62202458e20">llvm::BitCodeAbbrevOp::VBR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3a73888ec542d14d981f9b9c49c247fa">llvm::getBitcodeFileContents</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule/#a9508697fd741b13841d7563c897e01f3">llvm::BitcodeModule::getLTOInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#aac3e993fa38b2fd4caaacd62e4e152a4">hasObjCCategory</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a9f6235e5cdcd03f0d0dbb533debac0d9">readIdentificationCode</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a42cc3ae15d37346d7ca743801b572770">readTriple</a>.</p>

</div>
</div>

### skipToEnd() {#abf41858523e5da924205475408bac982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SimpleBitstreamCursor::skipToEnd ()</td>
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

<p>Skip to the end of the file.</p>

<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>Referenced by <a href="#a8b13d5acaf9ffcc5a0f9969888a7db33">skipRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### popBlockScope() {#ab521913a1498449caf16a8ac6056afbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitstreamCursor::popBlockScope ()</td>
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



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BlockInfo {#afbc3c828a36535a9cf76a3152921e774}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamBlockInfo* llvm::BitstreamCursor::BlockInfo = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>

</div>
</div>

### BlockScope {#aa3f212e0ea7a51a1d0a423ae94660b49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Block, 8&gt; llvm::BitstreamCursor::BlockScope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This tracks the codesize of parent blocks.</p>

<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>

</div>
</div>

### CurAbbrevs {#ae161fb8619188f66fc31b95a5125ebbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::shared_ptr&lt;BitCodeAbbrev&gt; &gt; llvm::BitstreamCursor::CurAbbrevs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Abbrevs installed at in this block.</p>

<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>

</div>
</div>

### CurCodeSize {#ae8138a493d1f9f04481c310f4a94700f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BitstreamCursor::CurCodeSize = 2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### MaxChunkSize {#a3c466b40cd38391f58d202c44f9d04f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const size_t llvm::BitstreamCursor::MaxChunkSize = 32</td>
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



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a>.</p>


<p>Referenced by <a href="#a6ced3cd5539e8a620f270f3dbb0c48ab">EnterSubBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitstream/lib/bitstream/reader/bitstreamreader-cpp/#a0f3f6e32f057400eb4132cecf266c4c3">readAbbreviatedField</a>, <a href="#a18edc8cef7ae17b03b6d4f3ad2cda8b3">ReadAbbrevRecord</a> and <a href="#a8b13d5acaf9ffcc5a0f9969888a7db33">skipRecord</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">BitstreamReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/bitstream/lib/bitstream/reader/bitstreamreader-cpp">BitstreamReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
