---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/appleacceltabletypedata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AppleAccelTableTypeData` Class

<p>Accelerator table data implementation for Apple type accelerator tables. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AppleAccelTableTypeData { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">llvm/CodeGen/AccelTable.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/appleacceltableoffsetdata">AppleAccelTableOffsetData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accelerator table data implementation for simple Apple accelerator tables with just a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> reference. <a href="/web-llvm/docs/api/classes/llvm/appleacceltableoffsetdata/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b78fa5fee16fd7fb3ad74624496ab83">AppleAccelTableTypeData</a> (const DIE &amp;D)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c96e96e3cf470498dedcd3c6d2da80a">emit</a> (AsmPrinter *Asm) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1980488378a856d388e27545744bc08f">print</a> (raw_ostream &amp;OS) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a956632a8c1a476d04a2dc17e9759a803">Atoms</a>[] = ...</td>
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

<p>Accelerator table data implementation for Apple type accelerator tables.</p>

<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AppleAccelTableTypeData() {#a4b78fa5fee16fd7fb3ad74624496ab83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AppleAccelTableTypeData::AppleAccelTableTypeData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; D)</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/appleacceltableoffsetdata/#aec1afde332ea9cf1e83885d2be0f32a1">llvm::AppleAccelTableOffsetData::AppleAccelTableOffsetData</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#a4c96e96e3cf470498dedcd3c6d2da80a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AppleAccelTableTypeData::emit (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * Asm)</td>
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



<p>Declaration at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>, definition at line 728 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/appleacceltableoffsetdata/#abb194e2c285b3e53c47eef9244bef57f">llvm::AppleAccelTableOffsetData::Die</a>.</p>

</div>
</div>

### print() {#a1980488378a856d388e27545744bc08f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AppleAccelTableTypeData::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Declaration at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>, definition at line 821 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/appleacceltableoffsetdata/#abb194e2c285b3e53c47eef9244bef57f">llvm::AppleAccelTableOffsetData::Die</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gaf17a843ca40c67635b127ba50ad45bdf">llvm::dwarf::TagString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### Atoms {#a956632a8c1a476d04a2dc17e9759a803}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AppleAccelTableData::Atom AppleAccelTableTypeData::Atoms</td>
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
      <a href="/web-llvm/docs/api/structs/llvm/appleacceltabledata/atom">Atom</a>(<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#addd759aec534bc0671ea60c8e9779e5da004bb656ad7f6bb23d888a35111de0a8">dwarf::DW_ATOM_type_flags</a>, dwarf::DW_FORM_data1)}
</div>
</dd>
</dl>

<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>

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
