---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/mc/mcwin64eh-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MCWin64EH.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwin64eh-h">llvm/MC/MCWin64EH.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectstreamer-h">llvm/MC/MCObjectStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">llvm/MC/MCSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">llvm/Support/Win64EH.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebb910ab6fa280018caf8bb78fcb91da">CountOfUnwindCodes</a> (std::vector&lt; WinEH::Instruction &gt; &amp;Insns)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab68ca7cc744c7d305f655930067e0a64">EmitAbsDifference</a> (MCStreamer &amp;Streamer, const MCSymbol *LHS, const MCSymbol *RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6144ace1bbb2a8b3fe310225914ee101">EmitUnwindCode</a> (MCStreamer &amp;streamer, const MCSymbol *begin, WinEH::Instruction &amp;inst)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70e3e2288f783c384791e314b8e20231">EmitSymbolRefWithOfs</a> (MCStreamer &amp;streamer, const MCSymbol *Base, int64_t Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9387871e1bade9ef3f96c2469ec92fe0">EmitSymbolRefWithOfs</a> (MCStreamer &amp;streamer, const MCSymbol *Base, const MCSymbol *Other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa186dddb4125136ff27007f97e26759a">EmitRuntimeFunction</a> (MCStreamer &amp;streamer, const WinEH::FrameInfo *info)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d75ea3f9831315ebdb816d70c58c30b">EmitUnwindInfo</a> (MCStreamer &amp;streamer, WinEH::FrameInfo *info)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaab77f3694a5bc3b29ffbc6ce87444ad">GetSubDivExpr</a> (MCStreamer &amp;Streamer, const MCSymbol *LHS, const MCSymbol *RHS, int Div)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa18d22b8d07f4376fcf7c00d5923422a">GetOptionalAbsDifference</a> (MCStreamer &amp;Streamer, const MCSymbol *LHS, const MCSymbol *RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78a76e3a4c69c3a2e321d1656155e9d9">GetAbsDifference</a> (MCStreamer &amp;Streamer, const MCSymbol *LHS, const MCSymbol *RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa32035802671dce51123a77b96594506">checkARM64Instructions</a> (MCStreamer &amp;Streamer, ArrayRef&lt; WinEH::Instruction &gt; Insns, const MCSymbol *Begin, const MCSymbol *End, StringRef Name, StringRef Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11eba4a181a5af5d65d14e020ae8ed1b">ARM64CountOfUnwindCodes</a> (ArrayRef&lt; WinEH::Instruction &gt; Insns)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a204614db7296af6e2492c48c3a8ffd03">ARM64EmitUnwindCode</a> (MCStreamer &amp;streamer, const WinEH::Instruction &amp;inst)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e599e8d393ec15804b6efbc478393a3">FindMatchingEpilog</a> (const std::vector&lt; WinEH::Instruction &gt; &amp;EpilogInstrs, const std::vector&lt; MCSymbol * &gt; &amp;Epilogs, const WinEH::FrameInfo *info)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27995b830d3e9bcf7a442eb12dee802f">simplifyARM64Opcodes</a> (std::vector&lt; WinEH::Instruction &gt; &amp;Instructions, bool Reverse)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c46170fb77eea7b7bec6513b4a084aa">getARM64OffsetInProlog</a> (const std::vector&lt; WinEH::Instruction &gt; &amp;Prolog, const std::vector&lt; WinEH::Instruction &gt; &amp;Epilog)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01564c0b334eed6d8b36993f0ef70b73">checkARM64PackedEpilog</a> (MCStreamer &amp;streamer, WinEH::FrameInfo *info, WinEH::FrameInfo::Segment *Seg, int PrologCodeBytes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c6c18ec71fabe4422710878b3d9c128">tryARM64PackedUnwind</a> (WinEH::FrameInfo *info, uint32_t FuncLength, int PackedEpilogOffset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaf1a735e35b87dee5107e5ccd874783">ARM64ProcessEpilogs</a> (WinEH::FrameInfo *info, WinEH::FrameInfo::Segment *Seg, uint32_t &amp;TotalCodeBytes, MapVector&lt; MCSymbol *, uint32_t &gt; &amp;EpilogInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83e6ea9ad14301bc03c55827f0689dc0">ARM64FindSegmentsInFunction</a> (MCStreamer &amp;streamer, WinEH::FrameInfo *info, int64_t RawFuncLength)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bd3fbe76161d42d7470f0dd7dd634de">ARM64EmitUnwindInfoForSegment</a> (MCStreamer &amp;streamer, WinEH::FrameInfo *info, WinEH::FrameInfo::Segment &amp;Seg, bool TryPacked=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6574f704d2fbd168f81e7552695170a8">ARM64EmitUnwindInfo</a> (MCStreamer &amp;streamer, WinEH::FrameInfo *info, bool TryPacked=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d7a8cae2277a3c682e59c1a7e7a1b8d">ARMCountOfUnwindCodes</a> (ArrayRef&lt; WinEH::Instruction &gt; Insns)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac14ca7f5bcd20cfe1c461a7b4a353764">ARMCountOfInstructionBytes</a> (ArrayRef&lt; WinEH::Instruction &gt; Insns, bool *HasCustom=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a64f841fb788b307e31f8a70e6c022a">checkARMInstructions</a> (MCStreamer &amp;Streamer, ArrayRef&lt; WinEH::Instruction &gt; Insns, const MCSymbol *Begin, const MCSymbol *End, StringRef Name, StringRef Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aaf032ee5c9603b8ae7c8da314f3013">isARMTerminator</a> (const WinEH::Instruction &amp;inst)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27cc5388854780051ed416ab2901e18e">ARMEmitUnwindCode</a> (MCStreamer &amp;streamer, const WinEH::Instruction &amp;inst)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66312fe172a047e8e8e25781786ada0b">getARMOffsetInProlog</a> (const std::vector&lt; WinEH::Instruction &gt; &amp;Prolog, const std::vector&lt; WinEH::Instruction &gt; &amp;Epilog, bool CanTweakProlog)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73622e67d89cdc5f662981287e16879f">checkARMPackedEpilog</a> (MCStreamer &amp;streamer, WinEH::FrameInfo *info, int PrologCodeBytes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7274589f20fb34bb658dbffebb1426c4">parseRegMask</a> (unsigned Mask, bool &amp;HasLR, bool &amp;HasR11, unsigned &amp;Folded, int &amp;IntRegs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a982dd5c343c1b1e191b5cc1d00fefaf6">tryARMPackedUnwind</a> (MCStreamer &amp;streamer, WinEH::FrameInfo *info, uint32_t FuncLength)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a> (MCStreamer &amp;streamer, WinEH::FrameInfo *info, bool TryPacked=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66a4df49046ec16dd9c64d36ba3cb62c">ARM64EmitRuntimeFunction</a> (MCStreamer &amp;streamer, const WinEH::FrameInfo *info)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48d2597504af337577491cde138a142b">ARMEmitRuntimeFunction</a> (MCStreamer &amp;streamer, const WinEH::FrameInfo *info)</td>
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

### ARM64CountOfUnwindCodes() {#a11eba4a181a5af5d65d14e020ae8ed1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t ARM64CountOfUnwindCodes (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a> &gt; Insns)</td>
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



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea5bf832be598907276533805261b14c94">llvm::Win64EH::UOP_AddFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea696f26056e05c65dd7c1bb6da6bb6c94">llvm::Win64EH::UOP_AllocLarge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eae2ba520dfe4a97772ebb8e010f14b90e">llvm::Win64EH::UOP_AllocMedium</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea852e7cdf29ed57cc4c6fe34fbe236166">llvm::Win64EH::UOP_AllocSmall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea1d63b21ce3a3530dc0992c9545532657">llvm::Win64EH::UOP_ClearUnwoundToCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaf3c84a367e177cb35173b55701e59b62">llvm::Win64EH::UOP_Context</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eacaef82dc45b07cc681ade2a07b365961">llvm::Win64EH::UOP_ECContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea87d69becc531e1d468e00f36b1d0c5dd">llvm::Win64EH::UOP_End</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea370cb5b95f05480a329dbc936969d5d7">llvm::Win64EH::UOP_Nop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabfe110fe2ab3ff5ef9141ceeb2fd0c7d">llvm::Win64EH::UOP_PACSignLR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabb99442c04b0287262dcb4395886bd7e">llvm::Win64EH::UOP_PushMachFrame</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea3ecd6abb34b66d0cea4a285a43ca62eb">llvm::Win64EH::UOP_SaveAnyRegD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaa32738827eafd247a5db8ccacf84ea84">llvm::Win64EH::UOP_SaveAnyRegDP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea143dd0f1157957f6d74230edfbdace28">llvm::Win64EH::UOP_SaveAnyRegDPX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea30be100959f86a48264856eb0130185e">llvm::Win64EH::UOP_SaveAnyRegDX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eafd194f2c1971298fa3ed259340dc7af0">llvm::Win64EH::UOP_SaveAnyRegI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eae8425317799d828362a3615b816ec496">llvm::Win64EH::UOP_SaveAnyRegIP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea54d0faec96686043b538bac78fe185d6">llvm::Win64EH::UOP_SaveAnyRegIPX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea7d52165a373988e5acd605fd09b65638">llvm::Win64EH::UOP_SaveAnyRegIX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea9fdabb65c8f4afc6d98b0997df0f4bc1">llvm::Win64EH::UOP_SaveAnyRegQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea3a9d85a19d84843f629750bfa002ab9b">llvm::Win64EH::UOP_SaveAnyRegQP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabda3f39fe0a0b595e2a21968c3cd83d4">llvm::Win64EH::UOP_SaveAnyRegQPX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea62df2c37135f5fa1bad0434bede59e70">llvm::Win64EH::UOP_SaveAnyRegQX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea40d470d658f8310637362abe42236e5a">llvm::Win64EH::UOP_SaveFPLR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea1c1e91f085207677f6a87f72211a8e7d">llvm::Win64EH::UOP_SaveFPLRX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea0ff61e9c16bb520f1195c5892ff628ec">llvm::Win64EH::UOP_SaveFReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea080b3b9cd2397e7ce59bfbd8d50220da">llvm::Win64EH::UOP_SaveFRegP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea17274b8b2b523abe03e911ad420586bf">llvm::Win64EH::UOP_SaveFRegPX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaf3b908c7dcda8acf3116614dc1874bd8">llvm::Win64EH::UOP_SaveFRegX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea77b13b268267acfad2a633a4207d695b">llvm::Win64EH::UOP_SaveLRPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaa0e067e95931107f1361a0853805202b">llvm::Win64EH::UOP_SaveNext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabcce408cff8a8caddd672fcf9d5f7c4d">llvm::Win64EH::UOP_SaveR19R20X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabd688d6bb3a01916b39bbf1d073ec4c1">llvm::Win64EH::UOP_SaveReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea8c6bd0c4141baac292a758ad1e4ed2d2">llvm::Win64EH::UOP_SaveRegP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea9f7d600586e92963f5881e13cb4886ce">llvm::Win64EH::UOP_SaveRegPX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea6177f784f0f7ad77aeda554a1bec7bc6">llvm::Win64EH::UOP_SaveRegX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea643ab7c0e9d1180026aeb5526d64afa9">llvm::Win64EH::UOP_SetFP</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eae869ae7d5bcd450c29ee40c32c15f971">llvm::Win64EH::UOP_TrapFrame</a>.</p>


<p>Referenced by <a href="#a6574f704d2fbd168f81e7552695170a8">ARM64EmitUnwindInfo</a>, <a href="#adaf1a735e35b87dee5107e5ccd874783">ARM64ProcessEpilogs</a>, <a href="#a01564c0b334eed6d8b36993f0ef70b73">checkARM64PackedEpilog</a> and <a href="#a3c46170fb77eea7b7bec6513b4a084aa">getARM64OffsetInProlog</a>.</p>

</div>
</div>

### ARM64EmitRuntimeFunction() {#a66a4df49046ec16dd9c64d36ba3cb62c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARM64EmitRuntimeFunction (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> * info)</td>
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



<p>Definition at line 2508 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc3817979bc871dba942b87773da1cc0">llvm::MCStreamer::emitInt32</a>, <a href="#a70e3e2288f783c384791e314b8e20231">EmitSymbolRefWithOfs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9488c32df3cb8819f6a07f8c88d72c66">llvm::MCStreamer::emitValueToAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a61907d1fede3c9e9713b6b3a29d35b01">llvm::MCSymbolRefExpr::VK_COFF_IMGREL32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/win64eh/arm64unwindemitter/#af344ffc71b7b9b6972bda73c603051a8">llvm::Win64EH::ARM64UnwindEmitter::Emit</a>.</p>

</div>
</div>

### ARM64EmitUnwindCode() {#a204614db7296af6e2492c48c3a8ffd03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARM64EmitUnwindCode (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a> &amp; inst)</td>
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



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af47540299db471532b82aba9314f1fc2">llvm::MCStreamer::emitInt8</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a86c704049f53c1ee871373dadce8aad5">llvm::WinEH::Instruction::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a35cb7e6f64b7406816d5bc30cfc5d27a">llvm::WinEH::Instruction::Operation</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a66c52d83c6dfd34d01144ab46d54efa6">llvm::WinEH::Instruction::Register</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea5bf832be598907276533805261b14c94">llvm::Win64EH::UOP_AddFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea696f26056e05c65dd7c1bb6da6bb6c94">llvm::Win64EH::UOP_AllocLarge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eae2ba520dfe4a97772ebb8e010f14b90e">llvm::Win64EH::UOP_AllocMedium</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea852e7cdf29ed57cc4c6fe34fbe236166">llvm::Win64EH::UOP_AllocSmall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea1d63b21ce3a3530dc0992c9545532657">llvm::Win64EH::UOP_ClearUnwoundToCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaf3c84a367e177cb35173b55701e59b62">llvm::Win64EH::UOP_Context</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eacaef82dc45b07cc681ade2a07b365961">llvm::Win64EH::UOP_ECContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea87d69becc531e1d468e00f36b1d0c5dd">llvm::Win64EH::UOP_End</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea370cb5b95f05480a329dbc936969d5d7">llvm::Win64EH::UOP_Nop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabfe110fe2ab3ff5ef9141ceeb2fd0c7d">llvm::Win64EH::UOP_PACSignLR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabb99442c04b0287262dcb4395886bd7e">llvm::Win64EH::UOP_PushMachFrame</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea3ecd6abb34b66d0cea4a285a43ca62eb">llvm::Win64EH::UOP_SaveAnyRegD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaa32738827eafd247a5db8ccacf84ea84">llvm::Win64EH::UOP_SaveAnyRegDP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea143dd0f1157957f6d74230edfbdace28">llvm::Win64EH::UOP_SaveAnyRegDPX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea30be100959f86a48264856eb0130185e">llvm::Win64EH::UOP_SaveAnyRegDX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eafd194f2c1971298fa3ed259340dc7af0">llvm::Win64EH::UOP_SaveAnyRegI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eae8425317799d828362a3615b816ec496">llvm::Win64EH::UOP_SaveAnyRegIP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea54d0faec96686043b538bac78fe185d6">llvm::Win64EH::UOP_SaveAnyRegIPX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea7d52165a373988e5acd605fd09b65638">llvm::Win64EH::UOP_SaveAnyRegIX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea9fdabb65c8f4afc6d98b0997df0f4bc1">llvm::Win64EH::UOP_SaveAnyRegQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea3a9d85a19d84843f629750bfa002ab9b">llvm::Win64EH::UOP_SaveAnyRegQP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabda3f39fe0a0b595e2a21968c3cd83d4">llvm::Win64EH::UOP_SaveAnyRegQPX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea62df2c37135f5fa1bad0434bede59e70">llvm::Win64EH::UOP_SaveAnyRegQX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea40d470d658f8310637362abe42236e5a">llvm::Win64EH::UOP_SaveFPLR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea1c1e91f085207677f6a87f72211a8e7d">llvm::Win64EH::UOP_SaveFPLRX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea0ff61e9c16bb520f1195c5892ff628ec">llvm::Win64EH::UOP_SaveFReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea080b3b9cd2397e7ce59bfbd8d50220da">llvm::Win64EH::UOP_SaveFRegP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea17274b8b2b523abe03e911ad420586bf">llvm::Win64EH::UOP_SaveFRegPX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaf3b908c7dcda8acf3116614dc1874bd8">llvm::Win64EH::UOP_SaveFRegX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea77b13b268267acfad2a633a4207d695b">llvm::Win64EH::UOP_SaveLRPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaa0e067e95931107f1361a0853805202b">llvm::Win64EH::UOP_SaveNext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabcce408cff8a8caddd672fcf9d5f7c4d">llvm::Win64EH::UOP_SaveR19R20X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabd688d6bb3a01916b39bbf1d073ec4c1">llvm::Win64EH::UOP_SaveReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea8c6bd0c4141baac292a758ad1e4ed2d2">llvm::Win64EH::UOP_SaveRegP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea9f7d600586e92963f5881e13cb4886ce">llvm::Win64EH::UOP_SaveRegPX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea6177f784f0f7ad77aeda554a1bec7bc6">llvm::Win64EH::UOP_SaveRegX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea643ab7c0e9d1180026aeb5526d64afa9">llvm::Win64EH::UOP_SetFP</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eae869ae7d5bcd450c29ee40c32c15f971">llvm::Win64EH::UOP_TrapFrame</a>.</p>


<p>Referenced by <a href="#a0bd3fbe76161d42d7470f0dd7dd634de">ARM64EmitUnwindInfoForSegment</a>.</p>

</div>
</div>

### ARM64EmitUnwindInfo() {#a6574f704d2fbd168f81e7552695170a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARM64EmitUnwindInfo (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> * info, bool TryPacked=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 1353 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="#a11eba4a181a5af5d65d14e020ae8ed1b">ARM64CountOfUnwindCodes</a>, <a href="#a0bd3fbe76161d42d7470f0dd7dd634de">ARM64EmitUnwindInfoForSegment</a>, <a href="#a83e6ea9ad14301bc03c55827f0689dc0">ARM64FindSegmentsInFunction</a>, <a href="#a78a76e3a4c69c3a2e321d1656155e9d9">GetAbsDifference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a> and <a href="#a27995b830d3e9bcf7a442eb12dee802f">simplifyARM64Opcodes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/win64eh/arm64unwindemitter/#af344ffc71b7b9b6972bda73c603051a8">llvm::Win64EH::ARM64UnwindEmitter::Emit</a> and <a href="/web-llvm/docs/api/classes/llvm/win64eh/arm64unwindemitter/#a23e988e2f737319fba0ad0f50b4791c3">llvm::Win64EH::ARM64UnwindEmitter::EmitUnwindInfo</a>.</p>

</div>
</div>

### ARM64EmitUnwindInfoForSegment() {#a0bd3fbe76161d42d7470f0dd7dd634de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARM64EmitUnwindInfoForSegment (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> * info, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/segment">WinEH::FrameInfo::Segment</a> &amp; Seg, bool TryPacked=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 1206 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="#a204614db7296af6e2492c48c3a8ffd03">ARM64EmitUnwindCode</a>, <a href="#adaf1a735e35b87dee5107e5ccd874783">ARM64ProcessEpilogs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a01564c0b334eed6d8b36993f0ef70b73">checkARM64PackedEpilog</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a299bf2f0329389424760f4a7c8af75ac">llvm::MCContext::createTempSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc3817979bc871dba942b87773da1cc0">llvm::MCStreamer::emitInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af47540299db471532b82aba9314f1fc2">llvm::MCStreamer::emitInt8</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a822ae1a4f19b7b00a297a100749f9b8a">llvm::MCStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9488c32df3cb8819f6a07f8c88d72c66">llvm::MCStreamer::emitValueToAlignment</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/segment/#aca4a957f9b71fbcb8e652df7b214c98a">llvm::WinEH::FrameInfo::Segment::Epilogs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/segment/#ae78e3a46142b178ceb9881abe75b03ae">llvm::WinEH::FrameInfo::Segment::HasProlog</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/segment/#af20720f31964dc84b5cd8990585fff66">llvm::WinEH::FrameInfo::Segment::Length</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/segment/#aee85c8341f37756e35d371088a955391">llvm::WinEH::FrameInfo::Segment::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/segment/#a85c2bc034ab3a145abeb46e81f655a31">llvm::WinEH::FrameInfo::Segment::Symbol</a>, <a href="#a5c6c18ec71fabe4422710878b3d9c128">tryARM64PackedUnwind</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a61907d1fede3c9e9713b6b3a29d35b01">llvm::MCSymbolRefExpr::VK_COFF_IMGREL32</a>.</p>


<p>Referenced by <a href="#a6574f704d2fbd168f81e7552695170a8">ARM64EmitUnwindInfo</a>.</p>

</div>
</div>

### ARM64FindSegmentsInFunction() {#a83e6ea9ad14301bc03c55827f0689dc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARM64FindSegmentsInFunction (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> * info, int64_t RawFuncLength)</td>
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



<p>Definition at line 1125 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="#aa32035802671dce51123a77b96594506">checkARM64Instructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a78a76e3a4c69c3a2e321d1656155e9d9">GetAbsDifference</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a6574f704d2fbd168f81e7552695170a8">ARM64EmitUnwindInfo</a>.</p>

</div>
</div>

### ARM64ProcessEpilogs() {#adaf1a735e35b87dee5107e5ccd874783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARM64ProcessEpilogs (<a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> * info, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/segment">WinEH::FrameInfo::Segment</a> * Seg, uint32_t &amp; TotalCodeBytes, <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, uint32_t &gt; &amp; EpilogInfo)</td>
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



<p>Definition at line 1081 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="#a11eba4a181a5af5d65d14e020ae8ed1b">ARM64CountOfUnwindCodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#ae091b147039557cf8ce505740e7ff7ac">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a8757ce7071547a0410c82cc096b1ec9a">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::contains</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/segment/#aca4a957f9b71fbcb8e652df7b214c98a">llvm::WinEH::FrameInfo::Segment::Epilogs</a>, <a href="#a9e599e8d393ec15804b6efbc478393a3">FindMatchingEpilog</a>, <a href="#a3c46170fb77eea7b7bec6513b4a084aa">getARM64OffsetInProlog</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/segment/#ae78e3a46142b178ceb9881abe75b03ae">llvm::WinEH::FrameInfo::Segment::HasProlog</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a> and <a href="/web-llvm/docs/api/classes/llvm/mapvector/#abca23bddf517f69d28c6d30c58a7b6f9">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::lookup</a>.</p>


<p>Referenced by <a href="#a0bd3fbe76161d42d7470f0dd7dd634de">ARM64EmitUnwindInfoForSegment</a>.</p>

</div>
</div>

### ARMCountOfInstructionBytes() {#ac14ca7f5bcd20cfe1c461a7b4a353764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t ARMCountOfInstructionBytes (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a> &gt; Insns, bool * HasCustom=nullptr)</td>
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



<p>Definition at line 1502 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea3380a84eb648ca0ee05c138bb4e59c48">llvm::Win64EH::UOP_AllocHuge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea696f26056e05c65dd7c1bb6da6bb6c94">llvm::Win64EH::UOP_AllocLarge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea852e7cdf29ed57cc4c6fe34fbe236166">llvm::Win64EH::UOP_AllocSmall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea459472d4a0e3cd23f8448702e0f84325">llvm::Win64EH::UOP_Custom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea87d69becc531e1d468e00f36b1d0c5dd">llvm::Win64EH::UOP_End</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea2c1e73f96a3eb49c02ea5e2c23582c60">llvm::Win64EH::UOP_EndNop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea370cb5b95f05480a329dbc936969d5d7">llvm::Win64EH::UOP_Nop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea35a232904dcd802033ea03851f7838b2">llvm::Win64EH::UOP_SaveFRegD0D15</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaf6e5478d3596267b0b6340a415e93f45">llvm::Win64EH::UOP_SaveFRegD16D31</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eab3bc8467e0977cc0f9426032256c5540">llvm::Win64EH::UOP_SaveFRegD8D15</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabe9ce7cc4dc6542d11f840cc8e51a6f6">llvm::Win64EH::UOP_SaveLR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea727048e9b2c0d090a5797b13e1c5c827">llvm::Win64EH::UOP_SaveRegMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea16cfe12e38096341a1a273a904ef0d31">llvm::Win64EH::UOP_SaveRegsR4R7LR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea73e5f2ff29af4a2c90c8711b8a6780e4">llvm::Win64EH::UOP_SaveSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea60b7e4a0be5c03d2ec6fadf011036552">llvm::Win64EH::UOP_WideAllocHuge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eac65a3d732455e48352266b753b1a90e6">llvm::Win64EH::UOP_WideAllocLarge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea2b7d6e82d9ab706a4ed67f4214efefe5">llvm::Win64EH::UOP_WideAllocMedium</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea122a936a6e1d854afed8b6ecc54faec0">llvm::Win64EH::UOP_WideEndNop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea055da35948045301bbb791b59fda7948">llvm::Win64EH::UOP_WideNop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eae14d06b7d47c095bd18678232bfd5148">llvm::Win64EH::UOP_WideSaveRegMask</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea444955343875efc999ae15232dca1d16">llvm::Win64EH::UOP_WideSaveRegsR4R11LR</a>.</p>


<p>Referenced by <a href="#a1a64f841fb788b307e31f8a70e6c022a">checkARMInstructions</a>, <a href="#a73622e67d89cdc5f662981287e16879f">checkARMPackedEpilog</a> and <a href="#a982dd5c343c1b1e191b5cc1d00fefaf6">tryARMPackedUnwind</a>.</p>

</div>
</div>

### ARMCountOfUnwindCodes() {#a0d7a8cae2277a3c682e59c1a7e7a1b8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t ARMCountOfUnwindCodes (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a> &gt; Insns)</td>
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



<p>Definition at line 1431 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea3380a84eb648ca0ee05c138bb4e59c48">llvm::Win64EH::UOP_AllocHuge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea696f26056e05c65dd7c1bb6da6bb6c94">llvm::Win64EH::UOP_AllocLarge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea852e7cdf29ed57cc4c6fe34fbe236166">llvm::Win64EH::UOP_AllocSmall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea459472d4a0e3cd23f8448702e0f84325">llvm::Win64EH::UOP_Custom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea87d69becc531e1d468e00f36b1d0c5dd">llvm::Win64EH::UOP_End</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea2c1e73f96a3eb49c02ea5e2c23582c60">llvm::Win64EH::UOP_EndNop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea370cb5b95f05480a329dbc936969d5d7">llvm::Win64EH::UOP_Nop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea35a232904dcd802033ea03851f7838b2">llvm::Win64EH::UOP_SaveFRegD0D15</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaf6e5478d3596267b0b6340a415e93f45">llvm::Win64EH::UOP_SaveFRegD16D31</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eab3bc8467e0977cc0f9426032256c5540">llvm::Win64EH::UOP_SaveFRegD8D15</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabe9ce7cc4dc6542d11f840cc8e51a6f6">llvm::Win64EH::UOP_SaveLR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea727048e9b2c0d090a5797b13e1c5c827">llvm::Win64EH::UOP_SaveRegMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea16cfe12e38096341a1a273a904ef0d31">llvm::Win64EH::UOP_SaveRegsR4R7LR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea73e5f2ff29af4a2c90c8711b8a6780e4">llvm::Win64EH::UOP_SaveSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea60b7e4a0be5c03d2ec6fadf011036552">llvm::Win64EH::UOP_WideAllocHuge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eac65a3d732455e48352266b753b1a90e6">llvm::Win64EH::UOP_WideAllocLarge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea2b7d6e82d9ab706a4ed67f4214efefe5">llvm::Win64EH::UOP_WideAllocMedium</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea122a936a6e1d854afed8b6ecc54faec0">llvm::Win64EH::UOP_WideEndNop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea055da35948045301bbb791b59fda7948">llvm::Win64EH::UOP_WideNop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eae14d06b7d47c095bd18678232bfd5148">llvm::Win64EH::UOP_WideSaveRegMask</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea444955343875efc999ae15232dca1d16">llvm::Win64EH::UOP_WideSaveRegsR4R11LR</a>.</p>


<p>Referenced by <a href="#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>, <a href="#a73622e67d89cdc5f662981287e16879f">checkARMPackedEpilog</a> and <a href="#a66312fe172a047e8e8e25781786ada0b">getARMOffsetInProlog</a>.</p>

</div>
</div>

### ARMEmitRuntimeFunction() {#a48d2597504af337577491cde138a142b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMEmitRuntimeFunction (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> * info)</td>
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



<p>Definition at line 2526 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc3817979bc871dba942b87773da1cc0">llvm::MCStreamer::emitInt32</a>, <a href="#a70e3e2288f783c384791e314b8e20231">EmitSymbolRefWithOfs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9488c32df3cb8819f6a07f8c88d72c66">llvm::MCStreamer::emitValueToAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a61907d1fede3c9e9713b6b3a29d35b01">llvm::MCSymbolRefExpr::VK_COFF_IMGREL32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/win64eh/armunwindemitter/#ab428fc29f43b7cfc8e9059f4f3fc09fd">llvm::Win64EH::ARMUnwindEmitter::Emit</a>.</p>

</div>
</div>

### ARMEmitUnwindCode() {#a27cc5388854780051ed416ab2901e18e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMEmitUnwindCode (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a> &amp; inst)</td>
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



<p>Definition at line 1599 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af47540299db471532b82aba9314f1fc2">llvm::MCStreamer::emitInt8</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a86c704049f53c1ee871373dadce8aad5">llvm::WinEH::Instruction::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a35cb7e6f64b7406816d5bc30cfc5d27a">llvm::WinEH::Instruction::Operation</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a66c52d83c6dfd34d01144ab46d54efa6">llvm::WinEH::Instruction::Register</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea3380a84eb648ca0ee05c138bb4e59c48">llvm::Win64EH::UOP_AllocHuge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea696f26056e05c65dd7c1bb6da6bb6c94">llvm::Win64EH::UOP_AllocLarge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea852e7cdf29ed57cc4c6fe34fbe236166">llvm::Win64EH::UOP_AllocSmall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea459472d4a0e3cd23f8448702e0f84325">llvm::Win64EH::UOP_Custom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea87d69becc531e1d468e00f36b1d0c5dd">llvm::Win64EH::UOP_End</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea2c1e73f96a3eb49c02ea5e2c23582c60">llvm::Win64EH::UOP_EndNop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea370cb5b95f05480a329dbc936969d5d7">llvm::Win64EH::UOP_Nop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea35a232904dcd802033ea03851f7838b2">llvm::Win64EH::UOP_SaveFRegD0D15</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaf6e5478d3596267b0b6340a415e93f45">llvm::Win64EH::UOP_SaveFRegD16D31</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eab3bc8467e0977cc0f9426032256c5540">llvm::Win64EH::UOP_SaveFRegD8D15</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabe9ce7cc4dc6542d11f840cc8e51a6f6">llvm::Win64EH::UOP_SaveLR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea727048e9b2c0d090a5797b13e1c5c827">llvm::Win64EH::UOP_SaveRegMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea16cfe12e38096341a1a273a904ef0d31">llvm::Win64EH::UOP_SaveRegsR4R7LR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea73e5f2ff29af4a2c90c8711b8a6780e4">llvm::Win64EH::UOP_SaveSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea60b7e4a0be5c03d2ec6fadf011036552">llvm::Win64EH::UOP_WideAllocHuge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eac65a3d732455e48352266b753b1a90e6">llvm::Win64EH::UOP_WideAllocLarge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea2b7d6e82d9ab706a4ed67f4214efefe5">llvm::Win64EH::UOP_WideAllocMedium</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea122a936a6e1d854afed8b6ecc54faec0">llvm::Win64EH::UOP_WideEndNop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea055da35948045301bbb791b59fda7948">llvm::Win64EH::UOP_WideNop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eae14d06b7d47c095bd18678232bfd5148">llvm::Win64EH::UOP_WideSaveRegMask</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea444955343875efc999ae15232dca1d16">llvm::Win64EH::UOP_WideSaveRegsR4R11LR</a>.</p>


<p>Referenced by <a href="#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>.</p>

</div>
</div>

### ARMEmitUnwindInfo() {#ab831cd4cdeb2330513a8ca4d3ad3f610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMEmitUnwindInfo (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> * info, bool TryPacked=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 2270 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="#a0d7a8cae2277a3c682e59c1a7e7a1b8d">ARMCountOfUnwindCodes</a>, <a href="#a27cc5388854780051ed416ab2901e18e">ARMEmitUnwindCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1a64f841fb788b307e31f8a70e6c022a">checkARMInstructions</a>, <a href="#a73622e67d89cdc5f662981287e16879f">checkARMPackedEpilog</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a8757ce7071547a0410c82cc096b1ec9a">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a6b303b433f43b901194dbf17adfb562c">llvm::MCBinaryExpr::createOr</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a299bf2f0329389424760f4a7c8af75ac">llvm::MCContext::createTempSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc3817979bc871dba942b87773da1cc0">llvm::MCStreamer::emitInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af47540299db471532b82aba9314f1fc2">llvm::MCStreamer::emitInt8</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a822ae1a4f19b7b00a297a100749f9b8a">llvm::MCStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9488c32df3cb8819f6a07f8c88d72c66">llvm::MCStreamer::emitValueToAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#abc5baba59c735eeb15bdef969b458794ae91e8abe0e8b6cf6fffe4fae46d1d01e">Epilog</a>, <a href="#a9e599e8d393ec15804b6efbc478393a3">FindMatchingEpilog</a>, <a href="#a66312fe172a047e8e8e25781786ada0b">getARMOffsetInProlog</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="#aa18d22b8d07f4376fcf7c00d5923422a">GetOptionalAbsDifference</a>, <a href="#aaab77f3694a5bc3b29ffbc6ce87444ad">GetSubDivExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a>, <a href="#a1aaf032ee5c9603b8ae7c8da314f3013">isARMTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#abca23bddf517f69d28c6d30c58a7b6f9">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::lookup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a>, <a href="#a982dd5c343c1b1e191b5cc1d00fefaf6">tryARMPackedUnwind</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a61907d1fede3c9e9713b6b3a29d35b01">llvm::MCSymbolRefExpr::VK_COFF_IMGREL32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/win64eh/armunwindemitter/#ab428fc29f43b7cfc8e9059f4f3fc09fd">llvm::Win64EH::ARMUnwindEmitter::Emit</a> and <a href="/web-llvm/docs/api/classes/llvm/win64eh/armunwindemitter/#ae3581e58aa167be222e1d2b9c164b10a">llvm::Win64EH::ARMUnwindEmitter::EmitUnwindInfo</a>.</p>

</div>
</div>

### checkARM64Instructions() {#aa32035802671dce51123a77b96594506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void checkARM64Instructions (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a> &gt; Insns, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Begin, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * End, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Type)</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="#aa18d22b8d07f4376fcf7c00d5923422a">GetOptionalAbsDifference</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea1d63b21ce3a3530dc0992c9545532657">llvm::Win64EH::UOP_ClearUnwoundToCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaf3c84a367e177cb35173b55701e59b62">llvm::Win64EH::UOP_Context</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eacaef82dc45b07cc681ade2a07b365961">llvm::Win64EH::UOP_ECContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabb99442c04b0287262dcb4395886bd7e">llvm::Win64EH::UOP_PushMachFrame</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eae869ae7d5bcd450c29ee40c32c15f971">llvm::Win64EH::UOP_TrapFrame</a>.</p>


<p>Referenced by <a href="#a83e6ea9ad14301bc03c55827f0689dc0">ARM64FindSegmentsInFunction</a>.</p>

</div>
</div>

### checkARM64PackedEpilog() {#a01564c0b334eed6d8b36993f0ef70b73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int checkARM64PackedEpilog (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> * info, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/segment">WinEH::FrameInfo::Segment</a> * Seg, int PrologCodeBytes)</td>
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



<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="#a11eba4a181a5af5d65d14e020ae8ed1b">ARM64CountOfUnwindCodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#abc5baba59c735eeb15bdef969b458794ae91e8abe0e8b6cf6fffe4fae46d1d01e">Epilog</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/segment/#aca4a957f9b71fbcb8e652df7b214c98a">llvm::WinEH::FrameInfo::Segment::Epilogs</a>, <a href="#a3c46170fb77eea7b7bec6513b4a084aa">getARM64OffsetInProlog</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/segment/#af20720f31964dc84b5cd8990585fff66">llvm::WinEH::FrameInfo::Segment::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/segment/#aee85c8341f37756e35d371088a955391">llvm::WinEH::FrameInfo::Segment::Offset</a>.</p>


<p>Referenced by <a href="#a0bd3fbe76161d42d7470f0dd7dd634de">ARM64EmitUnwindInfoForSegment</a>.</p>

</div>
</div>

### checkARMInstructions() {#a1a64f841fb788b307e31f8a70e6c022a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void checkARMInstructions (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a> &gt; Insns, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Begin, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * End, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Type)</td>
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



<p>Definition at line 1561 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="#ac14ca7f5bcd20cfe1c461a7b4a353764">ARMCountOfInstructionBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="#aa18d22b8d07f4376fcf7c00d5923422a">GetOptionalAbsDifference</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a>.</p>


<p>Referenced by <a href="#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>.</p>

</div>
</div>

### checkARMPackedEpilog() {#a73622e67d89cdc5f662981287e16879f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int checkARMPackedEpilog (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> * info, int PrologCodeBytes)</td>
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



<p>Definition at line 1771 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="#ac14ca7f5bcd20cfe1c461a7b4a353764">ARMCountOfInstructionBytes</a>, <a href="#a0d7a8cae2277a3c682e59c1a7e7a1b8d">ARMCountOfUnwindCodes</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/epilog/#a5cea8eb6141764d39a0b4475191d5b3c">llvm::WinEH::FrameInfo::Epilog::Condition</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#abc5baba59c735eeb15bdef969b458794ae91e8abe0e8b6cf6fffe4fae46d1d01e">Epilog</a>, <a href="#a66312fe172a047e8e8e25781786ada0b">getARMOffsetInProlog</a>, <a href="#aa18d22b8d07f4376fcf7c00d5923422a">GetOptionalAbsDifference</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/epilog/#a346001a30654d6b6d77457965833723f">llvm::WinEH::FrameInfo::Epilog::Instructions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>.</p>

</div>
</div>

### CountOfUnwindCodes() {#aebb910ab6fa280018caf8bb78fcb91da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t CountOfUnwindCodes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a> &gt; &amp; Insns)</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea696f26056e05c65dd7c1bb6da6bb6c94">llvm::Win64EH::UOP_AllocLarge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea852e7cdf29ed57cc4c6fe34fbe236166">llvm::Win64EH::UOP_AllocSmall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabb99442c04b0287262dcb4395886bd7e">llvm::Win64EH::UOP_PushMachFrame</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaae7e62281f7ac9af9a2305acf345e30c">llvm::Win64EH::UOP_PushNonVol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea4e13ff9dd4e7826d85bbdd2671d1aa24">llvm::Win64EH::UOP_SaveNonVol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea20d9d4f8ad4a32c577c3c3af202df151">llvm::Win64EH::UOP_SaveNonVolBig</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea7e9f984ddcbc105b772e19e4b095cffc">llvm::Win64EH::UOP_SaveXMM128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea91d84d5df0879f33b1770710b7705c7d">llvm::Win64EH::UOP_SaveXMM128Big</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea6a008a4f48e5b08f2f1ea75159e5fee3">llvm::Win64EH::UOP_SetFPReg</a>.</p>


<p>Referenced by <a href="#a5d75ea3f9831315ebdb816d70c58c30b">EmitUnwindInfo</a>.</p>

</div>
</div>

### EmitAbsDifference() {#ab68ca7cc744c7d305f655930067e0a64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitAbsDifference (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * RHS)</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a6144ace1bbb2a8b3fe310225914ee101">EmitUnwindCode</a> and <a href="#a5d75ea3f9831315ebdb816d70c58c30b">EmitUnwindInfo</a>.</p>

</div>
</div>

### EmitRuntimeFunction() {#aa186dddb4125136ff27007f97e26759a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitRuntimeFunction (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> * info)</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="#a70e3e2288f783c384791e314b8e20231">EmitSymbolRefWithOfs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9488c32df3cb8819f6a07f8c88d72c66">llvm::MCStreamer::emitValueToAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a61907d1fede3c9e9713b6b3a29d35b01">llvm::MCSymbolRefExpr::VK_COFF_IMGREL32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/win64eh/unwindemitter/#a2325284fc9cfe14f9764717f5f0e4fb7">llvm::Win64EH::UnwindEmitter::Emit</a> and <a href="#a5d75ea3f9831315ebdb816d70c58c30b">EmitUnwindInfo</a>.</p>

</div>
</div>

### EmitSymbolRefWithOfs() {#a70e3e2288f783c384791e314b8e20231}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitSymbolRefWithOfs (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Base, int64_t Offset)</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a61907d1fede3c9e9713b6b3a29d35b01">llvm::MCSymbolRefExpr::VK_COFF_IMGREL32</a>.</p>


<p>Referenced by <a href="#a66a4df49046ec16dd9c64d36ba3cb62c">ARM64EmitRuntimeFunction</a>, <a href="#a48d2597504af337577491cde138a142b">ARMEmitRuntimeFunction</a> and <a href="#aa186dddb4125136ff27007f97e26759a">EmitRuntimeFunction</a>.</p>

</div>
</div>

### EmitSymbolRefWithOfs() {#a9387871e1bade9ef3f96c2469ec92fe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitSymbolRefWithOfs (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Base, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Other)</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a61907d1fede3c9e9713b6b3a29d35b01">llvm::MCSymbolRefExpr::VK_COFF_IMGREL32</a>.</p>

</div>
</div>

### EmitUnwindCode() {#a6144ace1bbb2a8b3fe310225914ee101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitUnwindCode (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * begin, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a> &amp; inst)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsection/#add652e7ff42f6239bfb6aeef0e86c6f1">llvm::MCSection::begin</a>, <a href="#ab68ca7cc744c7d305f655930067e0a64">EmitAbsDifference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9d412a2cef594fc0f45de176d51fee3b">llvm::MCStreamer::emitInt16</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af47540299db471532b82aba9314f1fc2">llvm::MCStreamer::emitInt8</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a1ce1ca20845d767c94e459d4a1d5b885">llvm::WinEH::Instruction::Label</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a86c704049f53c1ee871373dadce8aad5">llvm::WinEH::Instruction::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a35cb7e6f64b7406816d5bc30cfc5d27a">llvm::WinEH::Instruction::Operation</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a66c52d83c6dfd34d01144ab46d54efa6">llvm::WinEH::Instruction::Register</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea696f26056e05c65dd7c1bb6da6bb6c94">llvm::Win64EH::UOP_AllocLarge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea852e7cdf29ed57cc4c6fe34fbe236166">llvm::Win64EH::UOP_AllocSmall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabb99442c04b0287262dcb4395886bd7e">llvm::Win64EH::UOP_PushMachFrame</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaae7e62281f7ac9af9a2305acf345e30c">llvm::Win64EH::UOP_PushNonVol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea4e13ff9dd4e7826d85bbdd2671d1aa24">llvm::Win64EH::UOP_SaveNonVol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea20d9d4f8ad4a32c577c3c3af202df151">llvm::Win64EH::UOP_SaveNonVolBig</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea7e9f984ddcbc105b772e19e4b095cffc">llvm::Win64EH::UOP_SaveXMM128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea91d84d5df0879f33b1770710b7705c7d">llvm::Win64EH::UOP_SaveXMM128Big</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea6a008a4f48e5b08f2f1ea75159e5fee3">llvm::Win64EH::UOP_SetFPReg</a>.</p>


<p>Referenced by <a href="#a5d75ea3f9831315ebdb816d70c58c30b">EmitUnwindInfo</a>.</p>

</div>
</div>

### EmitUnwindInfo() {#a5d75ea3f9831315ebdb816d70c58c30b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EmitUnwindInfo (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> * info)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aebb910ab6fa280018caf8bb78fcb91da">CountOfUnwindCodes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a299bf2f0329389424760f4a7c8af75ac">llvm::MCContext::createTempSymbol</a>, <a href="#ab68ca7cc744c7d305f655930067e0a64">EmitAbsDifference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9d412a2cef594fc0f45de176d51fee3b">llvm::MCStreamer::emitInt16</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc3817979bc871dba942b87773da1cc0">llvm::MCStreamer::emitInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af47540299db471532b82aba9314f1fc2">llvm::MCStreamer::emitInt8</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a822ae1a4f19b7b00a297a100749f9b8a">llvm::MCStreamer::emitLabel</a>, <a href="#aa186dddb4125136ff27007f97e26759a">EmitRuntimeFunction</a>, <a href="#a6144ace1bbb2a8b3fe310225914ee101">EmitUnwindCode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9488c32df3cb8819f6a07f8c88d72c66">llvm::MCStreamer::emitValueToAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a86c704049f53c1ee871373dadce8aad5">llvm::WinEH::Instruction::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a35cb7e6f64b7406816d5bc30cfc5d27a">llvm::WinEH::Instruction::Operation</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a66c52d83c6dfd34d01144ab46d54efa6">llvm::WinEH::Instruction::Register</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a5cbd04acfda223b46bb9c21e15d9e2fbad1f4738b73956f7f48051202ebbe58e6">llvm::Win64EH::UNW_ChainInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a5cbd04acfda223b46bb9c21e15d9e2fbac7a3e9484b4f8694d3070df883125725">llvm::Win64EH::UNW_ExceptionHandler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a5cbd04acfda223b46bb9c21e15d9e2fba19aa3cc5317963c4b698291979bdbd45">llvm::Win64EH::UNW_TerminateHandler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea6a008a4f48e5b08f2f1ea75159e5fee3">llvm::Win64EH::UOP_SetFPReg</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a61907d1fede3c9e9713b6b3a29d35b01">llvm::MCSymbolRefExpr::VK_COFF_IMGREL32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/win64eh/unwindemitter/#aaad7a7f0ae118b34d41f8ceed7136672">llvm::Win64EH::UnwindEmitter::EmitUnwindInfo</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#a55e3f6a5c003de75eabd889a24709857">anonymous{PerfSupportPlugin.cpp}::getRecords</a>.</p>

</div>
</div>

### FindMatchingEpilog() {#a9e599e8d393ec15804b6efbc478393a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * FindMatchingEpilog (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a> &gt; &amp; EpilogInstrs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt; &amp; Epilogs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> * info)</td>
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



<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>.</p>


<p>Referenced by <a href="#adaf1a735e35b87dee5107e5ccd874783">ARM64ProcessEpilogs</a> and <a href="#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>.</p>

</div>
</div>

### GetAbsDifference() {#a78a76e3a4c69c3a2e321d1656155e9d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t GetAbsDifference (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * RHS)</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="#aa18d22b8d07f4376fcf7c00d5923422a">GetOptionalAbsDifference</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a6574f704d2fbd168f81e7552695170a8">ARM64EmitUnwindInfo</a> and <a href="#a83e6ea9ad14301bc03c55827f0689dc0">ARM64FindSegmentsInFunction</a>.</p>

</div>
</div>

### getARM64OffsetInProlog() {#a3c46170fb77eea7b7bec6513b4a084aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getARM64OffsetInProlog (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a> &gt; &amp; Prolog, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a> &gt; &amp; Epilog)</td>
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



<p>Definition at line 740 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="#a11eba4a181a5af5d65d14e020ae8ed1b">ARM64CountOfUnwindCodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#abc5baba59c735eeb15bdef969b458794ae91e8abe0e8b6cf6fffe4fae46d1d01e">Epilog</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#abc5baba59c735eeb15bdef969b458794adbb7fde55b4b341b4478c749fe200737">Prolog</a>.</p>


<p>Referenced by <a href="#adaf1a735e35b87dee5107e5ccd874783">ARM64ProcessEpilogs</a> and <a href="#a01564c0b334eed6d8b36993f0ef70b73">checkARM64PackedEpilog</a>.</p>

</div>
</div>

### getARMOffsetInProlog() {#a66312fe172a047e8e8e25781786ada0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getARMOffsetInProlog (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a> &gt; &amp; Prolog, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a> &gt; &amp; Epilog, bool CanTweakProlog)</td>
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



<p>Definition at line 1735 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="#a0d7a8cae2277a3c682e59c1a7e7a1b8d">ARMCountOfUnwindCodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#abc5baba59c735eeb15bdef969b458794ae91e8abe0e8b6cf6fffe4fae46d1d01e">Epilog</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#abc5baba59c735eeb15bdef969b458794adbb7fde55b4b341b4478c749fe200737">Prolog</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea87d69becc531e1d468e00f36b1d0c5dd">llvm::Win64EH::UOP_End</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea2c1e73f96a3eb49c02ea5e2c23582c60">llvm::Win64EH::UOP_EndNop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea122a936a6e1d854afed8b6ecc54faec0">llvm::Win64EH::UOP_WideEndNop</a>.</p>


<p>Referenced by <a href="#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a> and <a href="#a73622e67d89cdc5f662981287e16879f">checkARMPackedEpilog</a>.</p>

</div>
</div>

### GetOptionalAbsDifference() {#aa18d22b8d07f4376fcf7c00d5923422a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; int64_t &gt; GetOptionalAbsDifference (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * RHS)</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>, <a href="#aa32035802671dce51123a77b96594506">checkARM64Instructions</a>, <a href="#a1a64f841fb788b307e31f8a70e6c022a">checkARMInstructions</a>, <a href="#a73622e67d89cdc5f662981287e16879f">checkARMPackedEpilog</a>, <a href="#a78a76e3a4c69c3a2e321d1656155e9d9">GetAbsDifference</a> and <a href="#a982dd5c343c1b1e191b5cc1d00fefaf6">tryARMPackedUnwind</a>.</p>

</div>
</div>

### GetSubDivExpr() {#aaab77f3694a5bc3b29ffbc6ce87444ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * GetSubDivExpr (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * RHS, int Div)</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#abf02d969009762015e1f45b7f9b17e90">llvm::MCBinaryExpr::createDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>.</p>

</div>
</div>

### isARMTerminator() {#a1aaf032ee5c9603b8ae7c8da314f3013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isARMTerminator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a> &amp; inst)</td>
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



<p>Definition at line 1586 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a35cb7e6f64b7406816d5bc30cfc5d27a">llvm::WinEH::Instruction::Operation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea87d69becc531e1d468e00f36b1d0c5dd">llvm::Win64EH::UOP_End</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea2c1e73f96a3eb49c02ea5e2c23582c60">llvm::Win64EH::UOP_EndNop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea122a936a6e1d854afed8b6ecc54faec0">llvm::Win64EH::UOP_WideEndNop</a>.</p>


<p>Referenced by <a href="#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>.</p>

</div>
</div>

### parseRegMask() {#a7274589f20fb34bb658dbffebb1426c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool parseRegMask (unsigned Mask, bool &amp; HasLR, bool &amp; HasR11, unsigned &amp; Folded, int &amp; IntRegs)</td>
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



<p>Definition at line 1828 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/asmparser/sparcasmparser-cpp/#a731439fe9f2d178743bb3d3258782e3b">IntRegs</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a982dd5c343c1b1e191b5cc1d00fefaf6">tryARMPackedUnwind</a>.</p>

</div>
</div>

### simplifyARM64Opcodes() {#a27995b830d3e9bcf7a442eb12dee802f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void simplifyARM64Opcodes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a> &gt; &amp; Instructions, bool Reverse)</td>
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



<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eafa67f115c1fddc4ce1aeb1c754001585bc">llvm::Reverse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea5bf832be598907276533805261b14c94">llvm::Win64EH::UOP_AddFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea40d470d658f8310637362abe42236e5a">llvm::Win64EH::UOP_SaveFPLR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea1c1e91f085207677f6a87f72211a8e7d">llvm::Win64EH::UOP_SaveFPLRX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaa0e067e95931107f1361a0853805202b">llvm::Win64EH::UOP_SaveNext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabcce408cff8a8caddd672fcf9d5f7c4d">llvm::Win64EH::UOP_SaveR19R20X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea8c6bd0c4141baac292a758ad1e4ed2d2">llvm::Win64EH::UOP_SaveRegP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea9f7d600586e92963f5881e13cb4886ce">llvm::Win64EH::UOP_SaveRegPX</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea643ab7c0e9d1180026aeb5526d64afa9">llvm::Win64EH::UOP_SetFP</a>.</p>


<p>Referenced by <a href="#a6574f704d2fbd168f81e7552695170a8">ARM64EmitUnwindInfo</a>.</p>

</div>
</div>

### tryARM64PackedUnwind() {#a5c6c18ec71fabe4422710878b3d9c128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool tryARM64PackedUnwind (<a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> * info, uint32_t FuncLength, int PackedEpilogOffset)</td>
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



<p>Definition at line 804 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/asmparser/sparcasmparser-cpp/#a731439fe9f2d178743bb3d3258782e3b">IntRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a86c704049f53c1ee871373dadce8aad5">llvm::WinEH::Instruction::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a35cb7e6f64b7406816d5bc30cfc5d27a">llvm::WinEH::Instruction::Operation</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a66c52d83c6dfd34d01144ab46d54efa6">llvm::WinEH::Instruction::Register</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea5bf832be598907276533805261b14c94">llvm::Win64EH::UOP_AddFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea696f26056e05c65dd7c1bb6da6bb6c94">llvm::Win64EH::UOP_AllocLarge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eae2ba520dfe4a97772ebb8e010f14b90e">llvm::Win64EH::UOP_AllocMedium</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea852e7cdf29ed57cc4c6fe34fbe236166">llvm::Win64EH::UOP_AllocSmall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea1d63b21ce3a3530dc0992c9545532657">llvm::Win64EH::UOP_ClearUnwoundToCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaf3c84a367e177cb35173b55701e59b62">llvm::Win64EH::UOP_Context</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eacaef82dc45b07cc681ade2a07b365961">llvm::Win64EH::UOP_ECContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea87d69becc531e1d468e00f36b1d0c5dd">llvm::Win64EH::UOP_End</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea370cb5b95f05480a329dbc936969d5d7">llvm::Win64EH::UOP_Nop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabfe110fe2ab3ff5ef9141ceeb2fd0c7d">llvm::Win64EH::UOP_PACSignLR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabb99442c04b0287262dcb4395886bd7e">llvm::Win64EH::UOP_PushMachFrame</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea3ecd6abb34b66d0cea4a285a43ca62eb">llvm::Win64EH::UOP_SaveAnyRegD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaa32738827eafd247a5db8ccacf84ea84">llvm::Win64EH::UOP_SaveAnyRegDP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea143dd0f1157957f6d74230edfbdace28">llvm::Win64EH::UOP_SaveAnyRegDPX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea30be100959f86a48264856eb0130185e">llvm::Win64EH::UOP_SaveAnyRegDX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eafd194f2c1971298fa3ed259340dc7af0">llvm::Win64EH::UOP_SaveAnyRegI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eae8425317799d828362a3615b816ec496">llvm::Win64EH::UOP_SaveAnyRegIP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea54d0faec96686043b538bac78fe185d6">llvm::Win64EH::UOP_SaveAnyRegIPX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea7d52165a373988e5acd605fd09b65638">llvm::Win64EH::UOP_SaveAnyRegIX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea9fdabb65c8f4afc6d98b0997df0f4bc1">llvm::Win64EH::UOP_SaveAnyRegQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea3a9d85a19d84843f629750bfa002ab9b">llvm::Win64EH::UOP_SaveAnyRegQP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabda3f39fe0a0b595e2a21968c3cd83d4">llvm::Win64EH::UOP_SaveAnyRegQPX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea62df2c37135f5fa1bad0434bede59e70">llvm::Win64EH::UOP_SaveAnyRegQX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea40d470d658f8310637362abe42236e5a">llvm::Win64EH::UOP_SaveFPLR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea1c1e91f085207677f6a87f72211a8e7d">llvm::Win64EH::UOP_SaveFPLRX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea0ff61e9c16bb520f1195c5892ff628ec">llvm::Win64EH::UOP_SaveFReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea080b3b9cd2397e7ce59bfbd8d50220da">llvm::Win64EH::UOP_SaveFRegP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea17274b8b2b523abe03e911ad420586bf">llvm::Win64EH::UOP_SaveFRegPX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaf3b908c7dcda8acf3116614dc1874bd8">llvm::Win64EH::UOP_SaveFRegX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea77b13b268267acfad2a633a4207d695b">llvm::Win64EH::UOP_SaveLRPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaa0e067e95931107f1361a0853805202b">llvm::Win64EH::UOP_SaveNext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabcce408cff8a8caddd672fcf9d5f7c4d">llvm::Win64EH::UOP_SaveR19R20X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabd688d6bb3a01916b39bbf1d073ec4c1">llvm::Win64EH::UOP_SaveReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea8c6bd0c4141baac292a758ad1e4ed2d2">llvm::Win64EH::UOP_SaveRegP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea9f7d600586e92963f5881e13cb4886ce">llvm::Win64EH::UOP_SaveRegPX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea6177f784f0f7ad77aeda554a1bec7bc6">llvm::Win64EH::UOP_SaveRegX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea643ab7c0e9d1180026aeb5526d64afa9">llvm::Win64EH::UOP_SetFP</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eae869ae7d5bcd450c29ee40c32c15f971">llvm::Win64EH::UOP_TrapFrame</a>.</p>


<p>Referenced by <a href="#a0bd3fbe76161d42d7470f0dd7dd634de">ARM64EmitUnwindInfoForSegment</a>.</p>

</div>
</div>

### tryARMPackedUnwind() {#a982dd5c343c1b1e191b5cc1d00fefaf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool tryARMPackedUnwind (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; streamer, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> * info, uint32_t FuncLength)</td>
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



<p>Definition at line 1868 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="#ac14ca7f5bcd20cfe1c461a7b4a353764">ARMCountOfInstructionBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/epilog/#a5cea8eb6141764d39a0b4475191d5b3c">llvm::WinEH::FrameInfo::Epilog::Condition</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#abc5baba59c735eeb15bdef969b458794ae91e8abe0e8b6cf6fffe4fae46d1d01e">Epilog</a>, <a href="#aa18d22b8d07f4376fcf7c00d5923422a">GetOptionalAbsDifference</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/epilog/#a346001a30654d6b6d77457965833723f">llvm::WinEH::FrameInfo::Epilog::Instructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/asmparser/sparcasmparser-cpp/#a731439fe9f2d178743bb3d3258782e3b">IntRegs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a86c704049f53c1ee871373dadce8aad5">llvm::WinEH::Instruction::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a35cb7e6f64b7406816d5bc30cfc5d27a">llvm::WinEH::Instruction::Operation</a>, <a href="#a7274589f20fb34bb658dbffebb1426c4">parseRegMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a66c52d83c6dfd34d01144ab46d54efa6">llvm::WinEH::Instruction::Register</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea3380a84eb648ca0ee05c138bb4e59c48">llvm::Win64EH::UOP_AllocHuge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea696f26056e05c65dd7c1bb6da6bb6c94">llvm::Win64EH::UOP_AllocLarge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea852e7cdf29ed57cc4c6fe34fbe236166">llvm::Win64EH::UOP_AllocSmall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea459472d4a0e3cd23f8448702e0f84325">llvm::Win64EH::UOP_Custom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea87d69becc531e1d468e00f36b1d0c5dd">llvm::Win64EH::UOP_End</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea2c1e73f96a3eb49c02ea5e2c23582c60">llvm::Win64EH::UOP_EndNop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea370cb5b95f05480a329dbc936969d5d7">llvm::Win64EH::UOP_Nop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea35a232904dcd802033ea03851f7838b2">llvm::Win64EH::UOP_SaveFRegD0D15</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaf6e5478d3596267b0b6340a415e93f45">llvm::Win64EH::UOP_SaveFRegD16D31</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eab3bc8467e0977cc0f9426032256c5540">llvm::Win64EH::UOP_SaveFRegD8D15</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabe9ce7cc4dc6542d11f840cc8e51a6f6">llvm::Win64EH::UOP_SaveLR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea727048e9b2c0d090a5797b13e1c5c827">llvm::Win64EH::UOP_SaveRegMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea16cfe12e38096341a1a273a904ef0d31">llvm::Win64EH::UOP_SaveRegsR4R7LR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea73e5f2ff29af4a2c90c8711b8a6780e4">llvm::Win64EH::UOP_SaveSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea60b7e4a0be5c03d2ec6fadf011036552">llvm::Win64EH::UOP_WideAllocHuge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eac65a3d732455e48352266b753b1a90e6">llvm::Win64EH::UOP_WideAllocLarge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea2b7d6e82d9ab706a4ed67f4214efefe5">llvm::Win64EH::UOP_WideAllocMedium</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea122a936a6e1d854afed8b6ecc54faec0">llvm::Win64EH::UOP_WideEndNop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea055da35948045301bbb791b59fda7948">llvm::Win64EH::UOP_WideNop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eae14d06b7d47c095bd18678232bfd5148">llvm::Win64EH::UOP_WideSaveRegMask</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea444955343875efc999ae15232dca1d16">llvm::Win64EH::UOP_WideSaveRegsR4R11LR</a>.</p>


<p>Referenced by <a href="#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
