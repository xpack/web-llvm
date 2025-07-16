---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/veasmbackend-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `VEAsmBackend.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vefixupkinds-h">MCTargetDesc/VEFixupKinds.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemctargetdesc-h">MCTargetDesc/VEMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmbackend-h">llvm/MC/MCAsmBackend.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">llvm/MC/MCELFObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixupkindinfo-h">llvm/MC/MCFixupKindInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectwriter-h">llvm/MC/MCObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">llvm/MC/MCValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">llvm/Support/EndianStream.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-veasmbackend-cpp-">anonymous{VEAsmBackend.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-veasmbackend-cpp-/veasmbackend">VEAsmBackend</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-veasmbackend-cpp-/elfveasmbackend">ELFVEAsmBackend</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0721c6cb6a44a6f8b45d864844e3cce2">adjustFixupValue</a> (unsigned Kind, uint64_t Value)</td>
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


<div class="doxySectionDef">

## Functions

### adjustFixupValue() {#a0721c6cb6a44a6f8b45d864844e3cce2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t adjustFixupValue (unsigned Kind, uint64_t Value)</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/veasmbackend-cpp">VEAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa2ad67f23f486e531ca82d71890a68a01">llvm::VE::fixup_ve_got_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa5405339da89126a4026867f540e33441">llvm::VE::fixup_ve_got_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa401919b7d910ed497dbe04087ffb51c0">llvm::VE::fixup_ve_gotoff_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa8a34234c9b623e8c9c425c81be4cb62c">llvm::VE::fixup_ve_gotoff_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aaa5364c6e73ddba627ce657e4356d0b49">llvm::VE::fixup_ve_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa78d516c790863298415e6177345d5ff8">llvm::VE::fixup_ve_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa667f7a97724598853fb6d3cebb1e27d3">llvm::VE::fixup_ve_pc_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aaaf6751559269bc22d124be47cec2bdb2">llvm::VE::fixup_ve_pc_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aade9959851c0f191c677111084c14698f">llvm::VE::fixup_ve_plt_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa122241fcebbf6c6cef07b513c0191a7c">llvm::VE::fixup_ve_plt_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aaf3cea4fe606bf2531f03ca6576c51961">llvm::VE::fixup_ve_reflong</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa060875c5f3e38d17d606f502fa3e06c1">llvm::VE::fixup_ve_srel32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aafc47658a501eaa76ba863b76fadd9735">llvm::VE::fixup_ve_tls_gd_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aafa85f01d7cc2698698e63aa36c528204">llvm::VE::fixup_ve_tls_gd_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa0312ddb55e9fd7d4e1288f15f6ac4246">llvm::VE::fixup_ve_tpoff_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aac8d006c70ba7b24159949d6159dcf08c">llvm::VE::fixup_ve_tpoff_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58ac6095ed6f2c30887aef8adc449b1efa5">llvm::FK_PCRel_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a11803cd0814af72a9d078ac0f7a33137">llvm::FK_PCRel_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a0f7a8485c2c761bc5e870fe2b6466372">llvm::FK_PCRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a7fa4d5bb1573ffbf54e99ae1fe36ad6e">llvm::FK_PCRel_8</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

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

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/veasmbackend-cpp">VEAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa2ad67f23f486e531ca82d71890a68a01">llvm::VE::fixup_ve_got_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa5405339da89126a4026867f540e33441">llvm::VE::fixup_ve_got_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa401919b7d910ed497dbe04087ffb51c0">llvm::VE::fixup_ve_gotoff_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa8a34234c9b623e8c9c425c81be4cb62c">llvm::VE::fixup_ve_gotoff_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aaa5364c6e73ddba627ce657e4356d0b49">llvm::VE::fixup_ve_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa78d516c790863298415e6177345d5ff8">llvm::VE::fixup_ve_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa667f7a97724598853fb6d3cebb1e27d3">llvm::VE::fixup_ve_pc_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aaaf6751559269bc22d124be47cec2bdb2">llvm::VE::fixup_ve_pc_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aade9959851c0f191c677111084c14698f">llvm::VE::fixup_ve_plt_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa122241fcebbf6c6cef07b513c0191a7c">llvm::VE::fixup_ve_plt_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aaf3cea4fe606bf2531f03ca6576c51961">llvm::VE::fixup_ve_reflong</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa060875c5f3e38d17d606f502fa3e06c1">llvm::VE::fixup_ve_srel32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aafc47658a501eaa76ba863b76fadd9735">llvm::VE::fixup_ve_tls_gd_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aafa85f01d7cc2698698e63aa36c528204">llvm::VE::fixup_ve_tls_gd_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa0312ddb55e9fd7d4e1288f15f6ac4246">llvm::VE::fixup_ve_tpoff_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aac8d006c70ba7b24159949d6159dcf08c">llvm::VE::fixup_ve_tpoff_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58ac6095ed6f2c30887aef8adc449b1efa5">llvm::FK_PCRel_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a11803cd0814af72a9d078ac0f7a33137">llvm::FK_PCRel_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a0f7a8485c2c761bc5e870fe2b6466372">llvm::FK_PCRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a7fa4d5bb1573ffbf54e99ae1fe36ad6e">llvm::FK_PCRel_8</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
