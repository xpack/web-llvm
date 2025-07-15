---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/dwarfemitterimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DwarfEmitterImpl` Class Reference

<p>This class emits DWARF data to the output stream. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::DwarfEmitterImpl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFLinker/Parallel/DWARFEmitterImpl.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0f3ae898a9d2639077d89220b794aed">DwarfEmitterImpl</a> (DWARFLinker::OutputFileType OutFileType, raw_pwrite_stream &amp;OutFile)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66fa607c96a11d3a9e973d33e733ac37">init</a> (Triple TheTriple, StringRef Swift5ReflectionSegmentName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> data. <a href="#a66fa607c96a11d3a9e973d33e733ac37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f777bd73d0a0069322b885161264698">getTargetTriple</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns triple of output stream. <a href="#a2f777bd73d0a0069322b885161264698">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af93817464b4ae9e54fb7088bc6671695">finish</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the file to the disk. <a href="#af93817464b4ae9e54fb7088bc6671695">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a937f56a8a0d470d5975028f545827f30">emitAbbrevs</a> (const SmallVector&lt; std::unique_ptr&lt; DIEAbbrev &gt; &gt; &amp;Abbrevs, unsigned DwarfVersion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit abbreviations. <a href="#a937f56a8a0d470d5975028f545827f30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33e9eb0eeafe2fb7ba03fb0da1ae35cf">emitCompileUnitHeader</a> (DwarfUnit &amp;Unit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit compile unit header. <a href="#a33e9eb0eeafe2fb7ba03fb0da1ae35cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5ac850992c69e76c0e1d40b83d9b0ff">emitDIE</a> (DIE &amp;Die)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> recursively. <a href="#ac5ac850992c69e76c0e1d40b83d9b0ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a750c2b9a0ee2c09fe4aedf34f9484486">getDebugInfoSectionSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of generated .debug_info section. <a href="#a750c2b9a0ee2c09fe4aedf34f9484486">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfe78bb04af8f68caf49868a303d5175">emitDebugNames</a> (DWARF5AccelTable &amp;Table, DebugNamesUnitsOffsets &amp;CUOffsets, CompUnitIDToIdx &amp;UnitIDToIdxMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits .debug_names section according to the specified <span class="doxyComputerOutput">Table</span>. <a href="#adfe78bb04af8f68caf49868a303d5175">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68524acaa0eb1e70014b75eb34c6e5cb">emitAppleNames</a> (AccelTable&lt; AppleAccelTableStaticOffsetData &gt; &amp;Table)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits .apple_names section according to the specified <span class="doxyComputerOutput">Table</span>. <a href="#a68524acaa0eb1e70014b75eb34c6e5cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad142c7a3266f8cfdb83702dd6d54a81a">emitAppleNamespaces</a> (AccelTable&lt; AppleAccelTableStaticOffsetData &gt; &amp;Table)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits .apple_namespaces section according to the specified <span class="doxyComputerOutput">Table</span>. <a href="#ad142c7a3266f8cfdb83702dd6d54a81a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9e8188b83f4aa27eb9c6831849c1767">emitAppleObjc</a> (AccelTable&lt; AppleAccelTableStaticOffsetData &gt; &amp;Table)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits .apple_objc section according to the specified <span class="doxyComputerOutput">Table</span>. <a href="#ae9e8188b83f4aa27eb9c6831849c1767">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac22d4c7f337f37c3d391b848a6422923">emitAppleTypes</a> (AccelTable&lt; AppleAccelTableStaticTypeData &gt; &amp;Table)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits .apple_types section according to the specified <span class="doxyComputerOutput">Table</span>. <a href="#ac22d4c7f337f37c3d391b848a6422923">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PatchTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a409df8806fbbd1a137435dadb22becb5">emitStringsImpl</a> (ArrayList&lt; PatchTy &gt; &amp;StringPatches, const StringEntryToDwarfStringPoolEntryMap &amp;Strings, uint64_t &amp;NextOffset, MCSection *OutSection)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20176bc2063ab732e93fc482035f00b2">OutFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The output file we stream the linked Dwarf to. <a href="#a20176bc2063ab732e93fc482035f00b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#aba62c3e12b7c341d64f21e98325f4082">DWARFLinkerBase::OutputFileType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89090b2e57e665fcdcd183fb507b393d">OutFileType</a> = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42f30d40390fe1f8124f3f20f1e87c15">DebugInfoSectionSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#gac7d027d3931c90220bf7937c28396ca7">MRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#ga5b41e1f351d717ae24f90ebc53295b15">MAI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#gaa4d2ea30e28521810b3c12f4b35698c5">MOFI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#ga8b6d76691d333cf8d18e6b613694733a">MC</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#gaa0b53c0d9a27b48cd3f483cc21382ced">MAB</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#ga57dcd436f44e455dc0bc208d05093636">MII</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#gaebbcaceef6a5a99507fd467c5a797627">MSTI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#ga2d3548e617af7adc6fa1500a7dba0b6c">MIP</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#ga6a9f33d56f2fb34942b7e6ff8fd88617">MCE</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#gad017cf458ba158570b0e5fc406eb7985">MS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#gab7956a2bad1d0586601d5c9f1cc788e9">TM</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/mcobjects/#ga702f78cb706f0b5dff4c1f533f5f0c86">Asm</a></td>
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

<p>This class emits DWARF data to the output stream.</p>


<p>It emits already generated section data and specific data, which could not be generated by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a>.</p>


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFEmitterImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DwarfEmitterImpl() {#ac0f3ae898a9d2639077d89220b794aed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::DwarfEmitterImpl::DwarfEmitterImpl (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#aba62c3e12b7c341d64f21e98325f4082">DWARFLinker::OutputFileType</a> OutFileType, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; OutFile)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFEmitterImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitAbbrevs() {#a937f56a8a0d470d5975028f545827f30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfEmitterImpl::emitAbbrevs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dieabbrev">DIEAbbrev</a> &gt; &gt; &amp; Abbrevs, unsigned DwarfVersion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit abbreviations.</p>

<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFEmitterImpl.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-cpp">DWARFEmitterImpl.cpp</a>.</p>

</div>
</div>

### emitAppleNames() {#a68524acaa0eb1e70014b75eb34c6e5cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfEmitterImpl::emitAppleNames (<a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata">AppleAccelTableStaticOffsetData</a> &gt; &amp; Table)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits .apple_names section according to the specified <span class="doxyComputerOutput">Table</span>.</p>

<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFEmitterImpl.h</a>, definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-cpp">DWARFEmitterImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa78b3092a3008359b197ec6e29618b9d">llvm::emitAppleAccelTable</a>.</p>

</div>
</div>

### emitAppleNamespaces() {#ad142c7a3266f8cfdb83702dd6d54a81a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfEmitterImpl::emitAppleNamespaces (<a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata">AppleAccelTableStaticOffsetData</a> &gt; &amp; Table)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits .apple_namespaces section according to the specified <span class="doxyComputerOutput">Table</span>.</p>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFEmitterImpl.h</a>, definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-cpp">DWARFEmitterImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa78b3092a3008359b197ec6e29618b9d">llvm::emitAppleAccelTable</a>.</p>

</div>
</div>

### emitAppleObjc() {#ae9e8188b83f4aa27eb9c6831849c1767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfEmitterImpl::emitAppleObjc (<a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata">AppleAccelTableStaticOffsetData</a> &gt; &amp; Table)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits .apple_objc section according to the specified <span class="doxyComputerOutput">Table</span>.</p>

<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFEmitterImpl.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-cpp">DWARFEmitterImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa78b3092a3008359b197ec6e29618b9d">llvm::emitAppleAccelTable</a>.</p>

</div>
</div>

### emitAppleTypes() {#ac22d4c7f337f37c3d391b848a6422923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfEmitterImpl::emitAppleTypes (<a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestatictypedata">AppleAccelTableStaticTypeData</a> &gt; &amp; Table)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits .apple_types section according to the specified <span class="doxyComputerOutput">Table</span>.</p>

<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFEmitterImpl.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-cpp">DWARFEmitterImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa78b3092a3008359b197ec6e29618b9d">llvm::emitAppleAccelTable</a>.</p>

</div>
</div>

### emitCompileUnitHeader() {#a33e9eb0eeafe2fb7ba03fb0da1ae35cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfEmitterImpl::emitCompileUnitHeader (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit">DwarfUnit</a> &amp; Unit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit compile unit header.</p>

<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFEmitterImpl.h</a>, definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-cpp">DWARFEmitterImpl.cpp</a>.</p>

</div>
</div>

### emitDebugNames() {#adfe78bb04af8f68caf49868a303d5175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfEmitterImpl::emitDebugNames (<a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltable">DWARF5AccelTable</a> &amp; Table, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#a6c8048488a79170bb4f1c87751d19bbb">DebugNamesUnitsOffsets</a> &amp; CUOffsets, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#add8831ecd792c1a085a12461a0cf680c">CompUnitIDToIdx</a> &amp; UnitIDToIdxMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits .debug_names section according to the specified <span class="doxyComputerOutput">Table</span>.</p>

<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFEmitterImpl.h</a>, definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-cpp">DWARFEmitterImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dieinteger/#af397b05376454122495039750b702064">llvm::DIEInteger::BestForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4372f5cbd92647d1f4f90fcdb8a5474">llvm::emitDWARF5AccelTable</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a>.</p>

</div>
</div>

### emitDIE() {#ac5ac850992c69e76c0e1d40b83d9b0ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfEmitterImpl::emitDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> recursively.</p>

<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFEmitterImpl.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-cpp">DWARFEmitterImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/die/#a260b23f8c0c3b34a94b27886008630f9">llvm::DIE::getSize</a>.</p>

</div>
</div>

### finish() {#af93817464b4ae9e54fb7088bc6671695}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DwarfEmitterImpl::finish ()</td>
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

<p>Dump the file to the disk.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFEmitterImpl.h</a>.</p>

</div>
</div>

### getDebugInfoSectionSize() {#a750c2b9a0ee2c09fe4aedf34f9484486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::parallel::DwarfEmitterImpl::getDebugInfoSectionSize ()</td>
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

<p>Returns size of generated .debug_info section.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFEmitterImpl.h</a>.</p>

</div>
</div>

### getTargetTriple() {#a2f777bd73d0a0069322b885161264698}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Triple &amp; llvm::dwarf_linker::parallel::DwarfEmitterImpl::getTargetTriple ()</td>
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

<p>Returns triple of output stream.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFEmitterImpl.h</a>.</p>

</div>
</div>

### init() {#a66fa607c96a11d3a9e973d33e733ac37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DwarfEmitterImpl::init (<a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> TheTriple, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Swift5ReflectionSegmentName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> data.</p>

<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFEmitterImpl.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-cpp">DWARFEmitterImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions/#a192e9c2a63352ff1000ebe757e5b1f12">llvm::MCTargetOptions::AsmVerbose</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#aba62c3e12b7c341d64f21e98325f4082ad75c45e11c8aeb13494dba59a388a164">llvm::dwarf_linker::DWARFLinkerBase::Assembly</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#af99edadf5e6ea4da9f9d4b92567b8767">llvm::Target::createAsmPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#aef9d1d02691bc877336d27be1c71a1c6">llvm::Target::createAsmStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a4c0bf2185facd6d2d548d7a5b8a68201">llvm::Target::createMCAsmBackend</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a9a65dcb8a1d47b55360f95a575dedb62">llvm::Target::createMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a305a6e954c6b56c92ad0761f4ec1fa55">llvm::Target::createMCCodeEmitter</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a9aecbb4df7336a0a60255508e24e93d3">llvm::Target::createMCInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#afbeb195717f888bfc2ba9f54e9623bae">llvm::Target::createMCInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a34b1bcd57f9c18a520b55819365ea9bb">llvm::Target::createMCObjectFileInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a7c1c0e56c4d13dab0c027120fadcafe7">llvm::Target::createMCObjectStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a7291082412f4df3356f434aac4685911">llvm::Target::createMCRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a3b11020c76ae0245d4aee684528e8a73">llvm::Target::createMCSubtargetInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a97b31e68ba164458a37e49e7d1053fc1">llvm::Target::createTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions/#a465c716319177c7bd66f91856de9b950a0ad3dcce4e7f9e1fa609ed0c529aba6d">llvm::MCTargetOptions::EnableDwarfDirectory</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a7bc9985614536143e793244dfb66028c">llvm::Triple::getTriple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mc/#a40c84135f8f6afce28578f48f4b2cb15">llvm::mc::InitMCTargetOptionsFromFlags</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a85a69009ec328d5835241f56fb62cc6d">llvm::TargetRegistry::lookupTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions/#a2ebf0d418b7b9e095f2fea195ca3647e">llvm::MCTargetOptions::MCUseDwarfDirectory</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#aba62c3e12b7c341d64f21e98325f4082a497031794414a552435f90151ac3b54b">llvm::dwarf_linker::DWARFLinkerBase::Object</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### emitStringsImpl() {#a409df8806fbbd1a137435dadb22becb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PatchTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DwarfEmitterImpl::emitStringsImpl (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/arraylist">ArrayList</a>&lt; PatchTy &gt; &amp; StringPatches, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/stringentrytodwarfstringpoolentrymap">StringEntryToDwarfStringPoolEntryMap</a> &amp; Strings, uint64_t &amp; NextOffset, <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * OutSection)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFEmitterImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DebugInfoSectionSize {#a42f30d40390fe1f8124f3f20f1e87c15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::parallel::DwarfEmitterImpl::DebugInfoSectionSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFEmitterImpl.h</a>.</p>

</div>
</div>

### OutFile {#a20176bc2063ab732e93fc482035f00b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_pwrite_stream&amp; llvm::dwarf_linker::parallel::DwarfEmitterImpl::OutFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The output file we stream the linked Dwarf to.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFEmitterImpl.h</a>.</p>

</div>
</div>

### OutFileType {#a89090b2e57e665fcdcd183fb507b393d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFLinkerBase::OutputFileType llvm::dwarf_linker::parallel::DwarfEmitterImpl::OutFileType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#aba62c3e12b7c341d64f21e98325f4082a497031794414a552435f90151ac3b54b">DWARFLinkerBase::OutputFileType::Object</a>
</div>
</dd>
</dl>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFEmitterImpl.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-cpp">DWARFEmitterImpl.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarfemitterimpl-h">DWARFEmitterImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
