---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-aarch64elfobjectwriter-cpp-/aarch64elfobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AArch64ELFObjectWriter` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{AArch64ELFObjectWriter.cpp}::AArch64ELFObjectWriter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter">MCELFObjectTargetWriter</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c264e897c2ed126d553e7240ef474b4">AArch64ELFObjectWriter</a> (uint8_t OSABI, bool IsILP32)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08f97f63455a07245e3ab6f6fb70ba4b">~AArch64ELFObjectWriter</a> () override=default</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85d0607dba50e8b55a836f53bc8184ca">getRelocType</a> (MCContext &amp;Ctx, const MCValue &amp;Target, const MCFixup &amp;Fixup, bool IsPCRel) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab26b820ccb3610a404a7a77cf1816ea3">needsRelocateWithSymbol</a> (const MCValue &amp;Val, const MCSymbol &amp;Sym, unsigned Type) const override</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a706f1e63a4b3079135a11120096cbcbc">IsILP32</a></td>
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


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfobjectwriter-cpp">AArch64ELFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AArch64ELFObjectWriter() {#a8c264e897c2ed126d553e7240ef474b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64ELFObjectWriter::AArch64ELFObjectWriter (uint8_t OSABI, bool IsILP32)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfobjectwriter-cpp">AArch64ELFObjectWriter.cpp</a>.</p>


<p>References <a href="#a706f1e63a4b3079135a11120096cbcbc">IsILP32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter/#ae6c6e76c9d8e0c912542fe4f8375e8ce">llvm::MCELFObjectTargetWriter::MCELFObjectTargetWriter</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AArch64ELFObjectWriter() {#a08f97f63455a07245e3ab6f6fb70ba4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64ELFObjectWriter.cpp}::AArch64ELFObjectWriter::~AArch64ELFObjectWriter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfobjectwriter-cpp">AArch64ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="#a85d0607dba50e8b55a836f53bc8184ca">getRelocType</a> and <a href="#ab26b820ccb3610a404a7a77cf1816ea3">needsRelocateWithSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getRelocType() {#a85d0607dba50e8b55a836f53bc8184ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AArch64ELFObjectWriter::getRelocType (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, bool IsPCRel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfobjectwriter-cpp">AArch64ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9ad535858a360e48fa51bd9c5ac0956162">llvm::AArch64::fixup_aarch64_add_imm12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9a99cefa5f52a371b91390c527f4648722">llvm::AArch64::fixup_aarch64_ldr_pcrel_imm19</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9ae794060e936aea9d09bdd85bb99dcf80">llvm::AArch64::fixup_aarch64_ldst_imm12_scale1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9ac2e74dcdf3c97291d6ce9fc8032d2e4f">llvm::AArch64::fixup_aarch64_ldst_imm12_scale16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9aa7eca8a3014a1980664443a7d07edec5">llvm::AArch64::fixup_aarch64_ldst_imm12_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9a1d9670f8c96a7890ee1396fc8596e5a4">llvm::AArch64::fixup_aarch64_ldst_imm12_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9adaa9de7bb7ea352fc17fcb5adec2a9f5">llvm::AArch64::fixup_aarch64_ldst_imm12_scale8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9a3e0254041247fb97318a3da8d0f489c6">llvm::AArch64::fixup_aarch64_movw</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9a9a9d665cbb724cea9ad2aae20668e464">llvm::AArch64::fixup_aarch64_pcrel_adr_imm21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9ad31b24bfe1fb4471f899fbfa37d240f7">llvm::AArch64::fixup_aarch64_pcrel_adrp_imm21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9a9cfa836f3def950d2b4a9cc69a5de67c">llvm::AArch64::fixup_aarch64_pcrel_branch14</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9a16eddc85596422ff5b09f44bd6ab5ae7">llvm::AArch64::fixup_aarch64_pcrel_branch16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9a87e08dcaf47dcab2f388f1d348002f3f">llvm::AArch64::fixup_aarch64_pcrel_branch19</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9a74a32a0e3d43c7e6b0ef010ebffa5f23">llvm::AArch64::fixup_aarch64_pcrel_branch26</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9a064b38da087b4f1840e307c3bb675470">llvm::AArch64::fixup_aarch64_pcrel_branch9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9a572647824895bc24ec60e6ed94fc2b05">llvm::AArch64::fixup_aarch64_pcrel_call26</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#a7dfd432f33b5e5ff4114b9be04a2b25f">llvm::AArch64MCExpr::getAddressFrag</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#a07e3d0ae8a67b027d48dbb2a51ed6e9a">llvm::AArch64MCExpr::getSymbolLoc</a>, <a href="#a706f1e63a4b3079135a11120096cbcbc">IsILP32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfobjectwriter-cpp/#af654489f3ea4efd14082ffe899b1ce58">isNonILP32reloc</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#a5a2b5e4ba4c1ccd001580fc8181e52eb">llvm::AArch64MCExpr::isNotChecked</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfobjectwriter-cpp/#aa68decaf355a8c4c7889f4368e67ecf7">R_CLS</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa873476895e81395d69f2a8a5e9f298cf">llvm::AArch64MCExpr::VK_ABS</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa35474485d868b25489fc57669a9c27f9">llvm::AArch64MCExpr::VK_ABS_G0</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa65e6d1b5482060081af43ab78352964d">llvm::AArch64MCExpr::VK_ABS_G0_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa7eb9497609b61ca20e383022f9ab3290">llvm::AArch64MCExpr::VK_ABS_G0_S</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfae40f238af3f6fe589641a720ab4f97a8">llvm::AArch64MCExpr::VK_ABS_G1</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa1f931e50ae5f4c5f77e050447b2e3320">llvm::AArch64MCExpr::VK_ABS_G1_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa53f60806897246321227204c69d467c3">llvm::AArch64MCExpr::VK_ABS_G1_S</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa284689a52a5f79b95b051a057c54fb1e">llvm::AArch64MCExpr::VK_ABS_G2</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa1089df68239d0e46c2fba2190c4c0eb8">llvm::AArch64MCExpr::VK_ABS_G2_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa536c18c873600b1e2aba9d9f894e9213">llvm::AArch64MCExpr::VK_ABS_G2_S</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa963191759d19cf8d90bc0c40435c8cb8">llvm::AArch64MCExpr::VK_ABS_G3</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa0121933247ec3c2a0477b4e9142fcdc9">llvm::AArch64MCExpr::VK_AUTH</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfaa8bd8587ab7bb2c4e6db67d515b0d83e">llvm::AArch64MCExpr::VK_AUTHADDR</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa261e5fdfac362b9c39961c5226dbfccf">llvm::AArch64MCExpr::VK_DTPREL</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa752f95c69e8b43369d83833adb099345">llvm::AArch64MCExpr::VK_DTPREL_G0</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfab73ae607357b58d9d3de5256d5558284">llvm::AArch64MCExpr::VK_DTPREL_G0_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa1ea6131fa4bc346a2285f73b1e3b2b88">llvm::AArch64MCExpr::VK_DTPREL_G1</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa1ea81fd8999cf2538b39f1e012f4a9cc">llvm::AArch64MCExpr::VK_DTPREL_G1_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa8f5d53560d98ded247f3bc911c00260d">llvm::AArch64MCExpr::VK_DTPREL_G2</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfad1e341aea3471c4a8356b69bfad7a772">llvm::AArch64MCExpr::VK_DTPREL_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfae976f5dddffeb8a77e5ecc471343842d">llvm::AArch64MCExpr::VK_DTPREL_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa690cf2259632dd195b29cb7ad0cd16b7">llvm::AArch64MCExpr::VK_DTPREL_LO12_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa96518ec6ca1da559ff4a909126b88060">llvm::AArch64MCExpr::VK_GOT</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa9ec4c589014eb66893073ac3083a2670">llvm::AArch64MCExpr::VK_GOT_AUTH</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa2f76c31f5c93ff69cd59e817abd85223">llvm::AArch64MCExpr::VK_GOT_AUTH_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a2a25c9a7112bb84b5d93e6ab5d0d8185">llvm::MCSymbolRefExpr::VK_GOTPCREL</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa6b76c48acac537ea0f3accd4f946b223">llvm::AArch64MCExpr::VK_GOTTPREL</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa9c3e5cca2bdd09fc0ecb532f2c5d7e45">llvm::AArch64MCExpr::VK_GOTTPREL_G0_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa818d75cf614986328128098bb46084ed">llvm::AArch64MCExpr::VK_GOTTPREL_G1</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa8456ae950bf4e253ace9693cd8635c80">llvm::AArch64MCExpr::VK_LO15</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab5951d4b3308f406e60e2bf743b14ca4">llvm::MCSymbolRefExpr::VK_PLT</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa8f3aaf6805e534003f15c7e878acdf32">llvm::AArch64MCExpr::VK_PREL_G0</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfab793dd2a7b912aeaae778108094a5689">llvm::AArch64MCExpr::VK_PREL_G0_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfab0d49b0ffa4753b61465eb29942f838c">llvm::AArch64MCExpr::VK_PREL_G1</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfadf42ca6f959ddac98d35254c0914af09">llvm::AArch64MCExpr::VK_PREL_G1_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfae308678726c12af491f9647e76f3f1b9">llvm::AArch64MCExpr::VK_PREL_G2</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa432b91e82080f70cff564bc1f0db2b17">llvm::AArch64MCExpr::VK_PREL_G2_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa9a4ed17656f61247e51858d2f8d9203d">llvm::AArch64MCExpr::VK_PREL_G3</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfaa1193d791c0127a6f7a86565a3f460bd">llvm::AArch64MCExpr::VK_TLSDESC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa32da9cfae143cc7c95c2e0f54ca40bcc">llvm::AArch64MCExpr::VK_TLSDESC_AUTH</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfacf90d92f6c5b8b5972b2631c72eb5dde">llvm::AArch64MCExpr::VK_TLSDESC_AUTH_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfae86e7fb84bad4ed1be1f5772229a8d58">llvm::AArch64MCExpr::VK_TLSDESC_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfaa3020e9ba5dfa0324318faad507a0a58">llvm::AArch64MCExpr::VK_TPREL</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfaeb8c93fb135d2775c869861178d11807">llvm::AArch64MCExpr::VK_TPREL_G0</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa6e1d58609fc75b55166830312b91d2df">llvm::AArch64MCExpr::VK_TPREL_G0_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa5027a58d31c5e57b7483970eaf6cd602">llvm::AArch64MCExpr::VK_TPREL_G1</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa11bfd951d2f6ec25329b879f8d428fa9">llvm::AArch64MCExpr::VK_TPREL_G1_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa4b1b25eea13543bbbe0d904a4776d430">llvm::AArch64MCExpr::VK_TPREL_G2</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa65b0bb155666aed0ad6a4a61dc4f76b6">llvm::AArch64MCExpr::VK_TPREL_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa69a04395c63763644a14a6a929075fb0">llvm::AArch64MCExpr::VK_TPREL_LO12</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfaa2d3ca49c7f86aedb741b49d223fce16">llvm::AArch64MCExpr::VK_TPREL_LO12_NC</a>.</p>


<p>Referenced by <a href="#a08f97f63455a07245e3ab6f6fb70ba4b">~AArch64ELFObjectWriter</a>.</p>

</div>
</div>

### needsRelocateWithSymbol() {#ab26b820ccb3610a404a7a77cf1816ea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64ELFObjectWriter::needsRelocateWithSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Sym, unsigned Type)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfobjectwriter-cpp">AArch64ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a48eebfa5f9f069075bc6412fd4371c7b">llvm::MCValue::getRefKind</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa96518ec6ca1da559ff4a909126b88060">llvm::AArch64MCExpr::VK_GOT</a>.</p>


<p>Referenced by <a href="#a08f97f63455a07245e3ab6f6fb70ba4b">~AArch64ELFObjectWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### IsILP32 {#a706f1e63a4b3079135a11120096cbcbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64ELFObjectWriter.cpp}::AArch64ELFObjectWriter::IsILP32</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfobjectwriter-cpp">AArch64ELFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#a8c264e897c2ed126d553e7240ef474b4">AArch64ELFObjectWriter</a> and <a href="#a85d0607dba50e8b55a836f53bc8184ca">getRelocType</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfobjectwriter-cpp">AArch64ELFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
