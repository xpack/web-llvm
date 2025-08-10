---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/amd-kernel-code-t
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `amd_kernel_code_t` Struct

<p>AMD Kernel Code Object (<a href="/web-llvm/docs/api/structs/amd-kernel-code-t">amd_kernel_code_t</a>). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct amd_kernel_code_t { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">Target/AMDGPU/AMDKernelCodeT.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69b3062747791cdac6a750dda916f69b">amd_kernel_code_version_major</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8a4325bdbe341cbe35667260d0cf612">amd_kernel_code_version_minor</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1776bdb052a121eea5af309942f9039c">amd_machine_kind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83a6743132dd0569a29101b5ea75ecc0">amd_machine_version_major</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12b6fd60f05bb2b48109c695d11e4b9c">amd_machine_version_minor</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac32688254d6765473b622910e45dba0e">amd_machine_version_stepping</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d4f73b89b79246bd80c7e70ade9dcfd">kernel_code_entry_byte_offset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Byte offset (possibly negative) from start of <a href="/web-llvm/docs/api/structs/amd-kernel-code-t">amd_kernel_code_t</a> object to kernel's entry point instruction. <a href="#a8d4f73b89b79246bd80c7e70ade9dcfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eee8a5ffadb28eca3f86b1d71abb956">kernel_code_prefetch_byte_offset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Range of bytes to consider prefetching expressed as an offset and size. <a href="#a8eee8a5ffadb28eca3f86b1d71abb956">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae19ee952d54955cc0b116bf491fbbdb6">kernel_code_prefetch_byte_size</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adecf388ad5ec215ace4396e00db4a8ac">reserved0</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reserved. Must be 0. <a href="#adecf388ad5ec215ace4396e00db4a8ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe887ee8071cec14eb579fdaba4e5fbf">compute_pgm_resource_registers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Shader program settings for CS. <a href="#afe887ee8071cec14eb579fdaba4e5fbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34a391217195263371f11ba2f8219479">code_properties</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Code properties. <a href="#a34a391217195263371f11ba2f8219479">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad74c415c7d3e3642886adcfd8619d11b">workitem_private_segment_byte_size</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The amount of memory required for the combined private, spill and arg segments for a work-item in bytes. <a href="#ad74c415c7d3e3642886adcfd8619d11b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a4649b6a04374eaaf4bc4ef80053264">workgroup_group_segment_byte_size</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The amount of group segment memory required by a work-group in bytes. <a href="#a8a4649b6a04374eaaf4bc4ef80053264">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c63fe3bc77fc8e389e09fcfefd4f693">gds_segment_byte_size</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of byte of GDS required by kernel dispatch. <a href="#a8c63fe3bc77fc8e389e09fcfefd4f693">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae197ddae3e0ec48aaf7ecdfa238d385a">kernarg_segment_byte_size</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The size in bytes of the kernarg segment that holds the values of the arguments to the kernel. <a href="#ae197ddae3e0ec48aaf7ecdfa238d385a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7b9ca2595bcadf009e3e8cec76039b1">workgroup_fbarrier_count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of fbarrier's used in the kernel and all functions it calls. <a href="#af7b9ca2595bcadf009e3e8cec76039b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b8d4c303b7a4c5102da8dc27a45a3ef">wavefront_sgpr_count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of scalar registers used by a wavefront. <a href="#a8b8d4c303b7a4c5102da8dc27a45a3ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13e3cc02a4f9ed0ad17dc6a427c8cfa6">workitem_vgpr_count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of vector registers used by each work-item. <a href="#a13e3cc02a4f9ed0ad17dc6a427c8cfa6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1db63c4debd90bffd965037be2dd2419">reserved_vgpr_first</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If reserved_vgpr_count is 0 then must be 0. <a href="#a1db63c4debd90bffd965037be2dd2419">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6be335b99bc919616ee2e7f979e4521b">reserved_vgpr_count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of consecutive VGPRs reserved by the client. <a href="#a6be335b99bc919616ee2e7f979e4521b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73a7429830686ee698c07843a92a765b">reserved_sgpr_first</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If reserved_sgpr_count is 0 then must be 0. <a href="#a73a7429830686ee698c07843a92a765b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd4b8bd479ae906c9830cd862d35fd1e">reserved_sgpr_count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of consecutive SGPRs reserved by the client. <a href="#afd4b8bd479ae906c9830cd862d35fd1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa83aedabe38cdb3d6943d6cb1f6b1a4">debug_wavefront_private_segment_offset_sgpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If is_debug_supported is 0 then must be 0. <a href="#afa83aedabe38cdb3d6943d6cb1f6b1a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af68c1702d9f26c793dd848c8765685f9">debug_private_segment_buffer_sgpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If is_debug_supported is 0 then must be 0. <a href="#af68c1702d9f26c793dd848c8765685f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a701ca94d346f682b471cb0648543e23e">kernarg_segment_alignment</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum byte alignment of variables used by the kernel in the specified memory segment. <a href="#a701ca94d346f682b471cb0648543e23e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f1b54ed94c72f92b98e6c5a36413d0b">group_segment_alignment</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f4bdeb2251ae4637ff3aa9ba109e48e">private_segment_alignment</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71c743526930a3412ac30725b307bd77">wavefront_size</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wavefront size expressed as a power of two. <a href="#a71c743526930a3412ac30725b307bd77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab57d5ee699912ac205d90dbeefaa2407">call_convention</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6afa9ab97cc0d46bf10b1b8739bd7767">reserved3</a>[12]</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b0cf6bce1e464a818f811b4a671fd24">runtime_loader_kernel_symbol</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5e524fb8cae5e05a0a1340b24f9337e">control_directives</a>[16]</td>
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

<p>AMD Kernel Code Object (<a href="/web-llvm/docs/api/structs/amd-kernel-code-t">amd_kernel_code_t</a>).</p>


<p>GPU CP uses the AMD Kernel Code Object to set up the hardware to execute the kernel dispatch.</p>


<p>Initial Kernel Register State.</p>


<p>Initial kernel register state will be set up by CP/SPI prior to the start of execution of every wavefront. This is limited by the constraints of the current hardware.</p>


<p>The order of the SGPR registers is defined, but the Finalizer can specify which ones are actually setup in the <a href="/web-llvm/docs/api/structs/amd-kernel-code-t">amd_kernel_code_t</a> object using the enable_sgpr_* bit fields. The register numbers used for enabled registers are dense starting at SGPR0: the first enabled register is SGPR0, the next enabled register is SGPR1 etc.; disabled registers do not have an SGPR number.</p>


<p>The initial SGPRs comprise up to 16 User SRGPs that are set up by CP and apply to all waves of the grid. It is possible to specify more than 16 User SGPRs using the enable_sgpr_* bit fields, in which case only the first 16 are actually initialized. These are then immediately followed by the System SGPRs that are set up by ADC/SPI and can have different values for each wave of the grid dispatch.</p>


<p>SGPR register initial state is defined as follows:</p>


<p>Private Segment Buffer (enable_sgpr_private_segment_buffer): Number of User SGPR registers: 4. V# that can be used, together with Scratch Wave Offset as an offset, to access the Private/Spill/Arg segments using a segment address. It must be set as follows:</p>


<ul class="doxyList ">
<li>Base address: of the scratch memory area used by the dispatch. It does not include the scratch wave offset. It will be the per process SH_HIDDEN_PRIVATE_BASE_VMID plus any offset from this dispatch (for example there may be a per pipe offset, or per AQL Queue offset).</li>
<li>Stride + data_format: Element Size * Index Stride (???)</li>
<li>Cache swizzle: ???</li>
<li>Swizzle enable: SH_STATIC_MEM_CONFIG.SWIZZLE_ENABLE (must be 1 for scratch)</li>
<li>Num records: Flat Scratch Work Item Size / Element Size (???)</li>
<li>Dst_sel_*: ???</li>
<li>Num_format: ???</li>
<li>Element_size: SH_STATIC_MEM_CONFIG.ELEMENT_SIZE (will be DWORD, must agree with amd_kernel_code_t.privateElementSize)</li>
<li>Index_stride: SH_STATIC_MEM_CONFIG.INDEX_STRIDE (will be 64 as must be number of wavefront lanes for scratch, must agree with amd_kernel_code_t.wavefrontSize)</li>
<li>Add tid enable: 1</li>
<li>ATC: from SH_MEM_CONFIG.PRIVATE_ATC,</li>
<li>Hash_enable: ???</li>
<li>Heap: ???</li>
<li>Mtype: from SH_STATIC_MEM_CONFIG.PRIVATE_MTYPE</li>
<li>Type: 0 (a buffer) (???)</li>
</ul>

<p>Dispatch Ptr (enable_sgpr_dispatch_ptr): Number of User SGPR registers: 2. 64 bit address of AQL dispatch packet for kernel actually executing.</p>


<p>Queue Ptr (enable_sgpr_queue_ptr): Number of User SGPR registers: 2. 64 bit address of AmdQueue object for AQL queue on which the dispatch packet was queued.</p>


<p>Kernarg Segment Ptr (enable_sgpr_kernarg_segment_ptr): Number of User SGPR registers: 2. 64 bit address of Kernarg segment. This is directly copied from the kernargPtr in the dispatch packet. Having CP load it once avoids loading it at the beginning of every wavefront.</p>


<p>Dispatch Id (enable_sgpr_dispatch_id): Number of User SGPR registers: 2. 64 bit Dispatch ID of the dispatch packet being executed.</p>


<p>Flat Scratch Init (enable_sgpr_flat_scratch_init): Number of User SGPR registers: 2. This is 2 SGPRs.</p>


<p>For CI/VI: The first SGPR is a 32 bit byte offset from SH_MEM_HIDDEN_PRIVATE_BASE to base of memory for scratch for this dispatch. This is the same offset used in computing the Scratch Segment Buffer base address. The value of Scratch Wave Offset must be added by the kernel code and moved to SGPRn-4 for use as the FLAT SCRATCH BASE in flat memory instructions.</p>


<p>The second SGPR is 32 bit byte size of a single work-item's scratch memory usage. This is directly loaded from the dispatch packet Private Segment Byte Size and rounded up to a multiple of DWORD.</p>


<div class="doxyXrefSect">
<dl class="doxyXrefSectList">
<dt class="doxyXrefSectTitle"><a href=/web-llvm/docs/api/pages/todo/#_todo000014>Todo</a></dt>
<dd class="doxyXrefSectDescription">
<p>[Does CP need to round this to &gt;4 byte alignment?]</p>
</dd>
</dl>
</div>

<p>The kernel code must move to SGPRn-3 for use as the FLAT SCRATCH SIZE in flat memory instructions. Having CP load it once avoids loading it at the beginning of every wavefront.</p>


<p>For PI: This is the 64 bit base address of the scratch backing memory for allocated by CP for this dispatch.</p>


<p>Private Segment Size (enable_sgpr_private_segment_size): Number of User SGPR registers: 1. The 32 bit byte size of a single work-item's scratch memory allocation. This is the value from the dispatch packet. Private Segment Byte Size rounded up by CP to a multiple of DWORD.</p>


<div class="doxyXrefSect">
<dl class="doxyXrefSectList">
<dt class="doxyXrefSectTitle"><a href=/web-llvm/docs/api/pages/todo/#_todo000015>Todo</a></dt>
<dd class="doxyXrefSectDescription">
<p>[Does CP need to round this to &gt;4 byte alignment?]</p>
</dd>
</dl>
</div>

<p>Having CP load it once avoids loading it at the beginning of every wavefront.</p>


<div class="doxyXrefSect">
<dl class="doxyXrefSectList">
<dt class="doxyXrefSectTitle"><a href=/web-llvm/docs/api/pages/todo/#_todo000016>Todo</a></dt>
<dd class="doxyXrefSectDescription">
<p>[This will not be used for CI/VI since it is the same value as the second SGPR of Flat Scratch Init. However, it is need for PI which changes meaning of Flat Scratchg Init..]</p>
</dd>
</dl>
</div>

<p>Grid Work-Group Count X (enable_sgpr_grid_workgroup_count_x): Number of User SGPR registers: 1. 32 bit count of the number of work-groups in the X dimension for the grid being executed. Computed from the fields in the HsaDispatchPacket as ((gridSize.x+workgroupSize.x-1)/workgroupSize.x).</p>


<p>Grid Work-Group Count Y (enable_sgpr_grid_workgroup_count_y): Number of User SGPR registers: 1. 32 bit count of the number of work-groups in the Y dimension for the grid being executed. Computed from the fields in the HsaDispatchPacket as ((gridSize.y+workgroupSize.y-1)/workgroupSize.y).</p>


<p>Only initialized if &lt;16 previous SGPRs initialized.</p>


<p>Grid Work-Group Count Z (enable_sgpr_grid_workgroup_count_z): Number of User SGPR registers: 1. 32 bit count of the number of work-groups in the Z dimension for the grid being executed. Computed from the fields in the HsaDispatchPacket as ((gridSize.z+workgroupSize.z-1)/workgroupSize.z).</p>


<p>Only initialized if &lt;16 previous SGPRs initialized.</p>


<p>Work-Group Id X (enable_sgpr_workgroup_id_x): Number of System SGPR registers: 1. 32 bit work group id in X dimension of grid for wavefront. Always present.</p>


<p>Work-Group Id Y (enable_sgpr_workgroup_id_y): Number of System SGPR registers: 1. 32 bit work group id in Y dimension of grid for wavefront.</p>


<p>Work-Group Id Z (enable_sgpr_workgroup_id_z): Number of System SGPR registers: 1. 32 bit work group id in Z dimension of grid for wavefront. If present then Work-group Id Y will also be present</p>


<p>Work-Group Info (enable_sgpr_workgroup_info): Number of System SGPR registers: 1. {first_wave, 14'b0000, ordered_append_term[10:0], threadgroup_size_in_waves[5:0]}</p>


<p>Private Segment Wave Byte Offset (enable_sgpr_private_segment_wave_byte_offset): Number of System SGPR registers: 1. 32 bit byte offset from base of dispatch scratch base. Must be used as an offset with Private/Spill/Arg segment address when using Scratch Segment Buffer. It must be added to Flat Scratch Offset if setting up FLAT SCRATCH for flat addressing.</p>


<p>The order of the VGPR registers is defined, but the Finalizer can specify which ones are actually setup in the <a href="/web-llvm/docs/api/structs/amd-kernel-code-t">amd_kernel_code_t</a> object using the enableVgpr* bit fields. The register numbers used for enabled registers are dense starting at VGPR0: the first enabled register is VGPR0, the next enabled register is VGPR1 etc.; disabled registers do not have an VGPR number.</p>


<p>VGPR register initial state is defined as follows:</p>


<p>Work-Item Id X (always initialized): Number of registers: 1. 32 bit work item id in X dimension of work-group for wavefront lane.</p>


<p>Work-Item Id X (enable_vgpr_workitem_id &gt; 0): Number of registers: 1. 32 bit work item id in Y dimension of work-group for wavefront lane.</p>


<p>Work-Item Id X (enable_vgpr_workitem_id &gt; 0): Number of registers: 1. 32 bit work item id in Z dimension of work-group for wavefront lane.</p>


<p>The setting of registers is being done by existing GPU hardware as follows: 1) SGPRs before the Work-Group Ids are set by CP using the 16 User Data registers. 2) Work-group Id registers X, Y, Z are set by SPI which supports any combination including none. 3) Scratch Wave Offset is also set by SPI which is why its value cannot be added into the value Flat Scratch Offset which would avoid the Finalizer generated prolog having to do the add. 4) The VGPRs are set by SPI which only supports specifying either (X), (X, Y) or (X, Y, Z).</p>


