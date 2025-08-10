---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/elf/elf32-rela
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Elf32_Rela` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::ELF::Elf32_Rela { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">llvm/BinaryFormat/ELF.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/elf/#a52f624470271b7177f8be9dd519daf61">Elf32_Word</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64ccc0f2888178676c576fdff94e93cd">getSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc5e815281893cc8beeaa68a189fd26e">getType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf113484fb851f1c57bf0a2bc371560a">setSymbol</a> (Elf32_Word s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23ea15574c880d52a8c56cd177a026c0">setType</a> (unsigned char t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada6e1f1789bb65d344b25f7c1eff1b94">setSymbolAndType</a> (Elf32_Word s, unsigned char t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42be90281ba7d1f55f285a1a344abc77">r_offset</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35fe5be6ddd3ff8a32cb48749f573bbe">r_info</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/elf/#a94d1340d745cf0686226fd30e0c22e61">Elf32_Sword</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac54eea298e917d307107fa527a0d2ccc">r_addend</a></td>
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


<p>Definition at line 1425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">ELF.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getSymbol() {#a64ccc0f2888178676c576fdff94e93cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Elf32_Word llvm::ELF::Elf32_Rela::getSymbol ()</td>
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



<p>Definition at line 1432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">ELF.h</a>.</p>


<p>Reference <a href="#a35fe5be6ddd3ff8a32cb48749f573bbe">r_info</a>.</p>


<p>Referenced by <a href="#a23ea15574c880d52a8c56cd177a026c0">setType</a>.</p>

</div>
</div>

### getType() {#adc5e815281893cc8beeaa68a189fd26e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::ELF::Elf32_Rela::getType ()</td>
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



<p>Definition at line 1433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">ELF.h</a>.</p>


<p>Reference <a href="#a35fe5be6ddd3ff8a32cb48749f573bbe">r_info</a>.</p>


<p>Referenced by <a href="#abf113484fb851f1c57bf0a2bc371560a">setSymbol</a>.</p>

</div>
</div>

### setSymbol() {#abf113484fb851f1c57bf0a2bc371560a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ELF::Elf32_Rela::setSymbol (<a href="/web-llvm/docs/api/namespaces/llvm/elf/#a52f624470271b7177f8be9dd519daf61">Elf32_Word</a> s)</td>
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



<p>Definition at line 1434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">ELF.h</a>.</p>


<p>References <a href="#adc5e815281893cc8beeaa68a189fd26e">getType</a> and <a href="#ada6e1f1789bb65d344b25f7c1eff1b94">setSymbolAndType</a>.</p>

</div>
</div>

### setSymbolAndType() {#ada6e1f1789bb65d344b25f7c1eff1b94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ELF::Elf32_Rela::setSymbolAndType (<a href="/web-llvm/docs/api/namespaces/llvm/elf/#a52f624470271b7177f8be9dd519daf61">Elf32_Word</a> s, unsigned char t)</td>
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



<p>Definition at line 1436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">ELF.h</a>.</p>


<p>Reference <a href="#a35fe5be6ddd3ff8a32cb48749f573bbe">r_info</a>.</p>


<p>Referenced by <a href="#abf113484fb851f1c57bf0a2bc371560a">setSymbol</a>, <a href="#a23ea15574c880d52a8c56cd177a026c0">setType</a> and <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#aa07832cc5201fc524e000dcc171a70e7">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeRelocations</a>.</p>

</div>
</div>

### setType() {#a23ea15574c880d52a8c56cd177a026c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ELF::Elf32_Rela::setType (unsigned char t)</td>
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



<p>Definition at line 1435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">ELF.h</a>.</p>


<p>References <a href="#a64ccc0f2888178676c576fdff94e93cd">getSymbol</a> and <a href="#ada6e1f1789bb65d344b25f7c1eff1b94">setSymbolAndType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### r\_addend {#ac54eea298e917d307107fa527a0d2ccc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Elf32_Sword llvm::ELF::Elf32_Rela::r_addend</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">ELF.h</a>.</p>

</div>
</div>

### r\_info {#a35fe5be6ddd3ff8a32cb48749f573bbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Elf32_Word llvm::ELF::Elf32_Rela::r_info</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">ELF.h</a>.</p>


<p>Referenced by <a href="#a64ccc0f2888178676c576fdff94e93cd">getSymbol</a>, <a href="#adc5e815281893cc8beeaa68a189fd26e">getType</a>, <a href="#ada6e1f1789bb65d344b25f7c1eff1b94">setSymbolAndType</a> and <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#aa07832cc5201fc524e000dcc171a70e7">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeRelocations</a>.</p>

</div>
</div>

### r\_offset {#a42be90281ba7d1f55f285a1a344abc77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Elf32_Addr llvm::ELF::Elf32_Rela::r_offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">ELF.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">ELF.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
