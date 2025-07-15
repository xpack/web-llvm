---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmachobjectwriter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ARMMachObjectWriter.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armfixupkinds-h">MCTargetDesc/ARMFixupKinds.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-h">MCTargetDesc/ARMMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">llvm/BinaryFormat/MachO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">llvm/MC/MCAssembler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">llvm/MC/MCFixup.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">llvm/MC/MCMachObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">llvm/MC/MCSection.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">llvm/MC/MCValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-armmachobjectwriter-cpp-">anonymous{ARMMachObjectWriter.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armmachobjectwriter-cpp-/armmachobjectwriter">ARMMachObjectWriter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a951157333861d746f5908c6ab6ead41a">getARMFixupKindMachOInfo</a> (unsigned Kind, unsigned &amp;RelocType, unsigned &amp;Log2Size)</td>
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

### getARMFixupKindMachOInfo() {#a951157333861d746f5908c6ab6ead41a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getARMFixupKindMachOInfo (unsigned Kind, unsigned &amp; RelocType, unsigned &amp; Log2Size)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmachobjectwriter-cpp">ARMMachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa0f9c042e43bdf5138b1cb367b81c24c4">llvm::MachO::ARM_RELOC_BR24</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfaf6e91ff8795152a02d4310c2debff044">llvm::MachO::ARM_RELOC_HALF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfafe908592b8ad4d11021be507dd0c2d72">llvm::MachO::ARM_RELOC_VANILLA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa191129bae4337ffd064cc19eeed66794">llvm::MachO::ARM_THUMB_RELOC_BR22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a0d7591bd8aae60a8151c5015a61f000b">llvm::ARM::fixup_arm_adr_pcrel_12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a92999538a175673cea0e806d24285585">llvm::ARM::fixup_arm_blx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0ac101b88c74df376a53087a2a12829576">llvm::ARM::fixup_arm_condbl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0afbaadabc6e1f4ff4ddacc0b8ddf61872">llvm::ARM::fixup_arm_condbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0ac8226e9dee163f040579c8cd8e5eb8c5">llvm::ARM::fixup_arm_ldst_pcrel_12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a551a7051fef9738a64327579574a84f1">llvm::ARM::fixup_arm_movt_hi16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a2b8a01780fc474ad24becf86799f112b">llvm::ARM::fixup_arm_movw_lo16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a1eea621a676048b22be7958e8be8a714">llvm::ARM::fixup_arm_pcrel_10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0adb86ef3fcfce8098efef7cb48f3ae98d">llvm::ARM::fixup_arm_thumb_bl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a78f923cec6a90c05ba09b4cf99112b93">llvm::ARM::fixup_arm_thumb_blx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a02e738702c5e86913f9f7df2f83480b3">llvm::ARM::fixup_arm_thumb_br</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a8b3ea0884f12a07077ecb6fd18395467">llvm::ARM::fixup_arm_uncondbl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a1f91bda8769d2b0c0a7e9d6e813334b8">llvm::ARM::fixup_arm_uncondbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a3175e012a680bfa04176f1073d837f78">llvm::ARM::fixup_t2_movt_hi16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0af29359bd1f79d7f6aec8e2c9275f44d1">llvm::ARM::fixup_t2_movw_lo16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a81dbbcf6c6a3e2c7c87af5dc5b9301d3">llvm::ARM::fixup_t2_uncondbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armmachobjectwriter-cpp-/armmachobjectwriter/#a03347d16edde093da0fc95c0e4a51420">anonymous{ARMMachObjectWriter.cpp}::ARMMachObjectWriter::recordRelocation</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
