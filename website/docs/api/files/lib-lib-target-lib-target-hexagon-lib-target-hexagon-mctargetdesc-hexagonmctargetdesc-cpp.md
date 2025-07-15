---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `HexagonMCTargetDesc.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">MCTargetDesc/HexagonMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagondeparch-h">HexagonDepArch.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetstreamer-h">HexagonTargetStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagoninstprinter-h">MCTargetDesc/HexagonInstPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcasminfo-h">MCTargetDesc/HexagonMCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcelfstreamer-h">MCTargetDesc/HexagonMCELFStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">MCTargetDesc/HexagonMCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/targetinfo/hexagontargetinfo-h">TargetInfo/HexagonTargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">llvm/BinaryFormat/ELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmbackend-h">llvm/MC/MCAsmBackend.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">llvm/MC/MCAssembler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeemitter-h">llvm/MC/MCCodeEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">llvm/MC/MCDwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">llvm/MC/MCELFObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfstreamer-h">llvm/MC/MCELFStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstranalysis-h">llvm/MC/MCInstrAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrinfo-h">llvm/MC/MCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hexagonattributes-h">llvm/Support/HexagonAttributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;mutex&gt;
#include &lt;new&gt;
#include &lt;string&gt;
#include &lt;unordered_map&gt;
#include "HexagonGenInstrInfo.inc"
#include "HexagonGenSubtargetInfo.inc"
#include "HexagonGenRegisterInfo.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-">anonymous{HexagonMCTargetDesc.cpp}</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/hexagonfunits">HexagonFUnits</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagontargetasmstreamer">HexagonTargetAsmStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagontargetelfstreamer">HexagonTargetELFStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagonmcinstranalysis">HexagonMCInstrAnalysis</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada3a2b0c364e8d049ebe9b2dd1ab3d3f">HexagonGetArchVariant</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7b0bbfb4d70e07b5c6587a6c9e314f1">createHexagonMCRegisterInfo</a> (const Triple &amp;TT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7b9e848c3ce6d787fb6bea4dd329e1c">createHexagonMCAsmInfo</a> (const MCRegisterInfo &amp;MRI, const Triple &amp;TT, const MCTargetOptions &amp;Options)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42cac87361dc127b8c38f96ec52f4a64">createHexagonMCInstPrinter</a> (const Triple &amp;T, unsigned SyntaxVariant, const MCAsmInfo &amp;MAI, const MCInstrInfo &amp;MII, const MCRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer">MCTargetStreamer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a215366d56d1b7eeafca6938a7b6591a0">createMCAsmTargetStreamer</a> (MCStreamer &amp;S, formatted_raw_ostream &amp;OS, MCInstPrinter *IP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5487e8e0178ee833202fada9a613f78b">createMCStreamer</a> (Triple const &amp;T, MCContext &amp;Context, std::unique_ptr&lt; MCAsmBackend &gt; &amp;&amp;MAB, std::unique_ptr&lt; MCObjectWriter &gt; &amp;&amp;OW, std::unique_ptr&lt; MCCodeEmitter &gt; &amp;&amp;Emitter)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer">MCTargetStreamer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e5b358a47a37ee955c4bf947efa659b">createHexagonObjectTargetStreamer</a> (MCStreamer &amp;S, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer">MCTargetStreamer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c51381863fd5a6f9b59e6da78b5ad3a">createHexagonNullTargetStreamer</a> (MCStreamer &amp;S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#acc1c483f4b4ee2f17bb6643a3b353609">LLVM_ATTRIBUTE_UNUSED</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a499b9606a8f1365f4515e3cce4f14474">clearFeature</a> (MCSubtargetInfo *STI, uint64_t F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#acc1c483f4b4ee2f17bb6643a3b353609">LLVM_ATTRIBUTE_UNUSED</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae64b1825b82ce592840287c8ebad2d2a">checkFeature</a> (MCSubtargetInfo *STI, uint64_t F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8377a5a0fe394aab78e4bc5b6b0ce059">isCPUValid</a> (StringRef CPU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis">MCInstrAnalysis</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40aeb85e7cc10164273a5372093b2d20">createHexagonMCInstrAnalysis</a> (const MCInstrInfo *Info)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436">Hexagon::ArchEnum</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab608a076dacb8c61a1135ac0a79af239">EnableHVX</a>("mhvx", cl::desc("Enable Hexagon Vector eXtensions"), cl::values(clEnumValN(Hexagon::ArchEnum::V60, "v60", "Build for HVX v60"), clEnumValN(Hexagon::ArchEnum::V62, "v62", "Build for HVX v62"), clEnumValN(Hexagon::ArchEnum::V65, "v65", "Build for HVX v65"), clEnumValN(Hexagon::ArchEnum::V66, "v66", "Build for HVX v66"), clEnumValN(Hexagon::ArchEnum::V67, "v67", "Build for HVX v67"), clEnumValN(Hexagon::ArchEnum::V68, "v68", "Build for HVX v68"), clEnumValN(Hexagon::ArchEnum::V69, "v69", "Build for HVX v69"), clEnumValN(Hexagon::ArchEnum::V71, "v71", "Build for HVX v71"), clEnumValN(Hexagon::ArchEnum::V73, "v73", "Build for HVX v73"), clEnumValN(Hexagon::ArchEnum::V75, "v75", "Build for HVX v75"), clEnumValN(Hexagon::ArchEnum::V79, "v79", "Build for HVX v79"), clEnumValN(Hexagon::ArchEnum::Generic, "", "")), cl::init(Hexagon::ArchEnum::NoArch), cl::ValueOptional)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5168e8208234b4e8ca93c2945119c5b9">DisableHVX</a>("mno-hvx", cl::Hidden, cl::desc("Disable Hexagon Vector eXtensions"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc5b01fc331da58853522cafa33dab7f">EnableHvxIeeeFp</a>("mhvx-ieee-fp", cl::Hidden, cl::desc("Enable HVX IEEE floating point extensions"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ee3b68a28f3eeaacdf7b3a02478d659">EnableHexagonCabac</a>("mcabac", cl::desc("tbd"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa4a019c2bb19ba4f60ae265214aa072">DefaultArch</a> = "hexagonv68"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bb37192519dda7f58d047ef64088275">ENABLE_INSTR_PREDICATE_VERIFIER</a></td>
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


<div class="doxySectionDef">

## Functions

### checkFeature() {#ae64b1825b82ce592840287c8ebad2d2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLVM_ATTRIBUTE_UNUSED checkFeature (<a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, uint64_t F)</td>
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



<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#acc1c483f4b4ee2f17bb6643a3b353609">LLVM_ATTRIBUTE_UNUSED</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#afb851cd69bea258a1020b268d3de3abd">llvm::Hexagon_MC::createHexagonMCSubtargetInfo</a>.</p>

</div>
</div>

### clearFeature() {#a499b9606a8f1365f4515e3cce4f14474}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVM_ATTRIBUTE_UNUSED clearFeature (<a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, uint64_t F)</td>
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



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#acc1c483f4b4ee2f17bb6643a3b353609">LLVM_ATTRIBUTE_UNUSED</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#acaa1de0987d9c003e41c92f310c45746">llvm::MCSubtargetInfo::ToggleFeature</a>.</p>

</div>
</div>

### createHexagonMCAsmInfo() {#ad7b9e848c3ce6d787fb6bea4dd329e1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmInfo * createHexagonMCAsmInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp; Options)</td>
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



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a0456a5b5fb7d2743d6852e8bba806c7d">llvm::MCAsmInfo::addInitialFrameState</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a64fe578753bb594671a8e440e32a2b95">llvm::MCCFIInstruction::cfiDefCfa</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>


<p>Referenced by <a href="#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a>.</p>

</div>
</div>

### createHexagonMCInstPrinter() {#a42cac87361dc127b8c38f96ec52f4a64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstPrinter * createHexagonMCInstPrinter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, unsigned SyntaxVariant, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp; MAI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a>.</p>

</div>
</div>

### createHexagonMCInstrAnalysis() {#a40aeb85e7cc10164273a5372093b2d20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstrAnalysis * createHexagonMCInstrAnalysis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> * Info)</td>
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



<p>Definition at line 740 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagonmcinstranalysis/#a554432bd6d3bd40c1347e6f7cca80e67">anonymous{HexagonMCTargetDesc.cpp}::HexagonMCInstrAnalysis::HexagonMCInstrAnalysis</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>.</p>


<p>Referenced by <a href="#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a>.</p>

</div>
</div>

### createHexagonMCRegisterInfo() {#aa7b0bbfb4d70e07b5c6587a6c9e314f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegisterInfo * createHexagonMCRegisterInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT)</td>
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



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a>.</p>

</div>
</div>

### createHexagonNullTargetStreamer() {#a1c51381863fd5a6f9b59e6da78b5ad3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCTargetStreamer * createHexagonNullTargetStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S)</td>
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



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a>.</p>

</div>
</div>

### createHexagonObjectTargetStreamer() {#a1e5b358a47a37ee955c4bf947efa659b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCTargetStreamer * createHexagonObjectTargetStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagontargetelfstreamer/#a08a63a7b8a4b95d82daa67e148736cd0">anonymous{HexagonMCTargetDesc.cpp}::HexagonTargetELFStreamer::HexagonTargetELFStreamer</a>.</p>


<p>Referenced by <a href="#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a>.</p>

</div>
</div>

### createMCAsmTargetStreamer() {#a215366d56d1b7eeafca6938a7b6591a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCTargetStreamer * createMCAsmTargetStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> * IP)</td>
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



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagontargetasmstreamer/#af893a2742572b05fddf2e6e6681cbd07">anonymous{HexagonMCTargetDesc.cpp}::HexagonTargetAsmStreamer::HexagonTargetAsmStreamer</a>.</p>

</div>
</div>

### createMCStreamer() {#a5487e8e0178ee833202fada9a613f78b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCStreamer * createMCStreamer (<a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt; &amp;&amp; MAB, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a> &gt; &amp;&amp; OW, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt; &amp;&amp; Emitter)</td>
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



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac220467edcbcaecf0def115cb4e1b38d">llvm::createHexagonELFStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### HexagonGetArchVariant() {#ada3a2b0c364e8d049ebe9b2dd1ab3d3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef HexagonGetArchVariant ()</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#aea799c06a81ebc7804f0dfeb8c6abb0e">anonymous{HexagonMCTargetDesc.cpp}::MV5</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#a4f8b07639f9e4ce4803ba229d3eb3092">anonymous{HexagonMCTargetDesc.cpp}::MV55</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#ac9bbef802364faa2709eec2f557cb1af">anonymous{HexagonMCTargetDesc.cpp}::MV60</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#a8bd7ac7fc67ff2e7071bea916c53166f">anonymous{HexagonMCTargetDesc.cpp}::MV62</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#a59f962fd218d26a3e04afb9952ee42a0">anonymous{HexagonMCTargetDesc.cpp}::MV65</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#a405a78336379f05386ce4535451c9260">anonymous{HexagonMCTargetDesc.cpp}::MV66</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#a946ef57fa8c3ddca341ec225dbfc9d23">anonymous{HexagonMCTargetDesc.cpp}::MV67</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#a4a352710d4ab7db74a7d33d71b585c85">anonymous{HexagonMCTargetDesc.cpp}::MV67T</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#af27b02a1ff6a77cde66910e6dae637d5">anonymous{HexagonMCTargetDesc.cpp}::MV68</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#ad19a56208855f807f2e8548d4e9f64f0">anonymous{HexagonMCTargetDesc.cpp}::MV69</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#a347bd13f61f1456fb3c8163449b460e9">anonymous{HexagonMCTargetDesc.cpp}::MV71</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#a69bf7aeb68398ee9123906db93ec61f5">anonymous{HexagonMCTargetDesc.cpp}::MV71T</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#ad58075072154993da11a73925cd864c1">anonymous{HexagonMCTargetDesc.cpp}::MV73</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#ab2b028f39911c18eaebbecd94de63eaf">anonymous{HexagonMCTargetDesc.cpp}::MV75</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#a5c8c1bc56cedd07c2a0a7433be767c11">anonymous{HexagonMCTargetDesc.cpp}::MV79</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#aa93fa22630383fe07736811e31c03f81">llvm::Hexagon_MC::selectHexagonCPU</a>.</p>

</div>
</div>

### isCPUValid() {#a8377a5a0fe394aab78e4bc5b6b0ce059}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isCPUValid (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU)</td>
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



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#afd5440e15db345bf9daf9a8961192663">llvm::Hexagon::getCpu</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#afb851cd69bea258a1020b268d3de3abd">llvm::Hexagon_MC::createHexagonMCSubtargetInfo</a>.</p>

</div>
</div>

### LLVMInitializeHexagonTargetMC() {#a98a868de586290904766e4922d3e870b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_EXTERNAL_VISIBILITY void LLVMInitializeHexagonTargetMC ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 745 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a72eaee9433568ed277e40ed923f7bb50">llvm::createHexagonAsmBackend</a>, <a href="#ad7b9e848c3ce6d787fb6bea4dd329e1c">createHexagonMCAsmInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a201ff94ae00517f5c91220e7f047c7e8">llvm::createHexagonMCCodeEmitter</a>, <a href="#a42cac87361dc127b8c38f96ec52f4a64">createHexagonMCInstPrinter</a>, <a href="#a40aeb85e7cc10164273a5372093b2d20">createHexagonMCInstrAnalysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa982b3d4867712314f94ac9d9006ee03">llvm::createHexagonMCInstrInfo</a>, <a href="#aa7b0bbfb4d70e07b5c6587a6c9e314f1">createHexagonMCRegisterInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#afb851cd69bea258a1020b268d3de3abd">llvm::Hexagon_MC::createHexagonMCSubtargetInfo</a>, <a href="#a1c51381863fd5a6f9b59e6da78b5ad3a">createHexagonNullTargetStreamer</a>, <a href="#a1e5b358a47a37ee955c4bf947efa659b">createHexagonObjectTargetStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmctargetdesc-cpp/#aa6de446dfda14bbfb87a6f0ca5c9c121">createMCAsmTargetStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-cpp/#a4108c77c9b7670161fa060ebad07e167">createMCStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57f539ab05ad50c345d4d4975d0ffd6f">llvm::getTheHexagonTarget</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#af5d003503498e90bccf7a5d1626e9af6">llvm::TargetRegistry::RegisterAsmTargetStreamer</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a73452a801e9e22c8eac961cc7b598fe3">llvm::TargetRegistry::RegisterELFStreamer</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a158db359a78dc87d4f7b2e96585b78ae">llvm::TargetRegistry::RegisterMCAsmBackend</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a2e06603b238d255bf8d182eaa9e18c7a">llvm::TargetRegistry::RegisterMCCodeEmitter</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#aabd8e913cb341182f1ef8c24c25e50ad">llvm::TargetRegistry::RegisterMCInstPrinter</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a515b55c070d9124a373c062641765ed1">llvm::TargetRegistry::RegisterMCInstrAnalysis</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#abea956a9e4d1526501d68bee93470e53">llvm::TargetRegistry::RegisterMCInstrInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a0be8ffbacd90d86a1c1f27a032e2265e">llvm::TargetRegistry::RegisterMCRegInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a469331cb6070bffd3354391877547014">llvm::TargetRegistry::RegisterMCSubtargetInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a7829ce3a27ad6098c5997b933c8a42f9">llvm::TargetRegistry::RegisterNullTargetStreamer</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a4fb8d8db91a731340d7ce8dd79af8a70">llvm::TargetRegistry::RegisterObjectTargetStreamer</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DefaultArch {#afa4a019c2bb19ba4f60ae265214aa072}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef DefaultArch = "hexagonv68"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#aa93fa22630383fe07736811e31c03f81">llvm::Hexagon_MC::selectHexagonCPU</a>.</p>

</div>
</div>

### DisableHVX {#a5168e8208234b4e8ca93c2945119c5b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableHVX("mno-hvx", cl::Hidden, cl::desc("Disable Hexagon Vector eXtensions"))</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>

</div>
</div>

### EnableHexagonCabac {#a0ee3b68a28f3eeaacdf7b3a02478d659}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableHexagonCabac("mcabac", cl::desc("tbd"), cl::init(false))</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#a0cbf0f1e4f9a6bf0e11f4453f89c878e">anonymous{HexagonMCTargetDesc.cpp}::selectHexagonFS</a>.</p>

</div>
</div>

### EnableHVX {#ab608a076dacb8c61a1135ac0a79af239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; Hexagon::ArchEnum &gt; EnableHVX("mhvx", cl::desc("Enable Hexagon Vector eXtensions"), cl::values(clEnumValN(Hexagon::ArchEnum::V60, "v60", "Build for HVX v60"), clEnumValN(Hexagon::ArchEnum::V62, "v62", "Build for HVX v62"), clEnumValN(Hexagon::ArchEnum::V65, "v65", "Build for HVX v65"), clEnumValN(Hexagon::ArchEnum::V66, "v66", "Build for HVX v66"), clEnumValN(Hexagon::ArchEnum::V67, "v67", "Build for HVX v67"), clEnumValN(Hexagon::ArchEnum::V68, "v68", "Build for HVX v68"), clEnumValN(Hexagon::ArchEnum::V69, "v69", "Build for HVX v69"), clEnumValN(Hexagon::ArchEnum::V71, "v71", "Build for HVX v71"), clEnumValN(Hexagon::ArchEnum::V73, "v73", "Build for HVX v73"), clEnumValN(Hexagon::ArchEnum::V75, "v75", "Build for HVX v75"), clEnumValN(Hexagon::ArchEnum::V79, "v79", "Build for HVX v79"), clEnumValN(Hexagon::ArchEnum::Generic, "", "")), cl::init(Hexagon::ArchEnum::NoArch), cl::ValueOptional)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#a0cbf0f1e4f9a6bf0e11f4453f89c878e">anonymous{HexagonMCTargetDesc.cpp}::selectHexagonFS</a>.</p>

</div>
</div>

### EnableHvxIeeeFp {#acc5b01fc331da58853522cafa33dab7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableHvxIeeeFp("mhvx-ieee-fp", cl::Hidden, cl::desc("Enable HVX IEEE floating point extensions"))</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#a0cbf0f1e4f9a6bf0e11f4453f89c878e">anonymous{HexagonMCTargetDesc.cpp}::selectHexagonFS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ENABLE\_INSTR\_PREDICATE\_VERIFIER {#a6bb37192519dda7f58d047ef64088275}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENABLE_INSTR_PREDICATE_VERIFIER</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>

</div>
</div>

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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>

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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>

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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
