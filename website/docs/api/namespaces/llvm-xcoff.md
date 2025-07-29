---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/xcoff
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `XCOFF` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::XCOFF { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/xcoff/tracebacktable">TracebackTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/xcoff/csectproperties">CsectProperties</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ReservedSectionNum : int16_t { <a href="#ab57487d0a7c9b4f4003ba302b693df97">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MagicNumber : uint16_t { <a href="#aee8f7e420a81c0a58e0febda6902a6f6">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AuxHeaderFlags64 : uint16_t { <a href="#a05c6b1f3be855ab23f376f499c51e720">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">XCOFFInterpret : uint16_t { <a href="#ad05b784bd1fda8fa92e47f5968bfce29">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FileFlag : uint16_t { <a href="#a22ef67cbe6de5a4072645faaa42eaa5a">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">StorageMappingClass : uint8_t { <a href="#abf0ae26de1e332dddf7d1383bb68502c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Storage Mapping Class definitions. <a href="#abf0ae26de1e332dddf7d1383bb68502c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SectionTypeFlags : int32_t { <a href="#af30dc250fcc756ed99640fe2d10389ae">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DwarfSectionSubtypeFlags : int32_t { <a href="#a0456b0e88222c998e39b69d80338a440">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Values for defining the section subtype of sections of type STYP_DWARF as they would appear in the (signed, 32-bit) s_flags field of the section header structure, contributing to the 16 most significant bits. <a href="#a0456b0e88222c998e39b69d80338a440">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">StorageClass : uint8_t { <a href="#abcfbfa374a3d08b4ee55f054ceb27a70">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SymbolType : uint8_t { <a href="#ae6213556e13de39091f6861f199d7b1f">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">VisibilityType : uint16_t { <a href="#a8a4cb520e5c6a7e39926cfe8dae0b73e">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Values for visibility as they would appear when encoded in the high 4 bits of the 16-bit unsigned n_type field of symbol table entries. <a href="#a8a4cb520e5c6a7e39926cfe8dae0b73e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RelocationType : uint8_t { <a href="#a7309c911b619149e89a825cd78010c8a">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CFileStringType : uint8_t { <a href="#ab91001ecee6942ce950e509c68682796">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CFileLangId : uint8_t { <a href="#a7942e785d649430386d39953d64d1e88">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CFileCpuId : uint8_t { <a href="#a91c69d4341c1d1dd2dabf18fb78e9a5f">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SymbolAuxType : uint8_t { <a href="#a6d134aed42e1f7be67a8dc02c9bd401f">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ExtendedTBTableFlag : uint8_t { <a href="#a74bbed636d573e998e8a4ef4279c3754">...</a> }</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5108aa1d02847a41b154cf255a52348b">getMappingClassString</a> (XCOFF::StorageMappingClass SMC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45337c02ef6094e30bf7aa0e1dc8826c">getRelocationTypeString</a> (XCOFF::RelocationType Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae15aa2110724f82f56c6f702c0d3f80f">getTCPUString</a> (XCOFF::CFileCpuId TCPU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 32 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a470daf78d8ec132289b57490e8e5207f">parseParmsType</a> (uint32_t Value, unsigned FixedParmsNum, unsigned FloatingParmsNum)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 32 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34c118d5f2c660e296a4e2bfdf6ba5f8">parseParmsTypeWithVecInfo</a> (uint32_t Value, unsigned FixedParmsNum, unsigned FloatingParmsNum, unsigned VectorParmsNum)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 32 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65e7fd6df26cd652ac6c015a35ddec17">parseVectorParmsType</a> (uint32_t Value, unsigned ParmsNum)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1dc50da0a38a1295f2fef3a4bc247d7">getNameForTracebackTableLanguageId</a> (TracebackTable::LanguageID LangId)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec7fd3672feec111d150c08c4cf6a69">getExtendedTBTableFlagString</a> (uint8_t Flag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a91c69d4341c1d1dd2dabf18fb78e9a5f">XCOFF::CFileCpuId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2584f7d1fe1c5ab17f8aaba3dafaed66">getCpuID</a> (StringRef CPU)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2ebde8b446e97a42ec08bab42c605e6">FileNamePadSize</a> = 6</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a03aac7419558e56bd606aeab244118">NameSize</a> = 8</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69faad047bdb065d3aa5b6d70c4ac854">AuxFileEntNameSize</a> = 14</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc1993feab64c40d80d24a354e56b1f3">FileHeaderSize32</a> = 20</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5003e35e21ae1096539469b9ce31c998">FileHeaderSize64</a> = 24</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab572f34f978141c97a476cf2b9c47321">AuxFileHeaderSize32</a> = 72</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54f0d697729c046e888f024228a131d9">AuxFileHeaderSize64</a> = 110</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab54ecf9a406b1567b73e4eeb73732c30">AuxFileHeaderSizeShort</a> = 28</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7ebe48b493a2edf775973aa50b5f0f5">SectionHeaderSize32</a> = 40</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c1a4c479a2ec0e5b1255fd3d47f8a67">SectionHeaderSize64</a> = 72</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0cbda82482585d346b65687e2f3a38a">SymbolTableEntrySize</a> = 18</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f792635361c0fbd371a68ae0f171a3">RelocationSerializationSize32</a> = 10</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a476cbe7f235a1f6f83c47ac0f27f98cb">RelocationSerializationSize64</a> = 14</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a50da96dc5db68c648e1dfe7891e695">ExceptionSectionEntrySize32</a> = 6</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27579d1ecd7d6ad37775b2ee530aa989">ExceptionSectionEntrySize64</a> = 10</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4c2e75ac22d396f86f5ed6a29698bd0">RelocOverflow</a> = 65535</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae25ae36fd61e9127012f65bc4a4fe652">AllocRegNo</a> = 31</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4291ff459e43ef7efd865792a0ca68a3">XR_SIGN_INDICATOR_MASK</a> = 0x80</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27ca5b303eeec633f293f39e77aabdc6">XR_FIXUP_INDICATOR_MASK</a> = 0x40</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0709edaad1f22f3b77a92004c31de7ac">XR_BIASED_LENGTH_MASK</a> = 0x3f</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cdb7f94606325a22e75e209055edb0d">VISIBILITY_MASK</a> = 0x7000</td>
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

## Enumerations

### AuxHeaderFlags64 {#a05c6b1f3be855ab23f376f499c51e720}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::XCOFF::AuxHeaderFlags64 : uint16_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHR_SYMTAB<a id="a05c6b1f3be855ab23f376f499c51e720a6860a9f889c8c7814636c01f5e47e441"></a></td>
<td class="doxyEnumItemDescription">At exec time, create shared symbol table for program (main program only) (= 0x8000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FORK_POLICY<a id="a05c6b1f3be855ab23f376f499c51e720a18afafcb35608e88a87fa5d50a7ef577"></a></td>
<td class="doxyEnumItemDescription">Forktree policy specified (main program only) (= 0x4000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FORK_COR<a id="a05c6b1f3be855ab23f376f499c51e720afcef4efe9655c6696eef8aad5dd4bb01"></a></td>
<td class="doxyEnumItemDescription">If _AOUT_FORK_POLICY is set, specify copy-on-reference if this bit is set (= 0x2000)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### CFileCpuId {#a91c69d4341c1d1dd2dabf18fb78e9a5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::XCOFF::CFileCpuId : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_INVALID<a id="a91c69d4341c1d1dd2dabf18fb78e9a5faf0488a9ae52d5efb69b8d9ade83b44f4"></a></td>
<td class="doxyEnumItemDescription">Invalid id - assumes POWER for old objects (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_PPC<a id="a91c69d4341c1d1dd2dabf18fb78e9a5faa18a5011d4dd4def870a4c221b0c17d6"></a></td>
<td class="doxyEnumItemDescription">PowerPC common architecture 32 bit mode (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_PPC64<a id="a91c69d4341c1d1dd2dabf18fb78e9a5fa484d7bc80e749ab715ae30010c307a6d"></a></td>
<td class="doxyEnumItemDescription">PowerPC common architecture 64-bit mode (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_COM<a id="a91c69d4341c1d1dd2dabf18fb78e9a5fa6dffcaea7c8e550d74ab0f42fae0ef9c"></a></td>
<td class="doxyEnumItemDescription">POWER and PowerPC architecture common (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_PWR<a id="a91c69d4341c1d1dd2dabf18fb78e9a5fa6a787eb98f9dbd13e11bb39d0f7ae29a"></a></td>
<td class="doxyEnumItemDescription">POWER common architecture objects (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_ANY<a id="a91c69d4341c1d1dd2dabf18fb78e9a5fa4373c4c8ce6ba7b05f10e73f67391c97"></a></td>
<td class="doxyEnumItemDescription">Mixture of any incompatable POWER and PowerPC architecture implementations (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_601<a id="a91c69d4341c1d1dd2dabf18fb78e9a5faceb0245d75f9a523cfe8d537b9ad070f"></a></td>
<td class="doxyEnumItemDescription">601 implementation of PowerPC architecture (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_603<a id="a91c69d4341c1d1dd2dabf18fb78e9a5fa9dde7b9eec34e97ce6ea0dc698c1682a"></a></td>
<td class="doxyEnumItemDescription">603 implementation of PowerPC architecture (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_604<a id="a91c69d4341c1d1dd2dabf18fb78e9a5fa30ff25aa56881c1ca0e425d2be2a622e"></a></td>
<td class="doxyEnumItemDescription">604 implementation of PowerPC architecture (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_620<a id="a91c69d4341c1d1dd2dabf18fb78e9a5fac4652524a18555e53587809b2b8674c0"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_A35<a id="a91c69d4341c1d1dd2dabf18fb78e9a5fa0903f1d63f0597b172aa93ef5fa91c55"></a></td>
<td class="doxyEnumItemDescription"> (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_PWR5<a id="a91c69d4341c1d1dd2dabf18fb78e9a5fab33654326d121d31b9719daf5634437e"></a></td>
<td class="doxyEnumItemDescription"> (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_970<a id="a91c69d4341c1d1dd2dabf18fb78e9a5fada4e56e8301f5d713f1b94395c96abd5"></a></td>
<td class="doxyEnumItemDescription"> (= 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_PWR6<a id="a91c69d4341c1d1dd2dabf18fb78e9a5faa23345d390b808814455a7d9927547dd"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_PWR5X<a id="a91c69d4341c1d1dd2dabf18fb78e9a5fa6ab1a2baa7b9b5b1cb1dc767e876cf9e"></a></td>
<td class="doxyEnumItemDescription"> (= 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_PWR6E<a id="a91c69d4341c1d1dd2dabf18fb78e9a5fa06923533627c876e0eb59bfd4d6b2def"></a></td>
<td class="doxyEnumItemDescription"> (= 23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_PWR7<a id="a91c69d4341c1d1dd2dabf18fb78e9a5fa34cac65f144da4d6cb79ee5ff74487b9"></a></td>
<td class="doxyEnumItemDescription"> (= 24)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_PWR8<a id="a91c69d4341c1d1dd2dabf18fb78e9a5fa428e0ff16cb3c14f6645fc43010f2e35"></a></td>
<td class="doxyEnumItemDescription"> (= 25)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_PWR9<a id="a91c69d4341c1d1dd2dabf18fb78e9a5fa087e289837b644ec1710ba50b325c22a"></a></td>
<td class="doxyEnumItemDescription"> (= 26)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_PWR10<a id="a91c69d4341c1d1dd2dabf18fb78e9a5fa517defe929b8d7279ffe5a4a62d49ae0"></a></td>
<td class="doxyEnumItemDescription"> (= 27)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCPU_PWRX<a id="a91c69d4341c1d1dd2dabf18fb78e9a5fa12f976d4603cb5674038fe90d2566c46"></a></td>
<td class="doxyEnumItemDescription">RS2 implementation of POWER architecture (= 224)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### CFileLangId {#a7942e785d649430386d39953d64d1e88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::XCOFF::CFileLangId : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TB_C<a id="a7942e785d649430386d39953d64d1e88ae4766f7a6bb3d7d995ea5cd0e3b6bb77"></a></td>
<td class="doxyEnumItemDescription">C language (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TB_Fortran<a id="a7942e785d649430386d39953d64d1e88a85c0f9c38aaebc6319d9feb323fd4410"></a></td>
<td class="doxyEnumItemDescription">Fortran language (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TB_CPLUSPLUS<a id="a7942e785d649430386d39953d64d1e88af2a6e014011f19976fbc47fd88d18adf"></a></td>
<td class="doxyEnumItemDescription">C++ language (= 9)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### CFileStringType {#ab91001ecee6942ce950e509c68682796}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::XCOFF::CFileStringType : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XFT_FN<a id="ab91001ecee6942ce950e509c68682796a21845567b9c0530bf3824048bd393936"></a></td>
<td class="doxyEnumItemDescription">Specifies the source-file name (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XFT_CT<a id="ab91001ecee6942ce950e509c68682796ab72dbd2184cc8fc9f79802f718420973"></a></td>
<td class="doxyEnumItemDescription">Specifies the compiler time stamp (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XFT_CV<a id="ab91001ecee6942ce950e509c68682796a5d46dc5fb5f9d70cbe8bcd7311cf93bd"></a></td>
<td class="doxyEnumItemDescription">Specifies the compiler version number (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XFT_CD<a id="ab91001ecee6942ce950e509c68682796a3b8db63d52f10c233048a2b498c1acf8"></a></td>
<td class="doxyEnumItemDescription">Specifies compiler-defined information (= 128)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### DwarfSectionSubtypeFlags {#a0456b0e88222c998e39b69d80338a440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::XCOFF::DwarfSectionSubtypeFlags : int32_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Values for defining the section subtype of sections of type STYP_DWARF as they would appear in the (signed, 32-bit) s_flags field of the section header structure, contributing to the 16 most significant bits.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSUBTYP_DWINFO<a id="a0456b0e88222c998e39b69d80338a440a5bac5756c6b8d0af4e27cd2d046f9cc4"></a></td>
<td class="doxyEnumItemDescription">DWARF info section (= 0x1'0000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSUBTYP_DWLINE<a id="a0456b0e88222c998e39b69d80338a440aec17bb51c8254d5d916947eaadff0743"></a></td>
<td class="doxyEnumItemDescription">DWARF line section (= 0x2'0000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSUBTYP_DWPBNMS<a id="a0456b0e88222c998e39b69d80338a440ac95bd855f756dbe9bdf775161dd8e42f"></a></td>
<td class="doxyEnumItemDescription">DWARF pubnames section (= 0x3'0000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSUBTYP_DWPBTYP<a id="a0456b0e88222c998e39b69d80338a440ad63489b6370030fcce1380b8d0d615b5"></a></td>
<td class="doxyEnumItemDescription">DWARF pubtypes section (= 0x4'0000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSUBTYP_DWARNGE<a id="a0456b0e88222c998e39b69d80338a440a04b13a24683ab33744016c4b39db2185"></a></td>
<td class="doxyEnumItemDescription">DWARF aranges section (= 0x5'0000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSUBTYP_DWABREV<a id="a0456b0e88222c998e39b69d80338a440a4667e9175300d42a5f7d9c7a8a623c92"></a></td>
<td class="doxyEnumItemDescription">DWARF abbrev section (= 0x6'0000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSUBTYP_DWSTR<a id="a0456b0e88222c998e39b69d80338a440afb84ff02c888aaa98ea208005ff3ffdd"></a></td>
<td class="doxyEnumItemDescription">DWARF str section (= 0x7'0000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSUBTYP_DWRNGES<a id="a0456b0e88222c998e39b69d80338a440a60ff01ad45b24bdb9abdd7a8bdade24d"></a></td>
<td class="doxyEnumItemDescription">DWARF ranges section (= 0x8'0000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSUBTYP_DWLOC<a id="a0456b0e88222c998e39b69d80338a440a706b772496f4db5525d2c9f639ec85b1"></a></td>
<td class="doxyEnumItemDescription">DWARF loc section (= 0x9'0000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSUBTYP_DWFRAME<a id="a0456b0e88222c998e39b69d80338a440a328a22a45a49b076716cd9208117a05f"></a></td>
<td class="doxyEnumItemDescription">DWARF frame section (= 0xA'0000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSUBTYP_DWMAC<a id="a0456b0e88222c998e39b69d80338a440a74e95ef0ee0aab9964cecdec25379f9c"></a></td>
<td class="doxyEnumItemDescription">DWARF macinfo section (= 0xB'0000)</td>
</tr>

</table>
</dd>
</dl>


<p>Defined in the system header <span class="doxyComputerOutput">scnhdr.h</span>.</p>


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### ExtendedTBTableFlag {#a74bbed636d573e998e8a4ef4279c3754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::XCOFF::ExtendedTBTableFlag : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TB_OS1<a id="a74bbed636d573e998e8a4ef4279c3754a1b8ec4dd720337e3ac82df2acc63016a"></a></td>
<td class="doxyEnumItemDescription">Reserved for OS use (= 0x80)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TB_RESERVED<a id="a74bbed636d573e998e8a4ef4279c3754a9d8a3c1bba3ee0c67bf94d78dfbab882"></a></td>
<td class="doxyEnumItemDescription">Reserved for compiler (= 0x40)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TB_SSP_CANARY<a id="a74bbed636d573e998e8a4ef4279c3754a5017ed2c4eaebdc40b8e5cb2c24f0e69"></a></td>
<td class="doxyEnumItemDescription">stack smasher canary present on stack (= 0x20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TB_OS2<a id="a74bbed636d573e998e8a4ef4279c3754a8ede8a94b9e3fe7bc2d0ab367c06281f"></a></td>
<td class="doxyEnumItemDescription">Reserved for OS use (= 0x10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TB_EH_INFO<a id="a74bbed636d573e998e8a4ef4279c3754a199c883f9750d7c4cf1f21c0365b88cc"></a></td>
<td class="doxyEnumItemDescription">Exception handling info present (= 0x08)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TB_LONGTBTABLE2<a id="a74bbed636d573e998e8a4ef4279c3754a5b9883472680131448cadb7461ea9fe0"></a></td>
<td class="doxyEnumItemDescription">Additional tbtable extension exists (= 0x01)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### FileFlag {#a22ef67cbe6de5a4072645faaa42eaa5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::XCOFF::FileFlag : uint16_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F_RELFLG<a id="a22ef67cbe6de5a4072645faaa42eaa5aa8a8024ae7789ad042c1ea426ce97e6a4"></a></td>
<td class="doxyEnumItemDescription">relocation info stripped from file (= 0x0001)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F_EXEC<a id="a22ef67cbe6de5a4072645faaa42eaa5aaf0ed8739dc4f5efcc1c8642c3a4d8433"></a></td>
<td class="doxyEnumItemDescription">file is executable (i.e., it has a loader section) (= 0x0002)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F_LNNO<a id="a22ef67cbe6de5a4072645faaa42eaa5aa4aee9eb02345abf01ec4b9e68a9aaa58"></a></td>
<td class="doxyEnumItemDescription">line numbers stripped from file (= 0x0004)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F_LSYMS<a id="a22ef67cbe6de5a4072645faaa42eaa5aab97f32cce13b85472a58059ada9cd7f0"></a></td>
<td class="doxyEnumItemDescription">local symbols stripped from file (= 0x0008)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F_FDPR_PROF<a id="a22ef67cbe6de5a4072645faaa42eaa5aac1c9ef85cf741be81011b98dcaf5680f"></a></td>
<td class="doxyEnumItemDescription">file was profiled with FDPR (= 0x0010)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F_FDPR_OPTI<a id="a22ef67cbe6de5a4072645faaa42eaa5aade4c67ce697b409b9fea33b68f21a3dc"></a></td>
<td class="doxyEnumItemDescription">file was reordered with FDPR (= 0x0020)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F_DSA<a id="a22ef67cbe6de5a4072645faaa42eaa5aa013694b6ebfd2e9083ffa5ba8ef01f6d"></a></td>
<td class="doxyEnumItemDescription">file uses Dynamic Segment Allocation (32-bit only) (= 0x0040)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F_DEP_1<a id="a22ef67cbe6de5a4072645faaa42eaa5aaa362f27f88c9f0f288512f17e5017d11"></a></td>
<td class="doxyEnumItemDescription">Data Execution Protection bit 1 (= 0x0080)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F_VARPG<a id="a22ef67cbe6de5a4072645faaa42eaa5aafb59bca5ce6a025e466428bb6e1464b1"></a></td>
<td class="doxyEnumItemDescription">executable requests using variable size pages (= 0x0100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F_LPTEXT<a id="a22ef67cbe6de5a4072645faaa42eaa5aa5c147db1b4f45b659708aa01e374ecf6"></a></td>
<td class="doxyEnumItemDescription">executable requires large pages for text (= 0x0400)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F_LPDATA<a id="a22ef67cbe6de5a4072645faaa42eaa5aa5914fb977827a0971a9867d6c34f52ca"></a></td>
<td class="doxyEnumItemDescription">executable requires large pages for data (= 0x0800)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F_DYNLOAD<a id="a22ef67cbe6de5a4072645faaa42eaa5aa53a9208cb47a30f0a01758c28891053e"></a></td>
<td class="doxyEnumItemDescription">file is dynamically loadable and executable (equivalent to F_EXEC on AIX) (= 0x1000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F_SHROBJ<a id="a22ef67cbe6de5a4072645faaa42eaa5aa1059978c0d28a0e7372774c3c4d38f52"></a></td>
<td class="doxyEnumItemDescription">file is a shared object (= 0x2000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F_LOADONLY<a id="a22ef67cbe6de5a4072645faaa42eaa5aa749d9df40c198db8794d25f20cff7387"></a></td>
<td class="doxyEnumItemDescription">
file can be loaded by the system loader, but it is ignored by the linker if it is a member of an archive (=
      0x4000)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F_DEP_2<a id="a22ef67cbe6de5a4072645faaa42eaa5aa1dd0616deae0cca744784103e6e2313e"></a></td>
<td class="doxyEnumItemDescription">Data Execution Protection bit 2 (= 0x8000)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### MagicNumber {#aee8f7e420a81c0a58e0febda6902a6f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::XCOFF::MagicNumber : uint16_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XCOFF32<a id="aee8f7e420a81c0a58e0febda6902a6f6a4c5a9c29c01fa6b38f58ffafd1514454"></a></td>
<td class="doxyEnumItemDescription"> (= 0x01DF)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XCOFF64<a id="aee8f7e420a81c0a58e0febda6902a6f6aaf686a3cf0f7adb2f4f0f3b1c01e0d8a"></a></td>
<td class="doxyEnumItemDescription"> (= 0x01F7)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### RelocationType {#a7309c911b619149e89a825cd78010c8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::XCOFF::RelocationType : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_POS<a id="a7309c911b619149e89a825cd78010c8aa5697ac4313fa05e5b1ca39e698ae0fbc"></a></td>
<td class="doxyEnumItemDescription">Positive relocation (= 0x00)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RL<a id="a7309c911b619149e89a825cd78010c8aab49259da6023d2cbb1bd956402f64cb5"></a></td>
<td class="doxyEnumItemDescription">Positive indirect load relocation. Modifiable instruction (= 0x0c)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RLA<a id="a7309c911b619149e89a825cd78010c8aa16d51d6b89c5628d66225cff9630ac4a"></a></td>
<td class="doxyEnumItemDescription">Positive load address relocation. Modifiable instruction (= 0x0d)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_NEG<a id="a7309c911b619149e89a825cd78010c8aa8347047056e2adce9b7ad615bca925a8"></a></td>
<td class="doxyEnumItemDescription">Negative relocation (= 0x01)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_REL<a id="a7309c911b619149e89a825cd78010c8aa81151f819ab38a2ae0a1ba727e4171a3"></a></td>
<td class="doxyEnumItemDescription">Relative to self relocation (= 0x02)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_TOC<a id="a7309c911b619149e89a825cd78010c8aa126bbcaab291460be1722fe8a2490530"></a></td>
<td class="doxyEnumItemDescription">Relative to the TOC relocation (= 0x03)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_TRL<a id="a7309c911b619149e89a825cd78010c8aa3b08100f3dac1e8426c4503a6450e6d1"></a></td>
<td class="doxyEnumItemDescription">TOC relative indirect load relocation (= 0x12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_TRLA<a id="a7309c911b619149e89a825cd78010c8aabc55a98a13889177827d4d56d4117796"></a></td>
<td class="doxyEnumItemDescription">
Relative to the TOC or to the thread-local storage base relocation (=
      0x13)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_GL<a id="a7309c911b619149e89a825cd78010c8aaa32c9a4aed56a2a94a2d18aa02aa6554"></a></td>
<td class="doxyEnumItemDescription">Global linkage-external TOC address relocation (= 0x05)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_TCL<a id="a7309c911b619149e89a825cd78010c8aabd8790ecfa6b9839555656e2e5b4befe"></a></td>
<td class="doxyEnumItemDescription">Local object TOC address relocation (= 0x06)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_REF<a id="a7309c911b619149e89a825cd78010c8aab32b714a6085785700777cab84db430f"></a></td>
<td class="doxyEnumItemDescription">A non-relocating relocation (= 0x0f)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_BA<a id="a7309c911b619149e89a825cd78010c8aa665ea4416814df60d7afcaa60edcbc4d"></a></td>
<td class="doxyEnumItemDescription">Branch absolute relocation (= 0x08)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_BR<a id="a7309c911b619149e89a825cd78010c8aa4af14f52e262c85d3f11ec65f5d3f8b3"></a></td>
<td class="doxyEnumItemDescription">Branch relative to self relocation (= 0x0a)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RBA<a id="a7309c911b619149e89a825cd78010c8aa5f580cdb49fb297a3e1b2bad00e7e6f8"></a></td>
<td class="doxyEnumItemDescription">Branch absolute relocation (= 0x18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_RBR<a id="a7309c911b619149e89a825cd78010c8aa04c13cb7fcc803870970c4b75b5c9905"></a></td>
<td class="doxyEnumItemDescription">Branch relative to self relocation (= 0x1a)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_TLS<a id="a7309c911b619149e89a825cd78010c8aae4144a827fe3865e989169e1fdfd3ede"></a></td>
<td class="doxyEnumItemDescription">General-dynamic reference to TLS symbol (= 0x20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_TLS_IE<a id="a7309c911b619149e89a825cd78010c8aa88aba99cf6b633d97e0cdd24fec5d0f5"></a></td>
<td class="doxyEnumItemDescription">Initial-exec reference to TLS symbol (= 0x21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_TLS_LD<a id="a7309c911b619149e89a825cd78010c8aadbc74cd663a943131b0e174006b6b581"></a></td>
<td class="doxyEnumItemDescription">Local-dynamic reference to TLS symbol (= 0x22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_TLS_LE<a id="a7309c911b619149e89a825cd78010c8aae54c065150485a9445e07674fb43c3a7"></a></td>
<td class="doxyEnumItemDescription">Local-exec reference to TLS symbol (= 0x23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_TLSM<a id="a7309c911b619149e89a825cd78010c8aa8b5d41ca43ab37f8160e4b56ec25c03e"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> reference to TLS (= 0x24)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_TLSML<a id="a7309c911b619149e89a825cd78010c8aa2bf3c877a5a2835a5e55ac54ddedccd6"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> reference to the local TLS storage (= 0x25)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_TOCU<a id="a7309c911b619149e89a825cd78010c8aacb6f8892a6761a91f9e29cdafb33a7c8"></a></td>
<td class="doxyEnumItemDescription">Relative to TOC upper (= 0x30)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_TOCL<a id="a7309c911b619149e89a825cd78010c8aac47fa14749515f1a3a0d88c51f854aa7"></a></td>
<td class="doxyEnumItemDescription">Relative to TOC lower (= 0x31)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### ReservedSectionNum {#ab57487d0a7c9b4f4003ba302b693df97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::XCOFF::ReservedSectionNum : int16_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">N_DEBUG<a id="ab57487d0a7c9b4f4003ba302b693df97a2c209de094ab85d67d57b03f5976e12c"></a></td>
<td class="doxyEnumItemDescription"> (= -2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">N_ABS<a id="ab57487d0a7c9b4f4003ba302b693df97af643a34fdae3d8c2e1440c1458f68745"></a></td>
<td class="doxyEnumItemDescription"> (= -1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">N_UNDEF<a id="ab57487d0a7c9b4f4003ba302b693df97a9bda16ced9ef53550951a707d8fb10ef"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### SectionTypeFlags {#af30dc250fcc756ed99640fe2d10389ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::XCOFF::SectionTypeFlags : int32_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STYP_PAD<a id="af30dc250fcc756ed99640fe2d10389aeaad2dde9fb3e75239c7e4da9337eecd9d"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0008)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STYP_DWARF<a id="af30dc250fcc756ed99640fe2d10389aea1dddb836146cb79d721a0eb775a670ab"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0010)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STYP_TEXT<a id="af30dc250fcc756ed99640fe2d10389aea625db7b5bb9b798cf7c4eac884e7722b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0020)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STYP_DATA<a id="af30dc250fcc756ed99640fe2d10389aea1e3f056d2214669889fba21e3d949ca3"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0040)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STYP_BSS<a id="af30dc250fcc756ed99640fe2d10389aeacb24e90dcfcba01d1c251bcf8b399ef2"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0080)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STYP_EXCEPT<a id="af30dc250fcc756ed99640fe2d10389aeabda15739c5c07c0ac38280faaa4a2306"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STYP_INFO<a id="af30dc250fcc756ed99640fe2d10389aea1f498f3fbb898ea8e37f18e59cf23e39"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0200)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STYP_TDATA<a id="af30dc250fcc756ed99640fe2d10389aea233a82ca0336e9be851e053af95ecb5d"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0400)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STYP_TBSS<a id="af30dc250fcc756ed99640fe2d10389aeadcf57b5531bdb50652a3604cf820b71d"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0800)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STYP_LOADER<a id="af30dc250fcc756ed99640fe2d10389aea18317b81fd433739e8c447d1b1b93d32"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STYP_DEBUG<a id="af30dc250fcc756ed99640fe2d10389aea91ad18218d1a31d6e08723d07b3df9ba"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STYP_TYPCHK<a id="af30dc250fcc756ed99640fe2d10389aea096fc439e418e4b17ce41780ff4a9f8d"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STYP_OVRFLO<a id="af30dc250fcc756ed99640fe2d10389aeac5d245ccdee6f92a2b232f49c0b4c41e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x8000)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### StorageClass {#abcfbfa374a3d08b4ee55f054ceb27a70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::XCOFF::StorageClass : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_FILE<a id="abcfbfa374a3d08b4ee55f054ceb27a70ab3ab2990d9bd88d3ff52e29f0ad776bf"></a></td>
<td class="doxyEnumItemDescription"> (= 103)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_BINCL<a id="abcfbfa374a3d08b4ee55f054ceb27a70a3808d2da54bf5b3f6f857accbe2c3880"></a></td>
<td class="doxyEnumItemDescription"> (= 108)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_EINCL<a id="abcfbfa374a3d08b4ee55f054ceb27a70a9a8191c757881847ba1f1023778377ee"></a></td>
<td class="doxyEnumItemDescription"> (= 109)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_GSYM<a id="abcfbfa374a3d08b4ee55f054ceb27a70a36ff92d88b07b2bd646659884e150690"></a></td>
<td class="doxyEnumItemDescription"> (= 128)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_STSYM<a id="abcfbfa374a3d08b4ee55f054ceb27a70ac23cf4733be97ac47ac844fa6ae6dab8"></a></td>
<td class="doxyEnumItemDescription"> (= 133)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_BCOMM<a id="abcfbfa374a3d08b4ee55f054ceb27a70a092dfc761b213557b52706a6832b9cc7"></a></td>
<td class="doxyEnumItemDescription"> (= 135)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_ECOMM<a id="abcfbfa374a3d08b4ee55f054ceb27a70afafe0602b4d711b2fee4c6b610012def"></a></td>
<td class="doxyEnumItemDescription"> (= 137)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_ENTRY<a id="abcfbfa374a3d08b4ee55f054ceb27a70a7bb74316ff9281462e80e36f26bcb6d9"></a></td>
<td class="doxyEnumItemDescription"> (= 141)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_BSTAT<a id="abcfbfa374a3d08b4ee55f054ceb27a70afcfb22d749188fb257dac81a5048e61a"></a></td>
<td class="doxyEnumItemDescription"> (= 143)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_ESTAT<a id="abcfbfa374a3d08b4ee55f054ceb27a70affd823048db3a0e496e765d352446a5f"></a></td>
<td class="doxyEnumItemDescription"> (= 144)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_GTLS<a id="abcfbfa374a3d08b4ee55f054ceb27a70a1629ee4e5de0988849d22ed29070e966"></a></td>
<td class="doxyEnumItemDescription"> (= 145)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_STTLS<a id="abcfbfa374a3d08b4ee55f054ceb27a70a8047e38123f8e32b2417e57003021cfc"></a></td>
<td class="doxyEnumItemDescription"> (= 146)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_DWARF<a id="abcfbfa374a3d08b4ee55f054ceb27a70ac93234a364235748b00c29e5b74fa37a"></a></td>
<td class="doxyEnumItemDescription"> (= 112)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_LSYM<a id="abcfbfa374a3d08b4ee55f054ceb27a70a9d4afaff861a057bff2f7c5af08c32d7"></a></td>
<td class="doxyEnumItemDescription"> (= 129)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_PSYM<a id="abcfbfa374a3d08b4ee55f054ceb27a70a23b5d2359b6b02d84912cd103918eafe"></a></td>
<td class="doxyEnumItemDescription"> (= 130)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_RSYM<a id="abcfbfa374a3d08b4ee55f054ceb27a70a4b786a64d1bbc3b454c56a1892a868b4"></a></td>
<td class="doxyEnumItemDescription"> (= 131)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_RPSYM<a id="abcfbfa374a3d08b4ee55f054ceb27a70a2d836f8d2e1d3a5e027f17a61d1ff267"></a></td>
<td class="doxyEnumItemDescription"> (= 132)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_ECOML<a id="abcfbfa374a3d08b4ee55f054ceb27a70ac2711eb069b88c200ab2ca3c68577be0"></a></td>
<td class="doxyEnumItemDescription"> (= 136)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_FUN<a id="abcfbfa374a3d08b4ee55f054ceb27a70a21dd315e5812d908aad50ccf97c9f98d"></a></td>
<td class="doxyEnumItemDescription"> (= 142)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_EXT<a id="abcfbfa374a3d08b4ee55f054ceb27a70a19f57c169e86a4332accccf291954261"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_WEAKEXT<a id="abcfbfa374a3d08b4ee55f054ceb27a70a8f5d26c17483f47bf923e263a4de4c2e"></a></td>
<td class="doxyEnumItemDescription"> (= 111)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_NULL<a id="abcfbfa374a3d08b4ee55f054ceb27a70ac131afeee63f28c559e32b0ca3816a53"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_STAT<a id="abcfbfa374a3d08b4ee55f054ceb27a70a690257670e7c27f441d8f5d5508f8b61"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_BLOCK<a id="abcfbfa374a3d08b4ee55f054ceb27a70a66c2b93e45dc730a3b17051d5b2d6fd3"></a></td>
<td class="doxyEnumItemDescription"> (= 100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_FCN<a id="abcfbfa374a3d08b4ee55f054ceb27a70aa3af513e95c6ae116a7fda56503371e1"></a></td>
<td class="doxyEnumItemDescription"> (= 101)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_HIDEXT<a id="abcfbfa374a3d08b4ee55f054ceb27a70aeffba1492a002e3d506d9eca64672a24"></a></td>
<td class="doxyEnumItemDescription"> (= 107)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_INFO<a id="abcfbfa374a3d08b4ee55f054ceb27a70a6c5f18c2d2f8ef4554287499b92dc853"></a></td>
<td class="doxyEnumItemDescription"> (= 110)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_DECL<a id="abcfbfa374a3d08b4ee55f054ceb27a70a22f4ff6ef6a421521b45beaf03de6e65"></a></td>
<td class="doxyEnumItemDescription"> (= 140)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_AUTO<a id="abcfbfa374a3d08b4ee55f054ceb27a70a44e2591f735b44c8efce8db2b3cd9e58"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_REG<a id="abcfbfa374a3d08b4ee55f054ceb27a70a619d9caa658508165d149f4e9de5ae60"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_EXTDEF<a id="abcfbfa374a3d08b4ee55f054ceb27a70a4f655dd1f0a80bd6ad9af733c5fce458"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_LABEL<a id="abcfbfa374a3d08b4ee55f054ceb27a70a551d2c39eb0ac93c195e5f301b0908f4"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_ULABEL<a id="abcfbfa374a3d08b4ee55f054ceb27a70ab25f119012e7012ef0ac4cceba4fda90"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_MOS<a id="abcfbfa374a3d08b4ee55f054ceb27a70a59294c9167080d273884fda5b8565dbc"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_ARG<a id="abcfbfa374a3d08b4ee55f054ceb27a70a25d455ff3a664bef107d47221af3c6dc"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_STRTAG<a id="abcfbfa374a3d08b4ee55f054ceb27a70a2ff548e5bdf7ffa54c16a60d1b9a7c0c"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_MOU<a id="abcfbfa374a3d08b4ee55f054ceb27a70ace13229751c9d27d68bf8ecd61cc816a"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_UNTAG<a id="abcfbfa374a3d08b4ee55f054ceb27a70a40d4ceefbe7e6f4ac3a277a326af1e44"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_TPDEF<a id="abcfbfa374a3d08b4ee55f054ceb27a70ae9c4390c7173df2cf0bc6dba3934ab03"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_USTATIC<a id="abcfbfa374a3d08b4ee55f054ceb27a70aedbae8ca40257b09c7cfdbc625ef1300"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_ENTAG<a id="abcfbfa374a3d08b4ee55f054ceb27a70a9833a6c18e0c7b8c2b5ad51150f8c057"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_MOE<a id="abcfbfa374a3d08b4ee55f054ceb27a70a0286450c0240ddf2918a0270eecd47d2"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_REGPARM<a id="abcfbfa374a3d08b4ee55f054ceb27a70ae40e51a60986650c4c81d1de654139ef"></a></td>
<td class="doxyEnumItemDescription"> (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_FIELD<a id="abcfbfa374a3d08b4ee55f054ceb27a70a366cd9be1725b5f7a95799fd7f188e1e"></a></td>
<td class="doxyEnumItemDescription"> (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_EOS<a id="abcfbfa374a3d08b4ee55f054ceb27a70a0f605fcb60753d7369dc31b4d5b98c95"></a></td>
<td class="doxyEnumItemDescription"> (= 102)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_LINE<a id="abcfbfa374a3d08b4ee55f054ceb27a70a174eaaa6c9518e2eeae14ce0de973719"></a></td>
<td class="doxyEnumItemDescription"> (= 104)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_ALIAS<a id="abcfbfa374a3d08b4ee55f054ceb27a70aa804b18d5bc65c8ff7f7487fffffd8a7"></a></td>
<td class="doxyEnumItemDescription"> (= 105)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_HIDDEN<a id="abcfbfa374a3d08b4ee55f054ceb27a70adcc91f5755c6978ad8625a83adf87230"></a></td>
<td class="doxyEnumItemDescription"> (= 106)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_EFCN<a id="abcfbfa374a3d08b4ee55f054ceb27a70aa8cfad4a65a4c9f06d6eb235a8d9957b"></a></td>
<td class="doxyEnumItemDescription"> (= 255)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_TCSYM<a id="abcfbfa374a3d08b4ee55f054ceb27a70af0657d2e13ef79a76f35f40360bee91f"></a></td>
<td class="doxyEnumItemDescription"> (= 134)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### StorageMappingClass {#abf0ae26de1e332dddf7d1383bb68502c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::XCOFF::StorageMappingClass : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Storage Mapping Class definitions.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_PR<a id="abf0ae26de1e332dddf7d1383bb68502cac7850ad5e926ed392928b68832be764e"></a></td>
<td class="doxyEnumItemDescription">Program Code (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_RO<a id="abf0ae26de1e332dddf7d1383bb68502ca8013b2bcd044df8d46c49e8b96eb9a52"></a></td>
<td class="doxyEnumItemDescription">Read Only <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_DB<a id="abf0ae26de1e332dddf7d1383bb68502ca81ef1e60ebc0edc6d2bc931745417a40"></a></td>
<td class="doxyEnumItemDescription">Debug Dictionary Table (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_GL<a id="abf0ae26de1e332dddf7d1383bb68502ca4fbe0b67fd3e6e9e044d17e1c8ea171f"></a></td>
<td class="doxyEnumItemDescription">Global Linkage (Interfile Interface Code) (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_XO<a id="abf0ae26de1e332dddf7d1383bb68502cac99ee804a17100dbadc4e46f52d37ea9"></a></td>
<td class="doxyEnumItemDescription">Extended Operation (Pseudo Machine <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>) (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_SV<a id="abf0ae26de1e332dddf7d1383bb68502ca9ba063c1e63ed44336c4faf7c1972cd6"></a></td>
<td class="doxyEnumItemDescription">Supervisor Call (32-bit process only) (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_SV64<a id="abf0ae26de1e332dddf7d1383bb68502ca546cf1339a751e5a0d3182b3da0f0f94"></a></td>
<td class="doxyEnumItemDescription">Supervisor Call for 64-bit process (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_SV3264<a id="abf0ae26de1e332dddf7d1383bb68502ca4a971a61a0ab8ce1947bb3a848049d07"></a></td>
<td class="doxyEnumItemDescription">Supervisor Call for both 32- and 64-bit processes (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_TI<a id="abf0ae26de1e332dddf7d1383bb68502cabfcf8ae01dcfbb5a8d45f147e252f002"></a></td>
<td class="doxyEnumItemDescription">Traceback Index csect (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_TB<a id="abf0ae26de1e332dddf7d1383bb68502ca2ca7cba39d254264abe8a4be429b9ce1"></a></td>
<td class="doxyEnumItemDescription">Traceback Table csect (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_RW<a id="abf0ae26de1e332dddf7d1383bb68502ca54b665a90facd18af1df67a6cf1194d5"></a></td>
<td class="doxyEnumItemDescription">Read Write Data (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_TC0<a id="abf0ae26de1e332dddf7d1383bb68502ca3a6f1e59368266cd566dd509082130b8"></a></td>
<td class="doxyEnumItemDescription">TOC Anchor for TOC Addressability (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_TC<a id="abf0ae26de1e332dddf7d1383bb68502caf3ddd7ad51b55d1c692d1cd3662e0fce"></a></td>
<td class="doxyEnumItemDescription">General TOC item (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_TD<a id="abf0ae26de1e332dddf7d1383bb68502caa250286dfb78ab47b0ba96d5b0f9bc51"></a></td>
<td class="doxyEnumItemDescription">Scalar data item in the TOC (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_DS<a id="abf0ae26de1e332dddf7d1383bb68502ca4ffc8d36538dfbb1c9eac9236b0855fb"></a></td>
<td class="doxyEnumItemDescription">Descriptor csect (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_UA<a id="abf0ae26de1e332dddf7d1383bb68502ca9b07ec722c8247ad2535a8c28b218220"></a></td>
<td class="doxyEnumItemDescription">Unclassified - Treated as Read Write (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_BS<a id="abf0ae26de1e332dddf7d1383bb68502cadc9c6c9efab40595101d1c98cb7bb4de"></a></td>
<td class="doxyEnumItemDescription">BSS class (uninitialized static internal) (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_UC<a id="abf0ae26de1e332dddf7d1383bb68502caa809cc9c58190ef28140c8fda5960954"></a></td>
<td class="doxyEnumItemDescription">Un-named Fortran Common (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_TL<a id="abf0ae26de1e332dddf7d1383bb68502ca58bcd5a7d086b06a4971a18c4596e711"></a></td>
<td class="doxyEnumItemDescription">Initialized thread-local variable (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_UL<a id="abf0ae26de1e332dddf7d1383bb68502cab35fc11d2968b541a2442c6138a1ba09"></a></td>
<td class="doxyEnumItemDescription">Uninitialized thread-local variable (= 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XMC_TE<a id="abf0ae26de1e332dddf7d1383bb68502ca01440f6a3c58a05d2ee20ba480d16443"></a></td>
<td class="doxyEnumItemDescription">Symbol mapped at the end of TOC (= 22)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### SymbolAuxType {#a6d134aed42e1f7be67a8dc02c9bd401f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::XCOFF::SymbolAuxType : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AUX_EXCEPT<a id="a6d134aed42e1f7be67a8dc02c9bd401fa3959d285dec0abd51691820d8ca5d5a6"></a></td>
<td class="doxyEnumItemDescription">Identifies an exception auxiliary entry (= 255)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AUX_FCN<a id="a6d134aed42e1f7be67a8dc02c9bd401fa3b70f3b48ec647fbfa3b39704d17aafa"></a></td>
<td class="doxyEnumItemDescription">Identifies a function auxiliary entry (= 254)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AUX_SYM<a id="a6d134aed42e1f7be67a8dc02c9bd401fa5037bc6cd3b6dc08f210db2bfb7b6ff5"></a></td>
<td class="doxyEnumItemDescription">Identifies a symbol auxiliary entry (= 253)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AUX_FILE<a id="a6d134aed42e1f7be67a8dc02c9bd401fa211ab0cbd5ee12209c942647bf1fa4d8"></a></td>
<td class="doxyEnumItemDescription">Identifies a file auxiliary entry (= 252)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AUX_CSECT<a id="a6d134aed42e1f7be67a8dc02c9bd401fab6ff03dac80c8cf393e7c3a876894607"></a></td>
<td class="doxyEnumItemDescription">Identifies a csect auxiliary entry (= 251)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AUX_SECT<a id="a6d134aed42e1f7be67a8dc02c9bd401fa11483bdf683e2a2b76c51ad843e033b0"></a></td>
<td class="doxyEnumItemDescription">Identifies a SECT auxiliary entry (= 250)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### SymbolType {#ae6213556e13de39091f6861f199d7b1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::XCOFF::SymbolType : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XTY_ER<a id="ae6213556e13de39091f6861f199d7b1fad8a6731bed03a3891075d7ba162f83ba"></a></td>
<td class="doxyEnumItemDescription">External reference (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XTY_SD<a id="ae6213556e13de39091f6861f199d7b1fabc703e0e4100086f310d23f214a3cf03"></a></td>
<td class="doxyEnumItemDescription">Csect definition for initialized storage (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XTY_LD<a id="ae6213556e13de39091f6861f199d7b1fac4e3fde018bdce1941b4fcb749178493"></a></td>
<td class="doxyEnumItemDescription">Label definition (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XTY_CM<a id="ae6213556e13de39091f6861f199d7b1fa533de1d99e6b391e90e30a38b9e3a954"></a></td>
<td class="doxyEnumItemDescription">Common csect definition. For uninitialized storage (= 3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### VisibilityType {#a8a4cb520e5c6a7e39926cfe8dae0b73e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::XCOFF::VisibilityType : uint16_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Values for visibility as they would appear when encoded in the high 4 bits of the 16-bit unsigned n_type field of symbol table entries.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SYM_V_UNSPECIFIED<a id="a8a4cb520e5c6a7e39926cfe8dae0b73ead0a12244f2c9383cf63c7e8ced746bdd"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SYM_V_INTERNAL<a id="a8a4cb520e5c6a7e39926cfe8dae0b73eaafb91dd7c1a967f6a8f5dc5ba0f428ce"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SYM_V_HIDDEN<a id="a8a4cb520e5c6a7e39926cfe8dae0b73ea5f87b6d679c546ae79ee03411c54a15f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SYM_V_PROTECTED<a id="a8a4cb520e5c6a7e39926cfe8dae0b73ea0eee4603371bd48180d987e3600ce5b6"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SYM_V_EXPORTED<a id="a8a4cb520e5c6a7e39926cfe8dae0b73ea6077f0f2b971e50bbacbc960260a8008"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4000)</td>
</tr>

</table>
</dd>
</dl>


<p>Valid for 32-bit <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> only when the vstamp in the auxiliary header is greater than 1.</p>


<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### XCOFFInterpret {#ad05b784bd1fda8fa92e47f5968bfce29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::XCOFF::XCOFFInterpret : uint16_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OLD_XCOFF_INTERPRET<a id="ad05b784bd1fda8fa92e47f5968bfce29a6bbd9cde4dd09a65c65d4268174c16ab"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NEW_XCOFF_INTERPRET<a id="ad05b784bd1fda8fa92e47f5968bfce29a1574d67d07664912e3e2f871590d7986"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getCpuID() {#a2584f7d1fe1c5ab17f8aaba3dafaed66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XCOFF::CFileCpuId llvm::XCOFF::getCpuID (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/xcoff-cpp">XCOFF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#aa13f802513b39e1e2a7650011e5651d7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a9e3c196667a91fdc81783769feab2e89">llvm::PPC::normalizeCPUName</a>, <a href="#a91c69d4341c1d1dd2dabf18fb78e9a5faceb0245d75f9a523cfe8d537b9ad070f">TCPU_601</a>, <a href="#a91c69d4341c1d1dd2dabf18fb78e9a5fa9dde7b9eec34e97ce6ea0dc698c1682a">TCPU_603</a>, <a href="#a91c69d4341c1d1dd2dabf18fb78e9a5fa30ff25aa56881c1ca0e425d2be2a622e">TCPU_604</a>, <a href="#a91c69d4341c1d1dd2dabf18fb78e9a5fac4652524a18555e53587809b2b8674c0">TCPU_620</a>, <a href="#a91c69d4341c1d1dd2dabf18fb78e9a5fada4e56e8301f5d713f1b94395c96abd5">TCPU_970</a>, <a href="#a91c69d4341c1d1dd2dabf18fb78e9a5fa4373c4c8ce6ba7b05f10e73f67391c97">TCPU_ANY</a>, <a href="#a91c69d4341c1d1dd2dabf18fb78e9a5fa6dffcaea7c8e550d74ab0f42fae0ef9c">TCPU_COM</a>, <a href="#a91c69d4341c1d1dd2dabf18fb78e9a5faf0488a9ae52d5efb69b8d9ade83b44f4">TCPU_INVALID</a>, <a href="#a91c69d4341c1d1dd2dabf18fb78e9a5fa517defe929b8d7279ffe5a4a62d49ae0">TCPU_PWR10</a>, <a href="#a91c69d4341c1d1dd2dabf18fb78e9a5fab33654326d121d31b9719daf5634437e">TCPU_PWR5</a>, <a href="#a91c69d4341c1d1dd2dabf18fb78e9a5fa6ab1a2baa7b9b5b1cb1dc767e876cf9e">TCPU_PWR5X</a>, <a href="#a91c69d4341c1d1dd2dabf18fb78e9a5faa23345d390b808814455a7d9927547dd">TCPU_PWR6</a>, <a href="#a91c69d4341c1d1dd2dabf18fb78e9a5fa06923533627c876e0eb59bfd4d6b2def">TCPU_PWR6E</a>, <a href="#a91c69d4341c1d1dd2dabf18fb78e9a5fa34cac65f144da4d6cb79ee5ff74487b9">TCPU_PWR7</a>, <a href="#a91c69d4341c1d1dd2dabf18fb78e9a5fa428e0ff16cb3c14f6645fc43010f2e35">TCPU_PWR8</a> and <a href="#a91c69d4341c1d1dd2dabf18fb78e9a5fa087e289837b644ec1710ba50b325c22a">TCPU_PWR9</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#af5ca20f498adaec1f940475984ad7050">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::doInitialization</a>.</p>

</div>
</div>

### getExtendedTBTableFlagString() {#a1ec7fd3672feec111d150c08c4cf6a69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt; 32 &gt; llvm::XCOFF::getExtendedTBTableFlagString (uint8_t Flag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>, definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/xcoff-cpp">XCOFF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="#a74bbed636d573e998e8a4ef4279c3754a199c883f9750d7c4cf1f21c0365b88cc">TB_EH_INFO</a>, <a href="#a74bbed636d573e998e8a4ef4279c3754a5b9883472680131448cadb7461ea9fe0">TB_LONGTBTABLE2</a>, <a href="#a74bbed636d573e998e8a4ef4279c3754a1b8ec4dd720337e3ac82df2acc63016a">TB_OS1</a>, <a href="#a74bbed636d573e998e8a4ef4279c3754a8ede8a94b9e3fe7bc2d0ab367c06281f">TB_OS2</a>, <a href="#a74bbed636d573e998e8a4ef4279c3754a9d8a3c1bba3ee0c67bf94d78dfbab882">TB_RESERVED</a> and <a href="#a74bbed636d573e998e8a4ef4279c3754a5017ed2c4eaebdc40b8e5cb2c24f0e69">TB_SSP_CANARY</a>.</p>

</div>
</div>

### getMappingClassString() {#a5108aa1d02847a41b154cf255a52348b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::XCOFF::getMappingClassString (<a href="#abf0ae26de1e332dddf7d1383bb68502c">XCOFF::StorageMappingClass</a> SMC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/xcoff-cpp">XCOFF.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/xcoff-cpp/#a4336dcdf868962fd85056bf0c4895ee1">SMC_CASE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a435597fd04ebfd9b5fb5708a4309febb">llvm::MCContext::getXCOFFSection</a>.</p>

</div>
</div>

### getNameForTracebackTableLanguageId() {#ae1dc50da0a38a1295f2fef3a4bc247d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::XCOFF::getNameForTracebackTableLanguageId (<a href="/web-llvm/docs/api/structs/llvm/xcoff/tracebacktable/#a85fbc332b83b1f0ad80ebb5e88826c29">TracebackTable::LanguageID</a> LangId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/xcoff-cpp">XCOFF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#adacba4cb06d1dd9232ee3d2d49a44d8fa972e73b7a882d0802a4e3a16946a2f94">llvm::Basic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/xcoff-cpp/#a098ff3b0c108e9e04ebb65bc9287a355">LANG_CASE</a>.</p>

</div>
</div>

### getRelocationTypeString() {#a45337c02ef6094e30bf7aa0e1dc8826c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::XCOFF::getRelocationTypeString (<a href="#a7309c911b619149e89a825cd78010c8a">XCOFF::RelocationType</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/xcoff-cpp">XCOFF.cpp</a>.</p>


<p>References <a href="#a7309c911b619149e89a825cd78010c8aa665ea4416814df60d7afcaa60edcbc4d">R_BA</a>, <a href="#a7309c911b619149e89a825cd78010c8aa4af14f52e262c85d3f11ec65f5d3f8b3">R_BR</a>, <a href="#a7309c911b619149e89a825cd78010c8aaa32c9a4aed56a2a94a2d18aa02aa6554">R_GL</a>, <a href="#a7309c911b619149e89a825cd78010c8aa8347047056e2adce9b7ad615bca925a8">R_NEG</a>, <a href="#a7309c911b619149e89a825cd78010c8aa5697ac4313fa05e5b1ca39e698ae0fbc">R_POS</a>, <a href="#a7309c911b619149e89a825cd78010c8aa5f580cdb49fb297a3e1b2bad00e7e6f8">R_RBA</a>, <a href="#a7309c911b619149e89a825cd78010c8aa04c13cb7fcc803870970c4b75b5c9905">R_RBR</a>, <a href="#a7309c911b619149e89a825cd78010c8aab32b714a6085785700777cab84db430f">R_REF</a>, <a href="#a7309c911b619149e89a825cd78010c8aa81151f819ab38a2ae0a1ba727e4171a3">R_REL</a>, <a href="#a7309c911b619149e89a825cd78010c8aab49259da6023d2cbb1bd956402f64cb5">R_RL</a>, <a href="#a7309c911b619149e89a825cd78010c8aa16d51d6b89c5628d66225cff9630ac4a">R_RLA</a>, <a href="#a7309c911b619149e89a825cd78010c8aabd8790ecfa6b9839555656e2e5b4befe">R_TCL</a>, <a href="#a7309c911b619149e89a825cd78010c8aae4144a827fe3865e989169e1fdfd3ede">R_TLS</a>, <a href="#a7309c911b619149e89a825cd78010c8aa88aba99cf6b633d97e0cdd24fec5d0f5">R_TLS_IE</a>, <a href="#a7309c911b619149e89a825cd78010c8aadbc74cd663a943131b0e174006b6b581">R_TLS_LD</a>, <a href="#a7309c911b619149e89a825cd78010c8aae54c065150485a9445e07674fb43c3a7">R_TLS_LE</a>, <a href="#a7309c911b619149e89a825cd78010c8aa8b5d41ca43ab37f8160e4b56ec25c03e">R_TLSM</a>, <a href="#a7309c911b619149e89a825cd78010c8aa2bf3c877a5a2835a5e55ac54ddedccd6">R_TLSML</a>, <a href="#a7309c911b619149e89a825cd78010c8aa126bbcaab291460be1722fe8a2490530">R_TOC</a>, <a href="#a7309c911b619149e89a825cd78010c8aac47fa14749515f1a3a0d88c51f854aa7">R_TOCL</a>, <a href="#a7309c911b619149e89a825cd78010c8aacb6f8892a6761a91f9e29cdafb33a7c8">R_TOCU</a>, <a href="#a7309c911b619149e89a825cd78010c8aa3b08100f3dac1e8426c4503a6450e6d1">R_TRL</a>, <a href="#a7309c911b619149e89a825cd78010c8aabc55a98a13889177827d4d56d4117796">R_TRLA</a> and <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/xcoff-cpp/#ae0b821b76d8dd0f994f3f7da62bfcbf1">RELOC_CASE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a181019615fec687b5203ba7489f65613">llvm::object::XCOFFObjectFile::getRelocationTypeName</a>.</p>

</div>
</div>

### getTCPUString() {#ae15aa2110724f82f56c6f702c0d3f80f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::XCOFF::getTCPUString (<a href="#a91c69d4341c1d1dd2dabf18fb78e9a5f">XCOFF::CFileCpuId</a> TCPU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/xcoff-cpp">XCOFF.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/xcoff-cpp/#ae8586c58917915c3ad166f81b2cf71e0">TCPU_CASE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#af5ca20f498adaec1f940475984ad7050">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::doInitialization</a>.</p>

</div>
</div>

### parseParmsType() {#a470daf78d8ec132289b57490e8e5207f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SmallString&lt; 32 &gt; &gt; llvm::XCOFF::parseParmsType (uint32_t Value, unsigned FixedParmsNum, unsigned FloatingParmsNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>, definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/xcoff-cpp">XCOFF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/structs/llvm/xcoff/tracebacktable/#a4797af849854b324d4eb3fe9cbe9e678">llvm::XCOFF::TracebackTable::ParmTypeFloatingIsDoubleBit</a> and <a href="/web-llvm/docs/api/structs/llvm/xcoff/tracebacktable/#a581c8f9f25bd39ab0feb3c03529a5e79">llvm::XCOFF::TracebackTable::ParmTypeIsFloatingBit</a>.</p>

</div>
</div>

### parseParmsTypeWithVecInfo() {#a34c118d5f2c660e296a4e2bfdf6ba5f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SmallString&lt; 32 &gt; &gt; llvm::XCOFF::parseParmsTypeWithVecInfo (uint32_t Value, unsigned FixedParmsNum, unsigned FloatingParmsNum, unsigned VectorParmsNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>, definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/xcoff-cpp">XCOFF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/structs/llvm/xcoff/tracebacktable/#a85b63b0fb3f18920f92b7168b34f3b1a">llvm::XCOFF::TracebackTable::ParmTypeIsDoubleBits</a>, <a href="/web-llvm/docs/api/structs/llvm/xcoff/tracebacktable/#ab799800aecd07878f00aad6ea1b165f8">llvm::XCOFF::TracebackTable::ParmTypeIsFixedBits</a>, <a href="/web-llvm/docs/api/structs/llvm/xcoff/tracebacktable/#ad6ed35c8a3d07c1900872c61c586247e">llvm::XCOFF::TracebackTable::ParmTypeIsFloatingBits</a>, <a href="/web-llvm/docs/api/structs/llvm/xcoff/tracebacktable/#abb09209bb20d7e4895b08150d60b2f01">llvm::XCOFF::TracebackTable::ParmTypeIsVectorBits</a> and <a href="/web-llvm/docs/api/structs/llvm/xcoff/tracebacktable/#a6f608bd67fed2c46e43a0874e6fdb315">llvm::XCOFF::TracebackTable::ParmTypeMask</a>.</p>

</div>
</div>

### parseVectorParmsType() {#a65e7fd6df26cd652ac6c015a35ddec17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SmallString&lt; 32 &gt; &gt; llvm::XCOFF::parseVectorParmsType (uint32_t Value, unsigned ParmsNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>, definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/xcoff-cpp">XCOFF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/structs/llvm/xcoff/tracebacktable/#ac0aec3a75b6a095741931c513091f730">llvm::XCOFF::TracebackTable::ParmTypeIsVectorCharBit</a>, <a href="/web-llvm/docs/api/structs/llvm/xcoff/tracebacktable/#acdb742bb9d7c37b75be1529f49245280">llvm::XCOFF::TracebackTable::ParmTypeIsVectorFloatBit</a>, <a href="/web-llvm/docs/api/structs/llvm/xcoff/tracebacktable/#aa28d86e154c96e90a36223f852a19ad6">llvm::XCOFF::TracebackTable::ParmTypeIsVectorIntBit</a>, <a href="/web-llvm/docs/api/structs/llvm/xcoff/tracebacktable/#a6780511ed1377c9cf0e01e40e87623f8">llvm::XCOFF::TracebackTable::ParmTypeIsVectorShortBit</a> and <a href="/web-llvm/docs/api/structs/llvm/xcoff/tracebacktable/#a6f608bd67fed2c46e43a0874e6fdb315">llvm::XCOFF::TracebackTable::ParmTypeMask</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AllocRegNo {#ae25ae36fd61e9127012f65bc4a4fe652}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::XCOFF::AllocRegNo = 31</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### AuxFileEntNameSize {#a69faad047bdb065d3aa5b6d70c4ac854}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::XCOFF::AuxFileEntNameSize = 14</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### AuxFileHeaderSize32 {#ab572f34f978141c97a476cf2b9c47321}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::XCOFF::AuxFileHeaderSize32 = 72</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### AuxFileHeaderSize64 {#a54f0d697729c046e888f024228a131d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::XCOFF::AuxFileHeaderSize64 = 110</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### AuxFileHeaderSizeShort {#ab54ecf9a406b1567b73e4eeb73732c30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::XCOFF::AuxFileHeaderSizeShort = 28</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### ExceptionSectionEntrySize32 {#a4a50da96dc5db68c648e1dfe7891e695}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::XCOFF::ExceptionSectionEntrySize32 = 6</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### ExceptionSectionEntrySize64 {#a27579d1ecd7d6ad37775b2ee530aa989}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::XCOFF::ExceptionSectionEntrySize64 = 10</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### FileHeaderSize32 {#abc1993feab64c40d80d24a354e56b1f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::XCOFF::FileHeaderSize32 = 20</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### FileHeaderSize64 {#a5003e35e21ae1096539469b9ce31c998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::XCOFF::FileHeaderSize64 = 24</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### FileNamePadSize {#ad2ebde8b446e97a42ec08bab42c605e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::XCOFF::FileNamePadSize = 6</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### NameSize {#a9a03aac7419558e56bd606aeab244118}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::XCOFF::NameSize = 8</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobedecoder/#a9095ead88f0488d321807ce4906ba4d4">llvm::MCPseudoProbeDecoder::buildGUID2FuncDescMap</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a9537162135cca043a3b82f0df2816ed7">llvm::object::Archive::Child::Child</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/csectsectionentry/#acbc7352200a105080886a8652f3b77da">anonymous{XCOFFObjectWriter.cpp}::CsectSectionEntry::CsectSectionEntry</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/dwarfsectionentry/#ae6cfee84ea7b7e4ff3b5ec82038da80b">anonymous{XCOFFObjectWriter.cpp}::DwarfSectionEntry::DwarfSectionEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#a32519abee87d93f315f9da6cbeed31cf">emitPPA1Name</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/exceptionsectionentry/#a5025bde0980a70bcfa30bbbf8b3d7b37">anonymous{XCOFFObjectWriter.cpp}::ExceptionSectionEntry::ExceptionSectionEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#abf04cdbb3bd4b5dc04636289e70ad71f">llvm::object::generateXCOFFFixedNameStringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a005329aa15a8ea20232fa18fc2cba61d">llvm::cl::generic_parser_base::getOptionWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/objectfiletransformer-cpp/#a675f0690b04eaa2c63f91d8e05c75106">getUUID</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/sectionentry/#a6b7a3c345f4636c39dc88bff87582e91">anonymous{XCOFFObjectWriter.cpp}::SectionEntry::SectionEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a73b370d004cc941240050b8048fefb7e">verifyNoteSection</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-xcoffemitter-cpp-/#a85a0cac85a17a54339c7d5f78ae8d608">anonymous{XCOFFEmitter.cpp}::writeName</a>.</p>

</div>
</div>

### RelocationSerializationSize32 {#a14f792635361c0fbd371a68ae0f171a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::XCOFF::RelocationSerializationSize32 = 10</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#adeb534d315c9a390fc59cdef8e9f261a">llvm::object::XCOFFObjectFile::relocations</a>.</p>

</div>
</div>

### RelocationSerializationSize64 {#a476cbe7f235a1f6f83c47ac0f27f98cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::XCOFF::RelocationSerializationSize64 = 14</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#adeb534d315c9a390fc59cdef8e9f261a">llvm::object::XCOFFObjectFile::relocations</a>.</p>

</div>
</div>

### RelocOverflow {#aa4c2e75ac22d396f86f5ed6a29698bd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::XCOFF::RelocOverflow = 65535</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a8b8e8f5c674a66e5bcb4c9554864267d">llvm::object::XCOFFObjectFile::getNumberOfRelocationEntries</a>.</p>

</div>
</div>

### SectionHeaderSize32 {#ac7ebe48b493a2edf775973aa50b5f0f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::XCOFF::SectionHeaderSize32 = 40</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### SectionHeaderSize64 {#a5c1a4c479a2ec0e5b1255fd3d47f8a67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::XCOFF::SectionHeaderSize64 = 72</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>

</div>
</div>

### SymbolTableEntrySize {#ad0cbda82482585d346b65687e2f3a38a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::XCOFF::SymbolTableEntrySize = 18</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#aafddeca2e7b57e958a25b8660f735cf8">llvm::object::XCOFFObjectFile::checkSymbolEntryPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#ac0d87919540a6096c1a44308a603c50e">llvm::object::XCOFFObjectFile::getAdvancedSymbolEntryAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a19321b2c5a24656fe59c193ae2892453">llvm::object::MachOObjectFile::getRelocationSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a7d7c96e485022e0023e9b8eec0257f0e">llvm::object::MachOObjectFile::getSymbolByIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a95439c835232ebad9940e1ccaa72e79a">llvm::object::XCOFFObjectFile::getSymbolByIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a24c6aaf027b70314a4e7cb05b34ab302">llvm::object::MachOObjectFile::getSymbolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a08c80392232d40366a1870cfb8e71c2f">llvm::object::XCOFFObjectFile::getSymbolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a42eea1d21f273fb22eb18192e519aaaa">llvm::object::MachOObjectFile::moveSymbolNext</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aabf498b6cb34cb967c73e3c0c51baee2">llvm::object::MachOObjectFile::symbol_end</a>.</p>

</div>
</div>

### VISIBILITY\_MASK {#a2cdb7f94606325a22e75e209055edb0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::XCOFF::VISIBILITY_MASK = 0x7000</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarbitsettraits-a51563d7941203bed8d21d721434a5e9/#a8d2eb1a9390cd642fe92d62f1e3fe0bf">llvm::yaml::ScalarBitSetTraits&lt; WasmYAML::SymbolFlags &gt;::bitset</a> and <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a26063993809b386ab934532d1af8b56c">llvm::object::XCOFFObjectFile::getSymbolFlags</a>.</p>

</div>
</div>

### XR\_BIASED\_LENGTH\_MASK {#a0709edaad1f22f3b77a92004c31de7ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::XCOFF::XR_BIASED_LENGTH_MASK = 0x3f</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/object/xcoffrelocation/#ac7628f9e0b10c3a71a88985030168481">llvm::object::XCOFFRelocation&lt; AddressType &gt;::getRelocatedLength</a>.</p>

</div>
</div>

### XR\_FIXUP\_INDICATOR\_MASK {#a27ca5b303eeec633f293f39e77aabdc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::XCOFF::XR_FIXUP_INDICATOR_MASK = 0x40</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/object/xcoffrelocation/#a167d10a9af44b34748f357ae382a9d07">llvm::object::XCOFFRelocation&lt; AddressType &gt;::isFixupIndicated</a>.</p>

</div>
</div>

### XR\_SIGN\_INDICATOR\_MASK {#a4291ff459e43ef7efd865792a0ca68a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::XCOFF::XR_SIGN_INDICATOR_MASK = 0x80</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/object/xcoffrelocation/#af06e0a51137d2c98bd0e51566bd916f1">llvm::object::XCOFFRelocation&lt; AddressType &gt;::isRelocationSigned</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/xcoff-h">XCOFF.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/binaryformat/xcoff-cpp">XCOFF.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
