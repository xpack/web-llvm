---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/objcopy/wasm/section
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Section` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::objcopy::wasm::Section { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobject-h">ObjCopy/wasm/WasmObject.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f6248ef8ae89023e9b794f67f618fd3">SectionType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8afc1d74a0303d1016db0aa79eb5c303">HeaderSecSizeEncodingLen</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec9545d1fbb019d82321902c588dbe75">Name</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b75640e3f42d0e0b592221f25ef0b66">Contents</a></td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobject-h">WasmObject.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Contents {#a5b75640e3f42d0e0b592221f25ef0b66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;uint8_t&gt; llvm::objcopy::wasm::Section::Contents</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobject-h">WasmObject.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#ab4c167a5e231ccb60ec1eb5552ca233b">llvm::objcopy::wasm::dumpSectionToFile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#a42dbc5cc7c04f8d8738edf9699d75654">llvm::objcopy::wasm::handleArgs</a>.</p>

</div>
</div>

### HeaderSecSizeEncodingLen {#a8afc1d74a0303d1016db0aa79eb5c303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint8_t&gt; llvm::objcopy::wasm::Section::HeaderSecSizeEncodingLen</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobject-h">WasmObject.h</a>.</p>

</div>
</div>

### Name {#aec9545d1fbb019d82321902c588dbe75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::objcopy::wasm::Section::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobject-h">WasmObject.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/wasm/reader/#a51514a556b4bbc63df0eabeec60c031f">llvm::objcopy::wasm::Reader::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#ab4c167a5e231ccb60ec1eb5552ca233b">llvm::objcopy::wasm::dumpSectionToFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#a42dbc5cc7c04f8d8738edf9699d75654">llvm::objcopy::wasm::handleArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#a08369588257f45ac9b845eda6e4352b3">llvm::objcopy::wasm::isCommentSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#a4dba745db7f48a6b368292275bf556c8">llvm::objcopy::wasm::isDebugSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#ad82fa2803c170f1ec4d650cf675ac11e">llvm::objcopy::wasm::isLinkerSection</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#ac3c7c565e25c8198f7dd825a62574961">llvm::objcopy::wasm::isNameSection</a>.</p>

</div>
</div>

### SectionType {#a0f6248ef8ae89023e9b794f67f618fd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::objcopy::wasm::Section::SectionType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobject-h">WasmObject.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/wasm/reader/#a51514a556b4bbc63df0eabeec60c031f">llvm::objcopy::wasm::Reader::create</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#a42dbc5cc7c04f8d8738edf9699d75654">llvm::objcopy::wasm::handleArgs</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobject-h">WasmObject.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
