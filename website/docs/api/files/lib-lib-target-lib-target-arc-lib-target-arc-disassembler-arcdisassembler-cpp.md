---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ARCDisassembler.cpp` File Reference

<p>This file is part of the ARC Disassembler. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arc-h">ARC.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcregisterinfo-h">ARCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcmctargetdesc-h">MCTargetDesc/ARCMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/targetinfo/arctargetinfo-h">TargetInfo/ARCTargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdecoderops-h">llvm/MC/MCDecoderOps.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcdisassembler-h">llvm/MC/MCDisassembler/MCDisassembler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrinfo-h">llvm/MC/MCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "ARCGenDisassemblerTables.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-arcdisassembler-cpp-">anonymous{ARCDisassembler.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-arcdisassembler-cpp-/arcdisassembler">ARCDisassembler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A disassembler class for ARC. <a href="/web-llvm/docs/api/classes/anonymous-arcdisassembler-cpp-/arcdisassembler/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d2ff5b7963ea79edc3889c72d7c39f5">readInstruction32</a> (ArrayRef&lt; uint8_t &gt; Bytes, uint64_t Address, uint64_t &amp;Size, uint32_t &amp;Insn)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a682f94cca74aeb23b1ab9c3b21380524">readInstruction64</a> (ArrayRef&lt; uint8_t &gt; Bytes, uint64_t Address, uint64_t &amp;Size, uint64_t &amp;Insn)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06df81cdff05ab7e363c6200e08a4521">readInstruction48</a> (ArrayRef&lt; uint8_t &gt; Bytes, uint64_t Address, uint64_t &amp;Size, uint64_t &amp;Insn)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a891641445e1af3e482f70a7264fba239">readInstruction16</a> (ArrayRef&lt; uint8_t &gt; Bytes, uint64_t Address, uint64_t &amp;Size, uint32_t &amp;Insn)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned B&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aace1f9726acd8d551604f23b4a2181a5">DecodeSignedOperand</a> (MCInst &amp;Inst, unsigned InsnS, uint64_t Address=0, const MCDisassembler *Decoder=nullptr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned B&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aac5afffddb9acd82d70ce8d4d86583ef">DecodeFromCyclicRange</a> (MCInst &amp;Inst, unsigned InsnS, uint64_t Address=0, const MCDisassembler *Decoder=nullptr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned B&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a59a9da13eca5fb814fd83303536747cf">DecodeBranchTargetS</a> (MCInst &amp;Inst, unsigned InsnS, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af48dd6610db11d5275ece9154300e514">DecodeMEMrs9</a> (MCInst &amp;, unsigned, uint64_t, const MCDisassembler *)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7956d4781c08702515a296790075c9d">DecodeLdLImmInstruction</a> (MCInst &amp;, uint64_t, uint64_t, const MCDisassembler *)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad49072913256760cce9a52ad08e123a6">DecodeStLImmInstruction</a> (MCInst &amp;, uint64_t, uint64_t, const MCDisassembler *)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1de0eac0bd3c65f8050ee57e0a004867">DecodeLdRLImmInstruction</a> (MCInst &amp;, uint64_t, uint64_t, const MCDisassembler *)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a746079c286d5e7dfd559520006cdbc82">DecodeSOPwithRS12</a> (MCInst &amp;, uint64_t, uint64_t, const MCDisassembler *)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2197fd22b3d4ec0302f9cc79d12a3402">DecodeSOPwithRU6</a> (MCInst &amp;, uint64_t, uint64_t, const MCDisassembler *)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04341f61408b84cf6d7b2b0a0485e437">DecodeCCRU6Instruction</a> (MCInst &amp;, uint64_t, uint64_t, const MCDisassembler *)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a347760ad409026bf174cb84186f2db33">DecodeMoveHRegInstruction</a> (MCInst &amp;Inst, uint64_t, uint64_t, const MCDisassembler *)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9deefe6628459b5cbdd92a375df7e139">DecodeGPR32RegisterClass</a> (MCInst &amp;Inst, unsigned RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0b5ad2d77b40f2a0ad5a186816ebf21">DecodeGBR32ShortRegister</a> (MCInst &amp;Inst, unsigned RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bfa2ec4204200e2afb6bedb6469e1cb">decodeCField</a> (unsigned Insn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c70fd25f059a226c407ddfeb4fc3ae7">decodeBField</a> (unsigned Insn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affbdff2d7ee69783b269fca2b967b7a8">decodeAField</a> (unsigned Insn)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af63af5d1f6f85810fdfcf4db31836760">DecodeSymbolicOperand</a> (MCInst &amp;Inst, uint64_t Address, uint64_t Value, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad51be7b10c11546e324f87e8f9a418b6">DecodeSymbolicOperandOff</a> (MCInst &amp;Inst, uint64_t Address, uint64_t Offset, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a705a8d3ec6b38a2b1e6dbab98241f287">createARCDisassembler</a> (const Target &amp;T, const MCSubtargetInfo &amp;STI, MCContext &amp;Ctx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87812879cf9b970b38668d2b1c1c7e46">LLVMInitializeARCDisassembler</a> ()</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add638d686c2786f42f08b7ad619fc6e9">GPR32DecoderTable</a>[] = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"arc-disassembler"</td>
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

<p>This file is part of the ARC Disassembler.</p>

<div class="doxySectionDef">

## Functions

### createARCDisassembler() {#a705a8d3ec6b38a2b1e6dbab98241f287}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDisassembler * createARCDisassembler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-arcdisassembler-cpp-/arcdisassembler/#ae69d0569b9155105a177e688cf85466c">anonymous{ARCDisassembler.cpp}::ARCDisassembler::ARCDisassembler</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a87812879cf9b970b38668d2b1c1c7e46">LLVMInitializeARCDisassembler</a>.</p>

</div>
</div>

### decodeAField() {#affbdff2d7ee69783b269fca2b967b7a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned decodeAField (unsigned Insn)</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>.</p>


<p>Referenced by <a href="#aa7956d4781c08702515a296790075c9d">DecodeLdLImmInstruction</a> and <a href="#a1de0eac0bd3c65f8050ee57e0a004867">DecodeLdRLImmInstruction</a>.</p>

</div>
</div>

### decodeBField() {#a6c70fd25f059a226c407ddfeb4fc3ae7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned decodeBField (unsigned Insn)</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>.</p>


<p>Referenced by <a href="#a04341f61408b84cf6d7b2b0a0485e437">DecodeCCRU6Instruction</a>, <a href="#aa7956d4781c08702515a296790075c9d">DecodeLdLImmInstruction</a>, <a href="#a1de0eac0bd3c65f8050ee57e0a004867">DecodeLdRLImmInstruction</a>, <a href="#a746079c286d5e7dfd559520006cdbc82">DecodeSOPwithRS12</a>, <a href="#a2197fd22b3d4ec0302f9cc79d12a3402">DecodeSOPwithRU6</a> and <a href="#ad49072913256760cce9a52ad08e123a6">DecodeStLImmInstruction</a>.</p>

</div>
</div>

### DecodeBranchTargetS() {#a59a9da13eca5fb814fd83303536747cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned B&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeBranchTargetS (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned InsnS, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ad51be7b10c11546e324f87e8f9a418b6">DecodeSymbolicOperandOff</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd6925150e1774fabfaff17efd3f9b9e">llvm::SignExtend32</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### DecodeCCRU6Instruction() {#a04341f61408b84cf6d7b2b0a0485e437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeCCRU6Instruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, uint64_t Insn, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a6c70fd25f059a226c407ddfeb4fc3ae7">decodeBField</a>, <a href="#a9deefe6628459b5cbdd92a375df7e139">DecodeGPR32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### decodeCField() {#a5bfa2ec4204200e2afb6bedb6469e1cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned decodeCField (unsigned Insn)</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>.</p>


<p>Referenced by <a href="#a1de0eac0bd3c65f8050ee57e0a004867">DecodeLdRLImmInstruction</a> and <a href="#ad49072913256760cce9a52ad08e123a6">DecodeStLImmInstruction</a>.</p>

</div>
</div>

### DecodeFromCyclicRange() {#aac5afffddb9acd82d70ce8d4d86583ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned B&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeFromCyclicRange (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned InsnS, uint64_t Address=0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder=nullptr)</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">llvm::max</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### DecodeGBR32ShortRegister() {#ad0b5ad2d77b40f2a0ad5a186816ebf21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeGBR32ShortRegister (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a> and <a href="#a9deefe6628459b5cbdd92a375df7e139">DecodeGPR32RegisterClass</a>.</p>

</div>
</div>

### DecodeGPR32RegisterClass() {#a9deefe6628459b5cbdd92a375df7e139}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeGPR32RegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="#add638d686c2786f42f08b7ad619fc6e9">GPR32DecoderTable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>


<p>Referenced by <a href="#a04341f61408b84cf6d7b2b0a0485e437">DecodeCCRU6Instruction</a>, <a href="#ad0b5ad2d77b40f2a0ad5a186816ebf21">DecodeGBR32ShortRegister</a>, <a href="#aa7956d4781c08702515a296790075c9d">DecodeLdLImmInstruction</a>, <a href="#a1de0eac0bd3c65f8050ee57e0a004867">DecodeLdRLImmInstruction</a>, <a href="#af48dd6610db11d5275ece9154300e514">DecodeMEMrs9</a>, <a href="#a347760ad409026bf174cb84186f2db33">DecodeMoveHRegInstruction</a>, <a href="#a746079c286d5e7dfd559520006cdbc82">DecodeSOPwithRS12</a>, <a href="#a2197fd22b3d4ec0302f9cc79d12a3402">DecodeSOPwithRU6</a> and <a href="#ad49072913256760cce9a52ad08e123a6">DecodeStLImmInstruction</a>.</p>

</div>
</div>

### DecodeLdLImmInstruction() {#aa7956d4781c08702515a296790075c9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeLdLImmInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, uint64_t Insn, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#affbdff2d7ee69783b269fca2b967b7a8">decodeAField</a>, <a href="#a6c70fd25f059a226c407ddfeb4fc3ae7">decodeBField</a>, <a href="#a9deefe6628459b5cbdd92a375df7e139">DecodeGPR32RegisterClass</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### DecodeLdRLImmInstruction() {#a1de0eac0bd3c65f8050ee57e0a004867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeLdRLImmInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, uint64_t Insn, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#affbdff2d7ee69783b269fca2b967b7a8">decodeAField</a>, <a href="#a6c70fd25f059a226c407ddfeb4fc3ae7">decodeBField</a>, <a href="#a5bfa2ec4204200e2afb6bedb6469e1cb">decodeCField</a>, <a href="#a9deefe6628459b5cbdd92a375df7e139">DecodeGPR32RegisterClass</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### DecodeMEMrs9() {#af48dd6610db11d5275ece9154300e514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeMEMrs9 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Insn, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Dec)</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a9deefe6628459b5cbdd92a375df7e139">DecodeGPR32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd6925150e1774fabfaff17efd3f9b9e">llvm::SignExtend32</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### DecodeMoveHRegInstruction() {#a347760ad409026bf174cb84186f2db33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeMoveHRegInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, uint64_t Insn, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a9deefe6628459b5cbdd92a375df7e139">DecodeGPR32RegisterClass</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### DecodeSignedOperand() {#aace1f9726acd8d551604f23b4a2181a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned B&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeSignedOperand (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned InsnS, uint64_t Address=0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder=nullptr)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79dff91526e31b1a05f59eed6c189eb4">llvm::maskTrailingOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd6925150e1774fabfaff17efd3f9b9e">llvm::SignExtend32</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### DecodeSOPwithRS12() {#a746079c286d5e7dfd559520006cdbc82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeSOPwithRS12 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, uint64_t Insn, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a6c70fd25f059a226c407ddfeb4fc3ae7">decodeBField</a>, <a href="#a9deefe6628459b5cbdd92a375df7e139">DecodeGPR32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0ab75fcdd2d72d9e000beab48622402d93">llvm::Lower</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0a19de5b94f7b83900d4b296d9fa491aec">llvm::Upper</a>.</p>

</div>
</div>

### DecodeSOPwithRU6() {#a2197fd22b3d4ec0302f9cc79d12a3402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeSOPwithRU6 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, uint64_t Insn, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a6c70fd25f059a226c407ddfeb4fc3ae7">decodeBField</a>, <a href="#a9deefe6628459b5cbdd92a375df7e139">DecodeGPR32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### DecodeStLImmInstruction() {#ad49072913256760cce9a52ad08e123a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeStLImmInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, uint64_t Insn, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a6c70fd25f059a226c407ddfeb4fc3ae7">decodeBField</a>, <a href="#a5bfa2ec4204200e2afb6bedb6469e1cb">decodeCField</a>, <a href="#a9deefe6628459b5cbdd92a375df7e139">DecodeGPR32RegisterClass</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### DecodeSymbolicOperand() {#af63af5d1f6f85810fdfcf4db31836760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DecodeSymbolicOperand (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, uint64_t Address, uint64_t Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a495c1c01a620a4f59ff21e667a90c35d">llvm::MCDisassembler::tryAddingSymbolicOperand</a>.</p>


<p>Referenced by <a href="#ad51be7b10c11546e324f87e8f9a418b6">DecodeSymbolicOperandOff</a>.</p>

</div>
</div>

### DecodeSymbolicOperandOff() {#ad51be7b10c11546e324f87e8f9a418b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DecodeSymbolicOperandOff (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, uint64_t Address, uint64_t Offset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#af63af5d1f6f85810fdfcf4db31836760">DecodeSymbolicOperand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a59a9da13eca5fb814fd83303536747cf">DecodeBranchTargetS</a>.</p>

</div>
</div>

### LLVMInitializeARCDisassembler() {#a87812879cf9b970b38668d2b1c1c7e46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_EXTERNAL_VISIBILITY void LLVMInitializeARCDisassembler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="#a705a8d3ec6b38a2b1e6dbab98241f287">createARCDisassembler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3c0e65af5c2ac2ab2dde70232e30fe50">llvm::getTheARCTarget</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a> and <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a8d3c3e977776517a7c1a82060b16da9f">llvm::TargetRegistry::RegisterMCDisassembler</a>.</p>

</div>
</div>

### readInstruction16() {#a891641445e1af3e482f70a7264fba239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool readInstruction16 (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Bytes, uint64_t Address, uint64_t &amp; Size, uint32_t &amp; Insn)</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-arcdisassembler-cpp-/arcdisassembler/#a60a4c495767416121a1937808b181361">anonymous{ARCDisassembler.cpp}::ARCDisassembler::getInstruction</a>.</p>

</div>
</div>

### readInstruction32() {#a9d2ff5b7963ea79edc3889c72d7c39f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool readInstruction32 (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Bytes, uint64_t Address, uint64_t &amp; Size, uint32_t &amp; Insn)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-arcdisassembler-cpp-/arcdisassembler/#a60a4c495767416121a1937808b181361">anonymous{ARCDisassembler.cpp}::ARCDisassembler::getInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/lanaidisassembler/#ab76206f183c98836269293f7e597b8f7">llvm::LanaiDisassembler::getInstruction</a>.</p>

</div>
</div>

### readInstruction48() {#a06df81cdff05ab7e363c6200e08a4521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool readInstruction48 (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Bytes, uint64_t Address, uint64_t &amp; Size, uint64_t &amp; Insn)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-arcdisassembler-cpp-/arcdisassembler/#a60a4c495767416121a1937808b181361">anonymous{ARCDisassembler.cpp}::ARCDisassembler::getInstruction</a>.</p>

</div>
</div>

### readInstruction64() {#a682f94cca74aeb23b1ab9c3b21380524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool readInstruction64 (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Bytes, uint64_t Address, uint64_t &amp; Size, uint64_t &amp; Insn)</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-arcdisassembler-cpp-/arcdisassembler/#a60a4c495767416121a1937808b181361">anonymous{ARCDisassembler.cpp}::ARCDisassembler::getInstruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### GPR32DecoderTable {#add638d686c2786f42f08b7ad619fc6e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint16_t GPR32DecoderTable[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    ARC::R0,  ARC::R1,    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h/#a9211f62d8e1e6de999eaa63ec0f6ae02">ARC::R2</a>,  ARC::R3,   <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h/#a166646d6a4037a236119b6e156051d90">ARC::R4</a>,  ARC::R5,  <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h/#ace331bebb5bd2780b8dfb7e6e97db7dd">ARC::R6</a>,
    ARC::R7,  ARC::R8,    ARC::R9,  ARC::R10,  ARC::R11, ARC::R12, ARC::R13,
    ARC::R14, ARC::R15,   ARC::R16, ARC::R17,  ARC::R18, ARC::R19, ARC::R20,
    ARC::R21, ARC::R22,   ARC::R23, ARC::R24,  ARC::R25, ARC::GP,  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">ARC::FP</a>,
    ARC::SP,  ARC::ILINK, ARC::R30, ARC::BLINK}
</div>
</dd>
</dl>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>


<p>Referenced by <a href="#a9deefe6628459b5cbdd92a375df7e139">DecodeGPR32RegisterClass</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp/#ad5c79fab583fc33e74dccc9bbbbd4d33">DecodeGPR32RegisterClass</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"arc-disassembler"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp">ARCDisassembler.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
