---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfabbreviationdeclaration
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DWARFAbbreviationDeclaration` Class



## Declaration

<div class="doxyDeclaration">
class llvm::DWARFAbbreviationDeclaration { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">llvm/DebugInfo/DWARF/DWARFAbbreviationDeclaration.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0910dfca074406871fc17f5a335ef283">AttributeSpecVector</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec">AttributeSpec</a>, 8 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ec5d1c6239e870507fc273f8aa4e6ce">attr_iterator_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aa11b903431c1931920939bac6b5293a2">AttributeSpecVector::const_iterator</a> &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ExtractState { <a href="#a45f09c6803dbfb2f9d93c99695f96c4f">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af09a94b7f29820590b6ab1ce422b0adc">DWARFAbbreviationDeclaration</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1c89d249411e93a83f15dbef8a16ca4">getCode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e2944e4346a2471510b6d9808b6c10b">getCodeByteSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9845eea8b8e03fc6df883a052e687a9d">getTag</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15569ecc35acb16fbf216df8dccac97f">hasChildren</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8ec5d1c6239e870507fc273f8aa4e6ce">attr_iterator_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6413f88dcc7951305366531706fd50bc">attributes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad83f0ea5f018d48bb5d14c233ecfbdc9">getFormByIndex</a> (uint32_t idx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a4a66da167ba3c1491519a9fcb7594c">getNumAttributes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a492fdf2702f0b7ff4fb07bc41e877bd5">getAttrByIndex</a> (uint32_t idx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a252fec4450c583c364a00273761ae520">getAttrIsImplicitConstByIndex</a> (uint32_t idx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a667fbf04d64dbf14c148c06da40249b4">getAttrImplicitConstValueByIndex</a> (uint32_t idx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5d511f8ee28fc98a1236c8f5cb23b67">findAttributeIndex</a> (dwarf::Attribute attr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the index of the specified attribute. <a href="#aa5d511f8ee28fc98a1236c8f5cb23b67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac303e4318857e7a74047f04168c5f697">getAttributeValue</a> (const uint64_t DIEOffset, const dwarf::Attribute Attr, const DWARFUnit &amp;U) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a DWARF form value from a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> specified by <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset. <a href="#ac303e4318857e7a74047f04168c5f697">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94f847fdc533254e25f90cd4ea91de3e">getAttributeOffsetFromIndex</a> (uint32_t AttrIndex, uint64_t DIEOffset, const DWARFUnit &amp;U) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute an offset from a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> specified by <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset and attribute index. <a href="#a94f847fdc533254e25f90cd4ea91de3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2e00474b41566a698cda953e1d62d3c">getAttributeValueFromOffset</a> (uint32_t AttrIndex, uint64_t Offset, const DWARFUnit &amp;U) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a DWARF form value from a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> speccified by attribute index and its offset. <a href="#ae2e00474b41566a698cda953e1d62d3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; <a href="#a45f09c6803dbfb2f9d93c99695f96c4f">ExtractState</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eb41e4fd2f2686492e3aadaeb8b0617">extract</a> (DataExtractor Data, uint64_t *OffsetPtr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae00d1e406bd4d7b04dce3326ccfd32d4">dump</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad753cf8292515be1a19ae880360ff2ab">getFixedAttributesByteSize</a> (const DWARFUnit &amp;U) const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2fc48f455d359b5a199f65294e0c128">clear</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91809a0f4a8ffd2c2d862d19a5bd7fca">Code</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01de99526f1591a96949b885fba73195">Tag</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4bd3ec635fdeea8c62a41a85177df02">CodeByteSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad99d628c765d6f17ff9b70837ee9da54">HasChildren</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0910dfca074406871fc17f5a335ef283">AttributeSpecVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e0d4c438e77489c3f8c8cc8ba9d7a2e">AttributeSpecs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; FixedSizeInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e44d51f7a61126ba5495e27ed59222f">FixedAttributeSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this abbreviation has a fixed byte size then FixedAttributeSize member variable below will have a value. <a href="#a9e44d51f7a61126ba5495e27ed59222f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### attr\_iterator\_range {#a8ec5d1c6239e870507fc273f8aa4e6ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DWARFAbbreviationDeclaration::attr_iterator_range = 
      iterator_range&lt;AttributeSpecVector::const_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>

</div>
</div>

### AttributeSpecVector {#a0910dfca074406871fc17f5a335ef283}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DWARFAbbreviationDeclaration::AttributeSpecVector =  SmallVector&lt;AttributeSpec, 8&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### ExtractState {#a45f09c6803dbfb2f9d93c99695f96c4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::DWARFAbbreviationDeclaration::ExtractState </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Complete<a id="a45f09c6803dbfb2f9d93c99695f96c4faae94f80b3ce82062a5dd7815daa04f9d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MoreItems<a id="a45f09c6803dbfb2f9d93c99695f96c4fa6dddae7592715059f525b0be03e12b66"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DWARFAbbreviationDeclaration() {#af09a94b7f29820590b6ab1ce422b0adc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFAbbreviationDeclaration::DWARFAbbreviationDeclaration ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfabbreviationdeclaration-cpp">DWARFAbbreviationDeclaration.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### attributes() {#a6413f88dcc7951305366531706fd50bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">attr_iterator_range llvm::DWARFAbbreviationDeclaration::attributes ()</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>

</div>
</div>

### dump() {#ae00d1e406bd4d7b04dce3326ccfd32d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFAbbreviationDeclaration::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfabbreviationdeclaration-cpp">DWARFAbbreviationDeclaration.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="#ac1c89d249411e93a83f15dbef8a16ca4">getCode</a>, <a href="#a9845eea8b8e03fc6df883a052e687a9d">getTag</a> and <a href="#a15569ecc35acb16fbf216df8dccac97f">hasChildren</a>.</p>

</div>
</div>

### extract() {#a0eb41e4fd2f2686492e3aadaeb8b0617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; DWARFAbbreviationDeclaration::ExtractState &gt; DWARFAbbreviationDeclaration::extract (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> Data, uint64_t * OffsetPtr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfabbreviationdeclaration-cpp">DWARFAbbreviationDeclaration.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a45f09c6803dbfb2f9d93c99695f96c4faae94f80b3ce82062a5dd7815daa04f9d">Complete</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a4b8a3f1fe8eed309f0b034064b508050">llvm::dwarf::DW_CHILDREN_yes</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa03b0ad8792b784269332332eb61d8ad">llvm::dwarf::getFixedFormByteSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#a45f09c6803dbfb2f9d93c99695f96c4fa6dddae7592715059f525b0be03e12b66">MoreItems</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfabbreviationdeclarationset/#a51185edea3b0246d3c37ee13b9553491">llvm::DWARFAbbreviationDeclarationSet::extract</a>.</p>

</div>
</div>

### findAttributeIndex() {#aa5d511f8ee28fc98a1236c8f5cb23b67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; DWARFAbbreviationDeclaration::findAttributeIndex (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> attr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the index of the specified attribute.</p>


<p>Searches the this abbreviation declaration for the index of the specified attribute.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">attr</td>
<td class="doxyParamItemDescription"><p>DWARF attribute to search for.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Optional index of the attribute if found, std::nullopt otherwise.</p></dd>
</dl>


<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>, definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfabbreviationdeclaration-cpp">DWARFAbbreviationDeclaration.cpp</a>.</p>


<p>Referenced by <a href="#ac303e4318857e7a74047f04168c5f697">getAttributeValue</a>.</p>

</div>
</div>

### getAttrByIndex() {#a492fdf2702f0b7ff4fb07bc41e877bd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Attribute llvm::DWARFAbbreviationDeclaration::getAttrByIndex (uint32_t idx)</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getAttributeOffsetFromIndex() {#a94f847fdc533254e25f90cd4ea91de3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t DWARFAbbreviationDeclaration::getAttributeOffsetFromIndex (uint32_t AttrIndex, uint64_t DIEOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute an offset from a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> specified by <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset and attribute index.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">AttrIndex</td>
<td class="doxyParamItemDescription"><p>an index of DWARF attribute.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DIEOffset</td>
<td class="doxyParamItemDescription"><p>the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset that points to the ULEB128 abbreviation code in the .debug_info data.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">U</td>
<td class="doxyParamItemDescription"><p>the <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> the contains the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an offset of the attribute.</p></dd>
</dl>


<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfabbreviationdeclaration-cpp">DWARFAbbreviationDeclaration.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#ad16686174287aeb36289484f271d5225">llvm::DWARFFormValue::skipValue</a>.</p>


<p>Referenced by <a href="#ac303e4318857e7a74047f04168c5f697">getAttributeValue</a>.</p>

</div>
</div>

### getAttributeValue() {#ac303e4318857e7a74047f04168c5f697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DWARFFormValue &gt; DWARFAbbreviationDeclaration::getAttributeValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t DIEOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract a DWARF form value from a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> specified by <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset.</p>


<p>Extract an attribute value for a <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> given the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset and the attribute.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DIEOffset</td>
<td class="doxyParamItemDescription"><p>the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset that points to the ULEB128 abbreviation code in the .debug_info data.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Attr</td>
<td class="doxyParamItemDescription"><p>DWARF attribute to search for.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">U</td>
<td class="doxyParamItemDescription"><p>the <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> the contains the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Optional DWARF form value if the attribute was extracted.</p></dd>
</dl>


<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfabbreviationdeclaration-cpp">DWARFAbbreviationDeclaration.cpp</a>.</p>


<p>References <a href="#aa5d511f8ee28fc98a1236c8f5cb23b67">findAttributeIndex</a>, <a href="#a94f847fdc533254e25f90cd4ea91de3e">getAttributeOffsetFromIndex</a>, <a href="#ae2e00474b41566a698cda953e1d62d3c">getAttributeValueFromOffset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getAttributeValueFromOffset() {#ae2e00474b41566a698cda953e1d62d3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DWARFFormValue &gt; DWARFAbbreviationDeclaration::getAttributeValueFromOffset (uint32_t AttrIndex, uint64_t Offset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract a DWARF form value from a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> speccified by attribute index and its offset.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">AttrIndex</td>
<td class="doxyParamItemDescription"><p>an index of DWARF attribute.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Offset</td>
<td class="doxyParamItemDescription"><p>offset of the attribute.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">U</td>
<td class="doxyParamItemDescription"><p>the <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> the contains the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Optional DWARF form value if the attribute was extracted.</p></dd>
</dl>


<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>, definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfabbreviationdeclaration-cpp">DWARFAbbreviationDeclaration.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#ac346eaa0ba929794c7261e78a757f7ad">llvm::DWARFFormValue::createFromSValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#aa146755e2500aea560c4417a30c0b96b">llvm::DWARFFormValue::extractValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#ac303e4318857e7a74047f04168c5f697">getAttributeValue</a>.</p>

</div>
</div>

### getAttrImplicitConstValueByIndex() {#a667fbf04d64dbf14c148c06da40249b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::DWARFAbbreviationDeclaration::getAttrImplicitConstValueByIndex (uint32_t idx)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getAttrIsImplicitConstByIndex() {#a252fec4450c583c364a00273761ae520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFAbbreviationDeclaration::getAttrIsImplicitConstByIndex (uint32_t idx)</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getCode() {#ac1c89d249411e93a83f15dbef8a16ca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFAbbreviationDeclaration::getCode ()</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>


<p>Referenced by <a href="#ae00d1e406bd4d7b04dce3326ccfd32d4">dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfabbreviationdeclarationset/#a51185edea3b0246d3c37ee13b9553491">llvm::DWARFAbbreviationDeclarationSet::extract</a>.</p>

</div>
</div>

### getCodeByteSize() {#a6e2944e4346a2471510b6d9808b6c10b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DWARFAbbreviationDeclaration::getCodeByteSize ()</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>

</div>
</div>

### getFixedAttributesByteSize() {#ad753cf8292515be1a19ae880360ff2ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; size_t &gt; DWARFAbbreviationDeclaration::getFixedAttributesByteSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>, definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfabbreviationdeclaration-cpp">DWARFAbbreviationDeclaration.cpp</a>.</p>

</div>
</div>

### getFormByIndex() {#ad83f0ea5f018d48bb5d14c233ecfbdc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Form llvm::DWARFAbbreviationDeclaration::getFormByIndex (uint32_t idx)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getNumAttributes() {#a0a4a66da167ba3c1491519a9fcb7594c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::DWARFAbbreviationDeclaration::getNumAttributes ()</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>

</div>
</div>

### getTag() {#a9845eea8b8e03fc6df883a052e687a9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Tag llvm::DWARFAbbreviationDeclaration::getTag ()</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>


<p>Referenced by <a href="#ae00d1e406bd4d7b04dce3326ccfd32d4">dump</a>.</p>

</div>
</div>

### hasChildren() {#a15569ecc35acb16fbf216df8dccac97f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFAbbreviationDeclaration::hasChildren ()</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>


<p>Referenced by <a href="#ae00d1e406bd4d7b04dce3326ccfd32d4">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### clear() {#ac2fc48f455d359b5a199f65294e0c128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFAbbreviationDeclaration::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfabbreviationdeclaration-cpp">DWARFAbbreviationDeclaration.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AttributeSpecs {#a0e0d4c438e77489c3f8c8cc8ba9d7a2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSpecVector llvm::DWARFAbbreviationDeclaration::AttributeSpecs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>

</div>
</div>

### Code {#a91809a0f4a8ffd2c2d862d19a5bd7fca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFAbbreviationDeclaration::Code</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>

</div>
</div>

### CodeByteSize {#aa4bd3ec635fdeea8c62a41a85177df02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DWARFAbbreviationDeclaration::CodeByteSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>

</div>
</div>

### FixedAttributeSize {#a9e44d51f7a61126ba5495e27ed59222f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;FixedSizeInfo&gt; llvm::DWARFAbbreviationDeclaration::FixedAttributeSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this abbreviation has a fixed byte size then FixedAttributeSize member variable below will have a value.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>

</div>
</div>

### HasChildren {#ad99d628c765d6f17ff9b70837ee9da54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFAbbreviationDeclaration::HasChildren</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>

</div>
</div>

### Tag {#a01de99526f1591a96949b885fba73195}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Tag llvm::DWARFAbbreviationDeclaration::Tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfabbreviationdeclaration-cpp">DWARFAbbreviationDeclaration.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
