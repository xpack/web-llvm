---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarflisttableheader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DWARFListTableHeader` Class

<p>A class representing the header of a list table such as the range list table in the .debug_rnglists section. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DWARFListTableHeader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">llvm/DebugInfo/DWARF/DWARFListTable.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10991e271022263175496ed3f21beba2">DWARFListTableHeader</a> (StringRef SectionName, StringRef ListTypeString)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7f2c25bd49b79a73986af210c45a0ac">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9da67a4898a8a7b6bf3e5bb1230eb145">getHeaderOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6fe384fdfff174af98c88929e5c3f9f">getAddrSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a101998cae50b0fceab1a6da2828a0eb4">getLength</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae975a13057dc42d20b975c343542db04">getVersion</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94ed75554b6e08ef74f9afe5d4ed692d">getOffsetEntryCount</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95eef5385262cc9aa7943ef8cd62e416">getSectionName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad720f15dafa6eb1b8d6af21439898634">getListTypeString</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">dwarf::DwarfFormat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93b517a8989cfb08deb763b3fdec7da2">getFormat</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5878d6c62b444d6d4dc49581e39091e1">dump</a> (DataExtractor Data, raw_ostream &amp;OS, DIDumpOptions DumpOpts={}) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c1d6e1effdc93963e12868a6c193d49">getOffsetEntry</a> (DataExtractor Data, uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a4f52d08af4f50e2e5b0f2ea73fe12f">extract</a> (DWARFDataExtractor Data, uint64_t *OffsetPtr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the table header and the array of offsets. <a href="#a1a4f52d08af4f50e2e5b0f2ea73fe12f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad57f13e13def9a42ea39b34bc323ca01">length</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the length of the table, including the length field, or 0 if the length has not been determined (e.g. <a href="#ad57f13e13def9a42ea39b34bc323ca01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Header</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01e0f558cd9324a7d7a1d9424386899c">HeaderData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">dwarf::DwarfFormat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a065e337a6e99f31b81a9eb0665514c8a">Format</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The table's format, either DWARF32 or DWARF64. <a href="#a065e337a6e99f31b81a9eb0665514c8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a976abf4c54c1cdd05632598573035d7f">HeaderOffset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The offset at which the header (and hence the table) is located within its section. <a href="#a976abf4c54c1cdd05632598573035d7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c143fddcc51b4c3cf3717896045642a">SectionName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The name of the section the list is located in. <a href="#a6c143fddcc51b4c3cf3717896045642a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a767e5743382cbdfa5c067119f124fb63">ListTypeString</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A characterization of the list for dumping purposes, e.g. <a href="#a767e5743382cbdfa5c067119f124fb63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1374388723b168fd14a77c5188d4a7db">getHeaderSize</a> (dwarf::DwarfFormat Format)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size of the table header including the length but not including the offsets. <a href="#a1374388723b168fd14a77c5188d4a7db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f1e95e7e70c3deda94768cb1e966915">getOffsetEntry</a> (DataExtractor Data, uint64_t OffsetTableOffset, dwarf::DwarfFormat Format, uint32_t Index)</td>
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

<p>A class representing the header of a list table such as the range list table in the .debug_rnglists section.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DWARFListTableHeader() {#a10991e271022263175496ed3f21beba2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFListTableHeader::DWARFListTableHeader (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ListTypeString)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#ab7f2c25bd49b79a73986af210c45a0ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFListTableHeader::clear ()</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>

</div>
</div>

### dump() {#a5878d6c62b444d6d4dc49581e39091e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFListTableHeader::dump (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> Data, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarflisttable-cpp">DWARFListTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gaad973adc80fce80cd7fb76d263240436">llvm::dwarf::FormatString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa234436b20c856bcf616330ffcad6939">llvm::dwarf::getDwarfOffsetByteSize</a>, <a href="#a1374388723b168fd14a77c5188d4a7db">getHeaderSize</a>, <a href="#a3c1d6e1effdc93963e12868a6c193d49">getOffsetEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#add6a33649e764a95f041d7b8358a019e">llvm::DIDumpOptions::Verbose</a>.</p>

</div>
</div>

### extract() {#a1a4f52d08af4f50e2e5b0f2ea73fe12f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DWARFListTableHeader::extract (<a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> Data, uint64_t * OffsetPtr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract the table header and the array of offsets.</p>

<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarflisttable-cpp">DWARFListTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e3d3da964f7eb14ef2eabf0c4a08ba5">llvm::c_str</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a62e2d6aade48552d756381ef9336576a">llvm::DWARFContext::checkAddressSizeSupported</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a34b4d38e06d609b405f4a79c223ed8d2">llvm::dwarf::DWARF64</a>, <a href="#a1374388723b168fd14a77c5188d4a7db">getHeaderSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a0b741aef91502fa04c0f5265a58ba45c">llvm::dwarf::getUnitLengthFieldByteSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="#ad57f13e13def9a42ea39b34bc323ca01">length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546baa55e82356e9721946aa9ba954733c6f0">llvm::not_supported</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>.</p>

</div>
</div>

### getAddrSize() {#ae6fe384fdfff174af98c88929e5c3f9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DWARFListTableHeader::getAddrSize ()</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>

</div>
</div>

### getFormat() {#a93b517a8989cfb08deb763b3fdec7da2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::DwarfFormat llvm::DWARFListTableHeader::getFormat ()</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>

</div>
</div>

### getHeaderOffset() {#a9da67a4898a8a7b6bf3e5bb1230eb145}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFListTableHeader::getHeaderOffset ()</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>


<p>Referenced by <a href="#a3c1d6e1effdc93963e12868a6c193d49">getOffsetEntry</a>.</p>

</div>
</div>

### getLength() {#a101998cae50b0fceab1a6da2828a0eb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFListTableHeader::getLength ()</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>

</div>
</div>

### getListTypeString() {#ad720f15dafa6eb1b8d6af21439898634}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DWARFListTableHeader::getListTypeString ()</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>

</div>
</div>

### getOffsetEntry() {#a3c1d6e1effdc93963e12868a6c193d49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::DWARFListTableHeader::getOffsetEntry (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> Data, uint32_t Index)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a9da67a4898a8a7b6bf3e5bb1230eb145">getHeaderOffset</a>, <a href="#a1374388723b168fd14a77c5188d4a7db">getHeaderSize</a> and <a href="#a3c1d6e1effdc93963e12868a6c193d49">getOffsetEntry</a>.</p>


<p>Referenced by <a href="#a5878d6c62b444d6d4dc49581e39091e1">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a5f2cc73e87e1f1a949943a14e14bea4a">llvm::DWARFUnit::getLoclistOffset</a>, <a href="#a3c1d6e1effdc93963e12868a6c193d49">getOffsetEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a29e8a80bfafc6bb58673eacdec89453b">llvm::DWARFUnit::getRnglistOffset</a>.</p>

</div>
</div>

### getOffsetEntryCount() {#a94ed75554b6e08ef74f9afe5d4ed692d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFListTableHeader::getOffsetEntryCount ()</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>

</div>
</div>

### getSectionName() {#a95eef5385262cc9aa7943ef8cd62e416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DWARFListTableHeader::getSectionName ()</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>

</div>
</div>

### getVersion() {#ae975a13057dc42d20b975c343542db04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::DWARFListTableHeader::getVersion ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>

</div>
</div>

### length() {#ad57f13e13def9a42ea39b34bc323ca01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t DWARFListTableHeader::length ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the length of the table, including the length field, or 0 if the length has not been determined (e.g.</p>


<p>because the table has not yet been parsed, or there was a problem in parsing).</p>


<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarflisttable-cpp">DWARFListTable.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a0b741aef91502fa04c0f5265a58ba45c">llvm::dwarf::getUnitLengthFieldByteSize</a>.</p>


<p>Referenced by <a href="#a1a4f52d08af4f50e2e5b0f2ea73fe12f">extract</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Format {#a065e337a6e99f31b81a9eb0665514c8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::DwarfFormat llvm::DWARFListTableHeader::Format</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The table's format, either DWARF32 or DWARF64.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>

</div>
</div>

### HeaderData {#a01e0f558cd9324a7d7a1d9424386899c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Header llvm::DWARFListTableHeader::HeaderData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>

</div>
</div>

### HeaderOffset {#a976abf4c54c1cdd05632598573035d7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFListTableHeader::HeaderOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The offset at which the header (and hence the table) is located within its section.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>

</div>
</div>

### ListTypeString {#a767e5743382cbdfa5c067119f124fb63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DWARFListTableHeader::ListTypeString</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A characterization of the list for dumping purposes, e.g.</p>


<p>"range" or "location".</p>


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>

</div>
</div>

### SectionName {#a6c143fddcc51b4c3cf3717896045642a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DWARFListTableHeader::SectionName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The name of the section the list is located in.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getHeaderSize() {#a1374388723b168fd14a77c5188d4a7db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DWARFListTableHeader::getHeaderSize (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">dwarf::DwarfFormat</a> Format)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the size of the table header including the length but not including the offsets.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a63265bb5719678b401b0abd0ed5ddd76">llvm::dwarf::DWARF32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a34b4d38e06d609b405f4a79c223ed8d2">llvm::dwarf::DWARF64</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a5878d6c62b444d6d4dc49581e39091e1">dump</a>, <a href="#a1a4f52d08af4f50e2e5b0f2ea73fe12f">extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarflisttablebase/#a3ead43c971432ac7c3cdae12c722fea8">llvm::DWARFListTableBase&lt; DWARFListType &gt;::getHeaderSize</a>, <a href="#a3c1d6e1effdc93963e12868a6c193d49">getOffsetEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a29eb6e9604006a962c4d3dc91c6b5c0f">llvm::DWARFUnit::tryExtractDIEsIfNeeded</a>.</p>

</div>
</div>

### getOffsetEntry() {#a0f1e95e7e70c3deda94768cb1e966915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::DWARFListTableHeader::getOffsetEntry (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> Data, uint64_t OffsetTableOffset, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">dwarf::DwarfFormat</a> Format, uint32_t Index)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a34b4d38e06d609b405f4a79c223ed8d2">llvm::dwarf::DWARF64</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarflisttable-cpp">DWARFListTable.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
