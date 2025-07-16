---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/objcopy/wasm/object
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Object` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::objcopy::wasm::Object { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobject-h">ObjCopy/wasm/WasmObject.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8b896e0f60be77a397633e4bbeee362">addSectionWithOwnedContents</a> (Section NewSection, std::unique_ptr&lt; MemoryBuffer &gt; &amp;&amp;Content)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ff1730158f82c9b5c99b3947740404">removeSections</a> (function_ref&lt; bool(const Section &amp;)&gt; ToRemove)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/wasm/wasmobjectheader">llvm::wasm::WasmObjectHeader</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6084713e32c94fe0da197223dadfda5d">Header</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section">Section</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16c713d625e7e58397151ee1b7b25c11">Sections</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab526098a7dfd803270afa67e86169cf7">isRelocatableObject</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada4b14620e88ef04c92f14ef9a6ee31a">OwnedContents</a></td>
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


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobject-h">WasmObject.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### addSectionWithOwnedContents() {#ae8b896e0f60be77a397633e4bbeee362}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcopy::wasm::Object::addSectionWithOwnedContents (<a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section">Section</a> NewSection, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &amp;&amp; Content)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobject-h">WasmObject.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobject-cpp">WasmObject.cpp</a>.</p>


<p>Reference <a href="#a16c713d625e7e58397151ee1b7b25c11">Sections</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#a42dbc5cc7c04f8d8738edf9699d75654">llvm::objcopy::wasm::handleArgs</a>.</p>

</div>
</div>

### removeSections() {#af9ff1730158f82c9b5c99b3947740404}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcopy::wasm::Object::removeSections (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section">Section</a> &amp;)&gt; ToRemove)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobject-h">WasmObject.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobject-cpp">WasmObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a7de5a04920954ac964059cfc428ad">llvm::erase_if</a>, <a href="#ab526098a7dfd803270afa67e86169cf7">isRelocatableObject</a>, <a href="#a16c713d625e7e58397151ee1b7b25c11">Sections</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a3bf42baf773b375802538951c88d8e12">ToRemove</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaa685069a810d109e09f4af7d2d115a8cd">llvm::wasm::WASM_SEC_CUSTOM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#a128c16fdb808e0e243d89ae57ed3717d">llvm::objcopy::wasm::removeSections</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Header {#a6084713e32c94fe0da197223dadfda5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::wasm::WasmObjectHeader llvm::objcopy::wasm::Object::Header</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobject-h">WasmObject.h</a>.</p>

</div>
</div>

### isRelocatableObject {#ab526098a7dfd803270afa67e86169cf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcopy::wasm::Object::isRelocatableObject = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobject-h">WasmObject.h</a>.</p>


<p>Referenced by <a href="#af9ff1730158f82c9b5c99b3947740404">removeSections</a>.</p>

</div>
</div>

### Sections {#a16c713d625e7e58397151ee1b7b25c11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Section&gt; llvm::objcopy::wasm::Object::Sections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobject-h">WasmObject.h</a>.</p>


<p>Referenced by <a href="#ae8b896e0f60be77a397633e4bbeee362">addSectionWithOwnedContents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#ab4c167a5e231ccb60ec1eb5552ca233b">llvm::objcopy::wasm::dumpSectionToFile</a> and <a href="#af9ff1730158f82c9b5c99b3947740404">removeSections</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### OwnedContents {#ada4b14620e88ef04c92f14ef9a6ee31a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;MemoryBuffer&gt; &gt; llvm::objcopy::wasm::Object::OwnedContents</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobject-h">WasmObject.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobject-cpp">WasmObject.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobject-h">WasmObject.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
