---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf5acceltabledata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DWARF5AccelTableData` Class Reference

<p>The Data class implementation for DWARF v5 accelerator table. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DWARF5AccelTableData { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">llvm/CodeGen/AccelTable.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/acceltabledata">AccelTableData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface which the different types of accelerator table data have to conform. <a href="/web-llvm/docs/api/classes/llvm/acceltabledata/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78053200052bb0909eac065e93094825">DWARF5AccelTableData</a> (const DIE &amp;Die, const uint32_t UnitID, const bool IsTU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0ac3049a2aa30d7a9c74ff0f7613f7b">DWARF5AccelTableData</a> (const uint64_t DieOffset, const std::optional&lt; uint64_t &gt; DefiningParentOffset, const unsigned DieTag, const unsigned UnitID, const bool IsTU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1baa6c82605b0537f9c4d34da8fbf109">print</a> (raw_ostream &amp;OS) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc1cffe1cdac849a8baf1bf17249bafe">getDieOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetandunitid">OffsetAndUnitID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91679cca53e558f5f9f9225afbe85165">getDieOffsetAndUnitID</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2819547388eeadf1d4e7104ea3302815">getDieTag</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a804c37e71c663a8cd9fb16b9c66ed125">getUnitID</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3472f9fc9f9ce96e95bad5605afff8f">isTU</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a313db586594d446033e60acebaff5a35">normalizeDIEToOffset</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd69c284c8fcc0b18863ec94cf588194">isNormalized</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5946ec196fb5c8b22125575a809d0003">getParentDieOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/offsetandunitid">OffsetAndUnitID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a319251aa85f6b1bc1d83668d4c33c089">getParentDieOffsetAndUnitID</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89019ec3287b942c36de37fd05b12676">setAbbrevNumber</a> (uint16_t AbbrevNum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets AbbrevIndex for an Entry. <a href="#a89019ec3287b942c36de37fd05b12676">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb05871493e11f32306901cd25e84139">getAbbrevNumber</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns AbbrevIndex for an Entry. <a href="#abb05871493e11f32306901cd25e84139">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c3a1a73fae2ac27c8949e24d5cd4390">order</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::variant&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *, uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a70ff4d180d8a54a1b224ef6f09ca67">OffsetVal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af347e9fc97c776d06d16ac55ea4351ac">ParentOffset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa59eddbdbc459635accf804e0caf2c98">DieTag</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a590610cf5e7dd4c873261831ec19fb75">AbbrevNumber</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a094ad3437ca6e5834a72a9df7d950423">IsTU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d8010dcda0ad853b5041ef5ff19c5e1">UnitID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a121a98a4d80d3befdfba30b09b684296">hash</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa762f32385fad86a276bd941c5844a96">getDefiningParentDieOffset</a> (const DIE &amp;Die)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">Die</span> has a non-null parent and the parent is not a declaration, return its offset. <a href="#aa762f32385fad86a276bd941c5844a96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The Data class implementation for DWARF v5 accelerator table.</p>


<p>Unlike the Apple Data classes, this class is just a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> wrapper, and does not know to serialize itself. The complete serialization logic is in the emitDWARF5AccelTable function.</p>


<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DWARF5AccelTableData() {#a78053200052bb0909eac065e93094825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARF5AccelTableData::DWARF5AccelTableData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t UnitID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool IsTU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>, definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a>.</p>


<p>References <a href="#a590610cf5e7dd4c873261831ec19fb75">AbbrevNumber</a>, <a href="#aa59eddbdbc459635accf804e0caf2c98">DieTag</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a8094520fe3fe9f3967fe72b7266a2f68">getTag</a>, <a href="#a094ad3437ca6e5834a72a9df7d950423">IsTU</a>, <a href="#a6a70ff4d180d8a54a1b224ef6f09ca67">OffsetVal</a> and <a href="#a8d8010dcda0ad853b5041ef5ff19c5e1">UnitID</a>.</p>

</div>
</div>

### DWARF5AccelTableData() {#ab0ac3049a2aa30d7a9c74ff0f7613f7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARF5AccelTableData::DWARF5AccelTableData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t DieOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; uint64_t &gt; DefiningParentOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned DieTag, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned UnitID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool IsTU)</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>References <a href="#a590610cf5e7dd4c873261831ec19fb75">AbbrevNumber</a>, <a href="#aa59eddbdbc459635accf804e0caf2c98">DieTag</a>, <a href="#a094ad3437ca6e5834a72a9df7d950423">IsTU</a>, <a href="#a6a70ff4d180d8a54a1b224ef6f09ca67">OffsetVal</a>, <a href="#af347e9fc97c776d06d16ac55ea4351ac">ParentOffset</a> and <a href="#a8d8010dcda0ad853b5041ef5ff19c5e1">UnitID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAbbrevNumber() {#abb05871493e11f32306901cd25e84139}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::DWARF5AccelTableData::getAbbrevNumber ()</td>
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

<p>Returns AbbrevIndex for an Entry.</p>

<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Reference <a href="#a590610cf5e7dd4c873261831ec19fb75">AbbrevNumber</a>.</p>

</div>
</div>

### getDieOffset() {#adc1cffe1cdac849a8baf1bf17249bafe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARF5AccelTableData::getDieOffset ()</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abd69c284c8fcc0b18863ec94cf588194">isNormalized</a> and <a href="#a6a70ff4d180d8a54a1b224ef6f09ca67">OffsetVal</a>.</p>


<p>Referenced by <a href="#a91679cca53e558f5f9f9225afbe85165">getDieOffsetAndUnitID</a>, <a href="#a8c3a1a73fae2ac27c8949e24d5cd4390">order</a> and <a href="#a1baa6c82605b0537f9c4d34da8fbf109">print</a>.</p>

</div>
</div>

### getDieOffsetAndUnitID() {#a91679cca53e558f5f9f9225afbe85165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetAndUnitID llvm::DWARF5AccelTableData::getDieOffsetAndUnitID ()</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>References <a href="#adc1cffe1cdac849a8baf1bf17249bafe">getDieOffset</a>, <a href="#a804c37e71c663a8cd9fb16b9c66ed125">getUnitID</a> and <a href="#ac3472f9fc9f9ce96e95bad5605afff8f">isTU</a>.</p>

</div>
</div>

### getDieTag() {#a2819547388eeadf1d4e7104ea3302815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARF5AccelTableData::getDieTag ()</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Reference <a href="#aa59eddbdbc459635accf804e0caf2c98">DieTag</a>.</p>


<p>Referenced by <a href="#a1baa6c82605b0537f9c4d34da8fbf109">print</a>.</p>

</div>
</div>

### getParentDieOffset() {#a5946ec196fb5c8b22125575a809d0003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::DWARF5AccelTableData::getParentDieOffset ()</td>
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



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Reference <a href="#a319251aa85f6b1bc1d83668d4c33c089">getParentDieOffsetAndUnitID</a>.</p>

</div>
</div>

### getParentDieOffsetAndUnitID() {#a319251aa85f6b1bc1d83668d4c33c089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; OffsetAndUnitID &gt; llvm::DWARF5AccelTableData::getParentDieOffsetAndUnitID ()</td>
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



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a804c37e71c663a8cd9fb16b9c66ed125">getUnitID</a>, <a href="#abd69c284c8fcc0b18863ec94cf588194">isNormalized</a>, <a href="#ac3472f9fc9f9ce96e95bad5605afff8f">isTU</a> and <a href="#af347e9fc97c776d06d16ac55ea4351ac">ParentOffset</a>.</p>


<p>Referenced by <a href="#a5946ec196fb5c8b22125575a809d0003">getParentDieOffset</a>.</p>

</div>
</div>

### getUnitID() {#a804c37e71c663a8cd9fb16b9c66ed125}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARF5AccelTableData::getUnitID ()</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Reference <a href="#a8d8010dcda0ad853b5041ef5ff19c5e1">UnitID</a>.</p>


<p>Referenced by <a href="#a91679cca53e558f5f9f9225afbe85165">getDieOffsetAndUnitID</a> and <a href="#a319251aa85f6b1bc1d83668d4c33c089">getParentDieOffsetAndUnitID</a>.</p>

</div>
</div>

### isNormalized() {#abd69c284c8fcc0b18863ec94cf588194}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARF5AccelTableData::isNormalized ()</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Reference <a href="#a6a70ff4d180d8a54a1b224ef6f09ca67">OffsetVal</a>.</p>


<p>Referenced by <a href="#adc1cffe1cdac849a8baf1bf17249bafe">getDieOffset</a>, <a href="#a319251aa85f6b1bc1d83668d4c33c089">getParentDieOffsetAndUnitID</a> and <a href="#a313db586594d446033e60acebaff5a35">normalizeDIEToOffset</a>.</p>

</div>
</div>

### isTU() {#ac3472f9fc9f9ce96e95bad5605afff8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARF5AccelTableData::isTU ()</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Reference <a href="#a094ad3437ca6e5834a72a9df7d950423">IsTU</a>.</p>


<p>Referenced by <a href="#a91679cca53e558f5f9f9225afbe85165">getDieOffsetAndUnitID</a> and <a href="#a319251aa85f6b1bc1d83668d4c33c089">getParentDieOffsetAndUnitID</a>.</p>

</div>
</div>

### normalizeDIEToOffset() {#a313db586594d446033e60acebaff5a35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARF5AccelTableData::normalizeDIEToOffset ()</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa762f32385fad86a276bd941c5844a96">getDefiningParentDieOffset</a>, <a href="#abd69c284c8fcc0b18863ec94cf588194">isNormalized</a>, <a href="#a6a70ff4d180d8a54a1b224ef6f09ca67">OffsetVal</a> and <a href="#af347e9fc97c776d06d16ac55ea4351ac">ParentOffset</a>.</p>

</div>
</div>

### print() {#a1baa6c82605b0537f9c4d34da8fbf109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARF5AccelTableData::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Declaration at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>, definition at line 812 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a>.</p>


<p>References <a href="#adc1cffe1cdac849a8baf1bf17249bafe">getDieOffset</a>, <a href="#a2819547388eeadf1d4e7104ea3302815">getDieTag</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gaf17a843ca40c67635b127ba50ad45bdf">llvm::dwarf::TagString</a>.</p>

</div>
</div>

### setAbbrevNumber() {#a89019ec3287b942c36de37fd05b12676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARF5AccelTableData::setAbbrevNumber (uint16_t AbbrevNum)</td>
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

<p>Sets AbbrevIndex for an Entry.</p>

<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Reference <a href="#a590610cf5e7dd4c873261831ec19fb75">AbbrevNumber</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### order() {#a8c3a1a73fae2ac27c8949e24d5cd4390}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARF5AccelTableData::order ()</td>
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



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Reference <a href="#adc1cffe1cdac849a8baf1bf17249bafe">getDieOffset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AbbrevNumber {#a590610cf5e7dd4c873261831ec19fb75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARF5AccelTableData::AbbrevNumber</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Referenced by <a href="#a78053200052bb0909eac065e93094825">DWARF5AccelTableData</a>, <a href="#ab0ac3049a2aa30d7a9c74ff0f7613f7b">DWARF5AccelTableData</a>, <a href="#abb05871493e11f32306901cd25e84139">getAbbrevNumber</a> and <a href="#a89019ec3287b942c36de37fd05b12676">setAbbrevNumber</a>.</p>

</div>
</div>

### DieTag {#aa59eddbdbc459635accf804e0caf2c98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARF5AccelTableData::DieTag</td>
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



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Referenced by <a href="#a78053200052bb0909eac065e93094825">DWARF5AccelTableData</a>, <a href="#ab0ac3049a2aa30d7a9c74ff0f7613f7b">DWARF5AccelTableData</a> and <a href="#a2819547388eeadf1d4e7104ea3302815">getDieTag</a>.</p>

</div>
</div>

### IsTU {#a094ad3437ca6e5834a72a9df7d950423}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARF5AccelTableData::IsTU</td>
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



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Referenced by <a href="#a78053200052bb0909eac065e93094825">DWARF5AccelTableData</a>, <a href="#ab0ac3049a2aa30d7a9c74ff0f7613f7b">DWARF5AccelTableData</a> and <a href="#ac3472f9fc9f9ce96e95bad5605afff8f">isTU</a>.</p>

</div>
</div>

### OffsetVal {#a6a70ff4d180d8a54a1b224ef6f09ca67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::variant&lt;const DIE *, uint64_t&gt; llvm::DWARF5AccelTableData::OffsetVal</td>
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



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Referenced by <a href="#a78053200052bb0909eac065e93094825">DWARF5AccelTableData</a>, <a href="#ab0ac3049a2aa30d7a9c74ff0f7613f7b">DWARF5AccelTableData</a>, <a href="#adc1cffe1cdac849a8baf1bf17249bafe">getDieOffset</a>, <a href="#abd69c284c8fcc0b18863ec94cf588194">isNormalized</a> and <a href="#a313db586594d446033e60acebaff5a35">normalizeDIEToOffset</a>.</p>

</div>
</div>

### ParentOffset {#af347e9fc97c776d06d16ac55ea4351ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::DWARF5AccelTableData::ParentOffset</td>
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



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Referenced by <a href="#ab0ac3049a2aa30d7a9c74ff0f7613f7b">DWARF5AccelTableData</a>, <a href="#a319251aa85f6b1bc1d83668d4c33c089">getParentDieOffsetAndUnitID</a> and <a href="#a313db586594d446033e60acebaff5a35">normalizeDIEToOffset</a>.</p>

</div>
</div>

### UnitID {#a8d8010dcda0ad853b5041ef5ff19c5e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARF5AccelTableData::UnitID</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Referenced by <a href="#a78053200052bb0909eac065e93094825">DWARF5AccelTableData</a>, <a href="#ab0ac3049a2aa30d7a9c74ff0f7613f7b">DWARF5AccelTableData</a> and <a href="#a804c37e71c663a8cd9fb16b9c66ed125">getUnitID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getDefiningParentDieOffset() {#aa762f32385fad86a276bd941c5844a96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARF5AccelTableData::getDefiningParentDieOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If <span class="doxyComputerOutput">Die</span> has a non-null parent and the parent is not a declaration, return its offset.</p>

<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>, definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/die/#a008bf8f3472eb0014e766bac06fbe537">llvm::DIE::findAttribute</a> and <a href="/web-llvm/docs/api/classes/llvm/die/#af985c8a58986e45114a8c3e6cbf0504a">llvm::DIE::getParent</a>.</p>


<p>Referenced by <a href="#a313db586594d446033e60acebaff5a35">normalizeDIEToOffset</a>.</p>

</div>
</div>

### hash() {#a121a98a4d80d3befdfba30b09b684296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARF5AccelTableData::hash (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/acceltable-h">AccelTable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aaf688be573d89d297c2971a2bf1ce294">llvm::caseFoldingDjbHash</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
