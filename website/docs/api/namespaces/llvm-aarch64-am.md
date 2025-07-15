---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/aarch64-am
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `AArch64_AM` Namespace Reference

<p><a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am">AArch64_AM</a> - <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> Addressing Mode Stuff. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::AArch64_AM { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ShiftExtendType { <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a2bf23de615e193f526a0a23c304711">getShiftExtendName</a> (AArch64_AM::ShiftExtendType ST)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getShiftName - Get the string encoding for the shift type. <a href="#a8a2bf23de615e193f526a0a23c304711">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1">AArch64_AM::ShiftExtendType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adff7aee2baba9b9691304bee7e76f574">getShiftType</a> (unsigned Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getShiftType - Extract the shift type. <a href="#adff7aee2baba9b9691304bee7e76f574">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22f623563f43de6d1aabcdfa9d341031">getShiftValue</a> (unsigned Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getShiftValue - Extract the shift value. <a href="#a22f623563f43de6d1aabcdfa9d341031">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeae88f12b667477f90db9b726556b337">getShifterImm</a> (AArch64_AM::ShiftExtendType ST, unsigned Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getShifterImm - Encode the shift type and amount: imm: 6-bit shift amount shifter: 000 ==&gt; lsl 001 ==&gt; lsr 010 ==&gt; asr 011 ==&gt; ror 100 ==&gt; msl {8-6} = shifter {5-0} = imm <a href="#aeae88f12b667477f90db9b726556b337">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a529c6b94f32165c3d420316bcb6e0d9e">getArithShiftValue</a> (unsigned Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getArithShiftValue - get the arithmetic shift value. <a href="#a529c6b94f32165c3d420316bcb6e0d9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1">AArch64_AM::ShiftExtendType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1679933777cb604308f2ab1976c62c9">getExtendType</a> (unsigned Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getExtendType - Extract the extend type for operands of arithmetic ops. <a href="#ab1679933777cb604308f2ab1976c62c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1">AArch64_AM::ShiftExtendType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad45de36bc238edb61ed6b9375030f62f">getArithExtendType</a> (unsigned Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97e1f05eb4f658b2089eb7ab935ba96a">getExtendEncoding</a> (AArch64_AM::ShiftExtendType ET)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping from extend bits to required operation: shifter: 000 ==&gt; uxtb 001 ==&gt; uxth 010 ==&gt; uxtw 011 ==&gt; uxtx 100 ==&gt; sxtb 101 ==&gt; sxth 110 ==&gt; sxtw 111 ==&gt; sxtx. <a href="#a97e1f05eb4f658b2089eb7ab935ba96a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35905b769bf1afa2cc7e2a223191e57e">getArithExtendImm</a> (AArch64_AM::ShiftExtendType ET, unsigned Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getArithExtendImm - Encode the extend type and shift amount for an arithmetic instruction: imm: 3-bit extend amount {5-3} = shifter {2-0} = imm3 <a href="#a35905b769bf1afa2cc7e2a223191e57e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1591248b3a851c448b3935c20086937">getMemDoShift</a> (unsigned Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getMemDoShift - Extract the "do shift" flag value for load/store instructions. <a href="#af1591248b3a851c448b3935c20086937">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1">AArch64_AM::ShiftExtendType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67a743ebbd73e62fc95a01447cace4c9">getMemExtendType</a> (unsigned Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getExtendType - Extract the extend type for the offset operand of loads/stores. <a href="#a67a743ebbd73e62fc95a01447cace4c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f2b2edb37104fc026a966265dfedc8b">getMemExtendImm</a> (AArch64_AM::ShiftExtendType ET, bool DoShift)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getExtendImm - Encode the extend type and amount for a load/store inst: doshift: should the offset be scaled by the access size shifter: 000 ==&gt; uxtb 001 ==&gt; uxth 010 ==&gt; uxtw 011 ==&gt; uxtx 100 ==&gt; sxtb 101 ==&gt; sxth 110 ==&gt; sxtw 111 ==&gt; sxtx {3-1} = shifter {0} = doshift <a href="#a1f2b2edb37104fc026a966265dfedc8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa95984b1da1308f393b2c8d292126511">ror</a> (uint64_t elt, unsigned size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cd3e23b97b495a98c0b723ab18e4d96">processLogicalImmediate</a> (uint64_t Imm, unsigned RegSize, uint64_t &amp;Encoding)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>processLogicalImmediate - Determine if an immediate value can be encoded as the immediate operand of a logical instruction for the given register size. <a href="#a2cd3e23b97b495a98c0b723ab18e4d96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a262431cccd14e6063eacc180130a5882">isLogicalImmediate</a> (uint64_t imm, unsigned regSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isLogicalImmediate - Return true if the immediate is valid for a logical immediate instruction of the given register size. <a href="#a262431cccd14e6063eacc180130a5882">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a832ad315a355f4ddcc32f189f34e28a9">encodeLogicalImmediate</a> (uint64_t imm, unsigned regSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>encodeLogicalImmediate - Return the encoded immediate value for a logical immediate instruction of the given register size. <a href="#a832ad315a355f4ddcc32f189f34e28a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1affd6d7e8a280fa6a0b642a6e0734b8">decodeLogicalImmediate</a> (uint64_t val, unsigned regSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>decodeLogicalImmediate - Decode a logical immediate value in the form "N:immr:imms" (where the immr and imms fields are each 6 bits) into the integer value it represents with regSize bits. <a href="#a1affd6d7e8a280fa6a0b642a6e0734b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a33ab78776cbb20a7b285e6f165888c">isValidDecodeLogicalImmediate</a> (uint64_t val, unsigned regSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isValidDecodeLogicalImmediate - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> to see if the logical immediate value in the form "N:immr:imms" (where the immr and imms fields are each 6 bits) is a valid encoding for an integer value with regSize bits. <a href="#a0a33ab78776cbb20a7b285e6f165888c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6517f30a8205ebfe6689d35d925fa5a9">getFPImmFloat</a> (unsigned Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab23f031bf813c9284ac27776b414a867">getFP16Imm</a> (const APInt &amp;Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFP16Imm - Return an 8-bit floating-point version of the 16-bit floating-point value. <a href="#ab23f031bf813c9284ac27776b414a867">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d99a67b80aa823579e6144312d2ab49">getFP16Imm</a> (const APFloat &amp;FPImm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d1d3c98268fd4f6017b99e4bd9415ed">getFP32Imm</a> (const APInt &amp;Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFP32Imm - Return an 8-bit floating-point version of the 32-bit floating-point value. <a href="#a5d1d3c98268fd4f6017b99e4bd9415ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8c5e2948d1d2c86073df3e61ed55b6a">getFP32Imm</a> (const APFloat &amp;FPImm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3b818e0d89b7804a311b48c18080a4f">getFP64Imm</a> (const APInt &amp;Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFP64Imm - Return an 8-bit floating-point version of the 64-bit floating-point value. <a href="#aa3b818e0d89b7804a311b48c18080a4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ee61f3cdffeade9f24458631bc67052">getFP64Imm</a> (const APFloat &amp;FPImm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc0e820b8853201ef6ff415931806b68">isAdvSIMDModImmType1</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af49fee539884eda3cd5c717bcdce4786">encodeAdvSIMDModImmType1</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a3ad8b0740dff0b81ff6ced48cab9ad">decodeAdvSIMDModImmType1</a> (uint8_t Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6c74fb3a2a8d0cb99feef8744eb3ace">isAdvSIMDModImmType2</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29c7eaffeccf0f5b17dbf57cbd618b81">encodeAdvSIMDModImmType2</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e75aac90f5def2ece7587f19ca7a6e3">decodeAdvSIMDModImmType2</a> (uint8_t Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9224d46b85d9e2fa60a5e5c77f07556">isAdvSIMDModImmType3</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4df25f698bb1307c5b3b9d5ac214fb4">encodeAdvSIMDModImmType3</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9297deb573f687e206c50b7e6e5b76e6">decodeAdvSIMDModImmType3</a> (uint8_t Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fe53b15d06d979154de9230ffc90a07">isAdvSIMDModImmType4</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae37687fd3e4b8a746f795bfcd64a70e7">encodeAdvSIMDModImmType4</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25e00de71d76ae2c0deab8993aef3815">decodeAdvSIMDModImmType4</a> (uint8_t Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d810d08a9bc5d3c0ef0d54b1c9eb646">isAdvSIMDModImmType5</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9db7472b1930619903c87129a187e77d">encodeAdvSIMDModImmType5</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9b54d7027c81dbc33d8cbb6ddbe9abb">decodeAdvSIMDModImmType5</a> (uint8_t Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec822bd18b696d033e3fb3a91db5b1ef">isAdvSIMDModImmType6</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adabd0632bbd6cb08e7c545cf755c56c8">encodeAdvSIMDModImmType6</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8f8d1e63c29d9f0ae84a6be2c6f80d1">decodeAdvSIMDModImmType6</a> (uint8_t Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a906b3231e8117e7b6b1ab0cfd9226d1b">isAdvSIMDModImmType7</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a2e3b44e9ff9c2b48e69a2182f27933">encodeAdvSIMDModImmType7</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a950d8877419079e58d5727ea9e2ec7ad">decodeAdvSIMDModImmType7</a> (uint8_t Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2fe7045c79cfc8be9f42ac54a8fca85">isAdvSIMDModImmType8</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe2a9b4774dc9d8c6e4dbeaad1ca31c4">decodeAdvSIMDModImmType8</a> (uint8_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfb7ccd4fe522eb89ad8b66f2cdf0022">encodeAdvSIMDModImmType8</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e61bc2a6e0481a74be8bfbbb11ba3aa">isAdvSIMDModImmType9</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73f853223199cac7a15bf2906c74dd3f">encodeAdvSIMDModImmType9</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab36d74fc992d6a03c482857e5b563a4c">decodeAdvSIMDModImmType9</a> (uint8_t Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacafb7aecc0ecc157dd1fbaac53bae38">isAdvSIMDModImmType10</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73d57b024abd09c15c27e89d3bea29b0">encodeAdvSIMDModImmType10</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab558509f6a3ef0739cea54ea66e1780d">decodeAdvSIMDModImmType10</a> (uint8_t Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad56db6bd1cb03dacae870fc6777f6838">isAdvSIMDModImmType11</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad42afbeb2b8bd3667fe4e05da5ab3f3c">encodeAdvSIMDModImmType11</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a575bb9ff72c673b1846c93885955c4bf">decodeAdvSIMDModImmType11</a> (uint8_t Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac844d76c3324182cd41105fc61371768">isAdvSIMDModImmType12</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6da348f7ca3bc56096e6a409b4ce67c4">encodeAdvSIMDModImmType12</a> (uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41cd1be17511908a999b34fac029554d">decodeAdvSIMDModImmType12</a> (uint8_t Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a783283846d982f14988fa8c1eb467dd4">isSVEMaskOfIdenticalElements</a> (int64_t Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if Imm is the concatenation of a repeating pattern of type T. <a href="#a783283846d982f14988fa8c1eb467dd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a99509002d9fccdb280ff2c66af1505f9">isSVECpyImm</a> (int64_t Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if Imm is valid for CPY/DUP. <a href="#a99509002d9fccdb280ff2c66af1505f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2ccd71fca66375c495f8c883988091b9">isSVEAddSubImm</a> (int64_t Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if Imm is valid for ADD/SUB. <a href="#a2ccd71fca66375c495f8c883988091b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b94013661adb0a0203a1dba80e27f1b">isSVEMoveMaskPreferredLogicalImmediate</a> (int64_t Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if Imm is valid for DUPM and has no single CPY/DUP equivalent. <a href="#a0b94013661adb0a0203a1dba80e27f1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f78ae6edfd108ae03965c8e49fbabab">isAnyMOVZMovAlias</a> (uint64_t Value, int RegWidth)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a923906a7a2b0e53a9d71fc27c39210">isMOVZMovAlias</a> (uint64_t Value, int Shift, int RegWidth)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a178fae9db42f799d5a2c3c4b3819d8bb">isMOVNMovAlias</a> (uint64_t Value, int Shift, int RegWidth)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51360b5f47268ba43911ef887318c34c">isAnyMOVWMovAlias</a> (uint64_t Value, int RegWidth)</td>
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

## Description {#details}

<p><a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am">AArch64_AM</a> - <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> Addressing Mode Stuff.</p>

<div class="doxySectionDef">

## Enumerations

### ShiftExtendType {#a7e75394a33f6a5897d7a14c0ba5d44f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AArch64_AM::ShiftExtendType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InvalidShiftExtend<a id="a7e75394a33f6a5897d7a14c0ba5d44f1a4738a48912fcb1ca44fbe35b8c98ab50"></a></td>
<td class="doxyEnumItemDescription"> (= -1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSL<a id="a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSR<a id="a7e75394a33f6a5897d7a14c0ba5d44f1a7e1384a3b7d612a03b54d9c8f2071a04"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ASR<a id="a7e75394a33f6a5897d7a14c0ba5d44f1a2f11475361161d9ce95a2f7be74de342"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROR<a id="a7e75394a33f6a5897d7a14c0ba5d44f1abb1fa5a6016bfee1580a7b989a454c9a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MSL<a id="a7e75394a33f6a5897d7a14c0ba5d44f1a5b297b24d84fef366a94098c36f07c3a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UXTB<a id="a7e75394a33f6a5897d7a14c0ba5d44f1a59dcdcd32661c3deea19d0b4c00aeb09"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UXTH<a id="a7e75394a33f6a5897d7a14c0ba5d44f1a822b65b0f419881e5f0352e2f4f33d29"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UXTW<a id="a7e75394a33f6a5897d7a14c0ba5d44f1a2620d8167a503c9942cc4afded7f830d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UXTX<a id="a7e75394a33f6a5897d7a14c0ba5d44f1ad2f6771d4027a09ba1d0de2e5ea54470"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SXTB<a id="a7e75394a33f6a5897d7a14c0ba5d44f1ac3bdf1b8c8fd1f36afa7af40bb1a1a59"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SXTH<a id="a7e75394a33f6a5897d7a14c0ba5d44f1ae52597f63d00aac32d655ca8d67a689b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SXTW<a id="a7e75394a33f6a5897d7a14c0ba5d44f1a13ed9069b0840f7eb3a47fce0878a5ad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SXTX<a id="a7e75394a33f6a5897d7a14c0ba5d44f1ae2de16560eda6fb0ee38a2173c863ba4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### decodeAdvSIMDModImmType1() {#a6a3ad8b0740dff0b81ff6ced48cab9ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AArch64_AM::decodeAdvSIMDModImmType1 (uint8_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>

</div>
</div>

### decodeAdvSIMDModImmType10() {#ab558509f6a3ef0739cea54ea66e1780d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AArch64_AM::decodeAdvSIMDModImmType10 (uint8_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a489e944ed336ebeb25656c01848e48fa">llvm::AArch64InstPrinter::printSIMDType10Operand</a>.</p>

</div>
</div>

### decodeAdvSIMDModImmType11() {#a575bb9ff72c673b1846c93885955c4bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AArch64_AM::decodeAdvSIMDModImmType11 (uint8_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>

</div>
</div>

### decodeAdvSIMDModImmType12() {#a41cd1be17511908a999b34fac029554d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AArch64_AM::decodeAdvSIMDModImmType12 (uint8_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>

</div>
</div>

### decodeAdvSIMDModImmType2() {#a2e75aac90f5def2ece7587f19ca7a6e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AArch64_AM::decodeAdvSIMDModImmType2 (uint8_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>

</div>
</div>

### decodeAdvSIMDModImmType3() {#a9297deb573f687e206c50b7e6e5b76e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AArch64_AM::decodeAdvSIMDModImmType3 (uint8_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>

</div>
</div>

### decodeAdvSIMDModImmType4() {#a25e00de71d76ae2c0deab8993aef3815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AArch64_AM::decodeAdvSIMDModImmType4 (uint8_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>

</div>
</div>

### decodeAdvSIMDModImmType5() {#ab9b54d7027c81dbc33d8cbb6ddbe9abb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AArch64_AM::decodeAdvSIMDModImmType5 (uint8_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>

</div>
</div>

### decodeAdvSIMDModImmType6() {#af8f8d1e63c29d9f0ae84a6be2c6f80d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AArch64_AM::decodeAdvSIMDModImmType6 (uint8_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>

</div>
</div>

### decodeAdvSIMDModImmType7() {#a950d8877419079e58d5727ea9e2ec7ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AArch64_AM::decodeAdvSIMDModImmType7 (uint8_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>

</div>
</div>

### decodeAdvSIMDModImmType8() {#abe2a9b4774dc9d8c6e4dbeaad1ca31c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AArch64_AM::decodeAdvSIMDModImmType8 (uint8_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 563 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>

</div>
</div>

### decodeAdvSIMDModImmType9() {#ab36d74fc992d6a03c482857e5b563a4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AArch64_AM::decodeAdvSIMDModImmType9 (uint8_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>

</div>
</div>

### decodeLogicalImmediate() {#a1affd6d7e8a280fa6a0b642a6e0734b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AArch64_AM::decodeLogicalImmediate (uint64_t val, unsigned regSize)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>decodeLogicalImmediate - Decode a logical immediate value in the form "N:immr:imms" (where the immr and imms fields are each 6 bits) into the integer value it represents with regSize bits.</p>

<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#aa95984b1da1308f393b2c8d292126511">ror</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ad11fff0bd7672635d1cabedca7be31c6">llvm::AArch64InstrInfo::analyzeCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#acca3317ec9abd9a2b3da9870ca65c9c5">getUsefulBitsFromAndWithImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#af0bbac5dd9f698f2c73477c4e5f36b60">llvm::AArch64InstrInfo::optimizeCondBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ab4e79ecca1f6c9c8b0dcf317d32a4523">llvm::AArch64InstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ab86bea1cb49f64b7eb22195b6653e317">llvm::AArch64InstPrinter::printLogicalImm</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#af71092aeb107ea7f054fac85a28ba146">llvm::AArch64InstPrinter::printSVELogicalImm</a>.</p>

</div>
</div>

### encodeAdvSIMDModImmType1() {#af49fee539884eda3cd5c717bcdce4786}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AArch64_AM::encodeAdvSIMDModImmType1 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aed120dd6850080b309b6054efd2b142b">tryAdvSIMDModImm32</a>.</p>

</div>
</div>

### encodeAdvSIMDModImmType10() {#a73d57b024abd09c15c27e89d3bea29b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AArch64_AM::encodeAdvSIMDModImmType10 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a275d93f01f3c0461c602869aa89a1fad">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSIMDImmType10Operands</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a52b49fd007d3e59011c1e924579f3a80">tryAdvSIMDModImm64</a>.</p>

</div>
</div>

### encodeAdvSIMDModImmType11() {#ad42afbeb2b8bd3667fe4e05da5ab3f3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AArch64_AM::encodeAdvSIMDModImmType11 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 684 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a41506ddab8a425491f9ebf969036eb84">tryAdvSIMDModImmFP</a>.</p>

</div>
</div>

### encodeAdvSIMDModImmType12() {#a6da348f7ca3bc56096e6a409b4ce67c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AArch64_AM::encodeAdvSIMDModImmType12 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 733 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a41506ddab8a425491f9ebf969036eb84">tryAdvSIMDModImmFP</a>.</p>

</div>
</div>

### encodeAdvSIMDModImmType2() {#a29c7eaffeccf0f5b17dbf57cbd618b81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AArch64_AM::encodeAdvSIMDModImmType2 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aed120dd6850080b309b6054efd2b142b">tryAdvSIMDModImm32</a>.</p>

</div>
</div>

### encodeAdvSIMDModImmType3() {#af4df25f698bb1307c5b3b9d5ac214fb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AArch64_AM::encodeAdvSIMDModImmType3 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aed120dd6850080b309b6054efd2b142b">tryAdvSIMDModImm32</a>.</p>

</div>
</div>

### encodeAdvSIMDModImmType4() {#ae37687fd3e4b8a746f795bfcd64a70e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AArch64_AM::encodeAdvSIMDModImmType4 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aed120dd6850080b309b6054efd2b142b">tryAdvSIMDModImm32</a>.</p>

</div>
</div>

### encodeAdvSIMDModImmType5() {#a9db7472b1930619903c87129a187e77d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AArch64_AM::encodeAdvSIMDModImmType5 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3cce50ef77513b8bd1cbeb48b4d9339d">tryAdvSIMDModImm16</a>.</p>

</div>
</div>

### encodeAdvSIMDModImmType6() {#adabd0632bbd6cb08e7c545cf755c56c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AArch64_AM::encodeAdvSIMDModImmType6 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3cce50ef77513b8bd1cbeb48b4d9339d">tryAdvSIMDModImm16</a>.</p>

</div>
</div>

### encodeAdvSIMDModImmType7() {#a6a2e3b44e9ff9c2b48e69a2182f27933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AArch64_AM::encodeAdvSIMDModImmType7 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a91b6b0ccb484e79d3d1558e8d9c12cd8">tryAdvSIMDModImm321s</a>.</p>

</div>
</div>

### encodeAdvSIMDModImmType8() {#abfb7ccd4fe522eb89ad8b66f2cdf0022}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AArch64_AM::encodeAdvSIMDModImmType8 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a91b6b0ccb484e79d3d1558e8d9c12cd8">tryAdvSIMDModImm321s</a>.</p>

</div>
</div>

### encodeAdvSIMDModImmType9() {#a73f853223199cac7a15bf2906c74dd3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AArch64_AM::encodeAdvSIMDModImmType9 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a55e427e6bf5d495e92fbbe9ba86e9990">tryAdvSIMDModImm8</a>.</p>

</div>
</div>

### encodeLogicalImmediate() {#a832ad315a355f4ddcc32f189f34e28a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AArch64_AM::encodeLogicalImmediate (uint64_t imm, unsigned regSize)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>encodeLogicalImmediate - Return the encoded immediate value for a logical immediate instruction of the given register size.</p>

<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a2cd3e23b97b495a98c0b723ab18e4d96">processLogicalImmediate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a9056346261cb779a567f627676c37068">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addLogicalImmNotOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ae997d5e3fd8015241b318c4b0da0c194">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addLogicalImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#aac53de41a4af1d12db6ce7d5a0cf6678">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitHwasanMemaccessSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a029c7ad54d8731492ed559aa860e3395">llvm::AArch64InstrInfo::insertSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a882ed852a717e7421c4dd8ede4908d92">optimizeLogicalImm</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>.</p>

</div>
</div>

### getArithExtendImm() {#a35905b769bf1afa2cc7e2a223191e57e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64_AM::getArithExtendImm (<a href="#a7e75394a33f6a5897d7a14c0ba5d44f1">AArch64_AM::ShiftExtendType</a> ET, unsigned Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getArithExtendImm - Encode the extend type and shift amount for an arithmetic instruction: imm: 3-bit extend amount {5-3} = shifter {2-0} = imm3</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a97e1f05eb4f658b2089eb7ab935ba96a">getExtendEncoding</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a12ebb7021420c49a1338058e4db7f435">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addExtend64Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a8a2b0c34d3cfaf2fa1561bfaf6182700">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addExtendOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab812d774aa563ffc2c67030a9ba1be39">llvm::AArch64TargetLowering::EmitAllocateSMESaveBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab9deb47df6ac29c81422ae6b4bfd924d">llvm::AArch64InstrInfo::probedStackAlloc</a>.</p>

</div>
</div>

### getArithExtendType() {#ad45de36bc238edb61ed6b9375030f62f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64_AM::ShiftExtendType llvm::AArch64_AM::getArithExtendType (unsigned Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Reference <a href="#ab1679933777cb604308f2ab1976c62c9">getExtendType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa9430ae4ad548095743aa0a26b235d82">llvm::AArch64InstrInfo::canFoldIntoAddrMode</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a7f89beec12829953872f4f813d8fbb5d">llvm::AArch64InstPrinter::printArithExtend</a>.</p>

</div>
</div>

### getArithShiftValue() {#a529c6b94f32165c3d420316bcb6e0d9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64_AM::getArithShiftValue (unsigned Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getArithShiftValue - get the arithmetic shift value.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa9430ae4ad548095743aa0a26b235d82">llvm::AArch64InstrInfo::canFoldIntoAddrMode</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a7f89beec12829953872f4f813d8fbb5d">llvm::AArch64InstPrinter::printArithExtend</a>.</p>

</div>
</div>

### getExtendEncoding() {#a97e1f05eb4f658b2089eb7ab935ba96a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64_AM::getExtendEncoding (<a href="#a7e75394a33f6a5897d7a14c0ba5d44f1">AArch64_AM::ShiftExtendType</a> ET)</td>
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

<p>Mapping from extend bits to required operation: shifter: 000 ==&gt; uxtb 001 ==&gt; uxth 010 ==&gt; uxtw 011 ==&gt; uxtx 100 ==&gt; sxtb 101 ==&gt; sxth 110 ==&gt; sxtw 111 ==&gt; sxtx.</p>

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1ac3bdf1b8c8fd1f36afa7af40bb1a1a59">SXTB</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1ae52597f63d00aac32d655ca8d67a689b">SXTH</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a13ed9069b0840f7eb3a47fce0878a5ad">SXTW</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1ae2de16560eda6fb0ee38a2173c863ba4">SXTX</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a59dcdcd32661c3deea19d0b4c00aeb09">UXTB</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a822b65b0f419881e5f0352e2f4f33d29">UXTH</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a2620d8167a503c9942cc4afded7f830d">UXTW</a> and <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1ad2f6771d4027a09ba1d0de2e5ea54470">UXTX</a>.</p>


<p>Referenced by <a href="#a35905b769bf1afa2cc7e2a223191e57e">getArithExtendImm</a> and <a href="#a1f2b2edb37104fc026a966265dfedc8b">getMemExtendImm</a>.</p>

</div>
</div>

### getExtendType() {#ab1679933777cb604308f2ab1976c62c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64_AM::ShiftExtendType llvm::AArch64_AM::getExtendType (unsigned Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getExtendType - Extract the extend type for operands of arithmetic ops.</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1ac3bdf1b8c8fd1f36afa7af40bb1a1a59">SXTB</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1ae52597f63d00aac32d655ca8d67a689b">SXTH</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a13ed9069b0840f7eb3a47fce0878a5ad">SXTW</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1ae2de16560eda6fb0ee38a2173c863ba4">SXTX</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a59dcdcd32661c3deea19d0b4c00aeb09">UXTB</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a822b65b0f419881e5f0352e2f4f33d29">UXTH</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a2620d8167a503c9942cc4afded7f830d">UXTW</a> and <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1ad2f6771d4027a09ba1d0de2e5ea54470">UXTX</a>.</p>


<p>Referenced by <a href="#ad45de36bc238edb61ed6b9375030f62f">getArithExtendType</a> and <a href="#a67a743ebbd73e62fc95a01447cace4c9">getMemExtendType</a>.</p>

</div>
</div>

### getFP16Imm() {#ab23f031bf813c9284ac27776b414a867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64_AM::getFP16Imm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getFP16Imm - Return an 8-bit floating-point version of the 16-bit floating-point value.</p>


<p>If the value cannot be represented as an 8-bit floating-point value, then return -1.</p>


<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="#a8d99a67b80aa823579e6144312d2ab49">getFP16Imm</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a0b5597ce1a7049500d0b30bef14951ca">llvm::AArch64TargetLowering::isFPImmLegal</a>.</p>

</div>
</div>

### getFP16Imm() {#a8d99a67b80aa823579e6144312d2ab49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64_AM::getFP16Imm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; FPImm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a> and <a href="#ab23f031bf813c9284ac27776b414a867">getFP16Imm</a>.</p>

</div>
</div>

### getFP32Imm() {#a5d1d3c98268fd4f6017b99e4bd9415ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64_AM::getFP32Imm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getFP32Imm - Return an 8-bit floating-point version of the 32-bit floating-point value.</p>


<p>If the value cannot be represented as an 8-bit floating-point value, then return -1.</p>


<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="#ae8c5e2948d1d2c86073df3e61ed55b6a">getFP32Imm</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a0b5597ce1a7049500d0b30bef14951ca">llvm::AArch64TargetLowering::isFPImmLegal</a>.</p>

</div>
</div>

### getFP32Imm() {#ae8c5e2948d1d2c86073df3e61ed55b6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64_AM::getFP32Imm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; FPImm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a> and <a href="#a5d1d3c98268fd4f6017b99e4bd9415ed">getFP32Imm</a>.</p>

</div>
</div>

### getFP64Imm() {#aa3b818e0d89b7804a311b48c18080a4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64_AM::getFP64Imm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getFP64Imm - Return an 8-bit floating-point version of the 64-bit floating-point value.</p>


<p>If the value cannot be represented as an 8-bit floating-point value, then return -1.</p>


<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aadc0596f177340a6d088aa4b9084263d">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addFPImmOperands</a>, <a href="#a5ee61f3cdffeade9f24458631bc67052">getFP64Imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ab81555068a211eb808e86d91d8ec390c">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isFPImm</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a0b5597ce1a7049500d0b30bef14951ca">llvm::AArch64TargetLowering::isFPImmLegal</a>.</p>

</div>
</div>

### getFP64Imm() {#a5ee61f3cdffeade9f24458631bc67052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64_AM::getFP64Imm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; FPImm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a> and <a href="#aa3b818e0d89b7804a311b48c18080a4f">getFP64Imm</a>.</p>

</div>
</div>

### getFPImmFloat() {#a6517f30a8205ebfe6689d35d925fa5a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float llvm::AArch64_AM::getFPImmFloat (unsigned Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a761e8a0a85cb668fdc8a026441fac635">llvm::AArch64InstPrinter::printFPImmOperand</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a0ff7af77f414b9796ed948a2723f6199">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseFPImm</a>.</p>

</div>
</div>

### getMemDoShift() {#af1591248b3a851c448b3935c20086937}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::getMemDoShift (unsigned Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getMemDoShift - Extract the "do shift" flag value for load/store instructions.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>

</div>
</div>

### getMemExtendImm() {#a1f2b2edb37104fc026a966265dfedc8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64_AM::getMemExtendImm (<a href="#a7e75394a33f6a5897d7a14c0ba5d44f1">AArch64_AM::ShiftExtendType</a> ET, bool DoShift)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getExtendImm - Encode the extend type and amount for a load/store inst: doshift: should the offset be scaled by the access size shifter: 000 ==&gt; uxtb 001 ==&gt; uxth 010 ==&gt; uxtw 011 ==&gt; uxtx 100 ==&gt; sxtb 101 ==&gt; sxth 110 ==&gt; sxtw 111 ==&gt; sxtx {3-1} = shifter {0} = doshift</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Reference <a href="#a97e1f05eb4f658b2089eb7ab935ba96a">getExtendEncoding</a>.</p>

</div>
</div>

### getMemExtendType() {#a67a743ebbd73e62fc95a01447cace4c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64_AM::ShiftExtendType llvm::AArch64_AM::getMemExtendType (unsigned Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getExtendType - Extract the extend type for the offset operand of loads/stores.</p>

<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Reference <a href="#ab1679933777cb604308f2ab1976c62c9">getExtendType</a>.</p>

</div>
</div>

### getShifterImm() {#aeae88f12b667477f90db9b726556b337}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64_AM::getShifterImm (<a href="#a7e75394a33f6a5897d7a14c0ba5d44f1">AArch64_AM::ShiftExtendType</a> ST, unsigned Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getShifterImm - Encode the shift type and amount: imm: 6-bit shift amount shifter: 000 ==&gt; lsl 001 ==&gt; lsr 010 ==&gt; asr 011 ==&gt; ror 100 ==&gt; msl {8-6} = shifter {5-0} = imm</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>References <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a2f11475361161d9ce95a2f7be74de342">ASR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">LSL</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a7e1384a3b7d612a03b54d9c8f2071a04">LSR</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a5b297b24d84fef366a94098c36f07c3a">MSL</a> and <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1abb1fa5a6016bfee1580a7b989a454c9a">ROR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ad007797dfd6b5c922a9818fd215aebd0">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addShifterOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ade00a4708e793e75a00a3030325cbf84">llvm::AArch64InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#aea02c3c9f298ea50ec11bb7c8201525a">emitFrameOffsetAdj</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#aac53de41a4af1d12db6ce7d5a0cf6678">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitHwasanMemaccessSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-imm/#a77a4e6615fbc6c2bbcf179370dbd0fa9">llvm::AArch64_IMM::expandMOVImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#a2edf9e8f09bfb0cc4949aa1813872322">expandMOVImmSimple</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#af20b4c8887374431df7cafec53a124bb">isWorthFoldingIntoOrrWithShift</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a22c90a0d582e484ad655a9f337002b05">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerMOVaddrPAC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a7321f8d9c50eb416611a0309a3fd9742">llvm::AArch64RegisterInfo::materializeFrameBaseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab9deb47df6ac29c81422ae6b4bfd924d">llvm::AArch64InstrInfo::probedStackAlloc</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a664436e80e651ce40c1abcf063d58fa9">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::promoteLoadFromStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ab46c572eae7ad5db65d1487f468bc6c5">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ac2847ce431c05147e95ed196fd1c0658">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectArithImmed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#aafaaafa83aac0fe8abe7498d59ceae37">tryOrrWithShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#a7000ac817f63a64697020f0538311927">trySequenceOfOnes</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#a6efd5b30fe34a042d2937ba63a73ad07">tryToreplicateChunks</a>.</p>

</div>
</div>

### getShiftExtendName() {#a8a2bf23de615e193f526a0a23c304711}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::AArch64_AM::getShiftExtendName (<a href="#a7e75394a33f6a5897d7a14c0ba5d44f1">AArch64_AM::ShiftExtendType</a> ST)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getShiftName - Get the string encoding for the shift type.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>References <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a2f11475361161d9ce95a2f7be74de342">ASR</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">LSL</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a7e1384a3b7d612a03b54d9c8f2071a04">LSR</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a5b297b24d84fef366a94098c36f07c3a">MSL</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1abb1fa5a6016bfee1580a7b989a454c9a">ROR</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1ac3bdf1b8c8fd1f36afa7af40bb1a1a59">SXTB</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1ae52597f63d00aac32d655ca8d67a689b">SXTH</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a13ed9069b0840f7eb3a47fce0878a5ad">SXTW</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1ae2de16560eda6fb0ee38a2173c863ba4">SXTX</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a59dcdcd32661c3deea19d0b4c00aeb09">UXTB</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a822b65b0f419881e5f0352e2f4f33d29">UXTH</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a2620d8167a503c9942cc4afded7f830d">UXTW</a> and <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1ad2f6771d4027a09ba1d0de2e5ea54470">UXTX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a763e5d73a932a30d95c888b81f45a0c3">anonymous{AArch64AsmParser.cpp}::AArch64Operand::print</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a7f89beec12829953872f4f813d8fbb5d">llvm::AArch64InstPrinter::printArithExtend</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a2ce2becffb8924f6a1d76eb62e2c3902">llvm::AArch64InstPrinter::printShifter</a>.</p>

</div>
</div>

### getShiftType() {#adff7aee2baba9b9691304bee7e76f574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64_AM::ShiftExtendType llvm::AArch64_AM::getShiftType (unsigned Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getShiftType - Extract the shift type.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>References <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a2f11475361161d9ce95a2f7be74de342">ASR</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a4738a48912fcb1ca44fbe35b8c98ab50">InvalidShiftExtend</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">LSL</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a7e1384a3b7d612a03b54d9c8f2071a04">LSR</a>, <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1a5b297b24d84fef366a94098c36f07c3a">MSL</a> and <a href="#a7e75394a33f6a5897d7a14c0ba5d44f1abb1fa5a6016bfee1580a7b989a454c9a">ROR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa9430ae4ad548095743aa0a26b235d82">llvm::AArch64InstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mccodeemitter-cpp-/aarch64mccodeemitter/#a902e7f80ee2b8750ee2be2fdbafffdba">anonymous{AArch64MCCodeEmitter.cpp}::AArch64MCCodeEmitter::getAddSubImmOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mccodeemitter-cpp-/aarch64mccodeemitter/#acd46b13d132b3a921ef3fb12a448e3e5">anonymous{AArch64MCCodeEmitter.cpp}::AArch64MCCodeEmitter::getImm8OptLsl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a4570ae797be267e31c05d7ab64ceb985">getUsefulBitsFromOrWithShiftedReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#adf3c1940dd03ebf286a0311bd556ccf9">llvm::AArch64InstPrinter::printImm8OptLsl</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a2ce2becffb8924f6a1d76eb62e2c3902">llvm::AArch64InstPrinter::printShifter</a>.</p>

</div>
</div>

### getShiftValue() {#a22f623563f43de6d1aabcdfa9d341031}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64_AM::getShiftValue (unsigned Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getShiftValue - Extract the shift value.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa9430ae4ad548095743aa0a26b235d82">llvm::AArch64InstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64framelowering-cpp-/#a5559902dd138e56d966b85d1a3491ebf">anonymous{AArch64FrameLowering.cpp}::canMergeRegUpdate</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#acdf3f4cb6342e67c42191cf29984df97">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#a5a37e55c5174e78950475941bec87c6c">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::findSuitableCompare</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mccodeemitter-cpp-/aarch64mccodeemitter/#a902e7f80ee2b8750ee2be2fdbafffdba">anonymous{AArch64MCCodeEmitter.cpp}::AArch64MCCodeEmitter::getAddSubImmOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mccodeemitter-cpp-/aarch64mccodeemitter/#acd46b13d132b3a921ef3fb12a448e3e5">anonymous{AArch64MCCodeEmitter.cpp}::AArch64MCCodeEmitter::getImm8OptLsl</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mccodeemitter-cpp-/aarch64mccodeemitter/#aa0e57491b71768868d72a2ef96800a84">anonymous{AArch64MCCodeEmitter.cpp}::AArch64MCCodeEmitter::getMoveVecShifterOpValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a4570ae797be267e31c05d7ab64ceb985">getUsefulBitsFromOrWithShiftedReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a3b7836e8ed50c4986e1ef6e48261750e">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::isMatchingUpdateInsn</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a006d92e5eae5fd3ca76b72ec1b749a1b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergeUpdateInsn</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a763e5d73a932a30d95c888b81f45a0c3">anonymous{AArch64AsmParser.cpp}::AArch64Operand::print</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a8f28c9e40efb457286cf0bac91a9f987">llvm::AArch64InstPrinter::printAddSubImm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#adf3c1940dd03ebf286a0311bd556ccf9">llvm::AArch64InstPrinter::printImm8OptLsl</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a2ce2becffb8924f6a1d76eb62e2c3902">llvm::AArch64InstPrinter::printShifter</a>.</p>

</div>
</div>

### isAdvSIMDModImmType1() {#afc0e820b8853201ef6ff415931806b68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isAdvSIMDModImmType1 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aed120dd6850080b309b6054efd2b142b">tryAdvSIMDModImm32</a>.</p>

</div>
</div>

### isAdvSIMDModImmType10() {#aacafb7aecc0ecc157dd1fbaac53bae38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isAdvSIMDModImmType10 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aa1892421b1a924f86a66c28974d47c7d">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSIMDImmType10</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a52b49fd007d3e59011c1e924579f3a80">tryAdvSIMDModImm64</a>.</p>

</div>
</div>

### isAdvSIMDModImmType11() {#ad56db6bd1cb03dacae870fc6777f6838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isAdvSIMDModImmType11 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 677 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a41506ddab8a425491f9ebf969036eb84">tryAdvSIMDModImmFP</a>.</p>

</div>
</div>

### isAdvSIMDModImmType12() {#ac844d76c3324182cd41105fc61371768}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isAdvSIMDModImmType12 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 727 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a41506ddab8a425491f9ebf969036eb84">tryAdvSIMDModImmFP</a>.</p>

</div>
</div>

### isAdvSIMDModImmType2() {#af6c74fb3a2a8d0cb99feef8744eb3ace}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isAdvSIMDModImmType2 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aed120dd6850080b309b6054efd2b142b">tryAdvSIMDModImm32</a>.</p>

</div>
</div>

### isAdvSIMDModImmType3() {#af9224d46b85d9e2fa60a5e5c77f07556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isAdvSIMDModImmType3 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aed120dd6850080b309b6054efd2b142b">tryAdvSIMDModImm32</a>.</p>

</div>
</div>

### isAdvSIMDModImmType4() {#a2fe53b15d06d979154de9230ffc90a07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isAdvSIMDModImmType4 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aed120dd6850080b309b6054efd2b142b">tryAdvSIMDModImm32</a>.</p>

</div>
</div>

### isAdvSIMDModImmType5() {#a4d810d08a9bc5d3c0ef0d54b1c9eb646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isAdvSIMDModImmType5 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3cce50ef77513b8bd1cbeb48b4d9339d">tryAdvSIMDModImm16</a>.</p>

</div>
</div>

### isAdvSIMDModImmType6() {#aec822bd18b696d033e3fb3a91db5b1ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isAdvSIMDModImmType6 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3cce50ef77513b8bd1cbeb48b4d9339d">tryAdvSIMDModImm16</a>.</p>

</div>
</div>

### isAdvSIMDModImmType7() {#a906b3231e8117e7b6b1ab0cfd9226d1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isAdvSIMDModImmType7 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a91b6b0ccb484e79d3d1558e8d9c12cd8">tryAdvSIMDModImm321s</a>.</p>

</div>
</div>

### isAdvSIMDModImmType8() {#ae2fe7045c79cfc8be9f42ac54a8fca85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isAdvSIMDModImmType8 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a91b6b0ccb484e79d3d1558e8d9c12cd8">tryAdvSIMDModImm321s</a>.</p>

</div>
</div>

### isAdvSIMDModImmType9() {#a2e61bc2a6e0481a74be8bfbbb11ba3aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isAdvSIMDModImmType9 (uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a55e427e6bf5d495e92fbbe9ba86e9990">tryAdvSIMDModImm8</a>.</p>

</div>
</div>

### isAnyMOVWMovAlias() {#a51360b5f47268ba43911ef887318c34c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isAnyMOVWMovAlias (uint64_t Value, int RegWidth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Reference <a href="#a0f78ae6edfd108ae03965c8e49fbabab">isAnyMOVZMovAlias</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ab4e79ecca1f6c9c8b0dcf317d32a4523">llvm::AArch64InstPrinter::printInst</a>.</p>

</div>
</div>

### isAnyMOVZMovAlias() {#a0f78ae6edfd108ae03965c8e49fbabab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isAnyMOVZMovAlias (uint64_t Value, int RegWidth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 831 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="#a51360b5f47268ba43911ef887318c34c">isAnyMOVWMovAlias</a> and <a href="#a178fae9db42f799d5a2c3c4b3819d8bb">isMOVNMovAlias</a>.</p>

</div>
</div>

### isLogicalImmediate() {#a262431cccd14e6063eacc180130a5882}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isLogicalImmediate (uint64_t imm, unsigned regSize)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isLogicalImmediate - Return true if the immediate is valid for a logical immediate instruction of the given register size.</p>


<p>Return false otherwise.</p>


<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Reference <a href="#a2cd3e23b97b495a98c0b723ab18e4d96">processLogicalImmediate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#aca56c12eb63eea9e71e826a1e888b51d">llvm::AArch64TTIImpl::getIntImmCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#ab34dcac5bf06a03d57cd29ba812c13ee">if</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a44820ac394a8f8fc10cdfa8e832fe1ce">if</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a9d689d56ccbeb5bad8afd84d615d31b7">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isLogicalImm</a>, <a href="#a0b94013661adb0a0203a1dba80e27f1b">isSVEMoveMaskPreferredLogicalImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a882ed852a717e7421c4dd8ede4908d92">optimizeLogicalImm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a3b40229ffa0ce512148acc985d56136c">llvm::AArch64TargetLowering::shouldConvertConstantLoadToIntImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a380449a9ad9e4e2d3b6b3fdfa75a64d9">tryBitfieldInsertOpFromOrAndImm</a>.</p>

</div>
</div>

### isMOVNMovAlias() {#a178fae9db42f799d5a2c3c4b3819d8bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isMOVNMovAlias (uint64_t Value, int Shift, int RegWidth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 850 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>References <a href="#a0f78ae6edfd108ae03965c8e49fbabab">isAnyMOVZMovAlias</a> and <a href="#a7a923906a7a2b0e53a9d71fc27c39210">isMOVZMovAlias</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a018eb3f34b1fe02b8d60532cf5713ba7">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMOVNMovAlias</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ab4e79ecca1f6c9c8b0dcf317d32a4523">llvm::AArch64InstPrinter::printInst</a>.</p>

</div>
</div>

### isMOVZMovAlias() {#a7a923906a7a2b0e53a9d71fc27c39210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isMOVZMovAlias (uint64_t Value, int Shift, int RegWidth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 839 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="#a178fae9db42f799d5a2c3c4b3819d8bb">isMOVNMovAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a21f95622afbe879f8b6fab324bb71a17">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMOVZMovAlias</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ab4e79ecca1f6c9c8b0dcf317d32a4523">llvm::AArch64InstPrinter::printInst</a>.</p>

</div>
</div>

### isSVEAddSubImm() {#a2ccd71fca66375c495f8c883988091b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isSVEAddSubImm (int64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if Imm is valid for ADD/SUB.</p>

<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a23b2900efc3dc7b9ab2e4655fd3874ca">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSVEAddSubImm</a>.</p>

</div>
</div>

### isSVECpyImm() {#a99509002d9fccdb280ff2c66af1505f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isSVECpyImm (int64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if Imm is valid for CPY/DUP.</p>

<p>Definition at line 784 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">llvm::max</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a78d9bb4d126d1c4906dfee221ec64e5b">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSVECpyImm</a> and <a href="#a0b94013661adb0a0203a1dba80e27f1b">isSVEMoveMaskPreferredLogicalImmediate</a>.</p>

</div>
</div>

### isSVEMaskOfIdenticalElements() {#a783283846d982f14988fa8c1eb467dd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isSVEMaskOfIdenticalElements (int64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if Imm is the concatenation of a repeating pattern of type T.</p>

<p>Definition at line 777 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad78da75bd1f157e72100f97d1ecdc756">llvm::all_equal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a0b94013661adb0a0203a1dba80e27f1b">isSVEMoveMaskPreferredLogicalImmediate</a>.</p>

</div>
</div>

### isSVEMoveMaskPreferredLogicalImmediate() {#a0b94013661adb0a0203a1dba80e27f1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isSVEMoveMaskPreferredLogicalImmediate (int64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if Imm is valid for DUPM and has no single CPY/DUP equivalent.</p>

<p>Definition at line 814 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="#a262431cccd14e6063eacc180130a5882">isLogicalImmediate</a>, <a href="#a99509002d9fccdb280ff2c66af1505f9">isSVECpyImm</a> and <a href="#a783283846d982f14988fa8c1eb467dd4">isSVEMaskOfIdenticalElements</a>.</p>

</div>
</div>

### isValidDecodeLogicalImmediate() {#a0a33ab78776cbb20a7b285e6f165888c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::isValidDecodeLogicalImmediate (uint64_t val, unsigned regSize)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isValidDecodeLogicalImmediate - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> to see if the logical immediate value in the form "N:immr:imms" (where the immr and imms fields are each 6 bits) is a valid encoding for an integer value with regSize bits.</p>

<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a46b59aec241e0564ca44770f25f2ec71">DecodeLogicalImmInstruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a8791e99741e918b4a6dd4de52c238d04">DecodeSVELogicalImmInstruction</a>.</p>

</div>
</div>

### processLogicalImmediate() {#a2cd3e23b97b495a98c0b723ab18e4d96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64_AM::processLogicalImmediate (uint64_t Imm, unsigned RegSize, uint64_t &amp; Encoding)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>processLogicalImmediate - Determine if an immediate value can be encoded as the immediate operand of a logical instruction for the given register size.</p>


<p>If so, return true with "encoding" set to the encoded value in the form N:immr:imms.</p>


<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d92de57590536d2f254fe5e903e3372">llvm::countl_one</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a239abca11deebf2731206dd41cf43c0e">llvm::countr_one</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a582e08755c7a8d1b0bf6c5dcb765aaa8">llvm::isShiftedMask_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a9c374320ed4e895f9afa199987182bd2">RegSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#a436cd44154cf245c297b6b5a5fac9a84">canUseOrr</a>, <a href="#a832ad315a355f4ddcc32f189f34e28a9">encodeLogicalImmediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-imm/#a77a4e6615fbc6c2bbcf179370dbd0fa9">llvm::AArch64_IMM::expandMOVImm</a>, <a href="#a262431cccd14e6063eacc180130a5882">isLogicalImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#aa20f3eb24c28efa9c93053a733a172c1">tryAndOfLogicalImmediates</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#ab2f723b31c9dbe46610248a047805046">tryEorOfLogicalImmediates</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#ae492dde0ae62ef0c16a80f8b648bae19">tryOrrOfLogicalImmediates</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#a7000ac817f63a64697020f0538311927">trySequenceOfOnes</a>.</p>

</div>
</div>

### ror() {#aa95984b1da1308f393b2c8d292126511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AArch64_AM::ror (uint64_t elt, unsigned size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>


<p>Referenced by <a href="#a1affd6d7e8a280fa6a0b642a6e0734b8">decodeLogicalImmediate</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">AArch64AddressingModes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
