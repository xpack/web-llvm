---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarfdebugline/sequence
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Sequence` Struct Reference

<p>Represents a series of contiguous machine instructions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::DWARFDebugLine::Sequence { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">llvm/DebugInfo/DWARF/DWARFDebugLine.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5614daeb66c330081b35eb249945e16">Sequence</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa108fa264ddea1330c82b79be3139072">reset</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3763a6c4002166be8aee41ddb34a008">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad71c2b014b37f42efef1e43d3d104a73">containsPC</a> (object::SectionedAddress PC) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f16f3782e217142f4b047fc49b6f1e3">LowPC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/sequence">Sequence</a> describes instructions at address range [LowPC, HighPC) and is described by line table rows [FirstRowIndex, LastRowIndex). <a href="#a0f16f3782e217142f4b047fc49b6f1e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8388ca6a84e17aed757e9d2236e0979">HighPC</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb77c4261bf7b7dd460a27a5b9d29d0e">SectionIndex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If relocation information is present then this is the index of the section which contains above addresses. <a href="#afb77c4261bf7b7dd460a27a5b9d29d0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a715e5c0283895a356cf6c4dd8436f220">FirstRowIndex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cde4a4d0a2dac5e31463bdff60dc4f0">LastRowIndex</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ffa2fcbd7dd2d8fec05cc06d3b08c4">Empty</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59805c2dc5142a4bad83a16d61e0fdeb">orderByHighPC</a> (const Sequence &amp;LHS, const Sequence &amp;RHS)</td>
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

<p>Represents a series of contiguous machine instructions.</p>


<p>Line table for each compilation unit may consist of multiple sequences, which are not guaranteed to be in the order of ascending instruction address.</p>


<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Sequence() {#ab5614daeb66c330081b35eb249945e16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDebugLine::Sequence::Sequence ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>Reference <a href="#aa108fa264ddea1330c82b79be3139072">reset</a>.</p>


<p>Referenced by <a href="#a59805c2dc5142a4bad83a16d61e0fdeb">orderByHighPC</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### containsPC() {#ad71c2b014b37f42efef1e43d3d104a73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFDebugLine::Sequence::containsPC (<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> PC)</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#a8807f1e455c2c5a36f3f2aaf617f823b">llvm::object::SectionedAddress::Address</a>, <a href="#ae8388ca6a84e17aed757e9d2236e0979">HighPC</a>, <a href="#a0f16f3782e217142f4b047fc49b6f1e3">LowPC</a>, <a href="#afb77c4261bf7b7dd460a27a5b9d29d0e">SectionIndex</a> and <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#adb3de5796b8423b3f4442e10b55747a5">llvm::object::SectionedAddress::SectionIndex</a>.</p>

</div>
</div>

### isValid() {#ac3763a6c4002166be8aee41ddb34a008}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFDebugLine::Sequence::isValid ()</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>References <a href="#af6ffa2fcbd7dd2d8fec05cc06d3b08c4">Empty</a>, <a href="#a715e5c0283895a356cf6c4dd8436f220">FirstRowIndex</a>, <a href="#ae8388ca6a84e17aed757e9d2236e0979">HighPC</a>, <a href="#a4cde4a4d0a2dac5e31463bdff60dc4f0">LastRowIndex</a> and <a href="#a0f16f3782e217142f4b047fc49b6f1e3">LowPC</a>.</p>

</div>
</div>

### reset() {#aa108fa264ddea1330c82b79be3139072}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFDebugLine::Sequence::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>References <a href="#af6ffa2fcbd7dd2d8fec05cc06d3b08c4">Empty</a>, <a href="#a715e5c0283895a356cf6c4dd8436f220">FirstRowIndex</a>, <a href="#ae8388ca6a84e17aed757e9d2236e0979">HighPC</a>, <a href="#a4cde4a4d0a2dac5e31463bdff60dc4f0">LastRowIndex</a>, <a href="#a0f16f3782e217142f4b047fc49b6f1e3">LowPC</a>, <a href="#afb77c4261bf7b7dd460a27a5b9d29d0e">SectionIndex</a> and <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#aab5f6719f1bf1cfd6c53e95ebce09470">llvm::object::SectionedAddress::UndefSection</a>.</p>


<p>Referenced by <a href="#ab5614daeb66c330081b35eb249945e16">Sequence</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Empty {#af6ffa2fcbd7dd2d8fec05cc06d3b08c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFDebugLine::Sequence::Empty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#ac3763a6c4002166be8aee41ddb34a008">isValid</a> and <a href="#aa108fa264ddea1330c82b79be3139072">reset</a>.</p>

</div>
</div>

### FirstRowIndex {#a715e5c0283895a356cf6c4dd8436f220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFDebugLine::Sequence::FirstRowIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#ac3763a6c4002166be8aee41ddb34a008">isValid</a> and <a href="#aa108fa264ddea1330c82b79be3139072">reset</a>.</p>

</div>
</div>

### HighPC {#ae8388ca6a84e17aed757e9d2236e0979}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFDebugLine::Sequence::HighPC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#ad71c2b014b37f42efef1e43d3d104a73">containsPC</a>, <a href="#ac3763a6c4002166be8aee41ddb34a008">isValid</a> and <a href="#aa108fa264ddea1330c82b79be3139072">reset</a>.</p>

</div>
</div>

### LastRowIndex {#a4cde4a4d0a2dac5e31463bdff60dc4f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFDebugLine::Sequence::LastRowIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#ac3763a6c4002166be8aee41ddb34a008">isValid</a> and <a href="#aa108fa264ddea1330c82b79be3139072">reset</a>.</p>

</div>
</div>

### LowPC {#a0f16f3782e217142f4b047fc49b6f1e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFDebugLine::Sequence::LowPC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/sequence">Sequence</a> describes instructions at address range [LowPC, HighPC) and is described by line table rows [FirstRowIndex, LastRowIndex).</p>

<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#ad71c2b014b37f42efef1e43d3d104a73">containsPC</a>, <a href="#ac3763a6c4002166be8aee41ddb34a008">isValid</a> and <a href="#aa108fa264ddea1330c82b79be3139072">reset</a>.</p>

</div>
</div>

### SectionIndex {#afb77c4261bf7b7dd460a27a5b9d29d0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFDebugLine::Sequence::SectionIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If relocation information is present then this is the index of the section which contains above addresses.</p>


<p>Otherwise this is object::SectionedAddress::Undef value.</p>


<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#ad71c2b014b37f42efef1e43d3d104a73">containsPC</a> and <a href="#aa108fa264ddea1330c82b79be3139072">reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### orderByHighPC() {#a59805c2dc5142a4bad83a16d61e0fdeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFDebugLine::Sequence::orderByHighPC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/sequence">Sequence</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/sequence">Sequence</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#ab5614daeb66c330081b35eb249945e16">Sequence</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
