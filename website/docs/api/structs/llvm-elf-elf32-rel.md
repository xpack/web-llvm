---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/elf/elf32-rel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Elf32_Rel` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::ELF::Elf32_Rel { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">llvm/BinaryFormat/ELF.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/elf/#a52f624470271b7177f8be9dd519daf61">Elf32_Word</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2f4b957de000895773388aaafa7cc04">getSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a660b0f39c531e054b8878c3adb127ef0">getType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfd89c89fb8c16ee4556d3ac551c9388">setSymbol</a> (Elf32_Word s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4639f525cdb6a98bae0c044805b31038">setType</a> (unsigned char t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9337e7fd9b40c79c9325dc86c9296e69">setSymbolAndType</a> (Elf32_Word s, unsigned char t)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/elf/#aa30851b22189ba371d10af2dd3703c35">Elf32_Addr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2da7804d67a9c1d4ed3d20569e882672">r_offset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/elf/#a52f624470271b7177f8be9dd519daf61">Elf32_Word</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5644f3fe07048bb6d31f2325173ee37">r_info</a></td>
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


<p>Definition at line 1409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">ELF.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getSymbol() {#aa2f4b957de000895773388aaafa7cc04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Elf32_Word llvm::ELF::Elf32_Rel::getSymbol ()</td>
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



<p>Definition at line 1415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">ELF.h</a>.</p>


<p>Reference <a href="#ad5644f3fe07048bb6d31f2325173ee37">r_info</a>.</p>


<p>Referenced by <a href="#a4639f525cdb6a98bae0c044805b31038">setType</a>.</p>

</div>
</div>

### getType() {#a660b0f39c531e054b8878c3adb127ef0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::ELF::Elf32_Rel::getType ()</td>
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



<p>Definition at line 1416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">ELF.h</a>.</p>


<p>Reference <a href="#ad5644f3fe07048bb6d31f2325173ee37">r_info</a>.</p>


<p>Referenced by <a href="#abfd89c89fb8c16ee4556d3ac551c9388">setSymbol</a>.</p>

</div>
</div>

### setSymbol() {#abfd89c89fb8c16ee4556d3ac551c9388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ELF::Elf32_Rel::setSymbol (<a href="/web-llvm/docs/api/namespaces/llvm/elf/#a52f624470271b7177f8be9dd519daf61">Elf32_Word</a> s)</td>
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



<p>Definition at line 1417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">ELF.h</a>.</p>


<p>References <a href="#a660b0f39c531e054b8878c3adb127ef0">getType</a> and <a href="#a9337e7fd9b40c79c9325dc86c9296e69">setSymbolAndType</a>.</p>

</div>
</div>

### setSymbolAndType() {#a9337e7fd9b40c79c9325dc86c9296e69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ELF::Elf32_Rel::setSymbolAndType (<a href="/web-llvm/docs/api/namespaces/llvm/elf/#a52f624470271b7177f8be9dd519daf61">Elf32_Word</a> s, unsigned char t)</td>
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



<p>Definition at line 1419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">ELF.h</a>.</p>


<p>Reference <a href="#ad5644f3fe07048bb6d31f2325173ee37">r_info</a>.</p>


<p>Referenced by <a href="#abfd89c89fb8c16ee4556d3ac551c9388">setSymbol</a> and <a href="#a4639f525cdb6a98bae0c044805b31038">setType</a>.</p>

</div>
</div>

### setType() {#a4639f525cdb6a98bae0c044805b31038}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ELF::Elf32_Rel::setType (unsigned char t)</td>
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



<p>Definition at line 1418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">ELF.h</a>.</p>


<p>References <a href="#aa2f4b957de000895773388aaafa7cc04">getSymbol</a> and <a href="#a9337e7fd9b40c79c9325dc86c9296e69">setSymbolAndType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### r\_info {#ad5644f3fe07048bb6d31f2325173ee37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Elf32_Word llvm::ELF::Elf32_Rel::r_info</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">ELF.h</a>.</p>


<p>Referenced by <a href="#aa2f4b957de000895773388aaafa7cc04">getSymbol</a>, <a href="#a660b0f39c531e054b8878c3adb127ef0">getType</a> and <a href="#a9337e7fd9b40c79c9325dc86c9296e69">setSymbolAndType</a>.</p>

</div>
</div>

### r\_offset {#a2da7804d67a9c1d4ed3d20569e882672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Elf32_Addr llvm::ELF::Elf32_Rel::r_offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">ELF.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">ELF.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
