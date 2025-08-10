---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/coff/importlookuptableentry32
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ImportLookupTableEntry32` Struct

<p>The PE32 Import Lookup Table. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::COFF::ImportLookupTableEntry32 { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/coff-h">llvm/BinaryFormat/COFF.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8fe2403f60630c5a0ecccbd4b15b98e">isOrdinal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this entry specified by ordinal, or name? <a href="#af8fe2403f60630c5a0ecccbd4b15b98e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed810f14da3149957dc649f1bd401a28">getOrdinal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the ordinal value of this entry. isOrdinal must be true. <a href="#aed810f14da3149957dc649f1bd401a28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfc69415bb516b20be6692a421d4d4d6">setOrdinal</a> (uint16_t o)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the ordinal value and set isOrdinal to true. <a href="#abfc69415bb516b20be6692a421d4d4d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c8cff4db189a501d02cf8ca645a0e39">getHintNameRVA</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the Hint/Name entry RVA. isOrdinal must be false. <a href="#a7c8cff4db189a501d02cf8ca645a0e39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ca59164db9b5d4866f5a977eb583a6f">setHintNameRVA</a> (uint32_t rva)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the Hint/Name entry RVA and set isOrdinal to false. <a href="#a7ca59164db9b5d4866f5a977eb583a6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a243cf5fdf69523240284e3fe19e41b22">data</a></td>
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

<p>The PE32 Import Lookup Table.</p>


<p>There is an array of these for each imported DLL. It represents either the ordinal to import from the target DLL, or a name to lookup and import from the target DLL.</p>


<p>This also happens to be the same format used by the Import Address Table when it is initially written out to the image.</p>


<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/coff-h">COFF.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getHintNameRVA() {#a7c8cff4db189a501d02cf8ca645a0e39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::COFF::ImportLookupTableEntry32::getHintNameRVA ()</td>
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

<p>Get the Hint/Name entry RVA. isOrdinal must be false.</p>

<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/coff-h">COFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a243cf5fdf69523240284e3fe19e41b22">data</a> and <a href="#af8fe2403f60630c5a0ecccbd4b15b98e">isOrdinal</a>.</p>

</div>
</div>

### getOrdinal() {#aed810f14da3149957dc649f1bd401a28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::COFF::ImportLookupTableEntry32::getOrdinal ()</td>
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

<p>Get the ordinal value of this entry. isOrdinal must be true.</p>

<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/coff-h">COFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a243cf5fdf69523240284e3fe19e41b22">data</a> and <a href="#af8fe2403f60630c5a0ecccbd4b15b98e">isOrdinal</a>.</p>

</div>
</div>

### isOrdinal() {#af8fe2403f60630c5a0ecccbd4b15b98e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::COFF::ImportLookupTableEntry32::isOrdinal ()</td>
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

<p>Is this entry specified by ordinal, or name?</p>

<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/coff-h">COFF.h</a>.</p>


<p>Reference <a href="#a243cf5fdf69523240284e3fe19e41b22">data</a>.</p>


<p>Referenced by <a href="#a7c8cff4db189a501d02cf8ca645a0e39">getHintNameRVA</a> and <a href="#aed810f14da3149957dc649f1bd401a28">getOrdinal</a>.</p>

</div>
</div>

### setHintNameRVA() {#a7ca59164db9b5d4866f5a977eb583a6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::COFF::ImportLookupTableEntry32::setHintNameRVA (uint32_t rva)</td>
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

<p>Set the Hint/Name entry RVA and set isOrdinal to false.</p>

<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/coff-h">COFF.h</a>.</p>


<p>Reference <a href="#a243cf5fdf69523240284e3fe19e41b22">data</a>.</p>

</div>
</div>

### setOrdinal() {#abfc69415bb516b20be6692a421d4d4d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::COFF::ImportLookupTableEntry32::setOrdinal (uint16_t o)</td>
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

<p>Set the ordinal value and set isOrdinal to true.</p>

<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/coff-h">COFF.h</a>.</p>


<p>Reference <a href="#a243cf5fdf69523240284e3fe19e41b22">data</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### data {#a243cf5fdf69523240284e3fe19e41b22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::COFF::ImportLookupTableEntry32::data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/coff-h">COFF.h</a>.</p>


<p>Referenced by <a href="#a7c8cff4db189a501d02cf8ca645a0e39">getHintNameRVA</a>, <a href="#aed810f14da3149957dc649f1bd401a28">getOrdinal</a>, <a href="#af8fe2403f60630c5a0ecccbd4b15b98e">isOrdinal</a>, <a href="#a7ca59164db9b5d4866f5a977eb583a6f">setHintNameRVA</a> and <a href="#abfc69415bb516b20be6692a421d4d4d6">setOrdinal</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/coff-h">COFF.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
