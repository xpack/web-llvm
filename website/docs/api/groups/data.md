---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/data
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The Members accessed asinchronously. Reference

<p>Data global for the whole linking process. <a href="#details">More...</a></p>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga5e9620201c9b49b8f8c8d68e5feb0bfd">LabelMapTy</a> = SmallDenseMap&lt; uint64_t, uint64_t, 1 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The DW_AT_low_pc of each DW_TAG_label. <a href="#ga5e9620201c9b49b8f8c8d68e5feb0bfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">OffsetToUnitTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gafd7049ce2cb017276874f4c5595f46fb">getUnitFromOffset</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga5c7d9bd15a383062b8e5f75fcf5ae73c">LowPc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9e0f022270d5a3e44af431e3af34652d">HighPc</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab86edd0c48eb5725a308acd67eeae7cf">NoODR</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag indicating whether type de-duplication is forbidden. <a href="#gab86edd0c48eb5725a308acd67eeae7cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">RangesTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga0ec587307301af081bfa7b7c47ad6de4">Ranges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The ranges in that map are the PC ranges for functions in this unit, associated with the PC offset to apply to the addresses to get the linked address. <a href="#ga0ec587307301af081bfa7b7c47ad6de4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4310ce7e9818832db0adcc6862f37c9c">RangesMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">LabelMapTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga1ea6532dfecf3eda51636f70c3724d58">Labels</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2dba5eeef4a0da36a58dc97909718698">LabelsMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; Stage &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga008ed8a31c6ce1601777f59877fcd33d">Stage</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This field keeps current stage of overall compile unit processing. <a href="#ga008ed8a31c6ce1601777f59877fcd33d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">SmallVector&lt; DIEInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga093fd13ae55a992a25c458daaee9cde4">DieInfoArray</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> info indexed by <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> index. <a href="#ga093fd13ae55a992a25c458daaee9cde4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">SmallVector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gadc3acd80975890a2c0c55c46113bbcb5">OutDieOffsetArray</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">SmallVector&lt; TypeEntry * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gabceb5168d49eea87e71da5324da808d6">TypeEntries</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ArrayList&lt; AccelInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga1a53358aaff0b57bd173c8aebee12297">AcceleratorRecords</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list of accelerator records for this unit. <a href="#ga1a53358aaff0b57bd173c8aebee12297">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga33e8e6d22f8dc53ca6e43b03464cb669">UniqueUnitID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for compile unit. <a href="#ga33e8e6d22f8dc53ca6e43b03464cb669">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">StringMap&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaee4878daad7f1fae48bef91eaf49685f">ClangModules</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping the PCM filename to the DwoId. <a href="#gaee4878daad7f1fae48bef91eaf49685f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab1d3ac01513e2f54ae9a9d98f4141ee2">ClangModulesMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; TypeUnit &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga83a3aaddca0607d7b14c89dcf9dd0ccd">ArtificialTypeUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> unit. <a href="#ga83a3aaddca0607d7b14c89dcf9dd0ccd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">LinkingGlobalData</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2c981717283fff014f2fc47ec9febc66">GlobalData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">StringEntryToDwarfStringPoolEntryMap</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa8ca7922927481c9c031e92763e35bbd">DebugStrStrings</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DwarfStringPoolEntries for .debug_str section. <a href="#gaa8ca7922927481c9c031e92763e35bbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">StringEntryToDwarfStringPoolEntryMap</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6990299c0e834de5dff8181b883da306">DebugLineStrStrings</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DwarfStringPoolEntries for .debug_line_str section. <a href="#ga6990299c0e834de5dff8181b883da306">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">SmallVector&lt; std::unique_ptr&lt; LinkContext &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga57b26f33c0c25d1960ef1af6c0bb9789">ObjectContexts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps all linking contexts. <a href="#ga57b26f33c0c25d1960ef1af6c0bb9789">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">OutputSections</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gacdf65b146e52dc91522d73d43113f388">CommonSections</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common sections. <a href="#gacdf65b146e52dc91522d73d43113f388">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">SectionHandlerTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7a05179a9b937ed748b2048984414169">SectionHandler</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hanler for output sections. <a href="#ga7a05179a9b937ed748b2048984414169">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga51eaaa95c9ad291f71a711dea6bedfb4">OverallNumberOfCU</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Overall compile units number. <a href="#ga51eaaa95c9ad291f71a711dea6bedfb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Data global for the whole linking process.</p>

