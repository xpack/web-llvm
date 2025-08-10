---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/classic/dwarfstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DwarfStreamer` Class

<p><a href="/web-llvm/docs/api/classes/llvm/user">User</a> of <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer">DwarfStreamer</a> should call initialization code for <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a>: <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::classic::DwarfStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">llvm/DWARFLinker/Classic/DWARFStreamer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfemitter">DwarfEmitter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfemitter">DwarfEmitter</a> presents interface to generate all debug info tables. <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfemitter/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b68ff50e1e1f073a066600407489bd8">DwarfStreamer</a> (DWARFLinkerBase::OutputFileType OutFileType, raw_pwrite_stream &amp;OutFile, DWARFLinkerBase::MessageHandlerTy Warning)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46d9f23594282ba2f47f20b2f43664e0">~DwarfStreamer</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7472bfb367d052f75ef1e00fa660be70">init</a> (Triple TheTriple, StringRef Swift5ReflectionSegmentName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa219176178ec28609335b3abbc253984">finish</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the file to the disk. <a href="#aa219176178ec28609335b3abbc253984">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac68bbd56c519d8bbc0528004f2510ccd">getAsmPrinter</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfa6fc1d4ec200c99cce6bd03bb41dee">switchToDebugInfoSection</a> (unsigned DwarfVersion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the current output section to debug_info and change the MC Dwarf version to <span class="doxyComputerOutput">DwarfVersion</span>. <a href="#adfa6fc1d4ec200c99cce6bd03bb41dee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae734c9b910054fa45f339c64f6a08d25">emitCompileUnitHeader</a> (CompileUnit &amp;Unit, unsigned DwarfVersion) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the compilation unit header for <span class="doxyComputerOutput">Unit</span> in the debug_info section. <a href="#ae734c9b910054fa45f339c64f6a08d25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e1d9b11ad28b498cafb76889dc09239">emitDIE</a> (DIE &amp;Die) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively emit the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree rooted at <span class="doxyComputerOutput">Die</span>. <a href="#a3e1d9b11ad28b498cafb76889dc09239">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa83137369d2d17f1a01722c9dbc1c625">emitAbbrevs</a> (const std::vector&lt; std::unique_ptr&lt; DIEAbbrev &gt; &gt; &amp;Abbrevs, unsigned DwarfVersion) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the abbreviation table <span class="doxyComputerOutput">Abbrevs</span> to the debug_abbrev section. <a href="#aa83137369d2d17f1a01722c9dbc1c625">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83ef4419b677602809ece02714515fdc">emitSectionContents</a> (StringRef SecData, DebugSectionKind SecKind) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit contents of section SecName From Obj. <a href="#a83ef4419b677602809ece02714515fdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e79865080aad82450af13818c5bccde">emitStrings</a> (const NonRelocatableStringpool &amp;Pool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the string table described by <span class="doxyComputerOutput">Pool</span> into .debug_str table. <a href="#a4e79865080aad82450af13818c5bccde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66752f73169dfa9247fe4f788c08e49e">emitStringOffsets</a> (const SmallVector&lt; uint64_t &gt; &amp;StringOffset, uint16_t TargetDWARFVersion) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the debug string offset table described by <span class="doxyComputerOutput">StringOffsets</span> into the .debug_str_offsets table. <a href="#a66752f73169dfa9247fe4f788c08e49e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6af42c1280c80b31795c26ab738637d6">emitLineStrings</a> (const NonRelocatableStringpool &amp;Pool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the string table described by <span class="doxyComputerOutput">Pool</span> into .debug_line_str table. <a href="#a6af42c1280c80b31795c26ab738637d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb71b6f90fe6bf50b3ff54cfc7092077">emitSwiftAST</a> (StringRef Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the swift_ast section stored in <span class="doxyComputerOutput">Buffer</span>. <a href="#aeb71b6f90fe6bf50b3ff54cfc7092077">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74e0e8c4a75f7e6b6be6c976a5738a0f">emitSwiftReflectionSection</a> (llvm::binaryformat::Swift5ReflectionSectionKind ReflSectionKind, StringRef Buffer, uint32_t Alignment, uint32_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the swift reflection section stored in <span class="doxyComputerOutput">Buffer</span>. <a href="#a74e0e8c4a75f7e6b6be6c976a5738a0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76c644f5c1f4d8496ba7bb40c27fc2a0">emitDwarfDebugRangeListHeader</a> (const CompileUnit &amp;Unit) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit debug ranges(.debug_ranges, .debug_rnglists) header. <a href="#a76c644f5c1f4d8496ba7bb40c27fc2a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdee70a37b2b5891f138329f0001b6eb">emitDwarfDebugRangeListFragment</a> (const CompileUnit &amp;Unit, const AddressRanges &amp;LinkedRanges, PatchLocation Patch, DebugDieValuePool &amp;AddrPool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit debug ranges(.debug_ranges, .debug_rnglists) fragment. <a href="#abdee70a37b2b5891f138329f0001b6eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af326d9b46d855973c0312e0b9b9df0ee">emitDwarfDebugRangeListFooter</a> (const CompileUnit &amp;Unit, MCSymbol *EndLabel) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit debug ranges(.debug_ranges, .debug_rnglists) footer. <a href="#af326d9b46d855973c0312e0b9b9df0ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab5961481095fc72e2dcce4049c04eac">emitDwarfDebugLocListHeader</a> (const CompileUnit &amp;Unit) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit debug locations(.debug_loc, .debug_loclists) header. <a href="#aab5961481095fc72e2dcce4049c04eac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6666e068e3dc915e7ad702b462af9ac6">emitDwarfDebugAddrsHeader</a> (const CompileUnit &amp;Unit) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit .debug_addr header. <a href="#a6666e068e3dc915e7ad702b462af9ac6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6c40412d73534e0fecf36d3e6497c81">emitDwarfDebugAddrs</a> (const SmallVector&lt; uint64_t &gt; &amp;Addrs, uint8_t AddrSize) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the addresses described by <span class="doxyComputerOutput">Addrs</span> into .debug_addr table. <a href="#ad6c40412d73534e0fecf36d3e6497c81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14bf077390ead4e3e4c772fe6c56d98b">emitDwarfDebugAddrsFooter</a> (const CompileUnit &amp;Unit, MCSymbol *EndLabel) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit .debug_addr footer. <a href="#a14bf077390ead4e3e4c772fe6c56d98b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a481a4c85572fe722d12161a938db2e55">emitDwarfDebugLocListFragment</a> (const CompileUnit &amp;Unit, const DWARFLocationExpressionsVector &amp;LinkedLocationExpression, PatchLocation Patch, DebugDieValuePool &amp;AddrPool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit debug ranges(.debug_loc, .debug_loclists) fragment. <a href="#a481a4c85572fe722d12161a938db2e55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56a0f9d54eda9f50af120e6eebb76681">emitDwarfDebugLocListFooter</a> (const CompileUnit &amp;Unit, MCSymbol *EndLabel) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit debug ranges(.debug_loc, .debug_loclists) footer. <a href="#a56a0f9d54eda9f50af120e6eebb76681">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b5a6fd6b5c5ce109d0c54457d817460">emitDwarfDebugArangesTable</a> (const CompileUnit &amp;Unit, const AddressRanges &amp;LinkedRanges) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit .debug_aranges entries for <span class="doxyComputerOutput">Unit</span>. <a href="#a1b5a6fd6b5c5ce109d0c54457d817460">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a099674e6a2c5c5b6d556d797cd44e6c1">getRangesSectionSize</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of generated .debug_ranges section. <a href="#a099674e6a2c5c5b6d556d797cd44e6c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7950d1f93783df9a2c0ee7a2ddd30052">getRngListsSectionSize</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of generated .debug_rnglists section. <a href="#a7950d1f93783df9a2c0ee7a2ddd30052">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad43ae71d8137d5a78d559644f17eb162">emitLineTableForUnit</a> (const DWARFDebugLine::LineTable &amp;LineTable, const CompileUnit &amp;Unit, OffsetsStringPool &amp;DebugStrPool, OffsetsStringPool &amp;DebugLineStrPool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit .debug_line table entry for specified <span class="doxyComputerOutput">LineTable</span>. <a href="#ad43ae71d8137d5a78d559644f17eb162">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54c96d59b67461c55d80da75a5367c89">getLineSectionSize</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of generated .debug_line section. <a href="#a54c96d59b67461c55d80da75a5367c89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab87c037c75932ed1aaa7e2972807fada">emitPubNamesForUnit</a> (const CompileUnit &amp;Unit) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the .debug_pubnames contribution for <span class="doxyComputerOutput">Unit</span>. <a href="#ab87c037c75932ed1aaa7e2972807fada">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1c6aa4a712ba25fc48031640b19f690">emitPubTypesForUnit</a> (const CompileUnit &amp;Unit) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the .debug_pubtypes contribution for <span class="doxyComputerOutput">Unit</span>. <a href="#ac1c6aa4a712ba25fc48031640b19f690">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e84332e336e7ded64bc2acb2bfc66a7">emitCIE</a> (StringRef CIEBytes) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a CIE. <a href="#a7e84332e336e7ded64bc2acb2bfc66a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3efa9219c5d461ff2e67802f8ea6aa7">emitFDE</a> (uint32_t CIEOffset, uint32_t AddreSize, uint64_t Address, StringRef Bytes) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an FDE with data <span class="doxyComputerOutput">Bytes</span>. <a href="#ab3efa9219c5d461ff2e67802f8ea6aa7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53a46254268dfc1ac0c64478894c1ca2">emitDebugNames</a> (DWARF5AccelTable &amp;Table) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit DWARF debug names. <a href="#a53a46254268dfc1ac0c64478894c1ca2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc88ed9d4746a98c3e718ba452fb7a2f">emitAppleNamespaces</a> (AccelTable&lt; AppleAccelTableStaticOffsetData &gt; &amp;Table) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit Apple namespaces accelerator table. <a href="#adc88ed9d4746a98c3e718ba452fb7a2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86e9803ff74cb07df7513b71e6c6a8f3">emitAppleNames</a> (AccelTable&lt; AppleAccelTableStaticOffsetData &gt; &amp;Table) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit Apple names accelerator table. <a href="#a86e9803ff74cb07df7513b71e6c6a8f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc0be8158bd04374e0649a131315bfc3">emitAppleObjc</a> (AccelTable&lt; AppleAccelTableStaticOffsetData &gt; &amp;Table) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit Apple Objective-C accelerator table. <a href="#adc0be8158bd04374e0649a131315bfc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a362d35ef2b2a4c791c03222f1bdd1c45">emitAppleTypes</a> (AccelTable&lt; AppleAccelTableStaticTypeData &gt; &amp;Table) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit Apple type accelerator table. <a href="#a362d35ef2b2a4c791c03222f1bdd1c45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9101ef55c2f1d70d82c7acdd94ba2b6">getFrameSectionSize</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of generated .debug_frame section. <a href="#ae9101ef55c2f1d70d82c7acdd94ba2b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0703b36dce3be3f918ad55530d2a774c">getDebugInfoSectionSize</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of generated .debug_info section. <a href="#a0703b36dce3be3f918ad55530d2a774c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abafe025d32ef832754a24bfedf614be1">getDebugMacInfoSectionSize</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of generated .debug_macinfo section. <a href="#abafe025d32ef832754a24bfedf614be1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46f98097ee23555c85fec17ca49186d9">getDebugMacroSectionSize</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of generated .debug_macro section. <a href="#a46f98097ee23555c85fec17ca49186d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ed87efa200b9505f5eebf2c68ca9914">getLocListsSectionSize</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of generated .debug_loclists section. <a href="#a7ed87efa200b9505f5eebf2c68ca9914">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54eee596df09d1f2f74a7ac5c4575ec1">getDebugAddrSectionSize</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of generated .debug_addr section. <a href="#a54eee596df09d1f2f74a7ac5c4575ec1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade966339669e6b2fad9f486468044008">emitMacroTables</a> (DWARFContext *Context, const Offset2UnitMap &amp;UnitMacroMap, OffsetsStringPool &amp;StringPool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit all available macro tables(DWARFv4 and DWARFv5). <a href="#ade966339669e6b2fad9f486468044008">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a74a7c7dfa7e4bc33a4f0904ca3d289">warn</a> (const Twine &amp;Warning, StringRef Context="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac39ec3315ec21dacfea52c5265f6eaf7">getMCSection</a> (DebugSectionKind SecKind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f4711416c07614a7eb2e4e476a83d01">emitMacroTableImpl</a> (const DWARFDebugMacro *MacroTable, const Offset2UnitMap &amp;UnitMacroMap, OffsetsStringPool &amp;StringPool, uint64_t &amp;OutOffset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5456633cd53a787d4ae7f566adc412ef">emitDwarfDebugRangesTableFragment</a> (const CompileUnit &amp;Unit, const AddressRanges &amp;LinkedRanges, PatchLocation Patch)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit piece of .debug_ranges for <span class="doxyComputerOutput">LinkedRanges</span>. <a href="#a5456633cd53a787d4ae7f566adc412ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8b1d60fe32fb00adaf8c7d4afb95db5">emitDwarfDebugRngListsTableFragment</a> (const CompileUnit &amp;Unit, const AddressRanges &amp;LinkedRanges, PatchLocation Patch, DebugDieValuePool &amp;AddrPool)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit piece of .debug_rnglists for <span class="doxyComputerOutput">LinkedRanges</span>. <a href="#ae8b1d60fe32fb00adaf8c7d4afb95db5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b0f1bbc8c054f7c9208ed958d6cbc95">emitDwarfDebugLocTableFragment</a> (const CompileUnit &amp;Unit, const DWARFLocationExpressionsVector &amp;LinkedLocationExpression, PatchLocation Patch)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit piece of .debug_loc for <span class="doxyComputerOutput">LinkedRanges</span>. <a href="#a7b0f1bbc8c054f7c9208ed958d6cbc95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac876d6a838333f26fdd979f9ff76f118">emitDwarfDebugLocListsTableFragment</a> (const CompileUnit &amp;Unit, const DWARFLocationExpressionsVector &amp;LinkedLocationExpression, PatchLocation Patch, DebugDieValuePool &amp;AddrPool)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit piece of .debug_loclists for <span class="doxyComputerOutput">LinkedRanges</span>. <a href="#ac876d6a838333f26fdd979f9ff76f118">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abafcc16d7961e532d0660f75e9aa0d4c">emitPubSectionForUnit</a> (MCSection *Sec, StringRef Name, const CompileUnit &amp;Unit, const std::vector&lt; CompileUnit::AccelInfo &gt; &amp;Names)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the pubnames or pubtypes section contribution for <span class="doxyComputerOutput">Unit</span> into <span class="doxyComputerOutput">Sec</span>. <a href="#abafcc16d7961e532d0660f75e9aa0d4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/line/#ga6bbbda77751245651d8a0b64406dd40a">emitLineTablePrologue</a> (const DWARFDebugLine::Prologue &amp;P, OffsetsStringPool &amp;DebugStrPool, OffsetsStringPool &amp;DebugLineStrPool)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/line/#ga97a657954ce847425a852e577f83b113">emitLineTableString</a> (const DWARFDebugLine::Prologue &amp;P, const DWARFFormValue &amp;String, OffsetsStringPool &amp;DebugStrPool, OffsetsStringPool &amp;DebugLineStrPool)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/line/#ga75f24ccccb80b2ec795ac0e5148c72f9">emitLineTableProloguePayload</a> (const DWARFDebugLine::Prologue &amp;P, OffsetsStringPool &amp;DebugStrPool, OffsetsStringPool &amp;DebugLineStrPool)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/line/#gab9eb50627b554fd10d2438155d8601ee">emitLineTablePrologueV2IncludeAndFileTable</a> (const DWARFDebugLine::Prologue &amp;P, OffsetsStringPool &amp;DebugStrPool, OffsetsStringPool &amp;DebugLineStrPool)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/line/#ga4f6ac912f85770e18de12b1fbff1d0f2">emitLineTablePrologueV5IncludeAndFileTable</a> (const DWARFDebugLine::Prologue &amp;P, OffsetsStringPool &amp;DebugStrPool, OffsetsStringPool &amp;DebugLineStrPool)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/line/#ga779f98344ec2bd623e8f88b2244d36aa">emitLineTableRows</a> (const DWARFDebugLine::LineTable &amp;LineTable, MCSymbol *LineEndSym, unsigned AddressByteSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/line/#ga9ce50e5791a6b42e431dd4a36c0966a0">emitIntOffset</a> (uint64_t Offset, dwarf::DwarfFormat Format, uint64_t &amp;SectionSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/line/#gabbfb6a9e55c2f7737c37e4f0ad7ecc6c">emitLabelDifference</a> (const MCSymbol *Hi, const MCSymbol *Lo, dwarf::DwarfFormat Format, uint64_t &amp;SectionSize)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a439a4903d72f44c38e8cd6e08ea95e4b">OutFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The output file we stream the linked Dwarf to. <a href="#a439a4903d72f44c38e8cd6e08ea95e4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#aba62c3e12b7c341d64f21e98325f4082">DWARFLinker::OutputFileType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a370dd06f8b06f2b3eb5126b6bcd33490">OutFileType</a> = <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#aba62c3e12b7c341d64f21e98325f4082a497031794414a552435f90151ac3b54b">DWARFLinker::OutputFileType::Object</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af197027ae801858b975e8a1a8b60cbe3">RangesSectionSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0781284590ad0315a2da58e580b95ad7">RngListsSectionSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a643e186d7a644d410132c7a3830114db">LocSectionSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb3e3f8383dfb12d577ad645bbc833a5">LocListsSectionSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3af70d972a8db3c47e366b84ef8ae1ad">LineSectionSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81469679ad3bfef6c3bd0d82d2fa838f">FrameSectionSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaca7be836f59cb0943ad42705697cfb7">DebugInfoSectionSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe0b33c01e01fabbda33dbf15f9b4f08">MacInfoSectionSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e688929e9f72c36396862f002ef7307">MacroSectionSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2383db640b1da77d6cc19c873e7b7b3">AddrSectionSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3d736f4408562fc9beeac61412032fb">StrOffsetSectionSize</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; EmittedUnit &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69e4138a3744aaa894fcd9a7ce90ab1e">EmittedUnits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a6171d1affe838c4595f5bc1306ca5749">DWARFLinkerBase::MessageHandlerTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30c03d3a761b65fc9ba67708228c9a25">WarningHandler</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; MCRegisterInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#ga8b86af68d3a346a41087f11c76bafc5d">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; MCAsmInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#ga2d38ac9c1c0e7e8d4686eb477df98d9b">MAI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; MCObjectFileInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#ga677a17c49d3b5177dc9a5f988bc925bc">MOFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; MCContext &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#ga39293e81e0b60520e49259bb36104d83">MC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MCAsmBackend *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#ga44d1657a550f15b45c240b3f2cacc1a4">MAB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; MCInstrInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#ga4ef2a68e8de64d42397c43dd7a64ac5d">MII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; MCSubtargetInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#ga29e5c01cb7264b4910207998f4222441">MSTI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MCInstPrinter *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#ga10238af746d5f44cde6aa24ffdb7cca6">MIP</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MCCodeEmitter *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#gabaea29d074c55dfeb27e32668f755906">MCE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MCStreamer *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#ga993d3bcef22c895ff7f00aeb4baaf1d4">MS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; TargetMachine &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#ga22645706eb23c8796cebcc2be6ee0d03">TM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; AsmPrinter &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#ga1b8dbaed8344933f104422ef5a95f44a">Asm</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer">DwarfStreamer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fa9dc1022d6e4b200632808fe58b99a">createStreamer</a> (const Triple &amp;TheTriple, DWARFLinkerBase::OutputFileType FileType, raw_pwrite_stream &amp;OutFile, DWARFLinkerBase::MessageHandlerTy Warning)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/user">User</a> of <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer">DwarfStreamer</a> should call initialization code for <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a>:</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/#a2c23d23778140065e285b5263d7d905a">InitializeAllTargetInfos()</a>; <a href="/web-llvm/docs/api/namespaces/llvm/#a162474ccafa6e8ccf58b2b60e7c63845">InitializeAllTargetMCs()</a>; <a href="/web-llvm/docs/api/namespaces/llvm/#ad27eabc8391834dce3a68261f8a334db">InitializeAllTargets()</a>; <a href="/web-llvm/docs/api/namespaces/llvm/#af12a586afbaec83aa9cd8b7e9ab0c116">InitializeAllAsmPrinters()</a>; The Dwarf streaming logic.</p>


<p>All interactions with the MC layer that is used to build the debug information binary representation are handled in this class.</p>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DwarfStreamer() {#a3b68ff50e1e1f073a066600407489bd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::classic::DwarfStreamer::DwarfStreamer (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#aba62c3e12b7c341d64f21e98325f4082">DWARFLinkerBase::OutputFileType</a> OutFileType, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; OutFile, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a6171d1affe838c4595f5bc1306ca5749">DWARFLinkerBase::MessageHandlerTy</a> Warning)</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DwarfStreamer() {#a46d9f23594282ba2f47f20b2f43664e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::dwarf_linker::classic::DwarfStreamer::~DwarfStreamer ()</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitAbbrevs() {#aa83137369d2d17f1a01722c9dbc1c625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitAbbrevs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dieabbrev">DIEAbbrev</a> &gt; &gt; &amp; Abbrevs, unsigned DwarfVersion)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the abbreviation table <span class="doxyComputerOutput">Abbrevs</span> to the debug_abbrev section.</p>


<p>Emit the <span class="doxyComputerOutput">Abbrevs</span> array as the shared abbreviation table for the linked Dwarf file.</p>


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitAppleNames() {#a86e9803ff74cb07df7513b71e6c6a8f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitAppleNames (<a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata">AppleAccelTableStaticOffsetData</a> &gt; &amp; Table)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit Apple names accelerator table.</p>

<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa78b3092a3008359b197ec6e29618b9d">llvm::emitAppleAccelTable</a>.</p>

</div>
</div>

### emitAppleNamespaces() {#adc88ed9d4746a98c3e718ba452fb7a2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitAppleNamespaces (<a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata">AppleAccelTableStaticOffsetData</a> &gt; &amp; Table)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit Apple namespaces accelerator table.</p>

<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa78b3092a3008359b197ec6e29618b9d">llvm::emitAppleAccelTable</a>.</p>

</div>
</div>

### emitAppleObjc() {#adc0be8158bd04374e0649a131315bfc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitAppleObjc (<a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata">AppleAccelTableStaticOffsetData</a> &gt; &amp; Table)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit Apple Objective-C accelerator table.</p>

<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa78b3092a3008359b197ec6e29618b9d">llvm::emitAppleAccelTable</a>.</p>

</div>
</div>

### emitAppleTypes() {#a362d35ef2b2a4c791c03222f1bdd1c45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitAppleTypes (<a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestatictypedata">AppleAccelTableStaticTypeData</a> &gt; &amp; Table)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit Apple type accelerator table.</p>

<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa78b3092a3008359b197ec6e29618b9d">llvm::emitAppleAccelTable</a>.</p>

</div>
</div>

### emitCIE() {#a7e84332e336e7ded64bc2acb2bfc66a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitCIE (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CIEBytes)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a CIE.</p>


<p>Emit a CIE into the debug_frame section.</p>


<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 1254 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### emitCompileUnitHeader() {#ae734c9b910054fa45f339c64f6a08d25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitCompileUnitHeader (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, unsigned DwarfVersion)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the compilation unit header for <span class="doxyComputerOutput">Unit</span> in the debug_info section.</p>


<p>As a side effect, this also switches the current Dwarf version of the MC layer to the one of U.getOrigUnit().</p>


<p>A Dwarf 4 section header is encoded as: uint32_t Unit length (omitting this field) uint16_t Version uint32_t Abbreviation table offset uint8_t Address size Leading to a total of 11 bytes.</p>


<p>A Dwarf 5 section header is encoded as: uint32_t Unit length (omitting this field) uint16_t Version uint8_t Unit type uint8_t Address size uint32_t Abbreviation table offset Leading to a total of 12 bytes.</p>


<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>Reference <a href="#adfa6fc1d4ec200c99cce6bd03bb41dee">switchToDebugInfoSection</a>.</p>

</div>
</div>

### emitDebugNames() {#a53a46254268dfc1ac0c64478894c1ca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitDebugNames (<a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltable">DWARF5AccelTable</a> &amp; Table)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit DWARF debug names.</p>

<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dieinteger/#af397b05376454122495039750b702064">llvm::DIEInteger::BestForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4372f5cbd92647d1f4f90fcdb8a5474">llvm::emitDWARF5AccelTable</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a>.</p>

</div>
</div>

### emitDIE() {#a3e1d9b11ad28b498cafb76889dc09239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively emit the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree rooted at <span class="doxyComputerOutput">Die</span>.</p>

<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/die/#a260b23f8c0c3b34a94b27886008630f9">llvm::DIE::getSize</a>.</p>

</div>
</div>

### emitDwarfDebugAddrs() {#ad6c40412d73534e0fecf36d3e6497c81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitDwarfDebugAddrs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint64_t &gt; &amp; Addrs, uint8_t AddrSize)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the addresses described by <span class="doxyComputerOutput">Addrs</span> into .debug_addr table.</p>


<p>Emit the .debug_addr addresses stored in <span class="doxyComputerOutput">Addrs</span>.</p>


<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 736 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitDwarfDebugAddrsFooter() {#a14bf077390ead4e3e4c772fe6c56d98b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitDwarfDebugAddrsFooter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * EndLabel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit .debug_addr footer.</p>

<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 746 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitDwarfDebugAddrsHeader() {#a6666e068e3dc915e7ad702b462af9ac6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * DwarfStreamer::emitDwarfDebugAddrsHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit .debug_addr header.</p>

<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 706 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitDwarfDebugArangesTable() {#a1b5a6fd6b5c5ce109d0c54457d817460}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitDwarfDebugArangesTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/addressranges">AddressRanges</a> &amp; LinkedRanges)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit .debug_aranges entries for <span class="doxyComputerOutput">Unit</span>.</p>

<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4a16f4c7a994d0fdb234317b16888302c1">llvm::dwarf::DW_ARANGES_VERSION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99cdcecbadc13087f087c61809bb44f1">llvm::offsetToAlignment</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

### emitDwarfDebugLocListFooter() {#a56a0f9d54eda9f50af120e6eebb76681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitDwarfDebugLocListFooter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * EndLabel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit debug ranges(.debug_loc, .debug_loclists) footer.</p>


<p>Emit debug locations(.debug_loc, .debug_loclists) footer.</p>


<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitDwarfDebugLocListFragment() {#a481a4c85572fe722d12161a938db2e55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitDwarfDebugLocListFragment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#afc9a8659aea188ea36273a12a45b5929">DWARFLocationExpressionsVector</a> &amp; LinkedLocationExpression, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/patchlocation">PatchLocation</a> Patch, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#a1ea4442463c620b2bef27de747ab16d7">DebugDieValuePool</a> &amp; AddrPool)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit debug ranges(.debug_loc, .debug_loclists) fragment.</p>


<p>Emit debug locations(.debug_loc, .debug_loclists) fragment.</p>


<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 639 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitDwarfDebugLocListHeader() {#aab5961481095fc72e2dcce4049c04eac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * DwarfStreamer::emitDwarfDebugLocListHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit debug locations(.debug_loc, .debug_loclists) header.</p>

<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitDwarfDebugRangeListFooter() {#af326d9b46d855973c0312e0b9b9df0ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitDwarfDebugRangeListFooter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * EndLabel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit debug ranges(.debug_ranges, .debug_rnglists) footer.</p>

<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitDwarfDebugRangeListFragment() {#abdee70a37b2b5891f138329f0001b6eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitDwarfDebugRangeListFragment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/addressranges">AddressRanges</a> &amp; LinkedRanges, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/patchlocation">PatchLocation</a> Patch, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#a1ea4442463c620b2bef27de747ab16d7">DebugDieValuePool</a> &amp; AddrPool)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit debug ranges(.debug_ranges, .debug_rnglists) fragment.</p>

<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitDwarfDebugRangeListHeader() {#a76c644f5c1f4d8496ba7bb40c27fc2a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * DwarfStreamer::emitDwarfDebugRangeListHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit debug ranges(.debug_ranges, .debug_rnglists) header.</p>

<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitFDE() {#ab3efa9219c5d461ff2e67802f8ea6aa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitFDE (uint32_t CIEOffset, uint32_t AddrSize, uint64_t Address, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FDEBytes)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit an FDE with data <span class="doxyComputerOutput">Bytes</span>.</p>


<p>Emit a FDE into the debug_frame section.</p>


<p><span class="doxyComputerOutput">FDEBytes</span> contains the FDE data without the length, CIE offset and address which will be replaced with the parameter values.</p>


<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 1264 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### emitLineStrings() {#a6af42c1280c80b31795c26ab738637d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitLineStrings (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/nonrelocatablestringpool">NonRelocatableStringpool</a> &amp; Pool)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the string table described by <span class="doxyComputerOutput">Pool</span> into .debug_line_str table.</p>


<p>Emit the debug_line_str section stored in <span class="doxyComputerOutput">Pool</span>.</p>


<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/nonrelocatablestringpool/#a648f04a20283c7dd28b9fad17ba85fac">llvm::NonRelocatableStringpool::getEntriesForEmission</a>.</p>

</div>
</div>

### emitLineTableForUnit() {#ad43ae71d8137d5a78d559644f17eb162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitLineTableForUnit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable">DWARFDebugLine::LineTable</a> &amp; LineTable, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; DebugStrPool, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; DebugLineStrPool)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit .debug_line table entry for specified <span class="doxyComputerOutput">LineTable</span>.</p>

<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 810 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4adc3aedef0caeccf6d845a430da6d3f8d">llvm::dwarf::DW_LENGTH_DWARF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a34b4d38e06d609b405f4a79c223ed8d2">llvm::dwarf::DWARF64</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams/#a1240b89e7d83c52d9b2dc05ad8824269">llvm::dwarf::FormParams::Format</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue/#ad1a98ac8bd44a05c862c20b5963957d4">llvm::DWARFDebugLine::Prologue::FormParams</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#aec306fc919df207db6e700f491872d71">llvm::DWARFDebugLine::LineTable::Prologue</a>.</p>

</div>
</div>

### emitMacroTables() {#ade966339669e6b2fad9f486468044008}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitMacroTables (<a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> * Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#a883bd25ef016f5881dd3f8573823f0b0">Offset2UnitMap</a> &amp; UnitMacroMap, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; StringPool)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit all available macro tables(DWARFv4 and DWARFv5).</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <span class="doxyComputerOutput">UnitMacroMap</span> to get compilation unit by macro table offset. Side effects: Fill <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/stringpool">StringPool</a></span> with macro strings, update DW_AT_macro_info, DW_AT_macros attributes for corresponding compile units.</p>


<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 1275 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### emitPubNamesForUnit() {#ab87c037c75932ed1aaa7e2972807fada}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitPubNamesForUnit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the .debug_pubnames contribution for <span class="doxyComputerOutput">Unit</span>.</p>


<p>Emit .debug_pubnames for <span class="doxyComputerOutput">Unit</span>.</p>


<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 1242 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitPubTypesForUnit() {#ac1c6aa4a712ba25fc48031640b19f690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitPubTypesForUnit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the .debug_pubtypes contribution for <span class="doxyComputerOutput">Unit</span>.</p>


<p>Emit .debug_pubtypes for <span class="doxyComputerOutput">Unit</span>.</p>


<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 1248 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitSectionContents() {#a83ef4419b677602809ece02714515fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitSectionContents (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SecData, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24">DebugSectionKind</a> SecKind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit contents of section SecName From Obj.</p>

<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitStringOffsets() {#a66752f73169dfa9247fe4f788c08e49e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitStringOffsets (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint64_t &gt; &amp; StringOffset, uint16_t TargetDWARFVersion)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the debug string offset table described by <span class="doxyComputerOutput">StringOffsets</span> into the .debug_str_offsets table.</p>

<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>.</p>

</div>
</div>

### emitStrings() {#a4e79865080aad82450af13818c5bccde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitStrings (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/nonrelocatablestringpool">NonRelocatableStringpool</a> &amp; Pool)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the string table described by <span class="doxyComputerOutput">Pool</span> into .debug_str table.</p>


<p>Emit the debug_str section stored in <span class="doxyComputerOutput">Pool</span>.</p>


<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/nonrelocatablestringpool/#a648f04a20283c7dd28b9fad17ba85fac">llvm::NonRelocatableStringpool::getEntriesForEmission</a>.</p>

</div>
</div>

### emitSwiftAST() {#aeb71b6f90fe6bf50b3ff54cfc7092077}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitSwiftAST (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the swift_ast section stored in <span class="doxyComputerOutput">Buffer</span>.</p>


<p>Emit the swift_ast section stored in <span class="doxyComputerOutput">Buffers</span>.</p>


<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a028a2916c58908b43c9866673f0b651c">llvm::MCSection::setAlignment</a>.</p>

</div>
</div>

### emitSwiftReflectionSection() {#a74e0e8c4a75f7e6b6be6c976a5738a0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitSwiftReflectionSection (<a href="/web-llvm/docs/api/namespaces/llvm/binaryformat/#ab355a2b14b4cc35373b4526fbfab894d">llvm::binaryformat::Swift5ReflectionSectionKind</a> ReflSectionKind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, uint32_t Alignment, uint32_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the swift reflection section stored in <span class="doxyComputerOutput">Buffer</span>.</p>

<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a028a2916c58908b43c9866673f0b651c">llvm::MCSection::setAlignment</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### finish() {#aa219176178ec28609335b3abbc253984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::finish ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the file to the disk.</p>

<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### getAsmPrinter() {#ac68bbd56c519d8bbc0528004f2510ccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmPrinter &amp; llvm::dwarf_linker::classic::DwarfStreamer::getAsmPrinter ()</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### getDebugAddrSectionSize() {#a54eee596df09d1f2f74a7ac5c4575ec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::getDebugAddrSectionSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of generated .debug_addr section.</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### getDebugInfoSectionSize() {#a0703b36dce3be3f918ad55530d2a774c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::getDebugInfoSectionSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of generated .debug_info section.</p>

<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### getDebugMacInfoSectionSize() {#abafe025d32ef832754a24bfedf614be1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::getDebugMacInfoSectionSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of generated .debug_macinfo section.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### getDebugMacroSectionSize() {#a46f98097ee23555c85fec17ca49186d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::getDebugMacroSectionSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of generated .debug_macro section.</p>

<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### getFrameSectionSize() {#ae9101ef55c2f1d70d82c7acdd94ba2b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::getFrameSectionSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of generated .debug_frame section.</p>

<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### getLineSectionSize() {#a54c96d59b67461c55d80da75a5367c89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::getLineSectionSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of generated .debug_line section.</p>

<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### getLocListsSectionSize() {#a7ed87efa200b9505f5eebf2c68ca9914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::getLocListsSectionSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of generated .debug_loclists section.</p>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### getRangesSectionSize() {#a099674e6a2c5c5b6d556d797cd44e6c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::getRangesSectionSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of generated .debug_ranges section.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### getRngListsSectionSize() {#a7950d1f93783df9a2c0ee7a2ddd30052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::getRngListsSectionSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of generated .debug_rnglists section.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### init() {#a7472bfb367d052f75ef1e00fa660be70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DwarfStreamer::init (<a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> TheTriple, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Swift5ReflectionSegmentName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions/#a192e9c2a63352ff1000ebe757e5b1f12">llvm::MCTargetOptions::AsmVerbose</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#aba62c3e12b7c341d64f21e98325f4082ad75c45e11c8aeb13494dba59a388a164">llvm::dwarf_linker::DWARFLinkerBase::Assembly</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#af99edadf5e6ea4da9f9d4b92567b8767">llvm::Target::createAsmPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#aef9d1d02691bc877336d27be1c71a1c6">llvm::Target::createAsmStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a4c0bf2185facd6d2d548d7a5b8a68201">llvm::Target::createMCAsmBackend</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a9a65dcb8a1d47b55360f95a575dedb62">llvm::Target::createMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a305a6e954c6b56c92ad0761f4ec1fa55">llvm::Target::createMCCodeEmitter</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a9aecbb4df7336a0a60255508e24e93d3">llvm::Target::createMCInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#afbeb195717f888bfc2ba9f54e9623bae">llvm::Target::createMCInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a34b1bcd57f9c18a520b55819365ea9bb">llvm::Target::createMCObjectFileInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a7c1c0e56c4d13dab0c027120fadcafe7">llvm::Target::createMCObjectStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a7291082412f4df3356f434aac4685911">llvm::Target::createMCRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a3b11020c76ae0245d4aee684528e8a73">llvm::Target::createMCSubtargetInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a97b31e68ba164458a37e49e7d1053fc1">llvm::Target::createTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions/#a465c716319177c7bd66f91856de9b950a0ad3dcce4e7f9e1fa609ed0c529aba6d">llvm::MCTargetOptions::EnableDwarfDirectory</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a7bc9985614536143e793244dfb66028c">llvm::Triple::getTriple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mc/#a40c84135f8f6afce28578f48f4b2cb15">llvm::mc::InitMCTargetOptionsFromFlags</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a85a69009ec328d5835241f56fb62cc6d">llvm::TargetRegistry::lookupTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions/#a2ebf0d418b7b9e095f2fea195ca3647e">llvm::MCTargetOptions::MCUseDwarfDirectory</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#aba62c3e12b7c341d64f21e98325f4082a497031794414a552435f90151ac3b54b">llvm::dwarf_linker::DWARFLinkerBase::Object</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### switchToDebugInfoSection() {#adfa6fc1d4ec200c99cce6bd03bb41dee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::switchToDebugInfoSection (unsigned DwarfVersion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the current output section to debug_info and change the MC Dwarf version to <span class="doxyComputerOutput">DwarfVersion</span>.</p>

<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>Referenced by <a href="#ae734c9b910054fa45f339c64f6a08d25">emitCompileUnitHeader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### emitDwarfDebugLocListsTableFragment() {#ac876d6a838333f26fdd979f9ff76f118}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitDwarfDebugLocListsTableFragment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#afc9a8659aea188ea36273a12a45b5929">DWARFLocationExpressionsVector</a> &amp; LinkedLocationExpression, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/patchlocation">PatchLocation</a> Patch, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#a1ea4442463c620b2bef27de747ab16d7">DebugDieValuePool</a> &amp; AddrPool)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit piece of .debug_loclists for <span class="doxyComputerOutput">LinkedRanges</span>.</p>


<p>Emit piece of .debug_loclists for <span class="doxyComputerOutput">LinkedLocationExpression</span>.</p>


<p>Declaration at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 757 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitDwarfDebugLocTableFragment() {#a7b0f1bbc8c054f7c9208ed958d6cbc95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitDwarfDebugLocTableFragment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#afc9a8659aea188ea36273a12a45b5929">DWARFLocationExpressionsVector</a> &amp; LinkedLocationExpression, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/patchlocation">PatchLocation</a> Patch)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit piece of .debug_loc for <span class="doxyComputerOutput">LinkedRanges</span>.</p>


<p>Emit piece of .debug_loc for <span class="doxyComputerOutput">LinkedLocationExpression</span>.</p>


<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 666 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitDwarfDebugRangesTableFragment() {#a5456633cd53a787d4ae7f566adc412ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitDwarfDebugRangesTableFragment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/addressranges">AddressRanges</a> &amp; LinkedRanges, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/patchlocation">PatchLocation</a> Patch)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit piece of .debug_ranges for <span class="doxyComputerOutput">LinkedRanges</span>.</p>

<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitDwarfDebugRngListsTableFragment() {#ae8b1d60fe32fb00adaf8c7d4afb95db5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitDwarfDebugRngListsTableFragment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/addressranges">AddressRanges</a> &amp; LinkedRanges, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/patchlocation">PatchLocation</a> Patch, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#a1ea4442463c620b2bef27de747ab16d7">DebugDieValuePool</a> &amp; AddrPool)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit piece of .debug_rnglists for <span class="doxyComputerOutput">LinkedRanges</span>.</p>

<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitMacroTableImpl() {#a7f4711416c07614a7eb2e4e476a83d01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitMacroTableImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugmacro">DWARFDebugMacro</a> * MacroTable, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#a883bd25ef016f5881dd3f8573823f0b0">Offset2UnitMap</a> &amp; UnitMacroMap, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; StringPool, uint64_t &amp; OutOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 1293 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitPubSectionForUnit() {#abafcc16d7961e532d0660f75e9aa0d4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitPubSectionForUnit (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Sec, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SecName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/compileunit/accelinfo">CompileUnit::AccelInfo</a> &gt; &amp; Names)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the pubnames or pubtypes section contribution for <span class="doxyComputerOutput">Unit</span> into <span class="doxyComputerOutput">Sec</span>.</p>


<p>The data is provided in <span class="doxyComputerOutput">Names</span>.</p>


<p>Declaration at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 1201 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### getMCSection() {#ac39ec3315ec21dacfea52c5265f6eaf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * DwarfStreamer::getMCSection (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24">DebugSectionKind</a> SecKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### warn() {#a2a74a7c7dfa7e4bc33a4f0904ca3d289}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::DwarfStreamer::warn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Warning, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Context="")</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AddrSectionSize {#ae2383db640b1da77d6cc19c873e7b7b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::AddrSectionSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### DebugInfoSectionSize {#aaca7be836f59cb0943ad42705697cfb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::DebugInfoSectionSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### EmittedUnits {#a69e4138a3744aaa894fcd9a7ce90ab1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;EmittedUnit&gt; llvm::dwarf_linker::classic::DwarfStreamer::EmittedUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### FrameSectionSize {#a81469679ad3bfef6c3bd0d82d2fa838f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::FrameSectionSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### LineSectionSize {#a3af70d972a8db3c47e366b84ef8ae1ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::LineSectionSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### LocListsSectionSize {#abb3e3f8383dfb12d577ad645bbc833a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::LocListsSectionSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### LocSectionSize {#a643e186d7a644d410132c7a3830114db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::LocSectionSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### MacInfoSectionSize {#afe0b33c01e01fabbda33dbf15f9b4f08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::MacInfoSectionSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### MacroSectionSize {#a8e688929e9f72c36396862f002ef7307}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::MacroSectionSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### OutFile {#a439a4903d72f44c38e8cd6e08ea95e4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_pwrite_stream&amp; llvm::dwarf_linker::classic::DwarfStreamer::OutFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The output file we stream the linked Dwarf to.</p>

<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### OutFileType {#a370dd06f8b06f2b3eb5126b6bcd33490}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFLinker::OutputFileType llvm::dwarf_linker::classic::DwarfStreamer::OutFileType = <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#aba62c3e12b7c341d64f21e98325f4082a497031794414a552435f90151ac3b54b">DWARFLinker::OutputFileType::Object</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### RangesSectionSize {#af197027ae801858b975e8a1a8b60cbe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::RangesSectionSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### RngListsSectionSize {#a0781284590ad0315a2da58e580b95ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::RngListsSectionSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### StrOffsetSectionSize {#ab3d736f4408562fc9beeac61412032fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::DwarfStreamer::StrOffsetSectionSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

### WarningHandler {#a30c03d3a761b65fc9ba67708228c9a25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFLinkerBase::MessageHandlerTy llvm::dwarf_linker::classic::DwarfStreamer::WarningHandler = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createStreamer() {#a4fa9dc1022d6e4b200632808fe58b99a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; DwarfStreamer &gt; &gt; DwarfStreamer::createStreamer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TheTriple, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#aba62c3e12b7c341d64f21e98325f4082">DWARFLinkerBase::OutputFileType</a> FileType, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; OutFile, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a6171d1affe838c4595f5bc1306ca5749">DWARFLinkerBase::MessageHandlerTy</a> Warning)</td>
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



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
