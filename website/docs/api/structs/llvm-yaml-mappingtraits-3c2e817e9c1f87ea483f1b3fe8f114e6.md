---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/mappingtraits-3c2e817e9c1f87ea483f1b3fe8f114e6
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MappingTraits` Struct Template



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::MappingTraits&lt;std::unique_ptr&lt; WasmYAML::Section &gt;&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/wasmyaml-h">llvm/ObjectYAML/WasmYAML.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a740fa91ae223f3049041dc18ed78d67d">mapping</a> (IO &amp;IO, std::unique_ptr&lt; WasmYAML::Section &gt; &amp;Section)</td>
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


<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/wasmyaml-h">WasmYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### mapping() {#a740fa91ae223f3049041dc18ed78d67d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::MappingTraits&lt; std::unique_ptr&lt; WasmYAML::Section &gt; &gt;::mapping (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO, std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/wasmyaml/section">WasmYAML::Section</a> &gt; &amp; Section)</td>
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



<p>Declaration at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/wasmyaml-h">WasmYAML.h</a>, definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/wasmyaml-cpp">WasmYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a740fa91ae223f3049041dc18ed78d67d">mapping</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a>, <a href="/web-llvm/docs/api/structs/llvm/sectionname/#ae7103e72bb9eaf5a0520a33f65a3b2b3">llvm::SectionName::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a3f9abe4cc7cc808cb6025ed882bcbb7d">llvm::yaml::IO::outputting</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a1ecc2a9dbffcb08b283b0a711245cfb3">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaa2891550fb4214ba533de409607f5f88a">llvm::wasm::WASM_SEC_CODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaa685069a810d109e09f4af7d2d115a8cd">llvm::wasm::WASM_SEC_CUSTOM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaaf5f28d03ffa839369fe16c44315b9f56">llvm::wasm::WASM_SEC_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaa5bc69c390761e831710eebe816c01c97">llvm::wasm::WASM_SEC_DATACOUNT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaacc3262a56b72cdc81e7ac6da2e50969d">llvm::wasm::WASM_SEC_ELEM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaa5818ad8530ad96e4642c4bff31b5189f">llvm::wasm::WASM_SEC_EXPORT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaac423bdc40b8e2a72b9548c3a9c4758ff">llvm::wasm::WASM_SEC_FUNCTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaaeddb30202aeb449ce5c1daf8ad54d84b">llvm::wasm::WASM_SEC_GLOBAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaa4d116565b7ec2cb530120760c03afbeb">llvm::wasm::WASM_SEC_IMPORT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaa43b80f5b5d06549146a1476e7a47b629">llvm::wasm::WASM_SEC_MEMORY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaacfeee95c8a8db3a7c1a910ddb24a7042">llvm::wasm::WASM_SEC_START</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaad628aef84b9091dee5d09358fc67a12e">llvm::wasm::WASM_SEC_TABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaaeb9ae911a9277a37d0ae49f88e7028a5">llvm::wasm::WASM_SEC_TAG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaadd3eb49eaff44231c33af7091ff5bb45">llvm::wasm::WASM_SEC_TYPE</a>.</p>


<p>Referenced by <a href="#a740fa91ae223f3049041dc18ed78d67d">mapping</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/wasmyaml-h">WasmYAML.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/wasmyaml-cpp">WasmYAML.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
