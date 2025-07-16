---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/aacacheloc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AACacheLoc` Struct Reference

<p>Cache key for <a href="/web-llvm/docs/api/classes/llvm/basicaa">BasicAA</a> results. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::AACacheLoc { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1380e153bffda56d149786dbfb868265">PtrTy</a> = <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 1, bool &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75934dddd565631124642e9235aae47a">AACacheLoc</a> (PtrTy Ptr, LocationSize Size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a447182e0ebd44636b8f0bc5b3490e96d">AACacheLoc</a> (const Value *Ptr, LocationSize Size, bool MayBeCrossIteration)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1380e153bffda56d149786dbfb868265">PtrTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41a01d0441a600ac9f5052b045d825b5">Ptr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64da0873855d196bed941696c83fc63a">Size</a></td>
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

<p>Cache key for <a href="/web-llvm/docs/api/classes/llvm/basicaa">BasicAA</a> results.</p>


<p>It only includes the pointer and size from <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a>, as <a href="/web-llvm/docs/api/classes/llvm/basicaa">BasicAA</a> is AATags independent. Additionally, it includes the value of MayBeCrossIteration, which may affect <a href="/web-llvm/docs/api/classes/llvm/basicaa">BasicAA</a> results.</p>


<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### PtrTy {#a1380e153bffda56d149786dbfb868265}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AACacheLoc::PtrTy =  PointerIntPair&lt;const Value *, 1, bool&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AACacheLoc() {#a75934dddd565631124642e9235aae47a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AACacheLoc::AACacheLoc (<a href="#a1380e153bffda56d149786dbfb868265">PtrTy</a> Ptr, <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a> Size)</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<p>References <a href="#a41a01d0441a600ac9f5052b045d825b5">Ptr</a> and <a href="#a64da0873855d196bed941696c83fc63a">Size</a>.</p>

</div>
</div>

### AACacheLoc() {#a447182e0ebd44636b8f0bc5b3490e96d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AACacheLoc::AACacheLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a> Size, bool MayBeCrossIteration)</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<p>References <a href="#a41a01d0441a600ac9f5052b045d825b5">Ptr</a> and <a href="#a64da0873855d196bed941696c83fc63a">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Ptr {#a41a01d0441a600ac9f5052b045d825b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PtrTy llvm::AACacheLoc::Ptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<p>Referenced by <a href="#a447182e0ebd44636b8f0bc5b3490e96d">AACacheLoc</a>, <a href="#a75934dddd565631124642e9235aae47a">AACacheLoc</a> and <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-00c712b9f8119dbcd9df11fd9c730cfe/#af571d431080d9ae43473571163bf9739">llvm::DenseMapInfo&lt; AACacheLoc &gt;::getHashValue</a>.</p>

</div>
</div>

### Size {#a64da0873855d196bed941696c83fc63a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationSize llvm::AACacheLoc::Size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<p>Referenced by <a href="#a447182e0ebd44636b8f0bc5b3490e96d">AACacheLoc</a>, <a href="#a75934dddd565631124642e9235aae47a">AACacheLoc</a> and <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-00c712b9f8119dbcd9df11fd9c730cfe/#af571d431080d9ae43473571163bf9739">llvm::DenseMapInfo&lt; AACacheLoc &gt;::getHashValue</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
