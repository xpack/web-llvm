---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `ARMAsmBackend.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">MCTargetDesc/ARMAsmBackend.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">MCTargetDesc/ARMAddressingModes.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackenddarwin-h">MCTargetDesc/ARMAsmBackendDarwin.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackendelf-h">MCTargetDesc/ARMAsmBackendELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackendwincoff-h">MCTargetDesc/ARMAsmBackendWinCOFF.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armfixupkinds-h">MCTargetDesc/ARMFixupKinds.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-h">MCTargetDesc/ARMMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">llvm/BinaryFormat/ELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">llvm/BinaryFormat/MachO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmbackend-h">llvm/MC/MCAsmBackend.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">llvm/MC/MCAssembler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdirectives-h">llvm/MC/MCDirectives.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">llvm/MC/MCELFObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixupkindinfo-h">llvm/MC/MCFixupKindInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectwriter-h">llvm/MC/MCObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">llvm/MC/MCTargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">llvm/MC/MCValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">llvm/Support/EndianStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "llvm/BinaryFormat/ELFRelocs/ARM.def"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-armasmbackend-cpp-">anonymous{ARMAsmBackend.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/cu">CU</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armasmbackend-cpp-/armelfobjectwriter">ARMELFObjectWriter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab6bca7f04b7048a44ef3e887328df7a">checkPCRelOffset</a> (uint64_t Value, int64_t Min, int64_t Max)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20dcf78408d6fb68621f440f31c5ccf2">swapHalfWords</a> (uint32_t Value, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dc7acf8b3c43429ae38afb5d9d562ae">joinHalfWords</a> (uint32_t FirstHalf, uint32_t SecondHalf, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac372fb24df18ed69d99fb8658ec0e7a7">getFixupKindNumBytes</a> (unsigned Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFixupKindNumBytes - The number of bytes the fixup may change. <a href="#ac372fb24df18ed69d99fb8658ec0e7a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a679283d1a6dfa1b34e7ae84492d9daa0">getFixupKindContainerSizeBytes</a> (unsigned Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFixupKindContainerSizeBytes - The number of bytes of the container involved in big endian. <a href="#a679283d1a6dfa1b34e7ae84492d9daa0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f6ab6658167369fdde830fd3c8d287c">createARMAsmBackend</a> (const Target &amp;T, const MCSubtargetInfo &amp;STI, const MCRegisterInfo &amp;MRI, const MCTargetOptions &amp;Options, llvm::endianness Endian)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a849ad88f43c60318de4376137d8e2afc">ELF_RELOC</a>(X, Y)&nbsp;&nbsp;&nbsp;.Case(#<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>)</td>
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

### checkPCRelOffset() {#aab6bca7f04b7048a44ef3e887328df7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * checkPCRelOffset (uint64_t Value, int64_t Min, int64_t Max)</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#a2dbae0b9fd70753e65a348ef9eaf1aaf">llvm::ARMAsmBackend::reasonForFixupRelaxation</a>.</p>

</div>
</div>

### createARMAsmBackend() {#a8f6ab6658167369fdde830fd3c8d287c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmBackend * createARMAsmBackend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp; Options, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> Endian)</td>
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



<p>Definition at line 1381 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201aa943abc041caa1cc4c074bbf38b76267">llvm::Triple::COFF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a456b64e26b8bcdbd8294689615d8a055">llvm::Triple::ELF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a71ceb704cd8260b471b28358df7bd0d4a92024c2a32564d5389413a91e0cc00b8">llvm::ELF::ELFOSABI_ARM_FDPIC</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a2e265a0d332c3e2db0acf0c7afd4175d">llvm::Triple::getObjectFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5a777de4cd152c5b22b9d28439326d50">llvm::Triple::getOS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter/#a886c9935f33464c780eb3b937c4560da">llvm::MCELFObjectTargetWriter::getOSABI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a1ef6ef4ff039e873e9f66e21e3e55e26">llvm::MCSubtargetInfo::getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#aea6d215256ae43bc9149bf41f2cc7694">llvm::Triple::isOSBinFormatELF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a7736bfc4c1afef875ecf02f2a7701fe3">llvm::Triple::isOSWindows</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a17b2679f91f697a4ffe46b872152e25b">llvm::Triple::isThumb</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a2ed78f59e2d35011e1d1ed0ad96cf411">llvm::Triple::MachO</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3839bb83ad5e546268d888a86d90fbf3">llvm::createARMBEAsmBackend</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4e8463919f27e573e0042eda41e434cb">llvm::createARMLEAsmBackend</a>.</p>

</div>
</div>

### getFixupKindContainerSizeBytes() {#a679283d1a6dfa1b34e7ae84492d9daa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getFixupKindContainerSizeBytes (unsigned Kind)</td>
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

<p>getFixupKindContainerSizeBytes - The number of bytes of the container involved in big endian.</p>

<p>Definition at line 1068 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a0d7591bd8aae60a8151c5015a61f000b">llvm::ARM::fixup_arm_adr_pcrel_12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a92999538a175673cea0e806d24285585">llvm::ARM::fixup_arm_blx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0ac101b88c74df376a53087a2a12829576">llvm::ARM::fixup_arm_condbl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0afbaadabc6e1f4ff4ddacc0b8ddf61872">llvm::ARM::fixup_arm_condbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0ac8226e9dee163f040579c8cd8e5eb8c5">llvm::ARM::fixup_arm_ldst_pcrel_12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0ad8333a61d51a1a24c7282773e6099667">llvm::ARM::fixup_arm_mod_imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a551a7051fef9738a64327579574a84f1">llvm::ARM::fixup_arm_movt_hi16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a2b8a01780fc474ad24becf86799f112b">llvm::ARM::fixup_arm_movw_lo16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a1eea621a676048b22be7958e8be8a714">llvm::ARM::fixup_arm_pcrel_10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a8c5b03f8ae59e84ef4b8301c9cf246b3">llvm::ARM::fixup_arm_pcrel_10_unscaled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a4e8f8786070cb526f59e12e7141d0b3d">llvm::ARM::fixup_arm_pcrel_9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a9ad27f8b55ac56d16b5e0c378bad0051">llvm::ARM::fixup_arm_thumb_bcc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0adb86ef3fcfce8098efef7cb48f3ae98d">llvm::ARM::fixup_arm_thumb_bl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a78f923cec6a90c05ba09b4cf99112b93">llvm::ARM::fixup_arm_thumb_blx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a02e738702c5e86913f9f7df2f83480b3">llvm::ARM::fixup_arm_thumb_br</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a293bb495311c0764277085879d15c057">llvm::ARM::fixup_arm_thumb_cb</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a7b3659cc67fef8cc53f589860b2f1299">llvm::ARM::fixup_arm_thumb_cp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a395a669e3966360328fdb04b8e4d32d5">llvm::ARM::fixup_arm_thumb_lower_0_7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0accb1029955f0d3a550b1b96e1d6b5f78">llvm::ARM::fixup_arm_thumb_lower_8_15</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a9ccf8ef9481f1525a17726e9637798a4">llvm::ARM::fixup_arm_thumb_upper_0_7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a0d3f21c752fedc664c8a23df76f9a107">llvm::ARM::fixup_arm_thumb_upper_8_15</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a8b3ea0884f12a07077ecb6fd18395467">llvm::ARM::fixup_arm_uncondbl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a1f91bda8769d2b0c0a7e9d6e813334b8">llvm::ARM::fixup_arm_uncondbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a6555681f7809e4db3c0869b70d55995e">llvm::ARM::fixup_bf_branch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a07e85c2a333077f3cc595abcb7a27291">llvm::ARM::fixup_bf_target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a74594465a337cf8b251cee95aa0f512b">llvm::ARM::fixup_bfc_target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0aa605fdc6a8c29df27b40b4d327c98b6f">llvm::ARM::fixup_bfcsel_else_target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a813cea44cae2b85cd8224f154ec4ff05">llvm::ARM::fixup_bfl_target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a3bf7591ae1a1baca62aa917ffd3f4d16">llvm::ARM::fixup_le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0aac71630154c96f2f6b3e2e324a40037c">llvm::ARM::fixup_t2_adr_pcrel_12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0abd8de06471430072373886fe44229083">llvm::ARM::fixup_t2_condbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a336d5f4419eb0ef8073bbac49a84de19">llvm::ARM::fixup_t2_ldst_pcrel_12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a3175e012a680bfa04176f1073d837f78">llvm::ARM::fixup_t2_movt_hi16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0af29359bd1f79d7f6aec8e2c9275f44d1">llvm::ARM::fixup_t2_movw_lo16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a6d87443e7775d51eaf0708da110f352a">llvm::ARM::fixup_t2_pcrel_10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a602810052128acb5e2f15572370533bf">llvm::ARM::fixup_t2_pcrel_9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0aeebc6c5e4e32b0c507045b954dd187b5">llvm::ARM::fixup_t2_so_imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a81dbbcf6c6a3e2c7c87af5dc5b9301d3">llvm::ARM::fixup_t2_uncondbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a09a9168eafc337c15e7de013524a1532">llvm::ARM::fixup_thumb_adr_pcrel_10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0adbee28ccbbf59371a33a9b6741c890a3">llvm::ARM::fixup_wls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#a454671b28fb42060da505e5692fccc77">llvm::ARMAsmBackend::applyFixup</a>.</p>

</div>
</div>

### getFixupKindNumBytes() {#ac372fb24df18ed69d99fb8658ec0e7a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getFixupKindNumBytes (unsigned Kind)</td>
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

<p>getFixupKindNumBytes - The number of bytes the fixup may change.</p>

<p>Definition at line 1002 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a0d7591bd8aae60a8151c5015a61f000b">llvm::ARM::fixup_arm_adr_pcrel_12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a92999538a175673cea0e806d24285585">llvm::ARM::fixup_arm_blx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0ac101b88c74df376a53087a2a12829576">llvm::ARM::fixup_arm_condbl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0afbaadabc6e1f4ff4ddacc0b8ddf61872">llvm::ARM::fixup_arm_condbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a48f07670606b6468cdcec6b936f0de95">llvm::ARM::fixup_arm_ldst_abs_12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0ac8226e9dee163f040579c8cd8e5eb8c5">llvm::ARM::fixup_arm_ldst_pcrel_12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0ad8333a61d51a1a24c7282773e6099667">llvm::ARM::fixup_arm_mod_imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a551a7051fef9738a64327579574a84f1">llvm::ARM::fixup_arm_movt_hi16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a2b8a01780fc474ad24becf86799f112b">llvm::ARM::fixup_arm_movw_lo16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a1eea621a676048b22be7958e8be8a714">llvm::ARM::fixup_arm_pcrel_10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a8c5b03f8ae59e84ef4b8301c9cf246b3">llvm::ARM::fixup_arm_pcrel_10_unscaled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a4e8f8786070cb526f59e12e7141d0b3d">llvm::ARM::fixup_arm_pcrel_9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a9ad27f8b55ac56d16b5e0c378bad0051">llvm::ARM::fixup_arm_thumb_bcc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0adb86ef3fcfce8098efef7cb48f3ae98d">llvm::ARM::fixup_arm_thumb_bl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a78f923cec6a90c05ba09b4cf99112b93">llvm::ARM::fixup_arm_thumb_blx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a02e738702c5e86913f9f7df2f83480b3">llvm::ARM::fixup_arm_thumb_br</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a293bb495311c0764277085879d15c057">llvm::ARM::fixup_arm_thumb_cb</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a7b3659cc67fef8cc53f589860b2f1299">llvm::ARM::fixup_arm_thumb_cp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a395a669e3966360328fdb04b8e4d32d5">llvm::ARM::fixup_arm_thumb_lower_0_7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0accb1029955f0d3a550b1b96e1d6b5f78">llvm::ARM::fixup_arm_thumb_lower_8_15</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a9ccf8ef9481f1525a17726e9637798a4">llvm::ARM::fixup_arm_thumb_upper_0_7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a0d3f21c752fedc664c8a23df76f9a107">llvm::ARM::fixup_arm_thumb_upper_8_15</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a8b3ea0884f12a07077ecb6fd18395467">llvm::ARM::fixup_arm_uncondbl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a1f91bda8769d2b0c0a7e9d6e813334b8">llvm::ARM::fixup_arm_uncondbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a6555681f7809e4db3c0869b70d55995e">llvm::ARM::fixup_bf_branch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a07e85c2a333077f3cc595abcb7a27291">llvm::ARM::fixup_bf_target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a74594465a337cf8b251cee95aa0f512b">llvm::ARM::fixup_bfc_target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0aa605fdc6a8c29df27b40b4d327c98b6f">llvm::ARM::fixup_bfcsel_else_target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a813cea44cae2b85cd8224f154ec4ff05">llvm::ARM::fixup_bfl_target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a3bf7591ae1a1baca62aa917ffd3f4d16">llvm::ARM::fixup_le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0aac71630154c96f2f6b3e2e324a40037c">llvm::ARM::fixup_t2_adr_pcrel_12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0abd8de06471430072373886fe44229083">llvm::ARM::fixup_t2_condbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a336d5f4419eb0ef8073bbac49a84de19">llvm::ARM::fixup_t2_ldst_pcrel_12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a3175e012a680bfa04176f1073d837f78">llvm::ARM::fixup_t2_movt_hi16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0af29359bd1f79d7f6aec8e2c9275f44d1">llvm::ARM::fixup_t2_movw_lo16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a6d87443e7775d51eaf0708da110f352a">llvm::ARM::fixup_t2_pcrel_10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a602810052128acb5e2f15572370533bf">llvm::ARM::fixup_t2_pcrel_9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0aeebc6c5e4e32b0c507045b954dd187b5">llvm::ARM::fixup_t2_so_imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a81dbbcf6c6a3e2c7c87af5dc5b9301d3">llvm::ARM::fixup_t2_uncondbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a09a9168eafc337c15e7de013524a1532">llvm::ARM::fixup_thumb_adr_pcrel_10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0adbee28ccbbf59371a33a9b6741c890a3">llvm::ARM::fixup_wls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a128346d352fde2e704c07867f4d82eef">llvm::FK_SecRel_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a8b2acba82b6d0830ab47d67eb8f1ccf0">llvm::FK_SecRel_4</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### joinHalfWords() {#a9dc7acf8b3c43429ae38afb5d9d562ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t joinHalfWords (uint32_t FirstHalf, uint32_t SecondHalf, bool IsLittleEndian)</td>
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



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#acd2d48bd67d42ac499c2b0acdef4c2c3">llvm::ARMAsmBackend::adjustFixupValue</a>.</p>

</div>
</div>

### swapHalfWords() {#a20dcf78408d6fb68621f440f31c5ccf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t swapHalfWords (uint32_t Value, bool IsLittleEndian)</td>
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



<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#acd2d48bd67d42ac499c2b0acdef4c2c3">llvm::ARMAsmBackend::adjustFixupValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ELF\_RELOC {#a849ad88f43c60318de4376137d8e2afc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ELF_RELOC(X, Y)&nbsp;&nbsp;&nbsp;.Case(#<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
