---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `DirectXMCTargetDesc.cpp` File Reference

<p>This file contains DirectX target initializer. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-h">DirectXMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxcontainerobjectwriter-h">DirectXContainerObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/targetinfo/directxtargetinfo-h">TargetInfo/DirectXTargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/lanebitmask-h">llvm/MC/LaneBitmask.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmbackend-h">llvm/MC/MCAsmBackend.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeemitter-h">llvm/MC/MCCodeEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdxcontainerwriter-h">llvm/MC/MCDXContainerWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">llvm/MC/MCInstPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrinfo-h">llvm/MC/MCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">llvm/MC/MCSchedule.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include &lt;memory&gt;
#include "DirectXGenInstrInfo.inc"
#include "DirectXGenSubtargetInfo.inc"
#include "DirectXGenRegisterInfo.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-directxmctargetdesc-cpp-">anonymous{DirectXMCTargetDesc.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-directxmctargetdesc-cpp-/dxilinstprinter">DXILInstPrinter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-directxmctargetdesc-cpp-/dxilmccodeemitter">DXILMCCodeEmitter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-directxmctargetdesc-cpp-/dxilasmbackend">DXILAsmBackend</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-directxmctargetdesc-cpp-/directxmcasminfo">DirectXMCAsmInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0399d3c78e56e239f0192f7aaa8a28f">createDXILMCInstPrinter</a> (const Triple &amp;T, unsigned SyntaxVariant, const MCAsmInfo &amp;MAI, const MCInstrInfo &amp;MII, const MCRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca8c2fe81ffc9734abbed210c08d8093">createDXILMCCodeEmitter</a> (const MCInstrInfo &amp;MCII, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a060a8c5679d3ab192edfa19d3cad5588">createDXILMCAsmBackend</a> (const Target &amp;T, const MCSubtargetInfo &amp;STI, const MCRegisterInfo &amp;MRI, const MCTargetOptions &amp;Options)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a179959fc36d6cd57ac4ad716ada53c07">createDirectXMCSubtargetInfo</a> (const Triple &amp;TT, StringRef CPU, StringRef FS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13dab147b3be186a5201ee8c79269e4b">createDirectXMCRegisterInfo</a> (const Triple &amp;Triple)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a772606323c9f7a7f78b47339c5ae4773">createDirectXMCInstrInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2650072c61d204c8fe4bc597fdc6672">LLVMInitializeDirectXTargetMC</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a308641466b881118ac1053e55c8b59aa">GET_INSTRINFO_MC_DESC</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9011f8eec608201d9da0eca43b0d12af">GET_INSTRINFO_MC_HELPERS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a125da064bb99459483887c91182923b8">GET_SUBTARGETINFO_MC_DESC</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7450ae576d0fab98e1f81508551d6e7e">GET_REGINFO_MC_DESC</a></td>
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

## Description {#details}

<p>This file contains DirectX target initializer.</p>

<div class="doxySectionDef">

## Functions

### createDirectXMCInstrInfo() {#a772606323c9f7a7f78b47339c5ae4773}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstrInfo * createDirectXMCInstrInfo ()</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-cpp">DirectXMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="#ae2650072c61d204c8fe4bc597fdc6672">LLVMInitializeDirectXTargetMC</a>.</p>

</div>
</div>

### createDirectXMCRegisterInfo() {#a13dab147b3be186a5201ee8c79269e4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegisterInfo * createDirectXMCRegisterInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; Triple)</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-cpp">DirectXMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="#ae2650072c61d204c8fe4bc597fdc6672">LLVMInitializeDirectXTargetMC</a>.</p>

</div>
</div>

### createDirectXMCSubtargetInfo() {#a179959fc36d6cd57ac4ad716ada53c07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSubtargetInfo * createDirectXMCSubtargetInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-cpp">DirectXMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="#ae2650072c61d204c8fe4bc597fdc6672">LLVMInitializeDirectXTargetMC</a>.</p>

</div>
</div>

