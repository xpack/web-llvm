---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarf-linker/parallel/sectiondescriptor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SectionDescriptor` Struct Reference

<p>This structure is used to keep data of the concrete section. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::dwarf_linker::parallel::SectionDescriptor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">DWARFLinker/Parallel/OutputSections.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase">SectionDescriptorBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This structure keeps data of the concrete section. <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfb7f075fc5e83f4c92bbe02c3d088e4">SectionDescriptor</a> (DebugSectionKind SectionKind, LinkingGlobalData &amp;GlobalData, dwarf::FormParams Format, llvm::endianness Endianess)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4ee8dc8a752ad8681e4f74a9ea092ae">clearAllSectionData</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase whole section content(data bits, list of patches). <a href="#ab4ee8dc8a752ad8681e4f74a9ea092ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70596a4759ebad01c1367c2719391c6f">clearSectionContent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase only section output data bits. <a href="#a70596a4759ebad01c1367c2719391c6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ada575452de07c297cfeea8ce744a79ed">notePatchWithOffsetUpdate</a> (const T &amp;Patch, OffsetsPtrVector &amp;PatchesOffsetsList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>While creating patches, offsets to attributes may be partially unknown(because size of abbreviation number is unknown). <a href="#ada575452de07c297cfeea8ce744a79ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0756e89d8eafc4bc2503dd3976765f61">setSizesForSectionCreatedByAsmPrinter</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some sections are emitted using <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a>. <a href="#a0756e89d8eafc4bc2503dd3976765f61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a860c597e55feedf9817bdeaf9067b639">getContents</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns section content. <a href="#a860c597e55feedf9817bdeaf9067b639">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25a7fc71830bebb1aa3eda2441838cd6">emitUnitLength</a> (uint64_t Length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit unit length into the current section contents. <a href="#a25a7fc71830bebb1aa3eda2441838cd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f60d07e41fe95295f7afe3ec3fb96ff">maybeEmitDwarf64Mark</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit DWARF64 mark into the current section contents. <a href="#a4f60d07e41fe95295f7afe3ec3fb96ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b514ad5d75b2375ee443a0338d694e8">emitOffset</a> (uint64_t Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit specified offset value into the current section contents. <a href="#a2b514ad5d75b2375ee443a0338d694e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4954fa6faa9509d506fcedc034eb02c8">emitIntVal</a> (uint64_t Val, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit specified integer value into the current section contents. <a href="#a4954fa6faa9509d506fcedc034eb02c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fdedfeb863a3688b3eac2b13eea3c87">emitString</a> (dwarf::Form StringForm, const char *StringVal)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72a02b2842e0381aaeb728cb1969d5e9">emitBinaryData</a> (llvm::StringRef Data)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fdd30c106c85cd071977c5062eeed69">emitInplaceString</a> (StringRef String)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit specified inplace string value into the current section contents. <a href="#a5fdd30c106c85cd071977c5062eeed69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad04584ea44f6ef1d2cb79d9b1aaab706">emitStringPlaceholder</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit string placeholder into the current section contents. <a href="#ad04584ea44f6ef1d2cb79d9b1aaab706">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e7ab4547b66cde4652390ba796d97a1">apply</a> (uint64_t PatchOffset, dwarf::Form AttrForm, uint64_t Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write specified <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> of <span class="doxyComputerOutput">AttrForm</span> to the <span class="doxyComputerOutput">PatchOffset</span>. <a href="#a5e7ab4547b66cde4652390ba796d97a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e4cc243fb344193485e9e4fe79399c7">getIntVal</a> (uint64_t PatchOffset, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns integer value of <span class="doxyComputerOutput">Size</span> located by specified <span class="doxyComputerOutput">PatchOffset</span>. <a href="#a6e4cc243fb344193485e9e4fe79399c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a404cacae16324605710710194e08e5ca">applyIntVal</a> (uint64_t PatchOffset, uint64_t Val, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Writes integer value <span class="doxyComputerOutput">Val</span> of <span class="doxyComputerOutput">Size</span> by specified <span class="doxyComputerOutput">PatchOffset</span>. <a href="#a404cacae16324605710710194e08e5ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e237e34d55840912a54fbef648eea92">applyULEB128</a> (uint64_t PatchOffset, uint64_t Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Writes integer value <span class="doxyComputerOutput">Val</span> of ULEB128 format by specified <span class="doxyComputerOutput">PatchOffset</span>. <a href="#a4e237e34d55840912a54fbef648eea92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c0cd7586ca23f44571c798723fee65f">applySLEB128</a> (uint64_t PatchOffset, uint64_t Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Writes integer value <span class="doxyComputerOutput">Val</span> of SLEB128 format by specified <span class="doxyComputerOutput">PatchOffset</span>. <a href="#a4c0cd7586ca23f44571c798723fee65f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4ef16179cba57f690c921b7778ba2eb">setOutputFormat</a> (dwarf::FormParams Format, llvm::endianness Endianess)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets output format. <a href="#aa4ef16179cba57f690c921b7778ba2eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1acb1c59484f29e48610196faf58a5fd">OutputSections</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af80b542f4b0c15d3425d97257ecda897">StartOffset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When objects(f.e. <a href="#af80b542f4b0c15d3425d97257ecda897">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream">raw_svector_ostream</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01de9af3f8e9b5ca39f42089c9a0e8ce">OS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stream which stores data to the Contents. <a href="#a01de9af3f8e9b5ca39f42089c9a0e8ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/linkingglobaldata">LinkingGlobalData</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5cd5abea8131106a410e39b80a5589b">GlobalData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#a94cbbc332c04c070829995c39843c554">OutSectionDataTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f6c2fed002a819f9bf08a21adf92476">Contents</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Section data bits. <a href="#a3f6c2fed002a819f9bf08a21adf92476">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa9f26636671c4eff83ff3821477a085">SectionOffsetInsideAsmPrinterOutputStart</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some sections are generated using <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a>. <a href="#aaa9f26636671c4eff83ff3821477a085">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab947ce3a5eb89fd72e0f787b27364d15">SectionOffsetInsideAsmPrinterOutputEnd</a> = 0</td>
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

<p>This structure is used to keep data of the concrete section.</p>


<p>Like data bits, list of patches, format.</p>


<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SectionDescriptor() {#acfb7f075fc5e83f4c92bbe02c3d088e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::SectionDescriptor::SectionDescriptor (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24">DebugSectionKind</a> SectionKind, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/linkingglobaldata">LinkingGlobalData</a> &amp; GlobalData, <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">dwarf::FormParams</a> Format, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> Endianess)</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>References <a href="#a3f6c2fed002a819f9bf08a21adf92476">Contents</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a4c4a80dc8fb3cb9ff7e985798d599313">llvm::dwarf_linker::parallel::SectionDescriptorBase::Endianess</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a657f147ee0c2ca97c60d8e929acbda5f">llvm::dwarf_linker::parallel::SectionDescriptorBase::Format</a>, <a href="#af5cd5abea8131106a410e39b80a5589b">GlobalData</a>, <a href="#a01de9af3f8e9b5ca39f42089c9a0e8ce">OS</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a5e12c3eb9ada6e834adf3bbabff0ff67">llvm::dwarf_linker::parallel::SectionDescriptorBase::SectionDescriptorBase</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a19378e3183278a6ec1d6fe2f3ac9841c">llvm::dwarf_linker::parallel::SectionDescriptorBase::SectionKind</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### apply() {#a5e7ab4547b66cde4652390ba796d97a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SectionDescriptor::apply (uint64_t PatchOffset, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> AttrForm, uint64_t Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write specified <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> of <span class="doxyComputerOutput">AttrForm</span> to the <span class="doxyComputerOutput">PatchOffset</span>.</p>

<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>, definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-cpp">OutputSections.cpp</a>.</p>


<p>References <a href="#a404cacae16324605710710194e08e5ca">applyIntVal</a>, <a href="#a4c0cd7586ca23f44571c798723fee65f">applySLEB128</a>, <a href="#a4e237e34d55840912a54fbef648eea92">applyULEB128</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a657f147ee0c2ca97c60d8e929acbda5f">llvm::dwarf_linker::parallel::SectionDescriptorBase::Format</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/debuglinesectionemitter/#a81feed7a90b5abc9e58b574e7da2a360">llvm::dwarf_linker::parallel::DebugLineSectionEmitter::emit</a>, <a href="/web-llvm/docs/api/groups/methods/#ga579ac60d76c4a3b6ca084238591d4437">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugStringOffsetSection</a> and <a href="/web-llvm/docs/api/groups/methods/#ga80d3884d82a541f6f1b11931db9fc5fb">llvm::dwarf_linker::parallel::DwarfUnit::emitPubAccelerators</a>.</p>

</div>
</div>

### clearAllSectionData() {#ab4ee8dc8a752ad8681e4f74a9ea092ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SectionDescriptor::clearAllSectionData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Erase whole section content(data bits, list of patches).</p>

<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-cpp">OutputSections.cpp</a>.</p>


<p>References <a href="#a70596a4759ebad01c1367c2719391c6f">clearSectionContent</a> and <a href="#af80b542f4b0c15d3425d97257ecda897">StartOffset</a>.</p>

</div>
</div>

### clearSectionContent() {#a70596a4759ebad01c1367c2719391c6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SectionDescriptor::clearSectionContent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Erase only section output data bits.</p>

<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-cpp">OutputSections.cpp</a>.</p>


<p>Reference <a href="#a3f6c2fed002a819f9bf08a21adf92476">Contents</a>.</p>


<p>Referenced by <a href="#ab4ee8dc8a752ad8681e4f74a9ea092ae">clearAllSectionData</a>.</p>

</div>
</div>

### emitBinaryData() {#a72a02b2842e0381aaeb728cb1969d5e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SectionDescriptor::emitBinaryData (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>, definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-cpp">OutputSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="#a01de9af3f8e9b5ca39f42089c9a0e8ce">OS</a>.</p>

</div>
</div>

### emitInplaceString() {#a5fdd30c106c85cd071977c5062eeed69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::SectionDescriptor::emitInplaceString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> String)</td>
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

<p>Emit specified inplace string value into the current section contents.</p>

<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>References <a href="#a4954fa6faa9509d506fcedc034eb02c8">emitIntVal</a>, <a href="#a01de9af3f8e9b5ca39f42089c9a0e8ce">OS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#aa5415f7dcc45583b4bb82acb6f64c73a">llvm::dwarf_linker::parallel::DwarfUnit::emitPubAcceleratorEntry</a> and <a href="#a3fdedfeb863a3688b3eac2b13eea3c87">emitString</a>.</p>

</div>
</div>

### emitIntVal() {#a4954fa6faa9509d506fcedc034eb02c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SectionDescriptor::emitIntVal (uint64_t Val, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit specified integer value into the current section contents.</p>

<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-cpp">OutputSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a4c4a80dc8fb3cb9ff7e985798d599313">llvm::dwarf_linker::parallel::SectionDescriptorBase::Endianess</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dba8e5f3adee38c8fccc13c1f3be0143796">llvm::native</a>, <a href="#a01de9af3f8e9b5ca39f42089c9a0e8ce">OS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ad0e418047a3e04c4fd1fb83325b571ae">llvm::sys::swapByteOrder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/methods/#ga579ac60d76c4a3b6ca084238591d4437">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugStringOffsetSection</a>, <a href="#a5fdd30c106c85cd071977c5062eeed69">emitInplaceString</a>, <a href="#a2b514ad5d75b2375ee443a0338d694e8">emitOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#aa5415f7dcc45583b4bb82acb6f64c73a">llvm::dwarf_linker::parallel::DwarfUnit::emitPubAcceleratorEntry</a>, <a href="/web-llvm/docs/api/groups/methods/#ga80d3884d82a541f6f1b11931db9fc5fb">llvm::dwarf_linker::parallel::DwarfUnit::emitPubAccelerators</a>, <a href="#a25a7fc71830bebb1aa3eda2441838cd6">emitUnitLength</a> and <a href="#a4f60d07e41fe95295f7afe3ec3fb96ff">maybeEmitDwarf64Mark</a>.</p>

</div>
</div>

### emitOffset() {#a2b514ad5d75b2375ee443a0338d694e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::SectionDescriptor::emitOffset (uint64_t Val)</td>
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

<p>Emit specified offset value into the current section contents.</p>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>References <a href="#a4954fa6faa9509d506fcedc034eb02c8">emitIntVal</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a2c022a96c1e5b992978a5b39a946fd56">llvm::dwarf_linker::parallel::SectionDescriptorBase::getFormParams</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/methods/#ga579ac60d76c4a3b6ca084238591d4437">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugStringOffsetSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#aa5415f7dcc45583b4bb82acb6f64c73a">llvm::dwarf_linker::parallel::DwarfUnit::emitPubAcceleratorEntry</a> and <a href="#ad04584ea44f6ef1d2cb79d9b1aaab706">emitStringPlaceholder</a>.</p>

</div>
</div>

### emitString() {#a3fdedfeb863a3688b3eac2b13eea3c87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SectionDescriptor::emitString (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> StringForm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * StringVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>, definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-cpp">OutputSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5fdd30c106c85cd071977c5062eeed69">emitInplaceString</a>, <a href="#ad04584ea44f6ef1d2cb79d9b1aaab706">emitStringPlaceholder</a>, <a href="#af5cd5abea8131106a410e39b80a5589b">GlobalData</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#a01de9af3f8e9b5ca39f42089c9a0e8ce">OS</a>.</p>

</div>
</div>

### emitStringPlaceholder() {#ad04584ea44f6ef1d2cb79d9b1aaab706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::SectionDescriptor::emitStringPlaceholder ()</td>
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

<p>Emit string placeholder into the current section contents.</p>

<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Reference <a href="#a2b514ad5d75b2375ee443a0338d694e8">emitOffset</a>.</p>


<p>Referenced by <a href="#a3fdedfeb863a3688b3eac2b13eea3c87">emitString</a>.</p>

</div>
</div>

### emitUnitLength() {#a25a7fc71830bebb1aa3eda2441838cd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::SectionDescriptor::emitUnitLength (uint64_t Length)</td>
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

<p>Emit unit length into the current section contents.</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>References <a href="#a4954fa6faa9509d506fcedc034eb02c8">emitIntVal</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a2c022a96c1e5b992978a5b39a946fd56">llvm::dwarf_linker::parallel::SectionDescriptorBase::getFormParams</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a> and <a href="#a4f60d07e41fe95295f7afe3ec3fb96ff">maybeEmitDwarf64Mark</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/debuglinesectionemitter/#a81feed7a90b5abc9e58b574e7da2a360">llvm::dwarf_linker::parallel::DebugLineSectionEmitter::emit</a> and <a href="/web-llvm/docs/api/groups/methods/#ga579ac60d76c4a3b6ca084238591d4437">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugStringOffsetSection</a>.</p>

</div>
</div>

### getContents() {#a860c597e55feedf9817bdeaf9067b639}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::dwarf_linker::parallel::SectionDescriptor::getContents ()</td>
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

<p>Returns section content.</p>

<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>References <a href="#a3f6c2fed002a819f9bf08a21adf92476">Contents</a>, <a href="#ab947ce3a5eb89fd72e0f787b27364d15">SectionOffsetInsideAsmPrinterOutputEnd</a> and <a href="#aaa9f26636671c4eff83ff3821477a085">SectionOffsetInsideAsmPrinterOutputStart</a>.</p>


<p>Referenced by <a href="#a404cacae16324605710710194e08e5ca">applyIntVal</a>, <a href="#a4c0cd7586ca23f44571c798723fee65f">applySLEB128</a>, <a href="#a4e237e34d55840912a54fbef648eea92">applyULEB128</a> and <a href="#a6e4cc243fb344193485e9e4fe79399c7">getIntVal</a>.</p>

</div>
</div>

### getIntVal() {#a6e4cc243fb344193485e9e4fe79399c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t SectionDescriptor::getIntVal (uint64_t PatchOffset, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns integer value of <span class="doxyComputerOutput">Size</span> located by specified <span class="doxyComputerOutput">PatchOffset</span>.</p>

<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>, definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-cpp">OutputSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a4c4a80dc8fb3cb9ff7e985798d599313">llvm::dwarf_linker::parallel::SectionDescriptorBase::Endianess</a>, <a href="#a860c597e55feedf9817bdeaf9067b639">getContents</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#af10ce40e426fd2ff3b12ff8158da378d">llvm::support::endian::read16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a1fda585fbf18128d11d28fa4c5b0ad7d">llvm::support::endian::read32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a7787225426474d5f50e2f0c4e3c16b1c">llvm::support::endian::read64</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### maybeEmitDwarf64Mark() {#a4f60d07e41fe95295f7afe3ec3fb96ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::SectionDescriptor::maybeEmitDwarf64Mark ()</td>
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

<p>Emit DWARF64 mark into the current section contents.</p>

<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4adc3aedef0caeccf6d845a430da6d3f8d">llvm::dwarf::DW_LENGTH_DWARF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a34b4d38e06d609b405f4a79c223ed8d2">llvm::dwarf::DWARF64</a>, <a href="#a4954fa6faa9509d506fcedc034eb02c8">emitIntVal</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a657f147ee0c2ca97c60d8e929acbda5f">llvm::dwarf_linker::parallel::SectionDescriptorBase::Format</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a2c022a96c1e5b992978a5b39a946fd56">llvm::dwarf_linker::parallel::SectionDescriptorBase::getFormParams</a>.</p>


<p>Referenced by <a href="#a25a7fc71830bebb1aa3eda2441838cd6">emitUnitLength</a>.</p>

</div>
</div>

### notePatchWithOffsetUpdate() {#ada575452de07c297cfeea8ce744a79ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::SectionDescriptor::notePatchWithOffsetUpdate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; Patch, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ad2dde002b59709a633439269e84fb29c">OffsetsPtrVector</a> &amp; PatchesOffsetsList)</td>
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

<p>While creating patches, offsets to attributes may be partially unknown(because size of abbreviation number is unknown).</p>


<p>In such case we remember patch itself and pointer to patch application offset to add size of abbreviation number later.</p>


<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#aafd0fac7574417fa923ca2bce4b9b85c">llvm::dwarf_linker::parallel::TypeUnit::createDIETree</a>.</p>

</div>
</div>

### setSizesForSectionCreatedByAsmPrinter() {#a0756e89d8eafc4bc2503dd3976765f61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SectionDescriptor::setSizesForSectionCreatedByAsmPrinter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Some sections are emitted using <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a>.</p>


<p>In that case "Contents" member of <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> contains elf file. This method searches for section data inside elf file and remember offset to it.</p>


<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-cpp">OutputSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="#a3f6c2fed002a819f9bf08a21adf92476">Contents</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a926af6aca697fdbacb3e3ea1000f0ec4">llvm::object::ObjectFile::createObjectFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a112b0124ddda89fd041dbdbc53016275">llvm::dwarf_linker::parseDebugTableName</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a19378e3183278a6ec1d6fe2f3ac9841c">llvm::dwarf_linker::parallel::SectionDescriptorBase::SectionKind</a>, <a href="#ab947ce3a5eb89fd72e0f787b27364d15">SectionOffsetInsideAsmPrinterOutputEnd</a>, <a href="#aaa9f26636671c4eff83ff3821477a085">SectionOffsetInsideAsmPrinterOutputStart</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a7c3ab4bc92e5a22d3ab1a70e63e04251">llvm::dwarf_linker::parallel::DWARFLinkerImpl::emitAppleAcceleratorSections</a>, <a href="/web-llvm/docs/api/groups/methods/#ga4353067d272bae6ec1a934e5ea39f924">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a267b3ad88431cb638221b36a45f7600f">llvm::dwarf_linker::parallel::DWARFLinkerImpl::emitDWARFv5DebugNamesSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### applyIntVal() {#a404cacae16324605710710194e08e5ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SectionDescriptor::applyIntVal (uint64_t PatchOffset, uint64_t Val, unsigned Size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Writes integer value <span class="doxyComputerOutput">Val</span> of <span class="doxyComputerOutput">Size</span> by specified <span class="doxyComputerOutput">PatchOffset</span>.</p>

<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>, definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-cpp">OutputSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a4c4a80dc8fb3cb9ff7e985798d599313">llvm::dwarf_linker::parallel::SectionDescriptorBase::Endianess</a>, <a href="#a860c597e55feedf9817bdeaf9067b639">getContents</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>


<p>Referenced by <a href="#a5e7ab4547b66cde4652390ba796d97a1">apply</a>.</p>

</div>
</div>

### applySLEB128() {#a4c0cd7586ca23f44571c798723fee65f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SectionDescriptor::applySLEB128 (uint64_t PatchOffset, uint64_t Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Writes integer value <span class="doxyComputerOutput">Val</span> of SLEB128 format by specified <span class="doxyComputerOutput">PatchOffset</span>.</p>

<p>Declaration at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>, definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-cpp">OutputSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac21006e81ffbbc79e8e51e44f7878053">llvm::encodeSLEB128</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a657f147ee0c2ca97c60d8e929acbda5f">llvm::dwarf_linker::parallel::SectionDescriptorBase::Format</a>, <a href="#a860c597e55feedf9817bdeaf9067b639">getContents</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="#a5e7ab4547b66cde4652390ba796d97a1">apply</a>.</p>

</div>
</div>

### applyULEB128() {#a4e237e34d55840912a54fbef648eea92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SectionDescriptor::applyULEB128 (uint64_t PatchOffset, uint64_t Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Writes integer value <span class="doxyComputerOutput">Val</span> of ULEB128 format by specified <span class="doxyComputerOutput">PatchOffset</span>.</p>

<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>, definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-cpp">OutputSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a657f147ee0c2ca97c60d8e929acbda5f">llvm::dwarf_linker::parallel::SectionDescriptorBase::Format</a>, <a href="#a860c597e55feedf9817bdeaf9067b639">getContents</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="#a5e7ab4547b66cde4652390ba796d97a1">apply</a>.</p>

</div>
</div>

### setOutputFormat() {#aa4ef16179cba57f690c921b7778ba2eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::SectionDescriptor::setOutputFormat (<a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">dwarf::FormParams</a> Format, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> Endianess)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets output format.</p>

<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a4c4a80dc8fb3cb9ff7e985798d599313">llvm::dwarf_linker::parallel::SectionDescriptorBase::Endianess</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a657f147ee0c2ca97c60d8e929acbda5f">llvm::dwarf_linker::parallel::SectionDescriptorBase::Format</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### OS {#a01de9af3f8e9b5ca39f42089c9a0e8ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_svector_ostream llvm::dwarf_linker::parallel::SectionDescriptor::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stream which stores data to the Contents.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#ac4560fb1d6b91d4ba6edb7e907573c1e">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::cloneAndEmitDebugFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/debuglinesectionemitter/#a81feed7a90b5abc9e58b574e7da2a360">llvm::dwarf_linker::parallel::DebugLineSectionEmitter::emit</a>, <a href="/web-llvm/docs/api/groups/methods/#ga9b4dbcbc740191455c092e2edd8afa51">llvm::dwarf_linker::parallel::DwarfUnit::emitAbbreviations</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a7c3ab4bc92e5a22d3ab1a70e63e04251">llvm::dwarf_linker::parallel::DWARFLinkerImpl::emitAppleAcceleratorSections</a>, <a href="#a72a02b2842e0381aaeb728cb1969d5e9">emitBinaryData</a>, <a href="/web-llvm/docs/api/groups/methods/#ga4353067d272bae6ec1a934e5ea39f924">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugInfo</a>, <a href="/web-llvm/docs/api/groups/methods/#ga579ac60d76c4a3b6ca084238591d4437">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugStringOffsetSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#aec20444d01151e8ad774f0d1354067c3">llvm::dwarf_linker::parallel::DwarfUnit::emitDwarfAbbrevEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a267b3ad88431cb638221b36a45f7600f">llvm::dwarf_linker::parallel::DWARFLinkerImpl::emitDWARFv5DebugNamesSection</a>, <a href="#a5fdd30c106c85cd071977c5062eeed69">emitInplaceString</a>, <a href="#a4954fa6faa9509d506fcedc034eb02c8">emitIntVal</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a5e9424dbd42c4c0b08ff61c556bd9aa1">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::emitInvariantSections</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#aa5415f7dcc45583b4bb82acb6f64c73a">llvm::dwarf_linker::parallel::DwarfUnit::emitPubAcceleratorEntry</a>, <a href="/web-llvm/docs/api/groups/methods/#ga80d3884d82a541f6f1b11931db9fc5fb">llvm::dwarf_linker::parallel::DwarfUnit::emitPubAccelerators</a>, <a href="#a3fdedfeb863a3688b3eac2b13eea3c87">emitString</a> and <a href="#acfb7f075fc5e83f4c92bbe02c3d088e4">SectionDescriptor</a>.</p>

</div>
</div>

### OutputSections {#a1acb1c59484f29e48610196faf58a5fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::dwarf_linker::parallel::SectionDescriptor::OutputSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>

</div>
</div>

### StartOffset {#af80b542f4b0c15d3425d97257ecda897}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::parallel::SectionDescriptor::StartOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When objects(f.e.</p>


<p>compile units) are glued into the single file, the debug sections corresponding to the concrete object are assigned with offsets inside the whole file. This field keeps offset to the debug section, corresponding to this object.</p>


<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a09b5d1027676907c7bc194a865ffe0df">llvm::dwarf_linker::parallel::OutputSections::applyPatches</a> and <a href="#ab4ee8dc8a752ad8681e4f74a9ea092ae">clearAllSectionData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Contents {#a3f6c2fed002a819f9bf08a21adf92476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutSectionDataTy llvm::dwarf_linker::parallel::SectionDescriptor::Contents</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Section data bits.</p>

<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Referenced by <a href="#a70596a4759ebad01c1367c2719391c6f">clearSectionContent</a>, <a href="#a860c597e55feedf9817bdeaf9067b639">getContents</a>, <a href="#acfb7f075fc5e83f4c92bbe02c3d088e4">SectionDescriptor</a> and <a href="#a0756e89d8eafc4bc2503dd3976765f61">setSizesForSectionCreatedByAsmPrinter</a>.</p>

</div>
</div>

### GlobalData {#af5cd5abea8131106a410e39b80a5589b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkingGlobalData&amp; llvm::dwarf_linker::parallel::SectionDescriptor::GlobalData</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Referenced by <a href="#a3fdedfeb863a3688b3eac2b13eea3c87">emitString</a> and <a href="#acfb7f075fc5e83f4c92bbe02c3d088e4">SectionDescriptor</a>.</p>

</div>
</div>

### SectionOffsetInsideAsmPrinterOutputEnd {#ab947ce3a5eb89fd72e0f787b27364d15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::dwarf_linker::parallel::SectionDescriptor::SectionOffsetInsideAsmPrinterOutputEnd = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Referenced by <a href="#a860c597e55feedf9817bdeaf9067b639">getContents</a> and <a href="#a0756e89d8eafc4bc2503dd3976765f61">setSizesForSectionCreatedByAsmPrinter</a>.</p>

</div>
</div>

### SectionOffsetInsideAsmPrinterOutputStart {#aaa9f26636671c4eff83ff3821477a085}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::dwarf_linker::parallel::SectionDescriptor::SectionOffsetInsideAsmPrinterOutputStart = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Some sections are generated using <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a>.</p>


<p>The real section data located inside elf file in that case. Following fields points to the real section content inside elf file.</p>


<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Referenced by <a href="#a860c597e55feedf9817bdeaf9067b639">getContents</a> and <a href="#a0756e89d8eafc4bc2503dd3976765f61">setSizesForSectionCreatedByAsmPrinter</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-cpp">OutputSections.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
