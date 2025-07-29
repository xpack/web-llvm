---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/outputsections
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `OutputSections` Class

<p>This class keeps contents and offsets to the debug sections. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::OutputSections { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">DWARFLinker/Parallel/OutputSections.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext">LinkContext</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps track of data associated with one object during linking. <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

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

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c365efc5be589ccbcf4ef2548d454df">SectionsSetTy</a> = std::map&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24">DebugSectionKind</a>, std::shared_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All keeping sections. <a href="#a6c365efc5be589ccbcf4ef2548d454df">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f3129c5b81b6f215d2ac67d576f6c5f">OutputSections</a> (LinkingGlobalData &amp;GlobalData)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d003066059ba2b698ace39edf39e2cf">setOutputFormat</a> (dwarf::FormParams Format, llvm::endianness Endianness)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets output format for all keeping sections. <a href="#a6d003066059ba2b698ace39edf39e2cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac346e762c5e3e2f8f8e97162b0afd05a">getSectionDescriptor</a> (DebugSectionKind SectionKind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns descriptor for the specified section of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></span>. <a href="#ac346e762c5e3e2f8f8e97162b0afd05a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2dd1e063f59535f2cbf1a790119f904">getSectionDescriptor</a> (DebugSectionKind SectionKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns descriptor for the specified section of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></span>. <a href="#ad2dd1e063f59535f2cbf1a790119f904">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a619f7575a44789258647c79fc9c156d1">tryGetSectionDescriptor</a> (DebugSectionKind SectionKind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns descriptor for the specified section of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></span>. <a href="#a619f7575a44789258647c79fc9c156d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a017e591e9bc64a32f08806dbbd9302d4">tryGetSectionDescriptor</a> (DebugSectionKind SectionKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns descriptor for the specified section of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></span>. <a href="#a017e591e9bc64a32f08806dbbd9302d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6597212694001f13f816944c69bb0b2">getOrCreateSectionDescriptor</a> (DebugSectionKind SectionKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns descriptor for the specified section of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></span>. <a href="#ab6597212694001f13f816944c69bb0b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a400254aefab880eb0cc6b1a7a896b223">eraseSections</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erases data of all sections. <a href="#a400254aefab880eb0cc6b1a7a896b223">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae15d3fd865c24112c03b48e951d71e8">forEach</a> (function_ref&lt; void(SectionDescriptor &amp;)&gt; Handler)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerate all sections and call <span class="doxyComputerOutput">Handler</span> for each. <a href="#aae15d3fd865c24112c03b48e951d71e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad254650b92ea2dca111d2aec0710a3d">forEach</a> (function_ref&lt; void(std::shared_ptr&lt; SectionDescriptor &gt; Section)&gt; Handler)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerate all sections and call <span class="doxyComputerOutput">Handler</span> for each. <a href="#aad254650b92ea2dca111d2aec0710a3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf76888e84a79bf369b5b06117b6a814">assignSectionsOffsetAndAccumulateSize</a> (std::array&lt; uint64_t, SectionKindsNum &gt; &amp;SectionSizesAccumulator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerate all sections, for each section set current offset (kept by <span class="doxyComputerOutput">SectionSizesAccumulator</span>), update current offset with section length. <a href="#abf76888e84a79bf369b5b06117b6a814">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09b5d1027676907c7bc194a865ffe0df">applyPatches</a> (SectionDescriptor &amp;Section, StringEntryToDwarfStringPoolEntryMap &amp;DebugStrStrings, StringEntryToDwarfStringPoolEntryMap &amp;DebugLineStrStrings, TypeUnit *TypeUnitPtr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerate all sections, for each section apply all section patches. <a href="#a09b5d1027676907c7bc194a865ffe0df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0df9b23ed5b92045b815ebf04d16070">getEndianness</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Endiannes for the sections. <a href="#ab0df9b23ed5b92045b815ebf04d16070">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72e4600f7a22981307da5b2a2b5acb68">getVersion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return DWARF version. <a href="#a72e4600f7a22981307da5b2a2b5acb68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e3b66f8d958f065300cf5ddda43f715">getDebugInfoHeaderSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return size of header of debug_info table. <a href="#a7e3b66f8d958f065300cf5ddda43f715">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a949ffc8914b0622f41a49cb8d91a5d01">getDebugAddrHeaderSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return size of header of debug_ table. <a href="#a949ffc8914b0622f41a49cb8d91a5d01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c784bcfa4ff19345f9220e672cc6153">getDebugStrOffsetsHeaderSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return size of header of debug_str_offsets table. <a href="#a0c784bcfa4ff19345f9220e672cc6153">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">dwarf::FormParams</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33ecefa9aec7bce5d08e92138ae1be08">getFormParams</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return size of address. <a href="#a33ecefa9aec7bce5d08e92138ae1be08">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ff0b6f2677a5d00534c3cc841b72598">GlobalData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">dwarf::FormParams</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1766b7f5152f1dfe8b9498df8314a356">Format</a> = {4, 4, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a63265bb5719678b401b0abd0ed5ddd76">dwarf::DWARF32</a>}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Format for sections. <a href="#a1766b7f5152f1dfe8b9498df8314a356">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a162a2cce104d19d511531b2df979c051">Endianness</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dba8e5f3adee38c8fccc13c1f3be0143796">llvm::endianness::native</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Endiannes for sections. <a href="#a162a2cce104d19d511531b2df979c051">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6c365efc5be589ccbcf4ef2548d454df">SectionsSetTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78090b60a0011957ec01c44e7c8396ca">SectionDescriptors</a></td>
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

<p>This class keeps contents and offsets to the debug sections.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> objects which is supposed to be emitted into the debug sections should use this class to track debug sections offsets and keep sections data.</p>


<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### SectionsSetTy {#a6c365efc5be589ccbcf4ef2548d454df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::parallel::OutputSections::SectionsSetTy = 
      std::map&lt;DebugSectionKind, std::shared_ptr&lt;SectionDescriptor&gt;&gt;</td>
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

<p>All keeping sections.</p>

<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### OutputSections() {#a0f3129c5b81b6f215d2ac67d576f6c5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::OutputSections::OutputSections (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/linkingglobaldata">LinkingGlobalData</a> &amp; GlobalData)</td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Reference <a href="#a0ff0b6f2677a5d00534c3cc841b72598">GlobalData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ad367b733292adfe15b6d45c5fc4db8b2">llvm::dwarf_linker::parallel::DwarfUnit::DwarfUnit</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a5ab3780e334068dcd1d8e0525e7b9607">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::LinkContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyPatches() {#a09b5d1027676907c7bc194a865ffe0df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputSections::applyPatches (<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &amp; Section, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/stringentrytodwarfstringpoolentrymap">StringEntryToDwarfStringPoolEntryMap</a> &amp; DebugStrStrings, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/stringentrytodwarfstringpoolentrymap">StringEntryToDwarfStringPoolEntryMap</a> &amp; DebugLineStrStrings, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit">TypeUnit</a> * TypeUnitPtr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enumerate all sections, for each section apply all section patches.</p>

<p>Declaration at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>, definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-cpp">OutputSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24af6f6931771db95a6bffec131b856bd50">llvm::dwarf_linker::DebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a0b4ec7dfa0beee39e0d09a0cf5c09f54">llvm::dwarf_linker::DebugLocLists</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a558f46094c3e1ffac3dba6928d34c2b9">llvm::dwarf_linker::DebugRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ab09a90abca61cf08407bb116fdc3b75d">llvm::dwarf_linker::DebugRngLists</a>, <a href="#a1766b7f5152f1dfe8b9498df8314a356">Format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/stringentrytodwarfstringpoolentrymap/#a9eae8f19c57158a5be2206d9852037e1">llvm::dwarf_linker::parallel::StringEntryToDwarfStringPoolEntryMap::getExistingEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeentrybody/#a30a134da38e368dc2cf1d981aec2bcf8">llvm::dwarf_linker::parallel::TypeEntryBody::getFinalDie</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#ac44e64e0d814099105dde610b11c9914">llvm::DIE::getOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa02a1d8fb0f561ab81f4a2570db7dc28">llvm::getULEB128Size</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectionpatch/#a1260d86292f1117eef813dec942e556b">llvm::dwarf_linker::parallel::SectionPatch::PatchOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#af80b542f4b0c15d3425d97257ecda897">llvm::dwarf_linker::parallel::SectionDescriptor::StartOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugstrpatch/#a879b5a35af86c2414da97bb10a132000">llvm::dwarf_linker::parallel::DebugStrPatch::String</a> and <a href="#a619f7575a44789258647c79fc9c156d1">tryGetSectionDescriptor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#af05462e5991a1325a9944da1b5d1d5b9">llvm::dwarf_linker::parallel::DWARFLinkerImpl::patchOffsetsAndSizes</a>.</p>

</div>
</div>

### assignSectionsOffsetAndAccumulateSize() {#abf76888e84a79bf369b5b06117b6a814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::OutputSections::assignSectionsOffsetAndAccumulateSize (std::array&lt; uint64_t, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a736c2f4f2d709c7b8159cbad577a3121">SectionKindsNum</a> &gt; &amp; SectionSizesAccumulator)</td>
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

<p>Enumerate all sections, for each section set current offset (kept by <span class="doxyComputerOutput">SectionSizesAccumulator</span>), update current offset with section length.</p>

<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Reference <a href="#a78090b60a0011957ec01c44e7c8396ca">SectionDescriptors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a503780ae68db06781462184c877ba5ad">llvm::dwarf_linker::parallel::DWARFLinkerImpl::assignOffsetsToSections</a>.</p>

</div>
</div>

### eraseSections() {#a400254aefab880eb0cc6b1a7a896b223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::OutputSections::eraseSections ()</td>
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

<p>Erases data of all sections.</p>

<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Reference <a href="#a78090b60a0011957ec01c44e7c8396ca">SectionDescriptors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0dec660c088023646b612c8aafc8966d">llvm::dwarf_linker::parallel::CompileUnit::maybeResetToLoadedStage</a>.</p>

</div>
</div>

### forEach() {#aae15d3fd865c24112c03b48e951d71e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::OutputSections::forEach (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &amp;)&gt; Handler)</td>
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

<p>Enumerate all sections and call <span class="doxyComputerOutput">Handler</span> for each.</p>

<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a78090b60a0011957ec01c44e7c8396ca">SectionDescriptors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#af05462e5991a1325a9944da1b5d1d5b9">llvm::dwarf_linker::parallel::DWARFLinkerImpl::patchOffsetsAndSizes</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a2e4feb28330f8c865244bec30383d1a9">llvm::dwarf_linker::parallel::DWARFLinkerImpl::writeCompileUnitsToTheOutput</a>.</p>

</div>
</div>

### forEach() {#aad254650b92ea2dca111d2aec0710a3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::OutputSections::forEach (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(std::shared_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &gt; Section)&gt; Handler)</td>
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

<p>Enumerate all sections and call <span class="doxyComputerOutput">Handler</span> for each.</p>

<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Reference <a href="#a78090b60a0011957ec01c44e7c8396ca">SectionDescriptors</a>.</p>

</div>
</div>

### getDebugAddrHeaderSize() {#a949ffc8914b0622f41a49cb8d91a5d01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::dwarf_linker::parallel::OutputSections::getDebugAddrHeaderSize ()</td>
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

<p>Return size of header of debug_ table.</p>

<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a63265bb5719678b401b0abd0ed5ddd76">llvm::dwarf::DWARF32</a> and <a href="#a1766b7f5152f1dfe8b9498df8314a356">Format</a>.</p>

</div>
</div>

### getDebugInfoHeaderSize() {#a7e3b66f8d958f065300cf5ddda43f715}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::dwarf_linker::parallel::OutputSections::getDebugInfoHeaderSize ()</td>
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

<p>Return size of header of debug_info table.</p>

<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Reference <a href="#a1766b7f5152f1dfe8b9498df8314a356">Format</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ab33a7e6fdc362895e1b739081c1286ba">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#aafd0fac7574417fa923ca2bce4b9b85c">llvm::dwarf_linker::parallel::TypeUnit::createDIETree</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ad24c182dd9def83d9d63a6cce49331c0">llvm::dwarf_linker::parallel::DwarfUnit::setOutUnitDIE</a>.</p>

</div>
</div>

### getDebugStrOffsetsHeaderSize() {#a0c784bcfa4ff19345f9220e672cc6153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::dwarf_linker::parallel::OutputSections::getDebugStrOffsetsHeaderSize ()</td>
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

<p>Return size of header of debug_str_offsets table.</p>

<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a63265bb5719678b401b0abd0ed5ddd76">llvm::dwarf::DWARF32</a> and <a href="#a1766b7f5152f1dfe8b9498df8314a356">Format</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#aafd0fac7574417fa923ca2bce4b9b85c">llvm::dwarf_linker::parallel::TypeUnit::createDIETree</a>.</p>

</div>
</div>

### getEndianness() {#ab0df9b23ed5b92045b815ebf04d16070}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::endianness llvm::dwarf_linker::parallel::OutputSections::getEndianness ()</td>
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

<p>Endiannes for the sections.</p>

<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Reference <a href="#a162a2cce104d19d511531b2df979c051">Endianness</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0b5afda9f8291e7c2433262c8dc8c167">llvm::dwarf_linker::parallel::CompileUnit::cloneDieAttrExpression</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#ad06d8aa0d7980827ad6f0a8543657f73">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::link</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a21dc5ae67ffaf38250ef5b5d377b5358">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::loadClangModule</a>.</p>

</div>
</div>

### getFormParams() {#a33ecefa9aec7bce5d08e92138ae1be08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const dwarf::FormParams &amp; llvm::dwarf_linker::parallel::OutputSections::getFormParams ()</td>
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

<p>Return size of address.</p>

<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Reference <a href="#a1766b7f5152f1dfe8b9498df8314a356">Format</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5d779ebf8d97beda3616fa4d7997e355">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0b5afda9f8291e7c2433262c8dc8c167">llvm::dwarf_linker::parallel::CompileUnit::cloneDieAttrExpression</a>, <a href="/web-llvm/docs/api/groups/methods/#ga4353067d272bae6ec1a934e5ea39f924">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#aa5415f7dcc45583b4bb82acb6f64c73a">llvm::dwarf_linker::parallel::DwarfUnit::emitPubAcceleratorEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#af7ec06f047bb304a65a2c02f3bb13063">llvm::dwarf_linker::parallel::TypeUnit::TypeUnit</a>.</p>

</div>
</div>

### getOrCreateSectionDescriptor() {#ab6597212694001f13f816944c69bb0b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionDescriptor &amp; llvm::dwarf_linker::parallel::OutputSections::getOrCreateSectionDescriptor (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24">DebugSectionKind</a> SectionKind)</td>
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

<p>Returns descriptor for the specified section of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></span>.</p>


<p>If descriptor does not exist then creates it.</p>


<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>References <a href="#a162a2cce104d19d511531b2df979c051">Endianness</a>, <a href="#a1766b7f5152f1dfe8b9498df8314a356">Format</a>, <a href="#a0ff0b6f2677a5d00534c3cc841b72598">GlobalData</a> and <a href="#a78090b60a0011957ec01c44e7c8396ca">SectionDescriptors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ab33a7e6fdc362895e1b739081c1286ba">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmit</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#ac4560fb1d6b91d4ba6edb7e907573c1e">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::cloneAndEmitDebugFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a26a4de20c065ba21d3af3b8f2fc2bb50">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#abe722b66707f8b5e4aaa19a24810480f">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#aafd0fac7574417fa923ca2bce4b9b85c">llvm::dwarf_linker::parallel::TypeUnit::createDIETree</a>, <a href="/web-llvm/docs/api/groups/methods/#ga9b4dbcbc740191455c092e2edd8afa51">llvm::dwarf_linker::parallel::DwarfUnit::emitAbbreviations</a>, <a href="/web-llvm/docs/api/groups/methods/#ga4353067d272bae6ec1a934e5ea39f924">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugInfo</a>, <a href="/web-llvm/docs/api/groups/methods/#ga579ac60d76c4a3b6ca084238591d4437">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugStringOffsetSection</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a5e9424dbd42c4c0b08ff61c556bd9aa1">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::emitInvariantSections</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#aa5415f7dcc45583b4bb82acb6f64c73a">llvm::dwarf_linker::parallel::DwarfUnit::emitPubAcceleratorEntry</a>, <a href="/web-llvm/docs/api/groups/methods/#ga80d3884d82a541f6f1b11931db9fc5fb">llvm::dwarf_linker::parallel::DwarfUnit::emitPubAccelerators</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#a2de70543d073c4a85bf44c845b7305e9">llvm::dwarf_linker::parallel::TypeUnit::finishCloningAndEmit</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#af7ec06f047bb304a65a2c02f3bb13063">llvm::dwarf_linker::parallel::TypeUnit::TypeUnit</a>.</p>

</div>
</div>

### getSectionDescriptor() {#ac346e762c5e3e2f8f8e97162b0afd05a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SectionDescriptor &amp; llvm::dwarf_linker::parallel::OutputSections::getSectionDescriptor (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24">DebugSectionKind</a> SectionKind)</td>
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

<p>Returns descriptor for the specified section of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></span>.</p>


<p>The descriptor should already be created. The llvm_unreachable would be raised if it is not.</p>


<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2e3d3da964f7eb14ef2eabf0c4a08ba5">llvm::c_str</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a2da32c7f0735e4bcb64c34222a79a6c1">llvm::dwarf_linker::getSectionName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#a78090b60a0011957ec01c44e7c8396ca">SectionDescriptors</a>.</p>

</div>
</div>

### getSectionDescriptor() {#ad2dd1e063f59535f2cbf1a790119f904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionDescriptor &amp; llvm::dwarf_linker::parallel::OutputSections::getSectionDescriptor (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24">DebugSectionKind</a> SectionKind)</td>
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

<p>Returns descriptor for the specified section of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></span>.</p>


<p>The descriptor should already be created. The llvm_unreachable would be raised if it is not.</p>


<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e3d3da964f7eb14ef2eabf0c4a08ba5">llvm::c_str</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a2da32c7f0735e4bcb64c34222a79a6c1">llvm::dwarf_linker::getSectionName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#a78090b60a0011957ec01c44e7c8396ca">SectionDescriptors</a>.</p>

</div>
</div>

### getVersion() {#a72e4600f7a22981307da5b2a2b5acb68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::dwarf_linker::parallel::OutputSections::getVersion ()</td>
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

<p>Return DWARF version.</p>

<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Reference <a href="#a1766b7f5152f1dfe8b9498df8314a356">Format</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0b155dc5f7f9374eb06f7277da633577">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitDebugLocations</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a67e7cb91f1de318011b4ad8f6453fa7a">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitRanges</a>, <a href="/web-llvm/docs/api/groups/methods/#ga579ac60d76c4a3b6ca084238591d4437">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugStringOffsetSection</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a53949973d752a1d918687b758424714a">llvm::dwarf_linker::parallel::CompileUnit::getDirAndFilenameFromLineTable</a>.</p>

</div>
</div>

### setOutputFormat() {#a6d003066059ba2b698ace39edf39e2cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::OutputSections::setOutputFormat (<a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">dwarf::FormParams</a> Format, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> Endianness)</td>
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

<p>Sets output format for all keeping sections.</p>

<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>References <a href="#a162a2cce104d19d511531b2df979c051">Endianness</a> and <a href="#a1766b7f5152f1dfe8b9498df8314a356">Format</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a26a4de20c065ba21d3af3b8f2fc2bb50">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#abe722b66707f8b5e4aaa19a24810480f">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#af7ec06f047bb304a65a2c02f3bb13063">llvm::dwarf_linker::parallel::TypeUnit::TypeUnit</a>.</p>

</div>
</div>

### tryGetSectionDescriptor() {#a619f7575a44789258647c79fc9c156d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; const SectionDescriptor * &gt; llvm::dwarf_linker::parallel::OutputSections::tryGetSectionDescriptor (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24">DebugSectionKind</a> SectionKind)</td>
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

<p>Returns descriptor for the specified section of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></span>.</p>


<p>Returns std::nullopt if section descriptor is not created yet.</p>


<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Reference <a href="#a78090b60a0011957ec01c44e7c8396ca">SectionDescriptors</a>.</p>


<p>Referenced by <a href="#a09b5d1027676907c7bc194a865ffe0df">applyPatches</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a717bca8e9eb21f64804ccf91908b2a49">llvm::dwarf_linker::parallel::CompileUnit::updateDieRefPatchesWithClonedOffsets</a>.</p>

</div>
</div>

### tryGetSectionDescriptor() {#a017e591e9bc64a32f08806dbbd9302d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; SectionDescriptor * &gt; llvm::dwarf_linker::parallel::OutputSections::tryGetSectionDescriptor (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24">DebugSectionKind</a> SectionKind)</td>
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

<p>Returns descriptor for the specified section of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></span>.</p>


<p>Returns std::nullopt if section descriptor is not created yet.</p>


<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Reference <a href="#a78090b60a0011957ec01c44e7c8396ca">SectionDescriptors</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Endianness {#a162a2cce104d19d511531b2df979c051}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::endianness llvm::dwarf_linker::parallel::OutputSections::Endianness = <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dba8e5f3adee38c8fccc13c1f3be0143796">llvm::endianness::native</a></td>
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

<p>Endiannes for sections.</p>

<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Referenced by <a href="#ab0df9b23ed5b92045b815ebf04d16070">getEndianness</a>, <a href="#ab6597212694001f13f816944c69bb0b2">getOrCreateSectionDescriptor</a> and <a href="#a6d003066059ba2b698ace39edf39e2cf">setOutputFormat</a>.</p>

</div>
</div>

### Format {#a1766b7f5152f1dfe8b9498df8314a356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::FormParams llvm::dwarf_linker::parallel::OutputSections::Format = {4, 4, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a63265bb5719678b401b0abd0ed5ddd76">dwarf::DWARF32</a>}</td>
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

<p>Format for sections.</p>

<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Referenced by <a href="#a09b5d1027676907c7bc194a865ffe0df">applyPatches</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a26a4de20c065ba21d3af3b8f2fc2bb50">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#abe722b66707f8b5e4aaa19a24810480f">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a>, <a href="#a949ffc8914b0622f41a49cb8d91a5d01">getDebugAddrHeaderSize</a>, <a href="#a7e3b66f8d958f065300cf5ddda43f715">getDebugInfoHeaderSize</a>, <a href="#a0c784bcfa4ff19345f9220e672cc6153">getDebugStrOffsetsHeaderSize</a>, <a href="#a33ecefa9aec7bce5d08e92138ae1be08">getFormParams</a>, <a href="#ab6597212694001f13f816944c69bb0b2">getOrCreateSectionDescriptor</a>, <a href="#a72e4600f7a22981307da5b2a2b5acb68">getVersion</a>, <a href="#a6d003066059ba2b698ace39edf39e2cf">setOutputFormat</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#af7ec06f047bb304a65a2c02f3bb13063">llvm::dwarf_linker::parallel::TypeUnit::TypeUnit</a>.</p>

</div>
</div>

### GlobalData {#a0ff0b6f2677a5d00534c3cc841b72598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkingGlobalData&amp; llvm::dwarf_linker::parallel::OutputSections::GlobalData</td>
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



<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a188e713b7044fc7477fa27c6f4efc662">llvm::dwarf_linker::parallel::CompileUnit::analyzeImportedModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ab33a7e6fdc362895e1b739081c1286ba">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmit</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#ac4560fb1d6b91d4ba6edb7e907573c1e">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::cloneAndEmitDebugFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a26a4de20c065ba21d3af3b8f2fc2bb50">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#abe722b66707f8b5e4aaa19a24810480f">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#aafd0fac7574417fa923ca2bce4b9b85c">llvm::dwarf_linker::parallel::TypeUnit::createDIETree</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ad367b733292adfe15b6d45c5fc4db8b2">llvm::dwarf_linker::parallel::DwarfUnit::DwarfUnit</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a5e9424dbd42c4c0b08ff61c556bd9aa1">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::emitInvariantSections</a>, <a href="/web-llvm/docs/api/groups/methods/#gab0417bf315aa0a768f1a33d55209135a">llvm::dwarf_linker::parallel::CompileUnit::error</a>, <a href="/web-llvm/docs/api/groups/methods/#ga067b49dc851a8db06344fa2b594cb6bb">llvm::dwarf_linker::parallel::CompileUnit::error</a>, <a href="/web-llvm/docs/api/groups/methods/#ga88ab67842e20cde2f963249cf344c2ed">llvm::dwarf_linker::parallel::DwarfUnit::error</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#a2de70543d073c4a85bf44c845b7305e9">llvm::dwarf_linker::parallel::TypeUnit::finishCloningAndEmit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#a461c26c602014baed9de7d2c019f4f8a">llvm::dwarf_linker::parallel::DwarfUnit::getGlobalData</a>, <a href="#ab6597212694001f13f816944c69bb0b2">getOrCreateSectionDescriptor</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a62ed34db5672583fcefb9c152e2dad01">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::isClangModuleRef</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#ad06d8aa0d7980827ad6f0a8543657f73">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::link</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a5ab3780e334068dcd1d8e0525e7b9607">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::LinkContext</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a8d0aeeed6972f179a2b97439943e7629">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::linkSingleCompileUnit</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a21dc5ae67ffaf38250ef5b5d377b5358">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::loadClangModule</a>, <a href="#a0f3129c5b81b6f215d2ac67d576f6c5f">OutputSections</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a1cd88157223b53c481e0e884c7e01933">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::registerModuleReference</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#af7ec06f047bb304a65a2c02f3bb13063">llvm::dwarf_linker::parallel::TypeUnit::TypeUnit</a>, <a href="/web-llvm/docs/api/groups/methods/#gae294385bb587a12499b98215ae8e7745">llvm::dwarf_linker::parallel::CompileUnit::warn</a>, <a href="/web-llvm/docs/api/groups/methods/#ga8b2f2eefb63daf2e6f322e1e90228a2e">llvm::dwarf_linker::parallel::CompileUnit::warn</a>, <a href="/web-llvm/docs/api/groups/methods/#ga654eee00b3eed07a03d37b22391d18e2">llvm::dwarf_linker::parallel::CompileUnit::warn</a> and <a href="/web-llvm/docs/api/groups/methods/#ga90690238930e2f8062b17bbea187d3b1">llvm::dwarf_linker::parallel::DwarfUnit::warn</a>.</p>

</div>
</div>

### SectionDescriptors {#a78090b60a0011957ec01c44e7c8396ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionsSetTy llvm::dwarf_linker::parallel::OutputSections::SectionDescriptors</td>
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



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Referenced by <a href="#abf76888e84a79bf369b5b06117b6a814">assignSectionsOffsetAndAccumulateSize</a>, <a href="#a400254aefab880eb0cc6b1a7a896b223">eraseSections</a>, <a href="#aae15d3fd865c24112c03b48e951d71e8">forEach</a>, <a href="#aad254650b92ea2dca111d2aec0710a3d">forEach</a>, <a href="#ab6597212694001f13f816944c69bb0b2">getOrCreateSectionDescriptor</a>, <a href="#ad2dd1e063f59535f2cbf1a790119f904">getSectionDescriptor</a>, <a href="#ac346e762c5e3e2f8f8e97162b0afd05a">getSectionDescriptor</a>, <a href="#a017e591e9bc64a32f08806dbbd9302d4">tryGetSectionDescriptor</a> and <a href="#a619f7575a44789258647c79fc9c156d1">tryGetSectionDescriptor</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-cpp">OutputSections.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
