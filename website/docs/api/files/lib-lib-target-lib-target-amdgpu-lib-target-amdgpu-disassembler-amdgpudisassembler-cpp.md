---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AMDGPUDisassembler.cpp` File Reference

<p>This file contains definition for <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> ISA disassembler. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">Disassembler/AMDGPUDisassembler.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-h">MCTargetDesc/AMDGPUMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/targetinfo/amdgputargetinfo-h">TargetInfo/AMDGPUTargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-h">Utils/AMDGPUAsmUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">Utils/AMDGPUBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">llvm-c/DisassemblerTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">llvm/BinaryFormat/ELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdecoderops-h">llvm/MC/MCDecoderOps.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">llvm/MC/MCInstrDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">llvm/Support/AMDHSAKernelDescriptor.h</a>"
#include "AMDGPUGenDisassemblerTables.inc"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/vopmodifiers">VOPModifiers</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af93d373e6e95b58feb6c1fdf50a0e396">DecodeStatus</a> = <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">llvm::MCDisassembler::DecodeStatus</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">MCDisassembler::DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a> (MCInst &amp;Inst, const MCOperand &amp;Opnd)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39c0a22d457ccc212829d0a052685264">insertNamedMCOperand</a> (MCInst &amp;MI, const MCOperand &amp;Op, uint16_t NameIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dc7b2dd9907d083db5fb49ac5490b97">decodeSOPPBrTarget</a> (MCInst &amp;Inst, unsigned Imm, uint64_t Addr, const MCDisassembler *Decoder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29ec63c03889b569a9f8ea9cc55e8f61">decodeSMEMOffset</a> (MCInst &amp;Inst, unsigned Imm, uint64_t Addr, const MCDisassembler *Decoder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad52fe682480e5a4022a50ddb9b03b80a">decodeBoolReg</a> (MCInst &amp;Inst, unsigned Val, uint64_t Addr, const MCDisassembler *Decoder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2f35a568e622ec0fa2fc9a0678d3d48">decodeSplitBarrier</a> (MCInst &amp;Inst, unsigned Val, uint64_t Addr, const MCDisassembler *Decoder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e82e523aa3cdb6231fee9301ec1e93b">decodeDpp8FI</a> (MCInst &amp;Inst, unsigned Val, uint64_t Addr, const MCDisassembler *Decoder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a724770ffa3ce3bb67ce53936f6123f72">decodeSrcOp</a> (MCInst &amp;Inst, unsigned EncSize, AMDGPUDisassembler::OpWidthTy OpWidth, unsigned Imm, unsigned EncImm, bool MandatoryLiteral, unsigned ImmWidth, AMDGPU::OperandSemantics Sema, const MCDisassembler *Decoder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;AMDGPUDisassembler::OpWidthTy OpWidth&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af3c6d1f202232b10665e32f3c9c5170a">decodeAV10</a> (MCInst &amp;Inst, unsigned Imm, uint64_t, const MCDisassembler *Decoder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;AMDGPUDisassembler::OpWidthTy OpWidth&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a89ff868f77585a2e2f4ed4cb3495b627">decodeSrcReg9</a> (MCInst &amp;Inst, unsigned Imm, uint64_t, const MCDisassembler *Decoder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;AMDGPUDisassembler::OpWidthTy OpWidth&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a35212d69efb20b5a402c000fc99bc2fa">decodeSrcA9</a> (MCInst &amp;Inst, unsigned Imm, uint64_t, const MCDisassembler *Decoder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;AMDGPUDisassembler::OpWidthTy OpWidth&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa8e88e4f3dac78e1282e220487ae2ab9">decodeSrcAV10</a> (MCInst &amp;Inst, unsigned Imm, uint64_t, const MCDisassembler *Decoder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0e3809fc5da6085c65e5c7ed95d60485">decodeSrcRegOrImm9</a> (MCInst &amp;Inst, unsigned Imm, uint64_t, const MCDisassembler *Decoder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a67efe1254e42ec0e86f7823257a40a38">decodeSrcRegOrImmA9</a> (MCInst &amp;Inst, unsigned Imm, uint64_t, const MCDisassembler *Decoder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4d5e8e8a196119453b96d7b758d8008b">decodeSrcRegOrImmDeferred9</a> (MCInst &amp;Inst, unsigned Imm, uint64_t, const MCDisassembler *Decoder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a869eb0ec1821f8576c98ced8745b1f30">DecodeVGPR_16RegisterClass</a> (MCInst &amp;Inst, unsigned Imm, uint64_t, const MCDisassembler *Decoder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4f043e93fc1f83ea48a4f98bdfa8958">DecodeVGPR_16_Lo128RegisterClass</a> (MCInst &amp;Inst, unsigned Imm, uint64_t, const MCDisassembler *Decoder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a501ee3504108a954dc813a4712ed3cb7">decodeOperand_VSrcT16_Lo128</a> (MCInst &amp;Inst, unsigned Imm, uint64_t, const MCDisassembler *Decoder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7efe6ae246d870766f8d98f24906cde6">decodeOperand_VSrcT16_Lo128_Deferred</a> (MCInst &amp;Inst, unsigned Imm, uint64_t, const MCDisassembler *Decoder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab64db06c075d376148faa2794e8a4d0c">decodeOperand_VSrcT16</a> (MCInst &amp;Inst, unsigned Imm, uint64_t, const MCDisassembler *Decoder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a358acca39fd0fcf3a282b6050564162f">decodeOperand_VGPR_16</a> (MCInst &amp;Inst, unsigned Imm, uint64_t, const MCDisassembler *Decoder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab13514a8df17e5cc0eb7a570110c8aaa">decodeOperand_KImmFP</a> (MCInst &amp;Inst, unsigned Imm, uint64_t Addr, const MCDisassembler *Decoder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9fa71823613012495803a4be21971d3">decodeOperandVOPDDstY</a> (MCInst &amp;Inst, unsigned Val, uint64_t Addr, const void *Decoder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67245482e0fb8189af448dfed2bc154a">IsAGPROperand</a> (const MCInst &amp;Inst, int OpIdx, const MCRegisterInfo *MRI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac34073953af52bfb6d10afcfa08233cd">decodeAVLdSt</a> (MCInst &amp;Inst, unsigned Imm, AMDGPUDisassembler::OpWidthTy Opw, const MCDisassembler *Decoder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;AMDGPUDisassembler::OpWidthTy Opw&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4ddc5958507d83b34305967186bb3ad1">decodeAVLdSt</a> (MCInst &amp;Inst, unsigned Imm, uint64_t, const MCDisassembler *Decoder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a518f398e1650cebe32756b5cb45c3da8">decodeOperand_VSrc_f64</a> (MCInst &amp;Inst, unsigned Imm, uint64_t Addr, const MCDisassembler *Decoder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31d2138e4e8a3d618d9841a3b13c5609">decodeVersionImm</a> (MCInst &amp;Inst, unsigned Imm, uint64_t, const MCDisassembler *Decoder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static T</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaff8a7b712c8ea0bb1275e621119e498">eatBytes</a> (ArrayRef&lt; uint8_t &gt; &amp;Bytes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/decoderuint128">DecoderUInt128</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a434621cd1f8f1c0240a47b65ba19ea9b">eat12Bytes</a> (ArrayRef&lt; uint8_t &gt; &amp;Bytes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/decoderuint128">DecoderUInt128</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d8ee6944c8121c49c2a8da4b1695fe7">eat16Bytes</a> (ArrayRef&lt; uint8_t &gt; &amp;Bytes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff9a81d3a94f8d3b4530e6430d5c772c">adjustMFMA_F8F6F4OpRegClass</a> (const MCRegisterInfo &amp;MRI, MCOperand &amp;MO, uint8_t NumRegs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adjust the register values used by V_MFMA_F8F6F4_f8_f8 instructions to the appropriate subregister for the used format width. <a href="#aff9a81d3a94f8d3b4530e6430d5c772c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/vopmodifiers">VOPModifiers</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0670115d0e8597ec2618045c1076d811">collectVOPModifiers</a> (const MCInst &amp;MI, bool IsVOP3P=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96eff11e4ce91e92cfaa3e59f7600100">getInlineImmVal32</a> (unsigned Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadb457499c6b9db87a068c5ae53ba32e">getInlineImmVal64</a> (unsigned Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad74d02e562b22b0af8c697d2df57a09e">getInlineImmValF16</a> (unsigned Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a596016f0072634c2d21a74e672d29719">getInlineImmValBF16</a> (unsigned Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51cb222cd0ee12f7f7eb5c1aba1f1803">getInlineImmVal16</a> (unsigned Imm, AMDGPU::OperandSemantics Sema)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a198680a0e69a43b37693d17862fffe63">getBitRangeFromMask</a> (uint32_t Mask, unsigned BaseBytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print a string describing the reserved bit range specified by Mask with offset BaseBytes for use in error comments. <a href="#a198680a0e69a43b37693d17862fffe63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff86ab78c9551cfaa6fd58da22f49dc5">createReservedKDBitsError</a> (uint32_t Mask, unsigned BaseBytes, const char *Msg="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an error object to return from onSymbolStart for reserved kernel descriptor bits being set. <a href="#aff86ab78c9551cfaa6fd58da22f49dc5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef7ddc0af2349fa45789289f716de36a">createReservedKDBytesError</a> (unsigned BaseInBytes, unsigned WidthInBytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an error object to return from onSymbolStart for reserved kernel descriptor bytes being set. <a href="#aef7ddc0af2349fa45789289f716de36a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad088e3815766f6d9b2e8485f2e89351b">createAMDGPUSymbolizer</a> (const Triple &amp;, LLVMOpInfoCallback, LLVMSymbolLookupCallback, void *DisInfo, MCContext *Ctx, std::unique_ptr&lt; MCRelocationInfo &gt; &amp;&amp;RelInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb9c73627ba15ed73cd8b8502c4137b3">createAMDGPUDisassembler</a> (const Target &amp;T, const MCSubtargetInfo &amp;STI, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf297f3f63ca3282686b6b725d3ca818">LLVMInitializeAMDGPUDisassembler</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"amdgpu-disassembler"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac8b18da22658e7589a0286322114803">SGPR_MAX</a>&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afec291717f10788ac7009575db1dc651">DECODE_OPERAND</a>(StaticDecoderName, DecoderName)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4aff7bd0c86d4158d48058d67825ba">DECODE_OPERAND_REG_8</a>(RegClass)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36efcd12c7aade02f99937d563a9dd16">DECODE_SrcOp</a>(Name, EncSize, OpWidth, EncImm, MandatoryLiteral, ImmWidth)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a33e20626a398a086dc8f51c676b75e">DECODE_OPERAND_REG_7</a>(RegClass, OpWidth)&nbsp;&nbsp;&nbsp;  <a href="#a36efcd12c7aade02f99937d563a9dd16">DECODE_SrcOp</a>(Decode##RegClass##RegisterClass, 7, OpWidth, Imm, false, 0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d7e4c42994334246aaea74d14f0f08c">DECODE_SDWA</a>(DecName)&nbsp;&nbsp;&nbsp;<a href="#afec291717f10788ac7009575db1dc651">DECODE_OPERAND</a>(decodeSDWA##DecName, decodeSDWA##DecName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbe651d6dbda0f8eacf67b705a8d3b13">GET_FIELD</a>(MASK)&nbsp;&nbsp;&nbsp;(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h/#a286f2813b785a6b1d7f9c688580c2dc4">AMDHSA_BITS_GET</a>(FourByteBuffer, MASK))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b14fc850e8e58263a51cd89e7d6c838">PRINT_DIRECTIVE</a>(DIRECTIVE, MASK)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44e38092dcf380740d2ead9690ae9bfc">PRINT_PSEUDO_DIRECTIVE_COMMENT</a>(DIRECTIVE, MASK)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedb8704fbe2ff70f458c06faec5462a7">CHECK_RESERVED_BITS_IMPL</a>(MASK, DESC, MSG)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa33da5c37d93576ec4aacb9ce7672368">CHECK_RESERVED_BITS</a>(MASK)&nbsp;&nbsp;&nbsp;<a href="#aedb8704fbe2ff70f458c06faec5462a7">CHECK_RESERVED_BITS_IMPL</a>(MASK, #MASK, "")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac67c208c1ef5d548e50e8d2efb76fc2c">CHECK_RESERVED_BITS_MSG</a>(MASK, MSG)&nbsp;&nbsp;&nbsp;  <a href="#aedb8704fbe2ff70f458c06faec5462a7">CHECK_RESERVED_BITS_IMPL</a>(MASK, #MASK, ", " MSG)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00cbaf3dc4f08d1784589594dfe6149d">CHECK_RESERVED_BITS_DESC</a>(MASK, DESC)&nbsp;&nbsp;&nbsp;  <a href="#aedb8704fbe2ff70f458c06faec5462a7">CHECK_RESERVED_BITS_IMPL</a>(MASK, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetailpredication-cpp/#a51f62d37762db1aa829ad4fe2627fbf9">DESC</a>, "")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa52988bf1e093da5f3499a666cf0a63">CHECK_RESERVED_BITS_DESC_MSG</a>(MASK, DESC, MSG)&nbsp;&nbsp;&nbsp;  <a href="#aedb8704fbe2ff70f458c06faec5462a7">CHECK_RESERVED_BITS_IMPL</a>(MASK, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetailpredication-cpp/#a51f62d37762db1aa829ad4fe2627fbf9">DESC</a>, ", " MSG)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a674d2e9303a1f09156c06c1320a4a096">PRINT_DIRECTIVE</a>(DIRECTIVE, MASK)&nbsp;&nbsp;&nbsp;...</td>
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

<p>This file contains definition for <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> ISA disassembler.</p>

<div class="doxySectionDef">

## Typedefs

### DecodeStatus {#af93d373e6e95b58feb6c1fdf50a0e396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DecodeStatus =  llvm::MCDisassembler::DecodeStatus</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### addOperand() {#a9fafc367cabbdce17ed971f70373c7c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDisassembler::DecodeStatus addOperand (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; Opnd)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#abbfcefd1ec45289db58eeb5622b6bd7e">llvm::MCOperand::isValid</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#ae5f0e6bc47c72961a9a05d307d6400f1">llvm::AMDGPUDisassembler::convertMIMGInst</a>, <a href="#ac34073953af52bfb6d10afcfa08233cd">decodeAVLdSt</a>, <a href="#ad52fe682480e5a4022a50ddb9b03b80a">decodeBoolReg</a>, <a href="#a4e82e523aa3cdb6231fee9301ec1e93b">decodeDpp8FI</a>, <a href="#ab13514a8df17e5cc0eb7a570110c8aaa">decodeOperand_KImmFP</a>, <a href="#a358acca39fd0fcf3a282b6050564162f">decodeOperand_VGPR_16</a>, <a href="#a518f398e1650cebe32756b5cb45c3da8">decodeOperand_VSrc_f64</a>, <a href="#ab64db06c075d376148faa2794e8a4d0c">decodeOperand_VSrcT16</a>, <a href="#a501ee3504108a954dc813a4712ed3cb7">decodeOperand_VSrcT16_Lo128</a>, <a href="#a7efe6ae246d870766f8d98f24906cde6">decodeOperand_VSrcT16_Lo128_Deferred</a>, <a href="#ac9fa71823613012495803a4be21971d3">decodeOperandVOPDDstY</a>, <a href="#a29ec63c03889b569a9f8ea9cc55e8f61">decodeSMEMOffset</a>, <a href="#a5dc7b2dd9907d083db5fb49ac5490b97">decodeSOPPBrTarget</a>, <a href="#af2f35a568e622ec0fa2fc9a0678d3d48">decodeSplitBarrier</a>, <a href="#a724770ffa3ce3bb67ce53936f6123f72">decodeSrcOp</a>, <a href="#a31d2138e4e8a3d618d9841a3b13c5609">decodeVersionImm</a>, <a href="#ac4f043e93fc1f83ea48a4f98bdfa8958">DecodeVGPR_16_Lo128RegisterClass</a>, <a href="#a869eb0ec1821f8576c98ced8745b1f30">DecodeVGPR_16RegisterClass</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#ab55c74c151c09190ab2204e33e77b299">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerHardenedBRJumpTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#adaf899f496f2ac717a79e58b4e439058">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerLOADauthptrstatic</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#aa50d150829937efa73527accf23a184d">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerLOADgotAUTH</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a22c90a0d582e484ad655a9f337002b05">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerMOVaddrPAC</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a175c0b6f2f4c39ae659845dcef17f71b">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::LowerPATCHPOINT</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a010b554002b5c2fdbc6e2d2b64afedb9">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerSTATEPOINT</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a50863928ef6e46cfbe213995fd4974c2">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::LowerSTATEPOINT</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#a8022309e0fcca527f4a1a49b8a8ba922">llvm::LoongArchAsmPrinter::LowerSTATEPOINT</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#acb424057b318d4f0d94f58c87edb8e54">llvm::VPReplicateRecipe::VPReplicateRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarphirecipe/#a0d27908ed27f8a71770249b7330c16cb">llvm::VPScalarPHIRecipe::VPScalarPHIRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a46b99b127f56b83e8e377f47db747158">llvm::VPWidenEVLRecipe::VPWidenEVLRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwideninductionrecipe/#a6df9383fcb4e6c458747b018afc83e15">llvm::VPWidenInductionRecipe::VPWidenInductionRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#aa01db46604297aadfc584687815e75a4">llvm::VPWidenIntOrFpInductionRecipe::VPWidenIntOrFpInductionRecipe</a> and <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#a46123306a8f5c93638c730e6f57581ed">llvm::VPWidenIntOrFpInductionRecipe::VPWidenIntOrFpInductionRecipe</a>.</p>

</div>
</div>

### adjustMFMA\_F8F6F4OpRegClass() {#aff9a81d3a94f8d3b4530e6430d5c772c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjustMFMA_F8F6F4OpRegClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; MO, uint8_t NumRegs)</td>
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

<p>Adjust the register values used by V_MFMA_F8F6F4_f8_f8 instructions to the appropriate subregister for the used format width.</p>

<p>Definition at line 861 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a604722fe2776c0df4d275cff37a37d95">llvm::MCOperand::setReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#acdb4b1dd5155bf0f31e8d74cdd8ccc6c">llvm::AMDGPUDisassembler::convertMAIInst</a>.</p>

</div>
</div>

### collectVOPModifiers() {#a0670115d0e8597ec2618045c1076d811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VOPModifiers collectVOPModifiers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, bool IsVOP3P=false)</td>
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



<p>Definition at line 921 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442a8e2f726558b97b38629c9fa9f8691612">llvm::SISrcMods::DST_OP_SEL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442af1ceb53a1b47dab205dc19070b47a1a6">llvm::SISrcMods::NEG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442aa2e6fe69892c3b751a1f9cb4933ca368">llvm::SISrcMods::NEG_HI</a>, <a href="/web-llvm/docs/api/structs/vopmodifiers/#a50cfb72a98aaefca11ba090c96675c4b">VOPModifiers::NegHi</a>, <a href="/web-llvm/docs/api/structs/vopmodifiers/#ad2dc1ae7fde6cd92a999715b2591feca">VOPModifiers::NegLo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442a3b095994a942145ccaaed4f175c7172a">llvm::SISrcMods::OP_SEL_0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442af0e8126187c47c5b74a1bdc635158144">llvm::SISrcMods::OP_SEL_1</a>, <a href="/web-llvm/docs/api/structs/vopmodifiers/#ac99f5b33e7000c0fc1807242045a7c06">VOPModifiers::OpSel</a> and <a href="/web-llvm/docs/api/structs/vopmodifiers/#adc6e974654f933ce90147818e89219a5">VOPModifiers::OpSelHi</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a5924dbd31504014961bf4324546da2cc">llvm::AMDGPUDisassembler::convertDPP8Inst</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a688f4832464547c17012a58790863c53">llvm::AMDGPUDisassembler::convertVOP3DPPInst</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#af2662661417cf1a8f0b242b84853829f">llvm::AMDGPUDisassembler::convertVOP3PDPPInst</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a074a4f039b95fd6ecd9a199e3db42097">llvm::AMDGPUDisassembler::convertVOPC64DPPInst</a>.</p>

</div>
</div>

### createAMDGPUDisassembler() {#abb9c73627ba15ed73cd8b8502c4137b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDisassembler * createAMDGPUDisassembler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 2603 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#abf297f3f63ca3282686b6b725d3ca818">LLVMInitializeAMDGPUDisassembler</a>.</p>

</div>
</div>

### createAMDGPUSymbolizer() {#ad088e3815766f6d9b2e8485f2e89351b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbolizer * createAMDGPUSymbolizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gaa8eb7ea1e53fd6e7a11b6aa4749c6e60">LLVMOpInfoCallback</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga05ffa603beb390898904a06b14ee5537">LLVMSymbolLookupCallback</a>, void * DisInfo, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> * Ctx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a> &gt; &amp;&amp; RelInfo)</td>
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



<p>Definition at line 2594 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Referenced by <a href="#abf297f3f63ca3282686b6b725d3ca818">LLVMInitializeAMDGPUDisassembler</a>.</p>

</div>
</div>

### createReservedKDBitsError() {#aff86ab78c9551cfaa6fd58da22f49dc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error createReservedKDBitsError (uint32_t Mask, unsigned BaseBytes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Msg="")</td>
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

<p>Create an error object to return from onSymbolStart for reserved kernel descriptor bits being set.</p>

<p>Definition at line 2296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2e3d3da964f7eb14ef2eabf0c4a08ba5">llvm::c_str</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a> and <a href="#a198680a0e69a43b37693d17862fffe63">getBitRangeFromMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a1ec298d8a742a9519e6dc0903f822f2b">llvm::AMDGPUDisassembler::decodeKernelDescriptorDirective</a>.</p>

</div>
</div>

### createReservedKDBytesError() {#aef7ddc0af2349fa45789289f716de36a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error createReservedKDBytesError (unsigned BaseInBytes, unsigned WidthInBytes)</td>
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

<p>Create an error object to return from onSymbolStart for reserved kernel descriptor bytes being set.</p>

<p>Definition at line 2305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a1ec298d8a742a9519e6dc0903f822f2b">llvm::AMDGPUDisassembler::decodeKernelDescriptorDirective</a>.</p>

</div>
</div>

### decodeAV10() {#af3c6d1f202232b10665e32f3c9c5170a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;AMDGPUDisassembler::OpWidthTy OpWidth&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeAV10 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, uint64_t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a724770ffa3ce3bb67ce53936f6123f72">decodeSrcOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab41bbc27a953d3ed08c9d36c7b9ae272a14af872950285c8905100828bc849349">llvm::AMDGPU::INT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/encvalues/#a8827d0769d5975ce9edb64c48d3a6614a1aabc86fcadc004d8e7a79e485174649">llvm::AMDGPU::EncValues::IS_VGPR</a>.</p>

</div>
</div>

### decodeAVLdSt() {#ac34073953af52bfb6d10afcfa08233cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeAVLdSt (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#ab8355dd4c437a99c65c3d9f3b6f5101a">AMDGPUDisassembler::OpWidthTy</a> Opw, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca953a5ba3766c4aea8d9b8eeeba722679">llvm::SIInstrFlags::DS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a3c5c7109f398fdca515509e2284cd8c0">llvm::MCInst::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#afd160d6c9cc947a3c786d83f07f06e71">IsAGPROperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="#a4ddc5958507d83b34305967186bb3ad1">decodeAVLdSt</a>.</p>

</div>
</div>

### decodeAVLdSt() {#a4ddc5958507d83b34305967186bb3ad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;AMDGPUDisassembler::OpWidthTy Opw&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeAVLdSt (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, uint64_t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="#ac34073953af52bfb6d10afcfa08233cd">decodeAVLdSt</a>.</p>

</div>
</div>

### decodeBoolReg() {#ad52fe682480e5a4022a50ddb9b03b80a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeBoolReg (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Val, uint64_t Addr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>.</p>

</div>
</div>

### decodeDpp8FI() {#a4e82e523aa3cdb6231fee9301ec1e93b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeDpp8FI (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Val, uint64_t Addr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>.</p>

</div>
</div>

### decodeOperand\_KImmFP() {#ab13514a8df17e5cc0eb7a570110c8aaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeOperand_KImmFP (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, uint64_t Addr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>.</p>

</div>
</div>

### decodeOperand\_VGPR\_16() {#a358acca39fd0fcf3a282b6050564162f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeOperand_VGPR_16 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, uint64_t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/encvalues/#a8827d0769d5975ce9edb64c48d3a6614a1aabc86fcadc004d8e7a79e485174649">llvm::AMDGPU::EncValues::IS_VGPR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

### decodeOperand\_VSrc\_f64() {#a518f398e1650cebe32756b5cb45c3da8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeOperand_VSrc_f64 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, uint64_t Addr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab41bbc27a953d3ed08c9d36c7b9ae272a1c2050e48d2c5ccd761ea8003597de90">llvm::AMDGPU::FP64</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#ab8355dd4c437a99c65c3d9f3b6f5101aaf4b2e7b624bfcb0b2c7116e43d97783a">llvm::AMDGPUDisassembler::OPW64</a>.</p>

</div>
</div>

### decodeOperand\_VSrcT16() {#ab64db06c075d376148faa2794e8a4d0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;AMDGPUDisassembler::OpWidthTy OpWidth, unsigned ImmWidth, unsigned OperandSemantics&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeOperand_VSrcT16 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, uint64_t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/encvalues/#a8827d0769d5975ce9edb64c48d3a6614a1aabc86fcadc004d8e7a79e485174649">llvm::AMDGPU::EncValues::IS_VGPR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

### decodeOperand\_VSrcT16\_Lo128() {#a501ee3504108a954dc813a4712ed3cb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;AMDGPUDisassembler::OpWidthTy OpWidth, unsigned ImmWidth, unsigned OperandSemantics&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeOperand_VSrcT16_Lo128 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, uint64_t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/encvalues/#a8827d0769d5975ce9edb64c48d3a6614a1aabc86fcadc004d8e7a79e485174649">llvm::AMDGPU::EncValues::IS_VGPR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

### decodeOperand\_VSrcT16\_Lo128\_Deferred() {#a7efe6ae246d870766f8d98f24906cde6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;AMDGPUDisassembler::OpWidthTy OpWidth, unsigned ImmWidth, unsigned OperandSemantics&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeOperand_VSrcT16_Lo128_Deferred (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, uint64_t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/encvalues/#a8827d0769d5975ce9edb64c48d3a6614a1aabc86fcadc004d8e7a79e485174649">llvm::AMDGPU::EncValues::IS_VGPR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

### decodeOperandVOPDDstY() {#ac9fa71823613012495803a4be21971d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeOperandVOPDDstY (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Val, uint64_t Addr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * Decoder)</td>
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



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>.</p>

</div>
</div>

### decodeSMEMOffset() {#a29ec63c03889b569a9f8ea9cc55e8f61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeSMEMOffset (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, uint64_t Addr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>.</p>

</div>
</div>

### decodeSOPPBrTarget() {#a5dc7b2dd9907d083db5fb49ac5490b97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeSOPPBrTarget (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, uint64_t Addr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### decodeSplitBarrier() {#af2f35a568e622ec0fa2fc9a0678d3d48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeSplitBarrier (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Val, uint64_t Addr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>.</p>

</div>
</div>

### decodeSrcA9() {#a35212d69efb20b5a402c000fc99bc2fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;AMDGPUDisassembler::OpWidthTy OpWidth&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeSrcA9 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, uint64_t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a724770ffa3ce3bb67ce53936f6123f72">decodeSrcOp</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab41bbc27a953d3ed08c9d36c7b9ae272a14af872950285c8905100828bc849349">llvm::AMDGPU::INT</a>.</p>

</div>
</div>

### decodeSrcAV10() {#aa8e88e4f3dac78e1282e220487ae2ab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;AMDGPUDisassembler::OpWidthTy OpWidth&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeSrcAV10 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, uint64_t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a724770ffa3ce3bb67ce53936f6123f72">decodeSrcOp</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab41bbc27a953d3ed08c9d36c7b9ae272a14af872950285c8905100828bc849349">llvm::AMDGPU::INT</a>.</p>

</div>
</div>

### decodeSrcOp() {#a724770ffa3ce3bb67ce53936f6123f72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeSrcOp (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned EncSize, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#ab8355dd4c437a99c65c3d9f3b6f5101a">AMDGPUDisassembler::OpWidthTy</a> OpWidth, unsigned Imm, unsigned EncImm, bool MandatoryLiteral, unsigned ImmWidth, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab41bbc27a953d3ed08c9d36c7b9ae272">AMDGPU::OperandSemantics</a> Sema, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#af3c6d1f202232b10665e32f3c9c5170a">decodeAV10</a>, <a href="#a35212d69efb20b5a402c000fc99bc2fa">decodeSrcA9</a>, <a href="#aa8e88e4f3dac78e1282e220487ae2ab9">decodeSrcAV10</a>, <a href="#a89ff868f77585a2e2f4ed4cb3495b627">decodeSrcReg9</a>, <a href="#a0e3809fc5da6085c65e5c7ed95d60485">decodeSrcRegOrImm9</a>, <a href="#a67efe1254e42ec0e86f7823257a40a38">decodeSrcRegOrImmA9</a> and <a href="#a4d5e8e8a196119453b96d7b758d8008b">decodeSrcRegOrImmDeferred9</a>.</p>

</div>
</div>

### decodeSrcReg9() {#a89ff868f77585a2e2f4ed4cb3495b627}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;AMDGPUDisassembler::OpWidthTy OpWidth&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeSrcReg9 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, uint64_t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a724770ffa3ce3bb67ce53936f6123f72">decodeSrcOp</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab41bbc27a953d3ed08c9d36c7b9ae272a14af872950285c8905100828bc849349">llvm::AMDGPU::INT</a>.</p>

</div>
</div>

### decodeSrcRegOrImm9() {#a0e3809fc5da6085c65e5c7ed95d60485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;AMDGPUDisassembler::OpWidthTy OpWidth, unsigned ImmWidth, unsigned OperandSemantics&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeSrcRegOrImm9 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, uint64_t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="#a724770ffa3ce3bb67ce53936f6123f72">decodeSrcOp</a>.</p>

</div>
</div>

### decodeSrcRegOrImmA9() {#a67efe1254e42ec0e86f7823257a40a38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;AMDGPUDisassembler::OpWidthTy OpWidth, unsigned ImmWidth, unsigned OperandSemantics&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeSrcRegOrImmA9 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, uint64_t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="#a724770ffa3ce3bb67ce53936f6123f72">decodeSrcOp</a>.</p>

</div>
</div>

### decodeSrcRegOrImmDeferred9() {#a4d5e8e8a196119453b96d7b758d8008b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;AMDGPUDisassembler::OpWidthTy OpWidth, unsigned ImmWidth, unsigned OperandSemantics&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeSrcRegOrImmDeferred9 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, uint64_t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="#a724770ffa3ce3bb67ce53936f6123f72">decodeSrcOp</a>.</p>

</div>
</div>

### decodeVersionImm() {#a31d2138e4e8a3d618d9841a3b13c5609}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus decodeVersionImm (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, uint64_t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> and <a href="#a31d2138e4e8a3d618d9841a3b13c5609">decodeVersionImm</a>.</p>


<p>Referenced by <a href="#a31d2138e4e8a3d618d9841a3b13c5609">decodeVersionImm</a>.</p>

</div>
</div>

### DecodeVGPR\_16\_Lo128RegisterClass() {#ac4f043e93fc1f83ea48a4f98bdfa8958}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeVGPR_16_Lo128RegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, uint64_t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

### DecodeVGPR\_16RegisterClass() {#a869eb0ec1821f8576c98ced8745b1f30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeVGPR_16RegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Imm, uint64_t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="#a869eb0ec1821f8576c98ced8745b1f30">DecodeVGPR_16RegisterClass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>


<p>Referenced by <a href="#a869eb0ec1821f8576c98ced8745b1f30">DecodeVGPR_16RegisterClass</a>.</p>

</div>
</div>

### eat12Bytes() {#a434621cd1f8f1c0240a47b65ba19ea9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecoderUInt128 eat12Bytes (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &amp; Bytes)</td>
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



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#acfdf941f45bc58470ed8423b98862486">llvm::support::endian::read</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#ad9305ad45a7db970a0a198791bea136a">llvm::AMDGPUDisassembler::getInstruction</a>.</p>

</div>
</div>

### eat16Bytes() {#a7d8ee6944c8121c49c2a8da4b1695fe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecoderUInt128 eat16Bytes (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &amp; Bytes)</td>
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



<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#acfdf941f45bc58470ed8423b98862486">llvm::support::endian::read</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#ad9305ad45a7db970a0a198791bea136a">llvm::AMDGPUDisassembler::getInstruction</a>.</p>

</div>
</div>

### eatBytes() {#aaff8a7b712c8ea0bb1275e621119e498}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T eatBytes (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &amp; Bytes)</td>
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



<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#acfdf941f45bc58470ed8423b98862486">llvm::support::endian::read</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a8c8699483ef63f1164acdd8a35f49066">llvm::AMDGPUDisassembler::decodeLiteralConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#ad9305ad45a7db970a0a198791bea136a">llvm::AMDGPUDisassembler::getInstruction</a>.</p>

</div>
</div>

### getBitRangeFromMask() {#a198680a0e69a43b37693d17862fffe63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt; 32 &gt; getBitRangeFromMask (uint32_t Mask, unsigned BaseBytes)</td>
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

<p>Print a string describing the reserved bit range specified by Mask with offset BaseBytes for use in error comments.</p>


<p>Mask is a single continuous range of 1s surrounded by zeros. The format here is meant to align with the tables that describe these bits in llvm.org/docs/AMDGPUUsage.html.</p>


<p>Definition at line 1998 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>.</p>


<p>Referenced by <a href="#aff86ab78c9551cfaa6fd58da22f49dc5">createReservedKDBitsError</a>.</p>

</div>
</div>

### getInlineImmVal16() {#a51cb222cd0ee12f7f7eb5c1aba1f1803}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t getInlineImmVal16 (unsigned Imm, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab41bbc27a953d3ed08c9d36c7b9ae272">AMDGPU::OperandSemantics</a> Sema)</td>
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



<p>Definition at line 1518 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab41bbc27a953d3ed08c9d36c7b9ae272a28961929a5f217cc19f135d1a9d0efe8">llvm::AMDGPU::BF16</a>, <a href="#a596016f0072634c2d21a74e672d29719">getInlineImmValBF16</a> and <a href="#ad74d02e562b22b0af8c697d2df57a09e">getInlineImmValF16</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a7e463b2ce57bfddac123b8ae44feba93">llvm::AMDGPUDisassembler::decodeFPImmed</a>.</p>

</div>
</div>

### getInlineImmVal32() {#a96eff11e4ce91e92cfaa3e59f7600100}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t getInlineImmVal32 (unsigned Imm)</td>
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



<p>Definition at line 1418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a7e463b2ce57bfddac123b8ae44feba93">llvm::AMDGPUDisassembler::decodeFPImmed</a>.</p>

</div>
</div>

### getInlineImmVal64() {#aadb457499c6b9db87a068c5ae53ba32e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t getInlineImmVal64 (unsigned Imm)</td>
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



<p>Definition at line 1443 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a7e463b2ce57bfddac123b8ae44feba93">llvm::AMDGPUDisassembler::decodeFPImmed</a>.</p>

</div>
</div>

### getInlineImmValBF16() {#a596016f0072634c2d21a74e672d29719}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t getInlineImmValBF16 (unsigned Imm)</td>
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



<p>Definition at line 1493 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a51cb222cd0ee12f7f7eb5c1aba1f1803">getInlineImmVal16</a>.</p>

</div>
</div>

### getInlineImmValF16() {#ad74d02e562b22b0af8c697d2df57a09e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t getInlineImmValF16 (unsigned Imm)</td>
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



<p>Definition at line 1468 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a51cb222cd0ee12f7f7eb5c1aba1f1803">getInlineImmVal16</a>.</p>

</div>
</div>

### insertNamedMCOperand() {#a39c0a22d457ccc212829d0a052685264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int insertNamedMCOperand (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; Op, uint16_t NameIdx)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a5924dbd31504014961bf4324546da2cc">llvm::AMDGPUDisassembler::convertDPP8Inst</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a0fcaab7e1e2ab1a6575d41a5e3fe99db">llvm::AMDGPUDisassembler::convertEXPInst</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a70ebec5cbc0a8238828d0527a06568f1">llvm::AMDGPUDisassembler::convertFMAanyK</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a4974310fb906d87e0b82ea333101d33c">llvm::AMDGPUDisassembler::convertMacDPPInst</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a9a2160759492c85b0f23cc8e5d9538f6">llvm::AMDGPUDisassembler::convertSDWAInst</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a951e9da312d0c74b6988e59280910007">llvm::AMDGPUDisassembler::convertVINTERPInst</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a688f4832464547c17012a58790863c53">llvm::AMDGPUDisassembler::convertVOP3DPPInst</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#af2662661417cf1a8f0b242b84853829f">llvm::AMDGPUDisassembler::convertVOP3PDPPInst</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a074a4f039b95fd6ecd9a199e3db42097">llvm::AMDGPUDisassembler::convertVOPC64DPPInst</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a2021d83fb89da51586187868e0ba649d">llvm::AMDGPUDisassembler::convertVOPCDPPInst</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#ad9305ad45a7db970a0a198791bea136a">llvm::AMDGPUDisassembler::getInstruction</a>.</p>

</div>
</div>

### IsAGPROperand() {#a67245482e0fb8189af448dfed2bc154a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IsAGPROperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, int OpIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> * MRI)</td>
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



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### LLVMInitializeAMDGPUDisassembler() {#abf297f3f63ca3282686b6b725d3ca818}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_EXTERNAL_VISIBILITY void LLVMInitializeAMDGPUDisassembler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2609 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#abb9c73627ba15ed73cd8b8502c4137b3">createAMDGPUDisassembler</a>, <a href="#ad088e3815766f6d9b2e8485f2e89351b">createAMDGPUSymbolizer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa4a596c65b215aae8d1ae5da8d1b63fc">llvm::getTheGCNTarget</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a8d3c3e977776517a7c1a82060b16da9f">llvm::TargetRegistry::RegisterMCDisassembler</a> and <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a0a47aba9e8635c85eef8e87912e87810">llvm::TargetRegistry::RegisterMCSymbolizer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### CHECK\_RESERVED\_BITS {#aa33da5c37d93576ec4aacb9ce7672368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CHECK_RESERVED_BITS(MASK)&nbsp;&nbsp;&nbsp;<a href="#aedb8704fbe2ff70f458c06faec5462a7">CHECK_RESERVED_BITS_IMPL</a>(MASK, #MASK, "")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2037 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a1a717ebce0af699c0b264313d0cb21e2">llvm::AMDGPUDisassembler::decodeCOMPUTE_PGM_RSRC1</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a341ce9a65b287f8033788c0bb12d8fa3">llvm::AMDGPUDisassembler::decodeCOMPUTE_PGM_RSRC2</a>.</p>

</div>
</div>

### CHECK\_RESERVED\_BITS\_DESC {#a00cbaf3dc4f08d1784589594dfe6149d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CHECK_RESERVED_BITS_DESC(MASK, DESC)&nbsp;&nbsp;&nbsp;  <a href="#aedb8704fbe2ff70f458c06faec5462a7">CHECK_RESERVED_BITS_IMPL</a>(MASK, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetailpredication-cpp/#a51f62d37762db1aa829ad4fe2627fbf9">DESC</a>, "")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2040 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a1a717ebce0af699c0b264313d0cb21e2">llvm::AMDGPUDisassembler::decodeCOMPUTE_PGM_RSRC1</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a341ce9a65b287f8033788c0bb12d8fa3">llvm::AMDGPUDisassembler::decodeCOMPUTE_PGM_RSRC2</a>.</p>

</div>
</div>

### CHECK\_RESERVED\_BITS\_DESC\_MSG {#afa52988bf1e093da5f3499a666cf0a63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CHECK_RESERVED_BITS_DESC_MSG(MASK, DESC, MSG)&nbsp;&nbsp;&nbsp;  <a href="#aedb8704fbe2ff70f458c06faec5462a7">CHECK_RESERVED_BITS_IMPL</a>(MASK, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetailpredication-cpp/#a51f62d37762db1aa829ad4fe2627fbf9">DESC</a>, ", " MSG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2042 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a1a717ebce0af699c0b264313d0cb21e2">llvm::AMDGPUDisassembler::decodeCOMPUTE_PGM_RSRC1</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a7de6bde5116ff125fb02491b47586333">llvm::AMDGPUDisassembler::decodeCOMPUTE_PGM_RSRC3</a>.</p>

</div>
</div>

### CHECK\_RESERVED\_BITS\_IMPL {#aedb8704fbe2ff70f458c06faec5462a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CHECK_RESERVED_BITS_IMPL(MASK, DESC, MSG)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  do {                                                                         \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (FourByteBuffer &amp; (MASK)) {                                             \
      return createStringError(std::errc::invalid_argument,                    \
                               "kernel descriptor " DESC                       \
                               " reserved %s set" MSG,                         \
                               <a href="#a198680a0e69a43b37693d17862fffe63">getBitRangeFromMask</a>((MASK), 0).c_str());        \
    }                                                                          \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (0)
</div>
</dd>
</dl>

<p>Definition at line 2027 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>

</div>
</div>

### CHECK\_RESERVED\_BITS\_MSG {#ac67c208c1ef5d548e50e8d2efb76fc2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CHECK_RESERVED_BITS_MSG(MASK, MSG)&nbsp;&nbsp;&nbsp;  <a href="#aedb8704fbe2ff70f458c06faec5462a7">CHECK_RESERVED_BITS_IMPL</a>(MASK, #MASK, ", " MSG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2038 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a1a717ebce0af699c0b264313d0cb21e2">llvm::AMDGPUDisassembler::decodeCOMPUTE_PGM_RSRC1</a>.</p>

</div>
</div>

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"amdgpu-disassembler"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>

</div>
</div>

### DECODE\_OPERAND {#afec291717f10788ac7009575db1dc651}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DECODE_OPERAND(StaticDecoderName, DecoderName)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a> StaticDecoderName(<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp;Inst, unsigned Imm,            \
                                        uint64_t /*Addr*/,                     \
                                        <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> *Decoder) {       \
    auto DAsm = static_cast&lt;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler">AMDGPUDisassembler</a> *&gt;(Decoder);              \
    return <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>(Inst, DAsm-&gt;DecoderName(Imm));                           \
  }
</div>
</dd>
</dl>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>

</div>
</div>

### DECODE\_OPERAND\_REG\_7 {#a9a33e20626a398a086dc8f51c676b75e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DECODE_OPERAND_REG_7(RegClass, OpWidth)&nbsp;&nbsp;&nbsp;  <a href="#a36efcd12c7aade02f99937d563a9dd16">DECODE_SrcOp</a>(Decode##RegClass##RegisterClass, 7, OpWidth, Imm, false, 0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>

</div>
</div>

### DECODE\_OPERAND\_REG\_8 {#a6f4aff7bd0c86d4158d48058d67825ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DECODE_OPERAND_REG_8(RegClass)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a> Decode##RegClass##RegisterClass(                         \
      <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp;Inst, unsigned Imm, uint64_t /*Addr*/,                           \
      <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> *Decoder) {                                         \
    <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>(Imm &lt; (1 &lt;&lt; 8) &amp;&amp; "8-bit encoding");                                \
    auto DAsm = static_cast&lt;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler">AMDGPUDisassembler</a> *&gt;(Decoder);              \
    return <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>(                                                         \
        Inst, DAsm-&gt;createRegOperand(AMDGPU::RegClass##RegClassID, Imm));      \
  }
</div>
</dd>
</dl>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>

</div>
</div>

### DECODE\_SDWA {#a5d7e4c42994334246aaea74d14f0f08c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DECODE_SDWA(DecName)&nbsp;&nbsp;&nbsp;<a href="#afec291717f10788ac7009575db1dc651">DECODE_OPERAND</a>(decodeSDWA##DecName, decodeSDWA##DecName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>

</div>
</div>

### DECODE\_SrcOp {#a36efcd12c7aade02f99937d563a9dd16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DECODE_SrcOp(Name, EncSize, OpWidth, EncImm, MandatoryLiteral, ImmWidth)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a> Name(<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp;Inst, unsigned Imm, uint64_t /*Addr*/,      \
                           <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> *Decoder) {                    \
    <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>(Imm &lt; (1 &lt;&lt; EncSize) &amp;&amp; #EncSize "-bit encoding");                  \
    auto DAsm = static_cast&lt;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler">AMDGPUDisassembler</a> *&gt;(Decoder);              \
    return <a href="#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>(Inst,                                                    \
                      DAsm-&gt;<a href="#a724770ffa3ce3bb67ce53936f6123f72">decodeSrcOp</a>(AMDGPUDisassembler::OpWidth, EncImm,   \
                                        MandatoryLiteral, ImmWidth));          \
  }
</div>
</dd>
</dl>

<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>

</div>
</div>

### GET\_FIELD {#adbe651d6dbda0f8eacf67b705a8d3b13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_FIELD(MASK)&nbsp;&nbsp;&nbsp;(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h/#a286f2813b785a6b1d7f9c688580c2dc4">AMDHSA_BITS_GET</a>(FourByteBuffer, MASK))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2016 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a1a717ebce0af699c0b264313d0cb21e2">llvm::AMDGPUDisassembler::decodeCOMPUTE_PGM_RSRC1</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a7de6bde5116ff125fb02491b47586333">llvm::AMDGPUDisassembler::decodeCOMPUTE_PGM_RSRC3</a>.</p>

</div>
</div>

### PRINT\_DIRECTIVE {#a7b14fc850e8e58263a51cd89e7d6c838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PRINT_DIRECTIVE(DIRECTIVE, MASK)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  do {                                                                         \
    KdStream &lt;&lt; Indent &lt;&lt; DIRECTIVE " " &lt;&lt; <a href="#adbe651d6dbda0f8eacf67b705a8d3b13">GET_FIELD</a>(MASK) &lt;&lt; '\n';            \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (0)
</div>
</dd>
</dl>

<p>Definition at line 2017 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a1a717ebce0af699c0b264313d0cb21e2">llvm::AMDGPUDisassembler::decodeCOMPUTE_PGM_RSRC1</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a341ce9a65b287f8033788c0bb12d8fa3">llvm::AMDGPUDisassembler::decodeCOMPUTE_PGM_RSRC2</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a7de6bde5116ff125fb02491b47586333">llvm::AMDGPUDisassembler::decodeCOMPUTE_PGM_RSRC3</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a1ec298d8a742a9519e6dc0903f822f2b">llvm::AMDGPUDisassembler::decodeKernelDescriptorDirective</a>.</p>

</div>
</div>

### PRINT\_DIRECTIVE {#a674d2e9303a1f09156c06c1320a4a096}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PRINT_DIRECTIVE(DIRECTIVE, MASK)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  do {                                                                         \
    KdStream &lt;&lt; Indent &lt;&lt; DIRECTIVE " "                                        \
             &lt;&lt; ((TwoByteBuffer &amp; MASK) &gt;&gt; (MASK##_SHIFT)) &lt;&lt; '\n';            \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (0)
</div>
</dd>
</dl>

<p>Definition at line 2318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>

</div>
</div>

### PRINT\_PSEUDO\_DIRECTIVE\_COMMENT {#a44e38092dcf380740d2ead9690ae9bfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PRINT_PSEUDO_DIRECTIVE_COMMENT(DIRECTIVE, MASK)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  do {                                                                         \
    KdStream &lt;&lt; Indent &lt;&lt; MAI.getCommentString() &lt;&lt; ' ' &lt;&lt; DIRECTIVE " "       \
             &lt;&lt; <a href="#adbe651d6dbda0f8eacf67b705a8d3b13">GET_FIELD</a>(MASK) &lt;&lt; '\n';                                       \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (0)
</div>
</dd>
</dl>

<p>Definition at line 2021 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a7de6bde5116ff125fb02491b47586333">llvm::AMDGPUDisassembler::decodeCOMPUTE_PGM_RSRC3</a>.</p>

</div>
</div>

### SGPR\_MAX {#aac8b18da22658e7589a0286322114803}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SGPR_MAX&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  (isGFX10Plus() ? AMDGPU::EncValues::SGPR_MAX_GFX10                           \
                 : AMDGPU::EncValues::SGPR_MAX_SI)
</div>
</dd>
</dl>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a7d7fece3c5c1c1d977334eb948baecfe">llvm::AMDGPUDisassembler::decodeNonVGPRSrcOp</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a9481f68151f53dba0f1e3416819e6e26">llvm::AMDGPUDisassembler::decodeSDWAVopcDst</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