<p>Flat Scratch Dispatch Offset and Flat Scratch Size are adjacent SGRRs so they can be moved as a 64 bit value to the hardware required SGPRn-3 and SGPRn-4 respectively using the Finalizer ?FLAT_SCRATCH? Register.</p>


<p>The global segment can be accessed either using flat operations or buffer operations. If buffer operations are used then the Global Buffer used to access HSAIL Global/Readonly/Kernarg (which are combine) segments using a segment address is not passed into the kernel code by CP since its base address is always 0. Instead the Finalizer generates prolog code to initialize 4 SGPRs with a V# that has the following properties, and then uses that in the buffer instructions:</p>


<ul class="doxyList ">
<li>base address of 0</li>
<li>no swizzle</li>
<li>ATC=1</li>
<li>MTYPE set to support memory coherence specified in amd_kernel_code_t.globalMemoryCoherence</li>
</ul>

<p>When the Global Buffer is used to access the Kernarg segment, must add the dispatch packet kernArgPtr to a kernarg segment address before using this V#. Alternatively scalar loads can be used if the kernarg offset is uniform, as the kernarg segment is constant for the duration of the kernel execution.</p>


<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### amd\_kernel\_code\_version\_major {#a69b3062747791cdac6a750dda916f69b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t amd_kernel_code_t::amd_kernel_code_version_major</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### amd\_kernel\_code\_version\_minor {#af8a4325bdbe341cbe35667260d0cf612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t amd_kernel_code_t::amd_kernel_code_version_minor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### amd\_machine\_kind {#a1776bdb052a121eea5af309942f9039c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t amd_kernel_code_t::amd_machine_kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### amd\_machine\_version\_major {#a83a6743132dd0569a29101b5ea75ecc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t amd_kernel_code_t::amd_machine_version_major</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### amd\_machine\_version\_minor {#a12b6fd60f05bb2b48109c695d11e4b9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t amd_kernel_code_t::amd_machine_version_minor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### amd\_machine\_version\_stepping {#ac32688254d6765473b622910e45dba0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t amd_kernel_code_t::amd_machine_version_stepping</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### call\_convention {#ab57d5ee699912ac205d90dbeefaa2407}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t amd_kernel_code_t::call_convention</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### code\_properties {#a34a391217195263371f11ba2f8219479}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t amd_kernel_code_t::code_properties</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Code properties.</p>