### createDXILMCAsmBackend() {#a060a8c5679d3ab192edfa19d3cad5588}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmBackend * createDXILMCAsmBackend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp; Options)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-cpp">DirectXMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-directxmctargetdesc-cpp-/dxilasmbackend/#ad729761f5d8ee04cf711a65b74c5bfb6">anonymous{DirectXMCTargetDesc.cpp}::DXILAsmBackend::DXILAsmBackend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#ae2650072c61d204c8fe4bc597fdc6672">LLVMInitializeDirectXTargetMC</a>.</p>

</div>
</div>

### createDXILMCCodeEmitter() {#aca8c2fe81ffc9734abbed210c08d8093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCodeEmitter * createDXILMCCodeEmitter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-cpp">DirectXMCTargetDesc.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-directxmctargetdesc-cpp-/dxilmccodeemitter/#aa634a438351aa808af928777e756ed51">anonymous{DirectXMCTargetDesc.cpp}::DXILMCCodeEmitter::DXILMCCodeEmitter</a>.</p>


<p>Referenced by <a href="#ae2650072c61d204c8fe4bc597fdc6672">LLVMInitializeDirectXTargetMC</a>.</p>

</div>
</div>

### createDXILMCInstPrinter() {#aa0399d3c78e56e239f0192f7aaa8a28f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstPrinter * createDXILMCInstPrinter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, unsigned SyntaxVariant, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp; MAI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-cpp">DirectXMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-directxmctargetdesc-cpp-/dxilinstprinter/#a624c93ec59ea0010d96268f38d5a8c7f">anonymous{DirectXMCTargetDesc.cpp}::DXILInstPrinter::DXILInstPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#ae2650072c61d204c8fe4bc597fdc6672">LLVMInitializeDirectXTargetMC</a>.</p>

</div>
</div>

### LLVMInitializeDirectXTargetMC() {#ae2650072c61d204c8fe4bc597fdc6672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_EXTERNAL_VISIBILITY void LLVMInitializeDirectXTargetMC ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-cpp">DirectXMCTargetDesc.cpp</a>.</p>


<p>References <a href="#a772606323c9f7a7f78b47339c5ae4773">createDirectXMCInstrInfo</a>, <a href="#a13dab147b3be186a5201ee8c79269e4b">createDirectXMCRegisterInfo</a>, <a href="#a179959fc36d6cd57ac4ad716ada53c07">createDirectXMCSubtargetInfo</a>, <a href="#a060a8c5679d3ab192edfa19d3cad5588">createDXILMCAsmBackend</a>, <a href="#aca8c2fe81ffc9734abbed210c08d8093">createDXILMCCodeEmitter</a>, <a href="#aa0399d3c78e56e239f0192f7aaa8a28f">createDXILMCInstPrinter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62377abdd4061d7fff25e630832036f8">llvm::getTheDirectXTarget</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a158db359a78dc87d4f7b2e96585b78ae">llvm::TargetRegistry::RegisterMCAsmBackend</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a2e06603b238d255bf8d182eaa9e18c7a">llvm::TargetRegistry::RegisterMCCodeEmitter</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#aabd8e913cb341182f1ef8c24c25e50ad">llvm::TargetRegistry::RegisterMCInstPrinter</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#abea956a9e4d1526501d68bee93470e53">llvm::TargetRegistry::RegisterMCInstrInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a0be8ffbacd90d86a1c1f27a032e2265e">llvm::TargetRegistry::RegisterMCRegInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a469331cb6070bffd3354391877547014">llvm::TargetRegistry::RegisterMCSubtargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### GET\_INSTRINFO\_MC\_DESC {#a308641466b881118ac1053e55c8b59aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INSTRINFO_MC_DESC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-cpp">DirectXMCTargetDesc.cpp</a>.</p>

</div>
</div>

### GET\_INSTRINFO\_MC\_HELPERS {#a9011f8eec608201d9da0eca43b0d12af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INSTRINFO_MC_HELPERS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-cpp">DirectXMCTargetDesc.cpp</a>.</p>

</div>
</div>

### GET\_REGINFO\_MC\_DESC {#a7450ae576d0fab98e1f81508551d6e7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_REGINFO_MC_DESC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-cpp">DirectXMCTargetDesc.cpp</a>.</p>

</div>
</div>

### GET\_SUBTARGETINFO\_MC\_DESC {#a125da064bb99459483887c91182923b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_SUBTARGETINFO_MC_DESC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-cpp">DirectXMCTargetDesc.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
