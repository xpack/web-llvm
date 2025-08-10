---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/compileunit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CompileUnit` Class

<p>Stores all information related to a compile unit, be it in its original instance of the object file or its brand new cloned and generated <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::CompileUnit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinker/Parallel/DWARFLinkerCompileUnit.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af89f4b5ceca35d58f59a02da07369e88">LinkedLocationExpressionsVector</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; LinkedLocationExpressionsWithOffsetPatches &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ec1f214175af88c2caf6f22de734234">ResolvedPathsMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cached resolved paths from the line table. <a href="#a8ec1f214175af88c2caf6f22de734234">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#ga5e9620201c9b49b8f8c8d68e5feb0bfd">LabelMapTy</a> = SmallDenseMap&lt; uint64_t, uint64_t, 1 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The DW_AT_low_pc of each DW_TAG_label. <a href="/web-llvm/docs/api/groups/data/#ga5e9620201c9b49b8f8c8d68e5feb0bfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Stage : uint8_t { <a href="#ac8f9de0c8d86b73c76368b681f0d7883">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The stages of new compile unit processing. <a href="#ac8f9de0c8d86b73c76368b681f0d7883">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DieOutputPlacement : uint8_t { <a href="#a5270021419d157f502aba678e1ee8549">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Kinds of placement for the output die. <a href="#a5270021419d157f502aba678e1ee8549">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe722b66707f8b5e4aaa19a24810480f">CompileUnit</a> (LinkingGlobalData &amp;GlobalData, unsigned ID, StringRef ClangModuleName, DWARFFile &amp;File, OffsetToUnitTy UnitFromOffset, dwarf::FormParams Format, llvm::endianness Endianess)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26a4de20c065ba21d3af3b8f2fc2bb50">CompileUnit</a> (LinkingGlobalData &amp;GlobalData, DWARFUnit &amp;OrigUnit, unsigned ID, StringRef ClangModuleName, DWARFFile &amp;File, OffsetToUnitTy UnitFromOffset, dwarf::FormParams Format, llvm::endianness Endianess)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac8f9de0c8d86b73c76368b681f0d7883">Stage</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7ae271aeb81750becb81e74a7be7582">getStage</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns stage of overall processing. <a href="#ab7ae271aeb81750becb81e74a7be7582">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5adb90b6c8a1e87fcc97f66cd70adfc">setStage</a> (Stage Stage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set stage of overall processing. <a href="#ab5adb90b6c8a1e87fcc97f66cd70adfc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee0400306419adf13952ab2f6734fc0a">loadLineTable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads unit line table. <a href="#aee0400306419adf13952ab2f6734fc0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91509cfc9da285731d483b1373c8584d">loadInputDIEs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns name of the file for the <span class="doxyComputerOutput">FileIdx</span> from the unit`s line table. <a href="#a91509cfc9da285731d483b1373c8584d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dec660c088023646b612c8aafc8966d">maybeResetToLoadedStage</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset compile units <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data(results of liveness analysis, clonning)</a> if current stage greater than <a href="#ac8f9de0c8d86b73c76368b681f0d7883a7381d487d18845b379422325c0a768d6">Stage::Loaded</a>. <a href="#a0dec660c088023646b612c8aafc8966d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a188e713b7044fc7477fa27c6f4efc662">analyzeImportedModule</a> (const DWARFDebugInfoEntry *DieEntry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect references to parseable Swift interfaces in imported DW_TAG_module blocks. <a href="#a188e713b7044fc7477fa27c6f4efc662">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63c52ca4471973f37308391bf9f5979e">analyzeDWARFStructure</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Navigate DWARF tree and set die properties. <a href="#a63c52ca4471973f37308391bf9f5979e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c8b9ba6422c57fd4edb9b5771b650d2">cleanupDataAfterClonning</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cleanup unneeded resources after compile unit is cloned. <a href="#a2c8b9ba6422c57fd4edb9b5771b650d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a717bca8e9eb21f64804ccf91908b2a49">updateDieRefPatchesWithClonedOffsets</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>After cloning stage the output DIEs offsets are deallocated. <a href="#a717bca8e9eb21f64804ccf91908b2a49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a827af09c394cd2cd8c71df05f65da2f4">resolveDependenciesAndMarkLiveness</a> (bool InterCUProcessingStarted, std::atomic&lt; bool &gt; &amp;HasNewInterconnectedCUs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for subprograms and variables referencing live code and discover dependend DIEs. <a href="#a827af09c394cd2cd8c71df05f65da2f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a901651fe587e9bf703e9a8adfcaa69cc">updateDependenciesCompleteness</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> dependend DIEs for incompatible placement. <a href="#a901651fe587e9bf703e9a8adfcaa69cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4e94a48345ff3b6df8fd5314d7bb885">verifyDependencies</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> DIEs to have a consistent marking(keep marking, placement marking). <a href="#ac4e94a48345ff3b6df8fd5314d7bb885">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ce07f2980494b70fbc5b5c8b7eac63a">assignTypeNames</a> (TypePool &amp;TypePoolRef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for type entries and assign names. <a href="#a2ce07f2980494b70fbc5b5c8b7eac63a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7aa5d85abec1dae3d16c35aeb187f73">getLowPc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns value of DW_AT_low_pc attribute. <a href="#ad7aa5d85abec1dae3d16c35aeb187f73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37be30a567171554abea498fb8dfb95f">getHighPc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns value of DW_AT_high_pc attribute. <a href="#a37be30a567171554abea498fb8dfb95f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a846300ab5a2ddde3e437f0a85d180dc8">hasLabelAt</a> (uint64_t Addr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if there is a label corresponding to the specified <span class="doxyComputerOutput">Addr</span>. <a href="#a846300ab5a2ddde3e437f0a85d180dc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03dd05be765df5bb4d0fa5af9d4ec76c">addLabelLowPc</a> (uint64_t LabelLowPc, int64_t PcOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the low_pc of a label that is relocated by applying offset <span class="doxyComputerOutput">PCOffset</span>. <a href="#a03dd05be765df5bb4d0fa5af9d4ec76c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae40361c138fe76519f53bc8366a281c7">resolveDIEReference</a> (const DWARFFormValue &amp;RefValue, ResolveInterCUReferencesMode CanResolveInterCUReferences)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resolve the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> attribute reference that has been extracted in <span class="doxyComputerOutput">RefValue</span>. <a href="#ae40361c138fe76519f53bc8366a281c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4cfe0d2715277bd9e110855ed46c66a">resolveDIEReference</a> (const DWARFDebugInfoEntry *DieEntry, dwarf::Attribute Attr, ResolveInterCUReferencesMode CanResolveInterCUReferences)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10c75cc83101598940d8c2cc8daa8858">addFunctionRange</a> (uint64_t LowPC, uint64_t HighPC, int64_t PCOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a function range [<span class="doxyComputerOutput">LowPC</span>, <span class="doxyComputerOutput">HighPC</span>) that is relocated by applying offset <span class="doxyComputerOutput">PCOffset</span>. <a href="#a10c75cc83101598940d8c2cc8daa8858">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#ae78c275f724455ea9876fb2de879bec6">RangesTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93cea00bbe10a959098b13fdc7bee00f">getFunctionRanges</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns function ranges of this unit. <a href="#a93cea00bbe10a959098b13fdc7bee00f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab33a7e6fdc362895e1b739081c1286ba">cloneAndEmit</a> (std::optional&lt; std::reference_wrapper&lt; const Triple &gt; &gt; TargetTriple, TypeUnit *ArtificialTypeUnit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone and emit this compilation unit. <a href="#ab33a7e6fdc362895e1b739081c1286ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b155dc5f7f9374eb06f7277da633577">cloneAndEmitDebugLocations</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone and emit debug locations(.debug_loc/.debug_loclists). <a href="#a0b155dc5f7f9374eb06f7277da633577">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67e7cb91f1de318011b4ad8f6453fa7a">cloneAndEmitRanges</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone and emit ranges. <a href="#a67e7cb91f1de318011b4ad8f6453fa7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab5e3c8afd376c7fedfcd02a86d31540">cloneAndEmitDebugMacro</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone and emit debug macros(.debug_macinfo/.debug_macro). <a href="#aab5e3c8afd376c7fedfcd02a86d31540">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1df1c26e0a60f062547d6ba537e0021a">cloneDIE</a> (const DWARFDebugInfoEntry *InputDieEntry, TypeEntry *ClonedParentTypeDIE, uint64_t OutOffset, std::optional&lt; int64_t &gt; FuncAddressAdjustment, std::optional&lt; int64_t &gt; VarAddressAdjustment, BumpPtrAllocator &amp;Allocator, TypeUnit *ArtificialTypeUnit)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d779ebf8d97beda3616fa4d7997e355">cloneAndEmitLineTable</a> (const Triple &amp;TargetTriple)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b5afda9f8291e7c2433262c8dc8c167">cloneDieAttrExpression</a> (const DWARFExpression &amp;InputExpression, SmallVectorImpl&lt; uint8_t &gt; &amp;OutputExpression, SectionDescriptor &amp;Section, std::optional&lt; int64_t &gt; VarAddressAdjustment, OffsetsPtrVector &amp;PatchesOffsets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone attribute location axpression. <a href="#a0b5afda9f8291e7c2433262c8dc8c167">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a743f8099b5d1857b748d9be592ab0692">getDebugAddrIndex</a> (uint64_t Addr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns index(inside .debug_addr) of an address. <a href="#a743f8099b5d1857b748d9be592ab0692">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc641b1f4e9cea792161329bdaab4078">getDirAndFilenameFromLineTable</a> (const DWARFFormValue &amp;FileIdxValue)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns directory and file from the line table by index. <a href="#adc641b1f4e9cea792161329bdaab4078">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53949973d752a1d918687b758424714a">getDirAndFilenameFromLineTable</a> (uint64_t FileIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns directory and file from the line table by index. <a href="#a53949973d752a1d918687b758424714a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa24ff91f920a0a4c418dabab4323125e">saveAcceleratorInfo</a> (const DwarfUnit::AccelInfo &amp;Info)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Save specified accelerator info <span class="doxyComputerOutput">Info</span>. <a href="#aa24ff91f920a0a4c418dabab4323125e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfc5e2823133518b807d3e54fff3686b">forEachAcceleratorRecord</a> (function_ref&lt; void(AccelInfo &amp;)&gt; Handler) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerates all units accelerator records. <a href="#acfc5e2823133518b807d3e54fff3686b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DIEInfo &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/group/#ga3cc183d3d4b3e914db2998f157d22e8a">getDIEInfo</a> (unsigned Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">Idx</span> index of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="/web-llvm/docs/api/groups/group/#ga3cc183d3d4b3e914db2998f157d22e8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DIEInfo &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/group/#ga5623acdba9bcde3f32b1d75ff41eff91">getDIEInfo</a> (unsigned Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">Idx</span> index of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="/web-llvm/docs/api/groups/group/#ga5623acdba9bcde3f32b1d75ff41eff91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DIEInfo &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/group/#ga67e10343676779815d39ecb9f3494161">getDIEInfo</a> (const DWARFDebugInfoEntry *Entry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">Idx</span> index of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="/web-llvm/docs/api/groups/group/#ga67e10343676779815d39ecb9f3494161">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DIEInfo &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/group/#ga46715474259d177dfee3f64cb84060b9">getDIEInfo</a> (const DWARFDebugInfoEntry *Entry) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">Idx</span> index of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="/web-llvm/docs/api/groups/group/#ga46715474259d177dfee3f64cb84060b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DIEInfo &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/group/#gaebaf347b4df991192eb43b3f5ec6982d">getDIEInfo</a> (const DWARFDie &amp;Die)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">Die</span> <a href="/web-llvm/docs/api/groups/group/#gaebaf347b4df991192eb43b3f5ec6982d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DIEInfo &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/group/#ga4d4950c415f9a38bf821dc4fac3d1fa3">getDIEInfo</a> (const DWARFDie &amp;Die) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">Die</span> <a href="/web-llvm/docs/api/groups/group/#ga4d4950c415f9a38bf821dc4fac3d1fa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/group/#ga4932257b2b71ddc6fa8da4a0c05ab6a6">getDieOutOffset</a> (uint32_t Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">Idx</span> index of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="/web-llvm/docs/api/groups/group/#ga4932257b2b71ddc6fa8da4a0c05ab6a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">TypeEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/group/#ga29be93ac65e487988de0407cc51f6317">getDieTypeEntry</a> (uint32_t Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">Idx</span> index of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="/web-llvm/docs/api/groups/group/#ga29be93ac65e487988de0407cc51f6317">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/group/#ga24d254de081807f2007f1791d41dbcc2">getDieOutOffset</a> (const DWARFDebugInfoEntry *InputDieEntry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">InputDieEntry</span> debug info entry. <a href="/web-llvm/docs/api/groups/group/#ga24d254de081807f2007f1791d41dbcc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">TypeEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/group/#ga78fda22e9740aea1e9dad0b83f09b667">getDieTypeEntry</a> (const DWARFDebugInfoEntry *InputDieEntry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">InputDieEntry</span> debug info entry. <a href="/web-llvm/docs/api/groups/group/#ga78fda22e9740aea1e9dad0b83f09b667">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/group/#ga284a7f7d31ae4012d2db6fc1cc0791ff">rememberDieOutOffset</a> (uint32_t Idx, uint64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">Idx</span> index of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="/web-llvm/docs/api/groups/group/#ga284a7f7d31ae4012d2db6fc1cc0791ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/group/#gab6d6048b9ba79d8a442e18b7ecc428a6">setDieTypeEntry</a> (uint32_t Idx, TypeEntry *Entry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">Idx</span> index of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="/web-llvm/docs/api/groups/group/#gab6d6048b9ba79d8a442e18b7ecc428a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/group/#gaa4bca7959b19725916051fad326d8ddf">setDieTypeEntry</a> (const DWARFDebugInfoEntry *InputDieEntry, TypeEntry *Entry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">InputDieEntry</span> debug info entry. <a href="/web-llvm/docs/api/groups/group/#gaa4bca7959b19725916051fad326d8ddf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DWARFUnit &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/helper/#ga4a7a4b7dd835a0d0791b13322e3b5679">getOrigUnit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns paired compile unit from input DWARF. <a href="/web-llvm/docs/api/groups/helper/#ga4a7a4b7dd835a0d0791b13322e3b5679">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDebugInfoEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/helper/#ga122417b360a01a5ac081c1c9b4aa971a">getFirstChildEntry</a> (const DWARFDebugInfoEntry *Die) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDebugInfoEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/helper/#ga0b2870f844dabdc24d144e1cd4b95fe0">getSiblingEntry</a> (const DWARFDebugInfoEntry *Die) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">DWARFDie</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/helper/#ga64ac1b3c171031003b392861e7fd8b2d">getParent</a> (const DWARFDebugInfoEntry *Die)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">DWARFDie</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/helper/#ga28d62fd02c932ec4b1e956b615747906">getDIEAtIndex</a> (unsigned Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDebugInfoEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/helper/#ga4793154b7cb56b07edd053ee0f2a34b9">getDebugInfoEntry</a> (unsigned Index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">DWARFDie</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/helper/#ga619b3ce46249265bdc72744dec7e953a">getUnitDIE</a> (bool ExtractUnitDIEOnly=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">DWARFDie</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/helper/#ga344f9eb0eda77b2c26871e2e0b55186a">getDIE</a> (const DWARFDebugInfoEntry *Die)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/helper/#gab537c76e7cadfb09365273a0fae0e896">getDIEIndex</a> (const DWARFDebugInfoEntry *Die) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/helper/#gac74dc3072176bf9eb4fd1f2db6ea9d3d">getDIEIndex</a> (const DWARFDie &amp;Die) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; DWARFFormValue &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/helper/#gaed7fe8d7d740751efb3cd56d309a63e9">find</a> (uint32_t DieIdx, ArrayRef&lt; dwarf::Attribute &gt; Attrs) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; DWARFFormValue &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/helper/#ga36cc8fce6194aa7a20ae36da44795e70">find</a> (const DWARFDebugInfoEntry *Die, ArrayRef&lt; dwarf::Attribute &gt; Attrs) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/helper/#ga15d48891883ccbfff9602a3c00b2f326">getDIEIndexForOffset</a> (uint64_t Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga8b2f2eefb63daf2e6f322e1e90228a2e">warn</a> (const Twine &amp;Warning, const DWARFDie *DIE=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga654eee00b3eed07a03d37b22391d18e2">warn</a> (Error Warning, const DWARFDie *DIE=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#gae294385bb587a12499b98215ae8e7745">warn</a> (const Twine &amp;Warning, const DWARFDebugInfoEntry *DieEntry)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#gab0417bf315aa0a768f1a33d55209135a">error</a> (const Twine &amp;Err, const DWARFDie *DIE=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga067b49dc851a8db06344fa2b594cb6bb">error</a> (Error Err, const DWARFDie *DIE=nullptr)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a876793bbbbcff8bb613e7845c1ab6c38">analyzeDWARFStructureRec</a> (const DWARFDebugInfoEntry *DieEntry, bool IsODRUnavailableFunctionScope)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Navigate DWARF tree recursively and set die properties. <a href="#a876793bbbbcff8bb613e7845c1ab6c38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf42c12f24bc06643f5cb48e93a54107">emitLocations</a> (DebugSectionKind LocationSectionKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit debug locations. <a href="#adf42c12f24bc06643f5cb48e93a54107">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab01c1b7bbb4585b1b18beb7ed13f7b54">emitLocListHeader</a> (SectionDescriptor &amp;OutLocationSection)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit location list header. <a href="#ab01c1b7bbb4585b1b18beb7ed13f7b54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafdbe7a0fa3d6292a64288052f7fdea2">emitLocListFragment</a> (const LinkedLocationExpressionsVector &amp;LinkedLocationExpression, SectionDescriptor &amp;OutLocationSection)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit location list fragment. <a href="#aafdbe7a0fa3d6292a64288052f7fdea2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2270ac65fe1c874f700d49b406ee8715">emitDebugAddrSection</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the .debug_addr section fragment for current unit. <a href="#a2270ac65fe1c874f700d49b406ee8715">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a548a5e71417cb3d21bd6b09b3e27eafe">emitAranges</a> (AddressRanges &amp;LinkedFunctionRanges)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit .debug_aranges. <a href="#a548a5e71417cb3d21bd6b09b3e27eafe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1695911f6e1b843def20a603bb3e001">cloneAndEmitRangeList</a> (DebugSectionKind RngSectionKind, AddressRanges &amp;LinkedFunctionRanges)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone and emit .debug_ranges/.debug_rnglists. <a href="#ae1695911f6e1b843def20a603bb3e001">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4690179231178168f3a618cef957933f">emitRangeListHeader</a> (SectionDescriptor &amp;OutRangeSection)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit range list header. <a href="#a4690179231178168f3a618cef957933f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8b5fba5f51fba9b90233cee0fc4d1c6">emitRangeListFragment</a> (const AddressRanges &amp;LinkedRanges, SectionDescriptor &amp;OutRangeSection)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit range list fragment. <a href="#aa8b5fba5f51fba9b90233cee0fc4d1c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeac84789b641ea69ee6a673f2608fd50">insertLineSequence</a> (std::vector&lt; DWARFDebugLine::Row &gt; &amp;Seq, std::vector&lt; DWARFDebugLine::Row &gt; &amp;Rows)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert the new line info sequence <span class="doxyComputerOutput">Seq</span> into the current set of already linked line info <span class="doxyComputerOutput">Rows</span>. <a href="#aeac84789b641ea69ee6a673f2608fd50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c3a091a8bbfad0d558dc8a20151afb7">emitMacroTableImpl</a> (const DWARFDebugMacro *MacroTable, uint64_t OffsetToMacroTable, bool hasDWARFv5Header)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits body for both macro sections. <a href="#a1c3a091a8bbfad0d558dc8a20151afb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f4e9895019956409162a47cfd659e96">createPlainDIEandCloneAttributes</a> (const DWARFDebugInfoEntry *InputDieEntry, DIEGenerator &amp;PlainDIEGenerator, uint64_t &amp;OutOffset, std::optional&lt; int64_t &gt; &amp;FuncAddressAdjustment, std::optional&lt; int64_t &gt; &amp;VarAddressAdjustment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> which would be placed into the "Plain" compile unit. <a href="#a4f4e9895019956409162a47cfd659e96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a192bf75da45878bc24b4c407a79d15c2">createTypeDIEandCloneAttributes</a> (const DWARFDebugInfoEntry *InputDieEntry, DIEGenerator &amp;TypeDIEGenerator, TypeEntry *ClonedParentTypeDIE, TypeUnit *ArtificialTypeUnit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> which would be placed into the "Type" compile unit. <a href="#a192bf75da45878bc24b4c407a79d15c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab04377f40c96367a39a6702f9f401be9">allocateTypeDie</a> (TypeEntryBody *TypeDescriptor, DIEGenerator &amp;TypeDIEGenerator, dwarf::Tag DieTag, bool IsDeclaration, bool IsParentDeclaration)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create output <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> inside specified <span class="doxyComputerOutput">TypeDescriptor</span>. <a href="#ab04377f40c96367a39a6702f9f401be9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51d1c66b3728c1f307115f90c44c7019">assignTypeNamesRec</a> (const DWARFDebugInfoEntry *DieEntry, SyntheticTypeNameBuilder &amp;NameBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerate <span class="doxyComputerOutput">DieEntry</span> children and assign names for them. <a href="#a51d1c66b3728c1f307115f90c44c7019">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01563c81f25d3c695c564916e8ea7dcd">File</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> containing this compile unit. <a href="#a01563c81f25d3c695c564916e8ea7dcd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ecb2f08bf8ea63222b196475204a315">OrigUnit</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to the paired compile unit from the input DWARF. <a href="#a6ecb2f08bf8ea63222b196475204a315">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90ba5f0fdf87513d9ce2f4256b55cd6f">Language</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The DW_AT_language of this unit. <a href="#a90ba5f0fdf87513d9ce2f4256b55cd6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable">DWARFDebugLine::LineTable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f4b23c7b12e77b72ec9b486d1de86a8">LineTablePtr</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Line table for this unit. <a href="#a0f4b23c7b12e77b72ec9b486d1de86a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">ResolvedPathsMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4701197d681a7a6803f90d480f9d378">ResolvedFullPaths</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a580627f8d539adea83d927b0110467">ResolvedParentPaths</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/indexedvaluesmap">IndexedValuesMap</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9a892f039ff90244f9c0d8ee6483cd6">DebugAddrIndexMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps an address into the index inside .debug_addr section. <a href="#aa9a892f039ff90244f9c0d8ee6483cd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker">DependencyTracker</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ee4438eed1c236ee20b9dbb22cebd6d">Dependencies</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">OffsetToUnitTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#gafd7049ce2cb017276874f4c5595f46fb">getUnitFromOffset</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#ga5c7d9bd15a383062b8e5f75fcf5ae73c">LowPc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#ga9e0f022270d5a3e44af431e3af34652d">HighPc</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#gab86edd0c48eb5725a308acd67eeae7cf">NoODR</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag indicating whether type de-duplication is forbidden. <a href="/web-llvm/docs/api/groups/data/#gab86edd0c48eb5725a308acd67eeae7cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">RangesTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#ga0ec587307301af081bfa7b7c47ad6de4">Ranges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The ranges in that map are the PC ranges for functions in this unit, associated with the PC offset to apply to the addresses to get the linked address. <a href="/web-llvm/docs/api/groups/data/#ga0ec587307301af081bfa7b7c47ad6de4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#ga4310ce7e9818832db0adcc6862f37c9c">RangesMutex</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#ga1ea6532dfecf3eda51636f70c3724d58">Labels</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#ga2dba5eeef4a0da36a58dc97909718698">LabelsMutex</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#ga008ed8a31c6ce1601777f59877fcd33d">Stage</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This field keeps current stage of overall compile unit processing. <a href="/web-llvm/docs/api/groups/data/#ga008ed8a31c6ce1601777f59877fcd33d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">SmallVector&lt; DIEInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#ga093fd13ae55a992a25c458daaee9cde4">DieInfoArray</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> info indexed by <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> index. <a href="/web-llvm/docs/api/groups/data/#ga093fd13ae55a992a25c458daaee9cde4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">SmallVector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#gadc3acd80975890a2c0c55c46113bbcb5">OutDieOffsetArray</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#gabceb5168d49eea87e71da5324da808d6">TypeEntries</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#ga1a53358aaff0b57bd173c8aebee12297">AcceleratorRecords</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list of accelerator records for this unit. <a href="/web-llvm/docs/api/groups/data/#ga1a53358aaff0b57bd173c8aebee12297">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Stores all information related to a compile unit, be it in its original instance of the object file or its brand new cloned and generated <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree.</p>


<p>NOTE: we need alignment of at least 8 bytes as we use <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair&lt;CompileUnit *, 3&gt;</a> in the <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a></p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### LinkedLocationExpressionsVector {#af89f4b5ceca35d58f59a02da07369e88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::parallel::CompileUnit::LinkedLocationExpressionsVector = 
      SmallVector&lt;LinkedLocationExpressionsWithOffsetPatches&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### ResolvedPathsMap {#a8ec1f214175af88c2caf6f22de734234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::parallel::CompileUnit::ResolvedPathsMap =  DenseMap&lt;unsigned, StringEntry *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cached resolved paths from the line table.</p>


<p>The key is &lt;UniqueUnitID, FileIdx&gt;.</p>


<p>Definition at line 685 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### DieOutputPlacement {#a5270021419d157f502aba678e1ee8549}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::dwarf_linker::parallel::CompileUnit::DieOutputPlacement : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Kinds of placement for the output die.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NotSet<a id="a5270021419d157f502aba678e1ee8549ae9311639cca717631f1dc39e18b1f62d"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TypeTable<a id="a5270021419d157f502aba678e1ee8549ae4e2eb6616a94c80f428778e4b1bb3bf"></a></td>
<td class="doxyEnumItemDescription">Corresponding <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> goes to the type table only (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PlainDwarf<a id="a5270021419d157f502aba678e1ee8549aecc6950928c245961306947efbae3db7"></a></td>
<td class="doxyEnumItemDescription">Corresponding <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> goes to the plain dwarf only (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Both<a id="a5270021419d157f502aba678e1ee8549a5d59de2bbf0cc536bfb1d56049d26d68"></a></td>
<td class="doxyEnumItemDescription">Corresponding <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> goes to type table and to plain dwarf (= 3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### Stage {#ac8f9de0c8d86b73c76368b681f0d7883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::dwarf_linker::parallel::CompileUnit::Stage : uint8_t</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The stages of new compile unit processing.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CreatedNotLoaded<a id="ac8f9de0c8d86b73c76368b681f0d7883a44f476a85bed95ceb67cabb6d0de35b7"></a></td>
<td class="doxyEnumItemDescription">Created, linked with input DWARF file (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Loaded<a id="ac8f9de0c8d86b73c76368b681f0d7883a7381d487d18845b379422325c0a768d6"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/input">Input</a> DWARF is loaded</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LivenessAnalysisDone<a id="ac8f9de0c8d86b73c76368b681f0d7883aa1af45d7ba3138a16acdede1e85ede84"></a></td>
<td class="doxyEnumItemDescription">
<a href="/web-llvm/docs/api/classes/input">Input</a> DWARF is analysed(DIEs pointing to the real code section are
discovered, type names are assigned if ODR is requested)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UpdateDependenciesCompleteness<a id="ac8f9de0c8d86b73c76368b681f0d7883ad0387a23f6c7310e7543f802cff3bce0"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if dependencies have incompatible placement</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TypeNamesAssigned<a id="ac8f9de0c8d86b73c76368b681f0d7883a2872e735c9749db6fa8336d07e11389e"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> names assigned to DIEs</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Cloned<a id="ac8f9de0c8d86b73c76368b681f0d7883a19a35ef9463a94f30004fac9ddb0fd52"></a></td>
<td class="doxyEnumItemDescription">Output DWARF is generated</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PatchesUpdated<a id="ac8f9de0c8d86b73c76368b681f0d7883a4e1541154b3fa09fc872add2c3993a62"></a></td>
<td class="doxyEnumItemDescription">Offsets inside patch records are updated</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Cleaned<a id="ac8f9de0c8d86b73c76368b681f0d7883a71fb656255391c5f521e5742aaad23dd"></a></td>
<td class="doxyEnumItemDescription">Resources(Input DWARF, Output DWARF tree) are released</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Skipped<a id="ac8f9de0c8d86b73c76368b681f0d7883ad9c8f187972e6320a34e9c40b4cba605"></a></td>
<td class="doxyEnumItemDescription">Compile Unit should be skipped</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CompileUnit() {#abe722b66707f8b5e4aaa19a24810480f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileUnit::CompileUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/linkingglobaldata">LinkingGlobalData</a> &amp; GlobalData, unsigned ID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ClangModuleName, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#a3275ccba37c06dcc20e0296954f614c7">OffsetToUnitTy</a> UnitFromOffset, <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">dwarf::FormParams</a> Format, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> Endianess)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ad6bdec0518399f994bc436daa5ad27a3">llvm::dwarf_linker::parallel::DwarfUnit::ClangModuleName</a>, <a href="#ac8f9de0c8d86b73c76368b681f0d7883a44f476a85bed95ceb67cabb6d0de35b7">CreatedNotLoaded</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24af6f6931771db95a6bffec131b856bd50">llvm::dwarf_linker::DebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ad367b733292adfe15b6d45c5fc4db8b2">llvm::dwarf_linker::parallel::DwarfUnit::DwarfUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a1766b7f5152f1dfe8b9498df8314a356">llvm::dwarf_linker::parallel::OutputSections::Format</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#ab6597212694001f13f816944c69bb0b2">llvm::dwarf_linker::parallel::OutputSections::getOrCreateSectionDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ab4bc76d8c13939bdfdaf0b96aa1d4f82">llvm::dwarf_linker::parallel::DwarfUnit::ID</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a6d003066059ba2b698ace39edf39e2cf">llvm::dwarf_linker::parallel::OutputSections::setOutputFormat</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#a2c338a607208f34a94cce92277176e35">llvm::dwarf_linker::parallel::DwarfUnit::UnitName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/outputunitvariantptr/#a9317eea533090c4df7295701b018f688">llvm::dwarf_linker::parallel::CompileUnit::OutputUnitVariantPtr::getAsCompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/outputunitvariantptr/#ac188afa7fcf9d7d05f2ceca0082b45eb">llvm::dwarf_linker::parallel::CompileUnit::OutputUnitVariantPtr::OutputUnitVariantPtr</a> and <a href="#ae40361c138fe76519f53bc8366a281c7">resolveDIEReference</a>.</p>

</div>
</div>

### CompileUnit() {#a26a4de20c065ba21d3af3b8f2fc2bb50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileUnit::CompileUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/linkingglobaldata">LinkingGlobalData</a> &amp; GlobalData, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> &amp; OrigUnit, unsigned ID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ClangModuleName, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#a3275ccba37c06dcc20e0296954f614c7">OffsetToUnitTy</a> UnitFromOffset, <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">dwarf::FormParams</a> Format, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> Endianess)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ad6bdec0518399f994bc436daa5ad27a3">llvm::dwarf_linker::parallel::DwarfUnit::ClangModuleName</a>, <a href="#ac8f9de0c8d86b73c76368b681f0d7883a44f476a85bed95ceb67cabb6d0de35b7">CreatedNotLoaded</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24af6f6931771db95a6bffec131b856bd50">llvm::dwarf_linker::DebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ad367b733292adfe15b6d45c5fc4db8b2">llvm::dwarf_linker::parallel::DwarfUnit::DwarfUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a315f90678bfa85d85d71a9dd12d5457a">llvm::DWARFDie::find</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a1766b7f5152f1dfe8b9498df8314a356">llvm::dwarf_linker::parallel::OutputSections::Format</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a834590fd64e02e844dd117b380ab819b">llvm::DWARFDie::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#ab6597212694001f13f816944c69bb0b2">llvm::dwarf_linker::parallel::OutputSections::getOrCreateSectionDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ab4bc76d8c13939bdfdaf0b96aa1d4f82">llvm::dwarf_linker::parallel::DwarfUnit::ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#a1780893d4361a1d80fbc26a6e38ded70">llvm::dwarf_linker::parallel::isODRLanguage</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a6d003066059ba2b698ace39edf39e2cf">llvm::dwarf_linker::parallel::OutputSections::setOutputFormat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870ad26b007baa81cc3cd38d8d6c93e6df42">llvm::ShortName</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#a6405b4fe980c4bdbffe7fd3732d74c18">llvm::dwarf_linker::parallel::DwarfUnit::SysRoot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa10731e4d6c303386a70337b0e0668d0">llvm::dwarf::toStringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ae150cb3561ce0a2979ed60d29301eef7">llvm::dwarf::toUnsigned</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#a2c338a607208f34a94cce92277176e35">llvm::dwarf_linker::parallel::DwarfUnit::UnitName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addFunctionRange() {#a10c75cc83101598940d8c2cc8daa8858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::CompileUnit::addFunctionRange (uint64_t LowPC, uint64_t HighPC, int64_t PCOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a function range [<span class="doxyComputerOutput">LowPC</span>, <span class="doxyComputerOutput">HighPC</span>) that is relocated by applying offset <span class="doxyComputerOutput">PCOffset</span>.</p>

<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### addLabelLowPc() {#a03dd05be765df5bb4d0fa5af9d4ec76c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::CompileUnit::addLabelLowPc (uint64_t LabelLowPc, int64_t PcOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the low_pc of a label that is relocated by applying offset <span class="doxyComputerOutput">PCOffset</span>.</p>

<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### analyzeDWARFStructure() {#a63c52ca4471973f37308391bf9f5979e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::CompileUnit::analyzeDWARFStructure ()</td>
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

<p>Navigate DWARF tree and set die properties.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/helper/#ga4793154b7cb56b07edd053ee0f2a34b9">getDebugInfoEntry</a> and <a href="/web-llvm/docs/api/groups/helper/#ga619b3ce46249265bdc72744dec7e953a">getUnitDIE</a>.</p>

</div>
</div>

### analyzeImportedModule() {#a188e713b7044fc7477fa27c6f4efc662}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CompileUnit::analyzeImportedModule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * DieEntry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect references to parseable Swift interfaces in imported DW_TAG_module blocks.</p>

<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/groups/helper/#gaed7fe8d7d740751efb3cd56d309a63e9">find</a>, <a href="/web-llvm/docs/api/groups/helper/#ga344f9eb0eda77b2c26871e2e0b55186a">getDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#afb30d50b24260ae45f84319d1d1825ea">llvm::dwarf_linker::parallel::DwarfUnit::getSysRoot</a>, <a href="/web-llvm/docs/api/groups/helper/#ga619b3ce46249265bdc72744dec7e953a">getUnitDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0e06d133446b7cfbee6b1800f3d993f7">llvm::dwarf_linker::guessDeveloperDir</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a59d172f36ecf079548e9c539ae54e5a4">llvm::sys::path::is_relative</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a85aa80526a5484cfab745ec2440b1a9e">llvm::dwarf_linker::isInToolchainDir</a>, <a href="/web-llvm/docs/api/groups/methods/#gga2c708209e1c0939d50f9e70bc5708491a49ee3087348e8d44e1feda1917443987">llvm::dwarf_linker::parallel::DwarfUnit::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#a6405b4fe980c4bdbffe7fd3732d74c18">llvm::dwarf_linker::parallel::DwarfUnit::SysRoot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a39a67e6dc97585d609932dc2fb04a377">llvm::dwarf::toString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa10731e4d6c303386a70337b0e0668d0">llvm::dwarf::toStringRef</a> and <a href="/web-llvm/docs/api/groups/methods/#ga8b2f2eefb63daf2e6f322e1e90228a2e">warn</a>.</p>

</div>
</div>

### assignTypeNames() {#a2ce07f2980494b70fbc5b5c8b7eac63a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CompileUnit::assignTypeNames (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typepool">TypePool</a> &amp; TypePoolRef)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Search for type entries and assign names.</p>

<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/helper/#ga4793154b7cb56b07edd053ee0f2a34b9">getDebugInfoEntry</a>, <a href="/web-llvm/docs/api/groups/helper/#ga619b3ce46249265bdc72744dec7e953a">getUnitDIE</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### cleanupDataAfterClonning() {#a2c8b9ba6422c57fd4edb9b5771b650d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CompileUnit::cleanupDataAfterClonning ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cleanup unneeded resources after compile unit is cloned.</p>

<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#aed631a14c4d5d968368454041e3d9413">llvm::dwarf_linker::parallel::DwarfUnit::AbbreviationsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a59ceaf24fba4056aa49e73e33b6a121c">llvm::DWARFUnit::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#a16cbefbd2f62758e696d04e82fc6fd1a">llvm::dwarf_linker::parallel::DwarfUnit::FileNames</a>, <a href="/web-llvm/docs/api/groups/helper/#ga4a7a4b7dd835a0d0791b13322e3b5679">getOrigUnit</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8fc529c79977cdd01e187986f960a07f">llvm::SmallVector</a>.</p>

</div>
</div>

### cloneAndEmit() {#ab33a7e6fdc362895e1b739081c1286ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CompileUnit::cloneAndEmit (std::optional&lt; std::reference_wrapper&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &gt; &gt; TargetTriple, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit">TypeUnit</a> * ArtificialTypeUnit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone and emit this compilation unit.</p>

<p>Declaration at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1231 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="#a0b155dc5f7f9374eb06f7277da633577">cloneAndEmitDebugLocations</a>, <a href="#aab5e3c8afd376c7fedfcd02a86d31540">cloneAndEmitDebugMacro</a>, <a href="#a5d779ebf8d97beda3616fa4d7997e355">cloneAndEmitLineTable</a>, <a href="#a67e7cb91f1de318011b4ad8f6453fa7a">cloneAndEmitRanges</a>, <a href="#a1df1c26e0a60f062547d6ba537e0021a">cloneDIE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24af6f6931771db95a6bffec131b856bd50">llvm::dwarf_linker::DebugInfo</a>, <a href="/web-llvm/docs/api/groups/methods/#ga9b4dbcbc740191455c092e2edd8afa51">llvm::dwarf_linker::parallel::DwarfUnit::emitAbbreviations</a>, <a href="/web-llvm/docs/api/groups/methods/#ga4353067d272bae6ec1a934e5ea39f924">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugInfo</a>, <a href="/web-llvm/docs/api/groups/methods/#ga579ac60d76c4a3b6ca084238591d4437">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugStringOffsetSection</a>, <a href="/web-llvm/docs/api/groups/methods/#ga80d3884d82a541f6f1b11931db9fc5fb">llvm::dwarf_linker::parallel::DwarfUnit::emitPubAccelerators</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a41fc5e2ca3d059c98029728b2677be44">llvm::DWARFDie::getDebugInfoEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a7e3b66f8d958f065300cf5ddda43f715">llvm::dwarf_linker::parallel::OutputSections::getDebugInfoHeaderSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#ab6597212694001f13f816944c69bb0b2">llvm::dwarf_linker::parallel::OutputSections::getOrCreateSectionDescriptor</a>, <a href="/web-llvm/docs/api/groups/helper/#ga4a7a4b7dd835a0d0791b13322e3b5679">getOrigUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typepool/#ac7c866021042c7a61e07bb8278865dad">llvm::dwarf_linker::parallel::TypePool::getRoot</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#a2b81039b4916fdc6acfd00effec90b7b">llvm::dwarf_linker::parallel::TypeUnit::getTypePool</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b5f2734488f7b1b52e982683675df24">llvm::DWARFUnit::getUnitDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#ae970d60ab52d996448bb030b4a0b67bc">llvm::DWARFDie::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a78ca7920cd1aaf69f7da553285c55308aa29bdd003ef6c0c34279807341f450f2">llvm::dwarf_linker::DWARFLinkerBase::Pub</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ad24c182dd9def83d9d63a6cce49331c0">llvm::dwarf_linker::parallel::DwarfUnit::setOutUnitDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### cloneAndEmitDebugLocations() {#a0b155dc5f7f9374eb06f7277da633577}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CompileUnit::cloneAndEmitDebugLocations ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone and emit debug locations(.debug_loc/.debug_loclists).</p>

<p>Declaration at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a0b4ec7dfa0beee39e0d09a0cf5c09f54">llvm::dwarf_linker::DebugLocLists</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#a461c26c602014baed9de7d2c019f4f8a">llvm::dwarf_linker::parallel::DwarfUnit::getGlobalData</a>, <a href="/web-llvm/docs/api/groups/helper/#ga4a7a4b7dd835a0d0791b13322e3b5679">getOrigUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a72e4600f7a22981307da5b2a2b5acb68">llvm::dwarf_linker::parallel::OutputSections::getVersion</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#ab33a7e6fdc362895e1b739081c1286ba">cloneAndEmit</a>.</p>

</div>
</div>

### cloneAndEmitDebugMacro() {#aab5e3c8afd376c7fedfcd02a86d31540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CompileUnit::cloneAndEmitDebugMacro ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone and emit debug macros(.debug_macinfo/.debug_macro).</p>

<p>Declaration at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 894 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7af5fd6eac5e3429291e19a0bc6fd51fabc5183644c3cfe8d28e144b1518446d9">llvm::Dwarf</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a315f90678bfa85d85d71a9dd12d5457a">llvm::DWARFDie::find</a>, <a href="/web-llvm/docs/api/groups/helper/#ga4a7a4b7dd835a0d0791b13322e3b5679">getOrigUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#afbcc691dc3aee7912fd0e6f49fb1bb8a">llvm::dwarf_linker::parallel::DwarfUnit::getOutUnitDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a966c7097853fffeaf2746f5d58861f36">llvm::dwarf::toSectionOffset</a>.</p>


<p>Referenced by <a href="#ab33a7e6fdc362895e1b739081c1286ba">cloneAndEmit</a>.</p>

</div>
</div>

### cloneAndEmitLineTable() {#a5d779ebf8d97beda3616fa4d7997e355}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CompileUnit::cloneAndEmitLineTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TargetTriple)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1516 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams/#a6892519cfb3ec739ebd611d7bd82ea2e">llvm::dwarf::FormParams::AddrSize</a>, <a href="/web-llvm/docs/api/groups/methods/#gaf5ad0e93c4f3b97d0e8d192675945746">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugLine</a>, <a href="/web-llvm/docs/api/groups/helper/#gaed7fe8d7d740751efb3cd56d309a63e9">find</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue/#ad1a98ac8bd44a05c862c20b5963957d4">llvm::DWARFDebugLine::Prologue::FormParams</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a33ecefa9aec7bce5d08e92138ae1be08">llvm::dwarf_linker::parallel::OutputSections::getFormParams</a>, <a href="#a93cea00bbe10a959098b13fdc7bee00f">getFunctionRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#a461c26c602014baed9de7d2c019f4f8a">llvm::dwarf_linker::parallel::DwarfUnit::getGlobalData</a>, <a href="/web-llvm/docs/api/groups/helper/#ga4a7a4b7dd835a0d0791b13322e3b5679">getOrigUnit</a>, <a href="/web-llvm/docs/api/groups/helper/#ga619b3ce46249265bdc72744dec7e953a">getUnitDIE</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#aec306fc919df207db6e700f491872d71">llvm::DWARFDebugLine::LineTable::Prologue</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a08f2df6a1aaacec42c6ded0585a11e4d">llvm::DWARFDebugLine::LineTable::Rows</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#ada29eb4559f13bb34130942122c76ec7">llvm::DWARFDebugLine::LineTable::Sequences</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/groups/methods/#ga8b2f2eefb63daf2e6f322e1e90228a2e">warn</a>.</p>


<p>Referenced by <a href="#ab33a7e6fdc362895e1b739081c1286ba">cloneAndEmit</a>.</p>

</div>
</div>

### cloneAndEmitRanges() {#a67e7cb91f1de318011b4ad8f6453fa7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CompileUnit::cloneAndEmitRanges ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone and emit ranges.</p>

<p>Declaration at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 674 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a558f46094c3e1ffac3dba6928d34c2b9">llvm::dwarf_linker::DebugRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ab09a90abca61cf08407bb116fdc3b75d">llvm::dwarf_linker::DebugRngLists</a>, <a href="#a93cea00bbe10a959098b13fdc7bee00f">getFunctionRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#a461c26c602014baed9de7d2c019f4f8a">llvm::dwarf_linker::parallel::DwarfUnit::getGlobalData</a>, <a href="/web-llvm/docs/api/groups/helper/#ga4a7a4b7dd835a0d0791b13322e3b5679">getOrigUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a72e4600f7a22981307da5b2a2b5acb68">llvm::dwarf_linker::parallel::OutputSections::getVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/addressranges/#a8762c3c9799f1cf6d3ee0b86f0ceea5d">llvm::AddressRanges::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#ab33a7e6fdc362895e1b739081c1286ba">cloneAndEmit</a>.</p>

</div>
</div>

### cloneDIE() {#a1df1c26e0a60f062547d6ba537e0021a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; DIE *, TypeEntry * &gt; CompileUnit::cloneDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * InputDieEntry, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> * ClonedParentTypeDIE, uint64_t OutOffset, std::optional&lt; int64_t &gt; FuncAddressAdjustment, std::optional&lt; int64_t &gt; VarAddressAdjustment, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit">TypeUnit</a> * ArtificialTypeUnit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1287 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/diegenerator/#a18ef43d7a80b7abfe19ae9d6aae351e3">llvm::dwarf_linker::parallel::DIEGenerator::addChild</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1df1c26e0a60f062547d6ba537e0021a">cloneDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#af1912d641eadda862e32bbb231a13e50">llvm::DWARFDebugInfoEntry::getAbbreviationDeclarationPtr</a>, <a href="/web-llvm/docs/api/groups/helper/#gab537c76e7cadfb09365273a0fae0e896">getDIEIndex</a>, <a href="/web-llvm/docs/api/groups/group/#ga3cc183d3d4b3e914db2998f157d22e8a">getDIEInfo</a>, <a href="/web-llvm/docs/api/groups/helper/#ga122417b360a01a5ac081c1c9b4aa971a">getFirstChildEntry</a>, <a href="/web-llvm/docs/api/groups/helper/#ga0b2870f844dabdc24d144e1cd4b95fe0">getSiblingEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#a53e2261d44de5b8447cfa73b482c647f">llvm::DWARFDebugInfoEntry::getTag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typepool/#a276eec77bd8816b367fb396d8a1962ca">llvm::dwarf_linker::parallel::TypePool::getThreadLocalAllocator</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#a2b81039b4916fdc6acfd00effec90b7b">llvm::dwarf_linker::parallel::TypeUnit::getTypePool</a>.</p>


<p>Referenced by <a href="#ab33a7e6fdc362895e1b739081c1286ba">cloneAndEmit</a> and <a href="#a1df1c26e0a60f062547d6ba537e0021a">cloneDIE</a>.</p>

</div>
</div>

### cloneDieAttrExpression() {#a0b5afda9f8291e7c2433262c8dc8c167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CompileUnit::cloneDieAttrExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression">DWARFExpression</a> &amp; InputExpression, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint8_t &gt; &amp; OutputExpression, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &amp; Section, std::optional&lt; int64_t &gt; VarAddressAdjustment, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ad2dde002b59709a633439269e84fb29c">OffsetsPtrVector</a> &amp; PatchesOffsets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone attribute location axpression.</p>

<p>Declaration at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1093 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a362a8723f1604e41107b4f8c667a6d1e">llvm::DWARFExpression::getData</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams/#a235a5f4eedbfa7b5583ba320309d408f">llvm::dwarf::FormParams::getDwarfOffsetByteSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#ab0df9b23ed5b92045b815ebf04d16070">llvm::dwarf_linker::parallel::OutputSections::getEndianness</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a33ecefa9aec7bce5d08e92138ae1be08">llvm::dwarf_linker::parallel::OutputSections::getFormParams</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#a461c26c602014baed9de7d2c019f4f8a">llvm::dwarf_linker::parallel::DwarfUnit::getGlobalData</a>, <a href="/web-llvm/docs/api/groups/helper/#ga4a7a4b7dd835a0d0791b13322e3b5679">getOrigUnit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dba8e5f3adee38c8fccc13c1f3be0143796">llvm::native</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5d4c961b9b6f1da17df74b4496ecb30e">llvm::StringRef::slice</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ad0e418047a3e04c4fd1fb83325b571ae">llvm::sys::swapByteOrder</a> and <a href="/web-llvm/docs/api/groups/methods/#ga8b2f2eefb63daf2e6f322e1e90228a2e">warn</a>.</p>

</div>
</div>

### forEachAcceleratorRecord() {#acfc5e2823133518b807d3e54fff3686b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::CompileUnit::forEachAcceleratorRecord (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarfunit/accelinfo">AccelInfo</a> &amp;)&gt; Handler)</td>
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

<p>Enumerates all units accelerator records.</p>

<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getDebugAddrIndex() {#a743f8099b5d1857b748d9be592ab0692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::parallel::CompileUnit::getDebugAddrIndex (uint64_t Addr)</td>
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

<p>Returns index(inside .debug_addr) of an address.</p>

<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getDirAndFilenameFromLineTable() {#adc641b1f4e9cea792161329bdaab4078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; StringRef, StringRef &gt; &gt; CompileUnit::getDirAndFilenameFromLineTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; FileIdxValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns directory and file from the line table by index.</p>

<p>Declaration at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1672 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a34b4361a52bbe519104734f746a248f9">llvm::DWARFFormValue::getAsSectionOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a95368a5748aa1df8f1d4a2923585a3d3">llvm::DWARFFormValue::getAsSignedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#acf6d7ec7b1699c2bf60e54e032aae623">llvm::DWARFFormValue::getAsUnsignedConstant</a> and <a href="#adc641b1f4e9cea792161329bdaab4078">getDirAndFilenameFromLineTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a53c9ecdd82532a2231dca73e685f4ae3">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addDieNameFromDeclFileAndDeclLine</a> and <a href="#adc641b1f4e9cea792161329bdaab4078">getDirAndFilenameFromLineTable</a>.</p>

</div>
</div>

### getDirAndFilenameFromLineTable() {#a53949973d752a1d918687b758424714a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; StringRef, StringRef &gt; &gt; CompileUnit::getDirAndFilenameFromLineTable (uint64_t FileIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns directory and file from the line table by index.</p>

<p>Declaration at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1688 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#a16cbefbd2f62758e696d04e82fc6fd1a">llvm::dwarf_linker::parallel::DwarfUnit::FileNames</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a610e091c42196cd8bdddce77b7a407e4">llvm::DWARFUnit::getCompilationDir</a>, <a href="/web-llvm/docs/api/groups/helper/#ga4a7a4b7dd835a0d0791b13322e3b5679">getOrigUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a72e4600f7a22981307da5b2a2b5acb68">llvm::dwarf_linker::parallel::OutputSections::getVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#aba60ebbb0330f9e5e713c887d90a40ea">llvm::dwarf_linker::isPathAbsoluteOnWindowsOrPosix</a>, <a href="/web-llvm/docs/api/groups/methods/#gga2c708209e1c0939d50f9e70bc5708491a49ee3087348e8d44e1feda1917443987">llvm::dwarf_linker::parallel::DwarfUnit::Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">llvm::sys::path::native</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/groups/methods/#ga8b2f2eefb63daf2e6f322e1e90228a2e">warn</a>.</p>

</div>
</div>

### getFunctionRanges() {#a93cea00bbe10a959098b13fdc7bee00f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RangesTy &amp; llvm::dwarf_linker::parallel::CompileUnit::getFunctionRanges ()</td>
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

<p>Returns function ranges of this unit.</p>

<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Referenced by <a href="#a5d779ebf8d97beda3616fa4d7997e355">cloneAndEmitLineTable</a> and <a href="#a67e7cb91f1de318011b4ad8f6453fa7a">cloneAndEmitRanges</a>.</p>

</div>
</div>

### getHighPc() {#a37be30a567171554abea498fb8dfb95f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::parallel::CompileUnit::getHighPc ()</td>
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

<p>Returns value of DW_AT_high_pc attribute.</p>

<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getLowPc() {#ad7aa5d85abec1dae3d16c35aeb187f73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::dwarf_linker::parallel::CompileUnit::getLowPc ()</td>
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

<p>Returns value of DW_AT_low_pc attribute.</p>

<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getStage() {#ab7ae271aeb81750becb81e74a7be7582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Stage llvm::dwarf_linker::parallel::CompileUnit::getStage ()</td>
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

<p>Returns stage of overall processing.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Referenced by <a href="#a0dec660c088023646b612c8aafc8966d">maybeResetToLoadedStage</a> and <a href="#ae40361c138fe76519f53bc8366a281c7">resolveDIEReference</a>.</p>

</div>
</div>

### hasLabelAt() {#a846300ab5a2ddde3e437f0a85d180dc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::CompileUnit::hasLabelAt (uint64_t Addr)</td>
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

<p>Returns true if there is a label corresponding to the specified <span class="doxyComputerOutput">Addr</span>.</p>

<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### loadInputDIEs() {#a91509cfc9da285731d483b1373c8584d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CompileUnit::loadInputDIEs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns name of the file for the <span class="doxyComputerOutput">FileIdx</span> from the unit`s line table.</p>


<p>*/ <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> *getFileName(unsigned FileIdx, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/stringpool">StringPool</a> &amp;GlobalStrings);</p>


<p>/ Returns <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> containing this compile unit. const <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp;getContaingFile() const { return File; }</p>


<p>/** Load DIEs of input compilation unit.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if input DIEs successfully loaded.</p></dd>
</dl>


<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/helper/#ga4a7a4b7dd835a0d0791b13322e3b5679">getOrigUnit</a> and <a href="/web-llvm/docs/api/groups/helper/#ga619b3ce46249265bdc72744dec7e953a">getUnitDIE</a>.</p>

</div>
</div>

### loadLineTable() {#aee0400306419adf13952ab2f6734fc0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CompileUnit::loadLineTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Loads unit line table.</p>

<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/groups/helper/#ga4a7a4b7dd835a0d0791b13322e3b5679">getOrigUnit</a>.</p>

</div>
</div>

### maybeResetToLoadedStage() {#a0dec660c088023646b612c8aafc8966d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CompileUnit::maybeResetToLoadedStage ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reset compile units <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data(results of liveness analysis, clonning)</a> if current stage greater than <a href="#ac8f9de0c8d86b73c76368b681f0d7883a7381d487d18845b379422325c0a768d6">Stage::Loaded</a>.</p>


<p>We need to reset data as we are going to repeat stages.</p>


<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#a4d32c9fbda345136f12dfba14237d2fc">llvm::dwarf_linker::parallel::DwarfUnit::Abbreviations</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#aed631a14c4d5d968368454041e3d9413">llvm::dwarf_linker::parallel::DwarfUnit::AbbreviationsSet</a>, <a href="#ac8f9de0c8d86b73c76368b681f0d7883a19a35ef9463a94f30004fac9ddb0fd52">Cloned</a>, <a href="#ac8f9de0c8d86b73c76368b681f0d7883a44f476a85bed95ceb67cabb6d0de35b7">CreatedNotLoaded</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a400254aefab880eb0cc6b1a7a896b223">llvm::dwarf_linker::parallel::OutputSections::eraseSections</a>, <a href="#ab7ae271aeb81750becb81e74a7be7582">getStage</a>, <a href="#ac8f9de0c8d86b73c76368b681f0d7883a7381d487d18845b379422325c0a768d6">Loaded</a>, <a href="/web-llvm/docs/api/groups/methods/#gga2c708209e1c0939d50f9e70bc5708491a49ee3087348e8d44e1feda1917443987">llvm::dwarf_linker::parallel::DwarfUnit::Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#a5a523c53d66f904a426d8b60e192fb72">llvm::dwarf_linker::parallel::DwarfUnit::OutUnitDIE</a> and <a href="#ab5adb90b6c8a1e87fcc97f66cd70adfc">setStage</a>.</p>

</div>
</div>

### resolveDependenciesAndMarkLiveness() {#a827af09c394cd2cd8c71df05f65da2f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CompileUnit::resolveDependenciesAndMarkLiveness (bool InterCUProcessingStarted, std::atomic&lt; bool &gt; &amp; HasNewInterconnectedCUs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Search for subprograms and variables referencing live code and discover dependend DIEs.</p>


<p>Mark live DIEs, set placement for DIEs.</p>


<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1831 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### resolveDIEReference() {#ae40361c138fe76519f53bc8366a281c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; UnitEntryPairTy &gt; CompileUnit::resolveDIEReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; RefValue, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#afcf78d2889ce6c20ba9de57049ac479f">ResolveInterCUReferencesMode</a> CanResolveInterCUReferences)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Resolve the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> attribute reference that has been extracted in <span class="doxyComputerOutput">RefValue</span>.</p>


<p>The resulting <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> might be in another <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>referenced die and corresponding compilation unit. compilation unit is null if reference could not be resolved.</p></dd>
</dl>


<p>Declaration at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="#ac8f9de0c8d86b73c76368b681f0d7883a19a35ef9463a94f30004fac9ddb0fd52">Cloned</a>, <a href="#abe722b66707f8b5e4aaa19a24810480f">CompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#ab967429b71c38060f3be76c48b359753">llvm::DWARFFormValue::getAsDebugInfoReference</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#aa379ebd24e7782b901ad1110ddd11833">llvm::DWARFFormValue::getAsRelativeReference</a>, <a href="/web-llvm/docs/api/groups/helper/#ga4793154b7cb56b07edd053ee0f2a34b9">getDebugInfoEntry</a>, <a href="/web-llvm/docs/api/groups/helper/#ga15d48891883ccbfff9602a3c00b2f326">getDIEIndexForOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af52bec8bfd6fcde07ecb8d04e495b8a0">llvm::DWARFUnit::getOffset</a>, <a href="#ab7ae271aeb81750becb81e74a7be7582">getStage</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#af0a85f9b35aad5e7d4790835e4ce7515">llvm::DWARFFormValue::getUnit</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a0186dfd0c814155d8e6a9cab1969afdd">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addReferencedODRDies</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#ad961b9c792517de751570e73618293ba">llvm::dwarf_linker::parallel::UnitEntryPairTy::getNamespaceOrigin</a> and <a href="#ae4cfe0d2715277bd9e110855ed46c66a">resolveDIEReference</a>.</p>

</div>
</div>

### resolveDIEReference() {#ae4cfe0d2715277bd9e110855ed46c66a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; UnitEntryPairTy &gt; CompileUnit::resolveDIEReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * DieEntry, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attr, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#afcf78d2889ce6c20ba9de57049ac479f">ResolveInterCUReferencesMode</a> CanResolveInterCUReferences)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/helper/#gaed7fe8d7d740751efb3cd56d309a63e9">find</a> and <a href="#ae40361c138fe76519f53bc8366a281c7">resolveDIEReference</a>.</p>

</div>
</div>

### saveAcceleratorInfo() {#aa24ff91f920a0a4c418dabab4323125e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::CompileUnit::saveAcceleratorInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarfunit/accelinfo">DwarfUnit::AccelInfo</a> &amp; Info)</td>
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

<p>Save specified accelerator info <span class="doxyComputerOutput">Info</span>.</p>

<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>.</p>

</div>
</div>

### setStage() {#ab5adb90b6c8a1e87fcc97f66cd70adfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::CompileUnit::setStage (<a href="#ac8f9de0c8d86b73c76368b681f0d7883">Stage</a> Stage)</td>
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

<p>Set stage of overall processing.</p>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Referenced by <a href="#a0dec660c088023646b612c8aafc8966d">maybeResetToLoadedStage</a>.</p>

</div>
</div>

### updateDependenciesCompleteness() {#a901651fe587e9bf703e9a8adfcaa69cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CompileUnit::updateDependenciesCompleteness ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> dependend DIEs for incompatible placement.</p>


<p>Make placement to be consistent.</p>


<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1840 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### updateDieRefPatchesWithClonedOffsets() {#a717bca8e9eb21f64804ccf91908b2a49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CompileUnit::updateDieRefPatchesWithClonedOffsets ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>After cloning stage the output DIEs offsets are deallocated.</p>


<p>This method copies output offsets for referenced DIEs into DIEs patches.</p>


<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24af6f6931771db95a6bffec131b856bd50">llvm::dwarf_linker::DebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a0b4ec7dfa0beee39e0d09a0cf5c09f54">llvm::dwarf_linker::DebugLocLists</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugdierefpatch/#a89a938dab68ecb317ff13a49ef69b07b">llvm::dwarf_linker::parallel::DebugDieRefPatch::RefCU</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debuguleb128dierefpatch/#af365f957c875caea0495402bfb5fa226">llvm::dwarf_linker::parallel::DebugULEB128DieRefPatch::RefCU</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugdierefpatch/#a5be88bdb2e9bf74dda956aea55e25ebf">llvm::dwarf_linker::parallel::DebugDieRefPatch::RefDieIdxOrClonedOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debuguleb128dierefpatch/#abb01a450d84b2b55309b72ab76c549e6">llvm::dwarf_linker::parallel::DebugULEB128DieRefPatch::RefDieIdxOrClonedOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a619f7575a44789258647c79fc9c156d1">llvm::dwarf_linker::parallel::OutputSections::tryGetSectionDescriptor</a>.</p>

</div>
</div>

### verifyDependencies() {#ac4e94a48345ff3b6df8fd5314d7bb885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CompileUnit::verifyDependencies ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> DIEs to have a consistent marking(keep marking, placement marking).</p>

<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1846 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### allocateTypeDie() {#ab04377f40c96367a39a6702f9f401be9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * CompileUnit::allocateTypeDie (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeentrybody">TypeEntryBody</a> * TypeDescriptor, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/diegenerator">DIEGenerator</a> &amp; TypeDIEGenerator, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> DieTag, bool IsDeclaration, bool IsParentDeclaration)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create output <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> inside specified <span class="doxyComputerOutput">TypeDescriptor</span>.</p>


<p>Allocates output <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for the specified <span class="doxyComputerOutput">TypeDescriptor</span>.</p>


<p>Declaration at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1421 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### analyzeDWARFStructureRec() {#a876793bbbbcff8bb613e7845c1ab6c38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CompileUnit::analyzeDWARFStructureRec (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * DieEntry, bool IsODRUnavailableFunctionScope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Navigate DWARF tree recursively and set die properties.</p>

<p>Declaration at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### assignTypeNamesRec() {#a51d1c66b3728c1f307115f90c44c7019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CompileUnit::assignTypeNamesRec (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * DieEntry, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder">SyntheticTypeNameBuilder</a> &amp; NameBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enumerate <span class="doxyComputerOutput">DieEntry</span> children and assign names for them.</p>

<p>Declaration at line 668 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### cloneAndEmitRangeList() {#ae1695911f6e1b843def20a603bb3e001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CompileUnit::cloneAndEmitRangeList (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24">DebugSectionKind</a> RngSectionKind, <a href="/web-llvm/docs/api/classes/llvm/addressranges">AddressRanges</a> &amp; LinkedFunctionRanges)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone and emit .debug_ranges/.debug_rnglists.</p>

<p>Declaration at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### createPlainDIEandCloneAttributes() {#a4f4e9895019956409162a47cfd659e96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * CompileUnit::createPlainDIEandCloneAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * InputDieEntry, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/diegenerator">DIEGenerator</a> &amp; PlainDIEGenerator, uint64_t &amp; OutOffset, std::optional&lt; int64_t &gt; &amp; FuncAddressAdjustment, std::optional&lt; int64_t &gt; &amp; VarAddressAdjustment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> which would be placed into the "Plain" compile unit.</p>

<p>Declaration at line 652 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1362 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### createTypeDIEandCloneAttributes() {#a192bf75da45878bc24b4c407a79d15c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeEntry * CompileUnit::createTypeDIEandCloneAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * InputDieEntry, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/diegenerator">DIEGenerator</a> &amp; TypeDIEGenerator, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> * ClonedParentTypeDIE, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit">TypeUnit</a> * ArtificialTypeUnit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> which would be placed into the "Type" compile unit.</p>

<p>Declaration at line 658 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1467 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### emitAranges() {#a548a5e71417cb3d21bd6b09b3e27eafe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CompileUnit::emitAranges (<a href="/web-llvm/docs/api/classes/llvm/addressranges">AddressRanges</a> &amp; LinkedFunctionRanges)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit .debug_aranges.</p>

<p>Declaration at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 838 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### emitDebugAddrSection() {#a2270ac65fe1c874f700d49b406ee8715}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CompileUnit::emitDebugAddrSection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the .debug_addr section fragment for current unit.</p>

<p>Declaration at line 626 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### emitLocations() {#adf42c12f24bc06643f5cb48e93a54107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CompileUnit::emitLocations (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24">DebugSectionKind</a> LocationSectionKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit debug locations.</p>

<p>Declaration at line 615 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### emitLocListFragment() {#aafdbe7a0fa3d6292a64288052f7fdea2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t CompileUnit::emitLocListFragment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">LinkedLocationExpressionsVector</a> &amp; LinkedLocationExpression, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &amp; OutLocationSection)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit location list fragment.</p>


<p>Emit debug locations(.debug_loc, .debug_loclists) fragment.</p>


<p>Declaration at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### emitLocListHeader() {#ab01c1b7bbb4585b1b18beb7ed13f7b54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t CompileUnit::emitLocListHeader (<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &amp; OutLocationSection)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit location list header.</p>


<p>Emit debug locations(.debug_loc, .debug_loclists) header.</p>


<p>Declaration at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### emitMacroTableImpl() {#a1c3a091a8bbfad0d558dc8a20151afb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CompileUnit::emitMacroTableImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugmacro">DWARFDebugMacro</a> * MacroTable, uint64_t OffsetToMacroTable, bool hasDWARFv5Header)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits body for both macro sections.</p>

<p>Declaration at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 922 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### emitRangeListFragment() {#aa8b5fba5f51fba9b90233cee0fc4d1c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CompileUnit::emitRangeListFragment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/addressranges">AddressRanges</a> &amp; LinkedRanges, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &amp; OutRangeSection)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit range list fragment.</p>

<p>Declaration at line 639 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 793 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### emitRangeListHeader() {#a4690179231178168f3a618cef957933f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t CompileUnit::emitRangeListHeader (<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &amp; OutRangeSection)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit range list header.</p>

<p>Declaration at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 770 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### insertLineSequence() {#aeac84789b641ea69ee6a673f2608fd50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CompileUnit::insertLineSequence (std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/row">DWARFDebugLine::Row</a> &gt; &amp; Seq, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/row">DWARFDebugLine::Row</a> &gt; &amp; Rows)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert the new line info sequence <span class="doxyComputerOutput">Seq</span> into the current set of already linked line info <span class="doxyComputerOutput">Rows</span>.</p>

<p>Declaration at line 644 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1610 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DebugAddrIndexMap {#aa9a892f039ff90244f9c0d8ee6483cd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedValuesMap&lt;uint64_t&gt; llvm::dwarf_linker::parallel::CompileUnit::DebugAddrIndexMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps an address into the index inside .debug_addr section.</p>

<p>Definition at line 690 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### Dependencies {#a5ee4438eed1c236ee20b9dbb22cebd6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DependencyTracker&gt; llvm::dwarf_linker::parallel::CompileUnit::Dependencies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 692 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### File {#a01563c81f25d3c695c564916e8ea7dcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFFile&amp; llvm::dwarf_linker::parallel::CompileUnit::File</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> containing this compile unit.</p>

<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### Language {#a90ba5f0fdf87513d9ce2f4256b55cd6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint16_t&gt; llvm::dwarf_linker::parallel::CompileUnit::Language</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The DW_AT_language of this unit.</p>

<p>Definition at line 678 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### LineTablePtr {#a0f4b23c7b12e77b72ec9b486d1de86a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugLine::LineTable* llvm::dwarf_linker::parallel::CompileUnit::LineTablePtr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Line table for this unit.</p>

<p>Definition at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### OrigUnit {#a6ecb2f08bf8ea63222b196475204a315}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnit* llvm::dwarf_linker::parallel::CompileUnit::OrigUnit = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer to the paired compile unit from the input DWARF.</p>

<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### ResolvedFullPaths {#aa4701197d681a7a6803f90d480f9d378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResolvedPathsMap llvm::dwarf_linker::parallel::CompileUnit::ResolvedFullPaths</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 686 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### ResolvedParentPaths {#a7a580627f8d539adea83d927b0110467}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;StringEntry *&gt; llvm::dwarf_linker::parallel::CompileUnit::ResolvedParentPaths</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 687 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
