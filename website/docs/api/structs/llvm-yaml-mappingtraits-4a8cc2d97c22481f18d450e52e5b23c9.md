---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/mappingtraits-4a8cc2d97c22481f18d450e52e5b23c9
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MappingTraits` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::MappingTraits&lt;WasmYAML::InitExpr&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/wasmyaml-h">llvm/ObjectYAML/WasmYAML.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d99c06ba93604da2fd5d5d0ce95ff7f">mapping</a> (IO &amp;IO, WasmYAML::InitExpr &amp;Expr)</td>
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


<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/wasmyaml-h">WasmYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### mapping() {#a3d99c06ba93604da2fd5d5d0ce95ff7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::MappingTraits&lt; WasmYAML::InitExpr &gt;::mapping (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO, <a href="/web-llvm/docs/api/structs/llvm/wasmyaml/initexpr">WasmYAML::InitExpr</a> &amp; Expr)</td>
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



<p>Declaration at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/wasmyaml-h">WasmYAML.h</a>, definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/wasmyaml-cpp">WasmYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/wasmyaml/initexpr/#a2c89372c658f8aa23fc05d684cd845e2">llvm::WasmYAML::InitExpr::Body</a>, <a href="/web-llvm/docs/api/structs/llvm/wasmyaml/initexpr/#a92bef8078d95c6e73aceb141b1a39921">llvm::WasmYAML::InitExpr::Extended</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexprmvp/#a54e438003e03c8c1973d3df49ec83445">llvm::wasm::WasmInitExprMVP::Float32</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexprmvp/#afcb363be1bef728b0b24ce93002948ff">llvm::wasm::WasmInitExprMVP::Float64</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexprmvp/#ad9bf9e2125b5c4ebd0aa07496a5762e6">llvm::wasm::WasmInitExprMVP::Global</a>, <a href="/web-llvm/docs/api/structs/llvm/wasmyaml/initexpr/#a03ad5943dd6d8c2311e6be3905703f84">llvm::WasmYAML::InitExpr::Inst</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexprmvp/#a01acce116ff99f623babd7fe30be1679">llvm::wasm::WasmInitExprMVP::Int32</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexprmvp/#aaef138df6847fb7ae420aec252e88bee">llvm::wasm::WasmInitExprMVP::Int64</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexprmvp/#a1312a3d70f2eb85753cb41c484b558dd">llvm::wasm::WasmInitExprMVP::Opcode</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexprmvp/#a0ec2f9d136ea1d19f4e60356d355aaee">llvm::wasm::WasmInitExprMVP::Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033a94085475370d28c3750f92a327224a53">llvm::wasm::WASM_OPCODE_F32_CONST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033a334197a2017c810968e76bdd6c7874a1">llvm::wasm::WASM_OPCODE_F64_CONST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033a9a3bf1c56c7bc61608587d378713e4ca">llvm::wasm::WASM_OPCODE_GLOBAL_GET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033af7ad1dcf98f3df5c78655b761f495c54">llvm::wasm::WASM_OPCODE_I32_CONST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033ad7ad0258400fc7d91485fa603ff41daf">llvm::wasm::WASM_OPCODE_I64_CONST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033a8169e7206232ec368246b729068cb465">llvm::wasm::WASM_OPCODE_REF_NULL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647ea8fe9c097be76685c503bf24177988a49">llvm::wasm::WASM_TYPE_EXTERNREF</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
