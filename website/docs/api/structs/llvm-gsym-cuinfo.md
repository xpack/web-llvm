---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/gsym/cuinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CUInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::gsym::CUInfo { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9a2ecd6a14be08a7a81ef10f869aa31">CUInfo</a> (DWARFContext &amp;DICtx, DWARFCompileUnit *CU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae36dc1e53f9c27b4d8d3d405ae3a0ce1">isHighestAddress</a> (uint64_t Addr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if Addr is the highest address for a given compile unit. <a href="#ae36dc1e53f9c27b4d8d3d405ae3a0ce1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44c3e2e1f1513822fef926de568c244f">DWARFToGSYMFileIndex</a> (GsymCreator &amp;Gsym, uint32_t DwarfFileIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert a DWARF compile unit file index into a GSYM global file index. <a href="#a44c3e2e1f1513822fef926de568c244f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable">DWARFDebugLine::LineTable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38439c35bdf12e0604fe47ea99c69a40">LineTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7feb7ffbce7900677f759ce616e1801">CompDir</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8121591ade8087937f24347b1fefc48">FileCache</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9acfdd97feb3ec5219b6abbf578cf30">Language</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac83698d6d3bd2d12473f769d24496f5c">AddrSize</a> = 0</td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CUInfo() {#ac9a2ecd6a14be08a7a81ef10f869aa31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::gsym::CUInfo::CUInfo (<a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp; DICtx, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DWARFCompileUnit</a> * CU)</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a>.</p>


<p>References <a href="#ac83698d6d3bd2d12473f769d24496f5c">AddrSize</a>, <a href="#ab7feb7ffbce7900677f759ce616e1801">CompDir</a>, <a href="#af8121591ade8087937f24347b1fefc48">FileCache</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a315f90678bfa85d85d71a9dd12d5457a">llvm::DWARFDie::find</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a6b034e23dde3985292359895c41c74f6">llvm::DWARFContext::getLineTableForUnit</a>, <a href="#aa9acfdd97feb3ec5219b6abbf578cf30">Language</a>, <a href="#a38439c35bdf12e0604fe47ea99c69a40">LineTable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ae150cb3561ce0a2979ed60d29301eef7">llvm::dwarf::toUnsigned</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### DWARFToGSYMFileIndex() {#a44c3e2e1f1513822fef926de568c244f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; llvm::gsym::CUInfo::DWARFToGSYMFileIndex (<a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> &amp; Gsym, uint32_t DwarfFileIdx)</td>
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

<p>Convert a DWARF compile unit file index into a GSYM global file index.</p>


<p>Each compile unit in DWARF has its own file table in the line table prologue. GSYM has a single large file table that applies to all files from all of the info in a GSYM file. This function converts between the two and caches and DWARF <a href="/web-llvm/docs/api/namespaces/cu">CU</a> file index that has already been converted so the first client that asks for a compile unit file index will end up doing the conversion, and subsequent clients will get the cached GSYM index.</p>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier/#a4d01b170267924ab4225e3c93ad666c3a7e2c85add6bbb98ae5b91471b11fd9a2">llvm::DILineInfoSpecifier::AbsoluteFilePath</a>, <a href="#ab7feb7ffbce7900677f759ce616e1801">CompDir</a>, <a href="#af8121591ade8087937f24347b1fefc48">FileCache</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#ac9372d27c9fb107c96a7b241848d05ed">llvm::gsym::GsymCreator::insertFile</a> and <a href="#a38439c35bdf12e0604fe47ea99c69a40">LineTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#af08e62850443dbd1f2003aac7845ab3b">convertFunctionLineTable</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a>.</p>

</div>
</div>

### isHighestAddress() {#ae36dc1e53f9c27b4d8d3d405ae3a0ce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gsym::CUInfo::isHighestAddress (uint64_t Addr)</td>
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

<p>Return true if Addr is the highest address for a given compile unit.</p>


<p>The highest address is encoded as -1, of all ones in the address. These high addresses are used by some linkers to indicate that a function has been dead stripped or didn't end up in the linked executable.</p>


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a>.</p>


<p>References <a href="#ac83698d6d3bd2d12473f769d24496f5c">AddrSize</a> and <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AddrSize {#ac83698d6d3bd2d12473f769d24496f5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::gsym::CUInfo::AddrSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a>.</p>


<p>Referenced by <a href="#ac9a2ecd6a14be08a7a81ef10f869aa31">CUInfo</a> and <a href="#ae36dc1e53f9c27b4d8d3d405ae3a0ce1">isHighestAddress</a>.</p>

</div>
</div>

### CompDir {#ab7feb7ffbce7900677f759ce616e1801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::gsym::CUInfo::CompDir</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a>.</p>


<p>Referenced by <a href="#ac9a2ecd6a14be08a7a81ef10f869aa31">CUInfo</a> and <a href="#a44c3e2e1f1513822fef926de568c244f">DWARFToGSYMFileIndex</a>.</p>

</div>
</div>

### FileCache {#af8121591ade8087937f24347b1fefc48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint32_t&gt; llvm::gsym::CUInfo::FileCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a>.</p>


<p>Referenced by <a href="#ac9a2ecd6a14be08a7a81ef10f869aa31">CUInfo</a> and <a href="#a44c3e2e1f1513822fef926de568c244f">DWARFToGSYMFileIndex</a>.</p>

</div>
</div>

### Language {#aa9acfdd97feb3ec5219b6abbf578cf30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::gsym::CUInfo::Language = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a>.</p>


<p>Referenced by <a href="#ac9a2ecd6a14be08a7a81ef10f869aa31">CUInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a>.</p>

</div>
</div>

### LineTable {#a38439c35bdf12e0604fe47ea99c69a40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugLine::LineTable* llvm::gsym::CUInfo::LineTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#af08e62850443dbd1f2003aac7845ab3b">convertFunctionLineTable</a>, <a href="#ac9a2ecd6a14be08a7a81ef10f869aa31">CUInfo</a> and <a href="#a44c3e2e1f1513822fef926de568c244f">DWARFToGSYMFileIndex</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
