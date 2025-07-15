---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `CSKYAsmBackend.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-h">CSKYAsmBackend.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-h">MCTargetDesc/CSKYMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">llvm/MC/MCAssembler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixupkindinfo-h">llvm/MC/MCFixupKindInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectwriter-h">llvm/MC/MCObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"csky-asmbackend"</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-cpp">CSKYAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a6d70355097ca3e247e1aedf88d6288d1">llvm::CSKY::fixup_csky_addr32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a5caa470fa9668e45540e67044ff14315">llvm::CSKY::fixup_csky_got32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2ac16105e6ed5d02c6d9664e008c649525">llvm::CSKY::fixup_csky_got_imm18_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a7189eb87f08082cd8e53fef4f48b83f1">llvm::CSKY::fixup_csky_gotoff</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a40093f3fe6bca907433c06cb5256cd15">llvm::CSKY::fixup_csky_gotpc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a36c5d2cff2efb3e83227a9dca61accc1">llvm::CSKY::fixup_csky_pcrel_imm10_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a536ed49406b71ec231209116d1459a92">llvm::CSKY::fixup_csky_pcrel_imm16_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a8548ad738cfd027c7759b8c2e0396c49">llvm::CSKY::fixup_csky_pcrel_imm18_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2aa11a4036cb9536c4ed8991e3fb2d126c">llvm::CSKY::fixup_csky_pcrel_imm26_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a8ebf6cafce7b2282b6db2e6b568518f5">llvm::CSKY::fixup_csky_pcrel_uimm16_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a4c2d802607ee153939c71f832414931c">llvm::CSKY::fixup_csky_pcrel_uimm7_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2ac3502715f5dd21573ae7085cdb2a7c3e">llvm::CSKY::fixup_csky_pcrel_uimm8_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2aa6060b29f15a989d994dd28029d887b7">llvm::CSKY::fixup_csky_plt32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2aa0247adcbb9af641dc8871d528adc437">llvm::CSKY::fixup_csky_plt_imm18_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad80b46c754cc7216244a866ec9b1cb0">llvm::isIntN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a995470163b6d76695cba5bc8dfb529">llvm::isUIntN</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"csky-asmbackend"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-cpp">CSKYAsmBackend.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
