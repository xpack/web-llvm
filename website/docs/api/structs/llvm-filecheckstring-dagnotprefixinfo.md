---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/filecheckstring/dagnotprefixinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DagNotPrefixInfo` Struct Reference

<p>Hold the information about the DAG/NOT strings in the program, which are not explicitly stored otherwise. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::FileCheckString::DagNotPrefixInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheck/FileCheckImpl.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7efa47116ffbd9de7eccc2c284c7b87">DagNotPrefixInfo</a> (const Pattern &amp;P, StringRef S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01523f461c4e79173b9308569bf7185e">DagNotPat</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c9db6f087ae1282b589734781636cd6">DagNotPrefix</a></td>
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

<p>Hold the information about the DAG/NOT strings in the program, which are not explicitly stored otherwise.</p>


<p>This allows for better and more accurate diagnostic messages.</p>


<p>Definition at line 829 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DagNotPrefixInfo() {#af7efa47116ffbd9de7eccc2c284c7b87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FileCheckString::DagNotPrefixInfo::DagNotPrefixInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> &amp; P, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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



<p>Definition at line 833 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<p>References <a href="#a01523f461c4e79173b9308569bf7185e">DagNotPat</a>, <a href="#a0c9db6f087ae1282b589734781636cd6">DagNotPrefix</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DagNotPat {#a01523f461c4e79173b9308569bf7185e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pattern llvm::FileCheckString::DagNotPrefixInfo::DagNotPat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 830 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<p>Referenced by <a href="#af7efa47116ffbd9de7eccc2c284c7b87">DagNotPrefixInfo</a>.</p>

</div>
</div>

### DagNotPrefix {#a0c9db6f087ae1282b589734781636cd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::FileCheckString::DagNotPrefixInfo::DagNotPrefix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 831 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<p>Referenced by <a href="#af7efa47116ffbd9de7eccc2c284c7b87">DagNotPrefixInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
