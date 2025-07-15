---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/wasmsymbol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `WasmSymbol` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::object::WasmSymbol { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">llvm/Object/Wasm.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb1e59df6fe134e48b166db844159749">WasmSymbol</a> (const wasm::WasmSymbolInfo &amp;Info, const wasm::WasmGlobalType *GlobalType, const wasm::WasmTableType *TableType, const wasm::WasmSignature *Signature)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22b4b2a57873f6d1d6e6c316f7e3ea7b">isTypeFunction</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d2fef8d962883e538bdb8e51b877851">isTypeTable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52ede2afce98daf76e64fd288d950379">isTypeData</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad93edb458875dd3631fa9e90f44790e1">isTypeGlobal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a810a65311ca4a0f4c78faeecf5bcbbc1">isTypeSection</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb7dffe4879c96ebb3b61df3096f1d5b">isTypeTag</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae576177c42a184ad8f6f494270982b16">isDefined</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab483e83f971b109566d148bb9fd25df">isUndefined</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a697b42f53e6e919b13c60a7b647bac3b">isBindingWeak</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f9f21a88a764578a7fa23db783c84e6">isBindingGlobal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2b0f34e9a47c8bfb482d4860ba645fa">isBindingLocal</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26b3068ba1c573a699fbc597428b4fae">getBinding</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8abb5a62bf89aff00e93fc2431a9e316">isHidden</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95704b849e81f7a95ebac973a008772b">getVisibility</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbc181f7d08ad3f2e82a96f055dc77ff">print</a> (raw_ostream &amp;Out) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3412ba697c4c2976a8b1fca317eea863">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsymbolinfo">wasm::WasmSymbolInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98e191e206c3b67a7d846f2a524debda">Info</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmglobaltype">wasm::WasmGlobalType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba43904398ddc9ddad390d48b0e965ed">GlobalType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmtabletype">wasm::WasmTableType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc9b889fdbc542e99396eeda3ce3916e">TableType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsignature">wasm::WasmSignature</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcdeab093670e007a8239b64bca6d27d">Signature</a></td>
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


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WasmSymbol() {#abb1e59df6fe134e48b166db844159749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::WasmSymbol::WasmSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsymbolinfo">wasm::WasmSymbolInfo</a> &amp; Info, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmglobaltype">wasm::WasmGlobalType</a> * GlobalType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmtabletype">wasm::WasmTableType</a> * TableType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsignature">wasm::WasmSignature</a> * Signature)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aba43904398ddc9ddad390d48b0e965ed">GlobalType</a>, <a href="#a98e191e206c3b67a7d846f2a524debda">Info</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsignature/#aba94b7f759be3145a1b804a6efef1f32ab0581545eba3efc6ff73269a73910a1a">llvm::wasm::WasmSignature::Placeholder</a>, <a href="#adcdeab093670e007a8239b64bca6d27d">Signature</a> and <a href="#abc9b889fdbc542e99396eeda3ce3916e">TableType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a3412ba697c4c2976a8b1fca317eea863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void WasmSymbol::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#abbc181f7d08ad3f2e82a96f055dc77ff">print</a>.</p>

</div>
</div>

### getBinding() {#a26b3068ba1c573a699fbc597428b4fae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::object::WasmSymbol::getBinding ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>References <a href="#a98e191e206c3b67a7d846f2a524debda">Info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a83c6245440a6ba5d9bbbf75de39e6b17">llvm::wasm::WASM_SYMBOL_BINDING_MASK</a>.</p>


<p>Referenced by <a href="#a8f9f21a88a764578a7fa23db783c84e6">isBindingGlobal</a>, <a href="#ad2b0f34e9a47c8bfb482d4860ba645fa">isBindingLocal</a>, <a href="#a697b42f53e6e919b13c60a7b647bac3b">isBindingWeak</a> and <a href="#abbc181f7d08ad3f2e82a96f055dc77ff">print</a>.</p>

</div>
</div>

### getVisibility() {#a95704b849e81f7a95ebac973a008772b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::object::WasmSymbol::getVisibility ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>References <a href="#a98e191e206c3b67a7d846f2a524debda">Info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#adbb7f68b4c714a9fa6ed5b4735afca1f">llvm::wasm::WASM_SYMBOL_VISIBILITY_MASK</a>.</p>


<p>Referenced by <a href="#a8abb5a62bf89aff00e93fc2431a9e316">isHidden</a>.</p>

</div>
</div>

### isBindingGlobal() {#a8f9f21a88a764578a7fa23db783c84e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmSymbol::isBindingGlobal ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>References <a href="#a26b3068ba1c573a699fbc597428b4fae">getBinding</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a3a46d26a9a9412217ce62b8154629ff6">llvm::wasm::WASM_SYMBOL_BINDING_GLOBAL</a>.</p>

</div>
</div>

### isBindingLocal() {#ad2b0f34e9a47c8bfb482d4860ba645fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmSymbol::isBindingLocal ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>References <a href="#a26b3068ba1c573a699fbc597428b4fae">getBinding</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a52bbcd525e04e81b8ae65758bf73463d">llvm::wasm::WASM_SYMBOL_BINDING_LOCAL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a33b0926d82731e04416d8528bf864405">llvm::object::WasmObjectFile::getSymbolFlags</a>.</p>

</div>
</div>

### isBindingWeak() {#a697b42f53e6e919b13c60a7b647bac3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmSymbol::isBindingWeak ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>References <a href="#a26b3068ba1c573a699fbc597428b4fae">getBinding</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a4acc7b0e22b2ec8231322d927cf9d562">llvm::wasm::WASM_SYMBOL_BINDING_WEAK</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a33b0926d82731e04416d8528bf864405">llvm::object::WasmObjectFile::getSymbolFlags</a>.</p>

</div>
</div>

### isDefined() {#ae576177c42a184ad8f6f494270982b16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmSymbol::isDefined ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>Reference <a href="#aab483e83f971b109566d148bb9fd25df">isUndefined</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a33b0926d82731e04416d8528bf864405">llvm::object::WasmObjectFile::getSymbolFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#ae34ddc299f0c959d7c22636cf103c2f1">llvm::object::WasmObjectFile::getSymbolSize</a> and <a href="#abbc181f7d08ad3f2e82a96f055dc77ff">print</a>.</p>

</div>
</div>

### isHidden() {#a8abb5a62bf89aff00e93fc2431a9e316}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmSymbol::isHidden ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>References <a href="#a95704b849e81f7a95ebac973a008772b">getVisibility</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#ae0c01d22ca81ccde89fab456512fc7f0">llvm::wasm::WASM_SYMBOL_VISIBILITY_HIDDEN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a33b0926d82731e04416d8528bf864405">llvm::object::WasmObjectFile::getSymbolFlags</a> and <a href="#abbc181f7d08ad3f2e82a96f055dc77ff">print</a>.</p>

</div>
</div>

### isTypeData() {#a52ede2afce98daf76e64fd288d950379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmSymbol::isTypeData ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>References <a href="#a98e191e206c3b67a7d846f2a524debda">Info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a3bf8c7186acf1ffbf50c1f7c915554bb">llvm::wasm::WASM_SYMBOL_TYPE_DATA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#ae34ddc299f0c959d7c22636cf103c2f1">llvm::object::WasmObjectFile::getSymbolSize</a> and <a href="#abbc181f7d08ad3f2e82a96f055dc77ff">print</a>.</p>

</div>
</div>

### isTypeFunction() {#a22b4b2a57873f6d1d6e6c316f7e3ea7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmSymbol::isTypeFunction ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>References <a href="#a98e191e206c3b67a7d846f2a524debda">Info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529ae2d3246e8f9451c96b200707078c83d9">llvm::wasm::WASM_SYMBOL_TYPE_FUNCTION</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a33b0926d82731e04416d8528bf864405">llvm::object::WasmObjectFile::getSymbolFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#ae34ddc299f0c959d7c22636cf103c2f1">llvm::object::WasmObjectFile::getSymbolSize</a>.</p>

</div>
</div>

### isTypeGlobal() {#ad93edb458875dd3631fa9e90f44790e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmSymbol::isTypeGlobal ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>References <a href="#a98e191e206c3b67a7d846f2a524debda">Info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a36f3d68b8025222c9f73a586aee5932f">llvm::wasm::WASM_SYMBOL_TYPE_GLOBAL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#ae34ddc299f0c959d7c22636cf103c2f1">llvm::object::WasmObjectFile::getSymbolSize</a>.</p>

</div>
</div>

### isTypeSection() {#a810a65311ca4a0f4c78faeecf5bcbbc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmSymbol::isTypeSection ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>References <a href="#a98e191e206c3b67a7d846f2a524debda">Info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529ad7d988e101231ece62ebfe7d06884a1f">llvm::wasm::WASM_SYMBOL_TYPE_SECTION</a>.</p>

</div>
</div>

### isTypeTable() {#a5d2fef8d962883e538bdb8e51b877851}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmSymbol::isTypeTable ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>References <a href="#a98e191e206c3b67a7d846f2a524debda">Info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a7e6d4cfa5233363b413a1b9997c98d7c">llvm::wasm::WASM_SYMBOL_TYPE_TABLE</a>.</p>

</div>
</div>

### isTypeTag() {#acb7dffe4879c96ebb3b61df3096f1d5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmSymbol::isTypeTag ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>References <a href="#a98e191e206c3b67a7d846f2a524debda">Info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a47169d0c34c301e7580280da4dc576a6">llvm::wasm::WASM_SYMBOL_TYPE_TAG</a>.</p>

</div>
</div>

### isUndefined() {#aab483e83f971b109566d148bb9fd25df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmSymbol::isUndefined ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>References <a href="#a98e191e206c3b67a7d846f2a524debda">Info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a03a447639436518ce8825dc21cab5cc9">llvm::wasm::WASM_SYMBOL_UNDEFINED</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#ac663c397d2633e31dac4bf80c5840a78">llvm::object::WasmObjectFile::getSymbolSection</a> and <a href="#ae576177c42a184ad8f6f494270982b16">isDefined</a>.</p>

</div>
</div>

### print() {#abbc181f7d08ad3f2e82a96f055dc77ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WasmSymbol::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#a26b3068ba1c573a699fbc597428b4fae">getBinding</a>, <a href="#a98e191e206c3b67a7d846f2a524debda">Info</a>, <a href="#ae576177c42a184ad8f6f494270982b16">isDefined</a>, <a href="#a8abb5a62bf89aff00e93fc2431a9e316">isHidden</a>, <a href="#a52ede2afce98daf76e64fd288d950379">isTypeData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba83a013c55b19255697393a10d9165e">llvm::toString</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a3a46d26a9a9412217ce62b8154629ff6">llvm::wasm::WASM_SYMBOL_BINDING_GLOBAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a52bbcd525e04e81b8ae65758bf73463d">llvm::wasm::WASM_SYMBOL_BINDING_LOCAL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a4acc7b0e22b2ec8231322d927cf9d562">llvm::wasm::WASM_SYMBOL_BINDING_WEAK</a>.</p>


<p>Referenced by <a href="#a3412ba697c4c2976a8b1fca317eea863">dump</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8487cec5d339c2d1de29d34869fab29b">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### GlobalType {#aba43904398ddc9ddad390d48b0e965ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const wasm::WasmGlobalType* llvm::object::WasmSymbol::GlobalType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>Referenced by <a href="#abb1e59df6fe134e48b166db844159749">WasmSymbol</a>.</p>

</div>
</div>

### Info {#a98e191e206c3b67a7d846f2a524debda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">wasm::WasmSymbolInfo llvm::object::WasmSymbol::Info</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>Referenced by <a href="#a26b3068ba1c573a699fbc597428b4fae">getBinding</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a6e9f3f7b04ea93857f5d16ee84c2646b">llvm::object::WasmObjectFile::getSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#ae34ddc299f0c959d7c22636cf103c2f1">llvm::object::WasmObjectFile::getSymbolSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a1128d16fcbf1d12b0a2f879dbd5a2fb2">llvm::object::WasmObjectFile::getSymbolType</a>, <a href="#a95704b849e81f7a95ebac973a008772b">getVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a17d258c3f5b6b5e3d7d0a192aac0b188">llvm::object::WasmObjectFile::getWasmSymbolValue</a>, <a href="#a52ede2afce98daf76e64fd288d950379">isTypeData</a>, <a href="#a22b4b2a57873f6d1d6e6c316f7e3ea7b">isTypeFunction</a>, <a href="#ad93edb458875dd3631fa9e90f44790e1">isTypeGlobal</a>, <a href="#a810a65311ca4a0f4c78faeecf5bcbbc1">isTypeSection</a>, <a href="#a5d2fef8d962883e538bdb8e51b877851">isTypeTable</a>, <a href="#acb7dffe4879c96ebb3b61df3096f1d5b">isTypeTag</a>, <a href="#aab483e83f971b109566d148bb9fd25df">isUndefined</a>, <a href="#abbc181f7d08ad3f2e82a96f055dc77ff">print</a> and <a href="#abb1e59df6fe134e48b166db844159749">WasmSymbol</a>.</p>

</div>
</div>

### Signature {#adcdeab093670e007a8239b64bca6d27d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const wasm::WasmSignature* llvm::object::WasmSymbol::Signature</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>Referenced by <a href="#abb1e59df6fe134e48b166db844159749">WasmSymbol</a>.</p>

</div>
</div>

### TableType {#abc9b889fdbc542e99396eeda3ce3916e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const wasm::WasmTableType* llvm::object::WasmSymbol::TableType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>Referenced by <a href="#abb1e59df6fe134e48b166db844159749">WasmSymbol</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
