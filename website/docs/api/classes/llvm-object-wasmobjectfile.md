---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/wasmobjectfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WasmObjectFile` Class



## Declaration

<div class="doxyDeclaration">
class llvm::object::WasmObjectFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">llvm/Object/Wasm.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is the base class for all object file types. <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78b45ebf4772364c848d6aedf38fd199">WasmObjectFile</a> (MemoryBufferRef Object, Error &amp;Err)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmobjectheader">wasm::WasmObjectHeader</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad06eb30f00a363db909c4d23e89225f6">getHeader</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol">WasmSymbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb7e136e9de32a391575d7f236ed9b71">getWasmSymbol</a> (const DataRefImpl &amp;Symb) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol">WasmSymbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b97101d75c9c68d1d2cdcbe733cb80c">getWasmSymbol</a> (const SymbolRef &amp;Symbol) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/wasmsection">WasmSection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9204e81d88bc6fc86d82831d13beb0f">getWasmSection</a> (const SectionRef &amp;Section) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmrelocation">wasm::WasmRelocation</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcc00d1267df0ecc8d7a6d18caf4dbd0">getWasmRelocation</a> (const RelocationRef &amp;Ref) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmdylinkinfo">wasm::WasmDylinkInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6caacbd89d19012d04a98812408d7ef">dylinkInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmproducerinfo">wasm::WasmProducerInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cc31d1082ab2594a844bdd6f47e1a5d">getProducerInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmfeatureentry">wasm::WasmFeatureEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab02f673d7957d581ff8564795fe25d6e">getTargetFeatures</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsignature">wasm::WasmSignature</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16ce863ffe13406410fea38e1710bdac">types</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmimport">wasm::WasmImport</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f6986af7115ea070d8ea80bca3eefe4">imports</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmtable">wasm::WasmTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac77f887ebfaa51b54fc0db2ef6e68ded">tables</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmlimits">wasm::WasmLimits</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d295864da5ece728c945a44056e7473">memories</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmglobal">wasm::WasmGlobal</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1a3717c799260aebdbecffcc520eadd">globals</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmtag">wasm::WasmTag</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7851d9cefb2cb935b5d760c6cf78a1fb">tags</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmexport">wasm::WasmExport</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5921b77df8b8cf6b15cec7f57410c4be">exports</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmlinkingdata">wasm::WasmLinkingData</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa55c9ca7c3064fa7a21278cc801f011">linkingData</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48c128d46ef3ca34ef75deae9558e253">getNumberOfSymbols</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmelemsegment">wasm::WasmElemSegment</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a228a1a905ae7df6cf6244f86aaf2286e">elements</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/wasmsegment">WasmSegment</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbc2e0650b48ed8753ae18f8fb2b7eaf">dataSegments</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmfunction">wasm::WasmFunction</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea6d019ccfd1f1131eb8665b4a52460b">functions</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmdebugname">wasm::WasmDebugName</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ab7ce7d090fe53f4631c59e9e07b74f">debugNames</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a321e801f073a2f55226e02053627b6ff">startFunction</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af398aedca6afba6b78ba58567e5010d2">getNumImportedGlobals</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2568dfc59c64aa5ea04257186ac6f85">getNumImportedTables</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3cb98babd68912bf3bed2420e4c92ad">getNumImportedFunctions</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62027a0565919070a2c35d87a2d67787">getNumImportedTags</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdc2834b5d5cd3325e93cc8cf646f754">getNumSections</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05bc4cd6519742157a6df78c18834252">moveSymbolNext</a> (DataRefImpl &amp;Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33b0926d82731e04416d8528bf864405">getSymbolFlags</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a5bf1bfacdebc64c1f70e3b2861ba76eb">basic_symbol_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02801821ae5fdb77c109244e84c77341">symbol_begin</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a5bf1bfacdebc64c1f70e3b2861ba76eb">basic_symbol_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30d36ada5b3d98a7e0bf17e1d2816da6">symbol_end</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e9f3f7b04ea93857f5d16ee84c2646b">getSymbolName</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e5f94f34b30ae0c423bfa15c643b491">is64Bit</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2a2757f91471e6b80ccffa7840cb154">getSymbolAddress</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17d258c3f5b6b5e3d7d0a192aac0b188">getWasmSymbolValue</a> (const WasmSymbol &amp;Sym) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ddc24dc2cdfcf8c8a407336306bb1d8">getSymbolValueImpl</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99b4a81ee84e2e2a967e4fee290efaba">getSymbolAlignment</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64380ff2c12bb4d1c84a93efd9931a66">getCommonSymbolSizeImpl</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04">SymbolRef::Type</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1128d16fcbf1d12b0a2f879dbd5a2fb2">getSymbolType</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac663c397d2633e31dac4bf80c5840a78">getSymbolSection</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a527185d51f8cd613611201b0ba35c4db">getSymbolSectionId</a> (SymbolRef Sym) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae34ddc299f0c959d7c22636cf103c2f1">getSymbolSize</a> (SymbolRef Sym) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1407f36011632e33a5fdd6cce369717">moveSectionNext</a> (DataRefImpl &amp;Sec) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe6783adf1a19511d1e8960996e8dcdd">getSectionName</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeca0f961d1e606d6c85649cb7805fbd3">getSectionAddress</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89dcc59abc9b3f4dad37782d053febcb">getSectionIndex</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7c80d89ddf584fde12a68516fe703c2">getSectionSize</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a851f27408d0faaa00930a43c3c3f0453">getSectionContents</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0960395891a8656b41d6fd373f59f0ce">getSectionAlignment</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5457c2e49cc8c005336f69ff02c9f1bd">isSectionCompressed</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25105b42581ad941bfbf55b4b89819fa">isSectionText</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbdfae040884e2bfd5a26f82f26a0d8c">isSectionData</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fad2affa7a157557a3af8e41230aaa4">isSectionBSS</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57d41740338f82d6be7ac1118a8ba11f">isSectionVirtual</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75c2cc14199307ebc8e9a27cd3630ed0">section_rel_begin</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03425ecd6379bfd3afa9e0be578fc3c5">section_rel_end</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43603839618af034988efc03427a91ca">moveRelocationNext</a> (DataRefImpl &amp;Rel) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c7ea6d35ebdd6f8b934e2dca2be7cf7">getRelocationOffset</a> (DataRefImpl Rel) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/symbol-iterator">symbol_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acab3ba419eaa03698db0773f121a8075">getRelocationSymbol</a> (DataRefImpl Rel) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1f3bdc28bdf53fdb25720bdba033e57">getRelocationType</a> (DataRefImpl Rel) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6902b7a4807f72288afd6e2c9bbbb721">getRelocationTypeName</a> (DataRefImpl Rel, SmallVectorImpl&lt; char &gt; &amp;Result) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b0d45e8e8093653af68f7567eb67f25">section_begin</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8349576fbde57780d1474b92f0352127">section_end</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77096036fa5993812f743394fee53bde">getBytesInAddress</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of bytes used to represent an address in this object file format. <a href="#a77096036fa5993812f743394fee53bde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ceba8d19595680fc90421470749fce2">getFileFormatName</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154">Triple::ArchType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabaffcbd691d5ea368e6ced4f6455309">getArch</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures">SubtargetFeatures</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd4662d6d72a2b37b241ca9b81f59d41">getFeatures</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40560d147674d89938435e6f1e359a87">isRelocatableObject</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is a relocatable object (.o/.obj). <a href="#a40560d147674d89938435e6f1e359a87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4d7dd7b27216ddfd472a0d19092ef95">isSharedObject</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a316094dd3f1c9126ec12b8188c80a43c">hasUnmodeledTypes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5255bf481c65baa9345f2144f5ffb00">isValidFunctionIndex</a> (uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0c1c5983d1f5d8a4e8cfed5917d9e9c">isDefinedFunctionIndex</a> (uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbca895d36b15ddeab2d5efddc46f208">isValidGlobalIndex</a> (uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ae279e6df5c1f24a07119b675ddddc3">isValidTableNumber</a> (uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8de02f0a228c61290365e69d39dbe3bd">isDefinedGlobalIndex</a> (uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47ee7764c3ccbbe99ec88f61261298fb">isDefinedTableNumber</a> (uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeb38e970e394749a52cee86270ba2cd">isValidTagIndex</a> (uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a417d205fb281cc2a8f07c90376414457">isDefinedTagIndex</a> (uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf5f7f4f6cf5279f8252ddd13fd02148">isValidFunctionSymbol</a> (uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9c710b5abeb1c33ff7b1e4261442329">isValidTableSymbol</a> (uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc948da2b560cc8124862aa288e15a1">isValidGlobalSymbol</a> (uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c7ac5735e715a386acf31ed94eae39d">isValidTagSymbol</a> (uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6971471fc71d591d8206922fece04d79">isValidDataSymbol</a> (uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8f383a425a7bbbb41d05ed361ee10d6">isValidSectionSymbol</a> (uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/wasm/wasmfunction">wasm::WasmFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f34118f8ede9b912e6e398a5dc5c1c7">getDefinedFunction</a> (uint32_t Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmfunction">wasm::WasmFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0455ccb3d2256a542ce58542ed21e481">getDefinedFunction</a> (uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmglobal">wasm::WasmGlobal</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8de15a2c15c595c345c6afbcb1b208ba">getDefinedGlobal</a> (uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/wasm/wasmtag">wasm::WasmTag</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9906081cb763a0c6f01cc1cdda159870">getDefinedTag</a> (uint32_t Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/wasmsection">WasmSection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc37f470e882a24167450fa561138926">getWasmSection</a> (DataRefImpl Ref) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmrelocation">wasm::WasmRelocation</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf91f46e07dda118c4dd3178e861a850">getWasmRelocation</a> (DataRefImpl Ref) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97291100ad8046b3953729f0182ce96c">getSymbolSectionIdImpl</a> (const WasmSymbol &amp;Symb) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61f7f959e52a2871465b796339934851">parseSection</a> (WasmSection &amp;Sec)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07b999263b8101951598fb5aa0572bb9">parseCustomSection</a> (WasmSection &amp;Sec, ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7308d4794c76526497376e5bc5ef1cd">parseTypeSection</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a642a6426e366f25fe02df9f1e23fca6a">parseImportSection</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbc5ed801cfd8ccd3a50a198499fb948">parseFunctionSection</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21328ffb1d46e9c50f7927517b8a1c23">parseTableSection</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8a9ecc27582804571ac81880b1b7dcd">parseMemorySection</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2a4f832e6980c5ce82b1468c14c8a2a">parseTagSection</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9b07a9c4017f9522e8c0649ac4e427d">parseGlobalSection</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92737c5a9d2bd3070ec21bc2bb188929">parseExportSection</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbf5bfb3e34f94f438f528916352226b">parseStartSection</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af36ecd85c357864c9a41e4d0e2994844">parseElemSection</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0b8cee247db4c6ad2c375a2fda39899">parseCodeSection</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a577a689177af274b296bdafe5098ad89">parseDataSection</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8be5c0482efcbceb059814c53a5244c7">parseDataCountSection</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc8363b94be9182c0152f2981020ab52">parseDylinkSection</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a0f641ac37aa39776ef9dd2450f7f84">parseDylink0Section</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a041f547939a824293e13641fba452ad1">parseNameSection</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14dc94ba358f40e3afc4517d67208e9f">parseLinkingSection</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdcd062d6ad73f8f98a78df1f7f586aa">parseLinkingSectionSymtab</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2622e97139cfa70eb480849371cf6ef">parseLinkingSectionComdat</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61bf7edf42d344a740761afe8d3c3234">parseProducersSection</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83cd315bffb219e9b5da49ef8aaeacee">parseTargetFeaturesSection</a> (ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72a45aa94ca94a6da2226e6714b9e2e1">parseRelocSection</a> (StringRef Name, ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/wasm/wasmobjectheader">wasm::WasmObjectHeader</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4884d22e9d9b5f22266ff9c240b8a01b">Header</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/object/wasmsection">WasmSection</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ba041d330e672edc9da3b91a245d2fd">Sections</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/wasm/wasmdylinkinfo">wasm::WasmDylinkInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95e2a35e343f15859dca18ccbedbc039">DylinkInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/wasm/wasmproducerinfo">wasm::WasmProducerInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a428156ec7927c79dcbffe1ad06572849">ProducerInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmfeatureentry">wasm::WasmFeatureEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d52ba8eb2d7a14cc8088b77e0b85afe">TargetFeatures</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsignature">wasm::WasmSignature</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff3ef4e32aa05ab37cf56c16e53a863b">Signatures</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmtable">wasm::WasmTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c82ae1de7578522e387f50305b9ac9b">Tables</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmlimits">wasm::WasmLimits</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad03df8f4ed63d7745283342c4002f22">Memories</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmglobal">wasm::WasmGlobal</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3be4a5279fa3ebcc575c001c3be0a566">Globals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmtag">wasm::WasmTag</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67eb4346eae6596d2733d0f94e46af5b">Tags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmimport">wasm::WasmImport</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef08e43508dc82ae6aad313d2e364f07">Imports</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmexport">wasm::WasmExport</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb68ebe1975c75fa77ce766edfa71b58">Exports</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmelemsegment">wasm::WasmElemSegment</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac21f50b0ce04d013436d27ec80c2c069">ElemSegments</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/object/wasmsegment">WasmSegment</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76b7ba2ac5310d8ce2dc8613e4231f5a">DataSegments</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01011ac4fe84118138c8819241c5d4bc">DataCount</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmfunction">wasm::WasmFunction</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb248ba30b9c1b3882a78df2ff081a1a">Functions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol">WasmSymbol</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21b470d8a81c410d330e76743f3eb129">Symbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmdebugname">wasm::WasmDebugName</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67af089851e64225cd11bd686f990629">DebugNames</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67ec2227850a9e5826f04e56ee48145d">StartFunction</a> = -1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11295f03914923cb8352a407bd3b9c14">HasLinkingSection</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ac3d80ce75fc3f38f73d72974470d86">HasDylinkSection</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9549419af0a115086e571641010c964c">HasMemory64</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83999d57affcea4e4a24fb7fa208a3c0">HasUnmodeledTypes</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/wasm/wasmlinkingdata">wasm::WasmLinkingData</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7ebde9a2cd0b3d450247e9ae481c7e5">LinkingData</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9253655545920368b57df475a5cbfcd2">NumImportedGlobals</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a921f2934965e3459cd3fb2694dbf0c3b">NumImportedTables</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8b23cb96bb3bffb5dd8f270590be982">NumImportedFunctions</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dc17a46814812a62defb19c0108f7b3">NumImportedTags</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add85b9b6c8acca5b5a4aae39275aa345">CodeSection</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d3c426408e5b53e69ef5d17eb61198d">DataSection</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88077bbe29025e112864905d11871930">TagSection</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61498365c87a58665acc544f526ff88d">GlobalSection</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6f120cf679e55e01fd693462fa4de14">TableSection</a> = 0</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf0542a10157b39246aa615422558497">classof</a> (const Binary *v)</td>
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


<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WasmObjectFile() {#a78b45ebf4772364c848d6aedf38fd199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WasmObjectFile::WasmObjectFile (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#adbc826dc76fd535f887e035d1795aa84">llvm::StringRef::bytes_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#af4e569b1876c0dbd751c766d6a1b926aa6549e4e09bf7fce24603d7c6e69040b6">llvm::object::Binary::ID_Wasm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#af74504142c7146b3602a3aa280d07df7">llvm::object::ObjectFile::ObjectFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp/#a67951f7188e316333fc6cf733db7f71f">readSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp/#a84247b20b236408869fe2931b9c744be">readUint32</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext/#aeb89f8e95555b6c91698e1fc9c78e5c3">llvm::object::WasmObjectFile::ReadContext::Start</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6f25ca50bd62389cc3743c6a4c8173ae">llvm::wasm::WasmVersion</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dataSegments() {#adbc2e0650b48ed8753ae18f8fb2b7eaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; WasmSegment &gt; llvm::object::WasmObjectFile::dataSegments ()</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### debugNames() {#a9ab7ce7d090fe53f4631c59e9e07b74f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; wasm::WasmDebugName &gt; llvm::object::WasmObjectFile::debugNames ()</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### dylinkInfo() {#ae6caacbd89d19012d04a98812408d7ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const wasm::WasmDylinkInfo &amp; llvm::object::WasmObjectFile::dylinkInfo ()</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### elements() {#a228a1a905ae7df6cf6244f86aaf2286e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; wasm::WasmElemSegment &gt; llvm::object::WasmObjectFile::elements ()</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### exports() {#a5921b77df8b8cf6b15cec7f57410c4be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; wasm::WasmExport &gt; llvm::object::WasmObjectFile::exports ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### functions() {#aea6d019ccfd1f1131eb8665b4a52460b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; wasm::WasmFunction &gt; llvm::object::WasmObjectFile::functions ()</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>Referenced by <a href="#ae34ddc299f0c959d7c22636cf103c2f1">getSymbolSize</a>.</p>

</div>
</div>

### getArch() {#aabaffcbd691d5ea368e6ced4f6455309}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::ArchType WasmObjectFile::getArch ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2102 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ac0478f40eaacc5f340e93827756e7a33">llvm::Triple::wasm32</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ad6b7ed7027706d2960e771c6374025b1">llvm::Triple::wasm64</a>.</p>

</div>
</div>

### getBytesInAddress() {#a77096036fa5993812f743394fee53bde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t WasmObjectFile::getBytesInAddress ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of bytes used to represent an address in this object file format.</p>

<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2096 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### getCommonSymbolSizeImpl() {#a64380ff2c12bb4d1c84a93efd9931a66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t WasmObjectFile::getCommonSymbolSizeImpl (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1893 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getFeatures() {#acd4662d6d72a2b37b241ca9b81f59d41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SubtargetFeatures &gt; WasmObjectFile::getFeatures ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2106 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### getFileFormatName() {#a6ceba8d19595680fc90421470749fce2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef WasmObjectFile::getFileFormatName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2100 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### getHeader() {#ad06eb30f00a363db909c4d23e89225f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const wasm::WasmObjectHeader &amp; WasmObjectFile::getHeader ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1783 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### getNumberOfSymbols() {#a48c128d46ef3ca34ef75deae9558e253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmObjectFile::getNumberOfSymbols ()</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### getNumImportedFunctions() {#ad3cb98babd68912bf3bed2420e4c92ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmObjectFile::getNumImportedFunctions ()</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>


<p>Referenced by <a href="#ae34ddc299f0c959d7c22636cf103c2f1">getSymbolSize</a>.</p>

</div>
</div>

### getNumImportedGlobals() {#af398aedca6afba6b78ba58567e5010d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmObjectFile::getNumImportedGlobals ()</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### getNumImportedTables() {#ab2568dfc59c64aa5ea04257186ac6f85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmObjectFile::getNumImportedTables ()</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### getNumImportedTags() {#a62027a0565919070a2c35d87a2d67787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmObjectFile::getNumImportedTags ()</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### getNumSections() {#afdc2834b5d5cd3325e93cc8cf646f754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmObjectFile::getNumSections ()</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### getProducerInfo() {#a2cc31d1082ab2594a844bdd6f47e1a5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const wasm::WasmProducerInfo &amp; llvm::object::WasmObjectFile::getProducerInfo ()</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### getRelocationOffset() {#a0c7ea6d35ebdd6f8b934e2dca2be7cf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t WasmObjectFile::getRelocationOffset (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2045 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#adcc00d1267df0ecc8d7a6d18caf4dbd0">getWasmRelocation</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmrelocation/#ab7701cf7646b6b8edbf005b1288504b8">llvm::wasm::WasmRelocation::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

### getRelocationSymbol() {#acab3ba419eaa03698db0773f121a8075}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">symbol_iterator WasmObjectFile::getRelocationSymbol (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2050 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2820613261c431d4de10b49e30b90ae4">llvm::object::DataRefImpl::b</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="#adcc00d1267df0ecc8d7a6d18caf4dbd0">getWasmRelocation</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmrelocation/#afe2562c41cb36ab150381294286b1bcb">llvm::wasm::WasmRelocation::Index</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>, <a href="#a30d36ada5b3d98a7e0bf17e1d2816da6">symbol_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a23fe52bbc164a30ba18e057d37bd2283">llvm::object::ObjectFile::SymbolRef</a> and <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmrelocation/#aac7bbac66690c003799967428a1c1957">llvm::wasm::WasmRelocation::Type</a>.</p>

</div>
</div>

### getRelocationType() {#ab1f3bdc28bdf53fdb25720bdba033e57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t WasmObjectFile::getRelocationType (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2060 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#adcc00d1267df0ecc8d7a6d18caf4dbd0">getWasmRelocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmrelocation/#aac7bbac66690c003799967428a1c1957">llvm::wasm::WasmRelocation::Type</a>.</p>

</div>
</div>

### getRelocationTypeName() {#a6902b7a4807f72288afd6e2c9bbbb721}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WasmObjectFile::getRelocationTypeName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Result)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2065 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="#adcc00d1267df0ecc8d7a6d18caf4dbd0">getWasmRelocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmrelocation/#aac7bbac66690c003799967428a1c1957">llvm::wasm::WasmRelocation::Type</a>.</p>

</div>
</div>

### getSectionAddress() {#aeca0f961d1e606d6c85649cb7805fbd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t WasmObjectFile::getSectionAddress (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1983 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="#a40560d147674d89938435e6f1e359a87">isRelocatableObject</a> and <a href="#ad4d7dd7b27216ddfd472a0d19092ef95">isSharedObject</a>.</p>


<p>Referenced by <a href="#af2a2757f91471e6b80ccffa7840cb154">getSymbolAddress</a>.</p>

</div>
</div>

### getSectionAlignment() {#a0960395891a8656b41d6fd373f59f0ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t WasmObjectFile::getSectionAlignment (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2008 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### getSectionContents() {#a851f27408d0faaa00930a43c3c3f0453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ArrayRef&lt; uint8_t &gt; &gt; WasmObjectFile::getSectionContents (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2001 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/structs/llvm/object/wasmsection/#a1649dfc662bba0263b3f9b2068e36db7">llvm::object::WasmSection::Content</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>.</p>

</div>
</div>

### getSectionIndex() {#a89dcc59abc9b3f4dad37782d053febcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t WasmObjectFile::getSectionIndex (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1991 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>.</p>

</div>
</div>

### getSectionName() {#afe6783adf1a19511d1e8960996e8dcdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; WasmObjectFile::getSectionName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1974 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20a0352e6404e8f88399d202d70b5bf34f9">llvm::object::invalid_section_index</a>, <a href="/web-llvm/docs/api/structs/llvm/object/wasmsection/#a46cceeb4e726b13eed910331a41ef7df">llvm::object::WasmSection::Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#ac737e1f79f17b2a3b9abb858d18257cc">llvm::wasm::sectionTypeToString</a>, <a href="/web-llvm/docs/api/structs/llvm/object/wasmsection/#aee122f9e75e7ae929d7080d19835ecf4">llvm::object::WasmSection::Type</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaa685069a810d109e09f4af7d2d115a8cd">llvm::wasm::WASM_SEC_CUSTOM</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaa5f11ab73cf94ba99f69b836f2c39c8fd">llvm::wasm::WASM_SEC_LAST_KNOWN</a>.</p>

</div>
</div>

### getSectionSize() {#aa7c80d89ddf584fde12a68516fe703c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t WasmObjectFile::getSectionSize (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1995 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/structs/llvm/object/wasmsection/#a1649dfc662bba0263b3f9b2068e36db7">llvm::object::WasmSection::Content</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### getSymbolAddress() {#af2a2757f91471e6b80ccffa7840cb154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; WasmObjectFile::getSymbolAddress (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1833 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#aeca0f961d1e606d6c85649cb7805fbd3">getSectionAddress</a>, <a href="#ac663c397d2633e31dac4bf80c5840a78">getSymbolSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aa520e1a721f81e1befb66b422c6e4a60">llvm::object::ObjectFile::getSymbolValue</a>, <a href="#aeb7e136e9de32a391575d7f236ed9b71">getWasmSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529ae2d3246e8f9451c96b200707078c83d9">llvm::wasm::WASM_SYMBOL_TYPE_FUNCTION</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a36f3d68b8025222c9f73a586aee5932f">llvm::wasm::WASM_SYMBOL_TYPE_GLOBAL</a>.</p>

</div>
</div>

### getSymbolAlignment() {#a99b4a81ee84e2e2a967e4fee290efaba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t WasmObjectFile::getSymbolAlignment (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1888 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getSymbolFlags() {#a33b0926d82731e04416d8528bf864405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint32_t &gt; WasmObjectFile::getSymbolFlags (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1789 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#aeb7e136e9de32a391575d7f236ed9b71">getWasmSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol/#ad2b0f34e9a47c8bfb482d4860ba645fa">llvm::object::WasmSymbol::isBindingLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol/#a697b42f53e6e919b13c60a7b647bac3b">llvm::object::WasmSymbol::isBindingWeak</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol/#ae576177c42a184ad8f6f494270982b16">llvm::object::WasmSymbol::isDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol/#a8abb5a62bf89aff00e93fc2431a9e316">llvm::object::WasmSymbol::isHidden</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol/#a22b4b2a57873f6d1d6e6c316f7e3ea7b">llvm::object::WasmSymbol::isTypeFunction</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a2d0d252cebc6c9ccac230cb8625d8d59">llvm::object::BasicSymbolRef::SF_Executable</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a1cc593ee22b60969ba0a3cb1e5e21b34">llvm::object::BasicSymbolRef::SF_Global</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a204140e5ce85b4dc444bf37cb0d8e402">llvm::object::BasicSymbolRef::SF_Hidden</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1cfe0c449b3dd82ae0eaeff1da6f766">llvm::object::BasicSymbolRef::SF_None</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1131f10939b205635a0dc81ca3c45d7">llvm::object::BasicSymbolRef::SF_Undefined</a> and <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ac199a3dc25299a191397723e89fd303e">llvm::object::BasicSymbolRef::SF_Weak</a>.</p>

</div>
</div>

### getSymbolName() {#a6e9f3f7b04ea93857f5d16ee84c2646b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; WasmObjectFile::getSymbolName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1829 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#aeb7e136e9de32a391575d7f236ed9b71">getWasmSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol/#a98e191e206c3b67a7d846f2a524debda">llvm::object::WasmSymbol::Info</a> and <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsymbolinfo/#a5118230b0e844bc72d1a406b6a47e2c2">llvm::wasm::WasmSymbolInfo::Name</a>.</p>

</div>
</div>

### getSymbolSection() {#ac663c397d2633e31dac4bf80c5840a78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; section_iterator &gt; WasmObjectFile::getSymbolSection (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1922 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#aeb7e136e9de32a391575d7f236ed9b71">getWasmSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol/#aab483e83f971b109566d148bb9fd25df">llvm::object::WasmSymbol::isUndefined</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>, <a href="#a8349576fbde57780d1474b92f0352127">section_end</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>.</p>


<p>Referenced by <a href="#af2a2757f91471e6b80ccffa7840cb154">getSymbolAddress</a>.</p>

</div>
</div>

### getSymbolSectionId() {#a527185d51f8cd613611201b0ba35c4db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t WasmObjectFile::getSymbolSectionId (<a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a> Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1932 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#aeb7e136e9de32a391575d7f236ed9b71">getWasmSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a23fe52bbc164a30ba18e057d37bd2283">llvm::object::ObjectFile::SymbolRef</a>.</p>

</div>
</div>

### getSymbolSize() {#ae34ddc299f0c959d7c22636cf103c2f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t WasmObjectFile::getSymbolSize (<a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a> Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1956 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsymbolinfo/#a1c2252fcc3cebecf1c18f54de08374a6">llvm::wasm::WasmSymbolInfo::DataRef</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsymbolinfo/#af5d3b408e077b06a899f420e5c843aec">llvm::wasm::WasmSymbolInfo::ElementIndex</a>, <a href="#aea6d019ccfd1f1131eb8665b4a52460b">functions</a>, <a href="#ad3cb98babd68912bf3bed2420e4c92ad">getNumImportedFunctions</a>, <a href="#aeb7e136e9de32a391575d7f236ed9b71">getWasmSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol/#a98e191e206c3b67a7d846f2a524debda">llvm::object::WasmSymbol::Info</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol/#ae576177c42a184ad8f6f494270982b16">llvm::object::WasmSymbol::isDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol/#a52ede2afce98daf76e64fd288d950379">llvm::object::WasmSymbol::isTypeData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol/#a22b4b2a57873f6d1d6e6c316f7e3ea7b">llvm::object::WasmSymbol::isTypeFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol/#ad93edb458875dd3631fa9e90f44790e1">llvm::object::WasmSymbol::isTypeGlobal</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmdatareference/#a8d5960590d75afa7f1752bb1c455e724">llvm::wasm::WasmDataReference::Size</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a23fe52bbc164a30ba18e057d37bd2283">llvm::object::ObjectFile::SymbolRef</a>.</p>

</div>
</div>

### getSymbolType() {#a1128d16fcbf1d12b0a2f879dbd5a2fb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SymbolRef::Type &gt; WasmObjectFile::getSymbolType (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1899 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#aeb7e136e9de32a391575d7f236ed9b71">getWasmSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol/#a98e191e206c3b67a7d846f2a524debda">llvm::object::WasmSymbol::Info</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsymbolinfo/#a9256dc33ac966b6f097b26877743273b">llvm::wasm::WasmSymbolInfo::Kind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a8a501fedaaa3e562541580b8f1db3975">llvm::object::SymbolRef::ST_Data</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04afe6722fa933ffee4c116ee60c2de5049">llvm::object::SymbolRef::ST_Debug</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a2fcf5b0171fb8526218be425765b5da1">llvm::object::SymbolRef::ST_Function</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a076f193658db35c0f4d60f9e0a3e329f">llvm::object::SymbolRef::ST_Other</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a3bf8c7186acf1ffbf50c1f7c915554bb">llvm::wasm::WASM_SYMBOL_TYPE_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529ae2d3246e8f9451c96b200707078c83d9">llvm::wasm::WASM_SYMBOL_TYPE_FUNCTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a36f3d68b8025222c9f73a586aee5932f">llvm::wasm::WASM_SYMBOL_TYPE_GLOBAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529ad7d988e101231ece62ebfe7d06884a1f">llvm::wasm::WASM_SYMBOL_TYPE_SECTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a7e6d4cfa5233363b413a1b9997c98d7c">llvm::wasm::WASM_SYMBOL_TYPE_TABLE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a47169d0c34c301e7580280da4dc576a6">llvm::wasm::WASM_SYMBOL_TYPE_TAG</a>.</p>

</div>
</div>

### getSymbolValueImpl() {#a1ddc24dc2cdfcf8c8a407336306bb1d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t WasmObjectFile::getSymbolValueImpl (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1884 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#aeb7e136e9de32a391575d7f236ed9b71">getWasmSymbol</a> and <a href="#a17d258c3f5b6b5e3d7d0a192aac0b188">getWasmSymbolValue</a>.</p>

</div>
</div>

### getTargetFeatures() {#ab02f673d7957d581ff8564795fe25d6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; wasm::WasmFeatureEntry &gt; llvm::object::WasmObjectFile::getTargetFeatures ()</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### getWasmRelocation() {#adcc00d1267df0ecc8d7a6d18caf4dbd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const wasm::WasmRelocation &amp; WasmObjectFile::getWasmRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/relocationref">RelocationRef</a> &amp; Ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2125 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#adcc00d1267df0ecc8d7a6d18caf4dbd0">getWasmRelocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a198fe5e1de4053e999d41555cb796801">llvm::object::ObjectFile::RelocationRef</a>.</p>


<p>Referenced by <a href="#a0c7ea6d35ebdd6f8b934e2dca2be7cf7">getRelocationOffset</a>, <a href="#acab3ba419eaa03698db0773f121a8075">getRelocationSymbol</a>, <a href="#ab1f3bdc28bdf53fdb25720bdba033e57">getRelocationType</a>, <a href="#a6902b7a4807f72288afd6e2c9bbbb721">getRelocationTypeName</a> and <a href="#adcc00d1267df0ecc8d7a6d18caf4dbd0">getWasmRelocation</a>.</p>

</div>
</div>

### getWasmSection() {#ab9204e81d88bc6fc86d82831d13beb0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const WasmSection &amp; WasmObjectFile::getWasmSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a> &amp; Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2120 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#ab9204e81d88bc6fc86d82831d13beb0f">getWasmSection</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>.</p>


<p>Referenced by <a href="#ab9204e81d88bc6fc86d82831d13beb0f">getWasmSection</a>, <a href="#afbdfae040884e2bfd5a26f82f26a0d8c">isSectionData</a>, <a href="#a25105b42581ad941bfbf55b4b89819fa">isSectionText</a> and <a href="#a03425ecd6379bfd3afa9e0be578fc3c5">section_rel_end</a>.</p>

</div>
</div>

### getWasmSymbol() {#aeb7e136e9de32a391575d7f236ed9b71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const WasmSymbol &amp; WasmObjectFile::getWasmSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Symb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1821 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2820613261c431d4de10b49e30b90ae4">llvm::object::DataRefImpl::b</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>.</p>


<p>Referenced by <a href="#af2a2757f91471e6b80ccffa7840cb154">getSymbolAddress</a>, <a href="#a33b0926d82731e04416d8528bf864405">getSymbolFlags</a>, <a href="#a6e9f3f7b04ea93857f5d16ee84c2646b">getSymbolName</a>, <a href="#ac663c397d2633e31dac4bf80c5840a78">getSymbolSection</a>, <a href="#a527185d51f8cd613611201b0ba35c4db">getSymbolSectionId</a>, <a href="#ae34ddc299f0c959d7c22636cf103c2f1">getSymbolSize</a>, <a href="#a1128d16fcbf1d12b0a2f879dbd5a2fb2">getSymbolType</a>, <a href="#a1ddc24dc2cdfcf8c8a407336306bb1d8">getSymbolValueImpl</a> and <a href="#a6b97101d75c9c68d1d2cdcbe733cb80c">getWasmSymbol</a>.</p>

</div>
</div>

### getWasmSymbol() {#a6b97101d75c9c68d1d2cdcbe733cb80c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const WasmSymbol &amp; WasmObjectFile::getWasmSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a> &amp; Symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1825 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a>, <a href="#aeb7e136e9de32a391575d7f236ed9b71">getWasmSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a23fe52bbc164a30ba18e057d37bd2283">llvm::object::ObjectFile::SymbolRef</a>.</p>

</div>
</div>

### getWasmSymbolValue() {#a17d258c3f5b6b5e3d7d0a192aac0b188}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t WasmObjectFile::getWasmSymbolValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol">WasmSymbol</a> &amp; Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1854 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/wasmsegment/#a74bac1d655ce7ee1bb84ad6c950e44e5">llvm::object::WasmSegment::Data</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsymbolinfo/#a1c2252fcc3cebecf1c18f54de08374a6">llvm::wasm::WasmSymbolInfo::DataRef</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsymbolinfo/#af5d3b408e077b06a899f420e5c843aec">llvm::wasm::WasmSymbolInfo::ElementIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexpr/#a1c6c5387903d9a93176f193ba4eda18b">llvm::wasm::WasmInitExpr::Extended</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol/#a98e191e206c3b67a7d846f2a524debda">llvm::object::WasmSymbol::Info</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexpr/#a590fbb568b4839190db23d8fef1149da">llvm::wasm::WasmInitExpr::Inst</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexprmvp/#a01acce116ff99f623babd7fe30be1679">llvm::wasm::WasmInitExprMVP::Int32</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexprmvp/#aaef138df6847fb7ae420aec252e88bee">llvm::wasm::WasmInitExprMVP::Int64</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsymbolinfo/#a9256dc33ac966b6f097b26877743273b">llvm::wasm::WasmSymbolInfo::Kind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmdatareference/#ac8619dc384cf0889194e60d14a2863aa">llvm::wasm::WasmDataReference::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmdatasegment/#ae92e5d9106dc741a9fb52ef3842125ae">llvm::wasm::WasmDataSegment::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexprmvp/#a1312a3d70f2eb85753cb41c484b558dd">llvm::wasm::WasmInitExprMVP::Opcode</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmdatareference/#a8eca2c641be5eb746984c55d95ce358a">llvm::wasm::WasmDataReference::Segment</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexprmvp/#a0ec2f9d136ea1d19f4e60356d355aaee">llvm::wasm::WasmInitExprMVP::Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033a9a3bf1c56c7bc61608587d378713e4ca">llvm::wasm::WASM_OPCODE_GLOBAL_GET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033af7ad1dcf98f3df5c78655b761f495c54">llvm::wasm::WASM_OPCODE_I32_CONST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033ad7ad0258400fc7d91485fa603ff41daf">llvm::wasm::WASM_OPCODE_I64_CONST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a3bf8c7186acf1ffbf50c1f7c915554bb">llvm::wasm::WASM_SYMBOL_TYPE_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529ae2d3246e8f9451c96b200707078c83d9">llvm::wasm::WASM_SYMBOL_TYPE_FUNCTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a36f3d68b8025222c9f73a586aee5932f">llvm::wasm::WASM_SYMBOL_TYPE_GLOBAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529ad7d988e101231ece62ebfe7d06884a1f">llvm::wasm::WASM_SYMBOL_TYPE_SECTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a7e6d4cfa5233363b413a1b9997c98d7c">llvm::wasm::WASM_SYMBOL_TYPE_TABLE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a47169d0c34c301e7580280da4dc576a6">llvm::wasm::WASM_SYMBOL_TYPE_TAG</a>.</p>


<p>Referenced by <a href="#a1ddc24dc2cdfcf8c8a407336306bb1d8">getSymbolValueImpl</a>.</p>

</div>
</div>

### globals() {#ac1a3717c799260aebdbecffcc520eadd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; wasm::WasmGlobal &gt; llvm::object::WasmObjectFile::globals ()</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### hasUnmodeledTypes() {#a316094dd3f1c9126ec12b8188c80a43c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmObjectFile::hasUnmodeledTypes ()</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### imports() {#a6f6986af7115ea070d8ea80bca3eefe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; wasm::WasmImport &gt; llvm::object::WasmObjectFile::imports ()</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### is64Bit() {#a4e5f94f34b30ae0c423bfa15c643b491}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmObjectFile::is64Bit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### isRelocatableObject() {#a40560d147674d89938435e6f1e359a87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isRelocatableObject ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this is a relocatable object (.o/.obj).</p>

<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2110 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>Referenced by <a href="#aeca0f961d1e606d6c85649cb7805fbd3">getSectionAddress</a>.</p>

</div>
</div>

### isSectionBSS() {#a2fad2affa7a157557a3af8e41230aaa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isSectionBSS (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2024 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### isSectionCompressed() {#a5457c2e49cc8c005336f69ff02c9f1bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isSectionCompressed (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2012 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### isSectionData() {#afbdfae040884e2bfd5a26f82f26a0d8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isSectionData (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2020 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#ab9204e81d88bc6fc86d82831d13beb0f">getWasmSection</a>, <a href="/web-llvm/docs/api/structs/llvm/object/wasmsection/#aee122f9e75e7ae929d7080d19835ecf4">llvm::object::WasmSection::Type</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaaf5f28d03ffa839369fe16c44315b9f56">llvm::wasm::WASM_SEC_DATA</a>.</p>

</div>
</div>

### isSectionText() {#a25105b42581ad941bfbf55b4b89819fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isSectionText (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2016 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#ab9204e81d88bc6fc86d82831d13beb0f">getWasmSection</a>, <a href="/web-llvm/docs/api/structs/llvm/object/wasmsection/#aee122f9e75e7ae929d7080d19835ecf4">llvm::object::WasmSection::Type</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaa2891550fb4214ba533de409607f5f88a">llvm::wasm::WASM_SEC_CODE</a>.</p>

</div>
</div>

### isSectionVirtual() {#a57d41740338f82d6be7ac1118a8ba11f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isSectionVirtual (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2026 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### isSharedObject() {#ad4d7dd7b27216ddfd472a0d19092ef95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isSharedObject ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2112 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>Referenced by <a href="#aeca0f961d1e606d6c85649cb7805fbd3">getSectionAddress</a>.</p>

</div>
</div>

### linkingData() {#aaa55c9ca7c3064fa7a21278cc801f011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const wasm::WasmLinkingData &amp; llvm::object::WasmObjectFile::linkingData ()</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### memories() {#a4d295864da5ece728c945a44056e7473}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; wasm::WasmLimits &gt; llvm::object::WasmObjectFile::memories ()</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### moveRelocationNext() {#a43603839618af034988efc03427a91ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WasmObjectFile::moveRelocationNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Rel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2043 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2820613261c431d4de10b49e30b90ae4">llvm::object::DataRefImpl::b</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>.</p>

</div>
</div>

### moveSectionNext() {#ad1407f36011632e33a5fdd6cce369717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WasmObjectFile::moveSectionNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1972 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>.</p>

</div>
</div>

### moveSymbolNext() {#a05bc4cd6519742157a6df78c18834252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WasmObjectFile::moveSymbolNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1787 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2820613261c431d4de10b49e30b90ae4">llvm::object::DataRefImpl::b</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>.</p>

</div>
</div>

### section\_begin() {#a3b0d45e8e8093653af68f7567eb67f25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">section_iterator WasmObjectFile::section_begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2084 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>.</p>

</div>
</div>

### section\_end() {#a8349576fbde57780d1474b92f0352127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">section_iterator WasmObjectFile::section_end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2090 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>.</p>


<p>Referenced by <a href="#ac663c397d2633e31dac4bf80c5840a78">getSymbolSection</a>.</p>

</div>
</div>

### section\_rel\_begin() {#a75c2cc14199307ebc8e9a27cd3630ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">relocation_iterator WasmObjectFile::section_rel_begin (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2028 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2820613261c431d4de10b49e30b90ae4">llvm::object::DataRefImpl::b</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a198fe5e1de4053e999d41555cb796801">llvm::object::ObjectFile::RelocationRef</a>.</p>

</div>
</div>

### section\_rel\_end() {#a03425ecd6379bfd3afa9e0be578fc3c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">relocation_iterator WasmObjectFile::section_rel_end (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2035 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2820613261c431d4de10b49e30b90ae4">llvm::object::DataRefImpl::b</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="#ab9204e81d88bc6fc86d82831d13beb0f">getWasmSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a198fe5e1de4053e999d41555cb796801">llvm::object::ObjectFile::RelocationRef</a> and <a href="/web-llvm/docs/api/structs/llvm/object/wasmsection/#a607ddcc9e8bb04ea35ad59b36c23dee7">llvm::object::WasmSection::Relocations</a>.</p>

</div>
</div>

### startFunction() {#a321e801f073a2f55226e02053627b6ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmObjectFile::startFunction ()</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### symbol\_begin() {#a02801821ae5fdb77c109244e84c77341}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">basic_symbol_iterator WasmObjectFile::symbol_begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1807 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

### symbol\_end() {#a30d36ada5b3d98a7e0bf17e1d2816da6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">basic_symbol_iterator WasmObjectFile::symbol_end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1814 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>


<p>Referenced by <a href="#acab3ba419eaa03698db0773f121a8075">getRelocationSymbol</a>.</p>

</div>
</div>

### tables() {#ac77f887ebfaa51b54fc0db2ef6e68ded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; wasm::WasmTable &gt; llvm::object::WasmObjectFile::tables ()</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### tags() {#a7851d9cefb2cb935b5d760c6cf78a1fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; wasm::WasmTag &gt; llvm::object::WasmObjectFile::tags ()</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### types() {#a16ce863ffe13406410fea38e1710bdac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; wasm::WasmSignature &gt; llvm::object::WasmObjectFile::types ()</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getDefinedFunction() {#a5f34118f8ede9b912e6e398a5dc5c1c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">wasm::WasmFunction &amp; WasmObjectFile::getDefinedFunction (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1564 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### getDefinedFunction() {#a0455ccb3d2256a542ce58542ed21e481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const wasm::WasmFunction &amp; WasmObjectFile::getDefinedFunction (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1570 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### getDefinedGlobal() {#a8de15a2c15c595c345c6afbcb1b208ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const wasm::WasmGlobal &amp; WasmObjectFile::getDefinedGlobal (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1575 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### getDefinedTag() {#a9906081cb763a0c6f01cc1cdda159870}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">wasm::WasmTag &amp; WasmObjectFile::getDefinedTag (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1580 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### getSymbolSectionIdImpl() {#a97291100ad8046b3953729f0182ce96c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t WasmObjectFile::getSymbolSectionIdImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol">WasmSymbol</a> &amp; Symb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1937 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### getWasmRelocation() {#abf91f46e07dda118c4dd3178e861a850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const wasm::WasmRelocation &amp; WasmObjectFile::getWasmRelocation (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2130 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### getWasmSection() {#adc37f470e882a24167450fa561138926}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const WasmSection &amp; WasmObjectFile::getWasmSection (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 2114 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### isDefinedFunctionIndex() {#ac0c1c5983d1f5d8a4e8cfed5917d9e9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isDefinedFunctionIndex (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1512 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### isDefinedGlobalIndex() {#a8de02f0a228c61290365e69d39dbe3bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isDefinedGlobalIndex (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1524 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### isDefinedTableNumber() {#a47ee7764c3ccbbe99ec88f61261298fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isDefinedTableNumber (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1528 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### isDefinedTagIndex() {#a417d205fb281cc2a8f07c90376414457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isDefinedTagIndex (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1536 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### isValidDataSymbol() {#a6971471fc71d591d8206922fece04d79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isValidDataSymbol (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1556 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### isValidFunctionIndex() {#ae5255bf481c65baa9345f2144f5ffb00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isValidFunctionIndex (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1508 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### isValidFunctionSymbol() {#acf5f7f4f6cf5279f8252ddd13fd02148}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isValidFunctionSymbol (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1540 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### isValidGlobalIndex() {#abbca895d36b15ddeab2d5efddc46f208}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isValidGlobalIndex (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1516 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### isValidGlobalSymbol() {#a5fc948da2b560cc8124862aa288e15a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isValidGlobalSymbol (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1548 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### isValidSectionSymbol() {#aa8f383a425a7bbbb41d05ed361ee10d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isValidSectionSymbol (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1560 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### isValidTableNumber() {#a7ae279e6df5c1f24a07119b675ddddc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isValidTableNumber (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1520 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### isValidTableSymbol() {#ae9c710b5abeb1c33ff7b1e4261442329}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isValidTableSymbol (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1544 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### isValidTagIndex() {#abeb38e970e394749a52cee86270ba2cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isValidTagIndex (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1532 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### isValidTagSymbol() {#a7c7ac5735e715a386acf31ed94eae39d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WasmObjectFile::isValidTagSymbol (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1552 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseCodeSection() {#ac0b8cee247db4c6ad2c375a2fda39899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseCodeSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1593 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseCustomSection() {#a07b999263b8101951598fb5aa0572bb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseCustomSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmsection">WasmSection</a> &amp; Sec, <a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1154 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseDataCountSection() {#a8be5c0482efcbceb059814c53a5244c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseDataCountSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1778 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseDataSection() {#a577a689177af274b296bdafe5098ad89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseDataSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1736 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseDylink0Section() {#a9a0f641ac37aa39776ef9dd2450f7f84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseDylink0Section (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseDylinkSection() {#adc8363b94be9182c0152f2981020ab52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseDylinkSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseElemSection() {#af36ecd85c357864c9a41e4d0e2994844}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseElemSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1639 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseExportSection() {#a92737c5a9d2bd3070ec21bc2bb188929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseExportSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1426 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseFunctionSection() {#abbc5ed801cfd8ccd3a50a198499fb948}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseFunctionSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1318 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseGlobalSection() {#af9b07a9c4017f9522e8c0649ac4e427d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseGlobalSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1402 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseImportSection() {#a642a6426e366f25fe02df9f1e23fca6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseImportSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1257 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseLinkingSection() {#a14dc94ba358f40e3afc4517d67208e9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseLinkingSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 614 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseLinkingSectionComdat() {#ab2622e97139cfa70eb480849371cf6ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseLinkingSectionComdat (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 894 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseLinkingSectionSymtab() {#abdcd062d6ad73f8f98a78df1f7f586aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseLinkingSectionSymtab (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 683 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseMemorySection() {#af8a9ecc27582804571ac81880b1b7dcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseMemorySection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1361 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseNameSection() {#a041f547939a824293e13641fba452ad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseNameSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseProducersSection() {#a61bf7edf42d344a740761afe8d3c3234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseProducersSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 950 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseRelocSection() {#a72a45aa94ca94a6da2226e6714b9e2e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseRelocSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1020 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseSection() {#a61f7f959e52a2871465b796339934851}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmsection">WasmSection</a> &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseStartSection() {#abbf5bfb3e34f94f438f528916352226b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseStartSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1585 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseTableSection() {#a21328ffb1d46e9c50f7927517b8a1c23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseTableSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1337 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseTagSection() {#ab2a4f832e6980c5ce82b1468c14c8a2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseTagSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1376 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseTargetFeaturesSection() {#a83cd315bffb219e9b5da49ef8aaeacee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseTargetFeaturesSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 991 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### parseTypeSection() {#ae7308d4794c76526497376e5bc5ef1cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error WasmObjectFile::parseTypeSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">ReadContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>, definition at line 1180 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CodeSection {#add85b9b6c8acca5b5a4aae39275aa345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmObjectFile::CodeSection = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### DataCount {#a01011ac4fe84118138c8819241c5d4bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;size_t&gt; llvm::object::WasmObjectFile::DataCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### DataSection {#a3d3c426408e5b53e69ef5d17eb61198d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmObjectFile::DataSection = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### DataSegments {#a76b7ba2ac5310d8ce2dc8613e4231f5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;WasmSegment&gt; llvm::object::WasmObjectFile::DataSegments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### DebugNames {#a67af089851e64225cd11bd686f990629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;wasm::WasmDebugName&gt; llvm::object::WasmObjectFile::DebugNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### DylinkInfo {#a95e2a35e343f15859dca18ccbedbc039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">wasm::WasmDylinkInfo llvm::object::WasmObjectFile::DylinkInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### ElemSegments {#ac21f50b0ce04d013436d27ec80c2c069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;wasm::WasmElemSegment&gt; llvm::object::WasmObjectFile::ElemSegments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### Exports {#adb68ebe1975c75fa77ce766edfa71b58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;wasm::WasmExport&gt; llvm::object::WasmObjectFile::Exports</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### Functions {#abb248ba30b9c1b3882a78df2ff081a1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;wasm::WasmFunction&gt; llvm::object::WasmObjectFile::Functions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### Globals {#a3be4a5279fa3ebcc575c001c3be0a566}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;wasm::WasmGlobal&gt; llvm::object::WasmObjectFile::Globals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### GlobalSection {#a61498365c87a58665acc544f526ff88d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmObjectFile::GlobalSection = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### HasDylinkSection {#a5ac3d80ce75fc3f38f73d72974470d86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmObjectFile::HasDylinkSection = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### HasLinkingSection {#a11295f03914923cb8352a407bd3b9c14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmObjectFile::HasLinkingSection = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### HasMemory64 {#a9549419af0a115086e571641010c964c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmObjectFile::HasMemory64 = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### HasUnmodeledTypes {#a83999d57affcea4e4a24fb7fa208a3c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmObjectFile::HasUnmodeledTypes = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### Header {#a4884d22e9d9b5f22266ff9c240b8a01b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">wasm::WasmObjectHeader llvm::object::WasmObjectFile::Header</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### Imports {#aef08e43508dc82ae6aad313d2e364f07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;wasm::WasmImport&gt; llvm::object::WasmObjectFile::Imports</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### LinkingData {#ac7ebde9a2cd0b3d450247e9ae481c7e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">wasm::WasmLinkingData llvm::object::WasmObjectFile::LinkingData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### Memories {#aad03df8f4ed63d7745283342c4002f22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;wasm::WasmLimits&gt; llvm::object::WasmObjectFile::Memories</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### NumImportedFunctions {#aa8b23cb96bb3bffb5dd8f270590be982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmObjectFile::NumImportedFunctions = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### NumImportedGlobals {#a9253655545920368b57df475a5cbfcd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmObjectFile::NumImportedGlobals = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### NumImportedTables {#a921f2934965e3459cd3fb2694dbf0c3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmObjectFile::NumImportedTables = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### NumImportedTags {#a5dc17a46814812a62defb19c0108f7b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmObjectFile::NumImportedTags = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### ProducerInfo {#a428156ec7927c79dcbffe1ad06572849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">wasm::WasmProducerInfo llvm::object::WasmObjectFile::ProducerInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### Sections {#a8ba041d330e672edc9da3b91a245d2fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;WasmSection&gt; llvm::object::WasmObjectFile::Sections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### Signatures {#aff3ef4e32aa05ab37cf56c16e53a863b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;wasm::WasmSignature&gt; llvm::object::WasmObjectFile::Signatures</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### StartFunction {#a67ec2227850a9e5826f04e56ee48145d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmObjectFile::StartFunction = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### Symbols {#a21b470d8a81c410d330e76743f3eb129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;WasmSymbol&gt; llvm::object::WasmObjectFile::Symbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### Tables {#a0c82ae1de7578522e387f50305b9ac9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;wasm::WasmTable&gt; llvm::object::WasmObjectFile::Tables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### TableSection {#ae6f120cf679e55e01fd693462fa4de14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmObjectFile::TableSection = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### Tags {#a67eb4346eae6596d2733d0f94e46af5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;wasm::WasmTag&gt; llvm::object::WasmObjectFile::Tags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### TagSection {#a88077bbe29025e112864905d11871930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WasmObjectFile::TagSection = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

### TargetFeatures {#a7d52ba8eb2d7a14cc8088b77e0b85afe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;wasm::WasmFeatureEntry&gt; llvm::object::WasmObjectFile::TargetFeatures</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#abf0542a10157b39246aa615422558497}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WasmObjectFile::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/binary">Binary</a> * v)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">Wasm.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
