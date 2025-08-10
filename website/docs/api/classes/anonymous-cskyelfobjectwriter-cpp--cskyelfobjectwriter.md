---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-cskyelfobjectwriter-cpp-/cskyelfobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CSKYELFObjectWriter` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{CSKYELFObjectWriter.cpp}::CSKYELFObjectWriter { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac36af2b9b75f5c30a0885f97b4043e7d">CSKYELFObjectWriter</a> (uint8_t OSABI=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad164476015d5b05cbf5d959fcc52fdee">~CSKYELFObjectWriter</a> ()</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcfdb6cf22cdaa14533e19d6c71d71a1">getRelocType</a> (MCContext &amp;Ctx, const MCValue &amp;Target, const MCFixup &amp;Fixup, bool IsPCRel) const override</td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyelfobjectwriter-cpp">CSKYELFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CSKYELFObjectWriter() {#ac36af2b9b75f5c30a0885f97b4043e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CSKYELFObjectWriter.cpp}::CSKYELFObjectWriter::CSKYELFObjectWriter (uint8_t OSABI=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyelfobjectwriter-cpp">CSKYELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter/#ae6c6e76c9d8e0c912542fe4f8375e8ce">llvm::MCELFObjectTargetWriter::MCELFObjectTargetWriter</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CSKYELFObjectWriter() {#ad164476015d5b05cbf5d959fcc52fdee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CSKYELFObjectWriter.cpp}::CSKYELFObjectWriter::~CSKYELFObjectWriter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyelfobjectwriter-cpp">CSKYELFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRelocType() {#adcfdb6cf22cdaa14533e19d6c71d71a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned CSKYELFObjectWriter::getRelocType (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, bool IsPCRel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyelfobjectwriter-cpp">CSKYELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a6d70355097ca3e247e1aedf88d6288d1">llvm::CSKY::fixup_csky_addr32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2ad1bf76d360185c7b047a69ac3ca47a31">llvm::CSKY::fixup_csky_addr_hi16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2af2da376d6904e5f37e2f389dc295810d">llvm::CSKY::fixup_csky_addr_lo16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2afdb8ccea389463c5c685e028b9f94726">llvm::CSKY::fixup_csky_doffset_imm18</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a5302f6fa84a724caf5ad8cdf6569d8c7">llvm::CSKY::fixup_csky_doffset_imm18_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a854b6d429bc64a8468194537a6f06e5f">llvm::CSKY::fixup_csky_doffset_imm18_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2ac16105e6ed5d02c6d9664e008c649525">llvm::CSKY::fixup_csky_got_imm18_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a36c5d2cff2efb3e83227a9dca61accc1">llvm::CSKY::fixup_csky_pcrel_imm10_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a536ed49406b71ec231209116d1459a92">llvm::CSKY::fixup_csky_pcrel_imm16_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a8548ad738cfd027c7759b8c2e0396c49">llvm::CSKY::fixup_csky_pcrel_imm18_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2aa11a4036cb9536c4ed8991e3fb2d126c">llvm::CSKY::fixup_csky_pcrel_imm26_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a8ebf6cafce7b2282b6db2e6b568518f5">llvm::CSKY::fixup_csky_pcrel_uimm16_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a4c2d802607ee153939c71f832414931c">llvm::CSKY::fixup_csky_pcrel_uimm7_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2ac3502715f5dd21573ae7085cdb2a7c3e">llvm::CSKY::fixup_csky_pcrel_uimm8_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2aa0247adcbb9af641dc8871d528adc437">llvm::CSKY::fixup_csky_plt_imm18_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a0f7a8485c2c761bc5e870fe2b6466372">llvm::FK_PCRel_4</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#af5d6e67c11188675c1309e098afac194">llvm::MCExpr::getKind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">llvm::MCExpr::Target</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56da00b43daca1c50769fde2954c18a6a08d">llvm::CSKYMCExpr::VK_CSKY_ADDR</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56da6f6264903a5cd681bef075a10d80830c">llvm::CSKYMCExpr::VK_CSKY_GOT</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56da459851e1e27ad13079a564826c441637">llvm::CSKYMCExpr::VK_CSKY_GOTOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56dab1b698cbe7df1349a4dd7b50bc879c59">llvm::CSKYMCExpr::VK_CSKY_GOTPC</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56da9651ea71fd4490018e90fc7093c586b4">llvm::CSKYMCExpr::VK_CSKY_None</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56da69348b1cbd18fce5aff9db7f91d273b9">llvm::CSKYMCExpr::VK_CSKY_PLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56da62b16a80d6774adcf5795e1f444f8481">llvm::CSKYMCExpr::VK_CSKY_TLSGD</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56da40d2178a63dd0ff09242ab5496938e95">llvm::CSKYMCExpr::VK_CSKY_TLSIE</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56da6bb8f22442c3370bcba69b73a07fdc21">llvm::CSKYMCExpr::VK_CSKY_TLSLDM</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56dafea681928cdde2355e1b87f6ed63761b">llvm::CSKYMCExpr::VK_CSKY_TLSLDO</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a93a07cb47b5fa9cdb2cc05126cd3d56da63f14a876cfe0a7d880dfcf341584a30">llvm::CSKYMCExpr::VK_CSKY_TLSLE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa780672c4378b10a1ef6094a4c46de10">llvm::MCSymbolRefExpr::VK_GOT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a4396d69feb19b053f335f9baa4fb9b62">llvm::MCSymbolRefExpr::VK_GOTOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab5951d4b3308f406e60e2bf743b14ca4">llvm::MCSymbolRefExpr::VK_PLT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab2e079373e7edad956ec4feb0587658e">llvm::MCSymbolRefExpr::VK_TLSGD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a3edde5344c6385f99e6b4f7606b79048">llvm::MCSymbolRefExpr::VK_TLSLDM</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aab276e610bb8711df7b2a9565411b2f3">llvm::MCSymbolRefExpr::VK_TPOFF</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyelfobjectwriter-cpp">CSKYELFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
