---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/wasmsectionorderchecker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WasmSectionOrderChecker` Class



## Declaration

<div class="doxyDeclaration">
class llvm::object::WasmSectionOrderChecker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">llvm/Object/Wasm.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : int { <a href="#a90dff24aa71c2d3ff9c67e499e9e2864">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b575c4fbaec067108afa87be8ca0ade">isValidSectionOrder</a> (unsigned ID, StringRef CustomSectionName="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78632da01e01a388bc4926341a8c732">getSectionOrder</a> (unsigned ID, StringRef CustomSectionName="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a377c6ca34aa2bd6211becda2e1b9a1b6">Seen</a>[WASM_NUM_SEC_ORDERS] = {}</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0204cef1f2793ca9897b5bdc91e3860">DisallowedPredecessors</a>[WASM_NUM_SEC_ORDERS][WASM_NUM_SEC_ORDERS]</td>
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


<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a90dff24aa71c2d3ff9c67e499e9e2864}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : int</td>
</tr>
</table>
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
<td class="doxyEnumItemName">WASM_SEC_ORDER_NONE<a id="a90dff24aa71c2d3ff9c67e499e9e2864a0e82e7af99f10e64eb3f4ea4928ae816"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_SEC_ORDER_TYPE<a id="a90dff24aa71c2d3ff9c67e499e9e2864a0260d9714f65614e96d54f9b2657cab0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_SEC_ORDER_IMPORT<a id="a90dff24aa71c2d3ff9c67e499e9e2864ae0318084aa007b72efc8052d8e42c8a0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_SEC_ORDER_FUNCTION<a id="a90dff24aa71c2d3ff9c67e499e9e2864affaf92c38f49a0b53128622fde0ff388"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_SEC_ORDER_TABLE<a id="a90dff24aa71c2d3ff9c67e499e9e2864a894126a56e811c0796a6209592725a83"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_SEC_ORDER_MEMORY<a id="a90dff24aa71c2d3ff9c67e499e9e2864a1371a6fabf3c067f090e51371430b01a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_SEC_ORDER_TAG<a id="a90dff24aa71c2d3ff9c67e499e9e2864adac4b24daf89fffe241a469f78994a7a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_SEC_ORDER_GLOBAL<a id="a90dff24aa71c2d3ff9c67e499e9e2864ad4e4802af61da1b228e00834f1b24614"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_SEC_ORDER_EXPORT<a id="a90dff24aa71c2d3ff9c67e499e9e2864ad79c8cf28678a4c51e39e13d12c8574c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_SEC_ORDER_START<a id="a90dff24aa71c2d3ff9c67e499e9e2864a3bf074182a2b3362a88dcf21de3fea2b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_SEC_ORDER_ELEM<a id="a90dff24aa71c2d3ff9c67e499e9e2864ad2eca9c17f664ac227a18ec0dd15ac76"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_SEC_ORDER_DATACOUNT<a id="a90dff24aa71c2d3ff9c67e499e9e2864aff0c5f7e621d5bb34f2c0c35f2b84361"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_SEC_ORDER_CODE<a id="a90dff24aa71c2d3ff9c67e499e9e2864a39b38c7c69ea5aff45df595ef5f4c4f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_SEC_ORDER_DATA<a id="a90dff24aa71c2d3ff9c67e499e9e2864a6e7ce2aef74c9b9456f541dbc8d39785"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_SEC_ORDER_DYLINK<a id="a90dff24aa71c2d3ff9c67e499e9e2864a597cc9f8b369243914d991fa0b7bfa65"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_SEC_ORDER_LINKING<a id="a90dff24aa71c2d3ff9c67e499e9e2864a604a5f4e04c484070dcca836a41dfd9d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_SEC_ORDER_RELOC<a id="a90dff24aa71c2d3ff9c67e499e9e2864a4605d91778cb5c802ea0c95038094dd6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_SEC_ORDER_NAME<a id="a90dff24aa71c2d3ff9c67e499e9e2864a54bcaf0bc06d8cd9b256027c19be6985"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_SEC_ORDER_PRODUCERS<a id="a90dff24aa71c2d3ff9c67e499e9e2864a16bd8b06c3a6f2710dfd32e26133dbaa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_SEC_ORDER_TARGET_FEATURES<a id="a90dff24aa71c2d3ff9c67e499e9e2864a0ad9dabb1d4c12bc7303c9f819337d47"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_NUM_SEC_ORDERS<a id="a90dff24aa71c2d3ff9c67e499e9e2864a9b2ea2812e6f6ee07135ffc13ee42873"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isValidSectionOrder() {#a0b575c4fbaec067108afa87be8ca0ade}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmSectionOrderChecker::isValidSectionOrder (unsigned ID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CustomSectionName="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2229 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#af0204cef1f2793ca9897b5bdc91e3860">DisallowedPredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a90dff24aa71c2d3ff9c67e499e9e2864a9b2ea2812e6f6ee07135ffc13ee42873">WASM_NUM_SEC_ORDERS</a> and <a href="#a90dff24aa71c2d3ff9c67e499e9e2864a0e82e7af99f10e64eb3f4ea4928ae816">WASM_SEC_ORDER_NONE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp/#a67951f7188e316333fc6cf733db7f71f">readSection</a> and <a href="/web-llvm/docs/api/classes/anonymous-wasmemitter-cpp-/wasmwriter/#acaacefba415b1f85febb359665476b2b">anonymous{WasmEmitter.cpp}::WasmWriter::writeWasm</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getSectionOrder() {#ad78632da01e01a388bc4926341a8c732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int WasmSectionOrderChecker::getSectionOrder (unsigned ID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CustomSectionName="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2137 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Seen {#a377c6ca34aa2bd6211becda2e1b9a1b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmSectionOrderChecker::Seen[WASM_NUM_SEC_ORDERS] = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### DisallowedPredecessors {#af0204cef1f2793ca9897b5bdc91e3860}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int WasmSectionOrderChecker::DisallowedPredecessors</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>Referenced by <a href="#a0b575c4fbaec067108afa87be8ca0ade">isValidSectionOrder</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
