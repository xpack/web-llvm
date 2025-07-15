---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-wasmobjectwriter-cpp-/wasmrelocationentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `WasmRelocationEntry` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{WasmObjectWriter.cpp}::WasmRelocationEntry { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8978fae3dc679729eaccabd8ff5b7799">WasmRelocationEntry</a> (uint64_t Offset, const MCSymbolWasm *Symbol, int64_t Addend, unsigned Type, const MCSectionWasm *FixupSection)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a669333e4e5d0cd698b7c92324c5c83fd">hasAddend</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6da0c74fa7e0a33dc5804181ad3f922">print</a> (raw_ostream &amp;Out) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf06e15f842e20ddb2a9bde2df06ec7b">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70e1e377c4a2f4ffadc1282d0787290c">Offset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm">MCSymbolWasm</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c73e23be8f3c6e200dbef83ad0b1983">Symbol</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b74275bf32480ad9558ee6c2c256c01">Addend</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90937d833f38fa578fed237cf05912df">Type</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsectionwasm">MCSectionWasm</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8372d0bfd5a9019a180a9bf8ff8862f6">FixupSection</a></td>
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


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp">WasmObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WasmRelocationEntry() {#a8978fae3dc679729eaccabd8ff5b7799}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{WasmObjectWriter.cpp}::WasmRelocationEntry::WasmRelocationEntry (uint64_t Offset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm">MCSymbolWasm</a> * Symbol, int64_t Addend, unsigned Type, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsectionwasm">MCSectionWasm</a> * FixupSection)</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp">WasmObjectWriter.cpp</a>.</p>


<p>References <a href="#a8b74275bf32480ad9558ee6c2c256c01">Addend</a>, <a href="#a8372d0bfd5a9019a180a9bf8ff8862f6">FixupSection</a>, <a href="#a70e1e377c4a2f4ffadc1282d0787290c">Offset</a>, <a href="#a3c73e23be8f3c6e200dbef83ad0b1983">Symbol</a> and <a href="#a90937d833f38fa578fed237cf05912df">Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#aaf06e15f842e20ddb2a9bde2df06ec7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void anonymous{WasmObjectWriter.cpp}::WasmRelocationEntry::dump ()</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp">WasmObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>

</div>
</div>

### hasAddend() {#a669333e4e5d0cd698b7c92324c5c83fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WasmObjectWriter.cpp}::WasmRelocationEntry::hasAddend ()</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp">WasmObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8eef3928a7427c4eb20eb250c223a4d3">llvm::wasm::relocTypeHasAddend</a> and <a href="#a90937d833f38fa578fed237cf05912df">Type</a>.</p>

</div>
</div>

### print() {#ad6da0c74fa7e0a33dc5804181ad3f922}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{WasmObjectWriter.cpp}::WasmRelocationEntry::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp">WasmObjectWriter.cpp</a>.</p>


<p>References <a href="#a8b74275bf32480ad9558ee6c2c256c01">Addend</a>, <a href="#a8372d0bfd5a9019a180a9bf8ff8862f6">FixupSection</a>, <a href="#a70e1e377c4a2f4ffadc1282d0787290c">Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#aed2af1215c25855163176bb263224436">llvm::wasm::relocTypetoString</a>, <a href="#a3c73e23be8f3c6e200dbef83ad0b1983">Symbol</a> and <a href="#a90937d833f38fa578fed237cf05912df">Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-wasmobjectwriter-cpp-/#af2a8209b4d8f20fce9a59611d7d67103">anonymous{WasmObjectWriter.cpp}::operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Addend {#a8b74275bf32480ad9558ee6c2c256c01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{WasmObjectWriter.cpp}::WasmRelocationEntry::Addend</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp">WasmObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#ad6da0c74fa7e0a33dc5804181ad3f922">print</a> and <a href="#a8978fae3dc679729eaccabd8ff5b7799">WasmRelocationEntry</a>.</p>

</div>
</div>

### FixupSection {#a8372d0bfd5a9019a180a9bf8ff8862f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSectionWasm* anonymous{WasmObjectWriter.cpp}::WasmRelocationEntry::FixupSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp">WasmObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#ad6da0c74fa7e0a33dc5804181ad3f922">print</a> and <a href="#a8978fae3dc679729eaccabd8ff5b7799">WasmRelocationEntry</a>.</p>

</div>
</div>

### Offset {#a70e1e377c4a2f4ffadc1282d0787290c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{WasmObjectWriter.cpp}::WasmRelocationEntry::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp">WasmObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#ad6da0c74fa7e0a33dc5804181ad3f922">print</a> and <a href="#a8978fae3dc679729eaccabd8ff5b7799">WasmRelocationEntry</a>.</p>

</div>
</div>

### Symbol {#a3c73e23be8f3c6e200dbef83ad0b1983}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbolWasm* anonymous{WasmObjectWriter.cpp}::WasmRelocationEntry::Symbol</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp">WasmObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#ad6da0c74fa7e0a33dc5804181ad3f922">print</a> and <a href="#a8978fae3dc679729eaccabd8ff5b7799">WasmRelocationEntry</a>.</p>

</div>
</div>

### Type {#a90937d833f38fa578fed237cf05912df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{WasmObjectWriter.cpp}::WasmRelocationEntry::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp">WasmObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#a669333e4e5d0cd698b7c92324c5c83fd">hasAddend</a>, <a href="#ad6da0c74fa7e0a33dc5804181ad3f922">print</a> and <a href="#a8978fae3dc679729eaccabd8ff5b7799">WasmRelocationEntry</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp">WasmObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
