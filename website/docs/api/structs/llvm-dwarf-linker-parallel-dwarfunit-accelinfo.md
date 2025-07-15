---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarf-linker/parallel/dwarfunit/accelinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AccelInfo` Struct Reference

<p>This structure keeps fields which would be used for creating accelerator table. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::dwarf_linker::parallel::DwarfUnit::AccelInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinker/Parallel/DWARFLinkerUnit.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/typeunit/typeunitaccelinfo">TypeUnitAccelInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/typeunit/typeunitaccelinfo">TypeUnitAccelInfo</a> extends AccelInfo structure with type specific fileds. <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/typeunit/typeunitaccelinfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95f75df2e07e658d74bb2791cb88605f">AccelInfo</a> ()</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fb6082cc0128c564b917d04cb825941">String</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Name of the entry. <a href="#a2fb6082cc0128c564b917d04cb825941">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5906a710bb736d687eb175597ad1265c">OutOffset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Output offset of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> this entry describes. <a href="#a5906a710bb736d687eb175597ad1265c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a929e6acfb2fffd2c24e96e7e8e5725c3">QualifiedNameHash</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hash of the fully qualified name. <a href="#a929e6acfb2fffd2c24e96e7e8e5725c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae13826c4c74a089af71fa55da9556b6d">Tag</a> = dwarf::DW_TAG_null</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tag of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> this entry describes. <a href="#ae13826c4c74a089af71fa55da9556b6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga2c708209e1c0939d50f9e70bc5708491">AccelType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c75d487b09af4c72db473d5ef471d97">Type</a> = <a href="/web-llvm/docs/api/groups/methods/#gga2c708209e1c0939d50f9e70bc5708491a6adf97f83acf6453d4a6a4b1070f3754">AccelType::None</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of this accelerator record. <a href="#a7c75d487b09af4c72db473d5ef471d97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23c62b1eefdc7c3cd1d0f5bbee7a52c6">AvoidForPubSections</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Avoid emitting this entry for pub sections. <a href="#a23c62b1eefdc7c3cd1d0f5bbee7a52c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd09de84ade0039a54c6fc07d137606b">ObjcClassImplementation</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this an ObjC class implementation? <a href="#abd09de84ade0039a54c6fc07d137606b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This structure keeps fields which would be used for creating accelerator table.</p>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AccelInfo() {#a95f75df2e07e658d74bb2791cb88605f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::DwarfUnit::AccelInfo::AccelInfo ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>References <a href="#a23c62b1eefdc7c3cd1d0f5bbee7a52c6">AvoidForPubSections</a> and <a href="#abd09de84ade0039a54c6fc07d137606b">ObjcClassImplementation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AvoidForPubSections {#a23c62b1eefdc7c3cd1d0f5bbee7a52c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::DwarfUnit::AccelInfo::AvoidForPubSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Avoid emitting this entry for pub sections.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Referenced by <a href="#a95f75df2e07e658d74bb2791cb88605f">AccelInfo</a>.</p>

</div>
</div>

### ObjcClassImplementation {#abd09de84ade0039a54c6fc07d137606b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::DwarfUnit::AccelInfo::ObjcClassImplementation</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is this an ObjC class implementation?</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Referenced by <a href="#a95f75df2e07e658d74bb2791cb88605f">AccelInfo</a>.</p>

</div>
</div>

### OutOffset {#a5906a710bb736d687eb175597ad1265c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::parallel::DwarfUnit::AccelInfo::OutOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Output offset of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> this entry describes.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>

</div>
</div>

### QualifiedNameHash {#a929e6acfb2fffd2c24e96e7e8e5725c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dwarf_linker::parallel::DwarfUnit::AccelInfo::QualifiedNameHash = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hash of the fully qualified name.</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>

</div>
</div>

### String {#a2fb6082cc0128c564b917d04cb825941}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringEntry* llvm::dwarf_linker::parallel::DwarfUnit::AccelInfo::String = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Name of the entry.</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>

</div>
</div>

### Tag {#ae13826c4c74a089af71fa55da9556b6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Tag llvm::dwarf_linker::parallel::DwarfUnit::AccelInfo::Tag = dwarf::DW_TAG_null</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tag of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> this entry describes.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>

</div>
</div>

### Type {#a7c75d487b09af4c72db473d5ef471d97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AccelType llvm::dwarf_linker::parallel::DwarfUnit::AccelInfo::Type = <a href="/web-llvm/docs/api/groups/methods/#gga2c708209e1c0939d50f9e70bc5708491a6adf97f83acf6453d4a6a4b1070f3754">AccelType::None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of this accelerator record.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/acceleratorrecordssaver/#ae49a5ef1608e2df3b53c880ef1543616">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::saveNameRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/acceleratorrecordssaver/#a3fdaa3ade4765ff2fc5c85c753c7a41b">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::saveNamespaceRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/acceleratorrecordssaver/#a4cb4f618e8ceb12af873c37a5d9c554b">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::saveObjCNameRecord</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/acceleratorrecordssaver/#a09878fd3b26b9ee9ab928cd3c1922bfe">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::saveTypeRecord</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
