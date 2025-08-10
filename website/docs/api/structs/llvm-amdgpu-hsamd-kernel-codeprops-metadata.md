---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/amdgpu/hsamd/kernel/codeprops/metadata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Metadata` Struct

<p>In-memory representation of kernel code properties metadata. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">llvm/Support/AMDGPUMetadata.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67e9d90e4bd4b8c7eb4405e2f84e59a4">Metadata</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default constructor. <a href="#a67e9d90e4bd4b8c7eb4405e2f84e59a4">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa191a3cfcaf6ed8a15ae52c3c5910bd3">empty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaad3816b6e743d6ce8d45096bcbeac69">notEmpty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a215d3f775ca94727ede0196cb228427b">mKernargSegmentSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size in bytes of the kernarg segment memory. <a href="#a215d3f775ca94727ede0196cb228427b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cdc6b690cc0517eb2cb99b4ea116ca3">mGroupSegmentFixedSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size in bytes of the group segment memory required by a workgroup. <a href="#a2cdc6b690cc0517eb2cb99b4ea116ca3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfe1aa2787c42d7b494b674189dc4fe9">mPrivateSegmentFixedSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size in bytes of the private segment memory required by a workitem. <a href="#adfe1aa2787c42d7b494b674189dc4fe9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a478e0eac063ab6481094213820c2329f">mKernargSegmentAlign</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maximum byte alignment of variables used by the kernel in the kernarg memory segment. <a href="#a478e0eac063ab6481094213820c2329f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa47a6d270474829391f9d35134743618">mWavefrontSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wavefront size. Required. <a href="#aa47a6d270474829391f9d35134743618">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a091de9fc5c638c5c840facd7b3a9b603">mNumSGPRs</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Total number of SGPRs used by a wavefront. Optional. <a href="#a091de9fc5c638c5c840facd7b3a9b603">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0becb88098b162aabd61424bc1439f4">mNumVGPRs</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Total number of VGPRs used by a workitem. Optional. <a href="#ab0becb88098b162aabd61424bc1439f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc4b4a16150a85c11702d364bafa83c6">mMaxFlatWorkGroupSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maximum flat work-group size supported by the kernel. Optional. <a href="#afc4b4a16150a85c11702d364bafa83c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8b04326e0b718f0cacc8f207253f7ec">mIsDynamicCallStack</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the generated machine code is using a dynamically sized call stack. <a href="#ab8b04326e0b718f0cacc8f207253f7ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cb5f32d879b67485e0e0450e3fad61e">mIsXNACKEnabled</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the generated machine code is capable of supporting XNACK. <a href="#a9cb5f32d879b67485e0e0450e3fad61e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a949e7dc9e47daa4e9f15f0c0b0a7433a">mNumSpilledSGPRs</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of SGPRs spilled by a wavefront. Optional. <a href="#a949e7dc9e47daa4e9f15f0c0b0a7433a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad4ba18fc68fc19450bde321c25e0b1f">mNumSpilledVGPRs</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of VGPRs spilled by a workitem. Optional. <a href="#aad4ba18fc68fc19450bde321c25e0b1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>In-memory representation of kernel code properties metadata.</p>

<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Metadata() {#a67e9d90e4bd4b8c7eb4405e2f84e59a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::Metadata ()</td>
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

<p>Default constructor.</p>

<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### empty() {#aa191a3cfcaf6ed8a15ae52c3c5910bd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::empty ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if kernel code properties metadata is empty, false otherwise.</p></dd>
</dl>


<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Reference <a href="#aaad3816b6e743d6ce8d45096bcbeac69">notEmpty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f4d9b6842bdae57db58da7af3602f037/#a587d9bdb751367010682b1147723230c">llvm::yaml::MappingTraits&lt; Kernel::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### notEmpty() {#aaad3816b6e743d6ce8d45096bcbeac69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::notEmpty ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if kernel code properties metadata is not empty, false otherwise.</p></dd>
</dl>


<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="#aa191a3cfcaf6ed8a15ae52c3c5910bd3">empty</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### mGroupSegmentFixedSize {#a2cdc6b690cc0517eb2cb99b4ea116ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mGroupSegmentFixedSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size in bytes of the group segment memory required by a workgroup.</p>


<p>This value does not include any dynamically allocated group segment memory that may be added when the kernel is dispatched. Required.</p>


<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-11a2b6dfa7f757480b342e43e05a8606/#a78a19c05dcd370eff160c0179bbf9b52">llvm::yaml::MappingTraits&lt; Kernel::CodeProps::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mIsDynamicCallStack {#ab8b04326e0b718f0cacc8f207253f7ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mIsDynamicCallStack = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the generated machine code is using a dynamically sized call stack.</p>


<p>Optional.</p>


<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-11a2b6dfa7f757480b342e43e05a8606/#a78a19c05dcd370eff160c0179bbf9b52">llvm::yaml::MappingTraits&lt; Kernel::CodeProps::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mIsXNACKEnabled {#a9cb5f32d879b67485e0e0450e3fad61e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mIsXNACKEnabled = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the generated machine code is capable of supporting XNACK.</p>


<p>Optional.</p>


<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-11a2b6dfa7f757480b342e43e05a8606/#a78a19c05dcd370eff160c0179bbf9b52">llvm::yaml::MappingTraits&lt; Kernel::CodeProps::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mKernargSegmentAlign {#a478e0eac063ab6481094213820c2329f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mKernargSegmentAlign = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maximum byte alignment of variables used by the kernel in the kernarg memory segment.</p>


<p>Required.</p>


<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-11a2b6dfa7f757480b342e43e05a8606/#a78a19c05dcd370eff160c0179bbf9b52">llvm::yaml::MappingTraits&lt; Kernel::CodeProps::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mKernargSegmentSize {#a215d3f775ca94727ede0196cb228427b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mKernargSegmentSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size in bytes of the kernarg segment memory.</p>


<p>Kernarg segment memory holds the values of the arguments to the kernel. Required.</p>


<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-11a2b6dfa7f757480b342e43e05a8606/#a78a19c05dcd370eff160c0179bbf9b52">llvm::yaml::MappingTraits&lt; Kernel::CodeProps::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mMaxFlatWorkGroupSize {#afc4b4a16150a85c11702d364bafa83c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mMaxFlatWorkGroupSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maximum flat work-group size supported by the kernel. Optional.</p>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-11a2b6dfa7f757480b342e43e05a8606/#a78a19c05dcd370eff160c0179bbf9b52">llvm::yaml::MappingTraits&lt; Kernel::CodeProps::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mNumSGPRs {#a091de9fc5c638c5c840facd7b3a9b603}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mNumSGPRs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Total number of SGPRs used by a wavefront. Optional.</p>

<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-11a2b6dfa7f757480b342e43e05a8606/#a78a19c05dcd370eff160c0179bbf9b52">llvm::yaml::MappingTraits&lt; Kernel::CodeProps::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mNumSpilledSGPRs {#a949e7dc9e47daa4e9f15f0c0b0a7433a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mNumSpilledSGPRs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of SGPRs spilled by a wavefront. Optional.</p>

<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-11a2b6dfa7f757480b342e43e05a8606/#a78a19c05dcd370eff160c0179bbf9b52">llvm::yaml::MappingTraits&lt; Kernel::CodeProps::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mNumSpilledVGPRs {#aad4ba18fc68fc19450bde321c25e0b1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mNumSpilledVGPRs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of VGPRs spilled by a workitem. Optional.</p>

<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-11a2b6dfa7f757480b342e43e05a8606/#a78a19c05dcd370eff160c0179bbf9b52">llvm::yaml::MappingTraits&lt; Kernel::CodeProps::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mNumVGPRs {#ab0becb88098b162aabd61424bc1439f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mNumVGPRs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Total number of VGPRs used by a workitem. Optional.</p>

<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-11a2b6dfa7f757480b342e43e05a8606/#a78a19c05dcd370eff160c0179bbf9b52">llvm::yaml::MappingTraits&lt; Kernel::CodeProps::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mPrivateSegmentFixedSize {#adfe1aa2787c42d7b494b674189dc4fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mPrivateSegmentFixedSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size in bytes of the private segment memory required by a workitem.</p>


<p>Private segment memory includes arg, spill and private segments. Required.</p>


<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-11a2b6dfa7f757480b342e43e05a8606/#a78a19c05dcd370eff160c0179bbf9b52">llvm::yaml::MappingTraits&lt; Kernel::CodeProps::Metadata &gt;::mapping</a>.</p>

</div>
</div>

### mWavefrontSize {#aa47a6d270474829391f9d35134743618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPU::HSAMD::Kernel::CodeProps::Metadata::mWavefrontSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Wavefront size. Required.</p>

<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-11a2b6dfa7f757480b342e43e05a8606/#a78a19c05dcd370eff160c0179bbf9b52">llvm::yaml::MappingTraits&lt; Kernel::CodeProps::Metadata &gt;::mapping</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
