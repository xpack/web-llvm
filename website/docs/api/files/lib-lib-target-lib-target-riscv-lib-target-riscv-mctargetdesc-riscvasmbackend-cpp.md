---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `RISCVAsmBackend.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">RISCVMCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">llvm/MC/MCAssembler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">llvm/MC/MCELFObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectwriter-h">llvm/MC/MCObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">llvm/MC/MCSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">llvm/MC/MCValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">llvm/Support/EndianStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/leb128-h">llvm/Support/LEB128.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "llvm/BinaryFormat/ELFRelocs/RISCV.def"
#include "llvm/BinaryFormat/ELFRelocs/RISCV_nonstandard.def"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab33289282719ea97ec8e54acbee45fbe">adjustFixupValue</a> (const MCFixup &amp;Fixup, uint64_t Value, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85cbc0c468227bf768eebe0a12b1525c">RelaxBranches</a>("riscv-asm-relax-branches", cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af76701b8fc911801230dde550cce7c33">ULEB128Reloc</a>("riscv-uleb128-reloc", cl::init(true), cl::Hidden, cl::desc("Emit R_RISCV_SET_ULEB128/E_RISCV_SUB_ULEB128 if appropriate"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe49e3813dd2affe2c0bc88e3be501b8">ELF_RELOC</a>(NAME, ID)&nbsp;&nbsp;&nbsp;.Case(#NAME, ID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5a684f2df878100a372681a34c13e7f">ELF_RISCV_NONSTANDARD_RELOC</a>(_VENDOR, NAME, ID)&nbsp;&nbsp;&nbsp;.Case(#NAME, ID)</td>
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

### adjustFixupValue() {#ab33289282719ea97ec8e54acbee45fbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t adjustFixupValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, uint64_t Value, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a21852a2668ad26c40c78267682662908">llvm::RISCV::fixup_riscv_12_i</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ad266f94de8002bb828840b8f22972ea8">llvm::RISCV::fixup_riscv_branch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a88ebf98dfcb9792c5ff93e1aaeae2795">llvm::RISCV::fixup_riscv_call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a173779bb566468845e601a108fdd0ad4">llvm::RISCV::fixup_riscv_call_plt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a4ff796b91dfd8a1d885eed8bf90d7cf7">llvm::RISCV::fixup_riscv_got_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a1ebb3c0abab31295b4d2eb846560a7bb">llvm::RISCV::fixup_riscv_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149af5d53b8db9782487831bb12e66c9061c">llvm::RISCV::fixup_riscv_jal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a8a2e61994b3021df5ad535363254b705">llvm::RISCV::fixup_riscv_lo12_i</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ab67201b0aad523fe1a9cdcfa3996cd8a">llvm::RISCV::fixup_riscv_lo12_s</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ad37e08bb2772b97fd5c82cc64b92b8c9">llvm::RISCV::fixup_riscv_pcrel_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a25f04a3aac7dcd8105cd6199add50589">llvm::RISCV::fixup_riscv_pcrel_lo12_i</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a352fb7bc558f75c5d77993daf797ea1c">llvm::RISCV::fixup_riscv_pcrel_lo12_s</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ad0ebbd5ab44960cdc83796e80006aaaa">llvm::RISCV::fixup_riscv_rvc_branch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a9f4ce31fb99c4613c6f173ce268f9725">llvm::RISCV::fixup_riscv_rvc_jump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a1dcfb88aadd66136c03e2620a6ff91dd">llvm::RISCV::fixup_riscv_tls_gd_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a13b9024d713be1b06a31431a40316038">llvm::RISCV::fixup_riscv_tls_got_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ac480fe24e2a9fc38e09382467a80c8e5">llvm::RISCV::fixup_riscv_tlsdesc_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a74ba417e94a716ab604d0ca6b34bb95c">llvm::RISCV::fixup_riscv_tlsdesc_load_lo12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a2f31aaf6d6645f72b9b48260e7297112">llvm::RISCV::fixup_riscv_tprel_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a649d0d8789e34184b131eec00e540e39">llvm::RISCV::fixup_riscv_tprel_lo12_i</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a0c02afb112894ac62bc5f4d4ce99f0ee">llvm::RISCV::fixup_riscv_tprel_lo12_s</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58ad273f7fe2962a053becd88767fee3b0d">llvm::FK_Data_leb128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### RelaxBranches {#a85cbc0c468227bf768eebe0a12b1525c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; RelaxBranches("riscv-asm-relax-branches", cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a67f770e0c7076b7fc767f1aee60edcd3">llvm::RISCVAsmBackend::fixupNeedsRelaxationAdvanced</a>.</p>

</div>
</div>

### ULEB128Reloc {#af76701b8fc911801230dde550cce7c33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ULEB128Reloc("riscv-uleb128-reloc", cl::init(true), cl::Hidden, cl::desc("Emit R_RISCV_SET_ULEB128/E_RISCV_SUB_ULEB128 if appropriate"))</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a0b10511c4a52fc282850610c648ba455">llvm::RISCVAsmBackend::relaxLEB128</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ELF\_RELOC {#afe49e3813dd2affe2c0bc88e3be501b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ELF_RELOC(NAME, ID)&nbsp;&nbsp;&nbsp;.Case(#NAME, ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>

</div>
</div>

### ELF\_RISCV\_NONSTANDARD\_RELOC {#ae5a684f2df878100a372681a34c13e7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ELF_RISCV_NONSTANDARD_RELOC(_VENDOR, NAME, ID)&nbsp;&nbsp;&nbsp;.Case(#NAME, ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
