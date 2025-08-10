---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/appleacceltablestatictypedata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AppleAccelTableStaticTypeData` Class

<p>Accelerator table data implementation for type accelerator tables with a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset but no actual <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> pointer. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AppleAccelTableStaticTypeData { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">llvm/CodeGen/AccelTable.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata">AppleAccelTableStaticOffsetData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accelerator table data implementation for simple Apple accelerator tables with a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset but no actual <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> pointer. <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec7a18e166c380de4e908418550d72f4">AppleAccelTableStaticTypeData</a> (uint32_t Offset, uint16_t Tag, bool ObjCClassIsImplementation, uint32_t QualifiedNameHash)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1906d67b9f9f768ad574e6482f10a9a8">emit</a> (AsmPrinter *Asm) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a227eec93999866de3d2938c4852188c8">print</a> (raw_ostream &amp;OS) const override</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f714be5c9560fd0049ad7eb741e7b76">order</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e6d17c9e15420f5bb990a4f6d93ddaa">QualifiedNameHash</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15e4fc3e4d8f3563b20b1394619a54ba">Tag</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22cc15580600ed1525322648016fdee7">ObjCClassIsImplementation</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/appleacceltabledata/atom">Atom</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c92ee909a79fa32bf5b1d66a1cbed56">Atoms</a>[] = ...</td>
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

<p>Accelerator table data implementation for type accelerator tables with a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset but no actual <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> pointer.</p>

<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AppleAccelTableStaticTypeData() {#aec7a18e166c380de4e908418550d72f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AppleAccelTableStaticTypeData::AppleAccelTableStaticTypeData (uint32_t Offset, uint16_t Tag, bool ObjCClassIsImplementation, uint32_t QualifiedNameHash)</td>
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



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata/#a474aad442f170882408cc88cfe6b21f2">llvm::AppleAccelTableStaticOffsetData::AppleAccelTableStaticOffsetData</a>, <a href="#a22cc15580600ed1525322648016fdee7">ObjCClassIsImplementation</a>, <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata/#a8db3b34af8c367f201cfbcebf5c3ef66">llvm::AppleAccelTableStaticOffsetData::Offset</a>, <a href="#a0e6d17c9e15420f5bb990a4f6d93ddaa">QualifiedNameHash</a> and <a href="#a15e4fc3e4d8f3563b20b1394619a54ba">Tag</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#a1906d67b9f9f768ad574e6482f10a9a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AppleAccelTableStaticTypeData::emit (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * Asm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>, definition at line 740 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#addd759aec534bc0671ea60c8e9779e5da5209d785d6f9540a65239398210353f9">llvm::dwarf::DW_FLAG_type_implementation</a>, <a href="#a22cc15580600ed1525322648016fdee7">ObjCClassIsImplementation</a>, <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata/#a8db3b34af8c367f201cfbcebf5c3ef66">llvm::AppleAccelTableStaticOffsetData::Offset</a>, <a href="#a0e6d17c9e15420f5bb990a4f6d93ddaa">QualifiedNameHash</a> and <a href="#a15e4fc3e4d8f3563b20b1394619a54ba">Tag</a>.</p>

</div>
</div>

### print() {#a227eec93999866de3d2938c4852188c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AppleAccelTableStaticTypeData::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>, definition at line 830 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#a22cc15580600ed1525322648016fdee7">ObjCClassIsImplementation</a>, <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata/#a8db3b34af8c367f201cfbcebf5c3ef66">llvm::AppleAccelTableStaticOffsetData::Offset</a>, <a href="#a0e6d17c9e15420f5bb990a4f6d93ddaa">QualifiedNameHash</a>, <a href="#a15e4fc3e4d8f3563b20b1394619a54ba">Tag</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gaf17a843ca40c67635b127ba50ad45bdf">llvm::dwarf::TagString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### order() {#a5f714be5c9560fd0049ad7eb741e7b76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AppleAccelTableStaticTypeData::order ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata/#a8db3b34af8c367f201cfbcebf5c3ef66">llvm::AppleAccelTableStaticOffsetData::Offset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ObjCClassIsImplementation {#a22cc15580600ed1525322648016fdee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AppleAccelTableStaticTypeData::ObjCClassIsImplementation</td>
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



<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Referenced by <a href="#aec7a18e166c380de4e908418550d72f4">AppleAccelTableStaticTypeData</a>, <a href="#a1906d67b9f9f768ad574e6482f10a9a8">emit</a> and <a href="#a227eec93999866de3d2938c4852188c8">print</a>.</p>

</div>
</div>

### QualifiedNameHash {#a0e6d17c9e15420f5bb990a4f6d93ddaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AppleAccelTableStaticTypeData::QualifiedNameHash</td>
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



<p>Definition at line 550 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Referenced by <a href="#aec7a18e166c380de4e908418550d72f4">AppleAccelTableStaticTypeData</a>, <a href="#a1906d67b9f9f768ad574e6482f10a9a8">emit</a> and <a href="#a227eec93999866de3d2938c4852188c8">print</a>.</p>

</div>
</div>

### Tag {#a15e4fc3e4d8f3563b20b1394619a54ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::AppleAccelTableStaticTypeData::Tag</td>
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



<p>Definition at line 551 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Referenced by <a href="#aec7a18e166c380de4e908418550d72f4">AppleAccelTableStaticTypeData</a>, <a href="#a1906d67b9f9f768ad574e6482f10a9a8">emit</a> and <a href="#a227eec93999866de3d2938c4852188c8">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### Atoms {#a2c92ee909a79fa32bf5b1d66a1cbed56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AppleAccelTableData::Atom AppleAccelTableStaticTypeData::Atoms</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
      <a href="/web-llvm/docs/api/structs/llvm/appleacceltabledata/atom">Atom</a>(<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#addd759aec534bc0671ea60c8e9779e5da729ef8a54240d5ae532c7261914cae96">dwarf::DW_ATOM_die_offset</a>, dwarf::DW_FORM_data4),
      <a href="/web-llvm/docs/api/structs/llvm/appleacceltabledata/atom">Atom</a>(<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#addd759aec534bc0671ea60c8e9779e5da297d590afe629760c5523b1a3e907941">dwarf::DW_ATOM_die_tag</a>, dwarf::DW_FORM_data2),
      <a href="/web-llvm/docs/api/structs/llvm/appleacceltabledata/atom">Atom</a>(5, dwarf::DW_FORM_data1), <a href="/web-llvm/docs/api/structs/llvm/appleacceltabledata/atom">Atom</a>(6, dwarf::DW_FORM_data4)}
</div>
</dd>
</dl>

<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
