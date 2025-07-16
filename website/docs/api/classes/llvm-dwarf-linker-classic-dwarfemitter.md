---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/classic/dwarfemitter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DwarfEmitter` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfemitter">DwarfEmitter</a> presents interface to generate all debug info tables. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::classic::DwarfEmitter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">llvm/DWARFLinker/Classic/DWARFLinker.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer">DwarfStreamer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/user">User</a> of <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer">DwarfStreamer</a> should call initialization code for <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a>: <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a473a4bb97252d1684fa89be34fdc1fb5">~DwarfEmitter</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24fe5542e4922a3a10f457b966065472">emitSectionContents</a> (StringRef SecData, DebugSectionKind SecKind)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit section named SecName with data SecData. <a href="#a24fe5542e4922a3a10f457b966065472">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac22be6346cf4a7cb375d9232f06c06bf">emitAbbrevs</a> (const std::vector&lt; std::unique_ptr&lt; DIEAbbrev &gt; &gt; &amp;Abbrevs, unsigned DwarfVersion)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the abbreviation table <span class="doxyComputerOutput">Abbrevs</span> to the .debug_abbrev section. <a href="#ac22be6346cf4a7cb375d9232f06c06bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adab31e0f23ffc9a183594d97e07b1edc">emitStrings</a> (const NonRelocatableStringpool &amp;Pool)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the string table described by <span class="doxyComputerOutput">Pool</span> into .debug_str table. <a href="#adab31e0f23ffc9a183594d97e07b1edc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3f99b1ee46c8c75d978f6bcbff61002">emitStringOffsets</a> (const SmallVector&lt; uint64_t &gt; &amp;StringOffsets, uint16_t TargetDWARFVersion)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the debug string offset table described by <span class="doxyComputerOutput">StringOffsets</span> into the .debug_str_offsets table. <a href="#af3f99b1ee46c8c75d978f6bcbff61002">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef54a288882a8834252270272e9dade2">emitLineStrings</a> (const NonRelocatableStringpool &amp;Pool)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the string table described by <span class="doxyComputerOutput">Pool</span> into .debug_line_str table. <a href="#aef54a288882a8834252270272e9dade2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94efe7bbf4c67ddede8b683eac67e13f">emitDebugNames</a> (DWARF5AccelTable &amp;Table)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit DWARF debug names. <a href="#a94efe7bbf4c67ddede8b683eac67e13f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ff8b7d770a47e7cd1af02c3b633c39c">emitAppleNamespaces</a> (AccelTable&lt; AppleAccelTableStaticOffsetData &gt; &amp;Table)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit Apple namespaces accelerator table. <a href="#a5ff8b7d770a47e7cd1af02c3b633c39c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab907c27f57ebb268824f2e083115cfde">emitAppleNames</a> (AccelTable&lt; AppleAccelTableStaticOffsetData &gt; &amp;Table)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit Apple names accelerator table. <a href="#ab907c27f57ebb268824f2e083115cfde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aa9bec8a37ab147ee209714ecadfbba">emitAppleObjc</a> (AccelTable&lt; AppleAccelTableStaticOffsetData &gt; &amp;Table)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit Apple Objective-C accelerator table. <a href="#a6aa9bec8a37ab147ee209714ecadfbba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96c72d0013f4e2d9f8d23228c558044b">emitAppleTypes</a> (AccelTable&lt; AppleAccelTableStaticTypeData &gt; &amp;Table)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit Apple type accelerator table. <a href="#a96c72d0013f4e2d9f8d23228c558044b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad25016a2dffdc1c3b9ee0fc6840665ac">emitDwarfDebugRangeListHeader</a> (const CompileUnit &amp;Unit)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit debug ranges (.debug_ranges, .debug_rnglists) header. <a href="#ad25016a2dffdc1c3b9ee0fc6840665ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36a5db1b18cbeab5f1815012996e5c98">emitDwarfDebugRangeListFragment</a> (const CompileUnit &amp;Unit, const AddressRanges &amp;LinkedRanges, PatchLocation Patch, DebugDieValuePool &amp;AddrPool)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit debug ranges (.debug_ranges, .debug_rnglists) fragment. <a href="#a36a5db1b18cbeab5f1815012996e5c98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9d95c4e33101cac1db3ddcea4187b92">emitDwarfDebugRangeListFooter</a> (const CompileUnit &amp;Unit, MCSymbol *EndLabel)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit debug ranges (.debug_ranges, .debug_rnglists) footer. <a href="#af9d95c4e33101cac1db3ddcea4187b92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf440f1ceee4a884a33c16dc52ddc409">emitDwarfDebugLocListHeader</a> (const CompileUnit &amp;Unit)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit debug locations (.debug_loc, .debug_loclists) header. <a href="#aaf440f1ceee4a884a33c16dc52ddc409">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f05ec7034314e6344d8025069204313">emitDwarfDebugLocListFragment</a> (const CompileUnit &amp;Unit, const DWARFLocationExpressionsVector &amp;LinkedLocationExpression, PatchLocation Patch, DebugDieValuePool &amp;AddrPool)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit debug locations (.debug_loc, .debug_loclists) fragment. <a href="#a8f05ec7034314e6344d8025069204313">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af17184244af807b14728452c1762f892">emitDwarfDebugLocListFooter</a> (const CompileUnit &amp;Unit, MCSymbol *EndLabel)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit debug locations (.debug_loc, .debug_loclists) footer. <a href="#af17184244af807b14728452c1762f892">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b6a582b9b13915c0dd4a553129d47fe">emitDwarfDebugAddrsHeader</a> (const CompileUnit &amp;Unit)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit .debug_addr header. <a href="#a9b6a582b9b13915c0dd4a553129d47fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ae76ec06166693c61669cf13e6b7878">emitDwarfDebugAddrs</a> (const SmallVector&lt; uint64_t &gt; &amp;Addrs, uint8_t AddrSize)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the addresses described by <span class="doxyComputerOutput">Addrs</span> into the .debug_addr section. <a href="#a0ae76ec06166693c61669cf13e6b7878">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae966e547d8ab1f6eac5ac2405499ca03">emitDwarfDebugAddrsFooter</a> (const CompileUnit &amp;Unit, MCSymbol *EndLabel)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit .debug_addr footer. <a href="#ae966e547d8ab1f6eac5ac2405499ca03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4399d9e33796a85525b59bff01978866">emitDwarfDebugArangesTable</a> (const CompileUnit &amp;Unit, const AddressRanges &amp;LinkedRanges)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit .debug_aranges entries for <span class="doxyComputerOutput">Unit</span>. <a href="#a4399d9e33796a85525b59bff01978866">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accea88c1a4f2c0a92bfce6b551d1f215">emitLineTableForUnit</a> (const DWARFDebugLine::LineTable &amp;LineTable, const CompileUnit &amp;Unit, OffsetsStringPool &amp;DebugStrPool, OffsetsStringPool &amp;DebugLineStrPool)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit specified <span class="doxyComputerOutput">LineTable</span> into .debug_line table. <a href="#accea88c1a4f2c0a92bfce6b551d1f215">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab557554187ddc2384f9539605b297fe8">emitPubNamesForUnit</a> (const CompileUnit &amp;Unit)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the .debug_pubnames contribution for <span class="doxyComputerOutput">Unit</span>. <a href="#ab557554187ddc2384f9539605b297fe8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d51c7a7291c5af21ea4bead000cfbc8">emitPubTypesForUnit</a> (const CompileUnit &amp;Unit)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the .debug_pubtypes contribution for <span class="doxyComputerOutput">Unit</span>. <a href="#a1d51c7a7291c5af21ea4bead000cfbc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f4839e52dd1c0844f1dd77d9c766405">emitCIE</a> (StringRef CIEBytes)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a CIE. <a href="#a4f4839e52dd1c0844f1dd77d9c766405">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eb102b85869be7eb1f6792953208e8f">emitFDE</a> (uint32_t CIEOffset, uint32_t AddreSize, uint64_t Address, StringRef Bytes)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an FDE with data <span class="doxyComputerOutput">Bytes</span>. <a href="#a5eb102b85869be7eb1f6792953208e8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4accd66a455c721b157bbbee24908d61">emitCompileUnitHeader</a> (CompileUnit &amp;Unit, unsigned DwarfVersion)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the compilation unit header for <span class="doxyComputerOutput">Unit</span> in the .debug_info section. <a href="#a4accd66a455c721b157bbbee24908d61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3b1ba42dcb6655ef37443ff55166084">emitDIE</a> (DIE &amp;Die)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively emit the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree rooted at <span class="doxyComputerOutput">Die</span>. <a href="#ab3b1ba42dcb6655ef37443ff55166084">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e16c9f1d1e12c1cc34f48b1685e7aee">emitMacroTables</a> (DWARFContext *Context, const Offset2UnitMap &amp;UnitMacroMap, OffsetsStringPool &amp;StringPool)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit all available macro tables(DWARFv4 and DWARFv5). <a href="#a7e16c9f1d1e12c1cc34f48b1685e7aee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfd8de3ff2915299328dfc181059df82">getLineSectionSize</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of generated .debug_line section. <a href="#acfd8de3ff2915299328dfc181059df82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53067ceac7717aa179f145bce55bebf3">getFrameSectionSize</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of generated .debug_frame section. <a href="#a53067ceac7717aa179f145bce55bebf3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec3690f06eb6d05f3251f31662013bdf">getRangesSectionSize</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of generated .debug_ranges section. <a href="#aec3690f06eb6d05f3251f31662013bdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a5fb637935f59cf9b6272c15c839a5d">getRngListsSectionSize</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of generated .debug_rnglists section. <a href="#a6a5fb637935f59cf9b6272c15c839a5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a446e90f0e2c54019e7b50dea102e9e98">getDebugInfoSectionSize</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of generated .debug_info section. <a href="#a446e90f0e2c54019e7b50dea102e9e98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4a26c79ad68d507db32e5f46c666059">getDebugMacInfoSectionSize</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of generated .debug_macinfo section. <a href="#ab4a26c79ad68d507db32e5f46c666059">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d02aed9a8e095673cfbfa5b24a4bb1f">getDebugMacroSectionSize</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of generated .debug_macro section. <a href="#a2d02aed9a8e095673cfbfa5b24a4bb1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac30203a717ab2f38e4774edbc3ca7e7c">getLocListsSectionSize</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of generated .debug_loclists section. <a href="#ac30203a717ab2f38e4774edbc3ca7e7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18b7bda6538e71fabb1b18ad8f8117b8">getDebugAddrSectionSize</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of generated .debug_addr section. <a href="#a18b7bda6538e71fabb1b18ad8f8117b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade208d5b2f48329fdb8992fe300c240f">finish</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the file to the disk. <a href="#ade208d5b2f48329fdb8992fe300c240f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfemitter">DwarfEmitter</a> presents interface to generate all debug info tables.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~DwarfEmitter() {#a473a4bb97252d1684fa89be34fdc1fb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::dwarf_linker::classic::DwarfEmitter::~DwarfEmitter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitAbbrevs() {#ac22be6346cf4a7cb375d9232f06c06bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitAbbrevs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dieabbrev">DIEAbbrev</a> &gt; &gt; &amp; Abbrevs, unsigned DwarfVersion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the abbreviation table <span class="doxyComputerOutput">Abbrevs</span> to the .debug_abbrev section.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitAppleNames() {#ab907c27f57ebb268824f2e083115cfde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitAppleNames (<a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata">AppleAccelTableStaticOffsetData</a> &gt; &amp; Table)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit Apple names accelerator table.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitAppleNamespaces() {#a5ff8b7d770a47e7cd1af02c3b633c39c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitAppleNamespaces (<a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata">AppleAccelTableStaticOffsetData</a> &gt; &amp; Table)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit Apple namespaces accelerator table.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitAppleObjc() {#a6aa9bec8a37ab147ee209714ecadfbba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitAppleObjc (<a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata">AppleAccelTableStaticOffsetData</a> &gt; &amp; Table)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit Apple Objective-C accelerator table.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitAppleTypes() {#a96c72d0013f4e2d9f8d23228c558044b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitAppleTypes (<a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestatictypedata">AppleAccelTableStaticTypeData</a> &gt; &amp; Table)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit Apple type accelerator table.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitCIE() {#a4f4839e52dd1c0844f1dd77d9c766405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitCIE (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CIEBytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a CIE.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitCompileUnitHeader() {#a4accd66a455c721b157bbbee24908d61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitCompileUnitHeader (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, unsigned DwarfVersion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the compilation unit header for <span class="doxyComputerOutput">Unit</span> in the .debug_info section.</p>


<p>As a side effect, this also switches the current Dwarf version of the MC layer to the one of U.getOrigUnit().</p>


<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitDebugNames() {#a94efe7bbf4c67ddede8b683eac67e13f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitDebugNames (<a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltable">DWARF5AccelTable</a> &amp; Table)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit DWARF debug names.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitDIE() {#ab3b1ba42dcb6655ef37443ff55166084}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively emit the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree rooted at <span class="doxyComputerOutput">Die</span>.</p>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitDwarfDebugAddrs() {#a0ae76ec06166693c61669cf13e6b7878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitDwarfDebugAddrs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint64_t &gt; &amp; Addrs, uint8_t AddrSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the addresses described by <span class="doxyComputerOutput">Addrs</span> into the .debug_addr section.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitDwarfDebugAddrsFooter() {#ae966e547d8ab1f6eac5ac2405499ca03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitDwarfDebugAddrsFooter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * EndLabel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit .debug_addr footer.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitDwarfDebugAddrsHeader() {#a9b6a582b9b13915c0dd4a553129d47fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MCSymbol * llvm::dwarf_linker::classic::DwarfEmitter::emitDwarfDebugAddrsHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit .debug_addr header.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitDwarfDebugArangesTable() {#a4399d9e33796a85525b59bff01978866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitDwarfDebugArangesTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/addressranges">AddressRanges</a> &amp; LinkedRanges)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit .debug_aranges entries for <span class="doxyComputerOutput">Unit</span>.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitDwarfDebugLocListFooter() {#af17184244af807b14728452c1762f892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitDwarfDebugLocListFooter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * EndLabel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit debug locations (.debug_loc, .debug_loclists) footer.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitDwarfDebugLocListFragment() {#a8f05ec7034314e6344d8025069204313}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitDwarfDebugLocListFragment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#afc9a8659aea188ea36273a12a45b5929">DWARFLocationExpressionsVector</a> &amp; LinkedLocationExpression, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/patchlocation">PatchLocation</a> Patch, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#a1ea4442463c620b2bef27de747ab16d7">DebugDieValuePool</a> &amp; AddrPool)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit debug locations (.debug_loc, .debug_loclists) fragment.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitDwarfDebugLocListHeader() {#aaf440f1ceee4a884a33c16dc52ddc409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MCSymbol * llvm::dwarf_linker::classic::DwarfEmitter::emitDwarfDebugLocListHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit debug locations (.debug_loc, .debug_loclists) header.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitDwarfDebugRangeListFooter() {#af9d95c4e33101cac1db3ddcea4187b92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitDwarfDebugRangeListFooter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * EndLabel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit debug ranges (.debug_ranges, .debug_rnglists) footer.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitDwarfDebugRangeListFragment() {#a36a5db1b18cbeab5f1815012996e5c98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitDwarfDebugRangeListFragment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/addressranges">AddressRanges</a> &amp; LinkedRanges, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/patchlocation">PatchLocation</a> Patch, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#a1ea4442463c620b2bef27de747ab16d7">DebugDieValuePool</a> &amp; AddrPool)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit debug ranges (.debug_ranges, .debug_rnglists) fragment.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitDwarfDebugRangeListHeader() {#ad25016a2dffdc1c3b9ee0fc6840665ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MCSymbol * llvm::dwarf_linker::classic::DwarfEmitter::emitDwarfDebugRangeListHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit debug ranges (.debug_ranges, .debug_rnglists) header.</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitFDE() {#a5eb102b85869be7eb1f6792953208e8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitFDE (uint32_t CIEOffset, uint32_t AddreSize, uint64_t Address, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Bytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit an FDE with data <span class="doxyComputerOutput">Bytes</span>.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>.</p>

</div>
</div>

### emitLineStrings() {#aef54a288882a8834252270272e9dade2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitLineStrings (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/nonrelocatablestringpool">NonRelocatableStringpool</a> &amp; Pool)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the string table described by <span class="doxyComputerOutput">Pool</span> into .debug_line_str table.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitLineTableForUnit() {#accea88c1a4f2c0a92bfce6b551d1f215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitLineTableForUnit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable">DWARFDebugLine::LineTable</a> &amp; LineTable, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; DebugStrPool, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; DebugLineStrPool)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit specified <span class="doxyComputerOutput">LineTable</span> into .debug_line table.</p>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitMacroTables() {#a7e16c9f1d1e12c1cc34f48b1685e7aee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitMacroTables (<a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> * Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#a883bd25ef016f5881dd3f8573823f0b0">Offset2UnitMap</a> &amp; UnitMacroMap, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; StringPool)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit all available macro tables(DWARFv4 and DWARFv5).</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <span class="doxyComputerOutput">UnitMacroMap</span> to get compilation unit by macro table offset. Side effects: Fill <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/stringpool">StringPool</a></span> with macro strings, update DW_AT_macro_info, DW_AT_macros attributes for corresponding compile units.</p>


<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitPubNamesForUnit() {#ab557554187ddc2384f9539605b297fe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitPubNamesForUnit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the .debug_pubnames contribution for <span class="doxyComputerOutput">Unit</span>.</p>

<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitPubTypesForUnit() {#a1d51c7a7291c5af21ea4bead000cfbc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitPubTypesForUnit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the .debug_pubtypes contribution for <span class="doxyComputerOutput">Unit</span>.</p>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitSectionContents() {#a24fe5542e4922a3a10f457b966065472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitSectionContents (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SecData, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24">DebugSectionKind</a> SecKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit section named SecName with data SecData.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitStringOffsets() {#af3f99b1ee46c8c75d978f6bcbff61002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitStringOffsets (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint64_t &gt; &amp; StringOffsets, uint16_t TargetDWARFVersion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the debug string offset table described by <span class="doxyComputerOutput">StringOffsets</span> into the .debug_str_offsets table.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### emitStrings() {#adab31e0f23ffc9a183594d97e07b1edc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::emitStrings (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/nonrelocatablestringpool">NonRelocatableStringpool</a> &amp; Pool)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the string table described by <span class="doxyComputerOutput">Pool</span> into .debug_str table.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### finish() {#ade208d5b2f48329fdb8992fe300c240f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::classic::DwarfEmitter::finish ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the file to the disk.</p>

<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### getDebugAddrSectionSize() {#a18b7bda6538e71fabb1b18ad8f8117b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::dwarf_linker::classic::DwarfEmitter::getDebugAddrSectionSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of generated .debug_addr section.</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### getDebugInfoSectionSize() {#a446e90f0e2c54019e7b50dea102e9e98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::dwarf_linker::classic::DwarfEmitter::getDebugInfoSectionSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of generated .debug_info section.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### getDebugMacInfoSectionSize() {#ab4a26c79ad68d507db32e5f46c666059}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::dwarf_linker::classic::DwarfEmitter::getDebugMacInfoSectionSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of generated .debug_macinfo section.</p>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### getDebugMacroSectionSize() {#a2d02aed9a8e095673cfbfa5b24a4bb1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::dwarf_linker::classic::DwarfEmitter::getDebugMacroSectionSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of generated .debug_macro section.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### getFrameSectionSize() {#a53067ceac7717aa179f145bce55bebf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::dwarf_linker::classic::DwarfEmitter::getFrameSectionSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of generated .debug_frame section.</p>

<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### getLineSectionSize() {#acfd8de3ff2915299328dfc181059df82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::dwarf_linker::classic::DwarfEmitter::getLineSectionSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of generated .debug_line section.</p>

<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### getLocListsSectionSize() {#ac30203a717ab2f38e4774edbc3ca7e7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::dwarf_linker::classic::DwarfEmitter::getLocListsSectionSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of generated .debug_loclists section.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### getRangesSectionSize() {#aec3690f06eb6d05f3251f31662013bdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::dwarf_linker::classic::DwarfEmitter::getRangesSectionSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of generated .debug_ranges section.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### getRngListsSectionSize() {#a6a5fb637935f59cf9b6272c15c839a5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::dwarf_linker::classic::DwarfEmitter::getRngListsSectionSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of generated .debug_rnglists section.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
