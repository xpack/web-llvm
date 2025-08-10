---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/support/endian
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `endian` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::support::endian { ... }
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/endian/anonymous-sampleprofwriter-cpp-">anonymous{SampleProfWriter.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/support/endian/writer">Writer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adapter to write values to a stream in a particular byte order. <a href="/web-llvm/docs/api/structs/llvm/support/endian/writer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename value_type&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a84722c6bdea9d2aa71fc07cd3d15395c">make_unsigned_t</a> = std::make_unsigned_t&lt; value_type &gt;</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename value_type&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">value_type</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a108ca68c609b3e8c00918a68d26905fa">byte_swap</a> (value_type value, endianness endian)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename value_type, endianness endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">value_type</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7933f338b6f4dd0048d6e53b44e62f8e">byte_swap</a> (value_type value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Swap the bytes of value to match the given endianness. <a href="#a7933f338b6f4dd0048d6e53b44e62f8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename value_type, std::size_t alignment = unaligned&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">value_type</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acfdf941f45bc58470ed8423b98862486">read</a> (const void *memory, endianness endian)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read a value of a particular endianness from memory. <a href="#acfdf941f45bc58470ed8423b98862486">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename value_type, endianness endian, std::size_t alignment&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">value_type</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0d7be50a346ebd1d16326100e443ef2e">read</a> (const void *memory)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">value_type</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae6c58c37f5229487e86ce915afe1ba12">readNext</a> (const CharT *&amp;memory, endianness endian)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read a value of a particular endianness from a buffer, and increment the buffer past that value. <a href="#ae6c58c37f5229487e86ce915afe1ba12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">value_type</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2e051ea385e4be1ae3907f5591f25c0c">readNext</a> (const CharT *&amp;memory)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename value_type, std::size_t alignment = unaligned&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#add1f2d1d972957d22186f4ec92f985f6">write</a> (void *memory, value_type value, endianness endian)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a value to memory with a particular endianness. <a href="#add1f2d1d972957d22186f4ec92f985f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename value_type, endianness endian, std::size_t alignment&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1ecbcb53160a474e80b5e63f1684beca">write</a> (void *memory, value_type value)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26209183e523b5376fb2a2a470db193a">writeNext</a> (CharT *&amp;memory, value_type value, endianness endian)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a value of a particular endianness, and increment the buffer past that value. <a href="#a26209183e523b5376fb2a2a470db193a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8d08f81e828ca1faf922e1d340e879f7">writeNext</a> (CharT *&amp;memory, value_type value)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename value_type, endianness endian, std::size_t alignment&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">value_type</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6d9995bf8da2a0fed6fa31bce97aeebd">readAtBitAlignment</a> (const void *memory, uint64_t startBit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read a value of a particular endianness from memory, for a location that starts at the given bit offset within the first byte. <a href="#a6d9995bf8da2a0fed6fa31bce97aeebd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename value_type, endianness endian, std::size_t alignment&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a60b7cc9c00de00b23725cfa29e75ca3f">writeAtBitAlignment</a> (void *memory, value_type value, uint64_t startBit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a value to memory with a particular endianness, for a location that starts at the given bit offset within the first byte. <a href="#a60b7cc9c00de00b23725cfa29e75ca3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, endianness E&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abdae71ac68500ce8b4b15de1854a1420">read</a> (const void *P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af10ce40e426fd2ff3b12ff8158da378d">read16</a> (const void *P, endianness E)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fda585fbf18128d11d28fa4c5b0ad7d">read32</a> (const void *P, endianness E)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7787225426474d5f50e2f0c4e3c16b1c">read64</a> (const void *P, endianness E)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;endianness E&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a05005b4c506ef063b9ee22dc95e50794">read16</a> (const void *P)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;endianness E&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab204069ac5f55c046931a972164afc52">read32</a> (const void *P)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;endianness E&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8f181956cb05f8e45f1c9d2ef412cfb6">read64</a> (const void *P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17a3ace88f2bb1abf73bf887cdc88e5f">read16le</a> (const void *P)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae865d5defb8785b365f342375822beaa">read32le</a> (const void *P)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fa2f859066acd16820ab083040158c9">read64le</a> (const void *P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb97fc0cbcfdf8bf9926a81fa65060d3">read16be</a> (const void *P)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a225814d4cc0d175373f7ffc59f66b4">read32be</a> (const void *P)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ec2abec8101a7b16ee520e882cc7d34">read64be</a> (const void *P)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, endianness E&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a19751324a6a2a94930b07ad3c9c5b559">write</a> (void *P, T V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a854c0fc7eb648278c0ae83f30a778d90">write16</a> (void *P, uint16_t V, endianness E)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a532f663ee4cfcf65d78284c90327b43c">write32</a> (void *P, uint32_t V, endianness E)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9d1f26310997ed6b5adfa0366c7ded3">write64</a> (void *P, uint64_t V, endianness E)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;endianness E&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a17273f17ee93fe9a1abcc26cc16517c5">write16</a> (void *P, uint16_t V)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;endianness E&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ace2d0c33b1cab1902210397a657db660">write32</a> (void *P, uint32_t V)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;endianness E&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acb96daac1fbf060aca79c995266942c9">write64</a> (void *P, uint64_t V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa78b55e85666182fee9ddb130ef482f4">write16le</a> (void *P, uint16_t V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f05956d010455624c13f5eb2217bc8b">write32le</a> (void *P, uint32_t V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46eee35129898d0466b2af97eacb19ee">write64le</a> (void *P, uint64_t V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a299867e9993a94d2c7247a64516d11fa">write16be</a> (void *P, uint16_t V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71eb44a745361d5437d4a53f9f30dd3d">write32be</a> (void *P, uint32_t V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac43575b832b9b53e2196b8bd503f0f89">write64be</a> (void *P, uint64_t V)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename value_type&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0d40b2f1e459508b598037aca1a32cfc">write_array</a> (raw_ostream &amp;os, ArrayRef&lt; value_type &gt; values, endianness endian)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename value_type&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9dbd69fb838179adf11cb50b3d029cda">write</a> (raw_ostream &amp;os, value_type value, endianness endian)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1517797a7158413251f2ed5ebdd73732">write&lt; float &gt;</a> (raw_ostream &amp;os, float value, endianness endian)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84f59f3d3274675eb656e42e329c2aa8">write&lt; double &gt;</a> (raw_ostream &amp;os, double value, endianness endian)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename value_type&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7ea072a359a717dcb634f1657c3c4c2d">write</a> (raw_ostream &amp;os, ArrayRef&lt; value_type &gt; vals, endianness endian)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename value_type&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afa89cb6b40c35921a3685f1afeb08af0">write</a> (SmallVectorImpl&lt; char &gt; &amp;Out, value_type V, endianness E)</td>
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


<div class="doxySectionDef">

## Typedefs

### make\_unsigned\_t {#a84722c6bdea9d2aa71fc07cd3d15395c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::support::endian::make_unsigned_t =  std::make_unsigned_t&lt;value_type&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### byte\_swap() {#a108ca68c609b3e8c00918a68d26905fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">value_type llvm::support::endian::byte_swap (value_type value, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> endian)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dba8e5f3adee38c8fccc13c1f3be0143796">llvm::native</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ad0e418047a3e04c4fd1fb83325b571ae">llvm::sys::swapByteOrder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hashbuilder/#a2f0e0694a40550ad8156ff89999df152">llvm::HashBuilder&lt; hashbuilder_detail::HashCodeHasher, llvm::endianness::native &gt;::adjustForEndiannessAndAdd</a>, <a href="#a7933f338b6f4dd0048d6e53b44e62f8e">byte_swap</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/binarycoveragereader/#a75f0ba2a248f2f7f77f477bfb8d6dab2">llvm::coverage::BinaryCoverageReader::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a971830cc1546210be8cc86fa568be8d0">llvm::MCStreamer::emitIntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter/#a23334fee66fedcc03e7c74ed4295611c">llvm::gsym::FileWriter::fixup32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/accessors/#a91db0b9fe0c605dd32a2e7b96929c25e">llvm::coverage::accessors::getDataSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/accessors/#ae52b19d4c976e143b7a6d3d2f7d029a3">llvm::coverage::accessors::getFuncHash</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/accessors/#a1de033f4f2e853a4bc81cd3079e72419">llvm::coverage::accessors::getFuncNameRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp/#a7851b0072b1b5a3330cda84355b476d3">loadTestingFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/cgdataostream/#a1d951f57be86b30e864740019b41f0f2">llvm::CGDataOStream::patch</a>, <a href="/web-llvm/docs/api/classes/llvm/profostream/#a52299b07451a31e9fc5a62e305d5fe21">llvm::ProfOStream::patch</a>, <a href="#acfdf941f45bc58470ed8423b98862486">read</a>, <a href="#a6d9995bf8da2a0fed6fa31bce97aeebd">readAtBitAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#aa0afd3ff35e9b67d4c567f6ec5ba2a3e">llvm::M68k::swapWord</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/testingformatwriter/#af47bcd2c269bb9099d476b455b4dc5ed">llvm::coverage::TestingFormatWriter::write</a>, <a href="#a9dbd69fb838179adf11cb50b3d029cda">write</a>, <a href="#afa89cb6b40c35921a3685f1afeb08af0">write</a>, <a href="#add1f2d1d972957d22186f4ec92f985f6">write</a>, <a href="#a0d40b2f1e459508b598037aca1a32cfc">write_array</a>, <a href="#a60b7cc9c00de00b23725cfa29e75ca3f">writeAtBitAlignment</a>, <a href="/web-llvm/docs/api/classes/anonymous-goffobjectwriter-cpp-/goffostream/#a8ca35719bf73f88c6dbfc81f3e720973">anonymous{GOFFObjectWriter.cpp}::GOFFOstream::writebe</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a27e478bd5208561e8eb16ec550509761">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeObject</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter/#a1dcdc350144ba397db6ac8d0f0d871d0">llvm::gsym::FileWriter::writeU16</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter/#a766e343d0ff12c414ffa59f35c1f562d">llvm::gsym::FileWriter::writeU32</a> and <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter/#ae6da8c6b7db557d8f5e8fae0462d89b8">llvm::gsym::FileWriter::writeU64</a>.</p>

</div>
</div>

### byte\_swap() {#a7933f338b6f4dd0048d6e53b44e62f8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type, endianness endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">value_type llvm::support::endian::byte_swap (value_type value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Swap the bytes of value to match the given endianness.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>Reference <a href="#a108ca68c609b3e8c00918a68d26905fa">byte_swap</a>.</p>

</div>
</div>

### read() {#acfdf941f45bc58470ed8423b98862486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type, std::size_t alignment = unaligned&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">value_type llvm::support::endian::read (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * memory, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> endian)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read a value of a particular endianness from memory.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="#a108ca68c609b3e8c00918a68d26905fa">byte_swap</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a2fd576fb00a760ba803c8a171bff051a">LLVM_ASSUME_ALIGNED</a> and <a href="/web-llvm/docs/api/structs/llvm/support/detail/pickalignment/#a660d2c8851fd5bfb532f9f73be4b1ba1a2fecc59ca732d5877341e57d1c746b6e">llvm::support::detail::PickAlignment&lt; T, alignment &gt;::value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a5f02c7d98f9ea50a2abb5c2741c54f23">consume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#aeea27c1cc8038ce807d5e7fb49734f4a">llvm::sys::fs::copy_file_internal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a434621cd1f8f1c0240a47b65ba19ea9b">eat12Bytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a7d8ee6944c8121c49c2a8da4b1695fe7">eat16Bytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#aaff8a7b712c8ea0bb1275e621119e498">eatBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor/#ae3b93b659d4c4f5aeaaedc892916d1bf">llvm::SimpleBitstreamCursor::fillCurWord</a>, <a href="/web-llvm/docs/api/classes/llvm/object/record/#a817de5ee95a965cf8ba4aa8b19bfd8ea">llvm::object::Record::get</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedinstrprofreader/#a2d771e664c8cbfcf4ed1e5a51d052b29">llvm::IndexedInstrProfReader::getFunctionBitmap</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedcodegendatareader/#a3d830a3c802045bb715c15756112ab48">llvm::IndexedCodeGenDataReader::hasFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedinstrprofreader/#a68f0d92916fe31f61b0a65d645f6b856">llvm::IndexedInstrProfReader::hasFormat</a>, <a href="/web-llvm/docs/api/structs/llvm/md5/md5result/#a6cb733f826e3afeef8dea5b75abf2b04">llvm::MD5::MD5Result::high</a>, <a href="/web-llvm/docs/api/structs/llvm/md5/md5result/#a0c78a5721bb5677678f80f9d0589f028">llvm::MD5::MD5Result::low</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ade579376a1cb799b25765b38039915b9">llvm::sys::fs::md5_contents</a>, <a href="/web-llvm/docs/api/structs/llvm/support/detail/packed-endian-specific-integral/ref/#a80d697c06b1706be070893928497434e">llvm::support::detail::packed_endian_specific_integral&lt; ValueType, Endian, Alignment, ALIGN &gt;::ref::operator value_type</a>, <a href="/web-llvm/docs/api/structs/llvm/support/detail/packed-endian-specific-integral/#a5afaeff946abd1866cd97b5541335cbc">llvm::support::detail::packed_endian_specific_integral&lt; T, llvm::endianness::little, support::unaligned &gt;::operator value_type</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/callercalleepairextractor/#a4aa0eb5ce1e5ea9ad6896b809f3f3747">llvm::memprof::CallerCalleePairExtractor::operator()</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/linearcallstackidconverter/#a9e35da6e4781e691207eecc7b4fa48c5">llvm::memprof::LinearCallStackIdConverter::operator()</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/disassembler/webassemblydisassembler-cpp/#ae6a0d5accd0cfdbb19d3201773677035">parseImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp/#a7f3ee08c28f1f56632e9b58a7e90a813">parseStrTabSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp/#a8eb3d9b91beb14411cbb1c3957c5cd49">parseVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/reader/#a4f20ee2ca37e3839b73900aef8e26ac5">llvm::msgpack::Reader::read</a>, <a href="#a0d7be50a346ebd1d16326100e443ef2e">read</a>, <a href="#a05005b4c506ef063b9ee22dc95e50794">read16</a>, <a href="#af10ce40e426fd2ff3b12ff8158da378d">read16</a>, <a href="#ab204069ac5f55c046931a972164afc52">read32</a>, <a href="#a1fda585fbf18128d11d28fa4c5b0ad7d">read32</a>, <a href="#a8f181956cb05f8e45f1c9d2ef412cfb6">read64</a>, <a href="#a7787225426474d5f50e2f0c4e3c16b1c">read64</a>, <a href="#a6d9995bf8da2a0fed6fa31bce97aeebd">readAtBitAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a6bb348b0b716cb9d060ecaef7a49dcc6">llvm::BinaryStreamReader::readInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a79b534a93144bf69a0b42214dc7a62de">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readNameTableSec</a>, <a href="#ae6c58c37f5229487e86ce915afe1ba12">readNext</a> and <a href="/web-llvm/docs/api/classes/anonymous-armdisassembler-cpp-/armdisassembler/#aff1d6eda516ee7a8ce4dd5334cc39586">anonymous{ARMDisassembler.cpp}::ARMDisassembler::suggestBytesToSkip</a>.</p>

</div>
</div>

### read() {#a0d7be50a346ebd1d16326100e443ef2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type, endianness endian, std::size_t alignment&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">value_type llvm::support::endian::read (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * memory)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>Reference <a href="#acfdf941f45bc58470ed8423b98862486">read</a>.</p>

</div>
</div>

### read() {#abdae71ac68500ce8b4b15de1854a1420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, endianness E&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T llvm::support::endian::read (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### read16() {#af10ce40e426fd2ff3b12ff8158da378d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::support::endian::read16 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * P, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> E)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#acfdf941f45bc58470ed8423b98862486">read</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a66aa742680260d77ebab20536c828c17">llvm::AMDGPUDisassembler::decodeKernelDescriptor</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a6e4cc243fb344193485e9e4fe79399c7">llvm::dwarf_linker::parallel::SectionDescriptor::getIntVal</a>, <a href="#adb97fc0cbcfdf8bf9926a81fa65060d3">read16be</a> and <a href="#a17a3ace88f2bb1abf73bf887cdc88e5f">read16le</a>.</p>

</div>
</div>

### read16() {#a05005b4c506ef063b9ee22dc95e50794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;endianness E&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::support::endian::read16 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#acfdf941f45bc58470ed8423b98862486">read</a>.</p>

</div>
</div>

### read16be() {#adb97fc0cbcfdf8bf9926a81fa65060d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::support::endian::read16be (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#af10ce40e426fd2ff3b12ff8158da378d">read16</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/m68kdisassembler/#a148939039bc8201973e8931087aa62a6">M68kDisassembler::getInstruction</a>.</p>

</div>
</div>

### read16le() {#a17a3ace88f2bb1abf73bf887cdc88e5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::support::endian::read16le (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#af10ce40e426fd2ff3b12ff8158da378d">read16</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad00527cce4ac88d76673ec97bc0c57da">llvm::add16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/loongarch/#a9b4c142fe5b9d4d263bef7ff0132a9a3">llvm::jitlink::loongarch::applyFixup</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a25991c233686a63c58cc75b2fc0d9a5f">discoverTypeIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ad53613e81c10091896d73287938ab8be">llvm::object::Archive::ec_symbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a8fa7e42c07f77ffbc093d9f6b80a36af">getEncodedIntegerLength</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskydisassembler-cpp-/cskydisassembler/#ab02ac21009a84db6e0a786c08e2be1b5">anonymous{CSKYDisassembler.cpp}::CSKYDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430disassembler-cpp-/msp430disassembler/#a55019fcf219b7cac44ca62e49a0eeb6a">anonymous{MSP430Disassembler.cpp}::MSP430Disassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/symbol/#aa53f9de42b9d8eeaf9af259f59f4a1be">llvm::object::Archive::Symbol::getMember</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#aa9a744b2382a97226e765258f365a15c">handleFieldList</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#abbb20c80e0c1ab59446de978f898fc1e">handleMethodOverloadList</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a96ae8a0897a355d1c0a04a7eae3f2466">handleOneMethod</a>.</p>

</div>
</div>

### read32() {#a1fda585fbf18128d11d28fa4c5b0ad7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::support::endian::read32 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * P, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> E)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#acfdf941f45bc58470ed8423b98862486">read</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#a5a393f897c1439c03e7ef35e7874a8a1">llvm::jitlink::ppc64::applyFixup</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a6e4cc243fb344193485e9e4fe79399c7">llvm::dwarf_linker::parallel::SectionDescriptor::getIntVal</a>, <a href="#a7a225814d4cc0d175373f7ffc59f66b4">read32be</a>, <a href="#ae865d5defb8785b365f342375822beaa">read32le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a350d2681d6fabc606cb82e4ac365af9e">llvm::jitlink::aarch32::readAddendData</a>, <a href="/web-llvm/docs/api/structs/llvm/jitlink/compactunwindtraits/#a9d9ddd9fe748227f30368cf9bf586ead">llvm::jitlink::CompactUnwindTraits&lt; CRTPImpl, PtrSize &gt;::readEncoding</a>, <a href="/web-llvm/docs/api/structs/llvm/jitlink/compactunwindtraits/#a183445ddb7eddb88ddac8aa02c0db977">llvm::jitlink::CompactUnwindTraits&lt; CRTPImpl, PtrSize &gt;::readPCRangeSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a73b370d004cc941240050b8048fefb7e">verifyNoteSection</a>.</p>

</div>
</div>

### read32() {#ab204069ac5f55c046931a972164afc52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;endianness E&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::support::endian::read32 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#acfdf941f45bc58470ed8423b98862486">read</a>.</p>

</div>
</div>

### read32be() {#a7a225814d4cc0d175373f7ffc59f66b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::support::endian::read32be (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a1fda585fbf18128d11d28fa4c5b0ad7d">read32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a2cc2e3fa12d8c5d0d37310647c9c3a4d">llvm::jitlink::aarch32::applyFixupData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a00c8a16f00462fc9765f5922f3ba761c">llvm::object::doesXCOFFTracebackTableBegin</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a5b923ddd75e27a332230dc648f4443f4">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitXCOFFCInfoSym</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcdisassembler-cpp-/ppcdisassembler/#aae7fc67fba3d73dc2dfe4a44f5e399af">anonymous{PPCDisassembler.cpp}::PPCDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/symbol/#aa53f9de42b9d8eeaf9af259f59f4a1be">llvm::object::Archive::Symbol::getMember</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a1e8893b8d88f459187356143661b34a3">llvm::object::Archive::getNumberOfSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a03e47f68ebb90174f21f2ab9b95d3d28">llvm::object::Archive::symbol_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sha1/#a58395fd08227a05b497a31b8a913645b">llvm::SHA1::update</a> and <a href="/web-llvm/docs/api/classes/llvm/sha256/#a8085b46c447eb45cf02de25f782e97a6">llvm::SHA256::update</a>.</p>

</div>
</div>

### read32le() {#ae865d5defb8785b365f342375822beaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::support::endian::read32le (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a1fda585fbf18128d11d28fa4c5b0ad7d">read32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#aebcf13b2162f23607396fffbf2b6ef7e">analyzeHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/loongarch/#a9b4c142fe5b9d4d263bef7ff0132a9a3">llvm::jitlink::loongarch::applyFixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a2cc2e3fa12d8c5d0d37310647c9c3a4d">llvm::jitlink::aarch32::applyFixupData</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a25991c233686a63c58cc75b2fc0d9a5f">discoverTypeIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ad53613e81c10091896d73287938ab8be">llvm::object::Archive::ec_symbols</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mctargetdesc-cpp-/aarch64mcinstranalysis/#ab74d7f466279e42ef6ac5ba405ef4301">anonymous{AArch64MCTargetDesc.cpp}::AArch64MCInstrAnalysis::findPltEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86-mc/#a9dc8dda7e6f1c6adc7eaaf755f6c27a5">llvm::X86_MC::findX86_64PltEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86-mc/#aa32860b6f507582db22346076bf5caa0">llvm::X86_MC::findX86PltEntries</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdisassembler-cpp-/loongarchdisassembler/#a38b30661f2481e385870d52d8cc9e996">anonymous{LoongArchDisassembler.cpp}::LoongArchDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcdisassembler-cpp-/ppcdisassembler/#aae7fc67fba3d73dc2dfe4a44f5e399af">anonymous{PPCDisassembler.cpp}::PPCDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/symbol/#aa53f9de42b9d8eeaf9af259f59f4a1be">llvm::object::Archive::Symbol::getMember</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/symbol/#a12a9df192d55690ac61ec468d47f14d3">llvm::object::Archive::Symbol::getNext</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a263730f838496be7a6dcc8960c170dac">llvm::object::Archive::getNumberOfECSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a1e8893b8d88f459187356143661b34a3">llvm::object::Archive::getNumberOfSymbols</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#ab36e33dbf8516f7892bd335ff40545e9">handlePointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a00941e59a16ad6eb14e905557a612501">llvm::identify_magic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab89fe4a3f1dc1b523f15e228f00a8574">llvm::or32le</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp/#a5fe3b78dbc5db233a6ba0047e36d34d3">or32le</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a9114640d8c0477c8c9c502e8acd7cbf7">llvm::RuntimeDyldCOFFAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp/#a84247b20b236408869fe2931b9c744be">readUint32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a429e5bc0f0329e5150ed7ad3fbbec0f3">llvm::jitlink::relaxCall</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a35e8cc985018e504a57093b9e0768d00">llvm::RuntimeDyldCOFFAArch64::resolveRelocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac0fd79668dfc1a7627b754817553138f">llvm::SkipBitcodeWrapperHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a03e47f68ebb90174f21f2ab9b95d3d28">llvm::object::Archive::symbol_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe9cd0d362607fa28dff081a7723c9dc">llvm::write32AArch64Addr</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp/#ad4b27c7f2e06cd483392ccd768752653">write32AArch64Addr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad5228b17874209f1777d90a8f5b75287">llvm::write32AArch64Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a80cb40734a5dea76db890881dadf50c1">llvm::write32AArch64Ldr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a1f9fe4a69b646dae9518d991adc12a00">XXH3_len_1to3_128b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a25817408849438429707b1d7c48e5fcd">XXH3_len_1to3_64b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a611ba08ac061c11dce0a30072099ba3c">XXH3_len_4to8_128b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a14f60c710e7d2ab06a8211b0ba1e5306">XXH3_len_4to8_64b</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afd78f9f642d72c07d9082f228a6389db">llvm::xxHash64</a>.</p>

</div>
</div>

### read64() {#a7787225426474d5f50e2f0c4e3c16b1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::support::endian::read64 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * P, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> E)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#acfdf941f45bc58470ed8423b98862486">read</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a6e4cc243fb344193485e9e4fe79399c7">llvm::dwarf_linker::parallel::SectionDescriptor::getIntVal</a>, <a href="/web-llvm/docs/api/classes/llvm/codegencoverage/#af03b9404e0ae4bd9abacbd8cf9221240">llvm::CodeGenCoverage::parse</a>, <a href="#a4ec2abec8101a7b16ee520e882cc7d34">read64be</a>, <a href="#a0fa2f859066acd16820ab083040158c9">read64le</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#a9a83d1d9a3a78b81e6e828a5a0d1ab14">llvm::jitlink::ppc64::readPrefixedInstruction</a>.</p>

</div>
</div>

### read64() {#a8f181956cb05f8e45f1c9d2ef412cfb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;endianness E&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::support::endian::read64 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#acfdf941f45bc58470ed8423b98862486">read</a>.</p>

</div>
</div>

### read64be() {#a4ec2abec8101a7b16ee520e882cc7d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::support::endian::read64be (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a7787225426474d5f50e2f0c4e3c16b1c">read64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a59a90ba7dd76e41d07e6c1cb792e0db3">appendGlobalSymbolTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/symbol/#aa53f9de42b9d8eeaf9af259f59f4a1be">llvm::object::Archive::Symbol::getMember</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a1e8893b8d88f459187356143661b34a3">llvm::object::Archive::getNumberOfSymbols</a> and <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a03e47f68ebb90174f21f2ab9b95d3d28">llvm::object::Archive::symbol_begin</a>.</p>

</div>
</div>

### read64le() {#a0fa2f859066acd16820ab083040158c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::support::endian::read64le (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a7787225426474d5f50e2f0c4e3c16b1c">read64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/loongarch/#a9b4c142fe5b9d4d263bef7ff0132a9a3">llvm::jitlink::loongarch::applyFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/symbol/#aa53f9de42b9d8eeaf9af259f59f4a1be">llvm::object::Archive::Symbol::getMember</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a1e8893b8d88f459187356143661b34a3">llvm::object::Archive::getNumberOfSymbols</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95bf65a141564e084f6fac52c00b6a6d">llvm::getPointerAuthStableSipHash</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a9114640d8c0477c8c9c502e8acd7cbf7">llvm::RuntimeDyldCOFFAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a33a776d038d88cf9261e439f16455d50">llvm::sampleprof::SampleProfileReaderBinary::readSampleContextFromTable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siphash-cpp-/#a159cdb1934bd81019941f78b393b0f0c">anonymous{SipHash.cpp}::siphash</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a03e47f68ebb90174f21f2ab9b95d3d28">llvm::object::Archive::symbol_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a2fa22ae762463bb383e63bd381952344">XXH128_mix32B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#adc9c81b2946609f0260dabe87fea8821">XXH3_accumulate_512_scalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a6f213bbbdebd84c8536a43217f014dbc">XXH3_len_0to16_128b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#adf1ca5feb6e370f2f2d4ceb328c927e6">XXH3_len_0to16_64b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a611ba08ac061c11dce0a30072099ba3c">XXH3_len_4to8_128b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a14f60c710e7d2ab06a8211b0ba1e5306">XXH3_len_4to8_64b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a68128490131d65e06f6066616f80ddf5">XXH3_len_9to16_128b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a00cd136a7e5ebdb8f1920e7353349525">XXH3_len_9to16_64b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a3bdcfa0a87da5bece4e02edac5b0446f">XXH3_mix16B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#add6dbf56c8f88ad835ce0c76e4fa3acc">XXH3_mix2Accs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#ad36d7562c24a3eed4705f092dd82ca23">XXH3_scrambleAcc_scalar</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afd78f9f642d72c07d9082f228a6389db">llvm::xxHash64</a>.</p>

</div>
</div>

### readAtBitAlignment() {#a6d9995bf8da2a0fed6fa31bce97aeebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type, endianness endian, std::size_t alignment&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">value_type llvm::support::endian::readAtBitAlignment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * memory, uint64_t startBit)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read a value of a particular endianness from memory, for a location that starts at the given bit offset within the first byte.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a108ca68c609b3e8c00918a68d26905fa">byte_swap</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a2fd576fb00a760ba803c8a171bff051a">LLVM_ASSUME_ALIGNED</a>, <a href="#acfdf941f45bc58470ed8423b98862486">read</a> and <a href="/web-llvm/docs/api/structs/llvm/support/detail/pickalignment/#a660d2c8851fd5bfb532f9f73be4b1ba1a2fecc59ca732d5877341e57d1c746b6e">llvm::support::detail::PickAlignment&lt; T, alignment &gt;::value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter/#a61b26222d7ecfe417406eec38edba698">llvm::BitstreamWriter::BackpatchByte</a>.</p>

</div>
</div>

### readNext() {#ae6c58c37f5229487e86ce915afe1ba12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type, std::size_t alignment = unaligned, typename CharT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">value_type llvm::support::endian::readNext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> CharT *&amp; memory, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> endian)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read a value of a particular endianness from a buffer, and increment the buffer past that value.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>Reference <a href="#acfdf941f45bc58470ed8423b98862486">read</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/indexedmemprofreader/#a7907bad312db28b49d4a53468ef4d0b1">llvm::IndexedMemProfReader::deserialize</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/frame/#aa13ffe5a20b13508a786c677e504bc8c">llvm::memprof::Frame::deserialize</a>, <a href="/web-llvm/docs/api/structs/llvm/outlinedhashtreerecord/#a2c9fcdfa14dafa4bf635b6bdd88e0c77">llvm::OutlinedHashTreeRecord::deserialize</a>, <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmaprecord/#a46fcb6ab7d4a17276796efb4fd9ef091">llvm::StableFunctionMapRecord::deserialize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acaa5a5ff92b2d28c6d06e8c933f6b532">llvm::memprof::deserializeV2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a2ac7af3ec53f7157147c7537fb810e96">llvm::memprof::deserializeV3</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtable/#a45c3bd7cba6a48f806cccbefbfb61acd">llvm::OnDiskChainedHashTable&lt; Info &gt;::find_hashed</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/callercalleepairextractor/#a4aa0eb5ce1e5ea9ad6896b809f3f3747">llvm::memprof::CallerCalleePairExtractor::operator()</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/linearcallstackidconverter/#a9e35da6e4781e691207eecc7b4fa48c5">llvm::memprof::LinearCallStackIdConverter::operator()</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#aa883a589f91024d0a09d1b3c1821ec85">readBinaryIdsInternal</a>, <a href="/web-llvm/docs/api/classes/llvm/instrproflookuptrait/#ab68d7f02ae82dffc7ab698204d1e7d57">llvm::InstrProfLookupTrait::ReadData</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstacklookuptrait/#ab21c89705e7c11df348a65bd90437bf6">llvm::memprof::CallStackLookupTrait::ReadData</a>, <a href="/web-llvm/docs/api/structs/llvm/indexedcgdata/header/#aa16f090e0884c6c014d968e0307e096b">llvm::IndexedCGData::Header::readFromBuffer</a>, <a href="/web-llvm/docs/api/structs/llvm/indexedinstrprof/header/#ae3e6b1da1e22e5265979f8219a1041c2">llvm::IndexedInstrProf::Header::readFromBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedinstrprofreader/#a172a26066ad6417d3ee4b506f7b441e8">llvm::IndexedInstrProfReader::readHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstacklookuptrait/#aa87729d95357a57c841240dc40ddf45e">llvm::memprof::CallStackLookupTrait::ReadKey</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/framelookuptrait/#af081247821946daf818870ab60b5ba95">llvm::memprof::FrameLookupTrait::ReadKey</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/recordlookuptrait/#a1c2650f73316dd63cb1ed82d5a6b3374">llvm::memprof::RecordLookupTrait::ReadKey</a>, <a href="/web-llvm/docs/api/classes/llvm/instrproflookuptrait/#a9ff73ccd210110a70f0fe33582fc2ca3">llvm::InstrProfLookupTrait::ReadKeyDataLength</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstacklookuptrait/#a6fbe74467a5c190c723902a7e2d04fca">llvm::memprof::CallStackLookupTrait::ReadKeyDataLength</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/framelookuptrait/#aa0952d3c8e5db069adfaa95fed6ba438">llvm::memprof::FrameLookupTrait::ReadKeyDataLength</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/recordlookuptrait/#a9b3692e41f11af5b013d645db414d38b">llvm::memprof::RecordLookupTrait::ReadKeyDataLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/anonymous-memprofreader-cpp-/#a4fd75ce06ed3355a2eca1dc0d0ed858e">llvm::memprof::anonymous{MemProfReader.cpp}::readMemInfoBlocksV3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/anonymous-memprofreader-cpp-/#abcd60615b324b6305d230736760acf69">llvm::memprof::anonymous{MemProfReader.cpp}::readMemInfoBlocksV4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ab97241ec9cdd10c96cce25b23eb23ccb">llvm::memprof::readMemProfSchema</a>, <a href="#a2e051ea385e4be1ae3907f5591f25c0c">readNext</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtable/#a2383821610f41fc1c653b249d3df0aa5">llvm::OnDiskChainedHashTable&lt; Info &gt;::readNumBucketsAndEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/anonymous-memprofreader-cpp-/#a4a29d1708d93d41d894ef8c0c57f0961">llvm::memprof::anonymous{MemProfReader.cpp}::readSegmentEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/anonymous-memprofreader-cpp-/#a96d4f18af7a09618894aac7e2062e33d">llvm::memprof::anonymous{MemProfReader.cpp}::readStackInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a9c60d8b65cd491edeafb796ba396acf8">llvm::sampleprof::SampleProfileReaderBinary::readUnencodedNumber</a>.</p>

</div>
</div>

### readNext() {#a2e051ea385e4be1ae3907f5591f25c0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type, endianness endian, std::size_t alignment = unaligned, typename CharT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">value_type llvm::support::endian::readNext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> CharT *&amp; memory)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>Reference <a href="#ae6c58c37f5229487e86ce915afe1ba12">readNext</a>.</p>

</div>
</div>

### write() {#add1f2d1d972957d22186f4ec92f985f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type, std::size_t alignment = unaligned&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write (void * memory, value_type value, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> endian)</td>
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

<p>Write a value to memory with a particular endianness.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="#a108ca68c609b3e8c00918a68d26905fa">byte_swap</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a2fd576fb00a760ba803c8a171bff051a">LLVM_ASSUME_ALIGNED</a> and <a href="/web-llvm/docs/api/structs/llvm/support/detail/pickalignment/#a660d2c8851fd5bfb532f9f73be4b1ba1a2fecc59ca732d5877341e57d1c746b6e">llvm::support::detail::PickAlignment&lt; T, alignment &gt;::value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bpfasmbackend-cpp-/bpfasmbackend/#a8042e91ea8d66d25a0e45e9f03465395">anonymous{BPFAsmBackend.cpp}::BPFAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a404cacae16324605710710194e08e5ca">llvm::dwarf_linker::parallel::SectionDescriptor::applyIntVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvmccodeemitter-cpp/#a4d70c868bafbd7d427233717f0738f87">emitOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarfframeemitter/#aa8057040c954e677e4172d5b69650b72">llvm::MCDwarfFrameEmitter::encodeAdvanceLoc</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mccodeemitter-cpp-/aarch64mccodeemitter/#a339bb20fead6005cd1cc37f479650617">anonymous{AArch64MCCodeEmitter.cpp}::AArch64MCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumccodeemitter-cpp-/amdgpumccodeemitter/#a57c601613d1b256c59417e392d0575bf">anonymous{AMDGPUMCCodeEmitter.cpp}::AMDGPUMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#ab9fa7a32ab33ce47e1cf86e1489e66f7">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter/#a79052c2401f49c8daef2440833b8f624">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kmccodeemitter-cpp-/m68kmccodeemitter/#a6f71c07949a30c419a392f05c1a7cb6e">anonymous{M68kMCCodeEmitter.cpp}::M68kMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#aef4f1647d634efffc620679419aa92e8">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcmccodeemitter-cpp-/sparcmccodeemitter/#a9887c70467f820ed639080a7edcdabaa">anonymous{SparcMCCodeEmitter.cpp}::SparcMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvmccodeemitter-cpp-/spirvmccodeemitter/#ad0a9e447125532de0cf38be1cf3cc337">anonymous{SPIRVMCCodeEmitter.cpp}::SPIRVMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-vemccodeemitter-cpp-/vemccodeemitter/#a3ed8285051488a52f37e53aa5cb23ac7">anonymous{VEMCCodeEmitter.cpp}::VEMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-lanaimccodeemitter-cpp-/lanaimccodeemitter/#ac982e3d8a19d54e768649683c082289b">llvm::anonymous{LanaiMCCodeEmitter.cpp}::LanaiMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#ada77d1fd6603eff06b4da3c2381b84be">llvm::MipsMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mccodeemitter/#aee7c87a08ee0563a113fb6f25f9205e8">llvm::MSP430MCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#a70ce07677e67d07bc4f1562901d2a35d">llvm::PPCMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#a4d0f1b592033820b9a9ab0758a980593">llvm::HexagonMCCodeEmitter::encodeSingleInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter/#ac6740cbf8bbdd52574f85db63500cd25">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::expandAddTPRel</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#afa2b2e58e0859c0608b6f10a8ad1c79f">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandAddTPRel</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#abb7cbfc91aec970d7d9b935b81f8db66">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandFunctionCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#aa9f55bb589105b8751fa61098690db0b">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandLongCondBr</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#a949f92840302b18bc451d406ddeb09a9">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandTLSDESCCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter/#a3985c640bde224e8ef6b275f9a1e3be7">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::expandToVectorLDI</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a84ea0567e15790f68c421dada011ec5f">llvm::MCContext::getELFSection</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-goffemitter-cpp-/#aef416bbc7f2a09ab58b27d0468ad514a">anonymous{GOFFEmitter.cpp}::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp/#a9f1e7fc31749b7af6e259adf5d1c95ec">operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/structs/llvm/support/detail/packed-endian-specific-integral/ref/#a484477e25aa3c799b28d1e74a03ebf05">llvm::support::detail::packed_endian_specific_integral&lt; ValueType, Endian, Alignment, ALIGN &gt;::ref::operator=</a>, <a href="/web-llvm/docs/api/structs/llvm/support/detail/packed-endian-specific-integral/#a9c4bf84a0ce6a4d46c66a6393d227966">llvm::support::detail::packed_endian_specific_integral&lt; T, llvm::endianness::little, support::unaligned &gt;::operator=</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aaf4c0b08270ecda12b4b183b52b7a2ea">printLE</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#abd062e69c3b1b4a76b873edc1127443a">llvm::LoongArchAsmBackend::relaxDwarfCFA</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a172850f33ba1afc4850ad347040d02a7">llvm::RISCVAsmBackend::relaxDwarfCFA</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a09963de4b3b90f89cf9f9b6f154af6bd">llvm::LoongArchAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a056a7266fa88806c3f88ab217fac6e4e">llvm::RISCVAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator/#a465010c6623882163d1cea22e4cd8836">anonymous{ELFEmitter.cpp}::ContiguousBlobAccumulator::write</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdxbc/psvruntimeinfo/#a8ce05943db5cfcb56bbff62909a08e9c">llvm::mcdxbc::PSVRuntimeInfo::write</a>, <a href="#a7ea072a359a717dcb634f1657c3c4c2d">write</a>, <a href="#a1ecbcb53160a474e80b5e63f1684beca">write</a>, <a href="/web-llvm/docs/api/structs/llvm/support/endian/writer/#a16a69d4248bb11c84536099421ea833b">llvm::support::endian::Writer::write</a>, <a href="/web-llvm/docs/api/structs/llvm/support/endian/writer/#ad1edaf45d75710bd11bc254a371b8e47">llvm::support::endian::Writer::write</a>, <a href="#a17273f17ee93fe9a1abcc26cc16517c5">write16</a>, <a href="#a854c0fc7eb648278c0ae83f30a778d90">write16</a>, <a href="#ace2d0c33b1cab1902210397a657db660">write32</a>, <a href="#a532f663ee4cfcf65d78284c90327b43c">write32</a>, <a href="#acb96daac1fbf060aca79c995266942c9">write64</a>, <a href="#ad9d1f26310997ed6b5adfa0366c7ded3">write64</a>, <a href="#a84f59f3d3274675eb656e42e329c2aa8">write&lt; double &gt;</a>, <a href="#a1517797a7158413251f2ed5ebdd73732">write&lt; float &gt;</a>, <a href="#a60b7cc9c00de00b23725cfa29e75ca3f">writeAtBitAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymccodeemitter-cpp/#a70481303bf794adcd050240bbb7df22f">writeData</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp/#a6ae6757140194100cc316df00b97773f">writeFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a5152bd91da7db6b185d42e839b7a3e82">llvm::RuntimeDyldImpl::writeInt16BE</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a2e2a818eaa1b3883192a5ae226b38a9e">llvm::RuntimeDyldImpl::writeInt32BE</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a423b6eebb04795995f7813b4ed73c00c">llvm::RuntimeDyldImpl::writeInt64BE</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#a344647bc1c4a4b53334296eba145d408">llvm::BinaryStreamWriter::writeInteger</a>, <a href="#a26209183e523b5376fb2a2a470db193a">writeNext</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmbackend-cpp-/amdgpuasmbackend/#ae6be0530b11fb45dd1d82160fee76e76">anonymous{AMDGPUAsmBackend.cpp}::AMDGPUAsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfasmbackend-cpp-/bpfasmbackend/#a76091bf4479abff002d36ef10260f4ee">anonymous{BPFAsmBackend.cpp}::BPFAsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#a4c00c27f8d0dd1c66b06b38458748a29">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmbackend-cpp-/ppcasmbackend/#a7fd7dd3a3c502259ea39a750c70edb94">anonymous{PPCAsmBackend.cpp}::PPCAsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmbackend-cpp-/sparcasmbackend/#a6d313bf87ed584a309f9c5c0ec366fe8">anonymous{SparcAsmBackend.cpp}::SparcAsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmbackend-cpp-/veasmbackend/#a5946dccbb251e12b7fb28281d45c5ead">anonymous{VEAsmBackend.cpp}::VEAsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#acfcc9bf39d2207d4e4e96c88903728fc">llvm::ARMAsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#af452e21aa5eefd6666ed1d0b693f770c">llvm::MachObjectWriter::writeObject</a> and <a href="/web-llvm/docs/api/classes/llvm/wincoffwriter/#a204d14337c246adfd274aac0837c6045">llvm::WinCOFFWriter::writeObject</a>.</p>

</div>
</div>

### write() {#a1ecbcb53160a474e80b5e63f1684beca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type, endianness endian, std::size_t alignment&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write (void * memory, value_type value)</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>Reference <a href="#add1f2d1d972957d22186f4ec92f985f6">write</a>.</p>

</div>
</div>

### write() {#a19751324a6a2a94930b07ad3c9c5b559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, endianness E&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write (void * P, T V)</td>
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



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### write() {#a9dbd69fb838179adf11cb50b3d029cda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; os, value_type value, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> endian)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">EndianStream.h</a>.</p>


<p>References <a href="#a108ca68c609b3e8c00918a68d26905fa">byte_swap</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>

</div>
</div>

### write() {#a7ea072a359a717dcb634f1657c3c4c2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; os, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; value_type &gt; vals, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> endian)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">EndianStream.h</a>.</p>


<p>Reference <a href="#add1f2d1d972957d22186f4ec92f985f6">write</a>.</p>

</div>
</div>

### write() {#afa89cb6b40c35921a3685f1afeb08af0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Out, value_type V, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> E)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">EndianStream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="#a108ca68c609b3e8c00918a68d26905fa">byte_swap</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>.</p>

</div>
</div>

### write\_array() {#a0d40b2f1e459508b598037aca1a32cfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write_array (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; os, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; value_type &gt; values, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> endian)</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">EndianStream.h</a>.</p>


<p>References <a href="#a108ca68c609b3e8c00918a68d26905fa">byte_swap</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcdxbc/psvruntimeinfo/#a8ce05943db5cfcb56bbff62909a08e9c">llvm::mcdxbc::PSVRuntimeInfo::write</a>.</p>

</div>
</div>

### write&lt; double &gt;() {#a84f59f3d3274675eb656e42e329c2aa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write&lt; double &gt; (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; os, double value, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> endian)</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">EndianStream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a> and <a href="#add1f2d1d972957d22186f4ec92f985f6">write</a>.</p>

</div>
</div>

### write&lt; float &gt;() {#a1517797a7158413251f2ed5ebdd73732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write&lt; float &gt; (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; os, float value, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> endian)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">EndianStream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a> and <a href="#add1f2d1d972957d22186f4ec92f985f6">write</a>.</p>

</div>
</div>

### write16() {#a854c0fc7eb648278c0ae83f30a778d90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write16 (void * P, uint16_t V, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> E)</td>
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



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#add1f2d1d972957d22186f4ec92f985f6">write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#a1b090e84230aaa1ea8df579d5ca9efcd">llvm::jitlink::ppc64::relocateHalf16</a>, <a href="#a299867e9993a94d2c7247a64516d11fa">write16be</a> and <a href="#aa78b55e85666182fee9ddb130ef482f4">write16le</a>.</p>

</div>
</div>

### write16() {#a17273f17ee93fe9a1abcc26cc16517c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;endianness E&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write16 (void * P, uint16_t V)</td>
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



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#add1f2d1d972957d22186f4ec92f985f6">write</a>.</p>

</div>
</div>

### write16be() {#a299867e9993a94d2c7247a64516d11fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write16be (void * P, uint16_t V)</td>
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



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a854c0fc7eb648278c0ae83f30a778d90">write16</a>.</p>

</div>
</div>

### write16le() {#aa78b55e85666182fee9ddb130ef482f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write16le (void * P, uint16_t V)</td>
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



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a854c0fc7eb648278c0ae83f30a778d90">write16</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad00527cce4ac88d76673ec97bc0c57da">llvm::add16</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a4e54d7200f6c98e3f58a44763335d5f6">llvm::jitlink::finalizeBlockRelax</a>.</p>

</div>
</div>

### write32() {#a532f663ee4cfcf65d78284c90327b43c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write32 (void * P, uint32_t V, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> E)</td>
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



<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#add1f2d1d972957d22186f4ec92f985f6">write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#a5a393f897c1439c03e7ef35e7874a8a1">llvm::jitlink::ppc64::applyFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#ae3dbe560d017873ff39f9b760e59b0b2">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovprofiler/#a30aa75d2cf30bd6480dac20d756f5e79">anonymous{GCOVProfiling.cpp}::GCOVProfiler::write</a>, <a href="#a71eb44a745361d5437d4a53f9f30dd3d">write32be</a> and <a href="#a4f05956d010455624c13f5eb2217bc8b">write32le</a>.</p>

</div>
</div>

### write32() {#ace2d0c33b1cab1902210397a657db660}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;endianness E&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write32 (void * P, uint32_t V)</td>
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



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#add1f2d1d972957d22186f4ec92f985f6">write</a>.</p>

</div>
</div>

### write32be() {#a71eb44a745361d5437d4a53f9f30dd3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write32be (void * P, uint32_t V)</td>
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



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a532f663ee4cfcf65d78284c90327b43c">write32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bpfasmbackend-cpp-/bpfasmbackend/#a8042e91ea8d66d25a0e45e9f03465395">anonymous{BPFAsmBackend.cpp}::BPFAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a2cc2e3fa12d8c5d0d37310647c9c3a4d">llvm::jitlink::aarch32::applyFixupData</a> and <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#a4c04d3fd68e4c5a63750703a90b54b25">llvm::StringTableBuilder::write</a>.</p>

</div>
</div>

### write32le() {#a4f05956d010455624c13f5eb2217bc8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write32le (void * P, uint32_t V)</td>
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



<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a532f663ee4cfcf65d78284c90327b43c">write32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bpfasmbackend-cpp-/bpfasmbackend/#a8042e91ea8d66d25a0e45e9f03465395">anonymous{BPFAsmBackend.cpp}::BPFAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a2cc2e3fa12d8c5d0d37310647c9c3a4d">llvm::jitlink::aarch32::applyFixupData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#afdcc3a66137dcf1fb3dbdc7adaedc26c">llvm::objcopy::coff::createGnuDebugLinkSectionContents</a>, <a href="/web-llvm/docs/api/classes/llvm/md5/#a5138672d89124f45e2217d8484a59a40">llvm::MD5::final</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a4e54d7200f6c98e3f58a44763335d5f6">llvm::jitlink::finalizeBlockRelax</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/tpihashing-cpp/#aa8fd1bec1979ec6fb2e1d7063569c620">getSourceLineHash</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp/#a5fe3b78dbc5db233a6ba0047e36d34d3">or32le</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-wasmobjectwriter-cpp-/#adad5590d922967efb0f15ac9abfaef4b">anonymous{WasmObjectWriter.cpp}::patchI32</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/wasm/writer/#a0c6b0217a29520ff740cb32952eac94f">llvm::objcopy::wasm::Writer::write</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#a4c04d3fd68e4c5a63750703a90b54b25">llvm::StringTableBuilder::write</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp/#ad4b27c7f2e06cd483392ccd768752653">write32AArch64Addr</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#af1886b67a152078f035dc14be966dc8b">writeInt32ToBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#ade2e0a3aaeed1571f499b1618fefa16f">llvm::object::writeStringTable</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/wasmemitter-cpp/#a199d700abdda200a3c69b29aba3be984">writeUint32</a>.</p>

</div>
</div>

### write64() {#ad9d1f26310997ed6b5adfa0366c7ded3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write64 (void * P, uint64_t V, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> E)</td>
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



<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#add1f2d1d972957d22186f4ec92f985f6">write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#a5a393f897c1439c03e7ef35e7874a8a1">llvm::jitlink::ppc64::applyFixup</a>, <a href="#ac43575b832b9b53e2196b8bd503f0f89">write64be</a>, <a href="#a46eee35129898d0466b2af97eacb19ee">write64le</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#aa0e3eba95ca2e695b6174ee43ddee641">llvm::jitlink::ppc64::writePrefixedInstruction</a>.</p>

</div>
</div>

### write64() {#acb96daac1fbf060aca79c995266942c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;endianness E&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write64 (void * P, uint64_t V)</td>
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



<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#add1f2d1d972957d22186f4ec92f985f6">write</a>.</p>

</div>
</div>

### write64be() {#ac43575b832b9b53e2196b8bd503f0f89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write64be (void * P, uint64_t V)</td>
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



<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#ad9d1f26310997ed6b5adfa0366c7ded3">write64</a>.</p>

</div>
</div>

### write64le() {#a46eee35129898d0466b2af97eacb19ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::write64le (void * P, uint64_t V)</td>
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



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#ad9d1f26310997ed6b5adfa0366c7ded3">write64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#a381769de0e2dcfdc39d00d50ec961c66">emitStrTab</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#accf8f848dfab29077924750f922e320d">emitVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/blockcoverageinference/#a09b2833329e8e77c280ce50d1f6f560e">llvm::BlockCoverageInference::getInstrumentedBlocksHash</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-wasmobjectwriter-cpp-/#a2f9c5a29000c354facddf3731e390d56">anonymous{WasmObjectWriter.cpp}::patchI64</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a79b534a93144bf69a0b42214dc7a62de">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readNameTableSec</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a33a776d038d88cf9261e439f16455d50">llvm::sampleprof::SampleProfileReaderBinary::readSampleContextFromTable</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a35e8cc985018e504a57093b9e0768d00">llvm::RuntimeDyldCOFFAArch64::resolveRelocation</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siphash-cpp-/#a159cdb1934bd81019941f78b393b0f0c">anonymous{SipHash.cpp}::siphash</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/wasmemitter-cpp/#ae902e3aa4f0a43e5771dd72e5c1d7b9e">writeUint64</a>.</p>

</div>
</div>

### writeAtBitAlignment() {#a60b7cc9c00de00b23725cfa29e75ca3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type, endianness endian, std::size_t alignment&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::writeAtBitAlignment (void * memory, value_type value, uint64_t startBit)</td>
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

<p>Write a value to memory with a particular endianness, for a location that starts at the given bit offset within the first byte.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a108ca68c609b3e8c00918a68d26905fa">byte_swap</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a2fd576fb00a760ba803c8a171bff051a">LLVM_ASSUME_ALIGNED</a>, <a href="/web-llvm/docs/api/structs/llvm/support/detail/pickalignment/#a660d2c8851fd5bfb532f9f73be4b1ba1a2fecc59ca732d5877341e57d1c746b6e">llvm::support::detail::PickAlignment&lt; T, alignment &gt;::value</a> and <a href="#add1f2d1d972957d22186f4ec92f985f6">write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter/#a61b26222d7ecfe417406eec38edba698">llvm::BitstreamWriter::BackpatchByte</a>.</p>

</div>
</div>

### writeNext() {#a26209183e523b5376fb2a2a470db193a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type, std::size_t alignment = unaligned, typename CharT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::writeNext (CharT *&amp; memory, value_type value, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> endian)</td>
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

<p>Write a value of a particular endianness, and increment the buffer past that value.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>Reference <a href="#add1f2d1d972957d22186f4ec92f985f6">write</a>.</p>


<p>Referenced by <a href="#a8d08f81e828ca1faf922e1d340e879f7">writeNext</a>.</p>

</div>
</div>

### writeNext() {#a8d08f81e828ca1faf922e1d340e879f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type, endianness endian, std::size_t alignment = unaligned, typename CharT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::writeNext (CharT *&amp; memory, value_type value)</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a>.</p>


<p>Reference <a href="#a26209183e523b5376fb2a2a470db193a">writeNext</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">Endian.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">EndianStream.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
