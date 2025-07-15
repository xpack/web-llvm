---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-webassemblyasmparser-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{WebAssemblyAsmParser.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{WebAssemblyAsmParser.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser">WebAssemblyAsmParser</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand">WebAssemblyOperand</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand">WebAssemblyOperand</a> - Instances of this class represent the operands in a parsed Wasm machine instruction. <a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmlimits">wasm::WasmLimits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a309c949ceae23cdcb7edd4ab0c65da49">defaultLimits</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm">MCSymbolWasm</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97776aecc75fa260afa954c88a1bfed6">getOrCreateFunctionTableSymbol</a> (MCContext &amp;Ctx, const StringRef &amp;Name, bool Is64)</td>
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


<div class="doxySectionDef">

## Functions

### defaultLimits() {#a309c949ceae23cdcb7edd4ab0c65da49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">wasm::WasmLimits anonymous{WebAssemblyAsmParser.cpp}::defaultLimits ()</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a59b99a8ddca474dff358ee96d7a5b9ada6b795ffd15b7b08b9a936f6fd6d0c6a7">llvm::wasm::WASM_LIMITS_FLAG_NONE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a4e07e3e64caa97fc5dbc73fe0b20d311">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseDirective</a>.</p>

</div>
</div>

### getOrCreateFunctionTableSymbol() {#a97776aecc75fa260afa954c88a1bfed6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbolWasm * anonymous{WebAssemblyAsmParser.cpp}::getOrCreateFunctionTableSymbol (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Name, bool Is64)</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a5a2f276f396875ef912e9b13ba292663">llvm::MCSymbolWasm::isFunctionTable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a54d32c6868ad27b8c94d4d0e7134af2a">llvm::MCSymbolWasm::setFunctionTable</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab65fa2b7850f38cafbc74ab99c3a3fed">llvm::MCSymbol::setUndefined</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#ab187a7eb85dd13023d632131620364ac">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::Initialize</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#ab7dfefac8dca2f4b81a848e540e14031">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseFunctionTableOperand</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
