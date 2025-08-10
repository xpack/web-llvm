---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/amdgpu/amdgpumckernelcodet
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `AMDGPUMCKernelCodeT` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::AMDGPU::AMDGPUMCKernelCodeT { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">Target/AMDGPU/Utils/AMDKernelCodeTUtils.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70ffc795ff52901ca0c240337952d1a3">PrintHelper</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> *)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9555171c9b8ab7a4b0a389e1ee43a6d3">AMDGPUMCKernelCodeT</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dfce6025a9fbad86f7dd26156f36912">initDefault</a> (const MCSubtargetInfo *STI, MCContext &amp;Ctx, bool InitMCExpr=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a951e1d6e08b65364350b68b2576bc0d0">validate</a> (const MCSubtargetInfo *STI, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc55d0fc80220516cb35d917277056d7">getMCExprForIndex</a> (int Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3c0ff6c6dac612ecb6bba24cfb0dabc">ParseKernelCodeT</a> (StringRef ID, MCAsmParser &amp;MCParser, raw_ostream &amp;Err)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a26180c2fb2542d3bbbf51b33da6569">EmitKernelCodeT</a> (raw_ostream &amp;OS, MCContext &amp;Ctx, PrintHelper Helper)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a> (MCStreamer &amp;OS, MCContext &amp;Ctx)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e3a1059821543e306d8a488b800d6ef">amd_kernel_code_version_major</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96a78cc694edd824a544a65144e0966f">amd_kernel_code_version_minor</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1550d48ce471038d65cdc99e7aa079fb">amd_machine_kind</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11ad91ca2ce53a02b83c4e6516f906aa">amd_machine_version_major</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d2d89a7f6ccb84afce98a980b9a24e9">amd_machine_version_minor</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34650b99793b6abb03fc301684f041a5">amd_machine_version_stepping</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47848fdaab8c2c3f2a20bbba2fc9dbb0">kernel_code_entry_byte_offset</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfd94f9a358192ff03eddc1e29dddbb6">kernel_code_prefetch_byte_offset</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1421451fa13d0ceb1eb6af3364d18ed">kernel_code_prefetch_byte_size</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8095223b57beaf04b2ff67a4df5d1154">reserved0</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb917a9d73e646aabe02a2ae51ab2872">compute_pgm_resource_registers</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60334426b817b7280c4e457bf1b07e5a">code_properties</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0fd2422e6e17b7c8a02656b58f5f419">workgroup_group_segment_byte_size</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ebf5db333576f482eeb692d029c1864">gds_segment_byte_size</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a162c0bb65c247c3e2981cb954da7ab94">kernarg_segment_byte_size</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89b3b767ff52421c957951ce8873dbc1">workgroup_fbarrier_count</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a098867c47bb0594730938852a2d813f9">reserved_vgpr_first</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f0522a9886e8bb6e358092c95c14ddf">reserved_vgpr_count</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94c31cb52ce04d78c82f70bb35848300">reserved_sgpr_first</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafeb9f25f1366b2eb1bae7dd93105bfd">reserved_sgpr_count</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41e37c0f5332104147659c31ce4585d1">debug_wavefront_private_segment_offset_sgpr</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a657cd112ec48c86b04e6c31da3e4a433">debug_private_segment_buffer_sgpr</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93b2f3da8f8d69f9020213a98c258958">kernarg_segment_alignment</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f5ea62647fa4a50093076ada8479f1d">group_segment_alignment</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a360c4178ea6241a6944bb35310442be0">private_segment_alignment</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22639e6edddf8f7f4f4a0270074348d8">wavefront_size</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9ffee3eb8c99a1cced5391a0c8ab395">call_convention</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad890cb776ec7cb5abc880a3c3635a181">reserved3</a>[12] = {0}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7ef8e27c750da0a9d3fdb6391057e71">runtime_loader_kernel_symbol</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a500da7c24840e8261487100f64211056">control_directives</a>[16] = {0}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aece145a2c1ba2f98ec0e96cc33efa8dd">compute_pgm_resource1_registers</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ab04bfdb9f1b4ab35ae580a098326fc">compute_pgm_resource2_registers</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1cfc4700351bc2051488c0f1315272c">is_dynamic_callstack</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96c7ab22693cd0aebc5795ef720f3e69">wavefront_sgpr_count</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab491a7842801afce25431ec875df34da">workitem_vgpr_count</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56fa63a65888bd0e08a4c4b2bc80abcf">workitem_private_segment_byte_size</a> = nullptr</td>
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


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### PrintHelper {#a70ffc795ff52901ca0c240337952d1a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AMDGPU::AMDGPUMCKernelCodeT::PrintHelper = 
      function_ref&lt;void(const MCExpr *, raw_ostream &amp;, const MCAsmInfo *)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AMDGPUMCKernelCodeT() {#a9555171c9b8ab7a4b0a389e1ee43a6d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::AMDGPUMCKernelCodeT::AMDGPUMCKernelCodeT ()</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a9dfce6025a9fbad86f7dd26156f36912">initDefault</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### EmitKernelCodeT() {#a7a26180c2fb2542d3bbbf51b33da6569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUMCKernelCodeT::EmitKernelCodeT (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="#a70ffc795ff52901ca0c240337952d1a3">PrintHelper</a> Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>, definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp">AMDKernelCodeTUtils.cpp</a>.</p>


<p>References <a href="#adc55d0fc80220516cb35d917277056d7">getMCExprForIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp/#ad59ca8a8dc03bd18b7c3a7c9a6eb4c83">printAmdKernelCodeField</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### EmitKernelCodeT() {#a766a8f22f00b2895f373b0328840e760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUMCKernelCodeT::EmitKernelCodeT (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>, definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp">AMDKernelCodeTUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h/#ae598a8419230cf7b6ff36928295c4246a28a75ca1415ef6ebd7cd3defa9f89f04">AMD_CODE_PROPERTY_IS_DYNAMIC_CALLSTACK_SHIFT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h/#ae598a8419230cf7b6ff36928295c4246a54fc8ea8bf4e2e3a86176aab4ac1577b">AMD_CODE_PROPERTY_IS_DYNAMIC_CALLSTACK_WIDTH</a>, <a href="#a6e3a1059821543e306d8a488b800d6ef">amd_kernel_code_version_major</a>, <a href="#a96a78cc694edd824a544a65144e0966f">amd_kernel_code_version_minor</a>, <a href="#a1550d48ce471038d65cdc99e7aa079fb">amd_machine_kind</a>, <a href="#a11ad91ca2ce53a02b83c4e6516f906aa">amd_machine_version_major</a>, <a href="#a7d2d89a7f6ccb84afce98a980b9a24e9">amd_machine_version_minor</a>, <a href="#a34650b99793b6abb03fc301684f041a5">amd_machine_version_stepping</a>, <a href="#ab9ffee3eb8c99a1cced5391a0c8ab395">call_convention</a>, <a href="#a60334426b817b7280c4e457bf1b07e5a">code_properties</a>, <a href="#aece145a2c1ba2f98ec0e96cc33efa8dd">compute_pgm_resource1_registers</a>, <a href="#a7ab04bfdb9f1b4ab35ae580a098326fc">compute_pgm_resource2_registers</a>, <a href="#afb917a9d73e646aabe02a2ae51ab2872">compute_pgm_resource_registers</a>, <a href="#a500da7c24840e8261487100f64211056">control_directives</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a6b303b433f43b901194dbf17adfb562c">llvm::MCBinaryExpr::createOr</a>, <a href="#a657cd112ec48c86b04e6c31da3e4a433">debug_private_segment_buffer_sgpr</a>, <a href="#a41e37c0f5332104147659c31ce4585d1">debug_wavefront_private_segment_offset_sgpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af94e84eca402017c9ce57b7b4c4104e3">llvm::MCStreamer::emitBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a971830cc1546210be8cc86fa568be8d0">llvm::MCStreamer::emitIntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="#a7ebf5db333576f482eeb692d029c1864">gds_segment_byte_size</a>, <a href="#a7f5ea62647fa4a50093076ada8479f1d">group_segment_alignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b622c469acc130c9a500b85b1473ef3">llvm::Hi_32</a>, <a href="#ac1cfc4700351bc2051488c0f1315272c">is_dynamic_callstack</a>, <a href="#a93b2f3da8f8d69f9020213a98c258958">kernarg_segment_alignment</a>, <a href="#a162c0bb65c247c3e2981cb954da7ab94">kernarg_segment_byte_size</a>, <a href="#a47848fdaab8c2c3f2a20bbba2fc9dbb0">kernel_code_entry_byte_offset</a>, <a href="#acfd94f9a358192ff03eddc1e29dddbb6">kernel_code_prefetch_byte_offset</a>, <a href="#ab1421451fa13d0ceb1eb6af3364d18ed">kernel_code_prefetch_byte_size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a901112c493d3827cda924430a6fbc9f4">llvm::Lo_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5f3ff39c7ddc47c851a92a89a6c68e3d">llvm::AMDGPU::maskShiftSet</a>, <a href="#a360c4178ea6241a6944bb35310442be0">private_segment_alignment</a>, <a href="#a8095223b57beaf04b2ff67a4df5d1154">reserved0</a>, <a href="#ad890cb776ec7cb5abc880a3c3635a181">reserved3</a>, <a href="#aafeb9f25f1366b2eb1bae7dd93105bfd">reserved_sgpr_count</a>, <a href="#a94c31cb52ce04d78c82f70bb35848300">reserved_sgpr_first</a>, <a href="#a0f0522a9886e8bb6e358092c95c14ddf">reserved_vgpr_count</a>, <a href="#a098867c47bb0594730938852a2d813f9">reserved_vgpr_first</a>, <a href="#ad7ef8e27c750da0a9d3fdb6391057e71">runtime_loader_kernel_symbol</a>, <a href="#a96c7ab22693cd0aebc5795ef720f3e69">wavefront_sgpr_count</a>, <a href="#a22639e6edddf8f7f4f4a0270074348d8">wavefront_size</a>, <a href="#a89b3b767ff52421c957951ce8873dbc1">workgroup_fbarrier_count</a>, <a href="#ad0fd2422e6e17b7c8a02656b58f5f419">workgroup_group_segment_byte_size</a>, <a href="#a56fa63a65888bd0e08a4c4b2bc80abcf">workitem_private_segment_byte_size</a> and <a href="#ab491a7842801afce25431ec875df34da">workitem_vgpr_count</a>.</p>

</div>
</div>

### getMCExprForIndex() {#adc55d0fc80220516cb35d917277056d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr *&amp; AMDGPUMCKernelCodeT::getMCExprForIndex (int Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>, definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp">AMDKernelCodeTUtils.cpp</a>.</p>


<p>Referenced by <a href="#a7a26180c2fb2542d3bbbf51b33da6569">EmitKernelCodeT</a> and <a href="#ad3c0ff6c6dac612ecb6bba24cfb0dabc">ParseKernelCodeT</a>.</p>

</div>
</div>

### initDefault() {#a9dfce6025a9fbad86f7dd26156f36912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUMCKernelCodeT::initDefault (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, bool InitMCExpr=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>, definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp">AMDKernelCodeTUtils.cpp</a>.</p>


<p>References <a href="#a9555171c9b8ab7a4b0a389e1ee43a6d3">AMDGPUMCKernelCodeT</a>, <a href="#aece145a2c1ba2f98ec0e96cc33efa8dd">compute_pgm_resource1_registers</a>, <a href="#a7ab04bfdb9f1b4ab35ae580a098326fc">compute_pgm_resource2_registers</a>, <a href="#afb917a9d73e646aabe02a2ae51ab2872">compute_pgm_resource_registers</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b622c469acc130c9a500b85b1473ef3">llvm::Hi_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab8a9a35e11965a5192429b791b2b25f5">llvm::AMDGPU::initDefaultAMDKernelCodeT</a>, <a href="#ac1cfc4700351bc2051488c0f1315272c">is_dynamic_callstack</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a901112c493d3827cda924430a6fbc9f4">llvm::Lo_32</a>, <a href="#a96c7ab22693cd0aebc5795ef720f3e69">wavefront_sgpr_count</a>, <a href="#a56fa63a65888bd0e08a4c4b2bc80abcf">workitem_private_segment_byte_size</a> and <a href="#ab491a7842801afce25431ec875df34da">workitem_vgpr_count</a>.</p>

</div>
</div>

### ParseKernelCodeT() {#ad3c0ff6c6dac612ecb6bba24cfb0dabc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUMCKernelCodeT::ParseKernelCodeT (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ID, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a> &amp; MCParser, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>, definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp">AMDKernelCodeTUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp/#af84e76651e34842ce3d8f63acb485b42">get_amd_kernel_code_t_FieldIndex</a>, <a href="#adc55d0fc80220516cb35d917277056d7">getMCExprForIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp/#a7a374b13bc9d10c9298dd591ee50fc82">parseExpr</a>.</p>

</div>
</div>

### validate() {#a951e1d6e08b65364350b68b2576bc0d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUMCKernelCodeT::validate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>, definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp">AMDKernelCodeTUtils.cpp</a>.</p>


<p>References <a href="#aece145a2c1ba2f98ec0e96cc33efa8dd">compute_pgm_resource1_registers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a69061dba082295bcb1266f58e1b9134c">G_00B848_DX10_CLAMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a20f35035ff86b48d108811731b5e4237">G_00B848_FWD_PROGRESS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a423ca74d9a483dd6548623712d8bb0bb">G_00B848_IEEE_MODE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a2af86f0cd01fc93df0a92ecc884e3186">G_00B848_MEM_ORDERED</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#abb34f354922eea8a73e0acebaf29a336">G_00B848_WGP_MODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab07da835cd8eddcfffcfb4192dff59a6">llvm::AMDGPU::isGFX10Plus</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a318d59d6a50364a460b64bb7ad1f17d0">llvm::AMDGPU::isGFX12Plus</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#ae3bd05a52450589489fbb3602ad95530">llvm::AMDGPUAsmPrinter::emitFunctionBodyStart</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### amd\_kernel\_code\_version\_major {#a6e3a1059821543e306d8a488b800d6ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPU::AMDGPUMCKernelCodeT::amd_kernel_code_version_major = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab8a9a35e11965a5192429b791b2b25f5">llvm::AMDGPU::initDefaultAMDKernelCodeT</a>.</p>

</div>
</div>

### amd\_kernel\_code\_version\_minor {#a96a78cc694edd824a544a65144e0966f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPU::AMDGPUMCKernelCodeT::amd_kernel_code_version_minor = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab8a9a35e11965a5192429b791b2b25f5">llvm::AMDGPU::initDefaultAMDKernelCodeT</a>.</p>

</div>
</div>

### amd\_machine\_kind {#a1550d48ce471038d65cdc99e7aa079fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::AMDGPU::AMDGPUMCKernelCodeT::amd_machine_kind = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab8a9a35e11965a5192429b791b2b25f5">llvm::AMDGPU::initDefaultAMDKernelCodeT</a>.</p>

</div>
</div>

### amd\_machine\_version\_major {#a11ad91ca2ce53a02b83c4e6516f906aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::AMDGPU::AMDGPUMCKernelCodeT::amd_machine_version_major = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab8a9a35e11965a5192429b791b2b25f5">llvm::AMDGPU::initDefaultAMDKernelCodeT</a>.</p>

</div>
</div>

### amd\_machine\_version\_minor {#a7d2d89a7f6ccb84afce98a980b9a24e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::AMDGPU::AMDGPUMCKernelCodeT::amd_machine_version_minor = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab8a9a35e11965a5192429b791b2b25f5">llvm::AMDGPU::initDefaultAMDKernelCodeT</a>.</p>

</div>
</div>

### amd\_machine\_version\_stepping {#a34650b99793b6abb03fc301684f041a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::AMDGPU::AMDGPUMCKernelCodeT::amd_machine_version_stepping = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab8a9a35e11965a5192429b791b2b25f5">llvm::AMDGPU::initDefaultAMDKernelCodeT</a>.</p>

</div>
</div>

### call\_convention {#ab9ffee3eb8c99a1cced5391a0c8ab395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::AMDGPU::AMDGPUMCKernelCodeT::call_convention = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab8a9a35e11965a5192429b791b2b25f5">llvm::AMDGPU::initDefaultAMDKernelCodeT</a>.</p>

</div>
</div>

### code\_properties {#a60334426b817b7280c4e457bf1b07e5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPU::AMDGPUMCKernelCodeT::code_properties = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab8a9a35e11965a5192429b791b2b25f5">llvm::AMDGPU::initDefaultAMDKernelCodeT</a>.</p>

</div>
</div>

### compute\_pgm\_resource\_registers {#afb917a9d73e646aabe02a2ae51ab2872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AMDGPU::AMDGPUMCKernelCodeT::compute_pgm_resource_registers = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a>, <a href="#a9dfce6025a9fbad86f7dd26156f36912">initDefault</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab8a9a35e11965a5192429b791b2b25f5">llvm::AMDGPU::initDefaultAMDKernelCodeT</a>.</p>

</div>
</div>

### compute\_pgm\_resource1\_registers {#aece145a2c1ba2f98ec0e96cc33efa8dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::AMDGPU::AMDGPUMCKernelCodeT::compute_pgm_resource1_registers = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a>, <a href="#a9dfce6025a9fbad86f7dd26156f36912">initDefault</a> and <a href="#a951e1d6e08b65364350b68b2576bc0d0">validate</a>.</p>

</div>
</div>

### compute\_pgm\_resource2\_registers {#a7ab04bfdb9f1b4ab35ae580a098326fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::AMDGPU::AMDGPUMCKernelCodeT::compute_pgm_resource2_registers = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a> and <a href="#a9dfce6025a9fbad86f7dd26156f36912">initDefault</a>.</p>

</div>
</div>

### control\_directives {#a500da7c24840e8261487100f64211056}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AMDGPU::AMDGPUMCKernelCodeT::control_directives[16] = {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a>.</p>

</div>
</div>

### debug\_private\_segment\_buffer\_sgpr {#a657cd112ec48c86b04e6c31da3e4a433}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::AMDGPU::AMDGPUMCKernelCodeT::debug_private_segment_buffer_sgpr = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a>.</p>

</div>
</div>

### debug\_wavefront\_private\_segment\_offset\_sgpr {#a41e37c0f5332104147659c31ce4585d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::AMDGPU::AMDGPUMCKernelCodeT::debug_wavefront_private_segment_offset_sgpr = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a>.</p>

</div>
</div>

### gds\_segment\_byte\_size {#a7ebf5db333576f482eeb692d029c1864}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPU::AMDGPUMCKernelCodeT::gds_segment_byte_size = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a>.</p>

</div>
</div>

### group\_segment\_alignment {#a7f5ea62647fa4a50093076ada8479f1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AMDGPU::AMDGPUMCKernelCodeT::group_segment_alignment = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab8a9a35e11965a5192429b791b2b25f5">llvm::AMDGPU::initDefaultAMDKernelCodeT</a>.</p>

</div>
</div>

### is\_dynamic\_callstack {#ac1cfc4700351bc2051488c0f1315272c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::AMDGPU::AMDGPUMCKernelCodeT::is_dynamic_callstack = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a> and <a href="#a9dfce6025a9fbad86f7dd26156f36912">initDefault</a>.</p>

</div>
</div>

### kernarg\_segment\_alignment {#a93b2f3da8f8d69f9020213a98c258958}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AMDGPU::AMDGPUMCKernelCodeT::kernarg_segment_alignment = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab8a9a35e11965a5192429b791b2b25f5">llvm::AMDGPU::initDefaultAMDKernelCodeT</a>.</p>

</div>
</div>

### kernarg\_segment\_byte\_size {#a162c0bb65c247c3e2981cb954da7ab94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AMDGPU::AMDGPUMCKernelCodeT::kernarg_segment_byte_size = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a>.</p>

</div>
</div>

### kernel\_code\_entry\_byte\_offset {#a47848fdaab8c2c3f2a20bbba2fc9dbb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AMDGPU::AMDGPUMCKernelCodeT::kernel_code_entry_byte_offset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab8a9a35e11965a5192429b791b2b25f5">llvm::AMDGPU::initDefaultAMDKernelCodeT</a>.</p>

</div>
</div>

### kernel\_code\_prefetch\_byte\_offset {#acfd94f9a358192ff03eddc1e29dddbb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AMDGPU::AMDGPUMCKernelCodeT::kernel_code_prefetch_byte_offset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a>.</p>

</div>
</div>

### kernel\_code\_prefetch\_byte\_size {#ab1421451fa13d0ceb1eb6af3364d18ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AMDGPU::AMDGPUMCKernelCodeT::kernel_code_prefetch_byte_size = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a>.</p>

</div>
</div>

### private\_segment\_alignment {#a360c4178ea6241a6944bb35310442be0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AMDGPU::AMDGPUMCKernelCodeT::private_segment_alignment = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab8a9a35e11965a5192429b791b2b25f5">llvm::AMDGPU::initDefaultAMDKernelCodeT</a>.</p>

</div>
</div>

### reserved\_sgpr\_count {#aafeb9f25f1366b2eb1bae7dd93105bfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::AMDGPU::AMDGPUMCKernelCodeT::reserved_sgpr_count = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a>.</p>

</div>
</div>

### reserved\_sgpr\_first {#a94c31cb52ce04d78c82f70bb35848300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::AMDGPU::AMDGPUMCKernelCodeT::reserved_sgpr_first = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a>.</p>

</div>
</div>

### reserved\_vgpr\_count {#a0f0522a9886e8bb6e358092c95c14ddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::AMDGPU::AMDGPUMCKernelCodeT::reserved_vgpr_count = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a>.</p>

</div>
</div>

### reserved\_vgpr\_first {#a098867c47bb0594730938852a2d813f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::AMDGPU::AMDGPUMCKernelCodeT::reserved_vgpr_first = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a>.</p>

</div>
</div>

### reserved0 {#a8095223b57beaf04b2ff67a4df5d1154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AMDGPU::AMDGPUMCKernelCodeT::reserved0 = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a>.</p>

</div>
</div>

### reserved3 {#ad890cb776ec7cb5abc880a3c3635a181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AMDGPU::AMDGPUMCKernelCodeT::reserved3[12] = {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a>.</p>

</div>
</div>

### runtime\_loader\_kernel\_symbol {#ad7ef8e27c750da0a9d3fdb6391057e71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AMDGPU::AMDGPUMCKernelCodeT::runtime_loader_kernel_symbol = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a>.</p>

</div>
</div>

### wavefront\_sgpr\_count {#a96c7ab22693cd0aebc5795ef720f3e69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::AMDGPU::AMDGPUMCKernelCodeT::wavefront_sgpr_count = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a> and <a href="#a9dfce6025a9fbad86f7dd26156f36912">initDefault</a>.</p>

</div>
</div>

### wavefront\_size {#a22639e6edddf8f7f4f4a0270074348d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AMDGPU::AMDGPUMCKernelCodeT::wavefront_size = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab8a9a35e11965a5192429b791b2b25f5">llvm::AMDGPU::initDefaultAMDKernelCodeT</a>.</p>

</div>
</div>

### workgroup\_fbarrier\_count {#a89b3b767ff52421c957951ce8873dbc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPU::AMDGPUMCKernelCodeT::workgroup_fbarrier_count = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a>.</p>

</div>
</div>

### workgroup\_group\_segment\_byte\_size {#ad0fd2422e6e17b7c8a02656b58f5f419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPU::AMDGPUMCKernelCodeT::workgroup_group_segment_byte_size = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a>.</p>

</div>
</div>

### workitem\_private\_segment\_byte\_size {#a56fa63a65888bd0e08a4c4b2bc80abcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::AMDGPU::AMDGPUMCKernelCodeT::workitem_private_segment_byte_size = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a> and <a href="#a9dfce6025a9fbad86f7dd26156f36912">initDefault</a>.</p>

</div>
</div>

### workitem\_vgpr\_count {#ab491a7842801afce25431ec875df34da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::AMDGPU::AMDGPUMCKernelCodeT::workitem_vgpr_count = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a>.</p>


<p>Referenced by <a href="#a766a8f22f00b2895f373b0328840e760">EmitKernelCodeT</a> and <a href="#a9dfce6025a9fbad86f7dd26156f36912">initDefault</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp">AMDKernelCodeTUtils.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-h">AMDKernelCodeTUtils.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
