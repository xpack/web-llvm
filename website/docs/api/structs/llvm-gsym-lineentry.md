---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/gsym/lineentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LineEntry` Struct Reference

<p>Line entries are used to encode the line tables in <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::gsym::LineEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lineentry-h">llvm/DebugInfo/GSYM/LineEntry.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa684e0f26d28e5a4b780d3e77d6b1282">LineEntry</a> (uint64_t A=0, uint32_t F=0, uint32_t L=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeabd0356b99fc4192f61bc8e8bedfe17">isValid</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf4509caa6884e20728dd5b8e08b925a">Addr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start address of this line entry. <a href="#abf4509caa6884e20728dd5b8e08b925a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a193c4a1af11b83092b6db93d02219b1e">File</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>1 based index of file in FileTable <a href="#a193c4a1af11b83092b6db93d02219b1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7648b354c70ebeac2fa9001116b84d11">Line</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Source line number. <a href="#a7648b354c70ebeac2fa9001116b84d11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Line entries are used to encode the line tables in <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects.</p>


<p>They are stored as a sorted vector of these objects and store the address, file and line of the line table row for a given address. The size of a line table entry is calculated by looking at the next entry in the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>'s vector of entries.</p>


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lineentry-h">LineEntry.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LineEntry() {#aa684e0f26d28e5a4b780d3e77d6b1282}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::gsym::LineEntry::LineEntry (uint64_t A=0, uint32_t F=0, uint32_t L=0)</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lineentry-h">LineEntry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#abf4509caa6884e20728dd5b8e08b925a">Addr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a193c4a1af11b83092b6db93d02219b1e">File</a> and <a href="#a7648b354c70ebeac2fa9001116b84d11">Line</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isValid() {#aeabd0356b99fc4192f61bc8e8bedfe17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gsym::LineEntry::isValid ()</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lineentry-h">LineEntry.h</a>.</p>


<p>Reference <a href="#a193c4a1af11b83092b6db93d02219b1e">File</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Addr {#abf4509caa6884e20728dd5b8e08b925a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::gsym::LineEntry::Addr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Start address of this line entry.</p>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lineentry-h">LineEntry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable/#a41c4a2acdbcfaf2a18a61b60d42a9dc4">llvm::gsym::LineTable::encode</a> and <a href="#aa684e0f26d28e5a4b780d3e77d6b1282">LineEntry</a>.</p>

</div>
</div>

### File {#a193c4a1af11b83092b6db93d02219b1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::gsym::LineEntry::File</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>1 based index of file in FileTable</p>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lineentry-h">LineEntry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable/#a41c4a2acdbcfaf2a18a61b60d42a9dc4">llvm::gsym::LineTable::encode</a>, <a href="#aeabd0356b99fc4192f61bc8e8bedfe17">isValid</a>, <a href="#aa684e0f26d28e5a4b780d3e77d6b1282">LineEntry</a> and <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a>.</p>

</div>
</div>

### Line {#a7648b354c70ebeac2fa9001116b84d11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::gsym::LineEntry::Line</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Source line number.</p>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lineentry-h">LineEntry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable/#a41c4a2acdbcfaf2a18a61b60d42a9dc4">llvm::gsym::LineTable::encode</a>, <a href="#aa684e0f26d28e5a4b780d3e77d6b1282">LineEntry</a> and <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lineentry-h">LineEntry.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
