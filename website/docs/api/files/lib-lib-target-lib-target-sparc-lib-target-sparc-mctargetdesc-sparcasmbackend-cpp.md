---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcasmbackend-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SparcAsmBackend.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcfixupkinds-h">MCTargetDesc/SparcFixupKinds.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmctargetdesc-h">MCTargetDesc/SparcMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmbackend-h">llvm/MC/MCAsmBackend.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">llvm/MC/MCELFObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixupkindinfo-h">llvm/MC/MCFixupKindInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectwriter-h">llvm/MC/MCObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">llvm/MC/MCValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">llvm/Support/EndianStream.h</a>"
#include "llvm/BinaryFormat/ELFRelocs/Sparc.def"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-sparcasmbackend-cpp-">anonymous{SparcAsmBackend.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-sparcasmbackend-cpp-/sparcasmbackend">SparcAsmBackend</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-sparcasmbackend-cpp-/elfsparcasmbackend">ELFSparcAsmBackend</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13448f8922e1004861f8be9adf109bbf">adjustFixupValue</a> (unsigned Kind, uint64_t Value)</td>
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

### adjustFixupValue() {#a13448f8922e1004861f8be9adf109bbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned adjustFixupValue (unsigned Kind, uint64_t Value)</td>
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



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcasmbackend-cpp">SparcAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da602d9804c6b15c3eaa51cdeeeda754d2">llvm::Sparc::fixup_sparc_13</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da0ed75123c86696d6dfbbc2643828abfc">llvm::Sparc::fixup_sparc_br16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da5c2a82f403be827f912129618ce8bb07">llvm::Sparc::fixup_sparc_br19</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502daa66dfa8233272b1a84f34f5732cb8ef8">llvm::Sparc::fixup_sparc_br22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da4adff73a6fdb09236d160a1058cd738c">llvm::Sparc::fixup_sparc_call30</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da3e8e53769c95864f744db5c800d2452c">llvm::Sparc::fixup_sparc_got10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da4bd19ebcb42069f48ac3d45dc1dc2c95">llvm::Sparc::fixup_sparc_got13</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da7904709be5733140c3834f84bf9721d3">llvm::Sparc::fixup_sparc_got22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da2cfd03bdef2da2a2493359d4443ffc00">llvm::Sparc::fixup_sparc_gotdata_hix22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502dabb1e74c3b7243667280210404a2d21d3">llvm::Sparc::fixup_sparc_gotdata_lox10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da4ffe3fe32ce294fa71d496bd72924532">llvm::Sparc::fixup_sparc_gotdata_op</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da7cb7e71faac52ef24527a11e314e7dae">llvm::Sparc::fixup_sparc_h44</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da2ed85fcf7a68bb72867d54508fdfa214">llvm::Sparc::fixup_sparc_hh</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da178d40a3cdc113de1bc4814dd67a11bc">llvm::Sparc::fixup_sparc_hi22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da6be1cb6bff4acb2026f1107593c5bcc1">llvm::Sparc::fixup_sparc_hix22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502daf9431782a67249942ea90c9d7882ea18">llvm::Sparc::fixup_sparc_hm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502dabad234abccd9064339207fe71a70c7be">llvm::Sparc::fixup_sparc_l44</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da138cb8615551a89f2ced1e3a40669bdd">llvm::Sparc::fixup_sparc_lm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da02012bd04e669f47b0ca2c3ef4ec8df7">llvm::Sparc::fixup_sparc_lo10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da1665b86cbda5300143d0c72d38b18b55">llvm::Sparc::fixup_sparc_lox10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da284cdb6a9399209232aa3c13ca8d2618">llvm::Sparc::fixup_sparc_m44</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502dac6502cb4a88284870e35d967c53ac47f">llvm::Sparc::fixup_sparc_pc10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502daa00d9587c28c43679ea78179d779dd85">llvm::Sparc::fixup_sparc_pc22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da7de44a4f47d68e0bb21221b59fc64104">llvm::Sparc::fixup_sparc_tls_gd_add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da1cb655722f351a56ac2d2d20c6d3f21c">llvm::Sparc::fixup_sparc_tls_gd_call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da55d287c9fa6b9f05e7d86d910d08ef90">llvm::Sparc::fixup_sparc_tls_gd_hi22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da6fd27a363f32a384e19d57732da83400">llvm::Sparc::fixup_sparc_tls_gd_lo10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da81404b1c1698c400556d6db381d79b9b">llvm::Sparc::fixup_sparc_tls_ie_add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da28c137eeff3f5dc170642e5313acd883">llvm::Sparc::fixup_sparc_tls_ie_hi22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da0f86df663d98896b5c6d6d04f70b8f76">llvm::Sparc::fixup_sparc_tls_ie_ld</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502dafe9a137fc276c5872c10a68d18b6a1ee">llvm::Sparc::fixup_sparc_tls_ie_ldx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da98ce1ac1905989049a13fcc997c6800c">llvm::Sparc::fixup_sparc_tls_ie_lo10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da20876dd25f69286a4dc4c4550f06e11f">llvm::Sparc::fixup_sparc_tls_ldm_add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da944eebfbe22a2c847d37530c43b3c1f3">llvm::Sparc::fixup_sparc_tls_ldm_call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502daa416e524e88172a66fad9215c0aa87d2">llvm::Sparc::fixup_sparc_tls_ldm_hi22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da85b7e3dc16b048b452f479497746c819">llvm::Sparc::fixup_sparc_tls_ldm_lo10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da4fc6b4d7c79e1fb07e1c82aa851d2bb9">llvm::Sparc::fixup_sparc_tls_ldo_add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da4d435f58d4d1322c2d1db3f0ca19bdd6">llvm::Sparc::fixup_sparc_tls_ldo_hix22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da1fc5a8838faa83012242676700d3fbe9">llvm::Sparc::fixup_sparc_tls_ldo_lox10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da26c24bbb56bdfabcd601f3763e07888c">llvm::Sparc::fixup_sparc_tls_le_hix22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da401542a0ee1c7424a271c196e9b70de2">llvm::Sparc::fixup_sparc_tls_le_lox10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502dafa321c88b1e9bb39ab5b2e09b05fe7a6">llvm::Sparc::fixup_sparc_wplt30</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

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

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcasmbackend-cpp">SparcAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>.</p>

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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcasmbackend-cpp">SparcAsmBackend.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
