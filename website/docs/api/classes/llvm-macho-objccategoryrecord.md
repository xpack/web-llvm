---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/macho/objccategoryrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ObjCCategoryRecord` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MachO::ObjCCategoryRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">llvm/TextAPI/Record.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/objccontainerrecord">ObjCContainerRecord</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaca0ca74b7c3089e4c81252e8b4d75c8">ObjCCategoryRecord</a> (StringRef ClassToExtend, StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab882a886d176a5ce72b39c822deffff1">getSuperClassName</a> () const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3751374f19f84f3d90d99174f419778a">ClassToExtend</a></td>
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


<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ObjCCategoryRecord() {#aaca0ca74b7c3089e4c81252e8b4d75c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::ObjCCategoryRecord::ObjCCategoryRecord (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ClassToExtend, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/macho/record/#ae1da3190ebbff030b4f205be49606ec6">llvm::MachO::Record::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/objccontainerrecord/#a97c5d891019f0f22072bf593df1545c0">llvm::MachO::ObjCContainerRecord::ObjCContainerRecord</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ffa88183b946cc5f0e8c96b2e66e1c74a7e">llvm::MachO::Unknown</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getSuperClassName() {#ab882a886d176a5ce72b39c822deffff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MachO::ObjCCategoryRecord::getSuperClassName ()</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/symbolconverter/#a4821f93278208c868cd078fb8afc2746">llvm::MachO::SymbolConverter::visitObjCCategory</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ClassToExtend {#a3751374f19f84f3d90d99174f419778a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MachO::ObjCCategoryRecord::ClassToExtend</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
