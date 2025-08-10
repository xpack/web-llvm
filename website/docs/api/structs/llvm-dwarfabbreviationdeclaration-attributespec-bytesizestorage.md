---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarfabbreviationdeclaration/attributespec/bytesizestorage
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ByteSizeStorage` Struct

<p>The following field is used for ByteSize for non-implicit_const attributes and as value for implicit_const ones, indicated by Form == DW_FORM_implicit_const. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::DWARFAbbreviationDeclaration::AttributeSpec::ByteSizeStorage { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b151309b1e4caac9974f42c329b3899">HasByteSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66d988aef2911a2d4e933f891ab0354f">ByteSize</a></td>
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

<p>The following field is used for ByteSize for non-implicit_const attributes and as value for implicit_const ones, indicated by Form == DW_FORM_implicit_const.</p>


<p>The following cases are distinguished:</p>


<ul class="doxyList ">
<li>Form != DW_FORM_implicit_const and HasByteSize is true: ByteSize contains the fixed size in bytes for the Form in this object.</li>
<li>Form != DW_FORM_implicit_const and HasByteSize is false: byte size of Form either varies according to the <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> that it is contained in or the value size varies and must be decoded from the debug information in order to determine its size.</li>
<li>Form == DW_FORM_implicit_const: <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> contains value for the implicit_const attribute.</li>
</ul>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### ByteSize {#a66d988aef2911a2d4e933f891ab0354f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DWARFAbbreviationDeclaration::AttributeSpec::ByteSizeStorage::ByteSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>

</div>
</div>

### HasByteSize {#a6b151309b1e4caac9974f42c329b3899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFAbbreviationDeclaration::AttributeSpec::ByteSizeStorage::HasByteSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