<p>See <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h/#ae598a8419230cf7b6ff36928295c4246">amd_code_property_mask_t</a> for a full list of properties.</p>


<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### compute\_pgm\_resource\_registers {#afe887ee8071cec14eb579fdaba4e5fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t amd_kernel_code_t::compute_pgm_resource_registers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Shader program settings for CS.</p>


<p>Contains COMPUTE_PGM_RSRC1 and COMPUTE_PGM_RSRC2 registers.</p>


<p>Definition at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### control\_directives {#ae5e524fb8cae5e05a0a1340b24f9337e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t amd_kernel_code_t::control_directives[16]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### debug\_private\_segment\_buffer\_sgpr {#af68c1702d9f26c793dd848c8765685f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t amd_kernel_code_t::debug_private_segment_buffer_sgpr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If is_debug_supported is 0 then must be 0.</p>


<p>Otherwise, this is the fixed SGPR number of the first of 4 SGPRs used to hold the scratch V# used for the entire kernel execution, or uint16_t(-1) if the registers are not used or not known.</p>


<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### debug\_wavefront\_private\_segment\_offset\_sgpr {#afa83aedabe38cdb3d6943d6cb1f6b1a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t amd_kernel_code_t::debug_wavefront_private_segment_offset_sgpr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If is_debug_supported is 0 then must be 0.</p>


