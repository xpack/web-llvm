---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/appleacceltablestaticoffsetdata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AppleAccelTableStaticOffsetData` Class

<p>Accelerator table data implementation for simple Apple accelerator tables with a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset but no actual <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> pointer. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AppleAccelTableStaticOffsetData { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">llvm/CodeGen/AccelTable.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/appleacceltabledata">AppleAccelTableData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A base class for different implementations of Data classes for Apple Accelerator Tables. <a href="/web-llvm/docs/api/classes/llvm/appleacceltabledata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/appleacceltablestatictypedata">AppleAccelTableStaticTypeData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accelerator table data implementation for type accelerator tables with a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset but no actual <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> pointer. <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestatictypedata/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a474aad442f170882408cc88cfe6b21f2">AppleAccelTableStaticOffsetData</a> (uint32_t Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab32b14df362967475934a4c132436447">emit</a> (AsmPrinter *Asm) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad455e60f8af04dd3977666f502a576b7">print</a> (raw_ostream &amp;OS) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad971625c2fcec3d0dd871103b2035db0">order</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8db3b34af8c367f201cfbcebf5c3ef66">Offset</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dfaec5ef310f5679f919f2913580c39">Atoms</a>[] = ...</td>
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

<p>Accelerator table data implementation for simple Apple accelerator tables with a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset but no actual <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> pointer.</p>

<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AppleAccelTableStaticOffsetData() {#a474aad442f170882408cc88cfe6b21f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AppleAccelTableStaticOffsetData::AppleAccelTableStaticOffsetData (uint32_t Offset)</td>
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



<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Reference <a href="#a8db3b34af8c367f201cfbcebf5c3ef66">Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestatictypedata/#aec7a18e166c380de4e908418550d72f4">llvm::AppleAccelTableStaticTypeData::AppleAccelTableStaticTypeData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#ab32b14df362967475934a4c132436447}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AppleAccelTableStaticOffsetData::emit (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * Asm)</td>
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



<p>Declaration at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>, definition at line 736 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a>.</p>


<p>Reference <a href="#a8db3b34af8c367f201cfbcebf5c3ef66">Offset</a>.</p>

</div>
</div>

### print() {#ad455e60f8af04dd3977666f502a576b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AppleAccelTableStaticOffsetData::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Declaration at line 518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>, definition at line 826 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a>.</p>


<p>Reference <a href="#a8db3b34af8c367f201cfbcebf5c3ef66">Offset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### order() {#ad971625c2fcec3d0dd871103b2035db0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AppleAccelTableStaticOffsetData::order ()</td>
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



<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Reference <a href="#a8db3b34af8c367f201cfbcebf5c3ef66">Offset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Offset {#a8db3b34af8c367f201cfbcebf5c3ef66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AppleAccelTableStaticOffsetData::Offset</td>
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



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Referenced by <a href="#a474aad442f170882408cc88cfe6b21f2">AppleAccelTableStaticOffsetData</a>, <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestatictypedata/#aec7a18e166c380de4e908418550d72f4">llvm::AppleAccelTableStaticTypeData::AppleAccelTableStaticTypeData</a>, <a href="#ab32b14df362967475934a4c132436447">emit</a>, <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestatictypedata/#a1906d67b9f9f768ad574e6482f10a9a8">llvm::AppleAccelTableStaticTypeData::emit</a>, <a href="#ad971625c2fcec3d0dd871103b2035db0">order</a>, <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestatictypedata/#a5f714be5c9560fd0049ad7eb741e7b76">llvm::AppleAccelTableStaticTypeData::order</a>, <a href="#ad455e60f8af04dd3977666f502a576b7">print</a> and <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestatictypedata/#a227eec93999866de3d2938c4852188c8">llvm::AppleAccelTableStaticTypeData::print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### Atoms {#a7dfaec5ef310f5679f919f2913580c39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AppleAccelTableData::Atom AppleAccelTableStaticOffsetData::Atoms</td>
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
      <a href="/web-llvm/docs/api/structs/llvm/appleacceltabledata/atom">Atom</a>(<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#addd759aec534bc0671ea60c8e9779e5da729ef8a54240d5ae532c7261914cae96">dwarf::DW_ATOM_die_offset</a>, dwarf::DW_FORM_data4)}
</div>
</dd>
</dl>

<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
