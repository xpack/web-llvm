---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/msf/superblock
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SuperBlock` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::msf::SuperBlock { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfcommon-h">llvm/DebugInfo/MSF/MSFCommon.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6791908bd8cd2e51e4449fe74af55a86">MagicBytes</a>[sizeof(Magic)]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4792a3763eaca59db556d1c9305741cd">BlockSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeef5352d9e16638b909465adff58aff">FreeBlockMapBlock</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1426565e730f0681edc1bfec6d59c5d5">NumBlocks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97837d9ad6f03bda18f25c7079cdb1f5">NumDirectoryBytes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4db179fae3660a4a9d9fcbe1b3797e50">Unknown1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab34f9d84245709af8ed19817a18c59ce">BlockMapAddr</a></td>
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


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfcommon-h">MSFCommon.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### BlockMapAddr {#ab34f9d84245709af8ed19817a18c59ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ulittle32_t llvm::msf::SuperBlock::BlockMapAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfcommon-h">MSFCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a6c98d361786661879be283e8abc78dbf">llvm::msf::MSFBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a6fc9c4f6f23dfa2eb0a1b8feb680ac92">llvm::msf::MSFBuilder::generateLayout</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a06fa30876215b96491f3bb001755c3fa">llvm::msf::validateSuperBlock</a>.</p>

</div>
</div>

### BlockSize {#a4792a3763eaca59db556d1c9305741cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ulittle32_t llvm::msf::SuperBlock::BlockSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfcommon-h">MSFCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a6c98d361786661879be283e8abc78dbf">llvm::msf::MSFBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfilebuilder/#ac8da698510d6ae1fafa8234b0c0b7b92">llvm::pdb::PDBFileBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream/#abb227e93ab0981688803772c461a0aa2">llvm::msf::MappedBlockStream::createDirectoryStream</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream/#a882f086ce986358c3aff75c298823739">llvm::msf::WritableMappedBlockStream::createDirectoryStream</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream/#aca02a882851c4f44d12552f22d5fb9d7">llvm::msf::MappedBlockStream::createFpmStream</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream/#a7b203ff4a29296106a6614438fd462d8">llvm::msf::WritableMappedBlockStream::createFpmStream</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream/#a17d9ec7154acf6bc5c1a090db9ef2936">llvm::msf::MappedBlockStream::createIndexedStream</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream/#a08d954d5d32ab48f6e656250700f8fc2">llvm::msf::WritableMappedBlockStream::createIndexedStream</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a6fc9c4f6f23dfa2eb0a1b8feb680ac92">llvm::msf::MSFBuilder::generateLayout</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a71744b158ac455bfc08863560e6f99a0">llvm::msf::getFpmStreamLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#aa8016724ba063de217ed1ccf4ddc095d">llvm::pdb::PDBFile::parseFileHeaders</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a06fa30876215b96491f3bb001755c3fa">llvm::msf::validateSuperBlock</a>.</p>

</div>
</div>

### FreeBlockMapBlock {#afeef5352d9e16638b909465adff58aff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ulittle32_t llvm::msf::SuperBlock::FreeBlockMapBlock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfcommon-h">MSFCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a6fc9c4f6f23dfa2eb0a1b8feb680ac92">llvm::msf::MSFBuilder::generateLayout</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a06fa30876215b96491f3bb001755c3fa">llvm::msf::validateSuperBlock</a>.</p>

</div>
</div>

### MagicBytes {#a6791908bd8cd2e51e4449fe74af55a86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::msf::SuperBlock::MagicBytes[sizeof(Magic)]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfcommon-h">MSFCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a6fc9c4f6f23dfa2eb0a1b8feb680ac92">llvm::msf::MSFBuilder::generateLayout</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a06fa30876215b96491f3bb001755c3fa">llvm::msf::validateSuperBlock</a>.</p>

</div>
</div>

### NumBlocks {#a1426565e730f0681edc1bfec6d59c5d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ulittle32_t llvm::msf::SuperBlock::NumBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfcommon-h">MSFCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a6c98d361786661879be283e8abc78dbf">llvm::msf::MSFBuilder::commit</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp/#a39370f41a63dc06ba5dc36059e555bc2">commitFpm</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a6fc9c4f6f23dfa2eb0a1b8feb680ac92">llvm::msf::MSFBuilder::generateLayout</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a71744b158ac455bfc08863560e6f99a0">llvm::msf::getFpmStreamLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#aa8016724ba063de217ed1ccf4ddc095d">llvm::pdb::PDBFile::parseFileHeaders</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a06fa30876215b96491f3bb001755c3fa">llvm::msf::validateSuperBlock</a>.</p>

</div>
</div>

### NumDirectoryBytes {#a97837d9ad6f03bda18f25c7079cdb1f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ulittle32_t llvm::msf::SuperBlock::NumDirectoryBytes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfcommon-h">MSFCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a6c98d361786661879be283e8abc78dbf">llvm::msf::MSFBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream/#abb227e93ab0981688803772c461a0aa2">llvm::msf::MappedBlockStream::createDirectoryStream</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream/#a882f086ce986358c3aff75c298823739">llvm::msf::WritableMappedBlockStream::createDirectoryStream</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a6fc9c4f6f23dfa2eb0a1b8feb680ac92">llvm::msf::MSFBuilder::generateLayout</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a06fa30876215b96491f3bb001755c3fa">llvm::msf::validateSuperBlock</a>.</p>

</div>
</div>

### Unknown1 {#a4db179fae3660a4a9d9fcbe1b3797e50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ulittle32_t llvm::msf::SuperBlock::Unknown1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfcommon-h">MSFCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a6fc9c4f6f23dfa2eb0a1b8feb680ac92">llvm::msf::MSFBuilder::generateLayout</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfcommon-h">MSFCommon.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
