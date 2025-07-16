---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/unions/llvm/globalvaluesummaryinfo/nameorgv
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - union

---

<div class="doxyPage">

# The `NameOrGV` Union Reference



## Declaration

<div class="doxyDeclaration">
union llvm::GlobalValueSummaryInfo::NameOrGV { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">llvm/IR/ModuleSummaryIndex.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98970915dfaf40ca34d42f217b91316f">NameOrGV</a> (bool HaveGVs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a4bce26dd4a1eb0f4c7a629dc600508">GV</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> corresponding to this summary. <a href="#a5a4bce26dd4a1eb0f4c7a629dc600508">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a631e4319a528f18fac78c07744da2d69">Name</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Summary string representation. <a href="#a631e4319a528f18fac78c07744da2d69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NameOrGV() {#a98970915dfaf40ca34d42f217b91316f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GlobalValueSummaryInfo::NameOrGV::NameOrGV (bool HaveGVs)</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>References <a href="#a5a4bce26dd4a1eb0f4c7a629dc600508">GV</a> and <a href="#a631e4319a528f18fac78c07744da2d69">Name</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### GV {#a5a4bce26dd4a1eb0f4c7a629dc600508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GlobalValue* llvm::GlobalValueSummaryInfo::NameOrGV::GV</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> corresponding to this summary.</p>


<p>This is only used in per-module summaries and when the IR is available. E.g. when module analysis is being run, or when parsing both the IR and the summary from assembly.</p>


<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="#a98970915dfaf40ca34d42f217b91316f">NameOrGV</a>.</p>

</div>
</div>

### Name {#a631e4319a528f18fac78c07744da2d69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::GlobalValueSummaryInfo::NameOrGV::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Summary string representation.</p>


<p>This <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> points to BC module string table and is valid until module data is stored in memory. This is guaranteed to happen until runThinLTOBackend function is called, so it is safe to use this field during thin link. This field is only valid if summary index was loaded from BC file.</p>


<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="#a98970915dfaf40ca34d42f217b91316f">NameOrGV</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this union was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
