---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/wasm/wasminitexprmvp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `WasmInitExprMVP` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::wasm::WasmInitExprMVP { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/wasm-h">llvm/BinaryFormat/Wasm.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1312a3d70f2eb85753cb41c484b558dd">Opcode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01acce116ff99f623babd7fe30be1679">Int32</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaef138df6847fb7ae420aec252e88bee">Int64</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54e438003e03c8c1973d3df49ec83445">Float32</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcb363be1bef728b0b24ce93002948ff">Float64</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9bf9e2125b5c4ebd0aa07496a5762e6">Global</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexprmvp">llvm::wasm::WasmInitExprMVP</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ec2f9d136ea1d19f4e60356d355aaee">Value</a></td>
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


<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/wasm-h">Wasm.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Float32 {#a54e438003e03c8c1973d3df49ec83445}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::wasm::WasmInitExprMVP::Float32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/wasm-h">Wasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a8cc2d97c22481f18d450e52e5b23c9/#a3d99c06ba93604da2fd5d5d0ce95ff7f">llvm::yaml::MappingTraits&lt; WasmYAML::InitExpr &gt;::mapping</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp/#a45f478a3e04bfcd32b4db7f75fc94577">readInitExpr</a>.</p>

</div>
</div>

### Float64 {#afcb363be1bef728b0b24ce93002948ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::wasm::WasmInitExprMVP::Float64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/wasm-h">Wasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a8cc2d97c22481f18d450e52e5b23c9/#a3d99c06ba93604da2fd5d5d0ce95ff7f">llvm::yaml::MappingTraits&lt; WasmYAML::InitExpr &gt;::mapping</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp/#a45f478a3e04bfcd32b4db7f75fc94577">readInitExpr</a>.</p>

</div>
</div>

### Global {#ad9bf9e2125b5c4ebd0aa07496a5762e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::wasm::WasmInitExprMVP::Global</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/wasm-h">Wasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a8cc2d97c22481f18d450e52e5b23c9/#a3d99c06ba93604da2fd5d5d0ce95ff7f">llvm::yaml::MappingTraits&lt; WasmYAML::InitExpr &gt;::mapping</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp/#a45f478a3e04bfcd32b4db7f75fc94577">readInitExpr</a>.</p>

</div>
</div>

### Int32 {#a01acce116ff99f623babd7fe30be1679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::wasm::WasmInitExprMVP::Int32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/wasm-h">Wasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a17d258c3f5b6b5e3d7d0a192aac0b188">llvm::object::WasmObjectFile::getWasmSymbolValue</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-18dd91fe8ed180bcb5ae4a900ca9e2b6/#a5bab3721e5b76c2b713804fbb8d9a458">llvm::yaml::MappingTraits&lt; WasmYAML::DataSegment &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a8cc2d97c22481f18d450e52e5b23c9/#a3d99c06ba93604da2fd5d5d0ce95ff7f">llvm::yaml::MappingTraits&lt; WasmYAML::InitExpr &gt;::mapping</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp/#a45f478a3e04bfcd32b4db7f75fc94577">readInitExpr</a>.</p>

</div>
</div>

### Int64 {#aaef138df6847fb7ae420aec252e88bee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::wasm::WasmInitExprMVP::Int64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/wasm-h">Wasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a17d258c3f5b6b5e3d7d0a192aac0b188">llvm::object::WasmObjectFile::getWasmSymbolValue</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a8cc2d97c22481f18d450e52e5b23c9/#a3d99c06ba93604da2fd5d5d0ce95ff7f">llvm::yaml::MappingTraits&lt; WasmYAML::InitExpr &gt;::mapping</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp/#a45f478a3e04bfcd32b4db7f75fc94577">readInitExpr</a>.</p>

</div>
</div>

### Opcode {#a1312a3d70f2eb85753cb41c484b558dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::wasm::WasmInitExprMVP::Opcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/wasm-h">Wasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a17d258c3f5b6b5e3d7d0a192aac0b188">llvm::object::WasmObjectFile::getWasmSymbolValue</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-18dd91fe8ed180bcb5ae4a900ca9e2b6/#a5bab3721e5b76c2b713804fbb8d9a458">llvm::yaml::MappingTraits&lt; WasmYAML::DataSegment &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a8cc2d97c22481f18d450e52e5b23c9/#a3d99c06ba93604da2fd5d5d0ce95ff7f">llvm::yaml::MappingTraits&lt; WasmYAML::InitExpr &gt;::mapping</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp/#a45f478a3e04bfcd32b4db7f75fc94577">readInitExpr</a>.</p>

</div>
</div>

### Value {#a0ec2f9d136ea1d19f4e60356d355aaee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::wasm::WasmInitExprMVP llvm::wasm::WasmInitExprMVP::Value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/wasm-h">Wasm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a17d258c3f5b6b5e3d7d0a192aac0b188">llvm::object::WasmObjectFile::getWasmSymbolValue</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-18dd91fe8ed180bcb5ae4a900ca9e2b6/#a5bab3721e5b76c2b713804fbb8d9a458">llvm::yaml::MappingTraits&lt; WasmYAML::DataSegment &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a8cc2d97c22481f18d450e52e5b23c9/#a3d99c06ba93604da2fd5d5d0ce95ff7f">llvm::yaml::MappingTraits&lt; WasmYAML::InitExpr &gt;::mapping</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp/#a45f478a3e04bfcd32b4db7f75fc94577">readInitExpr</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/wasm-h">Wasm.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
