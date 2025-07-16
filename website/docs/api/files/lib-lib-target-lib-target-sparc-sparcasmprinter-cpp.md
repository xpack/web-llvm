---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SparcAsmPrinter.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcinstprinter-h">MCTargetDesc/SparcInstPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-h">MCTargetDesc/SparcMCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmctargetdesc-h">MCTargetDesc/SparcMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparctargetstreamer-h">MCTargetDesc/SparcTargetStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparc-h">Sparc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-h">SparcInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparctargetmachine-h">SparcTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/targetinfo/sparctargetinfo-h">TargetInfo/SparcTargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/asmprinter-h">llvm/CodeGen/AsmPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">llvm/CodeGen/MachineModuleInfoImpls.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-sparcasmprinter-cpp-">anonymous{SparcAsmPrinter.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter">SparcAsmPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d0d7f47cce3c25a82585c9e4f27abac">createSparcMCOperand</a> (SparcMCExpr::VariantKind Kind, MCSymbol *Sym, MCContext &amp;OutContext)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d6a316aa92313bdc1e528b0fd69f748">createPCXCallOP</a> (MCSymbol *Label, MCContext &amp;OutContext)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7df82b40c89fe57a01cfd473dcfcd63">createPCXRelExprOp</a> (SparcMCExpr::VariantKind Kind, MCSymbol *GOTLabel, MCSymbol *StartLabel, MCSymbol *CurLabel, MCContext &amp;OutContext)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32deff36e6005bee8b6db8bd36353703">EmitCall</a> (MCStreamer &amp;OutStreamer, MCOperand &amp;Callee, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad58c68abd46a14fdb1cac72bc5b863a">EmitRDPC</a> (MCStreamer &amp;OutStreamer, MCOperand &amp;RD, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52cbef23880440f08e43fb0818d3ffb4">EmitSETHI</a> (MCStreamer &amp;OutStreamer, MCOperand &amp;Imm, MCOperand &amp;RD, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaec30cb8a497bd67f31b3a32d5e2626">EmitBinary</a> (MCStreamer &amp;OutStreamer, unsigned Opcode, MCOperand &amp;RS1, MCOperand &amp;Src2, MCOperand &amp;RD, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bc83ac6922f7a5c110b9cf161839520">EmitOR</a> (MCStreamer &amp;OutStreamer, MCOperand &amp;RS1, MCOperand &amp;Imm, MCOperand &amp;RD, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4aa22f8579614dd66937891bf35be65">EmitADD</a> (MCStreamer &amp;OutStreamer, MCOperand &amp;RS1, MCOperand &amp;RS2, MCOperand &amp;RD, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a113f6fe7b4fe9df10cf48a961fece297">EmitSHL</a> (MCStreamer &amp;OutStreamer, MCOperand &amp;RS1, MCOperand &amp;Imm, MCOperand &amp;RD, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb561d9aa366cbb13d91eb0e00e23344">EmitHiLo</a> (MCStreamer &amp;OutStreamer, MCSymbol *GOTSym, SparcMCExpr::VariantKind HiKind, SparcMCExpr::VariantKind LoKind, MCOperand &amp;RD, MCContext &amp;OutContext, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c3ee8310ea1759628789269f9e4ae3f">LLVMInitializeSparcAsmPrinter</a> ()</td>
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

### createPCXCallOP() {#a0d6a316aa92313bdc1e528b0fd69f748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand createPCXCallOP (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Label, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; OutContext)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp">SparcAsmPrinter.cpp</a>.</p>


<p>References <a href="#a0d0d7f47cce3c25a82585c9e4f27abac">createSparcMCOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0aea5914496aa2e808c471c9855e9e2403">llvm::SparcMCExpr::VK_Sparc_WDISP30</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ab74cde0c8282be6c158a967ff13642a3">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::LowerGETPCXAndEmitMCInsts</a>.</p>

</div>
</div>

### createPCXRelExprOp() {#ad7df82b40c89fe57a01cfd473dcfcd63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand createPCXRelExprOp (<a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0">SparcMCExpr::VariantKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * GOTLabel, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * StartLabel, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * CurLabel, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; OutContext)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp">SparcAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#a70deb9c48e0455e55db69bfd5eea03d2">llvm::SparcMCExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ab74cde0c8282be6c158a967ff13642a3">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::LowerGETPCXAndEmitMCInsts</a>.</p>

</div>
</div>

### createSparcMCOperand() {#a0d0d7f47cce3c25a82585c9e4f27abac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand createSparcMCOperand (<a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0">SparcMCExpr::VariantKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; OutContext)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp">SparcAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#a70deb9c48e0455e55db69bfd5eea03d2">llvm::SparcMCExpr::create</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>.</p>


<p>Referenced by <a href="#a0d6a316aa92313bdc1e528b0fd69f748">createPCXCallOP</a>, <a href="#afb561d9aa366cbb13d91eb0e00e23344">EmitHiLo</a> and <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ab74cde0c8282be6c158a967ff13642a3">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::LowerGETPCXAndEmitMCInsts</a>.</p>

</div>
</div>

### EmitADD() {#af4aa22f8579614dd66937891bf35be65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitADD (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RS1, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RS2, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp">SparcAsmPrinter.cpp</a>.</p>


<p>Reference <a href="#aaaec30cb8a497bd67f31b3a32d5e2626">EmitBinary</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ab74cde0c8282be6c158a967ff13642a3">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::LowerGETPCXAndEmitMCInsts</a>.</p>

</div>
</div>

### EmitBinary() {#aaaec30cb8a497bd67f31b3a32d5e2626}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitBinary (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RS1, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; Src2, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp">SparcAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="#af4aa22f8579614dd66937891bf35be65">EmitADD</a>, <a href="#a9bc83ac6922f7a5c110b9cf161839520">EmitOR</a> and <a href="#a113f6fe7b4fe9df10cf48a961fece297">EmitSHL</a>.</p>

</div>
</div>

### EmitCall() {#a32deff36e6005bee8b6db8bd36353703}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitCall (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; Callee, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp">SparcAsmPrinter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ab74cde0c8282be6c158a967ff13642a3">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::LowerGETPCXAndEmitMCInsts</a>.</p>

</div>
</div>

### EmitHiLo() {#afb561d9aa366cbb13d91eb0e00e23344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitHiLo (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * GOTSym, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0">SparcMCExpr::VariantKind</a> HiKind, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0">SparcMCExpr::VariantKind</a> LoKind, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RD, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; OutContext, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp">SparcAsmPrinter.cpp</a>.</p>


<p>References <a href="#a0d0d7f47cce3c25a82585c9e4f27abac">createSparcMCOperand</a>, <a href="#a9bc83ac6922f7a5c110b9cf161839520">EmitOR</a> and <a href="#a52cbef23880440f08e43fb0818d3ffb4">EmitSETHI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ab74cde0c8282be6c158a967ff13642a3">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::LowerGETPCXAndEmitMCInsts</a>.</p>

</div>
</div>

### EmitOR() {#a9bc83ac6922f7a5c110b9cf161839520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitOR (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RS1, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp">SparcAsmPrinter.cpp</a>.</p>


<p>Reference <a href="#aaaec30cb8a497bd67f31b3a32d5e2626">EmitBinary</a>.</p>


<p>Referenced by <a href="#afb561d9aa366cbb13d91eb0e00e23344">EmitHiLo</a> and <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ab74cde0c8282be6c158a967ff13642a3">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::LowerGETPCXAndEmitMCInsts</a>.</p>

</div>
</div>

### EmitRDPC() {#aad58c68abd46a14fdb1cac72bc5b863a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitRDPC (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp">SparcAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ab74cde0c8282be6c158a967ff13642a3">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::LowerGETPCXAndEmitMCInsts</a>.</p>

</div>
</div>

### EmitSETHI() {#a52cbef23880440f08e43fb0818d3ffb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitSETHI (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp">SparcAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="#afb561d9aa366cbb13d91eb0e00e23344">EmitHiLo</a> and <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ab74cde0c8282be6c158a967ff13642a3">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::LowerGETPCXAndEmitMCInsts</a>.</p>

</div>
</div>

### EmitSHL() {#a113f6fe7b4fe9df10cf48a961fece297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitSHL (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RS1, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp">SparcAsmPrinter.cpp</a>.</p>


<p>Reference <a href="#aaaec30cb8a497bd67f31b3a32d5e2626">EmitBinary</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ab74cde0c8282be6c158a967ff13642a3">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::LowerGETPCXAndEmitMCInsts</a>.</p>

</div>
</div>

### LLVMInitializeSparcAsmPrinter() {#a2c3ee8310ea1759628789269f9e4ae3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_EXTERNAL_VISIBILITY void LLVMInitializeSparcAsmPrinter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp">SparcAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ace90049f7690a2d7ebdd992d9971b05e">llvm::getTheSparcelTarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5ff53cbbc586bb1e2c72074990e86287">llvm::getTheSparcTarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ccc6ab0f8d73b68c4079891435e224">llvm::getTheSparcV9Target</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp">SparcAsmPrinter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
