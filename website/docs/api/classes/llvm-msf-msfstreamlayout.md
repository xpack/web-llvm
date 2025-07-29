---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/msf/msfstreamlayout
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MSFStreamLayout` Class

<p>Describes the layout of a stream in an MSF layout. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::msf::MSFStreamLayout { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfcommon-h">llvm/DebugInfo/MSF/MSFCommon.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84f5daa710f9284284e3137fe3d93280">Length</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ff01bfb0db5e159e59ecb411d020342">Blocks</a></td>
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

<p>Describes the layout of a stream in an MSF layout.</p>


<p>A "stream" here is defined as any logical unit of data which may be arranged inside the MSF file as a sequence of (possibly discontiguous) blocks. When we want to read from a particular MSF Stream, we fill out a stream layout structure and the reader uses it to determine which blocks in the underlying MSF file contain the data, so that it can be pieced together in the right order.</p>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfcommon-h">MSFCommon.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Blocks {#a8ff01bfb0db5e159e59ecb411d020342}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;support::ulittle32_t&gt; llvm::msf::MSFStreamLayout::Blocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfcommon-h">MSFCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/lineprinter-cpp/#abb45fec195a32d6c9255a3d626d41771">computeBlockRuns</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream/#abb227e93ab0981688803772c461a0aa2">llvm::msf::MappedBlockStream::createDirectoryStream</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream/#a882f086ce986358c3aff75c298823739">llvm::msf::WritableMappedBlockStream::createDirectoryStream</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream/#a17d9ec7154acf6bc5c1a090db9ef2936">llvm::msf::MappedBlockStream::createIndexedStream</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream/#a08d954d5d32ab48f6e656250700f8fc2">llvm::msf::WritableMappedBlockStream::createIndexedStream</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/lineprinter/#acee6d10b60b317467fecb1028dcec0ec">llvm::pdb::LinePrinter::formatMsfStreamBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a71744b158ac455bfc08863560e6f99a0">llvm::msf::getFpmStreamLayout</a> and <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream/#abe3861e116c9da3ce15c4dd46a1bfaf7">llvm::msf::WritableMappedBlockStream::writeBytes</a>.</p>

</div>
</div>

### Length {#a84f5daa710f9284284e3137fe3d93280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::msf::MSFStreamLayout::Length</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfcommon-h">MSFCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/lineprinter-cpp/#abb45fec195a32d6c9255a3d626d41771">computeBlockRuns</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream/#abb227e93ab0981688803772c461a0aa2">llvm::msf::MappedBlockStream::createDirectoryStream</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream/#a882f086ce986358c3aff75c298823739">llvm::msf::WritableMappedBlockStream::createDirectoryStream</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream/#a17d9ec7154acf6bc5c1a090db9ef2936">llvm::msf::MappedBlockStream::createIndexedStream</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream/#a08d954d5d32ab48f6e656250700f8fc2">llvm::msf::WritableMappedBlockStream::createIndexedStream</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/lineprinter/#acee6d10b60b317467fecb1028dcec0ec">llvm::pdb::LinePrinter::formatMsfStreamBlocks</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a71744b158ac455bfc08863560e6f99a0">llvm::msf::getFpmStreamLayout</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/msfcommon-h">MSFCommon.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
