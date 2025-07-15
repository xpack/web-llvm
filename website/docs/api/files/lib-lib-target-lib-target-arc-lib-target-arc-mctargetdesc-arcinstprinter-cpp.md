---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcinstprinter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ARCInstPrinter.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcinstprinter-h">ARCInstPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcinfo-h">MCTargetDesc/ARCInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrinfo-h">llvm/MC/MCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">llvm/MC/MCSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "ARCGenAsmWriter.inc"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0050808214ede9d85e0ccc652651fe3b">BadConditionCode</a> (T cc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81ecb8bc6fc6400da360f21052bdcb05">ARCBRCondCodeToString</a> (ARCCC::BRCondCode BRCC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a831a89e7e21ae539c70f658eabc09aa2">ARCCondCodeToString</a> (ARCCC::CondCode CC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0092f28dd2ee076c70d4c225678dc6ce">printExpr</a> (const MCExpr *Expr, const MCAsmInfo *MAI, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"asm-printer"</td>
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

### ARCBRCondCodeToString() {#a81ecb8bc6fc6400da360f21052bdcb05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * ARCBRCondCodeToString (<a href="/web-llvm/docs/api/namespaces/llvm/arccc/#ab2a5c94ee5074aa9f31e28eda349b514">ARCCC::BRCondCode</a> BRCC)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcinstprinter-cpp">ARCInstPrinter.cpp</a>.</p>


<p>References <a href="#a0050808214ede9d85e0ccc652651fe3b">BadConditionCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#ab2a5c94ee5074aa9f31e28eda349b514a03c139be512230f487f62726e1b35ab6">llvm::ARCCC::BREQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#ab2a5c94ee5074aa9f31e28eda349b514a8e5753127b5f0ebc0f897447a7400d72">llvm::ARCCC::BRGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#ab2a5c94ee5074aa9f31e28eda349b514a47a1b9aad95fdf10ec422d8e6432a8be">llvm::ARCCC::BRHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#ab2a5c94ee5074aa9f31e28eda349b514ab763925d9e680ff06a428384411b74c5">llvm::ARCCC::BRLO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#ab2a5c94ee5074aa9f31e28eda349b514aa9cd1b80e294031e0f457decbacabbb8">llvm::ARCCC::BRLT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#ab2a5c94ee5074aa9f31e28eda349b514a9ec00135d7244a871984916d30cc30d2">llvm::ARCCC::BRNE</a>.</p>

</div>
</div>

### ARCCondCodeToString() {#a831a89e7e21ae539c70f658eabc09aa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * ARCCondCodeToString (<a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006">ARCCC::CondCode</a> CC)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcinstprinter-cpp">ARCInstPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a912a5b8c0856fad709590b5d47aae1c7">llvm::ARCCC::AL</a>, <a href="#a0050808214ede9d85e0ccc652651fe3b">BadConditionCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a06424d16ad2a930de1f57d6b564cbc1b">llvm::ARCCC::EQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a815eaffff57498d8c26b03fb3510dec6">llvm::ARCCC::GE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006ad55c9ceb8b27f401f5d82c0ebd20d6be">llvm::ARCCC::GT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006ad072d903ed389a04331251bbbc069524">llvm::ARCCC::HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a4c1cec33829d627ebeeb767b3d2b2c36">llvm::ARCCC::HS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006aadc05bce3350700bee41e8525d23acc1">llvm::ARCCC::LE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a01b7f88b89f69e354f814793602b2256">llvm::ARCCC::LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006ae0363d765d2cb82180e8db9332366d2b">llvm::ARCCC::LS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a1695055effb07e0e8e69ff10aff4756b">llvm::ARCCC::LT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a4846867f356ee9f45a8c45853d5f7e7a">llvm::ARCCC::N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a913770d7f2c3565cff9146efa0621b8d">llvm::ARCCC::NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a799e707160aac5ed5107d38155b69d69">llvm::ARCCC::NZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a99e83610e4f815aa0556a531f26b2572">llvm::ARCCC::P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a71fc36687f36bb6cc52543c8cc812b0c">llvm::ARCCC::PNZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a6a9fb8f59362e12960359e5a55f777c8">llvm::ARCCC::VC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a8172a107e0d48ee61e1f7631ad071c37">llvm::ARCCC::VS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006aceb189306b941666e679bf556207c1e4">llvm::ARCCC::Z</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/arcinstprinter/#a01a08a4d5693a613b291b477f2a4d369">llvm::ARCInstPrinter::printCCOperand</a>.</p>

</div>
</div>

### BadConditionCode() {#a0050808214ede9d85e0ccc652651fe3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * BadConditionCode (T cc)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcinstprinter-cpp">ARCInstPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a81ecb8bc6fc6400da360f21052bdcb05">ARCBRCondCodeToString</a> and <a href="#a831a89e7e21ae539c70f658eabc09aa2">ARCCondCodeToString</a>.</p>

</div>
</div>

### printExpr() {#a0092f28dd2ee076c70d4c225678dc6ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> * MAI, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcinstprinter-cpp">ARCInstPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#ad860e326e495f296cdee70606908a6b1">llvm::MCSymbolRefExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a048f077746d95f142d02e56586862bf2">llvm::MCSymbolRefExpr::getSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a27f7a23e572edb7b1bc46d9639c3204a">llvm::MCSymbol::print</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a37b5dd8a8b82f2818e0f4ea9699d8ae5">llvm::raw_ostream::write_hex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bpfinstprinter/#a07b2f49008fa1aee47028452e3609212">llvm::BPFInstPrinter::printBrTargetOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstprinter/#a8ab9dbe63d2b01ab39359cfb5bd5319e">llvm::BPFInstPrinter::printImm64Operand</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstprinter/#ace0292b8a0ab3255644b2acf607d6439">llvm::BPFInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvinstprinter/#a27c4a87f88c20ac4710c4e092dadb6fb">llvm::SPIRVInstPrinter::printOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensainstprinter/#a9f811f31e57e6c1f82e14088b2d87b91">llvm::XtensaInstPrinter::printOperand</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"asm-printer"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcinstprinter-cpp">ARCInstPrinter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
