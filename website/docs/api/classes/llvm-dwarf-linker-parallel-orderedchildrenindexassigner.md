---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/orderedchildrenindexassigner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `OrderedChildrenIndexAssigner` Class

<p>This class helps to assign indexes for <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> children. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::OrderedChildrenIndexAssigner { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">DWARFLinker/Parallel/SyntheticTypeNameBuilder.h</a>"
</div>

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1f946bf0a1a7feb1321a93d6d6d9481">OrderedChildrenIndexesArrayTy</a> = std::array&lt; size_t, 8 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35a7e49f4e117e826cc996123028fd4a">OrderedChildrenIndexAssigner</a> (CompileUnit &amp;CU, const DWARFDebugInfoEntry *DieEntry)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::pair&lt; size_t, size_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2a32e394e2b3d454b598314fe152524">getChildIndex</a> (CompileUnit &amp;CU, const DWARFDebugInfoEntry *ChildDieEntry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns index of the specified child and width of hexadecimal representation. <a href="#aa2a32e394e2b3d454b598314fe152524">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c77e7d7880dad995ec6ff60f6630710">tagToArrayIndex</a> (CompileUnit &amp;CU, const DWARFDebugInfoEntry *DieEntry)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b9ff14bd99ede19ebc1c5bc5c94f467">NeedCountChildren</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab1f946bf0a1a7feb1321a93d6d6d9481">OrderedChildrenIndexesArrayTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb9e99d4b7c56a8df5ea73f5d1cd5cf3">OrderedChildIdxs</a> = {0}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab1f946bf0a1a7feb1321a93d6d6d9481">OrderedChildrenIndexesArrayTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b575a87e6e06783b292855117ee772">ChildIndexesWidth</a> = {0}</td>
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

<p>This class helps to assign indexes for <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> children.</p>


<p>Indexes are used to create type name for children which should be presented in the original order(function parameters, array dimensions, enumeration members, class/structure members).</p>


<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### OrderedChildrenIndexesArrayTy {#ab1f946bf0a1a7feb1321a93d6d6d9481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::parallel::OrderedChildrenIndexAssigner::OrderedChildrenIndexesArrayTy =  std::array&lt;size_t, 8&gt;</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### OrderedChildrenIndexAssigner() {#a35a7e49f4e117e826cc996123028fd4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OrderedChildrenIndexAssigner::OrderedChildrenIndexAssigner (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> &amp; CU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * DieEntry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>, definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a08b575a87e6e06783b292855117ee772">ChildIndexesWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#a53e2261d44de5b8447cfa73b482c647f">llvm::DWARFDebugInfoEntry::getTag</a>, <a href="#a7b9ff14bd99ede19ebc1c5bc5c94f467">NeedCountChildren</a> and <a href="#a7c77e7d7880dad995ec6ff60f6630710">tagToArrayIndex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getChildIndex() {#aa2a32e394e2b3d454b598314fe152524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; size_t, size_t &gt; &gt; OrderedChildrenIndexAssigner::getChildIndex (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> &amp; CU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * ChildDieEntry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns index of the specified child and width of hexadecimal representation.</p>

<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>, definition at line 750 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a08b575a87e6e06783b292855117ee772">ChildIndexesWidth</a>, <a href="#abb9e99d4b7c56a8df5ea73f5d1cd5cf3">OrderedChildIdxs</a> and <a href="#a7c77e7d7880dad995ec6ff60f6630710">tagToArrayIndex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### tagToArrayIndex() {#a7c77e7d7880dad995ec6ff60f6630710}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; size_t &gt; OrderedChildrenIndexAssigner::tagToArrayIndex (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> &amp; CU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * DieEntry)</td>
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



<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>, definition at line 715 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#ab9761bc1cfe0e7e41b91d4e590df92e4">llvm::DWARFDebugInfoEntry::getParentIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#a53e2261d44de5b8447cfa73b482c647f">llvm::DWARFDebugInfoEntry::getTag</a> and <a href="#a7b9ff14bd99ede19ebc1c5bc5c94f467">NeedCountChildren</a>.</p>


<p>Referenced by <a href="#aa2a32e394e2b3d454b598314fe152524">getChildIndex</a> and <a href="#a35a7e49f4e117e826cc996123028fd4a">OrderedChildrenIndexAssigner</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ChildIndexesWidth {#a08b575a87e6e06783b292855117ee772}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OrderedChildrenIndexesArrayTy llvm::dwarf_linker::parallel::OrderedChildrenIndexAssigner::ChildIndexesWidth = {0}</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>.</p>


<p>Referenced by <a href="#aa2a32e394e2b3d454b598314fe152524">getChildIndex</a> and <a href="#a35a7e49f4e117e826cc996123028fd4a">OrderedChildrenIndexAssigner</a>.</p>

</div>
</div>

### NeedCountChildren {#a7b9ff14bd99ede19ebc1c5bc5c94f467}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::OrderedChildrenIndexAssigner::NeedCountChildren = false</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>.</p>


<p>Referenced by <a href="#a35a7e49f4e117e826cc996123028fd4a">OrderedChildrenIndexAssigner</a> and <a href="#a7c77e7d7880dad995ec6ff60f6630710">tagToArrayIndex</a>.</p>

</div>
</div>

### OrderedChildIdxs {#abb9e99d4b7c56a8df5ea73f5d1cd5cf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OrderedChildrenIndexesArrayTy llvm::dwarf_linker::parallel::OrderedChildrenIndexAssigner::OrderedChildIdxs = {0}</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>.</p>


<p>Referenced by <a href="#aa2a32e394e2b3d454b598314fe152524">getChildIndex</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