<p>Otherwise, this is the fixed SGPR number used to hold the wave scratch offset for the entire kernel execution, or uint16_t(-1) if the register is not used or not known.</p>


<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### gds\_segment\_byte\_size {#a8c63fe3bc77fc8e389e09fcfefd4f693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t amd_kernel_code_t::gds_segment_byte_size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of byte of GDS required by kernel dispatch.</p>


<p>Must be 0 if not using GDS.</p>


<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### group\_segment\_alignment {#a2f1b54ed94c72f92b98e6c5a36413d0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t amd_kernel_code_t::group_segment_alignment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### kernarg\_segment\_alignment {#a701ca94d346f682b471cb0648543e23e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t amd_kernel_code_t::kernarg_segment_alignment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The maximum byte alignment of variables used by the kernel in the specified memory segment.</p>


<p>Expressed as a power of two. Must be at least HSA_POWERTWO_16.</p>


<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### kernarg\_segment\_byte\_size {#ae197ddae3e0ec48aaf7ecdfa238d385a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t amd_kernel_code_t::kernarg_segment_byte_size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The size in bytes of the kernarg segment that holds the values of the arguments to the kernel.</p>


<p>This could be used by CP to prefetch the kernarg segment pointed to by the dispatch packet.</p>


<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### kernel\_code\_entry\_byte\_offset {#a8d4f73b89b79246bd80c7e70ade9dcfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t amd_kernel_code_t::kernel_code_entry_byte_offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Byte offset (possibly negative) from start of <a href="/web-llvm/docs/api/structs/amd-kernel-code-t">amd_kernel_code_t</a> object to kernel's entry point instruction.</p>


