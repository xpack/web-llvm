---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `HexagonDisassembler.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonbaseinfo-h">MCTargetDesc/HexagonBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcchecker-h">MCTargetDesc/HexagonMCChecker.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">MCTargetDesc/HexagonMCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">MCTargetDesc/HexagonMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/targetinfo/hexagontargetinfo-h">TargetInfo/HexagonTargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdecoderops-h">llvm/MC/MCDecoderOps.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcdisassembler-h">llvm/MC/MCDisassembler/MCDisassembler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrinfo-h">llvm/MC/MCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">llvm/Support/Endian.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;memory&gt;
#include "HexagonDepDecoders.inc"
#include "HexagonGenDisassemblerTables.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-hexagondisassembler-cpp-">anonymous{HexagonDisassembler.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler">HexagonDisassembler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/hexagon">Hexagon</a> disassembler for all <a href="/web-llvm/docs/api/namespaces/llvm/hexagon">Hexagon</a> platforms. <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7c8b2ad6feda021ec9b6390f7c2ee26">DecodeIntRegsRegisterClass</a> (MCInst &amp;Inst, unsigned RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2a9bc273f95cc3abf60d457d766b1da">DecodeGeneralSubRegsRegisterClass</a> (MCInst &amp;Inst, unsigned RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c2459e050125014180f42d4ace0ed5f">DecodeIntRegsLow8RegisterClass</a> (MCInst &amp;Inst, unsigned RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47853acb4dae5246097b634690d019a4">DecodeHvxVRRegisterClass</a> (MCInst &amp;Inst, unsigned RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bf4202898855e8ca8faf99fe3699de5">DecodeDoubleRegsRegisterClass</a> (MCInst &amp;Inst, unsigned RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad11cd25d1252f3b19279e5922056531f">DecodeGeneralDoubleLow8RegsRegisterClass</a> (MCInst &amp;Inst, unsigned RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa72a8b8f32160c51a85853a7572592db">DecodeHvxWRRegisterClass</a> (MCInst &amp;Inst, unsigned RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33a88c166cc22423508784bc70c61c74">DecodeHvxVQRRegisterClass</a> (MCInst &amp;Inst, unsigned RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25a73d332f10cc18335da0d15a1cb8fa">DecodePredRegsRegisterClass</a> (MCInst &amp;Inst, unsigned RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5d3ffe2bb6262c59e3f71ef3a6070ed">DecodeHvxQRRegisterClass</a> (MCInst &amp;Inst, unsigned RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eafaabd2bbbb4eb856e553cdca85b99">DecodeCtrRegsRegisterClass</a> (MCInst &amp;Inst, unsigned RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153a3a25ff23af1db43174d338d2156f">DecodeGuestRegsRegisterClass</a> (MCInst &amp;Inst, unsigned RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a825fce70e335e0e3182dbfe04d328e66">DecodeSysRegsRegisterClass</a> (MCInst &amp;Inst, unsigned RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5920b44a0571dd783dc3257b3d06ec23">DecodeModRegsRegisterClass</a> (MCInst &amp;Inst, unsigned RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0a51db33ad8d7fcaf127661514016fb">DecodeCtrRegs64RegisterClass</a> (MCInst &amp;Inst, unsigned RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4fc6b486b45a0f90f1264af35348e56">DecodeGuestRegs64RegisterClass</a> (MCInst &amp;Inst, unsigned RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a581de7d5eb00d0a9a3a4783a68b06604">DecodeSysRegs64RegisterClass</a> (MCInst &amp;Inst, unsigned RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42a94b0bc3b45d5b82f8cf8d26dc8449">unsignedImmDecoder</a> (MCInst &amp;MI, unsigned tmp, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a753b4c73b07ef8f90dcada88f6ef4d">s32_0ImmDecoder</a> (MCInst &amp;MI, unsigned tmp, uint64_t, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20a8e4705041b6319c008c1e981eee45">brtargetDecoder</a> (MCInst &amp;MI, unsigned tmp, uint64_t Address, const MCDisassembler *Decoder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a9f9bc1fdf428c5e7544a0424a8cc8f">createHexagonDisassembler</a> (const Target &amp;T, const MCSubtargetInfo &amp;STI, MCContext &amp;Ctx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a7be637e77772d13f3cb8976fd40e26">LLVMInitializeHexagonDisassembler</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f793a0798fab60a5fd44654d33dbf21">adjustDuplex</a> (MCInst &amp;MI, MCContext &amp;Context)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8199e9ace5520235a9e3717a7cb5992e">DecodeRegisterClass</a> (MCInst &amp;Inst, unsigned RegNo, ArrayRef&lt; MCPhysReg &gt; Table)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a5462b5685cd80c97a88bd8d316003b">SysRegDecoderTable</a>[] = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cfae706910d385f4a522147251e3069">SysReg64DecoderTable</a>[] = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"hexagon-disassembler"</td>
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

### adjustDuplex() {#a6f793a0798fab60a5fd44654d33dbf21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjustDuplex (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context)</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>.</p>

</div>
</div>

### brtargetDecoder() {#a20a8e4705041b6319c008c1e981eee45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus brtargetDecoder (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned tmp, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 764 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a10e72ca32e8206bcc1a9ec642a797e44">llvm::HexagonMCInstrInfo::addConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagondisassembler-cpp-/#a286150b949c366f38d99bcf292053cf0">anonymous{HexagonDisassembler.cpp}::disassembler</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagondisassembler-cpp-/#a2e0e4ab18e7fb56c7dbd46fe864243e6">anonymous{HexagonDisassembler.cpp}::fullValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a38a8fc225b496e9ed8b4856441e08bba">llvm::HexagonMCInstrInfo::getExtentBits</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#a247d0faf64fb68b3e5ebc203adc6223f">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::HexagonDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### createHexagonDisassembler() {#a4a9f9bc1fdf428c5e7544a0424a8cc8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDisassembler * createHexagonDisassembler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#a247d0faf64fb68b3e5ebc203adc6223f">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::HexagonDisassembler</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a2a7be637e77772d13f3cb8976fd40e26">LLVMInitializeHexagonDisassembler</a>.</p>

</div>
</div>

### DecodeCtrRegs64RegisterClass() {#ad0a51db33ad8d7fcaf127661514016fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeCtrRegs64RegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 698 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### DecodeCtrRegsRegisterClass() {#a1eafaabd2bbbb4eb856e553cdca85b99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeCtrRegsRegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 669 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab8aff98d3587ddb15f9e46ed88687f0f">llvm::M0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a58328e0582aabaf012bf9bc6f36c9e04">llvm::M1</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### DecodeDoubleRegsRegisterClass() {#a8bf4202898855e8ca8faf99fe3699de5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeDoubleRegsRegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>Reference <a href="#a8199e9ace5520235a9e3717a7cb5992e">DecodeRegisterClass</a>.</p>

</div>
</div>

### DecodeGeneralDoubleLow8RegsRegisterClass() {#ad11cd25d1252f3b19279e5922056531f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeGeneralDoubleLow8RegsRegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>Reference <a href="#a8199e9ace5520235a9e3717a7cb5992e">DecodeRegisterClass</a>.</p>

</div>
</div>

### DecodeGeneralSubRegsRegisterClass() {#aa2a9bc273f95cc3abf60d457d766b1da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeGeneralSubRegsRegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a> and <a href="#a8199e9ace5520235a9e3717a7cb5992e">DecodeRegisterClass</a>.</p>

</div>
</div>

### DecodeGuestRegs64RegisterClass() {#ad4fc6b486b45a0f90f1264af35348e56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeGuestRegs64RegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 878 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### DecodeGuestRegsRegisterClass() {#a153a3a25ff23af1db43174d338d2156f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeGuestRegsRegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 852 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### DecodeHvxQRRegisterClass() {#ac5d3ffe2bb6262c59e3f71ef3a6070ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeHvxQRRegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>Reference <a href="#a8199e9ace5520235a9e3717a7cb5992e">DecodeRegisterClass</a>.</p>

</div>
</div>

### DecodeHvxVQRRegisterClass() {#a33a88c166cc22423508784bc70c61c74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_UNUSED DecodeStatus DecodeHvxVQRRegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>Reference <a href="#a8199e9ace5520235a9e3717a7cb5992e">DecodeRegisterClass</a>.</p>

</div>
</div>

### DecodeHvxVRRegisterClass() {#a47853acb4dae5246097b634690d019a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeHvxVRRegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="#a8199e9ace5520235a9e3717a7cb5992e">DecodeRegisterClass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a8cff5423006469332e8ae5e3a8c8559c">llvm::Hexagon::V5</a>.</p>

</div>
</div>

### DecodeHvxWRRegisterClass() {#aa72a8b8f32160c51a85853a7572592db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeHvxWRRegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>Reference <a href="#a8199e9ace5520235a9e3717a7cb5992e">DecodeRegisterClass</a>.</p>

</div>
</div>

### DecodeIntRegsLow8RegisterClass() {#a0c2459e050125014180f42d4ace0ed5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeIntRegsLow8RegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a> and <a href="#ab7c8b2ad6feda021ec9b6390f7c2ee26">DecodeIntRegsRegisterClass</a>.</p>

</div>
</div>

### DecodeIntRegsRegisterClass() {#ab7c8b2ad6feda021ec9b6390f7c2ee26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeIntRegsRegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="#a8199e9ace5520235a9e3717a7cb5992e">DecodeRegisterClass</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#a6aa2ad6e54832e162aafc6785a44c4b8">IntRegDecoderTable</a>.</p>


<p>Referenced by <a href="#a0c2459e050125014180f42d4ace0ed5f">DecodeIntRegsLow8RegisterClass</a>.</p>

</div>
</div>

### DecodeModRegsRegisterClass() {#a5920b44a0571dd783dc3257b3d06ec23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeModRegsRegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### DecodePredRegsRegisterClass() {#a25a73d332f10cc18335da0d15a1cb8fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodePredRegsRegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>Reference <a href="#a8199e9ace5520235a9e3717a7cb5992e">DecodeRegisterClass</a>.</p>

</div>
</div>

### DecodeRegisterClass() {#a8199e9ace5520235a9e3717a7cb5992e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeRegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt; Table)</td>
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



<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>


<p>Referenced by <a href="#a8bf4202898855e8ca8faf99fe3699de5">DecodeDoubleRegsRegisterClass</a>, <a href="#ad11cd25d1252f3b19279e5922056531f">DecodeGeneralDoubleLow8RegsRegisterClass</a>, <a href="#aa2a9bc273f95cc3abf60d457d766b1da">DecodeGeneralSubRegsRegisterClass</a>, <a href="#ac5d3ffe2bb6262c59e3f71ef3a6070ed">DecodeHvxQRRegisterClass</a>, <a href="#a33a88c166cc22423508784bc70c61c74">DecodeHvxVQRRegisterClass</a>, <a href="#a47853acb4dae5246097b634690d019a4">DecodeHvxVRRegisterClass</a>, <a href="#aa72a8b8f32160c51a85853a7572592db">DecodeHvxWRRegisterClass</a>, <a href="#ab7c8b2ad6feda021ec9b6390f7c2ee26">DecodeIntRegsRegisterClass</a> and <a href="#a25a73d332f10cc18335da0d15a1cb8fa">DecodePredRegsRegisterClass</a>.</p>

</div>
</div>

### DecodeSysRegs64RegisterClass() {#a581de7d5eb00d0a9a3a4783a68b06604}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeSysRegs64RegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 837 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a> and <a href="#a5cfae706910d385f4a522147251e3069">SysReg64DecoderTable</a>.</p>

</div>
</div>

### DecodeSysRegsRegisterClass() {#a825fce70e335e0e3182dbfe04d328e66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeSysRegsRegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a> and <a href="#a9a5462b5685cd80c97a88bd8d316003b">SysRegDecoderTable</a>.</p>

</div>
</div>

### LLVMInitializeHexagonDisassembler() {#a2a7be637e77772d13f3cb8976fd40e26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_EXTERNAL_VISIBILITY void LLVMInitializeHexagonDisassembler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="#a4a9f9bc1fdf428c5e7544a0424a8cc8f">createHexagonDisassembler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57f539ab05ad50c345d4d4975d0ffd6f">llvm::getTheHexagonTarget</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a> and <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a8d3c3e977776517a7c1a82060b16da9f">llvm::TargetRegistry::RegisterMCDisassembler</a>.</p>

</div>
</div>

### s32\_0ImmDecoder() {#a2a753b4c73b07ef8f90dcada88f6ef4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus s32_0ImmDecoder (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned tmp, uint64_t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-hexagondisassembler-cpp-/#a286150b949c366f38d99bcf292053cf0">anonymous{HexagonDisassembler.cpp}::disassembler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a38a8fc225b496e9ed8b4856441e08bba">llvm::HexagonMCInstrInfo::getExtentBits</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#a247d0faf64fb68b3e5ebc203adc6223f">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::HexagonDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagondisassembler-cpp-/#a924259105b9cc65caf1525588ae6ca8c">anonymous{HexagonDisassembler.cpp}::signedDecoder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### unsignedImmDecoder() {#a42a94b0bc3b45d5b82f8cf8d26dc8449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus unsignedImmDecoder (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned tmp, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 743 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a10e72ca32e8206bcc1a9ec642a797e44">llvm::HexagonMCInstrInfo::addConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagondisassembler-cpp-/#a286150b949c366f38d99bcf292053cf0">anonymous{HexagonDisassembler.cpp}::disassembler</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagondisassembler-cpp-/#a2e0e4ab18e7fb56c7dbd46fe864243e6">anonymous{HexagonDisassembler.cpp}::fullValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#a247d0faf64fb68b3e5ebc203adc6223f">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::HexagonDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### SysReg64DecoderTable {#a5cfae706910d385f4a522147251e3069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint16_t SysReg64DecoderTable[]</td>
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
    Hexagon::SGP1_0, Hexagon::S3_2,   Hexagon::S5_4,   Hexagon::S7_6,
    Hexagon::S9_8,   Hexagon::S11_10, Hexagon::S13_12, Hexagon::S15_14,
    Hexagon::S17_16, Hexagon::S19_18, Hexagon::S21_20, Hexagon::S23_22,
    Hexagon::S25_24, Hexagon::S27_26, Hexagon::S29_28, Hexagon::S31_30,
    Hexagon::S33_32, Hexagon::S35_34, Hexagon::S37_36, Hexagon::S39_38,
    Hexagon::S41_40, Hexagon::S43_42, Hexagon::S45_44, Hexagon::S47_46,
    Hexagon::S49_48, Hexagon::S51_50, Hexagon::S53_52, Hexagon::S55_54,
    Hexagon::S57_56, Hexagon::S59_58, Hexagon::S61_60, Hexagon::S63_62,
    Hexagon::S65_64, Hexagon::S67_66, Hexagon::S69_68, Hexagon::S71_70,
    Hexagon::S73_72, Hexagon::S75_74, Hexagon::S77_76, Hexagon::S79_78,
}
</div>
</dd>
</dl>

<p>Definition at line 823 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>Referenced by <a href="#a581de7d5eb00d0a9a3a4783a68b06604">DecodeSysRegs64RegisterClass</a>.</p>

</div>
</div>

### SysRegDecoderTable {#a9a5462b5685cd80c97a88bd8d316003b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint16_t SysRegDecoderTable[]</td>
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
    Hexagon::SGP0,       Hexagon::SGP1,      Hexagon::STID,
    Hexagon::ELR,        Hexagon::BADVA0,    Hexagon::BADVA1,
    Hexagon::SSR,        Hexagon::CCR,       Hexagon::HTID,
    Hexagon::BADVA,      Hexagon::IMASK,     Hexagon::S11,
    Hexagon::S12,        Hexagon::S13,       Hexagon::S14,
    Hexagon::S15,        Hexagon::EVB,       Hexagon::MODECTL,
    Hexagon::SYSCFG,     Hexagon::S19,       Hexagon::S20,
    Hexagon::VID,        Hexagon::S22,       Hexagon::S23,
    Hexagon::S24,        Hexagon::S25,       Hexagon::S26,
    Hexagon::CFGBASE,    Hexagon::DIAG,      Hexagon::REV,
    Hexagon::PCYCLELO,   Hexagon::PCYCLEHI,  Hexagon::ISDBST,
    Hexagon::ISDBCFG0,   Hexagon::ISDBCFG1,  Hexagon::S35,
    Hexagon::BRKPTPC0,   Hexagon::BRKPTCFG0, Hexagon::BRKPTPC1,
    Hexagon::BRKPTCFG1,  Hexagon::ISDBMBXIN, Hexagon::ISDBMBXOUT,
    Hexagon::ISDBEN,     Hexagon::ISDBGPR,   Hexagon::S44,
    Hexagon::S45,        Hexagon::S46,       Hexagon::S47,
    Hexagon::PMUCNT0,    Hexagon::PMUCNT1,   Hexagon::PMUCNT2,
    Hexagon::PMUCNT3,    Hexagon::PMUEVTCFG, Hexagon::PMUCFG,
    Hexagon::S54,        Hexagon::S55,       Hexagon::S56,
    Hexagon::S57,        Hexagon::S58,       Hexagon::S59,
    Hexagon::S60,        Hexagon::S61,       Hexagon::S62,
    Hexagon::S63,        <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a2b96ee4926f7c19420d19ecaf7adc1a8">Hexagon::S64</a>,       Hexagon::S65,
    Hexagon::S66,        Hexagon::S67,       Hexagon::S68,
    Hexagon::S69,        Hexagon::S70,       Hexagon::S71,
    Hexagon::S72,        Hexagon::S73,       Hexagon::S74,
    Hexagon::S75,        Hexagon::S76,       Hexagon::S77,
    Hexagon::S78,        Hexagon::S79,       Hexagon::S80,
}
</div>
</dd>
</dl>

<p>Definition at line 779 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>Referenced by <a href="#a825fce70e335e0e3182dbfe04d328e66">DecodeSysRegsRegisterClass</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"hexagon-disassembler"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
