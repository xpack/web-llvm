---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarf-linker/parallel/debugtypelinestrpatch
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DebugTypeLineStrPatch` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::dwarf_linker::parallel::DebugTypeLineStrPatch { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">DWARFLinker/Parallel/OutputSections.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectionpatch">SectionPatch</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>There are fields(sizes, offsets) which should be updated after sections are generated. <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectionpatch/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93fa3b05284ff998f26a25c556490915">DebugTypeLineStrPatch</a> (uint64_t PatchOffset, DIE *Die, TypeEntry *TypeName, StringEntry *String)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac11f6849e078fe392449623dfff945da">Die</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60d41af285aa7f26d29fa29781456311">TypeName</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae60983aed5422cde59b823cbcc72428c">String</a> = nullptr</td>
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


<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DebugTypeLineStrPatch() {#a93fa3b05284ff998f26a25c556490915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugTypeLineStrPatch::DebugTypeLineStrPatch (uint64_t PatchOffset, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * Die, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> * TypeName, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> * String)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-cpp">OutputSections.cpp</a>.</p>


<p>References <a href="#ac11f6849e078fe392449623dfff945da">Die</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectionpatch/#a1260d86292f1117eef813dec942e556b">llvm::dwarf_linker::parallel::SectionPatch::PatchOffset</a>, <a href="#ae60983aed5422cde59b823cbcc72428c">String</a> and <a href="#a60d41af285aa7f26d29fa29781456311">TypeName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Die {#ac11f6849e078fe392449623dfff945da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE* llvm::dwarf_linker::parallel::DebugTypeLineStrPatch::Die = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Referenced by <a href="#a93fa3b05284ff998f26a25c556490915">DebugTypeLineStrPatch</a>.</p>

</div>
</div>

### String {#ae60983aed5422cde59b823cbcc72428c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringEntry* llvm::dwarf_linker::parallel::DebugTypeLineStrPatch::String = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Referenced by <a href="#a93fa3b05284ff998f26a25c556490915">DebugTypeLineStrPatch</a>.</p>

</div>
</div>

### TypeName {#a60d41af285aa7f26d29fa29781456311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeEntry* llvm::dwarf_linker::parallel::DebugTypeLineStrPatch::TypeName = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Referenced by <a href="#a93fa3b05284ff998f26a25c556490915">DebugTypeLineStrPatch</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
