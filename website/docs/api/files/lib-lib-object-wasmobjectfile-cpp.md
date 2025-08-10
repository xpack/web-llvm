---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/object/wasmobjectfile-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `WasmObjectFile.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/denseset-h">llvm/ADT/DenseSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">llvm/ADT/SmallSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringset-h">llvm/ADT/StringSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/wasm-h">llvm/BinaryFormat/Wasm.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/binary-h">llvm/Object/Binary.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/error-h">llvm/Object/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">llvm/Object/ObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">llvm/Object/SymbolicFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/wasm-h">llvm/Object/Wasm.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">llvm/Support/Endian.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/leb128-h">llvm/Support/LEB128.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scopedprinter-h">llvm/Support/ScopedPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">llvm/TargetParser/SubtargetFeature.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;cstring&gt;
#include "llvm/BinaryFormat/WasmRelocs.def"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a56d780e151cbe22976176e82a9939b">readUint8</a> (WasmObjectFile::ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84247b20b236408869fe2931b9c744be">readUint32</a> (WasmObjectFile::ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa97de364fdc6a13668a8a2f5ce33db55">readFloat32</a> (WasmObjectFile::ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac253c43632e9d502a3b0bcf605b70ba0">readFloat64</a> (WasmObjectFile::ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf25b6c36a87e97fa229741286379421">readULEB128</a> (WasmObjectFile::ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a980857c412176c9d3fd897dcc7c1213d">readString</a> (WasmObjectFile::ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69dd19d502ba6316106ebc6fc66cf5dc">readLEB128</a> (WasmObjectFile::ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00063a617f40f3b7a59ed4717580cb13">readVaruint1</a> (WasmObjectFile::ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c027af723bc3512cd7fd0b00708d3d5">readVarint32</a> (WasmObjectFile::ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aa64e836d6031d14736a833a3e0f324">readVaruint32</a> (WasmObjectFile::ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af042141c1b3a6f4587212eb9c226466a">readVarint64</a> (WasmObjectFile::ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e37d1f1ae7e54b56e40fcaebafe1c2c">readVaruint64</a> (WasmObjectFile::ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cadc266a832202116502ee1f45ec3f2">readOpcode</a> (WasmObjectFile::ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8">wasm::ValType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4996c9580bd53e4db3a68369126bacf">parseValType</a> (WasmObjectFile::ReadContext &amp;Ctx, uint32_t Code)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45f478a3e04bfcd32b4db7f75fc94577">readInitExpr</a> (wasm::WasmInitExpr &amp;Expr, WasmObjectFile::ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmlimits">wasm::WasmLimits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58012c68833df211ab44f2492dde4f2a">readLimits</a> (WasmObjectFile::ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmtabletype">wasm::WasmTableType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5455a36997b3166ffc3beadf3dfee030">readTableType</a> (WasmObjectFile::ReadContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67951f7188e316333fc6cf733db7f71f">readSection</a> (WasmSection &amp;Section, WasmObjectFile::ReadContext &amp;Ctx, WasmSectionOrderChecker &amp;Checker)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"wasm-object"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04f3514e6a8a11d87e78fd103df9a1b5">VARINT7_MAX</a>&nbsp;&nbsp;&nbsp;((1 &lt;&lt; 7) - 1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e912c485891b1c27e9e1dcd84d92da3">VARINT7_MIN</a>&nbsp;&nbsp;&nbsp;(-(1 &lt;&lt; 7))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91813dda08674602ad36b5b0e3e70a83">VARUINT7_MAX</a>&nbsp;&nbsp;&nbsp;(1 &lt;&lt; 7)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa054ba44f4950b493a0e878a1a399ae0">VARUINT1_MAX</a>&nbsp;&nbsp;&nbsp;(1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a915bde402f5437ef5b9c9ad6a3600a89">WASM_RELOC</a>(name, value)&nbsp;&nbsp;&nbsp;...</td>
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

### parseValType() {#ad4996c9580bd53e4db3a68369126bacf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">wasm::ValType parseValType (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">WasmObjectFile::ReadContext</a> &amp; Ctx, uint32_t Code)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a26c7088bd944f387e539f2745fe8afd8">llvm::wasm::OTHERREF</a>, <a href="#af042141c1b3a6f4587212eb9c226466a">readVarint64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647eafa2c550d2128cc812bf5c320539bfc87">llvm::wasm::WASM_TYPE_EXNREF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647ea8fe9c097be76685c503bf24177988a49">llvm::wasm::WASM_TYPE_EXTERNREF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647eae88d0b78646db504ac64a9b0245fb2ff">llvm::wasm::WASM_TYPE_F32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647ea3e127f09d14b44569016ccb43c255081">llvm::wasm::WASM_TYPE_F64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647ea65b99d81eaf83487037a4d507a6f37a2">llvm::wasm::WASM_TYPE_FUNCREF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647eabde54aa45b9d6b85fb4c37fc5cca29f5">llvm::wasm::WASM_TYPE_I32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647ea2b4b3bdb67bcba743db32a1c0684ccff">llvm::wasm::WASM_TYPE_I64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647eaba5ab2abcb3cdba362b835d0d8a56b66">llvm::wasm::WASM_TYPE_NONNULLABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647ea1b94cea21e87116c94b203909acba755">llvm::wasm::WASM_TYPE_NULLABLE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647eaec7a320b098d9d72bb306fc75ab85646">llvm::wasm::WASM_TYPE_V128</a>.</p>


<p>Referenced by <a href="#a45f478a3e04bfcd32b4db7f75fc94577">readInitExpr</a> and <a href="#a5455a36997b3166ffc3beadf3dfee030">readTableType</a>.</p>

</div>
</div>

### readFloat32() {#aa97de364fdc6a13668a8a2f5ce33db55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t readFloat32 (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">WasmObjectFile::ReadContext</a> &amp; Ctx)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#a45f478a3e04bfcd32b4db7f75fc94577">readInitExpr</a>.</p>

</div>
</div>

### readFloat64() {#ac253c43632e9d502a3b0bcf605b70ba0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t readFloat64 (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">WasmObjectFile::ReadContext</a> &amp; Ctx)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#a45f478a3e04bfcd32b4db7f75fc94577">readInitExpr</a>.</p>

</div>
</div>

### readInitExpr() {#a45f478a3e04bfcd32b4db7f75fc94577}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error readInitExpr (<a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexpr">wasm::WasmInitExpr</a> &amp; Expr, <a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">WasmObjectFile::ReadContext</a> &amp; Ctx)</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexpr/#ac75b01907e39de57c2a3810b44c93c23">llvm::wasm::WasmInitExpr::Body</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexpr/#a1c6c5387903d9a93176f193ba4eda18b">llvm::wasm::WasmInitExpr::Extended</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexprmvp/#a54e438003e03c8c1973d3df49ec83445">llvm::wasm::WasmInitExprMVP::Float32</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexprmvp/#afcb363be1bef728b0b24ce93002948ff">llvm::wasm::WasmInitExprMVP::Float64</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexprmvp/#ad9bf9e2125b5c4ebd0aa07496a5762e6">llvm::wasm::WasmInitExprMVP::Global</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexpr/#a590fbb568b4839190db23d8fef1149da">llvm::wasm::WasmInitExpr::Inst</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexprmvp/#a01acce116ff99f623babd7fe30be1679">llvm::wasm::WasmInitExprMVP::Int32</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexprmvp/#aaef138df6847fb7ae420aec252e88bee">llvm::wasm::WasmInitExprMVP::Int64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexprmvp/#a1312a3d70f2eb85753cb41c484b558dd">llvm::wasm::WasmInitExprMVP::Opcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>, <a href="#ad4996c9580bd53e4db3a68369126bacf">parseValType</a>, <a href="#aa97de364fdc6a13668a8a2f5ce33db55">readFloat32</a>, <a href="#ac253c43632e9d502a3b0bcf605b70ba0">readFloat64</a>, <a href="#a8cadc266a832202116502ee1f45ec3f2">readOpcode</a>, <a href="#aaf25b6c36a87e97fa229741286379421">readULEB128</a>, <a href="#a4c027af723bc3512cd7fd0b00708d3d5">readVarint32</a>, <a href="#af042141c1b3a6f4587212eb9c226466a">readVarint64</a>, <a href="#a7aa64e836d6031d14736a833a3e0f324">readVaruint32</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasminitexprmvp/#a0ec2f9d136ea1d19f4e60356d355aaee">llvm::wasm::WasmInitExprMVP::Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#ab0f14af78fd85441d1f8e9f4ebf3960dac145f631a9a27b0308e3ee519b96257d">llvm::wasm::WASM_OPCODE_ARRAY_NEW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#ab0f14af78fd85441d1f8e9f4ebf3960da818bc967e692f98dadc38172eab63674">llvm::wasm::WASM_OPCODE_ARRAY_NEW_DEFAULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#ab0f14af78fd85441d1f8e9f4ebf3960da48dd10d1d26f99d78ca3f4b3e048c10d">llvm::wasm::WASM_OPCODE_ARRAY_NEW_FIXED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033a3bd24f6a3212ad61f5bb76efd6c6c994">llvm::wasm::WASM_OPCODE_END</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033a94085475370d28c3750f92a327224a53">llvm::wasm::WASM_OPCODE_F32_CONST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033a334197a2017c810968e76bdd6c7874a1">llvm::wasm::WASM_OPCODE_F64_CONST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033a8cede51ce4b2f703d2589becd61014ee">llvm::wasm::WASM_OPCODE_GC_PREFIX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033a9a3bf1c56c7bc61608587d378713e4ca">llvm::wasm::WASM_OPCODE_GLOBAL_GET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033aa49e4c95e5f48ca1afda814f85040f2a">llvm::wasm::WASM_OPCODE_I32_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033af7ad1dcf98f3df5c78655b761f495c54">llvm::wasm::WASM_OPCODE_I32_CONST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033aa03ea5a627699c800eb655f085f8ddff">llvm::wasm::WASM_OPCODE_I32_MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033a2727d4129445f1b3747d1c2ddf5240f1">llvm::wasm::WASM_OPCODE_I32_SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033a247f31491d5a6cad64a42c802c1a073e">llvm::wasm::WASM_OPCODE_I64_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033ad7ad0258400fc7d91485fa603ff41daf">llvm::wasm::WASM_OPCODE_I64_CONST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033a560081317c7007dafefd31d59e7decba">llvm::wasm::WASM_OPCODE_I64_MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033aa00f27b017a036e6a9560ed27312c3bc">llvm::wasm::WASM_OPCODE_I64_SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033a90984d85991b48fa68779e349e8f87c4">llvm::wasm::WASM_OPCODE_REF_FUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#ab0f14af78fd85441d1f8e9f4ebf3960da6253494df623769d25dec7b830656a35">llvm::wasm::WASM_OPCODE_REF_I31</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a8ff5928cf9c43e8cdb1b36b2c9e2d033a8169e7206232ec368246b729068cb465">llvm::wasm::WASM_OPCODE_REF_NULL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#ab0f14af78fd85441d1f8e9f4ebf3960da890061ed3bbefba374f91ceba68c7a19">llvm::wasm::WASM_OPCODE_STRUCT_NEW</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#ab0f14af78fd85441d1f8e9f4ebf3960daaa2013b9976221a00e926a09552a969e">llvm::wasm::WASM_OPCODE_STRUCT_NEW_DEFAULT</a>.</p>

</div>
</div>

### readLEB128() {#a69dd19d502ba6316106ebc6fc66cf5dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t readLEB128 (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">WasmObjectFile::ReadContext</a> &amp; Ctx)</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a405b6cecd013148b4b443dd37854b4c4">llvm::decodeSLEB128</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#a4c027af723bc3512cd7fd0b00708d3d5">readVarint32</a>, <a href="#af042141c1b3a6f4587212eb9c226466a">readVarint64</a> and <a href="#a00063a617f40f3b7a59ed4717580cb13">readVaruint1</a>.</p>

</div>
</div>

### readLimits() {#a58012c68833df211ab44f2492dde4f2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">wasm::WasmLimits readLimits (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">WasmObjectFile::ReadContext</a> &amp; Ctx)</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#a7aa64e836d6031d14736a833a3e0f324">readVaruint32</a>, <a href="#a5e37d1f1ae7e54b56e40fcaebafe1c2c">readVaruint64</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a59b99a8ddca474dff358ee96d7a5b9ada0a94fb8e747d2293e76e4fdbfc2cb6bd">llvm::wasm::WASM_LIMITS_FLAG_HAS_MAX</a>.</p>


<p>Referenced by <a href="#a5455a36997b3166ffc3beadf3dfee030">readTableType</a>.</p>

</div>
</div>

### readOpcode() {#a8cadc266a832202116502ee1f45ec3f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t readOpcode (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">WasmObjectFile::ReadContext</a> &amp; Ctx)</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>Reference <a href="#a9a56d780e151cbe22976176e82a9939b">readUint8</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86disassembler-cpp-/x86genericdisassembler/#a5872d463242e5872d4df00b5862e403f">anonymous{X86Disassembler.cpp}::X86GenericDisassembler::getInstruction</a> and <a href="#a45f478a3e04bfcd32b4db7f75fc94577">readInitExpr</a>.</p>

</div>
</div>

### readSection() {#a67951f7188e316333fc6cf733db7f71f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error readSection (<a href="/web-llvm/docs/api/structs/llvm/object/wasmsection">WasmSection</a> &amp; Section, <a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">WasmObjectFile::ReadContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsectionorderchecker">WasmSectionOrderChecker</a> &amp; Checker)</td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext/#ada98c2e462e8caccde767258a987c29b">llvm::object::WasmObjectFile::ReadContext::End</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsectionorderchecker/#a0b575c4fbaec067108afa87be8ca0ade">llvm::object::WasmSectionOrderChecker::isValidSectionOrder</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>, <a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext/#aef46df49bcc82743d5feddbd3fa953d9">llvm::object::WasmObjectFile::ReadContext::Ptr</a>, <a href="#a980857c412176c9d3fd897dcc7c1213d">readString</a>, <a href="#a9a56d780e151cbe22976176e82a9939b">readUint8</a>, <a href="#a7aa64e836d6031d14736a833a3e0f324">readVaruint32</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext/#aeb89f8e95555b6c91698e1fc9c78e5c3">llvm::object::WasmObjectFile::ReadContext::Start</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a13c1b5a253da5da49ce33d03dc1efc07">llvm::to_string</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaa685069a810d109e09f4af7d2d115a8cd">llvm::wasm::WASM_SEC_CUSTOM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a78b45ebf4772364c848d6aedf38fd199">llvm::object::WasmObjectFile::WasmObjectFile</a>.</p>

</div>
</div>

### readString() {#a980857c412176c9d3fd897dcc7c1213d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef readString (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">WasmObjectFile::ReadContext</a> &amp; Ctx)</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#aaf25b6c36a87e97fa229741286379421">readULEB128</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#a67951f7188e316333fc6cf733db7f71f">readSection</a>.</p>

</div>
</div>

### readTableType() {#a5455a36997b3166ffc3beadf3dfee030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">wasm::WasmTableType readTableType (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">WasmObjectFile::ReadContext</a> &amp; Ctx)</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#ad4996c9580bd53e4db3a68369126bacf">parseValType</a>, <a href="#a58012c68833df211ab44f2492dde4f2a">readLimits</a> and <a href="#a7aa64e836d6031d14736a833a3e0f324">readVaruint32</a>.</p>

</div>
</div>

### readUint32() {#a84247b20b236408869fe2931b9c744be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t readUint32 (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">WasmObjectFile::ReadContext</a> &amp; Ctx)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a78b45ebf4772364c848d6aedf38fd199">llvm::object::WasmObjectFile::WasmObjectFile</a>.</p>

</div>
</div>

### readUint8() {#a9a56d780e151cbe22976176e82a9939b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t readUint8 (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">WasmObjectFile::ReadContext</a> &amp; Ctx)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#a8cadc266a832202116502ee1f45ec3f2">readOpcode</a> and <a href="#a67951f7188e316333fc6cf733db7f71f">readSection</a>.</p>

</div>
</div>

### readULEB128() {#aaf25b6c36a87e97fa229741286379421}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t readULEB128 (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">WasmObjectFile::ReadContext</a> &amp; Ctx)</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3720bbfe79232f7792ab4b969dfbeed0">llvm::decodeULEB128</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#a45f478a3e04bfcd32b4db7f75fc94577">readInitExpr</a>, <a href="#a980857c412176c9d3fd897dcc7c1213d">readString</a>, <a href="#a7aa64e836d6031d14736a833a3e0f324">readVaruint32</a> and <a href="#a5e37d1f1ae7e54b56e40fcaebafe1c2c">readVaruint64</a>.</p>

</div>
</div>

### readVarint32() {#a4c027af723bc3512cd7fd0b00708d3d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t readVarint32 (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">WasmObjectFile::ReadContext</a> &amp; Ctx)</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#a69dd19d502ba6316106ebc6fc66cf5dc">readLEB128</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#a45f478a3e04bfcd32b4db7f75fc94577">readInitExpr</a>.</p>

</div>
</div>

### readVarint64() {#af042141c1b3a6f4587212eb9c226466a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t readVarint64 (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">WasmObjectFile::ReadContext</a> &amp; Ctx)</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>Reference <a href="#a69dd19d502ba6316106ebc6fc66cf5dc">readLEB128</a>.</p>


<p>Referenced by <a href="#ad4996c9580bd53e4db3a68369126bacf">parseValType</a> and <a href="#a45f478a3e04bfcd32b4db7f75fc94577">readInitExpr</a>.</p>

</div>
</div>

### readVaruint1() {#a00063a617f40f3b7a59ed4717580cb13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t readVaruint1 (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">WasmObjectFile::ReadContext</a> &amp; Ctx)</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#a69dd19d502ba6316106ebc6fc66cf5dc">readLEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="#aa054ba44f4950b493a0e878a1a399ae0">VARUINT1_MAX</a>.</p>

</div>
</div>

### readVaruint32() {#a7aa64e836d6031d14736a833a3e0f324}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t readVaruint32 (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">WasmObjectFile::ReadContext</a> &amp; Ctx)</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#aaf25b6c36a87e97fa229741286379421">readULEB128</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#a45f478a3e04bfcd32b4db7f75fc94577">readInitExpr</a>, <a href="#a58012c68833df211ab44f2492dde4f2a">readLimits</a>, <a href="#a67951f7188e316333fc6cf733db7f71f">readSection</a> and <a href="#a5455a36997b3166ffc3beadf3dfee030">readTableType</a>.</p>

</div>
</div>

### readVaruint64() {#a5e37d1f1ae7e54b56e40fcaebafe1c2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t readVaruint64 (<a href="/web-llvm/docs/api/structs/llvm/object/wasmobjectfile/readcontext">WasmObjectFile::ReadContext</a> &amp; Ctx)</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>Reference <a href="#aaf25b6c36a87e97fa229741286379421">readULEB128</a>.</p>


<p>Referenced by <a href="#a58012c68833df211ab44f2492dde4f2a">readLimits</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"wasm-object"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### VARINT7\_MAX {#a04f3514e6a8a11d87e78fd103df9a1b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VARINT7_MAX&nbsp;&nbsp;&nbsp;((1 &lt;&lt; 7) - 1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### VARINT7\_MIN {#a6e912c485891b1c27e9e1dcd84d92da3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VARINT7_MIN&nbsp;&nbsp;&nbsp;(-(1 &lt;&lt; 7))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### VARUINT1\_MAX {#aa054ba44f4950b493a0e878a1a399ae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VARUINT1_MAX&nbsp;&nbsp;&nbsp;(1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>Referenced by <a href="#a00063a617f40f3b7a59ed4717580cb13">readVaruint1</a>.</p>

</div>
</div>

### VARUINT7\_MAX {#a91813dda08674602ad36b5b0e3e70a83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VARUINT7_MAX&nbsp;&nbsp;&nbsp;(1 &lt;&lt; 7)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

### WASM\_RELOC {#a915bde402f5437ef5b9c9ad6a3600a89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define WASM_RELOC(name, value)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case wasm::name:                                                             \
    Res = #<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>;                                                               \
    break;
</div>
</dd>
</dl>

<p>Definition at line 2070 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
