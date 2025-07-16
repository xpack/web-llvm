---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `VEAsmPrinter.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/veinstprinter-h">MCTargetDesc/VEInstPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-h">MCTargetDesc/VEMCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vetargetstreamer-h">MCTargetDesc/VETargetStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/targetinfo/vetargetinfo-h">TargetInfo/VETargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/ve-h">VE.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veinstrinfo-h">VEInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/asmprinter-h">llvm/CodeGen/AsmPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">llvm/CodeGen/MachineModuleInfoImpls.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">llvm/CodeGen/TargetLoweringObjectFileImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mangler-h">llvm/IR/Mangler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">llvm/MC/MCSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-veasmprinter-cpp-">anonymous{VEAsmPrinter.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter">VEAsmPrinter</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a587150a33a51744021fd1bc8026194d3">createVEMCOperand</a> (VEMCExpr::VariantKind Kind, MCSymbol *Sym, MCContext &amp;OutContext)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1149e610692549287d358a9926ca0d44">createGOTRelExprOp</a> (VEMCExpr::VariantKind Kind, MCSymbol *GOTLabel, MCContext &amp;OutContext)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28d8abbfedd338d44a39887939340b91">emitSIC</a> (MCStreamer &amp;OutStreamer, MCOperand &amp;RD, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e94665a52b9daea5f22841f60760ab2">emitBSIC</a> (MCStreamer &amp;OutStreamer, MCOperand &amp;R1, MCOperand &amp;R2, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fd6a23b5a2ab5b7dc3f202529479a80">emitLEAzzi</a> (MCStreamer &amp;OutStreamer, MCOperand &amp;Imm, MCOperand &amp;RD, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58c5b4dc239b80405dfe9abdad268555">emitLEASLzzi</a> (MCStreamer &amp;OutStreamer, MCOperand &amp;Imm, MCOperand &amp;RD, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3812bc25ff6681233201a4c9187dec75">emitLEAzii</a> (MCStreamer &amp;OutStreamer, MCOperand &amp;RS1, MCOperand &amp;Imm, MCOperand &amp;RD, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc5831f0eaa7631d3dfeda1204813426">emitLEASLrri</a> (MCStreamer &amp;OutStreamer, MCOperand &amp;RS1, MCOperand &amp;RS2, MCOperand &amp;Imm, MCOperand &amp;RD, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3063fa549eed52187dad621a5646bf4e">emitBinary</a> (MCStreamer &amp;OutStreamer, unsigned Opcode, MCOperand &amp;RS1, MCOperand &amp;Src2, MCOperand &amp;RD, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb4aacf3fed59b974ae3994430d0c34c">emitANDrm</a> (MCStreamer &amp;OutStreamer, MCOperand &amp;RS1, MCOperand &amp;Imm, MCOperand &amp;RD, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7befbcc43661669d11b3a05a0cf03c86">emitHiLo</a> (MCStreamer &amp;OutStreamer, MCSymbol *GOTSym, VEMCExpr::VariantKind HiKind, VEMCExpr::VariantKind LoKind, MCOperand &amp;RD, MCContext &amp;OutContext, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a694773053cf48ae1c7ded9f6a7eb4628">LLVMInitializeVEAsmPrinter</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"ve-asmprinter"</td>
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

### createGOTRelExprOp() {#a1149e610692549287d358a9926ca0d44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand createGOTRelExprOp (<a href="/web-llvm/docs/api/classes/llvm/vemcexpr/#af04d361a436f54db54865f22611d8844">VEMCExpr::VariantKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * GOTLabel, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; OutContext)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp">VEAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/vemcexpr/#a874e7a37a3a7e51ef151eb95e146638f">llvm::VEMCExpr::create</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a349ac25a0317c2e30b66435a5bdede3d">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETFunPLTAndEmitMCInsts</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#ac5cfd4fb19000475fc0153c2301ab56b">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETGOTAndEmitMCInsts</a> and <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a15c1137ef9bebbeafd1060405cb71242">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETTLSAddrAndEmitMCInsts</a>.</p>

</div>
</div>

### createVEMCOperand() {#a587150a33a51744021fd1bc8026194d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand createVEMCOperand (<a href="/web-llvm/docs/api/classes/llvm/vemcexpr/#af04d361a436f54db54865f22611d8844">VEMCExpr::VariantKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; OutContext)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp">VEAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/vemcexpr/#a874e7a37a3a7e51ef151eb95e146638f">llvm::VEMCExpr::create</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>.</p>


<p>Referenced by <a href="#a7befbcc43661669d11b3a05a0cf03c86">emitHiLo</a>.</p>

</div>
</div>

### emitANDrm() {#acb4aacf3fed59b974ae3994430d0c34c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitANDrm (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RS1, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp">VEAsmPrinter.cpp</a>.</p>


<p>Reference <a href="#a3063fa549eed52187dad621a5646bf4e">emitBinary</a>.</p>


<p>Referenced by <a href="#a7befbcc43661669d11b3a05a0cf03c86">emitHiLo</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a349ac25a0317c2e30b66435a5bdede3d">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETFunPLTAndEmitMCInsts</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#ac5cfd4fb19000475fc0153c2301ab56b">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETGOTAndEmitMCInsts</a> and <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a15c1137ef9bebbeafd1060405cb71242">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETTLSAddrAndEmitMCInsts</a>.</p>

</div>
</div>

### emitBinary() {#a3063fa549eed52187dad621a5646bf4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitBinary (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RS1, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; Src2, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp">VEAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="#acb4aacf3fed59b974ae3994430d0c34c">emitANDrm</a>.</p>

</div>
</div>

### emitBSIC() {#a5e94665a52b9daea5f22841f60760ab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitBSIC (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; R1, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; R2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp">VEAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h/#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a15c1137ef9bebbeafd1060405cb71242">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETTLSAddrAndEmitMCInsts</a>.</p>

</div>
</div>

### emitHiLo() {#a7befbcc43661669d11b3a05a0cf03c86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitHiLo (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * GOTSym, <a href="/web-llvm/docs/api/classes/llvm/vemcexpr/#af04d361a436f54db54865f22611d8844">VEMCExpr::VariantKind</a> HiKind, <a href="/web-llvm/docs/api/classes/llvm/vemcexpr/#af04d361a436f54db54865f22611d8844">VEMCExpr::VariantKind</a> LoKind, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RD, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; OutContext, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp">VEAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a587150a33a51744021fd1bc8026194d3">createVEMCOperand</a>, <a href="#acb4aacf3fed59b974ae3994430d0c34c">emitANDrm</a>, <a href="#a58c5b4dc239b80405dfe9abdad268555">emitLEASLzzi</a>, <a href="#a9fd6a23b5a2ab5b7dc3f202529479a80">emitLEAzzi</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab8aff98d3587ddb15f9e46ed88687f0f">llvm::M0</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#ac5cfd4fb19000475fc0153c2301ab56b">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETGOTAndEmitMCInsts</a>.</p>

</div>
</div>

### emitLEASLrri() {#acc5831f0eaa7631d3dfeda1204813426}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitLEASLrri (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RS1, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RS2, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp">VEAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a349ac25a0317c2e30b66435a5bdede3d">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETFunPLTAndEmitMCInsts</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#ac5cfd4fb19000475fc0153c2301ab56b">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETGOTAndEmitMCInsts</a> and <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a15c1137ef9bebbeafd1060405cb71242">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETTLSAddrAndEmitMCInsts</a>.</p>

</div>
</div>

### emitLEASLzzi() {#a58c5b4dc239b80405dfe9abdad268555}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitLEASLzzi (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp">VEAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="#a7befbcc43661669d11b3a05a0cf03c86">emitHiLo</a>.</p>

</div>
</div>

### emitLEAzii() {#a3812bc25ff6681233201a4c9187dec75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitLEAzii (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RS1, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp">VEAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a349ac25a0317c2e30b66435a5bdede3d">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETFunPLTAndEmitMCInsts</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#ac5cfd4fb19000475fc0153c2301ab56b">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETGOTAndEmitMCInsts</a> and <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a15c1137ef9bebbeafd1060405cb71242">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETTLSAddrAndEmitMCInsts</a>.</p>

</div>
</div>

### emitLEAzzi() {#a9fd6a23b5a2ab5b7dc3f202529479a80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitLEAzzi (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp">VEAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="#a7befbcc43661669d11b3a05a0cf03c86">emitHiLo</a>.</p>

</div>
</div>

### emitSIC() {#a28d8abbfedd338d44a39887939340b91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitSIC (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp">VEAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a349ac25a0317c2e30b66435a5bdede3d">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETFunPLTAndEmitMCInsts</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#ac5cfd4fb19000475fc0153c2301ab56b">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETGOTAndEmitMCInsts</a> and <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a15c1137ef9bebbeafd1060405cb71242">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETTLSAddrAndEmitMCInsts</a>.</p>

</div>
</div>

### LLVMInitializeVEAsmPrinter() {#a694773053cf48ae1c7ded9f6a7eb4628}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_EXTERNAL_VISIBILITY void LLVMInitializeVEAsmPrinter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp">VEAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5717f26352c67f04afcd7029348de029">llvm::getTheVETarget</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"ve-asmprinter"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp">VEAsmPrinter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
