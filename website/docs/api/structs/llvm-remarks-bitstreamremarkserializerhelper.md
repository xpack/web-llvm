---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/bitstreamremarkserializerhelper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `BitstreamRemarkSerializerHelper` Struct

<p>Serialize the remarks to LLVM bitstream. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::BitstreamRemarkSerializerHelper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">llvm/Remarks/BitstreamRemarkSerializer.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68f9c63688d3f05a8a2c7a11fbe4bb3e">BitstreamRemarkSerializerHelper</a> (BitstreamRemarkContainerType ContainerType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0afe5be66cb8392716a909235216e386">BitstreamRemarkSerializerHelper</a> (const BitstreamRemarkSerializerHelper &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9117d19f409e298e25b9dcebbd789031">BitstreamRemarkSerializerHelper</a> (BitstreamRemarkSerializerHelper &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper">BitstreamRemarkSerializerHelper</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc34c7958b569de9ae40665b757776b">operator=</a> (const BitstreamRemarkSerializerHelper &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper">BitstreamRemarkSerializerHelper</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaad28b1a99a32b2f762a4a589025d31a">operator=</a> (BitstreamRemarkSerializerHelper &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b54a73faa0da69cad6fe56c979f7cb3">setupBlockInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set up the necessary block info entries according to the container type. <a href="#a9b54a73faa0da69cad6fe56c979f7cb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a193cc5f98c50ec99686f7eeb81e8a4ec">setupMetaBlockInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set up the block info for the metadata block. <a href="#a193cc5f98c50ec99686f7eeb81e8a4ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa45dbe007471b57fc449bb1e41458575">setupMetaRemarkVersion</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The remark version in the metadata block. <a href="#aa45dbe007471b57fc449bb1e41458575">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcbea6c51b9a8dea69e898fdf21b2142">emitMetaRemarkVersion</a> (uint64_t RemarkVersion)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad62618367c258fda8b4979e7d1c501b0">setupMetaStrTab</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The strtab in the metadata block. <a href="#ad62618367c258fda8b4979e7d1c501b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad436403de744b37b7517d0a7efd891e3">emitMetaStrTab</a> (const StringTable &amp;StrTab)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a902d073e6121eca59b75706548f013f6">setupMetaExternalFile</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The external file in the metadata block. <a href="#a902d073e6121eca59b75706548f013f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adabdb189a03a69e268428cdf0ea2ff23">emitMetaExternalFile</a> (StringRef Filename)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c2860948a6b6b47e5bf3fa15a1e5311">setupRemarkBlockInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The block info for the remarks block. <a href="#a7c2860948a6b6b47e5bf3fa15a1e5311">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ded13931ceb108ad4de88c551fb3972">emitMetaBlock</a> (uint64_t ContainerVersion, std::optional&lt; uint64_t &gt; RemarkVersion, std::optional&lt; const StringTable * &gt; StrTab=std::nullopt, std::optional&lt; StringRef &gt; Filename=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the metadata for the remarks. <a href="#a8ded13931ceb108ad4de88c551fb3972">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad385e18cefeea744d80d4ab608dfd09d">emitRemarkBlock</a> (const Remark &amp;Remark, StringTable &amp;StrTab)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a remark block. The string table is required. <a href="#ad385e18cefeea744d80d4ab608dfd09d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2ee2b1ce9ba0bb78d12f335d4c98164">flushToStream</a> (raw_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize the writing to <span class="doxyComputerOutput">OS</span>. <a href="#ae2ee2b1ce9ba0bb78d12f335d4c98164">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a507f27edd498d15a2e79b1d83f578f7e">getBuffer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize the writing to a buffer. <a href="#a507f27edd498d15a2e79b1d83f578f7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; char, 1024 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03d339a94efb251b5af9879daf79aa32">Encoded</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Buffer used for encoding the bitstream before writing it to the final stream. <a href="#a03d339a94efb251b5af9879daf79aa32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint64_t, 64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aae6129e9ba5f1e991ba48b23638b63">R</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Buffer used to construct records and pass to the bitstream writer. <a href="#a5aae6129e9ba5f1e991ba48b23638b63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09d80181adf28fef7e6b61a7e8ffee9d">Bitstream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The Bitstream writer. <a href="#a09d80181adf28fef7e6b61a7e8ffee9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1e">BitstreamRemarkContainerType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79698bffe6baad848b6be8f5ac90876f">ContainerType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type of the container we are serializing. <a href="#a79698bffe6baad848b6be8f5ac90876f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe3356506a2ed99b76c81d89c73b83c0">RecordMetaContainerInfoAbbrevID</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abbrev IDs initialized in the block info block. <a href="#afe3356506a2ed99b76c81d89c73b83c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51369e20196226367683c8ca66e76101">RecordMetaRemarkVersionAbbrevID</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40521a21f5e4212a785601ace4f49bf1">RecordMetaStrTabAbbrevID</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a822411770e09f75a5198224a1d1f04f9">RecordMetaExternalFileAbbrevID</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a700d196e2228c4b510b4424f45c2f2dd">RecordRemarkHeaderAbbrevID</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37b9dd59af53fc4056dc326cdbe6f23a">RecordRemarkDebugLocAbbrevID</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f90e6cf1ce5f74340d43ba29e094bb3">RecordRemarkHotnessAbbrevID</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5511e47247a177f18fd9432a7c0e756b">RecordRemarkArgWithDebugLocAbbrevID</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25b15f6a3bbbc0ac3cafcdcae7e9a89d">RecordRemarkArgWithoutDebugLocAbbrevID</a> = 0</td>
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

<p>Serialize the remarks to LLVM bitstream.</p>


<p>This class provides ways to emit remarks in the LLVM bitstream format and its associated metadata.</p>


<ul class="doxyList ">
<li>The separate model: Separate meta: | Container info | String table | External file

Separate remarks: | Container info | <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> version | Remark0 | Remark1 | Remark2 | ...</li>
<li>The standalone model: | Container info | String table | <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> version | Remark0 | Remark1 | Remark2 | ...</li>
</ul>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BitstreamRemarkSerializerHelper() {#a68f9c63688d3f05a8a2c7a11fbe4bb3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamRemarkSerializerHelper::BitstreamRemarkSerializerHelper (<a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1e">BitstreamRemarkContainerType</a> ContainerType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="#a09d80181adf28fef7e6b61a7e8ffee9d">Bitstream</a>, <a href="#a79698bffe6baad848b6be8f5ac90876f">ContainerType</a> and <a href="#a03d339a94efb251b5af9879daf79aa32">Encoded</a>.</p>


<p>Referenced by <a href="#a9117d19f409e298e25b9dcebbd789031">BitstreamRemarkSerializerHelper</a>, <a href="#a0afe5be66cb8392716a909235216e386">BitstreamRemarkSerializerHelper</a>, <a href="#aaad28b1a99a32b2f762a4a589025d31a">operator=</a> and <a href="#a7bc34c7958b569de9ae40665b757776b">operator=</a>.</p>

</div>
</div>

### BitstreamRemarkSerializerHelper() {#a0afe5be66cb8392716a909235216e386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::BitstreamRemarkSerializerHelper::BitstreamRemarkSerializerHelper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper">BitstreamRemarkSerializerHelper</a> &amp;)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Reference <a href="#a68f9c63688d3f05a8a2c7a11fbe4bb3e">BitstreamRemarkSerializerHelper</a>.</p>

</div>
</div>

### BitstreamRemarkSerializerHelper() {#a9117d19f409e298e25b9dcebbd789031}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::BitstreamRemarkSerializerHelper::BitstreamRemarkSerializerHelper (<a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper">BitstreamRemarkSerializerHelper</a> &amp;&amp;)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Reference <a href="#a68f9c63688d3f05a8a2c7a11fbe4bb3e">BitstreamRemarkSerializerHelper</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a7bc34c7958b569de9ae40665b757776b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamRemarkSerializerHelper &amp; llvm::remarks::BitstreamRemarkSerializerHelper::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper">BitstreamRemarkSerializerHelper</a> &amp;)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Reference <a href="#a68f9c63688d3f05a8a2c7a11fbe4bb3e">BitstreamRemarkSerializerHelper</a>.</p>

</div>
</div>

### operator=() {#aaad28b1a99a32b2f762a4a589025d31a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamRemarkSerializerHelper &amp; llvm::remarks::BitstreamRemarkSerializerHelper::operator= (<a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper">BitstreamRemarkSerializerHelper</a> &amp;&amp;)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Reference <a href="#a68f9c63688d3f05a8a2c7a11fbe4bb3e">BitstreamRemarkSerializerHelper</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitMetaBlock() {#a8ded13931ceb108ad4de88c551fb3972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitstreamRemarkSerializerHelper::emitMetaBlock (uint64_t ContainerVersion, std::optional&lt; uint64_t &gt; RemarkVersion, std::optional&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a> * &gt; StrTab=std::nullopt, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Filename=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the metadata for the remarks.</p>

<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a09d80181adf28fef7e6b61a7e8ffee9d">Bitstream</a>, <a href="#a79698bffe6baad848b6be8f5ac90876f">ContainerType</a>, <a href="#adabdb189a03a69e268428cdf0ea2ff23">emitMetaExternalFile</a>, <a href="#abcbea6c51b9a8dea69e898fdf21b2142">emitMetaRemarkVersion</a>, <a href="#ad436403de744b37b7517d0a7efd891e3">emitMetaStrTab</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a30a2d98c5581ada910c6b48afde25d7fa96cbb9f0138fc55670ed8eced6af857d">llvm::remarks::META_BLOCK_ID</a>, <a href="#a5aae6129e9ba5f1e991ba48b23638b63">R</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fab594601a3780245b09d12bc9827eaafa">llvm::remarks::RECORD_META_CONTAINER_INFO</a>, <a href="#afe3356506a2ed99b76c81d89c73b83c0">RecordMetaContainerInfoAbbrevID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1ea2a431092369d68b3ddf5f61852fee1a9">llvm::remarks::SeparateRemarksFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1ea4169738237fc9d6c1463bd5260de6c91">llvm::remarks::SeparateRemarksMeta</a> and <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1ea5c80f101108a356211fcb26b3f83eabb">llvm::remarks::Standalone</a>.</p>

</div>
</div>

### emitMetaExternalFile() {#adabdb189a03a69e268428cdf0ea2ff23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitstreamRemarkSerializerHelper::emitMetaExternalFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>, definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="#a09d80181adf28fef7e6b61a7e8ffee9d">Bitstream</a>, <a href="#a5aae6129e9ba5f1e991ba48b23638b63">R</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83faec8eaa274dde3835551571eb0fe9a985">llvm::remarks::RECORD_META_EXTERNAL_FILE</a> and <a href="#a822411770e09f75a5198224a1d1f04f9">RecordMetaExternalFileAbbrevID</a>.</p>


<p>Referenced by <a href="#a8ded13931ceb108ad4de88c551fb3972">emitMetaBlock</a>.</p>

</div>
</div>

### emitMetaRemarkVersion() {#abcbea6c51b9a8dea69e898fdf21b2142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitstreamRemarkSerializerHelper::emitMetaRemarkVersion (uint64_t RemarkVersion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="#a09d80181adf28fef7e6b61a7e8ffee9d">Bitstream</a>, <a href="#a5aae6129e9ba5f1e991ba48b23638b63">R</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fa3257414078656415dda5988b7a497fbf">llvm::remarks::RECORD_META_REMARK_VERSION</a> and <a href="#a51369e20196226367683c8ca66e76101">RecordMetaRemarkVersionAbbrevID</a>.</p>


<p>Referenced by <a href="#a8ded13931ceb108ad4de88c551fb3972">emitMetaBlock</a>.</p>

</div>
</div>

### emitMetaStrTab() {#ad436403de744b37b7517d0a7efd891e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitstreamRemarkSerializerHelper::emitMetaStrTab (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a> &amp; StrTab)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="#a09d80181adf28fef7e6b61a7e8ffee9d">Bitstream</a>, <a href="#a5aae6129e9ba5f1e991ba48b23638b63">R</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fa67132c432a4ef085fa04581bf9964ee9">llvm::remarks::RECORD_META_STRTAB</a>, <a href="#a40521a21f5e4212a785601ace4f49bf1">RecordMetaStrTabAbbrevID</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable/#a78e58ea3fcbfd1e8b4a5921c850507a0">llvm::remarks::StringTable::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>.</p>


<p>Referenced by <a href="#a8ded13931ceb108ad4de88c551fb3972">emitMetaBlock</a>.</p>

</div>
</div>

### emitRemarkBlock() {#ad385e18cefeea744d80d4ab608dfd09d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitstreamRemarkSerializerHelper::emitRemarkBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &amp; Remark, <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a> &amp; StrTab)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a remark block. The string table is required.</p>

<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable/#ae2e87ab6e6926b438f4d10e5ed1f33d6">llvm::remarks::StringTable::add</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remark/#ad43b86418150167e66360c78b004daae">llvm::remarks::Remark::Args</a>, <a href="#a09d80181adf28fef7e6b61a7e8ffee9d">Bitstream</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remark/#aa22dc5b75c24c27c88fda7c86be9e16a">llvm::remarks::Remark::FunctionName</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remark/#a55696a404b259163add62a3fc346de3b">llvm::remarks::Remark::Hotness</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/argument/#a1659ff309b2d229a210b52d897680ecd">llvm::remarks::Argument::Key</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/argument/#a47da97597ff2702cbce42d0ba7322349">llvm::remarks::Argument::Loc</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remark/#a357123bac089573c87522957e3eb12e3">llvm::remarks::Remark::Loc</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remark/#a35431065aaa52c0d81d719b2468697ed">llvm::remarks::Remark::PassName</a>, <a href="#a5aae6129e9ba5f1e991ba48b23638b63">R</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fab47a0f52d7a068b383bb8efa7bc4c964">llvm::remarks::RECORD_REMARK_ARG_WITH_DEBUGLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83faaf1240d15cbcc04f12c9c7c36d796a7b">llvm::remarks::RECORD_REMARK_ARG_WITHOUT_DEBUGLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fad5259ac7c5361f20e4ee591fb5d1c536">llvm::remarks::RECORD_REMARK_DEBUG_LOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fad48248d7c205d6a54125b2b6c10bb5cb">llvm::remarks::RECORD_REMARK_HEADER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fab81a5e37436c29b092e2a6a6db252d7b">llvm::remarks::RECORD_REMARK_HOTNESS</a>, <a href="#a5511e47247a177f18fd9432a7c0e756b">RecordRemarkArgWithDebugLocAbbrevID</a>, <a href="#a25b15f6a3bbbc0ac3cafcdcae7e9a89d">RecordRemarkArgWithoutDebugLocAbbrevID</a>, <a href="#a37b9dd59af53fc4056dc326cdbe6f23a">RecordRemarkDebugLocAbbrevID</a>, <a href="#a700d196e2228c4b510b4424f45c2f2dd">RecordRemarkHeaderAbbrevID</a>, <a href="#a5f90e6cf1ce5f74340d43ba29e094bb3">RecordRemarkHotnessAbbrevID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a30a2d98c5581ada910c6b48afde25d7fa6bbe4805277c5857c0c4b7abe5253525">llvm::remarks::REMARK_BLOCK_ID</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remark/#a8560e9790fc6522f5ac5ec7e4e3e1f95">llvm::remarks::Remark::RemarkName</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remark/#a241d25fa7a832abc5c8583bc728ec1f1">llvm::remarks::Remark::RemarkType</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/argument/#a43436771a3f98d9984cbd0428bc1b9a3">llvm::remarks::Argument::Val</a>.</p>

</div>
</div>

### flushToStream() {#ae2ee2b1ce9ba0bb78d12f335d4c98164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitstreamRemarkSerializerHelper::flushToStream (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalize the writing to <span class="doxyComputerOutput">OS</span>.</p>

<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>, definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="#a03d339a94efb251b5af9879daf79aa32">Encoded</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>

</div>
</div>

### getBuffer() {#a507f27edd498d15a2e79b1d83f578f7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef BitstreamRemarkSerializerHelper::getBuffer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalize the writing to a buffer.</p>


<p>The contents of the buffer remain valid for the lifetime of the object. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> call to any other function in this class will invalidate the buffer.</p>


<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>, definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>Reference <a href="#a03d339a94efb251b5af9879daf79aa32">Encoded</a>.</p>

</div>
</div>

### setupBlockInfo() {#a9b54a73faa0da69cad6fe56c979f7cb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitstreamRemarkSerializerHelper::setupBlockInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set up the necessary block info entries according to the container type.</p>

<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>, definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="#a09d80181adf28fef7e6b61a7e8ffee9d">Bitstream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#acc638ffc46bd235e04176e244948a300">llvm::remarks::ContainerMagic</a>, <a href="#a79698bffe6baad848b6be8f5ac90876f">ContainerType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1ea2a431092369d68b3ddf5f61852fee1a9">llvm::remarks::SeparateRemarksFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1ea4169738237fc9d6c1463bd5260de6c91">llvm::remarks::SeparateRemarksMeta</a>, <a href="#a193cc5f98c50ec99686f7eeb81e8a4ec">setupMetaBlockInfo</a>, <a href="#a902d073e6121eca59b75706548f013f6">setupMetaExternalFile</a>, <a href="#aa45dbe007471b57fc449bb1e41458575">setupMetaRemarkVersion</a>, <a href="#ad62618367c258fda8b4979e7d1c501b0">setupMetaStrTab</a>, <a href="#a7c2860948a6b6b47e5bf3fa15a1e5311">setupRemarkBlockInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1ea5c80f101108a356211fcb26b3f83eabb">llvm::remarks::Standalone</a>.</p>

</div>
</div>

### setupMetaBlockInfo() {#a193cc5f98c50ec99686f7eeb81e8a4ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitstreamRemarkSerializerHelper::setupMetaBlockInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set up the block info for the metadata block.</p>

<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="#a09d80181adf28fef7e6b61a7e8ffee9d">Bitstream</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672abfdef4054ace82e3ddb8794bc5ca471c">llvm::BitCodeAbbrevOp::Fixed</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp/#a4a2d80c17cbc001470acf77ff302a63b">initBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a30a2d98c5581ada910c6b48afde25d7fa96cbb9f0138fc55670ed8eced6af857d">llvm::remarks::META_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a77f13ca388c6b1db5b3d3bb898c46fdf">llvm::remarks::MetaBlockName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ab466e6828a9a212832f5880878e14d3c">llvm::remarks::MetaContainerInfoName</a>, <a href="#a5aae6129e9ba5f1e991ba48b23638b63">R</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fab594601a3780245b09d12bc9827eaafa">llvm::remarks::RECORD_META_CONTAINER_INFO</a>, <a href="#afe3356506a2ed99b76c81d89c73b83c0">RecordMetaContainerInfoAbbrevID</a> and <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp/#a7b2d5e08689d7bef5b9d6efd82da0aaf">setRecordName</a>.</p>


<p>Referenced by <a href="#a9b54a73faa0da69cad6fe56c979f7cb3">setupBlockInfo</a>.</p>

</div>
</div>

### setupMetaExternalFile() {#a902d073e6121eca59b75706548f013f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitstreamRemarkSerializerHelper::setupMetaExternalFile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The external file in the metadata block.</p>

<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="#a09d80181adf28fef7e6b61a7e8ffee9d">Bitstream</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672a35cc66c7fc730d5572ae851efc3f3f47">llvm::BitCodeAbbrevOp::Blob</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a30a2d98c5581ada910c6b48afde25d7fa96cbb9f0138fc55670ed8eced6af857d">llvm::remarks::META_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#adae35d03ba055f25fc95a9be115921e3">llvm::remarks::MetaExternalFileName</a>, <a href="#a5aae6129e9ba5f1e991ba48b23638b63">R</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83faec8eaa274dde3835551571eb0fe9a985">llvm::remarks::RECORD_META_EXTERNAL_FILE</a>, <a href="#a822411770e09f75a5198224a1d1f04f9">RecordMetaExternalFileAbbrevID</a> and <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp/#a7b2d5e08689d7bef5b9d6efd82da0aaf">setRecordName</a>.</p>


<p>Referenced by <a href="#a9b54a73faa0da69cad6fe56c979f7cb3">setupBlockInfo</a>.</p>

</div>
</div>

### setupMetaRemarkVersion() {#aa45dbe007471b57fc449bb1e41458575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitstreamRemarkSerializerHelper::setupMetaRemarkVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The remark version in the metadata block.</p>

<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="#a09d80181adf28fef7e6b61a7e8ffee9d">Bitstream</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672abfdef4054ace82e3ddb8794bc5ca471c">llvm::BitCodeAbbrevOp::Fixed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a30a2d98c5581ada910c6b48afde25d7fa96cbb9f0138fc55670ed8eced6af857d">llvm::remarks::META_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a58b7d38dc5638703d1dc9ff7cce5872c">llvm::remarks::MetaRemarkVersionName</a>, <a href="#a5aae6129e9ba5f1e991ba48b23638b63">R</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fa3257414078656415dda5988b7a497fbf">llvm::remarks::RECORD_META_REMARK_VERSION</a>, <a href="#a51369e20196226367683c8ca66e76101">RecordMetaRemarkVersionAbbrevID</a> and <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp/#a7b2d5e08689d7bef5b9d6efd82da0aaf">setRecordName</a>.</p>


<p>Referenced by <a href="#a9b54a73faa0da69cad6fe56c979f7cb3">setupBlockInfo</a>.</p>

</div>
</div>

### setupMetaStrTab() {#ad62618367c258fda8b4979e7d1c501b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitstreamRemarkSerializerHelper::setupMetaStrTab ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The strtab in the metadata block.</p>

<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="#a09d80181adf28fef7e6b61a7e8ffee9d">Bitstream</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672a35cc66c7fc730d5572ae851efc3f3f47">llvm::BitCodeAbbrevOp::Blob</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a30a2d98c5581ada910c6b48afde25d7fa96cbb9f0138fc55670ed8eced6af857d">llvm::remarks::META_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a3e5568f39f022fa7181d124f3e54dbb7">llvm::remarks::MetaStrTabName</a>, <a href="#a5aae6129e9ba5f1e991ba48b23638b63">R</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fa67132c432a4ef085fa04581bf9964ee9">llvm::remarks::RECORD_META_STRTAB</a>, <a href="#a40521a21f5e4212a785601ace4f49bf1">RecordMetaStrTabAbbrevID</a> and <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp/#a7b2d5e08689d7bef5b9d6efd82da0aaf">setRecordName</a>.</p>


<p>Referenced by <a href="#a9b54a73faa0da69cad6fe56c979f7cb3">setupBlockInfo</a>.</p>

</div>
</div>

### setupRemarkBlockInfo() {#a7c2860948a6b6b47e5bf3fa15a1e5311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitstreamRemarkSerializerHelper::setupRemarkBlockInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The block info for the remarks block.</p>

<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>, definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="#a09d80181adf28fef7e6b61a7e8ffee9d">Bitstream</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672abfdef4054ace82e3ddb8794bc5ca471c">llvm::BitCodeAbbrevOp::Fixed</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp/#a4a2d80c17cbc001470acf77ff302a63b">initBlock</a>, <a href="#a5aae6129e9ba5f1e991ba48b23638b63">R</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fab47a0f52d7a068b383bb8efa7bc4c964">llvm::remarks::RECORD_REMARK_ARG_WITH_DEBUGLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83faaf1240d15cbcc04f12c9c7c36d796a7b">llvm::remarks::RECORD_REMARK_ARG_WITHOUT_DEBUGLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fad5259ac7c5361f20e4ee591fb5d1c536">llvm::remarks::RECORD_REMARK_DEBUG_LOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fad48248d7c205d6a54125b2b6c10bb5cb">llvm::remarks::RECORD_REMARK_HEADER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeef144afcf67defcc6b922ea2612a83fab81a5e37436c29b092e2a6a6db252d7b">llvm::remarks::RECORD_REMARK_HOTNESS</a>, <a href="#a5511e47247a177f18fd9432a7c0e756b">RecordRemarkArgWithDebugLocAbbrevID</a>, <a href="#a25b15f6a3bbbc0ac3cafcdcae7e9a89d">RecordRemarkArgWithoutDebugLocAbbrevID</a>, <a href="#a37b9dd59af53fc4056dc326cdbe6f23a">RecordRemarkDebugLocAbbrevID</a>, <a href="#a700d196e2228c4b510b4424f45c2f2dd">RecordRemarkHeaderAbbrevID</a>, <a href="#a5f90e6cf1ce5f74340d43ba29e094bb3">RecordRemarkHotnessAbbrevID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a30a2d98c5581ada910c6b48afde25d7fa6bbe4805277c5857c0c4b7abe5253525">llvm::remarks::REMARK_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a33ae48f00781a97a560552ef504e5871">llvm::remarks::RemarkArgWithDebugLocName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae43a4d0711727eb9e7a49062478f46f5">llvm::remarks::RemarkArgWithoutDebugLocName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a0759084cfd0a1be0cb02b8591834e1c8">llvm::remarks::RemarkBlockName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aff0ebf16870352d7db8ce51b03cae117">llvm::remarks::RemarkDebugLocName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ab4d17c35a7e3a10739ced57234d1578c">llvm::remarks::RemarkHeaderName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a2395c19ea0f854bdda64e67246cae15b">llvm::remarks::RemarkHotnessName</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp/#a7b2d5e08689d7bef5b9d6efd82da0aaf">setRecordName</a> and <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672ade2457e8051855ad2911d62202458e20">llvm::BitCodeAbbrevOp::VBR</a>.</p>


<p>Referenced by <a href="#a9b54a73faa0da69cad6fe56c979f7cb3">setupBlockInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Bitstream {#a09d80181adf28fef7e6b61a7e8ffee9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamWriter llvm::remarks::BitstreamRemarkSerializerHelper::Bitstream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The Bitstream writer.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#a68f9c63688d3f05a8a2c7a11fbe4bb3e">BitstreamRemarkSerializerHelper</a>, <a href="#a8ded13931ceb108ad4de88c551fb3972">emitMetaBlock</a>, <a href="#adabdb189a03a69e268428cdf0ea2ff23">emitMetaExternalFile</a>, <a href="#abcbea6c51b9a8dea69e898fdf21b2142">emitMetaRemarkVersion</a>, <a href="#ad436403de744b37b7517d0a7efd891e3">emitMetaStrTab</a>, <a href="#ad385e18cefeea744d80d4ab608dfd09d">emitRemarkBlock</a>, <a href="#a9b54a73faa0da69cad6fe56c979f7cb3">setupBlockInfo</a>, <a href="#a193cc5f98c50ec99686f7eeb81e8a4ec">setupMetaBlockInfo</a>, <a href="#a902d073e6121eca59b75706548f013f6">setupMetaExternalFile</a>, <a href="#aa45dbe007471b57fc449bb1e41458575">setupMetaRemarkVersion</a>, <a href="#ad62618367c258fda8b4979e7d1c501b0">setupMetaStrTab</a> and <a href="#a7c2860948a6b6b47e5bf3fa15a1e5311">setupRemarkBlockInfo</a>.</p>

</div>
</div>

### ContainerType {#a79698bffe6baad848b6be8f5ac90876f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamRemarkContainerType llvm::remarks::BitstreamRemarkSerializerHelper::ContainerType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type of the container we are serializing.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#a68f9c63688d3f05a8a2c7a11fbe4bb3e">BitstreamRemarkSerializerHelper</a>, <a href="#a8ded13931ceb108ad4de88c551fb3972">emitMetaBlock</a> and <a href="#a9b54a73faa0da69cad6fe56c979f7cb3">setupBlockInfo</a>.</p>

</div>
</div>

### Encoded {#a03d339a94efb251b5af9879daf79aa32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;char, 1024&gt; llvm::remarks::BitstreamRemarkSerializerHelper::Encoded</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Buffer used for encoding the bitstream before writing it to the final stream.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#a68f9c63688d3f05a8a2c7a11fbe4bb3e">BitstreamRemarkSerializerHelper</a>, <a href="#ae2ee2b1ce9ba0bb78d12f335d4c98164">flushToStream</a> and <a href="#a507f27edd498d15a2e79b1d83f578f7e">getBuffer</a>.</p>

</div>
</div>

### R {#a5aae6129e9ba5f1e991ba48b23638b63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;uint64_t, 64&gt; llvm::remarks::BitstreamRemarkSerializerHelper::R</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Buffer used to construct records and pass to the bitstream writer.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#a8ded13931ceb108ad4de88c551fb3972">emitMetaBlock</a>, <a href="#adabdb189a03a69e268428cdf0ea2ff23">emitMetaExternalFile</a>, <a href="#abcbea6c51b9a8dea69e898fdf21b2142">emitMetaRemarkVersion</a>, <a href="#ad436403de744b37b7517d0a7efd891e3">emitMetaStrTab</a>, <a href="#ad385e18cefeea744d80d4ab608dfd09d">emitRemarkBlock</a>, <a href="#a193cc5f98c50ec99686f7eeb81e8a4ec">setupMetaBlockInfo</a>, <a href="#a902d073e6121eca59b75706548f013f6">setupMetaExternalFile</a>, <a href="#aa45dbe007471b57fc449bb1e41458575">setupMetaRemarkVersion</a>, <a href="#ad62618367c258fda8b4979e7d1c501b0">setupMetaStrTab</a> and <a href="#a7c2860948a6b6b47e5bf3fa15a1e5311">setupRemarkBlockInfo</a>.</p>

</div>
</div>

### RecordMetaContainerInfoAbbrevID {#afe3356506a2ed99b76c81d89c73b83c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::remarks::BitstreamRemarkSerializerHelper::RecordMetaContainerInfoAbbrevID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Abbrev IDs initialized in the block info block.</p>


<p>Note: depending on the container type, some IDs might be uninitialized. Warning: When adding more abbrev IDs, make sure to update the BlockCodeSize (in the call to EnterSubblock).</p>


<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#a8ded13931ceb108ad4de88c551fb3972">emitMetaBlock</a> and <a href="#a193cc5f98c50ec99686f7eeb81e8a4ec">setupMetaBlockInfo</a>.</p>

</div>
</div>

### RecordMetaExternalFileAbbrevID {#a822411770e09f75a5198224a1d1f04f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::remarks::BitstreamRemarkSerializerHelper::RecordMetaExternalFileAbbrevID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#adabdb189a03a69e268428cdf0ea2ff23">emitMetaExternalFile</a> and <a href="#a902d073e6121eca59b75706548f013f6">setupMetaExternalFile</a>.</p>

</div>
</div>

### RecordMetaRemarkVersionAbbrevID {#a51369e20196226367683c8ca66e76101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::remarks::BitstreamRemarkSerializerHelper::RecordMetaRemarkVersionAbbrevID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#abcbea6c51b9a8dea69e898fdf21b2142">emitMetaRemarkVersion</a> and <a href="#aa45dbe007471b57fc449bb1e41458575">setupMetaRemarkVersion</a>.</p>

</div>
</div>

### RecordMetaStrTabAbbrevID {#a40521a21f5e4212a785601ace4f49bf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::remarks::BitstreamRemarkSerializerHelper::RecordMetaStrTabAbbrevID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#ad436403de744b37b7517d0a7efd891e3">emitMetaStrTab</a> and <a href="#ad62618367c258fda8b4979e7d1c501b0">setupMetaStrTab</a>.</p>

</div>
</div>

### RecordRemarkArgWithDebugLocAbbrevID {#a5511e47247a177f18fd9432a7c0e756b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::remarks::BitstreamRemarkSerializerHelper::RecordRemarkArgWithDebugLocAbbrevID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#ad385e18cefeea744d80d4ab608dfd09d">emitRemarkBlock</a> and <a href="#a7c2860948a6b6b47e5bf3fa15a1e5311">setupRemarkBlockInfo</a>.</p>

</div>
</div>

### RecordRemarkArgWithoutDebugLocAbbrevID {#a25b15f6a3bbbc0ac3cafcdcae7e9a89d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::remarks::BitstreamRemarkSerializerHelper::RecordRemarkArgWithoutDebugLocAbbrevID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#ad385e18cefeea744d80d4ab608dfd09d">emitRemarkBlock</a> and <a href="#a7c2860948a6b6b47e5bf3fa15a1e5311">setupRemarkBlockInfo</a>.</p>

</div>
</div>

### RecordRemarkDebugLocAbbrevID {#a37b9dd59af53fc4056dc326cdbe6f23a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::remarks::BitstreamRemarkSerializerHelper::RecordRemarkDebugLocAbbrevID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#ad385e18cefeea744d80d4ab608dfd09d">emitRemarkBlock</a> and <a href="#a7c2860948a6b6b47e5bf3fa15a1e5311">setupRemarkBlockInfo</a>.</p>

</div>
</div>

### RecordRemarkHeaderAbbrevID {#a700d196e2228c4b510b4424f45c2f2dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::remarks::BitstreamRemarkSerializerHelper::RecordRemarkHeaderAbbrevID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#ad385e18cefeea744d80d4ab608dfd09d">emitRemarkBlock</a> and <a href="#a7c2860948a6b6b47e5bf3fa15a1e5311">setupRemarkBlockInfo</a>.</p>

</div>
</div>

### RecordRemarkHotnessAbbrevID {#a5f90e6cf1ce5f74340d43ba29e094bb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::remarks::BitstreamRemarkSerializerHelper::RecordRemarkHotnessAbbrevID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#ad385e18cefeea744d80d4ab608dfd09d">emitRemarkBlock</a> and <a href="#a7c2860948a6b6b47e5bf3fa15a1e5311">setupRemarkBlockInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
