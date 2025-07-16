---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarf-linker/parallel/typeunit/typeunitaccelinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `TypeUnitAccelInfo` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/typeunit/typeunitaccelinfo">TypeUnitAccelInfo</a> extends AccelInfo structure with type specific fileds. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::dwarf_linker::parallel::TypeUnit::TypeUnitAccelInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinker/Parallel/DWARFLinkerTypeUnit.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarfunit/accelinfo">AccelInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This structure keeps fields which would be used for creating accelerator table. <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarfunit/accelinfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa53a4ea046fa6be17c9a5e840e014e33">OutDIE</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to the output <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> which owns this accelerator record. <a href="#aa53a4ea046fa6be17c9a5e840e014e33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeentrybody">TypeEntryBody</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa658f543f12a76255073f1589383ebaa">TypeEntryBodyPtr</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to the type entry body. <a href="#aa658f543f12a76255073f1589383ebaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/typeunit/typeunitaccelinfo">TypeUnitAccelInfo</a> extends AccelInfo structure with type specific fileds.</p>


<p>We need these additional fields to decide whether OutDIE should have an accelerator record or not. The TypeEntryBodyPtr can refer to the declaration <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and definition <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> corresponding to the type entry. Only one of them would be used in final output. So if <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/typeunit/typeunitaccelinfo">TypeUnitAccelInfo</a> refers OutDIE which does not match with TypeEntryBodyPtr-&gt;getFinalDie() then such record should be skipped.</p>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### OutDIE {#aa53a4ea046fa6be17c9a5e840e014e33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE* llvm::dwarf_linker::parallel::TypeUnit::TypeUnitAccelInfo::OutDIE = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer to the output <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> which owns this accelerator record.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>.</p>

</div>
</div>

### TypeEntryBodyPtr {#aa658f543f12a76255073f1589383ebaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeEntryBody* llvm::dwarf_linker::parallel::TypeUnit::TypeUnitAccelInfo::TypeEntryBodyPtr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer to the type entry body.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkertypeunit-h">DWARFLinkerTypeUnit.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
