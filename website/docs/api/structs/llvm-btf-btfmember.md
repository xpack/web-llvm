---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/btf/btfmember
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BTFMember` Struct Reference

<p>BTF_KIND_STRUCT and BTF_KIND_UNION are followed by multiple "struct BTFMember". <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::BTF::BTFMember { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">llvm/DebugInfo/BTF/BTF.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ffcd706611ea780a90179deaa4ff57b">NameOff</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Member name offset in the string table. <a href="#a0ffcd706611ea780a90179deaa4ff57b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad51708ec32be9d7307732b6d308f06cc">Type</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Member type. <a href="#ad51708ec32be9d7307732b6d308f06cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2acadf022d68b4e7905efcadfbfd3444">Offset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BitOffset or BitFieldSize+BitOffset. <a href="#a2acadf022d68b4e7905efcadfbfd3444">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>BTF_KIND_STRUCT and BTF_KIND_UNION are followed by multiple "struct BTFMember".</p>


<p>The exact number of <a href="/web-llvm/docs/api/structs/llvm/btf/btfmember">BTFMember</a> is stored in the vlen (of the info in "struct CommonType").</p>


<p>If the struct/union contains any bitfield member, the Offset below represents BitOffset (bits 0 - 23) and BitFieldSize(bits 24 - 31) with BitFieldSize = 0 for non bitfield members. Otherwise, the Offset represents the BitOffset.</p>


<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">BTF.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### NameOff {#a0ffcd706611ea780a90179deaa4ff57b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::BTF::BTFMember::NameOff</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Member name offset in the string table.</p>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">BTF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btftypestruct/#ad9bd52649a7141c0bc1bae5f0a9e8f06">llvm::BTFTypeStruct::completeType</a>.</p>

</div>
</div>

### Offset {#a2acadf022d68b4e7905efcadfbfd3444}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::BTF::BTFMember::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>BitOffset or BitFieldSize+BitOffset.</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">BTF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btftypestruct/#ad9bd52649a7141c0bc1bae5f0a9e8f06">llvm::BTFTypeStruct::completeType</a>.</p>

</div>
</div>

### Type {#ad51708ec32be9d7307732b6d308f06cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::BTF::BTFMember::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Member type.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">BTF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btftypestruct/#ad9bd52649a7141c0bc1bae5f0a9e8f06">llvm::BTFTypeStruct::completeType</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">BTF.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