<p>The actual code for the kernel is required to be 256 byte aligned to match hardware requirements (SQ cache line is 16). The code must be position independent code (PIC) for AMD devices to give runtime the option of copying code to discrete GPU memory or APU L2 cache. The Finalizer should endeavour to allocate all kernel machine code in contiguous memory pages so that a device pre-fetcher will tend to only pre-fetch Kernel Code objects, improving cache performance.</p>


<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### kernel\_code\_prefetch\_byte\_offset {#a8eee8a5ffadb28eca3f86b1d71abb956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t amd_kernel_code_t::kernel_code_prefetch_byte_offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Range of bytes to consider prefetching expressed as an offset and size.</p>


<p>The offset is from the start (possibly negative) of <a href="/web-llvm/docs/api/structs/amd-kernel-code-t">amd_kernel_code_t</a> object. Set both to 0 if no prefetch information is available.</p>


<p>Definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### kernel\_code\_prefetch\_byte\_size {#ae19ee952d54955cc0b116bf491fbbdb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t amd_kernel_code_t::kernel_code_prefetch_byte_size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 551 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### private\_segment\_alignment {#a3f4bdeb2251ae4637ff3aa9ba109e48e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t amd_kernel_code_t::private_segment_alignment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### reserved\_sgpr\_count {#afd4b8bd479ae906c9830cd862d35fd1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t amd_kernel_code_t::reserved_sgpr_count</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of consecutive SGPRs reserved by the client.</p>


