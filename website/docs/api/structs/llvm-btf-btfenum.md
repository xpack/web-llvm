---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/btf/btfenum
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BTFEnum` Struct Reference

<p>BTF_KIND_ENUM is followed by multiple "struct BTFEnum". <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::BTF::BTFEnum { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">llvm/DebugInfo/BTF/BTF.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2b0b6acf1c8fdfb58411ebf5dff28f9">NameOff</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enum name offset in the string table. <a href="#ab2b0b6acf1c8fdfb58411ebf5dff28f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8871b9617c5991db1f8471de61d6a7ee">Val</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enum member value. <a href="#a8871b9617c5991db1f8471de61d6a7ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>BTF_KIND_ENUM is followed by multiple "struct BTFEnum".</p>


<p>The exact number of btf_enum is stored in the vlen (of the info in "struct CommonType").</p>


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">BTF.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### NameOff {#ab2b0b6acf1c8fdfb58411ebf5dff28f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::BTF::BTFEnum::NameOff</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enum name offset in the string table.</p>

<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">BTF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btftypeenum/#a203c3d259fa1aaee1f4e8a4330883bf4">llvm::BTFTypeEnum::completeType</a>.</p>

</div>
</div>

### Val {#a8871b9617c5991db1f8471de61d6a7ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::BTF::BTFEnum::Val</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enum member value.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">BTF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btftypeenum/#a203c3d259fa1aaee1f4e8a4330883bf4">llvm::BTFTypeEnum::completeType</a>.</p>

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
