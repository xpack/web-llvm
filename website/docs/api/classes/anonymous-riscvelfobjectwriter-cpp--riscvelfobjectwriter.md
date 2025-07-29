---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-riscvelfobjectwriter-cpp-/riscvelfobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RISCVELFObjectWriter` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{RISCVELFObjectWriter.cpp}::RISCVELFObjectWriter { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acabdeb8444e704a8b8ec0704048c4d0b">RISCVELFObjectWriter</a> (uint8_t OSABI, bool Is64Bit)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcf19380f13ac0a8db96fc7ed80516ff">~RISCVELFObjectWriter</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa711f6e9443cd8626d8797f22d1f34bc">needsRelocateWithSymbol</a> (const MCValue &amp;Val, const MCSymbol &amp;Sym, unsigned Type) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a292b37d2a3f3fb782daf79fed6123098">getRelocType</a> (MCContext &amp;Ctx, const MCValue &amp;Target, const MCFixup &amp;Fixup, bool IsPCRel) const override</td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvelfobjectwriter-cpp">RISCVELFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RISCVELFObjectWriter() {#acabdeb8444e704a8b8ec0704048c4d0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVELFObjectWriter::RISCVELFObjectWriter (uint8_t OSABI, bool Is64Bit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvelfobjectwriter-cpp">RISCVELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter/#ae6c6e76c9d8e0c912542fe4f8375e8ce">llvm::MCELFObjectTargetWriter::MCELFObjectTargetWriter</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RISCVELFObjectWriter() {#abcf19380f13ac0a8db96fc7ed80516ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVELFObjectWriter::~RISCVELFObjectWriter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvelfobjectwriter-cpp">RISCVELFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### needsRelocateWithSymbol() {#aa711f6e9443cd8626d8797f22d1f34bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVELFObjectWriter.cpp}::RISCVELFObjectWriter::needsRelocateWithSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Sym, unsigned Type)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvelfobjectwriter-cpp">RISCVELFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getRelocType() {#a292b37d2a3f3fb782daf79fed6123098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RISCVELFObjectWriter::getRelocType (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, bool IsPCRel)</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvelfobjectwriter-cpp">RISCVELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a63305955ac569a08596601f41364158c">llvm::RISCV::fixup_riscv_align</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ad266f94de8002bb828840b8f22972ea8">llvm::RISCV::fixup_riscv_branch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a88ebf98dfcb9792c5ff93e1aaeae2795">llvm::RISCV::fixup_riscv_call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a173779bb566468845e601a108fdd0ad4">llvm::RISCV::fixup_riscv_call_plt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a4ff796b91dfd8a1d885eed8bf90d7cf7">llvm::RISCV::fixup_riscv_got_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a1ebb3c0abab31295b4d2eb846560a7bb">llvm::RISCV::fixup_riscv_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149af5d53b8db9782487831bb12e66c9061c">llvm::RISCV::fixup_riscv_jal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a8a2e61994b3021df5ad535363254b705">llvm::RISCV::fixup_riscv_lo12_i</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ab67201b0aad523fe1a9cdcfa3996cd8a">llvm::RISCV::fixup_riscv_lo12_s</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ad37e08bb2772b97fd5c82cc64b92b8c9">llvm::RISCV::fixup_riscv_pcrel_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a25f04a3aac7dcd8105cd6199add50589">llvm::RISCV::fixup_riscv_pcrel_lo12_i</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a352fb7bc558f75c5d77993daf797ea1c">llvm::RISCV::fixup_riscv_pcrel_lo12_s</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a3a04590e7d054034a15f0c7c64180129">llvm::RISCV::fixup_riscv_relax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ad0ebbd5ab44960cdc83796e80006aaaa">llvm::RISCV::fixup_riscv_rvc_branch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a9f4ce31fb99c4613c6f173ce268f9725">llvm::RISCV::fixup_riscv_rvc_jump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a1dcfb88aadd66136c03e2620a6ff91dd">llvm::RISCV::fixup_riscv_tls_gd_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a13b9024d713be1b06a31431a40316038">llvm::RISCV::fixup_riscv_tls_got_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ada53b713dc586f277c29064f2f37204d">llvm::RISCV::fixup_riscv_tlsdesc_add_lo12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a2ea2f585dbae2849029cab18c49893fd">llvm::RISCV::fixup_riscv_tlsdesc_call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ac480fe24e2a9fc38e09382467a80c8e5">llvm::RISCV::fixup_riscv_tlsdesc_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a74ba417e94a716ab604d0ca6b34bb95c">llvm::RISCV::fixup_riscv_tlsdesc_load_lo12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a8a4b86f25fcb0c3c748f0e70066b9f7a">llvm::RISCV::fixup_riscv_tprel_add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a2f31aaf6d6645f72b9b48260e7297112">llvm::RISCV::fixup_riscv_tprel_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a649d0d8789e34184b131eec00e540e39">llvm::RISCV::fixup_riscv_tprel_lo12_i</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a0c02afb112894ac62bc5f4d4ce99f0ee">llvm::RISCV::fixup_riscv_tprel_lo12_s</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a0f7a8485c2c761bc5e870fe2b6466372">llvm::FK_PCRel_4</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#af5d6e67c11188675c1309e098afac194">llvm::MCExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">llvm::MCExpr::Target</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a2a25c9a7112bb84b5d93e6ab5d0d8185">llvm::MCSymbolRefExpr::VK_GOTPCREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab5951d4b3308f406e60e2bf743b14ca4">llvm::MCSymbolRefExpr::VK_PLT</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a604e28a9a3d857c263b22b49ba9b19f6">llvm::RISCVMCExpr::VK_RISCV_32_PCREL</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvelfobjectwriter-cpp">RISCVELFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
