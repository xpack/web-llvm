---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/typeunit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TypeUnit` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Unit is used to represent an artificial compilation unit which keeps all type information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::TypeUnit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinker/Parallel/DWARFLinkerTypeUnit.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit">DwarfUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for all Dwarf units(Compile unit/Type table unit). <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf32c0c93c48071b7c04c7fe558ce87b">DirectoriesMapTy</a> = std::map&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> *, size_t, CmpStringEntryRef &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Data members keeping file names for line table. <a href="#acf32c0c93c48071b7c04c7fe558ce87b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a254dff5ce1e179fd7e6c0a08d16fcc25">FilenamesMapTy</a> = std::map&lt; std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> *, uint64_t &gt;, size_t, CmpDirIDStringEntryRef &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7ec06f047bb304a65a2c02f3bb13063">TypeUnit</a> (LinkingGlobalData &amp;GlobalData, unsigned ID, std::optional&lt; uint16_t &gt; Language, dwarf::FormParams Format, llvm::endianness Endianess)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafd0fac7574417fa923ca2bce4b9b85c">createDIETree</a> (BumpPtrAllocator &amp;Allocator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generates <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree based on information from TypesMap. <a href="#aafd0fac7574417fa923ca2bce4b9b85c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2de70543d073c4a85bf44c845b7305e9">finishCloningAndEmit</a> (const Triple &amp;TargetTriple)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits resulting dwarf based on information from <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree. <a href="#a2de70543d073c4a85bf44c845b7305e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typepool">TypePool</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b81039b4916fdc6acfd00effec90b7b">getTypePool</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns global type pool. <a href="#a2b81039b4916fdc6acfd00effec90b7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0634202a336bbb1a7a03b7885865ba1">forEachAcceleratorRecord</a> (function_ref&lt; void(AccelInfo &amp;)&gt; Handler) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerates all accelerator records and call <span class="doxyComputerOutput">Handler</span> for each. <a href="#ad0634202a336bbb1a7a03b7885865ba1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8797c2bd69a6364a695cf7f88e3f5c11">getDebugStrIndex</a> (const StringEntry *String) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns index for the specified <span class="doxyComputerOutput">String</span> inside .debug_str_offsets. <a href="#a8797c2bd69a6364a695cf7f88e3f5c11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b32b6e055f2378aeb16ea13c10dd2a1">saveAcceleratorInfo</a> (const TypeUnitAccelInfo &amp;Info)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds <span class="doxyComputerOutput">Info</span> to the unit's accelerator records. <a href="#a0b32b6e055f2378aeb16ea13c10dd2a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfc41bff42dcd439cb2471a559c94b59">finalizeTypeEntryRec</a> (uint64_t OutOffset, DIE *OutDIE, TypeEntry *Entry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> DIEs are partially created at clonning stage. <a href="#acfc41bff42dcd439cb2471a559c94b59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5507388dec829face21275355050721">prepareDataForTreeCreation</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prepares DIEs to be linked into the tree. <a href="#ac5507388dec829face21275355050721">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7154b919b3ba7431056ccae0ec240671">addFileNameIntoLinetable</a> (StringEntry *Dir, StringEntry *FileName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add specified <span class="doxyComputerOutput">Dir</span> and <span class="doxyComputerOutput">Filename</span> into the line table of this type unit. <a href="#a7154b919b3ba7431056ccae0ec240671">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a>, uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18c0adcb73bc81c82ebd5ac9e8eea4fa">getScalarFormForValue</a> (uint64_t Value) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fa228353c42fed8cb59bd4fc06e6a4d">getSizeByAttrForm</a> (dwarf::Form Form) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30e031690972f48d7add65991a7d04aa">Language</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The DW_AT_language of this unit. <a href="#a30e031690972f48d7add65991a7d04aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable">DWARFDebugLine::LineTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdea2a1076b7ec3ce1ab8b323d514c07">LineTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This unit line table. <a href="#acdea2a1076b7ec3ce1ab8b323d514c07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DirectoriesMapTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f163afe4239194025f50e8e1ee90904">DirectoriesMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FilenamesMapTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4d97c97886b0a49a214f21d84e7e056">FileNamesMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typepool">TypePool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a880091c8f8312236175956e08f7df032">Types</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> DIEs tree. <a href="#a880091c8f8312236175956e08f7df032">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/arraylist">ArrayList</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/typeunit/typeunitaccelinfo">TypeUnitAccelInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dc400d0324deb648064d2b1492790b9">AcceleratorRecords</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of accelerator entries for this unit. <a href="#a6dc400d0324deb648064d2b1492790b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84dc96679214e94eba00c0030439ae64">DebugStringIndexMapMutex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Guard for DebugStringIndexMap. <a href="#a84dc96679214e94eba00c0030439ae64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Unit is used to represent an artificial compilation unit which keeps all type information.</p>


<p>This type information is referenced from other compilation units.</p>


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### DirectoriesMapTy {#acf32c0c93c48071b7c04c7fe558ce87b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::parallel::TypeUnit::DirectoriesMapTy =  std::map&lt;StringEntry *, size_t, CmpStringEntryRef&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Data members keeping file names for line table.</p>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>.</p>

</div>
</div>

### FilenamesMapTy {#a254dff5ce1e179fd7e6c0a08d16fcc25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::parallel::TypeUnit::FilenamesMapTy =  std::map&lt;std::pair&lt;StringEntry *, uint64_t&gt;, size_t,
                                  CmpDirIDStringEntryRef&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TypeUnit() {#af7ec06f047bb304a65a2c02f3bb13063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeUnit::TypeUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/linkingglobaldata">LinkingGlobalData</a> &amp; GlobalData, unsigned ID, std::optional&lt; uint16_t &gt; Language, <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">dwarf::FormParams</a> Format, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> Endianess)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-cpp">DWARFLinkerTypeUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24af6f6931771db95a6bffec131b856bd50">llvm::dwarf_linker::DebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ad367b733292adfe15b6d45c5fc4db8b2">llvm::dwarf_linker::parallel::DwarfUnit::DwarfUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a1766b7f5152f1dfe8b9498df8314a356">llvm::dwarf_linker::parallel::OutputSections::Format</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a33ecefa9aec7bce5d08e92138ae1be08">llvm::dwarf_linker::parallel::OutputSections::getFormParams</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#ab6597212694001f13f816944c69bb0b2">llvm::dwarf_linker::parallel::OutputSections::getOrCreateSectionDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ab4bc76d8c13939bdfdaf0b96aa1d4f82">llvm::dwarf_linker::parallel::DwarfUnit::ID</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a6d003066059ba2b698ace39edf39e2cf">llvm::dwarf_linker::parallel::OutputSections::setOutputFormat</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#a2c338a607208f34a94cce92277176e35">llvm::dwarf_linker::parallel::DwarfUnit::UnitName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createDIETree() {#aafd0fac7574417fa923ca2bce4b9b85c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TypeUnit::createDIETree (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generates <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree based on information from TypesMap.</p>

<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-cpp">DWARFLinkerTypeUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/diegenerator/#af54f8f41713ea2fd258a3143440bda14">llvm::dwarf_linker::parallel::DIEGenerator::addScalarAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/diegenerator/#a4e0b5008ca82c7f6a4b429d2ec441f7f">llvm::dwarf_linker::parallel::DIEGenerator::addStringPlaceholderAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/diegenerator/#a7bcf59b48e896fea4f6661dffa7351da">llvm::dwarf_linker::parallel::DIEGenerator::createDIE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24af6f6931771db95a6bffec131b856bd50">llvm::dwarf_linker::DebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a64dbaf07475300f47afcfd402de0a403">llvm::dwarf_linker::DebugLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#a98241a1a7e8a7cb3c7fa4e9202a5011b">llvm::dwarf_linker::parallel::DwarfUnit::DebugStringIndexMap</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#a191332ee5e954e8a95460cfaa5e88f26">llvm::DIE::getAbbrevNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a7e3b66f8d958f065300cf5ddda43f715">llvm::dwarf_linker::parallel::OutputSections::getDebugInfoHeaderSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0c784bcfa4ff19345f9220e672cc6153">llvm::dwarf_linker::parallel::OutputSections::getDebugStrOffsetsHeaderSize</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#ac44e64e0d814099105dde610b11c9914">llvm::DIE::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#ab6597212694001f13f816944c69bb0b2">llvm::dwarf_linker::parallel::OutputSections::getOrCreateSectionDescriptor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa02a1d8fb0f561ab81f4a2570db7dc28">llvm::getULEB128Size</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ab4d5c28a1b468db516b750ace450138d">llvm::dwarf_linker::parallel::DwarfUnit::getUnitName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#ada575452de07c297cfeea8ce744a79ed">llvm::dwarf_linker::parallel::SectionDescriptor::notePatchWithOffsetUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#ac5e71a222d770109a27a408f3df9d573">llvm::DIE::setOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ad24c182dd9def83d9d63a6cce49331c0">llvm::dwarf_linker::parallel::DwarfUnit::setOutUnitDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#a64a6a6e0ea513fadb1e384e8ef04bcca">llvm::DIE::setSize</a>, <a href="/web-llvm/docs/api/classes/llvm/parallel/taskgroup/#a5f936d7e589b0615fccac0a4c0cb8d97">llvm::parallel::TaskGroup::spawn</a> and <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af5dd7241878be5eed07736eb156bb10b">llvm::SmallString&lt; InternalLen &gt;::str</a>.</p>


<p>Referenced by <a href="#a2de70543d073c4a85bf44c845b7305e9">finishCloningAndEmit</a>.</p>

</div>
</div>

### finishCloningAndEmit() {#a2de70543d073c4a85bf44c845b7305e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TypeUnit::finishCloningAndEmit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TargetTriple)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits resulting dwarf based on information from <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree.</p>

<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>, definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-cpp">DWARFLinkerTypeUnit.cpp</a>.</p>


<p>References <a href="#aafd0fac7574417fa923ca2bce4b9b85c">createDIETree</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a67fcda65761299e9cc1cf923fe1bc751">llvm::dwarf_linker::DebugAbbrev</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24af6f6931771db95a6bffec131b856bd50">llvm::dwarf_linker::DebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a64dbaf07475300f47afcfd402de0a403">llvm::dwarf_linker::DebugLine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ab9f0ac5cd82959dfec84a8c1e8bf6aaf">llvm::dwarf_linker::DebugPubNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ab177be5746b8cbbce9ae68af24455c98">llvm::dwarf_linker::DebugPubTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24aff29b8418c7593f015431386cf40b181">llvm::dwarf_linker::DebugStrOffsets</a>, <a href="/web-llvm/docs/api/groups/methods/#ga9b4dbcbc740191455c092e2edd8afa51">llvm::dwarf_linker::parallel::DwarfUnit::emitAbbreviations</a>, <a href="/web-llvm/docs/api/groups/methods/#ga4353067d272bae6ec1a934e5ea39f924">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugInfo</a>, <a href="/web-llvm/docs/api/groups/methods/#gaf5ad0e93c4f3b97d0e8d192675945746">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugLine</a>, <a href="/web-llvm/docs/api/groups/methods/#ga579ac60d76c4a3b6ca084238591d4437">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugStringOffsetSection</a>, <a href="/web-llvm/docs/api/groups/methods/#ga80d3884d82a541f6f1b11931db9fc5fb">llvm::dwarf_linker::parallel::DwarfUnit::emitPubAccelerators</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#ab6597212694001f13f816944c69bb0b2">llvm::dwarf_linker::parallel::OutputSections::getOrCreateSectionDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#afbcc691dc3aee7912fd0e6f49fb1bb8a">llvm::dwarf_linker::parallel::DwarfUnit::getOutUnitDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6c45e3e95dd28727729bc0b62b2434a">llvm::parallelForEachError</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a78ca7920cd1aaf69f7da553285c55308aa29bdd003ef6c0c34279807341f450f2">llvm::dwarf_linker::DWARFLinkerBase::Pub</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### forEachAcceleratorRecord() {#ad0634202a336bbb1a7a03b7885865ba1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::TypeUnit::forEachAcceleratorRecord (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarfunit/accelinfo">AccelInfo</a> &amp;)&gt; Handler)</td>
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

<p>Enumerates all accelerator records and call <span class="doxyComputerOutput">Handler</span> for each.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>.</p>

</div>
</div>

### getDebugStrIndex() {#a8797c2bd69a6364a695cf7f88e3f5c11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::parallel::TypeUnit::getDebugStrIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> * String)</td>
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

<p>Returns index for the specified <span class="doxyComputerOutput">String</span> inside .debug_str_offsets.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#a98241a1a7e8a7cb3c7fa4e9202a5011b">llvm::dwarf_linker::parallel::DwarfUnit::DebugStringIndexMap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>.</p>

</div>
</div>

### getTypePool() {#a2b81039b4916fdc6acfd00effec90b7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypePool &amp; llvm::dwarf_linker::parallel::TypeUnit::getTypePool ()</td>
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

<p>Returns global type pool.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ab33a7e6fdc362895e1b739081c1286ba">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmit</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a1df1c26e0a60f062547d6ba537e0021a">llvm::dwarf_linker::parallel::CompileUnit::cloneDIE</a>.</p>

</div>
</div>

### saveAcceleratorInfo() {#a0b32b6e055f2378aeb16ea13c10dd2a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::TypeUnit::saveAcceleratorInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/typeunit/typeunitaccelinfo">TypeUnitAccelInfo</a> &amp; Info)</td>
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

<p>Adds <span class="doxyComputerOutput">Info</span> to the unit's accelerator records.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addFileNameIntoLinetable() {#a7154b919b3ba7431056ccae0ec240671}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t TypeUnit::addFileNameIntoLinetable (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> * Dir, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> * FileName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add specified <span class="doxyComputerOutput">Dir</span> and <span class="doxyComputerOutput">Filename</span> into the line table of this type unit.</p>

<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>, definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-cpp">DWARFLinkerTypeUnit.cpp</a>.</p>

</div>
</div>

### finalizeTypeEntryRec() {#acfc41bff42dcd439cb2471a559c94b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t TypeUnit::finalizeTypeEntryRec (uint64_t OutOffset, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * OutDIE, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> * Entry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> DIEs are partially created at clonning stage.</p>


<p>They are organised as a tree using type entries. This function links DIEs(corresponding
to the type entries) into the tree structure.</p>


<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>, definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-cpp">DWARFLinkerTypeUnit.cpp</a>.</p>

</div>
</div>

### getScalarFormForValue() {#a18c0adcb73bc81c82ebd5ac9e8eea4fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; dwarf::Form, uint8_t &gt; TypeUnit::getScalarFormForValue (uint64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>, definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-cpp">DWARFLinkerTypeUnit.cpp</a>.</p>

</div>
</div>

### getSizeByAttrForm() {#a8fa228353c42fed8cb59bd4fc06e6a4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t TypeUnit::getSizeByAttrForm (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> Form)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>, definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-cpp">DWARFLinkerTypeUnit.cpp</a>.</p>

</div>
</div>

### prepareDataForTreeCreation() {#ac5507388dec829face21275355050721}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TypeUnit::prepareDataForTreeCreation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prepares DIEs to be linked into the tree.</p>

<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-cpp">DWARFLinkerTypeUnit.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AcceleratorRecords {#a6dc400d0324deb648064d2b1492790b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayList&lt;TypeUnitAccelInfo&gt; llvm::dwarf_linker::parallel::TypeUnit::AcceleratorRecords</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of accelerator entries for this unit.</p>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>.</p>

</div>
</div>

### DebugStringIndexMapMutex {#a84dc96679214e94eba00c0030439ae64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::dwarf_linker::parallel::TypeUnit::DebugStringIndexMapMutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Guard for DebugStringIndexMap.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>.</p>

</div>
</div>

### DirectoriesMap {#a5f163afe4239194025f50e8e1ee90904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DirectoriesMapTy llvm::dwarf_linker::parallel::TypeUnit::DirectoriesMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>.</p>

</div>
</div>

### FileNamesMap {#ad4d97c97886b0a49a214f21d84e7e056}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FilenamesMapTy llvm::dwarf_linker::parallel::TypeUnit::FileNamesMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>.</p>

</div>
</div>

### Language {#a30e031690972f48d7add65991a7d04aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint16_t&gt; llvm::dwarf_linker::parallel::TypeUnit::Language</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The DW_AT_language of this unit.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>.</p>

</div>
</div>

### LineTable {#acdea2a1076b7ec3ce1ab8b323d514c07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDebugLine::LineTable llvm::dwarf_linker::parallel::TypeUnit::LineTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This unit line table.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>.</p>

</div>
</div>

### Types {#a880091c8f8312236175956e08f7df032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypePool llvm::dwarf_linker::parallel::TypeUnit::Types</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> DIEs tree.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-cpp">DWARFLinkerTypeUnit.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
