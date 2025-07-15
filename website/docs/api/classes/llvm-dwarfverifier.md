---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfverifier
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DWARFVerifier` Class Reference

<p>A class that verifies DWARF debug information given a DWARF Context. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DWARFVerifier { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">llvm/DebugInfo/DWARF/DWARFVerifier.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86c47eb9aae6d23d8198b7262c6955bc">ReferenceMap</a> = std::map&lt; uint64_t, std::set&lt; uint64_t &gt; &gt;</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa555a8e9d0e824277bb9ed7f0b813639">DWARFVerifier</a> (raw_ostream &amp;S, DWARFContext &amp;D, DIDumpOptions DumpOpts=DIDumpOptions::getForSingleDIE())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4c71e263810db89b9093317f9ffb48c">handleDebugAbbrev</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the information in any of the following sections, if available: .debug_abbrev, debug_abbrev.dwo. <a href="#af4c71e263810db89b9093317f9ffb48c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6eb6cb99b9b63fd2ad94746fe8d7c93">handleDebugInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the information in the .debug_info and .debug_types sections. <a href="#aa6eb6cb99b9b63fd2ad94746fe8d7c93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f68717723fce2a910828afff31f838a">handleDebugCUIndex</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the information in the .debug_cu_index section. <a href="#a9f68717723fce2a910828afff31f838a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cd4ba96c8f51dd40c91522ea21beea2">handleDebugTUIndex</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the information in the .debug_tu_index section. <a href="#a5cd4ba96c8f51dd40c91522ea21beea2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb3d42476a9be199a131e95a1af05de9">handleDebugLine</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the information in the .debug_line section. <a href="#abb3d42476a9be199a131e95a1af05de9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0863e40b075a475f0333b33714fb09d7">handleAccelTables</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the information in accelerator tables, if they exist. <a href="#a0863e40b075a475f0333b33714fb09d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a615332b0161a87347eea3360a5d51410">handleDebugStrOffsets</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the information in the .debug_str_offsets[.dwo]. <a href="#a615332b0161a87347eea3360a5d51410">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5188e82473da31b6460f80c0612b4d79">verifyDebugStrOffsets</a> (std::optional&lt; dwarf::DwarfFormat &gt; LegacyFormat, StringRef SectionName, const DWARFSection &amp;Section, StringRef StrData)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc7f16c0553ca0c637b42907ff64b9f5">summarize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits any aggregate information collected, depending on the dump options. <a href="#acc7f16c0553ca0c637b42907ff64b9f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b60f75e55bf2eeb4faadd736aaa19ae">error</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a950825456e285a3b4e192c54be459420">warn</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae326e056f0e8bc84008859ae1400d407">note</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac03a5c0604119747883b50deb94a1ff1">dump</a> (const DWARFDie &amp;Die, unsigned indent=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd21ecbe19f89c3654a7d71d398e1b4b">verifyAbbrevSection</a> (const DWARFDebugAbbrev *Abbrev)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verifies the abbreviations section. <a href="#acd21ecbe19f89c3654a7d71d398e1b4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6023afbb44ab1aec67d9adfda557c089">verifyUnitHeader</a> (const DWARFDataExtractor DebugInfoData, uint64_t *Offset, unsigned UnitIndex, uint8_t &amp;UnitType, bool &amp;isUnitDWARF64)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verifies the header of a unit in a .debug_info or .debug_types section. <a href="#a6023afbb44ab1aec67d9adfda557c089">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affc17016dfb8dc38f421ec8230e4275b">verifyName</a> (const DWARFDie &amp;Die)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43d71541628cf9201a712c7c87885096">verifyUnitContents</a> (DWARFUnit &amp;Unit, ReferenceMap &amp;UnitLocalReferences, ReferenceMap &amp;CrossUnitReferences)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verifies the header of a unit in a .debug_info or .debug_types section. <a href="#a43d71541628cf9201a712c7c87885096">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef7524bf3893135cc4630faa5705d6d1">verifyUnitSection</a> (const DWARFSection &amp;S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verifies the unit headers and contents in a .debug_info or .debug_types section. <a href="#aef7524bf3893135cc4630faa5705d6d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2adb5fb599eb8dd6c6008eff25988d8a">verifyUnits</a> (const DWARFUnitVector &amp;Units)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96671fd28c34f8ff73a54d0f83bb5ff9">verifyIndex</a> (StringRef Name, DWARFSectionKind SectionKind, StringRef Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9162f879e8abcbd6789434e31cfc154e">verifyDebugInfoCallSite</a> (const DWARFDie &amp;Die)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verifies that a call site entry is nested within a subprogram with a DW_AT_call attribute. <a href="#a9162f879e8abcbd6789434e31cfc154e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6bc3969279fd5bf87168d54bb7fe5f7">verifyDieRanges</a> (const DWARFDie &amp;Die, DieRangeInfo &amp;ParentRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that all Die ranges are valid. <a href="#aa6bc3969279fd5bf87168d54bb7fe5f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcd9f1c358452b6b19d655e965a8f5a3">verifyDebugInfoAttribute</a> (const DWARFDie &amp;Die, DWARFAttribute &amp;AttrValue)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verifies the attribute's DWARF attribute and its value. <a href="#adcd9f1c358452b6b19d655e965a8f5a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af370f91bfbffb2c65b7e853263ffc055">verifyDebugInfoForm</a> (const DWARFDie &amp;Die, DWARFAttribute &amp;AttrValue, ReferenceMap &amp;UnitLocalReferences, ReferenceMap &amp;CrossUnitReferences)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verifies the attribute's DWARF form. <a href="#af370f91bfbffb2c65b7e853263ffc055">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada93ebcea6044a41816d50549fcc55b9">verifyDebugInfoReferences</a> (const ReferenceMap &amp;, llvm::function_ref&lt; DWARFUnit *(uint64_t)&gt; GetUnitForDieOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verifies the all valid references that were found when iterating through all of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> attributes. <a href="#ada93ebcea6044a41816d50549fcc55b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3af2e80120f7af3f06775c9e1aa66ea9">verifyDebugLineStmtOffsets</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the DW_AT_stmt_list encoding and value and ensure that no compile units that have the same DW_AT_stmt_list value. <a href="#a3af2e80120f7af3f06775c9e1aa66ea9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8654bad88b98b03591b59c67621a956f">verifyDebugLineRows</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that all of the rows in the line table are valid. <a href="#a8654bad88b98b03591b59c67621a956f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20e5e8138c16f2dec974468796dc9ce4">verifyAppleAccelTable</a> (const DWARFSection *AccelSection, DataExtractor *StrData, const char *SectionName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that an Apple-style accelerator table is valid. <a href="#a20e5e8138c16f2dec974468796dc9ce4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac59f69a8f529cc0a58fefc9c6e67b259">verifyDebugNamesCULists</a> (const DWARFDebugNames &amp;AccelTable)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c690a08e784e55a14d675ded4a70266">verifyNameIndexBuckets</a> (const DWARFDebugNames::NameIndex &amp;NI, const DataExtractor &amp;StrData)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ede8d21b84b873a707e5c2357abf3ec">verifyNameIndexAbbrevs</a> (const DWARFDebugNames::NameIndex &amp;NI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea496f7acf35b098229bd5e3a1475186">verifyNameIndexAttribute</a> (const DWARFDebugNames::NameIndex &amp;NI, const DWARFDebugNames::Abbrev &amp;Abbr, DWARFDebugNames::AttributeEncoding AttrEnc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb92df3d0e9ee94f81ea8ace2d7fd12b">verifyNameIndexEntries</a> (const DWARFDebugNames::NameIndex &amp;NI, const DWARFDebugNames::NameTableEntry &amp;NTE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ebe3ce274eb96f125f48c08aa01ee92">verifyNameIndexCompleteness</a> (const DWARFDie &amp;Die, const DWARFDebugNames::NameIndex &amp;NI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1971b0cb1f922d864c57412c6e02091a">verifyDebugNames</a> (const DWARFSection &amp;AccelSection, const DataExtractor &amp;StrData)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that the DWARF v5 accelerator table is valid. <a href="#a1971b0cb1f922d864c57412c6e02091a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6607beea4bc89fba6a7910d77ecc301">OS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af63cf150998936b54ad004cf5273e0a5">DCtx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11a0426caa513f05bdb6ea724535b982">DumpOpts</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91932f6d259fa5b270052ada5c2dbc4a">NumDebugLineErrors</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/outputcategoryaggregator">OutputCategoryAggregator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e271462fc2bfd513a75d129dd1aaeb4">ErrorCategory</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7129932efd4237d3c84db98a0637546c">IsObjectFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf917b07ec7b16de432748a81690df30">IsMachOObject</a></td>
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

<p>A class that verifies DWARF debug information given a DWARF Context.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ReferenceMap {#a86c47eb9aae6d23d8198b7262c6955bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DWARFVerifier::ReferenceMap =  std::map&lt;uint64_t, std::set&lt;uint64_t&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DWARFVerifier() {#aa555a8e9d0e824277bb9ed7f0b813639}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFVerifier::DWARFVerifier (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp; D, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts=<a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#a39edcd45ac2f03df8e7c2b8f32a1d19b">DIDumpOptions::getForSingleDIE</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 1090 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#add6a33649e764a95f041d7b8358a019e">llvm::DIDumpOptions::Verbose</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### handleAccelTables() {#a0863e40b075a475f0333b33714fb09d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFVerifier::handleAccelTables ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify the information in accelerator tables, if they exist.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> errors are reported to the stream that was this object was constructed with.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the existing Apple-style accelerator tables verify successfully, false otherwise.</p></dd>
</dl>


<p>Declaration at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 2013 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a7ef02a65817764b3fd99c6ee3bb349f4">llvm::DWARFContext::verify</a>.</p>

</div>
</div>

### handleDebugAbbrev() {#af4c71e263810db89b9093317f9ffb48c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFVerifier::handleDebugAbbrev ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify the information in any of the following sections, if available: .debug_abbrev, debug_abbrev.dwo.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> errors are reported to the stream that was this object was constructed with.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if .debug_abbrev and .debug_abbrev.dwo verify successfully, false otherwise.</p></dd>
</dl>


<p>Declaration at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a25f76b12c29c25b6be56a6053fa97205">llvm::DWARFObject::getAbbrevDWOSection</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a350e8d98dea492e2ca37c2c5a2ec056c">llvm::DWARFObject::getAbbrevSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a7ef02a65817764b3fd99c6ee3bb349f4">llvm::DWARFContext::verify</a>.</p>

</div>
</div>

### handleDebugCUIndex() {#a9f68717723fce2a910828afff31f838a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFVerifier::handleDebugCUIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify the information in the .debug_cu_index section.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> errors are reported to the stream that was this object was constructed with.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the .debug_cu_index verifies successfully, false otherwise.</p></dd>
</dl>


<p>Declaration at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a7ef02a65817764b3fd99c6ee3bb349f4">llvm::DWARFContext::verify</a>.</p>

</div>
</div>

### handleDebugInfo() {#aa6eb6cb99b9b63fd2ad94746fe8d7c93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFVerifier::handleDebugInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify the information in the .debug_info and .debug_types sections.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> errors are reported to the stream that this object was constructed with.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if all sections verify successfully, false otherwise.</p></dd>
</dl>


<p>Declaration at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a77a07541d39f2bbd17b86af2fad3d94d">llvm::DWARFObject::forEachInfoSections</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#aaffaa54a17cd523b80d37dd617e052bb">llvm::DWARFObject::forEachTypesSections</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a7ef02a65817764b3fd99c6ee3bb349f4">llvm::DWARFContext::verify</a>.</p>

</div>
</div>

### handleDebugLine() {#abb3d42476a9be199a131e95a1af05de9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFVerifier::handleDebugLine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify the information in the .debug_line section.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> errors are reported to the stream that was this object was constructed with.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the .debug_line verifies successfully, false otherwise.</p></dd>
</dl>


<p>Declaration at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 1102 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a7ef02a65817764b3fd99c6ee3bb349f4">llvm::DWARFContext::verify</a>.</p>

</div>
</div>

### handleDebugStrOffsets() {#a615332b0161a87347eea3360a5d51410}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFVerifier::handleDebugStrOffsets ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify the information in the .debug_str_offsets[.dwo].</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> errors are reported to the stream that was this object was constructed with.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the .debug_line verifies successfully, false otherwise.</p></dd>
</dl>


<p>Declaration at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 2035 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a733315e35580ca7f322216d7b2a405ee">llvm::DWARFObject::forEachInfoDWOSections</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a10e13073556511543a885ea96b61ff6c">llvm::DWARFDataExtractor::getInitialLength</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a1caf3ec9eba3a658c9c33869801d2edc">llvm::DWARFObject::getStrDWOSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a4567f023a01ee1cc6f3479c6a9ec5953">llvm::DWARFObject::getStrOffsetsDWOSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#acb5051331242a21ba3a3518195e6da38">llvm::DWARFObject::getStrOffsetsSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#afa1fd4842364f0c95e87d1968a4885fb">llvm::DWARFObject::getStrSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a98923ce73981e5171ef246bdcc6fde60">llvm::DataExtractor::getU16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a> and <a href="#a5188e82473da31b6460f80c0612b4d79">verifyDebugStrOffsets</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a7ef02a65817764b3fd99c6ee3bb349f4">llvm::DWARFContext::verify</a>.</p>

</div>
</div>

### handleDebugTUIndex() {#a5cd4ba96c8f51dd40c91522ea21beea2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFVerifier::handleDebugTUIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify the information in the .debug_tu_index section.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> errors are reported to the stream that was this object was constructed with.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the .debug_tu_index verifies successfully, false otherwise.</p></dd>
</dl>


<p>Declaration at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 532 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a52d529efd96454b48642563c5f78e242a635a63c1fbd498b75ee76603878154ca">llvm::DW_SECT_EXT_TYPES</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a7ef02a65817764b3fd99c6ee3bb349f4">llvm::DWARFContext::verify</a>.</p>

</div>
</div>

### summarize() {#acc7f16c0553ca0c637b42907ff64b9f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFVerifier::summarize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits any aggregate information collected, depending on the dump options.</p>

<p>Declaration at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 2184 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a6118bd1b7164f1f8f02470a5cb6a538b">llvm::sys::fs::OF_Text</a> and <a href="/web-llvm/docs/api/classes/llvm/json/object/#a8506070467079c20e5ec2000024d2da9">llvm::json::Object::try_emplace</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a7ef02a65817764b3fd99c6ee3bb349f4">llvm::DWARFContext::verify</a>.</p>

</div>
</div>

### verifyDebugStrOffsets() {#a5188e82473da31b6460f80c0612b4d79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFVerifier::verifyDebugStrOffsets (std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">dwarf::DwarfFormat</a> &gt; LegacyFormat, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> &amp; Section, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> StrData)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 2065 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7530cd22b8952cb41774507dd40c6f3a520d0db389f362bf79ef56ca0af3dcab">llvm::Format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa234436b20c856bcf616330ffcad6939">llvm::dwarf::getDwarfOffsetByteSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba83a013c55b19255697393a10d9165e">llvm::toString</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="#a615332b0161a87347eea3360a5d51410">handleDebugStrOffsets</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### dump() {#ac03a5c0604119747883b50deb94a1ff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; DWARFVerifier::dump (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die, unsigned indent=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 2224 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### error() {#a1b60f75e55bf2eeb4faadd736aaa19ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; DWARFVerifier::error ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 2218 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### note() {#ae326e056f0e8bc84008859ae1400d407}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; DWARFVerifier::note ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 2222 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyAbbrevSection() {#acd21ecbe19f89c3654a7d71d398e1b4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DWARFVerifier::verifyAbbrevSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugabbrev">DWARFDebugAbbrev</a> * Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verifies the abbreviations section.</p>


<p>This function currently checks that: –No abbreviation declaration has more than one attributes with the same name.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Abbrev</td>
<td class="doxyParamItemDescription"><p>Pointer to the abbreviations section we are verifying Abbrev can be a pointer to either .debug_abbrev or debug_abbrev.dwo.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The number of errors that occurred during verification.</p></dd>
</dl>


<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyAppleAccelTable() {#a20e5e8138c16f2dec974468796dc9ce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DWARFVerifier::verifyAppleAccelTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> * AccelSection, <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> * StrData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * SectionName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify that an Apple-style accelerator table is valid.</p>


<p>This function currently checks that:</p>


<ul class="doxyList ">
<li>The fixed part of the header fits in the section</li>
<li>The size of the section is as large as what the header describes</li>
<li>There is at least one atom</li>
<li>The form for each atom is valid</li>
<li>The tag for each <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> in the table is valid</li>
<li>The buckets have a valid index, or they are empty</li>
<li>Each hashdata offset is valid</li>
<li>Each <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> is valid</li>
</ul>

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">AccelSection</td>
<td class="doxyParamItemDescription"><p>pointer to the section containing the acceleration table</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">StrData</td>
<td class="doxyParamItemDescription"><p>pointer to the string section</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/structs/llvm/sectionname"&gt;SectionName&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>the name of the table we're verifying</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The number of errors occurred during verification</p></dd>
</dl>


<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 1110 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyDebugInfoAttribute() {#adcd9f1c358452b6b19d655e965a8f5a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DWARFVerifier::verifyDebugInfoAttribute (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die, <a href="/web-llvm/docs/api/structs/llvm/dwarfattribute">DWARFAttribute</a> &amp; AttrValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verifies the attribute's DWARF attribute and its value.</p>


<p>This function currently checks for:</p>


<ul class="doxyList ">
<li>DW_AT_ranges values is a valid .debug_ranges offset</li>
<li>DW_AT_stmt_list is a valid .debug_line offset</li>
</ul>

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Die</td>
<td class="doxyParamItemDescription"><p>The DWARF <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> that owns the attribute value</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AttrValue</td>
<td class="doxyParamItemDescription"><p>The DWARF attribute value to check</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>NumErrors The number of errors occurred during verification of attributes' values in a unit</p></dd>
</dl>


<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 665 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyDebugInfoCallSite() {#a9162f879e8abcbd6789434e31cfc154e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DWARFVerifier::verifyDebugInfoCallSite (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verifies that a call site entry is nested within a subprogram with a DW_AT_call attribute.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Number of errors that occurred during verification.</p></dd>
</dl>


<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyDebugInfoForm() {#af370f91bfbffb2c65b7e853263ffc055}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DWARFVerifier::verifyDebugInfoForm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die, <a href="/web-llvm/docs/api/structs/llvm/dwarfattribute">DWARFAttribute</a> &amp; AttrValue, ReferenceMap &amp; UnitLocalReferences, ReferenceMap &amp; CrossUnitReferences)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verifies the attribute's DWARF form.</p>


<p>This function currently checks for:</p>


<ul class="doxyList ">
<li>All DW_FORM_ref values that are <a href="/web-llvm/docs/api/namespaces/cu">CU</a> relative have valid <a href="/web-llvm/docs/api/namespaces/cu">CU</a> offsets</li>
<li>All DW_FORM_ref_addr values have valid section offsets</li>
<li>All DW_FORM_strp values have valid .debug_str offsets</li>
</ul>

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Die</td>
<td class="doxyParamItemDescription"><p>The DWARF <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> that owns the attribute value</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AttrValue</td>
<td class="doxyParamItemDescription"><p>The DWARF attribute value to check</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>NumErrors The number of errors occurred during verification of attributes' forms in a unit</p></dd>
</dl>


<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 834 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyDebugInfoReferences() {#ada93ebcea6044a41816d50549fcc55b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DWARFVerifier::verifyDebugInfoReferences (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ReferenceMap &amp; References, <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> *(uint64_t)&gt; GetUnitForDieOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verifies the all valid references that were found when iterating through all of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> attributes.</p>


<p>This function will verify that all references point to DIEs whose <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset matches. This helps to ensure if a DWARF link phase moved things around, that it doesn't create invalid references by failing to relocate <a href="/web-llvm/docs/api/namespaces/cu">CU</a> relative and absolute references.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>NumErrors The number of errors occurred during verification of references for the .debug_info and .debug_types sections</p></dd>
</dl>


<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 916 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyDebugLineRows() {#a8654bad88b98b03591b59c67621a956f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFVerifier::verifyDebugLineRows ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify that all of the rows in the line table are valid.</p>


<p>This function currently checks for:</p>


<ul class="doxyList ">
<li>addresses within a sequence that decrease in value</li>
<li>invalid file indexes</li>
</ul>

<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 988 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyDebugLineStmtOffsets() {#a3af2e80120f7af3f06775c9e1aa66ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFVerifier::verifyDebugLineStmtOffsets ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify the DW_AT_stmt_list encoding and value and ensure that no compile units that have the same DW_AT_stmt_list value.</p>

<p>Declaration at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 941 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyDebugNames() {#a1971b0cb1f922d864c57412c6e02091a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DWARFVerifier::verifyDebugNames (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> &amp; AccelSection, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &amp; StrData)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify that the DWARF v5 accelerator table is valid.</p>


<p>This function currently checks that:</p>


<ul class="doxyList ">
<li>Headers individual Name Indices fit into the section and can be parsed.</li>
<li>Abbreviation tables can be parsed and contain valid index attributes with correct form encodings.</li>
<li>The <a href="/web-llvm/docs/api/namespaces/cu">CU</a> lists reference existing compile units.</li>
<li>The buckets have a valid index, or they are empty.</li>
<li>All names are reachable via the hash table (they have the correct hash, and the hash is in the correct bucket).</li>
<li>Information in the index entries is complete (all required entries are present) and consistent with the debug_info section DIEs.</li>
</ul>

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">AccelSection</td>
<td class="doxyParamItemDescription"><p>section containing the acceleration table</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">StrData</td>
<td class="doxyParamItemDescription"><p>string section</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The number of errors occurred during verification</p></dd>
</dl>


<p>Declaration at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 1957 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyDebugNamesCULists() {#ac59f69a8f529cc0a58fefc9c6e67b259}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DWARFVerifier::verifyDebugNamesCULists (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames">DWARFDebugNames</a> &amp; AccelTable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 1232 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyDieRanges() {#aa6bc3969279fd5bf87168d54bb7fe5f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DWARFVerifier::verifyDieRanges (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die, <a href="/web-llvm/docs/api/structs/llvm/dwarfverifier/dierangeinfo">DieRangeInfo</a> &amp; ParentRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify that all Die ranges are valid.</p>


<p>This function currently checks for:</p>


<ul class="doxyList ">
<li>cases in which lowPC &gt;= highPC</li>
</ul>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Number of errors that occurred during verification.</p></dd>
</dl>


<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyIndex() {#a96671fd28c34f8ff73a54d0f83bb5ff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DWARFVerifier::verifyIndex (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/#a52d529efd96454b48642563c5f78e242">DWARFSectionKind</a> SectionKind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyName() {#affc17016dfb8dc38f421ec8230e4275b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFVerifier::verifyName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyNameIndexAbbrevs() {#a6ede8d21b84b873a707e5c2357abf3ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DWARFVerifier::verifyNameIndexAbbrevs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/nameindex">DWARFDebugNames::NameIndex</a> &amp; NI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 1490 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyNameIndexAttribute() {#aea496f7acf35b098229bd5e3a1475186}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DWARFVerifier::verifyNameIndexAttribute (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/nameindex">DWARFDebugNames::NameIndex</a> &amp; NI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugnames/abbrev">DWARFDebugNames::Abbrev</a> &amp; Abbr, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugnames/attributeencoding">DWARFDebugNames::AttributeEncoding</a> AttrEnc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 1409 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyNameIndexBuckets() {#a3c690a08e784e55a14d675ded4a70266}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DWARFVerifier::verifyNameIndexBuckets (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/nameindex">DWARFDebugNames::NameIndex</a> &amp; NI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &amp; StrData)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 1288 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyNameIndexCompleteness() {#a6ebe3ce274eb96f125f48c08aa01ee92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DWARFVerifier::verifyNameIndexCompleteness (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/nameindex">DWARFDebugNames::NameIndex</a> &amp; NI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 1848 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyNameIndexEntries() {#abb92df3d0e9ee94f81ea8ace2d7fd12b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DWARFVerifier::verifyNameIndexEntries (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/nameindex">DWARFDebugNames::NameIndex</a> &amp; NI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/nametableentry">DWARFDebugNames::NameTableEntry</a> &amp; NTE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 1575 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyUnitContents() {#a43d71541628cf9201a712c7c87885096}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DWARFVerifier::verifyUnitContents (<a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> &amp; Unit, ReferenceMap &amp; UnitLocalReferences, ReferenceMap &amp; CrossUnitReferences)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verifies the header of a unit in a .debug_info or .debug_types section.</p>


<p>This function currently verifies:</p>


<ul class="doxyList ">
<li>The debug info attributes.</li>
<li>The debug info form=s.</li>
<li>The presence of a root <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</li>
<li>That the root <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> is a unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</li>
<li>If a unit type is provided, that the unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> matches the unit type.</li>
<li>The <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> ranges.</li>
<li>That call site entries are only nested within subprograms with a DW_AT_call attribute.</li>
</ul>

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Unit</td>
<td class="doxyParamItemDescription"><p>The DWARF Unit to verify.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The number of errors that occurred during verification.</p></dd>
</dl>


<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyUnitHeader() {#a6023afbb44ab1aec67d9adfda557c089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFVerifier::verifyUnitHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> DebugInfoData, uint64_t * Offset, unsigned UnitIndex, uint8_t &amp; UnitType, bool &amp; isUnitDWARF64)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verifies the header of a unit in a .debug_info or .debug_types section.</p>


<p>This function currently checks for:</p>


<ul class="doxyList ">
<li>Unit is in 32-bit DWARF format. The function can be modified to support 64-bit format.</li>
<li>The DWARF version is valid</li>
<li>The unit type is valid (if unit is in version &gt;=5)</li>
<li>The unit doesn't extend beyond the containing section</li>
<li>The address size is valid</li>
<li>The offset in the .debug_abbrev section is valid</li>
</ul>

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DebugInfoData</td>
<td class="doxyParamItemDescription"><p>The section data</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Offset</td>
<td class="doxyParamItemDescription"><p>A reference to the offset start of the unit. The offset will be updated to point to the next unit in the section</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UnitIndex</td>
<td class="doxyParamItemDescription"><p>The index of the unit to be verified</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UnitType</td>
<td class="doxyParamItemDescription"><p>A reference to the type of the unit</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">isUnitDWARF64</td>
<td class="doxyParamItemDescription"><p>A reference to a flag that shows whether the unit is in 64-bit format.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the header is verified successfully, false otherwise.</p></dd>
</dl>


<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyUnits() {#a2adb5fb599eb8dd6c6008eff25988d8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DWARFVerifier::verifyUnits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector">DWARFUnitVector</a> &amp; Units)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### verifyUnitSection() {#aef7524bf3893135cc4630faa5705d6d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DWARFVerifier::verifyUnitSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verifies the unit headers and contents in a .debug_info or .debug_types section.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">S</td>
<td class="doxyParamItemDescription"><p>The DWARF Section to verify.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The number of errors that occurred during verification.</p></dd>
</dl>


<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

### warn() {#a950825456e285a3b4e192c54be459420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; DWARFVerifier::warn ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 2220 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DCtx {#af63cf150998936b54ad004cf5273e0a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFContext&amp; llvm::DWARFVerifier::DCtx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>.</p>

</div>
</div>

### DumpOpts {#a11a0426caa513f05bdb6ea724535b982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDumpOptions llvm::DWARFVerifier::DumpOpts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>.</p>

</div>
</div>

### ErrorCategory {#a7e271462fc2bfd513a75d129dd1aaeb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputCategoryAggregator llvm::DWARFVerifier::ErrorCategory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>.</p>

</div>
</div>

### IsMachOObject {#adf917b07ec7b16de432748a81690df30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFVerifier::IsMachOObject</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>.</p>

</div>
</div>

### IsObjectFile {#a7129932efd4237d3c84db98a0637546c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFVerifier::IsObjectFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>.</p>

</div>
</div>

### NumDebugLineErrors {#a91932f6d259fa5b270052ada5c2dbc4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFVerifier::NumDebugLineErrors = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>.</p>

</div>
</div>

### OS {#aa6607beea4bc89fba6a7910d77ecc301}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream&amp; llvm::DWARFVerifier::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
