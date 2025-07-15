---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/gsym/header
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Header` Struct Reference

<p>The GSYM header. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::gsym::Header { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/header-h">llvm/DebugInfo/GSYM/Header.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae34d310282ea598de25cd12feb15d653">checkForError</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a header is valid and return an error if anything is wrong. <a href="#ae34d310282ea598de25cd12feb15d653">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a976c8e49991502be5186b73cdd2d3589">encode</a> (FileWriter &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode this object into <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> stream. <a href="#a976c8e49991502be5186b73cdd2d3589">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47ef9e8af3bae7caacb43b16108d03a1">Magic</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The magic bytes should be set to GSYM_MAGIC. <a href="#a47ef9e8af3bae7caacb43b16108d03a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05be47ccf18c7b121da8d5e2e00c4007">Version</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The version can number determines how the header is decoded and how each <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5ee">InfoType</a> in <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> is encoded/decoded. <a href="#a05be47ccf18c7b121da8d5e2e00c4007">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34f83b8e1b9a91f2e306a9d0df969a5b">AddrOffSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The size in bytes of each address offset in the address offsets table. <a href="#a34f83b8e1b9a91f2e306a9d0df969a5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae25e8b83cd8416417a33dd9267cbf4ce">UUIDSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The size in bytes of the <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a847f9d797fd06f1d451476d6362a6a41">UUID</a> encoded in the "UUID" member. <a href="#ae25e8b83cd8416417a33dd9267cbf4ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3a0fa4fd0587b1bcb2e1979bbe3c747">BaseAddress</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The 64 bit base address that all address offsets in the address offsets table are relative to. <a href="#af3a0fa4fd0587b1bcb2e1979bbe3c747">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae56c0257076bd0b9c1a4f42671eb03f0">NumAddresses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of addresses stored in the address offsets table. <a href="#ae56c0257076bd0b9c1a4f42671eb03f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f8bfadcb63e2bec5eb4e2f897e1c8f8">StrtabOffset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The file relative offset of the start of the string table for strings contained in the GSYM file. <a href="#a9f8bfadcb63e2bec5eb4e2f897e1c8f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf7da00d25cd0b1ec0e7105d1f15fcaf">StrtabSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The size in bytes of the string table. <a href="#aaf7da00d25cd0b1ec0e7105d1f15fcaf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa843b4319bce6f5a623cf632db244399">UUID</a>[GSYM_MAX_UUID_SIZE]</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a847f9d797fd06f1d451476d6362a6a41">UUID</a> of the original executable file. <a href="#aa843b4319bce6f5a623cf632db244399">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/header">Header</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e167f635eebf81005b8ac7290195165">decode</a> (DataExtractor &amp;Data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode an object from a binary data stream. <a href="#a3e167f635eebf81005b8ac7290195165">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The GSYM header.</p>


<p>The GSYM header is found at the start of a stand alone GSYM file, or as the first bytes in a section when GSYM is contained in a section of an executable file (<a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a>, mach-o, <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a>).</p>


<p>The structure is encoded exactly as it appears in the structure definition with no gaps between members. Alignment should not change from system to system as the members were laid out so that they shouldn't align differently on different architectures.</p>


<p>When endianness of the system loading a GSYM file matches, the file can be mmap'ed in and a pointer to the header can be cast to the first bytes of the file (stand alone GSYM file) or section data (GSYM in a section). When endianness is swapped, the <a href="#a3e167f635eebf81005b8ac7290195165">Header::decode()</a> function should be used to decode the header.</p>


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/header-h">Header.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### checkForError() {#ae34d310282ea598de25cd12feb15d653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error Header::checkForError ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a header is valid and return an error if anything is wrong.</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> the header and detect any errors.</p>


<p>This function can be used prior to encoding a header to ensure it is valid, or after decoding a header to ensure it is valid and supported.</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> a correctly byte swapped header for errors:</p>


<ul class="doxyList ">
<li>check magic value</li>
<li>check that version number is supported</li>
<li>check that the address offset size is supported</li>
<li>check that the <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a847f9d797fd06f1d451476d6362a6a41">UUID</a> size is valid</li>
</ul>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An error if anything is wrong in the header, or <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">Error::success()</a> if there are no errors.</p></dd>
</dl>


<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/header-h">Header.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/header-cpp">Header.cpp</a>.</p>


<p>References <a href="#a34f83b8e1b9a91f2e306a9d0df969a5b">AddrOffSize</a>, <a href="#ae34d310282ea598de25cd12feb15d653">checkForError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a75a03ed9f8e173b2e923681761f4a3ca">llvm::gsym::GSYM_MAGIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a37e27ac6f9e18bd3c2736669ac656062">llvm::gsym::GSYM_MAX_UUID_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a7feb3a53720bdec8d221e5ccc76d8e94">llvm::gsym::GSYM_VERSION</a>, <a href="#a47ef9e8af3bae7caacb43b16108d03a1">Magic</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#ae25e8b83cd8416417a33dd9267cbf4ce">UUIDSize</a> and <a href="#a05be47ccf18c7b121da8d5e2e00c4007">Version</a>.</p>


<p>Referenced by <a href="#ae34d310282ea598de25cd12feb15d653">checkForError</a> and <a href="#a976c8e49991502be5186b73cdd2d3589">encode</a>.</p>

</div>
</div>

### encode() {#a976c8e49991502be5186b73cdd2d3589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error Header::encode (<a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encode this object into <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> stream.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">O</td>
<td class="doxyParamItemDescription"><p>The binary stream to write the data to at the current file position.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An error object that indicates success or failure of the encoding process.</p></dd>
</dl>


<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/header-h">Header.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/header-cpp">Header.cpp</a>.</p>


<p>References <a href="#a34f83b8e1b9a91f2e306a9d0df969a5b">AddrOffSize</a>, <a href="#af3a0fa4fd0587b1bcb2e1979bbe3c747">BaseAddress</a>, <a href="#ae34d310282ea598de25cd12feb15d653">checkForError</a>, <a href="#a47ef9e8af3bae7caacb43b16108d03a1">Magic</a>, <a href="#ae56c0257076bd0b9c1a4f42671eb03f0">NumAddresses</a>, <a href="#a9f8bfadcb63e2bec5eb4e2f897e1c8f8">StrtabOffset</a>, <a href="#aaf7da00d25cd0b1ec0e7105d1f15fcaf">StrtabSize</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#aa843b4319bce6f5a623cf632db244399">UUID</a>, <a href="#ae25e8b83cd8416417a33dd9267cbf4ce">UUIDSize</a> and <a href="#a05be47ccf18c7b121da8d5e2e00c4007">Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#a9ede3510dd3c4a79112fd4ff9048e04b">llvm::gsym::GsymCreator::encode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AddrOffSize {#a34f83b8e1b9a91f2e306a9d0df969a5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::gsym::Header::AddrOffSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The size in bytes of each address offset in the address offsets table.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/header-h">Header.h</a>.</p>


<p>Referenced by <a href="#ae34d310282ea598de25cd12feb15d653">checkForError</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#a9ede3510dd3c4a79112fd4ff9048e04b">llvm::gsym::GsymCreator::encode</a> and <a href="#a976c8e49991502be5186b73cdd2d3589">encode</a>.</p>

</div>
</div>

### BaseAddress {#af3a0fa4fd0587b1bcb2e1979bbe3c747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::gsym::Header::BaseAddress</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The 64 bit base address that all address offsets in the address offsets table are relative to.</p>


<p>Storing a full 64 bit address allows our address offsets table to be smaller on disk.</p>


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/header-h">Header.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#a9ede3510dd3c4a79112fd4ff9048e04b">llvm::gsym::GsymCreator::encode</a> and <a href="#a976c8e49991502be5186b73cdd2d3589">encode</a>.</p>

</div>
</div>

### Magic {#a47ef9e8af3bae7caacb43b16108d03a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::gsym::Header::Magic</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The magic bytes should be set to GSYM_MAGIC.</p>


<p>This helps detect if a file is a GSYM file by scanning the first 4 bytes of a file or section. This value might appear byte swapped</p>


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/header-h">Header.h</a>.</p>


<p>Referenced by <a href="#ae34d310282ea598de25cd12feb15d653">checkForError</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#a9ede3510dd3c4a79112fd4ff9048e04b">llvm::gsym::GsymCreator::encode</a> and <a href="#a976c8e49991502be5186b73cdd2d3589">encode</a>.</p>

</div>
</div>

### NumAddresses {#ae56c0257076bd0b9c1a4f42671eb03f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::gsym::Header::NumAddresses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of addresses stored in the address offsets table.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/header-h">Header.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a2c4724c06d85bc195e23612de85f6774">llvm::gsym::GsymReader::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#a9ede3510dd3c4a79112fd4ff9048e04b">llvm::gsym::GsymCreator::encode</a> and <a href="#a976c8e49991502be5186b73cdd2d3589">encode</a>.</p>

</div>
</div>

### StrtabOffset {#a9f8bfadcb63e2bec5eb4e2f897e1c8f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::gsym::Header::StrtabOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The file relative offset of the start of the string table for strings contained in the GSYM file.</p>


<p>If the GSYM in contained in a stand alone file this will be the file offset of the start of the string table. If the GSYM is contained in a section within an executable file, this can be the offset of the first string used in the GSYM file and can possibly span one or more executable string tables. This allows the strings to share string tables in an <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> or mach-o file.</p>


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/header-h">Header.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#a9ede3510dd3c4a79112fd4ff9048e04b">llvm::gsym::GsymCreator::encode</a> and <a href="#a976c8e49991502be5186b73cdd2d3589">encode</a>.</p>

</div>
</div>

### StrtabSize {#aaf7da00d25cd0b1ec0e7105d1f15fcaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::gsym::Header::StrtabSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The size in bytes of the string table.</p>


<p>For a stand alone GSYM file, this will be the exact size in bytes of the string table. When the GSYM data is in a section within an executable file, this size can span one or more sections that contains strings. This allows any strings that are already stored in the executable file to be re-used, and any extra strings could be added to another string table and the string table offset and size can be set to span all needed string tables.</p>


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/header-h">Header.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#a9ede3510dd3c4a79112fd4ff9048e04b">llvm::gsym::GsymCreator::encode</a> and <a href="#a976c8e49991502be5186b73cdd2d3589">encode</a>.</p>

</div>
</div>

### UUID {#aa843b4319bce6f5a623cf632db244399}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::gsym::Header::UUID[GSYM_MAX_UUID_SIZE]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a847f9d797fd06f1d451476d6362a6a41">UUID</a> of the original executable file.</p>


<p>This is stored to allow matching a GSYM file to an executable file when symbolication is required. Only the first "UUIDSize" bytes of the <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a847f9d797fd06f1d451476d6362a6a41">UUID</a> are valid. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> bytes in the <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a847f9d797fd06f1d451476d6362a6a41">UUID</a> value that appear after the first UUIDSize bytes should be set to zero.</p>


<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/header-h">Header.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#a9ede3510dd3c4a79112fd4ff9048e04b">llvm::gsym::GsymCreator::encode</a> and <a href="#a976c8e49991502be5186b73cdd2d3589">encode</a>.</p>

</div>
</div>

### UUIDSize {#ae25e8b83cd8416417a33dd9267cbf4ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::gsym::Header::UUIDSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The size in bytes of the <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a847f9d797fd06f1d451476d6362a6a41">UUID</a> encoded in the "UUID" member.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/header-h">Header.h</a>.</p>


<p>Referenced by <a href="#ae34d310282ea598de25cd12feb15d653">checkForError</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#a9ede3510dd3c4a79112fd4ff9048e04b">llvm::gsym::GsymCreator::encode</a> and <a href="#a976c8e49991502be5186b73cdd2d3589">encode</a>.</p>

</div>
</div>

### Version {#a05be47ccf18c7b121da8d5e2e00c4007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::gsym::Header::Version</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The version can number determines how the header is decoded and how each <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5ee">InfoType</a> in <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> is encoded/decoded.</p>


<p>As version numbers increase, "Magic" and "Version" members should always appear at offset zero and 4 respectively to ensure clients figure out if they can parse the format.</p>


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/header-h">Header.h</a>.</p>


<p>Referenced by <a href="#ae34d310282ea598de25cd12feb15d653">checkForError</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#a9ede3510dd3c4a79112fd4ff9048e04b">llvm::gsym::GsymCreator::encode</a> and <a href="#a976c8e49991502be5186b73cdd2d3589">encode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### decode() {#a3e167f635eebf81005b8ac7290195165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; Header &gt; Header::decode (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &amp; Data)</td>
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

<p>Decode an object from a binary data stream.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Data</td>
<td class="doxyParamItemDescription"><p>The binary stream to read the data from. This object must have the data for the object starting at offset zero. The data can contain more data than needed.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A <a href="/web-llvm/docs/api/structs/llvm/gsym/header">Header</a> or an error describing the issue that was encountered during decoding.</p></dd>
</dl>


<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/header-h">Header.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/header-cpp">Header.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a37e27ac6f9e18bd3c2736669ac656062">llvm::gsym::GSYM_MAX_UUID_SIZE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/header-h">Header.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/header-cpp">Header.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
