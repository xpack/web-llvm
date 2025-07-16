---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/object/offloadbinary/offloadingimage
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `OffloadingImage` Struct Reference

<p>The offloading metadata that will be serialized to a memory buffer. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::object::OffloadBinary::OffloadingImage { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">llvm/Object/OffloadBinary.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#ae1135a376f397074fd6f8f79b7463e41">ImageKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a865ec496e0ae3a02e4778d6db2c05e4d">TheImageKind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a92b4561998310fbcfbeaeb7c449bad6a">OffloadKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39740c937ded0a868e287d8ea509c8a4">TheOffloadKind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55e305331a4556a83d806c1d6d3091e8">Flags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae20697624777c3f848573c5ca97bfc28">StringData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e5028688bea4574b8f3af7947c33a50">Image</a></td>
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

<p>The offloading metadata that will be serialized to a memory buffer.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Flags {#a55e305331a4556a83d806c1d6d3091e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::OffloadBinary::OffloadingImage::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#a56f47c8dc5df749b09ecdabc977e01c7">llvm::object::OffloadBinary::write</a>.</p>

</div>
</div>

### Image {#a7e5028688bea4574b8f3af7947c33a50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemoryBuffer&gt; llvm::object::OffloadBinary::OffloadingImage::Image</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#a56f47c8dc5df749b09ecdabc977e01c7">llvm::object::OffloadBinary::write</a>.</p>

</div>
</div>

### StringData {#ae20697624777c3f848573c5ca97bfc28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;StringRef, StringRef&gt; llvm::object::OffloadBinary::OffloadingImage::StringData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#a56f47c8dc5df749b09ecdabc977e01c7">llvm::object::OffloadBinary::write</a>.</p>

</div>
</div>

### TheImageKind {#a865ec496e0ae3a02e4778d6db2c05e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImageKind llvm::object::OffloadBinary::OffloadingImage::TheImageKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#a56f47c8dc5df749b09ecdabc977e01c7">llvm::object::OffloadBinary::write</a>.</p>

</div>
</div>

### TheOffloadKind {#a39740c937ded0a868e287d8ea509c8a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffloadKind llvm::object::OffloadBinary::OffloadingImage::TheOffloadKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#a56f47c8dc5df749b09ecdabc977e01c7">llvm::object::OffloadBinary::write</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