<div class="doxySectionDef">

## Typedefs

### LabelMapTy {#ga5e9620201c9b49b8f8c8d68e5feb0bfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::parallel::CompileUnit::LabelMapTy =  SmallDenseMap&lt;uint64_t, uint64_t, 1&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The DW_AT_low_pc of each DW_TAG_label.</p>

<p>Definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AcceleratorRecords {#ga1a53358aaff0b57bd173c8aebee12297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayList&lt;AccelInfo&gt; llvm::dwarf_linker::parallel::CompileUnit::AcceleratorRecords</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The list of accelerator records for this unit.</p>

<p>Definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### ArtificialTypeUnit {#ga83a3aaddca0607d7b14c89dcf9dd0ccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;TypeUnit&gt; llvm::dwarf_linker::parallel::DWARFLinkerImpl::ArtificialTypeUnit</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> unit.</p>

<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a9582267f462865c7f0de3c9e9aed93b5">llvm::dwarf_linker::parallel::DWARFLinkerImpl::forEachCompileAndTypeUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a1a8083cc3c516a879074fa43a7b70a51">llvm::dwarf_linker::parallel::DWARFLinkerImpl::forEachObjectSectionsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#aba93286151b2e53982f5e74695b42a24">llvm::dwarf_linker::parallel::DWARFLinkerImpl::forEachOutputString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a71330a23d2feee283a26bc08a32a412c">llvm::dwarf_linker::parallel::DWARFLinkerImpl::glueCompileUnitsAndWriteToTheOutput</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a42302ab883ef8ec7e51b00701d626ce4">llvm::dwarf_linker::parallel::DWARFLinkerImpl::link</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#ad06d8aa0d7980827ad6f0a8543657f73">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::link</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a8d0aeeed6972f179a2b97439943e7629">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::linkSingleCompileUnit</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#af05462e5991a1325a9944da1b5d1d5b9">llvm::dwarf_linker::parallel::DWARFLinkerImpl::patchOffsetsAndSizes</a>.</p>

</div>
</div>

### ClangModules {#gaee4878daad7f1fae48bef91eaf49685f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;uint64_t&gt; llvm::dwarf_linker::parallel::DWARFLinkerImpl::ClangModules</td>
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

<p>Mapping the PCM filename to the DwoId.</p>

<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#ab732f1d39ccd237bcf728ca5bb48ce14">llvm::dwarf_linker::parallel::DWARFLinkerImpl::addObjectFile</a>.</p>

</div>
</div>

### ClangModulesMutex {#gab1d3ac01513e2f54ae9a9d98f4141ee2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::dwarf_linker::parallel::DWARFLinkerImpl::ClangModulesMutex</td>
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



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>

</div>
</div>

### CommonSections {#gacdf65b146e52dc91522d73d43113f388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputSections llvm::dwarf_linker::parallel::DWARFLinkerImpl::CommonSections</td>
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

<p>Common sections.</p>

<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#aaef75f38cdc5c7015fe251728c47c9d9">llvm::dwarf_linker::parallel::DWARFLinkerImpl::DWARFLinkerImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a7c3ab4bc92e5a22d3ab1a70e63e04251">llvm::dwarf_linker::parallel::DWARFLinkerImpl::emitAppleAcceleratorSections</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#ac8c9b6d8ca3948e29ec1511b6037cdcf">llvm::dwarf_linker::parallel::DWARFLinkerImpl::emitCommonSectionsAndWriteCompileUnitsToTheOutput</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a267b3ad88431cb638221b36a45f7600f">llvm::dwarf_linker::parallel::DWARFLinkerImpl::emitDWARFv5DebugNamesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a9d569b5d160f74ec5712bf4c3be31c60">llvm::dwarf_linker::parallel::DWARFLinkerImpl::emitStringSections</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a42302ab883ef8ec7e51b00701d626ce4">llvm::dwarf_linker::parallel::DWARFLinkerImpl::link</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a4b5b872efe54c2815cd80e6f96280e0b">llvm::dwarf_linker::parallel::DWARFLinkerImpl::writeCommonSectionsToTheOutput</a>.</p>

</div>
</div>

### DebugLineStrStrings {#ga6990299c0e834de5dff8181b883da306}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringEntryToDwarfStringPoolEntryMap llvm::dwarf_linker::parallel::DWARFLinkerImpl::DebugLineStrStrings</td>
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

<p>DwarfStringPoolEntries for .debug_line_str section.</p>

<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a3c8a25a460f1104b2e1128879d9173d9">llvm::dwarf_linker::parallel::DWARFLinkerImpl::assignOffsetsToStrings</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#aba43fbeec79fbb09310fc06354a9f74a">llvm::dwarf_linker::parallel::DWARFLinkerImpl::cleanupDataAfterDWARFOutputIsWritten</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#aaef75f38cdc5c7015fe251728c47c9d9">llvm::dwarf_linker::parallel::DWARFLinkerImpl::DWARFLinkerImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a9d569b5d160f74ec5712bf4c3be31c60">llvm::dwarf_linker::parallel::DWARFLinkerImpl::emitStringSections</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#af05462e5991a1325a9944da1b5d1d5b9">llvm::dwarf_linker::parallel::DWARFLinkerImpl::patchOffsetsAndSizes</a>.</p>

</div>
</div>

### DebugStrStrings {#gaa8ca7922927481c9c031e92763e35bbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringEntryToDwarfStringPoolEntryMap llvm::dwarf_linker::parallel::DWARFLinkerImpl::DebugStrStrings</td>
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

<p>DwarfStringPoolEntries for .debug_str section.</p>

<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a3c8a25a460f1104b2e1128879d9173d9">llvm::dwarf_linker::parallel::DWARFLinkerImpl::assignOffsetsToStrings</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#aba43fbeec79fbb09310fc06354a9f74a">llvm::dwarf_linker::parallel::DWARFLinkerImpl::cleanupDataAfterDWARFOutputIsWritten</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#aaef75f38cdc5c7015fe251728c47c9d9">llvm::dwarf_linker::parallel::DWARFLinkerImpl::DWARFLinkerImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a7c3ab4bc92e5a22d3ab1a70e63e04251">llvm::dwarf_linker::parallel::DWARFLinkerImpl::emitAppleAcceleratorSections</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a267b3ad88431cb638221b36a45f7600f">llvm::dwarf_linker::parallel::DWARFLinkerImpl::emitDWARFv5DebugNamesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a9d569b5d160f74ec5712bf4c3be31c60">llvm::dwarf_linker::parallel::DWARFLinkerImpl::emitStringSections</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#af05462e5991a1325a9944da1b5d1d5b9">llvm::dwarf_linker::parallel::DWARFLinkerImpl::patchOffsetsAndSizes</a>.</p>

</div>
</div>

### DieInfoArray {#ga093fd13ae55a992a25c458daaee9cde4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DIEInfo&gt; llvm::dwarf_linker::parallel::CompileUnit::DieInfoArray</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> info indexed by <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> index.</p>

<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getUnitFromOffset {#gafd7049ce2cb017276874f4c5595f46fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetToUnitTy llvm::dwarf_linker::parallel::CompileUnit::getUnitFromOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### GlobalData {#ga2c981717283fff014f2fc47ec9febc66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkingGlobalData llvm::dwarf_linker::parallel::DWARFLinkerImpl::GlobalData</td>
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



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/methods/#ga447b8844a29e63edeb2f8f111f9d4ed9">llvm::dwarf_linker::parallel::DWARFLinkerImpl::addAccelTableKind</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#ab732f1d39ccd237bcf728ca5bb48ce14">llvm::dwarf_linker::parallel::DWARFLinkerImpl::addObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#aba43fbeec79fbb09310fc06354a9f74a">llvm::dwarf_linker::parallel::DWARFLinkerImpl::cleanupDataAfterDWARFOutputIsWritten</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#aaef75f38cdc5c7015fe251728c47c9d9">llvm::dwarf_linker::parallel::DWARFLinkerImpl::DWARFLinkerImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#ac8c9b6d8ca3948e29ec1511b6037cdcf">llvm::dwarf_linker::parallel::DWARFLinkerImpl::emitCommonSectionsAndWriteCompileUnitsToTheOutput</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a71330a23d2feee283a26bc08a32a412c">llvm::dwarf_linker::parallel::DWARFLinkerImpl::glueCompileUnitsAndWriteToTheOutput</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a42302ab883ef8ec7e51b00701d626ce4">llvm::dwarf_linker::parallel::DWARFLinkerImpl::link</a>, <a href="/web-llvm/docs/api/groups/methods/#ga833ee700f8518d752a7b88225ed74996">llvm::dwarf_linker::parallel::DWARFLinkerImpl::setAllowNonDeterministicOutput</a>, <a href="/web-llvm/docs/api/groups/methods/#ga372b14880235403f9e6558e8077d7bd7">llvm::dwarf_linker::parallel::DWARFLinkerImpl::setInputVerificationHandler</a>, <a href="/web-llvm/docs/api/groups/methods/#ga87f3f8572db8476d4613032daee7afb8">llvm::dwarf_linker::parallel::DWARFLinkerImpl::setKeepFunctionForStatic</a>, <a href="/web-llvm/docs/api/groups/methods/#gab184213d426e7f081daf5126d4be8d0c">llvm::dwarf_linker::parallel::DWARFLinkerImpl::setNoODR</a>, <a href="/web-llvm/docs/api/groups/methods/#ga1f6a1429f7ebe1cca2f2dd150a0e215b">llvm::dwarf_linker::parallel::DWARFLinkerImpl::setNumThreads</a>, <a href="/web-llvm/docs/api/groups/methods/#ga3fbe10652ed6870909b2ca982f8ec921">llvm::dwarf_linker::parallel::DWARFLinkerImpl::setObjectPrefixMap</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#abb9d371d27517ff11d4e9c7ccdf17a8e">llvm::dwarf_linker::parallel::DWARFLinkerImpl::setOutputDWARFHandler</a>, <a href="/web-llvm/docs/api/groups/methods/#gac3b0a6b8f7bcd351cd401bed2d17cb7c">llvm::dwarf_linker::parallel::DWARFLinkerImpl::setPrependPath</a>, <a href="/web-llvm/docs/api/groups/methods/#gaa6301620399ecf2b208db01a8684e685">llvm::dwarf_linker::parallel::DWARFLinkerImpl::setStatistics</a>, <a href="/web-llvm/docs/api/groups/methods/#ga8f0f5f298730862e2cbb1d40c00b1bd1">llvm::dwarf_linker::parallel::DWARFLinkerImpl::setSwiftInterfacesMap</a>, <a href="/web-llvm/docs/api/groups/methods/#ga2814e2cc1c4cb63b8f5cf54f16c2d5f7">llvm::dwarf_linker::parallel::DWARFLinkerImpl::setTargetDWARFVersion</a>, <a href="/web-llvm/docs/api/groups/methods/#ga8a80ebc00f7b521e86733924c74b607f">llvm::dwarf_linker::parallel::DWARFLinkerImpl::setUpdateIndexTablesOnly</a>, <a href="/web-llvm/docs/api/groups/methods/#ga3353de162ad20f4b351ce8f7f20ed0cf">llvm::dwarf_linker::parallel::DWARFLinkerImpl::setVerbosity</a>, <a href="/web-llvm/docs/api/groups/methods/#ga8729af41da30f5c338b8978beacc95b1">llvm::dwarf_linker::parallel::DWARFLinkerImpl::setVerifyInputDWARF</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a49eedb8f4407a04a750f0b63384f8217">llvm::dwarf_linker::parallel::DWARFLinkerImpl::validateAndUpdateOptions</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a901080a7f2755abf0fc90c2d0d9da87f">llvm::dwarf_linker::parallel::DWARFLinkerImpl::verifyInput</a>.</p>

</div>
</div>

### HighPc {#ga9e0f022270d5a3e44af431e3af34652d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::parallel::CompileUnit::HighPc = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### Labels {#ga1ea6532dfecf3eda51636f70c3724d58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LabelMapTy llvm::dwarf_linker::parallel::CompileUnit::Labels</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 713 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### LabelsMutex {#ga2dba5eeef4a0da36a58dc97909718698}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::dwarf_linker::parallel::CompileUnit::LabelsMutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 714 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### LowPc {#ga5c7d9bd15a383062b8e5f75fcf5ae73c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::dwarf_linker::parallel::CompileUnit::LowPc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 699 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### NoODR {#gab86edd0c48eb5725a308acd67eeae7cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::CompileUnit::NoODR = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag indicating whether type de-duplication is forbidden.</p>

<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### ObjectContexts {#ga57b26f33c0c25d1960ef1af6c0bb9789}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;LinkContext&gt; &gt; llvm::dwarf_linker::parallel::DWARFLinkerImpl::ObjectContexts</td>
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

<p>Keeps all linking contexts.</p>

<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#ab732f1d39ccd237bcf728ca5bb48ce14">llvm::dwarf_linker::parallel::DWARFLinkerImpl::addObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a9582267f462865c7f0de3c9e9aed93b5">llvm::dwarf_linker::parallel::DWARFLinkerImpl::forEachCompileAndTypeUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a392cf645fc5b9f664baf4a278c0cd5b3">llvm::dwarf_linker::parallel::DWARFLinkerImpl::forEachCompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a1a8083cc3c516a879074fa43a7b70a51">llvm::dwarf_linker::parallel::DWARFLinkerImpl::forEachObjectSectionsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a42302ab883ef8ec7e51b00701d626ce4">llvm::dwarf_linker::parallel::DWARFLinkerImpl::link</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a557d8187b93bd54d7263d4755c5e99e5">llvm::dwarf_linker::parallel::DWARFLinkerImpl::printStatistic</a> and <a href="/web-llvm/docs/api/groups/methods/#gafe8baf0ba96e0cb88ec5dd7695a2986b">llvm::dwarf_linker::parallel::DWARFLinkerImpl::setEstimatedObjfilesAmount</a>.</p>

</div>
</div>

### OutDieOffsetArray {#gadc3acd80975890a2c0c55c46113bbcb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;uint64_t&gt; llvm::dwarf_linker::parallel::CompileUnit::OutDieOffsetArray</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 721 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### OverallNumberOfCU {#ga51eaaa95c9ad291f71a711dea6bedfb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::parallel::DWARFLinkerImpl::OverallNumberOfCU = 0</td>
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

<p>Overall compile units number.</p>

<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#ab732f1d39ccd237bcf728ca5bb48ce14">llvm::dwarf_linker::parallel::DWARFLinkerImpl::addObjectFile</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a42302ab883ef8ec7e51b00701d626ce4">llvm::dwarf_linker::parallel::DWARFLinkerImpl::link</a>.</p>

</div>
</div>

### Ranges {#ga0ec587307301af081bfa7b7c47ad6de4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RangesTy llvm::dwarf_linker::parallel::CompileUnit::Ranges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The ranges in that map are the PC ranges for functions in this unit, associated with the PC offset to apply to the addresses to get the linked address.</p>

<p>Definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### RangesMutex {#ga4310ce7e9818832db0adcc6862f37c9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::dwarf_linker::parallel::CompileUnit::RangesMutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 709 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### SectionHandler {#ga7a05179a9b937ed748b2048984414169}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionHandlerTy llvm::dwarf_linker::parallel::DWARFLinkerImpl::SectionHandler = nullptr</td>
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

<p>Hanler for output sections.</p>

<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a71330a23d2feee283a26bc08a32a412c">llvm::dwarf_linker::parallel::DWARFLinkerImpl::glueCompileUnitsAndWriteToTheOutput</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#abb9d371d27517ff11d4e9c7ccdf17a8e">llvm::dwarf_linker::parallel::DWARFLinkerImpl::setOutputDWARFHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a4b5b872efe54c2815cd80e6f96280e0b">llvm::dwarf_linker::parallel::DWARFLinkerImpl::writeCommonSectionsToTheOutput</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a2e4feb28330f8c865244bec30383d1a9">llvm::dwarf_linker::parallel::DWARFLinkerImpl::writeCompileUnitsToTheOutput</a>.</p>

</div>
</div>

### Stage {#ga008ed8a31c6ce1601777f59877fcd33d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;Stage&gt; llvm::dwarf_linker::parallel::CompileUnit::Stage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This field keeps current stage of overall compile unit processing.</p>

<p>Definition at line 717 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### TypeEntries {#gabceb5168d49eea87e71da5324da808d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;TypeEntry *&gt; llvm::dwarf_linker::parallel::CompileUnit::TypeEntries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 722 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### UniqueUnitID {#ga33e8e6d22f8dc53ca6e43b03464cb669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;size_t&gt; llvm::dwarf_linker::parallel::DWARFLinkerImpl::UniqueUnitID</td>
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

<p>Unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for compile unit.</p>

<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#ab732f1d39ccd237bcf728ca5bb48ce14">llvm::dwarf_linker::parallel::DWARFLinkerImpl::addObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#aaef75f38cdc5c7015fe251728c47c9d9">llvm::dwarf_linker::parallel::DWARFLinkerImpl::DWARFLinkerImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a42302ab883ef8ec7e51b00701d626ce4">llvm::dwarf_linker::parallel::DWARFLinkerImpl::link</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
