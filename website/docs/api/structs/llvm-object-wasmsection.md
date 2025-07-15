---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/object/wasmsection
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `WasmSection` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::object::WasmSection { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">llvm/Object/Wasm.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e230794d0f2d5e0595e141d85643b3">WasmSection</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee122f9e75e7ae929d7080d19835ecf4">Type</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a83689520ab18b5914bba2f6d2e1496">Offset</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46cceeb4e726b13eed910331a41ef7df">Name</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bb43e47b1450730ddc9a9a2f5fcaad1">Comdat</a> = UINT32_MAX</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1649dfc662bba0263b3f9b2068e36db7">Content</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmrelocation">wasm::WasmRelocation</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a607ddcc9e8bb04ea35ad59b36c23dee7">Relocations</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a8d8b720dbc368e04297ef9685fa83b">HeaderSecSizeEncodingLen</a></td>
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


<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WasmSection() {#ae7e230794d0f2d5e0595e141d85643b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::WasmSection::WasmSection ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Comdat {#a2bb43e47b1450730ddc9a9a2f5fcaad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmSection::Comdat = UINT32_MAX</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### Content {#a1649dfc662bba0263b3f9b2068e36db7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;uint8_t&gt; llvm::object::WasmSection::Content</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/wasm/reader/#a51514a556b4bbc63df0eabeec60c031f">llvm::objcopy::wasm::Reader::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a851f27408d0faaa00930a43c3c3f0453">llvm::object::WasmObjectFile::getSectionContents</a> and <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#aa7c80d89ddf584fde12a68516fe703c2">llvm::object::WasmObjectFile::getSectionSize</a>.</p>

</div>
</div>

### HeaderSecSizeEncodingLen {#a7a8d8b720dbc368e04297ef9685fa83b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint8_t&gt; llvm::object::WasmSection::HeaderSecSizeEncodingLen</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/wasm/reader/#a51514a556b4bbc63df0eabeec60c031f">llvm::objcopy::wasm::Reader::create</a>.</p>

</div>
</div>

### Name {#a46cceeb4e726b13eed910331a41ef7df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::WasmSection::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/wasm/reader/#a51514a556b4bbc63df0eabeec60c031f">llvm::objcopy::wasm::Reader::create</a> and <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#afe6783adf1a19511d1e8960996e8dcdd">llvm::object::WasmObjectFile::getSectionName</a>.</p>

</div>
</div>

### Offset {#a9a83689520ab18b5914bba2f6d2e1496}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmSection::Offset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### Relocations {#a607ddcc9e8bb04ea35ad59b36c23dee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;wasm::WasmRelocation&gt; llvm::object::WasmSection::Relocations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a03425ecd6379bfd3afa9e0be578fc3c5">llvm::object::WasmObjectFile::section_rel_end</a>.</p>

</div>
</div>

### Type {#aee122f9e75e7ae929d7080d19835ecf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmSection::Type = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/wasm/reader/#a51514a556b4bbc63df0eabeec60c031f">llvm::objcopy::wasm::Reader::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#afe6783adf1a19511d1e8960996e8dcdd">llvm::object::WasmObjectFile::getSectionName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#afbdfae040884e2bfd5a26f82f26a0d8c">llvm::object::WasmObjectFile::isSectionData</a> and <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a25105b42581ad941bfbf55b4b89819fa">llvm::object::WasmObjectFile::isSectionText</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
