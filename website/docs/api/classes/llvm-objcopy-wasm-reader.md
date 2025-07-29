---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/objcopy/wasm/reader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Reader` Class



## Declaration

<div class="doxyDeclaration">
class llvm::objcopy::wasm::Reader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmreader-h">ObjCopy/wasm/WasmReader.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9bdee2e4c701a99dd8b1a4f3ca335e5">Reader</a> (const object::WasmObjectFile &amp;O)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/object">Object</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51514a556b4bbc63df0eabeec60c031f">create</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile">object::WasmObjectFile</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c589314cd0a26e33a6e20b0c07ed319">WasmObj</a></td>
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


<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmreader-h">WasmReader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Reader() {#aa9bdee2e4c701a99dd8b1a4f3ca335e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcopy::wasm::Reader::Reader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile">object::WasmObjectFile</a> &amp; O)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmreader-h">WasmReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### create() {#a51514a556b4bbc63df0eabeec60c031f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; Object &gt; &gt; llvm::objcopy::wasm::Reader::create ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmreader-h">WasmReader.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmreader-cpp">WasmReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/wasmsection/#a1649dfc662bba0263b3f9b2068e36db7">llvm::object::WasmSection::Content</a>, <a href="/web-llvm/docs/api/structs/llvm/object/wasmsection/#a7a8d8b720dbc368e04297ef9685fa83b">llvm::object::WasmSection::HeaderSecSizeEncodingLen</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section/#aec9545d1fbb019d82321902c588dbe75">llvm::objcopy::wasm::Section::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/object/wasmsection/#a46cceeb4e726b13eed910331a41ef7df">llvm::object::WasmSection::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section/#a0f6248ef8ae89023e9b794f67f618fd3">llvm::objcopy::wasm::Section::SectionType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#ac737e1f79f17b2a3b9abb858d18257cc">llvm::wasm::sectionTypeToString</a>, <a href="/web-llvm/docs/api/structs/llvm/object/wasmsection/#aee122f9e75e7ae929d7080d19835ecf4">llvm::object::WasmSection::Type</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaa685069a810d109e09f4af7d2d115a8cd">llvm::wasm::WASM_SEC_CUSTOM</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaa5f11ab73cf94ba99f69b836f2c39c8fd">llvm::wasm::WASM_SEC_LAST_KNOWN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#ae6098aac8d9341369e7479af43f3d1c2">llvm::objcopy::wasm::executeObjcopyOnBinary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### WasmObj {#a7c589314cd0a26e33a6e20b0c07ed319}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const object::WasmObjectFile&amp; llvm::objcopy::wasm::Reader::WasmObj</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmreader-h">WasmReader.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmreader-cpp">WasmReader.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmreader-h">WasmReader.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
