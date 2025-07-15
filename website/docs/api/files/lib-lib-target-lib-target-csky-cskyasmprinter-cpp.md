---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/csky/cskyasmprinter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `CSKYAsmPrinter.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyasmprinter-h">CSKYAsmPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/csky-h">CSKY.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskytargetmachine-h">CSKYTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyinstprinter-h">MCTargetDesc/CSKYInstPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-h">MCTargetDesc/CSKYMCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskytargetstreamer-h">MCTargetDesc/CSKYTargetStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/targetinfo/cskytargetinfo-h">TargetInfo/CSKYTargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/asmprinter-h">llvm/CodeGen/AsmPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">llvm/CodeGen/MachineConstantPool.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstbuilder-h">llvm/MC/MCInstBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "CSKYGenCompressInstEmitter.inc"
#include "CSKYGenMCPseudoLowering.inc"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b9a44903ebd93b1847e4f9ad2f32c92">STATISTIC</a> (CSKYNumInstrsCompressed, "Number of C-SKY Compressed instructions emitted")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56d">CSKYMCExpr::VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae10efc1566c53080b26268e68384a531">getModifierVariantKind</a> (CSKYCP::CSKYCPModifier Modifier)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dcee1df18b177084b438106e72ca785">LLVMInitializeCSKYAsmPrinter</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"csky-asm-printer"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84f3c007e1f867b85f442e9b86f19516">GEN_COMPRESS_INSTR</a></td>
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

### getModifierVariantKind() {#ae10efc1566c53080b26268e68384a531}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CSKYMCExpr::VariantKind getModifierVariantKind (<a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4">CSKYCP::CSKYCPModifier</a> Modifier)</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyasmprinter-cpp">CSKYAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4a11f72aa51db1915ad266a52e760f28af">llvm::CSKYCP::ADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4ae82a4118bf542c05ab38488e5b578ae1">llvm::CSKYCP::GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4a972b1bf03372caa6601f0a1b4903ae76">llvm::CSKYCP::GOTOFF</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4ab42535f4f838187946d69d1113f7cd32">llvm::CSKYCP::NO_MOD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4a4534acdb80b394f5943dcc36c9704c9b">llvm::CSKYCP::PLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4a5c32b033a20299c57276476c5b7c73b9">llvm::CSKYCP::TLSGD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4a200b54fa8d3a6ca97d345190f01a4087">llvm::CSKYCP::TLSIE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4ae32b3dc690462147ec73186713977244">llvm::CSKYCP::TLSLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56da00b43daca1c50769fde2954c18a6a08d">llvm::CSKYMCExpr::VK_CSKY_ADDR</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56da6f6264903a5cd681bef075a10d80830c">llvm::CSKYMCExpr::VK_CSKY_GOT</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56da459851e1e27ad13079a564826c441637">llvm::CSKYMCExpr::VK_CSKY_GOTOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56da9651ea71fd4490018e90fc7093c586b4">llvm::CSKYMCExpr::VK_CSKY_None</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56da69348b1cbd18fce5aff9db7f91d273b9">llvm::CSKYMCExpr::VK_CSKY_PLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56da62b16a80d6774adcf5795e1f444f8481">llvm::CSKYMCExpr::VK_CSKY_TLSGD</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56da40d2178a63dd0ff09242ab5496938e95">llvm::CSKYMCExpr::VK_CSKY_TLSIE</a> and <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56da63f14a876cfe0a7d880dfcf341584a30">llvm::CSKYMCExpr::VK_CSKY_TLSLE</a>.</p>

</div>
</div>

### LLVMInitializeCSKYAsmPrinter() {#a0dcee1df18b177084b438106e72ca785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_EXTERNAL_VISIBILITY void LLVMInitializeCSKYAsmPrinter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyasmprinter-cpp">CSKYAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9c4deebe900595840d904634582a9d1c">llvm::getTheCSKYTarget</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### STATISTIC() {#a6b9a44903ebd93b1847e4f9ad2f32c92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (CSKYNumInstrsCompressed, "Number of <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a1960c14773241d6a238d2db593abe552">C</a>-SKY Compressed <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> emitted")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyasmprinter-cpp">CSKYAsmPrinter.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"csky-asm-printer"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyasmprinter-cpp">CSKYAsmPrinter.cpp</a>.</p>

</div>
</div>

### GEN\_COMPRESS\_INSTR {#a84f3c007e1f867b85f442e9b86f19516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GEN_COMPRESS_INSTR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyasmprinter-cpp">CSKYAsmPrinter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
