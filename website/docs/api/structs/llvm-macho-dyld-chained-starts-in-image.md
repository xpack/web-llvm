---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/macho/dyld-chained-starts-in-image
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `dyld_chained_starts_in_image` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/macho/dyld-chained-starts-in-image">dyld_chained_starts_in_image</a> is embedded in LC_DYLD_CHAINED_FIXUPS payload. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MachO::dyld_chained_starts_in_image { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">llvm/BinaryFormat/MachO.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e998ebf13dc20da601244024f74cab0">seg_count</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8263e0219e2f1b5e80cce7d7211262f7">seg_info_offset</a>[1]</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/macho/dyld-chained-starts-in-image">dyld_chained_starts_in_image</a> is embedded in LC_DYLD_CHAINED_FIXUPS payload.</p>


<p>Each seg_info_offset entry is the offset into this struct for that segment followed by pool of dyld_chain_starts_in_segment data.</p>


<p>Definition at line 1077 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### seg\_count {#a9e998ebf13dc20da601244024f74cab0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::dyld_chained_starts_in_image::seg_count</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1078 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a766c3350d64dde8af24ef7b600b11185">llvm::object::MachOObjectFile::getChainedFixupsSegments</a>.</p>

</div>
</div>

### seg\_info\_offset {#a8263e0219e2f1b5e80cce7d7211262f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::dyld_chained_starts_in_image::seg_info_offset[1]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1079 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