<p>If is_debug_supported then this count includes SGPRs reserved for debugger use.</p>


<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### reserved\_sgpr\_first {#a73a7429830686ee698c07843a92a765b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t amd_kernel_code_t::reserved_sgpr_first</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If reserved_sgpr_count is 0 then must be 0.</p>


<p>Otherwise, this is the first fixed SGPR number reserved.</p>


<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### reserved\_vgpr\_count {#a6be335b99bc919616ee2e7f979e4521b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t amd_kernel_code_t::reserved_vgpr_count</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of consecutive VGPRs reserved by the client.</p>


<p>If is_debug_supported then this count includes VGPRs reserved for debugger use.</p>


<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### reserved\_vgpr\_first {#a1db63c4debd90bffd965037be2dd2419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t amd_kernel_code_t::reserved_vgpr_first</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If reserved_vgpr_count is 0 then must be 0.</p>


<p>Otherwise, this is the first fixed VGPR number reserved.</p>


<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### reserved0 {#adecf388ad5ec215ace4396e00db4a8ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t amd_kernel_code_t::reserved0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reserved. Must be 0.</p>

<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### reserved3 {#a6afa9ab97cc0d46bf10b1b8739bd7767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t amd_kernel_code_t::reserved3[12]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### runtime\_loader\_kernel\_symbol {#a2b0cf6bce1e464a818f811b4a671fd24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t amd_kernel_code_t::runtime_loader_kernel_symbol</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 647 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### wavefront\_sgpr\_count {#a8b8d4c303b7a4c5102da8dc27a45a3ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t amd_kernel_code_t::wavefront_sgpr_count</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of scalar registers used by a wavefront.</p>


<p>This includes the special SGPRs for VCC, Flat Scratch Base, Flat Scratch Size and XNACK (for GFX8 (VI)). It does not include the 16 SGPR added if a trap handler is enabled. Used to set COMPUTE_PGM_RSRC1.SGPRS.</p>


<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### wavefront\_size {#a71c743526930a3412ac30725b307bd77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t amd_kernel_code_t::wavefront_size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Wavefront size expressed as a power of two.</p>


<p>Must be a power of 2 in range 1..64 inclusive. Used to support runtime query that obtains wavefront size, which may be used by application to allocated dynamic group memory and set the dispatch work-group size.</p>


<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### workgroup\_fbarrier\_count {#af7b9ca2595bcadf009e3e8cec76039b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t amd_kernel_code_t::workgroup_fbarrier_count</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of fbarrier's used in the kernel and all functions it calls.</p>


<p>If the implementation uses group memory to allocate the fbarriers then that amount must already be included in the workgroup_group_segment_byte_size total.</p>


<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### workgroup\_group\_segment\_byte\_size {#a8a4649b6a04374eaaf4bc4ef80053264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t amd_kernel_code_t::workgroup_group_segment_byte_size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The amount of group segment memory required by a work-group in bytes.</p>


<p>This does not include any dynamically allocated group segment memory that may be added when the kernel is dispatched.</p>


<p>Definition at line 574 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### workitem\_private\_segment\_byte\_size {#ad74c415c7d3e3642886adcfd8619d11b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t amd_kernel_code_t::workitem_private_segment_byte_size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The amount of memory required for the combined private, spill and arg segments for a work-item in bytes.</p>


<p>If is_dynamic_callstack is 1 then additional space must be added to this value for the call stack.</p>


<p>Definition at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

### workitem\_vgpr\_count {#a13e3cc02a4f9ed0ad17dc6a427c8cfa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t amd_kernel_code_t::workitem_vgpr_count</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of vector registers used by each work-item.</p>


<p>Used to set COMPUTE_PGM_RSRC1.VGPRS.</p>


<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdkernelcodet-h">AMDKernelCodeT.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
