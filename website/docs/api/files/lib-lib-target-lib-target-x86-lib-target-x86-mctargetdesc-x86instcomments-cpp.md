---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `X86InstComments.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-h">X86InstComments.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-h">X86MCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86shuffledecode-h">X86ShuffleDecode.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrinfo-h">llvm/MC/MCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;string_view&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a185fac36097d2118ff0b494a0e6bb560">getVectorRegSize</a> (MCRegister Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cc75bf85d2d87e28c8366a766af3384">getRegOperandNumElts</a> (const MCInst *MI, unsigned ScalarSize, unsigned OperandIndex)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a894b4b25e2718aa162dc7675f5208912">getRegName</a> (MCRegister Reg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f75a161bbbea8de9bcffc8b6e294999">printMasking</a> (raw_ostream &amp;OS, const MCInst *MI, const MCInstrInfo &amp;MCII)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wraps the destination register name with AVX512 mask/maskz filtering. <a href="#a9f75a161bbbea8de9bcffc8b6e294999">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31b5b051ab96b75f4c104393b46b2f23">printFMAComments</a> (const MCInst *MI, raw_ostream &amp;OS, const MCInstrInfo &amp;MCII)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e448dfe33579cc1d0f660ba3219e900">printPTERNLOGComments</a> (const MCInst *MI, raw_ostream &amp;OS, const MCInstrInfo &amp;MCII)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8342adc3c89ccc8144d0db19a3485efd">printFPCLASSComments</a> (const MCInst *MI, raw_ostream &amp;OS, const MCInstrInfo &amp;MCII)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76b799643733c8e5f3b3c9537cec7fad">TernlogFunctions</a>[]</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a785793e2fb27e61530b7ecc7908f7e5e">CASE_SSE_INS_COMMON</a>(Inst, src)&nbsp;&nbsp;&nbsp;  case X86::Inst##src:</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, Suffix, src)&nbsp;&nbsp;&nbsp;  case X86::V##Inst##Suffix##src:</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(Inst, Suffix, src)&nbsp;&nbsp;&nbsp;  case X86::V##Inst##Suffix##src##k:</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(Inst, Suffix, src)&nbsp;&nbsp;&nbsp;  case X86::V##Inst##Suffix##src##kz:</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Suffix, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aada100dbe50383c5dace2d490150f1fe">CASE_MASK_INS_COMMON_INT</a>(Inst, Suffix, src)&nbsp;&nbsp;&nbsp;  case X86::V##Inst##Suffix##src##k_Int:</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ba15344103b1968cd6ed19283f105c9">CASE_MASKZ_INS_COMMON_INT</a>(Inst, Suffix, src)&nbsp;&nbsp;&nbsp;  case X86::V##Inst##Suffix##src##kz_Int:</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a091e509dfb1ce815bc745f5a4049652e">CASE_AVX512_INS_COMMON_INT</a>(Inst, Suffix, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f84bba1bde3b706ecc952a068974161">CASE_FPCLASS_PACKED</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ae70b284a661a2e082271923f476275">CASE_FPCLASS_PACKED_MEM</a>(Inst)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ff59dc78e00faddbecceb84ee3a7a5b">CASE_FPCLASS_SCALAR</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae93027cb9e673996c5b59d1bec7b1515">CASE_PTERNLOG</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47f32ffe68f1de3823cf76bab7557ea5">CASE_MOVDUP</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86a2b2a2b3f60b3eb1751a72dc2ea9c8">CASE_MASK_MOVDUP</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b32bc14e30b0a707371b8fc898c1311">CASE_MASKZ_MOVDUP</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92ace5d9d597bf35c6dcc000918e536f">CASE_PMOVZX</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af11c7684124a6ac3f7a6a46e229a954e">CASE_UNPCK</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a239f4e5621f2f5ab2fde61f576faaae8">CASE_MASK_UNPCK</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6be3fdfbc8e235972bf208b07817cea">CASE_MASKZ_UNPCK</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3adcd87f29de24c9eca58da035f75aec">CASE_SHUF</a>(Inst, suf)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8bf57a8bc5047ad6b0e93048f581685">CASE_MASK_SHUF</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae0d0f204552b016e1a0e196bbd56e2e">CASE_MASKZ_SHUF</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e852686f152f3ea28364c69a7ccc4d0">CASE_VPERMILPI</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9f3023a541c42b179b7d80b305e077d">CASE_MASK_VPERMILPI</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c99738570e7f28e1ade6e4226ea2adc">CASE_MASKZ_VPERMILPI</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a026d1658223e2a87d44670cac6c589c7">CASE_VPERM</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9417c5903615abb5ee4ae91393de85ec">CASE_MASK_VPERM</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e1365175259605547fe86dcc79e6952">CASE_MASKZ_VPERM</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a958ac7903dbb1c40a8eb5e69e7383e1e">CASE_VSHUF</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a290c67a0bb79b8b91c51f9951200b68a">CASE_MASK_VSHUF</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20b7a2c2e9b30d04773297076618e97a">CASE_MASKZ_VSHUF</a>(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27da674002083f9945965bd3ad8f2802">CASE_AVX512_FMA</a>(Inst, suf)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dc9b77edfc8ffb118085a28e0101ff8">CASE_FMA</a>(Inst, suf)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2169960f68eddcb8175287ed2e03dfe">CASE_FMA_PACKED_REG</a>(Inst)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b18ad8dbf9cbe7e533ab21e0339c29d">CASE_FMA_PACKED_MEM</a>(Inst)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c1793c6fb71a76f788ff0910ac0cec4">CASE_FMA_SCALAR_REG</a>(Inst)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e3b0f016236136709b5d6beb85406c5">CASE_FMA_SCALAR_MEM</a>(Inst)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44ea190375317bcc275497d62b88750f">CASE_FMA4</a>(Inst, suf)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9bdf477702a8738fd71da1e53d8160a">CASE_FMA4_PACKED_RR</a>(Inst)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41feee8092a0453eab558b3560f944f4">CASE_FMA4_PACKED_RM</a>(Inst)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a705455ef613dba5bdde8ffd7f33e2b40">CASE_FMA4_PACKED_MR</a>(Inst)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f35d58affa1b01628899682fd42a07d">CASE_FMA4_SCALAR_RR</a>(Inst)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8b6c2d7862bb8dbe06c41f51406565e">CASE_FMA4_SCALAR_RM</a>(Inst)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aed4935df28385f1474429f4f785799">CASE_FMA4_SCALAR_MR</a>(Inst)&nbsp;&nbsp;&nbsp;...</td>
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

### getRegName() {#a894b4b25e2718aa162dc7675f5208912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getRegName (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a124a43d72f8680a64fdd7132d29b1775">llvm::X86ATTInstPrinter::getRegisterName</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0303c1c5d962299e9e554c11e5400b19">llvm::EmitAnyX86InstComments</a>, <a href="#a31b5b051ab96b75f4c104393b46b2f23">printFMAComments</a>, <a href="#a8342adc3c89ccc8144d0db19a3485efd">printFPCLASSComments</a>, <a href="#a9f75a161bbbea8de9bcffc8b6e294999">printMasking</a> and <a href="#a0e448dfe33579cc1d0f660ba3219e900">printPTERNLOGComments</a>.</p>

</div>
</div>

### getRegOperandNumElts() {#a5cc75bf85d2d87e28c8366a766af3384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getRegOperandNumElts (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned ScalarSize, unsigned OperandIndex)</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>References <a href="#a185fac36097d2118ff0b494a0e6bb560">getVectorRegSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0303c1c5d962299e9e554c11e5400b19">llvm::EmitAnyX86InstComments</a>.</p>

</div>
</div>

### getVectorRegSize() {#a185fac36097d2118ff0b494a0e6bb560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getVectorRegSize (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#aa9fd738474c4c822202e6d73a9509904">llvm::X86II::isXMMReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#acc7da017f8afea15479e578fcc10a2e2">llvm::X86II::isYMMReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a301d6276fae739378e945ebbe0c8dd9b">llvm::X86II::isZMMReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#a5cc75bf85d2d87e28c8366a766af3384">getRegOperandNumElts</a>.</p>

</div>
</div>

### printFMAComments() {#a31b5b051ab96b75f4c104393b46b2f23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool printFMAComments (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII)</td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>References <a href="#a705455ef613dba5bdde8ffd7f33e2b40">CASE_FMA4_PACKED_MR</a>, <a href="#a41feee8092a0453eab558b3560f944f4">CASE_FMA4_PACKED_RM</a>, <a href="#ac9bdf477702a8738fd71da1e53d8160a">CASE_FMA4_PACKED_RR</a>, <a href="#a2aed4935df28385f1474429f4f785799">CASE_FMA4_SCALAR_MR</a>, <a href="#aa8b6c2d7862bb8dbe06c41f51406565e">CASE_FMA4_SCALAR_RM</a>, <a href="#a4f35d58affa1b01628899682fd42a07d">CASE_FMA4_SCALAR_RR</a>, <a href="#a9b18ad8dbf9cbe7e533ab21e0339c29d">CASE_FMA_PACKED_MEM</a>, <a href="#ae2169960f68eddcb8175287ed2e03dfe">CASE_FMA_PACKED_REG</a>, <a href="#a4e3b0f016236136709b5d6beb85406c5">CASE_FMA_SCALAR_MEM</a>, <a href="#a0c1793c6fb71a76f788ff0910ac0cec4">CASE_FMA_SCALAR_REG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a074efa948b2b878d89eed41dbc6b7d02a3765a3e5b572f57e131a5eb88c0d4722">llvm::FMSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a788ace9bfafe2db73b33d1f4301ce081a3fa37ac5f5d303429c55b37d11a86190">llvm::FNMADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a074efa948b2b878d89eed41dbc6b7d02a837b9b047b8d6dc7148a6a8882fb3e48">llvm::FNMSUB</a>, <a href="#a894b4b25e2718aa162dc7675f5208912">getRegName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9f75a161bbbea8de9bcffc8b6e294999">printMasking</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0303c1c5d962299e9e554c11e5400b19">llvm::EmitAnyX86InstComments</a>.</p>

</div>
</div>

### printFPCLASSComments() {#a8342adc3c89ccc8144d0db19a3485efd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool printFPCLASSComments (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII)</td>
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



<p>Definition at line 977 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>References <a href="#a0f84bba1bde3b706ecc952a068974161">CASE_FPCLASS_PACKED</a>, <a href="#a0ae70b284a661a2e082271923f476275">CASE_FPCLASS_PACKED_MEM</a>, <a href="#a9ff59dc78e00faddbecceb84ee3a7a5b">CASE_FPCLASS_SCALAR</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a894b4b25e2718aa162dc7675f5208912">getRegName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9f75a161bbbea8de9bcffc8b6e294999">printMasking</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0303c1c5d962299e9e554c11e5400b19">llvm::EmitAnyX86InstComments</a>.</p>

</div>
</div>

### printMasking() {#a9f75a161bbbea8de9bcffc8b6e294999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printMasking (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII)</td>
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

<p>Wraps the destination register name with AVX512 mask/maskz filtering.</p>

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eabe6298d9ba729db7fa5c2149de1b21ed">llvm::X86II::EVEX_K</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea11f2ede3e2eee190e2ff483d2e28c8c8">llvm::X86II::EVEX_Z</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#a176ca2c9108a997dcfd8aadf4c0f0fa0">llvm::MCInstrInfo::get</a>, <a href="#a894b4b25e2718aa162dc7675f5208912">getRegName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#aaa8eb58fd1b8466eb64a43df890cb8c1ae01b27a05209c02ca1bdb5a6033731fb">llvm::MCOI::TIED_TO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0303c1c5d962299e9e554c11e5400b19">llvm::EmitAnyX86InstComments</a>, <a href="#a31b5b051ab96b75f4c104393b46b2f23">printFMAComments</a>, <a href="#a8342adc3c89ccc8144d0db19a3485efd">printFPCLASSComments</a> and <a href="#a0e448dfe33579cc1d0f660ba3219e900">printPTERNLOGComments</a>.</p>

</div>
</div>

### printPTERNLOGComments() {#a0e448dfe33579cc1d0f660ba3219e900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool printPTERNLOGComments (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII)</td>
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



<p>Definition at line 915 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>References <a href="#ae93027cb9e673996c5b59d1bec7b1515">CASE_PTERNLOG</a>, <a href="#a894b4b25e2718aa162dc7675f5208912">getRegName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9f75a161bbbea8de9bcffc8b6e294999">printMasking</a> and <a href="#a76b799643733c8e5f3b3c9537cec7fad">TernlogFunctions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0303c1c5d962299e9e554c11e5400b19">llvm::EmitAnyX86InstComments</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### TernlogFunctions {#a76b799643733c8e5f3b3c9537cec7fad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringLiteral TernlogFunctions[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="#a0e448dfe33579cc1d0f660ba3219e900">printPTERNLOGComments</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### CASE\_AVX\_INS\_COMMON {#a756f4da8021c6e3d1897c348a166b05d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_AVX_INS_COMMON(Inst, Suffix, src)&nbsp;&nbsp;&nbsp;  case X86::V##Inst##Suffix##src:</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_AVX512\_FMA {#a27da674002083f9945965bd3ad8f2802}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_AVX512_FMA(Inst, suf)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z, suf)            \
  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z256, suf)         \
  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z128, suf)
</div>
</dd>
</dl>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_AVX512\_INS\_COMMON {#a78b56cee696aab225b57aa8d816c14e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_AVX512_INS_COMMON(Inst, Suffix, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, Suffix, src)          \
  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(Inst, Suffix, src)         \
  <a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(Inst, Suffix, src)
</div>
</dd>
</dl>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0303c1c5d962299e9e554c11e5400b19">llvm::EmitAnyX86InstComments</a>.</p>

</div>
</div>

### CASE\_AVX512\_INS\_COMMON\_INT {#a091e509dfb1ce815bc745f5a4049652e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_AVX512_INS_COMMON_INT(Inst, Suffix, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, Suffix, src##_Int)        \
  <a href="#aada100dbe50383c5dace2d490150f1fe">CASE_MASK_INS_COMMON_INT</a>(Inst, Suffix, src)         \
  <a href="#a8ba15344103b1968cd6ed19283f105c9">CASE_MASKZ_INS_COMMON_INT</a>(Inst, Suffix, src)
</div>
</dd>
</dl>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_FMA {#a8dc9b77edfc8ffb118085a28e0101ff8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FMA(Inst, suf)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a27da674002083f9945965bd3ad8f2802">CASE_AVX512_FMA</a>(Inst, suf)                      \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, , suf)                \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>, suf)
</div>
</dd>
</dl>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_FMA\_PACKED\_MEM {#a9b18ad8dbf9cbe7e533ab21e0339c29d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FMA_PACKED_MEM(Inst)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a8dc9b77edfc8ffb118085a28e0101ff8">CASE_FMA</a>(Inst##PD, m)                           \
  <a href="#a8dc9b77edfc8ffb118085a28e0101ff8">CASE_FMA</a>(Inst##PS, m)                           \
  <a href="#a27da674002083f9945965bd3ad8f2802">CASE_AVX512_FMA</a>(Inst##PD, mb)                   \
  <a href="#a27da674002083f9945965bd3ad8f2802">CASE_AVX512_FMA</a>(Inst##PS, mb)
</div>
</dd>
</dl>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="#a31b5b051ab96b75f4c104393b46b2f23">printFMAComments</a>.</p>

</div>
</div>

### CASE\_FMA\_PACKED\_REG {#ae2169960f68eddcb8175287ed2e03dfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FMA_PACKED_REG(Inst)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a8dc9b77edfc8ffb118085a28e0101ff8">CASE_FMA</a>(Inst##PD, r)                           \
  <a href="#a8dc9b77edfc8ffb118085a28e0101ff8">CASE_FMA</a>(Inst##PS, r)
</div>
</dd>
</dl>

<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="#a31b5b051ab96b75f4c104393b46b2f23">printFMAComments</a>.</p>

</div>
</div>

### CASE\_FMA\_SCALAR\_MEM {#a4e3b0f016236136709b5d6beb85406c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FMA_SCALAR_MEM(Inst)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SD, , m)              \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SS, , m)              \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SD, , m_Int)          \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SS, , m_Int)          \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SD, Z, m)             \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SS, Z, m)             \
  <a href="#a091e509dfb1ce815bc745f5a4049652e">CASE_AVX512_INS_COMMON_INT</a>(Inst##SD, Z, m)      \
  <a href="#a091e509dfb1ce815bc745f5a4049652e">CASE_AVX512_INS_COMMON_INT</a>(Inst##SS, Z, m)
</div>
</dd>
</dl>

<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="#a31b5b051ab96b75f4c104393b46b2f23">printFMAComments</a>.</p>

</div>
</div>

### CASE\_FMA\_SCALAR\_REG {#a0c1793c6fb71a76f788ff0910ac0cec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FMA_SCALAR_REG(Inst)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SD, , r)              \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SS, , r)              \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SD, , r_Int)          \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SS, , r_Int)          \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SD, Z, r)             \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SS, Z, r)             \
  <a href="#a091e509dfb1ce815bc745f5a4049652e">CASE_AVX512_INS_COMMON_INT</a>(Inst##SD, Z, r)      \
  <a href="#a091e509dfb1ce815bc745f5a4049652e">CASE_AVX512_INS_COMMON_INT</a>(Inst##SS, Z, r)
</div>
</dd>
</dl>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="#a31b5b051ab96b75f4c104393b46b2f23">printFMAComments</a>.</p>

</div>
</div>

### CASE\_FMA4 {#a44ea190375317bcc275497d62b88750f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FMA4(Inst, suf)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, 4, suf)               \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, 4<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>, suf)
</div>
</dd>
</dl>

<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_FMA4\_PACKED\_MR {#a705455ef613dba5bdde8ffd7f33e2b40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FMA4_PACKED_MR(Inst)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a44ea190375317bcc275497d62b88750f">CASE_FMA4</a>(Inst##PD, mr)                         \
  <a href="#a44ea190375317bcc275497d62b88750f">CASE_FMA4</a>(Inst##PS, mr)
</div>
</dd>
</dl>

<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="#a31b5b051ab96b75f4c104393b46b2f23">printFMAComments</a>.</p>

</div>
</div>

### CASE\_FMA4\_PACKED\_RM {#a41feee8092a0453eab558b3560f944f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FMA4_PACKED_RM(Inst)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a44ea190375317bcc275497d62b88750f">CASE_FMA4</a>(Inst##PD, rm)                         \
  <a href="#a44ea190375317bcc275497d62b88750f">CASE_FMA4</a>(Inst##PS, rm)
</div>
</dd>
</dl>

<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="#a31b5b051ab96b75f4c104393b46b2f23">printFMAComments</a>.</p>

</div>
</div>

### CASE\_FMA4\_PACKED\_RR {#ac9bdf477702a8738fd71da1e53d8160a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FMA4_PACKED_RR(Inst)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a44ea190375317bcc275497d62b88750f">CASE_FMA4</a>(Inst##PD, rr)                         \
  <a href="#a44ea190375317bcc275497d62b88750f">CASE_FMA4</a>(Inst##PS, rr)
</div>
</dd>
</dl>

<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="#a31b5b051ab96b75f4c104393b46b2f23">printFMAComments</a>.</p>

</div>
</div>

### CASE\_FMA4\_SCALAR\_MR {#a2aed4935df28385f1474429f4f785799}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FMA4_SCALAR_MR(Inst)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SD4, , mr)            \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SS4, , mr)            \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SD4, , mr_Int)        \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SS4, , mr_Int)
</div>
</dd>
</dl>

<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="#a31b5b051ab96b75f4c104393b46b2f23">printFMAComments</a>.</p>

</div>
</div>

### CASE\_FMA4\_SCALAR\_RM {#aa8b6c2d7862bb8dbe06c41f51406565e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FMA4_SCALAR_RM(Inst)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SD4, , rm)            \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SS4, , rm)            \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SD4, , rm_Int)        \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SS4, , rm_Int)
</div>
</dd>
</dl>

<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="#a31b5b051ab96b75f4c104393b46b2f23">printFMAComments</a>.</p>

</div>
</div>

### CASE\_FMA4\_SCALAR\_RR {#a4f35d58affa1b01628899682fd42a07d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FMA4_SCALAR_RR(Inst)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SD4, , rr)            \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SS4, , rr)            \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SD4, , rr_Int)        \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst##SS4, , rr_Int)
</div>
</dd>
</dl>

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="#a31b5b051ab96b75f4c104393b46b2f23">printFMAComments</a>.</p>

</div>
</div>

### CASE\_FPCLASS\_PACKED {#a0f84bba1bde3b706ecc952a068974161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FPCLASS_PACKED(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, Z, src##i)    \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, Z256, src##i) \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, Z128, src##i) \
  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(Inst, Z, src##i)
</div>
</dd>
</dl>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="#a8342adc3c89ccc8144d0db19a3485efd">printFPCLASSComments</a>.</p>

</div>
</div>

### CASE\_FPCLASS\_PACKED\_MEM {#a0ae70b284a661a2e082271923f476275}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FPCLASS_PACKED_MEM(Inst)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a0f84bba1bde3b706ecc952a068974161">CASE_FPCLASS_PACKED</a>(Inst, m)        \
  <a href="#a0f84bba1bde3b706ecc952a068974161">CASE_FPCLASS_PACKED</a>(Inst, mb)
</div>
</dd>
</dl>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="#a8342adc3c89ccc8144d0db19a3485efd">printFPCLASSComments</a>.</p>

</div>
</div>

### CASE\_FPCLASS\_SCALAR {#a9ff59dc78e00faddbecceb84ee3a7a5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FPCLASS_SCALAR(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, Z, src##i)  \
  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(Inst, Z, src##i)
</div>
</dd>
</dl>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="#a8342adc3c89ccc8144d0db19a3485efd">printFPCLASSComments</a>.</p>

</div>
</div>

### CASE\_MASK\_INS\_COMMON {#a52d16bbaf3b0f621e62ffdc933a4ccf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_MASK_INS_COMMON(Inst, Suffix, src)&nbsp;&nbsp;&nbsp;  case X86::V##Inst##Suffix##src##k:</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_MASK\_INS\_COMMON\_INT {#aada100dbe50383c5dace2d490150f1fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_MASK_INS_COMMON_INT(Inst, Suffix, src)&nbsp;&nbsp;&nbsp;  case X86::V##Inst##Suffix##src##k_Int:</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_MASK\_MOVDUP {#a86a2b2a2b3f60b3eb1751a72dc2ea9c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_MASK_MOVDUP(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(Inst, Z, r##src)           \
  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(Inst, Z256, r##src)        \
  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(Inst, Z128, r##src)
</div>
</dd>
</dl>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_MASK\_SHUF {#ad8bf57a8bc5047ad6b0e93048f581685}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_MASK_SHUF(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(Inst, Z, r##src##i)        \
  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(Inst, Z256, r##src##i)     \
  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(Inst, Z128, r##src##i)
</div>
</dd>
</dl>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_MASK\_UNPCK {#a239f4e5621f2f5ab2fde61f576faaae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_MASK_UNPCK(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(Inst, Z, r##src)           \
  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(Inst, Z256, r##src)        \
  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(Inst, Z128, r##src)
</div>
</dd>
</dl>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_MASK\_VPERM {#a9417c5903615abb5ee4ae91393de85ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_MASK_VPERM(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(Inst, Z, src##i)           \
  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(Inst, Z256, src##i)
</div>
</dd>
</dl>

<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_MASK\_VPERMILPI {#aa9f3023a541c42b179b7d80b305e077d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_MASK_VPERMILPI(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(Inst, Z, src##i)           \
  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(Inst, Z256, src##i)        \
  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(Inst, Z128, src##i)
</div>
</dd>
</dl>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_MASK\_VSHUF {#a290c67a0bb79b8b91c51f9951200b68a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_MASK_VSHUF(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(SHUFF##Inst, Z, r##src##i)     \
  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(SHUFI##Inst, Z, r##src##i)     \
  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(SHUFF##Inst, Z256, r##src##i)  \
  <a href="#a52d16bbaf3b0f621e62ffdc933a4ccf2">CASE_MASK_INS_COMMON</a>(SHUFI##Inst, Z256, r##src##i)
</div>
</dd>
</dl>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_MASKZ\_INS\_COMMON {#ab6fa081b218ad9afb52e457a4ea101a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_MASKZ_INS_COMMON(Inst, Suffix, src)&nbsp;&nbsp;&nbsp;  case X86::V##Inst##Suffix##src##kz:</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_MASKZ\_INS\_COMMON\_INT {#a8ba15344103b1968cd6ed19283f105c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_MASKZ_INS_COMMON_INT(Inst, Suffix, src)&nbsp;&nbsp;&nbsp;  case X86::V##Inst##Suffix##src##kz_Int:</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_MASKZ\_MOVDUP {#a2b32bc14e30b0a707371b8fc898c1311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_MASKZ_MOVDUP(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(Inst, Z, r##src)          \
  <a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(Inst, Z256, r##src)       \
  <a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(Inst, Z128, r##src)
</div>
</dd>
</dl>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_MASKZ\_SHUF {#aae0d0f204552b016e1a0e196bbd56e2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_MASKZ_SHUF(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(Inst, Z, r##src##i)       \
  <a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(Inst, Z256, r##src##i)    \
  <a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(Inst, Z128, r##src##i)
</div>
</dd>
</dl>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_MASKZ\_UNPCK {#ae6be3fdfbc8e235972bf208b07817cea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_MASKZ_UNPCK(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(Inst, Z, r##src)          \
  <a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(Inst, Z256, r##src)       \
  <a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(Inst, Z128, r##src)
</div>
</dd>
</dl>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_MASKZ\_VPERM {#a3e1365175259605547fe86dcc79e6952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_MASKZ_VPERM(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(Inst, Z, src##i)          \
  <a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(Inst, Z256, src##i)
</div>
</dd>
</dl>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_MASKZ\_VPERMILPI {#a6c99738570e7f28e1ade6e4226ea2adc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_MASKZ_VPERMILPI(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(Inst, Z, src##i)          \
  <a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(Inst, Z256, src##i)       \
  <a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(Inst, Z128, src##i)
</div>
</dd>
</dl>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_MASKZ\_VSHUF {#a20b7a2c2e9b30d04773297076618e97a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_MASKZ_VSHUF(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(SHUFF##Inst, Z, r##src##i)    \
  <a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(SHUFI##Inst, Z, r##src##i)    \
  <a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(SHUFF##Inst, Z256, r##src##i) \
  <a href="#ab6fa081b218ad9afb52e457a4ea101a8">CASE_MASKZ_INS_COMMON</a>(SHUFI##Inst, Z256, r##src##i)
</div>
</dd>
</dl>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_MOVDUP {#a47f32ffe68f1de3823cf76bab7557ea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_MOVDUP(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z, r##src)         \
  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z256, r##src)      \
  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z128, r##src)      \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, , r##src)             \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>, r##src)            \
  <a href="#a785793e2fb27e61530b7ecc7908f7e5e">CASE_SSE_INS_COMMON</a>(Inst, r##src)
</div>
</dd>
</dl>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0303c1c5d962299e9e554c11e5400b19">llvm::EmitAnyX86InstComments</a>.</p>

</div>
</div>

### CASE\_PMOVZX {#a92ace5d9d597bf35c6dcc000918e536f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_PMOVZX(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z, r##src)         \
  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z256, r##src)      \
  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z128, r##src)      \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, , r##src)             \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>, r##src)            \
  <a href="#a785793e2fb27e61530b7ecc7908f7e5e">CASE_SSE_INS_COMMON</a>(Inst, r##src)
</div>
</dd>
</dl>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0303c1c5d962299e9e554c11e5400b19">llvm::EmitAnyX86InstComments</a>.</p>

</div>
</div>

### CASE\_PTERNLOG {#ae93027cb9e673996c5b59d1bec7b1515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_PTERNLOG(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z, r##src##i)                                   \
  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z256, r##src##i)                                \
  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z128, r##src##i)
</div>
</dd>
</dl>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="#a0e448dfe33579cc1d0f660ba3219e900">printPTERNLOGComments</a>.</p>

</div>
</div>

### CASE\_SHUF {#a3adcd87f29de24c9eca58da035f75aec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_SHUF(Inst, suf)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z, suf)            \
  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z256, suf)         \
  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z128, suf)         \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, , suf)                \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>, suf)               \
  <a href="#a785793e2fb27e61530b7ecc7908f7e5e">CASE_SSE_INS_COMMON</a>(Inst, suf)
</div>
</dd>
</dl>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0303c1c5d962299e9e554c11e5400b19">llvm::EmitAnyX86InstComments</a>.</p>

</div>
</div>

### CASE\_SSE\_INS\_COMMON {#a785793e2fb27e61530b7ecc7908f7e5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_SSE_INS_COMMON(Inst, src)&nbsp;&nbsp;&nbsp;  case X86::Inst##src:</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>

</div>
</div>

### CASE\_UNPCK {#af11c7684124a6ac3f7a6a46e229a954e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_UNPCK(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z, r##src)         \
  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z256, r##src)      \
  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z128, r##src)      \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, , r##src)             \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>, r##src)            \
  <a href="#a785793e2fb27e61530b7ecc7908f7e5e">CASE_SSE_INS_COMMON</a>(Inst, r##src)
</div>
</dd>
</dl>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0303c1c5d962299e9e554c11e5400b19">llvm::EmitAnyX86InstComments</a>.</p>

</div>
</div>

### CASE\_VPERM {#a026d1658223e2a87d44670cac6c589c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VPERM(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z, src##i)         \
  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z256, src##i)      \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>, src##i)
</div>
</dd>
</dl>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0303c1c5d962299e9e554c11e5400b19">llvm::EmitAnyX86InstComments</a>.</p>

</div>
</div>

### CASE\_VPERMILPI {#a1e852686f152f3ea28364c69a7ccc4d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VPERMILPI(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z, src##i)         \
  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z256, src##i)      \
  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(Inst, Z128, src##i)      \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, , src##i)             \
  <a href="#a756f4da8021c6e3d1897c348a166b05d">CASE_AVX_INS_COMMON</a>(Inst, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>, src##i)
</div>
</dd>
</dl>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0303c1c5d962299e9e554c11e5400b19">llvm::EmitAnyX86InstComments</a>.</p>

</div>
</div>

### CASE\_VSHUF {#a958ac7903dbb1c40a8eb5e69e7383e1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VSHUF(Inst, src)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(SHUFF##Inst, Z, r##src##i)    \
  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(SHUFI##Inst, Z, r##src##i)    \
  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(SHUFF##Inst, Z256, r##src##i) \
  <a href="#a78b56cee696aab225b57aa8d816c14e0">CASE_AVX512_INS_COMMON</a>(SHUFI##Inst, Z256, r##src##i)
</div>
</dd>
</dl>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp">X86InstComments.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0303c1c5d962299e9e554c11e5400b19">llvm::EmitAnyX86InstComments</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
