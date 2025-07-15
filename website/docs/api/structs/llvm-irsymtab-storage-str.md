---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/irsymtab/storage/str
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Str` Struct Reference

<p>A reference to a string in the string table. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::irsymtab::storage::Str { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">llvm/Object/IRSymtab.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02a37f04a82457e3c3658f3f1c046e0f">get</a> (StringRef Strtab) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/irsymtab/storage/#ad2b23175625fe2187c025e9f539189a1">Word</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16bef735d0a180313a385ad5a3b2e7ed">Offset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/irsymtab/storage/#ad2b23175625fe2187c025e9f539189a1">Word</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a83ee57679792dc5d3af311350de08">Size</a></td>
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

<p>A reference to a string in the string table.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### get() {#a02a37f04a82457e3c3658f3f1c046e0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::irsymtab::storage::Str::get (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Strtab)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="#a16bef735d0a180313a385ad5a3b2e7ed">Offset</a> and <a href="#ab9a83ee57679792dc5d3af311350de08">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Offset {#a16bef735d0a180313a385ad5a3b2e7ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Word llvm::irsymtab::storage::Str::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>Referenced by <a href="#a02a37f04a82457e3c3658f3f1c046e0f">get</a> and <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a488144c223bdc29e3ba937ac31835b5f">anonymous{IRSymtab.cpp}::Builder::setStr</a>.</p>

</div>
</div>

### Size {#ab9a83ee57679792dc5d3af311350de08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Word llvm::irsymtab::storage::Str::Size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>Referenced by <a href="#a02a37f04a82457e3c3658f3f1c046e0f">get</a> and <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a488144c223bdc29e3ba937ac31835b5f">anonymous{IRSymtab.cpp}::Builder::setStr</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
