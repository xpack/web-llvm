---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/minidump/memorydescriptor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MemoryDescriptor` Struct Reference

<p>Describes a single memory range (both its VM address and where to find it in the file) of the process from which this minidump file was generated. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::minidump::MemoryDescriptor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/minidump-h">llvm/BinaryFormat/Minidump.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a08e0f89c05abcbbaa991af5a36fdf685">support::ulittle64_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6689695d7d481ceb299f69f65d48dab2">StartOfMemoryRange</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/minidump/locationdescriptor">LocationDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d2321be3fff5eaec3d8edb2d04ce46b">Memory</a></td>
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

<p>Describes a single memory range (both its VM address and where to find it in the file) of the process from which this minidump file was generated.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/minidump-h">Minidump.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Memory {#a7d2321be3fff5eaec3d8edb2d04ce46b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationDescriptor llvm::minidump::MemoryDescriptor::Memory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/minidump-h">Minidump.h</a>.</p>

</div>
</div>

### StartOfMemoryRange {#a6689695d7d481ceb299f69f65d48dab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ulittle64_t llvm::minidump::MemoryDescriptor::StartOfMemoryRange</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/minidump-h">Minidump.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/minidump-h">Minidump.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
