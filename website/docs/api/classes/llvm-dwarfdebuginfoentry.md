---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfdebuginfoentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DWARFDebugInfoEntry` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> - A <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> with only the minimum required data. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DWARFDebugInfoEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebuginfoentry-h">llvm/DebugInfo/DWARF/DWARFDebugInfoEntry.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60534760bbbd42fac118b0d6d5170a42">DWARFDebugInfoEntry</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8146aa10694a8fda28757fdd993823d9">extractFast</a> (const DWARFUnit &amp;U, uint64_t *OffsetPtr, const DWARFDataExtractor &amp;DebugInfoData, uint64_t UEndOffset, uint32_t ParentIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extracts a debug info entry, which is a child of a given unit, starting at a given offset. <a href="#a8146aa10694a8fda28757fdd993823d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74338425061cc0d9df5fe5398d48d9f2">getOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9761bc1cfe0e7e41b91d4e590df92e4">getParentIdx</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns index of the parent die. <a href="#ab9761bc1cfe0e7e41b91d4e590df92e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6987befdd1df06ab5e76eed81056cac2">getSiblingIdx</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns index of the sibling die. <a href="#a6987befdd1df06ab5e76eed81056cac2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a042d3521b72f2d10a22b25f1560b9783">setSiblingIdx</a> (uint32_t Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set index of sibling. <a href="#a042d3521b72f2d10a22b25f1560b9783">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53e2261d44de5b8447cfa73b482c647f">getTag</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac862abc22413dd0a1fe6bdf6b9cb26a6">hasChildren</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfabbreviationdeclaration">DWARFAbbreviationDeclaration</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1912d641eadda862e32bbb231a13e50">getAbbreviationDeclarationPtr</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae435402c53972c5fc3acf9ec938f19b4">Offset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset within the .debug_info of the start of this entry. <a href="#ae435402c53972c5fc3acf9ec938f19b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bf2e386cf9f7c5939d511af32d4abd1">ParentIdx</a> = UINT32_MAX</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Index of the parent die. UINT32_MAX if there is no parent. <a href="#a0bf2e386cf9f7c5939d511af32d4abd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a183a87ee2cb820df3788a275700aa97d">SiblingIdx</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Index of the sibling die. Zero if there is no sibling. <a href="#a183a87ee2cb820df3788a275700aa97d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfabbreviationdeclaration">DWARFAbbreviationDeclaration</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ab589918c9629e30efda0801ac57b96">AbbrevDecl</a> = nullptr</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> - A <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> with only the minimum required data.</p>

<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebuginfoentry-h">DWARFDebugInfoEntry.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DWARFDebugInfoEntry() {#a60534760bbbd42fac118b0d6d5170a42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFDebugInfoEntry::DWARFDebugInfoEntry ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebuginfoentry-h">DWARFDebugInfoEntry.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### extractFast() {#a8146aa10694a8fda28757fdd993823d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFDebugInfoEntry::extractFast (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> &amp; U, uint64_t * OffsetPtr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> &amp; DebugInfoData, uint64_t UEndOffset, uint32_t ParentIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extracts a debug info entry, which is a child of a given unit, starting at a given offset.</p>


<p>If <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> can't be extracted, returns false and doesn't change OffsetPtr. High performance extraction should use this call.</p>


<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebuginfoentry-h">DWARFDebugInfoEntry.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebuginfoentry-cpp">DWARFDebugInfoEntry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a6f2f68613d44758a66e49320fb075a02">llvm::DataExtractor::getULEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#ad6c780b958be0ededd6a525ce67206bb">llvm::DataExtractor::isValidOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#ad16686174287aeb36289484f271d5225">llvm::DWARFFormValue::skipValue</a>.</p>

</div>
</div>

### getAbbreviationDeclarationPtr() {#af1912d641eadda862e32bbb231a13e50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFAbbreviationDeclaration * llvm::DWARFDebugInfoEntry::getAbbreviationDeclarationPtr ()</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebuginfoentry-h">DWARFDebugInfoEntry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#aea3108f6ef726c8e9b0d244f51230050">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addArrayDimension</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a3fa9676347c5ae75e905430f8e0897ea">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a1df1c26e0a60f062547d6ba537e0021a">llvm::dwarf_linker::parallel::CompileUnit::cloneDIE</a> and <a href="/web-llvm/docs/api/groups/helper/#ga36cc8fce6194aa7a20ae36da44795e70">llvm::dwarf_linker::parallel::CompileUnit::find</a>.</p>

</div>
</div>

### getOffset() {#a74338425061cc0d9df5fe5398d48d9f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFDebugInfoEntry::getOffset ()</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebuginfoentry-h">DWARFDebugInfoEntry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/helper/#ga36cc8fce6194aa7a20ae36da44795e70">llvm::dwarf_linker::parallel::CompileUnit::find</a>.</p>

</div>
</div>

### getParentIdx() {#ab9761bc1cfe0e7e41b91d4e590df92e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; llvm::DWARFDebugInfoEntry::getParentIdx ()</td>
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

<p>Returns index of the parent die.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebuginfoentry-h">DWARFDebugInfoEntry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1790d029c849d8cce4869ff39b6b7396">llvm::DWARFUnit::getParentEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aaf2775409266704ae5ffe40b1588a104">llvm::DWARFUnit::getPreviousSiblingEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a137ba2e95278852dbeb5d4b7a372b3a3">llvm::dwarf_linker::parallel::DependencyTracker::markParentsAsKeepingChildren</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/orderedchildrenindexassigner/#a7c77e7d7880dad995ec6ff60f6630710">llvm::dwarf_linker::parallel::OrderedChildrenIndexAssigner::tagToArrayIndex</a>.</p>

</div>
</div>

### getSiblingIdx() {#a6987befdd1df06ab5e76eed81056cac2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; llvm::DWARFDebugInfoEntry::getSiblingIdx ()</td>
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

<p>Returns index of the sibling die.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebuginfoentry-h">DWARFDebugInfoEntry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab4662b7516c2006390c013710c6bb3f3">llvm::DWARFUnit::getLastChildEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a042cc638efbb7ab4559890854afd5179">llvm::DWARFUnit::getSiblingEntry</a>.</p>

</div>
</div>

### getTag() {#a53e2261d44de5b8447cfa73b482c647f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Tag llvm::DWARFDebugInfoEntry::getTag ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebuginfoentry-h">DWARFDebugInfoEntry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#ae03fdc522b86805416485b83c76a27a3">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#ab4e80bf7b79d77fda1c18134835ee26d">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addTypePrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a1df1c26e0a60f062547d6ba537e0021a">llvm::dwarf_linker::parallel::CompileUnit::cloneDIE</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp/#a123fab946df8deba32a875505ddef3d0">getTypeDeduplicationCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/orderedchildrenindexassigner/#a35a7e49f4e117e826cc996123028fd4a">llvm::dwarf_linker::parallel::OrderedChildrenIndexAssigner::OrderedChildrenIndexAssigner</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/acceleratorrecordssaver/#aca2d3ebfb1896c7f85f76bcb6dea8b81">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::save</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/acceleratorrecordssaver/#a37addefa67ac345264fef8f6f477eef8">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::saveObjC</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/orderedchildrenindexassigner/#a7c77e7d7880dad995ec6ff60f6630710">llvm::dwarf_linker::parallel::OrderedChildrenIndexAssigner::tagToArrayIndex</a>.</p>

</div>
</div>

### hasChildren() {#ac862abc22413dd0a1fe6bdf6b9cb26a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFDebugInfoEntry::hasChildren ()</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebuginfoentry-h">DWARFDebugInfoEntry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ace915cc7890f9756905f9be5f4ce4f17">llvm::DWARFUnit::getFirstChildEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab4662b7516c2006390c013710c6bb3f3">llvm::DWARFUnit::getLastChildEntry</a>.</p>

</div>
</div>

### setSiblingIdx() {#a042d3521b72f2d10a22b25f1560b9783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFDebugInfoEntry::setSiblingIdx (uint32_t Idx)</td>
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

<p>Set index of sibling.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebuginfoentry-h">DWARFDebugInfoEntry.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AbbrevDecl {#a7ab589918c9629e30efda0801ac57b96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFAbbreviationDeclaration* llvm::DWARFDebugInfoEntry::AbbrevDecl = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebuginfoentry-h">DWARFDebugInfoEntry.h</a>.</p>

</div>
</div>

### Offset {#ae435402c53972c5fc3acf9ec938f19b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFDebugInfoEntry::Offset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offset within the .debug_info of the start of this entry.</p>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebuginfoentry-h">DWARFDebugInfoEntry.h</a>.</p>

</div>
</div>

### ParentIdx {#a0bf2e386cf9f7c5939d511af32d4abd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFDebugInfoEntry::ParentIdx = UINT32_MAX</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Index of the parent die. UINT32_MAX if there is no parent.</p>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebuginfoentry-h">DWARFDebugInfoEntry.h</a>.</p>

</div>
</div>

### SiblingIdx {#a183a87ee2cb820df3788a275700aa97d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFDebugInfoEntry::SiblingIdx = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Index of the sibling die. Zero if there is no sibling.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebuginfoentry-h">DWARFDebugInfoEntry.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebuginfoentry-h">DWARFDebugInfoEntry.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebuginfoentry-cpp">DWARFDebugInfoEntry.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
