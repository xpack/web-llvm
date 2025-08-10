---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarf-linker/parallel/sectionpatch
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SectionPatch` Struct

<p>There are fields(sizes, offsets) which should be updated after sections are generated. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::dwarf_linker::parallel::SectionPatch { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">DWARFLinker/Parallel/OutputSections.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugdierefpatch">DebugDieRefPatch</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This structure is used to update reference to the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugdierefpatch/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugdietyperefpatch">DebugDieTypeRefPatch</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This structure is used to update reference to the type <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugdietyperefpatch/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debuglinestrpatch">DebugLineStrPatch</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This structure is used to update strings offsets into .debug_line_str. <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debuglinestrpatch/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debuglocpatch">DebugLocPatch</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This structure is used to update location list offset into .debug_loc/.debug_loclists. <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debuglocpatch/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugoffsetpatch">DebugOffsetPatch</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugrangepatch">DebugRangePatch</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This structure is used to update range list offset into .debug_ranges/.debug_rnglists. <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugrangepatch/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugstrpatch">DebugStrPatch</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This structure is used to update strings offsets into .debug_str. <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugstrpatch/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugtype2typedierefpatch">DebugType2TypeDieRefPatch</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This structure is used to update reference to the type <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugtype2typedierefpatch/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugtypelinestrpatch">DebugTypeLineStrPatch</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugtypestrpatch">DebugTypeStrPatch</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debuguleb128dierefpatch">DebugULEB128DieRefPatch</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This structure is used to update reference to the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> of ULEB128 form. <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debuguleb128dierefpatch/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1260d86292f1117eef813dec942e556b">PatchOffset</a> = 0</td>
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

<p>There are fields(sizes, offsets) which should be updated after sections are generated.</p>


<p>To remember offsets and related data the descendants of <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectionpatch">SectionPatch</a> structure should be used.</p>


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### PatchOffset {#a1260d86292f1117eef813dec942e556b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::parallel::SectionPatch::PatchOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a09b5d1027676907c7bc194a865ffe0df">llvm::dwarf_linker::parallel::OutputSections::applyPatches</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugdierefpatch/#ac444562be9c1152dd02c5d5bdd1677e8">llvm::dwarf_linker::parallel::DebugDieRefPatch::DebugDieRefPatch</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugdietyperefpatch/#ab250417c1030d08bae10b1794f342075">llvm::dwarf_linker::parallel::DebugDieTypeRefPatch::DebugDieTypeRefPatch</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugoffsetpatch/#a360a9b81fa5673b1a079aef1d1ae2294">llvm::dwarf_linker::parallel::DebugOffsetPatch::DebugOffsetPatch</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugtype2typedierefpatch/#ac269fd7a44c23634d602059ba3ed4658">llvm::dwarf_linker::parallel::DebugType2TypeDieRefPatch::DebugType2TypeDieRefPatch</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugtypelinestrpatch/#a93fa3b05284ff998f26a25c556490915">llvm::dwarf_linker::parallel::DebugTypeLineStrPatch::DebugTypeLineStrPatch</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugtypestrpatch/#a7881c5f2bc6e38539ac7d85501e96f79">llvm::dwarf_linker::parallel::DebugTypeStrPatch::DebugTypeStrPatch</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debuguleb128dierefpatch/#a7a5c313f3484fa33be9522ae89d07646">llvm::dwarf_linker::parallel::DebugULEB128DieRefPatch::DebugULEB128DieRefPatch</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/outputsections-h">OutputSections.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
